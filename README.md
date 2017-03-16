简介 : 
```
shellcode 加密工具
```
使用方法 : 
```
	python ShellcodeEncrypter.py [SHELLCODE_FILE] [PASSWORD]
```
原理 :
```
1. 读取shellcode
2. 根据用户输入的 password 将 shellcode 每一个字节与 password 异或
3. 构建 shellcode 的加载器
4. 将新的 shellcode 写入新的文件
```
注意事项 : 
```
1. 密码只可以为数字 , 范围是 0 - 255
```
参考代码 : 
```

```
