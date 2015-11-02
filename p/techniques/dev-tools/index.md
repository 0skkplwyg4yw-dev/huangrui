# ��������Թ���ʹ���ĵ� #

## ǰ�� ##
��д����ĵ�һ�쿪ʼ����������һֱ���������ǳ���Ա��ְҵ���ģ���Ϊǰ����Ա��������ˡ����������԰��������ڿ��������ж�λ��ҳ�е���ʾ�����硢���ܵȸ�ʽ���������⡣����������ķ��ٷ�չ��������������ϵĵ���������ҲԽ��ǿ�����г��õ��� FireFox �� Chrome �ĵ�������**����ʹ�� Chrome ������������������Եĳ��ù��ܵ�ʹ��**��

> F12 �� Ctrl + Shift + i ��ϼ��ɴ򿪵�������������ҳԪ�����ʼ�->���Ԫ�ء�

### Elements ###
���ڲ鿴���༭ DOM �� CSS �Ĺ��ܡ�
ͨ��ֱ���ڵ������ϸĶ� dom �� css���Բ��Ժ͵�����ʽ�ṹ��
������ Elements ���ֱ�ӸĶ� dom �� css �Ե�����ʽ����������ʽ���Ƶ� css �� html �ļ��ϡ����һ�����Ͳ���Ҫÿ�ζ��ڱ༭����Ķ���Ȼ��ˢ����ҳ���������˿���Ч�ʺͿ������顣

![elements][1]


### Network ###
���ڲ鿴��������Ĺ��ܡ�
�������ǲ鿴�������Ӧ���ݣ�����ʱ�䣬����״̬�ȹ��ܡ�
![network-1][2]

���һ�����󣬾Ϳ��Դ��������ϸ��Ϣ�����ĸ� tab���ֱ��� Headers��Preview��Response��Timing��
Headers���鿴����ͷ����Ӧͷ���� query string �ͱ���Ϣ
Preview��������Ӧ Content-Type Ԥ����Ӧ��Դ������Ӧ���ظ�ʽ�� image/jpeg����Ԥ����ʾΪһ��ͼƬ
Response���� Preview ��ʹ�û���һ������ͬ����Կ�[����][3]
Timing������ʱ��
![network-2][4]

### Sources ###
�˹��ܿ��Ի�ȡ��Ӧ�� js �� css �ļ����б����������֡�
�ɴ��б�����Դ� js �ļ����������ļ��д�ϵ���е��Դ��롣
**ͨ�� Ctrl + O �������������Կ��������� js �ļ����е��ԡ�**
![sources][5]

### Timeline ###
Timeline����¼�ͷ�����webӦ������ʱ�����л����������о��Ͳ���������������;����
ͨ����״ͼ��ʱ��ͼ�������ܷ�������λ��ʱ���Ĳ�����
�ı�ѡ�����ߵ������������ֱ�Ӷ�λ���ض�����������ܡ�
����ͼչʾҳ��ռ���ڴ�仯��
���Ͻ�����Ͱͼ���ǿ�� V8 ����һ�� gc��
![timeline][6]

### Profiles ###
ʱ����(timeline)�������Ǵ������л��ѵ�ʱ�䣬���ǲ�û�а�������֪���������е�ʱ������ʲô�����ǿ�����һЩ�Ķ�Ȼ�󲻶ϵĲ�ÿ�δ������е�ʱ�䣬������äĿ�ġ�profiles�������ṩ�˸��õķ�����profiler����������Щ������ִ��ռ���˴󲿷�ʱ�䡣�������л���chrome�����߹��ߵġ�Profiles����ǩҳ��ʼ���ܲ��ԣ�����һ���ṩ���������͵����ܲ��ԡ�

 1.  javascript cpu ʹ�����
 2. ��ջ����
 3. ��ջ��¼

![profiles-0][7]

#### javascript cpu ʹ����� ####
�˹��ܿ���չ��ҳ��������� js �����Ƚ�����ʱ�䡣
![profiles-1][8]

#### ��ջ���� ####
��ջ���տ���չʾ���ҳ���д� js ���� DOM �ڵ���ڴ���������
![profiles-2][9]

#### ��ջ��¼ ####
��¼һ��ʱ���� js ������ڴ���䣬�Զ�λ�ڴ�й¶��![profiles-3][10]

### Resources ###
Resources �������ڲ鿴��ҳ�ڱ��س־û������� cookie��Local Storage��Web SQL��IndexedDB �ȡ�
![resources][11]

### Audits ###
Audits ���ܿ������ҳ�沢�ҳ�ҳ���п����������ܵĵط��������Ƴ����õ� css��ʹ�� gzipѹ�����䣬�ϲ� js �ļ���ѹ�� cookie �Ƚ��飬�����ṩ������Ż�λ�ã��ļ���ӿڣ���
![audit-1][12]

![audit-2][13]


  [1]: https://dn-coding-net-production-pp.qbox.me/2c553e09-7be6-4e71-90c0-361e502a3944.png
  [2]: https://dn-coding-net-production-pp.qbox.me/bb2cc25d-367c-4ebc-87ce-828c7a8ff3b7.png
  [3]: http://jingyan.baidu.com/article/90bc8fc80bd5f3f652640c4b.html
  [4]: https://dn-coding-net-production-pp.qbox.me/5acffd40-075f-41a2-9cb9-b134d45d082f.png
  [5]: https://dn-coding-net-production-pp.qbox.me/ba13500d-6185-421b-8a07-e02b2bd16e4d.png
  [6]: https://dn-coding-net-production-pp.qbox.me/568b34ba-2707-471b-8541-742717a9053c.png
  [7]: https://dn-coding-net-production-pp.qbox.me/67c703f6-1ca1-4090-bdb3-e57efd67162d.png
  [8]: https://dn-coding-net-production-pp.qbox.me/803d5a1d-de79-4f98-bceb-52f80e4f0029.png
  [9]: https://dn-coding-net-production-pp.qbox.me/75337a19-c43c-4350-983b-652c654ad419.png
  [10]: https://dn-coding-net-production-pp.qbox.me/a601533a-cef9-4949-bc35-0c24ee70a953.png
  [11]: https://dn-coding-net-production-pp.qbox.me/db1c5089-9ff6-4286-a3ab-aa591bb4e2be.png
  [12]: https://dn-coding-net-production-pp.qbox.me/e34f3b46-e91f-4f8b-a846-c6ec80e7ed3d.png
  [13]: https://dn-coding-net-production-pp.qbox.me/ab9b0e26-7cf8-4992-a1e5-067df47a6aee.png