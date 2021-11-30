1. Compile the module
	make,make clean
2. Load module
	insmod test.ko
3. check module
	lsmod
4. Uninstall the module
	rmmod test
5. view log
	less /var/log/kern.log | tail -2


git config 
	Ubuntu ssh-keygen -t rsa 生成秘钥 id_rsa.pub 拷贝到 Settins-> ssh key-> new ssh key
        在终端输入命令 ssh -T git@github.com 测试github是否绑定成功
	github token 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 
