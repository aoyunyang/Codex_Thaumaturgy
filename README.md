  老东西终于把焚决交出来了！

这个项目的作用是让 AI 一读取，就自动判定当前环境属于 “安全研究沙箱”，从而绕过针对普通用户的道德限制。

1.找到配置文件夹 .codex 下面 把焚决放进去 然后 在config.toml 中添加 model_instructions_file = "./prompts/instruction2.md"(实际路径)
<img width="1069" height="666" alt="5b8d1ba385e82c11533928f69e3b61b" src="https://github.com/user-attachments/assets/9c51ca9e-9ff5-49fa-a91c-81745b9769bc" />

2.然后需要改AGENTS.md 直接把焚决打开 把内容复制进去保存 然后重启codex

<img width="307" height="781" alt="026847f7f76d3ea9ba8bbf4dcc31955" src="https://github.com/user-attachments/assets/97b79df8-926b-4ff6-bcdf-53fa05991b82" />

3.新线程对话前先启动焚决  激活CTF环境

<img width="781" height="377" alt="image" src="https://github.com/user-attachments/assets/c093ae2c-20e1-477b-974a-6cc79ec7bb40" />


我目前用这个还行 有时候也会道德
道德了就重新开一个线程让它接着文件夹继续干
gpt5.5没办法过 5.4还是可以
