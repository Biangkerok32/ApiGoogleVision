# ApiGoogleVision
Uso de Google Cloud Vision Api

Se agrega en el manifest los permisos correspondientes para usar  la api de google y la camara

Luego, se crea la clase PackageManagerUtils que proporciona lógica de utilidad para obtener la firma SHA1 de la aplicación. Se utiliza con claves de API restringidas.
Se agrega la clase PermissionUtils que ayuda a verificar que todos los permisos esten declarados en el manifest de no ser así, pues los agrega.
