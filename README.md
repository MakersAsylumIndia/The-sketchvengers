📘 Project Sketchvengers: A Braille Plotter Bot Making Tactile Graphics and Braille Accessible  
Vedant Garg, Prabhav Joshi, Raghav Dalvie, Krish Kapur

---

### Problem Statement

Millions of blind and visually impaired individuals often lack access to tactile graphics and printed Braille resources due to the absence of easy, affordable, and open-source tools. Existing solutions are expensive, limited in flexibility, or too technical for everyday users like educators and students.

---

### Our Solution

We are building a **Braille Plotter Bot**, a low-cost, open-source machine capable of transforming digital content into tactile Braille and diagrams. The bot receives commands from Inkscape and plots:

- Typed text converted into embossed Braille
- Braille-ready SVG files
- Tactile images made of dotted patterns for shapes, outlines, and textures

The bot uses a precision-controlled pen mechanism to emboss dots on thick paper, making it ideal for educational institutions, maker labs, and accessibility-focused classrooms.

---

### Hardware Used

🖨️ Plotting Mechanism  
- EasyDraw V2 (frame)
- Braille-embossing pen mount
- Schneider one change (pen - braille and drawning)
- ?gsm+ Paper  

🧠 Controller
- Raspberry Pi 4B – For motion control and serial communication  

---

### Software Used

🧩 **Inkscape + Custom Extensions**  
Used to convert typed text and images into Braille or dotted tactile graphics.

🧰 **Python**  
To process SVG files, convert to coordinate data, and send to the plotter via serial commands.


📦 Libraries & Tools  
- `svgpathtools` – For SVG path parsing  
- `inkex`, `lxml` – For Inkscape extension development  

---

### 📬 Contact / Team

**Makers Asylum**  
Vedant Garg  
Prabhav Joshi  
Raghav Dalvie  
Krish Kapur  
