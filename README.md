# Audit CRM — คอนแทคลูกค้างานสอบบัญชี (TPN Audit)

เว็บแอปไฟล์เดียว (no build) สำหรับติดตามคอนแทคลูกค้างานสอบบัญชี

- **ลูกค้า** — บันทึกคอนแทคตามลำดับ, เลือก stage (เคยมีส่งงานแล้ว / Add Line + ฝากคอนแทคแล้ว / ยังไม่ได้แอดไลน์), remark, เบอร์/Line
- **Budget** — Expected Budget รายลูกค้า: จำนวนงบที่คาด × ค่าสอบเฉลี่ยต่องบ = รายได้คาดปีหน้า พร้อม dashboard รวม + กราฟ + export Excel
- **Sync ข้ามเครื่อง** — ข้อมูลเข้ารหัส AES-256-GCM ด้วย PIN ก่อนส่งขึ้น repo ส่วนตัว `tpnaudit/audit-tracker-data` (ไฟล์ `crm.enc.json`) — ใช้ PIN ตัวเดียวกับ Audit Tracker
- ข้อมูลหลักเก็บใน localStorage ของแต่ละเครื่อง มีสำรอง/กู้คืน JSON

เปิดใช้: https://tpnaudit.github.io/audit-crm
