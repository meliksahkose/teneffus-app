# Teneffüs — LGS exam prep 2027

> Practice, progress tracking and study plans for Türkiye's LGS high-school entrance exam, built around a large original question bank.

**iOS · Android** · Designed and built end to end by [İbrahim Melikşah Köse](https://github.com/meliksahkose) at [MelberLabs](https://melberlabs.com)

## What it does
- **3,600+ original practice questions** across the LGS subjects, organised by topic and difficulty.
- **Progress tracking and study plans** for 8th-grade students.

## Engineering decisions
- **Content as a pipeline.** Questions are authored, validated and published through a Python content pipeline instead of being hand-entered in a CMS.
- **Database logic is tested.** Supabase migrations ship with pgTAP tests. CI runs type checks, lint, formatting and dependency checks on every push.
- **Stack:** React Native (Expo dev client) · Supabase (Postgres, Edge Functions) · Python (uv) content pipeline · GitHub Actions CI · EAS cloud builds · static marketing site.

---
<sub>Source code is private. Happy to walk through the architecture and code in an interview: meliksahkose90@gmail.com</sub>
