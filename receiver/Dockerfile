FROM maven:3.9.5-eclipse-temurin-17
WORKDIR /app
COPY . /app/
RUN mvn clean package -DskipTests
EXPOSE 8081
CMD ["mvn", "spring-boot:run"]