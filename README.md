# dtwinuz/homebrew-tap

[bitg](https://bitg.uz) uchun Homebrew tap. bitg — yozayotganingizda o'zbek matnini 2026-yilgi yangi lotin
alifbosiga (ö ğ ş ç) o'giradigan kiritish usuli.

[![ci](https://github.com/dtwinuz/homebrew-tap/actions/workflows/ci.yml/badge.svg)](https://github.com/dtwinuz/homebrew-tap/actions/workflows/ci.yml)
[![bitg](https://img.shields.io/github/v/release/dtwinuz/bitg?label=bitg)](https://github.com/dtwinuz/bitg/releases/latest)

**[bitg.uz](https://bitg.uz) · [Jonli demo](https://wonmor.io/demo/bitg/) · [bitg repo](https://github.com/dtwinuz/bitg) · [Releases](https://github.com/dtwinuz/bitg/releases)**

<p align="center"><a href="https://wonmor.io/demo/bitg/"><img src="https://raw.githubusercontent.com/dtwinuz/bitg/main/docs/screenshots/try.jpg" width="820" alt="bitg: eski yozuvdagi matn yozish paytida 2026-yilgi lotin alifbosiga o'tadi, inglizcha so'zlar o'zgarmaydi"></a></p>

```bash
brew install --cask dtwinuz/tap/bitg
```

So'ng tizimdan chiqib qayta kiring va **Tizim sozlamalari → Klaviatura → Kiritish manbalari → + → bitg** ni qo'shing.
Almashtirish: **Control + Probel**.

| Buyruq | Nima qiladi |
|---|---|
| `brew upgrade --cask bitg` | yangi versiyaga o'tkazadi |
| `brew uninstall --cask bitg` | dasturni o'chiradi |
| `brew uninstall --cask --zap bitg` | sozlamalar bilan birga o'chiradi (`~/Library/Application Support/bitg`) |

Mac versiyasi **sinov bosqichida** va hozircha Apple imzosiz. Muammo bo'lsa: [bitg.uz/fikr](https://bitg.uz/fikr/)
yoki [issues](https://github.com/dtwinuz/bitg/issues).

---

**English.** Homebrew tap for [bitg](https://bitg.uz), an input method that converts Uzbek text to the 2026 Latin
alphabet as you type. Install with `brew install --cask dtwinuz/tap/bitg`, log out and back in, then add bitg under
System Settings → Keyboard → Input Sources. macOS 11+, Apple silicon and Intel (one universal package). Beta, not
notarized yet.

Cask o'zi yangilanadi (`autobump` workflow, har 3 soatda): bitg'ning yangi relizi chiqsa, `.pkg` SHA-256 va SLSA
attestation (dtwinuz/bitg `build.yml`, shu teg) bilan tekshiriladi, cask haqiqiy macOS'da o'rnatib-o'chirib sinaladi va
faqat shundan keyin main'ga yoziladi. `ci` har o'zgarishda va har dushanba o'sha sinovni qaytaradi.
