---
linktitle: สิทธิประโยชน์ทางภาษีอากร
title: สิทธิประโยชน์ทางภาษีอากร
date: "2020-05-09T00:00:00Z"
lastmod: "2020-05-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  export.1:
    parent: คู่มือการปฏิบัติพิธีการ(Export)
    weight: 6

weight: 6
---


## Re-Export   

*ของนําเข้ามาแล้วส่งกลับออกไปภายใน 1 ปี โดยเสียอากร 1 ใน 10* (ตามมาตรา 28 พระราชบัญญัติศุลกากร พ.ศ. 2560) ให้ระบุค่าดังนี้   

- Re-Export = Y (ในส่วนของ Export Declaration Detail)
- Privilege Code = 003
- Export Tariff = 9PART3
- Tariff Code = บันทึกพิกัดศุลกากรให้ตรงกับชนิดของของที่ส่งออก
- Declaration NO = เลขที่ใบขนสินค้าขาเข้าที่อ้างถึง ซึ่งนําของเข้ามาตามมาตรา 28
- Declaration Line Number = รายการในใบขนสินค้าขาเข้าที่อ้างถึง

----------


## ขอคืนอากรตามมาตรา 29 


- Export Tax Incentives ID = เลขทะเบียนผู้ใช้สิทธิประโยชน์ทางภาษีอากรที่นําของออก (ใน
ส่วนของ Export Decalration Detail)
- 19 bis = Y (ในส่วนของ Export Declaration Detail)
- Privilege Code = 003
- Export Tariff = 9PART3
- Tariff Code = บันทึกพิกัดศุลกากรให้ตรงกับชนิดของของที่ส่งออก
- Model Number = เลขที่สูตรการผลิต
- Model Version = เวอร์ชันของสูตรการผลิต
- Model Company Tax Number = เลขประจําตัวผู้เสียภาษีอากรของบริษัทผู้ยื่นสูตร

----------

## คลังสินค้าทัณฑ์บน

**คลังสินค้าทัณฑ์บนส่งออกไปต่างประเทศ** 

- Export Tax Incentives ID = เลขทะเบียนผู้ใช้สิทธิประโยชน์ทางภาษีอากรที่นําของออก
(ในส่วนของ Export Decalration Detail)
- Bond = Y (ในส่วนของ Export Declaration Detail)
- ระบบจะตรวจสอบว่าเลขประจําตัวผู้เสียภาษีอากรของผู้ส่งของออกต้องเท่ากับเลขประจําตัว
ผู้เสียภาษีอากรที่จดทะเบียนคลังสินค้าทัณฑ์บน หรือ ที่เจ้าของคลังทัณฑ์บนได้แจ้งอนุญาตไว้
ในระบบทะเบียนไว้ในระบบผู้ใช้สิทธิประโยชน์ทางภาษีอากร
- Privilege Code = 003
- Export Tariff = 9PART3
- Tariff Code = บันทึกพิกัดศุลกากรให้ตรงกับชนิดของของที่ส่งออกสําหรับคลังสินค้าทัณฑ์บน
ทั่วไป
- Declaration No = เลขที่ใบขนสินค้าขาเข้า
- Declaration Line Number = รายการในใบขนสินค้าขาเข้าที่อ้างถึง
สําหรับคลังสินค้าทัณฑ์บนประเภทโรงผลิต และแบ่งบรรจุ
- Model Number = เลขที่สูตรการผลิต
- Model Version = เวอร์ชันของสูตรการผลิต
- Model Company Tax Number = เลขประจําตัวผู้เสียภาษีอากรของบริษัทผู้ยื่นสูตร

----------

## เขตปลอดอากร (Free Zone)

**ส่งออกจาก เขตปลอดอากร (Free Zone) ไปต่างประเทศ**


- Export Tax Incentives ID = เลขทะเบียนผู้ใช้สิทธิประโยชน์ทางภาษีอากรที่นําของออก
(ในส่วนของ Export Decalration Detail)
- Free Zone = Y (ในส่วนของ Export Declaration Detail)
- ระบบจะตรวจสอบว่าเลขประจําตัวผู้เสียภาษีอากรของผู้ส่งของออกต้องเท่ากับเลขประจําตัว
ผู้เสียภาษีอากรที่จดทะเบียนผู้ ประกอบการในเขตปลอดอากร หรือที่ผู้ ประกอบการใน
เขตปลอดอากรได้แจ้งอนุญาตไว้ในระบบทะเบียนผู้ใช้สิทธิประโยชน์ทางภาษีอากร
- Privilege Code = 003
- Export Tariff = 9PART3
- Tariff Code = บันทึกพิกัดศุลกากรให้ตรงกับชนิดของของที่ส่งออก

----------


## เขตประกอบการเสรี (I-EAT)

**ส่งออกจากเขตประกอบการเสรี (I-EAT) ไปต่างประเทศ**


- Export Tax Incentives ID = เลขทะเบียนผู้ใช้สิทธิประโยชน์ทางภาษีอากรที่นําของออก (ใน
ส่วนของ Export Decalration Detail)
- I-EAT Free Zone = Y (ในส่วนของ Export Declaration Detail)
- ระบบจะตรวจสอบว่าเลขประจําตัวผู้เสียภาษีอากรของผู้ส่งของออกต้องเท่ากับเลขประจําตัว
ผู้เสียภาษีอากรที่จดทะเบียนผู้ประกอบการในเขตประกอบการเสรีหรือที่ผู้ประกอบการใน
เขตประกอบการเสรีได้แจ้งอนุญาตําว้ในระบบทะเบียนผู้ใช้สิทธิประโยชน์ทางภาษีอากร
- Privilege Code = 003
- Export Tariff = 9PART3
- Tariff Code = บันทึกพิกัดศุลกากรให้ตรงกับชนิดของของที่ส่งออก

----------

## ชดเชยค่าภาษีอากร


- Compensation = Y (ในส่วนของ Export Declaration Detail)
- Privilege Code = 003
- Export Tariff = 9PART3
- Tariff Code = บันทึกพิกัดศุลกากรให้ตรงกับชนิดของของที่ส่งออก

----------

## ส่งเสริมการลงทุน BOI 


- BOI = Y (ในส่วนของ Export Declaration Detail)
- Privilege Code = 003
- Export Tariff = 9PART3
- Tariff Code = บันทึกพิกัดศุลกากรให้ตรงกับชนิดของของที่ส่งออก
- BOI License No = เลขที่บัตรส่งเสริมการลงทุน BOI
- กรณีมีการโอนสิทธิ์ BOI ให้ใช้สําเนาใบขนสินค้าขาออกฉบับพิมพ์จากผู้ส่งของออกโดยระบุวันที่
รับบรรทุก (Load Date) พร้อมแสดงรายการการโอนสิทธิ์ BOI ด้วย

----------