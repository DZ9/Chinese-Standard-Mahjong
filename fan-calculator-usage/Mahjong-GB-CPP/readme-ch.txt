�ο�test.cpp

ʹ��ǰ��ʼ��:
#include "MahjongGB/MahjongGB.h"
void MahjongInit();

�㷬����:
vector<pair<int, string> > MahjongFanCalculator(
    vector<pair<string, pair<string, int> > > pack,
    vector<string> hand,
    string winTile,
    int flowerCount,
    bool isZIMO,
    bool isJUEZHANG,
    bool isGANG,
    bool isLAST,
    int menFeng,
    int quanFeng);

pack:��ҵ����ƣ�ÿ���һ��stringΪ"PENG" "GANG" "CHI" ����֮һ���ڶ���stringΪ�ƴ��루���Ʊ�ʾ�м��ƴ��룩��������int������ʱ��ʾ�ϼҡ��Լҡ��¼ҹ��ƣ���ʱ123��ʾ�ڼ������ϼҹ��ơ�
hand:��ҵİ��ƣ�stringΪ�ƴ���
winTile:�͵������ƴ���
flowerCount:������
isZIMO:�Ƿ�Ϊ��������
isJUEZHANG:�Ƿ�Ϊ�;���
isGANG:���ڸܣ����ϵ��ʱΪǹ�ܺͣ�����������Ϊ���Ͽ���
isLast:�Ƿ�Ϊ��ǽ���һ�ţ���������Ϊ���ֻش�������Ϊ��������
menFeng:�ŷ磬0123��ʾ��������
quanFeng:Ȧ�磬0123��ʾ��������
��������vector��ÿ��int��ʾ���������Ϊ�ܷ�����string��ÿ�����ε�����