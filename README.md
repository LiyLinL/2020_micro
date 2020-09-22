# 2020_micro

# 姓名:林益立
## 就職單位: 昊聲訊息技術有限公司
### 職稱: 軟體工程師
#### 使用程式語言: 
    1. Java (Spring Boot)
    2. JS
    3. SAPUI5
#### DB: 
    1. Oracle
    2. SQL Server
    3. Hana

![Spirng](https://spring.io/images/spring-logo-9146a4d3298760c2e7e49595184e1975.svg "SPRING")
## [Spring boot](https://spring.io/projects/spring-boot)
### Test program [generator](https://github.com/LiyLinL/JavaWork/tree/master/generator)

## Code
```java
@RunWith(SpringRunner.class)
@SpringBootTest
@EnableAsync
public class GeneratorApplicationTests {
    @Test
    public void jms() throws InterruptedException, IOException {
        Jackson jackson = new Jackson();
        jackson.setAlways("A");
        jackson.setSome("B");
        ObjectMapper objectMapper = new ObjectMapper();
        String json = objectMapper.writeValueAsString(jackson);

        Object obj = jmsService.sendMessage("Q", json);
        jackson = objectMapper.readValue((String) obj, Jackson.class);
        System.out.println(jackson.getAlways());
    }
}
```

|Spring     |Version|
|:---------:|:------|
|Spring Boot|2.3.4  |
---
[![...](https://img.youtube.com/vi/4aH3fNaggBo/0.jpg)](https://www.youtube.com/watch?v=4aH3fNaggBo "...")
