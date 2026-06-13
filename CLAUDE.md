# 个人简历网站

## 更新简历

1. 编辑 `index.html`
2. 保存后执行：
```bash
cd ~/Desktop/个人网站
git add index.html
git commit -m "更新简历内容"
git push
```
3. 等 1-2 分钟，GitHub Pages 自动更新

## 如果改了照片

```bash
git add avatar.jpg index.html
git commit -m "更新照片"
git push
```

## 文件说明

- `index.html` — 简历页面（唯一需要部署的 HTML）
- `avatar.jpg` — 个人照片
- `workstation.html` — 编辑备份，不上传（已在 .gitignore）

## 在线地址

https://ming-baba.github.io/Personal-Resume-WEB/

## 注意

- 不要改名 `index.html`，GitHub Pages 默认找这个名字
- commit 信息随意写，只是给自己看的
