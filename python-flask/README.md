说明
===
ueditor的python-flask后台处理程序
可以处理上传图片的后台操作。

配置
===
../ueditor.config.json 

// 服务器统一请求接口路径
, serverUrl: URL + "php/controller.php"

依实际需求改掉

config.json 中
XXXXXPathFormat 依据自己需求改掉

controller.py 中
root_path = os.path.join(app.root_path, '../..')

依据自己需求改掉

