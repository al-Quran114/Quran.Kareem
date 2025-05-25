# 📖 موقع القرآن الكريم

موقع ويب بسيط لعرض سور وآيات القرآن الكريم مع ميزات الاستماع، التفسير، الترجمة، البحث، المفضلة، والوضع الليلي.

## ✅ الميزات:

- عرض سور وآيات القرآن الكريم.
- الاستماع للتلاوة بصوت العفاسي.
- البحث داخل الآيات أو أسماء السور أو الأرقام.
- عرض التفسير (الجلالين أو السعدي).
- عرض الترجمة (Sahih International أو Yusuf Ali).
- حفظ آخر سورة تم قراءتها.
- إضافة الآيات إلى قائمة المفضلات.
- دعم الوضع الليلي.

## 🛠️ التقنيات المستخدمة

- HTML / CSS / JavaScript
- [API من alquran.cloud](https://alquran.cloud/api)

## 🚀 كيفية التشغيل

1. افتح `index.html` في متصفحك مباشرة.
2. تأكد من الاتصال بالإنترنت لأن الموقع يعتمد على [API alquran.cloud](https://alquran.cloud/).
3. لا حاجة لأي إعدادات خادم — يعمل محليًا.

## 💡 مثال على جزء من الواجهة

```html
<button class="toggle-dark" onclick="toggleDarkMode()">🌙</button>
<h1>القرآن الكريم</h1>
<div class="search-box">
  <input type="text" id="searchInput" placeholder="ابحث في الآيات..." oninput="searchAyat()" />
</div>
<audio controls>
  <source src="https://server8.mp3quran.net/afs/001.mp3" type="audio/mpeg" />
  المتصفح لا يدعم تشغيل الصوت.
</audio>
