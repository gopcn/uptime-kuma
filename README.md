<div align=center>

# [uptime-kuma](https://github.com/louislam/uptime-kuma)
</div>

**[Node.js](https://replit.com)**

```bash
git clone https://github.com/gopcn/uptime-replit.git &&
shopt -s dotglob &&
mv -b uptime-replit/* ./ &&
rm -rf *~ uptime-replit .git .github index.js README.md &&
echo "部署成功，点击Run使用。"
```

**🆙 How to Update**
```bash
# 进入项目目录并拉取代码
cd uptime-kuma
git fetch --all
git checkout 1.22.1 --force

# 安装依赖、下载分发文件并重启应用
npm ci --production
npm run download-dist
pm2 restart uptime-kuma
```