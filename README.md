# 使用 cvtek 将 toml 文件生成简历

## 安装 cvtek

### 使用原版 cvtek

```bash
cargo install --git https://github.com/varbhat/cvtek
```

### 使用修改的 cvtek

```bash
cargo install --git https://github.com/J1nH4ng/cvtek
```

主要的修改内容：
1. 添加了中文模板
2. 修改了排版内容，使得符合国内的招聘需求

## 使用方法

```bash
# 生成模板
cvtek -t resume.toml

# 修改模板

# 生成 tex 文件
cvtek -f ./resume.toml -t resume.tex

# 使用在线工具转换为 resume.pdf
```
