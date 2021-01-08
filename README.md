## go-minio-uploader

基于go语言打包的二进制文件，实现在typro中插入图片时，自动上传到minio文件服务器中，并自动根据typro文件名新建文件夹



需要自行实现minio文件服务器



#### Installation

1. 在用户目录下，新建一个文件夹，比如：.minio-uploader
2. 复制 minio-uploader.exe 和 config.yml 到 .minio-uploader目录下
3. 打开 typro 设置中的 图像 -> 上传服务（Custom Command） -> 自定义命令 ("C:\Users\Mr_lee\.minio-uploader\minio-uploader.exe" upload -c "C:\Users\Mr_lee\.minio-uploader\config.yml" -f "${filename}" ) 即可

