# 介绍

Nest是构建高效，可扩展的 Node.js Web 应用程序的框架。 它使用现代的 JavaScript 或 TypeScript（保留与纯 JavaScript 的兼容性），并结合 OOP（面向对象编程），FP（函数式编程）和FRP（函数响应式编程）的元素。。

# 设计哲学

近几年，由于 Node.js，JavaScript 已经成为 Web 前端和后端应用程序的“通用语言”，并且有了 Angular，React 和 Vue 等令人耳目一新的项目，提高了开发人员的生产力，使得可以快速构建可测试的且可扩展的前端应用程序。 然而，在服务器端，虽然有很多优秀的库、helper 和 Node 工具，但是它们都没有有效地解决主要问题 - 架构。

Nest 旨在提供一个开箱即用的应用程序体系结构，允许轻松创建高度可测试，可扩展，松散耦合且易于维护的应用程序。

## [查看 8.0 文档](/8/)

### 中文交流QQ群：     
一群：277386223 （禁止闲聊.禁止广告）     
二群：1031015552 （禁止广告）


### 微信群：

微信三群：    

![](https://pic.imgdb.cn/item/61b6f7222ab3f51d913f49e7.jpg)  


微信一二群 （由于超过100人，微信限制，请先添加好友）

![](https://pic2.superbed.cn/item/5dee088d1f8f59f4d6586014.jpg)    





## 推荐视频

[全栈之巅](https://space.bilibili.com/341919508)

## 相关书籍


[《深入浅出 Node.js》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVAhADURNdHDJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUCEANRE10cHUtCCUZrEBxaXRNvH35ib3U-fgBgdGh7BlguQw4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhAGFQBlGmsVBREAUBNcFgMXD1MTaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFO0kJHQoRUF0dW0FVQgIGGl9GUBEOVhhZFQAQBVFMDBdQIgVUGl8c)


[《狼书（卷1）：更了不起的 Node.js》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVARUEVxheHDJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUBFQRXGF4cHUtCCUZrUVprQBVNOmZnVHEGAQJuBFdvEEg5Uw4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhACFwRlGmsVBREAUBNcFwcVD1YeaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFOx5fRgVAVFcdDBEFQQIFE1gcB0UCBxkOQAUQBlVMC0FRIgVUGl8c)

[《狼书（卷2）：Node.js Web应用开发》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVARUHUBNYEzJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUBFQdQE1gTHUtCCUZrQkVJASYBWxFidkdcegVqYRRwXWQfZQ4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhACFwRlGmsVBREAUBNcEAETBlEYaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFO0xfQQITAVZPXBcAFwICS1sdVUABV05eQFcaB10YXRAEIgVUGl8c)

[《深入理解 TypeScript》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVARQDURxYEDJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUBFANRHFgQHUtCCUZraFBxBi8cWBxnR3EsRAVLUUQBMmRcZQ4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhACFwRlGmsVBREAUBNcEgsSAVcbaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFO0kOHAdGU1xIWUBXQQJTS1wdAhABVhJZHQoWD1UeDxMCIgVUGl8c)

[《前端serverless面向全栈的无服务器架构实战》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVABEGXBxfEjJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUAEQZcHF8SHUtCCUZrYF0SYUtIX3dgR0c2ExMQQhJhL0cAdQ4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhACFwRlGmsVBREAURpbFwUQD1ISaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFOxtbFgobB1NPDkUKEwIFHAlFBRVTBkkPEAcQAwEbWhBXIgVUGl8c)

[《JavaScript悟道》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVARsOVxhfHTJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUBGw5XGF8dHUtCCUZrcnx7Xx4SGxxhQHUdUhMWcEpVB1tbUw4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhAGFQBlGmsVBREAURpbEgYRAVYSaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFOx4JFgpADgBIDhYHEQIBH1tGV0UBVxIMRgtFDwAcDkIHIgVUGl8c)

[《Node.js设计模式》](https://union-click.jd.com/jdc?e=&p=JF8AALsDIgZlGmsXAxcDXBpZFzJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRcDFwNcGlkXHUtCCUZrXnhPWh5cLEVnaVdUBRNLQAhvUFMoQw4eN1QrWx0GFARUGVwWMiIHUisQewMiBmUbXBYFFgZVH14dBRUEZRxbHDISB1AbWRIHDgFTGl0VAxEHZStrFjIiN1UrWCVAfFIAHA8cA0YOUUsPHAdGAl0SWBYEEwcHGF1HBhBUBx5cJQATBlES)


[《Node.js 区块链开发》](https://union-click.jd.com/jdc?e=&p=JF8AAM4DIgZlGFwXARMOUR9bFTISD1UYUhAGEgRTHmtRXUpZCisCUEdTRV4FRU1HRltKQA4KUExbSxtTFQEbAlEbWBMHDV4QRwYlXRNTERxSSAJyf1J5X2B1WUYcTQdzYh4LZRprFQoWAVYaWRIBIjdVHGtUbBsBVx5cJQMiB1IYXBAKFQRcGlkUBSIAVRJrFQIXB1ccXgkEFAZTG1oWAiI3ZRhrJTISN1YrGXsBQA9dSQ8UBBUCVEheEgNGVAEdDBAHElACHwkTA0dSVytZFAMWDg)    

[《实现领域驱动设计》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVABIFVR5THDJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUAEgVVHlMcHUtCCUZrE31sADEbEBFien1QE11eAWVEFGAbQw4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhACFwRlGmsVBREAURpbEAcaB1MeaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFO0lSFANCA1xMUxELFQICSQkcUUAOVRlYQldHDgZOXBIDIgVUGl8c)

[《Node.js：来一打 C++ 扩展》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVARAOVB5aEDJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUBEA5UHloQHUtCCUZrYwFtUhNZHBBhWkdRRylKSVJYPGw_ZQ4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhACFwRlGmsVBREAUBNcEQsRBF0faxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFOxpZEQtGAlNPWR1VQQJcGA5GABYCVk5YFgFBBwZLUxNXIgVUGl8c)

[《JavaScript 权威指南》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVAxoBUB5ZEjJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUDGgFQHlkSHUtCCUZrSn1KXVdOJFBhEXFTfjNqUhFBDEclZQ4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhADFgRlGmsVBREAUBNcEwoXBFYZaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFO0taHAdAUlQTDEUKRQJRG1kcCxZXUBwPEwESDgVMWBUAIgVUGl8c)




数据库:    

[《PostgreSQL修炼之道：从小工到专家（第2版）》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVARQFUhhaFTJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUBFAVSGFoVHUtCCUZrYGtLXw9uLh1hb1s3WA8TX2ZfCGI9dQ4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhADFgRlGmsVBREAUBNcHAQTD1ceaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFOx9bRwYUUgFJWkJWEQICGAgdURsCBh9dQVdAAVVOWRFQIgVUGl8c)

[《MySQL必知必会》(](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVARsHXBNSFjJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUBGwdcE1IWHUtCCUZrfHVGRAMbA11nW0MRUgRoXmJCCmUwQw4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhAGFQBlGmsVBREAUBNcHQUTBVwYaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFOxIPQAsbAwUcWBUKFQJVSQlGA0FQUR0JFwIXUFUTWhUKIgVUGl8c)


[《MongoDB从入门到商业实战》](https://union-click.jd.com/jdc?e=&p=JF8AAMQDIgZlGmsVARYBXRpaFTJWWA1FBCVbV0IUWVALHEpCAUdETlcNVQtHRRUBFgFdGloVHUtCCUZrY1BvZR1cHnBgS1MiQSxOVUR-U0g5Uw4eN1QrWx0GFARUGVwWMiIHUisNewITBlQaWhACFwRlGmsVBREAUBNdFAAQB10SaxICGzdVG14VABUCSR1dFAQSBlYbayUyETdlK1slASJFOx1YEQcVBQIYCBNQGwIHTgtGURBXBR5eQFEQDwUfWkYFIgVUGl8c)





## 赞助商广告：

本站托管在： [vultr   （免费送 100 美金）](https://www.vultr.com/?ref=8967015-8H)  
  [RamNode - 3美元-100G 高防](https://clientarea.ramnode.com/aff.php?aff=3451)    
  [Onevps-不限流量](https://www.onevps.cloud/?aff=12238)    
  [JMS 搬瓦工官方的科学上网工具](https://justmysocks3.net/members/aff.php?aff=6423)    
  [【捐赠】](https://gitee.com/notadd/docs.nestjs.cn?donate=true)   

百度云加速：WEB 高防，CDN 加速  QQ：1256985886     
专业版：30节点 100G/天 10GDDOS 防护  1690元/年 （买一送一）    
商务版：40节点 500G/天 20GDDOS 防护  6990元/年 （买一送一）    
企业版：50节点 1T/天 30GDDOS 防护  24990元/年 （买一送一）     


[![vultr](https://www.vultr.com/media/banner_1.png)](https://www.vultr.com/?ref=7815855-4F)
