# 极域工具

> [极域克星](https://pan.bilnn.cn/api/v3/file/sourcejump/Nl2ZGLuW/CgUzKinAxRSTZUjoZcRPacxyMD4k_DPsgp_8TpErLoY*)（链接已挂）

> [极域杀手 V4.1](https://pan.bilnn.cn/api/v3/file/sourcejump/1M3XWWIw/Q3m3vxHSDRkstIqPoaUXDC7GYxuHBMlGrGndIEKJdCI*)（链接已挂）

> [UnMythware_V4.5专业版](https://pan.bilnn.cn/s/2XBZiM)

> [byebye极域](https://pan.bilnn.cn/api/v3/file/sourcejump/DoKzGEI9/kIPLW6h6dm-eSbiuR_DcFWHQa2ouGjDb_6BLw-6a97I*)（链接已挂）

> [极域杀手（cmd窗口）](https://action.118pan.com/b1110932) 原地址：https://www.golue.com/game/v736248.html

### 技巧
- 一：网络类
   - 1.拔网线（物理）
   - 2.禁用网络适配器
       - 网络共享中心>网络适配器>右键>选择禁用
   - 3.更改IP地址
       - 网络和共享中心>本地连接>属性>选择任意一个Internet协议版本（IPv4或IPv6）>属性>选择手动填IP地址>乱填即可
- 注意：前三种方法会让你无法上网
   - 4.设置通用防火墙
       - 网络和共享中心>Windows防火墙>打开或关闭Windows防火墙>勾选“阻止所有传入链接，包括位于允许程序列表中的程序”（两个（就是“家庭或工作（专用）网络位置设置”和“公用网络位置设置”那里的）都要勾选！！！
       - 但是阻止传入所有链接也有很多副作用
   - 5.设置单独防火墙
       - 网络共享中心>Windows防火墙>高级设置>入站规则>找到所有的名为“StudentMain.exe”，选择禁用或删除
   - 6.内鬼Specialset
       - 打开极域的文件夹>找到Specialset.exe>打开它>勾选“Use IP Broadcast>点击确定
       - 但是这一切的一切都有一个条件，就是你的老师没有开断网锁机，否则后果自负。
       - 解决办法：修改注册表
         - 按下Win+R组合键>输入“regedit”>进入HKEY_LOCAL_MACHINE>SOFTWARE>Wow6432Node>TopDomain>e-Learning Class>Student>把EnableLockScreen的数值数据改为0>点击确定>关闭注册表

- 二：进程类
   - 1.任务管理器杀进程
       - 右键任务栏打开任务管理器（Windows11的系统Win+R打开运行，输入"taskmgr"）>转到“进程”选项卡>找到并选择名为"StudentMain.exe"的进程>结束进程
       - 但是这个方法在极域6.0版本之后，就用不了了
   - 2.提交文件杀
       - 打开计算机或此电脑>进入C盘>把Windows文件夹拖入提交文件的窗口中>点击提交>右键任务栏打开任务管理器（Windows11的系统Win+R打开运行，输入"taskmgr"）>转到“应用程序”选项卡（Windows10及以上版本在任务管理器底下点击简略信息）>选择“文件提交”>分别点击“结束任务”和“关闭程序”
   - 3.注册表解防杀
       - 按下Win+R组合键>输入“regedit”>进入HKEY_LOCAL_MACHINE>SOFTWARE>Wow6432Node>TopDomain>e-Learning Class>Student>把PreventKill的数值数据改为0>点击确定>关闭注册表>切换用户(Alt+f4>切换用户>确定）>右键任务栏打开任务管理器（Windows11的系统Win+R打开运行，输入"taskmgr"）>转到“进程”选项卡>找到并选择名为"StudentMain.exe"的进程>结束进程
   - 4.taskill命令
       - 按下Win+R组合键>输入"taskill /f/im studentmain.exe">确定
   - 5.资源监视器杀进程
       - 右键任务栏打开任务管理器（Windows11的系统Win+R打开运行，输入"taskmgr"）>转到“性能”选项卡>资源监视器>找到"StudentMain.exe">右键选择结束进程树
     
   - 6.资源监视器挂起
       - 右键任务栏打开任务管理器（Windows11的系统Win+R打开运行，输入"taskmgr"）>转到“性能”选项卡>资源监视器>找到"StudentMain.exe">右键选择挂起进程 

- 三：脱控类
   - 1.旋转键
       - 在老师广播屏幕时，狂点任意一个旋转键，cps够高就有几率卡崩极域。
   - 2.延时杀进程
       - 右键新建一个文本文档>后缀名改为.bat（如果没有后缀名，打开计算机（或此电脑），选项，转到查看，找到“隐藏已知文件类型的扩展名”，取消勾选即可）>右键选择编辑>填写以下内容
```
timeout /t (你要设置的延时，比如15）
taskill /f /im studentmain.exe
```
保存后执行即可。
   - 3.Win+L
       - 右键新建一个文本文档>后缀名改为.bat（如果没有后缀名，打开计算机（或此电脑），选项，转到查看，找到“隐藏已知文件类型的扩展名”，取消勾选即可）>右键选择编辑>填写以下内容
```
taskill /f /im studentmain.exe
```
然后按下Win+L>切换用户>等待极域出现后运行这个bat文件
   - 4.关机（伪）
      - 新建一个文本文档>随便写点什么（如：114514）>关闭记事本，不要保存。停留在是否保存的窗口>关机（物理或走程序）（注意不是让你直接拔电源！！！！！！！）
   - 5.粘滞键杀进程
       - 按下Win+R组合键>输入“regedit”>进入HKEY_LOCAL_MACHINE>SOFTWARE>Microsoft>Windows NT>在lmage Fil...中新建项sethc.exe>右键新建字符串值>命名为edbugger>打开>在“数值数据”那里填写“[任意名称].bat”>确定>打开此电脑或计算机>进入C盘>进入Windows文件夹>新建一个文本文档，名称为你在注册表中填写的.bat文件>更改后缀（如果没有后缀名，打开计算机（或此电脑），选项，转到查看，找到“隐藏已知文件类型的扩展名”，取消勾选即可）>打开>输入“taskill /f /im studentmain.exe”>按5此shift即可杀掉极域的进程

- 四：密码类
   - 1.注册表找密码
      - 按下Win+R组合键>输入“regedit”>进入HKEY_LOCAL_MACHINE>SOFTWARE>Wow6432Node>TopDomain>e-Learning Class Standard>1.00，UninstallPassword就是极域的密码
      - 但是这个方法在6.0版本之后就用不了了，不过还是可以通过注册表破解密码。
   - 2.注册表改密码
      - 按下Win+R组合键>输入“regedit”>进入HKEY_LOCAL_MACHINE>SOFTWARE>Wow6432Node>TopDomain>e-Learning Class>Student>找到那个名为Knock1的值，打开它，把里面的数字全部清除，这样密码就无了。
   - 3.极域万能密码 
```
mythware_super_password
```
      - 这个密码无论设了什么密码都能用它打开
   - 4.密码断连
      - 极域的设置>网络>改变频道或设置“选择教师登录”>确定
   - 5.密码卸载
      - 右键极域的快捷方式>选择“打开文件所在目录”>找到"unins000.exe"并打开它>输入万能密码选择卸载，此时极域会取消一次，多试几次即可卸载 
##### 此网页上的所有软件和技巧来源于互联网，若侵权，请发送邮件到lianshao5416@foxmail.com，我会第一时间删除相关文段。

###### 此网页由Expiorer267最后更新于2022年12月27日10点46分
