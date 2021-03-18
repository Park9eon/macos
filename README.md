macos
---

# 크론 탭 추가

```bash

(crontab -l 2>/dev/null; echo "00,20,40 * * * * osascript ${PWD}/warning.scpt") | crontab - ; crontab -l

```
