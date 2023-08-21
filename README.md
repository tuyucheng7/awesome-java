# Java生态资源大全

本项目统计了Java生态圈中的各种资源，包括库、框架、学习网站，并且按照其所属的领域进行了分类，方便大家查找。

## 测试

这里主要是一些测试框架和工具库，包括单元测试、集成测试、性能测试等。

### 单元测试

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

### 断言库

* [AssertJ](https://github.com/assertj/assertj)：AssertJ是一个提供易于使用的丰富类型断言的库。
* [JsonAssert](https://github.com/skyscreamer/JSONassert)：用更少的代码编写JSON单元测试，非常适合测试REST接口。
* [Truth](https://github.com/google/truth)：Google出品的流式断言库。
* [Hamcrest](https://github.com/hamcrest/JavaHamcrest)：Hamcrest的Java版本。
* [BeanMatcher](https://github.com/orien/bean-matchers)：用于测试Java bean的Hamcrest匹配器。
* [Deepdive](https://github.com/jdlib/deepdive)：Java的流式断言库。
* [Fest](https://github.com/alexruiz/fest-assert-2.x)：流式断言库。
* [expekt](https://github.com/winterbe/expekt): Kotlin的BDD断言库。

### Mock框架

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

## Mock工具

* [Moco](https://github.com/dreamhead/moco)：设置存根服务器。
* [RabbitMQ Mock](https://github.com/fridujo/rabbitmq-mock)：RabbitMQ的Mock库。
* [flashback](https://github.com/linkedin/flashback)：Flashback旨在模拟HTTP和HTTPS资源(例如Web服务和REST API)以用于测试目的。
* [S3Mock](https://github.com/adobe/S3Mock)：AWS S3 API的简单Mock实现，可作为Docker镜像、TestContainer、JUnit 4 Rule、JUnit Jupiter扩展或TestNG监听器启动。
* [CastleMock](https://github.com/castlemock/castlemock)：CastleMock是一个Web应用程序，提供模拟RESTful API和SOAP Web Service的功能。
* [restito](https://github.com/mkotsur/restito)：用于测试Rest客户端的Mock框架。

### 数据Mock

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

### BDD框架

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

### 自动化工具

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

### 负载测试

* [JMeter](https://github.com/apache/jmeter)：Apache出品的GUI形式的开源负载测试工具。
* [Ngrinder](https://github.com/naver/ngrinder)：企业级性能测试解决方案。
* [Gatling](https://github.com/gatling/gatling)：更现代的负载测试工具，以代码的方式编写测试用例。

### 其他库

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