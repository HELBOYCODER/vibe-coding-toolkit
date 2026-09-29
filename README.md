# 🛠️ بهترین ابزارهای کدنویسی و Vibe Coding — ۲۰۲۶

> لیست منتخب ابزارها، پلاگین‌ها و نصبی‌های مهم — مخصوص HELBOYCODER
> آخرین به‌روزرسانی: سپتامبر ۲۰۲۶

---

## ۱. عامل‌های کدنویسی AI (AI Coding Agents) — رده اول

| ابزار | نوع | چرا؟ |
|---|---|---|
| **Claude Code** | Terminal-first agent | بهترین عامل تعاملی؛ ادیت چند-فایلی، اجرای دستور، خودآزمایی با تست. افزونه VS Code، JetBrains، وب و Slack هم داره |
| **Cursor (Agent Mode)** | IDE هوش مصنوعی (فورک VS Code) | پرفروش‌ترین IDE هوش مصنوعی؛ Sub-agents موازی، AI Code Review، پشتیبانی از چند مدل (GPT، Claude، Grok) |
| **OpenAI Codex** | Agent | گزینه اصلی برای کار خودکار جدی، هم‌رده Claude Code |
| **Windsurf / Devin Desktop** | IDE / عامل | خودکارترین گزینه؛ مهاجرت‌ها، refactor و رفع باگ رو کامل سپاری می‌کنه |
| **Gemini CLI** | عامل ترمینال | بهترین رایگان؛ متن‌باز، از گوگل |
| **Grok Build (xAI)** | عامل + مدل | مدل Grok 4.5 با قیمت ارزان ($2/$6)، داخل Cursor هم موجوده |
| **OpenCode** | عامل متن‌باز | بهترین متن‌باز؛ پشتیبانی LSP و MCP، افزونه برای VS Code/Cursor/Zed/Windsurf |

## ۲. افزونه‌های VS Code (برای Cursor/Windsurf هم کار می‌کنن)

### هوش مصنوعی
- **Claude Code for VS Code** — عامل Claude بدون خروج از IDE (۲۳M نصب)
- **GitHub Copilot** — تکمیل خودکار کلاسیک + Copilot Chat
- **Continue** — عامل کد هوش مصنوعی متن‌باز
- **Windsurf Plugin (Codeium)** — تکمیل خودکار رایگان و سریع
- **Qodo** — self-review کد قبل از کامیت
- **Augment Code** — مخصوص کدبیس‌های بزرگ و پیچیده
- **Kimi Code / Qwen Code Companion** — گزینه‌های مدل‌های چینی

### Git و همکاری
- **GitLens** — تاریخچه فایل، blame خطی، کانتکست کامیت
- **GitHub Pull Requests** — مدیریت PR و Issue داخل VS Code
- **Git Graph** — نمای گرافیکی شاخه‌ها

### کیفیت کد
- **ESLint / Ruff** — لینت JS/TS و Python
- **Prettier** — فرمت‌کننده خودکار
- **Error Lens** — نمایش خطاها همان‌جا که هستی
- **Code Spell Checker**

### بهره‌وری و تست
- **Playwright Test for VS Code** — تست E2E مرورگری داخل ادیتور
- **REST Client** — تست API بدون Postman
- **Docker / Container Tools** — مدیریت کانتینر
- **Remote Development Pack** — کار روی سرور، WSL، کانتینر
- **Path IntelliSense** و **JavaScript (ES6) Snippets**

## ۳. ابزارهای موبایل برای کنترل عامل‌ها (از راه دور)

| ابزار | توضیح |
|---|---|
| **CodeAgent Mobile** | کنترل Claude Code، Codex، Cursor و... از گوشی — پهن‌ترین پشتیبانی |
| **Omnara** | مرکز فرماندهی Claude Code و Codex؛ تأیید مجوزها از گوشی |
| **Cursor iOS** | چت با Cursor از موبایل (فقط پرسش و پاسخ، نه کنترل فایل) |

## ۴. لیست نصبی‌های مهم (ترمینال)

```bash
# --- عامل‌های کدنویسی ---
npm install -g @anthropic-ai/claude-code   # Claude Code
npm install -g @google/gemini-cli          # Gemini CLI (رایگان)
npm install -g opencode-ai                 # OpenCode متن‌باز

# --- ابزارهای پایه ---
npm install -g pnpm                        # پکیج منیجر سریع
curl -LsSf https://astral.sh/uv/install.sh | sh   # uv (پایتون سریع)

# --- ابزارهای Git ---
git config --global init.defaultBranch main
# (توکن GitHub قبلاً روی این دستگاه تنظیم شده ✅)
```

## ۵. اتصال GitHub این دستگاه ✅

- اکانت: **HELBOYCODER** (HELBOY CODER)
- ۶۷ ریپو قابل دسترسی (۵۷ عمومی، ۱۰ خصوصی)
- Credential helper: فعال — push/pull بدون توکن اضافی
- ایمیل git: `HELBOYCODER@users.noreply.github.com`

## ۶. پیشنهاد شروع سریع

1. **Claude Code** رو نصب کن (عامل اصلی کار روزمره)
2. **Cursor** رو برای پروژه‌های جدی امتحان کن (رایگان شروع می‌شه)
3. افزونه‌های GitLens + Error Lens + Prettier + ESLint رو تو VS Code نصب کن
4. برای کار از راه دور با موبایل: **Omnara** (اگه با Claude Code کار می‌کنی)

---

*ساخته‌شده توسط LOL · The Joker 🃏 — ما می‌تونیم بخندیم و همچنان فیکسش کنیم.*
