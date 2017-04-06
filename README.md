# Backup
backup your website and sql at local server
利用shell脚本实现server端的网站文件及其数据库备份，将文件及数据库以ZIP压缩包形式压缩，可以根据需要设置压缩密码，防止数据泄露被非法利用。压缩包以“网站域名+db+星期”形式命名，结合crontab可以实现七天循环备份，并且新生成的压缩包会覆盖原来的同名文件，减少服务器的储存压力。
