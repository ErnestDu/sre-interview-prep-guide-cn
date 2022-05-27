# Site Reliability Engineer (SRE) 面试准备指南

本文旨在整合有用的资源，用于SRE面试准备。大部分问题来自[mxssl/sre-interview-prep-guide](https://github.com/mxssl/sre-interview-prep-guide)，已尽量替换成相应的中文内容。目前更新中，标有todo的还没完成。

## 基础

- [ ] 简单 [从输入 URL 到页面展示到底发生了什么？看完吊打面试官！](https://zhuanlan.zhihu.com/p/133906695)
- [ ] 详细 [当···时发生了什么？](https://github.com/skyline75489/what-happens-when-zh_CN)

## Linux

### 启动过程

- [ ] [Linux 开机引导和启动过程详解](https://blog.csdn.net/qq_26819733/article/details/77624141)
- [ ] [初步了解计算机与操作系统启动原理](https://www.jianshu.com/p/26e184605952)
- [ ] [浅谈操作系统-启动过程](https://zhuanlan.zhihu.com/p/32280478)
- [ ] [史上最详细linux启动过程讲解---没有之一](https://cloud.tencent.com/developer/article/1114481) 

### 文件系统

- [ ] [理解inode](https://www.ruanyifeng.com/blog/2011/12/inode.html)
- [ ] [深入理解linux系统下proc文件系统内容](https://www.cnblogs.com/cute/archive/2011/04/20/2022280.html)
- [ ] [mount命令详解](http://linux.51yip.com/search/mount)
- [ ] [一口气搞懂「文件系统」，就靠这 25 张图了](https://zhuanlan.zhihu.com/p/183238194)

### 内核

- [ ] [Linux内核基础](https://www.zhihu.com/column/kernel)
- [ ] [User space（用户空间）和 Kernel space（内核空间）](https://developer.aliyun.com/article/69258)
- [ ] [Linux内核三驾马车之-进程管理](https://blog.acean.vip/post/linux-kernel/gai-shu-linuxnei-he-san-jia-ma-che-zhi-jin-cheng-guan-li)
- [ ] [Linux kernel学习-内存寻址](https://zohead.com/archives/linux-kernel-learning-memory-addressing/)
- [ ] [linux内存管理（详解）](https://zhuanlan.zhihu.com/p/149581303)
- [ ] [kernel:堆(heap)和栈(stack)区别](https://blog.csdn.net/u012839187/article/details/47836137)
- [ ] [分页和分段的联系和区别](https://cloud.tencent.com/developer/article/1344772)
- [ ] [Linux系统调用](https://segmentfault.com/a/1190000039969312)
- [ ] [浅谈Linux虚拟文件系统](https://zhuanlan.zhihu.com/p/69289429)
- [ ] [Linux 内核的并发和竞态](https://blog.csdn.net/rex_nie/article/details/73250907)
- [ ] [内存泄漏的原因，内存泄漏如何避免？内存泄漏如何定位？](https://zhuanlan.zhihu.com/p/458541056)
- [ ] [Linux内核kernel panic机制浅析](https://blog.csdn.net/liukuan73/article/details/45537889)

### 故障排除

- [ ] [Linux 硬件故障排除指南](https://linux.cn/article-11953-1.html)
- [ ] [60,000毫秒内对Linux的性能诊断](https://www.oschina.net/translate/linux-performance-analysis-in-60s)

## 网络

- [ ] [计算机网络基础知识总结](https://www.runoob.com/w3cnote/summary-of-network.html)
- [ ] [Linux 中的虚拟网络接口](https://thiscute.world/posts/linux-virtual-network-interfaces/)
- [ ] [LINUX平台的开源多层负载均衡](https://blog.51cto.com/z00w00/2174319)
- [ ] [译 现代网络负载均衡与代理导论](http://arthurchiao.art/blog/intro-to-modern-lb-and-proxy-zh/)
- [ ] [负载均衡的6种算法，Ngnix的5种算法！](https://zhuanlan.zhihu.com/p/68733507)

## 容器(todo)

- [ ] [什么是 Linux 容器？](https://www.redhat.com/zh/topics/containers/whats-a-linux-container)
- [ ] [Containers Patterns](https://l0rd.github.io/containerspatterns)
- [ ] [Docker Container Anti Patterns](https://blog.couchbase.com/docker-container-anti-patterns/)
- [ ] [Anti-Patterns When Building Container Images](https://jpetazzo.github.io/2021/11/30/docker-build-container-images-antipatterns)

## Kubernetes(todo)

- [ ] [Deploying and Scaling Microservices with Docker and Kubernetes](http://container.training/kube-selfpaced.yml.html)
- [ ] [What happens when ... Kubernetes edition!](https://github.com/jamiehannaford/what-happens-when-k8s/blob/master/README.md)
- [ ] [Kubernetes Production Patterns](https://github.com/gravitational/workshop/blob/master/k8sprod.md)
- [ ] [Kubernetes production best practices](https://learnk8s.io/production-best-practices)
- [ ] [A Guide to the Kubernetes Networking Model](https://sookocheff.com/post/kubernetes/understanding-kubernetes-networking-model)
- [ ] [47 Things To Become a Kubernetes Expert](https://ymmt2005.hatenablog.com/entry/k8s-things)
- [ ] [Kubernetes Best Practices 101](https://github.com/diegolnasc/kubernetes-best-practices)

## 基础设施即代码IaC / 配置管理
- [ ] [Terraform](https://lonegunmanb.github.io/introduction-terraform/)
- [ ] [Ansible](https://ansible-tran.readthedocs.io/en/latest/)

## 数据库

- [ ] [数据库分片（Database Sharding)详解](https://zhuanlan.zhihu.com/p/57185574)
- [ ] [Data Replication in DBMS](https://www.geeksforgeeks.org/data-replication-in-dbms)

## CI/CD 持续集成/持续交付(todo)

- [ ] [7 Pipeline Design Patterns for Continuous Delivery](https://www.singlestoneconsulting.com/blog/7-pipeline-design-patterns-for-continuous-delivery)
- [ ] [CI/CD patterns](https://continuousdelivery.com/implementing/patterns)
- [ ] [Six Strategies for Application Deployment](https://thenewstack.io/deployment-strategies)

## 云计算
- [ ] [The Open Guide to Amazon Web Services](https://github.com/open-guides/og-aws)
- [ ] [Learning Azure](https://docs.microsoft.com/zh-cn/learn/azure/)
- [ ] [Hands-On Training with GCP](https://cloud.google.com/training/badges)
- [ ] [腾讯云培训认证中心](https://cloud.tencent.com/edu/training)
- [ ] [基于核心技术及岗位的阿里云权威认证](https://edu.aliyun.com/certification)

## 编程
### Python
- [ ] [PythonBasics 中文系列教程](https://github.com/apachecn/pythonbasics-zh)
- [ ] [Python For Everyone](https://www.bilibili.com/video/av46649799)


### Go (Golang)

- [ ] [Go 语言之旅](https://tour.go-zh.org/)
- [ ] [Go by Example中文版](https://gobyexample-cn.github.io/)
- [ ] [Learn Go with Tests](https://studygolang.gitbook.io/learn-go-with-tests)
- [ ] [Getting up and running with Go](http://www.golangprograms.com)
- [ ] [高效的 Go 编程 Effective Go](https://learnku.com/docs/effective-go/2020)
- [ ] [go-patterns-cn](https://github.com/archbobo/go-patterns-cn)
- [ ] [图解Go内存管理系列](https://blog.csdn.net/flynetcn/article/details/120228517)

### 大O标记法，算法，数据结构(todo)

- [ ] [AlgoExperts](https://www.algoexpert.io)
- [ ] [Hacking a Google Interview – Handout 1](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_1.pdf)
- [ ] [Hacking a Google Interview – Handout 2](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_2.pdf)
- [ ] [Hacking a Google Interview – Handout 3](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_3.pdf)

## 系统设计(todo)

- [ ] [SystemsExpert course from AlgoExpert](https://www.algoexpert.io/se/product)
- [ ] [Grokking the System Design Interview](https://www.educative.io/collection/5668639101419520/5649050225344512)
- [ ] [The System Design Primer](https://github.com/donnemartin/system-design-primer)
- [ ] [Crack the System Design Interview](https://www.puncsky.com/blog/2016/02/14/crack-the-system-design-interview)
- [ ] [System design interview for IT companies](https://github.com/checkcheckzz/system-design-interview)
- [ ] [Web Architecture 101](https://medium.com/storyblocks-engineering/web-architecture-101-a3224e126947)
- [ ] [What's in a Production Web Application?](https://web.archive.org/web/20210106095747/http://stephenmann.io/post/whats-in-a-production-web-application)
- [ ] [Distributed systems](http://book.mixu.net/distsys/single-page.html)

### 系统设计示例

- [ ] [硅谷之路58: 如何设计WhatsApp（一）](https://zhuanlan.zhihu.com/p/20923244)
- [ ] [系统设计：Uber/滴滴后端服务](https://cloud.tencent.com/developer/article/1942819)
- [ ] [Tinder 系统架构](https://xie.infoq.cn/article/b717a40affb80efa6f9cfee77)
- [ ] [【长文干货】8大步骤详解设计Instagram](https://www.1point3acres.com/bbs/thread-586264-1-1.html)
- [ ] [系统设计Netflix-一个完整的架构](https://www.imangodoc.com/187951.html)

## 监控

- [ ] [SLA、SLO 和 SLI 还是傻傻分不清么？](https://zhuanlan.zhihu.com/p/148295246)
- [ ] [说说微服务和监控](https://zhuanlan.zhihu.com/p/28851786)

## 流程(todo)

- [ ] [第13章 紧急事件响应](https://zhuanlan.zhihu.com/p/463756893)
- [ ] [Postmortems](https://postmortems.pagerduty.com)
- [ ] [Runbooks](https://www.transposit.com/blog/2019.11.14-what-makes-a-good-runbook)
- [ ] [Identifying and tracking toil using SRE principles](https://cloud.google.com/blog/products/management-tools/identifying-and-tracking-toil-using-sre-principles)
- [ ] [Building SRE from Scratch](https://medium.com/ibm-garage/building-sre-from-scratch-485e23985bbd)
- [ ] [SRE at Google: Our complete list of CRE life lessons](https://cloud.google.com/blog/products/devops-sre/sre-at-google-our-complete-list-of-cre-life-lessons)
- [ ] [Incident Management vs. Incident Response - What's the Difference?](https://rootly.io/blog/incident-management-vs-incident-response-what-s-the-difference)
- [ ] [Practical Guide to SRE: Using SLOs to Increase Reliability](https://rootly.io/blog/practical-guide-to-sre-using-slos-to-increase-reliability)
- [ ] [Practical Guide to SRE: Automating On-Call](https://rootly.io/blog/practical-guide-to-sre-automating-on-call)

## 简历(todo)

- [ ] [SRE Complete Resume Writing Guide](https://rootly.com/blog/sre-complete-resume-writing-guide)

## 面试(todo)

### 面试流程

- [ ] [How to hire talent](https://syedali.net/2014/04/01/how-to-hire-talent)
- [ ] [Recruitment process for a Google job (SRE, Site Reliability Engineer)](http://lambda-startup.com/recruitment-process-for-a-google-job-sre-site-reliability-engineer)

### 面试问题

- [ ] [A collection of questions to practice with for SRE interviews](https://github.com/michael-kehoe/sre-interview)
- [ ] [SRE Interview Questions](https://syedali.net/engineer-interview-questions)
- [ ] [Sysadmin Test Questions](https://github.com/trimstray/test-your-sysadmin-skills)
- [ ] [Kubernetes job interview questions](https://enterprisersproject.com/article/2019/2/kubernetes-job-interview-questions-how-prepare)
- [ ] [DevOps Guide](https://github.com/Tikam02/DevOps-Guide)
- [ ] [Questions I ask in SRE interviews](https://dev.to/logan/questions-i-ask-in-sre-interviews-a9j)
- [ ] [DevOps Roadmap: Learn to become a DevOps Engineer or SRE](https://roadmap.sh/devops)

### 博客文章

- [ ] [SRE Interviews in Silicon Valley](http://blog.marc-seeger.de/2015/05/01/sre-interviews-in-silicon-valley)
- [ ] [Preparing the SRE interview](https://blog.balthazar-rouberol.com/preparing-the-sre-interview)
- [ ] [How to Get Into SRE](https://blog.alicegoldfuss.com/how-to-get-into-sre)
- [ ] [My Job Interview at Google](https://catonmat.net/my-job-interview-at-google)
- [ ] [Path to Site Reliability Management](https://danrl.com/srm)
- [ ] [Becoming a Site Reliability Engineer](https://www.tik.dev/blog/becoming-an-sre)
- [ ] [How I get a job at Google as SRE](https://fabrizio2210.medium.com/how-i-get-a-job-at-google-as-sre-83d44aef7859)

## 书籍

### SRE

- [ ] [SRE：Google运维解密](https://book.douban.com/subject/26875239/)
- [ ] [Google SRE工作手册](https://book.douban.com/subject/35224058/)
- [ ] [SRE运维之道](https://book.douban.com/subject/35425841/)
- [ ] [Google系统架构解密](https://book.douban.com/subject/35585206/)
- [ ] [Implementing Service Level Objectives](https://book.douban.com/subject/34973920/)

### Linux

- [ ] [Linux内核设计与实现(原书第3版)](https://book.douban.com/subject/6097773/)
- [ ] [UNIX/Linux 系统管理技术手册](https://book.douban.com/subject/10747453/)
- [ ] [Linux口袋书](https://book.douban.com/subject/24736505/)

### 网络

- [ ] [TCP/IP详解 卷1：协议（原书第2版）](https://book.douban.com/subject/26825411/)

### 故障排除和性能

- [ ] [性能之巅：洞悉系统、企业与云计算](https://book.douban.com/subject/26586598/)
- [ ] [Systems Performance: Enterprise and the Cloud, Second Edition](https://book.douban.com/subject/35114639/)

## 课程(todo)

- [ ] [Site Reliability Engineering: Measuring and Managing Reliability](https://www.coursera.org/learn/site-reliability-engineering-slos)
- [ ] [School of SRE](https://linkedin.github.io/school-of-sre)
