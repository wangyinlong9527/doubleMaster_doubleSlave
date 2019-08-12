# doubleMaster_doubleSlave

## 双主双从的mysql集群

集群方案: m1-->s1  m2-->s2  m1-->m2   m2-->m1  


## 注意
由于安装包太大,所以需要自行下载安装包,下方给出安装包版本和存放位置


## 使用方式
  - 在role/mysql目录下创建file目录
  - 将mysql5.7的包放到file目录下
  - 根据包的版本和修改参数信息
  - 执行 ansible-playbook -i hosts   site.yml
