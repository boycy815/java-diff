### **ԭ��**

����˵����A=GGATCGA��B=GAATTCAGTTA

**��һ������ʼ��LD����**

��ʽһ

��ai=bj����LD(i,j)=LD(i-1,j-1)

��ai��bj����LD(i,j)=Min(LD(i-1,j-1),LD(i-1,j),LD(i,j-1))+1

![](https://github.com/skypanda100/merge/blob/master/wiki/1.jpg)

**�ڶ��������������Ĺ�ʽһ�������һ��**

![](https://github.com/skypanda100/merge/blob/master/wiki/2.jpg)

**�����������������Ĺ�ʾһ�������������**

![](https://github.com/skypanda100/merge/blob/master/wiki/3.jpg)

**���Ĳ�����λ�ھ�������½�**

![](https://github.com/skypanda100/merge/blob/master/wiki/4.jpg)

**���岽�����ݵ�Ԫ������������Ͻ�**

��ai=bj������ݵ����Ͻǵ�Ԫ��

![](https://github.com/skypanda100/merge/blob/master/wiki/5.jpg)

��ai��bj�����ݵ����Ͻǡ��ϱߡ������ֵ��С�ĵ�Ԫ��������ͬ��Сֵ�ĵ�Ԫ�����ȼ��������Ͻǡ��ϱߡ���ߵ�˳��

![](https://github.com/skypanda100/merge/blob/master/wiki/6.jpg)

����ǰ��Ԫ�����ھ���ĵ�һ�У����������ߵĵ�Ԫ��

����ǰ��Ԫ�����ھ���ĵ�һ�У���������ϱߵĵ�Ԫ��

![](https://github.com/skypanda100/merge/blob/master/wiki/7.jpg)

��������Ļ��ݷ��򣬻��ݵ���������Ͻ�

**�����������ݻ���·����д��ƥ���ִ�**

�����ݵ����Ͻǵ�Ԫ�񣬽�ai��ӵ�ƥ���ִ�A����bj��ӵ�ƥ���ִ�B

�����ݵ��ϱߵ�Ԫ�񣬽�ai��ӵ�ƥ���ִ�A����_��ӵ�ƥ���ִ�B

�����ݵ���ߵ�Ԫ�񣬽�_��ӵ�ƥ���ִ�A����bj��ӵ�ƥ���ִ�B

����������ƥ��·����ƥ���ִ�Ҳ�������

A��GGA_TC_G__A

B��GAATTCAGTTA

### **�ɹ���**
![](https://github.com/skypanda100/merge/blob/master/wiki/r0.jpg)

![](https://github.com/skypanda100/merge/blob/master/wiki/r1.jpg)