# WATER-PUMP-AUTOMATION-PLC-
A PLC-based automation project for smart water supply management. This system intelligently switches between a rainwater harvesting tank and the municipal water network based on tank levels using sensors (S1, S2) and a pump, ensuring a continuous water supply for a building.

# Smart Water Supply Management System (PLC)

**English Description:**
This project presents a PLC-based automation system designed to manage the water supply for a building using two sources: the municipal water network and a rainwater harvesting tank. 

**System Logic:**
- The system monitors the water level in the main tank using two sensors (S1 for High Level, S2 for Low Level).
- **Rainwater Mode:** If there is sufficient rainwater in the tank (above S1), pressing the START button activates the pump to supply the building. The municipal water valve remains closed.
- **Municipal Water Mode:** If the rainwater tank is empty (below S2) or insufficient, the pump is automatically turned off, and the municipal water valve opens to ensure an uninterrupted water supply to the building.

**Hardware & Components:**
- PLC Controller
- Pump
- Solenoid Valve (for Municipal Water)
- Pressure Tank
- Float/Limit Switches (S1, S2)
- START Push Button

---

**توضیحات فارسی:**
این پروژه یک سیستم اتوماسیون مبتنی بر PLC برای مدیریت تامین آب ساختمان از دو منبع "آب شهری" و "مخزن جمع‌آوری آب باران" است.

**منطق عملکرد سیستم:**
- سیستم سطح آب مخزن را با استفاده از دو سنسور (S1 برای سطح بالا و S2 برای سطح پایین) پایش می‌کند.
- **حالت آب باران:** اگر میزان آب باران کافی باشد (بالاتر از سنسور S1)، با زدن کلید START، پمپ روشن شده و آب به ساختمان می‌رسد و شیر آب شهری بسته می‌ماند.
- **حالت آب شهری:** در صورت خالی شدن مخزن (پایین‌تر از سنسور S2) یا ناکافی بودن آب، پمپ به صورت خودکار خاموش شده و شیر برقی آب شهری باز می‌شود تا نیاز ساختمان تامین گردد.

**تجهیزات استفاده شده:**
- کنترلر PLC
- پمپ آب
- شیر برقی (جهت آب شهری)
- منبع فشار
- سنسورهای سطح (S1, S2)
- کلید START
