# J2EE
##J2EE
##MVC##
  MVC全名是Model View Controller，是模型(model)－视图(view)－控制器(controller)的缩写.MVC模式的目的是实现一种动态的程序设计，使后续对程序的修改和扩展简化，并且使程序某一部分的重复利用成为可能。除此之外，此模式通过对复杂度的简化，使程序结构更加直观。
	·	控制器（Controller）- 负责转发请求，对请求进行处理。
	·	视图（View） - 界面设计人员进行图形界面设计。
	·	模型（Model） - 程序员编写程序应有的功能（实现算法等等）、数据库专家进行数据管理和数据库设计(可以实现具体的功能)。

##Apache Struts 2##
  Struts1设计的第一目标就是使MVC模式应用于web程序设计。在过去10年，Struts在更好的web应用方面所做的工作是值得肯定的。在某些方面，Struts社区注意到这一框架的局限性，所以这个活跃的社区通过对MVC运行模式的重新理解并同时引入一些新的建筑学方面的设计理念后，新的Struts2框架结构更清晰，使用更灵活方便。
这一新的结构包含应用逻辑的横切面拦截器，基于注释的配置以减少和去除XML形式的配置文件，功能强大的表达式语言，支持可更改、可重用UI组件的基于微MVC的标签库。Struts2有两方面的技术优势，一是所有的Struts2应用程序都是基于client/server HTTP交换协议，The Java Servlet API揭示了Java Servlet只是Java API的一个很小子集，这样我们可以在业务逻辑部分使用功能强大的Java语言进行程序设计。
Struts 2提供了对MVC的一个清晰的实现，这一实现包含了很多参与对所以请求进行处理的关键组件，如：拦截器、OGNL表达式语言、堆栈。

Spring Framework
Spring Framework 是一个开源的Java／Java EE全功能栈（full-stack）的应用程序框架，以Apache许可证形式发布，也有.NET平台上的移植版本。该框架基于 Expert One-on-One Java EE Design and Development（ISBN 0-7645-4385-7）一书中的代码，最初由Rod Johnson和Juergen Hoeller等开发。Spring Framework提供了一个简易的开发方式，这种开发方式，将避免那些可能致使底层代码变得繁杂混乱的大量的属性文件和帮助类。框架的主要优势之一就是其分层架构，分层架构允许您选择使用哪一个组件，同时为 J2EE 应用程序开发提供集成的框架。
Spring 框架是一个分层架构，由 7 个定义良好的模块组成。Spring 模块构建在核心容器之上，核心容器定义了创建、配置和管理 bean 的方式。

Hibernate 
Hibernate是一个开放源代码的对象关系映射框架，它对JDBC进行了非常轻量级的对象封装，它将POJO与数据库表建立映射关系，是一个全自动的orm框架，hibernate可以自动生成SQL语句，自动执行，使得Java程序员可以随心所欲的使用对象编程思维来操纵数据库。 Hibernate可以应用在任何使用JDBC的场合，既可以在Java的客户端程序使用，也可以在Servlet/JSP的Web应用中使用，最具革命意义的是，Hibernate可以在应用EJB的J2EE架构中取代CMP，完成数据持久化的重任。
Hibernate框架简化了java应用程序与数据库交互的开发。 Hibernate是一个开源，轻量级的ORM(对象关系映射)工具。
ORM工具简化了数据创建，数据处理和数据访问。它是将对象映射到数据库中存储的数据(表)的编程技术。
