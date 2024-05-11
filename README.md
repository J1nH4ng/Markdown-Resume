# 使用 cvtek 将 toml 文件生成简历

> 感谢原作者的贡献：[https://github.com/varbhat/cvtek](https://github.com/varbhat/cvtek)

## 安装 cvtek

### 安装原版 cvtek

```bash
cargo install --git https://github.com/varbhat/cvtek
```

### 安装修改的 cvtek

```bash
cargo install --git https://github.com/J1nH4ng/cvtek
```

主要的修改内容：
1. 添加了中文模板
2. 修改了排版内容，使得符合国内的招聘需求

## 使用方法

### 原版 cvtek 的使用方法

```bash
# 生成模板
cvtek -t resume.toml

# 修改模板

# 生成 tex 文件
cvtek -f ./resume.toml -t resume.tex

# 使用在线工具转换为 resume.pdf
```

### 修改版的 cvtek 的使用方法（推荐国内用户使用）

```bash
cvtek -t resume.toml

# 修改模板

# 生成 tex 文件
cvtek -f ./resume.toml -t resume-cn.tex
```

## TODO LIST

- [ ] 完善中文模板
- [ ] 完善生成文件为中文文档
- [ ] 完善 README 文档
