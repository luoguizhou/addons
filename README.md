NOTIC
=======
相关功能已经正式发pr到openerp-china,这里不再更新,大家可以去openerp-china上关注pr,查看最新动态,谢谢大家


MP
=========
1. 添加了汇率手动输入功能,这个可能不是每个人都需要,后期可能会删除(变成了汇率辅助显示)
2. 原有的报表使用reduce方式计算,速度缓慢,现在改成了闭包形式
3. 添加了资产损益表,利润表打印
4. 完全按照表结法进行计算,和官方功能同步

UPDATE
=========
1. 优化了report向导页面
2. 添加了"中国凭证快速输入"菜单
3. 优化了报表的页面代码.
4. 报表页面每一项都添加了余额,方便对账
5. 部分类使用v8 api重写
6. 日记账,会计期间和日期直接添加了onchange,优化用户体验
7. 中国凭证现在可以录入各种日记账内容
8. 中国凭证页面优化,反正各种页面优化,提高用户体验,改的比较多,不一一列举,有兴趣的可以看一下代码,欢迎提意见
.
.
.

TODO
=========
1. 目前还没有研究出来期初结余怎么和官方的开账分录日记账结合起来,所以报表里期初那个字段全部都是0.0, 等我研究清楚了这次修改我会发pr到osc(了解到官方是表结法,这个问题已经完美修复)

欢迎感兴趣的朋友测试提意见!!!尤其是期初结余的问题
