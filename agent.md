# 如何获取简单便宜开源的本地agent
## wsl 配置
win->搜索启用或关闭windows功能
<img width="688" height="635" alt="image" src="https://github.com/user-attachments/assets/a590c48b-ca28-4c06-9c84-b6c59c1381d1" />
适用于linux的windows子系统和虚拟机平台
<img width="688" height="635" alt="image" src="https://github.com/user-attachments/assets/4e2ee12b-ebfd-4ff1-8248-3c1818068da6" />
Microsoft Store搜索ubantu/debian
<img width="2559" height="1468" alt="image" src="https://github.com/user-attachments/assets/1bac1084-8696-4c54-b27e-c7fb4974a763" />
下载Linux内核更新包 wsl.exe --update / wsl.exe --install <br>
验证 win+r -> wt 打开powershell终端，输入wsl <br>
## 开源agent
### Hermes agent
cloud code 源码泄露后从其源码使用python逆向而来，github开源项目，易获取 <br>
GitHub地址：https://github.com/NousResearch/hermes-agent
<img width="1939" height="1099" alt="image" src="https://github.com/user-attachments/assets/9edb3929-0a2c-4d41-a842-b646bda33cf7" />

版本：
<img width="1946" height="1090" alt="image" src="https://github.com/user-attachments/assets/7d9cb03a-aefe-45e2-b3c5-38495b523c41" />

安装后配置api和模型
快速入门指南：https://hermes-agent.nousresearch.com/docs/getting-started/quickstart
<img width="1948" height="1076" alt="image" src="https://github.com/user-attachments/assets/fe560c20-81ad-43d8-ac6f-a14d17bfe9a8" />

## API配置
国产模型中deepseek的长文本处理较好，但是图像处理不好，glm综合能力还不错都推荐
### deepseek
deepseek官网：https://platform.deepseek.com/
在这里购买deepseekapi并配置到agent上
### 智谱旗下GLM
智谱官网：https://www.zhipuai.cn/zh
在这里购买api并配置到agent上
# agent辅助仿真（以codex为例）
- 开始前请创建一个文件夹给agent作为工作文件夹
<img width="1899" height="1248" alt="image" src="https://github.com/user-attachments/assets/22a6c3c8-bb3a-4739-895d-b1915662af91" />

- 把你需要的软件绝对路径输入给ai，并说清楚你的需求
<img width="1892" height="1262" alt="image" src="https://github.com/user-attachments/assets/4ed5f893-fb3e-4b88-aac6-0e04e6739354" />

- 开始享受你的agent辅助工作流
## ansys 
建议把maxwell的帮助文档和脚本帮助文档喂给ai，并另外配置一个python到本地
ansys自带的python不大稳定
<img width="1937" height="441" alt="image" src="https://github.com/user-attachments/assets/2f68fee6-692e-4d27-9961-ab6a68595e9d" />

## matlab
matlab有官方的mcp和skill包，matlab的工具包中的文档说把代码仓库丢给ai后他能自己配置mcp服务器，把地址丢给ai即可 <br>
matlab的官方软件仓库地址：https://github.com/matlab <br>
matlab的agent工具包和mcp地址： <br> 
mcp地址：https://github.com/matlab/matlab-mcp-core-server <br>
适用于matlab的agent工具包matlab-agentic-toolkit：https://github.com/matlab/matlab-agentic-toolkit <br>
适用于simulink的agent工具包simulink-agentic-toolkit：https://github.com/matlab/simulink-agentic-toolkit <br>
