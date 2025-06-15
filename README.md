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
- EasyDraw V2 "(frame)"
- Braille-embossing pen mount  
- 180gsm+ Paper or plastic tactile sheets  

🧠 Controller & Power  
- Arduino Uno / ESP32 – For motion control and serial communication  
- CNC Shield (for Arduino)  
- A4988 Stepper Drivers  
- Power Supply Unit (12V recommended)  

---

### Software Used

🧩 **Inkscape + Custom Extensions**  
Used to convert typed text and images into Braille or dotted tactile graphics.

🧰 **Python**  
To process SVG files, convert to coordinate data, and send to the plotter via serial commands.

⚙️ **GRBL Firmware** *(if using Arduino)*  
Handles G-code and low-level stepper movement logic.

📦 Libraries & Tools  
- `pyserial` – For communication with Arduino/ESP32  
- `svgpathtools` – For SVG path parsing  
- `inkex`, `lxml` – For Inkscape extension development  

---

### License

**Hardware**  
CERN Open Hardware License Version 2 - Strongly Reciprocal ([CERN-OHL-S-2.0](https://spdx.org/licenses/CERN-OHL-S-2.0.html))

**Software**  
MIT open source license ([MIT](https://opensource.org/licenses/MIT))

**Documentation**  
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
  <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" />
</a><br />
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
Creative Commons Attribution 4.0 International License</a>.

---

### 📬 Contact / Team

**Makers Asylum**  
Vedant Garg  
[github.com/Vedant-Garg](https://github.com/Vedant-Garg)  
Prabhav Joshi  
Raghav Dalvie  
Krish Kapur  
