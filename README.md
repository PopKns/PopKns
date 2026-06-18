### สวัสดีครับ 👋 I'm Pop

**Aspiring Data Engineer** — ผมชอบสร้าง data pipeline ที่ *ทนทาน ทดสอบได้ และนำไปใช้ได้จริง*
แล้วต่อยอดเป็น analysis + เครื่องมือที่คนอื่นเอาไปใช้ต่อได้

I build resilient, tested, production-minded data pipelines — then turn them into analysis and tools people can actually use.

- 🔭 **กำลังโฟกัส:** เก็บ → ทำความสะอาด → วิเคราะห์ ข้อมูลตลาด *จริง* แล้วเปลี่ยนเป็น insight
- 🛠️ **Stack:** Python · pandas · scikit-learn · Streamlit · pytest · GitHub Actions (CI) · SQL
- 🌏 Thailand · ทำงานได้ทั้งภาษาไทยและอังกฤษ
- 📫 ติดต่อ: **pop.kns@gmail.com**

---

#### 🚀 Featured projects

### 1 · [thai-freelance-market-analysis](https://github.com/PopKns/thai-freelance-market-analysis)
Data product แบบ **end-to-end** ที่วิเคราะห์ตลาดฟรีแลนซ์ไทย (Fastwork) — *ตลาด ณ ปัจจุบัน*
🔗 **Live demo:** https://thai-freelance-market-analysis-myvghxmmjph2yhesn9kvwa.streamlit.app/

| | |
|---|---|
| 🔌 **Data Engineering** | สุ่มตัวอย่าง ~3,000 gig (seeded, ทำซ้ำได้) จากตลาด 222k — rate-limited, cached, anonymized ตาม PDPA → clean → analyze (pipeline แยก stage ชัด) |
| 📊 **Dashboard** | Streamlit 4 แท็บ: แนะนำราคา · แผนที่ดีมานด์ · ค้นหาโอกาส · คัดกรองความน่าเชื่อถือ |
| 🤖 **ML** | **prototype** คัดกรองความผิดปกติแบบ unsupervised — IsolationForest + rule flags + เหตุผลที่อธิบายได้ (เป็น *triage* ให้คนตรวจ ไม่ใช่ตัวฟันธง) |
| ✅ **Engineering rigor** | 16 unit tests · ruff lint · GitHub Actions CI · เอกสาร ethics/compliance |

### 2 · [thai-freelance-trends](https://github.com/PopKns/thai-freelance-trends)
ตลาดเดียวกันแต่เพิ่ม **มิติเวลา** — ตลาดเปลี่ยนยังไงตั้งแต่ 2019 (โดยเฉพาะหลัง AI)
🔗 **Live demo:** https://thai-freelance-trends-dvynwtjqmevbmtt7xfnudg.streamlit.app/

| | |
|---|---|
| 💡 **Resourcefulness** | gig ไม่มีวันที่สร้าง → reconstruct ตลาดย้อนหลังจาก **Wayback Machine** (56k gig, 2019–2026) |
| 📈 **Analysis** | ส่วนแบ่งหมวดตามเวลา + trend slope/R² (แยก trend จริง/noise) + before/after AI — งานดิจิทัลที่ AI ทำแทนได้หดทั้งแผง |
| 🔬 **Statistical honesty** | จัดการ bias อย่างชัดเจน: ใช้ share ไม่ใช่ raw counts, archive-year เป็น proxy, correlation ≠ causation |

---

<sub>โปรเจกต์เหล่านี้ต่อยอดกัน — ตัวที่ 1 = ตลาดวันนี้, ตัวที่ 2 = ตลาดข้ามเวลา · More coming soon.</sub>
