# 介绍

构建 deepin 系统镜像。脚本内容只针对 deepin 系统进行构建，如果需要定制内容请自行修改，如果需要完整系统体验，请访问官网：https://www.deepin.org/zh/download/

# 构建 ISO

## amd64

```bash
# 设置系统为中文，默认为 en_US.UTF-8
export LOCALES=zh_CN.UTF-8
./build amd64
```

## arm64

```bash
# 设置系统为中文，默认为 en_US.UTF-8
export LOCALES=zh_CN.UTF-8
./build arm64
```

## loongarch64

```bash
# 设置系统为中文，默认为 en_US.UTF-8
export LOCALES=zh_CN.UTF-8
./build loongarch64
```

live user 用户密码为 live
