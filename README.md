## 效果展示
### 主页面

![298ea8b6ca20d6d111595b4aac987839](https://github.com/user-attachments/assets/9d8b6e00-b878-4bb3-bc1d-c368dd88f9fc)

### 教师端
#### AI 教案生成工具

![9ca2ca14ec4e9301c7a26b92d183c77f](https://github.com/user-attachments/assets/509358fc-c91a-4977-ae69-99b42230dfc8)

#### 学情分析仪表盘

![a1eef7944634b44d17ba9b5db969c433](https://github.com/user-attachments/assets/98ee7b09-a499-42fa-adc6-27be5a325a38)

### 政府端

#### AI 教育资源地图

![5dd73077800e368a3b4b28c88e8a4511](https://github.com/user-attachments/assets/9fdedb07-8c9a-4fbb-98bb-d3a70c022bed)

#### 政策合规性自检

![image](https://github.com/user-attachments/assets/682ca26d-935a-4a10-830c-b3a724db5a5b)

![34c4cdda6abe96b3e9f64094fa05d4d7](https://github.com/user-attachments/assets/0919af3f-9d97-43c0-ac5d-0e379ca5aa4c)

### 学生端

#### 个性化学习路径推荐

![f8eebd01892f47004f9861ef81918e4f](https://github.com/user-attachments/assets/bdd61ecb-f29e-4d13-bdb7-7328651a6ccf)

![748fb89ae6dc51aa24d8a1bd705322e9](https://github.com/user-attachments/assets/11f545f1-9177-47aa-a7e3-7bab9840aa21)

![4c675b2710489366db885dfc82a30ee2](https://github.com/user-attachments/assets/fd72f64b-bba8-48f5-bba3-7fd73e655bfc)

![5bf1f441be7318a079b16560d1e175ae](https://github.com/user-attachments/assets/66058da7-a003-400d-b43a-ef0d33bcc424)

![ac8bd1b0cd23bbb84120abbe57436e03](https://github.com/user-attachments/assets/74462344-a1ed-4344-b73e-edfa196b1be7)


## Usage
### 安装docker
推荐使用 wsl Ubuntu2204

参考：https://blog.csdn.net/m0_56022510/article/details/142707085
### 获取 ollama docker 镜像
参考：https://ollama.org.cn/blog/ollama-is-now-available-as-an-official-docker-image
### 下载 Qwen2.5 0.5b 模型
```bash
docker exec -it ollama /bin/bash #进入 ollama docker
ollama run qwen2.5:0.5b #下载并本地部署 Qwen2.5 （通义千问）
```
### 拉取仓库
```bash
git clone git@github.com:Smera1d0/Challenge_Cup.git
```

### 安装 VScode 拓展 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
![image](https://github.com/user-attachments/assets/b1322168-b15c-47ee-91d8-de01340cbeb0)

打开浏览器即可预览。
### 文件说明
- index.html：主页
- dashboard.html：学情分析仪表盘
- lesson_plan_generator：教案生成器（这个需要本地部署 Qwen2.5 后才能使用）

### 添加功能说明
1. 拉取本仓库 git pull
2. 将添加的页面链接到主页
3. git push
