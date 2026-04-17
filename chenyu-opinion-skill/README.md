# chenyu-opinion

基于[辰语](https://chenyuweb.com/)网站观点文章的 Kiro CLI skill，输出有深度的中文社会观点分析。

## 安装

```bash
npx skills add YOUR_GITHUB_USERNAME/chenyu-opinion-skill
```

## 使用

```
/chenyu-opinion 如何看待性别议题
```

## 涵盖议题

- 社会与民生
- 经济与制度
- 权力与司法
- AI与科技
- 性别与婚姻
- 教育与个体

## 发布到 GitHub

```bash
cd ~/chenyu-opinion-skill
git init
git add .
git commit -m "init chenyu-opinion skill"
gh repo create chenyu-opinion-skill --public --push
```
