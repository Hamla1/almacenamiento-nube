# Paso 2: Configurar la CLI y Crear el Bucket
Ahora vincularemos la terminal con nuestra "nube local" de MinIO para que puedas empezar a gestionar objetos.
### 1. Configurar las credenciales
Ejecuta estos comandos para que la AWS CLI sepa cómo autenticarse con MinIO:
```bash
aws configure set aws_access_key_id minioadmin
aws configure set aws_secret_access_key minioadmin
aws configure set region us-east-1
