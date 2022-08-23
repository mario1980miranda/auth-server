# auth-server

## Generate jks keypair
```
keytool -genkeypair -alias awblog -keyalg RSA -keypass 123456 -keystore awblog.jks -storepass 123456 -validity 3560
```

## Verify keys
```
keytool -list -keystore awblog.jks
```

## Github Spring Authorization Server
```
https://github.com/spring-projects/spring-authorization-server
```

## Github Spring Session
```
https://github.com/spring-projects/spring-session/blob/main/spring-session-jdbc/src/main/resources/org/springframework/session/jdbc/schema-postgresql.sql
```
