### Enable H2 Console Access

spring.h2.console.enabled=true

spring.h2.console.path=/h2-console


### Define H2 Datasource configurations

spring.datasource.url=jdbc:h2:file:~/test

spring.datasource.username=sa

spring.datasource.password=

spring.datasource.driver-class-name=org.h2.Driver

spring.jpa.hibernate.ddl-auto=create-drop

spring.jpa.show-sql=true

spring.jpa.properties.hibernate.format_sql=true
