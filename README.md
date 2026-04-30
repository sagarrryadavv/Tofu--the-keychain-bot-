# 🤖 Tofu Keychain Bot  

<p align="center">
  <img src="media/WhatsApp%20Image%202026-04-30%20at%208.57.45%20PM.jpeg" width="300"/>
</p>

<p align="center">
  <b>A tiny interactive emotional robot that fits in your pocket.</b><br>
  Built using STM32 + OLED + capacitive touch.
</p>

---

## ✨ Features  

- 👆 Dual capacitive touch inputs  
- 🎭 Expressive pixel animations  
- 🔊 Sound-based feedback  
- ⏱️ 25-minute Pomodoro timer  
- 🧠 Personality-driven interactions  

---

## 🎮 Interaction System  

<table>
<tr>
<th>Action</th>
<th>Behavior</th>
</tr>

<tr>
<td><b>Touch 1 (Single)</b></td>
<td>😂 Laughs</td>
</tr>

<tr>
<td><b>Touch 1 (Double)</b></td>
<td>🍜 Eats food</td>
</tr>

<tr>
<td><b>Touch 1 (Hold)</b></td>
<td>😴 Sleeps</td>
</tr>

<tr>
<td><b>Touch 2 (Single)</b></td>
<td>😡 Angry</td>
</tr>

<tr>
<td><b>Touch 2 (Double)</b></td>
<td>😭 Cries</td>
</tr>

<tr>
<td><b>Touch 2 (Hold)</b></td>
<td>⏳ Pomodoro (25 min)</td>
</tr>

<tr>
<td><b>Both Touch (Hold)</b></td>
<td>😵 Dizzy Mode</td>
</tr>

</table>

---

## 🧩 Hardware  

- **MCU:** STM32C011J6M6  
- **Display:** 0.96" OLED (SH1106)  
- **Input:** 2 Capacitive touch pads  
- **Sound:** Piezo buzzer + PAM8403 amplifier  
- **Power:** 3.3V  

---

## 🔌 Wiring  

### 🔧 Upload Wiring (ST-Link)  

<p align="center">
  <img src="media/Screenshot%202026-04-30%20225634.png"/>
</p>

<table>
<tr>
<th>ST-Link Pin</th>
<th>STM32 Pin</th>
</tr>

<tr>
<td><b>3.3V</b></td>
<td>Pin 2 (VDD)</td>
</tr>

<tr>
<td><b>GND</b></td>
<td>Pin 3 (VSS)</td>
</tr>

<tr>
<td><b>SWDIO</b></td>
<td>Pin 7 (PA13)</td>
</tr>

<tr>
<td><b>SWCLK</b></td>
<td>Pin 8 (PA14)</td>
</tr>

<tr>
<td><b>RST</b></td>
<td>Pin 4 (PA0)</td>
</tr>

</table>

---

### ⚠️ Flashing Instructions  

- 🔌 Keep **RST (Pin 4)** connected while starting upload  
- ⚡ Upload to **bare metal chip**  
- ❗ If you see *"Unable to reset the target"*:
  - Remove **RST connection**
  - Upload again → it will work  

---

### 🤖 Full Bot Wiring  

<p align="center">
  <img src="media/Screenshot%202026-04-30%20225623.png"/>
</p>

<table>
<tr>
<th>STM32 Pin</th>
<th>Component</th>
</tr>

<tr>
<td><b>Pin 1 (PB7)</b></td>
<td>OLED SDA (Data)</td>
</tr>

<tr>
<td><b>Pin 2 (VDD)</b></td>
<td>3.3V → OLED VCC + Touch VCC + PAM8403 (+)</td>
</tr>

<tr>
<td><b>Pin 3 (VSS)</b></td>
<td>GND → OLED GND + Touch GND + PAM8403 (-)</td>
</tr>

<tr>
<td><b>Pin 4 (PA0)</b></td>
<td>🚫 Leave Empty</td>
</tr>

<tr>
<td><b>Pin 5 (PA11)</b></td>
<td>Touch Sensor 1 (Smile / Feed / Sleep)</td>
</tr>

<tr>
<td><b>Pin 6 (PA12)</b></td>
<td>Touch Sensor 2 (Angry / Cry / Pomodoro)</td>
</tr>

<tr>
<td><b>Pin 7 (PA13)</b></td>
<td>PAM8403 Amplifier (+)</td>
</tr>

<tr>
<td><b>Pin 8 (PA14)</b></td>
<td>OLED SCL (Clock)</td>
</tr>

</table>

---

## ⚡ Performance Optimizations  

- ⚡ Direct register GPIO access  
- 🚀 High-speed I2C pipeline  
- 🔁 Loop unrolling  
- 🧠 Manual timing control  
- 🔄 OLED address reset every frame  

---

## ⚠️ Important Notes  

- 🔌 Disconnect ST-Link after uploading  
- ⏱️ Keep startup delay  
- 🔧 Use 10kΩ pull-ups  
- ⚡ Use open-drain configuration  

---

## 📸 Gallery  

<p align="center">
  <img src="images/1.jpg" width="200"/>
  <img src="images/2.jpg" width="200"/>
  <img src="images/3.jpg" width="200"/>
</p>

---

## 🧠 Concept  

This is not just electronics.  
It's a **tiny emotional companion**.

---

## 🚀 Future Improvements  

- 🎤 Voice interaction  
- 📱 Mobile control  
- 🔵 Bluetooth  
- 🎨 Animation editor  

---

## 👤 Author  

**Sagar**

---

## ⭐ Support  

If you like this project:  
- ⭐ Star this repo  
- 🍴 Fork it  
- 🛠️ Build your own version  

---

<p align="center">
  Made with ⚡ + 🧠 + too many debugging hours
</p>
