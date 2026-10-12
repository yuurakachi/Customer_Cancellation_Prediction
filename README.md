## Credenciales Modelo Microsoft Machine Learning


**Por razones de seguridad y privacidad, NO se incluyen los siguientes datos al repositorio.**  
Estos valores deben ser proporcionados directamente por los usuarios en su entorno local o mediante algun metodo seguro de transferencia de datos.

| Variable | Descripción | Ejemplo |
|----------|-------------|---------|
| `workspace_name` | Nombre del área de trabajo en Azure Machine Learning | `"prod-ml-workspace"` |
| `subscription_id` | ID único de la suscripción de Azure (sensible) | `"a1b2c3d4-e5f6-g7h8-i9j0-k1l2m3n4o5p6"` |
| `resource_group` | Grupo de recursos donde está implementado el servicio | `"ml-resources"` |
| `model_name` | Nombre registrado del modelo en Azure ML Studio | `"churn-prediction-model"` |
| `service_name` | Nombre del endpoint de despliegue del servicio web | `"churn-api"` |

## Bases de Datos
**Por razones de seguridad y privacidad, NO se incluyen las bases de datos proporcionadas por TCA dentro de este repositorio.**
Estos valores deben ser proporcionados directamente por los usuarios en su entorno local o mediante algun metodo seguro de transferencia de datos.

".\streamlit\backend\Datasets\iar_Agencias.csv" Es una base de datos necesaria para el funcionamiento de la aplicación, ésta contiene el catálogo de las agencias registradas.

## Modelo
**Por razones de la capacidad de almacenamiento disponible en github, el modelo.pkl se proporciona comprimido.zip.**
Este modelo debe extraido y ubicado en: ".\streamlit\backend\randomforest_model.pkl"

## Presentación
📄 [Ver presentación (PDF)](Insight%20Engineers%20Pres%20-%20TCA.pdf)
