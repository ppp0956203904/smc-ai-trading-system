# SMC AI Trading System

Smart Money Concept (SMC) + AI Trading Platform  
Built with Clean Architecture & Explainable AI mindset

---

## 🎯 Project Goal

ระบบเทรดอัตโนมัติที่:
- ใช้ Smart Money Concept (BOS, CHOCH, FVG, Liquidity)
- แยก logic ออกจาก MT5 / DB / UI อย่างชัดเจน
- ใช้ AI เพื่อช่วย “ตัดสินใจ” ไม่ใช่แทนมนุษย์
- อธิบายได้ทุกไม้ว่า *ทำไมถึงเข้า*

---

## 🧠 Architecture Principles

- **Core ไม่มี IO** (ไม่รู้จัก MT5, DB, API)
- **Application คุม flow**
- **Infrastructure ต่อโลกภายนอก**
- **AI ต้อง explain ได้**
- **ระบบต้องรู้จักหยุดเทรด**

---

## 🏗 Project Structure