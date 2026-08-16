# খুলনা রেঞ্জ রিপোর্ট সিস্টেম — GitHub Pages

এটি একটি static, GitHub Pages-ready রিপোর্ট viewer। সরবরাহ করা Excel workbook-এর ৬টি Sheet এবং সরবরাহ করা Document-এর tables `data/reports.json`-এ রাখা হয়েছে।

## Publish
1. GitHub-এ নতুন repository তৈরি করুন।
2. এই folder-এর `index.html`, `style.css`, `script.js`, `README.md` এবং `data/` folder upload করুন।
3. Repository → Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. কয়েক মিনিট পরে GitHub Pages URL পাওয়া যাবে।

## গুরুত্বপূর্ণ
এটি বর্তমানে **static viewer**। GitHub Pages নিজে database/backend নয়। নতুন রিপোর্ট অনলাইনে সংরক্ষণ, login/admin, edit approval বা permanent submission দরকার হলে backend (যেমন Supabase/Firebase/Apps Script) যোগ করতে হবে।
