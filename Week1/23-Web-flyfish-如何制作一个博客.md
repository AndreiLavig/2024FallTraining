---
title: �������һ������
---

<h2 id="lc4ZI">�����빤��׼��</h2>
+ <font style="color:rgb(31, 31, 31);">����ϵͳ��Windows11</font>
+ [Node.js �� ���κεط����� JavaScript (nodejs.org)](https://nodejs.org/zh-cn)  
+ [Git - ��װ Git (git-scm.com)](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git)
+ <font style="color:rgb(31, 31, 31);">Hexo</font>
+ <font style="color:rgb(31, 31, 31);">�ı��༭��(�Ƽ�VSCODE)</font>
+ <font style="color:rgb(31, 31, 31);">GitHub �ʺ�</font>

<h3 id="IxcZA"><font style="color:rgb(31, 31, 31);">��װhexo</font></h3>
�������Ҽ�ѡ��git bash������npm install -g hexo-cli

![image-20241029210320268](https://s2.loli.net/2024/10/29/gJk2KxV8jelCowv.png)

![image-20241029210402102](https://s2.loli.net/2024/10/29/f6w7Hc2iz3FTrdQ.png)



<h2 id="KWvKs">2.ע��ֿ�</h2>
1. ���newֱ�Ӵ����ֿ�

![image-20241029210459592](https://s2.loli.net/2024/10/29/o2q7CSk5MgFdVI6.png)

2. �����ֿ⣺�û���+.github.io
3. <font style="color:rgb(31, 31, 31);">��ѡ Initialize this repository with a README ��ʼ��һ��</font><font style="color:rgb(31, 31, 31);"> </font>[<font style="color:rgb(31, 31, 31);">README.md</font>](http://readme.md/)<font style="color:rgb(31, 31, 31);"> </font><font style="color:rgb(31, 31, 31);">�ļ�</font>
4. <font style="color:rgb(31, 31, 31);">��� Creat repository ���д���</font>

![image-20241029210518364](https://s2.loli.net/2024/10/29/ivZneDKt28VOSEH.png)





<h2 id="WNBEJ">3.git��ʼ��</h2>
��git bash

```shell
git config --global user.name "����û���"
git config --global user.email "�������"
```

<font style="color:rgb(31, 31, 31);">ͨ��</font>`<font style="color:rgb(244, 116, 102);">git config -l</font>`<font style="color:rgb(31, 31, 31);"> ����Ƿ����óɹ���</font>

<h2 id="zMo6F"><font style="color:rgb(31, 31, 31);">4.����github</font></h2>
1. ����ssh��Կ

��git��ִ��`ssh-keygen -t rsa -C "�������"`

<font style="color:rgb(31, 31, 31);">֮���C�����û��ļ����µ�.ssh���ļ��У��ῴ�� id_rsa.pub</font>

![](https://s2.loli.net/2024/10/29/6C1uxO4HfUVZsaE.png)

2. ��<font style="color:rgb(31, 31, 31);"> id_rsa.pub���������е�����</font>
3. <font style="color:rgb(31, 31, 31);">�� SSH KEY ���õ� GitHub</font>

<font style="color:rgb(31, 31, 31);">  ����github��������Ͻ�ͷ�� ѡ��</font>`<font style="color:rgb(244, 116, 102);">settings</font>`<font style="color:rgb(31, 31, 31);">����������ҳ��ѡ�� </font>`<font style="color:rgb(244, 116, 102);">SSH and GPG keys</font>`

![image-20241029210556718](https://s2.loli.net/2024/10/29/4YKDhJboGNWptRU.png)

![](https://s2.loli.net/2024/10/29/CIzHXWBY7upDsjS.png)

title������������Կ����<font style="color:#df2a3f;">key</font>�У����add ssh key����

![image-20241029210637377](https://s2.loli.net/2024/10/29/1NynTP4JIs3gX8V.png)

4.����

��git������`ssh -T git@github.com`�������˻���Ϣ�������������

<h2 id="xIcfi">5.��ʼ��Hexo��Ŀ</h2>
1. ѡ��һ���ļ��У��Ҽ���git bash ����hexo init

![image-20241029210647230](https://s2.loli.net/2024/10/29/PT6ivwytUDLNpal.png)

2. ������hexo s �����п����ڱ������������localhost:4000��

![image-20241029210656410](https://s2.loli.net/2024/10/29/czUji1GedVhZYQo.png)



<h2 id="HPalj">6.����̬���͹��ص� GitHub Pages</h2>
1. ��װ<font style="color:rgb(31, 31, 31);">hexo-deployer-git</font>

`<font style="color:rgb(31, 31, 31);">npm install hexo-deployer-git --save</font>`

2. <font style="color:rgb(31, 31, 31);">�޸� _config.yml �ļ�����deploy��������޸�Ϊ����ͼ��ʾ��ע��������</font>

```shell
deploy:
 type: git
 repository: #github��Ŀ��ַ
 branch: main
```

![image-20241029210734351](https://s2.loli.net/2024/10/29/I91EWBPrHG4JpMA.png)

![image-20241029210745046](https://s2.loli.net/2024/10/29/ziVLK1BZg3Ux58t.png)



3.<font style="color:rgb(31, 31, 31);">�޸ĺ����ú�����������������벿�� GitHub��</font>

<font style="color:rgb(31, 31, 31);">�������</font>`<font style="color:rgb(244, 116, 102);">Deploy done</font>`<font style="color:rgb(31, 31, 31);">����˵������ɹ��ˡ�</font>

<font style="color:rgb(31, 31, 31);">�Ե������ӣ�����������ʣ�</font>[https://](https://fomalhaut-blog.github.io/)�ֿ���<font style="color:rgb(31, 31, 31);"> ����ʱ�����ǾͿ��Կ������������ˡ�</font>

