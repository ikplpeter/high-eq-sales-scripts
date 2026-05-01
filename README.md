# high-eq-sales-scripts
high-eq-sales-scripts高情商营销话术

---

## 三、上传文件的两种方式
### 方式1：网页直接拖传（最简单）
1.  打开你刚建的 `high-eq-sales-scripts` 仓库页面
2.  把你整理好的 `skill.json`、`system.md`、`README.md` 三个文件，直接拖进浏览器页面里
3.  点「Commit changes」，就上传完成了

### 方式2：本地Git上传（适合后续更新）
如果你想后续自己提交更新，可以用这个方式：
```bash
# 1. 进入你的技能文件夹
cd C:\Users\你的用户名\Desktop\gaoqingshang_sale

# 2. 初始化Git
git init
git add .
git commit -m "Initial commit: HighEQ Sales Scripts v1.0.0"

# 3. 关联远程仓库（替换成你自己的仓库地址）
git remote add origin https://github.com/你的GitHub用户名/high-eq-sales-scripts.git

# 4. 推送到GitHub
git push -u origin master
