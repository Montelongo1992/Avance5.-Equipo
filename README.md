Paso 1: Abrir el Notebook en Google Colab Primero, asegúrese de abrir el notebook desde Google Colab. Puede hacerlo a través del enlace proporcionado en el repositorio de GitHub o directamente desde su cuenta de Google Drive.

Haga clic en el enlace del notebook o abra Colab y cargue el archivo desde su Google Drive. Verifique que las celdas del notebook estén listas para ser ejecutadas.

Paso 2: Montar Google Drive Este proyecto almacena las imágenes en Google Drive. Para acceder a ellas, debe montar Google Drive en Colab ejecutando la siguiente celda al inicio del notebook: from google.colab import drive drive.mount('/content/drive')
