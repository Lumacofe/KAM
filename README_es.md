✨ **CW — [C]ross [W]ord : Módulo para generar crucigramas**<br>
<img src="lib/jpg/kam_0.00h.jpg" width="300"><br>
Después de hacer clic en el botón **Download .ZIP**, el siguiente archivo estará en su carpeta de descargas: **Install_KAM_v0.00h.bat**
Haga doble clic en el archivo .bat y se descomprimirá la siguiente estructura a continuación:

⚪**Estructura de Directorios**<br>
* C:\KAM\
    * lib
        * ini
        * png
        * txt
        * ...
    * **KAM_0.00h.xlsm**

🎯 **Objetivo**<br><br>
El módulo CW está diseñado para crear crucigramas para:<br>
👉🏻Uso Lúdico<br>
👉🏻Uso Educativo<br>
👉🏻Ejercicios terapéuticos para pacientes con pérdida de memoria<br><br>

🧩 **Características del módulo**
| Artículo                          | Valor        |
|-----------------------------------|--------------|
| Versión actual                    | 0.01         |
| Fecha                             | 2026.APR.02  |
| Revelador                         | lumacofe     |
| Extensión del archivo de entrada  | .txt         |
| Número mínimo de palabras         | 2            |
| Número máximo de palabras         | 100          |
| Separador de columnas             | :            |
| Número de columnas                | 2            |

Archivo de ejemplo	: **Puntos cardinales.txt**<br>

📄 **Ejemplo de contenido de archivo**

NORTE: Polo donde se encuentra el Ártico<br>
SUR: Polo donde se encuentra la Antártida<br>
ESTE: Punto cardinal donde sale primero el Sol<br>
OESTE: Punto cardinal donde se pone más tarde el Sol<br>
NORESTE: Punto cardinal entre el este y el norte<br>
NOROESTE: Punto cardinal entre el norte y el oeste<br>
SUROESTE: Punto cardinal entre el oeste y el sur<br>
SURESTE: Punto cardinal entre el sur y el este<br>

⚙️ **Características**<br>
A continuación se muestra la barra de menú **KAM** que se abre en Excel al abrirlo. **CW_0.01.xlsm**<br><br> 
<img src="lib/jpg/menu.jpg" width="200"><br>

| Función       | Descripción |
|--------------|-----------|
| **File Import**  | Abre la interfaz para seleccionar el archivo. `.txt`. |
| **Gen CW**       | Generar el crucigrama (Cross Word). |
| **Gen PDF**      | Crea dos archivos PDF (sin las etiquetas de filas y columnas de la imagen):<br>🅰️ Uno con la clave de respuestas<br>🅱️ El otro con el crucigrama sin respuestas |
| **About**        |  Muestra la versión de KAM, su tamaño y un enlace al sitio web de mattlab.|<br>

**Archivo PDF** 🅰️ (Plantilla)<br>
<img src="lib/jpg/gabarito.jpg" width="700"><br>
**Archivo PDF** 🅱️ (Crucigrama)<br>
<img src="lib/jpg/cruzadinha.jpg" width="700"><br>

📢 **Observaciones**<br>
1️⃣El algoritmo organiza las palabras de mayor a menor, lo que facilita la construcción de la estructura CW.<br>
2️⃣Las listas muy cortas pueden dar lugar a errores, ya que existe una regla que impide que las palabras se unan vertical u horizontalmente.<br>
3️⃣La numeración de las palabras se inserta automáticamente mediante la macro, siguiendo la regla 1️⃣.<br><br>

💡 **Consideraciones finales**<br>
▫️El código es de código abierto y fue desarrollado en VBA para Excel.<br>
▫️Código comentado que se puede editar, modificar y distribuir con fines no comerciales.<br>
▫️Por favor, conserve los créditos de autoría.<br>
▫️Se agradecen las críticas, los elogios, las sugerencias y los informes de errores.<br>
▫️Utilice el formulario "Contáctenos" en el sitio web mattlab.com.br.<br><br>

📋 **Versionado**<br>
|Versión	|Fecha	| Descripción |
|-------|-----|-----------|
|0.01	|2026.APR.02	|Implementación inicial, Beta Test|
