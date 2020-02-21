#### CVE-2020-1938(Tomcat-file_include and file_red)
Tomcat的文件包含及文件读取漏洞利用POC

### 文件读取
* Usage :python2 "Tomcat-ROOT路径下文件读取(CVE-2020-1938).py" -p 8009 -f /test.txt 127.0.0.1
### 文件包含
* Usage :python2 "Tomcat-ROOT路径下文件包含(CVE-2020-1938).py" -p 8009 -f /test.txt 127.0.0.1

复现详情：http://www.svenbeast.com/post/fqSI9laE8/

* img:
![RCE](./rce.png)

参考链接：
* https://twitter.com/jas502n/status/1230531680999395328
* https://forum.90sec.com/t/topic/801
* https://github.com/YDHCUI/CNVD-2020-10487-Tomcat-Ajp-lfi/


