# Power Automate: Automatinis įrangos pirkimo patvirtinimas

## 📋 Aprašymas

Šis Power Automate projektas automatizuoja darbuotojų įrangos pirkimo prašymų valdymą, atsižvelgiant į įrangos vertę:

- 🟢 Jei suma **≤200 EUR/USD** – prašymas automatiškai patvirtinamas.
- 🟠 Jei suma **>200 EUR/USD** – siunčiamas el. laiškas vadovui dėl patvirtinimo.

Projektas taip pat apima savaitinę suvestinę apie visus prašymus.

---

## 🛠️ Naudojimo instrukcija

1. **Importuok srautus į Power Automate:**
   - `flow-approval.zip` – patvirtinimo srautas.
   - `flow-summary.zip` – savaitinės suvestinės srautas.

2. **Pririšk duomenų šaltinį:**
   - SharePoint lentelę arba Microsoft Formą.

3. **Testuok srautus:**
   - Patikrink ar el. pašto pranešimai ir sąlygos veikia kaip numatyta.

---

## 📂 Failų struktūra

- `flow-approval.zip` – pagrindinis srautas, vykdantis patvirtinimą.
- `flow-summary.zip` – srautas, siunčiantis savaitinę suvestinę.
- `Screenshot/`
  - `request-table.png` – SharePoint arba formos prašymų lentelė.
  - `work-flow.png` – Pagrindinio srauto schema.
  - `work-flow-2.png` – Patvirtinimo proceso detalė.

---

## 🖼️ Pavyzdžiai

### 🧾 Prašymų lentelė
![Request Table](Screenshot/request-table.png)

### 🔄 Pagrindinis srautas
![Work Flow](Screenshot/work-flow.png)

### ✅ Patvirtinimo žingsniai
![Work Flow 2](Screenshot/work-flow-2.png)

---

## 💼 Naudojimo scenarijai

Šis sprendimas naudingas įmonėms, kurios nori optimizuoti vidinį IT ar kitos įrangos pirkimo procesą, mažinant rankinio darbo kiekį ir įtraukiant vadovų patvirtinimą tik tada, kai to tikrai reikia.

---

## 📅 Sukūrė

Autorius: Darius  
Data: 2025 m.

