�ð�����һ���ܹ���һ���ӹ�Ʊ���ڻ����С�������������˺ţ�Ȼ������µ��Ĺ��ߡ�


�������WindR������

�˻�Ҫ��ʹ��w.tlogon��½������˺����½��Σ���������Basket<-data.frame��ʽ��ֵ��

���£�

library(WindR)
w.start(0,F);
w.tlogon('0000',0,c('w081263801','w081263802'),0,c('sh','cfe'));

Code<-c('600000.sh','600177.sh','IF1412.CFE','TF1412.CFE');
TradeSide<-c('buy','buy','buy','short');
Weight<-c(100,100,1,1);
Basket<-data.frame(Code=Code,TradeSide=TradeSide,Weight=Weight,stringsAsFactors = FALSE)

����������
       ��Ӧ�ð��������ο����κ�����ʹ�ñ������������ķ��ռ���ʧ��ʹ�������ге���Ӧ�ð����ṩ�߲����κ����Ρ�