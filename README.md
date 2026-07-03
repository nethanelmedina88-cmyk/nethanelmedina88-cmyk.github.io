# nethanelmedina88-cmyk.github.io

ריפו דף-הבית (root) של הדומיין `nethanelmedina88-cmyk.github.io`.

תפקידו:
1. **`/.well-known/assetlinks.json`** — אימות Digital Asset Links עבור אפליקציית Coach Medina ב-Google Play (TWA).
   קובץ זה חייב להתארח כאן, בשורש הדומיין (לא בתת-נתיב של פרויקט).
   ⚠ יש להחליף את `REPLACE_WITH_SHA256_FINGERPRINT_FROM_PLAY_APP_SIGNING` בטביעת ה-SHA-256
   של מפתח החתימה (מ-Play Console ← App integrity ← App signing, או מ-PWABuilder), ואז לדחוף מחדש.
2. **`/`** — מפנה אוטומטית לאפליקציה `/coach-medina/`.

`.nojekyll` נדרש כדי ש-GitHub Pages יגיש את תיקיית `.well-known` (Jekyll מתעלם מתיקיות שמתחילות בנקודה).
