本次作业的raft实现部分主要参考了MIT的6.824:Distributed Systems，其中raft算法我首先是按照其lab的要求完成的，然后在改用了grpc，实现了一个可用的kv分布式存储系统系统。由于这学期我同时在实验室做了一篇raft结合spot instance的论文，所以在raft的基础上我又增加了一些新的角色Secretary和Observer，形成了一个新的协议。具体的实现文档在http://jackdu.cn/distributed%20system/2020/12/20/Geo-Raft/项目地址在https://github.com/yunxiao3/MyRaft（在本文件下也可以直接查看）其中raft目录是mit lab的实现，myraft是将其改为grpc通信，geo-raft则是新的协议。Notes中是lab实现的一些记录。

