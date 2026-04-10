<details>
<summary><b>✨KAM — [K]ernel [A]nalytics [M]achine : KAM Tool Suite<br></b></summary><br>

<img src="lib/png/MarkDown/KAM Project 0.png" width="300"><br>

💡 **KAM Matrix**: It is the concatenation of rows (A to Z) and columns (A to Z).
* The **yellow** positions are structural helper functions.
* The **green** positions are fully implemented subroutine modules.
* The **gray** positions are future features.
* Clicking these positions redirects to the download area.

<img src="lib/jpg/matrix.jpg" width="600"><br>

📋 **Versioning**<br>
|Version |Date       |Description |
|--------|-----------|------------|
|0.00h   |2026‑03‑17 |Implementation of the [C]ross [W]ord module |
|0.00g   |2025‑05‑31 |Menu expansion |
|0.00f   |2025‑05‑18 |Refinement of the “historic” routine |
|0.00e   |2025‑04‑27 |Creation of the form layout |
|0.00d   |2025‑02‑22 |Elements & Flexibility II |
|0.00c   |2025‑02‑21 |Elements & Flexibility I |
|0.00b   |2025‑01‑31 |Project structuring |
|0.00a   |2025‑01‑30 |Concept development |

</details>


<details>
<summary><b>✨CW — [C]ross [W]ord : Module for crossword generation<br></b></summary>

<img src="lib/jpg/kam_0.00h.jpg" width="300"><br>

After clicking the **Download .ZIP** button, the following file will appear in your downloads folder: **Install_KAM_v0.00h.bat**  
Double‑click the .bat file and the following structure will be extracted:

⚪ **Directory Structure**<br>
* C:\KAM\
    * lib
        * ini
        * png
        * txt
        * ...
    * **KAM_0.00h.xlsm**

🎯 **Purpose**<br>
The CW module is designed to build crossword puzzles for:<br>
👉🏻 Recreational use<br>
👉🏻 Educational use<br>
👉🏻 Therapeutic exercises for patients with memory loss<br>

🧩 **Module Characteristics**
| Item                           | Value       |
|--------------------------------|-------------|
| Current version                | 0.01        |
| Date                           | 2026.APR.02 |
| Developer                      | lumacofe    |
| Input file extension           | .txt        |
| Minimum number of words        | 2           |
| Maximum number of words        | 100         |
| Column separator               | :           |
| Number of columns              | 2           |

📄 Example text files for use in **CrossWord**

| Text File     | Name                                                |
|---------------|-----------------------------------------------------|
| Example 1️⃣    | [Continents.txt](lib/txt/Continents.txt)           |
| Example 2️⃣    | [Planets.txt](lib/txt/Planets.txt)                 |
| Example 3️⃣    | [Cardinal Points.txt](lib/txt/CardinalPoints.txt)  |

⚙️ **Features**<br>
Below is the **KAM** menu bar that opens in Excel when loading **CW_0.01.xlsm**<br><br>
<img src="lib/jpg/menu.jpg" width="200"><br>

| Function      | Description |
|---------------|-------------|
| **File Import** | Opens the interface to select the `.txt` file. |
| **Gen CW**      | Generates the crossword puzzle. |
| **Gen PDF**     | Creates two PDF files (without row/column labels):<br>🅰️ One with the answer key<br>🅱️ One with the crossword puzzle without answers |
| **About**       | Displays the KAM version, its size, and a link to the mattlab website. |

**PDF File** 🅰️ (Answer Key)<br>
<img src="lib/jpg/gabarito.jpg" width="700"><br>
**PDF File** 🅱️ (Crossword)<br>
<img src="lib/jpg/cruzadinha.jpg" width="700"><br>

📢 **Notes**<br>
1️⃣ The algorithm organizes the words from longest to shortest, making CW structure construction easier.<br>
2️⃣ Very short lists may cause errors because there is a rule preventing words from touching vertically or horizontally.<br>
3️⃣ Word numbering is inserted automatically by the macro, following rule 1️⃣.<br>

💡 **Final Considerations**<br>
▫️ The code is Open Source, developed in VBA for Excel.<br>
▫️ The code is commented and open for editing, modification, and non‑commercial distribution.<br>
▫️ Credit to the author is kindly requested.<br>
▫️ Feedback, suggestions, compliments, or bug reports are welcome.<br>
▫️ Use the “Contact Us” form on the mattlab.com.br website.<br><br>

</details>
