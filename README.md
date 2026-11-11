# Avtoyul Kutubxona — Raqamli Kutubxona va AI Audio Platformasi

Ushbu loyiha kutubxonalardagi an'anaviy qog'oz (katta) daftarlar o'rnini bosuvchi, elektron darsliklarni mutolaa qilish (PDF) hamda Google tabiiy ovozli diktori yordamida audio tinglash imkoniyatiga ega zamonaviy veb-platformadir.

## Imkoniyatlari

- **Elektron Oldi-Berdi Jurnali:** Kitobxonga kitob berish, qaytarib olish, muddatni 7 kunga uzaytirish va holat bo'yicha saralash.
- **Muddati O'tganlarni Nazorat Qilish:** Kechikkan kunlar hisobi va kitobxon uchun tayyor Telegram/SMS eslatma matnini bir tugma bilan nusxalash.
- **Elektron Fond va PDF Mutolaa:** Darsliklar matnini o'qish, tungi rejim, shrift o'lchamini moslash va istalgan `.pdf` faylni biriktirib o'qish.
- **Google O'zbekcha Diktor (Audio Tinglash):** Kitob matnlarini jumlama-jumla, ravon va tushunarli ohangda ovozli o'qish, tezlikni boshqarish (`0.85x` – `1.3x`) va MP3 fayl yuklash.
- **Google AI Studio (Gemini 3.1 Flash TTS):** Yuqori sifatli 24kHz neyron diktor audio generatsiyasi va WAV formatida yuklab olish.
- **Excel (CSV) Eksport:** Barcha hisob-kitoblar va jurnal qaydlarini Excel formatida yuklab olish.

## GitHub Pages orqali 1 daqiqada bepul jonli sayt qilish

1. [GitHub.com](https://github.com/) saytida yangi repository oching (masalan, `avtoyul-kutubxona`).
2. Ushbu arxiv ichidagi `index.html` va `README.md` fayllarini repositoryga yuklang (`Upload files` orqali).
3. Repository sozlamalariga kiring: **Settings** &rarr; **Pages**.
4. **Branch** bo'limida `main` (yoki `master`) tanlab, **Save** tugmasini bosing.
5. 1 daqiqa ichida saytingiz quyidagi manzilda ishga tushadi:
   `https://<sizning-login>.github.io/avtoyul-kutubxona/`

## Git buyruqlari orqali yuklash

```bash
git init
git add .
git commit -m "Avtoyul Kutubxona dastlabki relizi"
git branch -M main
git remote add origin https://github.com/<sizning-login>/avtoyul-kutubxona.git
git push -u origin main
```
