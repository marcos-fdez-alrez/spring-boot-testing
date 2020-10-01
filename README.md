# spring-boot-testing

### Tests
mvn clean test

### Checkstyle
mvn checkstyle:checkstyle

### PMD
mvn pmd:check
mvn pmd:pmd

### Findbugs
mvnw findbugs:gui
mvnw findbugs:check
mvnw findbugs:findbugs
mvnw findbugs:help -Ddetail=true -Dgoal=check
mvnw findbugs:help -Ddetail=true -Dgoal=findbugs

### Spotbugs - security issues
mvn spotbugs:check
mvn spotbugs:spotbugs
mvn spotbugs:gui

### Site Generation
mvn site

