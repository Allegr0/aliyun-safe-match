# 1 ����
1. ����Ŀ�Ĵ����ǲμ� 
[�����ư�ȫ�㷨��ս��](https://tianchi.aliyun.com/competition/information.htm?raceId=231585) ʱд�ġ���Ҫ���ù����������ʽ��������29��
2. Ϊ�˸��õ������Ŀ������Ŀ�������ع��������˴�������岿�֡�

# 2 ����˼·

## 2.1 ������վ�ж�</h2>
* ��ȡ��վ��֮�ҡ�����վ���������������������Ĺؼ��ֵ���վ�ĵ�ַӳ���<br>
* ������ҳ,��ȡ�ؼ���<br>
* ���ݹؼ��ֲ�ѯ������<br>

## 2.2 WebShellͨ�ż��</h2>
* �оٶ�����룬�磺eval call_user_func ��<br>
* д����������������ʽ<br>
* ����������ʽƥ��<br>


# 3 ��Ŀ�ṹ

```
| - safe.fish �жϵ�����վ�������߼���
| ----  | DomainConflictChecker.java ����ҳ�����һЩ���ӳ�ͻ�����ж�
| ----  | FishFilter.java �жϵ�����վ������࣬�����߼�
| ----  | PageInfo.java ����URL��HTML����������ҳ��Ϣ����
| ----  | PageKeyChecker.java ������ҳ�ı��еĹؼ��ֽ��м��
| ----  | Result.java �����ö����
| - safe.fish.utils  �жϵ�����վ�Ĺ�����
| ----  | DataLoader.java �����ļ��е�����
| ----  | TitleDivider.java ����ҳ�����л�ȡ�ؼ���
| ----  | XnTool.java ����xn--����ַ�е�����
| ----  | ZhushiUtil.java ȥ��һЩע��
| - safe.fish.whitelist  ���ĵ�������ӳ���
| ----  | ChineseDns.java �������ĵ�������ӳ��
| ----  | SpiderOfChinaz.java ��ȡվ��֮�ҵ���������
| - safe.webshell �ж�webshell�������߼���
| ----  | Decoder.java ������
| ----  | TextChecker.java �ж��ı��Ƿ����ִ��
| ----  | WebShellDetector.java ����ַ�������м��
```