# POE2-Calculator
POE2 Calculator for deciding which currency should u trade for
[README.md](https://github.com/user-attachments/files/29363014/README.md)
# Path of Exile 2 Calculator

[TH] โปรแกรมคำนวณและเปรียบเทียบค่าเงินสำหรับเกม Path of Exile 2 เพื่อหาทางเลือกในการแลกเปลี่ยนที่คุ้มค่าที่สุด  
[EN] A currency calculator and comparison tool for Path of Exile 2 to find the most optimal exchange options.

---

## ภาษาไทย (Thai Version)

### รายละเอียดโปรแกรม
เบื่อไหมเวลาที่ได้ไอเทมแพง ๆ มาแต่ไม่รู้จะแลกเป็นอะไรดีให้คุ้มที่สุด? เพราะบางทีแลกออกมาเป็น Divine Orb แล้วมันดันติดทศนิยมสะงั้น โปรแกรมนี้ช่วยคุณแก้ปัญหานั้นได้! ระบบจะช่วยคำนวณและวิเคราะห์ความคุ้มค่าในการแลกเปลี่ยนสกุลเงินต่าง ๆ ในตลาดให้คุณโดยอัตโนมัติ

### วิธีใช้งานเบื้องต้น
1. **เปิดโปรแกรมขึ้นมา**
2. **เช็คราคาไอเทมกับ NPC Anje (แอนจ์):** ตรวจสอบราคาไอเทมปัจจุบัน (ราคาอาจจะคลาดเคลื่อนเล็กน้อยเนื่องจากกลไกตลาดมีการขยับตลอดเวลา แต่สามารถใช้ประมาณราคาได้) ส่วนใหญ่จะนิยมเช็คเป็นสกุลเงินหลักอย่าง **Exalted Orb**, **Divine Orb** และบางครั้งอาจรวมถึง **Chaos Orb** หรืออื่น ๆ
3. **ใส่ข้อมูลราคาไอเทม:** นำมูลค่าของไอเทมที่เรามีไปเช็คค่าเงินแต่ละอย่าง จากนั้นนำค่าเงินเหล่านั้นมาใส่ในรายการสกุลเงินเปรียบเทียบในโปรแกรม
4. **ระบุอัตราแลกเปลี่ยนตลาด:** เช็คอัตราแลกเปลี่ยนระหว่างสกุลเงินทั้งสองจาก NPC Anje แล้วนำมาระบุในโปรแกรม  
   *(หมายเหตุ: ถ้าหากไม่มีสกุลเงินที่ต้องการในลิสต์มาตรฐาน คุณสามารถพิมพ์ชื่อสกุลเงินเองได้ แต่ตัวอักษรต้องตรงกันทั้งในช่องอัตราแลกเปลี่ยนและช่องรายการสกุลเงินแลกเปลี่ยน)*
5. **วิเคราะห์ผล:** กดปุ่ม **"วิเคราะห์ทางเลือกคุ้มสุด"**
6. **ดูผลลัพธ์:** เลื่อนหน้าจอลงด้านล่างเพื่อดูผลลัพธ์การวิเคราะห์ที่คุ้มค่าที่สุด

### คำแนะนำเพิ่มเติม (กรณีมี 3 สกุลเงินขึ้นไป)
หากต้องการเปรียบเทียบตั้งแต่ 3 สกุลเงิน (Currencies) ขึ้นไป ให้นำค่าเงินเหล่านั้นไปเปรียบเทียบกับค่าเงินหลัก (ซึ่งโดยทั่วไปคือ Exalted Orb และ Divine Orb แต่คุณสามารถเปลี่ยนเป็นสกุลเงินอื่นได้หากต้องการ) โดยมีขั้นตอนการตั้งค่าดังนี้:

* **เพิ่มคู่อัตราแลกเปลี่ยนตลาดมาอีก 2 คู่:**
  * **คู่แรกที่เพิ่มมา:** ปรับช่องแรกเป็น *ค่าเงินที่คุณต้องการจะเปรียบเทียบ* และคู่ของมันปรับเป็น *Exalted Orb*
  * **คู่ที่สองที่เพิ่มมา:** ปรับช่องแรกเป็น *Chaos Orb* (หรือค่าเงินหลักที่คุณเลือกใช้) และคู่ของมันปรับเป็น *Divine Orb*

> **ตัวอย่างเพื่อให้เข้าใจง่าย:** แม้ว่าระบบจะรองรับสกุลเงินที่หลากหลาย แต่แนะนำให้ลองทดสอบและทำความเข้าใจด้วยคู่ของ **Exalted Orb** และ **Divine Orb** ก่อนเป็นอันดับแรก เมื่อคุณเข้าใจหลักการทำงานของคู่นี้แล้ว การใช้งานโปรแกรมสำหรับสกุลเงินอื่น ๆ ก็จะไม่ใช่เรื่องยากสำหรับคุณอีกต่อไปครับ!

---

## English Version

### Description
Tired of getting expensive items but not knowing what to exchange them for to get the best value? Sometimes, when you convert them into Divine Orbs, you end up with tricky decimals. This program is here to help! It automatically calculates and analyzes the market rates to ensure you get the absolute most out of your hard-earned loot.

### How to Use
1. **Launch the Program.**
2. **Check Item Prices with NPC Anje:** Verify the current item prices in-game (prices may fluctuate slightly due to the live market, but they provide a solid estimate). Most of the time, you will look at **Exalted Orbs**, **Divine Orbs**, and occasionally **Chaos Orbs** or others.
3. **Input Item Values:** Check the value of your item across different currencies and input those values into the comparison list inside the program.
4. **Set the Market Exchange Rate:** Check the current exchange rate between the two currencies from NPC Anje and fill it into the program.  
   *(Note: If a specific currency is not available in the dropdown, you can type it manually. However, the spelling must match exactly between the Exchange Rate field and the Currency List field).*
5. **Analyze:** Click the **"Analyze Best Option"** (Analyze Exchange Benefit) button.
6. **View Results:** Scroll down to see the breakdown of the most optimal choices.

### Advanced Usage (For 3 or More Currencies)
In cases where you have 3 or more currencies to evaluate, you should compare those values against the main baseline currencies, which are typically Exalted Orbs and Divine Orbs (you can change the baseline currencies if your build or economic goals differ).

* **Add 2 More Market Exchange Rate Pairs:**
  * **First Added Pair:** Set the first slot to *the currency you want to compare* and its counterpart to *Exalted Orb*.
  * **Second Added Pair:** Set the first slot to *Chaos Orb* (or your preferred primary currency) and its counterpart to *Divine Orb*.

> **An Easy Example:** To get a quick grasp of how this works, we highly recommend experimenting with **Exalted Orbs** and **Divine Orbs** first. Once you understand how the program processes these core currencies, scaling it up to other currency combinations will be completely effortless!
