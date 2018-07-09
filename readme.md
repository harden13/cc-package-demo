#### 开发laravel扩展

##### 用法
`composer require young/hasher`

或者在你的composer.json文件中添加

`"young/hasher":"~1.0"`

下载完毕后，直接配置app.php的provider数组

`\Young\Hasher\MD5HasherProvider::class,`