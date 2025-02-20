# Usage
## 安装docker
推荐使用 wsl Ubuntu2204

参考：https://blog.csdn.net/m0_56022510/article/details/142707085
## 获取 ollama docker 镜像
参考：https://ollama.org.cn/blog/ollama-is-now-available-as-an-official-docker-image
## 下载 Qwen2.5 0.5b 模型
```bash
docker exec -it ollama /bin/bash #进入 ollama docker
ollama run qwen2.5:0.5b #下载并本地部署 Qwen2.5 （通义千问）
```
## 拉取仓库
```bash
git clone git@github.com:Smera1d0/Challenge_Cup.git
```

## 安装 VScode 拓展 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
![image](https://github.com/user-attachments/assets/b1322168-b15c-47ee-91d8-de01340cbeb0)

打开浏览器即可预览。
## 文件说明
- index.html：主页
- dashboard.html：学情分析仪表盘
- lesson_plan_generator：教案生成器（这个需要本地部署 Qwen2.5 后才能使用）

## 添加功能说明
1. 拉取本仓库 git pull
2. 将添加的页面链接到主页
3. git push
