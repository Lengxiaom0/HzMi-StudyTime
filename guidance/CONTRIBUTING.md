# �����HzMi-StudyTime����

HzMi���Ⱦ�����ʵ���ҿ�Դ������λΪ��ʵ����ͬѧ�Է���֯�Ŀ�Դѧϰ������Ϊ���ô�ҵ�ѧϰ������������ƺ��Ѽ����֪ʶ���Ѷȴ�󽵵Ͷ���

���Ƿǳ�ϣ�������ܹ�Ϊ HzMi���Ⱦ�����ʵ���� ��Դ�����������ף����Ұ������ǰ������ñ����ڸ��ã�

## �ύ����PR��

��Ϊ�����ߣ������ύ�������֮ǰ������������ϣ������ѭ�Ĺ淶��

1. ���ȣ��� [HzMi-StudyTime GitHub](https://github.com/random-zhou/HzMi-StudyTime/pulls) ������������Ҫ�ύ��ص����ݿ��Ż�رյ� PR����������Ҳ��ϣ���ظ����еĹ�����

2. Ȼ�� [HzMi-StudyTime Fork](https://github.com/random-zhou/HzMi-StudyTime/fork) [HzMi-StudyTime](https://github.com/random-zhou/HzMi-StudyTime) �ֿ⣬��������Ĳֿ⵽����

   ```
   git clone ����fork�Ĳֿ��ַ��
   ```

3. ���HzMi-StudyTimeԭ�ֿ⣬����ͬ��Զ�ֿ̲����µĸ���

   ```
   git remote add upstream https://github.com/random-zhou/HzMi-StudyTime
   ```
   
4. ͬ�����ֿ���뵽�㱾�أ��Լ�ͬ������fork��Զ�ֿ̲�

   ```
   # ��upstream��֧�ϣ���ȡ���´���
   git fetch upstream
   # �л���main��֧��
   git checkout main
   # ��upstream��֧�ϵĸ������ݺϲ���main��,���ص�main��֧�ͺ�����ͬ����
   git merge upstream/main
   # ����ѱ���mainͬ��������fork�Ĳֿ��ַ����Զ�̷�֧
   git push origin main
   ```

   > ע�⣺ÿ�ο�ʼ�ύǰ������ͬ�����ֿ�Ĵ���

   

5. �����Լ�fork�Ĳֿ⣬�봴��һ����֧�����ύ��ı�����ݡ���֧�������ܵ���һ�����塣

   ```
   git checkout -b my-docs-branch main
   ```

6. ����ķ�֧��������޸ģ��ύcommitʱ���밴�����ǵ�[Commit��Ϣ��ʽ](#Commit��Ϣ��ʽ)���б�дcommit��������������������ģ�����д��������ʱ���밴��[���������淶](#���������淶)��д�������ݡ�

   ```
   git commit -m "[docs]: xxxx"
   ```

7. �ύ���ݵ����GitHub�ֿ�

   ```
   git push origin  my-docs-branch
   ```

8. �ص�GitHub�ֿ�ҳ�棬�ύPR��`HzMi-StudyTime:main`

9. ����"�������"�Ĺ�����Ŀ����ӵĹ���Ӧ������Ƶ�����йأ�����Ӧ���Ƿǳ�����ӡ����̵Ĺ�����

## Commit��Ϣ��ʽ

�ύ�� commit message  �������`<type>`��`<summary>`������

```
[<type>]: <summary>
  ��        ��
  ��        ����? �����������޸����ݣ���βû�о��
  ��
  ����? Commit Type: |docs|feat|fix|refactor|
```

### Type 

* **docs**�������޸����ĵ�������������ĵ���ѡ��`docs`

������������������漰������Э��Ԥ��

* **feat**��������ָһ���µĹ���
* **fix**���޸�bug
* **refactor**: �ع����룬���漰�¹��ܻ���bug�޸�

### summary

* ��Ӣ�������޸ĵ����ݣ���Ҫ�þ��(.)��β

> eg: git commit -m "[docs]: add a contributing.md file"

## ���������淶

```
# [�ڿ���] ��������
[CVPR 24] lovieChat: From Dense Token to Sparse Memory for Long VideoUnderstanding
```
