# Story-Generator
I successfully utilized the GPT-3.5 API engine to develop a chatbot capable of providing stories based on requested content, along with a feature to generate images from the stories using Diffusion, presented on the Gradio platform

### The code is designed and executed on Google Colab, so I will outline two methods to run the code:
#### Running on Google Colab
- Run all the cells to display the application.
- You can access the provided link to open the application on the website.
- Enter the corresponding keywords to generate stories as desired.

#### Chạy ngoài google colab
- Install the necessary libraries:
``` pip install openai==0.28 gradio diffusers invisible_watermark transformers accelerate safetensors ```
- Run the code in the second cell to open the application, similar to running it on Google Colab.

**Note: The environment needs to have CUDA to run on GPU, which supports the tasks in the model.
