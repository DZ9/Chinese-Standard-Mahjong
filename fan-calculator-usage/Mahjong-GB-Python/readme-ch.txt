����python setup.py install --user��װ

�ο�test.py

from MahjongGB import MahjongFanCalculator

�㷬��������ԭ��C++ѡ�ֲ�̫������Python����,����������ο�C++��readme��:
((value,descripthon),...) MahjongFanCalculator(
    pack=((packType,tileCode,data),...),
    hand=(tileCode,...),
    winTile,
    flowerCount,
    isZIMO,
    isJUEZHANG,
    isGANG,
    isLAST,
    menFeng,
    quanFeng);

pack��tuple��tuple��:��ҵ����ƣ�ÿ��packType(string)Ϊ"PENG" "GANG" "CHI" ����֮һ���ڶ���tileCode(string)Ϊ�ƴ��루���Ʊ�ʾ�м��ƴ��룩��data(int)������ʱ��ʾ�ϼҡ��Լҡ��¼ҹ��ƣ���ʱ123��ʾ�ڼ������ϼҹ��ơ�
hand��tuple��:��ҵİ��ƣ�tileCode(string)Ϊ�ƴ���
winTile��string��:�͵������ƴ���
flowerCount��int��:������
isZIMO��bool��:�Ƿ�Ϊ��������
isJUEZHANG��bool��:�Ƿ�Ϊ�;���
isGANG��bool��:���ڸܣ����ϵ��ʱΪǹ�ܺͣ�����������Ϊ���Ͽ���
isLast��bool��:�Ƿ�Ϊ��ǽ���һ�ţ���������Ϊ���ֻش�������Ϊ��������
menFeng��int��:�ŷ磬0123��ʾ��������
quanFeng��int��:Ȧ�磬0123��ʾ��������
�������أ�tuple��tuple��,ÿ���һ��int��ʾ���������Ϊ�ܷ������ڶ���string��ÿ�����ε�����