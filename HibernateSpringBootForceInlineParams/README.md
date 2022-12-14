**[Force inline params in Criteria API](https://github.com/AnghelLeonard/Hibernate-SpringBoot/tree/master/HibernateSpringBootForceInlineParams)**

**NOTE** Use this with high precaution since you open the gate for SQL injections.
 
**Description:** Sometimes we need to force inline params in Criteria API. By default, numeric parameters are inlined, but string parameters are not.

**Key points:**
- configure in `application.properties` the setting `spring.jpa.properties.hibernate.criteria.literal_handling_mode` as `inline`

-----------------------------------------------------------------------------------------------------------------------    
<table>
     <tr><td><b>If you need a deep dive into the performance recipes exposed in this repository then I am sure that you will love my book "Spring Boot Persistence Best Practices"</b></td><td><b>If you need a hand of tips and illustrations of 100+ Java persistence performance issues then "Java Persistence Performance Illustrated Guide" is for you.</b></td></tr>
     <tr><td>
<a href="https://www.apress.com/us/book/9781484256251"><p align="left"><img src="https://github.com/AnghelLeonard/Hibernate-SpringBoot/blob/master/Spring%20Boot%20Persistence%20Best%20Practices.jpg" height="500" width="450"/></p></a>
</td><td>
<a href="https://leanpub.com/java-persistence-performance-illustrated-guide"><p align="right"><img src="https://github.com/AnghelLeonard/Hibernate-SpringBoot/blob/master/Java%20Persistence%20Performance%20Illustrated%20Guide.jpg" height="500" width="450"/></p></a>
</td></tr></table>

-----------------------------------------------------------------------------------------------------------------------    

