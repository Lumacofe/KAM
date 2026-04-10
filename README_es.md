<details>
<summary><b>✨KAM — [K]ernel [A]nalytics [M]achine : Suite de herramientas KAM<br></b></summary><br>

<img src="lib/png/MarkDown/KAM Project 0.png" width="300"><br>

💡 **Matriz KAM**: Es la concatenación de filas (de A a Z) y columnas (de A a Z).
* Las posiciones en **amarillo** son funciones estructurales auxiliares.
* Las posiciones en **verde** son módulos de subrutinas completamente implementados.
* Las posiciones en **gris** son funcionalidades futuras.
* Al hacer clic en estas posiciones, se realiza la redirección al área de descarga.

<img src="lib/jpg/matrix.jpg" width="600"><br>

📋 **Versionado**<br>
|Versión |Fecha       |Descripción |
|--------|------------|------------|
|0.00h   |17/03/2026  |Implementación del módulo [C]ross [W]ord |
|0.00g   |31/05/2025  |Ampliación de los menús |
|0.00f   |18/05/2025  |Refinamiento de la rutina “historic” |
|0.00e   |27/04/2025  |Creación del diseño del formulario |
|0.00d   |22/02/2025  |Elementos & Flexibilidad II |
|0.00c   |21/02/2025  |Elementos & Flexibilidad I |
|0.00b   |31/01/2025  |Estructuración del proyecto |
|0.00a   |30/01/2025  |Concepción de las ideas |

</details>


<details>
<summary><b>✨CW — [C]ross [W]ord : Módulo para la generación de crucigramas<br></b></summary>

<img src="lib/jpg/kam_0.00h.jpg" width="300"><br>

Después de hacer clic en el botón **Download .ZIP**, el siguiente archivo aparecerá en la carpeta de descargas: **Install_KAM_v0.00h.bat**  
Haga doble clic en el archivo .bat y se extraerá la siguiente estructura:

⚪ **Estructura de directorios**<br>
* C:\KAM\
    * lib
        * ini
        * png
        * txt
        * ...
    * **KAM_0.00h.xlsm**

🎯 **Objetivo**<br>
El módulo CW tiene como finalidad construir crucigramas para:<br>
👉🏻 Uso lúdico<br>
👉🏻 Uso educativo<br>
👉🏻 Ejercicios terapéuticos para pacientes con pérdida de memoria<br>

🧩 **Características del módulo**
| Ítem                          | Valor       |
|-------------------------------|-------------|
| Versión actual                | 0.01        |
| Fecha                         | 2026.ABR.02 |
| Desarrollador                 | lumacofe    |
| Extensión del archivo de entrada | .txt     |
| Número mínimo de palabras     | 2           |
| Número máximo de palabras     | 100         |
| Separador de columnas         | :           |
| Número de columnas            | 2           |

📄 Ejemplos de archivos de texto para usar en **CrossWord**

| Archivo txt   | Nombre                                              |
|---------------|------------------------------------------------------|
| Ejemplo 1️⃣    | [Continentes.txt](lib/txt/Continentes.txt)          |
| Ejemplo 2️⃣    | [Planetas.txt](lib/txt/Planetas.txt)                |
| Ejemplo 3️⃣    | [Puntos Cardinales.txt](lib/txt/PontosCardeais.txt) |

⚙️ **Funcionalidades**<br>
A continuación, la barra de menús **KAM** que se abre en Excel al cargar **CW_0.01.xlsm**<br><br>
<img src="lib/jpg/menu.jpg" width="200"><br>

| Función       | Descripción |
|---------------|-------------|
| **File Import** | Abre la interfaz para seleccionar el archivo `.txt`. |
| **Gen CW**      | Genera el crucigrama. |
| **Gen PDF**     | Crea dos archivos PDF (sin etiquetas de filas y columnas):<br>🅰️ Uno con el solucionario<br>🅱️ Otro con el crucigrama sin respuestas |
| **About**       | Muestra la versión de KAM, su tamaño y un enlace al sitio mattlab. |

**Archivo PDF** 🅰️ (Solucionario)<br>
<img src="lib/jpg/gabarito.jpg" width="700"><br>
**Archivo PDF** 🅱️ (Crucigrama)<br>
<img src="lib/jpg/cruzadinha.jpg" width="700"><br>

📢 **Observaciones**<br>
1️⃣ El algoritmo organiza las palabras de la más larga a la más corta, facilitando la construcción del CW.<br>
2️⃣ Listas muy cortas pueden generar errores, ya que existe una regla que impide que las palabras queden pegadas vertical u horizontalmente.<br>
3️⃣ La numeración de las palabras se inserta automáticamente por la macro, siguiendo la regla 1️⃣.<br>

💡 **Consideraciones finales**<br>
▫️ El código es Open Source, desarrollado en VBA para Excel.<br>
▫️ Código comentado y abierto para edición, modificación y distribución sin fines comerciales.<br>
▫️ Solo se solicita mantener los créditos de autoría.<br>
▫️ Críticas, elogios, sugerencias o reportes de bugs son bienvenidos.<br>
▫️ Utilice el formulario “Entre en contacto” en el sitio mattlab.com.br.<br><br>

</details>
