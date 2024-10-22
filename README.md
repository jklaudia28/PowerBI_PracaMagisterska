# PowerBI_PracaMagisterska

1. Start
![image](https://github.com/user-attachments/assets/9ee13cc6-f8e6-40b6-b0af-d48aef0dba5b)

2. Main info
![image](https://github.com/user-attachments/assets/43e90939-caa8-4df9-aee9-857a84dcaf15)

Slicers:
![image](https://github.com/user-attachments/assets/e9ea013b-0ddf-48c5-932c-ad795cfdb148)

3. Brand comparison
![image](https://github.com/user-attachments/assets/15335106-cb26-4742-99d6-c0720cdab1a8)

MEASURES PARAMETER = {
    ("PRODUCTIVITY (SALES)", NAMEOF('Hours'[PRODUCTIVITY (SALES)]), 0),
    ("PRODUCTIVITY (UNITS)", NAMEOF('Hours'[PRODUCTIVITY (UNITS)]), 1),
    ("SALES / M2", NAMEOF (Sales[SALES / M2]), 2),
    ("SOLD UNITS / M2", NAMEOF (Sales[SOLD UNITS / M2]), 3),
    ("DELIVERY / M2", NAMEOF (Delivery[DELIVERY / M2]),4),
    ("USED WORKING HOURS", NAMEOF (Hours[USED WORKING HOURS]),5)
}

TIME PARAMETER = {
    ("YEAR", NAMEOF('Calendar'[YEAR]), 0),
    ("QUARTER", NAMEOF('Calendar'[QUARTER]), 1),
    ("MONTH", NAMEOF('Calendar'[MONTH]), 2)
}

4. World Overview
   ![image](https://github.com/user-attachments/assets/93e3631f-003d-424b-b5f9-b3a484142534)

