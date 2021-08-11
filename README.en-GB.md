# Web Security Study Notes

![](https://img.shields.io/github/stars/lylemi/learn-web-hacking.svg)
![](https://img.shields.io/github/forks/lylemi/learn-web-hacking.svg)
![](https://img.shields.io/github/issues/lylemi/learn-web-hacking.svg)
![](https://img.shields.io/github/license/lylemi/learn-web-hacking.svg)

### Introduction
---
While learning Web security, the author realised that the volume of content is vast, and in large part,scattered across many platforms and formats. Where there is no central reference material, learning the content becomes increasingly challenging. Therefore, after having a surface level understanding of Web security, I tried to organize and record some knowledge and ideas, and finally formed this project, hoping to provide some help to network security enthusiasts who are getting started. 

Before starting, one point that needs clarification is, what is Web security. A straightforward definition is, Web security is a series of security domains including websites, network applications, and network services. In other words, Web security focuses on the security of the application layer, especially the details related to the network. In short, the areas of interest for Web security are; the network protocol itself, the characteristics of network applications and corresponding security issues, along with the use of various tools. It is clear, these topics are rather fragmented and complex, so how should I learn? The author tries to answer this question with the way these notes are structured.

To better understand why the current Web security field is like this, and in what direction each research is developing, it is necessary to understand the development and the evolutionary history of Web application technology and network attacks and defenses. This is also the first part of the notes, recording and explaining the development and evolution of Web technology and basic knowledge in the security field.

Once a general understanding of the history of Web security development is developed, you can start to learn the basics of computer networks. This is the second part of this collection, which introduces some basic concepts of computer networking. Considering that there are many technical branches and rapid evolutions such as network databases and Web servers, this article only introduces network protocols and skips the part of network applications. In doing this, it should be relevant for various programming languages, web application frameworks, network services, while also providing some understanding of operating system characteristics.

After you have a foundational understanding, you can focus on some more detailed offensive and defensive content, such as the research of a certain vulnerability type, a certain language or the characteristics of an application and its corresponding security issues. This is the third part of this article. In this part, in the order of a regualar penetration test, a brief description of recon techniques, common web vulnerabilities, common languages and frameworks, intranet penetration techniques, etc. are given. You will usually come into contact with these topics when you start to learn penetration testing.

The fourth part returns to the topic of defense, describing from the perspective of a security team, threat intelligence and risk control, and also explains the more detailed technical content such as honeypots and traceability.

Finally, specific applications are included, focusing on the introduction and use of tools. This part recommends a list of some tools and resources, and also archives a part of the content that is not classified for the time being.

The author is only human, as such, it is inevitable that there will be some errors or incomplete sections within the notes. These are gradually being corrected and supplemented. If there are omissions or errors, readers are welcome to create [Issues](https://github.com/LyleMi/Learn-Web-Hacking/issues/new) or [PR's](https://github.com/LyleMi/Learn-Web-Hacking/pulls) I am very grateful for criticism and corrections.

In the process of writing notes, I referenced and extracted a lot of materials, and left corresponding links to the sources at the end of the article. I am very grateful to the authors of the origonal material for sharing. The online version of the notes can be found [here](https://websec.readthedocs.io).

### Contents
---

1. Introduction
    1. Evolution of Web Technology
    2. Evolution of Attack and Deffence Techniques
    3. Security Concept
2. Computer Networks and Protocols
    1. Network Foundations
    2. UDP Protocol
    3. TCP Protocol
    4. Routing Algorithms
    5. Domain Name System
    6. HTTP Standard
    7. HTTPS
    8. SSL/TLS
    9. IPsec
    10. Wi-Fi
3. Reconnaissance
    1. Overall network architecture
    2. Domain Information
    3. Port Information
    4. Site Information
    5. Search Engine Utilization
    6. Social Engineering
4. Common Vulnerabilities - attacks and mittigations
    1. SQL injection
    2. XSS
    3. CSRF
    4. SSRF
    5. Code Injection
    6. Directory Traversal
    7. File Download
    8. File Upload
    9. File Content
    10. XXE
    11. Template Injection
    12. Cross Path Injection
    13. Logic Flaws
    14. System Configuration
    15. Middleware
    16. Web Cache Spoofing
    17. HTTP request smuggling
5. Languages and Frameworks
    1. PHP
    2. Python
    3. Java
    4. JavaScript
    5. Golang
    6. Ruby
    7. ASP
    8. PowerShell
    9. Shell
6. Intranet Penetration
    1. Windows内网渗透
    2. Linux内网渗透
    3. 后门技术
    4. 综合技巧
    5. 参考链接
7. Deffensive technologies
    1. 团队建设
    2. 安全开发
    3. 威胁情报
    4. ATT&CK
    5. 风险控制
    6. 防御框架
    7. 加固检查
    8. 入侵检测
    9. 蜜罐技术
    10. RASP
    11. 应急响应
    12. 溯源分析
8. Authentication
    1. SSO
    2. JWT
    3. OAuth
    4. SAML
    5. Windows
    6. Kerberos
    7. NTLM 身份验证
9. Tools and Resources
    1. 推荐资源
    2. 相关论文
    3. 信息收集
    4. 社会工程学
    5. 模糊测试
    6. 漏洞利用
    7. 近源渗透
    8. Web持久化
    9. 横向移动
    10. 操作系统持久化
    11. 审计工具
    12. 防御
    13. 运维
    14. 其他
10. Quick Reference
    1. 爆破工具
    2. 下载工具
    3. 流量相关
    4. 嗅探工具
    5. SQLMap使用
11. Misc
    1. 代码审计
    2. WAF
    3. Unicode
    4. 拒绝服务攻击
    5. Docker
    6. APT
    7. 近源渗透

### Building locally
---

```bash
git clone https://github.com/LyleMi/Learn-Web-Hacking.git
cd Learn-Web-Hacking
pip install sphinx sphinx-rtd-theme
make html
```

### Contribution
---

If you have any questions, comments or suggestions, you are welcome to submit them in the form of an Issue or PR. They are greatly appreciated.

Thanks to the [contributors](https://github.com/LyleMi/Learn-Web-Hacking/graphs/contributors).

### License
---

The project is released under the CC0 1.0 license，see [here](https://github.com/LyleMi/Learn-Web-Hacking/blob/master/LICENSE) to browse the full text.

### Note
---

The contents of the notes are collected and organized from open source information, and are only for learning and communication reference. For the sake of public safety, some content is not included, please follow《[Cybersecurity Law of the People's Republic of China](http://www.npc.gov.cn/npc/xinwen/2016-11/07/content_2001605.htm)》，Do not perform any testing on unauthorized targets.
