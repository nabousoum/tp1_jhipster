pour ms1
  Pour lancer keycloack docker compose -f .\src\main\docker\keycloak.yml up -d
  pour lancer app registry docker-compose -f .\src\main\docker\jhipster-registry.yml up -d
  pour app registry : http://localhost:8761/
  pour keycloack : http://localhost:9080/
  pour les infos du realme pour la connexion a postman http://localhost:9080/realms/jhipster/.well-known/openid-configuration
  pour lancer ms1  ./mvnw


pour gateway
  pour keycloack http://localhost:9082/admin/master/console/#/jhipster/clients/6e8deddb-b4d6-4e2e-b389-b397d3f74fcd/settings 


pour ms2
  pour keycloack http://localhost:9081/
  pour lancer ms2  ./mvnw
