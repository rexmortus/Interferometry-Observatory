# Interferometer Observatory

A high-fidelity, interactive **Michelson Interferometer** simulation built with HTML5, CSS3, and Vanilla JavaScript. This tool provides a real-time visualization of optical interference phenomena, allowing users to manipulate laser wavelengths and path differences to observe constructive and destructive interference.

## 🚀 Features

* **Multi-Mode Laser Selection:**
* **Optical:**  (Visible Green)
* **LIGO:**  (Near-IR)
* **Quantum:**  (Rubidium Transition)


* **Real-Time Simulation:** * Adjustable **Path Difference ()** from  to .
* Variable **Beam Intensity** control.
* Dynamic **Instrument Geometry** canvas showing beam splitter and mirror positioning.


* **3-Channel Oscilloscope Trace:**
* **CH1 (Reference):** Baseline wave profile.
* **CH2 (Measurement):** Phase-shifted wave based on .
* **CH3 (Interference):** Summed resultant wave showing real-time interference power.


* **Precision Analytics:** Automated calculation of Phase Shift (rad/degrees), Interference Power, Fringe Visibility, and Coherence.

## 🛠️ Technical Details

### Physics Calculations

The simulation calculates phase shift based on the path difference relative to the selected wavelength:



*The factor of 2 accounts for the light traveling the path difference twice (to and from the mirror).*

### UI/UX

* **Styling:** Modern "Cyberpunk" dark-mode aesthetic using CSS variables and the `Rajdhani` / `JetBrains Mono` Google Fonts.
* **Rendering:** Dual-canvas system (Geometry and Oscilloscope) utilizing the HTML5 Canvas API for high-performance 60fps animations.
* **Responsiveness:** Fluid grid layout that adapts to various screen dimensions.

## 📂 Installation

1. Clone the repository:
```bash
git clone https://github.com/username/interferometer-observatory.git

```


2. Open `index.html` in any modern web browser. No dependencies or build steps required.

---

Would you like me to add a **save/export** feature to the code so you can download the oscilloscope data as a CSV?
