njuxc.github.io
===============

何欣程个人主页 —— 访问地址:https://njuxc.github.io

发布方法(二选一):

A. 网页上传(约2分钟,推荐)
1. 登录 GitHub,右上角 + 号 → New repository
2. Repository name 填:njuxc.github.io(必须完全一致),Public,不要勾选 README,点 Create
3. 在新仓库页面点 "uploading an existing file",把本目录的 index.html 拖进去
4. 点 Commit changes
5. 稍等 1-2 分钟,访问 https://njuxc.github.io 即可
   (若未生效:仓库 Settings → Pages → Source 选 "Deploy from a branch",Branch 选 main /root,保存)

B. 命令行
  git init -b main
  git add .
  git commit -m "personal homepage"
  git remote add origin https://github.com/njuxc/njuxc.github.io.git
  git push -u origin main
