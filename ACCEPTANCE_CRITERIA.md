# Acceptance Criteria — M0.1

ใช้ตรวจเอกสารเท่านั้น ไม่ใช่การทดสอบเกมที่ทำงานได้

| ID | เกณฑ์ผ่าน | วิธีตรวจ |
| --- | --- | --- |
| M01 | โฟลเดอร์ใหม่ตามที่ผู้ใช้เลือกมี Markdown ครบห้าไฟล์ตามชื่อที่ขอ | ตรวจรายการไฟล์กับ README |
| M02 | ระบุ Steam indie single-player และ Hybrid Survival/Card Equipment Deckbuilding พร้อม Tactical Turn-based AP/Card Combat | ตรวจ Vision D01–D03 |
| M03 | Map ระบุทางเดินกว้างหนึ่งช่อง ห้อง ประตู บันไดสองปลาย ซอมบี้สุ่มขวางเริ่มต้น และเคลียร์ถาวรยกเว้น Event | ตรวจ Vision D04 โดยไม่เติม Respawn อัตโนมัติ |
| M04 | Semi-random ห้อง/Loot/Event, Event เวลา/สุ่ม/เงื่อนไข, ไฟดับ/น้ำขัดข้อง, Mutant Zombies และ Hostile Humans ครบ | ตรวจ D05–D07 |
| M05 | Horror → Powerful Combos และระยะเวลา Run ที่ผู้เล่นเลือกได้ ไม่มีเวลาตายตัวหรือเกณฑ์บังคับให้ Deck พร้อมก่อนออก | ตรวจ D08–D09 |
| M06 | Multiple Endings แยก Helicopter optional rescue จาก Ground Escape → Endless ต่อเนื่อง; Endless ไม่บังคับทุก Run | ตรวจ D10 และบันทึกการแก้ความเข้าใจ T8/T9 |
| M07 | Endless ใช้ Deck/Equipment เดิม มีทรัพยากรจำกัด ไม่ใช้ Hunger/Thirst เต็มรูปแบบ สู้จนตายและเก็บสถิติ | ตรวจ D11; ไม่ล็อกชนิดทรัพยากรหรือรายการสถิติจากตัวอย่าง |
| M08 | Q10 Collection + Hints และรายละเอียด Room Listening เป็น PROPOSED; progression เป็น UNDECIDED — PLAYTEST; จุดพักยัง PROPOSED | ตรวจ D12–D15 ให้ตรงกันทุกไฟล์ |
| M09 | มีที่มาของการตัดสินใจ ข้อจำกัดประวัติที่อ่านได้ คำถามเปิด และเกณฑ์ตรวจรับ Milestone | ตรวจ Decision Log, ตาราง O01–O10 และ Milestones; ไม่มีคำอ้างต้นทางที่สร้างขึ้น |
| M10 | ไม่มี Code/Engine/Balance/Assets หรือการแก้ไข repository เกมเก่า; ระบุว่าห้ามเริ่ม Implementation ก่อน Game Design และ Production Plan อนุมัติ | ตรวจไฟล์ทั้งหมดและขอบเขตการเปลี่ยนแปลง |

## การตรวจรับของผู้ใช้

- [ ] ผู้ใช้ตรวจรับความถูกต้องของ M0.1
- [ ] หากมีการแก้ข้อสรุป ให้เพิ่มหลักฐานใน Decision Log และปรับทุกไฟล์ที่เกี่ยวข้อง

รายการนี้ยังไม่ถูกทำเครื่องหมายแทนผู้ใช้ การส่งมอบเอกสารไม่ได้อนุมัติข้อเสนอ Q10, Room Listening, จุดพัก หรือ Permanent Progression

## ประตูอนุมัติงานถัดไป

- [ ] Game Design ผ่านอนุมัติในงานถัดไป
- [ ] Production Plan และขอบเขต Prototype/Playtest ผ่านอนุมัติในงานถัดไป

ตราบใดที่สองรายการนี้ยังไม่ผ่าน ห้ามเริ่ม Implementation จากเอกสารชุดนี้ เกณฑ์ตรวจรับที่เสนอสำหรับแต่ละขั้นอยู่ใน [MILESTONES.md](MILESTONES.md)
