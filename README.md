# 🕋 خريطة مشعر منى التفاعلية
# Mina Hajj Interactive Map

**دليل الحاج الذكي | Smart Hajj Guide**
---
بيانات رسمية من دليل الكشافة السعودية 1446هـ

## 🗺️ الميزات | Features
- 📍 **624 مخيم** محدد بإحداثيات دقيقة GPS
- 🏥 **8 مستشفيات** + 26 مركز صحي + 23 مركز إسعاف
- 🚒 **44 وحدة دفاع مدني** موزعة على 7 مناطق
- 👮 **10 مراكز شرطة** مع أرقام الطوارئ
- ⚕️ **12 مركز نسك عناية**
- 🚂 **3 محطات قطار المشاعر**
- 🔍 **بحث فوري** عن المخيم برقم الشارع + المخيم
- 🧭 **أقصر طريق مشياً** عبر OSRM
- 🗺️ **فتح في Google Maps** مع المسار الصحيح
- 🌐 **ثنائي اللغة** عربي / English
- 📌 **أقرب المواقع** حسب موقعك
- 👤 **تسجيل دخول** بحساب Google لحفظ المخيم

## 🚀 نشر على GitHub Pages | Deploy to GitHub Pages

1. أنشئ **repository** جديد على GitHub
2. ارفع `index.html` 
3. اذهب إلى **Settings → Pages**
4. اختر **Branch: main / root**
5. احصل على رابطك: `https://username.github.io/repo-name`

## ⚙️ Google OAuth (اختياري)
لتفعيل تسجيل الدخول الحقيقي:
1. [Google Cloud Console](https://console.cloud.google.com)
2. APIs & Services → Credentials → Create OAuth 2.0 Client
3. الصق الـ Client ID في السطر:
   ```
   data-client_id="YOUR_CLIENT_ID"
   ```

## 📋 مصادر البيانات | Data Sources
- الدليل الإرشادي لمشعر منى، معسكرات الخدمة العامة 1446هـ
- جمعية الكشافة العربية السعودية

## 🛠️ التقنيات | Tech Stack
- [Leaflet.js](https://leafletjs.com/) — خرائط تفاعلية
- [OSRM](https://project-osrm.org/) — توجيه المشاة
- [Esri Satellite](https://www.esri.com/) — صور الأقمار الاصطناعية
- [CartoDB Labels](https://carto.com/) — طبقة التسميات

---
*متوافق مع جميع المتصفحات الحديثة | Compatible with all modern browsers*
