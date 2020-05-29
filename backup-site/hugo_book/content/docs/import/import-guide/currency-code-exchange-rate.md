---
weight: 12
bookFlatSection: true
title: รหัสสกุลเงินและอัตราแลกเปลี่ยน
bookToc: false
---

## รหัสสกุลเงินตราและอัตราแลกเปลี่ยน

### รหัสสกุลเงินตรา (Currency Code) 
- รหัสสกุลเงินตรา (Currency Code) ในส่วน Import Declaration Control ให้บันทึกค่ารหัสสกุลเงินตราตามมาตรฐาน **หากสินค้ามีหลายสกุลเงินตราในใบขนสินค้าให้ใช้รหัสสกุลเงินตราที่มีอัตราแลกเปลี่ยนสูงสุด**
- รหัสสกุลเงินตรา (Currency Code) ในส่วน Import Declaration Control (Invoice) ให้บันทึกค่ารหัสสกุลเงินตราตามมาตรฐาน **หากสินค้ามีหลายสกุลเงินตราในใบขนสินค้าให้ใช้รหัสสกุลเงินตราที่มีอัตราแลกเปลี่ยนสูงสุด**
- รหัสสกุลเงินตรา (Currency) ในส่วน Import Declaration Detail ให้บันทึกค่ารหัสสกุลเงินตราจริงตามมาตรฐาน 

### อัตราแลกเปลี่ยนเงินตรา (Exchange Rate)
-	ให้บันทึกค่าโดยตรวจสอบกับแฟ้มข้อมูลอัตราแลกเปลี่ยนเงินตราขาเข้า 
-	ให้ใช้อัตราแลกเปลี่ยนของสกุลเงินตราที่มีอัตราแลกเปลี่ยนสูงสุด

### หลักการคำนวณราคาของจากเงินตราต่างประเทศเป็นเงินตราไทย
1. การคำนวณราคาของให้เป็นเงินตราไทย ให้ปฏิบัติดังนี้
	- คำนวณตามอัตราแลกเปลี่ยนเงินตราต่างประเทศที่กรมศุลกากรประกาศกำหนด  สำหรับการนำเข้าและการส่งออก 
	- ของที่**นำเข้า** ให้ใช้อัตราแลกเปลี่ยนที่ใช้อยู่ใน **วันนำเข้า**
	-  ของ**ส่งออก**ให้ใช้อัตราแลกเปลี่ยนที่ใช้อยู่ใน **วันที่ออกใบขนสินค้าให้**
2. การประกาศกำหนดอัตราแลกเปลี่ยนเงินตราต่างประเทศ สำนักมาตรฐานพิธีการและราคาศุลกากร จะดำเนินการ ดังนี้
	- พิจารณากำหนดอัตราแลกเปลี่ยนเงินตราต่างประเทศเป็นเงินตราไทย จากข้อมูลของธนาคารแห่งประเทศไทยในรอบ **7 วัน ก่อนวันประกาศ**  โดยใช้**อัตราซื้อสำหรับการส่งออก** และ**อัตราขายสำหรับการนำเข้า**
	- ดำเนินการให้มีการประกาศใช้อัตราแลกเปลี่ยนเงินตราต่างประเทศก่อนสิ้นเดือนไม่น้อยกว่า 7 วัน และมีผลใช้ในเดือนถัดไป หากวันประกาศตรงกับวันหยุดราชการ ให้ประกาศในวันทำการถัดไป
	- กรณีมีการเปลี่ยนแปลงเกี่ยวกับสถานการณ์ทางการเงินหรือในระหว่างเดือน ปรากฏว่าอัตราแลกเปลี่ยนของเงินตราต่างประเทศ เป็นเงินตราไทย**สูงขึ้นหรือลดลงเกินกว่า_ร้อยละ 10_** ของอัตราที่ใช้อยู่อาจประกาศเปลี่ยนแปลงได้ตามความเหมาะสม โดยจะประกาศล่วงหน้าไม่น้อยกว่า 5 วัน ก่อนวันบังคับใช้

{{< button href="https://ecs-support.github.io/knowledge-center/single-page/reference/exchange_rate.html">}}อัตราแลกเปลี่ยนกรมศุลกากร{{< /button >}}