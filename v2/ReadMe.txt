基础操作：
1、首行为随从状态行，分别为：待命、待抽、缺失。默认为“待命”，若设置为“待抽”则需要有抽随从的牌配合，若设置为“缺失”则仅考虑没有该随从的打法
2、次行为打法行，分别为：otk、分回合启动、回/打十六、无限、逆序启动、清杂
3、末行为输入行，需要输入总费用（包括幸运币、暗影步减过费的鲨鱼或老千、伺机待发+骨刺存的费用等）、总杂牌数、目标伤害、暗影步数量、骨刺数量、殒命数量。“首轮”和“缺暗”为分回合启动时上回合的操作，默认为0
4、墨点为按钮，第一、二行墨点按下触发“切换状态”；第三行墨点按下触发“搜索解法”。右下角麒麟为复位按钮，按下后一键复位


备注：
1、殒命可以当幸运币用，若殒命数量为1无法操作，可以改成幸运币试试看
2、若仅含“暗影步”且“鲨鱼之灵”或“狐人老千”已被暗影步减费则关闭“逆序”；逆序时“免”为免费打出的杂牌，如果没有免费的牌，靠幸运币逆序，则杂牌数量需要+1
3、勾选“无限”后，仅显示无限相关操作，不考虑“伤害”；同理，勾选“十六”后，仅显示回/打十六相关操作，但会考虑伤害
4、勾选“十六”后，仅显示回/打十六相关操作，用于和快攻抢场面、分回合启动等，“伤害”分四档，为：0-16：回复16；17-32：回复16回手2条红龙；33-64：16+16~48；65-96：16+0~80
5、“首轮”和“缺暗”时，“杂牌”写除去可以免费打完的总手牌数
6、“杂”和“（杂）”均为“不抽牌杂”，如闪避等，区别是前者必须打出（清杂），后者可不打
7、“抽”默认为仅抽随从牌，若会抽其他牌（如行骗），需要加杂牌数
