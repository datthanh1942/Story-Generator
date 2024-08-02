# Story-Generator
## Code được thiết kế và chạy trên google colab nên em xin phép chia ra 2 cách để chạy code
### Chạy trên google colab
- Chỉ cần chạy hết tất cả các cells để hiển thị ứng dụng
- Có thể truy cập đường link được cung cấp để mở ứng dụng trên website
- Điền các từ khóa tương ứng để sinh ra truyện theo ý muốn

### Chạy ngoài google colab
- Cài đặt các thư viện cần thiết
``` pip install openai==0.28 gradio diffusers invisible_watermark transformers accelerate safetensors ```
- Chạy code ở trong cell thứ 2 để mở ra ứng dụng tương tự như chạy trên google colab

**Lưu ý: Môi trường cần có CUDA, để có thể chạy trên GPU nhằm hỗ trợ xử lý tác vụ có trong mô hình**
