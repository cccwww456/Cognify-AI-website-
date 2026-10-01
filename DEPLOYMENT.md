# 怎么上线和更新 / Publishing and updating

## 中文

这个包已经把两个网站接好了。最外层的 index.html 会进入介绍网站；“介绍网站”和“产品网站”文件夹分别保存两张独立网页。

1. 解压后，把里面的文件和文件夹上传到仓库根目录，不要只上传 ZIP，也不要多套一层文件夹。
2. 在 GitHub 仓库打开 Settings → Pages，选择 Deploy from a branch、main 和 / (root)，保存。
3. 等 Actions 里的 pages build and deployment 成功，再使用 Pages 页面给出的地址。README 顶部已经放了两个网站的完整链接。
4. 上线后亲自点一次介绍网站、产品网站和“开始对话”，确认跳转正常。

如果你之前已经上传旧包：删除旧的 app 文件夹和旧版 SHA256.json、PACKAGE-CHECK.json，再上传这个包中的同名文件及两个中文文件夹。根目录 index.html 要覆盖成新版。不会操作删除时，也可以先保留旧 app，但新入口只使用“产品网站”。旧数据请先从旧产品导出备份。

以后改介绍页，就更新“介绍网站/index.html”；改产品，就更新“产品网站/index.html”。不要随意改文件夹名称，否则要一起改链接。换仓库名或用户名时，也要更新两份 README 顶部的网址。

当前默认是体验模式，真实模型需要用户自行接入 API。发布静态网页不会自动增加账号、云同步或公共模型服务。

## English

The root index.html opens the introduction. The 介绍网站 and 产品网站 folders contain the two independent websites.

1. Upload the extracted contents to the repository root, including both folders. Do not upload only the ZIP or an extra enclosing folder.
2. Under Settings → Pages, select Deploy from a branch, main, and / (root), then save.
3. Wait for pages build and deployment to succeed in Actions. Use the URL shown by Pages. Both README files already contain the two website links.
4. Test both entry points and the introduction's conversation button after publication.

When replacing the older package, remove the old app folder and outdated SHA256.json and PACKAGE-CHECK.json, then upload the new files and Chinese-named folders. Replace the root index.html. The old app folder can remain temporarily, but new links use 产品网站. Back up records from the old product before migrating.

Update 介绍网站/index.html for the introduction and 产品网站/index.html for the product. Keep folder names unchanged unless you also update links. Update README URLs if the GitHub username or repository changes.

Static hosting does not add authentication, cloud sync, or a shared AI backend. Real model use still requires the user's API configuration.
