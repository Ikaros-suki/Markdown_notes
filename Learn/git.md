### �����汾��
1. ��ĳ���ļ����ڴ� git bash
2. ==git init==
3. ==git add *filename.filetype*==
   (����һ�� add ���)
4. ==git commit -m *"xxx (��������д��ע��)"*==

![](image/2022-02-23-21-18-10.png)

---

# ʱ�������

* Ҫ��ʱ���չ�������״̬��
  ʹ��==git status==���


* ���==git status==���������ļ����޸Ĺ���
  ��==git diff==���Բ鿴�޸����ݡ�

---

## �汾����

* HEADָ��İ汾���ǵ�ǰ�汾����ˣ�Git���������ڰ汾����ʷ֮�䴩��ʹ������==git reset --hard commit_id==��

* ����ǰ����==git log==���Բ鿴�ύ��ʷ���Ա�ȷ��Ҫ���˵��ĸ��汾��

* Ҫ�ط�δ������==git reflog==�鿴������ʷ���Ա�ȷ��Ҫ�ص�δ�����ĸ��汾��

---

## ���������ݻ���

#### ������

* ���� git �� ���ڵ��ļ���

#### �汾��

* �������ļ����ڵ� .git �ļ���
* git add ���ǽ��ļ��޸���ӵ��ݴ���
* git commit ���ݴ����������ļ��ύ����ǰ��֧
  
---

## �����޸�

* ÿ���޸ģ��������git add���ݴ������ǾͲ�����뵽commit�С�
  
---

## �����޸�

* �޸����ļ�, ��û�� add ʱ, ������ ==git restore <file>==
* add ֮��, ����ʹ�� ==git restore --staged <file>==
* ***���� git status***

---

## ɾ���ļ�

* ==git rm== ����ɾ�� git ���е��ļ�

---
---


# Զ�ֿ̲�

�� cmd ��ʹ�� 

$ ssh-keygen -t rsa -C "youremail@example.com"

���� ssh , pub Ϊ��Կ

---

## ���Զ�̿�

* Ҫ����һ��Զ�̿⣬ʹ������git remote add origin git@server-name:path/repo-name.git��
* ��Ϊʹ�� ==git remote add origin https==

* ����һ��Զ�̿�ʱ�����Զ�̿�ָ��һ�����֣�origin��Ĭ��ϰ��������

* ������ʹ������==git push -u origin master==**��һ��**����master��֧���������ݣ�

* �˺�ÿ�α����ύ��ֻҪ�б�Ҫ���Ϳ���ʹ������==git push origin master==���������޸ģ�

* **==SSL certificate problem: unable to get local issuer certificate
    ������� : $ git config --global http.sslverify false==**



---

## ��Զ�̿��¡

* Ҫ��¡һ���ֿ⣬���ȱ���֪���ֿ�ĵ�ַ��Ȼ��ʹ��==git clone==�����¡��

* Git֧�ֶ���Э�飬����https����sshЭ���ٶ���졣




