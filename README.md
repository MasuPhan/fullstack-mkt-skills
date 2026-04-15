# Fullstack Marketing Skills

> Bo skill marketing toan dien cho AI agent — thiet ke cho thi truong Viet Nam.

Framework **Run By Linh** — 16 skill chuyen dung, 4 agent chuyen biet, 3 workflow tu dong hoa.

---

## Skill nay lam gi?

Bien AI (Claude, ChatGPT, Gemini) thanh **tro ly marketing chuyen nghiep** — tu lap ke hoach, viet content, chay ads, den bao cao hang thang. Moi skill co:

- **Trigger tu dong** — AI nhan dien khi nao can dung
- **Thu thap thong tin** — hoi dung cau, khong thua khong thieu
- **Output co cau truc** — file .md hoan chinh, khong tra loi chung chung
- **Benchmark Vietnam 2025–2026** — so lieu thuc te thi truong VN
- **Cross-reference** — skill nay goi skill khac khi can

---

## Cau truc

```
fullstack-mkt-skills/
├── skills/                  # 16 skill chinh
│   ├── 00-ke-hoach-mkt.md          # Ke hoach MKT toan dien (master)
│   ├── 01-lich-noi-dung.md         # Lich noi dung
│   ├── 02-brief-chien-dich.md      # Brief chien dich
│   ├── 03-danh-gia-hieu-suat.md    # Danh gia hieu suat
│   ├── 04-script-video.md          # Script video
│   ├── 05-copy-quang-cao.md        # Copy quang cao
│   ├── 06-brief-ugc-egc.md         # Brief UGC/EGC
│   ├── 07-bao-cao-marketing.md     # Bao cao marketing
│   ├── 08-nghien-cuu-doi-thu.md    # Nghien cuu doi thu
│   ├── 09-insight-khach-hang.md    # Insight khach hang
│   ├── 10-tinh-kpi-nguoc.md        # Tinh KPI nguoc
│   ├── 11-thiet-lap-kenh.md        # Thiet lap kenh A-Z
│   ├── 12-brief-landing-page.md    # Brief landing page
│   ├── 13-phan-tich-du-lieu.md     # Phan tich du lieu (NEW)
│   ├── 14-email-marketing.md       # Email marketing (NEW)
│   └── 15-social-listening.md      # Social listening (NEW)
├── references/              # Tai lieu tham khao
│   ├── benchmarks-vietnam.md       # Benchmark thi truong VN
│   ├── channel-system.md           # He thong kenh Run By Linh
│   ├── content-angles.md           # Goc do noi dung theo pheu
│   ├── kpi-formulas.md             # Cong thuc tinh KPI
│   └── tool-stack.md               # Cong cu khuyen dung
├── workflows/               # Luong lam viec tu dong
│   ├── campaign-launch.md          # Chay chien dich A-Z
│   ├── monthly-cycle.md            # Chu ky thang
│   └── content-production.md       # San xuat noi dung
├── agents/                  # Agent chuyen biet
│   ├── mkt-strategist.md           # Chien luoc gia
│   ├── content-producer.md         # San xuat noi dung
│   ├── performance-analyst.md      # Phan tich hieu suat
│   └── channel-operator.md         # Van hanh kenh
├── CLAUDE.md                # Huong dan cho Claude Code
├── install.sh               # Cai dat (macOS/Linux)
├── install.ps1              # Cai dat (Windows)
└── examples/                # Vi du output mau
```

---

## Cai dat

### Claude Code (khuyen dung)

```bash
# macOS / Linux
curl -fsSL https://raw.githubusercontent.com/runbylinh/fullstack-mkt-skills/main/install.sh | bash

# Hoac clone ve
git clone https://github.com/runbylinh/fullstack-mkt-skills.git
cd fullstack-mkt-skills
chmod +x install.sh && ./install.sh
```

```powershell
# Windows (PowerShell)
git clone https://github.com/runbylinh/fullstack-mkt-skills.git
cd fullstack-mkt-skills
.\install.ps1
```

### Thu cong

Copy thu muc `skills/` vao `~/.claude/skills/marketing/` (hoac tuong duong tren he thong cua ban).

### Voi ChatGPT / Gemini / Agent khac

Upload cac file `.md` lam **Custom Instructions** hoac **System Prompt**. Moi file skill la mot prompt doc lap — khong can cai dat dac biet.

---

## Su dung nhanh

### Trong Claude Code

```
# Lap ke hoach marketing cho spa
> Lap ke hoach fullstack marketing cho spa cham soc da, ngan sach 30 trieu/thang

# Viet script TikTok
> Viet script TikTok 30s cho son moi moi ra mat

# Danh gia chien dich
> CPMess dang 45K, ROAS 1.8x — danh gia va de xuat toi uu

# Tinh ngan sach
> Can dat 200 trieu doanh thu/thang — tinh nguoc ngan sach ads
```

### Workflow tu dong

```
# Chay toan bo quy trinh ra mat chien dich
> Chay workflow campaign-launch cho san pham moi

# Bao cao + ke hoach thang
> Chay workflow monthly-cycle voi du lieu thang 3
```

---

## So sanh truoc va sau

| Truoc | Sau khi dung skill |
|-------|--------------------|
| "Lap ke hoach MKT di" → tra loi chung chung 500 tu | Output file .md 2000+ tu, 5 phan, co bang bieu, KPI cu the |
| "Viet copy ads" → 1 doan generic | 6 bien the theo 3 tang pheu TOFU/MOFU/BOFU |
| "Bao cao thang" → liet ke so lieu | Nhan dinh truoc, so lieu minh hoa, de xuat co thoi han |
| "Script TikTok" → 1 ban | 2 ban A/B, co hook + CTA + huong dan quay chi tiet |

---

## Dong gop

1. Fork repo
2. Tao branch: `git checkout -b feature/ten-skill-moi`
3. Viet skill theo format trong `CLAUDE.md`
4. Tao PR voi mo ta ro rang

### Quy tac viet skill

- Frontmatter bat buoc: `name`, `description`, `category`, `triggers`, `output`, `related`
- Phai co buoc "Thu thap thong tin" — khong bao gio gia dinh
- Output phai la file .md co cau truc, khong tra loi chung chung
- Benchmark phai ghi nguon va nam cap nhat
- Cross-reference den skill lien quan

---

## License

MIT — tu do su dung, chinh sua, phan phoi.

---

## Credit

- **Framework:** Run By Linh
- **Tac gia:** Linh Nguyen
- **Benchmark:** Thi truong Viet Nam 2025–2026
- **Tuong thich:** Claude Code, ChatGPT, Gemini, Copilot, bat ky AI agent nao doc Markdown
