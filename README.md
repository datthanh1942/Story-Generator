# Story-Generator
Utilize the GPT-3.5 API to generate stories based on user-selected features. Next, employ the Stable Diffusion API to create images from detailed prompts processed via the superprompt API. Finally, present all of this content within Gradio Apps. Additionally, it’s possible to explore story excerpts using the output link

### The code is designed and executed on Google Colab, so I will outline two methods to run the code:
#### Running on Google Colab
- Run all the cells to display the application.
- You can access the provided link to open the application on the website.
- Enter the corresponding keywords to generate stories as desired.

#### Running outside Google Colab
- Install the necessary libraries:
``` pip install openai==0.28 gradio diffusers invisible_watermark transformers accelerate safetensors ```
- Run the code in the second cell to open the application, similar to running it on Google Colab.

**Note: The environment needs to have CUDA to run on GPU, which supports the tasks in the model.
