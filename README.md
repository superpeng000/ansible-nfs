# ansible_nfs
Deployment nfs test environment via ansible.


步骤：
1、配置免密

2、给挂载硬盘分区  fdisk /dev/vdb

3、修改变量

4、进入ansible playbook目录：  ansible-playbook  -i inventory/hosts  config.yml