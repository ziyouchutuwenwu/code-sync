# README

## 步骤

复制相关的 json

```sh
~/.config/XXX/User/settings.json
~/.config/XXX/User/keybindings.json
```

插件

```sh
# 备份
code --list-extensions > extensions.txt

# 安装
cat extensions.txt | xargs -L 1 code --install-extension

# 卸载所有
code --list-extensions | xargs -r -L 1 code --uninstall-extension
```

中文

```sh
Configure Display Language
```
