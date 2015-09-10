# 试验Git操作

标签（空格分隔）： 未分类

---

## 操作小结(部分中间步骤已省略)

----------
2015-09-10 21.-22.

 1. PC-浏览器：打开 github
 2. PC-浏览器：创建 repository `tmplab`，顺便添加适配 `VisualStudio`  的`.gitignore` 和 `README.md`
 3. PC-资源管理器：打开目 录`E:\code\VS\mfc`
 4. PC-Visual Studio：创建MFC工程 `MFCApplication1`，F7生成可执行文件
 5. PC-资源管理器：在目录 `E:\code\VS\mfc` 中打开CMD
 6. PC-CMD：将 github 上的文件拖到本地 `git clone https://github.com/cmheia/tmplab.git`
 7. PC-CMD：切换工作目录到 `E:\code\VS\mfc\MFCApplication1`  `cd MFCApplication1`
 8. PC-资源管理器：进入上一步骤得到的新目录 `E:\code\VS\mfc\tmplab`
 9. PC-资源管理器：将目录内所有文件、文件夹剪切，粘贴到目录`E:\code\VS\mfc\MFCApplication1`内
 10. PC-CMD：把.cpp、.h等文件添加到本地index `git add *`
 11. PC-CMD：更新本地 repository `git commit -m "添加基本工程"`
 12. PC-CMD：把本地 repository 推送到 github `git push origin master`（中途会被要求输入 github 的用户名和密码，密码无回显，后同）
 13. PC-浏览器：使用 [Cmd Markdown](https://www.zybuluo.com/mdeditor) 编辑这些文字
 14. PC-npp：把这些文字粘贴到 `E:\code\VS\mfc\MFCApplication1\README.md` 并保存
 15. PC-CMD：更新本地 repository 先 `git add .`，再 `git commit -m "初尝markdown"`
 16. PC-CMD：把本地 repository 推送到github `git push origin master`

----------
小结 2015-09-10 22：

 - 修改本地 repository 的文件后，需要 先`git add .`把改动放进暂存区“index”，才能执行`git commit -m "这是说明"`提交到仓库，否则不能更新仓库：`Changes not staged for commit`
 - markdown （的编辑器）一点也不好用。



