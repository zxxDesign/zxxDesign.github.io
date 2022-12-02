# zxxDesign.github.io


### 维护
#### 编辑内容
``` shell
# 创建新项目
hexo new 项目名
# 然后将图片移到项目名同名文件夹下
# 封面移到 themes/hexo-theme-edinburgh/source/images 中
```


#### 上传源码
``` shell
git add .
git commit -m "描述更新内容"
git push origin main
```


#### 部署
``` shell
hexo clean
hexo g
hexo d
```