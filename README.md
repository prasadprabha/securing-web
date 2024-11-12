# Read Me First
There are two profiles in this spring boot project :

## 1. basic
* basic : Implemented with the basic spring security. For more information refer : https://spring.io/guides/gs/securing-web

## 2. LDAP 

* ldap : Implemented with the LDAP Support for spring security. You also need an LDAP server. Spring Boot provides auto-configuration for an embedded LDAP server written in pure Java, which is being used for this guide. For more information refer : https://spring.io/guides/gs/authenticating-ldap

# Configuring Spring Security

If Spring Security is on the classpath, Spring Boot automatically secures all HTTP endpoints with “basic” authentication. However, you can further customize the security settings. The first thing you need to do is add Spring Security to the classpath

Once the application starts up, point your browser to http://localhost:8080. You should see the home page:
