## ����У԰�ͻ���linux��docker����
[���Źٷ��ͻ�������](http://zsteduapp.10000.gd.cn/More/linuxDownLoad/linuxDownLoad.html)
### ʹ�÷�����
```bash
docker run -itd -e ESURFING_USER=�˺� -e ESURFING_PASSWORD=���� --name esurfing --net=host --cpus=0.05 --memory 128m --restart=always g4yd0n/esurfing:latest
```
### ��������
```
docker buildx build -t esurfing -f .\ESurfing.Dockerfile .
```