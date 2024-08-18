# files

```
https://github.com/git-lfs/git-lfs/releases
./install.sh
cd files
git lfs install
git add .gitattributes
git lfs track "*.rmvb"
git lfs track "*.mp4"
```

```
ffmpeg -i ~/Downloads/BigBuckBunny.mp4 -ss 00:00:30 -t 03:00:05 -c:v libx264 -crf 23 -preset medium -c:a aac -b:a 128k /Volumes/Mydisk_800/files/01.mp4
ffmpeg -i ~/Downloads/BigBuckBunny.mp4 -ss 00:00:30 -t 03:00:05 -c:v libx264 -b:v 1000k -c:a aac -b:a 128k /Volumes/Mydisk_800/files/02.mp4
```

```
https://raw.githubusercontent.com/用户名/仓库名/分支名/路径/文件名.mp4

https://raw.githubusercontent.com/qzw881130/files/main/02.mp4
```

```
git checkout -b gh-pages
git add your-video.mp4
git commit -m "Add video"
git push origin gh-pages
步骤 2: 启用 GitHub Pages

	1.	访问 GitHub 仓库的设置页面：
	•	在 GitHub 上，导航到你的仓库页面。
	•	点击页面上方的 “Settings” 标签。
	2.	找到 GitHub Pages 设置部分：
	•	在设置页面中，找到 “Pages” 部分（可能在侧边栏中或在页面的中间部分）。
	3.	选择 gh-pages 分支作为 GitHub Pages 来源：
	•	在 “Source” 部分，选择 gh-pages 分支作为 GitHub Pages 的来源。
	•	如果存在 “/root” 或 “/docs” 目录的选择，通常选择 /root 即可。
	4.	保存更改：
	•	点击 “Save” 按钮来保存你的设置。

步骤 3: 获取和使用链接

	1.	访问 GitHub Pages 网站：
	•	GitHub Pages 将使用你的 GitHub 用户名和仓库名生成一个 URL。
	•	通常，URL 的格式为 https://<username>.github.io/<repository>/。
	2.	访问你的文件：
	•	如果你的文件在 gh-pages 分支的根目录，你可以通过 https://<username>.github.io/<repository>/your-video.mp4 访问它。
	•	确保文件路径正确，视频应该可以通过浏览器直接播放。

https://qzw881130.github.io/files/

https://qzw881130.github.io/files/02.mp4
https://qzw881130.github.io/files/sd1722935871_2.MP4

```
