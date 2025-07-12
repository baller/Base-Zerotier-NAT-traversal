首先去 zerotier 官网下载一个 zerotier 客户端
https://www.zerotier.com/download/

将 planet 文件覆盖粘贴到 C:\ProgramData\ZeroTier\One 中 (这个目录是个隐藏目录，需要运允许查看隐藏目录才行)

Win+S 搜索 服务
找到 ZeroTier One，并且重启服务

使用管理员身份打开 PowerShell
执行如下命令，看到 join ok 字样就成功了
zerotier-cli join dd7733d0b6f823ae
zerotier-cli orbit dd7733d0b6 dd7733d0b6