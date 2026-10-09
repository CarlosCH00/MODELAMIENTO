# Reducción de dimensionalidad — Bank Marketing

Página estática en español creada con HTML y CSS para presentar el proyecto académico de reducción de dimensionalidad aplicado a `bank-additional-full.csv`.

## Archivos
- `index.html`: sitio web completo, adaptable a móviles y ordenadores.

## Publicar con GitHub Pages
1. Crea un repositorio nuevo en GitHub, por ejemplo `reduccion-dimensionalidad`.
2. Sube `index.html` a la raíz del repositorio.
3. Entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub publique el sitio. La URL aparecerá en la misma sección de Pages.

## Importante sobre los resultados
La página presenta las puntuaciones ANOVA F como aproximaciones y distingue la reducción de características de la evaluación predictiva. Antes de presentar resultados como evidencia de rendimiento de un modelo, realiza una evaluación con separación de entrenamiento y prueba. Considera también el posible uso de `duration` como fuga de información si la predicción debe realizarse antes de contactar al cliente.

No es necesario subir el CSV bancario al repositorio para publicar esta página, ya que el sitio no carga ni procesa el archivo: muestra una explicación de los resultados.
