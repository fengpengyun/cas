web:    java $JAVA_OPTS -jar build/libs/cas.war --server.ssl.enabled=false --cas.events.trackConfigurationModifications=false --cas.server.tomcat.http.enabled=false --cas.server.name=https://cas-oidc-cert.herokuapp.com --cas.server.prefix=https://cas-oidc-cert.herokuapp.com/cas --server.port=$PORT --cas.serviceRegistry.initFromJson=true --cas.authn.oidc.issuer=https://cas-oidc-cert.herokuapp.com/cas/oidc --cas.authn.oidc.jwksFile=file:keystore.jwks