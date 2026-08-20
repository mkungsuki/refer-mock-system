# ตารางนัดกลาง รพ.ชุมแพ — Mock / Prototype

**⚠️ MOCK — ข้อมูลสมมติทั้งหมด** ชื่อผู้ป่วย, HN, เลขบัตรประชาชน, ชื่อแพทย์ ล้วนสร้างขึ้นเพื่อสาธิต ไม่ใช่ข้อมูลจริง

Interactive prototype ระบบตารางนัดกลางสำหรับนำเสนอผู้บริหาร — ไฟล์เดียวจบ ไม่มี backend (ข้อมูลอยู่ใน localStorage ของเบราว์เซอร์)

- **เปิดใช้งาน:** [index.html](index.html) (GitHub Pages) หรือดาวน์โหลด `appointment-mock.html` เปิดในเครื่อง
- **โพยเดโม:** [demo-script.md](demo-script.md)
- **สเปก + decision log:** [_intake/appointment-system-spec.md](_intake/appointment-system-spec.md)

จุดเด่นที่สาธิต: slot target (หมอ/pool/service/เครื่อง) · โควตา refer แยกจากนัดปกติ · นัดตามระยะแบบ auto-search · ฝั่ง รพช. จองสลอต refer ด้วย CID/ThaiRefer · สิทธิ์ตามบทบาท · วันหยุด/หมอลา + นัดค้าง · นโยบายแทรกเกินเพดาน · dashboard บริหาร · หน้า IT จัดการโครงสร้าง
