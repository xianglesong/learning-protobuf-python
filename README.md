# protoc转换
$protoc -I=proto --python_out=. proto/msg.proto

# 安装
sudo pip install --upgrade protobuf

# 运行
python read.py address.dt