# Lab-01 Part 5 การกำหนดความกว้างของอาร์กิวเมนต์

เราสามารถแกหนดตำแหน่งของอักขระที่จะพิม์ออกทาง output ได้ โดยการใช้รูปแบบ { i, j }
โดย i ยังคงเป็นลำดับที่ตามตำแหน่งของ place holder และ j คือจำนวนช่องว่างทีต้องการ

👉แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
Console.WriteLine("00000000011111111112");
Console.WriteLine("12345678901234567890");
Console.WriteLine("{0, 0}", 1);
Console.WriteLine("{0, 1}", 1);
Console.WriteLine("{0, 2}", 1);
Console.WriteLine("{0, 3}", 1);
Console.WriteLine("{0, 5}", 1);
Console.WriteLine("{0, 10}", 1);
Console.WriteLine("{0, 15}", 1);
Console.WriteLine("{0, 20}", 1);
```

หมายเหตุ ตัวเลขสองบรรทัดบนสุด ใช้เพื่อกำหนดตำแหน่ง column ของตัวอักษร

➢ รันโปรแกรมและบันทึกผล
![ภาพ](https://github.com/AnchisaPhetnoi/03376836-OOP-2566-Lab-01/assets/144197034/33ba57b4-13be-47b3-b5f8-8d13a6e746a9)

 
❔ การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , } ในคำสั่ง ``Console.WriteLine()`` มีรูปแบบการใช้งานอย่างไร
<br>
มีรูปแบบการใช้งานดังนี้
<br> Console.WriteLine("{index, width}", arg);
<br>
    index คือ ตำแหน่งของอาร์กิวเมนต์ (เริ่มต้นที่ 0)
    <br>
    width คือ ความกว้างที่ต้องการให้อาร์กิวเมนต์มี
    <br>
    arg   คือ การเก็บค่าตัวแปรของข้อมูลให้อยู่ในตัวแปรเดียวกันของการเก็บข้อมูลทั้งหมด
<br>
## 6. การกำหนดรูปแบบของอาร์กิวเมนต์

👉 แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
int n = 123456789;
Console.WriteLine("{0, 0:E}", n);
Console.WriteLine("{0, 0:F}", n);
Console.WriteLine("{0, 0:G}", n);
Console.WriteLine("{0, 0:N}", n);
Console.WriteLine("{0, 0:P}", n);
Console.WriteLine("{0, 0:X}", n);
```

➢ รันโปรแกรมและบันทึกผล
![ภาพ](https://github.com/AnchisaPhetnoi/03376836-OOP-2566-Lab-01/assets/144197034/497eafbb-f709-4cd3-85e0-11d42068df77)

❔  การกำหนดตัวอักษร E, F, G, N, P, X หมายถึงให้พิมพ์ออกมาเป็นอะไร <br>
    E: Scientific notation = การแสดงผลทางวิทยาศาสตร์
    <br>
    F: Fixed-point notation = การแสดงผลที่มีจุดทศนิยมตามที่กำหนด
    <br>
    G: General format = รูปแบบทั่วไป - จะเลือกใช้ E หรือ F ตามที่เหมาะสม
    <br>
    N: Number format = การแสดงผลเป็นตัวเลขที่มีคั่นพันล้าน
    <br>
    P: Percentage format = รูปแบบเปอร์เซ็นต์
    <br>
    X: Hexadecimal format = รูปแบบเลขฐานสิบหก
 <br>

## 7. การกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์

👉 แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
int n = 123456789;
Console.WriteLine("{0, 20:E}", 1);
Console.WriteLine("{0, 20:F}", 1);
Console.WriteLine("{0, 20:G}", 1);
Console.WriteLine("{0, 20:N}", 1);
Console.WriteLine("{0, 20:P}", 1);
Console.WriteLine("{0, 20:X}", 1);
```

➢   รันโปรแกรมและบันทึกผล
![ภาพ](https://github.com/AnchisaPhetnoi/03376836-OOP-2566-Lab-01/assets/144197034/43c195d0-a9d3-4d3d-8dae-a1f0b233ccfb)

 
## [Part 8  การกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์](./Lab-01-part-8.md)
