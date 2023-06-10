# chatGPT-maya

这是一个工具，它会在OpenAI的ChatGPT生成代码并生成后将其执行到Maya中。

不幸的是，复杂的请求无法使用，但简单的自动化任务可以，尤其是如果您按照逻辑方式进行沟通并拆分步骤。

要测试并使用它：

- 您需要导航到Program Files\Autodesk\Maya20**\bin目录，

- 在此目录中，您需要打开cmd终端并运行“mayapy -m pip install openai”将openai python包安装到Maya中（重要的是您的cmd终端路径指向Program Files\Autodesk\Maya20**\bin路径）。

- 您需要从 https://platform.openai.com/account/api-keys 获取API密钥

- 转到我的github帐户并将代码复制到Maya脚本编辑器中，
  https://github.com/LouisRossouw/chatGPT-maya/blob/master/ChatGPT_Maya.py

- 将您的API密钥添加到名为“OPENAI_API_KEY”的环境变量中，或者在第44行中替换API = os.getenv（“OPENAI_API_KEY”）的内容为从openai获取的新API密钥（不建议这样做，您的API密钥应该保密）。

https://user-images.githubusercontent.com/80905013/208193188-537dc08e-5482-4b8d-bf3f-7f66b3d34759.mp4
