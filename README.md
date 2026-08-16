# APKEDITall
![Screenshot_2025-12-15-10-51-24-94_7c3fb34883d75b964ca4894b441e0887](https://github.com/user-attachments/assets/f12902b1-7fe7-4196-be5a-4823f4019917)

**``ໃຫ້ແອັດເຊ່ນ ຊື່ໃນສຕິງ owner_info``**
**``ໃຫ້ ຂຽນ @string/owner_info``**
**``android:text="@string/owner_info``**
```
<string name="owner_info">"👤OWN : ລັດ
"<font color="#ffffff">🧩CREATE : ANONYMOUS 모</font>"
"<font color="#ffff00">⚙️USER : PREMIUM</font></string>
```

<img width="535" height="123" alt="Screenshot_2026-08-16-09-12-17-84_9bb1ebbbe77763a71e2076eef80e3e18" src="https://github.com/user-attachments/assets/b6ce0a80-07e1-463e-a27e-d91905aa4629" />

```
<string name="b1"><font color="#FFFFFF">WeChat Proxy</font> : <font color="#00FF00">online</font></string>
```
```
<string name="apphome">SUPER<font color="#ffee00"> FAST</font></string>
```
# ແອັດພື້ນຫລັງສອງສີ
**android:background="@drawable/myadd"**
**ໃນ drawable**
```
<?xml version="1.0" encoding="utf-8"?>
<shape
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:aapt="http://schemas.android.com/aapt"
    xmlns:app="http://schemas.android.com/apk/res-auto">
    <gradient
        android:startColor="@color/formy1"
        android:endColor="@color/formy2"
        android:angle="0.0" />
    <corners
        android:radius="24.0dip" />
</shape>
```
**ເພີມໃນ base_src/res/values/color**
```
<color name="formy1">#801aaad6</color>
```
```
<color name="formy2">#80b217bf</color>
```
# ເພິມຂອບ
**YELLOW 🟡**
```
<?xml version="1.0" encoding="utf-8"?>
<selector
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:aapt="http://schemas.android.com/aapt"
    xmlns:app="http://schemas.android.com/apk/res-auto">
    <item>
        <shape
            android:shape="rectangle">
            <solid
                android:color="@android:color/transparent" />
            <corners
                android:radius="24.0dip" />
            <stroke
                android:width="2.0dip"
                android:color="@color/yellow" />
        </shape>
    </item>
</selector>
```
**ພື້ນຫລັງ**
```
android:background=""
```
**ສີ**
```
android:textColor=""
```
**ຂ້ໍຄວາມ**
```
android:text=""
```
**ຕົວຫນາ**
```
android:textStyle="bold"
```
**ຂະຫນາດ**
```
android:textSize=""
```
**ສໄຕ**
```
android:fontFamily="@font/..."
```
**``ສ້າງໃນ base_src/res/font/``**

# ทริคสำหรับ Android (ไม่ต้องเข้าเว็บ)

จำสูตรนี้ไว้ 👇

โครงสร้าง

#AARRGGBB

ตัวอย่าง

#00FFFF + 50%
→ Alpha = 80
→ #80FFFFFF

ใส = 100% → FF

โปร่งใส = 0% → 00


%	Hex

100%	FF

=75%	BF
=50%	80
=25%	40
=10%    1A

<img width="1079" height="1537" alt="Screenshot_2026-08-15-13-52-18-37_5d0571500ced2bca8e5a47a12b5ba108" src="https://github.com/user-attachments/assets/c5eda184-6cab-4247-9fe2-53962f432d21" />

# ເພີ່ມເສັ້ນຂີດຢູ່ລຸ່ມ
```
<TextView
                        android:textSize="14.0sp"
                        android:textStyle="bold"
                        android:textColor="#ffffffff"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_marginBottom="6.0dip"
                        android:text="P R O"
                        android:letterSpacing="0.5" />
                    <View
                        android:background="#00E1FF"
                        android:layout_width="120.0dip"
                        android:layout_height="2.0dip"
                        android:layout_marginBottom="10.0dip" />
```
**ເພິ່ມໄລຍະ ໃຫ້ຫ່າງຈາກລຸ່ມ**
```
android:layout_marginTop="10.0dip"
```
**กกำหนดระยะห่างด้านล่างของ View จากองค์ประกอบถัดไป**
**กำหนดระยะห่างด้านล่างของ เส้นกับสิ่งที่อยู่ข้างล่างเส้นห่างกัน 10dp**
```
android:layout_marginBottom="10.0dip" />
```
# จำง่าย ๆ:

```marginTop``` → ห่างจากด้านบน
```marginBottom``` → ห่างจากด้านล่าง
```marginStart``` → ห่างด้านซ้าย
```marginEnd``` → ห่างด้านขวา
และ 
```marginBottom```
**ไม่ได้ทำให้ตัว View สูงขึ้น แต่เป็นการเพิ่มพื้นที่ว่างหลัง View ครับ.**

**กลุ่มจัดตำแหน่งตรงกลาง**

```
android:gravity="center"
```
 (กลางทั้งแนวตั้งและแนวนอน)
```
android:gravity="center_horizontal"
```
(กลางแนวนอน ซ้าย-ขวา)
```
android:gravity="center_vertical"
```
 (กลางแนวตั้ง บน-ล่าง)

2. **กลุ่มอิงตามทิศทางภาษา (แนะนำให้ใช้)**

```
android:gravity="start"
```
 (ชิดด้านเริ่มต้น
```
android:gravity="end"
```
 (ชิดด้านสิ้นสุด

```
android:gravity="left"
``` 
(ชิดซ้ายตายตัว)
```
android:gravity="right"
```
 (ชิดขวาตายตัว)
```
android:gravity="top"
```
 (ชิดบน)
```
android:gravity="bottom"
``` 
(ชิดล่าง)

```
android:gravity="center_vertical|end"
```
 (กลางแนวตั้งและชิดขวา) 
 
เอาของข้างในไปไว้ "ด้านบนสุด" และ "ชิดซ้าย"*"
```
android:gravity="top|start"
```
เอาของข้างในไปไว้ "ด้านล่างสุด" และ "ชิดขวา"
```
android:gravity="bottom|end"
```
<img width="1080" height="247" alt="Screenshot_2026-08-16-08-33-08-15_9bb1ebbbe77763a71e2076eef80e3e18" src="https://github.com/user-attachments/assets/9b800fd4-e21a-4a2f-aa34-3c5a605ddc33" />

```
<?xml version="1.0" encoding="utf-8"?>
<shape
    android:shape="rectangle"
    xmlns:android="http://schemas.android.com/apk/res/android">
    <gradient
        android:startColor="#00646F"
        android:endColor="#78AB00"
        android:angle="90.0" />
    <corners
        android:radius="12.0dip" />
</shape>
```

# กลุ่มที่ 1: การไล่เฉดสี (Gradient)
```
android:startColor="..."
```
= สีเริ่มต้น (สีจุดแรก)
```
android:endColor="..."
```
= สีสิ้นสุด (สีจุดสุดท้าย)
```
android:centerColor="..."
```
= สีตรงกลาง (ใช้เมื่อต้องการไล่สีแบบ 3 สี)
```
android:angle="..."
```
= องศาการไล่ทิศทางของสี (เช่น 0 คือซ้ายไปขวา, 90 คือล่างขึ้นบน โดยต้องใส่เป็นทวีคูณของ 45 เช่น 0, 45, 90, 180)
```
android:type="..."
```
= รูปแบบการไล่สี
ตัวอย่างการเขียนในโค้ด:
***xml<gradient
    android:startColor="#FF0000" 
    android:centerColor="#00FF00"
    android:endColor="#0000FF"
    android:angle="45" />***

# กลุ่มที่ 2: การทำมุมโค้งมน (Corners)คำสั่งเหล่านี้ต้องเขียนอยู่ภายในแท็ก <corners /> เพื่อใช้ปรับให้ขอบของกล่องมีความโค้งมน ไม่เป็นเหลี่ยมแหลมๆ ครับ
```
android:radius="..."
```
= ปรับให้โค้งมน "เท่ากันทั้ง 4 มุม" พร้อมกันเลย
```
android:topLeftRadius="..."
```
= ปรับความโค้งเฉพาะ "มุมบนซ้าย"
```
android:topRightRadius="..."
```
= ปรับความโค้งเฉพาะ "มุมบนขวา"
```
android:bottomLeftRadius="..."
```
= ปรับความโค้งเฉพาะ "มุมล่างซ้าย"
```
android:bottomRightRadius="..."
```
= ปรับความโค้งเฉพาะ "มุมล่างขวา"ข้อควรระวัง: ถ้าใส่ **android:radius** ไปแล้ว มันจะคุมทับทุกมุม ทั่วไปจึงมักเลือกใช้อย่างใดอย่างหนึ่ง (โค้งเท่ากันหมดใช้ radius ตัวเดียวจบ
เก๋ๆ -->

cornersrs
***android:topLeftRadius="8dp"
    android:topRightRadius="0dp"
    android:bottomLeftRadius="0dp"
    android:bottomRightRadius="8dp" />***

# ຂະຫນາດ ສີ ຟອນ
```
android:textColor="#FF0000"
```
```
android:textSize="20.0sp"
```
```
android:fontFamily="@font/boom"
```
