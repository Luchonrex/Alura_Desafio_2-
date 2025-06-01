# Alura_Desafio_2-
Desarrollo  desafio 2 Alura Latam, Telecom X - Análisis de Evasión de Clientes

# 📊 Telecom X - Análisis de Evasión de Clientes

Bienvenido al proyecto **Telecom X - Análisis de Evasión de Clientes**. Este proyecto forma parte del desafío de análisis de churn 
para la empresa Telecom X, que busca reducir la tasa de cancelación de clientes. Como asistente de análisis de datos, tu tarea principal
será recopilar, procesar y analizar los datos con Python, extrayendo información valiosa para ayudar al equipo de Data Science a desarrollar
estrategias efectivas de retención.
---

## 📝 Descripción

Telecom X enfrenta una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes. Este proyecto 
aborda el análisis exploratorio de datos (EDA) y la limpieza inicial de los datos, usando Python y sus principales bibliotecas de análisis,
para sentar las bases de futuros modelos predictivos de churn.
---

## ⚙️ Instalación

Sigue estos pasos para preparar el entorno de ejecución y las dependencias:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/usuario/telecom-x-churn.git
   cd telecom-x-churn
   ---
   
(Opcional) Crear un entorno virtual:
python3 -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
---

#Instalar las dependencias principales:
pip install pandas matplotlib seaborn
🗃️ Dependencias principales El proyecto utiliza las siguientes librerías de Python:

pandas: para manipulación y análisis de datos.

matplotlib.pyplot: para generar visualizaciones básicas.

seaborn: para crear gráficos estadísticos avanzados.

Además, en el análisis se utiliza json_normalize para trabajar con datos en formato JSON.
---

💻 Modo de ejecución El proyecto se desarrolla íntegramente en un Jupyter Notebook (.ipynb). Para ejecutar el análisis:

Abre el Jupyter Notebook en tu entorno preferido (JupyterLab, Jupyter Notebook o Google Colab).

Ejecuta las celdas en orden para:

Importar las bibliotecas necesarias (pandas, json_normalize, matplotlib.pyplot, seaborn).

Cargar el archivo de datos (TelecomX_Data.json).

Realizar operaciones de limpieza y normalización.

Analizar y visualizar los datos.

Calcular correlaciones y métricas relevantes.
---

📂 Estructura del proyecto Actualmente, el proyecto consta de:

Notebook principal:

TelecomX_Analysis.ipynb Contiene la carga de datos, limpieza, EDA y visualizaciones.

Archivo de datos:

/content/TelecomX_Data.json (En proyectos reales, este archivo debería estar en una carpeta data/).

(Posible expansión futura):

models/ para almacenamiento de modelos predictivos.

src/ para funciones modulares.
---

⚠️ Problemas comunes y soluciones

Problema	Solución recomendada
Dependencias faltantes	Ejecuta !pip install pandas matplotlib seaborn en una celda del notebook si falta alguna librería.
Archivo de datos no encontrado	Verifica que TelecomX_Data.json exista en la ruta correcta y que esté cargado en el entorno (en Google Colab, 
súbelo o monta Drive adecuadamente).
Errores en la normalización de JSON	Asegúrate de que la estructura del JSON coincide con la esperada (columnas 'customer', 'phone', 'internet', 'account').
Inconsistencias de datos	Ten en cuenta valores atípicos, NaNs y formatos inesperados que puedan afectar el análisis; limpia o valida los datos antes de continuar.
Conversión de tipos	Se recomienda manejar errores en las conversiones y revisar advertencias como SettingWithCopyWarning para evitar resultados inesperados.
Errores en operaciones con strings	Comprueba que las columnas sobre las que aplicas .str.* sean de tipo object y conviértelas si es necesario.
Desbalance de clases	Reconoce que la variable Dejo_el_servicio está desbalanceada; considera técnicas como sobremuestreo o submuestreo en la fase de modelado.
Interpretación de correlaciones	Recuerda que la correlación de Pearson mide relaciones lineales y puede ser engañosa para variables binarias. Interpreta con precaución.
---

🤝 Contribución ¡Las contribuciones son bienvenidas! Si detectas errores, mejoras potenciales o deseas extender el análisis, por favor abre un issue o envía un pull request.

📄 Licencia Este proyecto está bajo la licencia MIT.
---

📬 Contacto Para cualquier pregunta o colaboración, por favor contacta a:

📧 luissaavedramarchant@gmail.com



   
