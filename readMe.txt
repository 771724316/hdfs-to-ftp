һ��ʹ��˵��
1.��ѹ
2.���ļ����е�hdfsToFtp.jar ��confĿ¼������hadoop������jar�ļ���conf�ļ��б�����ͬһ��Ŀ¼
3.�޸�confĿ¼��hdfs-on-ftp.properties����
4.����:hadoop jar hdfsToFtp.jar arg1 arg2 arg3

�������ͣ�
arg1:hdfs�ļ���Ŀ¼��·��
arg2:ftp�ļ���Ŀ¼��·��
arg3����ѡ��:���ĸ�ʱ�����ļ���ʼ���ļ�����ʱ�䣩����֧�����ָ�ʽ
  1.yyyyMMdd��ָ��ĳһ��Ĵ������ļ�
  2.yyyyMMhhddHH:ָ��ĳһСʱ�ڴ������ļ�
  3.yyyyMMhhddHHmmss~ :ָ��ĳ��ʱ���֮�󴴽����ļ�
  4.����Ļ���Ĭ�����е��ļ�

��������˵����

1.����hdfsĿ¼�е������ļ�������ftpĿ¼��
  hadoop jar hdfsToFtp.jar /itf/cdr/cdrfix/anhui /daas/nstl/cdrfix/anhui
 
2.����hdfsĿ¼�е��ļ���ftpĿ¼��ֻ����6��28�Ŵ������ļ�
  hadoop jar hdfsToFtp.jar /itf/cdr/cdrfix/anhui /daas/nstl/cdrfix/anhui 20150628

3.����hdfsĿ¼�е��ļ���ftpĿ¼��ֻ����6��28��10��~11��֮�䴴�����ļ�
  hadoop jar hdfsToFtp.jar /itf/cdr/cdrfix/anhui /daas/nstl/cdrfox/anhui 2015062810

4.����hdfsĿ¼�е��ļ���ftpĿ¼��ֻ����6��28 8:45֮�󴴽����ļ�
  hadoop jar hdfsToFtp.jar /itf/cdr/cdrfix/anhui /daas/nstl/cdrfox/anhui 20150628084500~

����Ч��
�����ԣ�һ���������ٶ�ԼΪ60MB/s
