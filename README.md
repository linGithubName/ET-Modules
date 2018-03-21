放置ET的Modules，每个Module一个目录,子目录的文件保持跟ET一样的结构，保证使用者复制粘贴就能放到正确的位置
比如http module  
  
每个module带两个文件，一个README.md是该Module的使用说明，一个Version.txt表示依赖的ET版本

Http  

----Readme.md  
----Version.txt  

----Server  
--------Model  
------------Module  
----------------Http  
--------Hotfix  
------------Module  
----------------Http  
----Unity  
