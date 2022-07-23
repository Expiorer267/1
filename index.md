# 极域工具

> [极域克星](https://pan.bilnn.cn/api/v3/file/sourcejump/Nl2ZGLuW/CgUzKinAxRSTZUjoZcRPacxyMD4k_DPsgp_8TpErLoY*)

> [极域杀手 V4.1](https://pan.bilnn.cn/api/v3/file/sourcejump/1M3XWWIw/Q3m3vxHSDRkstIqPoaUXDC7GYxuHBMlGrGndIEKJdCI*)

> [UnMythware_V4.5专业版](https://pan.bilnn.cn/s/2XBZiM)

>[byebye极域](https://pan.bilnn.cn/api/v3/file/sourcejump/DoKzGEI9/kIPLW6h6dm-eSbiuR_DcFWHQa2ouGjDb_6BLw-6a97I*)

### 技巧
 一：网络类
    
     1.拔网线（物理）
    
     2.禁用网络适配器
      - 网络共享中心>网络适配器>右键>选择禁用
    
     3.更改IP地址
      - 网络和共享中心>本地连接>属性>选择任意一个Internet协议版本（IPv4或IPv6）>属性>选择手动填IP地址>乱填即可
    
     注意：前三种方法会让你无法上网
    
     4.设置通用防火墙
      - 网络和共享中心>Windows防火墙>打开或关闭Windows防火墙>勾选“阻止所有传入链接，包括位于允许程序列表中的程序”（两个（就是“家庭或工作（专用）网络位置设置”和“公用网络位置设置”那里的）都要勾选！！！
      
      - 但是阻止传入所有链接也有很多副作用
    
     5.设置单独防火墙
      - 网络共享中心>Windows防火墙>高级设置>入站规则>找到所有的名为“StudentMain.exe”，选择禁用或删除
    
     6.内鬼Specialset
      - 打开极域的文件夹>找到Specialset.exe>打开它>勾选“Use IP Broadcast>点击确定
    
     但是这一切的一切都有一个条件，就是你的老师没有开断网锁机，否则后果自负。
      
      - 解决办法：修改注册表
        - 按下Win+R组合键>输入“regedit”>进入HKEY_LOCAL_MACHINE>SOFTWARE>Wow6432Node>TopDomain>e-Learning Class>Student>把EnableLockScreen的数值数据改为0>点击确定>关闭注册表

二：进程类
    
     1.任务管理器杀进程
      - 右键任务栏打开任务管理器（Windows11的系统Win+R打开运行，输入"taskmgr"）>转到“进程”选项卡>找到并选择名为"StudentMain.exe"的进程>结束进程
      - 但是这个方法在极域6.0版本之后，就用不了了
    
     2.提交文件杀
      - 打开计算机或此电脑>进入C盘>把Windows文件夹拖入提交文件的窗口中>点击提交>右键任务栏打开任务管理器（Windows11的系统Win+R打开运行，输入"taskmgr"）>转到“应用程序”选项卡（Windows10及以上版本在任务管理器底下点击简略信息）>选择“文件提交”>分别点击“结束任务”和“关闭程序”
