# openresty install

## Centos7 install 

```
wget https://openresty.org/package/centos/openresty.repo
mv openresty.repo /etc/yum.repos.d/
yum install -y openresty openresty-resty openresty-doc openresty-opm  openresty-valgrind openresty-asan
yum install -y  openresty-debug    #测试环境debug使用
```

## Centos8  install 