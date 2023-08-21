# Java生态资源大全

本项目统计了Java生态圈中的各种资源，包括库、框架、学习网站，并且按照其所属的领域进行了分类，方便大家查找。

## 测试

这里主要是一些测试框架和工具库，包括单元测试、集成测试、性能测试等。

#### 单元测试

* [JUnit 4](https://github.com/junit-team/junit4)：Java的单元测试框架。
* [JUnit 5](https://github.com/junit-team/junit5)：JUnit的全新版本框架。
* [TestNG](https://github.com/testng-team/testng)：TestNG测试框架。
* [Spock](https://github.com/spockframework/spock)：基于Groovy的测试框架，支持数据驱动、Mock等功能。
* [Robolectric](https://github.com/robolectric/robolectric)：一个Android的单元测试框架。
* [Kotest](https://github.com/kotest/kotest)：强大、优雅且灵活的Kotlin测试框架，具有额外的断言、属性测试和数据驱动测试功能。
* [TestFX](https://github.com/TestFX/TestFX)：用于JavaFX的单元测试框架。
* [scalatest](https://github.com/scalatest/scalatest)：面向Scala和Java开发人员的测试工具。
* [utest](https://github.com/com-lihaoyi/utest)：用于Scala的测试框架。
* [munit](https://github.com/scalameta/munit)：具有可操作错误和可扩展API的Scala测试库。

#### 断言库

* [AssertJ](https://github.com/assertj/assertj)：AssertJ是一个提供易于使用的丰富类型断言的库。
* [JsonAssert](https://github.com/skyscreamer/JSONassert)：用更少的代码编写JSON单元测试，非常适合测试REST接口。
* [Truth](https://github.com/google/truth)：Google出品的流式断言库。
* [Hamcrest](https://github.com/hamcrest/JavaHamcrest)：Hamcrest的Java版本。
* [BeanMatcher](https://github.com/orien/bean-matchers)：用于测试Java bean的Hamcrest匹配器。
* [Deepdive](https://github.com/jdlib/deepdive)：Java的流式断言库。
* [Fest](https://github.com/alexruiz/fest-assert-2.x)：流式断言库。
* [expekt](https://github.com/winterbe/expekt): Kotlin的BDD断言库。

#### Mock框架

* [Mockito](https://github.com/mockito/mockito)：Java中最热门的Mock框架。
* [PowerMock](https://github.com/powermock/powermock)：一个扩展Mockito的框架，支持Mock静态方法、构造函数、私有方法等。
* [Testable-Mock](https://github.com/alibaba/testable-mock)：Alibaba开发的Mock框架。
* [WireMock](https://github.com/wiremock/wiremock)：一个模拟HTTP服务的工具。
* [EasyMock](https://github.com/easymock/easymock)：一个比较古老的Mock库。
* [Mockk](https://github.com/mockk/mockk)：用于Kotlin的Mock框架。
* [ScalaMock](https://github.com/paulbutcher/ScalaMock)：原生Scala  Mock框架。
* [MockServer](https://github.com/mock-server/mockserver)：MockServer可以轻松模拟通过HTTP或HTTPS与用Java、JavaScript和Ruby编写的客户端集成的任何系统。
* [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver)：用于测试HTTP客户端的可编写脚本的Web服务器。
* [Jukito](https://github.com/ArcBees/Jukito)：JUnit、Guice和Mockito的组合。
* [JMockit](https://github.com/jmockit/jmockit1)：用于集成测试、Mock、伪造和代码覆盖率的高级Java库。
* [MockBukkit](https://github.com/MockBukkit/MockBukkit)：MockBukkit是bukkit的Mock框架，可以轻松地对Bukkit插件进行单元测试。

### Mock工具

* [Moco](https://github.com/dreamhead/moco)：设置存根服务器。
* [RabbitMQ Mock](https://github.com/fridujo/rabbitmq-mock)：RabbitMQ的Mock库。
* [flashback](https://github.com/linkedin/flashback)：Flashback旨在模拟HTTP和HTTPS资源(例如Web服务和REST API)以用于测试目的。
* [S3Mock](https://github.com/adobe/S3Mock)：AWS S3 API的简单Mock实现，可作为Docker镜像、TestContainer、JUnit 4 Rule、JUnit Jupiter扩展或TestNG监听器启动。
* [CastleMock](https://github.com/castlemock/castlemock)：CastleMock是一个Web应用程序，提供模拟RESTful API和SOAP Web Service的功能。
* [restito](https://github.com/mkotsur/restito)：用于测试Rest客户端的Mock框架。

#### 数据Mock

* [Instancio](https://github.com/instancio/instancio)：为单元测试创建完全填充的对象的库。
* [Junit Data Provider](https://github.com/TNG/junit-dataprovider)：类似TestNG的JUnit数据提供者运行程序，具有许多附加功能。
* [DataFaker](https://github.com/datafaker-net/datafaker)：为JVM(Java、Kotlin、Groovy)生成测试数据的库。
* [Java Faker](https://github.com/DiUS/java-faker)：将流行的ruby faker gem带到Java。
* [MockNeat](https://github.com/nomemory/mockneat)：现代的测试数据生成库。
* [jfairy](https://github.com/Devskiller/jfairy)：Java测试数据生成器。
* [EasyRandom](https://github.com/j-easy/easy-random)：简单的随机Java beans/记录生成器。
* [Jmockdata](https://github.com/jsonzou/jmockdata)：生成随机Java数据的插件。
* [JMock](https://github.com/jmock-developers/jmock-library)：用于测试驱动开发的富有表现力的对象Mock库。
* [burst](https://github.com/square/burst)：用于不同测试数据的单元测试库。
* [EasyModeling](https://github.com/easymodeling/easy-modeling)：EasyModeling是一个Java注解处理器，可生成随机填充的对象以供测试使用。

#### BDD框架

* [Cucumber](https://github.com/cucumber/cucumber-jvm)：JVM上的Cucumber实现。
* [Karate](https://github.com/karatelabs/karate)：一个BDD框架，支持API测试、UI测试、Mock等。
* [Serenity](https://github.com/serenity-bdd/serenity-core)：Serenity BDD是一个测试自动化库，旨在使编写自动化验收测试变得更容易、更有趣。
* [Concordion](https://github.com/concordion/concordion)：Concordion是一个Java开源框架，可让你将需求的简单英语描述转变为自动化测试。它通常与示例需求说明(SbE)和行为驱动开发(BDD)流程一起使用。
* [yaks](https://github.com/citrusframework/yaks)：YAKS是一个在Kubernetes上启用云原生BDD测试的平台。
* [JBehave](https://github.com/jbehave/jbehave-core)：JBehave是一个适用于Java和所有JVM语言Groovy、Kotlin、Ruby、Scala的BDD框架。
* [JGiven](https://github.com/TNG/JGiven)：用纯Java进行行为驱动开发的框架。
* [Chorus](https://github.com/Chorus-bdd/Chorus)：分布式系统的可执行规范。
* [Lambda Behave](https://github.com/RichardWarburton/lambda-behave)：Java 8的现代测试和行为规范框架。
* [Spectrum](https://github.com/greghaskins/spectrum)：适用于Java 8的BDD风格测试运行器。受Jasmine、RSpec和Cucumber启发。

#### 自动化工具

* [Selenium](https://github.com/SeleniumHQ/selenium)：浏览器自动化框架和生态系统。
* [Playwright](https://github.com/microsoft/playwright-java)：Java版本的Playwright测试和自动化库。
* [Selenide](https://github.com/selenide/selenide)：Selenium的封装，提供了更简洁的API。
* [WebDriverManager](https://github.com/bonigarcia/webdrivermanager)：Java中Selenium WebDriver的自动化驱动程序管理和其他辅助工具。
* [ashot](https://github.com/pazone/ashot)：WebDriver屏幕截图工具。
* [Allure](https://github.com/allure-framework/allure2)：一款灵活、轻量级的多语言测试报告工具。
* [FitNesse](https://github.com/unclebob/fitnesse)：一个验收测试工具。
* [SoapUI](https://github.com/SmartBear/soapui)：免费、开源的跨平台API和Web Service功能测试解决方案。
* [Galen](https://github.com/galenframework/galen)：一个自动化的布局和页面响应测试框架。
* [FluentLenium](https://github.com/FluentLenium/FluentLenium)：FluentLenium是一个Web和移动自动化框架，它扩展了Selenium以编写可靠且有弹性的UI功能测试。
* [Citrus](https://github.com/citrusframework/citrus)：专注于消息集成的自动化集成测试框架。
* [Webtau](https://github.com/testingisdocumenting/webtau)：WebTau(Web测试自动化)是一个测试API、命令行工具和一个用于编写单元、集成和端到端测试的框架。
* [SeLion](https://github.com/paypal/SeLion)：自动化测试工具。
* [jdi-light](https://github.com/jdi-testing/jdi-light)：Java中强大的UI自动化测试框架。
* [ZeroCode](https://github.com/authorjapps/zerocode)：社区开发的免费开源微服务API自动化和负载测试框架，使用JUnit核心运行程序构建，适用于Http REST、SOAP、安全性、数据库、Kafka等。
* [SoloPi](https://github.com/alipay/SoloPi)：SoloPi是一个无线化、非侵入式的Android自动化工具。
* [rest-client](https://github.com/wisdom-projects/rest-client)：测试REST API的自动化工具，可以生成精美的测试报告和REST API文档。
* [rest-client](https://github.com/wiztools/rest-client)：用于测试HTTP/RESTful WebService的工具。
* [opentest](https://github.com/mcdcorp/opentest)：适用于Web应用程序、移动应用程序和API的开源测试自动化工具。

#### 负载测试

* [JMeter](https://github.com/apache/jmeter)：Apache出品的GUI形式的开源负载测试工具。
* [Ngrinder](https://github.com/naver/ngrinder)：企业级性能测试解决方案。
* [Gatling](https://github.com/gatling/gatling)：更现代的负载测试工具，以代码的方式编写测试用例。

#### 其他库

* [Testcontainers](https://github.com/testcontainers/testcontainers-java)：一个用于在测试中启动Docker容器的库。
* [Rest Assured](https://github.com/rest-assured/rest-assured)：一个用于测试REST API的库。
* [ArchUnit](https://github.com/TNG/ArchUnit)：Java架构测试库，用于以纯Java指定和断言架构规则。
* [Pitest](https://github.com/hcoles/pitest)：最先进的JVM突变测试库。
* [Awaitility](https://github.com/awaitility/awaitility)：用于测试异步代码的库。
* [Microcks](https://github.com/microcks/microcks)：用于模拟和测试API和微服务的Kubernetes原生工具。
* [Embedded Redis](https://github.com/kstyrc/embedded-redis)：用于Java集成测试的Redis嵌入式服务器。
* [JsonUnit](https://github.com/lukas-krecan/JsonUnit)：用于比较JSON的库。
* [EqualsVerifier](https://github.com/jqno/equalsverifier)：EqualsVerifier可用于Java单元测试来验证equals和hashCode方法的约定是否得到满足。
* [Database-Rider](https://github.com/database-rider/database-rider)：让数据库集成测试变得更简单的库。
* [Jqwik](https://github.com/jqwik-team/jqwik)：JUnit平台上基于属性的测试库。
* [Fixture Monkey](https://github.com/naver/fixture-monkey)：可以自动生成包括边缘情况的测试实例。
* [OpenTest4J](https://github.com/ota4j-team/opentest4j)：JVM开放测试联盟。
* [randomizedtesting](https://github.com/randomizedtesting/randomizedtesting)：随机测试工具。
* [XmlUnit](https://github.com/xmlunit/xmlunit)：XMLUnit是一个支持以多种方式测试XML输出的库。
* [JUnit Pioneer](https://github.com/junit-pioneer/junit-pioneer)：JUnit 5扩展包，提供很多JUnit 5没有的Extension。
* [System Rules](https://github.com/stefanbirkner/system-rules)：用于测试使用java.lang.System的代码的JUnit Rule集合。
* [System Lambda](https://github.com/stefanbirkner/system-lambda)：用于测试使用java.lang.System的代码的函数集合。
* [System Stubs](https://github.com/webcompere/system-stubs)：Java系统资源的测试替身。
* [GreenMail](https://github.com/greenmail-mail-test/greenmail)：GreenMail是一个邮件服务器Mock库，允许开发人员测试基于电子邮件的应用程序、服务或系统，而无需访问实时邮件服务器。
* [Arquillian](https://github.com/arquillian/arquillian-core)：Arquillian提供了用于集成测试的组件模型，其中包括依赖注入和容器生命周期管理。
* [MicroShed](https://github.com/MicroShed/microshed-testing)：用于黑盒测试MicroProfile和Jakarta EE应用程序的测试框架。
* [JGotesting](https://github.com/tastapod/jgotesting)：受Go测试包启发的JUnit兼容测试工具。
* [Pact](https://github.com/pact-foundation/pact-jvm)：Pact的JVM版本，用于编写消费者驱动的契约测试。
* [wasabi](https://github.com/intuit/wasabi)：A/B测试工具，不再处于开发状态。
* [evosuite](https://github.com/EvoSuite/evosuite)：自动生成Java类的JUnit测试套件。
* [QuickTheories](https://github.com/quicktheories/QuickTheories)：Java 8基于属性的测试。
* [jwebunit](https://github.com/JWebUnit/jwebunit)：Java Web测试框架。
* [scalacheck](https://github.com/typelevel/scalacheck)：Scala基于属性的测试。

## Web框架

* [Spring MVC](https://github.com/spring-projects/spring-framework/tree/main/spring-webmvc)：Spring MVC是Spring生态中的Web框架。
* [Spring Boot](https://github.com/spring-projects/spring-boot)：用于快速开发Spring应用的脚手架框架。
* [Solon](https://github.com/noear/solon)：国产的轻量级Java Web框架。
* [Play](https://github.com/playframework/playframework)：Play框架结合了生产力和性能，可以轻松使用Java和Scala构建可扩展的Web应用程序。
* [Blade](https://github.com/lets-blade/blade)：国产的轻量级Web框架。
* [JFinal](https://github.com/jfinal/jfinal)：国产的Web、ORM框架。
* [Javalin](https://github.com/javalin/javalin)：简单而现代的Java和Kotlin Web框架。
* [Hilla](https://github.com/vaadin/hilla)：Java全栈框架，支持React和Lit/Web组件。
* [Ninja](https://github.com/ninjaframework/ninja)：Java的全栈Web框架。
* [Sofa-Boot](https://github.com/sofastack/sofa-boot)：蚂蚁开发的Spring Boot增强并与其完全兼容的框架，提供就绪性检查、类隔离等功能。
* [Grails](https://github.com/grails/grails-core)：Grails是一个用于使用Groovy编程语言构建Web应用程序的框架。
* [Vaadin](https://github.com/vaadin/framework)：Vaadin是用于现代Java Web应用程序的Java框架。
* [Jooby](https://github.com/jooby-project/jooby)：适用于Java和Kotlin的模块化Web框架。
* [Pippo](https://github.com/pippo-java/pippo)：Java开源的微型Web框架。
* [Spark](https://github.com/perwendel/spark)：一个简单的、富有表现力的Java Web框架。
* [Wicket](https://github.com/apache/wicket)：基于组件的Java Web框架。
* [Rife2](https://github.com/rife2/rife2)：全栈、无声明框架，可使用现代Java快速轻松地创建Web应用程序。
* [Tapestry](https://github.com/apache/tapestry-5)：Tapestry是一个面向组件的Java Web应用程序框架。
* [Ratpack](https://github.com/ratpack/ratpack)：一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [GWT](https://github.com/gwtproject/gwt)：快速构建和维护复杂但性能高的JavaScript前端应用程序的工具集。
* [Struts](https://github.com/apache/struts)：Apache Struts框架是一个用于创建Java Web应用程序的免费开源解决方案。
* [JavaLite](https://github.com/javalite/javalite)：一系列工具的集合框架。
* [Vraptor4](https://github.com/caelum/vraptor4)：一个基于Action的Web MVC框架，构建于CDI之上，用于快速且可维护的Java开发。
* [Takes](https://github.com/yegor256/takes)：面向对象的Java Web框架，没有NULL、静态方法、注解和可变对象。

## Rest框架

* [Jersey](https://github.com/eclipse-ee4j/jersey)：Jersey是一个Eclipse基金会下的REST框架，提供JAX-RS等参考实现。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：一个非常简单的库，用于构建生产就绪的RESTful Web服务。
* [Resteasy](https://github.com/resteasy/resteasy)：Jakarta RESTful Web服务规范的实现。
* [Bootique](https://github.com/bootique/bootique)：Bootique是一种最简单的Java启动器和集成技术，它旨在构建无容器的可运行Java应用程序。
* [Restx](https://github.com/restx/restx)：轻量级Java REST框架。
* [Restlet](https://github.com/restlet/restlet-framework-java)：Java REST API框架。
* [Rest.li](https://github.com/linkedin/rest.li)：领英开源的REST+JSON框架，用于使用动态发现和简单的异步API构建健壮、可扩展的服务架构。
* [Grumpyrest](https://github.com/MartinGeisse/grumpyrest)：没有注解/DI/响应式的Java REST框架。
* [Resty](https://github.com/Dreampie/Resty)：极简的REST框架。
* [RestExpress](https://github.com/RestExpress/RestExpress)：用于快速创建可扩展、Containerless、RESTful微服务的极简Java框架。

## 微服务框架

* [Spring Cloud](https://spring.io/projects/spring-cloud)：Spring生态中的微服务框架。
* [Dubbo](https://github.com/apache/dubbo)：阿里开源的RPC和微服务框架。
* [Micronaut](https://github.com/micronaut-projects/micronaut-core)：JVM平台上的微服务框架。
* [Quarkus](https://github.com/quarkusio/quarkus)：云原生时代的Java微服务框架。
* [Helidon](https://github.com/helidon-io/helidon)：用于编写微服务的Java库。
* [Spring Cloud Alibaba](https://github.com/alibaba/spring-cloud-alibaba)：阿里开源的Spring Cloud框架，提供一站式的微服务应用开发解决方案。
* [Spring Cloud GCP](https://github.com/GoogleCloudPlatform/spring-cloud-gcp)：集成了Google云功能的Spring Cloud框架，由Google提供。
* [Spring Cloud Tencent](https://github.com/Tencent/spring-cloud-tencent)：Spring Cloud Tencent是腾讯提供的基于Spring Cloud的服务治理框架。
* [Spring Cloud Azure](https://github.com/microsoft/spring-cloud-azure)：Spring Cloud Azure是微软开发的Spring Cloud框架，提供Spring与 Azure服务的无缝集成。
* [Spring Cloud AWS](https://github.com/awspring/spring-cloud-aws)：亚马逊提供的Spring Cloud框架。
* [JHipster](https://github.com/jhipster/generator-jhipster)：JHipster是一个用于快速生成、开发和部署现代Web应用程序和微服务架构的开发平台。
* [Ktor](https://github.com/ktorio/ktor)：Ktor是一个Kotlin编写的用于创建微服务、Web应用程序等的异步框架。
* [MicroProfile](https://github.com/eclipse/microprofile)：MicroProfile是一个Eclipse基金会项目，用于将Jakarta EE等企业Java技术应用于分布式微服务体系结构并不断发展。
* [ServiceComb](https://github.com/apache/servicecomb-java-chassis)：ServiceComb是一个软件开发套件，用于快速开发Java微服务。
* [Axon](https://github.com/AxonFramework/AxonFramework)：JVM上的演化消息驱动微服务框架。
* [Lagom](https://github.com/lagom/lagom)：JVM平台上的响应式微服务框架。
* [Armeria](https://github.com/line/armeria)：适用于任何情况的首选微服务框架，来自Netty创始人。你可以利用你喜欢的技术构建任何类型的微服务，包括gRPC、Thrift、Kotlin、Retrofit、Reactive Stream、Spring Boot和Dropwizard。
* [Light-4j](https://github.com/networknt/light-4j)：快速、轻量级且更高效的微服务框架。
* [JClouds](https://github.com/apache/jclouds)：Apache jclouds是一个适用于Java平台的开源多云工具包，可让你自由地创建可跨云移植的应用程序，同时让你完全控制使用特定于云的功能。
* [Msf4j](https://github.com/wso2/msf4j)：适用于Java的WSO2微服务框架。
* [NutzBoot](https://github.com/nutzam/nutzboot)：可靠的企业级微服务框架，提供自动配置、嵌入式Web服务、分布式会话、服务治理、负载均衡、hystrix、RPC等解决方案。

## ORM框架

* [Hibernate](https://github.com/hibernate/hibernate-orm)：老牌ORM框架。
* [Spring Data JPA](https://github.com/spring-projects/spring-data-jpa)：Spring生态中的JPA框架。
* [Mybatis](https://github.com/mybatis/mybatis-3)：Java的MyBatis SQL映射器框架。
* [Mybatis-Plus](https://github.com/baomidou/mybatis-plus)：国产Mybatis的封装框架。
* [Mybatis-Flex](https://github.com/mybatis-flex/mybatis-flex)：国产Mybatis增强框架。
* [Fluent-Mybatis](https://github.com/atool/fluent-mybatis)：国产Mybatis的封装框架。
* [EclipseLink](https://github.com/eclipse-ee4j/eclipselink)：Eclipse基金会下的JPA实现。
* [OpenJPA](https://github.com/apache/openjpa)：Apache基金会下的JPA实现。
* [APIJSON](https://github.com/Tencent/APIJSON)：腾讯开源的ORM库。
* [Blaze](https://github.com/Blazebit/blaze-persistence)：Blaze-Persistence是面向JPA提供程序的丰富Criteria API。
* [QueryDSL](https://github.com/querydsl/querydsl)：Querydsl是一个可以为多个后端(包括JPA、MongoDB和Java中的SQL)构建类型安全的类SQL查询的框架。
* [JOOQ](https://github.com/jOOQ/jOOQ)：jOOQ是一个内部DSL和源代码生成器，将SQL语言建模为类型安全的Java API，帮助编写更好的SQL。
* [Ebean](https://github.com/ebean-orm/ebean)：Ebean提供多个查询抽象级别ORM查询，与SQL、DTO查询、SqlQuery和JDBC混合。
* [ObjectiveSql](https://github.com/braisdom/ObjectiveSql)：使用Java语法编写SQL。
* [JPA-Streamer](https://github.com/speedment/jpa-streamer)：JPAstreamer是一个轻量级库，用于将JPA查询表达为Java Stream。
* [jdbi](https://github.com/jdbi/jdbi)：jdbi旨在提供Java中方便的表数据访问；包括模板化SQL、参数化和强类型查询以及Stream集成。
* [ORMLite](https://github.com/j256/ormlite-core)：精简版Java ORM。
* [Reladomo](https://github.com/goldmansachs/reladomo)：Reladomo是Java的企业级对象关系映射框架。
* [Cayenne](https://github.com/apache/cayenne)：Apache Cayenne是一个开源持久层框架，提供对象关系映射(ORM)和远程处理服务。
* [doma](https://github.com/domaframework/doma)：适用于Java 8+的面向DAO的数据库映射框架。
* [Jimmer](https://github.com/babyfish-ct/jimmer)：适用于Java和Kotlin的ORM框架。
* [JFinal](https://github.com/jfinal/jfinal)：国产的Web、ORM框架。
* [easy-query](https://github.com/xuejmnet/easy-query)：Java/Kotlin高性能轻量级JDBC查询解决方案，支持分表，数据库支持主从。
* [Nutz](https://github.com/nutzam/nutz)：包含全功能的ORM、Web框架。