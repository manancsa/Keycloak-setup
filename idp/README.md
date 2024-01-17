#Start docker -
docker run --name idp -p 8443:8443 \
 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=<password> \
 idp \
 start --optimized
