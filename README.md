# free4g
free4g private


授权码：sbwml.cn


常规VPS安装脚本（Centos6.x）：

wget https://github.com/ChicBrother/free4g/blob/master/vpn6;chmod +x vpn6;./vpn6


Centos7.0 综合脚本（2016-05-24 自定义端口）

wget https://github.com/ChicBrother/free4g/blob/master/vpn7;chmod +x vpn7;./vpn7
 
自定义端口命令：port


如果提示出错 bash: wget: command not found 
请执行 yum -y install wget

附加脚本： 开启网易蜂巢6/7.0 SSH密码登录

wget https://github.com/ChicBrother/free4g/blob/master/ssh163 && bash ssh163



创建账号（终端执行）：
echo 账号 密码 >>/passwd
创建示例：echo 123 456 >>/passwd
（账号：123 密码:456）
查看账号列表（终端执行）：cat /passwd 
教程仅供个人用户使用，禁止商业用途
