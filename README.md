# 一个简单的可以直接在页面上书写并存储的网页

## 直接使用nginx部署即可
- 首先将文件复制到`nginx`下的`www`目录
- 然后

```sh
  location /webnote {
    root /home/nginx/www/;
  }
```
预览如图：
![图片](https://user-images.githubusercontent.com/46232425/160725910-dd3c3ed1-d0b0-43a9-abb4-49866786ea93.png)
