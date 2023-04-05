# FinalProject

### ความเป็นมาของโปรแกรม
=เป็นเพราะว่าร้านขายอุปกปรณ์ที่ใหญ่ๆจะเช็คของหรือสินค้าลำบากและเวลาที่มีรถมาซ่อมเยอะๆจะเก็บข้อมูลวันที่หรือราคาลำบากเลยสร้างแอปที่มาตอบสนอง


### วัตถุประสงค์ของโปรแกรม
=บันทึกข้อมูลของอะไหล์สินค้ารถต่างๆเเละบันทึกการรับซ่อมรถของอู๋ซ่อมรถ


### โครงสร้างของโปรแกรม (Class diagram)

```
classDiagram
    Program<|--Form1
    Form1<|--Form2
    Form1<|--Form4
    Form2<|--picturelogocar1
    Form2<|--picturelogocar2
    class Program{
        +Main
    }
    class Form1{
        +button1_Click
        +button4_Clicka
    }

    class Form2{
        +button13_Click()
        +openToolStripMenuItem_Click()
        +button11_Click()
        +button3_Click()
        +button4_Click()
        +button5_Click()
        +button6_Click()
        +button7_Click()
        +button12_Click()
        +button10_Click()
        +button9_Click()
        +button8_Click()
        +button1_Click()
        +saveToolStripMenuItem_Click()
        +button2_Click()
    }
    class Form4{
        +button1_Click()
        +button2_Click()
        +button3_Click()
    }

    class picturelogocar1{
        +string Number()
        +string Name()
        +string Price()
        +string1 Number()
        +string1 Name()
        +string1 Price()
        +string2 Number()
        +string2 Name()
        +string2 Price()
        +string3 Number()
        +string3 Name()
        +string3 Price()
        +string4 Number()
        +string4 Name()
        +string4 Price()
        +string5 Number()
        +string5 Name()
        +string5 Price()
        +string6 Number()
        +string6 Name()
        +string6 Price()
    }
    class picturelogocar2{
        +string7 Number()
        +string7 Name()
        +string7 Price()
        +string8 Number()
        +string8 Name()
        +string8 Price()
        +string9 Number()
        +string9 Name()
        +string9 Price()
        +string10 Number()
        +string10 Name()
        +string10 Price()
    }

```

### ชื่อของผู้พัฒนาโปรแกรม
นายวิชญ์พล ยืนยง 653450103-3
