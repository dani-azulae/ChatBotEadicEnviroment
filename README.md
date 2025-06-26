# Entorno de chat bot para EADIC en N8N y Docker

## Plantilla N8N
Para cargar la plantilla, descargarla de este repositorio y luego importarla en uno de los flujos de N8N.

Habrá que configurar el LLM del nodo de Ollama, y el modelo de embedding. Esto se hará desde el contenedor ollama que instalaremos desde docker

## Entorno de Docker
Descargamos el .env y el docker-compose.yml, y con ambos en el mismo directorio, lo cargamos ejecutando en el CLI:

### docker-compose up
ó
### docker-compose up -d
