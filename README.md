# Installing-Llama-3.2-1b-on-Android-phone
参考思路：https://www.bilibili.com/video/BV1NA9uY3E7t/?share_source=copy_web&vd_source=98bf8ad58c47848e3afb8120e723103a
项目地址：https://github.com/sunshine0523/OllamaServer
Ollama Server功能：调用安卓可用的Ollama二进制文件，无需Termux，一键启用Ollama服务。并可以在可视界面下，下载模型，加载自定义模型，并与模型对话。
使用方法：见Bilibili原视频
![image](https://github.com/user-attachments/assets/4c472570-faf7-4617-a5a5-7b588d4679d9)
模型性能测试与内存占用：
问题1（写代码）：开始生成17s，停止生成70s
![5b47e9e4fc9573d5bd97bd5c747f471](https://github.com/user-attachments/assets/03eefea5-524b-49e6-ae38-024073603ab3)
问题1（写代码）：开始生成2s，停止生成17s（chatgpt版）
![image](https://github.com/user-attachments/assets/c60fc47d-92a1-4621-a441-9a3c03af75b9)
问题2（简单逻辑问题）：开始生成17s，停止生成70s
![92854cf5dcfab1953d33c57723ce73b](https://github.com/user-attachments/assets/30e4a245-8594-4815-955d-a27c315f43ce)
问题2（简单逻辑问题）：开始生成3s，停止生成17s（chatgpt版）
![image](https://github.com/user-attachments/assets/63ebb1e6-93d2-4db4-aee7-ae8b9ebf69c6)
问题3（简单数学问题）：开始生成26s，停止生成300s 【手动停止，毫无逻辑且陷入循环】
![0184b2c83f7023424cf52e8ac8356d6](https://github.com/user-attachments/assets/352833af-3fb1-4b55-bc9b-f206ec7c50a8)
问题3（简单数学问题）：开始生成2s，停止生成30s（chatgpt版）
![image](https://github.com/user-attachments/assets/ed22cca3-7e8f-4fbd-b07d-71b999f8271b)
