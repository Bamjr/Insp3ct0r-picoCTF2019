# Insp3ct0r - picoCTF 2019

![Challenge Screenshot](https://github.com/user-attachments/assets/e744f82a-7ee6-4a72-bf33-0b821920b64d)

---

## Solution / วิธีแก้ไข

### English Version

1. Open the given link, which will lead you to this website.  
   ![Step 1 Screenshot](https://github.com/user-attachments/assets/54faccb3-31b4-454c-ac0c-7a259e583636)

2. To open the developer tools (Inspector), right-click anywhere on the page and select **Inspect**. Then, go to the **Sources** tab, which contains all the files loaded by the page and may include hidden secret codes.  
   ![Step 2 Screenshot](https://github.com/user-attachments/assets/a06e81c3-49d2-4244-952b-4ce38590ea1f)

3. Inspect all the files (HTML, JS, CSS) inside `problem/44924`. The code is hidden in all of them but split into three parts that you need to arrange by yourself.

   - **Part 1**  
     ![Part 1 Screenshot](https://github.com/user-attachments/assets/fd85e4ec-6266-4f29-b10c-801cc355c3d7)  
   
   - **Part 2**  
     ![Part 2 Screenshot](https://github.com/user-attachments/assets/0ef2cea0-2a7b-4b64-be4e-7f6b344cebe3)  
   
   - **Part 3**  
     ![Part 3 Screenshot](https://github.com/user-attachments/assets/9dafcdea-54f5-4630-b4eb-c8be2b5536b0)

4. Finally, combine the code parts together to get the flag:

```
picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?f10be399}
```

---

### เวอร์ชันภาษาไทย

1. เปิดลิงก์ที่ให้มา ซึ่งจะนำคุณไปยังเว็บไซต์นี้  
   ![ภาพหน้าจอขั้นตอนที่ 1](https://github.com/user-attachments/assets/54faccb3-31b4-454c-ac0c-7a259e583636)

2. เปิด Developer Tools (Inspector) โดยคลิกขวาที่หน้าเว็บ แล้วเลือก **Inspect** จากนั้นไปที่แท็บ **Sources** ซึ่งเป็นแหล่งรวมไฟล์ทั้งหมดที่โหลดอยู่บนหน้าเว็บ และอาจมีรหัสลับซ่อนอยู่  
   ![ภาพหน้าจอขั้นตอนที่ 2](https://github.com/user-attachments/assets/a06e81c3-49d2-4244-952b-4ce38590ea1f)

3. ตรวจสอบไฟล์ทั้งหมด (HTML, JS, CSS) ในโฟลเดอร์ `problem/44924` คุณจะพบว่ารหัสถูกแบ่งเป็น 3 ส่วน ซึ่งต้องนำมารวมกันเอง  
   
   - **ส่วนที่ 1**  
     ![ภาพส่วนที่ 1](https://github.com/user-attachments/assets/fd85e4ec-6266-4f29-b10c-801cc355c3d7)  
   
   - **ส่วนที่ 2**  
     ![ภาพส่วนที่ 2](https://github.com/user-attachments/assets/0ef2cea0-2a7b-4b64-be4e-7f6b344cebe3)  
   
   - **ส่วนที่ 3**  
     ![ภาพส่วนที่ 3](https://github.com/user-attachments/assets/9dafcdea-54f5-4630-b4eb-c8be2b5536b0)

4. นำรหัสทั้งสามส่วนมารวมกัน จะได้คำตอบสุดท้ายคือ:

```
picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?f10be399}
```

