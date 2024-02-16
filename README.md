git init

# 创建README.md文件并输入内容"# ChatBot"
echo "# ChatBot" >> README.md
# 将README.md文件添加至暂存区
git add README.md
# 提交暂存区的更改
git commit -m "First commit"

git remote add origin <repository-url>

# 切换至主分支
git branch -M main
# 将本地主分支的内容推送到远程仓库
git push -u origin main
