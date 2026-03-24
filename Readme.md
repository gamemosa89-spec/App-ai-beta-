# 🤖 AI PRO - Iraq AI

<div align="center">

![AI PRO](https://img.shields.io/badge/AI-PRO-00ff00?style=for-the-badge&logo=robot&logoColor=white)
![Version](https://img.shields.io/badge/version-2.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

**تطبيق ذكاء اصطناعي متقدم يدعم جميع نماذج AI مع إمكانيات بحث متطورة**

[🚀 التجربة المباشرة](#-طريقة-التشغيل) • [📖 الدليل الكامل](#-المميزات) • [💬 الدعم](#-الدعم-والتواصل)

</div>

---

## 📋 جدول المحتويات

- [نظرة عامة](#-نظرة-عامة)
- [المميزات](#-المميزات)
- [طريقة التشغيل](#-طريقة-التشغيل)
- [إعداد API Keys](#-إعداد-api-keys)
- [الاستخدام](#-الاستخدام)
- [التحكم في الرصيد](#-التحكم-في-استهلاك-الرصيد)
- [الصانعون](#-الصانعون)
- [الدعم والتواصل](#-الدعم-والتواصل)
- [الترخيص](#-الترخيص)

---

## 🌟 نظرة عامة

**AI PRO** هو تطبيق ويب متقدم للذكاء الاصطناعي يجمع بين قوة نماذج AI المختلفة (Gemini, GPT, Claude وغيرها) مع إمكانيات بحث متطورة على الإنترنت. التطبيق مصمم لتوفير تجربة مستخدم سلسة ومتقدمة مع التحكم الكامل في استهلاك الرصيد.

### ✨ لماذا AI PRO؟

- 🔄 **دعم شامل**: يعمل مع أي API متوافق (Gemini, GPT, Claude, LLaMA وأكثر)
- 🌐 **بحث حقيقي**: روابط مباشرة 100% من Google و YouTube
- 💰 **توفير الرصيد**: تحكم دقيق في استهلاك API
- 🎨 **تصميم عصري**: واجهة سايبر بانك احترافية
- 📱 **متجاوب**: يعمل بشكل مثالي على جميع الأجهزة

---

## 🎯 المميزات

### 🤖 دعم AI متعدد النماذج

```yaml
النماذج المدعومة:
  ✅ Google Gemini (1.5 Pro, 1.5 Flash, وغيرها)
  ✅ OpenAI (GPT-4, GPT-3.5, DALL-E)
  ✅ Anthropic Claude (جميع الإصدارات)
  ✅ أي نموذج متوافق مع OpenAI API
```

### 🔍 بحث متقدم على الإنترنت

- **Google Custom Search**: نتائج بحث حقيقية من Google
- **YouTube API**: روابط فيديوهات مباشرة
- **بحث ذكي**: يتعرف تلقائياً على نوع الطلب (يوتيوب، أخبار، ويكيبيديا، إلخ)
- **عرض المصادر**: روابط قابلة للنقر لجميع النتائج

### 💎 التحكم الذكي في الرصيد

<table>
<tr>
<td>

**🎨 جودة الردود**
- نطاق: 0-100%
- يتحكم في: Temperature
- توفير: حتى 50%

</td>
<td>

**📏 طول الردود**
- نطاق: 0-4000 توكن
- يتحكم في: Max Tokens
- توفير: حتى 75%

</td>
<td>

**🔍 نتائج البحث**
- نطاق: 1-5 نتائج
- يتحكم في: عدد النتائج
- توفير: حتى 80%

</td>
</tr>
</table>

### 📁 دعم الملفات

- 🖼️ **الصور**: JPG, PNG, GIF, WebP
- 🎥 **الفيديو**: MP4, WebM, AVI
- 📄 **المستندات**: PDF, DOCX, TXT
- 🎵 **الصوت**: MP3, WAV, M4A

### 🎨 إنشاء الصور بالذكاء الاصطناعي

- **Stability AI**: SDXL، Stable Diffusion
- **DALL-E 3**: من OpenAI
- تعديل الصور الموجودة
- تحميل مباشر للنتائج

### 💬 إدارة المحادثات

- حفظ تلقائي للمحادثات
- تنظيم بالتاريخ
- حذف انتقائي
- استرجاع سريع

---

## 🚀 طريقة التشغيل

### الطريقة الأولى: فتح مباشر

```bash
1. حمّل الملف: ai-pro-updated.html
2. افتحه في أي متصفح حديث (Chrome, Firefox, Safari, Edge)
3. استمتع بالتطبيق! 🎉
```

### الطريقة الثانية: رفع على استضافة

#### GitHub Pages (مجاني)

```bash
# 1. إنشاء مستودع جديد على GitHub
git init
git add ai-pro-updated.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/username/ai-pro.git
git push -u origin main

# 2. تفعيل GitHub Pages من الإعدادات
# Settings > Pages > Source: main branch

# 3. الرابط الخاص بك سيكون:
# https://username.github.io/ai-pro/ai-pro-updated.html
```

#### Netlify (مجاني)

```bash
# 1. زيارة: https://app.netlify.com
# 2. اسحب ملف HTML إلى صفحة Netlify
# 3. احصل على رابط مباشر في ثوانٍ!
```

#### Vercel (مجاني)

```bash
# 1. زيارة: https://vercel.com
# 2. استيراد من GitHub أو رفع مباشر
# 3. نشر تلقائي مع HTTPS
```

### الطريقة الثالثة: استضافة محلية

```bash
# باستخدام Python
python -m http.server 8000
# افتح: http://localhost:8000/ai-pro-updated.html

# باستخدام Node.js (http-server)
npx http-server
# افتح: http://localhost:8080/ai-pro-updated.html

# باستخدام PHP
php -S localhost:8000
# افتح: http://localhost:8000/ai-pro-updated.html
```

---

## 🔑 إعداد API Keys

### 1️⃣ Google Gemini API (الأساسي - مطلوب)

```yaml
الحصول على المفتاح:
  1. زيارة: https://makersuite.google.com/app/apikey
  2. تسجيل الدخول بحساب Google
  3. انقر "Create API Key"
  4. انسخ المفتاح

الإعدادات في التطبيق:
  API Key: <المفتاح-الخاص-بك>
  Endpoint: https://generativelanguage.googleapis.com/v1beta/models/
  Model: gemini-1.5-flash (أو gemini-1.5-pro)

السعر: مجاني حتى 60 طلب/دقيقة
```

### 2️⃣ Google Custom Search API (اختياري - للبحث)

<details>
<summary><b>📖 دليل الحصول على المفتاح (انقر للتوسيع)</b></summary>

#### الخطوة 1: تفعيل Custom Search API

```bash
1. زيارة: https://console.cloud.google.com
2. إنشاء مشروع جديد (أو اختيار موجود)
3. من القائمة: APIs & Services > Library
4. البحث عن: "Custom Search API"
5. انقر "Enable"
```

#### الخطوة 2: إنشاء API Key

```bash
1. من القائمة: APIs & Services > Credentials
2. انقر "Create Credentials"
3. اختر "API Key"
4. انسخ المفتاح
```

#### الخطوة 3: إنشاء Search Engine

```bash
1. زيارة: https://programmablesearchengine.google.com
2. انقر "Get Started"
3. في "Sites to search": اكتب "*" للبحث في الإنترنت كله
4. اسم المحرك: أي اسم تريده
5. انقر "Create"
6. انسخ Search Engine ID (CX)
```

#### الاستخدام في التطبيق

```yaml
Google Search API Key: <مفتاح-api-هنا>
Search Engine ID (CX): <معرف-cx-هنا>

الحصة المجانية: 100 بحث/يوم
```

</details>

### 3️⃣ YouTube Data API v3 (اختياري - لليوتيوب)

<details>
<summary><b>📺 دليل الحصول على مفتاح YouTube (انقر للتوسيع)</b></summary>

```bash
الخطوات:
  1. زيارة: https://console.cloud.google.com
  2. تفعيل "YouTube Data API v3"
  3. إنشاء Credentials > API Key
  4. انسخ المفتاح

الاستخدام:
  YouTube API Key: <المفتاح-الخاص-بك>

الحصة المجانية: 10,000 وحدة/يوم (حوالي 100 بحث)
```

</details>

### 4️⃣ Stability AI / OpenAI (اختياري - لإنشاء الصور)

<details>
<summary><b>🎨 مفاتيح إنشاء الصور (انقر للتوسيع)</b></summary>

#### Stability AI

```yaml
الحصول:
  1. زيارة: https://platform.stability.ai
  2. التسجيل
  3. انسخ API Key

الاستخدام:
  Image API Key: <مفتاح-stability>
  Model: Stability AI (SDXL)

السعر: $0.003 لكل صورة
```

#### OpenAI DALL-E 3

```yaml
الحصول:
  1. زيارة: https://platform.openai.com
  2. التسجيل
  3. API Keys > Create Key

الاستخدام:
  Image API Key: <مفتاح-openai>
  Model: OpenAI (DALL-E 3)

السعر: $0.04 لكل صورة
```

</details>

### 5️⃣ نماذج AI أخرى (اختياري)

<details>
<summary><b>🤖 استخدام نماذج أخرى (انقر للتوسيع)</b></summary>

#### OpenAI GPT

```yaml
API Key: sk-...
Endpoint: https://api.openai.com/v1/chat/completions
Model: gpt-4 أو gpt-3.5-turbo
```

#### Anthropic Claude

```yaml
API Key: sk-ant-...
Endpoint: https://api.anthropic.com/v1/messages
Model: claude-3-opus-20240229
```

#### أي API متوافق

```yaml
API Key: <مفتاحك>
Endpoint: <رابط-endpoint>
Model: <اسم-النموذج>
```

</details>

---

## 📚 الاستخدام

### 🎯 البدء السريع

```bash
1. افتح التطبيق
2. انقر على ⚙️ الإعدادات
3. أدخل Gemini API Key (الأساسي)
4. اختياري: أضف Google Search و YouTube APIs
5. احفظ الإعدادات
6. ابدأ المحادثة! 🚀
```

### 💬 أمثلة على الاستخدام

#### مثال 1: سؤال عادي

```
👤 المستخدم: ما هو الذكاء الاصطناعي؟

🤖 AI: الذكاء الاصطناعي هو فرع من علوم الحاسوب...
```

#### مثال 2: بحث على الإنترنت

```
👤 المستخدم: ابحث عن آخر أخبار التكنولوجيا

🔍 يبحث في Google...
🤖 AI: وفقاً لآخر الأخبار:
📰 [عنوان الخبر 1](رابط-1)
📰 [عنوان الخبر 2](رابط-2)
```

#### مثال 3: بحث يوتيوب

```
👤 المستخدم: أغنية Shape of You

🔍 يبحث في YouTube...
🤖 AI: وجدت:
🎵 [Ed Sheeran - Shape of You](youtube.com/watch?v=...)
```

#### مثال 4: تحميل ملف

```
👤 المستخدم: [يرفع صورة] وصف هذه الصورة

🤖 AI: الصورة تحتوي على...
```

---

## 💎 التحكم في استهلاك الرصيد

### شريط جودة الردود 🎨

```yaml
0-25%:   توفير أقصى، ردود بسيطة
26-50%:  توازن جيد (موصى به)
51-75%:  جودة عالية
76-100%: أقصى جودة، إبداعية

التوفير المتوقع: حتى 50% من التكلفة
```

### شريط طول الردود 📏

```yaml
0-25%:   ردود مختصرة جداً (0-1000 توكن)
26-50%:  ردود متوسطة (1000-2000 توكن)
51-75%:  ردود تفصيلية (2000-3000 توكن)
76-100%: ردود شاملة (3000-4000 توكن)

التوفير المتوقع: حتى 75% من التكلفة
```

### شريط نتائج البحث 🔍

```yaml
0-25%:   نتيجة واحدة فقط
26-50%:  2-3 نتائج
51-75%:  3-4 نتائج
76-100%: 5 نتائج (الحد الأقصى)

التوفير المتوقع: حتى 80% من استهلاك Google API
```

### 💡 نصائح لتوفير الرصيد

1. ✅ استخدم الإعدادات المتوسطة (50%) للاستخدام اليومي
2. ✅ ارفع الجودة فقط للمهام المعقدة
3. ✅ قلل عدد نتائج البحث للأسئلة البسيطة
4. ✅ استخدم System Prompt لتوجيه AI بدلاً من رسائل إضافية

---

## 👥 الصانعون

### 🌟 فريق التطوير

<table>
<tr>
<td align="center" width="33%">
<img src="https://img.icons8.com/fluency/96/000000/google-gemini.png" width="100px"/>
<br/>
<b>🧠 Google Gemini AI</b>
<br/>
<sub>نموذج الذكاء الاصطناعي</sub>
<br/>
<br/>
<a href="https://gemini.google.com">
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat&logo=google&logoColor=white"/>
</a>
<br/>
<br/>
<i>المحرك الذكي وراء التطبيق</i>
</td>

<td align="center" width="33%">
<img src="https://img.icons8.com/color/96/000000/claude-ai.png" width="100px"/>
<br/>
<b>⚡ Claude AI</b>
<br/>
<sub>مساعد التطوير</sub>
<br/>
<br/>
<a href="https://claude.ai">
  <img src="https://img.shields.io/badge/Claude-D4A27A?style=flat&logo=anthropic&logoColor=white"/>
</a>
<br/>
<br/>
<i>المساعد في تطوير وتحسين الكود</i>
</td>

<td align="center" width="33%">
<img src="https://img.icons8.com/fluency/96/000000/developer.png" width="100px"/>
<br/>
<b>❤️ HAJI MOSA</b>
<br/>
<sub>المطور والصانع</sub>
<br/>
<br/>
<a href="https://t.me/m_t_2k">
  <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=flat&logo=telegram&logoColor=white"/>
</a>
<br/>
<br/>
<i>صانع ومطوّر التطبيق الرئيسي</i>
</td>
</tr>
</table>

### 🏆 المساهمات

```yaml
Google Gemini AI:
  - محرك الذكاء الاصطناعي الأساسي
  - معالجة اللغة الطبيعية
  - فهم الصور والملفات
  
Claude AI (Anthropic):
  - مساعدة في كتابة الكود
  - تحسين الأداء
  - حل المشاكل التقنية

HAJI MOSA:
  - التصميم والواجهة الأمامية
  - دمج APIs المختلفة
  - إضافة المميزات والتحسينات
  - الدعم الفني والصيانة
```

---

## 💬 الدعم والتواصل

### 📧 البريد الإلكتروني

```
📮 Email: mwsy18093@gmail.com
⏰ وقت الرد: عادةً خلال 24 ساعة
```

[📧 إرسال بريد إلكتروني](mailto:mwsy18093@gmail.com)

### 💬 تيليجرام

```
👤 Username: @m_t_2k
⚡ رد فوري عبر Telegram
🌐 اللغة: العربية والإنجليزية
```

[💬 تواصل عبر تيليجرام](https://t.me/m_t_2k)

### 🐛 الإبلاغ عن مشكلة

إذا واجهت أي مشكلة:

1. ✅ تأكد من صحة API Keys
2. ✅ تأكد من اتصال الإنترنت
3. ✅ جرب إعادة تحميل الصفحة
4. ✅ امسح الـ Cache وأعد المحاولة
5. 📧 إذا استمرت المشكلة، راسلنا!

### 💡 اقتراح ميزة جديدة

نحب سماع أفكارك! راسلنا عبر:
- 📧 البريد: mwsy18093@gmail.com
- 💬 تيليجرام: [@m_t_2k](https://t.me/m_t_2k)

---

## 🌐 روابط عمل التطبيق

### استضافة مجانية مقترحة

```yaml
GitHub Pages:
  الرابط: https://pages.github.com
  المميزات: مجاني، HTTPS تلقائي، سهل
  الاستخدام: رفع الملف فقط
  
Netlify:
  الرابط: https://www.netlify.com
  المميزات: Deploy سريع، CDN عالمي
  الاستخدام: اسحب وأسقط الملف
  
Vercel:
  الرابط: https://vercel.com
  المميزات: أداء عالي، تحديثات تلقائية
  الاستخدام: ربط مع GitHub أو رفع مباشر

Cloudflare Pages:
  الرابط: https://pages.cloudflare.com
  المميزات: سرعة فائقة، أمان عالي
  الاستخدام: من GitHub مباشرة
```

### مثال: رابط عمل على GitHub Pages

```bash
# بعد رفع الملف على GitHub:
https://yourusername.github.io/ai-pro/ai-pro-updated.html

# مثال حقيقي:
https://hajimosa.github.io/ai-pro/ai-pro-updated.html
```

### إنشاء رابط قصير مخصص

```yaml
الخيار 1 - Bitly:
  1. زيارة: https://bitly.com
  2. الصق الرابط الطويل
  3. احصل على: bit.ly/ai-pro-iraq

الخيار 2 - TinyURL:
  1. زيارة: https://tinyurl.com
  2. الصق الرابط
  3. احصل على: tinyurl.com/ai-pro

الخيار 3 - دومين مخصص:
  1. اشترِ دومين (مثل: ai-pro.com)
  2. اربطه مع الاستضافة
  3. احصل على: https://ai-pro.com
```

---

## 🔐 الأمان والخصوصية

### 🛡️ حماية البيانات

```yaml
التخزين: محلي في متصفحك فقط (localStorage)
النقل: مباشر إلى APIs عبر HTTPS
المشاركة: لا نشارك أي بيانات مع أطراف ثالثة

API Keys: محفوظة محلياً في جهازك
المحادثات: لا تُرسل لأي خادم خارجي
الملفات: تُعالج محلياً قبل الإرسال
```

### 🔒 نصائح الأمان

1. ✅ لا تشارك API Keys مع أحد
2. ✅ استخدم HTTPS دائماً
3. ✅ احذف المحادثات الحساسة بعد الانتهاء
4. ✅ راجع استخدام API بشكل دوري

---

## 🎨 التخصيص

### تغيير الألوان

```css
/* افتح الملف وابحث عن: */
:root {
  --bg: #000;           /* لون الخلفية */
  --sidebar: #0a0a0a;   /* لون الشريط الجانبي */
  --border: #222;       /* لون الحدود */
  --text: #fff;         /* لون النص */
  --accent: #fff;       /* اللون الأساسي */
}
```

### تغيير الخط

```html
<!-- ابحث عن: -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700;900&display=swap">

<!-- استبدل بـ: -->
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap">
```

### إضافة لغات جديدة

```javascript
// يمكنك إضافة ملف ترجمة:
const translations = {
  en: {
    title: "AI PRO",
    settings: "Settings",
    // ... المزيد
  },
  ar: {
    title: "الذكاء الاصطناعي",
    settings: "الإعدادات",
    // ... المزيد
  }
}
```

---

## 🚀 التحديثات القادمة

### الإصدار 2.1 (قريباً)

- [ ] دعم الأوامر الصوتية
- [ ] تصدير المحادثات بصيغة PDF
- [ ] وضع داكن/فاتح قابل للتبديل
- [ ] دعم لغات برمجة إضافية في المحرر
- [ ] تكامل مع المزيد من نماذج AI

### الإصدار 2.2 (مخطط له)

- [ ] تطبيق موبايل (Android/iOS)
- [ ] مزامنة سحابية للمحادثات
- [ ] إنشاء فيديوهات بالذكاء الاصطناعي
- [ ] نظام Plugins للمطورين

---

## 📊 الإحصائيات

```yaml
الإصدار: v2.0
تاريخ الإطلاق: 2024
حجم الملف: ~45KB (مضغوط)
المتصفحات المدعومة: جميع المتصفحات الحديثة
الأجهزة: Desktop, Tablet, Mobile
اللغات: العربية (أساسي)
```

---

## 🤝 المساهمة

نرحب بمساهماتكم! إذا كنت ترغب في تحسين التطبيق:

1. 🍴 Fork المشروع
2. 🔨 أنشئ فرع جديد (`git checkout -b feature/amazing`)
3. 💾 Commit التغييرات (`git commit -m 'إضافة ميزة رائعة'`)
4. 📤 Push للفرع (`git push origin feature/amazing`)
5. 🔃 افتح Pull Request

---

## 📄 الترخيص

```
MIT License

Copyright (c) 2024 HAJI MOSA

يُسمح بالاستخدام والتعديل والتوزيع مجاناً
مع الاحتفاظ بحقوق الملكية الأصلية
```

### ⚖️ شروط الاستخدام

```yaml
يُسمح:
  ✅ الاستخدام الشخصي
  ✅ الاستخدام التجاري
  ✅ التعديل والتطوير
  ✅ إعادة التوزيع

يُطلب:
  📝 الإشارة للمطور الأصلي
  📝 الاحتفاظ بملف الترخيص

ممنوع:
  ❌ إزالة اسم المطور
  ❌ بيع الكود المصدري كما هو
```

---

## 💖 الدعم المالي

إذا أعجبك التطبيق وترغب في دعم التطوير المستمر:

### 💰 USDT (TRC20)

```
TGRf25w3YrPXRwbCGCtXqSmmu43XviLhUV
```

<div align="center">

**🙏 دعمك يساعد في:**
- 🔧 تطوير مميزات جديدة
- 🐛 إصلاح الأخطاء بسرعة
- 📚 تحسين الوثائق
- 🌟 إبقاء التطبيق مجانياً للجميع

</div>

---

## 📞 معلومات الاتصال السريع

<div align="center">

| الوسيلة | الرابط/المعلومات |
|---------|-------------------|
| 📧 **البريد** | [mwsy18093@gmail.com](mailto:mwsy18093@gmail.com) |
| 💬 **تيليجرام** | [@m_t_2k](https://t.me/m_t_2k) |
| 💰 **USDT TRC20** | `TGRf25w3YrPXRwbCGCtXqSmmu43XviLhUV` |
| 🌐 **الموقع** | [قريباً] |

</div>

---

## ❓ الأسئلة الشائعة (FAQ)

<details>
<summary><b>هل التطبيق مجاني؟</b></summary>

نعم، التطبيق مجاني تماماً. تحتاج فقط لـ API Keys المجانية من Google.
</details>

<details>
<summary><b>هل يعمل بدون إنترنت؟</b></summary>

لا، التطبيق يحتاج اتصال إنترنت للتواصل مع APIs الذكاء الاصطناعي.
</details>

<details>
<summary><b>هل بياناتي آمنة؟</b></summary>

نعم، جميع البيانات محفوظة محلياً في متصفحك. لا نستخدم أي خوادم خارجية.
</details>

<details>
<summary><b>كيف أحصل على API Key مجاني؟</b></summary>

اتبع قسم [إعداد API Keys](#-إعداد-api-keys) في هذا الدليل.
</details>

<details>
<summary><b>هل يعمل على الهاتف؟</b></summary>

نعم، التطبيق متجاوب ويعمل بشكل مثالي على جميع الأجهزة.
</details>

---

## 🎉 شكر خاص

<div align="center">

**شكراً لـ:**

🤖 **Google Gemini** - على النموذج القوي والمجاني

⚡ **Anthropic Claude** - على المساعدة في التطوير

🌟 **المجتمع المفتوح** - على الدعم والتشجيع

❤️ **أنت** - على استخدام التطبيق!

</div>

---

<div align="center">

## 🌟 إذا أعجبك التطبيق، لا تنسَ:

⭐ **Star** المشروع على GitHub

📢 **مشاركة** مع أصدقائك

💬 **تواصل** معنا للتحسينات

💰 **دعم** المطور

---

**صُنع بـ ❤️ في العراق**

**HAJI MOSA © 2024**

[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)](https://t.me/m_t_2k)
[![Iraq](https://img.shields.io/badge/Made%20in-Iraq%20🇮🇶-green?style=for-the-badge)](https://t.me/m_t_2k)

</div>
