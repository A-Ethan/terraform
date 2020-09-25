# 

## Chocolatey (Windows) 
If you are on a Windows machine and use Chocolatey for package management, you can install Hugo with the following one-liner:

install-with-chocolatey.ps1

```
choco install hugo -confirm
```
Or if you need the “extended” Sass/SCSS version:

install-extended-with-chocolatey.ps1
```
choco install hugo-extended -confirm
```
## hugo

生成站点
```
hugo new site
```

创建页面
```
hugo new about.md
```

生成静态页面
```
hugo --destination="./docs"
```

本地测试
```
hugo server --theme=hyde-y --buildDrafts
```
访问

http://localhost:1313

