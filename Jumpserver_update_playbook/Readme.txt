1.安装前需要先准备Jumpserver离线安装包
2.关闭ansible的ssh秘钥检查
+++++++++++++++++++++++++++++++++++++++
    # vim /etc/ansible/ansible.cfg
    host_key_checking = False
+++++++++++++++++++++++++++++++++++++++
3.如果使用root用户执行，可以开启 pipelinging
pipelinging = True