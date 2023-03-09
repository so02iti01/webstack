# 说明
一个使用 hugo 主题 [webstack-hugo](https://github.com/iplaycode/webstack-hugo) 的网址导航
# 其它信息
- 网址信息通过  `data/webstack.yml` 修改，格式是
```
---
- taxonomy: 灵感采集  # 分类名
  icon: linecons-lightbulb # 分类标题的图标
  list: 
    - term: 发现产品 # 小列表名
      links:
        - title: Producthunt # 网站1
          logo: assets/images/logos/producthunt.png
          url: https://www.producthunt.com/
          description: 发现新鲜有趣的产品
        - title: Producthunt # 网站2
          logo: assets/images/logos/producthunt.png
          url: https://www.producthunt.com/
          description: 发现新鲜有趣的产品
```
- 站点的"关于本站"页面，在 `content/about.md` 修改
- 其它信息（导航网站的名称等）通过 `config.toml` 修改
- 可能用到的 hugo 命令
```
hugo -D  # deploy
hugo server # 本地测试
```
- 感谢主题制作者[iplaycode](https://github.com/iplaycode)

