###test
## 利用Python3.6的Splinter模块模拟浏览器刷12306火车票

### 问题交流

文章，我发布在掘金上面，有问题的，可以看里面的评论，看能不能解决，不行的话，留言给我

文章地址：[Python3.6实现12306火车票自动抢票](https://juejin.im/post/5b116504f265da6e0636cbc2)

### 文件结构

```
├── qiangpiao.py                       # 旧的脚本，12306官网改版，现在已经跑不通了
├── new_qiangpiao.py                   # 12306官网改版，修改的对应版本，只能单车次抢票
├── new_qiangpiao_by_no.py             # 多车次抢票（循环所有车次，不建议用）
├── new_qiangpiao_by_no_v2.py          # 多车次抢票（只处理有效车次，建议使用）
├── new_qiangpiao_by_no_v2_test.py     # 多车次抢票的快速调试测试版，不需要再每次运行输入相关信息，抢票信息直接写入代码里
├── new_qiangpiao_by_time.py           # 一天范围内的时间段抢票
```

### 交流学习

如有写的不对或者错误的地方，希望大家指正，相互交流，谢谢。
