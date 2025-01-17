# Lab-01 Part 2~3 คำสั่ง Console.Write() และ Console.WriteLine()

## 2. การใช้เมดธอด Console.Write()

### 2.1 การใช้เมดธอด Console.Write()
👉 แก้ไขโปรแกรม ให้เป็นดังด้านล่างนี้

```csharp
Console.Write("Hello");
Console.Write("Hello");
```

➢ รันโปรแกรมและบันทึกผล
![ภาพ](https://github.com/AnchisaPhetnoi/03376836-OOP-2566-Lab-01/assets/144197034/f7d6015e-df78-4cfc-8d1e-3305940ec211)


❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
<br>
Helloนั้นมีคำอยู่สองคำซึ่งทั้งสองคำนั้นติดกัน เป็นไปอย่างที่คิด เพราะดูจากโค้ดมีแต่ะConsole.Write("Hello"); ซึ่งใช้ในการเขียนตัวอักษรหรือเพิ่มข้อความแต่ไม่มีโค้ดที่ใช้ในการส่งอักขระขึ้นบรรทัดใหม่ไปยัง console
<br>
### 2.2 การใช้เมดธอด Console.Write() ร่วมกับ  `Environment.NewLine`

`Environment.NewLine` เป็นค่าคงที่ที่ถูกนิยามในภาษา C# เพื่อใช้สำหรับการส่งอักขระขึ้นบรรทัดใหม่ไปยัง console

👉 แก้ไขโปรแกรม ให้เป็นดังด้านล่างนี้

```csharp
Console.Write("Hello" + Environment.NewLine);
Console.Write("Hello" + Environment.NewLine);
```

➢ รันโปรแกรมและบันทึกผล
![ภาพ](https://github.com/AnchisaPhetnoi/03376836-OOP-2566-Lab-01/assets/144197034/c6a4a580-9c5d-4d73-bd6c-bae3fa3d46e2)


❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
<br>
Hello นั้นขึ้นไปยังอีกบรรนทัดหรืออีก console  เป็นไปอย่างที่คิดเพราะในโค้ดของ Hello มีการใช้คำสั่ง ("Hello" + Environment.NewLine); เพื่อใช้สำหรับการส่งอักขระขึ้นบรรทัดใหม่ไปยัง console ผลจึงได้ออกมาเป็น Hello สองบรรทัด
<br>
## 3. เมดธอด Console.WriteLine()

`Console.WriteLine()` เป็นคำสั่งที่เทียบเท่ากับการใช้  `Console.Write` ร่วมกับ  `Environment.NewLine` ทำให้ประหยัดเวลาในการเขียนโปรแกรม
👉 แก้โปรแกรมในเมดธอด Main() ให้เป็นดังต่อไปนี้

```csharp
Console.WriteLine("Hello");
```

➢ รันโปรแกรมและบันทึกผล
![ภาพ](https://github.com/AnchisaPhetnoi/03376836-OOP-2566-Lab-01/assets/144197034/f5a237db-738e-4245-9a3b-1cee61ed882a)


👉 แก้ไขโปรแกรม ให้เป็นดังรูปด้านล่างนี้

```csharp
Console.Write("Hello, ");
Console.WriteLine("World!");
```

➢ รันโปรแกรมและบันทึกผล
![ภาพ](https://github.com/AnchisaPhetnoi/03376836-OOP-2566-Lab-01/assets/144197034/1e2673e6-3c3c-4872-bff9-1647d665563d)

❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
<br>
ผลลัพธ์ที่ได้เป็นไปอย่างที่คิดโดย
<br>
คำสั่ง Console.Write("Hello, "); ใช้เพื่อพิมพ์ข้อความ "Hello, " โดยไม่สร้างบรรทัดใหม่ ซึ่งทำให้ข้อความถัดจากคำสั่งนี้จะถูกพิมพ์ต่อจากข้อความนี้
<br>
คำสั่ง Console.WriteLine("World!"); ใช้เพื่อพิมพ์ข้อความ "World!" และสร้างบรรทัดใหม่หลังจากการพิมพ์ ทำให้ข้อความถัดจากคำสั่งนี้จะถูกพิมพ์บนบรรทัดใหม่
<br>
<br>
❔ จงอธิบายความแตกต่างระหว่างคำสั่ง Console.Write() และ Console.WriteLine()
<br>
Console.Write  พิมย์ข้อความโดยไม่สร้างบรรนทัดใหม่
<br>
Console.WriteLine พิมย์ข้อความและสร้างบรรนทัดใหม่หลังจากการพิมย์
   
<br>

## [4. จำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()](./Lab-01-part-4.md)
