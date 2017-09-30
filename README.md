1、 pom 中 依赖对其他module的pom的依赖<dependency>，只是包的依赖。
除此之外的其他配置，如properties、build 等只能通过继承得到<parent>。
因此 maven编译jdk版本，字符编码，项目版本等都是配置在root结构的pom中的。