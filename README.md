# baka page 部署测试

自动部署静态网站到 GitHub Pages。

## 使用方法

```yaml
- name: Deploy
  uses: your-org/auto-deploy-action@v1
  with:
    token: ${{ secrets.GITHUB_TOKEN }}
