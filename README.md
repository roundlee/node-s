# node-s
# 学习一下
# 对 githup 设置了ssh 访问
* ssh-keygen -t rsa -C "round20@163.com"*
* ~/.ssh/id_rsa.pub    # 公钥
* ~/.ssh/id_rsa        # 私钥
* cat  ~/.ssh/id_rsa.pub   # 查看公钥
# 然后把公钥添加到github 上
# 然后在本地git 上设置
*  ssh -T git@github.com # 查看是否添加成功
*git remote add origin william.henry.harrison@example-pet-store.com:round20/node-s.git*
# 然后就可以push 到github 上
