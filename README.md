# vcard
vcf2txt.exe
>>>本工具把通讯录 从VCARD格式导出文本TEXT电话号码  BY Hong Wenjun

>>>示例 1 ：D:\>vcf2txt.exe  TelVcard.vcf
>>示例 2 ：D:\>vcf2txt.exe  TelVcard.vcf  TelText.txt


txt2vcf.exe
>>>本工具把通讯录 从文本TEXT转换成VCARD格式导入手机使用  BY Hong Wenjun

>>>示例 1 ：D:\>txt2vcf.exe  TelText.txt
>>示例 2 ：D:\>txt2vcf.exe  TelText.txt  TelVcard.vcf


测试输入(按回车转换记录,按Ctrl+Z关闭程序):

姓名    手机号码        移动短号
>吃枣药丸   13412341234     1234


>>>
BEGIN:VCARD
VERSION:2.1
N;CHARSET=UTF-8;ENCODING=QUOTED-PRINTABLE:;=E5=90=83=E6=9E=A3=E8=8D=AF=E4=B8=B8=
20=20=20=31=33=34=31=32=33=34=31=32=33=34=20=20=20=20=20=31=32=33=34;;;
FN;CHARSET=UTF-8;ENCODING=QUOTED-PRINTABLE:=E5=90=83=E6=9E=A3=E8=8D=AF=E4=B8=B8=
20=20=20=31=33=34=31=32=33=34=31=32=33=34=20=20=20=20=20=31=32=33=34
TEL;CELL:
TEL;HOME:
END:VCARD

