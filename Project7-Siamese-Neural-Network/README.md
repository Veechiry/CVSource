# 孪生网络(SiameseNet)

孪生网络的目标是一次性学习(one-shot learning), 也就是在增加新的类别的情况下, 无需重新训练网络. 例如在上班刷脸打卡的应用里面, 假设每天都有新员工入职, 新的员工的脸就是一个新的类别, 这个类别在网络原来的训练数据中并不存在. 如果使用传统的网络, 就需要重新训练, 但是每一个新员工入职都要重新训练显然太繁琐. 无人商店也一样, 一直有新的会员加入, 不可能即时训练新的网络. 有了孪生网络这种one-shot learning, 就可以解决以上的问题.

Part 1: 一次性学习(one-shot learning)的原理和必要性

Part 2: 孪生网络(SiameseNet)的网络结构

Part 3: 使用代码实现孪生网络(SiameseNet)

Part 4: 使用孪生网络(SiameseNet)做一个基于人脸的门禁/打卡系统