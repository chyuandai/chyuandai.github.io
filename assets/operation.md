# 1. 初始化仓库（如果之前没成功的话）
git init

# 2. 关联你的 GitHub 仓库
git remote add origin https://github.com/chyuandai/chyuandai.github.io.git

# 3. 将所有文件添加到暂存区
git add .

# 4. 提交更改并添加备注
git commit -m "update my personal page"

# 5. 确保当前分支名为 main
git branch -M main

# 6. 推送代码到 GitHub
git push -u origin main