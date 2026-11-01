# Slide Director

สกิลให้ AI ทำสไลด์แบบมีผู้กำกับ คุณเลือกทิศทาง AI ทำงานจากของจริง และงานจบเมื่อใช้ได้จริงบนจอ

AI จะเสนอหน้าปก 3 แบบก่อนทำทั้งเด็ค ส่งตารางรายหน้าพร้อมบทพูดให้อนุมัติ ใช้ภาพจริงเป็นหลัก ไม่แต่งตัวเลข และแยกรายงานสิ่งที่ตรวจแล้วกับยังไม่ได้ตรวจ

## ลงสกิล

### วิธีง่ายสุด

ถ้า AI ของคุณลงสกิลได้ ให้พิมพ์ว่า

```text
ลงสกิลจาก https://github.com/podcharatee/slide-director ให้หน่อย
```

### Claude Code บน macOS และ Linux

```bash
git clone https://github.com/podcharatee/slide-director ~/.claude/skills/slide-director
```

### Claude Code บน Windows PowerShell

```powershell
git clone https://github.com/podcharatee/slide-director "$HOME\.claude\skills\slide-director"
```

### AI ตัวอื่นที่รองรับ SKILL.md

Codex, Gemini CLI และ Copilot CLI อ่านสกิลจาก `~/.agents/skills/` ได้ ส่วนนี้ยังไม่ได้ทดสอบ

```bash
git clone https://github.com/podcharatee/slide-director ~/.agents/skills/slide-director
```

### AI ที่ลงสกิลไม่ได้

คัดลอก Prompt แล้ววางในแชตได้เลย

- [เริ่มเด็คใหม่](prompts/new-deck.md)
- [ตรวจและยกระดับเด็คที่มีอยู่](prompts/audit-deck.md)

## วิธีใช้

เปิดแชตใหม่ แล้วพิมพ์งานตามปกติ เช่น

```text
ทำสไลด์ขายงานให้หน่อย พูด 5 นาทีในห้อง 100 คน ปลายทางเป็น Canva ไฟล์อยู่ในโฟลเดอร์นี้
```

ถ้า AI ไม่หยิบสกิลมาใช้เอง ให้บอกว่า `ใช้สกิล slide-director`

## อัปเดตและถอนการติดตั้ง

macOS และ Linux

```bash
git -C ~/.claude/skills/slide-director pull
```

Windows PowerShell

```powershell
git -C "$HOME\.claude\skills\slide-director" pull
```

ถ้าจะถอนการติดตั้ง ให้ลบโฟลเดอร์ `slide-director` ออก

## มีอะไรในนี้

| ไฟล์ | หน้าที่ |
|---|---|
| `SKILL.md` | ขั้นตอนและกฎที่ AI ใช้ |
| `references/tools.md` | เครื่องมือแยกตามงาน และข้อจำกัดของปลายทาง |
| `prompts/` | Prompt สำหรับ AI ที่ลงสกิลไม่ได้ |

สกิลนี้เป็นไฟล์ข้อความล้วน ไม่มีสคริปต์ ไม่มีรหัสหรือคีย์ และไม่อ้างถึงโฟลเดอร์ในเครื่องของใคร

## ข้อจำกัด

- ข้อจำกัดของ Canva มาจากการใช้งานจริงเมื่อ ต.ค. 2569 และอาจเปลี่ยนแล้ว
- ทดสอบกับ Claude Code เท่านั้น
- เครื่องมือที่ไม่มีให้ใช้ AI จะบอกข้อจำกัดแทนการทำแทน

## License

[MIT](LICENSE)
