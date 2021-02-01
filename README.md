# weiyi151
基于B/S模式的初级程序员交流论坛的实现

# 基于B/S模式的初级程序员交流论坛的实现




#### 介绍
在校学习期间，自己从当初门外汉变成了一个懂一些电脑知识，熟悉了一些编程语言的IT菜鸟。学习的过程总是充满痛苦和艰辛的，是一条充满荆棘的忐忑道路。在刚刚接触编程语言的时候，往往会在开发环境配置的阶段就陷入了困境，学习开发的过程中，在课堂上学习的知识是远远不够的，大学的学习生活要靠自觉，而当我们离开了课堂的时候，一个专属于IT初级人员交流的平台则是为学生提供了一个很有意义的地方。
本交流论坛系统是根据国内知名CSDN平台的结构进行架构的，使用了MySQL数据库，在管理工具方面使用了Phpadmin对数据库进行管理，该系统通过Mybatis和数据库进行连接，可以方便对数据库的连接数据进行修改和迁移。在经过大量地对比和调研后，页面设计采用了UK框架技术，后台框架采用了MVC设计模式，使用了框架SpringMVC和Mybatis。另一方面采用了一些JavaScript插件技术，为操作人员和使用用户提供了不错的体验。
本项目主要应用论坛管理思想设计一套基于用户体验的全栈交流论坛系统，本系统融合了目前流行的Spring框架技术以及简约易用的UIkit技术，能够为当下的校内学生和小团体提供交流技术的平台，将理论和实践并行。

本系统将是一个专属于IT菜鸟的交流平台。一个初级菜鸟在遭受学习上的挫折时，可以敞开心扉尽情倾述的一个平台。在这个平台上，你可以提问所有的关于你在学习编程时所遇到的各种问题，当你的开发环境不会配置时，可以在上面找到答案。你可以在自己遇到问题解决之后，将解决问题的过程及方法，解决问题后的心得体会，分享给其他人，帮助其他需要帮助的人。这里不仅是一个知识分享，解决学习问题的平台，同时也要做初级程序员心灵上的港湾。平台可以交流一些就业，求职的经验，和一些地区的工作环境，薪资水平。最重要的一点是对一些不良企业以及存在欺骗行为的企业进行曝光。让走在求职道路上的新人们少走一些弯路。避免一些可以避免的心灵伤害。挽回一些本不必遭受的经济损失，净化我们这些对未来满怀期待的职场新人的求职道路。若将来有一天我的这个项目真的可以正式上线运营的话，我觉得不只是对我个人能力的一次升华，同时它也会成为一个对社会有积极向上作用的一个服务于大众，回报于大众具有良好社会意义的项目。





#### 项目说明
![输入图片说明](https://images.gitee.com/uploads/images/2021/0201/232204_4f51e1c4_8621591.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0201/232212_96e6220a_8621591.png "屏幕截图.png")

本系统工作原理如下说明：
（1）用户发送请求至 前端控制器DispatcherServlet。
（2）前端控制器DispatcherServlet收到请求后调用处理器映射器HandlerMapping。
（3）处理器映射器HandlerMapping根据请求的Url找到具体的处理器，生成处理器对象Handler及处理器拦截器HandlerIntercepter（如果有则生成）一并返回给前端控制器DispatcherServlet。
（4）前端控制器DispatcherServlet通过处理器适配器HandlerAdapter调用处理器Controller。
（5）执行处理器（Controller，也叫后端控制器）。
（6）处理器Controller执行完后返回ModelAnView。
（7）处理器映射器HandlerAdapter将处理器Controller执行返回的结果ModelAndView返回给前端控制器DispatcherServlet。
（8）前端控制器DispatcherServlet将ModelAnView传给视图解析器ViewResolver。
（9）视图解析器ViewResolver解析后返回具体的视图View。
（10）前端控制器DispatcherServlet对视图View进行渲染视图（即：将模型数据填充至视图中）。
（11）前端控制器DispatcherServlet响应用户。


#### 项目截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0201/232240_04a0aec8_8621591.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0201/232247_5f74f866_8621591.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0201/232254_8058cb9b_8621591.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0201/232304_3b3969a5_8621591.png "屏幕截图.png")

#### 求助热线


代码有任何问题可联系
联系Q：2762501186

                            
![输入图片说明](https://images.gitee.com/uploads/images/2020/1119/003728_cd598bb9_4865385.jpeg "微信.jpg")           

感谢Gitee！！  
觉得项目不错的给个Star谢谢大佬！！！
提供无偿review服务
