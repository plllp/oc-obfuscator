### Description:
1. Make sure ```reskey.txt``` is under the current directory.
2. Input your project path.
3. Input salt value, Only letters are allowed.
4. If successful, an encrypted key-value is output, good luck..


### build:
```
$ git clone https://github.com/ch4r04/oc-obfuscator.git
$ cd oc-obfuscator
```
### step 1:
```
$ python oc-obfuscator.py
```
### step 2:
input your project path;
```
->ProjectName:/User/aaa/Desktop/ExampleProj
```
Folder tree structure:
```
├── /Users/aaa/Desktop/ExampleProj/ExampleProj
		├── /Users/aaa/Desktop/ExampleProj/.git
			├── COMMIT_EDITMSG
			├── config
			├── description
			├── HEAD
			├── /Users/aaa/Desktop/ExampleProj/ExampleProj/.git/hooks
				├── README.sample
.....
....
```
### step 3:
```
->SaltKey:hello
```
```
Read OK!!!!!
SaltKey:OIJ
------------------------------------------
LogPath: /Users/aaa/Desktop/TrueSDK/oc-obfuscator/seclog.txt
Encrypt ProjectPath: /Users/aaa/Desktop/ExampleProj/oc-obfuscator/FuckSDK
success!
``

