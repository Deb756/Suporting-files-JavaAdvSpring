# Spring Core

## Bean class
> Every class that has some variable and every variable has getter and setters then that type of class called bean class

## Creating Object by Spring Container

 There are 2 ways of it i.e 
 > 1 - by using XmlBeanfactory Interface

 ```java
 	   ClassPathResource cpr = new ClassPathResource("Myconfig.xml");
	   XmlBeanFactory xmb = new XmlBeanFactory(cpr);
	   Alien bean = (Alien) xmb.getBean("alien");
	   bean.code();
	   System.out.println(bean);

```
> 2 - by using ApplicationContext Interface

```java
ApplicationContext ap = new ClassPathXmlApplicationContext("Myconfig.xml");
		Alien a =(Alien) ap.getBean("alien");
		a.code();
```
### Configuration for xml bean 

```xml
<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xmlns:context="http://www.springframework.org/schema/context"
	xsi:schemaLocation="http://www.springframework.org/schema/beans
            http://www.springframework.org/schema/beans/spring-beans.xsd
            http://www.springframework.org/schema/context
            http://www.springframework.org/schema/context/spring-context-3.0.xsd">

	<bean id="alien" class="com.org.SpringYT_1.Alien"></bean>

</beans>
```
### Bean - scope attribute
```xml

```

