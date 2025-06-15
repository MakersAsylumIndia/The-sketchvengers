📘 Project Braille Plotter Bot: Making Tactile Graphics and Braille Accessible  
Vedant Garg

---

### Problem Statement

Blind and visually impaired individuals often lack access to tactile graphics and printed Braille resources due to the absence of easy, affordable, and open-source tools. Existing solutions are expensive, limited in flexibility, or too technical for everyday users like educators and students.

---

### Our Solution

We developed a set of Inkscape extensions that allow users to:
- Convert any typed text into properly spaced Braille
- Plot Braille-ready SVG files
- Create tactile diagrams and images using evenly spaced Braille-style dots

This enables educators, assistive technology developers, and makerspaces to generate customized tactile learning materials with minimal cost and effort.

---

### Hardware Used

🖨️ Output & Plotting  
- Braille-Compatible Plotter (e.g., modified pen plotter or CNC-based Braille embosser)  
- 180gsm+ Paper or plastic tactile sheets

🔌 Optional Electronics  
- Raspberry Pi (if running standalone)  
- Arduino or ESP32 (if automating hardware triggering)  

---

### Software Used

🧩 **Inkscape**  
Main software interface used for design and plotting

🧰 **Python**  
Custom extensions written to generate and manipulate Braille-compatible SVG files  
- SVG Path manipulation  
- Text-to-Braille conversion  
- Dot grid generation for tactile images

📦 **Libraries Used**  
- `lxml` – For SVG/XML parsing  
- `inkex` – Inkscape extension API  
- `os`, `math`, `re` – Built-in modules for text and coordinate handling

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
