# fitness nation | Katalog-Motion

Dritte Katalog-Ansicht (eigenes Projekt neben `fn-webkatalog` und `fn-katalog-showroom`):
Showroom-Konzept + **lebende Produkt-Bühnen** — echte Produkt-Freisteller wurden per
Higgsfield/Seedance zu kurzen **360°-Rotations-Clips** animiert (Bodycheck, Terminal,
Vending, TV-Stick; Gates als Kamera-Rundgang). Beim Überfahren der Bühne dreht sich
das Produkt (Touch: spielt im Sichtfeld), dazu Ambient-Mint, Hover-Glow, getönte Wechselseiten.

## Betrieb
- Bauen: `python3 build/build.py` → `site/de|en(+/smart)`; Preise live aus dem Brain
- Clips: `site/assets/video/<name>.mp4` + `<name>_poster.webp` (Quelle: Higgsfield seedance_2_0_mini, Start-Frame = Freisteller auf Mint-Bühne)
- Deploy: push → Vercel (Output Directory `site`, kein Build-Command)
