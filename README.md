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
- **Sound:** Piezo buzzer  
- **Power:** 3.3V  

---

## 🔌 Wiring  

📌 Full wiring diagram and pin mapping available in this repo.  

⚠️ This project uses a **custom pin hack**, so follow wiring exactly.

---

## ⚡ Performance Optimizations  

This build is heavily optimized for speed:

- ⚡ Direct register GPIO access  
- 🚀 High-speed I2C pipeline  
- 🔁 Loop unrolling (no runtime loops)  
- 🧠 Manual timing control  
- 🔄 OLED address reset every frame  

---

## ⚠️ Important Notes  

> These are not optional — they prevent bugs and hardware issues.

- 🔌 Disconnect ST-Link after uploading  
- ⏱️ Keep startup delay (for stability)  
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

The goal was to simulate personality using:
- touch interactions  
- expressions  
- timing  
- sound  

---

## 🚀 Future Improvements  

- 🎤 Voice interaction  
- 📱 Mobile control  
- 🎨 Animation editor  
- 🔵 Bluetooth connectivity  

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
