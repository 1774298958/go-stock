运行
wails dev
#为当前系统构建

wails build

#为 Windows 64位构建

wails build -platform windows/amd64

#为 macOS Intel 和 Apple Silicon 构建通用二进制

wails build -platform darwin/universal

#一次构建多个平台（Windows 64位、Linux 64位）

wails build -platform "windows/amd64,linux/amd64"