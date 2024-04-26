# 网络设置


```plaintext
git config --global https.proxy 'http://'
```

```plaintext
git config --global http.proxy 'http://'
```

# Email 账户

查询当前的 Git 邮箱地址
打开命令行工具（在 Windows 上可能是 CMD 或 PowerShell，在 macOS 或 Linux 上是 Terminal）。
转到你的 Git 项目目录下。
输入以下命令查看全局配置的邮箱地址（这是默认使用的邮箱地址）：

```plaintext
git config --global user.email
```
如果你只想查看当前项目的邮箱配置（如果有的话），可以使用：
```plaintext
git config user.email
```
更改 Git 邮箱地址
如果你想要更改你的邮箱地址，可以按照以下步骤：

全局更改邮箱（影响所有项目）
如果你想要更改所有 Git 项目的默认邮箱地址，可以使用以下命令：
```plaintext
git config --global user.email "user.email"
```

```plaintext
git config user.email "user.email"
```

