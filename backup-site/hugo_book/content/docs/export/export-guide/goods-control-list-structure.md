---
title: โครงสร้างใบกำกับการขนย้าย
weight: 10
bookFlatSection: true
bookToc: true
---

โครงสร้างข้อมูลใบกำกับการขนย้ายสินค้า
===

## ใบกํากับการขนย้ายสินค้า แบ่งออกเป็น 2 ส่วน ได้แก่
1. [**Goods Transition Control**](#goods-transition-control) ประกอบด้วย 31 Field
2. [**Goods Transition Detail**](#goods-transition-detail) ประกอบด้วย 8 Field


## เงื่อนไขการบันทึกข้อมูล ในกรณีผู้บันทึกไม่สามารถหาข้อมูลได้

1. หาก Field ใด กำหนดให้ต้องระบุค่า **(Value = M)** แต่ผู้บันทึกไม่สามารถหาข้อมูลได้
- สำหรับ Field ที่เป็น Alphabet (แสดงออกเป็นตัวอักษร) ให้ระบุค่าเป็น N/A 
- สำหรับ Field ที่เป็น Numeric (แสดงออกเป็นตัวเลข) ให้ระบุค่าเป็น 0 (ศูนย์)
2. หาก Field ใด กำหนดให้ไม่ต้องระบุค่า **(Value = O)** และผู้บันทึกไม่สามารถหาข้อมูลได้ ก็ไม่ต้องบันทึกค่าใด ๆ 
3. หาก Field ใด กำหนดให้ต้องระบุค่า เมื่อเข้าเงื่อนไขที่กำหนด **(Value = C)** แต่ผู้บันทึกไม่สามารถหาข้อมูลได้
- สำหรับ Field ที่เป็น Alphabet (แสดงออกเป็นตัวอักษร) ให้ระบุค่าเป็น N/A 
-  สำหรับ Field ที่เป็น Numeric (แสดงออกเป็นตัวเลข) ให้ระบุค่าเป็น 0 (ศูนย์)
	
## อักษรย่อ ที่ใช้ในการอธิบายรูปแบบชนิดของข้อมูล

|  อักษรย่อ   |	คำอธิบาย  |
|:------------:|----------------------------|
|n3 |ข้อมูลชนิดตัวเลข (Numeric Characters) คงที่คือ 3 ตัวอักษร|
|a3  |	ข้อมูลชนิดตัวอักษร (Alphabetic Characters) คงที่คือ 3 ตัวอักษร|
|an3  |	ข้อมูลชนิดตัวอักษรหรือตัวเลข คงที่ คือ 3 ตัวอักษร|
|n..3|	ข้อมูลชนิดตัวเลขความยาวข้อมูลแปรผันตามความยาวสูงสุด 3 ตัวอักษร|
|a..3|	ข้อมูลชนิดตัวอักษรความยาวข้อมูลแปรผันตามความยาวสูงสุด 3 ตัวอักษร|
|an..3  |	ข้อมูลชนิดตัวอักษรหรือตัวเลขความยาวข้อมูลแปรผันตามความยาวสูงสุด 3 ตัวอักษร|
|n..16,2|ข้อมูลชนิดตัวเลขความยาวข้อมูลแปรผันตามความยาวสูงสุด 16 ตัวอักษรรวมความยาวทศนิยมสูงสุด 2 ตัวอักษร|

### Goods Transition Control

![](https://github.com/ecs-support/knowledge-center/raw/master/img/export/export-guide/e-Export-guidejpg_Page55.jpg)

![](https://github.com/ecs-support/knowledge-center/raw/master/img/export/export-guide/e-Export-guidejpg_Page56.jpg)

![](https://github.com/ecs-support/knowledge-center/raw/master/img/export/export-guide/e-Export-guidejpg_Page57.jpg)

![](https://github.com/ecs-support/knowledge-center/raw/master/img/export/export-guide/e-Export-guidejpg_Page58.jpg)

![](https://github.com/ecs-support/knowledge-center/raw/master/img/export/export-guide/e-Export-guidejpg_Page59.jpg)

![](https://github.com/ecs-support/knowledge-center/raw/master/img/export/export-guide/e-Export-guidejpg_Page60.jpg)


### Goods Transition Detail

![](https://github.com/ecs-support/knowledge-center/raw/master/img/export/export-guide/e-Export-guidejpg_Page61.jpg)

![](https://github.com/ecs-support/knowledge-center/raw/master/img/export/export-guide/e-Export-guidejpg_Page62.jpg)