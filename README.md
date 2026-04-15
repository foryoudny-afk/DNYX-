# 🖤 DNYX- AI Skill Repository

> **"Scent. Identity. Simpelity."**  
> Ekosistem AI resmi untuk DNYX PROJECT — brand parfum premium lokal Indonesia.

---

## Tentang Repository Ini

Repository ini berisi kumpulan **skill files** yang membentuk ekosistem AI DNYX PROJECT.  
Setiap skill dirancang untuk membantu operasional brand — dari customer service, marketing, memory, analytics, hingga chatbot.

**Brand:** DNYX PROJECT  
**Komunitas:** FAMILIA  
**Stack AI:** Anthropic Claude + Custom Skill System  

---

## 📦 Daftar Skill

### 🧠 Memory & Knowledge

| Skill | Deskripsi |
|-------|-----------|
| `dnyx-memory-engine.skill` | Sistem memori utama — capture, store & recall semua aktivitas brand |
| `dnyx-memory-engine-deep.skill` | Analisa mendalam lintas seluruh memory database, deteksi pola tersembunyi |
| `dnyx-memory-engine-lite.skill` | Versi ringkas & cepat untuk percakapan harian dan quick logging |
| `dnyx-memory-engine-vector.skill` | Memory berbasis semantic search menggunakan vector embeddings |
| `dnyx-cloud-knowledge.skill` | Pusat kecerdasan — sintesis knowledge brand menjadi insight & strategi |
| `dnyx-query-engine.skill` | Terjemahkan business intent menjadi query data yang presisi |

---

### 📊 Analytics & Research

| Skill | Deskripsi |
|-------|-----------|
| `dnyx-analytics-report.skill` | Laporan performa bulanan/mingguan — revenue, sosmed, ecommerce, KOL |
| `dnyx-trend-research.skill` | Deteksi & adaptasi trend dan pergeseran budaya untuk konten DNYX |

---

### 🤖 Chatbot & Customer Service

| Skill | Deskripsi |
|-------|-----------|
| `dnyx-chatbot.skill` | DNYX AI Assistant — simulasi internal CS bot + generate kode deploy ke WhatsApp/Web/IG |

---

### 🎨 Konten & Marketing

| Skill | Deskripsi |
|-------|-----------|
| `dnyx-carousel.skill` | Generator carousel Instagram — 7 slide per varian, caption, hashtag, visual guide |

---

## 🗂️ Struktur Ekosistem

```
DNYX AI ECOSYSTEM
│
├── 🧠 MEMORY LAYER
│   ├── dnyx-memory-engine         ← Core memory
│   ├── dnyx-memory-engine-deep    ← Deep analysis
│   ├── dnyx-memory-engine-lite    ← Quick ops
│   └── dnyx-memory-engine-vector  ← Semantic search
│
├── 💡 KNOWLEDGE LAYER
│   ├── dnyx-cloud-knowledge       ← Knowledge synthesis
│   └── dnyx-query-engine          ← Data querying
│
├── 📈 ANALYTICS LAYER
│   ├── dnyx-analytics-report      ← Performance reports
│   └── dnyx-trend-research        ← Trend detection
│
├── 🤖 ENGAGEMENT LAYER
│   └── dnyx-chatbot               ← CS bot (internal + deploy)
│
└── 🎨 CONTENT LAYER
    └── dnyx-carousel              ← Instagram carousel generator
```

---

## 🔗 Integrasi Antar Skill

```
dnyx-chatbot
    ↓ menggunakan
    ├── dnyx-memory-engine       (simpan history percakapan)
    ├── dnyx-cloud-knowledge     (jawab pertanyaan kompleks)
    └── dnyx-analytics-report    (analisa performa bot)

dnyx-carousel
    ↓ menggunakan
    ├── dnyx-cloud-knowledge     (storytelling & copywriting)
    └── dnyx-trend-research      (carousel berbasis trend terkini)

dnyx-analytics-report
    ↓ menggunakan
    ├── dnyx-memory-engine       (data historis)
    └── dnyx-query-engine        (ekstrak metrics)
```

---

## 🛍️ Produk DNYX PROJECT

| Kemasan | Harga |
|---------|-------|
| Travel Size 10ML | Rp 45.000 |
| Full Size 50ML EDP | Rp 150.000 |
| Recharge Refill 100ML | Rp 239.000 |

### 8 Varian Parfum

| Varian | Tagline | Kategori |
|--------|---------|----------|
| BLOOM | The Serene | 🌿 FRESH |
| HAVEN | The Comfort | 🌿 FRESH |
| LUMINA | The Radiant | 🌿 FRESH |
| EDEN | The Paradise | 🌿 FRESH |
| PRIME | The Power | 🔥 BOLD |
| VELVET | The Seductive | 🔥 BOLD |
| AURA DUSK +62 | The Bold | 🔥 BOLD |
| ECLIPSE | The Provocative | 🔥 BOLD |

---

## 🚀 Cara Install Skill

1. Download file `.skill` yang dibutuhkan
2. Upload ke sistem skill di path: `/mnt/skills/user/`
3. Ekstrak — setiap `.skill` adalah folder berisi `SKILL.md` + `references/`
4. Skill aktif otomatis saat kata kunci yang relevan disebut

---

## 📋 Roadmap Skill

- [x] Memory Engine (core, deep, lite, vector)
- [x] Cloud Knowledge
- [x] Query Engine
- [x] Analytics Report
- [x] Trend Research
- [x] Chatbot (internal + deploy)
- [x] Carousel Generator
- [ ] dnyx-sales-conversion
- [ ] dnyx-copywriter
- [ ] dnyx-offer-pricing
- [ ] dnyx-kol-management

---

## 👤 Kontributor

**foryoudny-afk** — DNYX PROJECT  
AI Ecosystem Architect

---

> *"Setiap skill adalah satu lapisan kecerdasan.*  
> *Bersama, mereka membentuk brand yang berpikir."*  
> — DNYX AI Ecosystem 🖤
