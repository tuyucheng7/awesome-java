# Java生态资源大全

该项目汇总了Java生态圈中的各种框架、库、中间件，包括Web开发、大数据、桌面开发、机器学习、软件测试、物联网、Android、生物学等领域。

所有框架和库都是基于Java语言实现的，只有极少数是由Kotlin、Scala、Groovy等JVM系语言混合开发，并且也可以在Java中兼容使用。

## 目录

- [Web框架](#web-framework)
- [REST框架](#rest-framework)
- [微服务框架](#microservice-framework)
- [微服务工具](#microservice-tool)
- [持久层框架](#orm-framework)
- [脚手架](#scaffold)
- [单元测试](#unit-test)
- [断言库](#assertions)
- [Mock框架](#mocks)
- [Mock工具](#mocks-lib)
- [数据Mock](#mocks-data)
- [BDD框架](#bdd)
- [性能测试](#load)
- [属性测试](#propertytest)
- [其他测试库](#test-lib)
- [自动化框架](#automation-framework)
- [自动化工具](#automation-tool)
- [代码覆盖率](#coverage)
- [构建工具](#build)
- [开源JDK](#jdk)
- [JVM编程语言](#jvm)
- [Java IDE](#ide)
- [持续集成](#ci)
- [发布工具](#publish)
- [项目管理](#project-management)
- [云原生](#cloud-native)
- [容器化工具](#container)
- [云服务](#cloudservice)
- [APM监控工具](#apm)
- [分布式追踪](#distributed-tracing)
- [指标报告](#metrics)
- [注册中心](#registry)
- [容错库](#rate-limiting)
- [网关](#gateway)
- [性能分析](#profiler)
- [大数据框架](#bigdata)
- [大数据组件](#bigdatatool)
- [消息中间件](#message)
- [Kafka管理工具](#kafka-tool)
- [分布式组件](#distributed)
- [分布式锁](#distributed-lock)
- [分布式ID生成器](#distributed-id-generator)
- [搜索引擎](#search-engine)
- [图数据库](#graph-db)
- [嵌入式数据库](#embedded-db)
- [关系型数据库](#rdbms-db)
- [NoSQL数据库](#nosql-db)
- [数据库连接池](#db-conn)
- [中间件客户端](#mid-client)
- [HTTP客户端库](#httpclient)
- [RPC框架](#rpc)
- [响应式库](#reactive)
- [WebServer](#webserver)
- [WebSocket](#websocket)
- [游戏服务器](#gameserver)
- [IM服务器](#im)
- [JakartaEE产品](#jakartaee)
- [工具库](#utils)
- [依赖注入](#di)
- [AOP](#aop)
- [日志库](#log)
- [GraphQL](#graphql)
- [任务调度](#job)
- [配置库](#configuration)
- [业务流程管理](#bpm)
- [规则引擎](#ruleengine)
- [低代码平台](#lowcode)
- [ERP系统](#erp)
- [业务](#business)
- [支付](#pay)
- [API管理](#api-manage)
- [缓存库](#cache)
- [PDF库](#pdf)
- [Excel库](#excel)
- [CSV库](#csv)
- [XML库](#xml)
- [文件库](#file)
- [反射](#reflection)
- [杂项](#miscellaneous)
- [日期时间库](#datetime)
- [机器学习](#ml)
- [自然语言处理](#nlp)
- [深度学习](#dl)
- [遗传算法](#genetic)
- [人脸识别](#face)
- [专家系统](#expert-system)
- [数据科学](#science)
- [数学库](#math)
- [本体库](#ontology)
- [语义Web](#semantic)
- [生物信息学](#bioinformatics)
- [基因组学](#genomics)
- [医疗平台](#medical)
- [并发编程](#concurrency)
- [安全库](#security-lib)
- [身份认证](#authentication)
- [JWT](#jwt)
- [OAuth](#oauth)
- [加密](#encryption)
- [事务](#transaction)
- [模板引擎](#template-engine)
- [JSON库](#json)
- [Bean映射](#mapper)
- [CLI工具](#cli)
- [SSH工具](#ssh)
- [DNS&内网穿透](#dns)
- [Git工具](#git)
- [集合库](#collection)
- [函数式编程](#functional)
- [字节码操作](#bytecode)
- [图像处理](#image)
- [验证码](#captcha)
- [压缩](#compress)
- [爬虫](#crawler)
- [数据处理](#data)
- [注解处理器](#annotation-processor)
- [事件总线](#event-bus)
- [接口文档](#apidoc)
- [集群管理](#cluster-management)
- [代码分析](#code-analysis)
- [Maven插件](#maven)
- [Gradle插件](#gradle)
- [SDK](#sdk)
- [API](#api)
- [区块链](#blockchain)
- [以太坊](#ethereum)
- [比特币](#bitcoin)
- [物联网](#iot)
- [MQTT](#mqtt)
- [金融](#finance)
- [短信](#sms)
- [Spring生态](#spring)
- [Raft算法](#raft)
- [Paxos算法](#paxos)
- [CQRS框架](#cqrs)
- [DDD框架](#ddd)
- [软件工程](#architecture)
- [迁移工具](#migrate)
- [JSF框架](#jsf)
- [机器人](#bot)
- [安卓库](#android)
- [Swing库](#swing)
- [JavaFx库](#javafx-lib)
- [JavaFX样式库](#javafx-ui)
- [JavaFX图表库](#javafx-chart)
- [JavaFX小工具](#javafx-tool)
- [GUI程序](#gui)
- [数据库工具](#dbtool)
- [字节码工具](#classtool)
- [字节码混淆工具](#obfuscator)
- [游戏开发](#game-engine)
- [JVM代理](#agent)
- [编译器&插件](#compiler)
- [语言服务器](#lsp)
- [数据库驱动](#db-client)
- [Minecraft](#minecraft)
- [音视频处理](#video)
- [数据结构](#datastructure)
- [布隆过滤器](#bloom)
- [算法库](#algorithms)
- [原生开发库](#native)
- [硬件操作库](#hardware)
- [逆向工程](#reverse-engineering)
- [开源CMS](#cms)
- [网络库](#network)
- [状态机](#statemachine)
- [二维码生成器](#qrcode)
- [文件系统](#filesystem)
- [报表引擎](#report)
- [部署工具](#deploy)
- [地理空间](#geo)
- [序列化](#serialization)
- [IO操作](#ioutils)
- [邮件操作](#email)
- [RSS](#rss)
- [OSGI](#osgi)
- [校验](#validation)
- [词法解析](#ast)
- [形式验证](#formal-verification)
- [正则表达式](#regex)
- [代码生成器](#codegen)
- [目录服务](#ldap)

<h2 id="web-framework">Web框架</h2>

* [Spring MVC](https://github.com/spring-projects/spring-framework/tree/main/spring-webmvc)：Spring MVC是Spring生态中的Web框架。
* [Spring Boot](https://github.com/spring-projects/spring-boot)：用于快速开发Spring应用的脚手架框架。
* [Solon](https://gitee.com/noear/solon)：国产的轻量级Java Web框架。
* [Play](https://github.com/playframework/playframework)：Play框架结合了生产力和性能，可以轻松使用Java和Scala构建可扩展的Web应用程序。
* [Blade](https://github.com/lets-blade/blade)：国产的轻量级Web框架。
* [JFinal](https://github.com/jfinal/jfinal)：国产的Web、ORM框架。
* [Javalin](https://github.com/javalin/javalin)：简单而现代的Java和Kotlin Web框架。
* [Hilla](https://github.com/vaadin/hilla)：Java全栈框架，支持React和Lit/Web组件。
* [Ninja](https://github.com/ninjaframework/ninja)：Java的全栈Web框架。
* [SOFABoot](https://github.com/sofastack/sofa-boot)：蚂蚁开发的Spring Boot增强并与其完全兼容的框架，提供就绪性检查、类隔离等功能。
* [Grails](https://github.com/grails/grails-core)：Grails是一个用于使用Groovy编程语言构建Web应用程序的框架。
* [Vaadin](https://github.com/vaadin/framework)：Vaadin是用于现代Java Web应用程序的Java框架。
* [Jooby](https://github.com/jooby-project/jooby)：适用于Java和Kotlin的模块化Web框架。
* [Pippo](https://github.com/pippo-java/pippo)：Java开源的微型Web框架。
* [Spark](https://github.com/perwendel/spark)：一个简单的、富有表现力的Java Web框架。
* [Apache Wicket](https://github.com/apache/wicket)：基于组件的Java Web框架。
* [Rife2](https://github.com/rife2/rife2)：全栈、无声明框架，可使用现代Java快速轻松地创建Web应用程序。
* [Apache Tapestry](https://github.com/apache/tapestry-5)：Tapestry是一个面向组件的Java Web应用程序框架。
* [Ratpack](https://github.com/ratpack/ratpack)：一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [Google Web Toolkit](https://github.com/gwtproject/gwt)：快速构建和维护复杂但性能高的JavaScript前端应用程序的工具集，由Google开发。
* [Apache Struts](https://github.com/apache/struts)：Apache Struts框架是一个用于创建Java Web应用程序的免费开源解决方案。
* [JavaLite](https://github.com/javalite/javalite)：一系列工具的集合框架。
* [Vraptor4](https://github.com/caelum/vraptor4)：一个基于Action的Web MVC框架，构建于CDI之上，用于快速且可维护的Java开发。
* [Apache Cocoon](https://github.com/apache/cocoon)：Apache Cocoon是一个基于Spring的Web框架，围绕关注点分离和基于组件的开发概念构建。
* [Apache Turbine](https://github.com/apache/turbine-core)：Apache Turbine是一个基于Servlet的框架，可以快速构建Web应用程序。
* [Takes](https://github.com/yegor256/takes)：面向对象的Java Web框架，没有NULL、静态方法、注解和可变对象。
* [Firefly](https://github.com/hypercube1024/firefly)：Firefly是一个异步Web框架，用于快速开发高性能Web应用程序。
* [Cicada](https://github.com/TogetherOS/cicada)：基于Netty的快速、轻量级Web框架。
* [ZK](https://github.com/zkoss/zk)：ZK是一个高效的Java框架，用于构建企业Web和移动应用程序。
* [CUBA](https://github.com/cuba-platform/cuba)：CUBA平台是一个高级框架，用于快速开发具有丰富Web界面的企业应用程序。
* [Tiny](https://gitee.com/tinyframework/tiny)：企业级Java EE应用开发框架套件。

<h2 id="rest-framework">REST框架</h2>

* [Jersey](https://github.com/eclipse-ee4j/jersey)：Jersey是一个Eclipse基金会下的REST框架，提供JAX-RS等参考实现。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：一个非常简单的库，用于构建生产就绪的RESTful Web服务。
* [RESTEasy](https://github.com/resteasy/resteasy)：Jakarta RESTful Web服务规范的实现。
* [Bootique](https://github.com/bootique/bootique)：Bootique是一种最简单的Java启动器和集成技术，它旨在构建无容器的可运行Java应用程序。
* [Restx](https://github.com/restx/restx)：轻量级Java REST框架。
* [Restlet](https://github.com/restlet/restlet-framework-java)：Java REST API框架。
* [Rest.li](https://github.com/linkedin/rest.li)：LinkedIn开源的REST + JSON框架，用于使用动态发现和简单的异步API构建健壮、可扩展的服务架构。
* [Grumpyrest](https://github.com/MartinGeisse/grumpyrest)：没有注解/DI/响应式的Java REST框架。
* [Resty](https://github.com/Dreampie/Resty)：极简的REST框架。
* [Airlift](https://github.com/airlift/airlift)：Airlift是一个用Java构建REST服务的框架。
* [RestExpress](https://github.com/RestExpress/RestExpress)：用于快速创建可扩展、Containerless、RESTful微服务的极简Java框架。
* [Apache CXF](https://github.com/apache/cxf)： Apache CXF是一个开源框架，提供了用于方便地构建和开发Web Service的可靠基础架构。
* [Kilo](https://github.com/HTTP-RPC/Kilo)：Kilo是一个开源框架，用于在Java中创建和使用RESTful和类REST Web服务。
* [Crnk](https://github.com/crnk-project/crnk-framework)：Crnk是JSON API规范和建议的Java实现，旨在促进构建RESTful应用程序。
* [Apache Sling](https://sling.apache.org/)：Apache Sling是一个基于可扩展内容树的RESTful Web应用程序框架。
* [Spring HATEOAS](https://github.com/spring-projects/spring-hateoas)：支持实现超文本驱动的REST Web服务表示的库。
* [Apache Wink](https://wink.apache.org/)：Apache Wink是一个简单可靠的框架，用于构建RESTful Web服务。
* [Apache Olingo](https://olingo.apache.org/)：Apache Olingo是一个实现开放数据协议(OData)的Java和JavaScript库。
* [Rocket API](https://gitee.com/alenfive/rocket-api)：API敏捷开发框架，用于API接口功能的快速开发。

<h2 id="microservice-framework">微服务框架</h2>

* [Spring Cloud](https://spring.io/projects/spring-cloud)：Spring生态中的微服务框架。
* [Dubbo](https://github.com/apache/dubbo)：阿里开源的RPC和微服务框架。
* [Micronaut](https://github.com/micronaut-projects/micronaut-core)：JVM平台上的微服务框架，由GraalVM项目组维护。
* [Quarkus](https://github.com/quarkusio/quarkus)：云原生时代的Java微服务框架，由RedHat开发。
* [Helidon](https://github.com/helidon-io/helidon)：用于编写微服务的Java库，基于Java虚拟线程，由Oracle开发。
* [Spring Cloud Netflix](https://github.com/spring-cloud/spring-cloud-netflix)：Spring Cloud Netflix是Spring Cloud的子项目，提供了Netflix开源项目的整合。
* [Spring Cloud Alibaba](https://github.com/alibaba/spring-cloud-alibaba)：阿里开源的Spring Cloud框架，提供一站式的微服务应用开发解决方案。
* [Spring Cloud GCP](https://github.com/GoogleCloudPlatform/spring-cloud-gcp)：集成了Google云功能的Spring Cloud框架，由Google提供。
* [Spring Cloud Tencent](https://github.com/Tencent/spring-cloud-tencent)：Spring Cloud Tencent是腾讯提供的基于Spring Cloud的服务治理框架。
* [Spring Cloud Azure](https://github.com/microsoft/spring-cloud-azure)：Spring Cloud Azure是微软开发的Spring Cloud框架，提供Spring与Azure服务的无缝集成。
* [Spring Cloud AWS](https://github.com/awspring/spring-cloud-aws)：亚马逊提供的Spring Cloud框架。
* [Spring Cloud Huawei](https://github.com/huaweicloud/spring-cloud-huawei)：华为开源的使Spring Cloud开发微服务变得更加简单和高效的框架。
* [JHipster](https://github.com/jhipster/generator-jhipster)：JHipster是一个用于快速生成、开发和部署现代Web应用程序和微服务架构的开发平台。
* [Ktor](https://github.com/ktorio/ktor)：Ktor是一个Kotlin编写的用于创建微服务、Web应用程序等的异步框架。
* [MicroProfile](https://github.com/eclipse/microprofile)：MicroProfile是一个Eclipse基金会项目，用于将Jakarta EE等企业Java技术应用于分布式微服务体系结构并不断发展。
* [ServiceComb](https://github.com/apache/servicecomb-java-chassis)：ServiceComb是一个华为云开源的软件开发套件，用于快速开发Java微服务。
* [Kotless](https://github.com/JetBrains/kotless)：Kotlin开发的Serverless框架，由JetBrains开源。
* [Axon](https://github.com/AxonFramework/AxonFramework)：JVM上的演化消息驱动微服务框架。
* [Riposte](https://github.com/Nike-Inc/riposte)：Riposte是一个基于Netty的微服务框架，用于快速开发生产就绪的HTTP API，由Nike开源。
* [Lagom](https://github.com/lagom/lagom)：JVM平台上的响应式微服务框架。
* [Armeria](https://github.com/line/armeria)：适用于任何情况的首选微服务框架，来自Netty创始人。你可以利用你喜欢的技术构建任何类型的微服务，包括gRPC、Thrift、Kotlin、Retrofit、Reactive Stream、Spring Boot和Dropwizard。
* [Light-4j](https://github.com/networknt/light-4j)：快速、轻量级且更高效的微服务框架。
* [JClouds](https://github.com/apache/jclouds)：Apache jclouds是一个适用于Java平台的开源多云工具包，可让你自由地创建可跨云移植的应用程序，同时让你完全控制使用特定于云的功能。
* [Msf4j](https://github.com/wso2/msf4j)：适用于Java的WSO2微服务框架。
* [NutzBoot](https://github.com/nutzam/nutzboot)：可靠的企业级微服务框架，提供自动配置、嵌入式Web服务、分布式会话、服务治理、负载均衡、Hystrix、RPC等解决方案。
* [Piggy Metrics](https://github.com/sqshq/piggymetrics)：使用Spring Boot、Spring Cloud和Docker的微服务架构。
* [Jupiter](https://github.com/fengjiachun/Jupiter)：Jupiter是一款性能非常不错的，轻量级的分布式服务框架。
* [Ja-Micro](https://github.com/Sixt/ja-micro)：用于构建Java微服务的轻量级框架。
* [JBoot](https://github.com/yangfuhai/jboot)：JBoot是一个基于JFinal、Dubbo、Seata、Sentinel、ShardingSphere、Nacos等开发的国产框架。
* [Flower](https://github.com/zhihuili/flower)：Flower是一个构建在Akka上的响应式微服务框架。
* [Redkale](https://github.com/redkale/redkale)：Redkale是基于Java 11全新的微服务框架，包含HTTP、WebSocket、TCP/UDP、数据序列化、数据缓存、依赖注入等功能。
* [Mica](https://gitee.com/596392912/mica)：Spring Cloud微服务开发核心工具集。
* [Atmosphere](https://github.com/Atmosphere/atmosphere)：Atmosphere框架包含用于构建异步Web应用程序的客户端和服务器端组件。
* [Finatra](https://github.com/twitter/finatra)：Finatra是一个轻量级框架，用于在TwitterServer和Finagle之上构建快速、可测试的Scala应用程序，由Twitter开源。
* [Open Capacity Platform](https://gitee.com/dromara/open-capacity-platform)：OCP是基于Spring Cloud的企业级微服务框架(用户权限管理、配置中心管理、应用管理...)，其目标是帮助企业搭建一套类似百度能力开放平台的微服务框架，由dromara社区开源。

<h2 id="microservice-tool">微服务工具</h2>

* [Conductor](https://github.com/Netflix/conductor)：微服务编排引擎，由Netflix开源。
* [Apollo](https://github.com/spotify/apollo)：用于编写可组合微服务的Java库，由Spotify开源。
* [SiteWhere](https://github.com/sitewhere/sitewhere)：SiteWhere是一个工业级物联网开源应用支持平台，提供了基于多租户微服务的基础设施。
* [Microserver](https://github.com/aol/micro-server)：Microserver是一个Java 8原生、零配置、基于标准、久经考验的库，可通过标准Java主类运行Java REST微服务。
* [Eventuate-Tram](https://github.com/eventuate-tram/eventuate-tram-core)：Eventuate Tram是一个解决微服务架构中固有的分布式数据管理问题的平台。
* [Eventuate-Sagas](https://github.com/eventuate-tram/eventuate-tram-sagas)：Eventuate Sagas框架是使用JDBC/JPA和Spring Boot/Micronaut的Java微服务的Saga框架。
* [ActiveJ](https://github.com/activej/activej)：ActiveJ是一个从头开始构建的现代Java平台。
* [Mappedbus](https://github.com/caplogic/Mappedbus)：Mappedbus是一种用于利用共享内存的Java微服务的低延迟消息总线。
* [Abixen-Platform](https://github.com/abixen/abixen-platform)：Abixen平台是一个基于微服务的软件平台，用于构建企业应用程序，通过创建特定的微服务并通过提供的CMS集成来提供功能。
* [MicroStream](https://github.com/microstream-one/microstream)：微秒响应时间、超高吞吐量、最小延迟，创建超快速内存数据库应用程序和微服务。
* [MSEC](https://github.com/Tencent/MSEC)：由腾讯QQ团队开源，它是一个后端DEV & OPS引擎，包括RPC、名称查找、负载均衡、监控、发布和容量管理。
* [Moss](https://github.com/SpringCloud/Moss)：Spring Cloud体系的服务治理平台。
* [SwimOS](https://github.com/swimos/swim)：用于构建有状态微服务、流API和实时UI的全栈应用程序平台。
* [Conjure](https://github.com/palantir/conjure)：适用于浏览器和微服务的强类型HTTP/JSON API。
* [GreenLightning](https://github.com/oci-pronghorn/GreenLightning)：高性能微服务运行时。
* [Ribbon](https://github.com/Netflix/ribbon)：Ribbon是一个进程间通信(远程过程调用)库，具有内置的软件负载均衡器，由Netflix开源。
* [Jmix](https://github.com/jmix-framework/jmix)：Jmix是一组库和工具，用于加速Spring Boot以数据为中心的应用程序开发。
* [Mantis](https://github.com/Netflix/mantis)：该平台使开发人员可以轻松构建实时、经济高效、以运营为中心的应用程序。
* [Hollow](https://github.com/Netflix/hollow)：Hollow是一个Java库和工具集，用于将内存数据集从单个生产者传播到许多消费者，以实现高性能只读访问。
* [Apache Juneau](https://github.com/apache/juneau)：一个使用通用框架将POJO编组到各种内容类型的工具包，并可以使用非常少的代码创建复杂的自记录REST接口和微服务。
* [Magic API](https://gitee.com/ssssssss-team/magic-api)：Magic API是一个基于Java的接口快速开发框架，编写接口将通过Magic API提供的UI界面完成，自动映射为HTTP接口，无需定义Controller、Service、Dao、Mapper、XML、VO等Java对象即可完成常见的HTTP API接口开发。
* [UAVStack](https://github.com/uavorg/uavstack)：UAVStack是智能化服务技术栈，是研发运维一体化的解决方案。
* [Sermant](https://github.com/huaweicloud/Sermant)：一个基于Javaagent的无代理服务网格解决方案，由华为开源。
* [Apache Pekko](https://github.com/apache/incubator-pekko)：Apache Pekko是一个开源框架，用于构建并发、分布式、弹性的应用程序。

<h2 id="orm-framework">持久层框架</h2>

* [Hibernate](https://github.com/hibernate/hibernate-orm)：Java中最老牌的ORM框架。
* [Spring Data JPA](https://github.com/spring-projects/spring-data-jpa)：Spring生态中的JPA框架。
* [Mybatis](https://github.com/mybatis/mybatis-3)：Java的MyBatis SQL映射器框架。
* [Mybatis-Plus](https://github.com/baomidou/mybatis-plus)：国产Mybatis的封装框架。
* [Mybatis-Flex](https://github.com/mybatis-flex/mybatis-flex)：国产Mybatis封装框架。
* [Fluent-Mybatis](https://github.com/atool/fluent-mybatis)：国产Mybatis的封装框架。
* [Mapper](https://gitee.com/free/Mapper)：极其方便的使用Mybatis单表的增删改查工具。
* [APIJSON](https://github.com/Tencent/APIJSON)：腾讯开源的零代码、全功能、强安全ORM库。
* [EclipseLink](https://github.com/eclipse-ee4j/eclipselink)：Eclipse基金会下的JPA实现。
* [Apache Commons DbUtils](https://github.com/apache/commons-dbutils)：Apache Commons DbUtils包是一组用于简化JDBC开发的Java实用程序类。
* [greenDAO](https://github.com/greenrobot/greenDAO)：greenDAO是一个轻量且快速的Android ORM，可将对象映射到SQLite数据库。
* [OpenJPA](https://github.com/apache/openjpa)：Apache基金会下的JPA实现。
* [Blaze Persistence](https://github.com/Blazebit/blaze-persistence)：Blaze-Persistence是面向JPA提供程序的丰富Criteria API。
* [QueryDSL](https://github.com/querydsl/querydsl)：Querydsl是一个可以为多个后端(包括JPA、MongoDB和Java中的SQL)构建类型安全的类SQL查询的框架。
* [JOOQ](https://github.com/jOOQ/jOOQ)：jOOQ是一个内部DSL和源代码生成器，将SQL语言建模为类型安全的Java API，帮助编写更好的SQL。
* [Ebean](https://github.com/ebean-orm/ebean)：Ebean提供多个查询抽象级别ORM查询，与SQL、DTO查询、SqlQuery和JDBC混合。
* [ObjectiveSql](https://github.com/braisdom/ObjectiveSql)：ObjectiveSQL是一个基于ActiveRecord模式的Java ORM框架，它鼓励快速开发和清洁，最少的代码，以及约定优于配置。
* [JPA-Streamer](https://github.com/speedment/jpa-streamer)：JPAstreamer是一个轻量级库，用于将JPA查询表达为Java Stream。
* [Jdbi](https://github.com/jdbi/jdbi)：Jdbi旨在提供Java中方便的表数据访问；包括模板化SQL、参数化和强类型查询以及Stream集成。
* [ORMLite](https://github.com/j256/ormlite-core)：精简版Java ORM。
* [Reladomo](https://github.com/goldmansachs/reladomo)：Reladomo是Java的企业级对象关系映射框架。
* [Apache Cayenne](https://github.com/apache/cayenne)：Apache Cayenne是一个开源持久层框架，提供对象关系映射(ORM)和远程处理服务。
* [Doma](https://github.com/domaframework/doma)：适用于Java 8+的面向DAO的数据库映射框架。
* [Mapper](https://github.com/abel533/Mapper)：易于使用的Mybatis通用Mapper。
* [Jimmer](https://github.com/babyfish-ct/jimmer)：适用于Java和Kotlin的ORM框架。
* [JFinal](https://github.com/jfinal/jfinal)：国产的Web、ORM框架。
* [AnyLine](https://gitee.com/anyline/anyline)：基于Spring生态的D-ORM，兼容各种数据库、动态注册切换数据源、生成或执行DDL/DML。
* [Easy-Query](https://github.com/xuejmnet/easy-query)：Java/Kotlin高性能轻量级JDBC查询解决方案，支持分表，数据库支持主从。
* [Bee](https://github.com/automvc/bee)：Bee是一个人工智能、简单、高效的ORM框架，支持JDBC、Cassandra、Mongodb、Sharding。
* [Nutz](https://github.com/nutzam/nutz)：包含全功能的ORM、Web框架。
* [Bean Searcher](https://github.com/troyzhxu/bean-searcher)：专注于高级查询的只读ORM，天然支持连接表，并且避免DTO/VO转换，使得一行代码实现复杂查询成为可能。
* [Speedment](https://github.com/speedment/speedment)：Speedment是一个Stream ORM Java工具包和运行时。
* [Easy-ES](https://gitee.com/dromara/easy-es)：Easy-ES是一款简化ElasticSearch搜索引擎操作的开源框架。
* [Kundera](https://github.com/Impetus/kundera)：Kundera是一个带有JPA接口的“多语言对象映射器”。
* [Requery](https://github.com/requery/requery)：一个轻量级但功能强大的对象映射和SQL生成器，适用于Java/Kotlin/Android，支持RxJava和Java 8。
* [BeetlSQL](https://gitee.com/xiandafu/beetlsql)：简洁方便，功能强大的ORM工具。
* [Eclipse JNoSQL](https://github.com/eclipse/jnosql)：Eclipse JNoSQL是Jakarta NoSQL和Jakarta Data规范的兼容实现，可简化Java应用程序与NoSQL数据库的集成。
* [Eclipse Store](https://github.com/eclipse-store/store)：高性能Java原生持久层，部分存储和加载任何Java对象图或子图，摆脱重量级JPA。
* [Sql2o](https://github.com/aaberg/sql2o)：Sql2o是一个小型库，可以轻松地将SQL语句的结果转换为对象。
* [Morphia](https://github.com/MorphiaOrg/morphia)：基于Java的MongoDB对象-文档映射器。
* [Apache MetaModel](https://metamodel.apache.org/)：借助MetaModel，你可以获得许多不同数据存储类型的统一连接器和查询API。
* [Jinq](https://github.com/my2iu/Jinq)：Jinq为开发人员提供了一种用Java编写数据库查询的简单而自然的方法。
* [Permazen](https://github.com/permazen/permazen)：语言自然持久层。
* [Apache Gora](https://github.com/apache/gora)：Apache Gora框架提供内存数据模型和大数据持久化。Gora支持持久化列存储、键值存储、文档存储和RDBMS，并通过广泛的Apache Hadoop MapReduce、Apache Spark、Apache Flink和Apache Pig支持来分析数据。

<h2 id="scaffold">脚手架</h2>

* [Pig](https://gitee.com/log4j/pig)：基于Spring Boot 3.0、Spring Cloud 2022 & Alibaba、SAS OAuth2的微服务RBAC权限管理系统。
* [RuoYi](https://gitee.com/zhijiantianya/ruoyi-vue-pro)：基于Spring Boot + MyBatisPlus + Vue & Element实现的后台管理系统、微信小程序。
* [RuoYi Cloud](https://gitee.com/zhijiantianya/yudao-cloud)：基于Spring Cloud Alibaba、Gateway、Nacos、RocketMQ、Vue实现的后台管理系统 + 用户小程序。
* [Zheng](https://gitee.com/shuzheng/zheng)：基于Spring + Spring MVC+ Mybatis分布式敏捷开发系统架构，提供整套公共微服务模块。
* [Cloud Platform](https://gitee.com/geek_qi/cloud-platform)：Spring Cloud微服务化RBAC的管理平台。
* [SpringBlade](https://gitee.com/smallc/SpringBlade)：提供基于React和Vue的两个前端框架用于快速搭建企业级的SaaS多租户微服务平台。
* [JeeSpringCloud](https://gitee.com/JeeHuangBingGui/jeeSpringCloud)：基于Spring Boot 2.0的后台权限管理系统界面简洁美观敏捷开发系统架构。
* [Hope Boot](https://github.com/java-aodeng/hope-boot)：一款现代化的脚手架项目。
* [Spring Boot Plus](https://github.com/geekidea/spring-boot-plus)：Spring Boot Plus是一个简单易用、高速、高效、功能丰富的开源Spring Boot脚手架。
* [X-SpringBoot](https://github.com/yzcheng90/X-SpringBoot)：X-SpringBoot是一个轻量级的Java快速开发平台。
* [Lenosp](https://gitee.com/zzdevelop/lenosp)：lenosp是一个基于Spring Boot的脚手架。
* [SpringCloud](https://github.com/zhoutaoo/SpringCloud)：基于Spring Cloud 2.1的微服务开发脚手架。
* [Liugh](https://github.com/qq53182347/liugh-parent)：实现RESTful快速开发的后端脚手架。
* [ES](https://github.com/zhangkaitao/es)：Java EE项目开发脚手架。
* [BallCat](https://github.com/ballcat-projects/ballcat)：一个快速开发脚手架，快速搭建企业级后台管理系统，并提供多种便捷starter进行功能扩展。
* [Mall-Tiny](https://github.com/macrozheng/mall-tiny)：一款基于Spring Boot + MyBatisPlus的快速开发脚手架。
* [AgileBoot](https://github.com/valarchie/AgileBoot-Back-End)：规范易于二开的全栈基础快速开发脚手架。
* [Spring Boot API Project Seed](https://github.com/lihengming/spring-boot-api-project-seed)：一个基于Spring Boot、MyBatis的种子项目，用于快速构建中小型API、RESTful API项目。
* [Vole](https://github.com/gavenwangcn/vole)：Spring Cloud微服务商业脚手架。
* [SpringBoot_v2](https://gitee.com/bdj/SpringBoot_v2)：Spring Boot项目开发脚手架。
* [Slife](https://gitee.com/jamen/slife)：Spring Boot搭建的一个企业级快速开发脚手架。
* [Vhr](https://gitee.com/lenve/vhr)：Spring Boot + Vue前后端分离的人力资源管理项目，可做常规企业级应用脚手架。
* [Maozi](https://github.com/1095071913/maozi-cloud-parent)：基于Spring Cloud Alibaba、Dubbo二开封装。
* [JBone](https://github.com/417511458/jbone)：jbone基于Spring Cloud框架开发，旨在为中小企业提供稳定的微服务解决方案，为开发人员提供基础开发骨架。
* [HsWeb](https://github.com/hs-web/hsweb-framework)：一个基于Spring Boot开发，使用全响应式编程的企业级后台管理系统基础项目。
* [Source-Vue](https://gitee.com/open-source-byte/source-vue)：基于Spring Boot + Vue前后端分离的Java快速开发框架。
* [Pangu](https://gitee.com/pulanos/pangu-framework)：盘古开发框架是一套轻量稳健的工业级前、中、后台三维多端行业数字化赋能开发基座。
* [JavaFX-Falsework](https://gitee.com/lwdillon/fx-falsework)：基于JavaFX、Spring Boot开发的客户端与服务端系统开发脚手架。
* [XBoot](https://github.com/Exrick/xboot)：基于Spring Boot 2.x的一站式前后端分离快速开发平台。
* [X-SpringBoot](https://github.com/yzcheng90/X-SpringBoot)：一个轻量级的Java快速开发平台，能快速开发项目并交付。
* [RenRen Security](https://gitee.com/renrenio/renren-security)：采用Spring Boot、MyBatisPlus、Shiro、Vue 3、ElementPlus等框架开发的一套权限系统。
* [Snowy](https://gitee.com/xiaonuobase/snowy)：Snowy是国内首个国密前后端分离快速开发平台，集成国密加解密插件，软件层面完全符合等保测评要求，同时实现国产化机型、中间件、数据库适配。
* [FCat](https://gitee.com/softnetcat/FCat)：FCat项目是企业级基础功能框架，软件巢工作室出品。

<h2 id="test">测试</h2>

这里主要是一些测试框架和工具库，包括单元测试、集成测试、性能测试等。

<h4 id="unit-test">单元测试</h4>

* [JUnit 4](https://github.com/junit-team/junit4)：Java的单元测试框架。
* [JUnit 5](https://github.com/junit-team/junit5)：JUnit的全新版本框架。
* [TestNG](https://github.com/testng-team/testng)：TestNG测试框架。
* [Spock](https://github.com/spockframework/spock)：基于Groovy的测试框架，支持数据驱动、Mock等功能。
* [Robolectric](https://github.com/robolectric/robolectric)：一个Android的单元测试框架。
* [Kotest](https://github.com/kotest/kotest)：强大、优雅且灵活的Kotlin测试框架，具有额外的断言、属性测试和数据驱动测试功能。
* [TestFX](https://github.com/TestFX/TestFX)：用于JavaFX的单元测试框架。
* [ScalaTest](https://github.com/scalatest/scalatest)：面向Scala和Java开发人员的测试工具。
* [uTest](https://github.com/com-lihaoyi/utest)：用于Scala的测试框架。
* [MUnit](https://github.com/scalameta/munit)：具有可操作错误和可扩展API的Scala测试库。
* [Unitils](http://www.unitils.org/summary.html)：用于单元和集成测试的模块化测试库。

<h4 id="assertions">断言库</h4>

* [AssertJ](https://github.com/assertj/assertj)：AssertJ是一个提供易于使用的丰富类型断言的库。
* [AssertJ Android](https://github.com/square/assertj-android)：一组用于测试Android的AssertJ助手。
* [JsonAssert](https://github.com/skyscreamer/JSONassert)：用更少的代码编写JSON单元测试，非常适合测试REST接口。
* [Truth](https://github.com/google/truth)：Google出品的流式断言库。
* [Hamcrest](https://github.com/hamcrest/JavaHamcrest)：Hamcrest的Java版本。
* [Spotify Hamcrest](https://github.com/spotify/java-hamcrest)：使用有用的匹配器扩展Hamcrest的库。
* [BeanMatcher](https://github.com/orien/bean-matchers)：用于测试Java bean的Hamcrest匹配器。
* [Deepdive](https://github.com/jdlib/deepdive)：Java的流式断言库。
* [Fest](https://github.com/alexruiz/fest-assert-2.x)：流式断言库。
* [Expekt](https://github.com/winterbe/expekt): Kotlin的BDD断言库。
* [AssertJ-DB](https://github.com/assertj/assertj-db)：AssertJ-DB提供断言来测试数据库中的值。

<h4 id="mocks">Mock框架</h4>

* [Mockito](https://github.com/mockito/mockito)：Java中最热门的Mock框架。
* [PowerMock](https://github.com/powermock/powermock)：一个扩展Mockito的框架，支持Mock静态方法、构造函数、私有方法等。
* [Testable-Mock](https://github.com/alibaba/testable-mock)：Alibaba开发的Mock框架。
* [WireMock](https://github.com/wiremock/wiremock)：一个模拟HTTP服务的工具。
* [EasyMock](https://github.com/easymock/easymock)：一个比较古老的Mock库。
* [Mockk](https://github.com/mockk/mockk)：用于Kotlin的Mock框架。
* [ScalaMock](https://github.com/paulbutcher/ScalaMock)：原生Scala Mock框架。
* [MockServer](https://github.com/mock-server/mockserver)：MockServer可以轻松模拟通过HTTP或HTTPS与用Java、JavaScript和Ruby编写的客户端集成的任何系统。
* [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver)：用于测试HTTP客户端的可编写脚本的Web服务器。
* [Jukito](https://github.com/ArcBees/Jukito)：JUnit、Guice和Mockito的组合。
* [JMockit](https://github.com/jmockit/jmockit1)：用于集成测试、Mock、伪造和代码覆盖率的高级Java库。
* [MockBukkit](https://github.com/MockBukkit/MockBukkit)：MockBukkit是bukkit的Mock框架，可以轻松地对Bukkit插件进行单元测试。
* [Mock-Box](https://github.com/mock-box/mock-box)：Mock-Box是一个轻量级且功能强大的支持测试的Mock库。
* [Microcks](https://github.com/microcks/microcks)：用于模拟和测试API和微服务的Kubernetes原生工具。

<h4 id="mocks-lib">Mock工具</h4>

* [Moco](https://github.com/dreamhead/moco)：Moco是一个易于设置的存根框架。
* [RabbitMQ Mock](https://github.com/fridujo/rabbitmq-mock)：RabbitMQ的Mock库。
* [Flashback](https://github.com/linkedin/flashback)：Flashback旨在模拟HTTP和HTTPS资源(例如Web服务和REST API)以用于测试目的。
* [S3Mock](https://github.com/adobe/S3Mock)：AWS S3 API的简单Mock实现，可作为Docker镜像、TestContainer、JUnit 4 Rule、JUnit Jupiter扩展或TestNG监听器启动。
* [CastleMock](https://github.com/castlemock/castlemock)：CastleMock是一个Web应用程序，提供模拟RESTful API和SOAP Web Service的功能。
* [Restito](https://github.com/mkotsur/restito)：用于测试Rest客户端的Mock框架。
* [Mockrunner](https://github.com/mockrunner/mockrunner)：用于企业级应用程序的Mock工具。
* [DaggerMock](https://github.com/fabioCollini/DaggerMock)：用于轻松覆盖Dagger 2对象的JUnit Rule。
* [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP)：DeepfakeHTTP是一个使用HTTP转储作为响应源的Web服务器。
* [Embedded Redis](https://github.com/kstyrc/embedded-redis)：用于Java集成测试的Redis嵌入式服务器。
* [Embedded PostgreSQL](https://github.com/opentable/otj-pg-embedded)：用于测试的Java嵌入式PostgreSQL组件。
* [Database-Rider](https://github.com/database-rider/database-rider)：让数据库集成测试变得更简单的库。
* [GreenMail](https://github.com/greenmail-mail-test/greenmail)：GreenMail是一个邮件服务器Mock库，允许开发人员测试基于电子邮件的应用程序、服务或系统，而无需访问实时邮件服务器。
* [CassandraUnit](https://github.com/jsevellec/cassandra-unit)：CassandraUnit是一个Java实用程序测试工具，它可以用于测试使用Cassandra数据库后端创建的Java应用程序。
* [Embedded LDAP JUnit](https://github.com/zapodot/embedded-ldap-junit)：用于在JUnit测试中运行嵌入式LDAP服务器的JUnit Rule。
* [Hoverfly](https://github.com/SpectoLabs/hoverfly-java)：Hoverfly的本机绑定，Hoverfly是一个允许你模拟HTTP服务的代理。

<h4 id="mocks-data">数据Mock</h4>

* [Instancio](https://github.com/instancio/instancio)：为单元测试创建完全填充的对象的库。
* [Junit-Data-Provider](https://github.com/TNG/junit-dataprovider)：类似TestNG的JUnit数据提供者运行程序，具有许多附加功能。
* [DataFaker](https://github.com/datafaker-net/datafaker)：为JVM(Java、Kotlin、Groovy)生成测试数据的库。
* [Java Faker](https://github.com/DiUS/java-faker)：将流行的ruby faker gem带到Java。
* [MockNeat](https://github.com/nomemory/mockneat)：现代的测试数据生成库。
* [jfairy](https://github.com/Devskiller/jfairy)：Java测试数据生成器。
* [EasyRandom](https://github.com/j-easy/easy-random)：简单的随机Java beans/记录生成器。
* [Jmockdata](https://github.com/jsonzou/jmockdata)：生成随机Java数据的插件。
* [JMock](https://github.com/jmock-developers/jmock-library)：用于测试驱动开发的富有表现力的对象Mock库。
* [Burst](https://github.com/square/burst)：用于不同测试数据的单元测试库。
* [EasyModeling](https://github.com/easymodeling/easy-modeling)：EasyModeling是一个Java注解处理器，可生成随机填充的对象以供测试使用。
* [Beanmother](https://github.com/keepcosmos/beanmother)：用于将Java对象设置为测试数据的库。
* [Common-Random](https://github.com/yindz/common-random)：用于测试目的的简单易用随机数据生成器。
* [Fixture Factory](https://github.com/six2six/fixture-factory)：Fixture Factory是一个帮助开发人员快速构建和组织假对象以进行单元测试的工具。

<h4 id="bdd">BDD框架</h4>

* [Cucumber](https://github.com/cucumber/cucumber-jvm)：JVM上的Cucumber实现。
* [Karate](https://github.com/karatelabs/karate)：一个BDD框架，支持API测试、UI测试、Mock等。
* [Serenity](https://github.com/serenity-bdd/serenity-core)：Serenity BDD是一个测试自动化库，旨在使编写自动化验收测试变得更容易、更有趣。
* [Concordion](https://github.com/concordion/concordion)：Concordion是一个Java开源框架，可让你将需求的简单英语描述转变为自动化测试。它通常与示例需求说明(SbE)和行为驱动开发(BDD)流程一起使用。
* [YAKS](https://github.com/citrusframework/yaks)：YAKS是一个在Kubernetes上启用云原生BDD测试的平台。
* [JBehave](https://github.com/jbehave/jbehave-core)：JBehave是一个适用于Java和所有JVM语言Groovy、Kotlin、Ruby、Scala的BDD框架。
* [JGiven](https://github.com/TNG/JGiven)：用纯Java进行行为驱动开发的框架。
* [Chorus](https://github.com/Chorus-bdd/Chorus)：分布式系统的可执行规范。
* [Lambda Behave](https://github.com/RichardWarburton/lambda-behave)：Java 8的现代测试和行为规范框架。
* [Spectrum](https://github.com/greghaskins/spectrum)：适用于Java 8的BDD风格测试运行器。受Jasmine、RSpec和Cucumber启发。
* [Specs2](https://github.com/etorreborre/specs2)：Specs2是一个用于在Scala中编写可执行软件规范的库。
* [YatSpec](https://github.com/bodar/yatspec)：YatSpec是一个BDD测试框架，可以运行JUnit测试并生成人类可读的HTML报告。
* [SmartBDD](https://github.com/bit-smart-io/smart-bdd)：从Java代码创建交互式HTML文档/功能文件的BDD框架。
* [BDD-Security](https://github.com/iriusrisk/bdd-security)：BDD-Security是一个安全测试框架，它使用行为驱动开发概念来创建自我验证的安全规范。
* [Cluecumber](https://github.com/trivago/cluecumber)：用于从Cucumber BDD、Karate和其他框架生成的Cucumber兼容JSON文件创建聚合测试报告。

<h4 id="load">性能测试</h4>

* [Apache JMeter](https://github.com/apache/jmeter)：Apache出品的GUI形式的开源负载测试工具。
* [Ngrinder](https://github.com/naver/ngrinder)：企业级性能测试解决方案。
* [Gatling](https://github.com/gatling/gatling)：更现代的负载测试工具，以代码的方式编写测试用例。
* [JMH](https://github.com/openjdk/jmh)：JMH是一个Java工具，用于构建、运行和分析用Java和其他针对JVM的语言编写的宏观基准测试。
* [Criterium](https://github.com/hugoduncan/criterium)：使用Clojure编写的用于JVM的基准测试库。
* [JfrUnit](https://github.com/moditect/jfrunit)：用于断言JFR(JDK Flight Recorder)事件的JUnit扩展。
* [PerfCake](https://github.com/PerfCake/PerfCake)：轻量级通用性能测试框架。
* [OWASP Benchmark](https://github.com/OWASP-Benchmark/BenchmarkJava)：OWASP基准项目是一个Java测试套件，用于验证漏洞检测工具的速度和准确性。

<h4 id="propertytest">属性测试</h4>

* [JUnit Quickcheck](https://github.com/pholser/junit-quickcheck)：junit-quickcheck是一个支持在JUnit中编写和运行基于属性的测试的库。
* [Jqwik](https://github.com/jqwik-team/jqwik)：JUnit平台上基于属性的测试库。
* [ScalaCheck](https://github.com/typelevel/scalacheck)：ScalaCheck是一个用Scala编写的库，用于对Scala或Java程序进行基于属性的自动化测试。
* [QuickTheories](https://github.com/quicktheories/QuickTheories)：Java 8基于属性的测试。
* [jetCheck](https://github.com/JetBrains/jetCheck)：由JetBrains开源的基于属性的测试框架。
* [QuickPerf](https://github.com/quick-perf/quickperf)：QuickPerf是Java的一个测试库，用于快速评估和改进一些与性能相关的属性。

<h4 id="test-lib">其他测试库</h4>

* [Testcontainers](https://github.com/testcontainers/testcontainers-java)：一个用于在测试中启动Docker容器的库。
* [Rest Assured](https://github.com/rest-assured/rest-assured)：一个用于测试REST API的库。
* [ArchUnit](https://github.com/TNG/ArchUnit)：Java架构测试库，用于以纯Java指定和断言架构规则。
* [Pitest](https://github.com/hcoles/pitest)：最先进的JVM突变测试库。
* [Awaitility](https://github.com/awaitility/awaitility)：用于测试异步代码的库。
* [JsonUnit](https://github.com/lukas-krecan/JsonUnit)：用于在单元测试中比较JSON的库。
* [EqualsVerifier](https://github.com/jqno/equalsverifier)：EqualsVerifier可用于Java单元测试来验证equals和hashCode方法的约定是否得到满足。
* [Fixture Monkey](https://github.com/naver/fixture-monkey)：可以自动生成包括边缘情况的测试实例。
* [OpenTest4J](https://github.com/ota4j-team/opentest4j)：JVM开放测试联盟。
* [RandomizedTesting](https://github.com/randomizedtesting/randomizedtesting)：随机测试工具。
* [HtmlUnit](https://github.com/HtmlUnit/htmlunit)：HtmlUnit是用于Java程序的无GUI浏览器。
* [XmlUnit](https://github.com/xmlunit/xmlunit)：XMLUnit是一个支持以多种方式测试XML输出的库。
* [JUnit Pioneer](https://github.com/junit-pioneer/junit-pioneer)：JUnit 5扩展包，提供很多JUnit 5没有的Extension。
* [JUnitParams](https://github.com/Pragmatists/JUnitParams)：JUnit 4的参数化测试扩展。
* [System Rules](https://github.com/stefanbirkner/system-rules)：用于测试使用java.lang.System的代码的JUnit Rule集合。
* [System Lambda](https://github.com/stefanbirkner/system-lambda)：用于测试使用java.lang.System的代码的函数集合。
* [System Stubs](https://github.com/webcompere/system-stubs)：Java系统资源的测试替身。
* [Arquillian](https://github.com/arquillian/arquillian-core)：Arquillian提供了用于集成测试的组件模型，其中包括依赖注入和容器生命周期管理。
* [MicroShed](https://github.com/MicroShed/microshed-testing)：用于黑盒测试MicroProfile和Jakarta EE应用程序的测试框架。
* [JGotesting](https://github.com/tastapod/jgotesting)：受Go测试包启发的JUnit兼容测试工具。
* [Pact](https://github.com/pact-foundation/pact-jvm)：Pact的JVM版本，用于编写消费者驱动的契约测试。
* [Wasabi](https://github.com/intuit/wasabi)：A/B测试工具，不再处于开发状态。
* [EvoSuite](https://github.com/EvoSuite/evosuite)：自动生成Java类的JUnit测试套件。
* [JWebUnit](https://github.com/JWebUnit/jwebunit)：Java Web测试框架。
* [LogCaptor](https://github.com/Hakky54/log-captor)：LogCaptor是一个能够轻松捕获用于单元和集成测试目的的日志记录条目的库。
* [JUnit 5 FormattedSource](https://github.com/mikemybytes/junit5-formatted-source)：JUnit 5格式驱动的参数化测试。
* [SikuliRobot](https://github.com/rainmanwy/robotframework-SikuliLibrary)：Sikuli机器人框架库为Robot Framework提供关键字，可以通过Sikuli测试UI。
* [Docker Compose JUnit Rule](https://github.com/palantir/docker-compose-rule)：使用Docker Compose管理Docker容器的JUnit Rule。
* [NoSQLUnit](https://github.com/lordofthejars/nosql-unit)：NoSQLUnit是一个JUnit扩展，可用于编写NoSQL单元测试。
* [SQLancer](https://github.com/sqlancer/sqlancer)：SQLancer是一个自动测试数据库管理系统以发现其实现中的逻辑错误的工具。
* [AREX](https://github.com/arextest/arex-agent-java)：Arex是一个围绕利用现实世界数据(即数据库记录、服务负载、缓存项等)进行回归测试的非常简单的原则设计的框架。
* [Cucumber Reporting](https://github.com/damianszczepanik/cucumber-reporting)：这是一个Java报告发布器，主要用于在Jenkins构建服务器上发布Cucumber报告。
* [ACTS](https://github.com/sofastack/sofa-acts)：ACTS是一个基于数据模型驱动的白盒测试框架，由蚂蚁开源。
* [GraphicsFuzz](https://github.com/google/graphicsfuzz)：GraphicsFuzz是一组用于测试shader编译器的工具。
* [Firing Range](https://github.com/google/firing-range)：Firing Range是Web应用程序安全扫描器的测试台，为一系列漏洞提供综合、广泛的覆盖，由Google开源。
* [Jazzer](https://github.com/CodeIntelligenceTesting/jazzer)：Jazzer是由Code Intelligence开发的适用于JVM平台的覆盖率引导的进程内模糊器。它基于libFuzzer，并将许多由仪器驱动的突变功能引入JVM。
* [ConcurrentUnit](https://github.com/jhalterman/concurrentunit)：一个简单的、零依赖的工具包，用于测试多线程代码。
* [MutabilityDetector](https://github.com/MutabilityDetector/MutabilityDetector)：报告给定类的实例是否是不可变。

<h4 id="automation-framework">自动化框架</h4>

* [Selenium](https://github.com/SeleniumHQ/selenium)：浏览器自动化框架和生态系统。
* [Playwright](https://github.com/microsoft/playwright-java)：Java版本的Playwright测试和自动化库。
* [Selenide](https://github.com/selenide/selenide)：Selenium的封装，提供了更简洁的API。
* [WebDriverManager](https://github.com/bonigarcia/webdrivermanager)：Java中Selenium WebDriver的自动化驱动程序管理和其他辅助工具。
* [aShot](https://github.com/pazone/ashot)：WebDriver屏幕截图工具。
* [Allure](https://github.com/allure-framework/allure2)：一款灵活、轻量级的多语言测试报告工具。
* [FitNesse](https://github.com/unclebob/fitnesse)：一个验收测试工具。
* [Galen](https://github.com/galenframework/galen)：一个自动化的布局和页面响应测试框架。
* [FluentLenium](https://github.com/FluentLenium/FluentLenium)：FluentLenium是一个Web和移动自动化框架，它扩展了Selenium以编写可靠且有弹性的UI功能测试。
* [Citrus](https://github.com/citrusframework/citrus)：专注于消息集成的自动化集成测试框架。
* [SeLion](https://github.com/paypal/SeLion)：Paypal开源的自动化测试工具。
* [JDI-Light](https://github.com/jdi-testing/jdi-light)：Java中强大的UI自动化测试框架。
* [ZeroCode](https://github.com/authorjapps/zerocode)：社区开发的免费开源微服务API自动化和负载测试框架，使用JUnit核心运行器构建，适用于HTTP REST、SOAP、安全性、数据库、Kafka等。
* [Geb](https://github.com/geb/geb)：Geb是一种浏览器自动化解决方案，它汇集了WebDriver的强大功能、jQuery内容选择的优雅性、页面对象建模的稳健性以及Groovy语言的表现力。
* [QMetry](https://github.com/qmetry/qaf)：使用Selenium、WebDriver、TestNG和Java Jersey的Web、MobileWeb移动原生和Rest Web服务的质量自动化框架。
* [HBrowser](https://github.com/Osiris-Team/HBrowser)：无头/完整的Java浏览器，支持下载文件、使用Cookie、检索HTML和模拟真实用户输入。
* [Appium-Client](https://github.com/appium/java-client)：用于编写符合WebDriver协议的Appium测试的Java语言绑定。
* [Zalenium](https://github.com/zalando/zalenium)：灵活且可扩展的基于容器的Selenium Grid，具有视频录制、实时预览、基本身份验证和仪表板，由Zalando开源。

<h4 id="automation-tool">自动化工具</h4>

* [Testsigma](https://github.com/testsigmahq/testsigma)：Testsigma是一个开源、可扩展的测试自动化平台，开箱即用。使用简单的英语快速(快5倍)自动化Web、移动应用程序和API测试。
* [OpenTest](https://github.com/mcdcorp/opentest)：适用于Web应用程序、移动应用程序和API的开源测试自动化工具。
* [SoapUI](https://github.com/SmartBear/soapui)：免费、开源的跨平台API和Web Service功能测试解决方案。
* [MeterSphere](https://github.com/metersphere/metersphere)：MeterSphere是一站式开源持续测试平台，涵盖测试跟踪、接口测试、UI测试和性能测试等功能，全面兼容JMeter、Selenium等主流开源标准。
* [Sonic](https://github.com/SonicCloudOrg/sonic-agent)：Sonic是一个集远程控制调试和移动设备自动化测试于一体的平台，致力于为全球开发者和测试工程师创造更好的使用体验。
* [LuckyFrameWeb](https://gitee.com/seagull1985/LuckyFrameWeb)：LuckyFrame测试平台是一款免费开源的测试平台，最大的特点是全纬度覆盖了接口自动化、WEB UI自动化、APP自动化。
* [Carina](https://github.com/zebrunner/carina)：Carina自动化框架(TestNG)：Web、移动、API、DB等测试。
* [Webtau](https://github.com/testingisdocumenting/webtau)：WebTau(Web测试自动化)是一个测试API、命令行工具和一个用于编写单元、集成和端到端测试的框架。
* [Wisdom](https://github.com/wisdom-projects/rest-client)：测试REST API的自动化工具，可以生成精美的测试报告和REST API文档。
* [Vividus](https://github.com/vividus-framework/vividus)：VIVIDUS是一种测试自动化工具，为测试最流行的应用程序类型提供已实施的解决方案。
* [Cerberus](https://github.com/cerberustesting/cerberus-core)：Cerberus Test是一个低代码测试自动化平台，支持测试Web、iOS、Android和API(REST、SOAP和Kafka)应用程序。
* [SoloPi](https://github.com/alipay/SoloPi)：SoloPi是一个无线化、非侵入式的Android自动化工具，由阿里开源。
* [SHAFT](https://github.com/ShaftHQ/SHAFT_ENGINE)：SHAFT是一个统一的测试自动化引擎，由一流的框架提供支持，提供类似向导的语法来高效推动自动化、最大化你的投资回报率并最小化你的学习曲线。
* [AutoMeter](https://gitee.com/season-fan/autometer-api)：AutoMeter是一款针对分布式服务、微服务API做功能和性能一体化的自动化测试平台。
* [HydraLab](https://github.com/microsoft/HydraLab)：HydraLab是一个可以帮助利用现有的测试设备/机器轻松构建云测试平台的框架，由微软开源。
* [RESTClient](https://github.com/wiztools/rest-client)：RESTClient是一个用于测试RESTful Web服务的Java应用程序。

<h2 id="coverage">代码覆盖率</h2>

* [JaCoCo](https://github.com/jacoco/jacoco)：Java中使用最广泛的代码覆盖率库。
* [Clover](https://bitbucket.org/atlassian/clover)：Atlassian开源的Java和Groovy代码覆盖率工具。
* [Cobertura](https://github.com/cobertura/cobertura)：Cobertura是一个免费的Java代码覆盖率报告工具。
* [JCov](https://wiki.openjdk.org/display/CodeTools/jcov)：用于收集与测试套件的生产相关的质量指标，JCov的开放是为了促进在OpenJDK开发中验证回归测试的测试执行的实践。
* [JSCover](https://github.com/tntim96/JSCover)：JSCover是一个JavaScript代码覆盖率工具，可测量行、分支和函数覆盖率。
* [EMMA](https://emma.sourceforge.net/)：免费的Java代码覆盖率工具。
* [Codecov](https://about.codecov.io/)：Codecov与OpenClover、JaCoCo和JCov兼容，但它也支持其他语言的多种工具。
* [Parasoft JTest](https://www.parasoft.com/)：包括多种现代QA工具，允许测量代码覆盖率，并对其进行静态和动态分析，这是一款商业工具。

<h2 id="build">构建工具</h2>

* [Apache Maven](https://github.com/apache/maven)：使用最广泛的Java构建工具。
* [Mvnd](https://github.com/apache/maven-mvnd)：提供更快的Maven构建。
* [Gradle](https://github.com/gradle/gradle)：灵活，快速的Java、Android构建工具。
* [Apache Ant](https://github.com/apache/ant)：一个基于Java的古老构建工具。
* [Bazel](https://github.com/bazelbuild/bazel)：快速、多语言且可扩展的构建系统，由Google开发。
* [Buck](https://github.com/facebook/buck)：一个快速构建系统，鼓励在各种平台和语言上创建小型、可重用的模块，由Facebook开发。
* [SBT](https://github.com/sbt/sbt)：适用于Scala、Java的构建工具。
* [Mill](https://github.com/com-lihaoyi/mill)：Mill是一个现代化的构建工具，支持Scala和Java项目的构建和管理。
* [Apache Ivy](https://github.com/apache/ant-ivy)：Apache Ivy是一个用于管理项目依赖关系的工具，具有很高的灵活性和可配置性，并且与Apache Ant紧密集成。
* [Leiningen](https://github.com/technomancy/leiningen)：Leiningen是一种构建自动化和依赖管理工具，用于以Clojure编程语言编写的软件项目的简单配置。
* [Apache Archiva](https://github.com/apache/archiva)：Apache Archiva是一种可扩展的存储库管理软件，可帮助管理你自己的个人或企业范围的构建工件存储库。

<h2 id="jdk">开源JDK</h2>

* [Open JDK](https://github.com/openjdk/jdk)：Oracle开源的OpenJDK官方版本。
* [AWS Corretto](https://github.com/corretto/corretto-8)：亚马逊开源的JDK版本。
* [Eclipse Temurin](https://github.com/adoptium/temurin-build)：Eclipse基金会下的JDK版本。
* [Bellsoft Liberica](https://github.com/bell-sw/Liberica)：BellSoft开源的JDK版本。
* [GraalVM](https://github.com/oracle/graal)：Oracle开源的一个高性能JDK发行版，旨在加速用Java和其他JVM语言编写的应用程序的执行，并支持JavaScript、Ruby、Python和许多其他流行语言。
* [Microsoft JDK](https://github.com/microsoft/openjdk)：微软开源的JDK构建版本。
* [Azul Zulu](https://www.azul.com/zh-hans/core/)：Azul开源的JDK版本。
* [IBM Semeru](https://www.ibm.com/support/pages/java-sdk-downloads)：IBM开源的JDK版本。
* [Eclipse OpenJ9](https://github.com/eclipse-openj9/openj9)：适用于OpenJDK的Java虚拟机，针对占用空间小、启动快和高吞吐量进行了优化。
* [Redhat JDK](https://developers.redhat.com/products/openjdk/download)：Redhat开源的JDK版本。
* [JetBrains JDK](https://github.com/JetBrains/JetBrainsRuntime)：JetBrains开发的基于OpenJDK的运行时环境。
* [Alibaba Dragonwell](https://github.com/dragonwell-project/dragonwell8)：阿里开源的JDK版本。
* [Tencent Kona](https://github.com/Tencent/TencentKona-17)：腾讯开源的JDK版本。
* [Huawei bisheng](https://www.openeuler.org/zh/other/projects/bishengjdk/)：华为开源的JDK版本，代号毕昇。
* [Loongson JDK](https://github.com/loongson/jdk)：龙芯中科基于OpenJDK研制并发布的龙芯平台Java环境。
* [OpenLogic](https://www.openlogic.com/openjdk-downloads)：Openlogic开源的JDK版本。
* [SapMachine](https://github.com/SAP/SapMachine)：由SAP维护和支持的OpenJDK版本。
* [leJOS](https://lejos.sourceforge.io/)：乐高开发的JVM，基于leJOS开发的机器人曾经在国际空间站上运行，该VM很早就已经停止维护。
* [JamJVM](https://jamvm.sourceforge.net/)：一个比较小众的JVM。
* [Maxine VM](https://github.com/beehive-lab/Maxine-VM)：Java中的元循环VM。
* [Jikes RVM](https://github.com/JikesRVM/JikesRVM)：一个由Java开发的虚拟机，曾经为虚拟机技术前沿研究超过180篇出版物和36篇论文。
* [Duppio](https://github.com/plasma-umass/doppio)：一个兼容POSIX的运行时系统以及一个用TypeScript编写的JVM。

<h2 id="jvm">JVM编程语言</h2>

* [Java](https://www.oracle.com/java/)：Java是一种采用面向对象范式的通用编程语言。
* [Groovy](https://github.com/apache/groovy)：适用于JVM平台的强大的多方面编程语言。
* [kotlin](https://github.com/JetBrains/kotlin)：一种开源静态类型编程语言，由JetBrains和开源贡献者支持和开发。
* [Scala](https://github.com/scala/scala)：基于JVM平台的函数式语言。
* [Clojure](https://github.com/clojure/clojure)：Clojure是Lisp编程语言在Java平台上的现代、动态及函数式方言。
* [Jython](https://github.com/jython/jython)：用于Java平台的Python。
* [JRuby](https://github.com/jruby/jruby)：Ruby语言在JVM上的实现。
* [AviatorScript](https://github.com/killme2008/aviatorscript)：AviatorScript是一门高性能、轻量级寄宿于JVM(包括Android平台)之上的脚本语言。
* [Eta](https://github.com/typelead/eta)：Eta编程语言是Haskell的一种方言，运行在JVM上。
* [Flix](https://github.com/flix/flix)：Flix是一种静态类型函数式、命令式和逻辑编程语言。
* [Golo](https://github.com/eclipse-archived/golo-lang)：JVM的轻量级动态语言。
* [Rascal](https://github.com/usethesource/rascal)：Rascal元编程语言的核心实现，包含解释器、解析器生成器、解析器运行时。
* [JPHP](https://github.com/jphp-group/jphp)：JPHP是使用JVM的PHP的新实现，支持PHP语言(7.1+)的许多功能。
* [JGO](https://github.com/thomasmodeneis/jgo)：Golang的Java编译器和运行时环境。
* [LuaJ](https://github.com/luaj/luaj)：为JME和JSE编写的轻量级、快速、以Java为中心的Lua解释器。
* [Enkel](https://github.com/JakubDziworski/Enkel-JVM-language)： Enkel是一种运行在JVM上的简单编程语言。
* [Yeti](https://github.com/mth/yeti)：JVM的函数式编程语言。
* [Concurnas](https://github.com/Concurnas/Concurnas)：Concurnas是一种开源JVM编程语言，旨在构建可靠、可扩展、高性能的并发、分布式和并行系统。
* [Ioke](https://github.com/olabini/ioke)：Ioke是一种强类型、动态、基于原型的编程语言。
* [Fantom](https://github.com/fantom-lang/fantom)：Fantom是一种在JVM和现代Web浏览器上运行的可移植语言。
* [Ceylon](https://github.com/eclipse-archived/ceylon)：Ceylon是一种用于Java和JavaScript虚拟机的现代、模块化、静态类型编程语言。
* [Frege](https://github.com/Frege/frege)：Frege是JVM的Haskell，它将纯函数式编程引入了Java平台。
* [Xtend](https://github.com/eclipse/xtext-xtend)：Xtend是一种灵活且富有表现力的Java方言，可编译成可读的Java源代码。
* [Renjin](https://github.com/bedatadriven/renjin)：基于JVM的R语言解释器。
* [Ballerina](https://github.com/ballerina-platform/ballerina-lang)：Ballerina是一种静态类型、开源云原生编程语言，由WSO2开发和支持。
* [BeanShell](https://github.com/beanshell/beanshell)：BeanShell是一个小型、免费、可嵌入的Java源解释器，具有对象脚本语言功能。
* [Rhino](https://github.com/mozilla/rhino)：Rhino是完全用Java编写的JavaScript的开源实现。
* [Erjang](https://github.com/trifork/erjang)：基于JVM的Erlang VM。

<h2 id="ide">集成开发环境</h2>

* [IntelliJ IDEA](https://github.com/JetBrains/intellij-community)：Jetbrains开发的Java、Kotlin IDE。
* [Eclipse](https://github.com/eclipse-platform)：Eclipse下开源免费的Java IDE。
* [Visual Studio Code](https://code.visualstudio.com/)：微软开源的文本编辑器，也支持作为IDE开发Java。
* [Android Studio](https://developer.android.com/studio)：Google开发的Android开发IDE，基于Intellij引擎。
* [Apache NetBeans](https://github.com/apache/netbeans)：Apache下开源免费的Java IDE，最初由Oracle开发。
* [MyEclipse](https://www.genuitec.com/products/myeclipse/)：MyEclipse是一个基于Eclipse的商业Java IDE。
* [STS](https://github.com/spring-projects/sts4)：Spring官方出品的基于Eclipse的Java IDE。
* [JDeveloper](https://www.oracle.com/application-development/technologies/jdeveloper.html)：Oracle开发的Java IDE。
* [BlueJ](https://github.com/k-pet-group/BlueJ-Greenfoot)：专为初学者设计的免费Java开发环境。
* [JBuilder](https://borland-jbuilder.software.informer.com/)：Borland软件公司出品的Java集成编程环境，有不同功能程度的多个版本。
* [Consulo](https://github.com/consulo/consulo)：开源的可用于Java的IDE，基于Intellij引擎。
* [Greenfoot](https://www.greenfoot.org/home)：免费的Java集成开发环境。
* [DrJava](http://www.drjava.org/)：DrJava是一个简单、轻量级、交互式Java IDE。
* [RStudio](https://github.com/rstudio/rstudio)：RStudio是R编程语言的集成开发环境。
* [MPS](https://github.com/JetBrains/MPS)：JetBrains元编程系统。

<h2 id="ci">持续集成</h2>

* [Jenkins](https://github.com/jenkinsci/jenkins)：Jenkins是领先的开源自动化服务器，使用Java构建，提供超过2000个插件来支持几乎所有事情的自动化。
* [TeamCity](https://www.jetbrains.com/teamcity/)：JetBrain的持续集成解决方案，提供免费版本。
* [Bamboo](https://www.atlassian.com/software/bamboo)：Bamboo是一款持续集成构建服务器软件，Atlassian提供的商业软件，也有免费版本。
* [Go](https://github.com/gocd/gocd)：持续交付服务器，由ThoughtWork开源。
* [OneDev](https://github.com/theonedev/onedev)：具有CI/CD和看板的自托管Git服务器。
* [FlowCI](https://github.com/FlowCI/flow-core-x)：功能强大且用户友好的CI/CD服务器，具有高可用性、并行构建、代理扩展特点。
* [BlueKing](https://github.com/TencentBlueKing/bk-ci)：bk-ci是一个免费并开源的CI服务，可助你自动化构建-测试-发布工作流，持续、快速、高质量地交付你的产品，由腾讯开源。
* [Hudson](https://github.com/hudson/hudson-2.x)：持续集成服务器，Jenkins的前身。
* [BK-Job](https://github.com/TencentBlueKing/bk-job)：蓝鲸作业平台是一套运维基础操作管理系统，具备海量任务并发处理能力，由腾讯开源。
* [Apache Continuum](https://continuum.apache.org/)：Apache Continuum是一款企业级持续集成服务器，具有自动构建、发布管理、基于角色的安全性以及与流行构建工具和源代码控制管理系统集成等功能。

<h2 id="publish">发布工具</h2>

* [JitPack](https://github.com/jitpack/jitpack.io)：打包GitHub仓库的便捷工具，可根据需要构建Maven、Gradle项目，发布可立即使用的组件。
* [IzPack](https://github.com/izpack/izpack)：IzPack是一种广泛使用的工具，用于将Java平台上的应用程序打包为跨平台安装程序。
* [Launch4j](https://launch4j.sourceforge.net/)：Launch4j是一个跨平台工具，用于将作为jar分发的Java应用程序包装在轻量级Windows本机可执行文件中。
* [Packr](https://github.com/libgdx/packr/)：用于打包JAR、资源和JVM，以便在Windows、Linux和Mac OS X上分发。
* [Nexus](https://github.com/sonatype/nexus-public)：支持代理和缓存功能的二进制管理工具。
* [Bintray](https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/)：发布二进制文件版本控制工具，可以于Maven或Gradle一起配合使用，提供开源免费版本和几种商业收费版本。
* [Maven Central](https://central.sonatype.com/)：最大的二进制组件仓库，面向开源社区提供免费服务。
* [Cloudsmith](https://cloudsmith.io/)：完全托管的包管理SaaS，支持Maven/Gradle/SBT，并提供免费套餐。

<h2 id="project-management">项目管理</h2>

* [MyCollab](https://github.com/MyCollab/mycollab)：MyCollab是免费的开源项目管理软件。
* [GanttProject](https://github.com/bardsoftware/ganttproject)：GanttProject是一款免费的桌面项目管理应用程序。
* [Jira](https://www.atlassian.com/software/jira)：全球领先的跟踪和管理任务的商业软件开发工具。
* [Lavagna](https://github.com/digitalfondue/lavagna)：Lavagna是一款小型且易于使用的问题/项目跟踪软件。
* [Zerocrat](https://github.com/zerocracy/farm)：Zerocrat核心引擎。
* [Freeplane](https://github.com/freeplane/freeplane)：Freeplane是一款免费的开源软件应用程序，提供了一组用于思维导图和导航映射信息的工具。
* [Gerrit](https://github.com/GerritCodeReview/gerrit)：Gerrit是基于Git的项目的代码审查和项目管理工具，由Google开源。
* [Hawtio](https://github.com/hawtio/hawtio)：Hawtio是一个轻量级、模块化的Web控制台，用于管理Java应用程序，由IBM开源。
* [Copybara](https://github.com/google/copybara)：Copybara是Google内部使用的工具，用于在仓库之间转换和移动代码。
* [Kooteam](https://gitee.com/sinbo/kooteam)：Kooteam是一款轻量级的在线团队协作工具，提供各类文档工具、在线思维导图、在线流程图、项目管理、任务分发，知识库管理等工具。

<h2 id="cloud-native">云原生</h2>

* [Discovery](https://github.com/Nepxion/Discovery)：蓝绿灰度发布、路由、限流、熔断、降级、隔离、追踪、流量染色、故障转移、多活。
* [Spring Cloud Kubernetes](https://github.com/spring-cloud/spring-cloud-kubernetes)：Kubernetes与Spring Cloud Discovery客户端、配置等集成。
* [HummerRisk](https://github.com/chaitin/HummerRisk)：HummerRisk是云原生安全平台，包括混合云安全治理和云原生安全检测。
* [SREWorks](https://github.com/alibaba/SREWorks)：云原生数智运维平台。
* [Siddhi](https://github.com/siddhi-io/siddhi)：流处理和复杂事件处理引擎。
* [Apache EventMesh](https://github.com/apache/eventmesh)：EventMesh是新一代无服务器事件中间件，用于构建分布式事件驱动应用程序。
* [PolarDB-X](https://github.com/polardb/polardbx-sql)：PolarDB-X是一款云原生分布式SQL数据库，专为高并发、海量存储、复杂查询场景而设计，由阿里开源。
* [PacBot](https://github.com/tmobile/pacbot)：PacBot是一个用于云持续合规性监控、合规性报告和安全自动化的平台，由T-Mobile开源。
* [MQCloud](https://github.com/sohutv/mqcloud)：RocketMQ企业级一站式服务平台。
* [Scoold](https://github.com/Erudika/scoold)：Scoold是一个面向团队的问答和知识共享平台。
* [iTranswarp](https://github.com/michaelliao/itranswarp)：功能齐全的CMS，包括博客、wiki、讨论等。由Spring Boot提供支持的云原生应用程序。
* [LINSTOR](https://github.com/LINBIT/linstor-server)：适用于容器、云和虚拟化的高性能软件定义块存储，与Docker、Kubernetes、Openstack、Proxmox等完全集成。
* [Mendmix](https://github.com/dromara/mendmix)：Mendmix提供了数据库、缓存、消息中间件、分布式定时任务、安全框架、网关以及主流产商云服务快速集成能力。
* [Apache Submarine](https://github.com/apache/submarine)：Submarine是云原生机器学习平台。
* [DataSophon](https://github.com/datavane/datasophon)：致力于快速实现大数据云原生平台的部署、管理、监控和自动化运维，帮助你快速构建稳定、高效、弹性、可扩展的大数据云原生平台。
* [Kogito](https://github.com/kiegroup/kogito-runtimes)：Kogito是一种云原生业务自动化技术，用于构建云就绪的业务应用程序。
* [Strimzi](https://github.com/strimzi/strimzi-kafka-operator)：Strimzi提供了一种在Kubernetes或OpenShift上以各种部署配置运行Apache Kafka集群的方法，由RedHat开源。
* [OpenWMS.org](https://github.com/openwms/org.openwms)：开放式仓库管理系统。
* [JoyQueue](https://github.com/chubaostream/joyqueue)：具有高性能的云原生生产质量消息传递平台。
* [DataEase](https://gitee.com/fit2cloud-feizhiyun/DataEase)：DataEase是开源的数据可视化分析工具，帮助用户快速分析数据并洞察业务趋势，从而实现业务的改进与优化。
* [Micro-Integrator](https://github.com/wso2/micro-integrator)：云原生配置驱动的运行时，可帮助开发人员实现组合微服务。
* [Hazelcast-Kubernetes](https://github.com/hazelcast/hazelcast-kubernetes)：Hazelcast的Kubernetes发现。
* [Chaos](https://github.com/openmessaging/openchaos)：Chaos为供应商提出了一个统一的API，为在云原生环境中执行混沌工程原理的各个方面提供解决方案。
* [Smart-MQTT](https://gitee.com/smartboot/smart-mqtt)：一款开源的云原生分布式MQTT Broker服务器，支持海量物联网设备互联互通。
* [Firehose](https://github.com/raystack/firehose)：Firehose是一种可扩展、无代码、云原生服务，用于将实时流数据从Kafka加载到数据存储、数据湖和分析存储系统。
* [Dagger](https://github.com/raystack/dagger)：Dagger是一个易于使用、通过代码进行配置的云原生框架，构建在Apache Flink之上，用于实时流数据的状态处理。
* [Apache OpenWhisk](https://github.com/apache/openwhisk)：OpenWhisk是一个用于构建云应用程序的Serverless函数平台，由IBM开源。
* [EDDI](https://github.com/labsai/EDDI)：用于对话式AI API(例如ChatGPT)的提示和对话管理中间件。
* [GeoServer](https://github.com/geoserver/geoserver-cloud)：通过Docker化微服务在云中使用的GeoServer。
* [Infinispan](https://github.com/infinispan/infinispan)：Infinispan是一个开源数据网格平台和高度可扩展的NoSQL云数据存储。
* [Starwhale](https://github.com/star-whale/starwhale)：MLOps/LLMOps平台。
* [KalDB](https://github.com/slackhq/kaldb)：KalDB是一个用于日志、跟踪和审计数据的云原生搜索和分析引擎。
* [Teiid](https://github.com/teiid/teiid)：Teiid是一种数据虚拟化系统，允许应用程序使用来自多个异构数据存储的数据，由RedHat主导。
* [XAP](https://github.com/xap/xap)：分布式、高度可扩展的内存数据网格。
* [Spring Boot Istio](https://github.com/piomin/spring-boot-istio)：用于与Kubernetes上的Istio集成的Spring Boot库。
* [SimianArmy](https://github.com/Netflix/SimianArmy)：SimianArmy是一套工具，可让云保持最佳状态运行，由Netflix开源。
* [CloudSimPlus](https://github.com/cloudsimplus/cloudsimplus)：最先进的云计算框架，现代、功能齐全、易于使用、高度可扩展、更快和更准确用于云计算研究的Java 17+工具。
* [HoloInsight](https://github.com/traas-stack/holoinsight)：HoloInsight是一个云原生可观测平台，重点关注于实时日志分析和人工智能集成。
* [Syncany](https://github.com/syncany/syncany)：Syncany是一款云存储和文件共享应用程序，重点关注存储的安全性和抽象性。
* [Serverless Java container](https://github.com/awslabs/aws-serverless-java-container)：Serverless Java container让你可以在AWS Lambda中轻松运行使用Spring、Spring Boot、Apache Struts、Jersey或Spark等框架编写的Java应用程序。
* [Spring Cloud Function](https://github.com/spring-cloud/spring-cloud-function)：Spring Cloud Function是基于Spring Boot的函数计算框架。

<h2 id="container">容器化工具</h2>

* [Jib](https://github.com/GoogleContainerTools/jib)：Jib无需Docker守护进程即可为Java应用程序构建优化的Docker和OCI镜像，它可作为Maven和Gradle的插件以及Java库使用，由Google开源。
* [Dockerfile Maven](https://github.com/spotify/dockerfile-maven)：一组用于处理Dockerfile的Maven工具，由Spotify开源。
* [Docker Maven Plugin](https://github.com/spotify/docker-maven-plugin)：Docker的Maven插件，Spotify开源，该项目不再活跃。
* [Docker Java](https://github.com/docker-java/docker-java)：Java Docker API客户端。
* [Jenkins Kubernetes](https://github.com/jenkinsci/kubernetes-plugin)：用于在Kubernetes集群中运行动态代理的Jenkins插件。
* [Helios](https://github.com/spotify/helios)：Helios是一个Docker编排平台，用于跨整个服务器群部署和管理容器，由Spotify开源。
* [docker-maven-plugin](https://github.com/fabric8io/docker-maven-plugin)：用于运行和创建Docker镜像的Maven插件。
* [Spotify Docker Client](https://github.com/spotify/docker-client)：这是一个用Java编写的Docker客户端，之前被用于Spotify的许多关键生产系统，目前Spotify已不再维护该项目。
* [Terrakube](https://github.com/AzBuilder/terrakube)：开源Terraform自动化和协作软件。
* [Eclipse JKube](https://github.com/eclipse/jkube)：在Kubernetes上构建和部署Java应用程序。
* [Cattle](https://github.com/rancher/cattle)：Cattle是为Rancher提供支持的编排引擎，它的主要作用是元数据管理和外部系统的编排。
* [DotCi](https://github.com/groupon/DotCi)：为Jenkins带来TravisCI等云CI系统的构建配置的便捷性以及Docker运行时环境配置的便捷性。
* [Jenkins Docker](https://github.com/jenkinsci/docker-plugin)：该插件允许使用Docker将容器动态配置为Jenkins节点，它是Docker的Jenkins Cloud插件。
* [HyScale](https://github.com/hyscale/hyscale)：HyScale是基于K8s的以应用程序为中心的抽象框架。
* [Styx](https://github.com/spotify/styx)：Styx是一项用于触发Docker容器定期调用的服务。
* [Cryostat](https://github.com/cryostatio/cryostat)：容器原生JVM应用程序，充当其他容器化JVM的桥梁，并公开安全的API，用于从云工作负载中生成、分析和检索JFR数据。
* [Haven](https://github.com/codeabovelab/haven-platform)：Haven是一个开源Docker容器管理系统，它将容器、应用程序、集群、镜像和注册表管理集成在一处。
* [Docker Client](https://github.com/amihaiemil/docker-java-api)：另一个轻量级的Java Docker客户端库。
* [Kubernetes Java](https://github.com/kubernetes-client/java)：kubernetes的官方Java客户端库。
* [Kubernetes & OpenShift Client](https://github.com/fabric8io/kubernetes-client)：适用于Kubernetes和OpenShift的Java客户端。
* [OpsCloud4](https://github.com/ixrjog/opscloud4)：用于云上运维的工具，提供持续交付、多实例动态数据源、堡垒机等功能。
* [StackGres](https://github.com/ongres/stackgres)：StackGres是Kubernetes的全栈PostgreSQL发行版，打包到一个简单的部署单元中，拥有一组精心挑选和调整的周边PostgreSQL组件。
* [Kubernetes Operators](https://github.com/operator-framework/java-operator-sdk)：Java Operator SDK是一个生产就绪的框架，可以轻松地在Java中实现Kubernetes Operator。
* [Dekorate](https://github.com/dekorateio/dekorate)：用于生成Kubernetes相关清单的工具。
* [Jaeger Kubernetes](https://github.com/jaegertracing/jaeger-kubernetes)：Jaeger Operator提供了一个CLI，用于从Jaeger CR生成Kubernetes清单。
* [Pulumi Kubernetes](https://github.com/pulumi/pulumi-kubernetes)：Kubernetes的Pulumi资源提供程序，用于管理正在运行的集群中的API资源和工作负载。
* [Funktion](https://github.com/funktionio/funktion-connectors)：Funktion是一个基于Kubernetes的开源事件驱动的Lambda风格编程模型。
* [KubeHelper](https://github.com/KubeHelper/kubehelper)：通过Web界面简化了许多日常Kubernetes集群任务，搜索、分析、运行命令、cron作业、报告、过滤器、Git同步等等。
* [Kardio](https://github.com/tmobile/kardio)：Kardio是一个简单的工具，可以配置为在任何端点上执行运行状况检查，由T-Mobile开源。
* [OpenShift Java](https://github.com/openshift/openshift-restclient-java)：这是基于Kubernetes的OpenShift版本3架构的Java REST客户端。

<h2 id="cloudservice">云服务</h2>

* [Apache CloudStack](https://github.com/apache/cloudstack)：Apache CloudStack是一个开源基础设施即服务(IaaS)云计算平台。
* [ZStack](https://github.com/zstackio/zstack)：ZStack是开源IaaS软件，旨在实现数据中心自动化，通过API管理计算、存储和网络资源。
* [Gaia](https://github.com/gaia-app/gaia)：Gaia是一个用于Terraform模块和自助服务基础设施的Terraform UI。
* [CloudSim](https://github.com/Cloudslab/cloudsim)：云计算基础设施和服务的建模和仿真框架。
* [AWS SaaS Boost](https://github.com/awslabs/aws-saas-boost)：AWS SaaS Boost为组织提供即用型核心软件元素，以便在云中成功运行SaaS工作负载，由Amazon开源。
* [Wemirr](https://gitee.com/battcn/wemirr-platform)：优秀、简单的开源SaaS平台。
* [HZERO](https://gitee.com/open-hand/hzero)：基于微服务架构开源免费的企业级PaaS平台，由上海汉得公司开发。
* [J2PaaS](https://gitee.com/j2paas/j2paas-framework)：J2PaaS是吉鼎科技基于多年项目经验打造的开源PaaS开发工具。
* [Apache Stratos](https://github.com/apache/stratos)：Apache Stratos是一个高度可扩展的PaaS框架，可帮助运行Apache Tomcat、PHP和MySQL应用程序，并可扩展以支持所有主要云基础设施上的更多环境。
* [Eclipse Jemo](https://github.com/eclipse/jemo)：Eclipse Jemo旨在为基于JVM的语言提供真正的多云FaaS实现。
* [Eclipse Dirigible](https://github.com/eclipse/dirigible)：Eclipse Dirigible是一种高生产力PaaS，它提供了一个由预选执行引擎和内置Web开发工具组成的应用程序服务器，它也适合利用低代码/无代码技术来快速开发业务应用程序。

<h2 id="apm">APM监控工具</h2>

* [Apache SkyWalking](https://github.com/apache/skywalking)：Apache基金会下的应用程序性能监控系统，国产开源。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint)：采用Java语言编写的链路分析和应用性能监控系统，由韩国Naver研发团队开源。
* [Cat](https://github.com/dianping/cat)：服务端项目基础组件，可以提供系统丰富的性能指标、健康状况、实时告警等，由美团点评开源。
* [Matrix](https://github.com/Tencent/matrix)：Matrix是微信开发的插件式、非侵入式APM系统。
* [Hertzbeat](https://github.com/dromara/hertzbeat)：开源实时监控系统，具有自定义监控、高性能集群和无代理功能，由dromara社区开源。
* [ArgusAPM](https://github.com/Qihoo360/ArgusAPM)：360开源的线上移动性能检测平台。
* [Scouter](https://github.com/scouter-project/scouter)：开源APM工具。
* [Femas](https://github.com/TencentFemas/femas)：基于Java Agent的微服务治理平台，由腾讯开源。
* [Stagemonitor](https://github.com/stagemonitor/stagemonitor)：用于Java服务器应用程序性能监控的开源解决方案。
* [Glowroot](https://github.com/glowroot/glowroot)：易于使用，开销极低的Java APM。
* [BeeAPM](https://gitee.com/beetle082/bee-apm)：分布式跟踪和应用性能监控系统，基于Java Agent。
* [EasyAgent](https://github.com/megaease/easeagent)：Java系统的代理组件。
* [inspectIT](https://github.com/inspectIT/inspectIT)：inspectIT是领先的开源APM工具，用于分析Java应用程序。
* [Frostmourne](https://github.com/AutohomeCorp/frostmourne)：汽车之家经销商技术部监控系统的开源版本，用于帮助监控几乎所有数据库数据(包括Elasticsearch、Prometheus、SkyWalking、MySQL等等)。
* [Lightrun](https://lightrun.com/)：Lightrun是一个面向开发人员的可观察性工具。

<h2 id="distributed-tracing">分布式追踪</h2>

* [Zipkin](https://github.com/openzipkin/zipkin)：Zipkin是一个分布式追踪系统，由Twitter开源。
* [SOFATracer](https://github.com/sofastack/sofa-tracer)：SOFATracer是一个用于分布式系统调用跟踪的组件，由蚂蚁开源。
* [Brave](https://github.com/openzipkin/brave)：Brave是一个分布式跟踪基础库。
* [SkyEye](https://github.com/JThink/SkyEye)：对Java、Scala等运行于JVM的程序进行实时日志采集、索引和可视化，对系统进行进程级别的监控的工具。
* [Spring Cloud Sleuth](https://github.com/spring-cloud/spring-cloud-sleuth)：Spring Cloud Sleuth为分布式跟踪提供Spring Boot自动配置。
* [OpenCensus](https://github.com/census-instrumentation/opencensus-java)：统计数据收集和分布式跟踪框架。
* [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-java)：OpenTelemetry Java SDK。
* [Fiery](https://github.com/weiboad/fiery)：微博开源的APM应用程序性能管理工具。
* [DataDog](https://github.com/DataDog/dd-trace-java)：DadaDog分布式跟踪工具的Java客户端。
* [Wingtips](https://github.com/Nike-Inc/wingtips)：Wingtips是基于Google Dapper论文的Java分布式跟踪解决方案，由Nike开源。

<h2 id="metrics">指标报告</h2>

* [Dropwizard Metrics](https://github.com/dropwizard/metrics)：用于捕获JVM和应用程序级别的指标。
* [Prometheus Java](https://github.com/prometheus/client_java)：用于JVM应用程序的Prometheus检测库。
* [Servo](https://github.com/Netflix/servo)：Servo提供了一个简单的接口，用于在Java中公开和发布应用程序指标，由Netflix开源。
* [OpenMessaging Java](https://github.com/openmessaging/openmessaging-java)：Java的OpenMessaging运行时接口。
* [Oculus](https://github.com/etsy/oculus)：Etsy Kale系统的度量相关组件。
* [Metrics Spring](https://github.com/ryantenney/metrics-spring)：该项目将Dropwizard Metrics库与Spring集成，并提供XML和Java配置。
* [Spectator](https://github.com/Netflix/spectator)：用于记录维度时间序列的检测代码的简单库，由Netflix开源。
* [Micrometer](https://github.com/micrometer-metrics/micrometer)：最流行的可观察性工具的应用程序可观察性门面。
* [Dubbo Metrics](https://github.com/alibaba/metrics)：Metrics(原Alibaba Metrics)是阿里巴巴内部广泛使用的度量埋点基础类库。
* [Argus](https://github.com/salesforce/Argus)：Argus是一个时序监控和警报平台，它由离散服务组成，用于配置警报、摄取和转换指标和事件、发送通知、创建命名空间以及建立和实施策略和使用配额。
* [Keycloak Metrics](https://github.com/aerogear/keycloak-metrics-spi)：向Keycloak添加指标端点的SPI，端点返回可供Prometheus抓取的指标数据。
* [SOFALookout](https://github.com/sofastack/sofa-lookout)：SOFALookout是一个利用多维度的Metrics对目标系统进行度量和监控的项目。
* [PerfMon](https://github.com/undera/perfmon-agent)：用于访问远程计算机上的系统指标的代理应用程序。
* [InfluxDB Metrics](https://github.com/davidB/metrics-influxdb)：向InfluxDB服务器公布度量结果的指标报告器。
* [ElasticSearch Metrics](https://github.com/elastic/elasticsearch-metrics-reporter-java)：向ElasticSearch服务器公布度量结果的指标报告器
* [Hawkular](https://github.com/hawkular/hawkular-metrics)：基于Cassandra的时序指标引擎。
* [Spf4j](https://github.com/zolyfarkas/spf4j)：Java的简单性能框架。
* [Jmxtrans](https://github.com/jmxtrans/jmxtrans-agent)：基于Java代理的JMX指标导出器。

<h2 id="registry">注册中心</h2>

* [Nacos](https://github.com/alibaba/nacos)：一个易于使用的动态服务发现、配置和服务管理平台，用于构建云原生应用程序，由阿里开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：ZooKeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务。
* [Apollo](https://github.com/apolloconfig/apollo)：可靠的配置管理系统，适用于微服务配置管理场景，由携程开源。
* [Eureka](https://github.com/Netflix/eureka)：用于弹性中间层负载均衡和故障转移的AWS服务注册中心，Netflix开源。
* [Pantheon](https://github.com/ProgrammerAnthony/Pantheon)：分布式微服务注册中心。
* [Nomulus](https://github.com/google/nomulus)：Google App Engine上的顶级域名注册服务。
* [SOFARegistry](https://github.com/sofastack/sofa-registry)：SOFARegistry是由蚂蚁金服提供支持的生产级、低延迟、高可用性服务注册中心。
* [Flair-Registry](https://github.com/viz-centric/flair-registry)：Flair BI的服务发现。

<h2 id="rate-limiting">容错库</h2>

* [Sentinel](https://github.com/alibaba/Sentinel)：面向云原生微服务的高可用流控防护组件，由阿里开源。
* [Hystrix](https://github.com/Netflix/Hystrix)：Hystrix是一个延迟和容错库，可以防止级联故障，由Netflix开源。
* [Resilience4j](https://github.com/resilience4j/resilience4j)：Resilience4j是一个专为Java 8和函数式编程设计的容错库。
* [Bucket4j](https://github.com/bucket4j/bucket4j)：Bucket4j是一个基于令牌桶算法的Java限流库。
* [RateLimiter4j](https://github.com/wangzheng0822/ratelimiter4j)：Java限流库/框架。
* [Concurrency-Limits](https://github.com/Netflix/concurrency-limits)：实现并集成了从TCP拥塞控制到自动检测服务并发限制的概念，以便以最佳延迟实现最佳吞吐量。
* [RateLimitJ](https://github.com/mokies/ratelimitj)：用于速率限制的Java库，提供可扩展的存储和应用程序框架适配器，该项目不再活跃。
* [Fastbreak](https://github.com/Nike-Inc/fastbreak)：Fastbreak是一个简单但功能强大的断路器，本身支持Java 8 CompletableFuture，由Nike开源。
* [Token-Bucket](https://github.com/bbeck/token-bucket)：令牌桶限速算法。
* [RedisRateLimiter](https://github.com/tangaiyun/RedisRateLimiter)：基于Redis的API访问速率限制器。
* [Neural](https://gitee.com/yu120/neural)：提供分布式限流、降级、熔断、重试和隔离的容错特性。
* [Discovery](https://gitee.com/nepxion/Discovery)：蓝绿灰度发布、路由、限流、熔断、降级、隔离、追踪、流量染色、故障转移。
* [SnowJena](https://github.com/onblog/SnowJena)：基于令牌桶算法实现的分布式无锁限流框架。
* [Failsafe](https://github.com/failsafe-lib/failsafe)：Failsafe是一个轻量级、零依赖库，用于处理Java 8+中的故障，具有用于处理日常用例的简洁API和处理其他所有内容的灵活性。
* [SDS](https://github.com/didi/sds)：SDS是一个轻量级、简单、易用的限流、熔断、降级系统，由滴滴开源。
* [Spring Retry](https://github.com/spring-projects/spring-retry)：该项目为Spring应用程序提供声明式重试支持。
* [Guava Retry](https://github.com/rholder/guava-retrying)：这是Google Guava库的一个小扩展，允许为任意函数调用创建可配置的重试策略。
* [Async Retry](https://github.com/nurkiewicz/async-retry)：用于Java 7/8的异步重试库。
* [Retry4j](https://github.com/elennick/retry4j)：Retry4j是一个简单的Java库，可帮助重试瞬时故障情况或不可靠的代码，该项目不再维护。
* [Easy Retry](https://github.com/alibaba/easy-retry)：一种存储介质可扩展的持久化重试方案，由阿里开源。
* [Easy Retry](https://gitee.com/aizuda/easy-retry)：致力提高分布式业务系统一致性的分布式重试平台。
* [Retrieval](https://gitee.com/spjich/retrieval)：一个精简的Java重试组件，支持同步，异步，以及制定时间内重试。
* [Sisyphus](https://github.com/houbb/sisyphus)：支持过程式编程和注解编程的Java重试框架。

<h2 id="gateway">网关</h2>

* [Zuul](https://github.com/Netflix/zuul)：Zuul是一种网关服务，提供动态路由、监控、弹性、安全性等，由Netflix开源。
* [Apache ShenYu](https://github.com/apache/shenyu)：Apache ShenYu是一个Java原生API网关，用于服务代理、协议转换和API治理，由dromara社区创始人开源。
* [Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway)：基于Spring Boot构建的网关，提供路由等功能。
* [SMSSync](https://github.com/ushahidi/SMSSync)：适用于Android的SMS网关。
* [FizzGate](https://github.com/fizzgate/fizz-gateway-node)：FizzGate是一个基于Java开发的微服务聚合网关。
* [VX-API-Gateway](https://gitee.com/mirren/VX-API-Gateway)：VX-API-Gateway是基于Vert.x开发的API网关，是一个全异步、高性能、可扩展、轻量级的API网关。
* [Haafiz](https://github.com/ProgrammerAnthony/Haafiz)：基于Netty、Disruptor、etcd等技术实现的开源网关。
* [SIA-Gateway](https://github.com/siaorg/sia-gateway)：基于Spring Cloud微服务生态体系下开发的一个分布式微服务网关系统。
* [Stargate](https://github.com/stargate/stargate)：Stargate是部署在客户端应用程序和Cassandra数据库之间的数据网关。
* [Eclipse Kura](https://github.com/eclipse/kura)：基于OSGi的M2M服务网关应用程序框架。
* [Artio](https://github.com/real-logic/artio)：弹性高性能FIX和FIXP网关。
* [Choreo-Connect](https://github.com/wso2/product-microgateway)：Choreo Connect是一个云原生、开源且以开发人员为中心的API网关。
* [Liiklus](https://github.com/bsideup/liiklus)：基于事件的系统的响应式(RSocket/gRPC)网关。
* [IOTGate](https://gitee.com/willbeahero/IOTGate)：Java版基于Netty的物联网高并发智能网关。
* [Choreo Connect](https://github.com/wso2/product-microgateway)：Choreo Connect是一个云原生、开源且以开发人员为中心的API网关代理。
* [Membrane](https://github.com/membrane/api-gateway)：用Java编写的REST、OpenAPI、GraphQL和SOAP的API网关。

<h2 id="profiler">性能分析</h2>

* [VisualVM](https://github.com/oracle/visualvm)：VisualVM是一款一体化Java故障排除工具。
* [Arthas](https://arthas.aliyun.com/)：阿里巴巴开源的Java诊断工具。
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html)：商业分析器。
* [YourKit](https://www.yourkit.com/features/)：商业分析器。
* [AppDynamics](https://www.appdynamics.com/)：服务性能监控/管理工具。
* [Async-Profiler](https://github.com/async-profiler/async-profiler)：该项目是一个低开销的Java采样分析器，不会遇到安全点偏差问题。
* [JVM-Profiler](https://github.com/uber-common/jvm-profiler)：可以将指标发送到Kafka、控制台输出或自定义报告器的JVM Profiler，由Uber开源。
* [TProfiler](https://github.com/alibaba/TProfiler)：TProfiler是一个可以在生产环境长期使用的性能分析工具，由阿里开源。
* [NetBeans Profiler](https://github.com/apache/netbeans/tree/master/profiler)：Apache NetBeans的内置分析器。
* [Greys](https://github.com/oldmanpushcart/greys-anatomy)：Java诊断工具。
* [Bistoury](https://github.com/qunarcorp/bistoury)：Bistoury是去哪儿网开源的Java应用生产问题诊断工具，提供了一站式的问题诊断方案。
* [JMC](https://github.com/openjdk/jmc)：Oracle开源的一个生产时间分析和诊断工具套件。
* [GCToolkit](https://github.com/microsoft/gctoolkit)：GCToolkit是一组用于分析HotSpot Java垃圾回收(GC)日志文件的库，由微软开源。
* [JITWatch](https://github.com/AdoptOpenJDK/jitwatch)：Java HotSpot JIT编译器的日志分析器/可视化器。
* [jHiccup](https://github.com/giltene/jHiccup)：提供平台中JVM暂停的日志和记录。
* [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils)：用于延迟测量和报告的实用程序。
* [JOL](https://github.com/openjdk/jol)：JOL(Java对象布局)是用于分析JVM中对象布局的微型工具箱。
* [Sematext](https://github.com/sematext/sematext-agent-java)：全栈基础设施监控工具。
* [JMX-Exporter](https://github.com/prometheus/jmx_exporter)：通过HTTP公开JMX Bean供Prometheus使用的工具。
* [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler)：没有安全点样本偏差的JVM采样分析器。
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler)：使用StatsD和其他指标后端的简单JVM分析器。
* [SJK](https://github.com/aragozin/jvm-tools)：SJK是一个用于JVM诊断、故障排除和分析的命令行工具。
* [MyPerf4J](https://github.com/LinShunKang/MyPerf4J)：一个针对高并发、低延迟应用设计的高性能Java性能监控和统计工具。
* [Jvmtop](https://github.com/patric-r/jvmtop)：Java命令行监控工具，包括分析器。
* [GCeasy](https://gceasy.io/)：非常好用的在线分析GC日志的工具。
* [Aprof](https://github.com/devexperts/aprof)：Java内存分配分析器。
* [MySQL Performance Analyzer](https://github.com/yahoo/mysql_perf_analyzer)：MySQL性能分析器是一个用于MySQL性能监控和分析的开源项目，由Yahoo开源。
* [Sniffy](https://github.com/sniffy/sniffy)：Java的交互式分析器、测试和混沌工程工具。
* [JavaMelody](https://github.com/javamelody/javamelody)：JavaMelody的目标是监控QA和生产环境中的Java或Java EE应用程序。
* [FastThread](https://fastthread.io/)：Java线程转储分析器。
* [Automon](https://github.com/stevensouza/automon)：Automon将AOP(AspectJ)的强大功能与已使用的监视或日志记录工具相结合，以声明方式监视Java代码、JDK和第三方库。
* [Spring Boot Startup Report](https://github.com/maciejwalkowiak/spring-boot-startup-report)：Spring Boot启动报告库生成交互式Spring Boot应用程序启动报告，让你了解影响应用程序启动时间的因素，并可能有助于优化它。
* [Spring Startup Ananlyzer](https://github.com/linyimin0812/spring-startup-analyzer)：Spring Startup Analyzer生成交互式Spring应用程序启动报告，让你了解影响应用程序启动时间的因素并帮助优化它。
* [Eclipse Jifa](https://github.com/eclipse/jifa)：Eclipse Jifa是一个开源的Web端软件，用于更好地排除Java应用程序中出现的常见问题。
* [LeakCanary](https://github.com/square/leakcanary)：适用于Android和Java的内存泄漏检测库。
* [GCViewer](https://github.com/chewiebug/GCViewer)：GCViewer是一个小工具，可以可视化Sun/Oracle、IBM、HP和BEA Java虚拟机生成的详细GC输出。
* [XRebel](https://www.jrebel.com/products/xrebel)：用于Java Web应用程序的商业分析器。
* [Kamon](https://www.kamon.io/)：用于监视JVM上运行的应用程序的工具。
* [New Relic](https://newrelic.com/)：商业性能监视器。
* [SPM](https://sematext.com/spm/)：商业性能监视器，可为JVM应用程序提供分布式事务跟踪。

<h2 id="bigdata">大数据框架</h2>

* [Apache Hadoop](https://github.com/apache/hadoop)：Apache Hadoop软件库是一个框架，允许使用简单的编程模型跨计算机集群分布式处理大型数据集，由Yahoo开源。
* [Apache Flink](https://github.com/apache/flink)：Apache Flink是一个开源流处理框架，具有强大的流处理和批处理能力，由柏林工业大学发起的项目。
* [Apache Spark](https://github.com/apache/spark)：用于大规模数据处理的统一分析引擎，由加州大学柏克莱分校AMPLab开源。
* [Apache RocketMQ](https://github.com/apache/rocketmq)：云原生消息传递和流媒体平台，可以轻松构建事件驱动的应用程序，由阿里开源。
* [Apache Kafka](https://github.com/apache/kafka)：使用最广泛的分布式流平台，由LinkedIn开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：新一代云原生分布式消息流平台，由Yahoo开源。
* [Apache ShardingSphere](https://github.com/apache/shardingsphere)：分布式SQL事务和查询引擎，可在任何数据库上进行数据分片、扩展、加密等，由京东开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：ZooKeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、组服务，也是Google的Chubby的⼀个开源实现。
* [Apache Pig](https://github.com/apache/pig)：基于Hadoop的大规模数据分析平台，由Yahoo开源。
* [Apache Beam](https://github.com/apache/beam)：Apache Beam是用于批处理和流数据处理的统一编程模型，由Google开源。
* [Apache Storm](https://github.com/apache/storm)：Apache Storm是一个分布式实时计算系统，由Twitter开源。
* [Apache Cassandra](https://github.com/apache/cassandra)：Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache SeaTunnel](https://github.com/apache/seatunnel)：下一代超高性能、分布式、海量数据集成工具，由中国通信学会开源技术委员会发起的项目。
* [Apache Zeppelin](https://github.com/apache/zeppelin)：基于Web的笔记本，支持使用SQL、Scala等进行数据驱动、交互式数据分析和协作文档。
* [Apache Hive](https://github.com/apache/hive)：基于Hadoop的一个数据仓库工具，可以将结构化的数据文件映射为一张数据库表，并提供类SQL查询功能，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：Apache HBase是一个开源、分布式、版本化、面向列的存储，也是谷歌BigTable的开源实现。
* [Apache Iceberg](https://github.com/apache/iceberg)：Apache Iceberg是由Netflix开源的用于庞大分析数据集的开放表格式。
* [Apache Doris](https://github.com/apache/doris)：一个易于使用、高性能和统一的分析数据库，由百度开源。
* [Apache Hudi](https://github.com/apache/hudi)：新一代流式数据湖平台，由Uber开源。
* [Apache Calcite](https://github.com/apache/calcite)：Apache Calcite是一个动态数据管理框架。
* [Apache Nifi](https://github.com/apache/nifi)：Apache NiFi是一个易于使用、功能强大且可靠的系统，用于处理和分发数据，由美国国家安全局开源。
* [Apache Heron](https://github.com/apache/incubator-heron)：由Twitter开发的实时分析平台。
* [Apache Kylin](https://github.com/apache/kylin)：Apache Kylin是一个开源分布式分析引擎，由eBay贡献。
* [Apache Linkis](https://github.com/apache/linkis)：Apache Linkis是一种计算中间件，充当上层应用程序和底层引擎(例如Apache Spark、Apache Hive和Apache Flink)之间的层，由微众开源。
* [Apache Flume](https://github.com/apache/flume)：由Cloudera软件公司产出的可分布式日志收集系统。
* [Apache Geode](https://github.com/apache/geode)：Apache Geode是一个数据管理平台，可在广泛分布的云架构中提供对数据密集型应用程序的实时、一致的访问，由GemStone开源。
* [Apache Gobblin](https://github.com/apache/gobblin)：用于流数据和批处理数据生态系统的分布式大数据集成框架，由LinkedIn开源。
* [Apache Parquet](https://github.com/apache/parquet-mr)：Apache Parquet是Hadoop生态系统中的任何项目都可以使用的列式存储格式，由Twitter和Cloudera共同开源。
* [Apache Ambari](https://github.com/apache/ambari)：基于Web的工具，用于安装、配置、管理和监视Hadoop集群，由Hortonworks开源。
* [Apache Drill](https://github.com/apache/drill)：Apache Drill是一个用于自描述数据的分布式MPP查询层，Google Dremel的开源版本。
* [Apache Bookkeeper](https://github.com/apache/bookkeeper)：一种可扩展、容错和低延迟的存储服务，针对仅附加工作负载进行了优化，由雅虎研究院开发。
* [Apache Atlas](https://github.com/apache/atlas)：Apache Atlas框架是一组可扩展的核心基础治理服务-使企业能够有效地满足Hadoop内的合规性要求，并允许与整个企业数据生态系统集成，由Hortonworks开源。
* [Apache Paimon](https://github.com/apache/incubator-paimon)：Apache Paimon是一个流数据湖平台，支持高速数据摄取、变更数据跟踪和高效的实时分析。
* [Apache InLong](https://github.com/apache/inlong)：海量数据一站式全场景集成框架，由腾讯大数据团队开源。
* [Apache Accumulo](https://github.com/apache/accumulo)：Apache Accumulo是一种排序的分布式键/值存储，可提供强大、可扩展的数据存储和检索，由美国国家安全局开源。
* [Apache Phoenix](https://github.com/apache/phoenix)：Phoenix是一个Hbase的开源SQL引擎，由Salesforce开源。
* [Apache Oozie](https://github.com/apache/oozie)：基于工作流引擎的开源框架，是Hadoop平台的开源的工作流调度引擎，用来管理Hadoop作业，由Cloudera开源。
* [Apache Ozone](https://github.com/apache/ozone)：适用于Apache Hadoop的可扩展、冗余和分布式对象存储，由腾讯大数据团队开源。
* [Apache Celeborn](https://github.com/apache/incubator-celeborn)：Apache Celeborn是一种弹性且高性能的服务，用于洗牌和溢出数据，由阿里云开源。
* [Apache CarbonData](https://github.com/apache/carbondata)：高性能数据存储解决方案，由华为开源。
* [Apache Kyuubi](https://github.com/apache/kyuubi)：Apache Kyuubi是一个分布式多租户网关，用于在数据仓库和Lakehouse上提供无服务器SQL，由网易开源。
* [Piflow](https://github.com/cas-bigdatalab/piflow)：支持Spark的大数据流引擎，由科学大数据社区开源。
* [Hazelcast](https://github.com/hazelcast/hazelcast)：Hazelcast是一个实时流处理平台，可让你构建立即对数据采取操作的应用程序，由Hazelcast开源。
* [DataX](https://github.com/alibaba/DataX)：阿里开源的一个异构数据源离线同步工具。
* [Scio](https://github.com/spotify/scio)：适用于Apache Beam和Google Cloud Dataflow的Scala API，由Spotify开源。
* [Presto](https://github.com/prestodb/presto)：用于大数据的分布式SQL查询引擎，由Facebook开源。
* [Voldemort](https://github.com/voldemort/voldemort)：Voldemort是一个分布式键值存储系统，Amazon Dynamo的开源克隆。
* [HiBench](https://github.com/Intel-bigdata/HiBench)：HiBench是一个大数据基准测试套件，由Intel开源。
* [DataHub](https://github.com/datahub-project/datahub)：由LinkedIn的数据团队开源的一款提供元数据搜索与发现的工具。
* [Trino](https://github.com/trinodb/trino)：Trino是一个用于大数据的分布式SQL查询引擎，由Facebook开源。
* [Genie](https://github.com/Netflix/genie)：分布式大数据编排服务，由Netflix开源。
* [Venice](https://github.com/linkedin/venice)：Venice是一个衍生的数据存储平台，由LinkedIn开源。
* [DataWave](https://github.com/NationalSecurityAgency/datawave)：DataWave是一个基于Java的摄取和查询框架，它利用Apache Accumulo提供对数据的快速、安全访问，由美国国家安全局开源。
* [Taier](https://github.com/DTStack/Taier)：太二是一个提交、调度、运维、指标信息展示的大数据开发平台，由袋鼠云开源。
* [Ambrose](https://github.com/twitter-archive/ambrose)：数据工作流可视化和实时监控平台，由Twitter开源。
* [Apache Crunch](https://crunch.apache.org/)：提供用于编写、测试和运行MapReduce管道的框架，由Google开源。
* [Apache MRUnit](https://mrunit.apache.org/)：Apache MRUnit是由Cloudera公司开发的专门针对Hadoop中编写MapReduce单元测试的框架。

<h2 id="bigdatatool">大数据组件</h2>

* [Canal](https://github.com/alibaba/canal)：Canal是阿里开发的基于数据库增量日志解析，提供增量数据订阅&消费的中间件。
* [Otter](https://github.com/alibaba/otter)：Otter是阿里开源的一个分布式数据库同步系统，尤其是在跨机房数据库同步方面，有很强大的功能。
* [Flink CDC Connectors](https://github.com/ververica/flink-cdc-connectors)：CDC Connectors是Apache Flink的一组源连接器，使用变更数据捕获(CDC)从不同数据库中获取变更。
* [ChunJun](https://github.com/DTStack/chunjun)：基于Flink的批流统一打造的数据同步工具，可以实现各种异构数据源之间的数据同步和计算，由袋鼠云开源。
* [DataSphereStudio](https://github.com/WeBankFinTech/DataSphereStudio)：DataSphere Studio(简称DSS)是微众银行开发的一站式数据应用开发管理门户WeDataSphere。
* [Dinky](https://github.com/DataLinkDC/dinky)：Dinky是一个开箱即用的一站式实时计算平台，致力于统一流批处理、统一数据湖和数据仓库的构建和实践。
* [Quicksql](https://github.com/Qihoo360/Quicksql)：Quicksql是一款360开源的SQL查询产品，可用于特定数据存储查询或多个数据存储关联查询，它支持关系型数据库、非关系型数据库甚至不支持SQL的数据存储(如Elasticsearch、Druid)。
* [FlinkStreamSQL](https://github.com/DTStack/flinkStreamSQL)：基于开源的Flink，对其实时SQL进行扩展；主要实现了流与维表的join，支持原生Flink SQL所有的语法，由袋鼠云开源。
* [BitSail](https://github.com/bytedance/bitsail)：BitSail是一个分布式高性能数据集成引擎，支持批量、流式和增量场景，由字节开源。
* [AthenaX](https://github.com/uber-archive/AthenaX)：基于SQL的大规模流分析平台，由Uber开源。
* [TIS](https://github.com/datavane/tis)：支持基于Flink、DataX和Flink-CDC的敏捷DataOps，Chunjun具有Web-UI，由Datavane大数据组织开源。
* [Dr.Elephant](https://github.com/linkedin/dr-elephant)：Dr.Elephant是一款针对Apache Hadoop和Apache Spark的作业和流级性能监控和调优工具，由LinkedIn开源。
* [Kylo](https://github.com/Teradata/kylo)：Kylo是一个数据湖管理软件平台和框架，用于在Teradata、Apache Spark和/或Hadoop等大数据技术上实现可扩展的企业级数据湖，由Teradata开源。
* [CDAP](https://github.com/cdapio/cdap)：CDAP是一个面向Hadoop生态系统的集成开源应用程序开发平台，为开发人员提供数据和应用程序抽象，目前是Google云端项目。
* [Nessie](https://github.com/projectnessie/nessie)：Nessie是由Dremio团队开源的一个类似Git管理数据湖的系统方案。
* [EGADS](https://github.com/yahoo/egads)：一个自动检测大规模时间序列数据异常的Java包，由Yahoo开源。
* [Yanagishima](https://github.com/yanagishima/yanagishima)：适用于Trino、Hive和SparkSQL的Web UI。
* [Apache Ambari](https://github.com/apache/ambari)：Apache Ambari是一个用于配置、管理和监控Apache Hadoop集群的工具，由一组RESTful API和一个基于浏览器的管理界面组成，由Hortonworks开源。
* [Elasticsearch Hadoop](https://github.com/elastic/elasticsearch-hadoop)：Elasticsearch实时搜索和分析与Hadoop原生集成，支持Map/Reduce、Apache Hive和Apache Spark。
* [XLearning](https://github.com/Qihoo360/XLearning)：XLearning是一个结合大数据和人工智能的便捷高效的调度平台，支持多种机器学习、深度学习框架，由360开源。
* [Addax](https://github.com/wgzhao/Addax)：Addax是一款多功能开源ETL工具，可以在各种RDBMS和NoSQL数据库之间无缝传输数据，使其成为数据迁移的理想解决方案，最初来源于阿里的DataX。
* [Amoro](https://github.com/NetEase/amoro)：Amoro是一个基于开放数据湖格式构建的Lakehouse管理系统，由网易开源。
* [Apache StreamPark](https://github.com/apache/incubator-streampark)：StreamPark是一个流处理开发框架和专业管理平台。
* [Firestorm](https://github.com/Tencent/Firestorm)：Firestorm是一项远程Shuffle服务，为Apache Spark和Apache Hadoop MapReduce应用程序提供在远程服务器上存储Shuffle数据的功能，由腾讯开源。
* [DataGear](https://gitee.com/datagear/datagear)：DataGear是一款开源免费的数据可视化分析平台，支持接入SQL、CSV、Excel、HTTP接口、JSON等多种数据源。
* [Yugong](https://github.com/alibaba/yugong)：阿里巴巴去Oracle数据迁移同步工具。
* [Debezium](https://github.com/debezium/debezium)：Debezium是一个开源项目，为变更数据捕获(CDC)提供低延迟数据流平台，由RedHat开源。
* [Cubert](https://github.com/LinkedInAttic/Cubert)：Cubert是一种快速高效的批量计算引擎，用于对Hadoop上的海量数据集进行复杂分析和报告，由LinkedIn开源。
* [Exchangis](https://github.com/WeBankFinTech/Exchangis)：Exchangis是微众银行大数据平台WeDataSphere与社区用户共同开发的新版数据交换工具，支持异构数据源之间结构化和非结构化数据的同步传输。
* [Apache ORC](https://github.com/apache/orc)：ORC是一种自描述、类型感知的列式文件格式，专为Hadoop工作负载而设计。它针对大型流读取进行了优化，但具有快速查找所需行的集成支持，由Hortonworks和Facebook联合开发。
* [Kettle](https://github.com/pentaho/pentaho-kettle)：一款开源的ETL工具，可以用它来对数据进行抽取、清洗和转换操作，主作者是Matt Casters。
* [Secor](https://github.com/pinterest/secor)：Secor是一项将Kafka日志持久保存到Amazon S3、Google Cloud Storage、Microsoft Azure Blob Storage和Openstack Swift的服务，由Pinterest开源。
* [DataBand](https://gitee.com/475660/databand)：轻量级一站式大数据分析平台。
* [Big Whale](https://gitee.com/meetyoucrop/big-whale)：巨鲸任务调度平台为美柚大数据研发的分布式计算任务调度系统，提供Spark、Flink等批处理任务的DAG调度和流处理任务的运行管理和状态监控，并具有Yarn应用管理、重复应用检测、大内存应用检测等功能。
* [Fili](https://github.com/yahoo/fili)：Fili是一个基于Java的框架，可以轻松构建和维护用于时序报告和分析的RESTful Web服务，由Yahoo开源。
* [Zebra](https://github.com/Meituan-Dianping/Zebra)：Zebra是一个基于JDBC API协议上开发出的高可用、高性能的数据库访问层解决方案，是美团点评内部使用的数据库访问层中间件。
* [Cobar](https://github.com/alibaba/cobar)：Cobar是分库分表的代理，兼容MySQL协议和MySQL SQL语法，底层存储仅支持MySQL，支持前台业务更简单、稳定、高效、安全，由阿里开源。
* [Qualitis](https://github.com/WeBankFinTech/Qualitis)：Qualitis是一个数据质量管理平台，支持各种数据源的质量验证、通知和管理，用于解决数据处理过程中引起的各种数据质量问题，由微众开源。
* [Mycat2](https://github.com/MyCATApache/Mycat2)：支持分布式SQL查询、兼容MySQL通信协议，以Java生态支持多种后端数据库，通过数据分片提高数据查询处理能力。
* [Oceanus](https://github.com/wuba/Oceanus)：58同城数据库中间件，功能简单、易于上手。
* [DBLE](https://github.com/actiontech/dble)：由爱可生开发的一种高扩展性的MySQL分片中间件。
* [Embulk](https://github.com/embulk/embulk)：Embulk是一个并行批量数据加载器，有助于在各种存储、数据库、NoSQL和云服务之间传输数据。
* [Stroom](https://github.com/gchq/stroom)：Stroom是一个数据处理、存储和分析平台，由英国政府通讯总部开源。
* [DnA](https://github.com/mercedes-benz/DnA)：为分析领域的企业提供A-Z解决方案，从计划和正在进行的活动的透明度到提供实现这些活动的开源组件，由奔驰开源。
* [IndexR](https://github.com/shunfei/indexr)：一种开源柱状数据格式，专为快速实时分析大数据而设计，由舜飞开源。
* [Elephant bird](https://github.com/twitter/elephant-bird)：Elephant Bird是Twitter的开源库，包含LZO、Thrift和/或Protocol Buffer相关的Hadoop InputFormats、OutputFormats、Writables、Pig LoadFuncs、Hive SerDe、HBase杂项等。
* [Priam](https://github.com/Netflix/Priam)：Cassandra的备份/恢复、令牌管理和集中配置管理的协同进程，由Netflix开源。
* [Variety](https://github.com/variety/variety)：MongoDB的模式分析器。
* [JStorm](https://github.com/alibaba/jstorm)：JStorm是一个分布式、容错的实时计算系统，受Apache Storm启发并由阿里重写开源。
* [DataFu](https://github.com/LinkedInAttic/datafu)：Apache DataFu是用于处理Hadoop中的大规模数据的库集合，由LinkedIn开源。
* [Apache Hama](http://hama.apache.org/)：Hama是一个高效且可扩展的通用BSP计算引擎。
* [Apache Tez](https://github.com/apache/tez)：Apache Tez是一个通用数据处理管道引擎，被设想为用于更高抽象的低级引擎，例如Apache Hadoop Map-Reduce、Apache Pig、Apache Hive等，由IBM和Adobe开发。
* [Apache Falcon](http://falcon.apache.org/)：Hadoop的数据管理和处理平台。
* [Apache Giraph](https://giraph.apache.org/)：Apache Giraph是一个专为高可扩展性而构建的迭代图形处理系统，Facebook基于Pregel思想的开源实现。
* [Marquez](https://github.com/MarquezProject/marquez)：Marquez是一种开源元数据服务，用于数据生态系统元数据的收集、聚合和可视化，由WeWork开源。
* [ODD](https://github.com/opendatadiscovery/odd-platform)：ODD是一款面向数据团队的开源数据发现和可观察性工具，有助于通过现代用户友好的环境有效实现数据民主化、增强协作并减少数据发现时间。
* [Egeria](https://github.com/odpi/egeria)：Egeria提供开放元数据和治理类型系统、框架、API、事件有效负载和交换协议，由IBM开源。
* [Cloudbreak](https://github.com/hortonworks/cloudbreak)：CDP公共云是部署在云服务上的集成分析和数据管理平台，它提供广泛的数据分析和人工智能功能以及安全的用户访问和数据治理功能，由Hortonworks开源。
* [BigQuery Data Lineage](https://github.com/GoogleCloudPlatform/bigquery-data-lineage)：使用审核日志、ZetaSQL和Dataflow对BigQuery进行实时数据沿袭跟踪的参考实现，由Google开源。
* [Vespa](https://github.com/vespa-engine/vespa)：Yahoo开源的大数据服务引擎，在服务时存储、搜索、组织大数据并进行机器学习推理。
* [Kafka REST Proxy](https://github.com/confluentinc/kafka-rest)：Kafka REST Proxy为Kafka集群提供RESTful接口，它可以轻松地生成和消费数据、查看集群状态以及执行管理操作，而无需使用本机Kafka协议或客户端，由Confluent开源。

<h2 id="message">消息中间件</h2>

* [Apache RocketMQ](https://github.com/apache/rocketmq)：云原生消息传递和流媒体平台，可以轻松构建事件驱动的应用程序，由阿里开源。
* [Apache Kafka](https://github.com/apache/kafka)：使用最广泛的分布式流平台，由领英开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：新一代云原生分布式消息流平台，由雅虎开源。
* [Apache ActiveMQ](https://github.com/apache/activemq)：一个比较传统的高性能消息代理。
* [BifroMQ](https://github.com/baidu/bifromq)：采用Serverless架构的MQTT代理实现，由百度开源。
* [QMQ](https://github.com/qunarcorp/qmq)：QMQ是去哪儿网内部广泛使用的消息中间件。
* [PMQ](https://github.com/ppdaicorp/pmq)：信也科技开源的轻量级分布式消息队列。
* [JeroMQ](https://github.com/zeromq/jeromq)：ZeroMQ的Java版本。
* [DDMQ](https://github.com/didi/DDMQ)：DDMQ是滴滴基础设施团队基于Apache RocketMQ打造的分布式消息产品。
* [JGroups](https://github.com/belaban/JGroups)：JGroups是一个集群库，允许成员交换消息。
* [Apache Camel](https://github.com/apache/camel)：能够快速轻松地集成使用或生成数据的各种系统的开源框架。
* [Chronicle-Queue](https://github.com/OpenHFT/Chronicle-Queue)：Chronicle Queue是一个适用于高性能应用程序的持久低延迟消息传递框架。
* [HornetQ](https://github.com/hornetq/hornetq)：HornetQ是一个开源项目，用于构建多协议、可嵌入、高性能、集群、异步消息传递系统。
* [XXL-MQ](https://github.com/xuxueli/xxl-mq)：由XXL开源的分布式消息队列。
* [Gifsockets](https://github.com/videlalvaro/gifsockets)：使用Gif动画作为传输的实时通信库。
* [Aeron](https://github.com/real-logic/Aeron)：高效可靠的UDP单播、UDP组播和IPC消息传输。
* [Metamorphosis](https://github.com/killme2008/Metamorphosis)：一个高可用、高性能的分布式消息系统，由淘宝开源。
* [Openfire](https://github.com/igniterealtime/Openfire)：开源XMPP服务器。
* [Eclipse OpenMQ](https://github.com/eclipse-ee4j/openmq)：JMS规范实现。
* [Hermes](https://github.com/allegro/hermes)：构建在Kafka之上的快速可靠的消息代理。
* [Apache Qpid](http://qpid.apache.org/)：AMQP企业消息传递实现。
* [Apache Synapse](https://github.com/apache/synapse)：Apache Synapse是一种轻量级高性能企业服务总线(ESB)。

<h2 id="kafka-tool">Kafka管理工具</h2>

* [AKHQ](https://github.com/tchiotludo/akhq)：用于Apache Kafka的Kafka GUI，用于管理主题、主题数据、消费者组、模式注册表、连接等等。
* [KnowStreaming](https://github.com/didi/KnowStreaming)：滴滴开源的Kafka运维管控平台。
* [Kafka-UI](https://github.com/provectus/kafka-ui)：用于Apache Kafka管理的开源Web UI。
* [EFAK](https://github.com/smartloli/EFAK)：一个简单且高性能的监控系统，用于对kafka集群进行全面的监控和管理。
* [Cruise-control](https://github.com/linkedin/cruise-control)：Cruise-control是同类中第一个完全自动化Kafka集群动态工作负载重新平衡和自我修复的工具，它通过简化Kafka集群的操作为Kafka用户提供了巨大的价值。
* [KCenter](https://github.com/xaecbd/KCenter)：KKafka中心是kafka集群管理维护、生产者/消费者监控、生态组件使用的统一平台。
* [Kafka-Sprout](https://github.com/oslabs-beta/Kafka-Sprout)：用于Kafka集群管理的Web GUI。
* [Xinfra-Monitor](https://github.com/linkedin/kafka-monitor)：Xinfra Monitor通过使用端到端管道生成合成工作负载来监控Kafka集群的可用性。
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry)：Kafka的Confluence模式注册中心。
* [Kafdrop](https://github.com/HomeAdvisor/Kafdrop)：Kafdrop是一个用于监控Apache Kafka集群的UI工具。
* [Mirus](https://github.com/salesforce/mirus)：一种基于Kafka Connect的Apache Kafka集群之间分布式、大容量复制的工具。
* [Kafdrop](https://github.com/obsidiandynamics/kafdrop)：Kafdrop是一个用于查看Kafka主题和浏览消费者组的Web UI。
* [Jikkou](https://github.com/streamthoughts/jikkou)：一个命令行工具，可帮助你自动管理Apache Kafka集群上的配置。
* [Julie](https://github.com/kafka-ops/julie)：帮助你在Apache Kafka部署中构建自动化和gitop的解决方案。

<h2 id="distributed">分布式组件</h2>

* [Databus](https://github.com/linkedin/databus)：与源无关的分布式变更数据捕获系统，由LinkedIn开发。
* [Jet](https://github.com/hazelcast/hazelcast-jet)：Jet是一个开源、内存中、分布式批处理和流处理引擎，由Hazelcast开源。
* [DSLabs](https://github.com/emichael/dslabs)：分布式系统Labs和框架。
* [Hadoop-20](https://github.com/facebookarchive/hadoop-20)：Facebook基于Apache Hadoop 0.20-append的实时分布式FS。
* [Orbit](https://github.com/orbit/orbit)：用于构建分布式系统的虚拟Actor框架。
* [Coherence](https://github.com/oracle/coherence)：Coherence是一个可扩展、容错、云就绪的分布式平台，用于构建基于网格的应用程序并可靠地存储数据，由Oracle开源。
* [Brooklin](https://github.com/linkedin/brooklin)：Brooklin是一个分布式系统，旨在在各种异构源和目标系统之间流式传输数据，具有高可靠性和大规模吞吐量，由LinkedIn开发。
* [Suro](https://github.com/Netflix/suro)：Suro是一种数据管道服务，用于收集、聚合和调度大量应用程序事件(包括日志数据)，由Netflix开发。
* [Blueflood](https://github.com/rax-maas/blueflood)：Blueflood是一个多租户、分布式度量处理系统，能够大规模地摄取、汇总和提供指标。
* [H-Store](https://github.com/apavlo/h-store)：H-Store是一个实验性主存并行数据库管理系统，针对在线事务处理(OLTP)应用程序进行了优化。
* [Hive2Hive](https://github.com/Hive2Hive/Hive2Hive)：用于安全、分布式、基于P2P的文件同步和共享的Java库。
* [TAPIR](https://github.com/UWSysLab/tapir)：分布式事务存储系统。
* [Waltz](https://github.com/wepay/waltz)：Waltz是一种基于仲裁的分布式预写日志，用于复制事务，由WePay开源。
* [Dynein](https://github.com/airbnb/dynein)：Dynein是Airbnb开源的分布式延迟作业排队系统。
* [kontraktor](https://github.com/RuedigerMoeller/kontraktor)：由分布式Actor模型提供支持的异步远程通信的无样板且一致的抽象。
* [TuGraph-analytics](https://github.com/TuGraph-family/tugraph-analytics)：TuGraph-analytics是一个基于图模型的分布式流式计算引擎，由蚂蚁开源。
* [Stubby4j](https://github.com/azagniotov/stubby4j)：HTTP/1.1、HTTP/2和WebSocket存根服务器，用于在Docker和非容器化环境中存根分布式Web服务以进行契约测试。
* [Concourse](https://github.com/cinchapi/concourse)：用于跨时间交易、搜索和分析的分布式数据库仓库。
* [Rewrite](https://github.com/openrewrite/rewrite)：OpenRewrite项目是一个海量源代码重构生态系统，由Netflix开源。
* [Apache Fluo](https://github.com/apache/fluo)：Apache Fluo是一个分布式处理系统，允许用户对大型数据集进行增量更新，Google Percolator的开源实现。
* [HotKey](https://gitee.com/jd-platform-opensource/hotkey)：京东App后台中间件，毫秒级探测热点数据，毫秒级推送至服务器集群内存，大幅降低热key对数据层查询压力。
* [XXL-DEEP](https://github.com/xuxueli/xxl-deep)：XXL-DEEP是一个分布式企业开发平台，提供整套开箱即用的基础模块。
* [Redis Session Manager](https://github.com/jcoleman/tomcat-redis-session-manager)：用于Apache Tomcat的Redis支持的非粘性会话存储。
* [dCache](https://github.com/dCache/dcache)：dCache是一个用于存储和检索大量数据的系统，这些数据分布在大量异构服务器节点中，在具有多种标准访问方法的单个虚拟文件系统树下。
* [Gradoop](https://github.com/dbs-leipzig/gradoop)：Gradoop是一个开源研究框架，用于构建在Apache Flink之上的可扩展图分析。
* [Octobot](https://github.com/cscotta/Octobot)：专为吞吐量、并行性和集群而设计的分布式任务队列工作线程。
* [Emissary](https://github.com/NationalSecurityAgency/emissary)：Emissary是一种基于P2P的数据驱动工作流引擎，运行在异构的、可能广泛分散的多层P2P计算资源网络中，由美国国家安全局开源。
* [DIZK](https://github.com/scipr-lab/dizk)：DIZK是一个用于分布式零知识证明系统的Java库。
* [ModeShape](https://github.com/ModeShape/modeshape)：ModeShape是一种分布式、分层、事务性和一致的数据存储，支持查询、全文搜索、事件、版本控制、引用以及灵活的动态模式。
* [Ambry](https://github.com/linkedin/ambry)：Ambry是一个分布式对象存储，支持存储数万亿个小型不可变对象(50K-100K)以及数十亿个大型对象，由LinkedIn开发。
* [Dempsy](https://github.com/Dempsy/dempsy)：分布式弹性消息处理系统。
* [Shuttle](https://github.com/cubefs/shuttle)：Shuttle提供远程shuffle功能，可以按分区将shuffle数据分组并转储到分布式文件系统中，由Vivo大数据团队开源。
* [Batch Processing Gateway](https://github.com/apple/batch-processing-gateway)：批处理网关使在Kubernetes上运行Spark服务变得容易，它允许用户通过直观的API调用在Kubernetes上提交、检查和删除Spark应用程序，而无需过多担心幕后发生的事情，由苹果开源。

<h2 id="distributed-lock">分布式锁</h2>

* [Redisson](https://github.com/redisson/redisson)：具有内存数据网格功能的简单Redis Java客户端，包含实现分布式锁的功能。
* [ShedLock](https://github.com/lukas-krecan/ShedLock)：计划任务的分布式锁。
* [klock](https://github.com/kekingcn/spring-boot-klock-starter)：基于Redis的分布式锁组件，简单方便快捷接入项目，使项目拥有分布式锁能力。
* [Apache Curator](https://github.com/apache/curator)：Apache Curator是Apache ZooKeeper(分布式协调服务)的Java/JVM客户端库。
* [Distributed-Kit](https://github.com/yujiasun/Distributed-Kit)：基于Redis和Zookeeper分布式工具集，包括分布式锁实现。
* [Lock4j](https://gitee.com/baomidou/lock4j)：基于Spring AOP的声明式和编程式分布式锁，支持RedisTemplate、Redisson、Zookeeper。
* [Amazon DynamoDB Lock Client](https://github.com/awslabs/amazon-dynamodb-lock-client)：构建在DynamoDB之上的通用分布式锁库，支持粗粒度和细粒度锁定。
* [Aquarius](https://github.com/Nepxion/Aquarius)：Aquarius是一款基于Redis + Zookeeper的分布式应用组件集合，包含分布式锁功能。
* [redis-distributed-lock](https://github.com/TaXueWWL/redis-distributed-lock)：Redis分布式锁工具包，提供纯Java方式调用，支持传统Spring工程，为Spring Boot应用提供了Starter，更方便快捷的调用。
* [Distributed Lock](https://github.com/alturkovic/distributed-lock)：使用Spring进行分布式锁的简单实现。
* [DLock](https://github.com/baidu/dlock)：有效可靠的分布式锁，由百度开源。
* [jedis-lock](https://github.com/abelaska/jedis-lock)：Jedis分布式锁支持。
* [WLock](https://github.com/wuba/WLock)：基于共识算法组件WPaxos的高可靠、高吞吐量的分布式锁服务。
* [Distributor](https://gitee.com/HappyChicken/Distributor)：常用分布式组件：分布式锁、分布式序列、分布式限流等。
* [coody-elock](https://gitee.com/coodyer/coody-elock)：一款基于Redis订阅实现的分布式锁插件。
* [redis-shared-lock](https://gitee.com/lsongiu/redis-shared-lock)：基于Redis的分布式共享锁，使用注解的方式对方法加锁。
* [DistributedLock](https://github.com/wyzssw/DistributedLock)：Redis分布式锁实现。

<h2 id="distributed-id-generator">分布式ID生成器</h2>

* [Leaf](https://github.com/Meituan-Dianping/Leaf)：分布式ID生成服务，由美团开源。
* [Tinyid](https://github.com/didi/tinyid)：简单易用、高性能、高可用的分布式ID生成系统，由滴滴开源。
* [Icicle](https://github.com/intenthq/icicle)：使用Redis和Lua的分布式、可排序的唯一ID生成系统。
* [Sequence](https://gitee.com/yu120/sequence)：高效GUID生成算法，基于Snowflake实现64位自增ID算法。
* [IDWorker](https://github.com/imadcn/idworker)：基于Zookeeper和雪花算法的分布式ID生成工具。
* [Redis ID Generator](https://github.com/hengyunabc/redis-id-generator)：基于Redis的分布式ID生成器。
* [UidGenerator](https://github.com/baidu/uid-generator)：UidGenerator是一个Java实现的、基于Snowflake的唯一ID生成器，由百度开源。
* [JNanoId](https://github.com/aventrix/jnanoid)：Java的唯一字符串ID生成器。
* [CosId](https://github.com/Ahoo-Wang/CosId)：通用、灵活、高性能的分布式ID生成器。
* [UUID-Creator](https://github.com/f4b6a3/uuid-creator)：用于生成通用唯一标识符(UUID)的Java库。
* [ULID-Creator](https://github.com/f4b6a3/ulid-creator)：用于生成通用唯一词典可排序标识符(ULID)的Java库。
* [Java-Snowflak](https://github.com/callicoder/java-snowflake)：基于雪花算法的分布式ID生成器。
* [Apache Commons RNG](https://github.com/apache/commons-rng)：提供伪随机生成器的纯Java实现。

<h2 id="db">数据库</h2>

这里包含使用Java编写的数据库软件

<h4 id="search-engine">搜索引擎</h4>

* [ElasticSearch](https://github.com/elastic/elasticsearch)：免费开源的分布式、RESTful搜索引擎。
* [Apache Lucene](https://github.com/apache/lucene)：开源搜索引擎。
* [Solr](https://github.com/apache/solr)：Solr是一款流行、速度极快的开源搜索平台，基于Apache Lucene构建。
* [OpenSearch](https://github.com/opensearch-project/OpenSearch)：开源分布式RESTful搜索引擎，由Amazon主导。
* [YaCy](https://github.com/yacy/yacy_search_server)：分布式点对点Web搜索引擎和Intranet搜索设备。
* [Fess](https://github.com/codelibs/fess)：Fess是非常强大且易于部署的企业搜索服务器。
* [OpenSearchServer](https://github.com/jaeksoft/opensearchserver)：开源企业级搜索引擎软件。
* [Loklak](https://github.com/loklak/loklak_server)：Loklak是一个服务器应用程序，能够从各种来源收集消息，包括Twitter。服务器包含搜索索引和点对点索引共享接口。
* [Kooder](https://gitee.com/koode/kooder)：Kooder是一个开源的代码搜索工具，目标是为包括Gitee/GitLab/Gitea在内的代码托管系统提供自动的源码、仓库和Issue的搜索服务。
* [IndexTank Engine](https://github.com/LinkedInAttic/indextank-engine)：该项目包含IndexTank搜索引擎实现，包括变量(提升)、类别、分面搜索、片段、自定义评分函数、建议和自动完成等功能，由LinkedIn开源。
* [Cleo](https://github.com/LinkedInAttic/cleo)：Cleo是一个灵活的软件库，用于快速开发部分、无序和实时的预输入搜索，由LinkedIn开源。
* [Elasticsearch IK Analysis](https://github.com/medcl/elasticsearch-analysis-ik)：IK分词插件可将Lucene IK分词器集成到ElasticSearch中，支持自定义字典。
* [Apache Marmotta](https://marmotta.apache.org/)：用于在存储库或搜索索引之间传输内容的开源软件。

<h4 id="graph-db">图数据库</h4>

* [Neo4j](https://github.com/neo4j/neo4j)：使用最广泛的图数据库。
* [JanusGraph](https://github.com/JanusGraph/janusgraph)：开源的分布式图数据库。
* [Apache HugeGraph](https://github.com/apache/incubator-hugegraph)：支持超过100+十亿数据、高性能和可扩展性的图数据库(包括OLTP引擎和REST API和后端)，该项目正在Apache基金会下孵化，最早由百度开源。
* [Titan](https://github.com/thinkaurelius/titan)：分布式图数据库。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是最通用的DBMS，在一个多模型产品中支持图、文档、响应式、全文和地理空间模型。
* [Apache TinkerPop](https://github.com/apache/tinkerpop)：为图数据库(OLTP)和图分析系统(OLAP)提供图计算功能。
* [GraphJet](https://github.com/twitter/GraphJet)：GraphJet是一个实时图处理库，由Twitter开源。
* [GraphDB](https://www.ontotext.com/)：企业级RDF和图数据库，具有高效推理、集群和外部索引同步支持。它还支持通过SPARQL对知识图和GraphQL进行SQL JDBC访问。
* [Stardog](https://www.stardog.com/)：一款商业图数据库。
* [BlazeGraph](https://github.com/blazegraph/database)：一款开源的高性能图数据库。
* [TypeDB](https://github.com/vaticle/typedb)：TypeDB是一个强类型数据库，具有丰富且逻辑的类型系统。
* [Gaffer](https://github.com/gchq/Gaffer)：支持属性聚合的大规模实体和关系数据库，由英国政府通讯总部开源。
* [HyperGraphDB](https://github.com/hypergraphdb/hypergraphdb)：专为人工智能和语义Web项目设计的图数据库，也可以用作各种规模项目的嵌入式面向对象数据库。
* [YangDB](https://github.com/YANG-DB/yang-db)：开源、可扩展、非原生图数据库(由Elasticsearch提供支持)。

<h4 id="embedded-db">嵌入式数据库</h4>

* [H2](https://github.com/h2database/h2database)：用Java编写的嵌入式RDBMS。
* [Apache Derby](https://github.com/apache/derby)：Derby是一个纯Java、基于标准的关系数据库引擎。
* [HSQLDB](https://hsqldb.org/)：HSQLDB是一个用Java编写的关系数据库引擎。
* [QuickIO](https://github.com/artbits/quickio)：Java嵌入式数据库。
* [MapDB](https://github.com/jankotek/mapdb)：MapDB提供由磁盘存储或堆外内存支持的并发映射、集合和队列。它是一个快速且易于使用的嵌入式Java数据库引擎。
* [ObjectBox](https://github.com/objectbox/objectbox-java)：Java和Android数据库-快速且轻量级，无需任何ORM。
* [Xodus](https://github.com/JetBrains/xodus)：JetBrains YouTrack和JetBrains Hub使用的事务性无模式嵌入式数据库。
* [SirixDB](https://github.com/sirixdb/sirix)：SirixDB 是一个嵌入式、时态、进化数据库系统，它使用仅附加方法来存储不可变的修订。
* [LMDB](https://github.com/lmdbjava/lmdbjava)：Java版闪电内存数据库(LMDB)：低延迟、事务性、排序、嵌入式、键值存储。
* [Nitrite](https://github.com/nitrite/nitrite-java)：Java嵌入式NoSQL文档存储。
* [JDBM3](https://github.com/jankotek/JDBM3)：嵌入式键值Java数据库。
* [HerdDB](https://github.com/diennea/herddb)：可嵌入JVM的分布式数据库。
* [PalDB](https://github.com/linkedin/PalDB)：用Java编写的嵌入式一次性写入键值存储，由LinkedIn开源。
* [Realm](https://github.com/realm/realm-java)：Realm是一个移动数据库，SQLite和ORM的替代品。
* [HaloDB](https://github.com/yahoo/HaloDB)：HaloDB是一个用Java编写的快速且简单的嵌入式键值存储，由Yahoo开源。
* [MariaDB4j](https://github.com/MariaDB4j/MariaDB4j)：Java JAR中嵌入的MariaDB。

<h4 id="rdbms-db">关系型数据库</h4>

* [VoltDB](https://github.com/VoltDB/voltdb)：VoltDB是一种水平可扩展的内存中SQL RDBMS，专为具有极高读写吞吐量要求的应用程序而设计。
* [Apache EmpireDB](https://github.com/apache/empire-db)：Apache EmpireDB是一个轻量级关系数据库抽象层和数据持久组件。
* [ArcadeDB](https://github.com/ArcadeData/arcadedb)：一种支持SQL、Cypher、Gremlin、HTTP/JSON、MongoDB和Redis的多模型DBMS。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式且可扩展的SQL数据库，用于近乎实时地存储和分析大量数据，甚至可以进行复杂的查询。它与PostgreSQL兼容，并且基于Lucene。

<h4 id="nosql-db">NoSQL数据库</h4>

* [Apache Cassandra](https://github.com/apache/cassandra)：Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：Apache HBase是一个开源、分布式、版本化、面向列的存储，
* [Apache IoTDB](https://github.com/apache/iotdb)：IoTDB是时序数据的数据管理系统，为用户提供数据采集、存储、分析等特定服务，该项目由清华大学主导，在Apache基金会下开源。
* [Apache Pinot](https://github.com/apache/pinot)：实时分布式OLAP数据存储，由领英开源。
* [Apache Druid](https://github.com/apache/druid)：高性能实时分析数据库，由MetaMarkets开源。
* [Apache Doris](https://github.com/apache/doris)：一个易于使用、高性能和统一的分析数据库，由百度开源。
* [Apache Ignite](https://github.com/apache/ignite)：分布式数据库，用于以内存速度进行高性能计算，由GridGain开源。
* [Apache Kylin](https://github.com/apache/kylin)：适用于大数据的极致OLAP引擎，由eBay开源。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是最通用的DBMS，在一个多模型产品中支持图、文档、响应式、全文和地理空间模型。
* [Paper](https://github.com/pilgr/Paper)：Paper是Android上Java/Kotlin对象的快速类NoSQL存储，具有自动模式迁移支持。
* [OpenLineage](https://github.com/OpenLineage/openlineage)：谱系元数据收集的开放标准。
* [QuestDB](https://github.com/questdb/questdb)：用于快速摄取和SQL查询的开源时间序列数据库。
* [Lealone](https://github.com/lealone/Lealone)：高性能的面向OLTP场景的关系数据库。
* [DingoDB](https://github.com/dingodb/dingo)：多模态向量数据库，支持对结构化和非结构化数据使用统一SQL进行更新插入和向量查询，同时满足高并发和超低延迟的要求。
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb)：OpenTSDB是一个分布式、可扩展的时序数据库(TSDB)，基于HBase开发，由StumbleUpon开源。
* [ElephantDB](https://github.com/nathanmarz/elephantdb)：ElephantDB是一个专门从Hadoop导出键/值数据的数据库。
* [Elassandra](https://github.com/strapdata/elassandra)：Elassandra是一个Apache Cassandra发行版，包括Elasticsearch搜索引擎。
* [Sensei](https://github.com/LinkedInAttic/sensei)：Sensei是一个分布式、弹性的实时可搜索数据库，由LinkedIn开源。
* [Heroic](https://github.com/spotify/heroic)：基于Bigtable、Cassandra和Elasticsearch的可扩展时序数据库，由Spotify开源。
* [StarRocks](https://github.com/StarRocks/starrocks)：StarRocks是Linux基金会的一个项目，是下一代数据平台，旨在使数据密集型实时分析变得快速、轻松，由百度Doris团队成员开源。
* [KairosDB](https://github.com/kairosdb/kairosdb)：KairosDB是一个基于Cassandra编写的快速分布式可扩展时序数据库。
* [ToroDB](https://github.com/torodb/stampede)：在RDBMS之上运行的开源NoSQL数据库，与MongoDB协议和API兼容，但支持原生SQL、原子操作以及PostgreSQL等可靠耐用的后端。
* [LevelDB](https://github.com/dain/leveldb)：这是Java中LevelDB的重写，此目标是拥有一个功能完整的实现，其性能与C++原始版本的性能相差不超过10%，并生成C++代码的逐字节精确副本。
* [Tarantool](https://github.com/tarantool/tarantool)：一个开源NoSQL数据库管理系统和Lua应用服务器。
* [eXistDB](https://github.com/eXist-db/exist)：eXist-db是一个高性能开源原生XML数据库，完全围绕XML技术构建的NoSQL文档数据库和应用程序平台。
* [KSqlDB](https://github.com/confluentinc/ksql)：KSqlDB是一个用于在Apache Kafka之上构建流处理应用程序的数据库，由Confluent开源。

<h2 id="db-conn">数据库连接池</h2>

* [Druid](https://github.com/alibaba/druid)：阿里云计算平台DataWorks团队出品，为监控而生的数据库连接池。
* [HikariCP](https://github.com/brettwooldridge/HikariCP)：可靠、高性能的JDBC连接池。
* [Apache Commons DBCP](https://github.com/apache/commons-dbcp)：Apache下开源的数据库连接池。
* [C3P0](https://github.com/swaldman/c3p0)：一个成熟的、高度并发的JDBC连接池库，支持缓存和重用PreparedStatements。
* [BoneCP](https://github.com/wwadge/bonecp)：BoneCP是一种JDBC连接池实现，它通过最大限度地减少锁争用来实现高性能，从而为应用程序提供更大的吞吐量。
* [FlexyPool](https://github.com/vladmihalcea/flexy-pool)：可以向给定的连接池添加指标和故障转移策略，使其能够按需调整大小。
* [Agroal](https://github.com/agroal/agroal)：一个小巧的数据库连接池。
* [Vibur DBCP](https://github.com/vibur/vibur-dbcp)：并发和动态JDBC连接池。
* [Tomcat JDBC](https://tomcat.apache.org/tomcat-7.0-doc/jdbc-pool.html)：Tomcat JDBC连接池。
* [R2DBC-Pool](https://github.com/r2dbc/r2dbc-pool)：用于响应式关系数据库连接的连接池。
* [BeeCP](https://gitee.com/Chris2018998/BeeCP)：一个小型的JDBC连接池，性能高、代码轻量、稳定性好。

<h2 id="mid-client">中间件客户端</h2>

* [NATS Java Client](https://github.com/nats-io/nats.java)：NATS消息系统的Java客户端。
* [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client)：RabbitMQ Java客户端。
* [MinIO](https://github.com/minio/minio-java)：用于Java的MinIO客户端SDK。
* [InfluxDB Java](https://github.com/influxdata/influxdb-java)：InfluxDB的官方Java客户端库。
* [InfluxDB2 Java](https://github.com/influxdata/influxdb-client-java)：适用于JVM的InfluxDB 2客户端。
* [ClickHouse Java](https://github.com/ClickHouse/clickhouse-java)：用于连接ClickHouse并处理各种格式数据的Java库。
* [Paho](https://github.com/eclipse/paho.mqtt.java)：Eclipse Paho Java MQTT客户端库，Paho是一个Eclipse IoT项目。
* [HiveMQ MQTT Client](https://github.com/hivemq/hivemq-mqtt-client)：MQTT 5.0和3.1.1兼容且功能丰富的高性能Java客户端库，具有不同的API风格和背压支持。
* [Couchbase](https://github.com/couchbase/couchbase-java-client)：Couchbase Server的官方Java客户端。
* [Consul](https://github.com/Ecwid/consul-api)：Consul的Java客户端。
* [Grafana OpenTelemetry Starter](https://github.com/grafana/grafana-opentelemetry-starter)：用于OpenTelemetry的Spring Boot Starter。
* [Sentry SDK](https://github.com/getsentry/sentry-java/)：适用于Java、Android和其他JVM语言的Sentry SDK。
* [OceanBase Client](https://github.com/oceanbase/obconnector-j)：兼容JDBC 4.2的OceanBase Java驱动程序。

<h2 id="httpclient">HTTP客户端库</h2>

* [Apache HttpComponents Core](https://github.com/apache/httpcomponents-core)：Apache开源的HTTP客户端库。
* [Apache HttpComponents Client](https://github.com/apache/httpcomponents-client)：Apache开源的HTTP客户端库，相比HttpComponents Core提供更流式的API。
* [Apache HttpAsyncClient](https://github.com/apache/httpasyncclient)：Apache开源的异步HTTP客户端库。
* [Feign](https://github.com/OpenFeign/feign)：Feign是一个Java到HTTP客户端绑定器，其灵感来自于Retrofit、JAXRS-2.0和WebSocket，由Netflix开源。
* [OkHttp](https://github.com/square/okhttp)：Square为JVM、Android和GraalVM精心设计的HTTP客户端。
* [Retrofit](https://github.com/square/retrofit)：适用于Android和JVM的类型安全HTTP客户端。
* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)：适用于Java的异步HTTP和WebSocket客户端库。
* [Android Asynchronous HttpClient](https://github.com/android-async-http/android-async-http)：适用于Android的异步、基于回调的HTTP客户端，构建于Apache的HttpClient库之上。
* [Google HTTP Client](https://github.com/googleapis/google-http-java-client)：Google开发的适用于Java的HTTP客户端库。
* [HttpClientUtil](https://github.com/Arronlong/httpclientutil)：基于HttpClient 4.4.1封装的工具类。
* [Http Request](https://github.com/kevinsawicki/http-request)：一个简单的便利库，用于使用HttpURLConnection发出请求并访问响应。
* [rest-client](https://github.com/wisdom-projects/rest-client)：自动化测试REST API的工具，可以生成精美的测试报告和REST API文档。
* [EasyHttp](https://github.com/getActivity/EasyHttp)：Android网络请求框架，简单易用。
* [OkGo](https://github.com/jeasonlzy/okhttp-OkGo)：基于HTTP协议，封装了OkHttp的网络请求框架，比Retrofit更简单易用。
* [AndroidAsync](https://github.com/koush/AndroidAsync)：适用于Android的异步套接字、HTTP(s)和WebSocket库。基于NIO，而不是线程。
* [Chuck](https://github.com/jgilfelt/chuck)：适用于Android OkHttp客户端的应用内HTTP检查器。
* [Bilibili Android Client](https://github.com/HotBitmapGG/bilibili-android-client)：适用于Android的非官方BiliBili客户端。
* [Unirest](https://github.com/Kong/unirest-java)：简化的轻量级HTTP客户端库。
* [HTTP-Kit](https://github.com/http-kit/http-kit)：适用于Clojure的简单、高性能、事件驱动的HTTP客户端+服务器。
* [Forest](https://github.com/dromara/forest)：由dromara社区开源的声明式HTTP客户端框架。
* [Jetty ReactiveStream HttpClient](https://github.com/jetty-project/jetty-reactive-httpclient)：Jetty HttpClient的响应流包装器。
* [Jodd HTTP](https://github.com/oblac/jodd-http)：简单的Java HTTP客户端。
* [ESA RestClient](https://github.com/esastack/esa-restclient)：一个基于Netty的异步事件驱动的HTTP客户端。
* [SSLContext Kickstart](https://github.com/Hakky54/sslcontext-kickstart)：一个轻量级库，用于配置基于SSLContext或其他属性(例如TrustManager、KeyManager或受信任证书)的 HTTP客户端或服务器，以通过SSLFactory提供的单向身份验证或双向身份验证通过SSL/TLS进行通信。
* [Hosebird Client](https://github.com/twitter/hbc)：用于消费Twitter标准Streaming API的Java HTTP客户端，由Twitter开源。
* [FusionAuth HTTP Client](https://github.com/FusionAuth/java-http)：完全用纯Java编写的全功能、独立、高性能HTTP服务器和客户端。
* [Parallec](https://github.com/eBay/parallec)：Parallec是一个基于Akka的快速并行异步HTTP(S)/SSH/TCP/UDP/Ping客户端Java库，由eBay开源。
* [OkHttps](https://gitee.com/troyzhxu/okhttps)：对OkHttp3轻量封装的框架，包括异步预处理器，特色的标签，灵活的上传下载进度监听与过程控制功能。
* [Riptide](https://github.com/zalando/riptide)：Spring RestTemplate的客户端响应路由，由Zalando开源。
* [HTTP4K](https://github.com/http4k/http4k)：HTTP4K是一个用纯Kotlin编写的轻量级但功能齐全的HTTP工具包，可以以功能一致的方式提供和使用HTTP服务。

<h2 id="rpc">RPC框架</h2>

* [Dubbo](https://github.com/apache/dubbo)：阿里开源的RPC和微服务框架。
* [gRPC](https://github.com/grpc/grpc-java)：Google RPC的Java实现，基于HTTP/2的RPC。
* [Finagle](https://github.com/twitter/finagle)：容错、协议无关的RPC系统，由Twitter开源并广泛使用。
* [Motan](https://github.com/weibocom/motan)：Motan是一个跨语言远程过程调用(RPC)框架，用于快速开发高性能分布式服务，由微博开源。
* [SOFARPC](https://github.com/sofastack/sofa-rpc)：一个高性能、高扩展性、生产级的Java RPC框架，由蚂蚁金服开源并广泛使用。
* [Pigeon](https://github.com/dianping/pigeon)：大众点评开源的RPC框架。
* [Apache Thrift](https://github.com/apache/thrift)：Thrift是一个由Facebook开源的轻量级、独立于语言的软件堆栈，用于点对点RPC实现的框架。
* [OCTO-RPC](https://github.com/Meituan-Dianping/octo-rpc)：OCTO-RPC是支持Java和C++的企业级通信框架，在RPC服务之上扩展了丰富的服务治理功能，由美团开源。
* [DeFiBus](https://gitee.com/WeBank/DeFiBus)：由微众银行开源的分布式金融级消息总线，提供了RPC同步调用、MQ的异步事件通知、事件组播和广播等常用服务调用和消息模式。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint/tree/master/rpc)：Naver开源的RPC框架，服务于Pinpoint。
* [TChannel](https://github.com/uber/tchannel-java)：TChannel协议的Java实现，由Uber开源。
* [TarsJava](https://github.com/TarsCloud/TarsJava)：Java语言框架RPC源码实现，在Tars基金会下开源。
* [Protobuf RPC](https://github.com/baidu/Jprotobuf-rpc-socket)：Protobuf RPC是一种基于TCP协议的二进制RPC通信协议的Java实现，由百度开源。
* [Storm](https://github.com/nathanmarz/storm)：分布式和容错实时计算：流处理、连续计算、分布式RPC等。
* [Starlight](https://github.com/baidu/starlight)：百度RPC、多协议、高性能RPC的Java实现。
* [NettyRpc](https://github.com/luxiaoxun/NettyRpc)：一个基于Netty、ZooKeeper和Spring的简单RPC框架。
* [Koalas](https://gitee.com/dromara/koalas-rpc)：dromara社区开源的高可用可拓展的RPC框架。
* [XXL-RPC](https://github.com/xuxueli/xxl-rpc)：XXL社区开源的国产高性能、分布式RPC框架。
* [Wire](https://github.com/square/wire)：适用于Android、Kotlin、Swift和Java的gRPC和协议缓冲区。
* [Armeria](https://github.com/line/armeria)：可以利用不同技术构建任何类型微服务的框架，包括gRPC、Thrift、Kotlin、Retrofit、Reactive Stream、Spring Boot和Dropwizard，由Line开源。
* [RPC-Framework](https://github.com/Snailclimb/guide-rpc-framework)：一款基于Netty + Kyro + Zookeeper实现的自定义RPC框架。
* [NFS4J](https://github.com/dCache/nfs4j)：NFS服务器版本3、4.0和4.1的纯Java实现，包括带有nfs4.1-files和flex-files布局类型的pNFS扩展。
* [JoyRPC](https://github.com/joyrpc/joyrpc)：高性能、高扩展性的Java RPC框架。
* [Thunder](https://github.com/Nepxion/Thunder)：多协议、多组件、多序列化的分布式RPC调用框架，由Nepxion开源。
* [ONCRPC4J](https://github.com/dCache/oncrpc4j)：ONCRPC/SUNRPC的纯Java实现。
* [Hprose](https://github.com/hprose/hprose-java)：Hprose是一个跨语言的RPC。
* [NettyRPC](https://github.com/tang-jie/NettyRPC)：NettyRPC是基于Netty的高性能Java RPC服务器，使用kryo、hessian、protostuff支持消息序列化。

<h2 id="reactive">响应式库</h2>

* [RxJava](https://github.com/ReactiveX/RxJava)：JVM的Reactive扩展–一个使用Java VM的可观察序列编写异步和基于事件的程序的库。
* [Reactor](https://github.com/reactor/reactor-core)：JVM的非阻塞响应式基础。
* [Webflux](https://github.com/spring-projects/spring-framework/tree/main/spring-webflux)：Spring生态中基于Reactor的异步非阻塞Web框架。
* [Reactive Stream](https://github.com/reactive-streams/reactive-streams-jvm)：JVM的响应式流规范。
* [Vert.x](https://github.com/eclipse-vertx/vert.x)：一个用于在JVM上构建响应式应用程序的工具包。
* [Akka](https://github.com/akka/akka)：在JVM上构建高度并发、分布式和弹性的消息驱动应用程序。
* [RSocket](https://github.com/rsocket/rsocket-java)：RSocket的Java实现。
* [Agera](https://github.com/google/agera)：Android的响应式编程库。
* [Mobius](https://github.com/spotify/mobius)：用于管理状态演化和副作用的函数响应式框架。
* [Smallrye](https://github.com/smallrye/smallrye-mutiny)：直观的Java事件驱动响应式编程库。
* [AutoDispose](https://github.com/uber/AutoDispose)：RxJava流的自动绑定+处置。
* [Ratpack](https://github.com/ratpack/ratpack)：Ratpack是一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [Alibaba RSocket Broker](https://github.com/alibaba/alibaba-rsocket-broker)：Alibaba RSocket Broker是一款基于RSocket协议的响应式对等通讯系统，为通讯多方构建分布式的RPC、Pub/Sub、Streaming等通讯支持。
* [RSC](https://github.com/making/rsc)：RSocket Client CLI(RSC)旨在成为RSocket的curl。
* [Sqlbrite](https://github.com/square/sqlbrite)：SQLiteOpenHelper的轻量级包装器，它将响应式流语义引入SQL操作。
* [StorIO](https://github.com/pushtorefresh/storio)：SQLiteDatabase和ContentResolver的响应式API。
* [Rx-Preferences](https://github.com/f2prateek/rx-preferences)：Android的响应式SharedPreferences。
* [RxNetty](https://github.com/ReactiveX/RxNetty)：Netty响应式扩展适配器。
* [Reactive gRPC](https://github.com/salesforce/reactive-grpc)：gRPC的响应式存根。
* [QBit](https://github.com/advantageous/qbit)：QBit是一个用于构建微服务的响应式编程库。
* [ScaleCube](https://github.com/scalecube/scalecube-services)：scalecube-services是一个高吞吐量、低延迟的响应式微服务库。
* [Reactor Kafka](https://github.com/reactor/reactor-kafka)：Reactor响应式Kafka驱动程序。
* [Reactive-Audit](https://github.com/octo-online/reactive-audit)：旨在为项目实施中使用响应式架构提供帮助的审计工具。
* [Twitch4j](https://github.com/twitch4j/twitch4j)：模块化异步/同步/响应式Twitch API客户端/IRC客户端。
* [XOOM-Actors](https://github.com/vlingo/xoom-actors)：用于类型安全Actor模型的VLINGO XOOM平台SDK，使用Java和其他JVM语言提供响应式并发、高可扩展性、高吞吐量和弹性。
* [CohereFlux](https://github.com/pellse/cohereflux)：CohereFlux是一个响应式数据聚合框架，用于查询和合并来自多个数据源/服务的数据。

<h2 id="webserver">WebServer</h2>

* [Netty](https://github.com/netty/netty)：事件驱动的异步网络应用框架。
* [Apache Tomcat](https://github.com/apache/tomcat)：Apache Tomcat是Java Servlet、JavaServer Pages、Java EL和Java WebSocket技术的开源实现。
* [Apache TomEE](https://github.com/apache/tomee)：一个轻量级但功能强大的Java EE应用服务器，具有功能丰富的工具。
* [Helidon Nima](https://github.com/helidon-io/helidon/tree/helidon-3.x/webserver)：基于JDK虚拟线程的轻量级Web服务器。
* [Undertow](https://github.com/undertow-io/undertow)：高性能非阻塞Web服务器。
* [Wildfly](https://github.com/wildfly/wildfly)：WildFly应用服务器。
* [Weblogic](https://www.oracle.com/sg/java/weblogic/)：Oracle的商业应用服务器。
* [Open Liberty](https://github.com/OpenLiberty/open-liberty)：Open Liberty是一个高度可组合、快速启动的动态应用程序服务器运行时环境，由IBM提供。
* [Jetty](https://github.com/eclipse/jetty.project)：Jetty是一个轻量级、高度可扩展的基于Java的Web服务器和Servlet引擎。
* [Glassfish](https://github.com/eclipse-ee4j/glassfish)：Eclipse基金会下开源的Jakarta服务器。
* [Payara](https://github.com/payara/Payara)：Payara Server是一个开源中间件平台，支持在本地、云端或混合环境中可靠、安全地部署Java EE(Jakarta EE)和MicroProfile应用程序。
* [Apache Geronimo](https://geronimo.apache.org/)：Apache基金会下开源的Java EE服务器。
* [Red5](https://github.com/Red5/red5-server)：Red5是一个用Java编写的开源Flash服务器。
* [Microhttp](https://github.com/ebarlas/microhttp)：快速、可扩展、独立、单线程Java Web服务器。
* [Apache MINA](https://github.com/apache/mina)：Apache MINA是一个网络应用框架，可以帮助用户开发高性能和高可扩展性的网络应用程序。
* [ZIO](https://github.com/zio/zio)：一个类型安全、可组合的库，用于Scala中的异步和并发编程。
* [zfoo](https://github.com/zfoo-project/zfoo)：极致性能的Java服务器框架，RPC，游戏服务器框架，Web应用服务器框架。
* [Eclipse Grizzly](https://github.com/eclipse-ee4j/grizzly)：Grizzly的目标是帮助开发人员使用NIO构建可扩展且强大的服务器，并提供扩展框架组件。
* [Reactor-Netty](https://github.com/reactor/reactor-netty)：TCP/HTTP/UDP/QUIC客户端/服务器，使用基于Netty的Reactor。
* [Nettosphere](https://github.com/Atmosphere/nettosphere)：基于Atmosphere和Netty框架的Java WebSocket/HTTP服务器。
* [NanoHTTPD](https://github.com/NanoHttpd/nanohttpd)：微型、可轻松嵌入Java中的HTTP服务器。
* [Java NIO Server](https://github.com/jjenkov/java-nio-server)：一个始终使用非阻塞IO的Java NIO服务器。
* [AndServer](https://github.com/yanzhenjie/AndServer)：Android平台的Web服务器和Web框架。
* [Rapidoid](https://github.com/rapidoid/rapidoid)：极其快速、简单且功能强大的Java Web框架和HTTP服务器。
* [REST Commander](https://github.com/eBay/restcommander)：快速并行异步HTTP客户端即服务，用于监控和管理10000个Web服务器，由eBay开发。
* [EzyFox](https://github.com/youngmonkeys/ezyfox-server)：套接字服务器(包括SSL)支持TCP、UDP和Websocket的实时应用程序、实时游戏、MMORPG、消息传递、聊天和流数据。
* [Para](https://github.com/Erudika/para)：用于快速构建Web和移动应用程序的多租户后端服务器。
* [Methanol](https://github.com/mizosoft/methanol)：Java的轻量级HTTP扩展。
* [Nginx-Clojure](https://github.com/nginx-clojure/nginx-clojure)：Nginx模块，用于嵌入Clojure或Java或Groovy程序，通常是基于Ring的处理程序。

<h2 id="websocket">WebSocket</h2>

* [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket)：用纯Java编写的准系统WebSocket客户端和服务器实现。
* [Scarlet](https://github.com/Tinder/Scarlet)：受Retrofit启发的适用于Kotlin、Java和Android的WebSocket客户端。
* [AndroidAsync](https://github.com/koush/AndroidAsync)：适用于Android的异步套接字、HTTP(s)和WebSocket库。基于NIO，而不是线程。
* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)：适用于Java的异步HTTP和WebSocket客户端库。
* [NV-Websocket-Client](https://github.com/TakahikoKawasaki/nv-websocket-client)：Java中的高质量WebSocket客户端实现。
* [WebSocket Android](https://github.com/codebutler/android-websockets)：一个非常简单的Android WebSocket客户端。
* [Kafka-WebSocket](https://github.com/b/kafka-websocket)：Kafka-WebSocket是kafka分布式消息代理的简单WebSocket服务器接口。
* [Socket.IO Java](https://github.com/socketio/socket.io-client-java)：全功能的Java Socket.IO客户端库，与Socket.IO v1.0及更高版本兼容。
* [Pusher Java Client](https://github.com/pusher/pusher-websocket-java)：适用于Java的 Pusher Channels客户端库，面向Java和Android。
* [JavaWebsocketClient](https://github.com/jacek-marchwicki/JavaWebsocketClient)：JavaWebsocketClient库是用于Java和Android的RX中Websocket连接的简单库，它被设计为快速且容错。
* [Netty-Socket.IO](https://github.com/mrniko/netty-socketio)：该项目是Socket.IO服务器的开源Java实现，基于Netty服务器框架。
* [wAsync](https://github.com/Atmosphere/wasync)：wAsync是一个基于Java的库，允许与任何支持WebSocket或HTTP协议的Web服务器进行异步通信。
* [Java/Android WebSocket Client](https://github.com/gusavila92/java-android-websocket-client)：一个非常轻量级的WebSocket客户端库，适用于基于JVM的客户端或Android，旨在实现RFC 6455中定义的WebSocket协议。
* [Proxyee](https://github.com/monkeyWie/proxyee)：Proxyee是一个Java编写的HTTP代理服务器库，支持HTTP、HTTPS、WebSocket协议，并支持MITM，可以捕获和篡改HTTP、HTTPS数据包。
* [Webbit](https://github.com/webbit/webbit)：基于Java事件的WebSocket和HTTP服务器。

<h2 id="gameserver">游戏服务器</h2>

* [NettyGameServer](https://github.com/jwpttcg66/NettyGameServer)：使用Netty 4.X实现的手机游戏分布式服务器,支持TCP、UDP、HTTP、WebSocket链接。
* [Jetserver](https://github.com/menacher/java-game-server)：Jetserver是一个基于高速NIO套接字的多人Java游戏服务器，使用Netty和Jetlang编写。
* [Game-Server](https://github.com/jzyong/game-server)：分布式Java游戏服务器，包括集群管理服务器、网关服务器、大厅服务器、游戏逻辑服务器。
* [Summer](https://github.com/SwingFrog/Summer)：轻量级、一站式的Java游戏服务器框架，也可用于开发简单的Web服务。
* [Mmorpg](https://github.com/kingston-csj/mmorpg)：用Java编写的分布式高性能mmorpg手游服务端框架。
* [Everwar](https://github.com/geektcp/everwar)：魔兽世界完整的服务端源码版本。
* [GameServer4j](https://github.com/jzyong/GameServer4j)：分布式Java游戏服务器，包括登录、网关、游戏演示。
* [ioGame](https://gitee.com/game-town/ioGame)：无锁异步化、事件驱动架构设计的Java Netty网络游戏服务器框架。
* [Socket.IO](https://github.com/scalecube/socketio)：基于Netty的Socket.IO Java服务器，为了满足游戏性能要求而创建的。
* [Apollo](https://github.com/apollo-rsps/apollo)：一个开源Java游戏服务器套件，旨在轻量、快速且安全。
* [Noark](https://gitee.com/xiaoe/noark3)：一个由Java实现的游戏服务器端框架，可快速开发出易维护、高性能、高扩展能力的游戏服务器。
* [Carmelo](https://github.com/needmorecode/carmelo)：Carmelo是一个快速、可扩展的Java服务器框架，专为在线游戏而设计。
* [Okra](https://github.com/ogcs/Okra)：基于Netty和Disruptor的高性能游戏服务器框架。
* [Gamioo](https://github.com/jiangguilong2000/gamioo)：游戏服务器框架，基于此框架，可以快速实现一个高可用、易维护、稳定、高性能的游戏服务器。
* [TenIO](https://github.com/congcoi123/tenio)：TenIO是一个用于创建多人在线游戏的开源项目。
* [Avalon](https://gitee.com/codeborker/Avalon)：基于Akka的高性能可伸缩的Java网络游戏服务器，简单的单服务器开发与集群开发的切换。

<h2 id="im">IM服务器</h2>

* [TIMSDK](https://github.com/TencentCloud/TIMSDK)：腾讯云即时消息服务。
* [CIM](https://github.com/crossoverJie/cim)：一款面向开发者的IM(即时通讯)系统，同时提供了一些组件帮助开发者构建一款属于自己可水平扩展的IM。
* [野火IM](https://github.com/wildfirechat/im-server)：野火IM是专业级的即时通讯和实时音视频整体解决方案，由北京野火无限网络科技有限公司维护和支持。
* [MPush](https://github.com/mpusher/mpush)：开源实时消息推送系统。
* [NettyChat](https://github.com/FreddyChen/NettyChat)：基于Netty + TCP + Protobuf实现的Android IM库。
* [Turms](https://github.com/turms-im/turms)：Turms是全球最先进的开源即时通讯引擎，支持100K~10M并发用户。
* [InChat](https://github.com/AwakenCN/InChat)：一个轻量级、高效、分布式的异步通信框架, 支持聊天和物联网。
* [Camellia](https://github.com/netease-im/camellia)：Camellia是网易云信开发的服务器基础组件。
* [Smack](https://github.com/igniterealtime/Smack)：用Java编写的模块化、可移植的开源XMPP客户端库，适用于Android和Java。
* [J-IM](https://gitee.com/xchao/j-im)：J-IM是用Java语言开发的轻量、高性能、单机支持几十万至百万在线用户IM。
* [CIM](https://gitee.com/farsunset/cim)：CIM是一套基于Netty框架下的推送系统。

<h2 id="jakartaee">JakartaEE产品</h2>

* [Payara](https://github.com/payara/Payara)：Payara Server是一个开源中间件平台，支持在本地、云端或混合环境中可靠、安全地部署Java EE(Jakarta EE)和MicroProfile应用程序。
* [Apache TomEE](https://github.com/apache/tomee)：一个轻量级但功能强大的Java EE应用服务器，具有功能丰富的工具。
* [Piranha](https://github.com/piranhacloud/piranha)：Piranha项目提供云就绪容器和有用的附加/集成模块。
* [Open Liberty](https://github.com/OpenLiberty/open-liberty)：Open Liberty是一个高度可组合、快速启动的动态应用程序服务器运行时环境，它是IBM WebSphere Liberty的开源实现。
* [KumuluzEE](https://github.com/kumuluz/kumuluzee)：轻量级开源框架，用于使用标准Jakarta EE技术开发微服务并将Jakarta EE迁移到云原生架构。
* [Cricket](https://github.com/gskorupa/cricket)：Java微服务框架。
* [AISWare Flying Server](http://www.antdb.net/flyingserver)：亚信科技提供的满足Jakarta EE 8规范的通用应用服务器中间件产品。
* [Apusic AAS](https://www.apusic.com/list-117.html)：金蝶Apusic应用服务器是一款标准、安全、高效、集成并具丰富功能的企业级应用服务器软件，全面支持Jakarta EE 8/9的技术规范。
* [Eclipse Glassfish](https://github.com/eclipse-ee4j/glassfish)：Eclipse GlassFish是由Eclipse基金会赞助的Jakarta EE兼容实现。
* [FUJITSU Software Interstage Application Server](https://www.fujitsu.com/jp/software/interstage/apserver)：由富士通提供的高可靠、高性能Jakarta EE应用服务器。
* [IBM WebSphere Liberty](https://www.ibm.com/support/pages/node/6250961#asset/runtimes-wlp-javaee8)：由IBM提供的兼容Jakarta EE规范的应用服务器。
* [InforSuite Application Server](https://www.inforbus.com/as.html)：中创应用服务器软件是国内通过Jakarta EE 9、8及Java EE 8、7、6完整兼容认证的企业级中间件，与国际主流产品最新版本保持规范一致，为应用运行提供高性能、高可用、高安全的支撑平台。
* [JBoss Enterprise Application Platform](https://www.redhat.com/en/technologies/jboss-middleware/application-platform)：RedHat JBoss企业应用平台(JBoss EAP)可在任何环境中提供企业级安全性、性能和可扩展性。
* [Primeton AppServer](https://www.primeton.com/products/pas/)：支持Jakarta EE Platform 8国际标准规范、支持Web容器所有特性，由普元提供。
* [WildFly](https://www.wildfly.org/downloads/)：WildFly是一款功能强大、模块化且轻量级的应用程序服务器。
* [BES Application Server](https://www.bessystem.com/product/0ad9b8c4d6af462b8d15723a5f25a87d/info?p=101#page-2)：一款遵循JavaEE标准的面向Java应用的通用中间件，由宝兰德提供。
* [ManageFish Server](https://managecat.com/products/managed-glassfish)：ManageFish是Eclipse GlassFish应用服务器版本的商业支持的发行版。
* [Oracle WebLogic](https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html)：WebLogic是Oracle出品的用于开发、集成、部署和管理大型分布式Web应用、网络应用和数据库应用的Java应用服务器。
* [RockyAS](https://rockyasfile.obs-cn-shenzhen.pinganyun.com/RockyAS.html)：Rocky是一款标准、安全、高效的Web应用服务器，为企业级应用系统的便捷开发、灵活部署、可靠运行、高效管理及快速集成提供关键支撑能力，由平安云提供。
* [TongWeb Application Server](https://www.tongtech.com/dft/pctype/25.html)：TongWeb是一款全面符合Java EE、Jakarta EE最新标准规范、轻量易于使用、性能强大、具有高可靠性和高安全性的应用服务器产品，由东方通提供。
* [WebOTX Application Server](https://jpn.nec.com/webotx/appserver/index.html)：一个Java应用程序执行平台，非常适合在从本地到云的各种IT资源中推广DX，这是日本电气公司的产品。
* [Xigema Application Server](http://www.vsettan.com.cn/7752.html)：XigemaAS是企业级应用服务器产品，完全符合Java EE 7规范， 产品架构基于OSGi内核，高模块化、高动态性、强扩展性、轻量且配置简单，为企业应用提供稳定、高效、安全的运行引擎和支撑平台，这是华胜信泰的产品。
* [Thunisoft Application Server](https://www.thunisoft.cn/col81/index)：华宇自主研发的企业级中间件产品，符合Jakarta EE标准的轻量级服务器。

<h2 id="utils">工具库</h2>

* [Guava](https://github.com/google/guava)：Google开源的Java工具库。
* [Apache Commons](https://github.com/apache/commons-lang)：Apache下的Java工具库。
* [Lombok](https://github.com/projectlombok/lombok)：对Java语法非常有用的补充，消除大量样板代码。
* [Hutool](https://github.com/dromara/hutool)：功能极其丰富的Java工具库，由dromara社区开源。
* [NullAway](https://github.com/uber/NullAway)：一种帮助消除Java代码中NullPointerExceptions(NPE)的工具，由Uber开源。
* [Cactoos](https://github.com/yegor256/cactoos)：面向对象的Java原始类型，作为Google Guava和Apache Commons的替代品。
* [JCommon](https://github.com/facebookarchive/jcommon)：Facebook开源的Java工具库，含并发、集合、统计/分析、配置、测试等功能。
* [Jodd](https://github.com/oblac/jodd)：零依赖的Java工具库。
* [Ph-Commons](https://github.com/phax/ph-commons)：Java 11库，包含所有项目所需的大量实用程序类。
* [Essentials](https://github.com/greenrobot/essentials)：适用于Android和Java的通用实用程序和哈希函数。
* [Twitter Commons](https://github.com/twitter-archive/commons)：Twitter的JVM公共库，已弃用。
* [ModiTect](https://github.com/moditect/moditect)：Java 9模块系统工具库。
* [Annotations](https://github.com/JetBrains/java-annotations)：一组可在基于JVM的语言中使用的Java注解，由JetBrains开源。
* [JUtils](https://github.com/chenssy89/jutils)：通用的Java工具类库。
* [SOFA-Common](https://github.com/sofastack/sofa-common-tools)：sofa-common-tools是一个为其他SOFA库提供一些实用功能的库。
* [Commons Core](https://github.com/ponfee/commons-core)：Java工具类库。
* [XXL-TOOL](https://github.com/xuxueli/xxl-tool)：XXL-TOOL是一个Java工具类库，包含集合、缓存、并发、字符串、IO、Excel、Emoji等数十个模块。
* [xUtils](https://github.com/wyouflf/xUtils3)：xUtils包含了ORM、HTTP、图片处理等工具类。
* [TypeTools](https://github.com/jhalterman/typetools)：一个用于处理类型的简单、零依赖库，支持 Java 1.6+和Android。
* [Apache Commons Text](https://github.com/apache/commons-text)：Apache Commons Text是一个专注于字符串算法的库。
* [Apache Commons BSF](https://github.com/apache/commons-bsf)：BSF是一组Java类，它在Java应用程序中提供脚本语言支持，并通过脚本语言访问Java对象和方法。
* [Apache Commons Chain](https://github.com/apache/commons-chain)：GoF责任链模式的实现。
* [Apache Commons Codec](https://github.com/apache/commons-codec)：Apache Commons Codec包含各种格式(例如Base64和十六进制)的简单编码器和解码器。
* [Apache Commons Daemon](https://github.com/apache/commons-daemon)：Apache Commons Daemon是一组实用程序和Java支持类，用于将Java应用程序作为服务器进程运行。
* [Apache Commons Digester](https://github.com/apache/commons-digester)：Apache Commons Digester包允许你配置XML到Java对象映射模块，每当识别出嵌套XML元素的特定模式时，该模块就会触发称为规则的某些操作。
* [Apache Commons Exec](https://github.com/apache/commons-exec)：Apache Commons Exec是一个从JVM内可靠地执行外部进程的库。
* [Apache Commons FileUpload](https://github.com/apache/commons-fileupload)：Apache Commons FileUpload组件提供了一种简单而灵活的方法来向Servlet和Web应用程序添加对分段文件上传功能的支持。
* [Apache Commons JCI](https://github.com/apache/commons-jci)：Apache Commons JCI是一个Java编译器接口，它可用于编译Java本身，或任何其他可编译为Java类的语言(例如Groovy或JavaScript)。
* [Apache Commons Jelly](https://github.com/apache/commons-jelly)：Apache Commons Jelly是一个基于Java和XML的脚本引擎。
* [Apache Commons JEXL](https://github.com/apache/commons-jexl)：Apache Commons JEXL库是Java共生表达式语言的实现。
* [Apache Commons OGNL](https://github.com/apache/commons-ognl)：OGNL代表对象图导航语言；它是一种表达式语言，用于获取和设置Java对象的属性，以及其他附加功能，例如列表投影和选择以及Lambda表达式。
* [Apache Commons Pool](https://github.com/apache/commons-pool)：Apache Commons对象池库。
* [Apache Commons Proxy](https://github.com/apache/commons-proxy)：用于动态代理的Java库。

<h2 id="di">依赖注入</h2>

* [Spring](https://github.com/spring-projects/spring-framework)：Spring生态中的依赖注入框架。
* [Guice](https://github.com/google/guice)：Guice是一个适用于Java 8及更高版本的轻量级依赖注入框架，由Google提供。
* [Dagger](https://github.com/google/dagger)：适用于Android和Java的快速依赖注入器。
* [Koin](https://github.com/InsertKoinIO/koin)：适用于Kotlin和Kotlin多平台的实用轻量级依赖注入框架。
* [PicoContainer](https://github.com/picocontainer/picocontainer)：古老的Java依赖注入库。
* [Avaje-Inject](https://github.com/avaje/avaje-inject)：面向服务端开发人员的基于APT的依赖注入。
* [Eclipse HK2](https://github.com/eclipse-ee4j/glassfish-hk2)：轻量级动态依赖注入框架。
* [Apache DeltaSpike](https://github.com/apache/deltaspike)：Apache DeltaSpike是一套可移植的CDI扩展。
* [Javax-Inject](https://github.com/javax-inject/javax-inject)：JSR-330依赖注入标准。
* [CDI](https://www.cdi-spec.org/)：CDI规范，定义了一组强大的补充服务。
* [Apache OpenWebBeans](https://github.com/apache/openwebbeans)：Apache OpenWebBeans是上下文和依赖注入2.0规范(CDI-2.0)的实现。
* [Sisu](https://github.com/eclipse/sisu.inject)：Sisu是一个基于JSR330的模块化容器，支持类路径扫描、自动绑定和动态自动装配。
* [Weld](https://github.com/weld/core)：Weld是CDI的参考实现。
* [Coody](https://gitee.com/coodyer/Coody-Framework)：国产IOC框架，轻量级、简单快速。
* [Scaldi](https://github.com/scaldi/scaldi)：轻量级Scala依赖注入库。
* [Kodein](https://github.com/kosi-libs/Kodein)：Kotlin依赖注入。
* [Transfuse](https://github.com/johncarl81/transfuse)：Google Android的依赖注入和集成框架。
* [Governator](https://github.com/Netflix/governator)：Governator是一个扩展和实用程序库，可增强Google Guice的功能，提供类路径扫描和自动绑定、生命周期管理、字段映射配置、字段验证和并行对象预热等功能，由Netflix开源。

<h2 id="aop">AOP</h2>

* [AspectJ](https://eclipse.dev/aspectj/)：一个易用的功能强大的AOP框架。
* [JVM-SANDBOX](https://github.com/alibaba/jvm-sandbox)：基于JVM的实时非侵入式AOP框架容器。
* [JBossAop](https://jbossaop.jboss.org/)：JBoss AOP是一个100%纯Java面向切面的框架，可在任何编程环境中使用或与我们的应用程序服务器紧密集成。
* [Apache Commons Weaver](https://github.com/apache/commons-weaver)：Apache Commons Weaver提供了一种通过生成(“织入”)字节码到这些类中来增强已编译Java类的简单方法。
* [FastAop](https://github.com/fast-light/fastaop)：基于Java注解处理的轻量级高性能AOP框架，类似于Lombok。
* [Alliance](https://aopalliance.sourceforge.net/)：Alliance项目是几个对AOP和Java感兴趣的软件工程人员联合发起的开源项目。
* [Lancet](https://github.com/eleme/lancet)：面向Android App和SDK开发人员的轻量级快速AOP框架。
* [jcabi-aspects](https://github.com/jcabi/jcabi-aspects)：AspectJ Java切面的集合，促进面向切面的编程模式：日志记录、缓存、验证等。
* [Eclipse AspectJ](https://github.com/eclipse-aspectj/aspectj)：Java编程语言的无缝面向切面扩展。

<h2 id="log">日志库</h2>

* [Log4j](https://github.com/apache/logging-log4j1)：Log4j的初始版本，已经停止维护。
* [Log4j2](https://github.com/apache/logging-log4j2)：一个多功能、功能丰富、高效的Java日志记录API。
* [Logback](https://github.com/qos-ch/logback)：可靠、通用、快速且灵活的Java日志记录框架。
* [Slf4j](https://github.com/qos-ch/slf4j)：Java的简单日志门面。
* [Flogger](https://github.com/google/flogger)：适用于Java的流式日志记录API，由Google开发。
* [Apache Commons Logging](https://github.com/apache/commons-logging)：Apache下的通用日志记录接口。
* [Logstash](https://github.com/elastic/logstash)：传输和处理日志、事件或其他数据。
* [Twitter-Logging](https://github.com/twitter/util/tree/develop/util-logging)：Twitter开发的日志工具库。
* [Tinylog](https://github.com/tinylog-org/tinylog)：适用于Java、Kotlin、Scala和Android的轻量级日志框架。
* [Graylog](https://github.com/Graylog2/graylog2-server)：Graylog是一个免费开放的日志管理平台。
* [Blitz4j](https://github.com/Netflix/blitz4j)：用于固定异步日志记录的日志记录框架，由Netflix开源。
* [Kotlin Logging](https://github.com/oshai/kotlin-logging)：Kotlin的轻量级多平台日志框架。
* [DistributedLog](https://github.com/apache/distributedlog)：DistributedLog(DL)是一种高吞吐量、低延迟的复制日志服务，提供持久性、复制和强一致性，由Twitter开发。
* [JBoss Logging](https://github.com/jboss-logging/jboss-logging)：JBoss开源的日志库。
* [Timbermill](https://github.com/salesforce/Timbermill)：Timbermill是专为Elasticsearch构建的高级开源日志服务。
* [Scala Logging](https://github.com/lightbend-labs/scala-logging)：用于包装Slf4j的Scala的方便且高性能的日志记录库。
* [Logger](https://github.com/orhanobut/logger)：简单、功能强大的Android记录器。
* [Timber](https://github.com/JakeWharton/timber)：具有小型可扩展API的日志记录器。
* [Plumelog](https://gitee.com/plumeorg/plumelog)：国产的分布式日志收集系统。
* [Logbook](https://github.com/zalando/logbook)：用于HTTP请求和响应日志记录的可扩展Java库，由Zalando开源。
* [xLog](https://github.com/elvishew/xLog)：适用于Android和Java的轻量、强大且灵活的记录器。
* [TLog](https://gitee.com/dromara/TLog)：dromara社区开源的轻量级分布式日志标记追踪框架。
* [JLog](https://gitee.com/jd-platform-opensource/jlog)：京东开源的海量日志搜集、传输、存储解决方案。
* [P6Spy](https://github.com/p6spy/p6spy)：P6Spy是一个框架，无需对应用程序进行任何代码更改即可无缝拦截和记录数据库数据。

<h2 id="graphql">GraphQL</h2>

* [GraphQL Java](https://github.com/graphql-java/graphql-java)：GraphQL Java实现。
* [DGS-Framework](https://github.com/netflix/dgs-framework)：DGS(Domain Graph Service)框架是由Netflix开发的Spring Boot的GraphQL服务器框架。
* [Apollo Kotlin](https://github.com/apollographql/apollo-kotlin)：适用于JVM、Android和Kotlin多平台的强类型缓存GraphQL客户端。
* [Rejoiner](https://github.com/google/rejoiner)：用于从gRPC微服务和其他Protobuf源生成统一的GraphQL模式，由Google开发。
* [Spring GraphQL](https://github.com/spring-projects/spring-graphql)：GraphQL的Spring集成。
* [GraphQL Kotlin](https://github.com/ExpediaGroup/graphql-kotlin)：构建在graphql-java之上，可简化在Kotlin中运行GraphQL客户端和服务器。
* [GraphQL SPQR](https://github.com/leangen/graphql-spqr)：可以让任何Java项目添加GraphQL API变得非常简单，它的工作原理是从Java代码动态生成GraphQL模式。
* [GraphQL SPQR Starter](https://github.com/leangen/graphql-spqr-spring-boot-starter)：由GraphQL SPQR提供支持的Spring Boot Starter。
* [GraphQL Spring Boot](https://github.com/graphql-java-kickstart/graphql-spring-boot)：集成GraphQL Java和Spring Boot的库。
* [Elide](https://github.com/yahoo/elide)：Elide是一个Java库，可以轻松设置模型驱动的GraphQL或JSON API Web服务，由Yahoo开源。
* [GraphQL-Java Annotations](https://github.com/Enigmatis/graphql-java-annotations)：该库为GraphQL模式定义提供基于注解的语法。
* [KGraphQL](https://github.com/aPureBase/KGraphQL)：GraphQL的纯Kotlin实现。
* [GraphQL-Calculator](https://github.com/graphql-calculator/graphql-calculator)：一个轻量级的GraphQL计算引擎，用于改变查询的执行行为。
* [Microprofile GraphQL](https://github.com/eclipse/microprofile-graphql)：MicroProfile框架中用于构建GraphQL应用程序的GraphQL服务器和客户端规范。
* [Nodes](https://github.com/americanexpress/nodes)：Nodes是一个GraphQL客户端，旨在根据标准模型定义构建查询。
* [GraphQL Java Generator](https://github.com/graphql-java-generator/graphql-maven-plugin-project)：GraphQL Java生成器可以轻松地以模式优先的方式在Java中使用GraphQL。
* [GraphQL Codegen](https://github.com/kobylynskyi/graphql-java-codegen)：GraphQL Java代码生成器可以轻松地让你的Java应用程序遵循模式优先的方法，无论它是服务器应用程序还是客户端应用程序。
* [GraphQL JPA](https://github.com/introproventures/graphql-jpa-query)：可以为JPA实体模型生成GraphQL查询API。
* [HyperGraphQL](https://github.com/hypergraphql/hypergraphql)：HyperGraphQL是一个GraphQL接口，用于在Web上查询和提供链接数据。

<h2 id="job">任务调度</h2>

* [XXL-JOB](https://github.com/xuxueli/xxl-job)：分布式任务调度平台。
* [Quartz](https://github.com/quartz-scheduler/quartz)：老牌任务调度框架。
* [ElasticJob](https://github.com/apache/shardingsphere-elasticjob)：当当网开源的分布式任务调度框架，基于Quartz二次开发。
* [PowerJob](https://github.com/PowerJob/PowerJob)：具有分布式计算能力的企业作业调度中间件。
* [Spring Task](https://docs.spring.io/spring-framework/reference/integration/scheduling.html#scheduling-task-scheduler)：Spring提供的任务调度集成。
* [Jobrunr](https://github.com/jobrunr/jobrunr)：一种在Java中执行后台处理的极其简单的方法，由持久存储支持。
* [SchedulerX](https://www.aliyun.com/aliware/schedulerx)：阿里开发的基于Akka架构的分布式任务调度平台。
* [ShedLock](https://github.com/lukas-krecan/ShedLock)：调度任务的分布式锁。
* [DisJob](https://gitee.com/dromara/disjob)：dromara社区开源的分布式任务调度框架。
* [Saturn](https://github.com/vipshop/Saturn)：唯品会开源的分布式作业调度平台。
* [Apache Aurora](https://github.com/apache/aurora)：用于长时间运行的服务、cron作业和临时作业的Mesos框架，该项目在Apache基金会下已经退役。
* [DB Scheduler](https://github.com/kagkarlsson/db-scheduler)：适用于Java的持久集群友好调度程序。
* [OpenJob](https://github.com/open-job/openjob)：分布式高性能任务调度框架。
* [PlumeJob](https://gitee.com/plumeorg/plumejob)：PlumeJob是一个去中心化的分布式调度系统，集成简单易用，并可和PlumeLog整合。
* [Sundial](https://github.com/knowm/Sundial)：轻量级的作业调度框架。
* [Wisp](https://github.com/Coreoz/Wisp)：一个简单的Java调度库，具有最小的占用空间和简单的API。
* [Android Job](https://github.com/Evernote/android-job)：用于在后台处理作业的Android库，由Evernote开源。
* [Cron4j](http://www.sauronsoftware.it/projects/cron4j/)：古老的Java平台调度程序。
* [Job-Dispatcher](https://gitee.com/daye_daye/job-dispatcher)：国产的基于事件的流程编排和调度引擎。
* [SIA-TASK](https://github.com/siaorg/sia-task)：微服务任务调度框架。
* [Jobs](https://gitee.com/baomidou/jobs)：baomidou社区开源的分布式任务调度组件。
* [Light Task Scheduler](https://github.com/ltsopensource/light-task-scheduler)：分布式作业调度框架。
* [Chronus](https://github.com/360digitech/chronus)：Chronus是360金融技术团队基于阿里开源项目TBSchedule进行重写的分布式调度平台。

<h2 id="configuration">配置库</h2>

* [Config](https://github.com/lightbend/config)：使用HOCON文件的JVM语言的配置库。
* [Microconfig](https://github.com/microconfig/microconfig)：用于微服务配置管理的现代工具。
* [Spring Cloud Config](https://github.com/spring-cloud/spring-cloud-config)：Spring Cloud Config为分布式系统中的外部化配置提供服务器端和客户端支持。
* [BRCC](https://github.com/baidu/brcc)：BRCC是一个分布式配置中心，用于统一管理应用服务的配置信息，由百度开源。
* [Disconf](https://github.com/knightliao/disconf)：专注于各种分布式系统配置管理的通用组件和通用平台，提供统一的配置管理服务。
* [CentralDogma](https://github.com/line/centraldogma)：Central Dogma是一个基于Git、ZooKeeper和HTTP/2的开源、高可用、版本控制的服务配置存储库，由Line开源。
* [XXL-Conf](https://github.com/xuxueli/xxl-conf)：轻量级分布式配置管理平台。
* [Spring-Fu](https://github.com/spring-projects-experimental/spring-fu)：Spring Fu是JaFu(Java DSL)和KoFu(Kotlin DSL)的孵化器，旨在以声明性方式使用代码显式配置Spring Boot。
* [Apache Commons Configuration](https://github.com/apache/commons-configuration)：协助读取各种格式的配置/首选项文件的工具。
* [NightConfig](https://github.com/TheElectronWill/night-config)：强大的Java配置库，适用于Toml、Yaml、Hocon、Json和内存配置。
* [Archaius](https://github.com/Netflix/archaius)：Archaius是一个配置库，用于将静态和动态配置的混合作为单个配置单元进行访问，由Netflix开源。
* [CFG4J](https://github.com/cfg4j/cfg4j)：用Java编写的分布式应用程序的现代配置库。
* [Configurate](https://github.com/SpongePowered/Configurate)：一个简单的Java应用程序配置库，提供节点结构、多种格式和转换工具。
* [Directories](https://github.com/dirs-dev/directories-jvm)：一个提供配置/缓存/数据路径的小型库，遵循Linux、macOS、BSD和Windows上的相应约定。
* [MicroProfile-Config](https://github.com/eclipse/microprofile-config)：MicroProfile框架提供的配置功能。
* [Smallrye-Config](https://github.com/smallrye/smallrye-config)：Smallrye提供的配置库。
* [Apache Yetus](https://github.com/apache/yetus)：Apache Yetus是一个库和工具的集合，支持软件项目的贡献和发布过程。
* [Diablo](https://github.com/ihaolin/diablo)：轻量的分布式配置管理平台。
* [OWNER](https://github.com/matteobaccan/owner)：可以最大限度地减少通过Java属性文件处理应用程序配置所需的代码。

<h2 id="bpm">业务流</h2>

* [Activiti](https://github.com/Activiti/Activiti)：Activiti是一个轻量级工作流程和业务流程管理(BPM)平台，面向业务人员、开发人员和系统管理员。
* [Flowable](https://github.com/flowable/flowable-engine)：为开发人员、系统管理员和业务用户提供紧凑且高效的工作流程和业务流程管理(BPM)平台。
* [Camunda](https://github.com/camunda/camunda-bpm-platform)：使用BPMN和DMN实现工作流程和决策自动化的灵活框架。与Spring、Spring Boot、CDI集成。
* [Apache Dolphinscheduler](https://github.com/apache/dolphinscheduler)：Apache DolphinScheduler是现代数据编排平台，以低代码敏捷创建高性能工作流程，由易观开源。
* [jBPM](https://github.com/kiegroup/jbpm)：业务流程管理(BPM)套件。
* [Piper](https://github.com/runabol/piper)：分布式工作流引擎。
* [Turbo](https://github.com/didi/turbo)：一款轻量级流程引擎服务框架，可作为底层服务支持各类流程设计、低代码设计、工作流、服务编排等场景，由滴滴开源。
* [Zeebe](https://github.com/camunda/zeebe)：用于微服务编排的分布式工作流引擎。
* [Compileflow](https://github.com/alibaba/compileflow)：阿里开源的高性能流程编排引擎。
* [Bulbasaur](https://github.com/alibaba/bulbasaur)：阿里开源的可插拔的精简流程引擎，可快速实现流程、审批、业务失败重试等场景。
* [SmartEngine](https://github.com/alibaba/SmartEngine)：阿里开源的一个轻量级的业务编排引擎。
* [Kestra](https://github.com/kestra-io/kestra)：Kestra是一个无限可扩展的编排和调度平台，可创建、运行、调度和监控数百万个复杂的管道。
* [Azkaban](https://github.com/azkaban/azkaban)：Azkaban是LinkedIn创建的批处理工作流作业调度程序，用于运行Hadoop作业。
* [Imixs-Workflow](https://github.com/imixs/imixs-workflow)：用于业务流程管理的开源框架。
* [Bonita](https://github.com/bonitasoft/bonita-engine)：部署、执行、管理使用Bonita studio或通过Engine API制作的基于流程的应用程序。
* [Digdag](https://github.com/treasure-data/digdag)：工作负载自动化系统。
* [Cadence](https://github.com/uber/cadence-java-client)：Cadence工作流服务的Java框架，由Uber开发。
* [AgileBPM](https://gitee.com/agile-bpm)：快速、简洁且强大的低代码流程开发平台。
* [Schedulis](https://github.com/WeBankFinTech/Schedulis)：Schedulis是一个基于LinkedIn的开源项目Azkaban开发的工作流任务调度系统，由微众开源。
* [TestHub](https://gitee.com/dromara/TestHub)：基于流程编排的国产自动化测试工具。
* [FlowLong](https://gitee.com/aizuda/flowlong)：国产开源的工作流引擎。
* [Concord](https://github.com/walmartlabs/concord)：Concord是一个工作流服务器，它是使用用户创建的场景和插件将不同系统连接在一起的编排引擎。
* [JsonFlow](https://gitee.com/jackrolling/jsonflow-ui)：简单但强大易用易扩展且适应复杂场景的中国式审批的工作流引擎系统。

<h2 id="ruleengine">规则引擎</h2>

* [Drools](https://github.com/kiegroup/drools)：Drools是Java的规则引擎、DMN引擎和复杂事件处理(CEP)引擎。
* [Easy Rules](https://github.com/j-easy/easy-rules)：简单的Java规则引擎。
* [Liteflow](https://github.com/dromara/liteflow)：dromara开源的轻量级、快速、稳定、可编程的基于组件的规则引擎/流程引擎。
* [Radar](https://github.com/wfh45678/radar)：一款基于Java语言，使用Spring Boot + MongoDB + Groovy + Es等框架搭建的轻量级实时风控引擎。
* [RuleBook](https://github.com/deliveredtechnologies/rulebook)：纯Java、支持Lambda的轻量级规则引擎，具有简单直观的DSL。
* [RuleEngine](https://github.com/Hale-Lee/RuleEngine)：非常好用的规则引擎，可以直接使用SQL语句定义规则，简化了编码的负荷，也可以使用XML、drl文件配置规则，还支持drools文件导入。
* [Evrete](https://github.com/evrete/evrete)：Evrete是一个轻量级且直观的Java规则引擎。
* [OpenL Tablets](https://github.com/openl-tablets/openl-tablets)：业务规则管理系统。
* [Jess](http://alvarestech.com/temp/fuzzyjess/Jess60/Jess70b7/docs/index.html)：Jess是最早能够轻松与Java集成的规则引擎之一。
* [dataframe-rules-engine](https://github.com/databrickslabs/dataframe-rules-engine)：用于自定义数据框/数据集验证的可扩展规则引擎。

<h2 id="lowcode">低代码平台</h2>

* [JeeSite](https://gitee.com/thinkgem/jeesite4)：JeeSite快速开发平台，不仅仅是一个后台开发框架，更是一个企业级快速开发解决方案。
* [Guns](https://gitee.com/stylefeng/guns)：Guns是一个现代化的Java应用开发基础框架，基于主流技术Spring Boot，配套代码生成平台、DevOps运维平台、CI/CD持续集成能力、在线API接口管理。
* [Maku Boot](https://gitee.com/makunet/maku-boot)：采用Spring Boot 3.1、Spring Security 6.1、MybatisPlus等框架开发的一套Spring Boot低代码开发平台。
* [MateCloud](https://gitee.com/matevip/matecloud)：基于Spring Cloud Alibaba的微服务架构，支持多租户的低代码平台。
* [JeecgBoot](https://gitee.com/jeecg/jeecg-boot)：JeecgBoot是一款基于代码生成器的低代码开发平台，前后端分离架构Spring Boot 2.x、Spring Cloud、Ant Design & Vue、MybatisPlus、Shiro、JWT，支持微服务。
* [DiBoot](https://github.com/dibo-software/diboot)：为开发人员打造的低代码开发平台。
* [OPSLI](https://github.com/hiparker/opsli-boot)：OPSLI是一款低代码快速平台，零代码开发，致力于更简洁的后台管理系统。
* [RESTHeart](https://github.com/SoftInstigate/restheart)：开源低代码API开发框架，具有现成的安全性和MongoDB API。
* [Structr](https://github.com/structr/structr)：Structr是一个使用图数据库的集成低代码开发和运行时环境，使用Structr，可以比传统开发方法更快地构建企业Web应用程序。
* [DBApi](https://github.com/freakchick/DBApi)：DBAPI是一款为开发者提供的低代码工具，只需在页面上编写SQL并配置参数即可自动生成HTTP API。
* [Citrus](https://github.com/Yiuman/citrus)：低代码快速开发脚手架，灵活、高效。
* [Convertigo](https://github.com/convertigo/convertigo)：Convertigo是一个开源低代码平台，包括用于全栈移动和Web应用程序开发的无代码应用程序构建器。
* [Orienteer](https://github.com/OrienteerBAP/Orienteer)：业务应用程序平台-用于构建业务应用程序的无代码/低代码平台。
* [Open Lowcode](https://github.com/openlowcode/Open-Lowcode)：特定企业软件快速开发解决方案。
* [LAMP Cloud](https://github.com/dromara/lamp-cloud)：基于JDK 11、Spring Cloud、Spring Boot开发的微服务中后台快速开发平台，专注于多租户(SaaS架构)解决方案，由dromara社区开源。
* [Portofino](https://github.com/ManyDesigns/Portofino)：Portofino 5是下一代开源低代码Web框架，其目的是帮助开发人员使用REST API和Angular UI创建现代的、响应式的企业应用程序。
* [Jianmu](https://github.com/jianmu-dev/jianmu)：健木是一款易于扩展的开源NoCode(Graphical)/LowCode(GitOps) DevOps工具。
* [Skyeye](https://gitee.com/doc_wei01/skyeye)：智能制造一体化，采用Spring Boot + WinUI的低代码平台开发模式。
* [diboot](https://gitee.com/dibo_software/diboot)：为开发人员打造的低代码开发平台。
* [Erupt](https://github.com/erupts/erupt)：Erupt是一个低代码全栈类框架，使用Java注解动态生成页面以及增、删、改、查、权限控制等后台功能。

<h2 id="erp">ERP系统</h2>

* [华夏ERP](https://gitee.com/jishenghua/JSH_ERP)：基于Spring Boot框架和SaaS模式开源的ERP软件，目前专注进销存、财务、生产功能。
* [赤龙ERP](https://gitee.com/redragon/redragon-erp)：一款免费开源、业务闭环、灵活稳定的企业级ERP系统。
* [metasfresh](https://github.com/metasfresh/metasfresh)：metasfresh是一个响应迅速、免费且开源的ERP系统。
* [REBUILD](https://gitee.com/getrebuild/rebuild)：REBUILD通过创新的业务流程引擎帮助你快速搭建各类企业管理系统，全图形化配置无需了解技术。
* [OMS](https://github.com/FJ-OMS/oms-erp)：一站式全渠道业务中台系统，包括订单管理系统OMS/电商ERP、库存WMS统一管理系统和SAP财务管理系统等。
* [ADempiere](https://github.com/adempiere/adempiere)：ADempiere Business Suite ERP/CRM/MFG/SCM/POS以开放且不减的方式实现了Bazaar方式。
* [Apache OFBiz](https://github.com/apache/ofbiz-framework)：Apache OFBiz是一个用于企业流程自动化的开源产品，它包括 ERP、CRM、电子商务/电子商务、供应链管理和制造资源规划的框架组件和业务应用程序。
* [iDempiere](https://github.com/idempiere/idempiere)：完全开源商务套件ERP/CRM/MFG/SCM/POS。
* [ERP-Pro](https://gitee.com/doc_wei01/erp-pro)：基于Spring Boot框架，为中小企业打造的开源好用ERP软件。

<h2 id="business">业务</h2>

* [EventHub](https://github.com/Codecademy/EventHub)：开源事件分析平台。
* [Liferay](https://github.com/liferay/liferay-portal)：Liferay Portal是一个开源企业Web平台，用于构建可提供即时结果和长期价值的业务解决方案。
* [BroadleafCommerce](https://github.com/BroadleafCommerce/BroadleafCommerce)：BroadleafCommerce是一个完全用Java编写并利用Spring框架的电子商务框架。
* [Spring Roo](https://github.com/spring-attic/spring-roo)：Spring Roo是面向Java开发人员的下一代快速应用程序开发工具。它专注于更高的生产率、标准Java API、高可用性、避免工程权衡并促进轻松删除Roo。
* [Apache Protals](http://portals.apache.org/)：Apache Portals项目提供各种软件产品，包括Apache Jetspeed-2、Apache Pluto和Apache Portals Applications。
* [Apache ODE](https://ode.apache.org/)：Apache ODE是一种WS-BPEL实现，它支持使用灵活的流程定义进行Web服务编排。
* [Spring Integration](https://github.com/spring-projects/spring-integration)：Spring Integration提供了Spring编程模型的扩展，以支持众所周知的企业集成模式(EIP)。

<h2 id="pay">支付</h2>

* [WxJava](https://gitee.com/binary/weixin-java-tools)：微信开发Java SDK，支持微信支付、开放平台、公众号、企业号/企业微信、小程序等的后端开发。
* [Jeepay](https://gitee.com/jeequan/jeepay)：Jeepay是一套适合互联网企业使用的开源支付系统，支持多渠道服务商和普通商户模式。
* [IJPay](https://gitee.com/javen205/IJPay)：封装了微信支付、QQ支付、支付宝支付、京东支付、银联支付、PayPal支付等常用的支付方式以及各种常用的接口。
* [Roncoo-Pay](https://gitee.com/roncoocom/roncoo-pay)：龙果支付系统是国内首款开源的互联网支付系统，拥有独立的账户体系、用户体系、支付接入体系、支付交易体系、对账清结算体系。
* [Pay-Java](https://gitee.com/egzosn/pay-java-parent)：全能第三方支付对接Java开发工具包。
* [Pay-SDK](https://github.com/Pay-Group/best-pay-sdk)：支付宝、微信支付SDK。
* [PayPal](https://github.com/paypal/PayPal-Android-SDK)：接入PayPal支付的Android SDK。
* [IJPay](https://github.com/Javen205/IJPay)：封装了微信支付、QQ支付、支付宝支付、京东支付、银联支付、PayPal支付等常用的支付方式以及各种常用的接口。
* [KillBill](https://github.com/killbill/killbill)：KillBill在过去10年中一直是领先的开源订阅计费和支付平台，该平台的存在是为了帮助扩展计费和支付基础设施并发展业务。
* [微信支付Java SDK](https://github.com/YClimb/wxpay-sdk)：最新最全微信支付集成SDK，一行代码调用微信支付，包含基础支付功能。
* [微信支付API v3](https://github.com/wechatpay-apiv3/wechatpay-java)：微信支付API v3的官方Java SDK。
* [Paypal](https://github.com/paypal/Checkout-Java-SDK)：PayPal结账Java SDK。
* [Alipay](https://github.com/alipay/alipay-easysdk)：支付宝开放平台服务端SDK。
* [YunGouOS-PAY-SDK](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK)：微信/支付宝官方服务商接口(支持个人、个体户、企业)签约开通。
* [Payment-Spring-Boot](https://gitee.com/dromara/payment-spring-boot)：Java微信支付V3支付Spring Boot Starter，支持微信优惠券，代金券、商家转账到零钱、公众号支付、微信小程序支付、电商收付通等全部微信支付功能API。
* [EMV-NFC-Paycard-Enrollment](https://github.com/devnied/EMV-NFC-Paycard-Enrollment)：用于从NFC EMV信用卡读取和提取公共数据的Java库。

<h2 id="api-manage">API管理</h2>

* [XXL-API](https://github.com/xuxueli/xxl-api)：XXL-API是一个强大易用的API管理平台，提供API的管理、文档、Mock和测试等功能。
* [WSO2 API Manager](https://github.com/wso2/product-apim)：WSO2 API Manager是一个用于创建、管理、使用和监控Web API的强大平台。
* [Apiman](https://github.com/apiman/apiman)：Apiman是一个灵活的开源API管理平台，由RedHat开源。
* [Japicmp](https://github.com/siom79/japicmp)：Japicmp是一个比较Jar存档的两个版本的工具。
* [CrapApi](https://gitee.com/CrapApi/CrapApi)：一个由AngularJS + Bootstrap + Spring MVC + Mybatis搭建的免费开源的API接口管理系统、BUG管理系统、文档管理系统。
* [Zyplayer DOC](https://gitee.com/dromara/zyplayer-doc)：Zyplayer DOC是一款适合团队和个人使用的WIKI文档管理工具，同时还包含数据库文档、API接口文档，由dromara社区开源。
* [EasyOpen](https://gitee.com/durcframework/easyopen)：一个简单易用的接口开放平台，平台封装了常用的参数校验、结果返回等功能。
* [Torna](https://gitee.com/durcframework/torna)：接口文档解决方案，目标是让接口文档管理变得更加方便、快捷。

<h2 id="cache">缓存库</h2>

* [Guava](https://github.com/google/guava/tree/master/guava/src/com/google/common/cache)：Guava库提供的Java本地缓存工具。
* [Caffeine](https://github.com/ben-manes/caffeine)：Java的高性能缓存库。
* [Ehcache](https://github.com/ehcache/ehcache3)：一个纯Java的进程内缓存框架。
* [Apache Commons JCS](https://github.com/apache/commons-jcs)：Apache Commons JCS是一个分布式、多功能的缓存系统。
* [JetCache](https://github.com/alibaba/jetcache)：阿里开源的Java缓存框架。
* [DiskLruCache](https://github.com/JakeWharton/DiskLruCache)：基于磁盘的LRU缓存的Java实现，专门针对Android兼容性。
* [ASimpleCache](https://github.com/yangfuhai/ASimpleCache)：ASimpleCache是一个为Java和Android制定的轻量级开源缓存框架。
* [RxCache](https://github.com/VictorAlbertos/RxCache)：适用于Android和Java的响应式缓存库。
* [Infinispan](https://github.com/infinispan/infinispan)：针对缓存的高并发键值对数据存储。
* [EVCache](https://github.com/Netflix/EVCache)：云分布式内存数据存储。
* [Cache2K](https://github.com/cache2k/cache2k)：轻量级、高性能Java缓存。
* [AutoLoadCache](https://github.com/qiujiayu/AutoLoadCache)：基于AOP+注解等技术实现的高效的缓存管理解决方案。
* [J2Cache](https://gitee.com/ld/J2Cache)：Java二级缓存框架，可以让应用支持两级缓存框架Ehcache(Caffeine) + redis。
* [RedisCache](https://gitee.com/darkidiot/RedisCache)：RedisCache是基于Jedis的SDK。
* [XXL-CACHE](https://github.com/xuxueli/xxl-cache)：XXL-CACHE是一个分布式缓存管理平台，其核心设计目标是让分布式缓存的接入和管理的更加的简洁和高效。

<h2 id="file-parse">文件解析</h2>

这里包含用于解析各种文件格式的库，例如PDF、Word、Excel、CSV等。

<h4 id="pdf">PDF库</h4>

* [Apache PDFBox](https://pdfbox.apache.org/)：Apache下用于处理PDF文档的开源Java工具。
* [iText](https://github.com/itext/itext7)：一个易于使用的PDF函数库，用来编程创建PDF文件。
* [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF)：本地托管的Web应用程序，允许你对PDF文件执行各种操作。
* [Flying Saucer](https://github.com/seam/reports)：Java EE的可移植扩展，提供用于从现有报告框架(JasperReports等)编译、填充和呈现报告(Excel、PDF等)的API。
* [OpenPDF](https://github.com/LibrePDF/OpenPDF)：OpenPDF是一个免费的Java库，用于使用LGPL和MPL开源许可证创建和编辑PDF文件。
* [X-EasyPDF](https://gitee.com/dromara/x-easypdf)：dromara开源的PDF文档库。
* [PDF2JSON](https://github.com/modesty/pdf2json)：一个PDF文件解析器，可将PDF二进制文件转换为基于文本的JSON，由PDF.JS的分支提供支持。
* [OPEN HTML TO PDF](https://github.com/danfickle/openhtmltopdf)：用于JVM的HTML到PDF的转换库，基于Flying Saucer和Apache PDF-BOX 2。
* [Tabula-Java](https://github.com/tabulapdf/tabula-java)：从PDF文件中提取表格的工具库。
* [PDFLayoutTextStripper](https://github.com/JonathanLink/PDFLayoutTextStripper)：将PDF文件转换为文本文件，同时保留原始PDF的布局。
* [Apache FOP](https://xmlgraphics.apache.org/fop/)：从XSL-FO创建PDF的库。
* [PdfCompare](https://github.com/red6/pdfcompare)：一个比较两个PDF文件的简单Java库。
* [DynamicReports](http://dynamicreports.org/)：免费开源Java报告工具。

<h4 id="excel">Excel库</h4>

* [Apache POI](https://github.com/apache/poi)：用于读写Microsoft Office二进制和OOXML文件格式的Java库。
* [EasyExcel](https://github.com/alibaba/easyexcel)：快速、简洁、解决大文件内存溢出的Java处理Excel工具，由阿里开源。
* [AutoPOI](https://github.com/jeecgboot/autopoi)：国产的Excel和Word简易工具类，基于Apache POI。
* [Docx4j](https://github.com/plutext/docx4j)：用于Word docx、Powerpoint pptx和Excel xlsx文件的基于JAXB的Java库。
* [MyExcel](https://github.com/liaochong/myexcel)：MyExcel是一个集导入、导出、加密Excel等多项功能的工具包。
* [EasyPoi](https://gitee.com/lemur/easypoi)：国产的POI工具类。
* [Excel4j](https://gitee.com/Crab2Died/Excel4J)：基于POI的Excel和Commons-CSV的CSV操作组件，大大减少代码量，提高开发效率。
* [FastExcel](https://github.com/dhatim/fastexcel)：快速生成和读取大Excel文件。
* [JXLS](https://github.com/jxlsteam/jxls)：用于使用Excel模板创建Excel报告的Java库。
* [Documents4j](https://github.com/documents4j/documents4j)：一个用于将文档转换为另一种文档格式的Java库。
* [XresLoader](https://github.com/xresloader/xresloader)：跨平台Excel导表工具。
* [Excel Streaming Reader](https://github.com/pjfanning/excel-streaming-reader)：使用Apache POI的流式Excel读取器的易于使用的实现。
* [AutoExcel](https://github.com/feng-haitao/auto-excel)：Excel的快速导入和导出工具。

<h4 id="csv">CSV库</h4>

* [Apache Commons CSV](https://github.com/apache/commons-csv)：Apache下的CSV操作库。
* [AdaptiveTableLayout](https://github.com/Cleveroad/AdaptiveTableLayout)：可以读取、编辑和写入CSV文件的库。
* [MyExcel](https://github.com/liaochong/myexcel)：MyExcel是一个集导入、导出、加密Excel等多项功能的工具包，支持CSV文件。
* [Super CSV](https://github.com/super-csv/super-csv)：一个快速、程序员友好、免费的Java CSV库。
* [FastCSV](https://github.com/osiegmar/FastCSV)：适用于Java的高性能CSV读取器和写入器。
* [Excel4j](https://gitee.com/Crab2Died/Excel4J)：基于POI的Excel和Commons-CSV的CSV操作组件，大大减少代码量，提高开发效率。
* [Jackson Dataformats Text](https://github.com/FasterXML/jackson-dataformats-text)：支持通过Jackson抽象读取和写入CSV编码数据。
* [UniVocity Parsers](https://github.com/uniVocity/univocity-parsers)：速度最快功能最全的CSV开发库之一，同时支持TSV与固定宽度记录的读写。
* [Scala CSV](https://github.com/tototoshi/scala-csv)：用于Scala的CSV读取器/写入器。
* [Opencsv](https://opencsv.sourceforge.net/)：Opencsv是一个易于使用的Java CSV解析器库。
* [kotlin CSV](https://github.com/doyaaaaaken/kotlin-csv)：纯Kotlin CSV读取器/写入器。
* [FlatPack](https://flatpack.sourceforge.net/)：积极开发的开源CSV库。
* [CSVeed](https://github.com/42BV/CSVeed)：轻量级、易于使用的基于Java的CSV实用程序。
* [Java CSV](http://sourceforge.net/projects/javacsv)：Java CSV是一个小型快速开源Java库，用于读写CSV和纯分隔文本文件。
* [DeCS](https://github.com/diergo/decs)：一个简单的Java 8 CSV解析器和生成器。
* [CSV Utils](https://ostermiller.org/utils/CSV.html)：用于读取和写入CSV(逗号分隔值)文本文件的实用程序。

<h4 id="word">Word库</h4>

* [kkFileView](https://github.com/kekingcn/kkFileView)：基于Spring Boot的通用文件在线预览项目。
* [Docx4j](https://github.com/plutext/docx4j)：用于Word docx、Powerpoint pptx和Excel xlsx文件的基于JAXB的Java库。
* [POI-TL](https://github.com/Sayi/poi-tl)：一种更好的模板生成word(docx)的方法，基于Apache POI。

<h4 id="xml">XML库</h4>

* [FlyingSaucer](https://github.com/flyingsaucerproject/flyingsaucer)：Flying Saucer是一个纯Java库，用于使用CSS 2.1进行布局和格式化、输出到Swing面板、PDF和图像来呈现任意格式良好的XML(或XHTML)。
* [XDocReport](https://github.com/opensagres/xdocreport)：用于将使用MS Office(docx)或OpenOffice(odt)、LibreOffice(odt)创建的XML文档与Java模型合并，以生成报告并在需要时将其转换为其他格式(PDF、XHTML等)。
* [Dom4j](https://github.com/dom4j/dom4j)：Dom4j是一个处理XML的开源框架，它与XPath集成，完全支持DOM、SAX、JAXP和Java平台(例如Java 2 Collections)。
* [XStream](https://github.com/x-stream/xstream)：用于Java和XML相互转换的库。
* [BaseX](https://github.com/BaseXdb/basex)：BaseX是一个XML数据库，用来存储紧缩的XML数据，提供了高效的XPath和XQuery的实现。
* [Apache Commons JXPath](https://github.com/apache/commons-jxpath)：XPath 1.0的基于Java的实现，除了XML处理之外，还可以检查/修改Java对象图，甚至混合Java/XML结构。
* [XmlToJson](https://github.com/smart-fun/XmlToJson)：用于将XML转换为JSON以及将JSON转换为XML的Android库。
* [Jackson-XML](https://github.com/FasterXML/jackson-dataformat-xml)：Jackson JSON处理器的扩展，增加了对POJO序列化为XML(以及从XML反序列化)的支持，作为JSON的替代方案。
* [jOOX](https://github.com/jOOQ/jOOX)：org.w3c.dom包的简单包装器，允许在需要DOM但过于冗长的情况下流式地创建和操作XML文档。
* [Apache Commons SCXML](https://github.com/apache/commons-scxml)：状态图XML引擎的Java实现。
* [TikXML](https://github.com/Tickaroo/tikxml)：适用于Java和Android的快速XML解析器。
* [Smooks](https://github.com/smooks/smooks)：用于构建基于XML和非XML片段的应用程序的可扩展数据集成Java框架。
* [JAXB Tools](https://github.com/highsource/jaxb-tools)：用于XML模式编译的最先进的JAXB2 Maven插件。
* [JDOM](https://github.com/hunterhacker/jdom)：可以让Java操作XML变得容易。
* [Aalto-XML](https://github.com/FasterXML/aalto-xml)：Aalto XML处理器是超高性能的下一代Stax XML处理器实现，实现了基本的Stax API(javax.xml.stream)和Stax2 API扩展(org.codehaus.woodstox.stax2)。
* [Xembly](https://github.com/yegor256/xembly)：Xembly是一种类似于汇编的命令式编程语言，用于XML文档中的数据操作。
* [GsonXml](https://github.com/stanfy/gson-xml)：GsonXml是一个小型库，允许使用Google Gson库进行XML反序列化。
* [Woodstox](https://github.com/FasterXML/woodstox)：Stax XML API(javax.xml.stream)实现。
* [Jaxb RI](https://github.com/eclipse-ee4j/jaxb-ri)：JAXB的Eclipse实现。
* [SitemapGen4j](https://github.com/dfabulich/sitemapgen4j)：SitemapGen4j是一个用Java生成XML站点地图的库。
* [Jaxen](https://github.com/jaxen-xpath/jaxen)：用于Java的XPath引擎。
* [Jettison](https://github.com/jettison-json/jettison)：Jettison是一个Java库，用于在StAX的帮助下将XML和JSON相互转换，它实现XMLStreamWriter和XMLStreamReader并支持Mapped和BadgerFish约定。
* [Simple-XMl](http://simple.sourceforge.net)：Simple是一个高性能的Java XML序列化和配置框架。
* [Xalan](https://xalan.apache.org/xalan-j/)：Xalan-J是一个用Java编写的XSLT处理器。
* [Xerces](http://xerces.apache.org/xerces2-j/)：Xerces-J是一个用Java编写的验证XML解析器。
* [Apache XML Graphics](https://xmlgraphics.apache.org/)：从XML到图形输出的转换工具。
* [Apache VXQuery](https://vxquery.apache.org/)：并行XML查询处理器。

<h4 id="file">文件库</h4>

* [SnakeYAML](https://bitbucket.org/asomov/snakeyaml/overview)：YAML解析库。
* [ini4j](https://github.com/facebookarchive/ini4j)：简单的Java API Windows风格.ini文件处理。
* [Epublib](https://github.com/psiegman/epublib)：Epublib是一个用于读取/写入/操作epub文件的Java库。
* [Commonmark-Java](https://github.com/commonmark/commonmark-java)：用于根据CommonMark规范(和一些扩展)解析和渲染Markdown文本的Java库。
* [libpst](https://github.com/rjohnsondev/java-libpst)：一个用Java读取PST文件的库，不需要外部库。
* [Markwon](https://github.com/noties/Markwon)：Android Markdown库。
* [jOpenDocument](https://www.jopendocument.org/)：用于OASIS Open Document文件操作的纯Java库。
* [Markdown Doclet](https://github.com/Abnaxos/markdown-doclet)：允许在JavaDoc注释中使用Markdown的Doclet。
* [JTidy](https://github.com/jtidy/jtidy)：JTidy是HTML Tidy的Java端口，是一个HTML语法检查器和漂亮的打印机。
* [CDC](https://gitlab.com/cdc-java/cdc-office)：与Office文档相关的实用程序。

<h2 id="datetime">日期时间库</h2>

* [Joda-Time](https://github.com/JodaOrg/joda-time)：Joda-Time是Java 8之前广泛使用的Java日期和时间类的替代品。
* [Prettytime](https://github.com/ocpsoft/prettytime)：Java的社交风格日期和时间格式。
* [Time4J](https://github.com/MenoData/Time4J)：Java的高级日期、时间和间隔库。
* [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra)：ThreeTen-Extra提供了额外的日期时间类来补充JDK 8中的类。
* [XK-Time](https://github.com/xkzhangsan/xk-time)：xk-time包含时间转换、时间计算、时间格式化、时间解析、日历、时间Cron表达式和时间NLP等工具。
* [ThreeTen](https://github.com/ThreeTen/threeten.github.io)：JSR 310实现，为JDK提供更具特点的时间和日期API。
* [Date4j](http://www.date4j.net)：小型、简单、实用的Java日期API。
* [Chronicle](https://github.com/peter-lawrey/Java-Chronicle)：Java索引记录编年史。
* [ThreeTen](https://github.com/ThreeTen/threetenbp)：JSR-310为Java SE 8提供了一个新的日期和时间库，该项目是Java SE 6和7的向后移植。
* [Jollyday](https://github.com/svendiedrichsen/jollyday)：确定给定年份、国家/名称以及最终州/地区的假期。
* [iCal4j](https://github.com/ical4j/ical4j)：用于解析和构建iCalendar数据模型的Java库。

<h2 id="reflection">反射</h2>

* [Reflections](https://github.com/ronmamo/reflections)：reflections会扫描项目的类路径元数据并为其建立索引，从而允许在运行时对类型系统进行反向传递查询。
* [jOOR](https://github.com/jOOQ/jOOR)：用于反射的流式API库，可以以更直观的方式访问Class类结构。
* [ReflectASM](https://github.com/EsotericSoftware/reflectasm)：ReflectASM是一个非常小的Java库，它通过使用代码生成来提供高性能反射。
* [Procyon](https://github.com/mstrobel/procyon)：Procyon是一套Java元编程工具，包括丰富的反射API、用于运行时代码生成的受LINQ启发的表达式树API以及Java反编译器。
* [Objenesis](https://github.com/easymock/objenesis)：Objenesis是一个专门用于在创建对象时绕过构造函数的库。
* [Apache Commons Beanutils](https://github.com/apache/commons-beanutils)：Apache Commons BeanUtils提供了一个易于使用且灵活的反射和内省包装器。
* [Mirror](https://github.com/Genymobile/mirror)：Java和Android的轻松反射。
* [FEST-Reflect](https://github.com/alexruiz/fest-reflect)：FEST-Reflect提供了直观、紧凑且类型安全的流式API，使Java反射非常易于使用：不再需要强制转换、处理受检异常或setAccessible调用。
* [Lambda-Factory](https://github.com/Hervian/lambda-factory)：lambda-factory是一个Java实用程序项目，提供了基于反射的方法调用的快速替代方案。
* [Mirror](http://projetos.vidageek.net/mirror/mirror/)：Mirror的创建是为了解决一个简单的问题，通常命名为ReflectionUtil，它几乎适用于所有依赖反射来完成高级任务的项目。

<h2 id="miscellaneous">杂项</h2>

* [GWT-Bootstrap](https://github.com/gwtbootstrap/gwt-bootstrap)：提供了简单灵活的组件来表示Bootstrap组件、样式和插件，由Twitter开源。
* [CSSEmbed](https://github.com/nzakas/cssembed)：用于在CSS文件中嵌入数据URI的工具。
* [J2ObjC](https://github.com/google/j2objc)：Java到iOS Objective-C的转换工具和运行时，由Google开源。
* [Jabba](https://github.com/shyiko/jabba)：Java版本管理工具。
* [ELK](https://github.com/eclipse/elk)：Eclipse布局内核提供了许多布局算法以及基于Eclipse的基础架构，将它们连接到编辑器和查看器。
* [Eclipse Xtext](https://github.com/eclipse/xtext)：Eclipse Xtext是一个用于开发编程语言和特定领域语言的框架。它涵盖了完整语言基础设施的所有方面，从解析器、链接器、编译器或解释器到针对Eclipse和基于Web的IDE的成熟的顶级IDE集成。
* [RED](https://github.com/nokia/RED)：RED是基于Eclipse IDE的现代编辑器，可与RobotFramework测试件一起提供高效、舒适的工作，由Nokia开源。
* [AWS CloudFormation Template](https://github.com/widdix/aws-cf-templates)：AWS CloudFormation的免费模板。
* [iQuantum](https://github.com/Cloudslab/iQuantum)：用于量子计算环境建模和仿真的工具包。
* [SecurityShepherd](https://github.com/OWASP/SecurityShepherd)：SecurityShepherd是一个Web和移动应用的安全培训平台，用于促进和提高人员的安全意识，由OWASP开源。
* [Emoji-Java](https://github.com/vdurmont/emoji-java)：emoji-java是一个轻量级的Java库，可帮助你在Java应用程序中使用表情符号。
* [Connector](https://github.com/eclipse-edc/Connector)：EDC核心服务包括数据平面和控制平面。
* [esProc](https://github.com/SPLWare/esProc)：esProc SPL是一种用于数据处理的脚本语言，具有精心设计的丰富的库函数和强大的语法，可以通过JDBC接口在Java程序中执行并独立计算。
* [Syndesis](https://github.com/syndesisio/syndesis)：一个灵活且可定制的开源平台，以服务形式提供核心集成功能，由Fuse Online开源。
* [Autopsy](https://github.com/sleuthkit/autopsy)：Autopsy是一个数字取证平台以及The Sleuth Kit和其他数字取证工具的图形界面。
* [DCEVM](https://github.com/dcevm/dcevm)：Java 7/8的动态代码演化VM。
* [OpenTracing](https://github.com/opentracing/opentracing-java)：OpenTracing的Java平台API。
* [Cling](https://github.com/4thline/cling)：适用于Java和Android的UPnP/DLNA库。
* [CodenameOne](https://github.com/codenameone/CodenameOne)：用于使用Java或Kotlin构建真正的本机移动应用程序的跨平台框架。
* [Pi4J](https://github.com/Pi4J/pi4j-v1)：适用于Raspberry Pi(GPIO、I2C、SPI、UART)的Java I/O库。
* [IJava](https://github.com/SpencerPark/IJava)：用于执行Java代码的Jupyter内核。
* [RackShift](https://github.com/fit2cloud/rackshift)：RackShift是开源的裸金属服务器管理平台，功能覆盖裸金属服务器的发现、带外管理、RAID配置、固件更新、操作系统安装等。
* [WSO2 Enterprise Integrator](https://github.com/wso2/product-ei)：WSO2 Enterprise Integrator是一个开源、快速、云原生且可扩展的集成解决方案，是WSO2集成敏捷平台的核心。
* [Rundeck](https://github.com/rundeck/rundeck)：Rundeck是一种开源自动化服务，具有Web控制台、命令行工具和Web API。
* [Apache Hop](https://github.com/apache/hop)：Hop编排平台旨在促进数据和元数据编排的各个方面，也是Kettle的前身。
* [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner)：开源多式联运旅行规划器。
* [Exhibitor](https://github.com/soabase/exhibitor)：ZooKeeper协同处理实例，例如监控、备份/恢复、清理和可视化，由Netflix开源。
* [Eclipse Scout](https://github.com/eclipse-scout/scout.rt)：Eclipse Scout是一个一站式框架，具有简单的概念、强大的应用程序模型和多功能的UI，它使你能够使用Java或TypeScript开发专业软件。
* [Eclipse Titan](https://gitlab.eclipse.org/eclipse/titan)：Eclipse Titan是一个TTCN-3编译和执行环境，具有基于Eclipse的IDE。该工具的用户可以开发测试用例、测试执行逻辑并为多个平台构建可执行测试套件。
* [Eclipse Transformer](https://github.com/eclipse/transformer)：Eclipse Transformer提供了转换Java二进制文件(例如单个class文件和完整的JAR和WAR)的工具和运行时组件，将更改映射到Java包、类型名称和相关资源名称。
* [Eclipse AAS4J](https://github.com/eclipse-aas4j/aas4j)：Eclipse AA4J实现了Asset Administration Shell(AAS)的规范，例如基于AAS规范的元模型、子模型、序列化和反序列化模块、验证器和转换库。
* [Guacamole Client](https://github.com/glyptodon/guacamole-client)：HTML5/JavaScript Guacamole客户端，其包含Web应用程序和相关组件。
* [Apache Jackrabbit](https://github.com/apache/jackrabbit)：Apache Jackrabbit是Java技术API(JCR)内容仓库的完全一致的实现。
* [Apache JSPWiki](https://github.com/apache/jspwiki)：Apache JSPWiki是领先的开源WikiWiki引擎，功能丰富且围绕标准JEE组件(Java、Servlet、JSP)构建。
* [Bateman](https://github.com/fearofcode/bateman)：简单的股票交易系统，通过粒子群优化来优化其参数。
* [Java REPL](https://github.com/albertlatacz/java-repl)：Java REPL是Java语言的简单Read-Eval-Print-Loop。
* [Seyren](https://github.com/scobal/seyren)：Graphite的警报仪表板。
* [Ttorrent](https://github.com/mpetazzoni/ttorrent)：BitTorrent协议的Java实现。
* [LanguageTool](https://github.com/languagetool-org/languagetool)：LanguageTool是一款开源校对软件，适用于英语、西班牙语、法语、德语、葡萄牙语、波兰语、荷兰语和其他20多种语言，可以发现许多简单的拼写检查器无法检测到的错误。
* [Apache OpenMeetings](https://openmeetings.apache.org/)：视频会议、即时消息、白板和协作文档编辑应用程序。
* [OpenIG](https://github.com/OpenIdentityPlatform/OpenIG)：OpenIG是一种高性能反向代理服务器，具有专门的会话管理和凭证重播功能。
* [TEAMMATES](https://github.com/TEAMMATES/teammates)：TEAMMATES是一个免费的在线工具，用于管理学生的同行评估和其他反馈路径。它作为基于云的服务提供给教育工作者/学生，目前已被全球数百所大学使用。

<h2 id="ai">人工智能</h2>

这里包含了Java里面人工智能领域相关的库。

<h4 id="ml">机器学习</h4>

* [Angel](https://github.com/Angel-ML/angel)：用于大规模机器学习的灵活且强大的参数服务器，由腾讯联合北京大学开源。
* [Spark-MLlib](https://github.com/apache/spark/tree/master/mllib)：MLlib是Apache Spark的可扩展机器学习库。
* [Alluxio](https://github.com/Alluxio/alluxio)：用于云中分析和机器学习的数据编排，由李浩源于2013年在加州大学伯克利分校AMP实验室创建。
* [Smile](https://github.com/haifengl/smile)：Smile是一个使用Java和Scala编写的快速且全面的机器学习、NLP、线性代数、图形、插值和可视化系统。
* [Flink-ML](https://github.com/apache/flink-ml)：Apache Flink机器学习库。
* [Apache Mahout](https://github.com/apache/mahout)：Apache Mahout项目的目标是构建一个用于快速创建可扩展、高性能机器学习应用程序的环境。
* [Weka](https://www.cs.waikato.ac.nz/ml/weka/)：Weka是用于数据挖掘任务的机器学习算法的集合，它包含用于数据准备、分类、回归、聚类、关联规则挖掘和可视化的工具，由新西兰怀卡托大学开发。
* [TorchServe](https://github.com/pytorch/serve)：TorchServe是一种灵活且易于使用的工具，用于在生产中提供和扩展PyTorch模型。
* [Apache Samoa](https://github.com/apache/incubator-samoa)：Apache SAMOA是一个用于挖掘大数据流的平台。它是一个分布式流式机器学习(ML)框架，包含分布式流式机器学习算法的编程抽象，由Yahoo开源。
* [Alink](https://github.com/alibaba/Alink)：Alink是基于Flink的机器学习算法平台，由阿里巴巴计算平台PAI团队开发。
* [SynapseML](https://github.com/microsoft/SynapseML)：SynapseML是一个开源库，可简化大规模可扩展机器学习(ML)管道的创建，由微软开源。
* [Apache PredictionIO](https://github.com/apache/predictionio)：一个面向开发人员、数据科学家和最终用户的开源机器学习框架。
* [H2O](https://github.com/h2oai/h2o-3)：H2O是一个开源、分布式、快速且可扩展的机器学习平台。
* [Apache Submarine](https://github.com/apache/submarine)：Apache Submarine是一个端到端机器学习平台，允许数据科学家创建端到端机器学习工作流程。
* [GROBID](https://github.com/kermitt2/grobid)：GROBID是一个机器学习库，用于提取、解析PDF等原始文档并将其重新构建为结构化XML/TEI编码文档，特别关注技术和科学出版物。
* [EasyML](https://github.com/ICT-BDA/EasyML)：EasyML是一种基于数据流的通用系统，可简化将机器学习算法应用于现实世界任务的过程。
* [DeepDive](https://github.com/HazyResearch/deepdive)：斯坦福大学开发的信息抽取系统。
* [Oryx](https://github.com/OryxProject/oryx)：Apache Spark、Apache Kafka上的Lambda架构，用于实时大规模机器学习。
* [Seldon](https://github.com/SeldonIO/seldon-server)：基于Kubernetes构建的机器学习平台和推荐引擎。
* [Tribuo](https://github.com/oracle/tribuo)：Oracle开源的Java机器学习库。
* [AeroSolve](https://github.com/airbnb/aerosolve)：一个从头开始设计的人性化机器学习库，由Airbnb开源。
* [Apache SystemDS](https://github.com/apache/systemds)：用于端到端数据科学生命周期的开源机器学习系统。
* [QuickML](https://github.com/sanity/quickml)：Java中快速且易于使用的决策树学习器。
* [Datumbox](https://github.com/datumbox/datumbox-framework)：Datumbox是一个用Java编写的开源机器学习框架，可以快速开发机器学习和统计应用程序。
* [Dagli](https://github.com/linkedin/dagli)：用于定义机器学习模型的框架，包括特征生成和转换，如有向无环图(DAG)，由LinkedIn开源。
* [Spring AI](https://github.com/spring-projects-experimental/spring-ai)：Spring AI项目旨在简化包含人工智能功能的应用程序的开发，避免不必要的复杂性。
* [Ytk-learn](https://github.com/kanyun-inc/ytk-learn)：Ytk-learn是一个分布式机器学习库，实现了大多数流行的机器学习算法。
* [Meka](https://github.com/Waikato/meka)：使用Weka机器学习框架的多标签分类器和评估程序，由怀卡托大学开发。
* [TensorFlow Java](https://github.com/tensorflow/java)：TensorFlow的Java绑定。
* [Mallet](https://github.com/mimno/Mallet)：MALLET是一个基于Java的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用。
* [oj!Algorithms](https://github.com/optimatika/ojAlgo)：与数学、线性代数和优化有关的开源Java代码。
* [Metarank](https://github.com/metarank/metarank)：Metarank是一项开源排名服务，它可以帮助你构建个性化的语义/神经搜索和推荐。
* [LangChain4j](https://github.com/langchain4j/langchain4j)：该项目的目标是简化AI/LLM功能到Java应用程序的集成。
* [ModelMesh](https://github.com/kserve/modelmesh)：ModelMesh框架是一个成熟的通用模型，服务于管理层/路由层，专为高规模、高密度和频繁变化的模型用例而设计，由IBM开源。
* [RapidMiner](https://rapidminer.com/)：RapidMiner是一个数据科学平台，通过GUI和Java API提供各种机器学习算法。
* [MOA](https://github.com/Waikato/moa)：MOA是一个用于大数据流挖掘的开源框架，它包括一系列机器学习算法(分类、回归、聚类、异常值检测、概念漂移检测和推荐系统)和评估工具，由怀卡托大学开发。
* [Encog](https://github.com/jeffheaton/encog-java-core)：Encog是一个先进的机器学习框架，支持支持向量机、人工神经网络、遗传编程、贝叶斯网络、隐马尔可夫模型、遗传编程和遗传算法。
* [Neuroph](https://github.com/neuroph/neuroph)：Neuroph是一个轻量级的Java神经网络框架。
* [SimpleDNN](https://github.com/KotlinNLP/SimpleDNN)：SimpleDNN是一个用Kotlin编写的机器学习轻量级开源库，旨在支持自然语言处理任务中的相关神经网络架构。
* [TransmogrifAI](https://github.com/salesforce/TransmogrifAI)：TransmogrifAI是一个AutoML库，用于在Apache Spark上构建模块化、可重用、强类型的机器学习工作流程，只需最少的手动调整。
* [JSAT](https://github.com/EdwardRaff/JSAT)：Java统计分析工具，用于机器学习的Java库。
* [Java-ML](https://github.com/charliermarsh/java-ml)：多种机器学习分类算法的Java实现。
* [HTM.Java](https://github.com/numenta/htm.java)：Java中的分层临时内存实现-Numenta智能计算平台(NuPIC)的官方社区驱动Java端口。
* [GeoGebra](https://github.com/geogebra/geogebra)：GeoGebra应用程序。
* [Libsvm](https://github.com/cjlin1/libsvm)：Libsvm是一款简单、易用、高效的SVM分类和回归软件。它可以解决C-SVM分类、nu-SVM分类、一类SVM、epsilon-SVM回归和nu-SVM回归问题。
* [Elasticsearch Learning](https://github.com/o19s/elasticsearch-learning-to-rank)：用于将机器学习与Elasticsearch集成的插件。
* [AIAS](https://gitee.com/mymagicpower/AIAS)：人工智能加速器套件，提供SDK、平台引擎、场景套件。
* [Dubhe](https://gitee.com/zhijiangtianshu/Dubhe)：之江天枢人工智能开源平台是由之江实验室牵头，联合国内顶尖科研力量共同打造的国产化自主可控的人工智能开源平台。

<h4 id="nlp">自然语言处理</h4>

* [CoreNLP](https://github.com/stanfordnlp/CoreNLP)：一套Java核心NLP工具，用于标记化、句子分段、NER、解析、共指、情感分析等，由斯坦福开源。
* [OpenNLP](https://github.com/apache/opennlp)：Apache OpenNLP库是一个基于机器学习的工具包，用于处理自然语言文本。
* [CogCompNLP](https://github.com/CogComp/cogcomp-nlp)：CogComp的自然语言处理库。
* [FudanNLP](https://github.com/FudanNLP/fnlp)：中文自然语言处理工具包。
* [Lingua](https://github.com/pemistahl/lingua)：适用于Java和JVM的最准确的自然语言检测库，适用于长文本和短文本。
* [DKPro-Core](https://github.com/dkpro/dkpro-core)：基于Apache UIMA框架的自然语言处理(NLP)软件组件集合。
* [Mallet](https://github.com/mimno/Mallet)：MALLET是一个基于Java的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用，由马萨诸塞大学和宾夕法尼亚大学开发。
* [Jcseg](https://github.com/lionsoul2014/jcseg)：Jcseg是一个用Java开发的轻量级NLP框架。
* [Neo4j-NLP](https://github.com/graphaware/neo4j-nlp)：提供基于图的自然语言处理功能。
* [MiNLP](https://github.com/XiaoMi/MiNLP)：小米开发的自然语言处理工具包。
* [NLP-Lang](https://github.com/NLPchina/nlp-lang)：这个项目是一个基本包，封装了大多数NLP项目中常用工具。
* [Mynlp](https://github.com/mayabot/mynlp)：一个生产级、高性能、模块化、可扩展的中文NLP工具包。
* [Apache UIMA](https://github.com/apache/uima-uimaj)：UIMA应用程序是分析大量非结构化信息以发现与最终用户相关的知识的软件系统。
* [Apache cTAKES](https://github.com/apache/ctakes)：Apache cTAKES是一个用于临床文本的自然语言处理(NLP)平台。
* [Apache NLPCraft](https://github.com/apache/incubator-nlpcraft)：将自然语言转换为操作的API。
* [EasyAI](https://gitee.com/ldp_dpsmax/easyAi)：通过简单的API调用就可以实现常用的图像内物体的识别，定位等图像AI服务，及自然语言分类处理服务。
* [Hawking](https://github.com/zoho/hawking)：自然语言日期时间解析器，可以从具有上下文的文本中提取日期和时间并解析为所需的格式。
* [LingPipe](https://www.alias-i.com/)：用于从POS标记到情感分析等任务的工具包。
* [Twitter Text](https://github.com/twitter/twitter-text)：Twitter使用此代码对文本进行标记和解析，以满足平台上可用内容的期望。
* [NLP4J](https://github.com/emorynlp/nlp4j)：NLP4J项目(以前称为ClearNLP)为JVM语言提供了一个NLP工具包，该项目目前由埃默里大学NLP研究小组开发。
* [Joshua](http://joshua-decoder.org/)：Joshua是一个开源统计机器翻译解码器，用于基于短语、分层和基于语法的机器翻译，由约翰霍普金斯大学人类语言技术卓越中心开发。
* [Z-MERT](http://cs.jhu.edu/~ozaidan/zmert/)：Z-MERT是一款用于机器翻译系统最小错误率训练的软件工具，由约翰霍普金斯大学开发。
* [ClearTK](https://github.com/ClearTK/cleartk)：ClearTK提供了一个用Java开发统计自然语言处理组件的框架，并构建在Apache UIMA之上，它由科罗拉多大学博尔德分校计算语言和教育研究中心(CLEAR)开发。
* [ARK Twitter NLP](https://github.com/brendano/ark-tweet-nlp)：CMU ARK Twitter词性标注器。
* [GATE](https://github.com/GateNLP/gate-core)：GATE是一个开源软件工具包，能够解决几乎所有文本处理问题，由谢菲尔德大学开发。

<h4 id="dl">深度学习</h4>

* [Eclipse Deeplearning4J](https://github.com/deeplearning4j/deeplearning4j)：Eclipse Deeplearning4J(DL4J)生态系统是一组旨在支持基于JVM的深度学习应用程序的所有需求的项目。
* [DJL](https://github.com/deepjavalibrary/djl)：Java中与引擎无关的深度学习框架，由亚马逊开源。
* [KotlinDL](https://github.com/Kotlin/kotlindl)：用Kotlin编写的高级深度学习API，受到Keras的启发。
* [Multi Model Server](https://github.com/awslabs/multi-model-server)：用于服务神经网络模型进行推理的工具，由亚马逊开源。
* [Deep Neural Networks](https://github.com/ivan-vasilev/neuralnetworks)：Java深度学习算法和带有GPU加速的深度神经网络。
* [TonY](https://github.com/tony-framework/TonY)：TonY是一个在Apache Hadoop上本地运行深度学习作业的框架。
* [Porcupine](https://github.com/Picovoice/porcupine)：由深度学习提供支持的设备上唤醒词检测。
* [Deep Learning Flink](https://github.com/flink-extended/dl-on-flink)：旨在集成Flink和深度学习框架(例如TensorFlow、PyTorch等)，以在Flink集群上实现分布式深度学习训练和推理。
* [Onyx](https://github.com/hanuor/onyx)：一个Android库，使用人工智能、机器学习和深度学习等技术来让开发人员理解他们在应用程序中显示的内容。
* [OpenDL](https://github.com/guoding83128/OpenDL)：Spark上的深度学习训练框架。
* [TensorDash](https://github.com/CleanPegasus/TensorDash)：TensorDash是一款应用程序，可让你远程监控深度学习模型的指标，并在模型训练完成或崩溃时通知你。
* [Omega-AI](https://gitee.com/iangellove/omega-ai)：基于Java打造的深度学习框架，帮助你快速搭建神经网络，实现训练或测试模型，引擎支持自动求导，多线程与GPU运算。
* [DLSF](https://github.com/Cloudslab/DLSF)：用于随机雾云计算环境的基于深度学习的调度程序。
* [ADAMS](https://adams.cms.waikato.ac.nz/)：ADAMS代表高级数据挖掘和机器学习系统，是专门针对Java的深度学习库，由怀卡托大学开发。

<h4 id="genetic">遗传算法</h4>

* [Jenetics](https://github.com/jenetics/jenetics)：Jenetics是一种用Java编写的高级遗传算法，它提供了遗传算法概念的清晰分离。
* [Watchmaker](https://github.com/dwdyer/watchmaker)：Watchmaker Framework是一个用Java实现遗传算法的框架。
* [ECJ 23](https://cs.gmu.edu/~eclab/projects/ecj/)：ECJ 23是一个基于Java的研究框架，为遗传算法提供强大的算法支持。
* [JGAP](https://sourceforge.net/projects/jgap/)：JGAP是作为Java框架提供的遗传编程组件。
* [Eva](https://github.com/decorators-squad/eva)：Eva是一个简单的Java OOP进化算法框架。
* [Genetic Algorithms](https://github.com/lagodiuk/genetic-algorithm)：Java中遗传算法的通用实现。
* [MergeLife](https://github.com/jeffheaton/mergelife)：使用遗传算法演化复杂的元胞自动机。

<h4 id="face">人脸识别</h4>

* [CompreFace](https://github.com/exadel-inc/CompreFace)：Exadel CompreFace是一项免费的开源人脸识别服务，无需具备机器学习技能即可轻松集成到任何系统中。
* [Face Recognition](https://github.com/Qualeams/Android-Face-Recognition-with-Deep-Learning-Library)：用于Android和Java的人脸识别库，其中包含多种人脸识别方法。
* [FaceRecognition](https://github.com/wihoho/FaceRecognition)：使用PCA、LDA和LPP实现的人脸识别。
* [SeetafaceJNI](https://gitee.com/cnsugar/seetafaceJNI)：基于中科院Seetaface 2进行封装的Java人脸识别库，支持人脸识别、1:1比对、1:N比对。
* [FaceSearch](https://gitee.com/open-visual/face-search)：本项目是阿里云视觉智能开放平台的人脸搜索M：N的开源替代，项目中使用的模型均为开源模型，项目支持OpenSearch、Milvus和Proxima向量存储库，并具有较高的自定义能力。
* [red5-rtmp-push](https://gitee.com/endlesshh/red5-rtmp-push)：Java版天网人脸识别系统，可以获取视频流进行人脸识别后推送到流媒体服务器实时展示。
* [Qiansou Face SDK](https://gitee.com/qiansou/face-v4-java-sdk)：第5代深度学习人脸识别引擎Java SDK，由千搜科技开源。

<h4 id="expert-system">专家系统</h4>

* [Apache Jena](https://github.com/apache/jena)：Apache Jena是一个开源Java框架，用于从RDF数据构建语义Web和链接数据应用程序。它提供了一个API来从RDF图中提取数据并写入RDF图中。
* [PowerLoom](https://www.isi.edu/isd/LOOM/PowerLoom/)：PowerLoom是一个用于创建智能、基于知识的应用程序的平台。
* [d3web](https://github.com/denkbares)：d3web是一个开源推理引擎，用于开发、测试问题解决知识并将其应用于给定的问题情况，其中已经包含许多算法。
* [Eye](https://github.com/eyereasoner/eye)：Eye是一个用于执行半逆向推理的开源推理引擎。
* [Tweety](https://github.com/TweetyProjectTeam/TweetyProject)：Tweety是用于人工智能和知识表示的逻辑方面的Java框架的集合。
* [OptaPlanner](https://github.com/kiegroup/optaplanner)：OptaPlanner是一个基于Java的约束求解器。
* [Choco](https://github.com/chocoteam/choco-solver)：用于约束编程的开源Java库。
* [JaCoP](https://github.com/radsz/jacop/)：Java约束编程求解器。
* [Sat4j](http://www.sat4j.org/)：Sat4j是一个用于解决布尔满足和优化问题的Java库，它可以解决SAT、MAXSAT、伪布尔、最小不可满足子集(MUS)问题。
* [Timefold](https://github.com/TimefoldAI/timefold-solver)：灵活的求解器，支持Spring/Quarkus以及车辆路线问题、维护计划、员工轮班计划等快速入门。
* [OptaPy](https://github.com/optapy/optapy)：OptaPy是Python的AI约束求解器，用于优化规划和调度问题。

<h2 id="science">数据科学</h2>

* [Tablesaw](https://github.com/jtablesaw/tablesaw)：Tablesaw是一个数据框架和可视化库，支持加载、清理、转换、过滤和汇总数据。
* [JGraphT](https://github.com/jgrapht/jgrapht)：JGraphT是一个免费的Java类库，提供数学图论对象和算法。
* [XChart](https://github.com/knowm/XChart)：XChart是一个轻量且方便的数据绘制库，旨在在尽可能短的时间内从数据到图表，并消除自定义图表样式时的猜测工作。
* [JGraphX](https://github.com/jgraph/jgraphx)：JGraphX是一个Java Swing图表(图形可视化)库。
* [JUNG](https://github.com/jrtom/jung)：JUNG是一个软件库，它提供了一种通用且可扩展的语言，用于对可以表示为图形或网络的数据进行建模、分析和可视化。
* [GraphStream](https://github.com/graphstream/gs-core)：GraphStream项目是一个Java库，提供API来建模、分析和可视化图和动态图。
* [Morpheus](https://github.com/zavtech/morpheus-core)：Morpheus库旨在促进涉及大型数据集的高性能分析软件的开发，以便在Java虚拟机(JVM)上进行离线和实时分析。
* [LogicNG](https://github.com/logic-ng/LogicNG)：LogicNG是一个用于创建、操作和求解布尔和伪布尔公式的Java库，它包括MiniSAT、Glucose、PBLib或OpenWBO等流行工具的纯Java实现。
* [Erdos](https://github.com/Erdos-Graph-Framework/Erdos)：Erdos是一个非常轻量、模块化且超级易于使用的Java现代图论算法框架。
* [Apache Commons Statistics](https://github.com/apache/commons-statistics)：Apache Commons Statistics提供用于统计应用程序的实用程序，为常用的连续和离散分布提供支持。
* [Mines JTK](https://github.com/MinesJTK/jtk)：Mines Java Toolkit(Mines JTK)是一组用于科学和工程的Java包和原生(非Java)软件库，目前的应用包括数字信号处理、线性代数、优化、网格划分、插值以及2D和3D图形。
* [JScience](https://github.com/javolution/jscience)：提供一组用于处理科学测量和单位的类。
* [SimpleNLG](https://github.com/simplenlg/simplenlg)：SimpleNLG是一个简单的Java API，旨在促进自然语言的生成。它最初由阿伯丁大学计算科学系教授、Arria NLG联合创始人Ehud Reiter开发。
* [Neo4j Graph Data Science](https://github.com/neo4j/graph-data-science)：GDS包括图算法、图转换和机器学习管道，通过Neo4j DBMS内的Cypher程序进行操作。
* [KNIME Python](https://github.com/knime/knime-python)：KNIME Python集成缩小了KNIME分析平台和Python之间的差距，它提供了编写和执行Python脚本的节点以及在KNIME分析平台的其他部分使用Python的功能。
* [JFreeChart](https://github.com/jfree/jfreechart)：用于Java应用程序(JavaFX、Swing或服务器端)的2D图表库。
* [DataMelt](https://datamelt.org/)：DataMelt是一款为科学家、工程师和学生提供的免费数学软件，它可用于数值计算、统计、符号计算、数据分析和数据可视化。
* [Dex](https://github.com/PatMartin/Dex)：Dex是数据科学的强大工具，它是在JavaFX之上用Groovy和Java编写的数据可视化工具，能够进行强大的ETL和发布Web可视化。
* [Dataframe](https://github.com/Kotlin/dataframe)：Dataframe旨在利用Kotlin语言的全部功能以及Jupyter Notebook和REPL中间歇性代码执行提供的机会，协调Kotlin的静态类型与数据的动态特性。
* [krangl](https://github.com/holgerbrandl/krangl)：krangl是一个用于数据处理的Kotlin库，通过使用现代函数式API实现数据操作语法，它允许过滤、转换、聚合和重塑表格数据。
* [Science Parse](https://github.com/allenai/science-parse)：用于解析科学论文(PDF形式)并以结构化形式返回的Java库。
* [OpenRefine](https://github.com/OpenRefine/OpenRefine)：OpenRefine是一个基于Java的强大工具，可让你加载数据、理解数据、清理数据、协调数据，并使用来自Web的数据对其进行扩充。
* [Hopsworks](https://github.com/logicalclocks/hopsworks)：Hopsworks是一个ML数据平台，具有以Python为中心的特征存储和MLOps功能。
* [ELKI](https://github.com/elki-project/elki)：用Java编写的开源数据挖掘软件，由德国多特蒙德大学开发。
* [Zingg](https://github.com/zinggAI/zingg)：使用机器学习进行可扩展的身份解析、实体解析、数据掌握和重复数据删除。
* [DataCleaner](https://github.com/datacleaner/DataCleaner)：DataCleaner是一个数据质量工具包，可让你分析、更正和丰富你的数据。
* [RumbleDB](https://github.com/RumbleDB/rumble)：适用于Apache Spark，对大规模、混乱的类JSON数据(JSON、文本、CSV、Parquet、ROOT、AVRO、SVM...)运行查询、声明式机器学习等。
* [Featran](https://github.com/spotify/featran)：用于数据科学和机器学习的Scala特征转换库，由Spotify开源。
* [Datavines](https://github.com/datavane/datavines)：Datavines是下一代数据观测平台，支持元数据管理和数据质量。
* [EarthSci](https://github.com/GeoscienceAustralia/earthsci)：EarthSci是一个Eclipse RCP平台，用于创建地球科学数据可视化应用程序，它是基于NASA World Wind Java SDK构建的现有GA World Wind Suite的演变。

<h2 id="math">数学库</h2>

* [SuanShu](https://github.com/aaiyer/SuanShu)：SuanShu是一个Java数学库，用于数值分析、统计、求根、线性代数、优化等。
* [Colt](https://dst.lbl.gov/ACSSoftware/colt/)：Colt是Java中用于高性能科学计算的库。它包含用于数据分析、线性代数、多维数组、傅里叶变换、统计和直方图的有效算法。
* [Apache Commons Math](https://github.com/apache/commons-math)：Commons Math是一个轻量级、独立的数学和统计组件库，可解决Java编程语言或Commons Lang中无法解决的最常见问题。
* [Apache Commons Numbers](https://github.com/apache/commons-numbers)：Apache Commons Numbers项目提供数字类型和实用程序。
* [Apache Commons Geometry](https://github.com/apache/commons-geometry)：Apache Commons Geometry项目提供几何类型和实用程序。
* [Eclipse January](https://github.com/eclipse/january)：这是一个用Java处理数据的库，它部分受到NumPy的启发，旨在提供类似的功能。
* [ELEFUNT](http://www.math.utah.edu/~beebe/software/java/)：附带了一个扩展了java.lang.Math的新类库，以及用于数字输出格式化的新类库。
* [JNT](https://math.nist.gov/jnt/)：包含计算内核的坚实基础，可以帮助引导开发Java中复杂数值应用程序的工作。
* [JUMP](https://sourceforge.net/projects/jump-math/)：JUMP是一个基于Java的可扩展高精度数学包，包括对基于分数的计算的支持，支持转换为浮点数和BigDecimal。
* [JSci](https://jsci.sourceforge.net/)：这是一组免费的Java包，目的是以最自然的方式概括科学方法/原理。
* [Jampack](https://math.nist.gov/pub/Jampack/Jampack/AboutJampack.html)：Jampack是一个协作类的集合，旨在在Java应用程序中执行矩阵计算。
* [JAMA](https://math.nist.gov/javanumerics/jama/)：JAMA是Java的基本线性代数包，它提供了用于构造和操作真实的稠密矩阵的用户级类。
* [JOML](https://github.com/JOML-CI/JOML)：用于OpenGL渲染计算的Java数学库。
* [KeenWrite](https://github.com/DaveJarvis/KeenWrite)：免费、开源、跨平台桌面Markdown文本编辑器，具有实时预览、字符串插值和数学功能。
* [Symja](https://github.com/axkr/symja_android_library)：计算机代数语言和符号数学库，用纯Java实现的流行算法的集合。
* [BigDecimalMath](https://github.com/eobermuhlner/big-math)：使用任意精度的高级Java BigDecimal数学函数库。
* [uncommons-maths](https://github.com/dwdyer/uncommons-maths)：Java的随机数生成器、概率分布、组合学和统计库。
* [Hacktoberfest-Mathematics](https://github.com/BaReinhard/Hacktoberfest-Mathematics)：数学公式和函数的脚本和/或程序库。
* [RxJavaMath](https://github.com/ReactiveX/RxJavaMath)：RxJava的数学运算符。
* [KMath](https://github.com/SciProgCentre/kmath)：Kotlin数学扩展库。
* [ParallelColt](https://github.com/rwl/ParallelColt)：Parallel Colt是Colt的多线程版本。

<h2 id="ontology">本体库</h2>

* [WebProtégé](https://github.com/protegeproject/webprotege)：WebProtégé是一个免费、开源的协作本体开发环境。
* [OWLAPI](https://github.com/owlcs/owlapi)：OWL API是用于创建、操作和序列化OWL本体的Java API。
* [Karma](https://github.com/usc-isi-i2/Web-Karma)：Karma是一种信息集成工具，使用户能够快速轻松地集成来自各种数据源的数据，包括数据库、电子表格、分隔文本文件、XML、JSON、KML和Web API。
* [Widoco](https://github.com/dgarijo/Widoco)：WIDOCO是一个带有本体文档的HTML模板逐步生成器，它使用LODE环境来创建部分模板。
* [Ontop](https://github.com/ontop/ontop)：Ontop是一个使用SPARQL将关系数据库查询为虚拟RDF知识图的平台。
* [Scowl](https://github.com/phenoscape/scowl)：用于使用OWL API进行编程的Scala DSL。
* [SnowOwl](https://github.com/b2ihealthcare/snow-owl)：SnowOwl是一款高度可扩展的开源术语服务器，具有修订控制功能和协作创作平台功能。允许快速高效地存储、搜索和创作大量术语工件。
* [DL-Learner](https://github.com/SmartDataAnalytics/DL-Learner)：DL-Learner是一个用于执行丰富语义背景知识的机器学习的框架。
* [ROBOT](https://github.com/ontodev/robot)：ROBOT是一个用于自动化本体开发任务的命令行工具和库，重点是开放生物和生物医学本体。
* [SciGraph](https://github.com/SciGraph/SciGraph)：Neo4j支持的本体存储。
* [OWL2VOWL](https://github.com/VisualDataWeb/OWL2VOWL)：本体转换器。
* [LogMap](https://github.com/ernestojimenezruiz/logmap-matcher)：本体对齐和对齐修复系统。
* [Openllet](https://github.com/Galigator/openllet)：Openllet是Java中的OWL 2推理器，构建在Pellet之上。
* [ELK](https://github.com/liveontologies/elk-reasoner)：基于Java的OWL 2 EL推理器。
* [OWLTools](https://github.com/owlcollab/owltools)：OWLTools是OWL API之上的便捷Java API。
* [Slib](https://github.com/sharispe/slib)：Slib是一个专门用于基于文本和/或本体处理的语义数据挖掘的Java库。
* [OBOGraphs](https://github.com/geneontology/obographs)：包含用于本体交换的JSON/YAML格式规范，以及参考Java对象模型和OWL转换器。
* [Ontology Java SDK](https://github.com/ontio/ontology-java-sdk)：这是本体区块链的综合Java库，支持本地钱包管理、数字身份管理、数字资产管理、智能合约的部署和调用、与本体区块链的通信。
* [Ontmalizer](https://github.com/srdc/ontmalizer)：自动执行XML模式(XSD)和XML数据到RDF/OWL的全面转换的工具。

<h2 id="semantic">语义Web</h2>

* [VIVO](https://github.com/vivo-project/VIVO)：VIVO是一个开源语义Web工具，用于研究发现、寻找人和他们所做的研究。
* [SPARQL](https://github.com/SPARQL-Anything/sparql.anything)：SPARQL是一个用于语义Web重新设计的系统，允许用户使用SPARQL查询任何内容。
* [LinkedGeoData](https://github.com/GeoKnow/LinkedGeoData)：LinkedGeoData致力于向数据网/语义网添加空间维度，LinkedGeoData使用OpenStreetMap项目收集的信息，并根据关联数据原则将其作为RDF知识库提供。
* [Ripple](https://github.com/joshsh/ripple)：Ripple是一种基于堆栈的函数式查询语言，适用于关联数据和其他RDF数据源。
* [Vitro](https://github.com/vivo-project/Vitro)：Vitro是一个通用的基于Web的本体和实例编辑器，具有可定制的公共浏览功能。
* [Apache Commons RDF](https://github.com/apache/commons-rdf)：RDF旨在为RDF 1.1提供一个通用库，并实现常见Java RDF框架(如RDF4J、Apache Jena)以及其他库(如OWLAPI、Clerezza和其他JVM语言)的实现。
* [Corese](https://github.com/Wimmics/corese)：Corese是一个实现和扩展语义网标准的软件平台，它允许创建、操作、解析、序列化、查询、推理和验证RDF数据。
* [neosemantics](https://github.com/neo4j-labs/neosemantics)：neosemantics是一个允许在Neo4j中使用RDF的插件。
* [Wikidata Toolkit](https://github.com/Wikidata/Wikidata-Toolkit)：Wikidata Toolkit是一个用于访问Wikidata和其他Wikibase安装的Java库。它可用于创建机器人、执行数据提取任务以及进行对于使用简单的SPARQL查询服务来说过于复杂的大规模分析。
* [Eclipse RDF4J](https://github.com/eclipse-rdf4j/rdf4j)：Eclipse RDF4J是一个强大的Java框架，用于处理和处理RDF数据，这包括使用RDF和链接数据创建、解析、可扩展存储、推理和查询。
* [D2RQ](https://github.com/d2rq/d2rq)：一个数据库到RDF映射引擎和SPARQL服务器。
* [RDFUnit](https://github.com/AKSW/RDFUnit)：RDFUnit在测试驱动数据验证本体之上实现，旨在读取和生成仅符合该本体的RDF。
* [Rdf-File](https://github.com/alipay/rdf-file)：Rdf-File是一个处理结构化文本文件的工具组件。
* [LodView](https://github.com/LodLive/LodView)：LodView是一个基于Spring和Jena的Web应用程序，它是一个能够提供符合W3C标准的IRI解引用的工具。
* [Empire](https://github.com/mhgrove/Empire)：Empire使用SPARQL为RDF数据库提供标准JPA风格的接口。
* [HDT](https://github.com/rdfhdt/hdt-java)：HDT-lib是一个Java库，它实现了RDF HDT(标头-字典-三元组)二进制格式的W3C提交。
* [CARML](https://github.com/carml/carml)：CARML是一个Java库，根据RML规范，将结构化源转换为RDF。
* [JSON2RDF](https://github.com/AtomGraph/JSON2RDF)：流式的通用JSON到RDF转换器。

<h2 id="bioinformatics">生物信息学</h2>

* [Nextflow](https://github.com/nextflow-io/nextflow)：Nextflow是一个生物信息学工作流程管理器，支持开发可移植且可重复的工作流程。
* [Cromwell](https://github.com/broadinstitute/cromwell)：Cromwell是一个用于生物信息学的开源工作流程管理系统。
* [GATK](https://github.com/broadinstitute/gatk)：包含下一代基因组分析工具包(GATK)。
* [BioJava](https://github.com/biojava/biojava)：BioJava是一个开源项目，致力于提供用于处理生物数据的Java库。
* [ADAM](https://github.com/bigdatagenomics/adam)：ADAM是一个库和命令行工具，支持使用Apache Spark跨集群/云计算环境并行进行基因组数据分析。
* [WDL](https://github.com/openwdl/wdl)：工作流描述语言的规范和实现。
* [Jvarkit](https://github.com/lindenb/jvarkit)：用于生物信息学的Java实用程序。
* [CDK](https://github.com/cdk/cdk)：CDK是一个用于化学信息学和生物信息学的开源Java库。
* [biometrics](https://github.com/SelfLender/react-native-biometrics)：适用于iOS和Android生物识别的React Native模块
* [InterMine](https://github.com/intermine/intermine)：一个强大的开源数据仓库系统，允许用户以最少的努力集成不同的数据源，InterMine为生命科学领域一些最大的数据仓库提供支持。
* [BBMap](https://github.com/BioInfoTools/BBMap)：用于DNA/RNAseq的BBMap短读对齐器和其他生物信息学工具。
* [Pegasus](https://github.com/pegasus-isi/pegasus)：Pegasus WMS是一个可配置系统，用于在各种计算基础设施(包括笔记本电脑、校园集群、超级计算机、网格以及商业和学术云)上映射和执行科学工作流程。
* [GloBI](https://github.com/globalbioticinteractions/globalbioticinteractions)：提供对现有物种相互作用数据集的访问。
* [MOLGENIS](https://github.com/molgenis/molgenis)：MOLGENIS是一个协作开源项目，其目的是为生命科学研究生成出色的软件基础设施。
* [Hadoop-BAM](https://github.com/HadoopGenomics/Hadoop-BAM)：Hadoop-BAM是一个Java库，用于使用Hadoop MapReduce框架操作常见生物信息学格式的文件。
* [SIRIUS](https://github.com/boecker-lab/sirius)：SIRIUS是一个基于Java的软件框架，用于分析代谢物和其他“具有生物意义的小分子”的LC-MS/MS数据。
* [LibLevenshtein](https://github.com/universal-automata/liblevenshtein-java)：有关Levenshtein传感器的各种实用程序。
* [Jannovar](https://github.com/charite/jannovar)：Java中的功能变体文件注释，Jannovar提供了一个用于VCF文件注释的程序，并通过库API公开其功能。
* [SIRIUS](https://github.com/boecker-lab/sirius-libs)：用Java编写的用于小分子分子式识别的代谢组学质谱框架。
* [PeptideShaker](https://github.com/compomics/peptide-shaker)：PeptideShaker是一个独立于搜索引擎的平台，用于解释来自多个搜索和de novo引擎的蛋白质组学鉴定结果，目前支持X! Tandem、MS-GF+、MS Amanda、OMSSA、MyriMatch、Comet、Tide、Mascot、Andromeda、MetaMorpheus、Sage、Novor、DirecTag和mzIdentML。
* [OME](https://github.com/ome/openmicroscopy)：OME(开放显微镜环境)开发用于存储和操作生物光学显微镜数据的开源软件和数据格式标准，OME是欧洲和美国大学、研究机构和行业之间的联合项目。
* [NSGA-II](https://github.com/onclave/NSGA-II)：NSGA-II的Java实现。
* [SearchGUI](https://github.com/compomics/searchgui)：SearchGUI是一个高度适应性的开源通用界面，用于配置和运行蛋白质组学搜索和de novo引擎，目前支持X! Tandem、MyriMatch、MS Amanda、MS-GF+、OMSSA、Comet、Tide、Andromeda、MetaMorpheus、Sage、Novor和DirecTag。
* [Bio-Formats](https://github.com/ome/bioformats)：Bio-Formats是一个Java库，用于读取和写入生命科学图像文件格式的数据。
* [Bio4j](https://github.com/bio4j/bio4j)：Bio4j是一个生物信息学图形数据平台，集成了Uniprot KB(SwissProt + Trembl)、Gene Ontology(GO)、UniRef(50,90,100)、NCBI Taxonomy和Expasy Enzyme DB中的大部分可用数据。
* [libSBOLj](https://github.com/SynBioDex/libSBOLj)：合成生物学开放语言Java库。

<h2 id="genomics">基因组学</h2>

* [cBioPortal](https://github.com/cBioPortal/cbioportal)：cBioPortal提供大规模癌症基因组学数据集的可视化、分析和下载。
* [IGV](https://github.com/igvteam/igv)：综合基因组学查看器，快速、高效、可扩展的基因组数据和注释可视化工具。
* [HTSJDK](https://github.com/samtools/htsjdk)：HTSJDK是统一Java库的实现，用于访问用于高通量测序数据的常见文件格式，例如SAM和VCF，还有许多有用的实用程序可用于操作HTS数据。
* [GRIDSS](https://github.com/PapenfussLab/gridss)：GRIDSS是一个模块软件套件，包含可用于检测基因组重排的工具。GRIDSS包括一个全基因组断裂末端组装程序，以及一个用于Illumina测序数据的结构变异调用程序。
* [Artemis](https://github.com/sanger-pathogens/Artemis)：Artemis是一款免费的基因组浏览器和注释工具，可实现序列特征、下一代数据和序列背景下的分析结果及其六帧翻译的可视化。
* [MISO](https://github.com/miso-lims/miso-lims)：适用于小型到大型测序中心的开源LIMS。
* [OpenCGA](https://github.com/opencb/opencga)：用于基因组学大数据处理和分析的开放计算基因组分析平台。
* [GORpipe](https://github.com/gorpipe/gor)：GORpipe是一种基于基因组有序关系架构的工具，允许在并行执行引擎中使用声明性查询语言分析大量基因组和表型表格数据。
* [Exomiser](https://github.com/exomiser/Exomiser)：Exomiser是一个Java程序，可以从全外显子组或全基因组测序数据中查找潜在的致病变异。
* [HMFTools](https://github.com/hartwigmedical/hmftools)：用于分析基因组数据的各种算法。
* [Cloud-Pipeline](https://github.com/epam/cloud-pipeline)：与云无关的基因组学分析、科学计算和存储平台。
* [DNAnalyzer](https://github.com/VerisimilitudeX/DNAnalyzer)：致力于彻底改变DNA分析领域，目标是使DNA分析工具的使用更加民主化。
* [IRIDA](https://github.com/phac-nml/irida)：IRIDA是加拿大基因组流行病学综合快速传染病分析平台。

<h2 id="medical">医疗平台</h2>

* [HAPI FHIR](https://github.com/hapifhir/hapi-fhir)：用于HL7 FHIR客户端和服务器的Java API。
* [Connect](https://github.com/nextgenhealthcare/connect)：医疗保健一体化的瑞士军刀。
* [Clinical Quality Language](https://github.com/cqframework/clinical_quality_language)：临床质量语言(CQL)是用于表达临床知识的HL7)标准，可在广泛的临床领域中使用，包括临床决策支持(CDS)和临床质量测量(CQM)。
* [IPF](https://github.com/oehf/ipf)：IPF是Apache Camel路由和中介引擎的扩展，为医疗保健领域的消息处理和连接信息系统提供全面支持。
* [HAPI FHIR Core](https://github.com/hapifhir/org.hl7.fhir.core)：适用于FHIR规范的Java核心对象处理代码，带有实用程序(包括验证器)。
* [OpenMRS](https://github.com/openmrs/openmrs-core)：OpenMRS是一个基于患者的医疗记录系统，专注于为提供商提供免费的可定制电子医疗记录系统(EMR)。
* [dcm4che](https://github.com/dcm4che/dcm4che)：Java中的DICOM实现。

<h2 id="concurrency">并发编程</h2>

* [Disruptor](https://github.com/LMAX-Exchange/disruptor)：高性能线程间消息传递库。
* [Quasar](https://github.com/puniverse/quasar)：JVM上的Fiber、Channel和Actor实现。
* [JCTools](https://github.com/JCTools/JCTools)：用于JVM的Java并发工具，该项目旨在提供JDK目前缺少的一些并发数据结构。
* [AsyncTool](https://gitee.com/jd-platform-opensource/asyncTool)：京东开源的多线程编排一站式解决方案。
* [Thread Weaver](https://github.com/google/thread-weaver)：用于测试多线程代码的Java框架。
* [Kilim](https://github.com/kilim/kilim)：Java的轻量级线程，具有消息传递、NIO、HTTP和调度支持。
* [EA-Async](https://github.com/electronicarts/ea-async)：EA-Async在JVM中实现Async-Await方法，它允许程序员以顺序方式编写异步代码。
* [TransmittableThreadLocal](https://github.com/alibaba/transmittable-thread-local)：提供了一个增强的InheritableThreadLocal，即使使用线程池组件也可以在线程之间传输值，由阿里开源。
* [ConcurrentLinkedHashMap](https://github.com/ben-manes/concurrentlinkedhashmap)：Java的ConcurrentLinkedHashMap。
* [Trickle](https://github.com/spotify/trickle)：用于编写异步代码的小型库，由Spotity开源。
* [Loom](https://github.com/openjdk/loom)：JDK实现的虚拟线程、结构化并发项目。
* [Java Concurrency Stress](https://github.com/openjdk/jcstress)：jcstress是实验性工具和一套测试，用于帮助研究JVM、类库和硬件中并发支持的正确性。
* [JCommon](https://github.com/facebookarchive/jcommon)：并发、集合、统计/分析、配置、测试等，由Facebook开发。
* [JDeferred](https://github.com/jdeferred/jdeferred)：JDeferred是一个小型Java库(也支持Groovy)，用于实现异步拓扑，而无需编写样板代码。
* [Coroutines](https://github.com/esoco/coroutines)：协作并发的纯Java实现，又名协程。
* [Menagerie](https://github.com/sfines/menagerie)：基于ZooKeeper的Java并发库。
* [Thread Affinity](https://github.com/OpenHFT/Java-Thread-Affinity)：该库允许你将线程绑定到给定核心，这可以提高性能(在Linux上运行最佳)。
* [Tascalate Concurrent](https://github.com/vsilaev/tascalate-concurrent)：阻塞可取消java.util.concurrent.CompletionStage的实现以及java.util.concurrent.ExecutorService的相关扩展。
* [Coroutines](https://github.com/offbynull/coroutines)：允许编写协程的Java工具包。
* [Completable Futures](https://github.com/spotify/completable-futures)：Java 8中处理Future的实用程序，由Spotify开源。
* [DynamicTp](https://github.com/dromara/dynamic-tp)：基于配置中心的轻量级动态线程池，内置监控告警功能，集成常用中间件线程池管理，可通过SPI自定义扩展实现，由dromara社区开源。
* [TaskManager](https://github.com/iqiyi/TaskManager)：一种支持依赖关系、任务兜底策略的任务调度管理工具，由爱奇艺开发。
* [Hippo4j](https://github.com/opengoofy/hippo4j)：国产异步线程池框架，支持线程池动态变更、监控、报警。
* [Gobrs-Async](https://gitee.com/dromara/gobrs-async)：多线程并发编程框架，由dromara社区开源。
* [Fact-Async](https://gitee.com/china2010pan/fact-async)：Fact-Async是一个基于Spring的异步并行框架。
* [ParSeq](https://github.com/linkedin/parseq)：ParSeq是一个框架，可以更轻松地用Java编写异步代码。
* [Threadly](https://github.com/threadly/threadly)：协助安全并发Java开发的工具库，提供独特的基于优先级的线程池，以及安全分配线程工作的方法。

<h2 id="security">安全</h2>

这里列出了安全相关的库、框架、组件，例如JWT、OAuth和CAS。

<h4 id="security-lib">安全库</h4>

* [ZAP](https://github.com/zaproxy/zaproxy)：可以在在开发和测试应用程序时自动查找Web应用程序中的安全漏洞，由专门的国际志愿者团队积极维护。
* [Kisso](https://gitee.com/baomidou/kisso)：Java基于Cookie的SSO中间件低代码组件库。
* [JustAuth](https://github.com/justauth/JustAuth)：第三方授权登录的工具类库。
* [Passay](https://github.com/vt-middleware/passay)：Java的密码策略实现。
* [Tsunami](https://github.com/google/tsunami-security-scanner)：Tsunami是一款通用网络安全扫描器，具有可扩展的插件系统，可高置信度地检测高严重性漏洞，由谷歌开源。
* [PicketLink](https://github.com/picketlink/picketlink)：PicketLink是一个用于保护Java EE应用程序的安全框架。
* [DependencyCheck](https://github.com/jeremylong/DependencyCheck)：OWASP DependencyCheck是一种软件组合分析实用程序，可检测应用程序依赖中公开披露的漏洞。
* [SSLContext Kickstart](https://github.com/Hakky54/sslcontext-kickstart)：一个轻量级库，用于配置基于SSLContext或其他属性(例如TrustManager、KeyManager或受信任证书)的HTTP客户端或服务器，以通过SSLFactory提供的单向身份验证或双向身份验证通过SSL/TLS进行通信。
* [okta](https://github.com/okta/okta-spring-boot)：Okta Spring Boot Starter。
* [auth0-java](https://github.com/auth0/auth0-java)：Auth0平台的Java客户端库。
* [jCasbin](https://github.com/casbin/jcasbin)：Java中支持ACL、RBAC、ABAC等访问控制模型的授权库。
* [Keywhiz](https://github.com/square/keywhiz)：Keywhiz是一个用于分发和管理密钥的系统。
* [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz)：密码强度估计器。
* [BurpGPT](https://github.com/aress31/burpgpt)：Burp Suite扩展集成了OpenAI的GPT，可以执行额外的被动扫描以发现高度定制的漏洞，并支持运行任何类型的基于流量的分析。
* [Janssen](https://github.com/JanssenProject/jans)：数字身份基础设施软件协作中心。
* [Bcrypt](https://github.com/patrickfav/bcrypt)：bcrypt密码哈希函数的Java独立实现。
* [Spring Session](https://github.com/spring-projects/spring-session)：Spring Session提供了一个API和实现来管理用户的会话信息，同时也使得支持集群会话变得很简单，而无需绑定到应用程序容器特定的解决方案。
* [2FA](https://github.com/j256/two-factor-auth)：2因素身份验证(2FA)Java代码，使用基于时间的一次性密码(TOTP)算法。
* [Microsoft Authentication Library](https://github.com/AzureAD/microsoft-authentication-library-for-java)：MSAL4J使应用程序能够与Microsoft身份平台集成。
* [Firebase Admin SDK](https://github.com/firebase/firebase-admin-java)：Firebase Admin提供的Java SDK。
* [RiskScanner](https://github.com/fit2cloud/riskscanner)：RiskScanner是开源的多云安全合规扫描平台，基于Cloud Custodian、Prowler和Nuclei引擎，实现对主流公(私)有云资源的安全合规扫描和漏洞扫描。
* [PowerAuth](https://github.com/wultra/powerauth-crypto)：PowerAuth是一种用于密钥交换和后续请求签名的协议，专为具有高安全性要求的应用程序(例如银行应用程序或身份管理应用程序)而设计。
* [OWASP Java Encoder](https://github.com/OWASP/owasp-java-encoder)：OWASP Java Encoder是一个简单易用的嵌入式高性能编码器类，没有依赖且包袱很少，由OWASP开源。

<h4 id="authentication">身份认证</h4>

* [Spring Security](https://github.com/spring-projects/spring-security)：Spring生态提供的安全框架。
* [Apache Shiro](https://github.com/apache/shiro)：Apache下开源的功能强大且易于使用的Java安全框架，可以执行身份验证、授权、加密和会话管理。
* [Apereo CAS](https://github.com/apereo/cas)：集中认证服务平台，可用于企业内部单点登录系统。
* [Google Authenticator](https://github.com/google/google-authenticator)：Google Authenticator项目包括针对多个移动平台的一次性密码生成器的实现。
* [andOTP](https://github.com/andOTP/andOTP)：适用于Android的开源双因素身份验证。
* [Soter](https://github.com/Tencent/soter)：腾讯主导的Android下安全、快速的生物识别认证标准及平台。
* [XXL-SSO](https://github.com/xuxueli/xxl-sso)：分布式单点登录框架。
* [GoogleAuth](https://github.com/wstrange/GoogleAuth)：GoogleAuth是一个Java服务器库，它实现RFC 6238中指定的基于时间的一次性密码(TOTP)算法。
* [Sa-Token](https://github.com/dromara/sa-token)：由dromara社区开源的轻量级Java权限认证框架。
* [java-cas-client](https://github.com/apereo/java-cas-client)：Apereo Java CAS客户端库。
* [Athenz](https://github.com/AthenZ/athenz)：Athenz是一个开源平台，用于动态基础设施中基于X.509证书的服务身份验证和细粒度访问控制，由Yahoo开源。
* [Sureness](https://github.com/dromara/sureness)：由dromara社区开源的一个简单高效的安全框架。
* [WSO2 Identity Server](https://github.com/wso2/product-is)：WSO2 Identity Server是一种开源身份和访问管理解决方案，跨企业和云服务环境联合和管理身份。它支持多种身份验证协议，例如SAML 2.0 Web SSO、OpenID、OAuth 2.0、OpenID Connect和WS-Federation Passive。
* [Android-Goldfinger](https://github.com/infinum/Android-Goldfinger)：用于简化生物识别身份验证实施的Android库。
* [Akto](https://github.com/akto-api-security/akto)：即时、开源API安全、API发现、自动化业务逻辑测试和运行时检测。
* [UAF](https://github.com/eBay/UAF)：通用认证框架，由eBay开源。
* [SocialAuth](https://github.com/3pillarlabs/socialauth)：用于在Google、Yahoo、Facebook、Twitter、LinkedIn和许多其他提供商上进行身份验证、获取个人资料、联系人和更新状态的Java库。
* [Apache Syncope](https://github.com/apache/syncope)：Apache Syncope是一个用于管理企业环境中的数字身份的开源系统，采用Java EE技术实现。
* [Vertx-Auth](https://github.com/eclipse-vertx/vertx-auth)：包含Vert.x和常见身份验证接口的身份验证实现。
* [OACC](https://github.com/acciente/oacc-core)：是一个功能齐全的API，可强制执行和管理应用程序的身份验证和授权需求。
* [Waffle](https://github.com/Waffle/waffle)：Waffle是一个本机Windows身份验证框架，执行与Windows身份验证相关的功能，支持Negotiate、NTLM和Kerberos。
* [WebAuthn4J](https://github.com/webauthn4j/webauthn4j)：用于WebAuthn和Apple App Attest服务器端验证的可移植Java库。
* [OpenAM](https://github.com/OpenIdentityPlatform/OpenAM)：OpenAM是一种访问管理解决方案，包括身份验证、SSO、授权、联合、权利和Web服务安全。

<h4 id="jwt">JWT库</h4>

* [JJWT](https://github.com/jwtk/jjwt)：适用于Java和Android的JWT库。
* [Java-JWT](https://github.com/auth0/java-jwt)：JWT的Java实现。
* [JWT-Starter](https://github.com/bfwg/springboot-jwt-starter)：适用于无状态和基于令牌的身份验证应用程序的Spring Boot JWT Starter套件。
* [Jose4j](https://bitbucket.org/b_c/jose4j/src/master/)：一个健壮且易于使用的JWT和JOSE规范套件(JWS、JWE和JWK)的开源实现。
* [Nimbus-JOSE-JWT](https://connect2id.com/products/nimbus-jose-jwt)：适用于Java和Android的JWT库。
* [FusionAuth-JWT](https://github.com/FusionAuth/fusionauth-jwt)：一个简单易用的Java 8 JWT库。
* [Vert.x Auth](https://github.com/vert-x3/vertx-auth)：Vertx框架提供JWT集成的库。
* [Inverno](https://github.com/inverno-io/inverno-mods/tree/master/inverno-security-jose)：Inverno框架提供JWT库，提供JSON对象签名和加密RFC规范的完整实现。
* [JWT](https://github.com/PhilJay/JWT)：轻量级Kotlin JWT实现。
* [Jwks RSA](https://github.com/auth0/jwks-rsa-java)：使用流式的API轻松创建和解析JWT并创建自定义JWT验证器。

<h4 id="oauth">OAuth库</h4>

* [SuperTokens](https://github.com/supertokens/supertokens-core)：Auth0/Firebase Auth/AWS Cognito的开源替代品。
* [ScribeJava](https://github.com/scribejava/scribejava)：适用于Java的简单OAuth库。
* [Spring Authorization Server](https://github.com/spring-projects/spring-authorization-server)：Spring生态中提供的OAuth 2.1授权服务器支持。
* [AppAuth](https://github.com/openid/AppAuth-Android)：用于与OAuth 2.0和OIDC提供商进行通信的Android客户端SDK。
* [Pac4j](https://github.com/pac4j/pac4j)：简单而强大的Java安全框架，支持OAuth、CAS、SAML、OIDC、LDAP、JWT。
* [UAA](https://github.com/cloudfoundry/uaa)：CloudFoundry用户帐户和身份验证(UAA)服务器。
* [MaxKey](https://github.com/dromara/MaxKey)：业界领先的IAM-IDaas身份管理和认证产品,支持OAuth 2.x、OIDC、SAML 2.0、JWT、CAS、SCIM等SSO标准协议，由dromara社区开源。
* [PlayAuthenticate](https://github.com/joscha/play-authenticate)：Play框架2.x(Java)的身份验证插件。
* [OAuth-Apis](https://github.com/OAuth-Apis/apis)：该项目提供了一个OAuth 2.0授权服务器，可用于配置API身份验证，目前不再维护。
* [Google OAuth Client](https://github.com/googleapis/google-oauth-java-client)：由Google编写的一个功能强大且易于使用的Java库，适用于OAuth 1.0和OAuth 2.0授权标准。
* [oxAuth](https://github.com/GluuFederation/oxAuth)：OAuth 2.0服务器和客户端；OIDC提供商(OP)和UMA授权服务器(AS)。
* [Java Authorization Server](https://github.com/authlete/java-oauth-server)：这是Java中的授权服务器实现，支持OAuth 2.0和OpenID Connect。
* [JOAuth](https://github.com/twitter/joauth)：使用OAuth验证HTTP请求的Java库，由Twitter开源。
* [MITREid-Connect](https://github.com/mitreid-connect/OpenID-Connect-Java-Spring-Server)：该服务器可用作OpenID Connect身份提供商以及通用OAuth 2.0授权服务器。
* [oauth2-essentials](https://github.com/dmfs/oauth2-essentials)：基于http-client-essentials的OAuth2客户端实现。
* [Tokens](https://github.com/zalando/tokens)：Tokens是一个用于验证和存储OAuth 2.0服务访问令牌的Java库，它具有弹性、可配置且经过生产测试，并且适用于所有JVM语言，由Zalando开源。
* [Keycloak](https://github.com/keycloak/keycloak)：Keycloak是适用于现代应用程序和服务的开源身份和访问管理解决方案，由RedHat基金会开源。
* [Smart-SSO](https://github.com/a466350665/smart-sso)：Spring Boot SSO单点登录，OAuth2实现，支持App登录、分布式。
* [JustAuthPlus](https://gitee.com/fujieid/jap)：一款开源的登录认证中间件，基于模块化设计，为所有需要登录认证的Web应用提供一套标准的技术解决方案。

<h4 id="encryption">加密库</h4>

* [Tink](https://github.com/google/tink)：Tink是一个多语言、跨平台、开源库，提供安全、易于正确使用且难以误用的加密API，由Google开源。
* [Bouncy Castle Java](https://github.com/bcgit/bc-java)：Bouncy Castle Java发行版。
* [Jasypt](https://github.com/jasypt/jasypt)：Jasypt是一个允许开发人员以最小的努力向项目添加基本加密功能的Java库。
* [Cryptomator](https://github.com/cryptomator/cryptomator)：对云中文件进行多平台透明客户端加密。
* [Hawk](https://github.com/orhanobut/hawk)：适用于Android的安全、简单的键值存储。
* [Wycheproof](https://github.com/google/wycheproof)：Wycheproof项目针对已知攻击测试加密库。
* [Bt](https://github.com/atomashpolskiy/bt)：BitTorrent库和客户端，具有DHT、磁力链接、加密等功能。
* [Peergos](https://github.com/Peergos/Peergos)：P2P、安全文件存储、社交网络和应用程序协议。
* [I2P](https://github.com/i2p/i2p.i2p)：I2P是一个匿名网络，提供一个简单的层，身份敏感的应用程序可以使用它来安全地通信。
* [AndroidWM](https://github.com/huangyz0918/AndroidWM)：一个支持隐写术的Android图像水印库。
* [Cipher.so](https://github.com/linisme/Cipher.so)：将密码等安全数据加密到本机.so库中的简单方法。
* [Conscrypt](https://github.com/google/conscrypt)：Conscrypt是一个Java安全提供程序，它实现了部分Java加密扩展和Java安全套接字扩展，由谷歌开源。
* [Apache Commons Crypto](https://github.com/apache/commons-crypto)：Apache Commons Crypto是一个使用AES-NI(高级加密标准新指令)优化的加密库，它提供了密码级别和Java流级别的Java API。
* [Whorlwind](https://github.com/square/whorlwind)：Android指纹API的响应式包装器，使用指纹处理敏感数据的加密/解密。
* [Encrypt](https://github.com/GcsSloop/encrypt)：适用于Java和Android的加解密工具库。
* [Java-AES-Crypto](https://github.com/tozny/java-aes-crypto)：一个简单的Android库，用于加密和解密字符串，旨在避免大多数此类类所遭受的经典错误。
* [Spring Cloud Config AWS KMS Add-on](https://github.com/zalando/spring-cloud-config-aws-kms)：这是一个Spring Cloud Config附加组件，通过AWS KMS提供加密，由Zalando开源。
* [EncryptedPreferences](https://github.com/PDDStudio/EncryptedPreferences)：适用于Java和Android的AES-256加密SharedPreferences。
* [OTP-Java](https://github.com/BastiaanJansen/OTP-Java)：一款小型且易于使用的Java一次性密码生成器，实现RFC 4226(HOTP)和RFC 6238(TOTP)。
* [Keyczar](https://github.com/google/keyczar)：易于使用的加密工具包，由Google开源。
* [Apache Santuario](https://santuario.apache.org/)：实现XML数字签名规范和XML加密规范的库。
* [Themis](https://github.com/cossacklabs/themis)：易于使用的数据保护加密框架，具有前向保密和安全数据存储的安全消息传递。
* [Password4j](https://github.com/Password4j/password4j)：Password4j是一个Java用户友好的加密库，用于使用不同的密钥派生函数(KDF)和加密哈希函数(CHF)来加密和验证密码。
* [Kalium](https://github.com/abstractj/kalium)：网络和密码学(NaCl)库的Java绑定。

<h2 id="transaction">事务</h2>

* [Seata](https://github.com/seata/seata)：Seata是一个易于使用、高性能、开源的分布式事务解决方案，由阿里开源。
* [ByteTCC](https://github.com/liuyangming/ByteTCC)：ByteTCC是一个基于TCC(Try/Confirm/Cancel)机制的分布式事务管理器，它与JTA规范兼容。
* [Atomikos](https://github.com/atomikos/transactions-essentials)：Java的分布式事务管理库。
* [Narayana](https://github.com/jbosstm/narayana)：Narayana是一个事务工具包，为使用各种基于标准的事务协议开发的应用程序提供支持。
* [Bitronix](https://github.com/bitronix/btm)：Bitronix事务管理器(BTM)是JTA 1.1 API的简单但完整的实现。
* [AtlasDB](https://github.com/palantir/atlasdb)：事务分布式数据库层。
* [Hmily](https://github.com/dromara/hmily)：分布式事务解决方案，由dromara社区开源。
* [TCC-Transaction](https://github.com/changmingxie/tcc-transaction)：开源的微服务架构下的TCC型分布式事务解决方案。
* [Multiverse](https://github.com/pveentjer/Multiverse)：JVM的软件事务内存实现。
* [LCN](https://github.com/codingapi/tx-lcn)：LCN分布式事务框架，兼容Dubbo、Spring Cloud、Motan框架，支持各种关系数据库。
* [EasyTransaction](https://github.com/QNJR-GROUP/EasyTransaction)：分布式事务解决方案，统一使用TCC、SAGA、FMT、可靠消息、补偿等。
* [Servicecomb-pack](https://github.com/apache/servicecomb-pack)：提供TCC和Saga分布式事务协调解决方案，使用Alpha作为事务协调器，Omega作为事务代理，在Apache基金会下开源。
* [Raincat](https://github.com/dromara/raincat)：强一致分布式事务框架。
* [Scalardb](https://github.com/scalar-labs/scalardb)：通用事务管理器。
* [ByteJTA](https://github.com/liuyangming/ByteJTA)：ByteJTA是一个基于XA/2PC机制的分布式事务管理器，它与JTA规范兼容。
* [Myth](https://gitee.com/dromara/myth)：采用消息队列解决分布式事务的开源框架。

<h2 id="template-engine">模板引擎</h2>

* [Thymeleaf](https://github.com/thymeleaf/thymeleaf)：Thymeleaf是一个现代服务器端Java模板引擎，适用于Web和独立环境。
* [JSP](https://www.oracle.com/java/technologies/jspt.html)：JSP是Java应用程序最流行的视图技术之一，也是内置的模板引擎。
* [Apache FreeMarker](https://github.com/apache/freemarker)：FreeMarker是一个基于模板生成文本输出(从HTML到自动生成源代码的任何内容)的通用工具。
* [Pebble](https://github.com/PebbleTemplates/pebble)：Pebble是一个受Twig启发的Java模板引擎。
* [Groovy](http://groovy-lang.org/templating.html#_the_markuptemplateengine)：Groovy提供Markup模板引擎，该引擎基于构建器语法，可用于生成任何文本格式。
* [Apache Velocity](https://github.com/apache/velocity-engine)：Apache Velocity是一个用Java编写的通用模板引擎。
* [Mustache](https://github.com/spullara/mustache.java)：Mustache是一个支持许多其他编程语言的模板引擎。
* [Apache Tiles](https://github.com/apache/tiles)：适用于现代Java应用程序的免费开源模板框架。
* [Jade4j](https://github.com/neuland/jade4j)：用Java编写的jade实现，现在改成pug4j。
* [Handlebars.java](https://github.com/jknack/handlebars.java)：使用Java的无逻辑和语义Mustache模板。
* [Beetl](https://github.com/javamonkey/beetl2.0)：新一代的模板引擎，更简单易用。
* [Rocker](https://github.com/fizzed/rocker)：Java 8优化、内存高效、快速模板引擎生成静态类型、纯Java对象。
* [Jinja](https://github.com/HubSpot/jinjava)：基于Django模板语法的基于Java的模板引擎，适用于渲染Jinja模板。
* [HTTL](https://github.com/httl/httl)：HTTL是一个高性能的开源Java模板引擎，适用于动态HTML页面输出，可替代JSP页面，指令和Velocity相似。
* [HtmlFlow](https://github.com/xmlet/HtmlFlow/)：HtmlFlow是一种Java DSL，可以以流式的方式编写类型安全的HTML文档。
* [Chunk](https://github.com/tomj74/chunk-templates)：Chunk是一个Java模板引擎，适用于服务HTML或XML的应用程序。
* [Trimou](https://github.com/trimou/trimou)：Java中的Mustache/Handlebars模板引擎。
* [Rythm](https://github.com/rythmengine/rythmengine)：类似Razor、功能丰富、高性能且易于使用的Java模板引擎。
* [Liqp](https://github.com/bkiers/Liqp)：基于ANTLR的“Liquid模板”解析器和渲染引擎。
* [StringTemplate](https://github.com/antlr/stringtemplate4)：StringTemplate是一个Java模板引擎，用于生成源代码、网页、电子邮件或任何其他格式化文本输出。
* [JTE](https://github.com/casid/jte)：适用于Java和Kotlin的安全且快速的模板。

<h2 id="json">JSON库</h2>

* [Jackson](https://github.com/FasterXML/jackson-databind)：Java中使用最广泛的JSON库，也是Spring默认的JSON处理器。
* [Gson](https://github.com/google/gson)：由Google开源的一个JSON序列化/反序列化库。
* [Fastjson](https://github.com/alibaba/fastjson)：由阿里开源的一个JSON处理库，性能较好。
* [Moshi](https://github.com/square/moshi)：适用于Kotlin和Java的现代JSON库。
* [JsonPath](https://github.com/json-path/JsonPath)：JsonPath的实现版本。
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare)：适用于Android的快速JSON解析和序列化库。
* [JSON-P](https://github.com/jakartaee/jsonp-api)：JSON-P是一个用于解析、构建、转换和查询JSON消息的属于Jakarta EE规范下的API。
* [Kryo](https://github.com/EsotericSoftware/kryo)：快速、高效、自动化的Java对象序列化和克隆库。
* [Eclipse Yasson](https://github.com/eclipse-ee4j/yasson)：由Eclipse开源的一个JSON处理库，也是JSR-367的官方参考实现。
* [HikariJSON](https://github.com/brettwooldridge/HikariJSON)：高性能JSON解析器。
* [Eclipse Parsson](https://github.com/eclipse-ee4j/parsson)：Eclipse Parsson是Jakarta JSON Processing规范的实现。
* [JsonLube](https://github.com/alibaba/JsonLube)：JsonLube可以在编译期自动生成JSON解析代码，用户使用方式更简单，同时能收获原生解析的性能，由阿里开发。
* [JSON.simple](https://github.com/fangyidong/json-simple)：非常简单的JSON库，可以用于编码和解码JSON文本。
* [JSON-Java](https://github.com/stleary/JSON-java)：Java中JSON包的参考实现。
* [JSON-io](https://github.com/jdereg/json-io)：小巧、轻量级的JSON和Java对象转换库。
* [Jsoniter](https://github.com/json-iterator/java)：Jsoniter(json-iterator)是Java和Go中可用的快速且灵活的JSON解析器。
* [Genson](https://github.com/owlike/genson)：Genson是一个完整的JSON转换库，提供完整的数据绑定、流媒体等等。
* [Jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo)：从JSON或JSON Schema生成Java类型，并标注这些类型以与Jackson、Gson等进行数据绑定。
* [DSL-JSON](https://github.com/ngs-doo/dsl-json)：高性能JVM JSON库，具有高级编译时数据绑定支持。
* [Ason](https://github.com/afollestad/ason)：提供JSON序列化功能的Java库，已经停止维护。
* [jsonld-java](https://github.com/jsonld-java/jsonld-java)：JSON-LD 1.0规范和JSON-LD-API 1.0规范的Java实现。
* [Jolt](https://github.com/bazaarvoice/jolt)：使用Java编写的JSON到JSON转换库。
* [Instagram Json Parser](https://github.com/Instagram/ig-json-parser)：用于Java项目的快速JSON解析器，由Instagram开源。
* [Minimal Json](https://github.com/ralfstx/minimal-json)：一个快速、小型的Java JSON解析器和写入器。
* [JSON Sanitizer](https://github.com/OWASP/json-sanitizer)：给定类似JSON的内容，JSON Sanitizer会将其转换为有效的JSON，由OWASP开源。
* [Jfire-codejson](https://gitee.com/eric_ds/jfire-codejson)：性能非常高的JSON序列化和反序列化库。
* [Snack3](https://gitee.com/noear/snack3)：一个高性能的JsonPath框架，支持序列化反序列化、解析和转换、构建、查找、JsonPath查询。
* [Sawmill](https://github.com/logzio/sawmill)：Sawmill是一个JSON转换Java库。
* [JSON Schema Validator](https://github.com/networknt/json-schema-validator)：这是用于JSON模式验证的JSON Schema规范的Java实现。
* [OkJson](https://gitee.com/calvinwilliams/okjson)：Java编写的小巧、高效、灵活的JSON处理器。
* [JSON Schema Validator](https://github.com/java-json-tools/json-schema-validator)：Java中的纯JSON模式验证实现，具有可靠的正确性和性能。
* [JsonSurfer](https://github.com/wanglingsong/JsonSurfer)：Java中的流式JsonPath处理器。
* [Problem](https://github.com/zalando/problem)：一个实现application/problem+json的Java库，由Zalando开源。

<h2 id="mapper">Bean映射</h2>

* [MapStruct](https://github.com/mapstruct/mapstruct)：用于生成类型安全Bean映射器的注解处理器。
* [Dozer](https://github.com/DozerMapper/dozer)：一个强大的，通用的，灵活的，可重用的和可配置的开源映射框架。
* [ModelMapper](https://github.com/modelmapper/modelmapper)：智能对象映射库。
* [Orika](https://github.com/orika-mapper/orika)：更简单、更好、更快的Java Bean映射框架。
* [JMapper](https://github.com/jmapper-framework/jmapper-core)：集优雅、高性能和稳健性于一体的Java Bean映射器。
* [Selma](https://github.com/xebia-france/selma)：可以在编译时生成Java代码处理字段到字段映射的注解处理器。
* [BeanMapper](https://github.com/42BV/beanmapper)：用于根据Bean约定从一个Java类转换为名称相似的不同Java类的库。
* [Tamper](https://github.com/alibaba/tamper)：Tamper是一款处理Bean/Map进行属性复制映射的工具，支持递归、集合等深度映射。
* [ReMap](https://github.com/remondis-it/remap)：用于简化可测试对象映射的声明式映射库。
* [Bull](https://github.com/ExpediaGroup/bull)：Bull是一种Java Bean到Java Bean转换器，通用、灵活、可重用、可配置，并且速度非常快。
* [Datus](https://github.com/roookeee/datus)：Datus使你能够在流式的函数式API中定义两个数据结构之间的转换过程。

<h2 id="cli">CLI</h2>

* [Picocli](https://github.com/remkop/picocli)：Picocli是一个现代框架，用于轻松构建功能强大、用户友好、支持GraalVM的命令行应用程序。
* [SDKMAN](https://github.com/sdkman/sdkman-cli)：SDKMAN是一个用于在任何基于Unix的系统上管理多个软件开发套件的并行版本的工具。
* [JBang](https://github.com/jbangdev/jbang)：JBang是一个将脚本引入Java领域的框架。
* [JCommander](https://github.com/cbeust/jcommander)：基于Java 8注解的参数解析框架。
* [JLine](https://github.com/jline/jline3)：JLine是一个用于处理控制台输入的Java库。
* [Spring Shell](https://github.com/spring-projects/spring-shell)：Spring Shell可帮助你创建基于Spring的、针对CLI空间的生产级应用程序。
* [Lanterna](https://github.com/mabe02/lanterna)：Lanterna是一个Java库，允许你在纯文本环境中编写简单的半图形用户界面。
* [Just](https://github.com/maciejwalkowiak/just)：用于开发Spring Boot应用程序的命令行工具包。
* [JReleaser](https://github.com/jreleaser/jreleaser)：JReleaser是一个用于Java和非Java项目的自动化发布工具。
* [Jansi](https://github.com/fusesource/jansi)：Jansi是一个小型Java库，允许使用ANSI转义序列来格式化控制台输出，甚至可以在Windows上运行。
* [ASCII Table](https://github.com/vdmeer/asciitable)：文本表的几种实现，最初使用ASCII和UTF-8字符作为边框。
* [Crash](https://github.com/crashub/crash)：Crash是一个为扩展Java程序和Java虚拟机而设计的Shell。
* [Text-IO](https://github.com/beryx/text-io)：Text-IO是一个用于创建Java控制台应用程序的库，它可用于需要读取用户交互式输入的应用程序。
* [Java ASCII Render](https://github.com/indvd00m/java-ascii-render)：纯Java的ASCII渲染器，没有外部依赖。
* [Apache Commons CLI](https://github.com/apache/commons-cli)：Apache Commons CLI提供了一个简单的API，用于呈现、处理和验证命令行界面。
* [MCS](https://github.com/mthmulders/mcs)：可以从命令行搜索Maven中央仓库。
* [JD-Core](https://github.com/java-decompiler/jd-core)：JD-Core是一个用Java编写的Java反编译器。
* [JD-CLI](https://github.com/intoolswetrust/jd-cli)：JD-CLI是JD-Core项目的简单命令行包装器。
* [Airline](https://github.com/rvesse/airline)：基于Java注解的框架，用于解析类似Git的命令行结构，具有深度可扩展性。
* [JBock](https://github.com/jbock-java/jbock)：无反射命令行解析器。
* [Args4j](https://github.com/kohsuke/args4j)：Args4j是一个小型Java类库，可以轻松解析CUI应用程序中的命令行选项/参数。
* [Aesh](https://github.com/aeshell/aesh)：Aesh是一个用于处理控制台输入的Java库。
* [JeeSh](https://github.com/jeeshell/je2sh)：JVM可扩展和可嵌入Shell。
* [ConsoleUI](https://github.com/awegmann/consoleui)：微型Java库，可在基于ANSI控制台的终端上启用简单的UI元素。
* [Progressbar](https://github.com/ctongfei/progressbar)：Java/JVM基于终端的进度条。
* [Jexer](https://gitlab.com/AutumnMeowMeow/jexer)：高级控制台(和Swing)文本用户界面库，具有可鼠标拖动的窗口、内置终端窗口管理器和Sixel图像支持。

<h2 id="ssh">SSH工具</h2>

* [SSHJ](https://github.com/hierynomus/sshj)：用于Java的SSH、SCP和SFTP。
* [Bastillion](https://github.com/bastillion-io/Bastillion)：Bastilion是一个基于Web的SSH控制台，可集中管理对系统的管理访问。
* [ConnectBot](https://github.com/connectbot/connectbot)：ConnectBot是适用于Android的安全Shell客户端，可让你通过加密安全链接连接到远程服务器。
* [Snowflake](https://github.com/subhra74/snowflake)：图形化SFTP客户端和终端仿真器以及有用的实用程序。
* [Apache MINA SSHD](https://github.com/apache/mina-sshd)：Apache MINA sshd是一个用于客户端和服务器端SSH的综合Java库。
* [Pty4J](https://github.com/JetBrains/pty4j)：Java中的伪终端(PTY)实现。
* [JediTerm](https://github.com/JetBrains/jediterm)：纯Java终端模拟器，适用于SSH和PTY，由JetBrains开源。
* [JSch](https://github.com/mwiede/jsch)：实现SSH功能的Java库，可用于连接SFTP服务器。
* [Jcabi-SSH](https://github.com/jcabi/jcabi-ssh)：Java SSH客户端(JSch的面向对象包装器)。
* [JSch](https://github.com/is/jsch)：JSch是SSH2的纯Java实现。

<h2 id="ssh">DNS&内网穿透</h2>

* [DNS66](https://github.com/julian-klode/dns66)：适用于Android的基于DNS的主机拦截器。
* [NoPE Proxy](https://github.com/summitt/Burp-Non-HTTP-Extension)：Burp Suite的非HTTP协议扩展(NoPE)代理和DNS。
* [DNSJava](https://github.com/dnsjava/dnsjava)：DNS协议的Java实现。
* [DNS Proxy](https://github.com/mageddo/dns-proxy-server)：用于从Docker容器、本地配置、互联网中解析DNS主机。
* [Dns Cache Manipulator](https://github.com/alibaba/java-dns-cache-manipulator)：一个微小的0依赖线程安全Java库，用于以编程方式设置/查看DNS，无需接触host文件，使单元/集成测试可移植，由阿里开源。
* [Denominator](https://github.com/Netflix/denominator)：Denominator是一个用于操作DNS云的可移植Java库，由Netflix开源。
* [Happy DNS](https://github.com/qiniu/happy-dns-android)：用于Android的DNS库。
* [DNS-Java](https://github.com/spotify/dns-java)：提供了一些与SRV查找相关的有用功能的小型DNS包装器库，由Spotify开源。
* [DNS-Cheater](https://gitee.com/matrixy/dns-cheater)：Java实现的DNS服务器，可通过WEB管理界面随意设置灵活的解析规则。
* [Neutrino-Proxy](https://gitee.com/dromara/neutrino-proxy)：一款基于Netty的内网穿透神器，由dromara社区开源。
* [Lanproxy](https://gitee.com/fengfei/lanproxy)：Lanproxy是一个将局域网个人电脑、服务器代理到公网的内网穿透工具。
* [MagpieBridge](https://gitee.com/jiucheng_org/magpiebridge)：使用Java基于AIO/NIO实现的内网穿透工具。

<h2 id="git">Git工具</h2>

* [Gitblit](https://github.com/gitblit-org/gitblit)：Gitblit是一个开源、纯Java Git解决方案，用于管理、查看和服务Git仓库。
* [Gitiles](https://github.com/google/gitiles)：Gitiles是一个简单的Git存储库浏览器，基于JGit构建，由Google开源。
* [Agit](https://github.com/rtyley/agit)：Agit是适用于Android设备的开源Git客户端。
* [Kooder](https://github.com/oschina/kooder)：Kooder是一个为Gitee/GitLab开发的开源代码搜索工具。
* [Jcabi-Github](https://github.com/jcabi/jcabi-github)：GitHub API的Java面向对象包装器。
* [RepoSense](https://github.com/reposense/RepoSense)：Git存储库的贡献分析工具。
* [JGit](https://eclipse.dev/jgit/)：可以用于操作Git存储库的纯Java实现。
* [Git Commit Id Maven Plugin](https://github.com/git-commit-id/git-commit-id-maven-plugin)：可以将构建时Git仓库信息包含到POJO/properties文件中。
* [GitLab4J](https://github.com/gitlab4j/gitlab4j-api)：GitLab4J提供了功能齐全且易于使用的Java库，用于通过GitLab REST API使用GitLab存储库。
* [GitSolo](https://gitee.com/zhiqim/gitsolo)：知启蒙团队开源的极简Git服务器，纯Java开发。
* [Github Java API](https://github.com/hub4j/github-api)：GitHub的Java API。
* [BitHub](https://github.com/signalapp/BitHub)：BitHub是一项服务，每次提交到GitHub仓库时都会自动支付一定比例的比特币资金。

<h2 id="collection">集合库</h2>

* [Apache Commons Collections](https://github.com/apache/commons-collections)：Apache基金会下的开源Java集合工具库。
* [Eclipse Collections](https://github.com/eclipse/eclipse-collections)：Eclipse Collections是一个Java集合框架，具有优化的数据结构和丰富、实用且流式的API。
* [Fastutil](https://github.com/vigna/fastutil)：Fastutil通过提供特定于类型的Map、Set、List和Queue来扩展Java集合框架。
* [HPPC](https://github.com/carrotsearch/hppc)：Java的高性能原始类型集合。
* [PCollections](https://github.com/hrldcpr/pcollections)：PCollections充当Java集合框架的持久且不可变的类似物。
* [CQEngine](https://github.com/npgall/cqengine)：集合查询引擎–是一个高性能Java集合，可以使用类似SQL的查询进行搜索，并且延迟极低。
* [Agrona](https://github.com/real-logic/agrona)：Java的高性能数据结构和实用方法。
* [Koloboke](https://github.com/leventov/Koloboke)：精心设计的Java集合框架扩展，具有原始类型特化等功能。
* [Javolution](https://github.com/javolution/javolution)：用于实时和嵌入式系统的Java核心库。
* [Trove](https://bitbucket.org/trove4j/trove/src/master/)：为Java提供高速对象和原始集合。
* [Primitive-Collections](https://github.com/Speiger/Primitive-Collections)：一个原始集合库，可减少内存使用并提高性能。
* [Capsule](https://github.com/usethesource/capsule)：Capsule旨在成为Java 11+的成熟(不可变)集合库，完全围绕持久尝试构建。
* [LMAXCollections](https://github.com/LMAX-Exchange/LMAXCollections)：高性能集合库。
* [Paguro](https://github.com/GlenKPeterson/Paguro)：JVM的泛型、空安全、不可变集合和函数式转换。
* [Persistent Collections](https://github.com/pmem/pcj)：Java的持久集合库。
* [Zero-Allocation Hashing](https://github.com/OpenHFT/Zero-Allocation-Hashing)：用于对Java中的任何字节序列进行哈希处理，包括各种原始数组、缓冲区、CharSequence等。

<h2 id="functional">函数式编程</h2>

* [Vavr](https://github.com/vavr-io/vavr)：Vavr是Java 8的对象函数语言扩展，旨在减少代码行数并提高代码质量。
* [StreamEx](https://github.com/amaembo/streamex)：对Java Stream API的增强库。
* [JOOL](https://github.com/jOOQ/jOOL)：为Java 8 Lambda提供了一些有用的扩展。
* [JavaTuples](https://github.com/javatuples/javatuples)：Java中元组的类型安全表示。
* [Apache Commons Functor](https://github.com/apache/commons-functor)：Apache Commons Functor库定义了通用函子和函子相关的接口、实现和实用程序。
* [Throwing Function](https://github.com/pivovarit/throwing-function)：支持受检异常的Java 8函数接口+适配器。
* [FunctionalJava](https://github.com/functionaljava/functionaljava)：Functional Java是一个开源库，促进Java中的函数式编程。
* [Cyclops](https://github.com/aol/cyclops)：一个先进且易于使用的平台，用于在Java 8中编写函数式应用程序。
* [Linq4j](https://github.com/julianhyde/linq4j)：LINQ的Java实现库。
* [Functional](https://github.com/io-fairy/functional)：提供更简单更好用的Java函数式编程接口。
* [Parallel-Collector](https://github.com/pivovarit/parallel-collectors)：可使用Stream API简化Java中的并行收集处理的工具包。
* [NoException](https://github.com/robertvazan/noexception)：用于以简洁、统一且架构干净的方式处理异常的Java库。
* [Protonpack](https://github.com/poetix/protonpack)：Java Stream API的实用工具库。
* [Totallylazy](https://github.com/bodar/totallylazy/)：用于Java的函数式编程库。
* [Retrolambda](https://github.com/luontola/retrolambda)：Retrolambda允许你在Java 7、6或5上运行带有Lambda表达式、方法引用和try-with-resources语句的Java 8代码。
* [Fugue](https://bitbucket.org/atlassian/fugue/src/master/)：Guava的函数式编程扩展。
* [Lambda](https://github.com/palatable/lambda)：Java的函数式模式。
* [Underscore Java](https://github.com/javadev/underscore-java)：Underscore.js的Java版本。
* [Faux-Pas](https://github.com/zalando/faux-pas)：一个简化Java函数式编程错误处理的库，由Zalando开源。
* [Lightweight-Stream-API](https://github.com/aNNiMON/Lightweight-Stream-API)：Java Stream API的扩展库。
* [LINQ](https://github.com/timandy/linq)：LINQ到对象转换的Java库。
* [More Lambda](https://github.com/PhantomThief/more-lambdas-java)：Java 8的一些有用的Lambda实现。
* [Formulog](https://github.com/HarvardPL/formulog)：支持SMT查询和一阶函数编程的数据记录。
* [Purefun](https://github.com/tonivade/purefun)：Java函数式编程库。
* [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow)：SneakyThrow是一个忽略受检异常的Java库。
* [Streams Utils](https://github.com/JosePaumard/streams-utils)：Streams Utils是一组基于Java 8 Stream编写的操作，它允许一些Java 8中不可用的基本操作。

<h2 id="bytecode">字节码操作</h2>

* [ASM](https://gitlab.ow2.org/asm/asm)：通用底层字节码操作和分析开发库。
* [Byte Buddy](https://github.com/raphw/byte-buddy)：Byte Buddy是一个代码生成和操作库，用于在Java应用程序运行时创建和修改Java类，而无需编译器的帮助。
* [Byteman](https://github.com/bytemanproject/byteman)：Byteman支持将副作用注入到Java程序中用于跟踪和测试应用程序行为的目的。
* [Apache Commons BCEL](https://github.com/apache/commons-bcel)：Apache Commons BCEL为用户提供一种便捷的方式来分析、创建和操作Java class文件。
* [Javassist](https://github.com/jboss-javassist/javassist)：Java字节码工程工具包。
* [CGLIB](https://github.com/cglib/cglib)：用于生成和转换Java字节码的高级API。
* [ByteX](https://github.com/bytedance/ByteX)：字节开源的字节码插件开发平台。
* [Allocation Instrumenter](https://github.com/google/allocation-instrumenter)：将字节码重写为工具分配站点的Java代理，由Google开源。
* [Soot](https://github.com/soot-oss/soot)：Soot是一个Java优化框架，提供了多种用于分析和转换Java字节码的中间表示形式。
* [Mixin](https://github.com/SpongePowered/Mixin)：Mixin是一个使用ASM的Java特征/混合和字节码编织框架。
* [RoboVM](https://github.com/MobiVM/robovm)：针对IOS、Mac OSX和Linux的JVM字节码AOT。
* [ByteKit](https://github.com/alibaba/bytekit)：Java字节码工具包，由阿里开发。
* [ProGuard](https://github.com/Guardsquare/proguard-core)：用于读取、写入、分析和处理Java字节码的库。
* [DroidAssist](https://github.com/didi/DroidAssist)：一个基于Javassist的轻量级Android Studio Gradle插件，用于在Android中编辑字节码，由滴滴开源。

<h2 id="image">图像处理</h2>

* [Thumbnailator](https://github.com/coobird/thumbnailator)：Java的缩略图生成库。
* [Pngtastic](https://github.com/depsypher/pngtastic/)：一个纯Java PNG图像优化和操作库。
* [ImageJ](https://github.com/imagej/ImageJ)：用于处理和分析科学图像的公共领域软件。
* [OpenIMAJ](https://github.com/openimaj/openimaj)：OpenIMAJ是一个屡获殊荣的库和工具集合，用于多媒体(图像、文本、视频、音频等)内容分析和内容生成。
* [Apache Commons Imaging](https://github.com/apache/commons-imaging)：Apache Commons Imaging是一个纯Java图像库。
* [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys)：Java ImageIO的附加插件和扩展。
* [OpenCV](https://github.com/openpnp/opencv)：OpenCV(开源计算机视觉)是一个用于实时计算机视觉和图像处理的库。
* [树洞OCR](https://github.com/AnyListen/tools-ocr)：一款跨平台的OCR小工具。
* [C-OCR](https://github.com/ctripcorp/C-OCR)：C-OCR是携程自研的OCR项目，主要包括身份证、护照、火车票、签证等旅游相关证件、材料的识别。
* [Tess4j](https://github.com/nguyenq/tess4j)：Tesseract OCR API的Java JNA包装器。
* [imgscalr](https://github.com/rkalla/imgscalr)：简单的Java图像缩放库，实现Chris Campbell的增量缩放算法以及Java 2D的“最佳实践”图像缩放技术。
* [Marvin](https://github.com/gabrielarchanjo/marvin-framework)：Marvin图像处理框架提供实时处理图像和视频的功能。
* [JavaCV](https://github.com/bytedeco/javacv)： OpenCV、FFmpeg等的Java接口。
* [Skija](https://github.com/JetBrains/skija)：Skia是一个开源2D图形库，提供可跨各种硬件和软件平台工作的通用API，由JetBrains开源。
* [webcam-capture](https://github.com/sarxos/webcam-capture)：该库允许你直接从Java使用内置或外部网络摄像头，它旨在抽象常用的相机功能并支持各种捕获框架。
* [Picasso](https://github.com/square/picasso)：一个强大的Android图像下载和缓存库。
* [Image Comparison](https://github.com/romankh3/image-comparison)：可以比较2个相同大小的图像，并通过绘制矩形直观地显示差异。
* [xmlgraphics-batik](https://github.com/apache/xmlgraphics-batik)：Batik是一个基于Java的工具包，适用于处理可缩放矢量图形(SVG)格式的图像各种目的，例如观看、生成或操纵。
* [Luban](https://github.com/Curzibn/Luban)：Android图片压缩工具，仿微信朋友圈压缩策略。
* [PixelFlow](https://github.com/diwi/PixelFlow)：用于高性能GPU计算(GLSL)处理的Java库。
* [ImageJ2](https://github.com/imagej/imagej2)：Image的重写版本，用于多维图像数据，重点是科学成像。
* [BoofCV](https://github.com/lessthanoptimal/BoofCV)：用于SFM、校准、基准、跟踪、图像处理等的快速计算机视觉库。
* [Scrimage](https://github.com/sksamuel/scrimage)：Java、Scala和Kotlin图像处理库。
* [cv4j](https://github.com/imageprocessor/cv4j)：一个用纯Java实现的高质量、实时的图像处理和机器学习库。
* [ImgLib2](https://github.com/imglib/imglib2)：用于图像处理的通用下一代Java库。
* [Imglib](https://github.com/nackily/imglib)：一个轻量级的Java图像处理库，致力于简化对图像的常见处理。
* [AndroidLibyuvImageUtils](https://github.com/myrao/AndroidLibyuvImageUtils)：Android上的图像处理库，基于libyuv。
* [ImageCombiner](https://gitee.com/dromara/image-combiner)：ImageCombiner是一个专门用于Java服务端图片合成的工具。
* [image-plugin](https://gitee.com/hellokaton/image-plugin)：非常简单的图片处理插件，可快速集成在Web应用中。
* [imagetool](https://gitee.com/xshuai/imagetool)：一个简单的图片处理工具，支持图片压缩、图片水印、图片裁剪、图片旋转、图片格式转换等功能。
* [JFreeSVG](https://github.com/jfree/jfreesvg)：一个快速、轻量级的Java库，用于创建可扩展矢量图形(SVG)输出。
* [Image2LaTeX](https://github.com/blaisewang/img2latex-mathpix)：Image2LaTeX提供将图像转换为某些LaTeX方程格式和OCR的核心功能。
* [MathOCR](https://github.com/chungkwong/MathOCR)：MathOCR是一个用纯Java编写的印刷科学文档识别系统，MathOCR具有图像预处理、布局分析和字符识别的功能，尤其是数学表达式的识别能力。
* [SikuliX](https://github.com/RaiMan/SikuliX1)：SikuliX可以自动化你在运行Windows、Mac或某些Linux/Unix的台式计算机屏幕上看到的任何内容，它使用由OpenCV提供支持的图像识别来识别GUI组件，并可以通过鼠标和键盘操作对其进行操作。
* [SealKit](https://gitee.com/liuzy1988/SealKit)：印章生成工具。

<h2 id="captcha">验证码</h2>

* [Captcha](https://github.com/anji-plus/captcha)：行为验证码(滑动拼图、点选文字)。
* [Captcha-Killer](https://github.com/c0ny1/captcha-killer)：burp验证码识别接口调用插件。
* [Captcha-Killer-Modified](https://github.com/f0ng/captcha-killer-modified)：captcha-killer的修改版，支持关键词识别Base64编码的图片，添加免费OCR库，用于验证码爆破，适配新版Burpsuite。
* [EasyCaptcha](https://gitee.com/ele-admin/EasyCaptcha)：Java图形验证码，支持Gif、中文、算术等类型，可用于Java Web、Java SE等项目。
* [Tianai-Captcha](https://gitee.com/tianai/tianai-captcha)：非常好用的开源行为验证码(滑块验证码、点选验证码、行为验证码、旋转验证码、滑动验证码)。
* [Kaptcha Spring Boot Starter](https://gitee.com/baomidou/kaptcha-spring-boot-starter)：简单快速集成Google Kaptcha验证码的库，由baomidou社区开源。
* [Happy-Captcha](https://gitee.com/ramostear/Happy-Captcha)：Happy Captcha是一款易于使用的Java验证码软件包。
* [kaptcha](https://github.com/penggle/kaptcha)：kaptcha生成引擎。
* [JCaptcha](https://mvnrepository.com/artifact/com.octo.captcha/jcaptcha/1.0)：一个可以生成图片、声音式验证码的Java库。

<h2 id="compress">压缩</h2>

* [CompressHelper](https://github.com/nanchen2251/CompressHelper)：文件、图片压缩工具类。
* [AdvancedLuban](https://github.com/shaohui10086/AdvancedLuban)：高效、简洁的图片压缩工具库。
* [JavaEWAH](https://github.com/lemire/javaewah)：
* [Apache Commons Compress](https://github.com/apache/commons-compress)：Apache Commons压缩软件定义了用于处理压缩和存档格式的API。
* [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap)：Java中更好的压缩位集。
* [LZF Compressor](https://github.com/ning/compress)：一个用于编码和解码LZF格式数据的Java库。
* [JZlib](http://www.jcraft.com/jzlib/)：JZlib是zlib在纯Java中的重新实现。
* [Snappy Java](https://github.com/xerial/snappy-java)：Snappy-Java是Snappy的Java移植版，Snappy是Google开发的快速C++压缩器/解压缩器。
* [LZMA](https://github.com/jponge/lzma-java)：该库为在Java平台上运行的应用程序提供LZMA压缩。
* [LZO](https://github.com/shevek/lzo-java)：liblzo2 LZO压缩算法的纯Java实现。
* [LZ4](https://github.com/lz4/lz4-java)：用于Java的LZ4压缩库。
* [YUI Compressor](https://github.com/yui/yuicompressor)：YUI Compressor是一个JavaScript压缩器，除了删除注释和空格之外，它还使用尽可能小的变量名称来混淆局部变量，该库由Yahoo开源。
* [Compress](https://gitee.com/yu120/compress)：基于gzip、deflate、lz4、snappy、lzo等算法实现数据压缩，主要用于RPC通讯数据的压缩。
* [Zip4j](https://github.com/srikanth-lingala/zip4j)：Zip4j是一个全面的zip文件或流Java库。

<h2 id="crawler">爬虫</h2>

* [Crawler4j](https://github.com/yasserg/crawler4j)：Java开源网络爬虫库。
* [Apache Nutch](https://github.com/apache/nutch)：Apache Nutch是一个可扩展且可伸缩的网络爬虫库。
* [WebMagic](https://github.com/code4craft/webmagic)：用于Java的可扩展网络爬虫框架。
* [Jsoup](https://github.com/jhy/jsoup/)：Java HTML解析器，专为HTML编辑、清理、抓取和XSS安全而构建。
* [StormCrawler](https://github.com/DigitalPebble/storm-crawler)：基于Apache Storm的可扩展、成熟且多功能的网络爬虫库。
* [Sparkler](https://github.com/USCDataScience/sparkler)：在Apache Spark上运行的类似Apache Nutch的爬虫库。
* [Spider-Flow](https://github.com/ssssssss-team/spider-flow)：新一代爬虫平台，以图形化方式定义爬虫流程，不写代码即可完成爬虫。
* [WebCollector](https://github.com/CrawlScript/WebCollector)：WebCollector是一个基于Java的开源网络爬虫框架，提供了一些简单的网络爬虫接口。
* [Heritrix](https://github.com/internetarchive/heritrix3)：Heritrix是互联网档案馆的开源、可扩展、网络规模、档案质量的网络爬虫项目。
* [Gecco](https://github.com/xtuhcy/gecco)：易用的轻量化网络爬虫库。
* [SeimiCrawler](https://github.com/zhegexiaohuozi/SeimiCrawler)：一个简单、敏捷、分布式的支持Spring Boot的Java爬虫框架。
* [Apache ManifoldCF](https://github.com/apache/manifoldcf)：Apache ManifoldCF是一个多仓库爬虫框架，具有多个连接器。
* [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler)：免费的数据库模式发现和理解工具。
* [FS-Crawler](https://github.com/dadoonet/fscrawler)：Elasticsearch文件系统爬虫。
* [Zhihu-Crawler](https://github.com/wycm/zhihu-crawler)：zhihu-crawler是一个基于Java的高性能、支持免费HTTP代理池、横向扩展、分布式爬虫项目。
* [XXL-Crawler](https://github.com/xuxueli/xxl-crawler)：Java分布式爬虫框架。
* [Jvppeteer](https://github.com/fanyong920/jvppeteer)：适用于Java的无头Chrome。
* [NetDiscovery](https://github.com/fengzhizi715/NetDiscovery)：NetDiscovery是一款基于Vert.x、RxJava 2等框架实现的通用爬虫框架/中间件。
* [Spiderman](https://gitee.com/l-weiwei/spiderman)：Java开源Web数据抽取工具。
* [XueQiuSuperSpider](https://github.com/decaywood/XueQiuSuperSpider)：雪球超级爬虫是基于雪球网、东方财富和同花顺实现的股票数据爬虫程序。
* [Anthelion](https://github.com/YahooArchive/anthelion)：Anthelion是Apache Nutch的一个插件，用于抓取HTML页面中的语义注释，由Yahoo开源。
* [Crawljax](https://github.com/crawljax/crawljax)：Crawljax是一个自动爬取和测试现代Web应用程序的工具。
* [ACHE](https://github.com/VIDA-NYU/ache)：ACHE是一个用于特定域搜索的网络爬虫。
* [Spiderman2](https://gitee.com/l-weiwei/Spiderman2)：Spiderman的升级版，在性能、架构、易用性上有提升，支持分布式。
* [YayCrawler](https://gitee.com/shentong_012/YayCrawler)：分布式爬虫系统，简单使用，高级配置。
* [Wind-Bell](https://gitee.com/zhiyubujian/wind-bell)：轻量级的高效爬虫工具，配置简单，方便二次开发。
* [Crawler-Commons](https://github.com/crawler-commons/crawler-commons)：一组可重用的Java组件，实现任何网络爬虫通用的功能。
* [Zongtui WebCrawler](https://gitee.com/zongtui/zongtui-webcrawler)：基于Hadoop思维的分布式网络爬虫。
* [VsCrawler](https://gitee.com/virjar/vscrawler)：适合抓取封堵的爬虫框架。
* [Elves](https://github.com/hellokaton/elves)：轻量级爬虫框架的设计与实现。
* [MongooCrawler](https://gitee.com/coliza/MongooCrawler)：一款低入侵分布式爬虫框架，仅仅依赖少量第三方包，具有多进程多线程，集成反爬、验证码破解方案等特性。
* [CrawlerDemon](https://gitee.com/spirit_demon/CrawlerDemon)：基于Akka的高性能分布式爬虫框架。
* [Nokogiri](https://github.com/sparklemotion/nokogiri)：Nokogiri是一个HTML、XML、SAX和Reader解析器，支持XPath和CSS选择器。
* [Parboiled](https://github.com/sirthias/parboiled)：Java和Scala中的优雅解析-轻量级、易于使用、功能强大。
* [Pegdown](https://github.com/sirthias/pegdown)：基于parboiled PEG解析器的纯Java Markdown处理器，支持多种扩展。

<h2 id="data">数据处理</h2>

* [JaVers](https://github.com/javers/javers)： Java的对象审计和差异框架。
* [Spring Batch](https://github.com/spring-projects/spring-batch)：Spring Batch是一个使用Java和Spring编写批处理应用程序的框架。
* [Spring Cloud Data Flow](https://github.com/spring-cloud/spring-cloud-dataflow)：Spring Cloud Data Flow是一个基于微服务的工具包，用于在Cloud Foundry和Kubernetes中构建流式和批量数据处理管道。
* [Easy Batch](https://github.com/j-easy/easy-batch)：Easy Batch是一个旨在简化Java批处理的框架。它专为简单的单任务ETL作业而设计。
* [Liquibase](https://github.com/liquibase/liquibase)：用于跟踪、版本化和部署数据库模式更改。
* [Dynamic-DataSource](https://github.com/baomidou/dynamic-datasource)：一个基于Spring Boot的快速集成多数据源的Starter。
* [DataSource-Proxy](https://github.com/jdbc-observations/datasource-proxy)：通过代理为JDBC交互和查询执行提供监听器框架。
* [Apache Tika](https://github.com/apache/tika)：Apache Tika工具包可从一千多种不同的文件类型(例如PPT、XLS和PDF)中检测并提取元数据和文本。

<h2 id="annotation-processor">注解处理器</h2>

* [Immutables](https://github.com/immutables/immutables)：用于创建不可变对象和构建器的注解处理器。
* [Derive4j](https://github.com/derive4j/derive4j)：Java 8注解处理器，用于派生代数数据类型构造函数、模式匹配等。
* [AndroidAnnotations](https://github.com/androidannotations/androidannotations)：快速的Android开发，维护方便。
* [DeepLinkDispatch](https://github.com/airbnb/DeepLinkDispatch)：一个简单、基于注解的库，用于在Android上更好地处理深度链接，，由Airbnb开源。
* [jackson-annotations](https://github.com/FasterXML/jackson-annotations)：Jackson数据处理器的核心注解。
* [compile-testing](https://github.com/google/compile-testing)：javac和注解处理器的测试工具，由Google开源。
* [PaperParcel](https://github.com/grandstaish/paperparcel)：自动生成Java和Kotlin的Parcelable实现。
* [RecordBuilder](https://github.com/Randgalt/record-builder)：Java记录的记录构建器。
* [RAVE](https://github.com/uber-archive/rave)：使用Java注解处理的数据模型验证框架。
* [PojoBuilder](https://github.com/mkarneim/pojobuilder)：POJO构建器的Java代码生成器。
* [Moxy](https://github.com/moxy-community/Moxy)：Moxy是适用于Android的MVP库，具有增量注解处理器和ktx功能。
* [Hugo](https://github.com/JakeWharton/hugo)：调试版本的注解触发方法调用日志记录。
* [Jackdaw](https://github.com/vbauer/jackdaw)：可以简化开发的Java注解处理器。
* [ParcelablePlease](https://github.com/sockeqwe/ParcelablePlease)：用于生成Parcelable代码的注解处理器。
* [BeanKnife](https://github.com/vipcxj/beanknife)：用于自动生成数据传输对象(DTO)的注解处理器库。
* [Rest.Vertx](https://github.com/zandero/rest.vertx)：类似JAX-RS的注解处理器，适用于Vert.x Vertical。
* [FreeBuilder](https://github.com/inferred/FreeBuilder)：自动生成Java的Builder模式。
* [Airline](https://github.com/airlift/airline)：Airline是一个基于Java注解的框架，用于解析类似命令行结构的Git。
* [Config-Builder](https://github.com/TNG/config-builder)：使用注解和反射来构建自定义类的配置实例。

<h2 id="event-bus">事件总线</h2>

* [EventBus](https://github.com/greenrobot/EventBus)：适用于Android和Java的事件总线，简化了Activity、Fragments、Threads、Services等之间的通信。代码更少，质量更好。
* [MBassador](https://github.com/bennidi/mbassador)：MBassador是一个利用发布-订阅语义的高性能事件总线。
* [Otto](https://github.com/square/otto)：增强的基于Guava的事件总线，重点是Android支持。
* [Spring Cloud Bus](https://github.com/spring-cloud/spring-cloud-bus)：Spring Cloud事件总线。
* [LiveEventBus](https://github.com/JeremyLiao/LiveEventBus)：LiveEventBus是一款Android消息总线，基于LiveData，具有生命周期感知能力，支持Sticky、AndroidX、款进程。
* [ZBUS](https://gitee.com/openforce/zbus)：轻量级服务总线，面向高性能、低时延、高可用特性调优，支持RPC，消息队列服务。
* [RxBus](https://github.com/AndroidKnife/RxBus)：RxJava的事件总线。
* [HermesEventBus](https://github.com/Xiaofei-it/HermesEventBus)：用于在进程之间使用EventBus的库，在IPC或插件开发中很有用。
* [AndroidEventBus](https://github.com/hehonghui/AndroidEventBus)：适用于Android的轻量级事件总线库，简化了Activity、Fragments、Threads、Services等之间的通信。
* [Nakadi](https://github.com/zalando/nakadi)：分布式事件总线，在类似Kafka的队列之上实现RESTful API抽象，由Zalando开源。
* [DeFiBus](https://gitee.com/WeBank/DeFiBus)：基于开源消息中间件打造的安全可控的分布式金融级消息总线。
* [Low-Level-Design](https://github.com/InterviewReady/Low-Level-Design)：常见数据结构的低级设计，包括事件总线。

<h2 id="apidoc">接口文档</h2>

* [Swagger Core](https://github.com/swagger-api/swagger-core)：Swagger Core是OpenAPI规范的Java实现。
* [Knife4j](https://gitee.com/xiaoym/knife4j)：Knife4j是一个集Swagger 2和OpenAPI 3为一体的增强解决方案。
* [Springfox](https://github.com/springfox/springfox)：使用Spring构建的API的自动化JSON API文档。
* [Swagger Parser](https://github.com/swagger-api/swagger-parser)：Swagger Parser是Swagger工具之一，可以帮助我们解析OpenAPI文档并提取其各个组件。
* [SpringDoc-OpenAPI](https://github.com/springdoc/springdoc-openapi)：Springdoc-openapi是一个用于Spring Boot项目的OpenAPI 3实现。
* [Swagger2Markup](https://github.com/Swagger2Markup/swagger2markup)：Swagger到AsciiDoc或Markdown转换器，通过将手写文档与自动生成的API文档相结合，简化最新RESTful API文档的生成。
* [Spring Boot Starter Swagger](https://github.com/SpringForAll/spring-boot-starter-swagger)：个人开发的Spring Boot集成Swagger的Starter。
* [Swagger2Word](https://github.com/JMCuixy/swagger2word)：一个Swagger API文档转Word文档的工具项目。
* [CATS](https://github.com/Endava/cats)：CATS是一个REST API模糊器和OpenAPI端点的负面测试工具。
* [Spring REST Docs](https://github.com/spring-projects/spring-restdocs)：该项目的主要目标是通过将使用Asciidoctor手写的内容与使用Spring MVC测试框架生成的自动生成的示例相结合，轻松记录RESTful服务。
* [OpenAPI-diff](https://github.com/OpenAPITools/openapi-diff)：用于比较两个OpenAPI规范的实用程序。
* [SwaggerSocket](https://github.com/swagger-api/swagger-socket)：基于WebSocket的REST。
* [Swagger-Play](https://github.com/swagger-api/swagger-play)：这是一个在Play框架控制器中支持Swagger注解的模块。
* [Swagger Validator Badge](https://github.com/swagger-api/validator-badge)：该项目在网站上显示“valid swagger”徽章，支持Swagger/OpenAPI 2.0和OpenAPI 3.x规范。
* [OpenAPI Style Validator](https://github.com/OpenAPITools/openapi-style-validator)：可定制的样式验证器，可确保你的OpenAPI规范遵循你组织的标准。
* [Smart-Doc](https://gitee.com/TongchengOpenSource/smart-doc)：Smart-Doc是一款同时支持Java REST API和Apache Dubbo RPC接口文档生成的工具，由同程开源。

<h2 id="cluster-management">集群管理</h2>

* [Apache Aurora](https://github.com/apache/aurora)：Apache Aurora是一个Mesos框架，用于长时间运行服务和定时任务，由Twitter开源。
* [Singularity](https://github.com/HubSpot/Singularity)：Singularity是一种API和Web应用程序，用于运行和调度Apache Mesos任务，包括长时间运行的进程、计划作业和一次性任务。
* [CacheCloud](https://github.com/sohutv/cachecloud)：搜狐视频Redis私有云平台：支持Redis多种架构高效管理、有效降低大规模Redis运维成本，提升资源管控能力和利用率。
* [MSEC](https://github.com/Tencent/MSEC)：集群海量服务引擎，由腾讯开源。
* [Haven](https://github.com/codeabovelab/haven-platform)：Haven是一个Docker集群管理系统，用户可以通过用户友好且功能强大的用户界面和命令行工具控制整个平台。
* [Declarative Cluster Management](https://github.com/vmware/declarative-cluster-management)：使用约束编程的声明式集群管理，其中约束使用SQL进行描述。
* [CorfuDB](https://github.com/CorfuDB/CorfuDB)：Corfu是一个围绕共享日志抽象设计的一致性平台。
* [Apache Helix](https://github.com/apache/helix)：Helix是一个通用集群管理框架，用于自动管理节点集群上托管的分区、复制和分布式资源，由LinkedIn开源。
* [Apache Airavata](https://airavata.apache.org/)：Apache Airavata是一个软件框架，用于在分布式计算资源(包括本地集群、超级计算机、国家电网、学术和商业云)上执行和管理计算作业和工作流程。
* [Fenzo](https://github.com/Netflix/Fenzo)：Fenzo是一个适用于Apache Mesos框架的调度程序Java库，支持调度优化插件并促进集群自动扩展，由Netflix开源。
* [Apache REEF](https://github.com/apache/reef)：Apache REEF是一个用于为集群资源管理器(例如Apache Hadoop YARN或Apache Mesos)开发可移植应用程序的库。例如，Microsoft Azure流分析是基于REEF和Hadoop构建的。

<h2 id="code-analysis">代码分析</h2>

* [Checkstyle](https://github.com/checkstyle/checkstyle)：Checkstyle是一种开发工具，可帮助程序员编写符合编码标准的Java代码。
* [Infer](https://github.com/facebook/infer)：适用于Java、C、C++和Objective-C的静态分析器，由Facebook开源。
* [P3C](https://github.com/alibaba/p3c)：阿里巴巴Java编码指南PMD实现和IDE插件。
* [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail)：免费开源交互式源浏览器。
* [ErrorProne](https://github.com/google/error-prone)：可以将常见的Java错误捕获为编译时错误，由Google开源。
* [PMD](https://github.com/pmd/pmd)：可扩展的多语言静态代码分析器。
* [SpotBugs](https://github.com/spotbugs/spotbugs)：一种静态分析工具，用于查找Java代码中的错误。
* [SonarJava](https://github.com/SonarSource/sonar-java)：用于Java代码质量和安全性的SonarSource静态分析器。
* [Google Java Format](https://github.com/google/google-java-format)：google-java-format是一个重新格式化Java源代码以符合Google Java风格的程序。
* [Spotless](https://github.com/diffplug/spotless)：Spotless是支持多种语言的代码格式化工具。
* [Spoon](https://github.com/INRIA/spoon)：Spoon是一个用于分析和转换Java源代码的元编程库。
* [FindBugs](https://github.com/findbugsproject/findbugs)：Findbugs是一款开源的Java源码静态分析工具。
* [jQAssistant](https://github.com/jQAssistant/jqassistant)：一个基于Neo4j数据库的依赖分析工具，支持分析Java、XML、JSON等格式的数据，并提供可视化界面和查询语言。
* [Dependency-Track](https://github.com/DependencyTrack/dependency-track)：Dependency-Track是一个智能组件分析平台，允许组织识别并降低软件供应链中的风险。
* [OWASP Find Security Bugs](https://github.com/find-sec-bugs/find-sec-bugs)：用于Java Web应用程序和Android应用程序安全审核的SpotBugs插件。
* [Tai-e](https://github.com/pascal-lab/Tai-e)：一个易于学习/使用的Java静态分析框架。
* [Eclipse Steady](https://github.com/eclipse/steady)：分析你的Java应用程序是否存在已知漏洞的开源依赖项，同时使用静态分析和测试来确定代码上下文和使用情况，以提高准确性。
* [MobsfScan](https://github.com/MobSF/mobsfscan)：mobsfscan是一个静态分析工具，可以在Android和IOS源代码中查找不安全的代码模式。
* [CK](https://github.com/mauricioaniche/ck)：通过静态分析获得Java代码的代码度量。
* [JSpecify](https://github.com/jspecify/jspecify)：完全指定注解的工件，用于支持静态分析检查，从无效分析开始。
* [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst)：识别并优先考虑Java代码库中你应该首先重构的上帝类和高度耦合类。
* [Qulice](https://github.com/yegor256/qulice)：Java项目的质量警察：Checkstyle、PMD和SpotBugs的聚合器。
* [jPeek](https://github.com/cqfn/jpeek)：Java代码内聚度指标的托管和命令行计算器。
* [OpenGrok](https://github.com/oracle/opengrok)：OpenGrok是一个快速且可用的源代码搜索和交叉引用引擎，可以帮助你搜索、交叉引用和导航源树，由Oracle开源。

<h2 id="Maven">Maven插件</h2>

* [Frontend Maven Plugin](https://github.com/eirslett/frontend-maven-plugin)：可在本地下载/安装Node和NPM，运行NPM install、Grunt、Gulp和/或Karma。
* [Android Maven Plugin](https://github.com/simpligility/android-maven-plugin)：用于Android应用程序开发等的Maven插件。
* [Javafx Maven Plugin](https://github.com/javafx-maven-plugin/javafx-maven-plugin)：JavaFX的Maven插件。
* [Swagger Maven Plugin](https://github.com/kongchen/swagger-maven-plugin)：该插件使你的Swagger注解项目能够在Maven构建阶段生成Swagger规范和可定制的模板化静态文档。
* [SonarQube Scanner](https://github.com/SonarSource/sonar-scanner-maven)：用于Maven的SonarQube扫描器。
* [Scala Maven Plugin](https://github.com/davidB/scala-maven-plugin)：用于在Maven中编译/测试/运行/记录Scala代码。
* [Depgraph Maven Plugin](https://github.com/ferstl/depgraph-maven-plugin)：可生成各种格式(DOT、GML、PlantUML、JSON和Text)依赖关系图的Maven插件。
* [JMeter Maven Plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin)：JMeter Maven插件。
* [JAXB Tools](https://github.com/highsource/jaxb-tools)：用于XML模式编译的最先进的JAXB2 Maven插件。
* [Modernizer Maven Plugin](https://github.com/gaul/modernizer-maven-plugin)：检测旧版Java API的使用。
* [JavaFX Maven Plugin](https://github.com/openjfx/javafx-maven-plugin)：用于运行JavaFX 11+应用程序的Maven插件。
* [Versions Maven Plugin](https://github.com/mojohaus/versions)：用于管理项目POM中的工件版本。
* [Asciidoctor Maven Plugin](https://github.com/asciidoctor/asciidoctor-maven-plugin)：通过JRuby使用Asciidoctor来处理项目内的AsciiDoc源文件。
* [Fmt Maven Plugin](https://github.com/spotify/fmt-maven-plugin)：格式化Java代码的固定Maven插件。
* [OS Maven Plugin](https://github.com/trustin/os-maven-plugin)：用于设置从${os.name}和${os.arch}属性检测到的各种有用属性。
* [Native Build Tools](https://github.com/graalvm/native-build-tools)：适用于各种构建工具的本机镜像插件。
* [Azure Maven Plugin](https://github.com/microsoft/azure-maven-plugins)：适用于Azure的Maven插件。
* [Protoc-jar Maven Plugin](https://github.com/os72/protoc-jar-maven-plugin)：使用protoc-jar多平台可执行protoc JAR执行protobuf代码生成。
* [License Maven Plugin](https://github.com/mathieucarbou/license-maven-plugin)：用于管理源文件中的许可证标头。
* [Appbundle Maven Plugin](https://github.com/federkasten/appbundle-maven-plugin)：可为OS X创建包含所有项目依赖项和必要元数据的应用程序包。
* [Duplicate-finder Maven Plugin](https://github.com/basepom/duplicate-finder-maven-plugin)：用于查找重复类或资源的Maven插件。
* [GluonFX Maven Plugin](https://github.com/gluonhq/gluonfx-maven-plugin)：简化为Java/JavaFX Maven项目创建本机镜像的插件。
* [Tomcat Maven Plugin](https://github.com/apache/tomcat-maven-plugin)：Apache Tomcat Maven插件。
* [Exec Maven Plugin](https://github.com/mojohaus/exec-maven-plugin)：可以执行Java程序的Maven插件。
* [GWT Maven Plugin](https://github.com/tbroyer/gwt-maven-plugin)：使Maven构建GWT项目更加容易。
* [JShell Maven Plugin](https://github.com/johnpoth/jshell-maven-plugin)：Java Shell工具(JShell)的Maven插件。
* [Springdoc-openapi Maven Plugin](https://github.com/springdoc/springdoc-openapi-maven-plugin)：该插件的目的是在运行时生成JSON和YAML OpenAPI描述。
* [Cucable-Plugin](https://github.com/trivago/cucable-plugin)：简化并行运行Cucumber场景的Maven插件。
* [Web3j Maven Plugin](https://github.com/web3j/web3j-maven-plugin)：用于根据Solidity合约文件创建Java类。
* [AspectJ Maven Plugin](https://github.com/mojohaus/aspectj-maven-plugin)：该插件使用AspectJ编译器ajc将AspectJ切面编织到类中。
* [App Maven Plugin](https://github.com/GoogleCloudPlatform/app-maven-plugin)：用于构建和部署Google App Engine应用程序的Maven插件。
* [Mosec Maven Plugin](https://github.com/momosecurity/mosec-maven-plugin)：用于检测Maven项目的第三方依赖组件是否存在安全漏洞。
* [Rewrite Maven Plugin](https://github.com/openrewrite/rewrite-maven-plugin)：OpenRewrite的Maven插件。
* [Allure Maven Plugin](https://github.com/allure-framework/allure-maven)：根据测试结果生成Allure报告的Maven插件。
* [Heroku Maven Plugin](https://github.com/heroku/heroku-maven-plugin)：用于将Java应用程序直接部署到Heroku，而无需推送到Git仓库。

<h2 id="gradle">Gradle插件</h2>

* [Gradle Retrolambda Plugin](https://github.com/evant/gradle-retrolambda)：一个Gradle插件，用于在Java 6、7和Android中获取Java Lambda支持。
* [Dexcount Gradle Plugin](https://github.com/KeepSafe/dexcount-gradle-plugin)：一个Gradle插件，用于报告每次构建时APK中方法引用的数量。
* [Hunter](https://github.com/Leaking/Hunter)：一个快速、增量、并发的框架，用于开发Android项目的编译插件来操作字节码。
* [Gradle Docker plugin](https://github.com/bmuschko/gradle-docker-plugin)：用于管理Docker镜像和容器的Gradle插件。
* [Dependency Management Plugin](https://github.com/spring-gradle-plugins/dependency-management-plugin)：一个Gradle插件，提供类似Maven的依赖管理功能。
* [JavaFX Gradle Plugin](https://github.com/FibreFoX/javafx-gradle-plugin)：用于JavaFX的Gradle插件。
* [Google Play Plugin](https://github.com/google/play-services-plugins)：帮助使用Google Play服务SDK的插件。
* [Clean Architecture](https://github.com/bancolombia/scaffold-clean-architecture)：用于按照最佳实践创建基于Clean Architecture的Java和Kotlin应用程序的Gradle插件。
* [Git-Version Gradle Plugin](https://github.com/palantir/gradle-git-version)：使用git describe生成版本字符串的Gradle插件。
* [Gradle Avro Plugin](https://github.com/davidmc24/gradle-avro-plugin)：允许轻松执行Apache Avro的Java代码生成的Gradle插件。
* [Gradle Baseline](https://github.com/palantir/gradle-baseline)：一组Gradle插件，为开发人员配置默认的代码质量工具。
* [Gradle AWS Plugin](https://github.com/classmethod/gradle-aws-plugin)：用于管理Amazon Web Services的Gradle插件。
* [Gradle Modules Plugin](https://github.com/java9-modularity/gradle-modules-plugin)：这个Gradle插件有助于使用Java 9平台模块系统。
* [Android SVG Drawable Plugin](https://github.com/avianey/androidsvgdrawable-plugin)：可在Android项目构建时从SVG文件生成合格的、特定于密度的PNG绘图。

<h2 id="sdk">SDK</h2>

* [Aliyun](https://github.com/aliyun/aliyun-openapi-java-sdk)：阿里云Java SDK。
* [Azure](https://github.com/Azure/azure-sdk-for-java)：Azure Java SDK。
* [Azure IoT](https://github.com/Azure/azure-iot-sdk-java)：用于将设备连接到Microsoft Azure IoT服务的Java SDK。
* [Tencent](https://github.com/TencentCloud/tencentcloud-sdk-java)：腾讯云API 3.0 Java SDK。
* [Kubernetes Operator](https://github.com/operator-framework/java-operator-sdk)：用于构建Kubernetes Operator的Java SDK。
* [Aliyun OSS](https://github.com/aliyun/aliyun-oss-java-sdk)：Aliyun OSS的Java SDK。
* [Aliyun OSS Android](https://github.com/aliyun/aliyun-oss-android-sdk)：阿里云对象存储服务Android SDK。
* [Aliyun log](https://github.com/aliyun/aliyun-log-java-sdk)：可以调用所有日志服务API的Java SDK。
* [aliyun-odps-java-sdk](https://github.com/aliyun/aliyun-odps-java-sdk)：面向Java开发者的ODPS SDK。
* [Volcengine](https://github.com/volcengine/volcengine-java-sdk)：火山引擎Java SDK。
* [WxJava](https://github.com/Wechat-Group/WxJava)：微信开发Java SDK，支持包括微信支付、开放平台、小程序、企业微信、公众号等的后端开发。
* [AWS](https://github.com/aws/aws-sdk-java-v2)：AWS官方的Java SDK。
* [AWS Encryption](https://github.com/aws/aws-encryption-sdk-java)：AWS加密SDK。
* [AWS IoT](https://github.com/aws/aws-iot-device-sdk-java)：用于从设备连接到AWS IoT的Java SDK。
* [AWS X-Ray](https://github.com/aws/aws-xray-sdk-java)：适用于Java的官方AWS X-Ray记录器SDK。
* [AWS C3R](https://github.com/aws/c3r)：C3R加密客户端和SDK。
* [Huawei](https://github.com/huaweicloud/huaweicloud-sdk-java-v3)：华为云Java SDK。
* [Huawei OBS](https://github.com/huaweicloud/huaweicloud-sdk-java-obs)：用于访问对象存储服务的OBS Java SDK。
* [Google App Engine](https://github.com/GoogleCloudPlatform/appengine-java-standard)：Google App Engine标准Java运行时：Prod运行时、本地devappserver、Cloud SDK Java组件、GAE API和GAE API模拟器。
* [DataflowTemplates](https://github.com/GoogleCloudPlatform/DataflowTemplates)：Google提供的Cloud Dataflow模板管道用于解决简单的云内数据任务。
* [Google Pub/Sub](https://github.com/GoogleCloudPlatform/pubsub)：Google Cloud Pub/Sub开源项目。
* [Google Cloud Java](https://github.com/googleapis/google-cloud-java)：适用于Java的Google Cloud客户端库。
* [Google APIs Client](https://github.com/googleapis/google-api-java-client)：适用于Java的Google API客户端库。
* [Google Map](https://github.com/googlemaps/android-maps-utils)：Android地图SDK实用程序库。
* [React-Native](https://github.com/facebookarchive/react-native-fbsdk)：针对Android和iOS的Facebook SDK的React Native包装器。
* [JFinal Weixin](https://gitee.com/jfinal/jfinal-weixin)：JFinal Weixin是基于JFinal的微信公众号极速开发SDK，只需浏览Demo代码即可进行极速开发。
* [Weixin-Java-Tools](https://github.com/chanjarster/weixin-java-tools)：微信公众号、企业号Java SDK。
* [Weixin-Popular](https://github.com/liyiorg/weixin-popular)：微信Java SDK(公众平台、开放平台、商户平台、服务商平台)。
* [Firebase Android](https://github.com/firebase/firebase-android-sdk)：Firebase安卓SDK。
* [Lancet](https://github.com/eleme/lancet)：面向Android App和SDK开发人员的轻量级快速AOP框架。
* [Twitter4J](https://github.com/Twitter4J/Twitter4J)：Twitter4J是Twitter API的开源Java库。
* [Wizcorp Phonegap](https://github.com/Wizcorp/phonegap-facebook-plugin)：Apache Cordova/PhoneGap中Facebook的官方插件。
* [Ice](https://github.com/Teevity/ice)：AWS使用工具，由Netflix开源。

<h2 id="api">API</h2>

* [REST Countries](https://github.com/apilayer/restcountries)：通过RESTful API获取有关国家/地区的信息的工具。
* [RestFB](https://github.com/restfb/restfb)：RestFB是一个纯Java Facebook Graph API客户端，没有外部依赖。

<h2 id="blockchain">区块链</h2>

* [Web3j](https://github.com/web3j/web3j)：用于与以太坊客户端集成的轻量级Java和Android库。
* [Token Core](https://github.com/consenlabs/token-core-android)：Android上的区块链私钥管理库。
* [MD BlockChain](https://gitee.com/tianyalei/md_blockchain)：开源Java区块链平台，可做联盟链、私链使用，不适用于公链。
* [Keycard](https://github.com/status-im/status-keycard)：Keycard是在Javacard 3.0.4+上运行的BIP-32 HD钱包的实现。
* [Arbitrader](https://github.com/agonyforge/arbitrader)：市场中立的加密货币交易机器人。
* [Apache Tuweni](https://github.com/apache/incubator-tuweni)：Apache Tuweni是一组库和其他工具，可帮助使用Java和其他JVM语言开发区块链和其他去中心化软件。
* [FundRequest](https://github.com/FundRequest/platform)：FundRequest平台代码。
* [Blockj](https://gitee.com/blackfox/blockj)：Java实现的一个简易区块链(联盟链)项目，包括加密工具、钱包、P2P传输、区块同步、网络共识等基础实现。
* [JD Chain](https://gitee.com/jdchain/jdchain)：京东区块链是一个企业级的区块链框架系统，具有简洁、易用、可扩展和高性能的特点。
* [J2Chain](https://gitee.com/ld/J2Chain)：Java开发区块链的开源项目。
* [FexCoin](https://gitee.com/koch/fex-wallet-app)：加密货币钱包，数字货币交易所，区块链数字资产管理工具。
* [Fabric SDK Java](https://github.com/hyperledger/fabric-sdk-java)：该项目提供了一个用于与Hyperledger Fabric区块链网络交互的低级API。
* [WeIdentity](https://github.com/WeBankBlockchain/WeIdentity)：基于区块链的符合W3C DID和Verifiable Credential规范的分布式身份解决方案。
* [WeEvent](https://github.com/WeBankBlockchain/WeEvent)：基于区块链的事件驱动架构。
* [WeBASE](https://github.com/WeBankBlockchain/WeBASE)：微众银行区块链应用软件扩展。
* [WeCross](https://github.com/WeBankBlockchain/WeCross)：WeCross跨链路由。
* [TokenCore](https://github.com/GalaxySciTech/tokencore)：区块链钱包后端核心组件，支持多种区块链地址生成和离线签名。
* [NULS-v1](https://github.com/nuls-io/nuls-v1)：NULS是一个全球区块链开源项目，是一个高度可定制的模块化区块链基础设施。
* [NULS-v2](https://github.com/nuls-io/nuls-v2)：NULS协议的官方Java实现。
* [RepChain](https://gitee.com/BTAJL/repchain)：RepChain是第一款采用响应式编程实现的自主可控的区块链基础组件，由广州软件应用技术研究院、中国科学院软件所、贵阳信息技术研究院、中科智城信息科技有限公司、中科软科技股份有限公司和北京连琪科技有限公司共同研发。
* [Aion](https://github.com/aionnetwork/aion)：Aion网络-Java实现。
* [Blockchain](https://github.com/Will1229/Blockchain)：区块链的Java简单实现。
* [TRON](https://github.com/tronprotocol/java-tron)：Tron白皮书的Java实现。
* [Hyperledger Quilt](https://github.com/hyperledger-archives/quilt)：Interledger协议的实现。
* [SimBlock](https://github.com/dsg-titech/simblock)：开源区块链网络模拟器。
* [Neow3j](https://github.com/neow3j/neow3j)：Neo区块链的Java/Kotlin/Android开发工具包。
* [COTI Node](https://github.com/coti-io/coti-node)：COTI是第一个基于DAG的链协议，针对企业和稳定币进行了优化。
* [EOSIO](https://github.com/EOSIO/eosio-java)：用于与基于EOSIO的区块链集成的API。
* [Cardano](https://github.com/bloxbean/cardano-client-lib)：Java中的Cardano客户端库。
* [Thunder](https://github.com/blockchain/thunder)：使用智能合约进行链下比特币支付。
* [Web3signer](https://github.com/Consensys/web3signer)：Web3Signer是一种开源签名服务，能够使用存储在外部保管库中或加密在磁盘上的私钥在多个平台(Ethereum1和2、Filecoin)上进行签名。
* [Hedera Services](https://github.com/hashgraph/hedera-services)：Hedera公共账本的加密货币、代币、共识、文件和智能合约服务。
* [SmartJ](https://github.com/signum-network/signum-smartj)：Signum的Java智能合约。

<h2 id="ethereum">以太坊</h2>

* [Ethereumj](https://github.com/ethereum/ethereumj)：以太坊黄皮书的Java实现。
* [Besu](https://github.com/hyperledger/besu)：基于Java的企业级以太坊客户端。
* [Teku](https://github.com/Consensys/teku)：以太坊2.0信标链的Java实现。
* [AlphaWallet](https://github.com/AlphaWallet/alpha-wallet-android)：先进的以太坊手机钱包。
* [Eventeum](https://github.com/eventeum/eventeum)：弹性以太坊事件监听器，可连接你的智能合约事件和后端微服务。
* [Presto Ethereum Connector](https://github.com/xiaoyao1991/presto-ethereum)：Presto以太坊连接器-以太坊上的SQL。
* [Trust](https://github.com/trustwallet/trust-wallet-android-source)：Android版以太坊钱包。
* [ETHWallet](https://github.com/DwyaneQ/ETHWallet)：像imToken这样的以太坊钱包。
* [Securify](https://github.com/eth-sri/securify)：以太坊智能合约安全扫描器。
* [BitcoinWallet](https://github.com/terryjiao/BitcoinWallet)：比特币和以太坊钱包。
* [Wuhan Chain](https://github.com/BSN-DDC/wuhanchain)：BSN官方DDC智能合约和SDK基于开放许可的区块链-武汉链(以太坊)。

<h2 id="bitcoin">比特币</h2>

* [Bitcoinj](https://github.com/bitcoinj/bitcoinj)：使用比特币的库。
* [Bisq](https://github.com/bisq-network/bisq)：去中心化的比特币交易网络。
* [XChange](https://github.com/knowm/XChange)：XChange是一个Java库，提供简化的API，用于与60多个比特币和山寨币交易所进行交互，为交易和访问市场数据提供一致的接口。
* [Bitcoin Wallet](https://github.com/bitcoin-wallet/bitcoin-wallet)：适用于Android设备的比特币钱包应用程序。
* [Exchange-core](https://github.com/exchange-core/exchange-core)：使用Java编写的超快速匹配引擎，基于LMAX Disruptor、Eclipse Collections、Agrona、OpenHFT、LZ4 Java和Adaptive Radix Trees。
* [Crypto-Exchange](https://github.com/jammy928/CoinExchange_CryptoExchange_Java)：基于Spring Cloud微服务开发，可用于数字货币交易所的搭建和二次开发。
* [OBAndroid](https://github.com/omnilaboratory/OBAndroid)：OBAndroid是一款适用于Android设备的自我托管OmniBOLT闪电钱包。
* [Sparrow](https://github.com/sparrowwallet/sparrow)：Sparrow是一款现代桌面比特币钱包应用程序，支持大多数硬件钱包，并基于PSBT等通用标准构建，强调透明度和可用性。
* [Drongo](https://github.com/sparrowwallet/drongo)：一个Java比特币库。
* [BX-bot](https://github.com/gazbert/bxbot)：用Java编写的简单比特币交易机器人。
* [Mycelium Bitcoin Wallet](https://github.com/mycelium-com/wallet-android)：Android版Mycelium比特币钱包。
* [DiabloMiner](https://github.com/Diablo-D3/DiabloMiner)：比特币OpenCL矿工。
* [Bither](https://github.com/bither/bither-android)：简单安全的比特币钱包。
* [Warp Exchange](https://github.com/michaelliao/warpexchange)：简单、超快的7 x 24交易。
* [Boilr](https://github.com/drpout/boilr)：比特币、加密货币、加密资产、期货和期权的价格警报。
* [CoinExchange](https://gitee.com/cexchange/CoinExchange)：开源数字货币合约交易所，基于Java开发的比特币交易所、BTC交易所、ETH交易所、数字货币交易所、交易平台、撮合交易引擎。

<h2 id="iot">物联网</h2>

* [ThingsBoard](https://github.com/thingsboard/thingsboard)：ThingsBoard是一个开源物联网平台，用于数据收集、处理、可视化和设备管理。
* [JetLinks](https://gitee.com/jetlinks/jetlinks-community)：一个开箱即用，可二次开发的企业级物联网基础平台。
* [Eclipse Milo](https://github.com/eclipse/milo)：OPC UA(IEC 62541)的开源实现。
* [Apache PLC4X](https://github.com/apache/plc4x)：PLC4X工业物联网适配器。
* [Eclipse SmartHome](https://github.com/eclipse-archived/smarthome)：旨在创建一个构建智能家居解决方案的框架，其重点是异构环境，即各种协议和标准集成。
* [OpenRemote](https://github.com/openremote/openremote)：100%开源物联网平台，可以构建完整的IoT设备管理解决方案，包括设备管理和自动配置、资产类型自定义、通过“When-Then”、Flow、JavaScript和Groovy规则实现自动化、数据分析、通过多个协议代理和管理器API(例如MQTT代理、HTTP/REST、WS)进行连接、多租户(领域)、用户和角色管理、Edge网关、前端UI Web组件和控制台以及Insights仪表板生成器。
* [OpenHAB](https://github.com/openhab/openhab-core)：开放式家庭自动化总线(OpenHAB)是一个开源、与技术无关的家庭自动化平台，作为智能家居的中心运行。
* [FastBee](https://gitee.com/kerwincui/wumei-smart)：FastBee开源物联网平台，简单易用，更适合中小企业和个人学习使用。适用于智能家居、智慧办公、智慧社区、农业监测、水利监测、工业控制等。
* [Eclipse Californium](https://github.com/eclipse-californium/californium)：Eclipse Californium是RFC7252(物联网云服务的约束应用协议)的Java实现。
* [Zeus](https://github.com/zmops/zeus-iot)：Zeus IoT是一个分布式物联网采集、分析、存储平台，是全球第一个基于zabbix二次开发的物联网开源平台。
* [ThingLinks](https://gitee.com/mqttsnet/thinglinks)：高性能、高吞吐量、高扩展性的物联网平台。
* [Eclipse Leshan](https://github.com/eclipse-leshan/leshan)：Eclipse Leshan是OMA轻量级M2M服务器和客户端Java实现。
* [Groza](https://github.com/IoT-Technology/Groza)：开源物联网平台-物联网解决方案的设备管理，数据收集，处理。
* [ThingLinks](https://github.com/mqttsnet/thinglinks)：采用Spring Cloud微服务架构，一款高性、高吞吐量、高扩展性的物联网平台。
* [Eclipse Ditto](https://github.com/eclipse-ditto/ditto)：Eclipse IoT的数字孪生框架。
* [Eclipse Kura](https://github.com/eclipse/kura)：基于OSGi的M2M服务网关应用程序框架。
* [IoTLink](https://gitee.com/sdyunze/iotlink)：基于Spring Boot、Vue、Mybatis、RabbitMQ、MySQL、Redis等开发的轻量级的物联网综合业务支撑平台。
* [Apache StreamPipes](https://github.com/apache/streampipes)：一个自助(工业)物联网工具箱，使非技术用户能够连接、分析和探索物联网数据流。
* [Eclipse hawkBit](https://github.com/eclipse/hawkbit)：Eclipse hawkBit是一个独立于域的后端解决方案，用于向受限边缘设备以及连接到基于 IP 的网络基础设施的更强大的控制器和网关推出软件更新。
* [DeviceHive](https://github.com/devicehive/devicehive-java-server)：DeviceHive将任何连接的设备变成物联网的一部分。它提供通信层、控制软件和多平台库，以引导智能能源、家庭自动化、遥感、遥测、远程控制和监控软件等的开发。
* [Freedomotic](https://github.com/freedomotic/freedomotic)：Freedomotic是一个开源、灵活、安全的物联网(IoT)应用程序框架，可用于构建和管理现代智能空间。
* [DC3](https://github.com/pnoker/iot-dc3)：DC3是基于Spring Cloud的开源可分布式物联网平台，用于快速开发、部署物联设备接入项目，是一整套物联系统解决方案。
* [Warp10](https://github.com/senx/warp10-platform)：Warp10是一个专为物联网设计的模块化开源平台，可收集、存储并允许你分析传感器数据。
* [Tigase](https://github.com/tigase/tigase-server)：Tigase XMPP Server是用Java编写的高度优化、高度模块化且非常灵活的XMPP/Jabber服务器。
* [Eclipse Vorto](https://github.com/eclipse/vorto)：Eclipse Vorto提供了一种用于描述IoT数字孪生模型和接口的语言。
* [SquirrelJME](https://github.com/SquirrelJME/SquirrelJME)：SquirrelJME是用于嵌入式和物联网设备的Java ME 8虚拟机，它的最终目标是与Java ME标准99.9%兼容。
* [IoT DC3](https://gitee.com/pnoker/iot-dc3)：IoT DC3是一个基于Spring Cloud的开源、分布式的物联网(IoT)平台，用于快速开发物联网项目和管理物联设备，是一整套物联系统解决方案。
* [Eclipse Tahu](https://github.com/eclipse/tahu)：Eclipse Tahu解决了遗留SCADA/DCS/ICS协议和基础设施的问题，并提供了急需的定义，说明如何最好地将MQTT应用到这些现有的工业运营环境中。
* [NetXMS](https://github.com/netxms/netxms)：NetXMS是一款开源网络和基础设施监控和管理解决方案，为IT基础设施的所有层提供性能和可用性监控以及灵活的事件处理、警报、报告和图表。
* [OpenIita](https://gitee.com/open-iita/iotkit-parent)：铱塔智联开源平台是一个开源的物联网基础开发平台，提供了物联网及相关业务开发的常见基础功能，能帮助你快速搭建自己的物联网相关业务平台。
* [ha-bridge](https://github.com/bwssytems/ha-bridge)：将Philips Hue API模拟到其他家庭自动化网关，例如Amazon Echo/Dot或支持Philips Hue本地网络发现的其他系统。
* [openHAB Add-ons](https://github.com/openhab/openhab-addons)：该库包含在openHAB核心API之上实现的官方附加组件集。
* [Amazon Echo Bridge](https://github.com/armzilla/amazon-echo-ha-bridge)：Amazon Echo Bridge允许你快速模拟Phillips Hue桥，从而能够将Amazon Echo无缝集成到各种家庭自动化系统中。
* [Eclipse Kapua](https://github.com/eclipse/kapua)：Eclipse Kapua是一个模块化平台，提供管理物联网网关和智能边缘设备所需的服务。Kapua提供了一个核心集成框架和一组初始的核心物联网服务，包括设备注册表、设备管理服务、消息传递服务、数据管理和应用程序支持。
* [Eclipse Hono](https://github.com/eclipse-hono/hono)：Eclipse Hono提供统一(远程)服务接口，用于将大量IoT设备连接到(云)后端。
* [Azure IoT SDK](https://github.com/Azure/azure-iot-sdk-java)：用于将设备连接到Microsoft Azure IoT服务的Java SDK。
* [Indriya](https://github.com/unitsofmeasurement/indriya)：JSR 385参考实现。

<h2 id="mqtt">MQTT</h2>

* [Moquette](https://github.com/moquette-io/moquette)：Java轻量级MQTT Broker。
* [MQTT-Client](https://github.com/fusesource/mqtt-client)：MQTT-Client为MQTT提供API，如果发生任何网络故障，它会自动重新连接到MQTT服务器并恢复客户端会话。
* [AndrOBD](https://github.com/fr3ts0n/AndrOBD)：AndrOBD允许Android设备通过任何ELM327兼容的OBD适配器连接到汽车的车载诊断系统，显示各种信息并执行操作。
* [HiveMQ](https://github.com/hivemq/hivemq-community-edition)：HiveMQ是一个基于Java的开源MQTT代理，完全支持MQTT 3.x和MQTT 5。
* [ActiveMQ Artemis](https://github.com/apache/activemq-artemis)：ActiveMQ Artemis是Apache ActiveMQ的下一代消息代理。
* [Mica](https://gitee.com/596392912/mica-mqtt)：低延迟、高性能的MQTT物联网组件。
* [SMQTT](https://github.com/quickmsg/smqtt)：开源MQTT服务器(基于Reactor-Netty实现高性能的、可扩展、支持千万级设备接入集群)，支持MQTT 3.1.1、MQTT 5等协议。
* [MqttWk](https://github.com/Wizzercn/MqttWk)：Java + Netty实现的高并发高可用MQTT服务Broker。
* [Jmqtt](https://github.com/Cicizz/jmqtt)：一个MQTT Broker，由Java和Netty实现，支持持久化和集群。
* [TBMQ](https://github.com/thingsboard/tbmq)：开源MQTT Broker-促进MQTT客户端连接、消息发布和订阅者之间的分发。
* [Joynr](https://github.com/bmwcarit/joynr)：与传输协议无关(MQTT、HTTP、WebSockets等)、基于Franca IDL的通信框架，支持多种通信范例(RPC、Pub-Sub、广播等)。
* [MoP](https://github.com/streamnative/mop)：MQTT-on-Pulsar(又名MoP)是为了在Apache Pulsar上原生支持MQTT协议而开发的。
* [EnMasse](https://github.com/EnMasseProject/enmasse)：EnMasse在Kubernetes和OpenShift上提供了一个自助消息传递平台，具有统一的界面来管理不同的消息传递基础设施。
* [RocketMQ MQTT](https://github.com/apache/rocketmq-mqtt)：全新的MQTT协议架构模型，基于该模型RocketMQ可以更好地支持来自物联网设备、手机APP等终端的消息。

<h2 id="finance">金融</h2>

* [Apache Fineract](https://github.com/apache/fineract)：Fineract是一个具有开放API的成熟平台，可为金融机构提供可靠、强大且价格实惠的核心银行解决方案，为全球30亿银行服务不足和无银行账户的人口提供服务。
* [Strata](https://github.com/OpenGamma/Strata)：OpenGamma的开源分析和市场风险库。
* [Portfolio](https://github.com/portfolio-performance/portfolio)：用于跟踪和评估股票、加密货币和其他资产的投资组合的表现。
* [JavaMoney](https://github.com/JavaMoney/javamoney-lib)：提供基于JSR 354(兼容实现)构建的扩展和库。
* [QuickFIX/J](https://github.com/quickfix-j/quickfixj)：QuickFIX/J是适用于FIX(金融信息交换)协议的全功能消息传递引擎。
* [Northstar](https://gitee.com/dromara/northstar)：国内最优秀的Java开源一站式量化交易平台，具备历史回放、策略研发、模拟交易、实盘交易等功能，由dromara社区开源。
* [CDM](https://github.com/finos/common-domain-model)：CDM是金融产品、这些产品的交易以及这些交易的生命周期事件的模型。它是一个开源标准，可以协调数据、系统和流程，并且可以多种语言的代码形式提供，以便于跨技术实现，由金融科技开源基金会FINOS托管。
* [Ta4j](https://github.com/ta4j/ta4j)：用于技术分析的Java库。
* [Stripe Java](https://github.com/stripe/stripe-java)：官方Stripe Java客户端库。
* [Philadelphia](https://github.com/paritytrading/philadelphia)：Philadelphia是一个用于JVM的快速金融信息交换(FIX)协议库。
* [Parity](https://github.com/paritytrading/parity)：Parity是一个用于交易场所的开源软件平台，它可用于运行金融市场、开发算法交易代理或研究市场微观结构。
* [Cassandre Trading Bot](https://github.com/cassandre-tech/cassandre-trading-bot)：在几分钟内创建Java加密货币交易机器人，Starter负责处理交易所连接、账户、订单、交易和头寸，以便可以专注于构建策略。
* [Open Banking](https://github.com/wso2/financial-open-banking)：WSO2开放银行加速器是一系列技术的集合，可提高开放银行合规性的速度并降低其复杂性。你无需从头开始构建解决方案，而是可以使用WSO2开放银行加速器来满足所有立法要求，并获得合规性之外的其他好处。

<h2 id="sms">短信</h2>

* [Twilio Java](https://github.com/twilio/twilio-java)：用于与Twilio REST API通信并生成TwiML的Java库。
* [SMS4J](https://gitee.com/dromara/sms4j)：SMS4J为短信聚合框架，可以轻松集成多家短信服务，解决接入多个短信SDK的繁琐流程。
* [Austin](https://gitee.com/zhongfucheng/austin)：统一的接口发送各种类型消息，对消息生命周期全链路追踪。
* [Guerlab](https://gitee.com/guerlab_net/guerlab-sms)：基于Spring Boot的短信服务支持，通过引用不同的Starter启用不同的短信通道支持，支持多通道下的负载均衡，支持同步/异步方式发送。

<h2 id="spring">Spring生态</h2>

* [Spring Boot Admin](https://github.com/codecentric/spring-boot-admin)：用于管理Spring Boot应用程序的管理UI。
* [MyBatis Spring Boot](https://github.com/mybatis/spring-boot-starter)：MyBatis与Spring Boot集成。
* [Spring Initializr](https://github.com/spring-io/initializr)：Spring项目的快速生成器。
* [gRPC Spring Boot](https://github.com/yidongnan/grpc-spring-boot-starter)：gRPC框架的Spring Boot Starter模块。
* [gRPC Spring Boot](https://github.com/LogNet/grpc-spring-boot-starter)：gRPC的Spring Boot Starter模块。
* [Retrofit Spring Boot](https://github.com/LianjiaTech/retrofit-spring-boot-starter)：适用于Retrofit的Spring Boot Starter，支持快速集成和功能增强。
* [Spring Boot DataSource Decorator](https://github.com/gavlyukovskiy/spring-boot-data-source-decorator)：Spring Boot与p6spy、datasource-proxy、flexy-pool和spring-cloud-sleuth集成。
* [ChatGPT Spring Boot](https://github.com/linux-china/chatgpt-spring-boot-starter)：Spring Boot ChatGPT Starter。
* [Spring Boot Dubbo](https://github.com/apache/dubbo-spring-boot-project)：Apache Dubbo Spring Boot项目可以轻松使用Dubbo作为RPC框架创建Spring Boot应用程序。
* [Spring Boot Jasypt](https://github.com/ulisesbocchio/jasypt-spring-boot)：Jasypt Spring Boot为Spring Boot应用程序中的属性源提供加密支持。
* [Spring Data JPA EntityGraph](https://github.com/Cosium/spring-data-jpa-entity-graph)：Spring Data JPA扩展允许在Repository上完全动态使用EntityGraph。
* [Error Handling Spring Boot](https://github.com/wimdeblauwe/error-handling-spring-boot-starter)：可配置的REST API错误处理。
* [Okta Spring Boot](https://github.com/okta/okta-spring-boot)：Okta Spring Boot Starter。
* [Spring Content](https://github.com/paulcwarren/spring-content)：Spring的云原生存储和企业内容服务(ECMS)。
* [Spring Boot Logging](https://github.com/piomin/spring-boot-logging)：用于记录Spring Boot应用程序的HTTP请求/响应以及与Elastic Stack集成的库。
* [Spring Boot Starter Calma](https://github.com/marvinSpring/spring-boot-starter-calma)：异常通知框架。
* [Spring Boot HTMX](https://github.com/wimdeblauwe/htmx-spring-boot)：用于使用htmx的Spring Boot和Thymeleaf助手。
* [WireMock Spring Boot](https://github.com/maciejwalkowiak/wiremock-spring-boot)：WireMock Spring Boot极大地简化了基于Spring Boot和Junit 5的集成测试中的HTTP客户端测试。
* [DJL Spring Boot](https://github.com/deepjavalibrary/djl-spring-boot-starter)：DJL Spring Boot Starter。
* [Spring ViewComponent](https://github.com/tschuehly/spring-view-component)：使用Spring创建服务器端ViewComponent的库。
* [Narayana Spring Boot](https://github.com/snowdrop/narayana-spring-boot)：Narayana Spring Boot自动配置和Starter。
* [Spring DBUnit](https://github.com/springtestdbunit/spring-test-dbunit)：Spring测试框架和DBUnit之间的集成。
* [Alibaba Spring Boot](https://github.com/alibaba/aliyun-spring-boot)：阿里云服务Spring Boot Starter。
* [Springwolf](https://github.com/springwolf/springwolf-core)：使用Spring Boot构建的异步API的自动化文档。
* [Apache Camel Spring Boot](https://github.com/apache/camel-spring-boot)：Apache Camel Spring Boot支持。
* [Wicket Spring Boot](https://github.com/MarcGiffing/wicket-spring-boot)：Apache Wicket的Spring Boot Starter。
* [Bitcoin Spring Boot](https://github.com/theborakompanioni/bitcoin-spring-boot-starter)：使用Spring Boot编写企业比特币应用程序的工具。
* [Spring Boot Bucket4j](https://github.com/MarcGiffing/bucket4j-spring-boot-starter)：Bucket4j的Spring Boot Starter。
* [Camunda Spring Boot](https://github.com/camunda/camunda-bpm-spring-boot-starter)：Camunda的Spring Boot Starter。
* [Charon Spring Boot](https://github.com/mkopylec/charon-spring-boot-starter)：以Spring Boot Starter形式的反向代理实现。
* [Desensitization Spring Boot](https://github.com/allurx/desensitization-spring-boot)：脱敏库与Spring Boot集成。
* [Errors Spring Boot](https://github.com/alimate/errors-spring-boot-starter)：Spring Boot的优雅错误处理。
* [reCAPTCHA Spring Boot](https://github.com/mkopylec/recaptcha-spring-boot-starter)：Google reCAPTCHA的Spring Boot Starter。
* [RocketMQ Spring](https://github.com/apache/rocketmq-spring)：该项目旨在帮助开发者快速将RocketMQ与Spring Boot集成。
* [PageHelper Spring Boot](https://github.com/pagehelper/pagehelper-spring-boot)：Mybatis分页插件与Spring Boot的集成。
* [Pug4j Spring Boot](https://github.com/domix/jade4j-spring-boot-starter)：Spring Boot jade4j Starter。
* [RESTEasy Spring Boot](https://github.com/resteasy/resteasy-spring-boot)：RESTEasy Spring Boot Starter。
* [Apache CXF Spring Boot](https://github.com/codecentric/cxf-spring-boot-starter)：由Spring Boot和Apache CXF提供支持的企业和生产就绪SOAP Web Service。
* [Spring Boot Batch Web](https://github.com/codecentric/spring-boot-starter-batch-web)：由Spring Boot提供支持的企业就绪、生产就绪的批处理应用程序。
* [Problem Spring Web](https://github.com/zalando/problem-spring-web)：用于处理Spring Web MVC中问题的库，由Zalando开源。

<h2 id="raft">Raft算法</h2>

* [SOFAJRaft](https://github.com/sofastack/sofa-jraft)：Raft共识算法的生产级Java实现。
* [Raft Java](https://github.com/wenweihu86/raft-java)：Raft算法的简单Java实现。
* [Apache Ratis](https://github.com/apache/ratis)：Raft共识协议的开源Java实现。
* [Dledger](https://github.com/openmessaging/dledger)：一个基于Raft的java库，用于构建高可用、高持久、强一致的提交日志。
* [Lu-Raft-KV-Storage](https://github.com/stateIs0/lu-raft-kv)：这是一个Java版本的Raft(CP) KV分布式存储实现。
* [Copycat](https://github.com/atomix/copycat)：Raft一致性算法的新颖实现。
* [jGroups Raft](https://github.com/belaban/jgroups-raft)：Raft共识协议在JGroups中的实现。
* [xRaft](https://github.com/xnnyygn/xraft)：简单的Raft共识算法实现。
* [jRaft](https://github.com/datatechnology/jraft)：简单的Raft共识算法实现。
* [MicroRaft](https://github.com/MicroRaft/MicroRaft)：Raft一致性算法在Java中的功能完整实现。

<h2 id="paxos">Paxos算法</h2>

* [WPaxos](https://github.com/wuba/WPaxos)：Paxos共识算法的生产级Java实现。
* [WLock](https://github.com/wuba/WLock)：基于共识算法组件WPaxos的高可靠、高吞吐量的分布式锁服务。
* [Klein](https://github.com/shihuili1218/klein)：Klein是一个基于Paxos的分布式集合工具库，包括分布式ArrayList、分布式HashMap、分布式Cache、分布式锁等。
* [Paxos](https://github.com/jaksa76/paxos)：Paxos算法的Java实现。
* [URingPaxos](https://github.com/sambenz/URingPaxos)：高吞吐量原子多播协议。
* [PaxosImpl](https://github.com/hellolinjx/PaxosImpl)：Paxos算法的多线程实现。

<h2 id="cqrs">CQRS框架</h2>

* [JDON](https://github.com/banq/jdonframework)：领域驱动设计Pub/Sub领域事件框架。
* [Reveno](https://github.com/dmart28/reveno)：高性能和低延迟事件源/CQRS框架。
* [Zilla](https://github.com/aklivity/zilla)：多协议、事件本机边缘/服务代理。
* [Splitet](https://github.com/Splitet/SplitetFramework)：Splitet是一个基于Java的事件溯源框架，计划以最小的学习曲线和易于适应的方式进行CQRS转换的团队可以从中受益。
* [Loom](https://github.com/loom/loom-java)：Loom是一组用于实现分布式消息传递和事件源模式的框架。
* [Sourcerer](https://github.com/elder-oss/sourcerer)：一个功能性且与存储无关的框架，用于使用事件源在Java 8中实现CQRS架构。
* [Apache Polygene](https://github.com/apache/polygene-java)：探索面向领域的应用程序开发的面向复合编程。
* [Dewdrop](https://github.com/matsientst/dewdrop)：Dewdrop是一个简单、快速且功能强大的基于Java的事件源框架。

<h2 id="ddd">DDD框架</h2>

* [Library](https://github.com/ddd-by-examples/library)：全面的领域驱动设计示例，包含问题空间战略分析和各种战术模式。
* [DDDplus](https://github.com/funkygao/cp-ddd-framework)：轻量级DDD正向/逆向业务建模框架。
* [Apache Causeway](https://github.com/apache/causeway)：Apache Causeway软件是一个用于使用Java快速开发领域驱动应用程序的框架。
* [DDDLib](https://github.com/dayatang/dddlib)：DDDLib是一个领域驱动设计类库。
* [Dante-Cloud](https://github.com/dromara/dante-cloud)：Dante Cloud是一款企业级微服务架构和服务能力开发平台，是采用领域驱动模型(DDD)设计思想的、全面拥抱Spring Authorization Server、基于OAuth 2.1协议、支持智能电视、IoT等物联网设备认证的多租户微服务解决方案。
* [DDDplus](https://github.com/dddplus/dddplus)：轻量级DDD增强框架。
* [DDD Base](https://github.com/linux-china/ddd-base)：DDD Java基础包。
* [Context Mapper DSL](https://github.com/ContextMapper/context-mapper-dsl)：用于上下文映射和服务分解的领域特定语言。
* [Spine Event Engine](https://github.com/SpineEventEngine/core-java)：DDD框架核心的Java实现。

<h2 id="architecture">软件工程</h2>

* [COLA](https://github.com/alibaba/COLA)：干净的面向对象和分层架构组件，由阿里开源。
* [jMolecules](https://github.com/xmolecules/jmolecules)：可帮助开发人员以无干扰、简单的旧式Java实现域模型。
* [Rosie](https://github.com/Karumi/Rosie)：Rosie是一个Android框架，用于创建遵循清洁架构原则的应用程序。
* [Capella](https://github.com/eclipse/capella)：基于模型的系统工程的开源解决方案。
* [Structurizr](https://c4model.com/)：Structurizr打破了架构图编辑器(例如UML)的传统拖放方法，并允许我们使用我们最了解的工具：Java来描述我们的架构工件。
* [Modelio](https://github.com/ModelioOpenSource/Modelio)：Modelio是一种建模解决方案，提供基于企业架构、软件开发和系统工程主要标准的广泛功能。
* [Spring Modulith](https://github.com/spring-projects/spring-modulith)：Spring Modulith允许开发人员构建结构良好的Spring Boot应用程序，并指导开发人员查找和使用由领域驱动的应用程序模块。
* [Moduliths](https://github.com/moduliths/moduliths)：构建模块化、整体式Spring Boot应用程序的框架。

<h2 id="migrate">迁移工具</h2>

* [EMT4J](https://github.com/adoptium/emt4j)：EMT4J是一个旨在简化Java版本迁移的项目，目前，该项目专注于三个LTS版本：8、11和17。
* [Mongock](https://github.com/mongock/mongock)：Mongock是一个基于Java的迁移工具，作为应用程序代码的一部分。
* [Spring Boot Migrator](https://github.com/spring-projects-experimental/spring-boot-migrator)：Spring Boot Migrator(SBM)旨在通过提供自动迁移的方法来帮助开发人员升级或迁移到Spring Boot。
* [Windup](https://github.com/windup/windup)：Windup是一个工具集，支持跨广泛转换和用例的大规模Java应用程序现代化和迁移项目。
* [Jakarta Migration](https://github.com/apache/tomcat-jakartaee-migration)：该工具的目的是自动对为Java EE 8编写并在Apache Tomcat 9上运行的Web应用程序进行转换，以便可以在实现Jakarta EE 9的Apache Tomcat 10上运行。

<h2 id="jsf">JSF框架</h2>

* [PrimeFaces](https://github.com/primefaces/primefaces)：JavaServer Faces的终极组件套件。
* [JoinFaces](https://github.com/joinfaces/joinfaces)：旨在解决JSF和Spring Boot集成功能。
* [PrimeFaces-Extensions](https://github.com/primefaces-extensions/primefaces-extensions)：PrimeFaces扩展。
* [Omnifaces](https://github.com/omnifaces/omnifaces)：让JSF开发更轻松。
* [Adminfaces](https://github.com/adminfaces/admin-template)：AdminFaces是一个开源项目，它集成了Primefaces、Bootstrap和Admin LTE，以创建完全响应且适合移动设备的JSF应用程序。
* [Mojarra](https://github.com/eclipse-ee4j/mojarra)：Eclipse基金会下的Jakarta Faces实现。
* [Apache MyFaces](https://github.com/apache/myfaces)：Apache基金会下的Jakarta Faces实现。
* [ButterFaces](https://github.com/butterfaces/butterfaces)：一个轻量级、响应式的JSF框架，结合了Bootstrap、jQuery和HTML 5的优点，使用JSF 2开发快速、简单和现代的Web应用程序。
* [RichFaces](https://github.com/richfaces/richfaces)：RedHat JBoss的JSF组件框架。
* [ChartistJSF](https://github.com/hatemalimam/ChartistJSF)：JavaServer Faces的高度可定制响应式图表。
* [Springfaces](https://github.com/philwebb/springfaces)：Spring JSF集成。

<h2 id="bot">机器人</h2>

* [MusicBot](https://github.com/jagrosh/MusicBot)：一个可以轻松设置和运行的Discord音乐机器人。
* [Mirai](https://github.com/mamoe/mirai)：高效率QQ机器人支持库。
* [TelegramBots](https://github.com/rubenlagus/TelegramBots)：使用Telegram Bots API创建机器人的Java库。
* [JDA](https://github.com/discord-jda/JDA)：流行的聊天和VOIP服务的Java包装器。
* [Discord4J](https://github.com/Discord4J/Discord4J)：Discord4J是一个快速、强大、无偏见的响应式库，可使用官方Discord Bot API快速轻松地开发适用于Java、Kotlin和其他JVM语言的Discord机器人。
* [Java Telegram Bot API](https://github.com/pengrad/java-telegram-bot-api)：用于Java的Telegram Bot API。
* [JBot](https://github.com/rampatra/jbot)：JBot是一个Java框架(受Botkit启发)，可在几分钟内创建Slack和Facebook机器人。
* [R-Bot](https://github.com/semicons/java_oci_manage)：应用于甲骨文云/Azure云的一些快捷操作。
* [Javacord](https://github.com/Javacord/Javacord)：一个易于使用的多线程库，用于在Java中创建Discord机器人。
* [GiveawayBot](https://github.com/jagrosh/GiveawayBot)：在Discord服务器上快速轻松地保存赠品。
* [Line Message SDK](https://github.com/line/line-bot-sdk-java)：适用于Java的LINE Messaging API SDK可以轻松使用LINE Messaging API开发机器人，并且可以在几分钟内创建示例机器人。
* [BotLibre](https://github.com/BotLibre/BotLibre)：适用于人工智能、聊天机器人、虚拟代理、社交媒体自动化和实时聊天自动化的开放平台。
* [Vortex](https://github.com/jagrosh/Vortex)：Discord审核机器人。
* [Jeeves](https://github.com/kanjielu/jeeves)：一个智能微信机器人。
* [Repairnator](https://github.com/eclipse/repairnator)：Github上的软件机器人开源平台。
* [MantaroBot](https://github.com/Mantaro/MantaroBot)：使用JDA用Java制作的多用途Discord机器人。
* [TradeBot](https://github.com/markusaksli/TradeBot)：使用Binance API的加密货币交易机器人。
* [WeChat Robot](https://gitee.com/hellokaton/wechat-robot)：Java版微信普通号机器人。
* [dwBot](https://gitee.com/dullwolf/dwBot)：一款可以实现指令读取的QQ机器人。
* [Sokobot](https://github.com/PolyMarsDev/Sokobot)：一个可以玩推箱子的Discord机器人。
* [AIODE](https://github.com/robinfriedli/aiode)：可播放Spotify曲目和YouTube视频或任何URL(包括Soundcloud链接和Twitch流)的Discord机器人。
* [JDA-Utilities](https://github.com/JDA-Applications/JDA-Utilities)：JDA协助创建机器人的一系列工具和实用程序。
* [Messenger4j](https://github.com/messenger4j/messenger4j)：用于在Facebook Messenger平台上构建聊天机器人的Java库。
* [TDLight Java](https://github.com/tdlight-team/tdlight-java)：基于TDLib的完整Bot和Userbot Telegram库。
* [Microsoft Bot Framework Java SDK](https://github.com/microsoft/botbuilder-java)：Microsoft Bot Framework提供了构建和连接智能机器人所需的功能，无论用户在哪里交谈，这些机器人都可以自然地交互，从文本/短信到Skype、Slack、Office 365邮件和其他流行服务。
* [Chuu](https://github.com/ishwi/Chuu)：Chuu是一个Discord机器人，将Last.fm与Discord集成。
* [Mutters](https://github.com/rabidgremlin/Mutters)：构建机器人大脑的框架。
* [WeChatBotEngine](https://github.com/moontide/WeChatBotEngine)：基于微信网页版HTTP协议的机器人引擎。
* [FeishuBot](https://github.com/rawchen/FeishuBot)：飞书群聊/私聊ChatGPT机器人。
* [PokuBot](https://github.com/norecha/pokubot)：部落冲突机器人。

<h2 id="android">安卓库</h2>

* [React Native](https://github.com/facebook/react-native)：使用React构建原生应用程序的框架，由Facebook开源。
* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)：强大的Android图表视图/图形视图库，支持折线图、饼图、雷达图、气泡图和烛台图以及缩放、平移和动画。
* [Lottie](https://github.com/airbnb/lottie-android)：Lottie是一个适用于Android和iOS的移动库，它可以解析使用Bodymovin导出为JSON的Adobe After Effects动画，并在移动设备上本地渲染它们，由Airbnb开源。
* [Glide](https://github.com/bumptech/glide)：Glide是一个快速高效的Android开源媒体管理和图像加载框架，它将媒体解码、内存和磁盘缓存以及资源池封装到一个简单易用的界面中。
* [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)：该库封装了Android开发中常用的功能，有完整的Demo和单元测试。
* [Butter Knife](https://github.com/JakeWharton/butterknife)：将Android视图和回调绑定到字段和方法。
* [NewPipe](https://github.com/TeamNewPipe/NewPipe)：适用于Android的自由轻量级流媒体前端。
* [Termux](https://github.com/termux/termux-app)：Termux是一个Android终端应用程序和Linux环境。
* [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)：SmartRefreshLayout以打造一个强大、稳定、成熟的下拉刷新框架为目标，并集成各种的炫酷、多样、实用、美观的Header和Footer。
* [Freeline](https://github.com/alibaba/freeline)：Android超快速构建工具，Instant Run的替代品，由阿里开源。
* [Signal Android](https://github.com/signalapp/Signal-Android)：Signal是一个简单、强大且安全的信使。
* [Telegram](https://github.com/DrKLO/Telegram)：Telegram是一款注重速度和安全性的消息应用程序。
* [ExoPlayer](https://github.com/google/ExoPlayer)：适用于Android的可扩展媒体播放器，由Google开源。
* [RxAndroid](https://github.com/ReactiveX/RxAndroid)：适用于Android的RxJava绑定。
* [DoKit](https://github.com/didi/DoKit)：一款面向泛前端产品研发全生命周期的效率平台，由滴滴开源。
* [Walle](https://github.com/Meituan-Dianping/walle)：Android Signature V2 Scheme签名下的新一代渠道包打包神器，由美团开源。
* [Mindustry](https://github.com/Anuken/Mindustry)：用Java编写的自动化塔防RTS。
* [PhotoView](https://github.com/Baseflow/PhotoView)：Android版ImageView的实现，支持通过各种触摸手势进行缩放。
* [Fresco](https://github.com/facebook/fresco)：用于管理图像及其使用的内存的Android库，由Facebook开源。
* [Tinker](https://github.com/Tencent/tinker)：Tinker是Android的热修复解决方案库，它支持dex、库和资源更新，无需重新安装apk，由腾讯开源。
* [Material Components Android](https://github.com/material-components/material-components-android)：适用于Android的模块化和可定制的Material Design UI组件。
* [VirtualXposed](https://github.com/android-hacker/VirtualXposed)：无需Root即可使用Xpose，解锁引导加载程序或修改系统镜像等。
* [CircleImageView](https://github.com/hdodenhof/CircleImageView)：快速的圆形ImageView，非常适合个人资料图像。
* [ARouter](https://github.com/alibaba/ARouter)：帮助Android APP进行组件化改造的路由框架，由阿里开源。
* [QMUI_Android](https://github.com/Tencent/QMUI_Android)：提高Android UI开发效率的UI库，由腾讯开源。
* [Stetho](https://github.com/facebookarchive/stetho)：Stetho是Android应用程序的调试桥，支持强大的Chrome开发者工具等，由Facebook开源。
* [SmartTube](https://github.com/yuliskov/SmartTubeNext)：适用于运行Android操作系统的机顶盒和电视的高级播放器。
* [Matisse](https://github.com/zhihu/Matisse)：精心设计的Android本地图像和视频选择器，由知乎开源。
* [QtScrcpy](https://github.com/barry-ran/QtScrcpy)：Android实时显示控制软件。
* [LSPosed](https://github.com/LSPosed/LSPosed)：Xpose是一个模块框架，可以在不接触任何APK的情况下更改系统和应用程序的行为。
* [VasSonic](https://github.com/Tencent/VasSonic)：VasSonic是腾讯VAS团队开发的一款轻量级、高性能的Hybrid框架，旨在加速Android和iOS平台上的网站首屏速度。
* [uCrop](https://github.com/Yalantis/uCrop)：Android图像裁剪库。
* [Dex2Jar](https://github.com/pxb1988/dex2jar)：用于处理Android .dex和Java .class文件的工具。
* [PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher)：用于处理Android运行时权限的声明式API。
* [DanmakuFlameMaster](https://github.com/bilibili/DanmakuFlameMaster)：Android上开源弹幕解析绘制引擎项目，由B站开发。
* [Epoxy](https://github.com/airbnb/epoxy)：Epoxy是一个Android库，用于在RecyclerView中构建复杂的屏幕，由Airbnb开源。
* [Atlas](https://github.com/alibaba/atlas)：一个强大的Android动态组件框架，由阿里开源。
* [Hippy](https://github.com/Tencent/Hippy)：Hippy是一个跨平台的开发框架，旨在帮助开发者一次编写，在多个平台(iOS、Android、Web等)上运行，由腾讯开源。
* [Litho](https://github.com/facebook/litho)：Litho是一个用于在Android上构建高效UI的声明式框架，由Facebook开源。
* [RePlugin](https://github.com/Qihoo360/RePlugin)：一个灵活、稳定、易用的Android插件框架，由360开源。
* [Shadow](https://github.com/Tencent/Shadow)：零反射全动态Android插件框架，由腾讯开源。
* [Robust](https://github.com/Meituan-Dianping/Robust)：Robust是一款高兼容性、高稳定性的Android HotFix解决方案，由美团开源。
* [MagicaSakura](https://github.com/bilibili/MagicaSakura)：Android多主题框架，由B站开源。
* [Bundletool](https://github.com/google/bundletool)：Bundletool是一个操作Android App Bundle和Android SDK Bundle的工具，由Google开源。
* [Andromeda](https://github.com/iqiyi/Andromeda)：Andromeda为本地和远程服务提供模块之间的通信，由爱奇艺开发。

<h2 id="gui">GUI开发工具</h2>

这里列出了Java中常用的Swing、JavaFx开发库，以及一些Java开发的GUI工具和游戏引擎。

<h4 id="swing">Swing库</h4>

* [FlatLaf](https://github.com/JFormDesigner/FlatLaf)：FlatLaf是Java Swing桌面应用程序的现代开源跨平台外观。
* [BeautyEye](https://github.com/JackJiang2011/beautyeye)：BeautyEye是一种Java Swing跨平台外观。
* [WebLaf](https://github.com/mgarin/weblaf)：WebLaF是一个完全开源的外观和感觉以及用纯Java编写的组件库，用于跨平台桌面Swing应用程序。
* [Orson-Charts](https://github.com/jfree/orson-charts)：用于Java应用程序(JavaFX、Swing或服务器端)的3D图表库。
* [RSyntaxTextArea](https://github.com/bobbylight/RSyntaxTextArea)：用于Java Swing应用程序的语法突出显示、代码折叠文本编辑器。
* [Radiance](https://github.com/kirill-grouchnikov/radiance)：Radiance是一个库集合，用于基于Ephemeral设计系统编写现代、优雅且快速的Swing应用程序。
* [SWT](https://www.eclipse.org/swt/)：SWT是一个用于Java的开源小部件工具包。
* [Material-UI-Swing](https://github.com/atarw/material-ui-swing)：适用于Java Swing的现代Material Design UI。
* [Darklaf](https://github.com/weisJ/darklaf)：该项目基于Swing的Darcula外观和感觉。
* [SystemTray](https://github.com/dorkbox/SystemTray)：Java 8+上对Swing/AWT、MacOS、GtkStatusIcon和AppIndicator的跨平台SystemTray支持。
* [MiGLayout](https://github.com/mikaelgrev/miglayout)：Swing、SWT和JavaFX的官方MiG布局。
* [Material-UI-Swing](https://github.com/vincenzopalazzo/material-ui-swing)：Java Swing的现代Material Design UI。
* [TableLayout](https://github.com/EsotericSoftware/tablelayout)：Java UI工具包基于表格的布局：Libgdx、Swing、Android、TWL。
* [LGoodDatePicker](https://github.com/LGoodDatePicker/LGoodDatePicker)：Java Swing日期选择器，易于使用、美观、功能强大且本地化。
* [Swing9patch](https://github.com/JackJiang2011/Swing9patch)：一组很酷的Java Swing可重用组件或UI效果。
* [DJ-Native-Swing](https://github.com/Chrriis/DJ-Native-Swing)：用于Swing的Web浏览器、Flash播放器、HTML编辑器、媒体播放器。
* [SwingBits](https://github.com/eugener/oxbow)：Swing UI增强。
* [AutoComplete](https://github.com/bobbylight/AutoComplete)：Swing文本组件的代码完成库，特别支持RSyntaxTextArea。
* [Chromium](https://github.com/equodev/chromium)：在Java、SWT、Swing和Eclipse RCP应用程序中创建和呈现Web UI。
* [jSystemThemeDetector](https://github.com/Dansoftowner/jSystemThemeDetector)：用于检测(桌面)操作系统是否使用深色UI主题的Java库。
* [JDatePicker](https://github.com/JDatePicker/JDatePicker)：Java Swing日期选择器。
* [SlidingLayout](https://github.com/AurelienRibon/sliding-layout)：功能强大的Java Swing面板/布局，具有涉及滑动子面板的炫酷过渡。
* [SwingLibrary](https://github.com/robotframework/SwingLibrary)：Robot Framework的Swing UI测试库。
* [assertj-swing](https://github.com/assertj/assertj-swing)：用于Swing应用程序的流式断言。
* [RxSwing](https://github.com/ReactiveX/RxSwing)：Swing的RxJava绑定。
* [KControls](https://github.com/k33ptoo/KControls)：Java Swing自定义控件。
* [UiBooster](https://github.com/Milchreis/UiBooster)：创建快速、简单对话框的实用工具。
* [Sierra](https://github.com/HTTP-RPC/Sierra)：Java的声明式UI。
* [LEGUI](https://github.com/SpinyOwl/legui)：Java OpenGL GUI库，专为与最新的LWJGL(LWJGL 3)一起使用而创建。
* [InventoryGui](https://github.com/Phoenix616/InventoryGui)：用于Bukkit插件的库，用于创建带有清单的GUI。
* [InvUI](https://github.com/NichtStudioCode/InvUI)：用于创建基于库存的自定义GUI的插头库。
* [Lemur](https://github.com/jMonkeyEngine-Contributions/Lemur)：Lemur是一个基于jMonkeyEngine的UI工具包。
* [Limelight](https://github.com/slagyr/limelight)：用于Ruby/Clojure/Java的GUI库。

<h4 id="javafx-lib">JavaFX库</h4>

* [JFoenix](https://github.com/sshahine/JFoenix)：JavaFX材料设计库。
* [xJavaFxTool](https://github.com/864381832/xJavaFxTool)：基于JavaFX搭建的实用小工具集合，方便开发过程中的代码编写与调试。
* [TrayNotification](https://github.com/PlusHaze/TrayNotification)：JavaFX中的托盘通知类，允许在桌面计算机上调用美观的通知。
* [RichTextFX](https://github.com/FXMisc/RichTextFX)：RichTextFX为JavaFX提供了一个节省内存的文本区，允许开发人员设置文本范围的样式。
* [MaterialFX](https://github.com/palexdev/MaterialFX)：JavaFX材质组件库。
* [CalendarFX](https://github.com/dlsc-software-consulting-gmbh/CalendarFX)：用于创建复杂日历视图的Java框架。
* [FXLauncher](https://github.com/edvin/fxlauncher)：JavaFX应用程序的自动更新启动器。
* [XR3Player](https://github.com/goxr3plus/XR3Player)：最先进的JavaFX媒体播放器。
* [SceneBuilder](https://github.com/gluonhq/scenebuilder)：Scene Builder是一个可视化拖放布局工具，用于设计JavaFX应用程序用户界面。
* [JFXtras](https://github.com/JFXtras/jfxtras)：JavaFX的支持库，包含工具程序类、扩展布局、控件和其他有趣的小部件。
* [RxJavaFX](https://github.com/ReactiveX/RxJavaFX)：JavaFX的RxJava绑定。
* [WorkbenchFX](https://github.com/dlsc-software-consulting-gmbh/WorkbenchFX)：用于JavaFX应用程序的轻量级RCP框架。
* [mvvmFX](https://github.com/sialcasa/mvvmFX)：使用JavaFX实现MVVM模式的应用程序框架。
* [AnimateFX](https://github.com/Typhon0/AnimateFX)：包含70多个即用型JavaFX动画的库。
* [DashboardFx](https://github.com/gleidsonmt/DashboardFx)：该项目是为JavaFX创建的自定义组件集的一部分。
* [ReactFX](https://github.com/TomasMikula/ReactFX)：ReactFX是对JavaFX(函数式)响应式编程技术的补充。
* [Substrate](https://github.com/gluonhq/substrate)：Gluon Substrate是一款将JavaFX客户端应用程序转换为桌面、移动和嵌入式设备的本机可执行文件的工具。
* [GemsFX](https://github.com/dlsc-software-consulting-gmbh/GemsFX)：JavaFX控件和实用程序的集合。
* [VWorkflows](https://github.com/miho/VWorkflows)：JavaFX和VRL-Studio的流可视化库。
* [DockFX](https://github.com/RobertBColton/DockFX)：适用于JavaFX平台的功能齐全的对接库。
* [WebFX](https://github.com/webfx-project/webfx)：JavaFX应用程序转译器，使用JavaFX编写Web应用程序，WebFX会将其转译为纯JS。
* [FXRibbon](https://github.com/dukke/FXRibbon)：Java的Ribbon控件，使用JavaFX框架，基于Microsoft Ribbon。
* [WebBrowser](https://github.com/goxr3plus/JavaFX-Web-Browser)：用Java和JavaFX制作的Web浏览器。
* [RXControls](https://github.com/leewyatt/rxcontrols)：RXControls是一个JavaFX自定义组件库。
* [TornadoFX](https://github.com/edvin/tornadofx)：Kotlin的轻量级JavaFX框架。
* [AnchorFX](https://github.com/alexbodogit/AnchorFX)：JavaFX平台停靠框架。
* [Flowless](https://github.com/FXMisc/Flowless)：JavaFX的高效VirtualFlow。
* [ValidatorFX](https://github.com/effad/ValidatorFX)：JavaFX的表单验证库。
* [EasyBind](https://github.com/TomasMikula/EasyBind)：EasyBind在创建自定义绑定时利用Lambda来减少样板文件，为Bindings.select*方法提供类型安全的替代方案，并向ObservableValue添加单子操作。
* [Maps](https://github.com/gluonhq/maps)：Gluon Maps提供了一种将OpenStreetMaps集成到JavaFX应用程序中的简单方法。
* [Ikonli](https://github.com/kordamp/ikonli)：Ikonli提供可在Java应用程序中使用的图标包，目前支持Swing和JavaFX UI工具包。
* [DesktopPaneFX](https://github.com/kordamp/desktoppanefx)：JavaFX的MDI组件。
* [KeyboardFX](https://github.com/dlsc-software-consulting-gmbh/KeyboardFX)：JavaFX应用程序的屏幕键盘。
* [LibRawFX](https://github.com/lanthale/LibRawFX)：集成适用于所有主要操作系统的JavaFX的LibRaw库。
* [LitFX](https://github.com/Birdasaur/LitFX)：可连接到JavaFX 2D GUI的闪电和其他动画光/粒子效果。
* [NSMenuFX](https://github.com/0x4a616e/NSMenuFX)：JavaFX应用程序的完整macOS菜单栏访问。
* [PDFViewFX](https://github.com/dlsc-software-consulting-gmbh/PDFViewFX)：允许应用程序显示PDF文件的自定义控件。
* [TiwulFX](https://github.com/panemu/tiwulfx-dock)：TiwulFX-Dock提供增强的JavaFX TabPane，支持选项卡重新排序、分离和对接。
* [UnitFX](https://github.com/dlsc-software-consulting-gmbh/UnitFX)：用于创建测量单位输入字段的框架。
* [UpdateFX](https://github.com/vinumeris/updatefx)：一个用于对Java应用程序进行灵活、多签名Web风格在线更新的库。

<h4 id="javafx-ui">JavaFX样式库</h4>

* [ControlsFX](https://github.com/controlsfx/controlsfx)：ControlsFX是JavaFX的一个开源项目，旨在提供真正高质量的UI控件和其他工具来补充核心JavaFX发行版。
* [BootstrapFX](https://github.com/kordamp/bootstrapfx)：BootstrapFX是Twitter Bootstrap的部分移植。
* [PreferencesFX](https://github.com/dlsc-software-consulting-gmbh/PreferencesFX)：用于轻松创建应用程序设置/首选项UI的框架。
* [FormsFX](https://github.com/dlsc-software-consulting-gmbh/FormsFX)：用于轻松创建JavaFX UI表单的框架。
* [AtlantaFX](https://github.com/mkpaz/atlantafx)：现代JavaFX CSS主题集合，带有附加控件。
* [JFXtras Styles](https://github.com/JFXtras/jfxtras-styles)：Java、JavaFX主题或外观，目前包含JMetro主题。
* [JBootX](https://github.com/dicolar/jbootx)：JavaFX Bootstrap主题库。
* [CustomStage](https://github.com/Oshan96/CustomStage)：用于创建完全自定义的未修饰窗口的JavaFX UI框架。
* [CSSFX](https://github.com/McFoggy/cssfx)：允许运行时修改JavaFX CSS。
* [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph)：该项目提供了一个通用JavaFX图形可视化库，可以通过力导向算法实时自动排列顶点的位置。
* [Animated](https://github.com/iamgio/animated)：JavaFX的现代动画库。
* [FXSkins](https://github.com/dukke/FXSkins)：现有JavaFX控件的新外观集合。
* [JSilhouette](https://github.com/kordamp/jsilhouette)：JSilhouette为Java应用程序提供了额外的形状。
* [JFXShader](https://github.com/Teragam/JFXShader)：允许在JavaFX中自定义效果着色器。
* [MDFX](https://github.com/JPro-one/markdown-javafx-renderer)：MDFX是一个简单的JavaFX渲染器。
* [FXParallax](https://github.com/dukke/FXParallax)：用于为Java添加视差效果的控件。
* [Actlist](https://github.com/actlist/actlist)：Actlist是一个实用平台，可以轻松简单地执行你自己的行为列表。

<h4 id="javafx-chart">JavaFX图表库</h4>

* [TilesFX](https://github.com/HanSolo/tilesfx)：包含可用于仪表板的图块的JavaFX库。
* [Medusa](https://github.com/HanSolo/medusa)：用于仪表的JavaFX库。
* [Charts](https://github.com/HanSolo/charts)：包含不同类型图表的JavaFX库。
* [ChartFx](https://github.com/fair-acc/chart-fx)：一个科学图表库，专注于以25Hz更新速率针对具有几万到500万个数据点的数据集进行性能优化的实时数据可视化。
* [FXTrayIcon](https://github.com/dustinkredmond/FXTrayIcon)：用于JavaFX应用程序的库，可以更轻松地添加系统托盘图标。
* [GMapsFX](https://github.com/dlsc-software-consulting-gmbh/GMapsFX)：用于在JavaFX应用程序中使用Google地图的Java API。
* [FXForm2](https://github.com/dooApp/FXForm2)：动态JavaFX表单生成。
* [FXGraphics2D](https://github.com/jfree/fxgraphics2d)：一个JavaFX库，允许使用Java2D代码(Graphics2D)绘制到Canvas节点。
* [FlexGanttFX](https://dlsc.com/products/flexganttfx/)：FlexGanttFX是目前可用于Java的最先进的基于JavaFX的甘特图框架。
* [FXyz](https://github.com/FXyz/FXyz)：JavaFX 3D可视化和组件库。
* [Countries](https://github.com/HanSolo/countries)：包含不同控件的JavaFX库，用于可视化基于国家/地区的数据。
* [Animated](https://github.com/iAmGio/animated)：JavaFX的现代动画库。

<h4 id="javafx-tool">JavaFX小工具</h4>

* [JabRef](https://github.com/JabRef/jabref)：用于管理BibTeX和biblatex(.bib)数据库的图形化Java应用程序。
* [PDFsam](https://github.com/torakiki/pdfsam)：一款用于拆分、合并、混合、旋转PDF文件和提取页面的桌面应用程序。
* [AsciidocFX](https://github.com/asciidocfx/AsciidocFX)：使用JavaFX 19编写的Asciidoc编辑器和工具链(构建PDF、Epub、Mobi和HTML书籍、文档和幻灯片)。
* [Fofa Viewer](https://github.com/wgpsec/fofa_viewer)：用JavaFX编写的简单FOFA客户端。
* [QuPath](https://github.com/qupath/qupath)：QuPath是用于生物图像分析的开源软件。
* [Everest](https://github.com/RohitAwate/Everest)：一个漂亮的跨平台REST客户端。
* [Phoenicis](https://github.com/PhoenicisOrg/phoenicis)：Phoenicis是PlayOnLinux和PlayOnMac 4的指定继承者，允许你在您喜欢的操作系统上安装和使用非本机应用程序。
* [JetUML](https://github.com/prmr/JetUML)：用于快速绘制UML图表的桌面应用程序。
* [XPipe](https://github.com/xpipe-io/xpipe)：全新的Shell连接集线器和远程文件管理器。
* [Artillery](https://github.com/Weik1/Artillery)：Java插件化漏洞扫描器，GUI基于JavaFX。
* [LaTeXDraw](https://github.com/latexdraw/latexdraw)：LaTeX的矢量绘图编辑器。
* [JDKMon](https://github.com/HanSolo/JDKMon)：一个用JavaFX编写的小工具，用于监视已安装的JDK并通知你有关更新的信息。
* [TerminalFX](https://github.com/javaterminal/TerminalFX)：JavaFX终端模拟器。
* [Binjr](https://github.com/binjr/binjr)：时序数据浏览器。
* [SQLucky](https://github.com/tenie/SQLucky)：跨平台数据库可视化操作工具。
* [FakeImageDetection](https://github.com/afsalashyana/FakeImageDetection)：使用机器学习检测虚假图像。
* [OwlPlug](https://github.com/DropSnorz/OwlPlug)：音频插件管理器，用于在Windows、MacOS和Linux上管理VST/AU/LV2插件的小工具。
* [LogFX](https://github.com/renatoathaydes/LogFX)：LogFX是一个简单的日志阅读器，支持颜色突出显示并能够处理巨型文件。
* [DSTE](https://ai-solutions.com/dste/)：深空轨迹探测器，被约翰逊航天中心用作设计工具。
* [JMetro](https://pixelduke.com/java-javafx-theme-jmetro/)：JavaFX应用程序的现代主题，具有浅色和深色风格。
* [Object-Graph-Visualizer](https://github.com/Nurtak/ObjectGraphVisualization)：对象图可视化工具。

<h4 id="gui">GUI程序</h4>

* [FinalShell](https://www.hostbuf.com/)：国内开源的SSH客户端工具。
* [SoapUI](https://github.com/SmartBear/soapui)：SoapUI是一个免费、开源的跨平台API和Web Service功能测试解决方案。
* [ArgoUML](https://github.com/argouml-tigris-org/argouml)：一个用于绘制UML图的应用软件。
* [PlantUML](https://github.com/plantuml/plantuml)：可以通过纯文本的方式来生成UML图。
* [Matlab](https://www.mathworks.com/products/matlab.html)：Matlab是一种用于算法开发、数据可视化、数据分析以及数值计算的高级技术计算语言和交互式环境，其GUI部分由Java开发。
* [Protege](https://github.com/protegeproject/protege)：Protege是一个免费的开源本体编辑器，支持最新的OWL 2.0标准。
* [Gephi](https://github.com/gephi/gephi/)：可视化跨平台网络图形化操作程序。
* [blobsaver](https://github.com/airsquared/blobsaver)：用于自动保存SHSH blob的跨平台GUI和CLI应用程序。
* [Sonarqube](https://github.com/SonarSource/sonarqube)：SonarQube是一个开源的代码分析平台，可以用来持续分析和评测项目源代码的质量。
* [LibreOffice](https://github.com/LibreOffice/core)：一款开源的办公套件，包括文档处理、电子表格、演示文稿等功能。
* [Teambition](https://www.teambition.com/)：阿里旗下的项目协作工具。
* [Atlassian Confluence](https://www.atlassian.com/zh/software)：Confluence是一个专业的企业知识管理与协同软件。
* [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)：STM32CubeMX是ST公司推出的一种自动创建单片机工程及初始化代码的工具。
* [GeoGebra](https://www.geogebra.org/)：GeoGebra是一款动态数学(几何)软件，于2001年由Markus Hohenwarter在奥地利萨尔茨堡大学制作。
* [Logisim-evolution](https://github.com/logisim-evolution/logisim-evolution)：数字逻辑设计工具和模拟器。
* [Bits'N'Picas](https://github.com/kreativekorp/bitsnpicas)：位图和表情符号字体创建和转换工具。
* [ImageJ](https://imagej.net/ij/index.html)：生物医学领域的图像处理软件。
* [Vivado](https://www.xilinx.com/products/design-tools/vivado.html)：Xilinx开发的用于HDL设计的合成和分析的软件套件，具有用于片上系统开发和高级综合的附加功能。
* [Citespace](https://citespace.podia.com/)：基于Java语言编写的可视化文献分析软件。
* [ArcTime](https://arctime.org/)：ArcTime是使用Java编写的免费跨平台字幕软件。
* [FreeMind](https://github.com/jiangxin/freemind-mmx)：FreeMind是一款免费开源的思维导图软件。
* [Xmind](https://xmind.app/)：Xmind是一款全功能的思维导图和头脑风暴软件。
* [CuratOR](https://eizo-or.com/en/global/products/or-software/curator-caliop-vm/)：CuratorOR由德国EIZO GmbH开发，是一款用在医院手术室的应用程序。
* [mybatis-generator-gui](https://github.com/zouzg/mybatis-generator-gui)：Mybatis-Generator界面工具，可以更加直观的生成代码。
* [ThinkPHPGUI](https://github.com/Lotus6/ThinkphpGUI)：Thinkphp(GUI)漏洞利用工具，支持各版本TP漏洞检测，命令执行，getshell。
* [Super-Xray](https://github.com/4ra1n/super-xray)：Web漏洞扫描工具XRAY的GUI启动器。
* [Poc2jar](https://github.com/f0ng/poc2jar)：Java编写，Python作为辅助依赖的漏洞验证、利用工具。
* [Particle-Life](https://github.com/tom-mohr/particle-life-app)：Particle Life的GUI，这是一个显示逼真行为的粒子系统。
* [FutureRestore-GUI](https://github.com/CoocooFroggy/FutureRestore-GUI)：FutureRestore的现代GUI，添加了使过程更容易的功能。
* [NMapGUI](https://github.com/daniel-cues/NMapGUI)：NMap的高级图形用户界面。
* [jExifToolGUI](https://github.com/hvdwolf/jExifToolGUI)：jExifToolGUI是Phil Harvey的一个多平台Java/Swing图形前端，用于优秀的命令行ExifTool应用程序。
* [WePush](https://github.com/rememberber/WePush)：专注批量推送的小而美的工具，目前支持：模板消息-公众号、模板消息-小程序、微信客服消息等。
* [WeSync](https://github.com/rememberber/WeSync)：用Java Swing写的数据库同步软件。
* [Remote Desktop Control](https://github.com/Cool-Coding/remote-desktop-control)：远程桌面控制软件。
* [CXTouch](https://github.com/cxplan/CXTouch)：基于Java Swing的PC客户端查看和管理Android设备，支持Windows、Linux和MacOS。
* [JavaANPR](https://github.com/oskopek/javaanpr)：Java的自动车牌识别系统。
* [MooInfo](https://github.com/rememberber/MooInfo)：OSHI的可视化实现，用于查看有关系统和硬件的信息。
* [Perceptron](https://github.com/Jasonnor/Perceptron)：使用Java Swing实现的单层感知器神经网络。

<h4 id="dbtool">数据库工具</h4>

* [DBeaver](https://github.com/dbeaver/dbeaver)：免费的通用数据库工具和SQL客户端。
* [Chat2DB](https://github.com/chat2db/Chat2DB)：智能的通用数据库SQL客户端和报表工具，由阿里开源。
* [Jailer](https://github.com/Wisser/Jailer)：数据库子集和关系数据浏览工具。
* [RedisClient](https://github.com/caoxinyu/RedisClient)：基于Java SWT和Jedis编写的Redis客户端GUI工具。
* [Redis-Admin](https://github.com/mauersu/redis-admin)：一个基于Java EE和Jedis编写的Redis客户端Web工具。
* [RedisDesktopClient](https://gitee.com/RedisDesktopClient/redis-desktop-client)：RedisDesktopClient是一款颜值较高、使用方便的Redis客户端工具。
* [RedisPlus](https://gitee.com/MaxBill/RedisPlus)：RedisPlus是为Redis可视化管理开发的一款开源免费的桌面客户端软件，支持Windows、Linux、Mac三大系统平台。
* [Redis-Admin](https://gitee.com/xuebusi/redis-admin)：一个简单好用的Redis缓存图形化管理工具，包含Redis的5种数据类型的CRUD操作。
* [RedisFront](https://gitee.com/dromara/RedisFront)：RedisFront是一款dromara社区开源的跨平台Redis桌面客户端工具, 支持单机模式、集群模式、哨兵模式以及SSH隧道连接。
* [PrettyZoo](https://github.com/vran-dev/PrettyZoo)：Zookeeper GUI，支持Win/Mac/Linux平台。
* [ZkUI](https://github.com/DeemOpen/zkui)：允许在Zookeeper上进行CRUD操作的UI仪表板。
* [ZkClient](https://github.com/sgroschupf/zkclient)：Zookeeper客户端库。
* [Taokeeper](https://github.com/alibaba/taokeeper)：Java中Zookeeper的监视器，由阿里开源。
* [kafkaUI-lite](https://gitee.com/freakchicken/kafka-ui-lite)：非常好用的Kafka UI客户端工具，同时支持Zookeeper、Redis。
* [Shepher](https://gitee.com/zhannngchen/shepher)：Shepher是一款ZooKeeper的管理工具。
* [Zookeeper-Visualizer](https://github.com/xin497668869/zookeeper-visualizer)：Zookeeper的可视化管理工具。

<h4 id="classtool">字节码工具</h4>

* [JD-GUI](https://github.com/java-decompiler/jd-gui)：Java反编译器GUI。
* [Recaf](https://github.com/Col-E/Recaf)：现代Java字节码编辑器。
* [ClassyShark](https://github.com/google/android-classyshark)：Android和Java字节码查看器。
* [JClasslib](https://github.com/ingokegel/jclasslib)：jclasslib字节码编辑器是一个工具，可以可视化已编译的Java类文件和所包含的字节码的各个方面。
* [GDA](https://github.com/charles2gan/GDA-android-reversing-Tool)：最快、最强大的Android反编译器，适用于APK、DEX、ODEX、OAT、JAR、AAR和CLASS文件。
* [Luyten](https://github.com/deathmarine/Luyten)：Procyon的开源Java反编译器GUI。
* [Classpy](https://github.com/zxh0/classpy)：Classpy是一个GUI工具，用于研究Java类文件、Lua二进制块、Wasm二进制代码和其他二进制文件格式。
* [Jar-Analyzer](https://github.com/4ra1n/jar-analyzer-gui)：一个用于分析Jar包的GUI工具，可以用多种方式搜索你想要的信息，自动构建方法调用关系，支持分析Spring框架。
* [ClassViewer](https://github.com/ClassViewer/ClassViewer)：ClassViewer是一个轻量级的Java字节码文件查看器，仅依赖于JDK和JavaFX。
* [JADXecute](https://github.com/LaurieWired/JADXecute)：用于动态反编译器操作的JADX-GUI脚本插件。
* [Decompiler](https://github.com/sotasan/decompiler)：小巧的Java反编译器GUI。
* [Bytecoder](https://github.com/mirkosertic/Bytecoder)：用于将JVM字节码解释和转换为JavaScript、OpenCL或WebAssembly的框架。
* [Vineflower](https://github.com/Vineflower/vineflower)：Vineflower是一种现代通用JVM语言反编译器，专注于提供最佳的质量、速度和可用性。
* [Fernflower](https://github.com/fesh0r/fernflower)：Java反编译器。
* [JD-Core-Java](https://github.com/nviennot/jd-core-java)：Java反编译器JD-Core库。
* [Friday](https://github.com/zifeihan/friday)：Java实时反编译工具。
* [CFR](https://github.com/leibnitz27/cfr)：可以很好地将class文件从其他JVM语言转回Java。
* [JD-Eclipse](https://github.com/java-decompiler/jd-eclipse)：Java反编译器Eclipse插件。
* [ClassGraph](https://github.com/classgraph/classgraph)：超快速并行Java类路径扫描器和模块扫描器。

<h4 id="obfuscator">字节码混淆工具</h4>

* [ProGuard](https://github.com/Guardsquare/proguard)：ProGuard是一个免费的Java字节码收缩器、优化器、混淆器和预验证器。
* [AabResGuard](https://github.com/bytedance/AabResGuard)：Android App bundle资源混淆工具。
* [BlackObfuscator](https://github.com/CodingGay/BlackObfuscator)：Black Obfuscator是一款针对Android APK DexFile的混淆器，它可以帮助开发者通过控制流扁平化来保护源代码，并使分析实际程序控制流变得困难。
* [Skidfuscator](https://github.com/skidfuscatordev/skidfuscator-java-obfuscator)：使用cts和bibl设计的MapleIR框架的公共概念验证混淆器。
* [Native-Obfuscator](https://github.com/radioegor146/native-obfuscator)：用于JNI的Java class到cpp转换器。
* [Radon](https://github.com/ItzSomebody/radon)：磨损的Java字节码混淆器。
* [yGuard](https://github.com/yWorks/yGuard)：yWorks推出的与Ant和Gradle配合使用的开源Java混淆工具-图表专家。
* [Caesium](https://github.com/sim0n/Caesium)：Java字节码混淆器。
* [dProtect](https://github.com/open-obfuscator/dProtect)：dProtect是一个基于Proguard的Java和Kotlin混淆器。
* [Bozar](https://github.com/vimasig/Bozar)：使用GUI的Java字节码混淆器。
* [AndroidLibrary](https://github.com/StringCare/AndroidLibrary)：用于在运行时显示或混淆字符串和资源的Android库。
* [MCPMappingViewer](https://github.com/bspkrs/MCPMappingViewer)：一个小型GUI，用于查看从Minecraft混淆代码名称到MCP代码名称的映射。
* [SpecialSource](https://github.com/md-5/SpecialSource)：jar混淆映射的自动生成器和重命名器。
* [Masxinlingvonta](https://github.com/superblaubeere27/masxinlingvonta)：将Java字节码编译为LLVM IR(用于混淆目的)。
* [Simple String obfuscator](https://github.com/shamanland/simple-string-obfuscator)：Java的简单字符串混淆器。
* [Enigma](https://github.com/christopherney/Enigma)：混淆器字符串加密(Android/Java)。
* [CAFED00D](https://github.com/Col-E/CAFED00D)：混淆弹性Java class读取器/写入器。
* [Obfuscator](https://github.com/superblaubeere27/obfuscator)：Java混淆器。

<h4 id="game-engine">游戏开发</h4>

* [libGDX](https://github.com/libgdx/libgdx)：桌面/Android/HTML5/IOS Java游戏开发框架。
* [LWJGL](https://github.com/LWJGL/lwjgl3)：LWJGL是一个Java库，支持跨平台访问流行的本机API，可用于图形(OpenGL、Vulkan、bgfx)、音频(OpenAL、Opus)、并行计算(OpenCL、CUDA)和XR(OpenVR、LibOVR、OpenXR)应用程序。
* [Grasscutter](https://github.com/Grasscutters/Grasscutter)：某动漫游戏的服务器软件重新实现。
* [FXGL](https://github.com/AlmasB/FXGL)：Java/JavaFX/Kotlin游戏引擎库。
* [KTX](https://github.com/libktx/ktx)：libGDX游戏框架的Kotlin扩展。
* [Terasology](https://github.com/MovingBlocks/Terasology)：开源体素世界。
* [jMonkeyEngine](https://github.com/jMonkeyEngine/jmonkeyengine)：用Java编写的完整3D游戏开发套件。
* [KorGE](https://github.com/korlibs/korge)：多平台Kotlin游戏引擎。
* [JBox2d](https://github.com/jbox2d/jbox2d)：2D Java物理引擎，C++物理引擎Box2D和LiquidFun的本机Java端口。
* [AndEngine](https://github.com/nicolasgramlich/AndEngine)：免费Android 2D OpenGL游戏引擎。
* [XMage](https://github.com/magefree/mage)：XMage允许你与一名或多名在线玩家或电脑对手玩万智牌。
* [OpenRTS](https://github.com/methusalah/OpenRTS)：纯Java编码的即时战略游戏3D引擎。
* [jforgame](https://github.com/kingston-csj/jforgame)：jforgame是一个一站式游戏服务器开发框架，包含游戏服、跨服、匹配服、后台管理系统等模块。
* [FriceEngine](https://github.com/icela/FriceEngine)：基于Swing/JavaFX的JVM游戏引擎。
* [TripleA](https://github.com/triplea-game/triplea)：TripleA是一款回合制策略游戏和棋盘游戏引擎，类似于Axis & Allies或Risk。
* [Delver](https://github.com/Interrupt/delverengine)：Delver游戏引擎和编辑器。
* [LITIENGINE](https://github.com/gurkenlabs/litiengine)：纯2D Java游戏引擎。
* [Oreon](https://github.com/fynnfluegge/oreon-engine)：OpenGL/Vulkan Java 3D引擎。
* [Bladecoder-Adventure](https://github.com/bladecoder/bladecoder-adventure-engine)：经典的点击式冒险游戏引擎和编辑器。
* [mini2Dx](https://github.com/mini2Dx/mini2Dx)：高级跨平台2D游戏开发API。
* [LGame](https://github.com/cping/LGame)：一个跨平台的Java游戏引擎，支持JavaFX/Android/IOS/HTML5/Linux/MAC/Windows。
* [Spout](https://github.com/spoutdev/Spout)：开源、多线程、体素游戏引擎和平台。
* [Forge](https://github.com/Card-Forge/forge)：世界上最伟大的纸牌游戏的非官方规则引擎。
* [ModernUI](https://github.com/BloCamLimb/ModernUI)：从低级3D图形API到高级视图模型的现代桌面框架，用于开发2D/3D渲染软件或游戏引擎，具有国际化支持和许多新技术。
* [LionEngine](https://github.com/b3dgs/lionengine)：Java 2D游戏引擎。
* [SilenceEngine](https://github.com/sriharshachilakapati/SilenceEngine)：跨平台2D/3D Java游戏引擎(桌面/Html5/Android)。
* [PlayN](https://github.com/playn/playn)：PlayN是一个用Java编写的跨平台Java游戏开发库，面向HTML5浏览器、桌面JVM、Android和IOS设备。
* [DisUnity](https://github.com/ata4/disunity)：用Java编写的Unity资源和资源包文件的实验性命令行工具集，主要用于提取。
* [LWJGL](https://github.com/LWJGL/lwjgl)：轻量级Java游戏库。
* [DimensioneX](https://www.dimensionex.net/)：用于制作具有伪3D视图的浏览器游戏，游戏可以变成Facebook应用程序。
* [Jake2](https://bytonic.de/html/jake2.html)：Quake II游戏引擎的Java端口。

<h2 id="agent">JVM代理</h2>

* [WGCLOUD](https://github.com/tianshiyeben/wgcloud)：Linux运维监控工具，支持系统硬件信息、内存、CPU、温度、磁盘空间及IO、硬盘smart、系统负载、网络流量等监控。
* [Spring-Loaded](https://github.com/spring-projects/spring-loaded)：Spring Loaded是一个JVM代理，用于在JVM运行时重新加载class文件更改。
* [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent)：Java无限运行时类和资源重定义。
* [BlockHound](https://github.com/reactor/BlockHound)：用于检测来自非阻塞线程的阻塞调用的Java代理。
* [Jamm](https://github.com/jbellis/jamm)：用于内存测量的Java代理。
* [Dongtai-agent-java](https://github.com/HXSecurity/DongTai-agent-java)：针对Java应用程序的数据采集工具。
* [Cubic](https://github.com/dromara/cubic)：一站式问题定位平台，分布式实例监控、线程栈监控、线程池监控、动态Arthas命令集、依赖分析等等。
* [BTrace](https://github.com/btraceio/btrace)：用于Java平台的安全、动态跟踪工具。
* [JRebel](http://zeroturnaround.com/software/jrebel/)：用于Java的热部署工具。

<h2 id="compiler">编译器&插件</h2>

* [Google Closure Compiler](https://github.com/google/closure-compiler)：Google开源的JavaScript检查器和优化器。
* [TeaVM](https://github.com/konsoletyper/teavm)：Java字节码到JavaScript的编译器。
* [Janin](https://github.com/janino-compiler/janino)：Janino是一个超小型、快速的Java编译器。
* [JWebAssembly](https://github.com/i-net-software/JWebAssembly)：JWebAssembly是一个Java字节码到WebAssembly的编译器。
* [RoboVM](https://github.com/MobiVM/robovm)：针对iOS、Mac OSX和Linux的JVM字节码AOT编译器。
* [Chronicle Runtime Compiler](https://github.com/OpenHFT/Java-Runtime-Compiler)：Java运行时编译器。
* [Language Server](https://github.com/georgewfraser/java-language-server)：使用Java编译器API的Java语言服务器。
* [Java-OO](https://github.com/amelentev/java-oo)：Java-OO是Java编译器和IDE的模块化扩展(插件)，用于支持(类似Scala)运算符重载。
* [Manifold](https://github.com/manifold-systems/manifold)：Manifold是一个Java编译器插件，其功能包括元编程、属性、扩展方法、运算符重载、模板、预处理器等。
* [J2CL](https://github.com/google/j2cl)：J2CL是一个功能强大、简单且轻量级的从Java到Closure风格JavaScript的转译器，由Google开源。
* [Zotero](https://github.com/jlegewie/zotfile)：Zotfile是一个Zotero插件。
* [VirtualAPK](https://github.com/didi/VirtualAPK)：一个强大且轻量级的Android插件框架，由滴滴开源。
* [DroidPlugin](https://github.com/DroidPluginTeam/DroidPlugin)：Android上的插件框架，无需安装、修改或重新打包即可运行任何第三方apk。
* [Jarslink](https://github.com/sofastack/sofa-jarslink)：Jarslink是SOFABoot官方基于SOFAArk开发的功能插件，负责管理多应用在SOFAArk容器之上的合并部署，由蚂蚁开源。
* [VasDolly](https://github.com/Tencent/VasDolly)：Android V1和V2签名通道包插件，由腾讯开源。
* [PF4J](https://github.com/pf4j/pf4j)：Java插件框架。

<h2 id="lsp">语言服务器</h2>

* [Eclipse JDT Language Server](https://github.com/eclipse-jdtls/eclipse.jdt.ls)：Eclipse JDT语言服务器是语言服务器协议的Java语言特定实现，可以与支持该协议的任何编辑器一起使用，为Java语言提供良好的支持。
* [Smithy](https://github.com/smithy-lang/smithy)：Smithy是一种与协议无关的接口定义语言和一组工具，用于为任何编程语言生成客户端、服务器和文档。
* [Eclipse LSP4J](https://github.com/eclipse-lsp4j/lsp4j)：语言服务器协议的Java实现，旨在由用Java实现的工具和语言服务器使用。
* [Eclipse LemMinX](https://github.com/eclipse/lemminx)：LemMinX是语言服务器协议的XML语言特定实现，可以与支持该协议的任何编辑器一起使用，为XML语言提供良好的支持。
* [Groovy Language Server](https://github.com/GroovyLanguageServer/groovy-language-server)：Groovy的语言服务器。

<h2 id="db-client">数据库驱动</h2>

* [MongoDB](https://github.com/mongodb/mongo-java-driver)：适用于Java、Kotlin和Scala的官方MongoDB驱动程序。
* [Postgresql](https://github.com/pgjdbc/pgjdbc)：Postgresql JDBC驱动程序。
* [Postgresql R2DBC](https://github.com/pgjdbc/r2dbc-postgresql)：Postgresql R2DBC驱动程序。
* [MySQL](https://github.com/mysql/mysql-connector-j)：MySQL JDBC驱动程序。
* [AWS MySQL JDBC](https://github.com/awslabs/aws-mysql-jdbc)：AWS MuSQL Driver是一个使应用程序能够充分利用集群MySQL数据库功能的驱动程序。
* [Oracle](https://www.oracle.com/database/technologies/maven-central-guide.html)：Oracle JDBC驱动程序。
* [Oracle R2DBC](https://github.com/oracle/oracle-r2dbc)：Oracle数据库的R2DBC驱动程序。
* [SqlServer](https://github.com/microsoft/mssql-jdbc)：SqlServer JDBC驱动程序。
* [ElasticSearch](https://github.com/elastic/elasticsearch-java)：Elasticsearch官方Java客户端。
* [Jest](https://github.com/searchbox-io/Jest)：Jest是ElasticSearch的Java HTTP REST客户端。
* [Bboss](https://github.com/bbossgroups/bboss-elasticsearch)：ElasticSearch高级Java REST客户端API。
* [Redisson](https://github.com/redisson/redisson)：具有内存数据网格功能的简单Redis Java客户端。
* [Jedis](https://github.com/redis/jedis)：Jedis是Redis的Java客户端，旨在提高性能和易用性。
* [Lettuce](https://github.com/lettuce-io/lettuce-core)：高级Java Redis客户端，用于线程安全同步、异步和响应式使用。支持集群、哨兵、管道和编解码器。
* [Redis OM Spring](https://github.com/redis/redis-om-spring)：Spring Data Redis扩展，可实现更好的搜索、文档模型等。
* [Spring Data Redis](https://github.com/spring-projects/spring-data-redis)：更轻松地构建基于Redis的Spring应用程序。
* [JRedis](https://github.com/alphazero/jredis)：Redis的Java客户端和连接器。
* [Redis Protocol](https://github.com/spullara/redis-protocol)：Redis的Java客户端和服务端实现。
* [DataStax Java Driver](https://github.com/datastax/java-driver)：适用于Apache Cassandra的DataStax Java驱动程序。
* [Astyanax](https://github.com/Netflix/astyanax)：Cassandra Java客户端库，由Netflix开源。

<h2 id="minecraft">Minecraft</h2>

* [Paper](https://github.com/PaperMC/Paper)：使用最广泛的高性能Minecraft服务器，旨在修复游戏玩法和机制的不一致问题。
* [MinecraftForge](https://github.com/MinecraftForge/MinecraftForge)：Forge是一个免费的开源模组API，所有常见模组都在使用。
* [HMCL](https://github.com/huanghongxun/HMCL)：一款多功能、跨平台、流行的Minecraft桌面。
* [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher)：基于Boardwalk的Minecraft：适用于Android和iOS的Java版启动器。
* [Sodium](https://github.com/CaffeineMC/sodium-fabric)：旨在提高帧速率并减少微卡顿的Fabric模组。
* [Geyser](https://github.com/GeyserMC/Geyser)：允许使用Minecraft基岩版连接到Minecraft Java版服务器的桥接器。
* [Malmo](https://github.com/microsoft/malmo)：Project Malmo是一个建立在Minecraft之上的人工智能实验和研究平台。
* [Brigadier](https://github.com/Mojang/brigadier)：Brigadier是一个命令解析器和调度器，专为Minecraft Java版设计和开发。
* [WorldEdit](https://github.com/EngineHub/WorldEdit)：Minecraft地图编辑器和模组。
* [Iris](https://github.com/IrisShaders/Iris)：Minecraft的现代着色器模组，旨在与现有的OptiFine着色器包兼容。
* [MCA Selector](https://github.com/Querz/mcaselector)：一种从Minecraft世界中选择块进行删除或导出的工具。
* [Bukkit](https://github.com/Bukkit/Bukkit)：Minecraft服务器API。
* [Create](https://github.com/Creators-of-Create/Create)：一个为建筑、装饰和美学自动化提供各种工具和模块的模组。
* [Amidst](https://github.com/toolbox4minecraft/amidst)：Amidst是一个工具，用于显示Minecraft世界的概览，而无需实际创建它。
* [Minestom](https://github.com/Minestom/Minestom)：1.19.3轻量级Minecraft服务器。
* [Dynmap](https://github.com/webbukkit/dynmap)：一组Minecraft模组，为各种Minecraft服务器实现提供基于Web的实时地图系统。
* [Fabric](https://github.com/FabricMC/fabric)：Fabric API是Fabric mods的基本钩子和互操作机制的库。
* [Glowstone](https://github.com/GlowstoneMC/Glowstone)：一个快速、可定制且兼容的Minecraft Java版开源服务器。
* [CatServer](https://github.com/Luohuayu/CatServer)：高性能和高兼容性的1.12.2/1.16.5/1.18.2版本Forge + Bukkit + Spigot服务端。
* [LuckPerms](https://github.com/LuckPerms/LuckPerms)：Minecraft服务器的权限插件。
* [Lithium](https://github.com/CaffeineMC/lithium-fabric)：Lithium是一款免费开源的Minecraft模组，可优化游戏的许多领域，以提供更好的整体性能。
* [Essentials](https://github.com/EssentialsX/Essentials)：用于Spigot和Paper的现代Essentials套件。
* [Meteor](https://github.com/MeteorDevelopment/meteor-client)：基础Minecraft实用程序模组。
* [BungeeCord](https://github.com/SpigotMC/BungeeCord)：BungeeCord是一个复杂的代理和API，主要设计用于在多个Minecraft服务器之间传送玩家。
* [BlueMap](https://github.com/BlueMap-Minecraft/BlueMap)：一款Minecraft地图工具，可创建Minecraft世界的3D模型并将其显示在Web查看器中。
* [Velocity](https://github.com/PaperMC/Velocity)：下一代Minecraft服务器代理。
* [FarPlaneTwo](https://github.com/PorkStudios/FarPlaneTwo)：Minecraft中的细节层次渲染器，允许渲染数百万个块的距离。
* [Applied Energistics 2](https://github.com/AppliedEnergistics/Applied-Energistics-2)：一个关于物质、能量并利用它们征服世界的模组。
* [Botania](https://github.com/VazkiiMods/Botania)：以自然和植物生命的魔力为主题的Minecraft技术模组。
* [SpongeAPI](https://github.com/SpongePowered/SpongeAPI)：成熟的Minecraft插件API，不包括实现。
* [Nukkit](https://github.com/CloudburstMC/Nukkit)：Nukkit是Minecraft基岩版的核动力服务器软件。
* [SpongeForge](https://github.com/SpongePowered/SpongeForge)：一个实现SpongeAPI的Forge模组。
* [Adventure](https://github.com/KyoriPowered/adventure)：Minecraft Java版的服务器端用户界面库。
* [BuildCraft](https://github.com/BuildCraft/BuildCraft)：Minecraft模组。

<h2 id="video">音视频处理</h2>

* [Jitsi](https://github.com/jitsi/jitsi)：Jitsi是一个音频/视频和聊天通信器，支持SIP、XMPP/Jabber、IRC等协议和许多其他有用的功能。
* [Sndcpy](https://github.com/rom1v/sndcpy)：Android音频转发工具。
* [Metadata Extractor](https://github.com/drewnoakes/metadata-extractor)：一个用于从媒体文件中读取元数据的Java库。
* [Horizon](https://github.com/Yalantis/Horizon)：适用于Android的简单视觉均衡器。
* [RxAndroidAudio](https://github.com/Piasy/RxAndroidAudio)：Android音频封装库，部分Rx支持。
* [Airsonic](https://github.com/airsonic/airsonic)：Airsonic 是一款免费的基于网络的媒体流媒体，可让你随时随地访问音乐。
* [JT808](https://gitee.com/yezhihao/jt808-server)：JT808、808协议解析；支持TCP、UDP，实时兼容2011、2013、2019版本协议，支持分包。支持JT/T1078音视频协议、T/JSATL12苏标主动安全协议、T/GDRTA002粤标主动安全协议，支持Android客户端编解码。
* [TarsosDSP](https://github.com/JorenSix/TarsosDSP)：TarsosDSP是一个用于音频处理的Java库，其目的是为实用的音乐处理算法提供一个易于使用的接口。
* [WaveInApp](https://github.com/Cleveroad/WaveInApp)：可以从任何来源(音频播放器、流、语音输入)获取音频，并以高帧速率为其制作动画。
* [OpenAudible](https://github.com/openaudible/openaudible)：用于下载和管理Audible有声读物的跨平台桌面应用程序。
* [JAVE2](https://github.com/a-schild/jave2)：JAVE(Java音频视频编码器)库是ffmpeg项目的Java包装器。
* [LavaPlayer](https://github.com/sedmelluq/lavaplayer)：LavaPlayer是一个用Java编写的音频播放器库，它可以从各种源加载音轨并将其转换为Opus帧流，专为Discord机器人使用而设计。
* [Quick Media](https://github.com/liuyueyi/quick-media)：多媒体处理Web服务。
* [OmRecorder](https://github.com/kailash09dabhi/OmRecorder)：一个简单的Pcm/Wav录音机。
* [Sphinx-4](https://github.com/cmusphinx/sphinx4)：纯Java语音识别库，由美国卡内基梅隆大学开发。
* [Minim](https://github.com/ddf/Minim)：一个Java音频库，设计用于与Processing一起使用。
* [libjitsi](https://github.com/jitsi/libjitsi)：用于安全实时音频/视频通信的高级Java媒体库。
* [MP4 Parser](https://github.com/sannies/mp4parser)：用于读取、写入和创建MP4容器的Java API，操作容器与编码和解码视频和音频不同。
* [LiTr](https://github.com/linkedin/LiTr)：适用于Android的轻量级硬件加速视频/音频转码器。
* [AudioBookConverter](https://github.com/yermak/AudioBookConverter)：基于freeipod软件版本改进的AudioBookConverter(mp3到m4b转换器)。
* [Echoprint Server](https://github.com/spotify/echoprint-server)：Echoprint音频指纹系统服务器。
* [jPSXdec](https://github.com/m35/jpsxdec)：jPSXdec是一款现代的跨平台PlayStation 1音频/视频转换器。
* [JJazzLab-X](https://github.com/jjazzboss/JJazzLab-X)：一个完整的基于Midi的自动背景音乐生成框架。
* [OSCI Render](https://github.com/jameshball/osci-render)：用于通过使用音频输出在示波器上绘制对象、文本和图像来制作音乐的合成器。
* [Supersonic](https://github.com/Mach5/supersonic)：基于网络的开源媒体流媒体和点唱机分支Subsonic，支持MP3、OGG、AAC等流媒体音视频格式。
* [Jave](https://github.com/dadiyang/jave)：音频转码工具，主要用于将微信语音amr格式转换为mp3格式以便在H5的audio标签中进行播放。
* [JSyn](https://github.com/philburk/jsyn)：Java模块化音频合成器。
* [JLayer](https://github.com/umjammer/jlayer)：JLayer是一个为Java平台实时解码/播放/转换MPEG 1/2/2.5 Layer 1/2/3(即MP3)的库。
* [MaryTTS](https://github.com/marytts/marytts)：一个用纯Java编写的开源、多语言文本到语音合成系统。
* [UniversalMediaServer](https://github.com/UniversalMediaServer/UniversalMediaServer)：兼容DLNA的UPnP媒体服务器，它能够在大多数现代设备之间共享视频、音频和图像。
* [Smallville](https://github.com/nickm980/smallville)：生成代理是虚拟角色，可以存储记忆并对环境做出动态反应。
* [Rebound](https://github.com/facebookarchive/rebound)：一个Java库，用于模拟弹簧动力学并将真实世界的物理添加到你的应用程序中，由Facebook开源。
* [Processing](https://github.com/processing/processing)：处理核心和开发环境。

<h2 id="datastructure">数据结构</h2>

* [T-Digest](https://github.com/tdunning/t-digest)：一种新的数据结构，用于准确在线累积基于排名的统计数据，例如分位数和修剪平均值。
* [Bifurcan](https://github.com/lacuna/bifurcan)：该库提供了可变和不可变数据结构的高质量Java实现，每个实现都共享一个通用API。
* [Prefuse](https://github.com/prefuse/Prefuse)：Prefuse支持一组丰富的数据建模、可视化和交互功能。它为表、图和树提供优化的数据结构、大量布局和视觉编码技术，并支持动画、动态查询、集成搜索和数据库连接。
* [Tree](https://github.com/Scalified/tree)：该库包含树数据结构的不同实现，例如K进制、二叉树、表达式树等。
* [BTree4j](https://github.com/myui/btree4j)：用纯Java编写的基于磁盘的B+树。
* [Sux4J](https://github.com/vigna/Sux4J)：提供了许多相关数据结构的实现，涵盖位数组、压缩列表和最小完美哈希函数的排名/选择。
* [Conversant](https://github.com/conversant/disruptor)：Conversant Disruptor是环形缓冲区中性能最高的实现，因为它几乎没有开销，并且采用了特别简单的设计。
* [BPlusTree](https://github.com/andylamp/BPlusTree)：一种高效、简洁、简单的纯磁盘B+Tree数据结构实现。
* [RMLMapper](https://github.com/RMLio/rmlmapper-java)：RLMMapper执行RML规则来生成链接数据。
* [Chronicle-Map](https://github.com/OpenHFT/Chronicle-Map)：Chronicle Map是一种超快速、内存中、非阻塞键值存储，专为低延迟和/或多进程应用程序(例如交易和金融市场应用程序)而设计。
* [networkanalysis](https://github.com/CWTSLeiden/networkanalysis)：提供了用于网络分析的算法和数据结构，专注于网络的聚类(或社区检测)和布局(或映射)。
* [Time-Utilities](https://github.com/Breinify/brein-time-utilities)：包含多个时间相关数据和索引结构(例如IntervalTree、BucketTimeSeries)以及算法的库。
* [Funcj](https://github.com/typemeta/funcj)：用于Java的面向函数的数据结构、算法和库的集合。
* [Athena](https://github.com/sanity/Athena)：支持任意布尔查询的高效内存数据结构。
* [KVStore](https://github.com/ggrandes/kvstore)：KVStore是一个基于B+Tree的Java内存和磁盘键值存储。
* [RTree](https://github.com/davidmoten/rtree)：使用响应式API在Java中实现不可变的内存中R树和R*树。
* [Agrona](https://github.com/real-logic/Agrona)：Java的高性能数据结构和实用方法。
* [JUnion](https://github.com/TehLeo/junion)：为Java编程语言提供结构类型。

<h2 id="bloom">布隆过滤器</h2>

* [Orestes Bloomfilter](https://github.com/Baqend/Orestes-Bloomfilter)：Java中不同布隆过滤器的库，具有可选的Redis支持、计数和许多哈希选项。
* [inbloom](https://github.com/EverythingMe/inbloom)：跨语言布隆过滤器实现。
* [JRedisBloom](https://github.com/RedisBloom/JRedisBloom)：RedisBloom概率模块的Java客户端。
* [Greplin Bloom Filter](https://github.com/Cue/greplin-bloom-filter)：概率集合数据结构的Java实现。
* [PDD](https://github.com/jparkie/PDD)：基于高级布隆过滤器的算法，可在流中实现高效的近似数据去重复。
* [Minperf](https://github.com/thomasmueller/minperf)：极小的完美哈希函数库。
* [Bloofi](https://github.com/lemire/bloofi)：多维布隆过滤器的Java实现。

<h2 id="algorithms">算法库</h2>

* [Java String Similarity](https://github.com/tdebatty/java-string-similarity)：各种字符串相似度和距离算法的实现：Levenshtein、Jaro-winkler、n-Gram、Q-Gram、Jaccard索引、最长公共子序列编辑距离、余弦相似度。
* [TLAPlus](https://github.com/tlaplus/tlaplus)：TLC是一个显式状态模型检查器，用于检查以TLA+编写的规范，TLA+Toolbox是TLA+的IDE。
* [Hashids.java](https://github.com/yomorun/hashids-java)：Hashids算法Java实现。
* [AhoCorasickDoubleArrayTrie](https://github.com/hankcs/AhoCorasickDoubleArrayTrie)：基于双数组Trie结构的Aho-Corasick算法的极快实现。
* [Apache DataSketches](https://github.com/apache/datasketches-java)：随机流算法的软件库。
* [Aho-Corasick](https://github.com/robert-bor/aho-corasick)：用于高效字符串匹配的Aho-Corasick算法的Java实现。
* [Graph Neo4j](https://github.com/neo4j-contrib/neo4j-graph-algorithms)：Neo4j的高效图算法。
* [JavaWuzzy](https://github.com/xdrop/fuzzywuzzy)：FuzzyWuzzy模糊字符串匹配算法的Java实现。
* [Carrot2](https://github.com/carrot2/carrot2)：Carrot2是一个用于聚类文本的编程库。
* [Mathematical Finance Library](https://github.com/finmath/finmath-lib)：finmath-lib库提供了与数学金融相关的方法的JVM)实现。
* [Java-LSH](https://github.com/tdebatty/java-LSH)：局部敏感哈希(LSH)的Java实现。
* [Viterbi](https://github.com/hankcs/Viterbi)：通用的维特比算法实现。
* [3d-bin-container-packing](https://github.com/skjolber/3d-bin-container-packing)：最大区域拟合优先(LAFF)算法 + 暴力算法的变体。
* [Hipster4j](https://github.com/citiususc/hipster)：Hipster4j是一个轻量级且功能强大的Java和Android启发式搜索库，它包含常见的、完全可定制的算法，例如Dijkstra、A*(A-Star)、DFS、BFS、Bellman-Ford等。
* [Java HyperLogLog](https://github.com/aggregateknowledge/java-hll)：HyperLogLog算法的Java库。
* [Min2phase](https://github.com/cs0x7f/min2phase)：Kociemba两阶段算法的优化实现。
* [k-NN](https://github.com/opendistro-for-elasticsearch/k-NN)：一个机器学习插件，支持Open Distro的近似k-NN搜索算法。
* [ABAGAIL](https://github.com/pushkar/ABAGAIL)：该库包含许多互连的Java包，用于实现机器学习和人工智能算法。
* [JWave](https://github.com/graetz23/JWave)：离散傅里叶变换(DFT)、快速小波变换(FWT)和小波包变换(WPT)算法的Java实现。
* [Dexter](https://github.com/dexter/dexter)：Dexter是一个框架，它实现了一些流行的算法，并提供了开发任何实体链接技术所需的所有工具。
* [AnomalyDetection](https://github.com/JeemyJohn/AnomalyDetection)：Java实现的异常检测算法。
* [ASTRAL](https://github.com/smirarab/ASTRAL)：ASTRAL是一种在给定一组无根基因树的情况下估计无根物种树的工具。
* [Shamir](https://github.com/codahale/shamir)：Shamir的秘密共享算法在GF(256)上的Java实现。
* [TarsosLSH](https://github.com/JorenSix/TarsosLSH)：TarsosLSH是一个实现次线性最近邻搜索算法的Java库，它包含近似搜索算法和精确搜索算法。
* [RendezvousHash](https://github.com/clohfink/RendezvousHash)：基于环的一致哈希的替代方案，这是Rendezvous(最高随机权重，HRW)哈希的快速线程安全实现。
* [T-SNE-Java](https://github.com/lejon/T-SNE-Java)：Van Der Maaten和Hinton的t-SNE聚类算法的纯Java实现。
* [Streaminer](https://github.com/mayconbordin/streaminer)：用于挖掘数据流的算法集合，包括频繁项集、分位数、采样、移动平均、集合成员资格和基数。
* [Patricia-Trie](https://github.com/rkapsi/patricia-trie)：检索以字母数字编码的信息的实用算法。
* [LearnLib](https://github.com/LearnLib/learnlib)：LearnLib是一个免费的开源Java库，用于自动机学习算法。
* [Simhash Java](https://github.com/sing1ee/simhash-java)：Simhash算法的Java简单实现。
* [Junto](https://github.com/parthatalukdar/junto)：该工具包由各种基于图的半监督学习(SSL)算法的实现组成，包含高斯随机场(GRF)、吸附和修正吸附(MAD)。
* [Clust4j](https://github.com/tgsmith61591/clust4j)：一组基于Java的分类聚类算法。

<h2 id="native">原生开发库</h2>

* [JNA](https://github.com/java-native-access/jna)：JNA使Java程序可以轻松访问原生共享库，而无需编写Java代码之外的任何内容-不需要JNI或原生代码。
* [JavaCPP](https://github.com/bytedeco/javacpp)：JavaCPP提供了对Java内部原生C++的高效访问。
* [JNR-FFI](https://github.com/jnr/jnr-ffi)：JNR-FFI是一个Java库，用于加载本机库，无需手动编写JNI代码或使用SWIG等工具。
* [OSHI](https://github.com/oshi/oshi)：OSHI是一个免费的基于JNA(本机)的Java操作系统和硬件信息库，提供跨平台实现来检索系统信息，例如操作系统版本、进程、内存和CPU使用情况、磁盘和分区、设备、传感器等。
* [ReLinker](https://github.com/KeepSafe/ReLinker)：适用于Android的强大原生库加载器。
* [Spring Native](https://github.com/spring-attic/spring-native)：Spring Native提供了使用GraalVM本机映像编译器将Spring应用程序编译为本机可执行文件的beta支持。
* [JavaCPP-Presets](https://github.com/bytedeco/javacpp-presets)：JavaCPP-Presets模块包含广泛使用的C/C++库的Java配置和接口类。
* [Chronicle-Core](https://github.com/OpenHFT/Chronicle-Core)：Chronicle-Core是一个先进的低级库，为开发人员提供了与操作系统交互、管理内存、处理资源等功能强大的工具。
* [JNAerator](https://github.com/nativelibs4java/JNAerator)：JNAerator为C、C++和Objective-C库生成完整的本机绑定，针对BridJ、JNA或Node.js运行时。
* [Aparapi](https://github.com/Syncleus/aparapi)：Aparapi允许开发人员通过在运行时动态地将Java字节代码转换为OpenCL内核来编写能够直接在显卡GPU上执行的本机Java代码。
* [ImGui-Java](https://github.com/SpaiR/imgui-java)：ImGui基于JNI的绑定。
* [Jacob](https://github.com/freemansoft/jacob-project)：Jacob是一个Java库，允许Java应用程序与Microsoft Windows DLL或COM库进行通信。
* [Nalim](https://github.com/apangin/nalim)：Nalim是一个使用JVMCI(JVM编译器接口)将Java方法链接到本机函数的库。
* [LuaJava](https://github.com/jasonsantos/luajava)：LuaJava是一个Java脚本编写工具，该工具的目标是允许用Lua编写的脚本操作用Java开发的组件。
* [nrjavaserial](https://github.com/NeuronRobotics/nrjavaserial)：Java串行端口系统，这是RXTX项目的一个分支，用于本地代码的jar加载。
* [Native-Utils](https://github.com/adamheinrich/native-utils)：一个简单的工具库，用于加载存储在JAR存档中的动态库。
* [Hid4Java](https://github.com/gary-rowe/hid4java)：libusb/hidapi库的跨平台Java Native Access(JNA)包装器，在Windows/Mac/Linux上开箱即用。
* [BridJ](https://github.com/nativelibs4java/BridJ)：BridJ是一个Java/原生互操作性库，专注于速度和易用性。

<h2 id="hardware">硬件操作库</h2>

* [OpenPnP](https://github.com/openpnp/openpnp)：开源SMT拾放硬件和软件。
* [JNativeHook](https://github.com/kwhat/jnativehook)：JNativeHook是一个为Java提供全局键盘和鼠标监听器的库。
* [Repeat](https://github.com/repeats/Repeat)：跨平台鼠标/键盘记录/重播和自动化热键/宏创建，以及更高级的自动化功能。
* [System-Hook](https://github.com/kristian/system-hook)：Java应用程序的全局键盘/鼠标钩子。
* [NaturalMouseMotion](https://github.com/JoonasVali/NaturalMouseMotion)：该库提供了一种将光标可靠地移动到屏幕上指定坐标的方法，同时随机形成弧线，看起来就像真手使用鼠标将其移动到那里。
* [USB4Java](https://github.com/usb4java/usb4java)：该库可用于在Java中访问USB设备。
* [JavaSysMon](https://github.com/jezhumble/javasysmon)：JavaSysMon提供了一种独立于操作系统的方式来管理操作系统进程并获取实时系统性能信息，例如CPU和内存使用情况。
* [PixelController](https://github.com/neophob/PixelController)：该应用程序的主要目标是创建一个易于使用的矩阵控制器软件。
* [r2cloud](https://github.com/dernasherbrezon/r2cloud)：r2cloud可以跟踪和解码来自卫星的各种无线电信号。
* [S-Tools](https://github.com/naman14/S-Tools)：跟踪CPU和传感器以及拾色器、指南针和设备信息等有用功能。
* [JCuda](https://github.com/jcuda/jcuda)：CUDA的Java绑定。

<h2 id="reverse-engineering">逆向工程</h2>

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra)：Ghidra是一个由美国国家安全局研究局创建和维护的软件逆向工程(SRE)框架。
* [Apktool](https://github.com/iBotPeaches/Apktool)：Android apk文件逆向工程工具。
* [JByteMod](https://github.com/GraxCode/JByteMod-Beta)：JByteMod是一个多功能字节码编辑器，具有语法突出显示、实时反编译和方法绘图功能。
* [Bytecode Viewer](https://github.com/Konloch/bytecode-viewer)： Java 8+ Jar和Android APK逆向工程套件。
* [Super JADX](https://github.com/pkilller/super-jadx)：添加逆向工程的新功能，例如：类、字段、方法、变量、引用图等的重命名。
* [BinNavi](https://github.com/google/binnavi)：BinNavi是一个二进制分析IDE，允许检查、导航、编辑和注释控制流图以及反汇编代码的调用图，由Google开源。
* [gdbghidra](https://github.com/Comsecuris/gdbghidra)：GDB会话和GHIDRA之间的可视化桥梁。
* [Helios](https://github.com/helios-decompiler/standalone-app)：Helios是一款一体化Java逆向工程工具，它具有与最新反编译器集成的功能。
* [Kaiju](https://github.com/cmu-sei/kaiju)：CERT Kaiju是Ghidra软件逆向工程套件的二进制分析框架扩展。

<h2 id="cms">开源CMS</h2>

* [Halo](https://github.com/halo-dev/halo)：强大易用的开源建站工具。
* [Novel](https://github.com/201206030/novel)：Novel是一套基于时下最新Java技术栈Spring Boot 3 + Vue 3开发的前后端分离学习型小说项目。
* [MCMS](https://gitee.com/mingSoft/MCMS)：免费可商用的开源Java CMS内容管理系统。
* [JPress](https://gitee.com/JPressProjects/jpress)：一个完整的Java CMS网站管理系统。
* [师说CMS](https://gitee.com/shishuo/CMS_old)：一款使用Java语言开发的CMS，使用了Spring MVC、Spring、MyBatis等流行框架，提供首页大图管理、目录管理、文章管理和管理员管理等功能。
* [JFinal-CMS](https://gitee.com/jflyfox/jfinal_cms)：JFinal CMS是一个Java开发的功能强大的信息咨询网站，采用了简洁强大的JFinal作为Web框架。
* [FastCMS](https://gitee.com/dianbuapp_admin/fastcms)：FastCMS是基于Spring Boot前后端分离技术，且具有插件化架构的CMS系统。
* [DotCMS](https://github.com/dotCMS/core)：适用于企业的无头/混合内容管理系统。
* [Novel-Plus](https://github.com/201206030/novel-plus)：Novel-Plus是一个多端(PC、WAP)阅读，功能完善的原创文学CMS系统。
* [White-Jotter](https://github.com/Antabot/White-Jotter)：Spring Boot和Vue.js开发的一个简单的CMS。
* [PublicCMS](https://github.com/sanluan/PublicCMS)：PublicCMS是2023年采用主流技术开发的开源Java CCMS系统。
* [Dreamer-CMS](https://gitee.com/iteachyou/dreamer_cms)：Dreamer-CMS采用流行的Spring Boot搭建，支持静态化、标签化建站。
* [Apache Roller](https://github.com/apache/roller)：Apache Roller是一个基于Java的全功能、多用户和群组博客服务器，适用于大大小小的博客网站。
* [Tianti](https://github.com/xujeff/tianti)：天梯是一款使用Java编写的免费的轻量级CMS系统，目前提供了从后台管理到前端展现的整体解决方案。
* [巡云轻论坛系统](https://github.com/diyhi/bbs)：包含论坛、问答模块，采用Java+MySQL架构。
* [Lin-CMS](https://github.com/TaleLin/lin-cms-spring-boot)：基于Spring Boot的CMS/DMS/管理系统开发框架。
* [iTranswarp](https://github.com/michaelliao/itranswarp)：功能齐全的CMS，包括博客、wiki、讨论等，由Spring Boot提供支持的云原生应用程序。
* [FlyCms](https://github.com/sunkaifei/FlyCms)：FlyCms是一个类似知乎以问答为基础的完全开源的Java语言开发的社交网络建站程序。
* [Gentics-Mesh](https://github.com/gentics/mesh)：为开发人员提供的开源无头CMS。

<h2 id="network">网络库</h2>

* [IPScan](https://github.com/angryip/ipscan)：快速且友好的网络扫描器。
* [T-IO](https://gitee.com/tywo45/t-io)：T-IO是基于Java开发的一款高性能网络编程框架。
* [Network-Connection](https://github.com/facebookarchive/network-connection-class)：在应用程序中监听当前的网络流量并对网络质量进行分类。
* [Nzyme](https://github.com/lennartkoopmann/nzyme)：网络防御系统。
* [ONOS](https://github.com/opennetworkinglab/onos)：ONOS是唯一支持从传统“棕地”网络向SDN“绿地”网络过渡的SDN控制器平台。
* [Batfish](https://github.com/batfish/batfish)：Batfish是一种网络验证工具，通过分析网络设备的配置，为安全性、可靠性和合规性提供正确性保证。
* [ServiceTalk](https://github.com/apple/servicetalk)：苹果开源的网络框架。
* [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN)：GRASSMARLIN提供工业控制系统(ICS)以及监控和数据采集(SCADA)网络的IP网络态势感知，以支持网络安全。
* [OpenNMS](https://github.com/OpenNMS/opennms)：OpenNMS是一个开源网络监控平台，可帮助可视化和监控本地和分布式网络上的所有内容。
* [Smart-Socket](https://gitee.com/smartboot/smart-socket)：极简、易用、高性能的AIO通信框架。
* [One-NIO](https://github.com/odnoklassniki/one-nio)：One-NIO是一个用于构建高性能Java服务器的库。
* [Apache Commons Net](https://github.com/apache/commons-net)：Apache Commons Net库包含网络实用程序和协议实现的集合。
* [Envoy Mobile](https://github.com/envoyproxy/envoy-mobile)：基于适用于iOS、Android等的Envoy项目的客户端HTTP和网络库。
* [WS-Attacker](https://github.com/RUB-NDS/WS-Attacker)：WS-Attacker是一个用于Web服务渗透测试的模块化框架，它由波鸿鲁尔大学网络和数据安全系主任和Hackmanit GmbH开发。
* [Chronos](https://github.com/XiaoMi/chronos)：实现高可用、高性能、提供全局唯一而且严格单调递增timestamp的服务。
* [AdbLib](https://github.com/cgutman/AdbLib)：ADB网络协议的Java库实现。
* [Tatami](https://github.com/ippontech/tatami)：一个开源企业社交网络。
* [Universa](https://github.com/UniversaBlockchain/universa)：Universa网络、节点、客户端和API。
* [SunNetwork](https://github.com/tronprotocol/sun-network)：SunNetwork是一个致力于构建TRON区块链可信去中心化侧链的项目。
* [Jpcap](https://github.com/jpcap/jpcap)：用Java编写的应用程序的网络数据包捕获库。
* [SageTV](https://github.com/google/sagetv)：SageTV是一个跨平台的网络DVR和媒体管理系统。
* [Chronicle Network](https://github.com/OpenHFT/Chronicle-Network)：高性能网络(TCP/IP)库。
* [Netshot](https://github.com/netfishers-onl/Netshot)：网络配置和合规性管理。
* [KryoNet](https://github.com/EsotericSoftware/kryonet)：KryoNet是一个Java库，它提供了一个干净、简单的API，用于使用NIO进行高效的TCP和UDP客户端/服务器网络通信。
* [HTTP Proxy Servlet](https://github.com/mitre/HTTP-Proxy-Servlet)：这是Java Servlet形式的HTTP代理(又名网关)。
* [COMSAT](https://github.com/puniverse/comsat)：将标准Java Web相关API与Quasar纤程和Actor集成。
* [Drift](https://github.com/airlift/drift)：一个基于注解的Java库，用于创建Thrift可序列化类型和服务。
* [TLS Channel](https://github.com/marianobarrios/tls-channel)：TLS Channel是一个通过TLS连接实现ByteChannel接口的库。
* [SOFABolt](https://github.com/sofastack/sofa-bolt)：SOFABolt是一个基于Netty的轻量级、易用且高性能的远程框架，由蚂蚁开源。
* [Voovan](https://gitee.com/helyho/Voovan)：Voovan是高性能异步通信、HTTP服务器和客户端通信、动态编译支持、数据库操作帮助类等工具的框架。

<h2 id="statemachine">状态机</h2>

* [Squirrel](https://github.com/hekailiang/squirrel)：一个轻量级、高度灵活和可扩展、可诊断、易于使用和类型安全的Java状态机实现。
* [Spring-Statemachine](https://github.com/spring-projects/spring-statemachine)：Spring Statemachine项目提供了一个通用的基础设施来在Spring应用程序中使用状态机概念。
* [GdxAI](https://github.com/libgdx/gdx-ai)：基于或不基于libGDX的游戏人工智能框架，特征：转向行为、编队运动、寻路、行为树和有限状态机。
* [Stateless4j](https://github.com/stateless4j/stateless4j)：轻量级Java状态机。
* [EasyFlow](https://github.com/Beh01der/EasyFlow)：用于Java的简单轻量级有限状态机。
* [Easy-States](https://github.com/j-easy/easy-states)：Easy States是Java中事件驱动的确定性有限自动机实现。
* [StatefulJ](https://github.com/statefulj/statefulj)：有限状态机实现以及基于Spring的集成框架。
* [nFlow](https://github.com/NitorCreations/nflow)：nFlow是一种经过验证的用于编排业务流程的解决方案，它可以用作微服务编排器(Saga模式)、业务流程引擎或持久有限状态机。
* [state-machine](https://github.com/davidmoten/state-machine)：Java的有限状态机类生成器。
* [Makina](https://github.com/clnhlzmn/makina)：一个生成C语言的简单分层状态机编译器。

<h2 id="qrcode">二维码生成器</h2>

* [ZXing](https://github.com/zxing/zxing)：适用于Java、Android的ZXing条码扫描库。
* [QR-Code-generator](https://github.com/nayuki/QR-Code-generator)：Java、TypeScript/JavaScript、Python、Rust、C++、C语言的高质量QR码生成器库。
* [ZXingLite](https://github.com/jenly1314/ZXingLite)：ZXing的精简极速版，优化扫码和生成二维码/条形码，内置闪光灯等功能。
* [QArt4J](https://github.com/dieforfree/qart4j)：一个QR码生成器，可提供ASCII Art输出图像。
* [Barbecue](https://barbecue.sourceforge.net/)：Barbecue是一个开源Java库，支持广泛的一维条形码格式。
* [Barcode4J](https://barcode4j.sourceforge.net/)：提供二维条形码格式(例如DataMatrix和PDF417)以及更多输出格式。
* [QRGen](https://github.com/kenglxn/QRGen)：一个基于ZXING构建的简单的Java二维码生成API。
* [java-ocr-api](https://github.com/Asprise/java-ocr-api)：Java OCR允许你对图像(JPEG、PNG、TIFF、PDF等)执行OCR和条形码识别，并输出为纯文本、具有完整坐标的XML以及可搜索的PDF。
* [ZXingGenerator](https://github.com/vivian8725118/ZXingGenerator)：花式二维码生成库，提供了6种样式。
* [react-qr-code](https://github.com/rosskhanas/react-qr-code)：用于React和React Native的QR代码生成器。
* [visual-qr-code](https://gitee.com/boat824109722/visual-qr-code)：可以创建出设置了虚拟背景图片的二维码。
* [QRext4j](https://gitee.com/BYSRepo/qrext4j)：一个简单易用的二维码生成工具，可自定义二维码颜色和码眼样式。
* [FiwanQRCode](https://gitee.com/frogchou/FiwanQRCode)：飞网开发的二维码生成工具。

<h2 id="filesystem">文件系统</h2>

* [Jimfs](https://github.com/google/jimfs)：Jimfs是Java 8及更高版本的内存文件系统，实现了java.nio.file抽象文件系统API，由Google开源。
* [XtreemFS](https://github.com/xtreemfs/xtreemfs)：XtreemFS是一个用于联合IT基础设施的分布式、可复制和容错的文件系统。
* [Memory File System](https://github.com/marschall/memoryfilesystem)：JSR-203文件系统的内存实现。
* [RubiX](https://github.com/qubole/rubix)：针对列格式和对象存储优化的缓存文件系统。
* [ADFS](https://github.com/taobao/ADFS)：ADFS(阿里分布式文件系统)是Hadoop的演进版本，提供高可用性、自动重启等特性。
* [TngouFS](https://gitee.com/397713572/tngouFS)：天狗文件系统，主要用于图片、视频、文档等相关文件的管理。
* [Apache Commons VFS](https://github.com/apache/commons-vfs)：Apache Commons VFS是一个虚拟文件系统库。
* [FastDFS Client](https://github.com/happyfish100/fastdfs-client-java)：FastDFS Java客户端SDK。
* [JNR FUSE](https://github.com/SerCeMan/jnr-fuse)：JNR FUSE是使用Java Native Runtime(JNR)的Java中的FUSE实现。

<h2 id="report">报表引擎</h2>

* [JimuReport](https://github.com/jeecgboot/JimuReport)：一款免费的数据可视化报表，含报表和大屏设计，功能涵盖数据报表、打印设计、图表报表、大屏设计等！
* [UReport2](https://github.com/youseries/ureport)：UReport2是一个基于Spring架构的高性能纯Java报表引擎，可以通过迭代单元格来准备复杂的中式报表和报表。
* [EasyReport](https://github.com/xianrendzw/EasyReport)：EasyReport是一个简单易用的Web报表工具，它的主要功能是把SQL语句查询出的行列结构转换成HTML表格，并支持表格的跨行与跨列。
* [Telescope](https://github.com/mattprecious/telescope)：一个简单的工具，可以在你的应用程序中轻松捕获错误报告。
* [JasperReports](https://github.com/TIBCOSoftware/jasperreports)：一个复杂的报表引擎。
* [Eclipse BIRT](https://github.com/eclipse-birt/birt)：开源报告和数据可视化项目。
* [Yarg](https://github.com/cuba-platform/yarg)：YARG是一个Java开源报告库，由Haulmont开发。
* [Pentaho](https://github.com/pentaho/pentaho-reporting)：Pentaho Reporting是用于生成报告的Java类库，它使用来自多个来源的数据提供灵活的报告和打印功能，并支持输出到显示设备、打印机、PDF、Excel、XHTML、纯文本、XML和CSV文件。
* [DynamicJasper](https://github.com/intive-FDV/DynamicJasper)：DynamicJasper是一个隐藏JasperReports复杂性的API，它可以帮助开发人员在设计简单/中等复杂性报表时节省时间，自动生成报表元素的布局。
* [ExtentReports](https://github.com/extent-framework/extentreports-java)：使用ExtentReports库，可以为你的测试创建美观、交互式且详细的报告。
* [CBoard](https://gitee.com/tuiqiao/CBoard)：由上海楚果信息技术有限公司主导开源，它不仅仅是一款自助BI数据分析产品，还是开放的BI产品开发平台。
* [FineReport](https://www.finereport.com/en/)：一款商业的BI报告和仪表板软件。
* [Logi Report](https://devnet.logianalytics.com/hc/en-us/categories/1500001227442-Logi-Report)：Logi Report被设计为作为独立服务器执行，但可以将其集成到现有WAR项目中。
* [Report Mill](http://www.reportmill.com/product/)：ReportMill可以平滑地嵌入到每个Java应用程序中，此外，与BIRT一样它非常灵活：可以在运行时自定义报告。
* [iReport](https://community.jaspersoft.com/project/ireport-designer)：这是一个开源报表设计器，对于JasperReports库和JasperReports服务器免费。
* [OpenReports](https://sourceforge.net/projects/oreports/)：基于Web的报告解决方案，允许用户通过浏览器动态查看XLS、HTML或PDF格式创建的报告。
* [AJ-Report](https://gitee.com/anji-plus/report)：AJ-Report是一个完全开源，拖拽编辑的可视化设计工具。
* [JRelax-BI](https://gitee.com/zengchao/JRelax-BI)：BI商业智能，自定义表单 + 自定义流程 + 自定义报表。
* [R3-Query](https://gitee.com/aagagagag/R3-Query)：整合了企业报表领域各个周期的支持，其中包括报表设计、报表发布、报表生成、报表管理、订阅发布和报表监控等报表的整个生命周期的步骤。

<h2 id="deploy">部署工具</h2>

* [SOFAArk](https://github.com/sofastack/sofa-ark)：SOFAArk是一款基于Java实现的动态热部署和轻量级类隔离框架，由蚂蚁集团开源贡献，主要提供应用模块的动态热部署和类隔离能力。
* [Capsule](https://github.com/puniverse/capsule)：Capsule是JVM应用程序的打包和部署工具。
* [ShinyProxy](https://github.com/openanalytics/shinyproxy)：用于Shiny和数据科学应用程序的开源企业部署。
* [Rultor](https://github.com/yegor256/rultor)：Rultor是一个DevOps团队助理，它通过易于使用的直观聊天机器人界面帮助你自动执行日常操作(合并、部署和发布)。
* [Storm-yarn](https://github.com/yahoo/storm-yarn)：Storm-yarn使Storm集群能够部署到Hadoop YARN管理的机器中。
* [Raigad](https://github.com/Netflix/Raigad)：用于ElasticSearch备份/恢复、自动部署和集中配置管理的协同进程。
* [jDeploy](https://github.com/shannah/jdeploy)：jdeploy github action允许你在Github工作流中为Java项目生成本机桌面安装程序。
* [Obevo](https://github.com/goldmansachs/obevo)：Obevo是一种数据库部署工具，可处理企业规模的架构和复杂性。
* [Stork](https://github.com/fizzed/stork)：Stork是一个轻量级实用程序的集合，用于通过填补Java构建系统和执行之间的空白来优化“构建后”工作流程。
* [Linux Deploy](https://github.com/meefik/linuxdeploy)：可在Android设备上快速轻松地安装操作系统(OS) GNU/Linux。
* [Artipie](https://github.com/artipie/artipie)：Artipie是一个二进制工件管理工具，类似于Artifactory、Nexus、Archiva、ProGet等。
* [CloudCaptain](https://cloudcaptain.sh/)：使用不可变基础设施的原则将JVM应用程序部署到AWS。
* [Getdown](https://github.com/threerings/getdown)：Getdown是一个用于将Java应用程序部署到最终用户计算机并保持这些应用程序最新的系统。
* [JavaPackager](https://github.com/fvarrui/JavaPackager)：JavaPackager是Maven和Gradle的混合插件，它提供了一种在本机Windows、MacOS或GNU/Linux可执行文件中打包Java应用程序并为其生成安装程序的简单方法。

<h2 id="geo">地理空间</h2>

* [WorldWindJava](https://github.com/NASAWorldWind/WorldWindJava)：美国国家航空航天局(NASA)发布的一个开源的地理科普软件，由NASA Research开发。它是一个可视化地球仪，将NASA、USGS以及其它WMS服务商提供的图像通过一个三维的地球模型展现。
* [JTS](https://github.com/locationtech/jts)：JTS是一个用于创建和操作向量几何的Java库。
* [GeoTools](https://github.com/geotools/geotools)：GeoTools是一个开源Java库，提供地理空间数据工具。
* [Geometry API](https://github.com/Esri/geometry-api-java)：Geometry API可用于在第三方数据处理解决方案中启用空间数据处理。
* [Open Location Code](https://github.com/google/open-location-code)：Open Location Code是一种将位置编码为比纬度和经度更易于使用的形式的技术，由Google开源。
* [Gisgraphy](https://github.com/gisgraphy/gisgraphy)：免费、开源且随时可用的地理编码器、反向地理编码器和地理定位网络服务。
* [GAMA](https://github.com/gama-platform/gama)：GAMA是一个易于使用的开源建模和仿真环境，用于创建基于代理的空间显式仿真。
* [MeteoInfo](https://github.com/meteoinfo/MeteoInfo)：MeteoInfo是GIS应用(MeteoInfoMap)、科学计算和可视化环境(MeteoInfoLab)的集成框架，特别适合气象界。
* [Apache SIS](https://github.com/apache/sis)：Apache SIS是一个用于开发地理空间应用程序的Java语言库，该库是OGC GeoAPI 3.0.2接口的实现，可用于桌面或服务器应用程序。
* [MapFish](https://github.com/mapfish/mapfish-print)：MapFish的一个组件，用于打印模板化地图，该模块是Java服务器端模块。
* [Geo Assist](https://github.com/thegeekyasian/geo-assist)：Geo Assist是一个用于管理内存中空间数据的空间库。
* [GraphHopper](https://github.com/graphhopper/graphhopper)：OpenStreetMap的开源路由引擎，将其用作Java库或独立的Web服务器。
* [Proj4J](https://github.com/locationtech/proj4j)：Proj4J是一个用于在不同地理空间坐标参考系之间转换坐标的Java库，它被设计为与proj.4参数兼容，并从proj.4源中派生出一些实现。
* [SLDEditor](https://github.com/sldeditor/sldeditor)：SLDEditor是由SCISYS开发的Java桌面应用程序，允许使用图形用户界面以交互方式创建和编辑OGC样式层描述符。
* [Deegree](https://github.com/deegree/deegree3)：Deegree是用于空间数据基础设施和地理空间网络的开源软件，Deegree包含地理空间数据管理组件，包括数据访问、可视化、发现和安全性。
* [Mapsforge](https://github.com/mapsforge/mapsforge)：用于Android和桌面应用的矢量地图库和编写器。
* [Tinfour](https://github.com/gwlucastrig/Tinfour)：Java中的Delaunay和约束Delaunay三角剖分，为表面建模提供高性能实用程序，支持激光雷达LAS文件、数字高程模型 (DEM)、有限元分析、路径规划、自然邻域插值以及不规则三角网络(TIN)的其他应用。
* [Geolatte-geom](https://github.com/GeoLatte/geolatte-geom)：符合OGC SQL简单功能规范的几何模型。
* [NoiseModelling](https://github.com/Universite-Gustave-Eiffel/NoiseModelling)：NoiseModelling是一个能够生成噪声图的库，它可以免费用于研究和教育，也可以由专家用于专业用途。
* [Spatial4j](https://github.com/locationtech/spatial4j)：Spatial4j是一个通用空间/地理空间开源Java库，它的核心功能有3个方面：提供可在欧几里得和测地线(球面)世界模型中工作的常见形状，提供距离计算和其他数学，以及从WKT和GeoJSON等格式读取和写入形状，Spatial4j是Eclipse基金会LocationTech行业工作组的一个项目。
* [Importer/Exporter](https://github.com/3dcitydb/importer-exporter)：基于Java的3D城市数据库导入器/导出器客户端，它允许高性能加载和提取3D城市模型数据。
* [geOrchestra](https://github.com/georchestra/georchestra)：geOrchestra是一个完整的空间数据基础设施解决方案。
* [OrbisGIS](https://github.com/orbisgis/orbisgis)：OrbisGIS是一个由研究创建并用于研究的跨平台开源地理信息系统(GIS)，它由法国Lab-STICC实验室(Vannes的DECIDE团队)内的CNRS领导。
* [GeoServer](https://github.com/geoserver/geoserver)：GeoServer是一个用Java编写的开源软件服务器，允许用户共享和编辑地理空间数据。
* [Geohash Java](https://github.com/kungfoo/geohash-java)：Geohashes的纯Java实现。
* [GeoIP2 Java](https://github.com/maxmind/GeoIP2-java)：用于GeoIP2 Web服务客户端和数据库读取器的Java API。
* [GeoFire Java](https://github.com/firebase/geofire-java)：使用Firebase进行实时位置查询的Java SDK。
* [GeoWave](https://github.com/locationtech/geowave)：GeoWave在Accumulo、HBase、BigTable、Cassandra、Kudu、Redis、RocksDB和DynamoDB之上提供地理空间和时间索引。
* [Geotoolkit](https://github.com/Geomatys/geotoolkit)：Geotoolkit是一个开源库，提供了操作制图数据的工具。
* [Photon](https://github.com/komoot/photon)：Photon是一个为OpenStreetMap数据构建的开源地理编码器。
* [geo](https://github.com/davidmoten/geo)：用于地理哈希的Java实用方法。
* [GeoGig](https://github.com/locationtech/geogig)：地理空间分布式版本控制系统。
* [GeoWebCache](https://github.com/GeoWebCache/geowebcache)：GeoWebCache是一个用Java实现的图块缓存服务器，提供各种图块缓存服务，如WMS-C、TMS、WMTS、Google Maps、MS Bing等。
* [H2GIS](https://github.com/orbisgis/h2gis)：增加了对H2的新几何类型、开放地理空间联盟(OGC)SQL简单特征(SFSQL)函数以及CNRS开发的其他空间函数的空间特征和操作管理的支持。
* [CLAVIN](https://github.com/Novetta/CLAVIN)：CLAVIN(制图位置和邻近索引器)是一个开源软件包，用于文档地理解析和地理分辨率，采用基于上下文的地理实体分辨率。
* [GeoNetwork](https://github.com/geonetwork/core-geonetwork)：GeoNetwork是一个用于管理空间参考资源的目录应用程序，它提供强大的元数据编辑和搜索功能以及交互式网络地图查看器。
* [地图瓦片图下载器](https://gitee.com/CrimsonHu/java_map_download)：使用Java开发的地图瓦片图下载工具，支持OpenStreetMap、天地图、谷歌地图、高德地图、腾讯地图、必应地图的XYZ瓦片图下载与合并。
* [GAF](https://gitee.com/supermapgaf/GAF)：基于SuperMap GIS平台，采用Spring Cloud和Vue等技术，提供权限、GIS数据、服务和二三维地图场景等功能，用于快速搭建企业级GIS微服务框架。
* [GeoDesk](https://github.com/clarisma/geodesk)：GeoDesk是一个用于OpenStreetMap数据的快速且存储高效的地理空间数据库。
* [Timeshape](https://github.com/RomanIakovlev/timeshape)：Timeshape是一个Java库，可用于确定给定地理坐标属于哪个时区。
* [Traccar](https://github.com/traccar/traccar)：GPS追踪系统。
* [Apache Sedona](https://github.com/apache/sedona)：处理大规模地理空间数据的集群计算框架。

<h2 id="serialization">序列化</h2>

* [Ysoserial](https://github.com/frohoff/ysoserial)：一种概念验证工具，用于生成利用不安全的Java对象反序列化的有效负载。
* [Apache Avro](https://github.com/apache/avro)：Apache Avro是一个数据序列化系统。
* [Protostuff](https://github.com/protostuff/protostuff)：一个Java序列化库，内置对向前向后兼容性(模式演化)和验证的支持。
* [FlatBuffers](https://github.com/google/flatbuffers)：FlatBuffers是一个跨平台序列化库，旨在实现最大内存效率，由Google开源。
* [FST](https://github.com/RuedigerMoeller/fast-serialization)：快速Java序列化下降替换。
* [Fury](https://github.com/alipay/fury)：由JIT和零拷贝支持的超快多语言序列化框架，由阿里开源。
* [MessagePack](https://github.com/msgpack/msgpack-java)：Java的MessagePack序列化器实现。
* [Serial](https://github.com/twitter/Serial)：用于Java对象序列化的轻量级快速框架，支持Android，由Twitter开源。
* [Swift](https://github.com/facebookarchive/swift)：Swift是一个易于使用、基于注解的Java库，用于创建Thrift可序列化类型和服务，由Facebook开源。
* [Ion Java](https://github.com/amazon-ion/ion-java)：Ion数据表示法的Java实现，由Amazon开源。
* [SerializationDumper](https://github.com/NickstaDB/SerializationDumper)：一种以更易于理解的形式转储和重建Java序列化流和Java RMI数据包内容的工具。
* [Colfer](https://github.com/pascaldekloe/colfer)：Colfer是一种针对速度和大小进行优化的二进制序列化格式。
* [Chronicle-Wire](https://github.com/OpenHFT/Chronicle-Wire)：支持多种格式的低垃圾Java序列化库。
* [GeoJson Jackson](https://github.com/opendatalab-de/geojson-jackson)：用于通过JSON Jackson解析器序列化和反序列化对象，该库符合2008 GeoJSON规范。
* [OpenRTB](https://github.com/google/openrtb)：该库支持OpenRTB规范，为所有protobuf支持的语言提供绑定，并为Java提供额外支持，例如JSON序列化和验证，由Google开源。
* [Reservoir](https://github.com/anupcowkur/Reservoir)：可使用键/值对轻松序列化对象并将其缓存到磁盘的Android库。
* [Eclipse Serializer](https://github.com/eclipse-serializer/serializer)：Eclipse Serializer项目可以对任何Java对象进行(反)序列化，而无需生成代码的注解、超类或接口或数据模式。

<h2 id="ioutils">IO工具类</h2>

* [Apache Commons IO](https://github.com/apache/commons-io)：Apache Commons IO库包含实用程序类、流实现、文件过滤器、文件比较器、字节序转换类等等。
* [Okio](https://github.com/square/okio/)：Okio是一个补充java.io和java.nio的库，使你可以更轻松地访问、存储和处理数据。
* [UberFire I/O](https://github.com/kiegroup/appformer/tree/main/uberfire-io)：NIO.2的实用程序/门面集。
* [JNR-UnixSocket](https://github.com/jnr/jnr-unixsocket)：Java的本机I/O访问。
* [Plexus IO](https://github.com/codehaus-plexus/plexus-io)：Plexus IO是一组Plexus组件，设计用于I/O操作。
* [OPS4J](https://github.com/ops4j/org.ops4j.base)：与java.io相关的实用程序/扩展。
* [Jaydio](https://github.com/smacke/jaydio)：Jaydio是一个Java库，可让程序员更好地控制文件I/O，部分方法是绕过操作系统缓冲区高速缓存。
* [JTar](https://github.com/kamranzafar/jtar)：JTar是一个简单的Java Tar库，它提供了一种使用IO流创建和读取tar文件的简单方法。
* [jMimeMagic](https://github.com/arimus/jmimemagic)：jMimeMagic是一个用于确定文件或流的MIME类型的Java库。
* [SimpleMagic](https://github.com/j256/simplemagic)：简单的文件幻数和内容类型库，提供文件和字节数组的MIME类型确定。
* [MimeCraft](https://github.com/square/mimecraft)：用于创建符合RFC要求的Multipart和表单编码HTTP请求主体的实用程序。
* [Ballerina MIME](https://github.com/ballerina-platform/module-ballerina-mime)：该库提供了一组用于处理消息的API，这些API遵循RFC 2045标准中指定的多用途Internet邮件扩展(MIME)规范。
* [Apache MIME4J](https://github.com/apache/james-mime4j)：Mime4j可用于解析纯rfc822和MIME格式的电子邮件消息流，并构建电子邮件消息的树表示形式。
* [MIME Type](https://github.com/overview/mime-types)：用于检测文件MIME类型的Java库。
* [Tape](https://github.com/square/tape)：Tape是Android和Java中与队列相关的类的集合。
* [Simple Binary Encoding](https://github.com/real-logic/simple-binary-encoding)：高性能消息编解码器。

<h2 id="email">邮件操作</h2>

* [Simple Java Mail](https://github.com/bbottema/simple-java-mail)：Simple Java Mail是最简单的Java轻量级邮件库，同时能够发送复杂的电子邮件，包括CLI支持、附件、嵌入图像、自定义标头和属性、强大的地址验证、构建模式甚至DKIM签名、S/MIME支持和具有属性覆盖的外部配置文件、Spring支持和电子邮件转换工具。
* [FakeSMTP](https://github.com/Nilhcem/FakeSMTP)：基于GUI的虚拟SMTP服务器，可轻松测试应用程序中的电子邮件。
* [Apache James](https://github.com/apache/james-project)：它具有基于丰富的现代高效组件的模块化架构，最终提供在JVM上运行的完整、稳定、安全和可扩展的邮件服务器。
* [Mail Utils](https://github.com/hellokaton/oh-my-email)：非常轻量的Java邮件发送类库。
* [SendGrid](https://github.com/sendgrid/sendgrid-java)：该库允许你通过Java快速轻松地使用Twilio SendGrid Web API v3。
* [Fake SMTP Server](https://github.com/gessnerfl/fake-smtp-server)：用于测试目的的简单SMTP服务器，电子邮件存储在内存数据库中并呈现在Web UI中。
* [Mailgun](https://github.com/sargue/mailgun)：使用Mailgun服务轻松发送电子邮件的Java库。
* [Apache Commons Email](https://github.com/apache/commons-email)：Apache Commons Email提供用于发送电子邮件的API，它构建在JavaMail API之上，旨在简化JavaMail API。
* [JMail](https://github.com/RohanNagar/jmail)：一个现代、快速、零依赖的库，用于在Java中处理电子邮件地址并执行电子邮件地址验证。
* [Jakarta Mail](https://github.com/jakartaee/mail-api)：Jakarta Mail定义了一个独立于平台和协议的框架来构建邮件和消息传递应用程序。
* [Angus Mail](https://github.com/eclipse-ee4j/angus-mail)：该项目提供了Jakarta Mail规范2.1+的实现。
* [TrashEmail](https://github.com/rosehgal/TrashEmail)：托管的一次性电子邮件电报机器人，对隐私极其友好；
* [exJello](https://code.google.com/archive/p/exjello/)：exJello是一个连接到Microsoft Exchange服务器的JavaMail提供程序，它被设计为标准POP3和SMTP提供商的直接替代品。
* [DKIM](https://www.agitos.de/dkim-for-javamail/)：DKIM是一个开源库，允许你使用域名密钥标识邮件(DKIM)对邮件进行签名。
* [Jack Mail](https://sourceforge.net/projects/jackmailclient/)：Jack Mail Client是一个简单的邮件客户端，可以以最少的配置使用任何邮件服务器。
* [Aspirin](https://github.com/masukomi/aspirin)：Aspirin是一个供Java开发人员使用的嵌入式仅发送SMTP服务器。
* [Tawebmail](https://yawebmail.sourceforge.net/)：yawebmail是一个用Java编写的网络邮件客户端，作为一个Web应用程序，它支持SMTP(包括SMTP身份验证)、POP3和IMAP。
* [Aperture](https://aperture.sourceforge.net/)：Aperture是一个Java框架，用于从各种信息系统(例如文件系统、网站、邮箱)以及这些系统中出现的文件格式(例如文档、图像)中提取和查询全文内容和元数据。
* [JMBox](https://sourceforge.net/projects/jmbox/)：jmbox项目使开发人员能够使用JavaMail API来管理存储在本地存储库(如Outlook Express、Mozilla、Netscape等)中的邮件。
* [JavaMail Crypto](http://javamail-crypto.sourceforge.net/)：JavaMail-Crypto是一个简单、易于使用的API，它提供了使用JavaMail访问OpenPGP和S/MIME加密功能的统一方法。

<h2 id="rss">RSS</h2>

* [Rome](https://github.com/rometools/rome)：用于RSS和Atom提要的Java库。
* [CommaFeed](https://github.com/Athou/commafeed)：CommaFeed是受Google Reader启发而开发的自托管RSS阅读器，基于Dropwizard和React/TypeScript。
* [Android-RSS](https://github.com/ahorn/android-rss)：用于解析RSS 2.0提要的轻量级Android库。
* [Sismics Reader](https://github.com/sismics/reader)：Reader是一个开源的、基于Web的内容聚合器，由Web Feeds(RSS、Atom)提供服务。
* [RSSOwl](https://github.com/rssowl/RSSOwl)：RSS Owl是一个功能强大的应用程序，可以以舒适的方式组织、搜索和阅读RSS、RDF和Atom新闻源。
* [RSS Recipes](https://github.com/Netflix/recipes-rss)：使用多个Netflix OSS组件的RSS阅读器食谱。
* [Apache Uniffle](https://github.com/apache/incubator-uniffle)：Uniffle是一种用于分布式计算引擎的高性能、通用远程洗牌服务。
* [RSS Reader](https://github.com/w3stling/rssreader)：RSS Reader是一个简单的Java库，用于读取RSS和Atom提要。

<h2 id="osgi">OSGI</h2>

* [Distributed Data Framework](https://github.com/codice/ddf)：DDF是一个开源、模块化的集成框架。
* [Apache ServiceMix](https://github.com/apache/servicemix)：Apache ServiceMix是一个灵活的开源集成容器，它将Apache ActiveMQ、Camel、CXF和Karaf的特性和功能成为一个强大的运行时平台，你可以使用它来构建自己的集成解决方案。它提供了一个完全由OSGi提供支持的企业级ESB。
* [Apache Karaf](https://github.com/apache/karaf)：Karaf提供了一个轻量级的OSGi容器，可以用于部署各种组件。
* [OPS4j Pax Web](https://github.com/ops4j/org.ops4j.pax.web)：Pax Web通过更好的Servlet支持、过滤器、监听器、错误页面和JSP等扩展了OSGi HTTP服务，以满足最新版本的Servlet规范。
* [Bnd](https://github.com/bndtools/bnd)：用于构建OSGi包的工具，包括Eclipse、Maven和Gradle插件。
* [OSGi enRoute](https://github.com/osgi/osgi.enroute)：OSGi enRoute项目提供了OSGi应用程序的编程模型，该项目包含为OSGi enRoute基本配置文件提供API的捆绑包和用于OSGi enRoute项目的捆绑包。

<h2 id="validation">校验</h2>

* [Hibernate Validator](https://github.com/hibernate/hibernate-validator)：Jakarta Bean Validation参考实现。
* [Cron Utils](https://github.com/jmrozanec/cron-utils)：用于解析、验证和人类可读描述以及日期/时间互操作性的Cron实用程序。
* [Fluent Validator](https://github.com/neoremind/fluent-validator)：利用流式的接口风格和JSR 303规范的Java验证框架。
* [JSON Schema Validator](https://github.com/everit-org/json-schema)：用于Java的JSON模式验证器，基于org.json API。
* [YAVI](https://github.com/making/yavi)：基于Lambda的类型安全验证框架。
* [iban4j](https://github.com/arturmkrtchyan/iban4j)：用于生成和验证国际银行帐号(IBAN ISO_13616)和企业标识符代码(BIC ISO_9362)的Java库。
* [LibPhoneNumber](https://github.com/google/libphonenumber)：Google的通用Java、C++和JavaScript库，用于解析、格式化和验证国际电话号码。
* [Apache Commons Validator](https://github.com/apache/commons-validator)：Apache开源的通用数据验证框架。
* [Java Fluent Validator](https://github.com/mvallim/java-fluent-validator)：在Java语言中定义了一个内部DSL供程序员使用。
* [DSS](https://github.com/esig/dss)：数字签名服务：高级电子签名的创建、扩展和验证。
* [Backstopper](https://github.com/Nike-Inc/backstopper)：Backstopper是一个与框架无关的API错误处理和(可选)模型验证解决方案，适用于Java 7及更高版本，由Nike开源。
* [veraPDF](https://github.com/veraPDF/veraPDF-library)：行业支持的开源PDF/A验证库。
* [CSS Validator](https://github.com/w3c/css-validator)：W3C CSS验证服务。
* [Galimatias](https://github.com/smola/galimatias)：galimatias是一个用Java编写的URL解析和规范化库。
* [JHOVE](https://github.com/openpreserve/jhove)：JHOVE是一个可扩展的软件框架，用于执行数字对象的格式识别、验证和表征，由哈佛大学开发。
* [Coody Verification](https://gitee.com/coodyer/coody-verification)：一款反射+注解实现的参数自动化校验工具。
* [Apache BVal](https://bval.apache.org/)：Apache BVal提供了Java Bean Validation规范的实现，适用于Java 8或更高版本。
* [JBVE](https://github.com/nomemory/java-bean-validation-extension)：JBVE(Java Bean Validation Extension)是一个小型工具库，它通过额外注解扩展了Java Bean Validation规范。
* [Collection Validator](https://github.com/jirutka/validator-collection)：该库可以轻松地为任何验证约束创建“伪约束”(通常命名为@EachX)来标注简单类型的集合，而无需为每个集合编写额外的验证器或不必要的包装类。
* [dOOv](https://github.com/doov-org/doov)：dOOv是一个用于类型安全域模型验证和映射的流式API。
* [OVal](https://sourceforge.net/projects/oval/)：一个实用且可扩展的验证框架，适用于任何类型的Java对象。不符合JSR 303/JSR 380，但支持Bean验证约束。

<h2 id="ast">词法解析</h2>

* [ANTLR](https://github.com/antlr/antlr4)：ANTLR是一个强大的解析器生成器，用于读取、处理、执行或翻译结构化文本或二进制文件。
* [JavaParser](https://github.com/javaparser/javaparser)：该项目包含一组实现具有高级分析功能的Java 1.0 - Java 17解析器的库。
* [Piranha](https://github.com/uber/piranha)：用于重构与功能标志API相关的代码的工具，由Uber开源。
* [Flexmark Java](https://github.com/vsch/flexmark-java)：flexmark-java是CommonMark(规范0.28)解析器的Java实现，使用块优先、内联后Markdown解析架构。
* [kotlinx.ast](https://github.com/kotlinx/ast)：kotlinx.ast是一个通用的AST(抽象语法树)解析库，Kotlin是目前唯一支持的语言。
* [Gumtree Spoon AST Diff](https://github.com/SpoonLabs/gumtree-spoon-ast-diff)：使用Gumtree算法计算两个Spoon抽象语法树之间的AST差异。
* [JSqlParser](https://github.com/JSQLParser/JSqlParser)：JSqlParser解析SQL语句并将其转换为Java类的层次结构，可以使用访问者模式来导航生成的层次结构。
* [JavaCC](https://github.com/javacc/javacc)：JavaCC是用于Java应用程序的最流行的解析器生成器。
* [JFlex](https://github.com/jflex-de/jflex)：JFlex是Java的词法分析器生成器(也称为扫描器生成器)。

<h2 id="formal-verification">形式验证</h2>

* [CATG](https://github.com/ksen007/janala2)：Concolic单元测试引擎，使用形式化方法自动生成单元测试。
* [Checker Framework](https://checkerframework.org/)：可插拔类型系统，包括空类型、物理单位、不变性类型等等。
* [Daikon](https://plse.cs.washington.edu/daikon/)：检测可能的程序不变量并根据这些不变量生成JML规范。
* [Java PathFinder](https://github.com/javapathfinder/jpf-core)：JVM形式验证工具，包含模型检查器等，由NASA开源。
* [JmlOk2](https://massoni.computacao.ufcg.edu.br/home/jmlok)：通过反馈引导的随机测试生成来检测代码和JML规范之间的不一致，并建议检测到的每个不符合项的可能原因。
* [KeY](https://github.com/KeYProject/key)：形式化软件开发工具，旨在尽可能无缝地集成面向对象软件的设计、实现、形式化规范和形式化验证。
* [OpenJML](https://github.com/OpenJML/OpenJML)：OpenJML是Java程序的程序验证工具，可让你检查以Java建模语言注释的程序规范。

<h2 id="regex">正则表达式</h2>

* [RegexGenerator](https://github.com/MaLeLabTs/RegexGenerator)：该项目包含用于生成文本提取正则表达式的工具的源代码。
* [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions)：VerbalExpressions是一个Java库，可帮助构建困难的正则表达式。
* [Generex](https://github.com/mifmif/Generex)：用于生成与给定正则表达式匹配的字符串的Java库。
* [RE2/J](https://github.com/google/re2j)：RE2是一个正则表达式引擎，其运行时间与输入大小成线性关系，由Google开源。

<h2 id="codegen">代码生成器</h2>

* [Auto](https://github.com/google/auto)：一系列用于Java的源代码生成器，由Google开发。
* [Joda-Beans](https://github.com/JodaOrg/joda-beans)：Joda-Beans提供了一个向Java添加属性的小型框架，极大地增强了Java Bean。
* [Burningwave](https://github.com/burningwave/core)：一个先进且高度优化的Java库，用于构建框架：它对于扫描类路径、在运行时生成类、促进反射的使用、扫描文件系统、执行字符串化源代码等等很有用。
* [JavaPoet](https://github.com/square/javapoet)：用于生成.java源文件的Java API。
* [Java::Geci](https://github.com/verhas/javageci)：Java::Geci是一个用于生成Java代码的库，可以使用Java::Geci执行代码生成程序来生成新的源代码或修改现有的Java源文件。
* [Avaje-HTTP](https://github.com/avaje/avaje-http)：Javalin、Helidon SE的控制器生成器。
* [Fulib](https://github.com/fujaba/fulib)：Fulib是一个为UML类模型和一些模型管理功能提供代码生成的库，使用Java API提供的特定于域的语言，它允许你定义类、属性以及与元模型的关联。
* [ADT4J](https://github.com/sviperll/adt4j)：该库为Java实现了代数数据类型。
* [AutoRecord](https://github.com/pawellabaj/auto-record)：AutoRecord是一个代码生成器，可以帮助你轻松生成Java记录。
* [MAKU](https://gitee.com/makunet/maku-generator)：一款低代码生成器，可根据自定义模板内容，快速生成代码，可实现项目的快速开发、上线，减少重复的代码编写。
* [Mybatis Generator](https://github.com/mybatis/generator)：用于Mybatis的代码生成器。
* [MybatisPlus Generator](https://github.com/baomidou/generator)：用于MybatisPlus的代码生成器。
* [Sculptor](https://github.com/sculptor/sculptor)：Sculptor是一个代码生成器，应用了领域驱动设计和领域特定语言的概念。
* [Bootify](https://bootify.io/)：使用JPA模型和REST API生成基于浏览器的Spring Boot应用程序，商业项目。
* [Code Gen](https://gitee.com/durcframework/code-gen)：一款代码生成工具，可自定义模板生成不同的代码，支持MySQL、Oracle、SQL Server、PostgreSQL。
* [AiCode](https://gitee.com/lemur/aicode)：新一代代码生成器，根据模板配置生成代码。

<h2 id="ladp">目录服务</h2>

* [PWM](https://github.com/pwm-project/pwm)：PWM是一个用于LDAP目录的开源密码自助服务应用程序。
* [DavMail](https://github.com/mguessan/davmail)：POP/IMAP/SMTP/Caldav/Carddav/LDAP Exchange和Office 365网关。
* [Spring LDAP](https://github.com/spring-projects/spring-ldap)：Spring LDAP是一个用于简化Java LDAP编程的库，其构建原理与Spring JDBC相同。
* [UnboundID LDAP SDK](https://github.com/pingidentity/ldapsdk)：UnboundID LDAP SDK是一个快速、功能强大、用户友好且完全免费的开源Java库，用于与LDAP目录服务器进行通信。
* [Apache DS](https://github.com/apache/directory-server)：Apache DS是一个完全用Java编写的可扩展、可嵌入的目录服务器，已通过Open Group认证，兼容LDAPv3。
* [OpenDJ Community Edition](https://github.com/ForgeRock/opendj-community-edition)：OpenDJ是一个目录服务器，它实现了广泛的轻量级目录访问协议和相关标准，包括完全符合LDAPv3，而且还支持目录服务标记语言(DSMLv2)。
* [Apache Directory Kerby](https://github.com/apache/directory-kerby)：Apache Directory子项目，是Java Kerberos绑定。它提供了丰富、直观且可互操作的实现、库、KDC和各种设施，根据云、Hadoop和移动等现代环境的需要集成了PKI、OTP和令牌(OAuth2)。
* [Apache Directory Studio](https://github.com/apache/directory-studio)：Apache Directory Studio是一个完整的目录工具平台，旨在与任何LDAP服务器一起使用，但它是专门为与ApacheDS一起使用而设计的。
* [Rogue JNDI](https://github.com/veracode-research/rogue-jndi)：用于JNDI注入攻击的恶意LDAP服务器。
* [Spring Data LDAP](https://github.com/spring-projects/spring-data-ldap)：Spring Data LDAP项目旨在为Spring LDAP提供熟悉且一致的存储库抽象。
* [OpenDJ](https://github.com/OpenIdentityPlatform/OpenDJ)：OpenDJ是一种兼容LDAPv3的目录服务，专为Java平台开发，可为组织管理的身份提供高性能、高可用性且安全的存储。