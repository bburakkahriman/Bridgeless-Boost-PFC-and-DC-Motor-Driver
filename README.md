# ⚙️ Bridgeless Boost PFC ve Dört Bölgeli DC Motor Sürücü Sistemi  
### ⚙️ Bridgeless Boost PFC and Four-Quadrant DC Motor Drive System

---

## 🇹🇷 Proje Açıklaması

Merhabalar.  
Bu proje, **Bridgeless Boost PFC** yapısını kullanarak güç faktörünü iyileştiren ve toplam harmonik distorsiyonu (THD) düşüren bir **AC-DC dönüştürücü** ile, dört bölgeli bir **DC motor sürücü sistemini** bir araya getiriyor. Tüm model, **MATLAB/Simulink** ortamında detaylı olarak tasarlandı ve test edildi.

### 💡 Ne Yaptım?

- Bridgeless Boost PFC, **Histerezis Akım Kontrolü (HCC)** ile tasarlanarak **500V DC çıkış** elde edilmiştir.  
- Bu çıkış, **Unipolar PWM anahtarlama** yöntemi ile kontrol edilen dört bölgeli DC motor sürücüsüne uygulanmıştır.  
- **Alan zayıflatma (field weakening)** tekniğiyle motorun nominal hızın üstüne çıkması sağlanmıştır.

### 🧪 Simülasyon Özellikleri

- İleri–geri yönlü dönüş, frenleme ve durma senaryoları  
- Boost PFC çıkışından alan sargısına besleme için **Buck converter** ile alan gerilimi kontrolü  
- **THD analizleri** (0–2625 RPM arası, 12 farklı aşama)  
- Ortalama simülasyon süresi: **~22 saat**

---

## 🇬🇧 Project Description

Hello!  
This project combines an **AC-DC converter** based on the **Bridgeless Boost PFC** topology—which improves power factor and reduces **Total Harmonic Distortion (THD)**—with a **four-quadrant DC motor drive system**. The entire model was designed and simulated in the **MATLAB/Simulink** environment.

### 💡 What Was Done?

- A Bridgeless Boost PFC converter was designed using **Hysteresis Current Control (HCC)** to achieve a **500 V DC output**.  
- The output was applied to a four-quadrant DC motor drive controlled with **Unipolar PWM switching**.  
- The **field weakening technique** was used to allow the motor to operate above its nominal speed.

### 🧪 Simulation Features

- Forward/reverse rotation, braking, and stopping scenarios  
- **Field voltage control** via Buck converter connected to the PFC output  
- **THD analysis** across 12 operating stages (from 0 to 2625 RPM)  
- Approximate simulation time: **~22 hours** on a mid-range computer

---

📌 Bu proje, akademik bir bitirme çalışması kapsamında geliştirilmiştir.  
📌 This project was developed as part of an academic capstone (graduation) project.
