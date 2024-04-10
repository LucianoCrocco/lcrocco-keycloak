# Keycloak config
Configuracion de keycloak1

## Keycloak rest
Inyecto un servicio [rest](https://github.com/Identicum/keycloak-rest-repo) para la user federation

## Realms
Dentro de la carpeta objects tengo un realm que inicializo al keycloak. Para esto preciso hacer 
 - En volumes: ./config/keycloak1/objects/realm.json:/opt/keycloak/data/import/realm.json 
 - En command como flag de incio: --import-realm 

## Custom Themes
Para un custom theme si quiero aplicar un archivo global si o si tengo que especificar las 4 opciones que me da el realm sino quedan como 'vacias'