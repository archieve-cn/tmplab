# 试验Git操作

标签（空格分隔）： 未分类

---

## 操作记录(部分中间步骤已忽略)

----------
2015-09-10 21

 1. PC-浏览器：打开github
 2. PC-浏览器：创建repository“tmplab”，顺便添加适配VisualStudio的“.gitignore”和README.md
 3. PC-资源管理器：打开目录“E:\code\VS\mfc”
 4. PC-Visual Studio：创建MFC工程MFCApplication1，F7生成可执行文件
 5. PC-资源管理器：在目录“E:\code\VS\mfc”中打开CMD
 6. PC-CMD：将github上的文件拖到本地 [git clone https://github.com/cmheia/tmplab.git]
 7. PC-资源管理器：进入上一步骤得到的新目录“E:\code\VS\mfc\tmplab”
 8. PC-资源管理器：将目录内所有文件、文件夹剪切，粘贴到目录“E:\code\VS\mfc\MFCApplication1”内
 9. PC-CMD：把.cpp、.h等文件添加到本地index [git add *]
 11. PC-CMD：更新本地repository [git commit -m "添加基本工程"]
 12. PC-CMD：把本地repository推送到github [git push origin master] 中途会被要求输入github的用户名和密码，密码无回显
 13. PC-npp：把上面这些字粘贴到“E:\code\VS\mfc\MFCApplication1\README.md”并保存
 14. PC-CMD：更新本地repository [git add .]，[git commit -m "初尝markdown"]
 15. PC-CMD：把本地repository推送到github [git push origin master]

