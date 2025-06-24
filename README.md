本项目旨在构建一个本地智能舆情分析系统，通过自然语言处理与多工具协作，实现用户查询意图的自动理解、新闻检索、情绪分析、结构化输出与邮件推送。
![image](https://github.com/user-attachments/assets/0e7bed53-5321-4b9f-bbbe-9ac28ccc45a5)
python版本大于等于3.10就行 \n
安装环境：pip install uv  \n
通过cd命令进入你要创建项目的空间，然后输入：uv init mcp-project 即可创建出一个空的MCP项目
在创建了这个空的MCP项目之后，需要创建两个Python文件，分别是client.py和server.py。
client.py是客户端，用户与客户端进行交互。
server.py是服务端，其中包含了多种工具函数，客户端会对其中的工具函数进行调用。
其余操作以及需要配的密钥都在文件夹里的README.md文件中自己看。
代码解读在py文件里面，如何搭建的可以对应的去看
