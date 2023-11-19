1. **文件和目录操作:**
   - `ls`: 列出目录内容
   - `cd`: 切换目录
   - `pwd`: 显示当前工作目录的路径
   - `cp`: 复制文件或目录
   - `mv`: 移动文件或目录，也可用于重命名
   - `rm`: 删除文件或目录
   - `mkdir`: 创建新目录
   
2. **文件查看和编辑:**
   
   - `cat`: 连续显示文件内容
   - `more` or `less`: 分屏显示文件内容
   - `nano` or `vim` or `emacs`: 文本编辑器
   - `head` and `tail`: 显示文件的开头或结尾几行
   
3. **系统信息:**
   - `uname -a`: 显示系统信息
   - `df -h`: 显示磁盘空间使用情况
   - `free -m`: 显示内存使用情况
   - `top` or `htop`: 实时显示系统资源使用情况
   
4. **进程管理:**
   - `ps`: 显示系统进程
   - `kill`: 杀死进程
   - `killall`: 杀死指定名称的所有进程
   
5. **用户和权限:**
   - `whoami`: 显示当前用户名
   - `passwd`: 修改密码
   - `sudo`: 以超级用户权限执行命令
   - `chmod`: 修改文件权限
   - `chown`: 修改文件所有者
   
6. **网络相关:**
   - `ping`: 测试与另一台主机的连接
   - `ifconfig` or `ip a`: 显示网络接口信息
   - `netstat`: 显示网络状态
   - `traceroute` or `mtr`: 跟踪数据包的路径
   - `wget` or `curl`: 下载文件
   
7. **压缩和解压缩:**
   
   - `tar`: 创建和解压tar归档
   - `zip` and `unzip`: 创建和解压zip文件
   - `gzip` and `gunzip` or `zcat`: 压缩和解压缩文件
   
8. **查找文件:**
   
   - `find`: 根据条件查找文件
   - `grep`: 在文件中搜索特定模式
   
9. **后台启动java程序:**

   - `nohub java -jar name &`

   - `ps -ef | grep java`: 查看运行java程序

   - `kill -9 [进程号]`: 关闭运行的java程序

10. **maven打包程序**

    -  `mvn clean package -DskipTests=true`
