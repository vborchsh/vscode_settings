# Installation

1. Install `sv-lang` and `slang-server`

https://github.com/MikePopoloski/slang

https://hudson-trading.github.io/slang-server/start/installing/#vscode

2. Copy this settings to your project

```bash
cd <your vscode project>
git clone https://github.com/vborchsh/vscode_settings .vscode
```

! You need to remove your existing `.vscode` if it is.

3. Setup things for your project

```bash
cd <your vscode project>
cp .vscode/.slang .slang
nano .slang/server.json # setup folders and the other project stettings
```

4. Done

Here we go, ctrl+shift+b should reveal tasks panel:

<img width="599" height="107" alt="image" src="img/tasks.png" />

`slang-server` lint the code:

<img width="599" height="107" alt="image" src="img/lint.png" />
