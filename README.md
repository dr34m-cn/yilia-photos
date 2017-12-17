# yilia-photos
yilia的相册
这是[Litten](http://litten.me/)相册的修改版，版权归原作者所有

#### [点此预览效果](https://blog.ctftools.com/photos/)

### 使用说明

#### 本相册适用于hexo-yilia主题，移植到其他主题需要改动

#### 这是[Litten](http://litten.me/)相册的修改版，版权归原作者所有，源文件见[Litten博客备份](https://github.com/litten/BlogBackup)

### 使用方法

1.将本项目所有文件保存到您hexo的source目录下的一个目录里

2.将原图片保存到ins文件夹下，图片略缩图保存在minins文件夹下

3.如果原图名称为xxxx.jpg，则略缩图名称为xxxx.min.jpg

4.修改ins.json与您实际情况相匹配，其中图片名不需要写后缀，描述部分随意，图片尺寸格式为图片宽度x图片高度，例如：
```
{
	"date": "2015-05",
	"arr": {
		"year": 2015,
		"month": 5,
		"link": ["201505251818"],
		"text": ["这是一张在2015年五月拍摄的照片"],
		"sizes": ["1000x1000"]
	}
}
```
