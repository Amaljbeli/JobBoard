FROM openjdk:17
#utilise le meme port que le fichier application.properties
EXPOSE 8020
ADD target/candidat-0.0.1-SNAPSHOT.jar candidat.jar
ENTRYPOINT ["java", "-jar","candidat.jar"]
