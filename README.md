Proyecto TP3 – Ingeniería de Software 3

Este repositorio contiene el trabajo práctico N.° 3 realizado en Azure DevOps, aplicando metodologías ágiles y control de versiones con Git.

1- Acceder al proyecto de Azure DevOps

  Ir a 👉 https://dev.azure.com
  .Iniciar sesión con la cuenta de Microsoft.
  
  Organización: soficuozzo
  Proyecto: ProyectoTP3-Cuozzo-Hernandez.

2- Clonar y trabajar con el repositorio
  # Clonar el repo importado desde Azure Repos
  git clone https://github.com/soficuozzo/TP3-IngeSoftware3-Cuozzo-Hernandez.git
  cd TP3-IngeSoftware3-Cuozzo-Hernandez
  
  # Crear una rama de feature
  git checkout -b feature/us1-inscripcion
  
  # Hacer cambios → agregar, commitear y pushear
  git add .
  git commit -m "Implementación US1 - inscripcion"
  git push origin feature/us1-inscripcion


3- Ejecutar los pipelines

  En Pipelines, se creó un Starter pipeline en YAML a partir de Azure Repos Git.
  Durante la primera ejecución apareció el error de “No hosted parallelism has been purchased”.
  Para resolverlo, se completó el formulario oficial de Microsoft solicitando el paralelismo gratuito para la organización.

Una vez aprobado, los pipelines pudieron ejecutarse correctamente.
