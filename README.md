<div align=center>

# [uptime-kuma](https://github.com/louislam/uptime-kuma)
</div>

**[Node.js](https://replit.com)**

```bash
git clone https://github.com/gopcn/uptime-kuma.git &&
shopt -s dotglob &&
mv -b uptime-kuma/* ./ &&
rm -rf *~ uptime-kuma .git .github index.js README.md &&
echo "部署成功，点击Run使用。"
```

**🆙 How to Update**
```bash
# 进入项目目录并拉取代码
cd uptime-kuma
git fetch --all
git checkout 1.23.6 --force

# 安装依赖、下载分发文件并重启应用
npm ci --production
npm run download-dist
pm2 restart uptime-kuma
```