\src\flaskr\static\js\wangEditor.min.js
# 用来修改单图片上传大小
uploadImgMaxSize

conf/app.conf
# 允许便签最大大小
MEMO_MAX_SIZE = 5

python虚拟环境运行
cd /d %~dp0
%~dp0\venv\Scripts\python.exe src/main.py -c conf/app.conf
