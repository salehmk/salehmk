# 🚀 دليل تفعيل الصفحة الشخصية على GitHub (@salehmk)

تم تصميم هذا المستودع لمحاكاة وتطوير نفس الفكرة والتصميم الرائع لصفحة المهندس أحمد مرعي على GitHub، ومخصصة بالكامل لبياناتك ومشاريعك في تحليل البيانات، وبايثون، و SQL، والويب.

---

## 📁 محتويات هذا المجلد:
1. **[README.md](./README.md)**: الملف الأساسي الذي يظهر على صفحتك الشخصية في GitHub.
2. **[preview.html](./preview.html)**: صفحة ويب تفاعلية لمعاينة التصميم والشكل النهائي قبل أو أثناء النشر في متصفحك.
3. **[.github/workflows/snake.yml](./.github/workflows/snake.yml)**: حركة الثعبان التلقائية (GitHub Actions) التي تأكل مساهماتك على GitHub مثل الصفحة المرجعية.

---

## 🛠️ خطوات النشر خطوة بخطوة:

### 1. إنشاء المستودع الخاص على GitHub:
- توجه إلى: [GitHub New Repository](https://github.com/new).
- في خانة **Repository name**، اكتب اسم حسابك بالضبط: `salehmk`.
- ستظهر لك رسالة مميزة باللون الأخضر:
  > *"salehmk/salehmk is a ✨special✨ repository that you can use to add a README.md to your GitHub profile."*
- تأكد أن المستودع **Public**.
- لا تقم بإضافة README افتراضي إذا كنت ستقوم برفع ملفات هذا المجلد.

### 2. رفع الملفات إلى المستودع:
افتح Terminal أو Git Bash في هذا المجلد ونفذ الأوامر التالية:

```bash
git init
git add .
git commit -m "feat: Add custom GitHub Profile README and workflows"
git branch -M main
git remote add origin https://github.com/salehmk/salehmk.git
git push -u origin main
```

*(أو يمكنك سحب وإفلات الملفات عبر واجهة موقع GitHub مباشرة).*

---

### 3. تفعيل لعبة مساهمات الثعبان (Snake Animation):
لكي يعمل الثعبان الذي يأكل مساهماتك ويتم تحديثه تلقائياً:
1. اذهب إلى صفحة المستودع `salehmk/salehmk` على GitHub.
2. اضغط على **Settings** (الإعدادات).
3. من القائمة الجانبية اختر **Actions** ثم **General**.
4. انزل إلى قسم **Workflow permissions**.
5. اختر **Read and write permissions** ثم اضغط **Save**.
6. اذهب إلى تبويب **Actions** في المستودع، اختر `Generate Snake Animation` ثم اضغط على زر **Run workflow**.

---

### 4. التخصيص السريع (روابطك الخاصة):
داخل ملف `README.md`، يمكنك تعديل القيم التالية بحسب رغبتك:
- استبدال رابط لينكد إن: `https://www.linkedin.com/in/YOUR_USERNAME`
- إضافة أو تعديل أي مهارات تقنية تفضل إبرازها.
