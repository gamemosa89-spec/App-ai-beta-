# 🤖 APP AI - منصة ذكاء اصطناعي متعددة النماذج

تطبيق متكامل يوفر واجهة موحدة للوصول إلى أقوى نماذج الذكاء الاصطناعي من جميع مزودي الخدمات.

## ✨ الميزات الرئيسية

### 🔑 إدارة مفاتيح API
- أضف مفاتيح API من أي نموذج ذكاء اصطناعي
- أدخل endpoint مخصص لأي نموذج
- ادفع اسم النموذج وحفظه بأمان

### 🎨 إنشاء وتعديل الصور
- إنشاء صور من وصف نصي
- تحرير وتعديل الصور الموجودة
- دعم نماذج متعددة (DALL-E, Stable Diffusion, إلخ)

### 🎵 إنشاء الأصوات والأغاني
- توليد موسيقى وأغاني
- تحويل النصوص إلى صوت (TTS)
- دعم لغات متعددة

### 🎬 إنشاء الفيديوهات
- توليد فيديوهات من وصف نصي
- تحرير وتحسين الفيديوهات
- دعم جودات عالية

### 📁 إنشاء والملفات
- توليد ملفات نصية
- إنشاء جداول بيانات
- تحويل الصيغ المختلفة

### 🔄 نقل البيانات من التطبيقات الأخرى
- استيراد البيانات من Google Gemini وتطبيقات أخرى
- نظام Prompt متقدم للنقل الآمن
- حفظ البيانات بصيغة منظمة

---

## 🚀 البدء السريع

### المتطلبات
- Python 3.8+
- مفاتيح API من الخدمات المراد استخدامها

### التثبيت

```bash
# استنساخ المستودع
git clone https://github.com/gamemosa89-spec/App-ai-beta-.git
cd App-ai-beta-

# تثبيت المتطلبات
pip install -r requirements.txt
```

### الاستخدام

```python
from app import AIApp

# إنشاء التطبيق
app = AIApp()

# إضافة مفتاح API
app.add_api_key(
    model_name="gpt-4",
    api_key="your-api-key",
    endpoint="https://api.openai.com/v1"
)

# إنشاء صورة
image = app.generate_image(
    prompt="منظر طبيعي جميل",
    model="dall-e"
)

# توليد نص
text = app.generate_text(
    prompt="اكتب قصة قصيرة",
    model="gpt-4"
)

# نقل البيانات من Google Gemini
app.import_from_gemini(
    api_key="your-gemini-key",
    data_type="conversations"
)
```

---

## 🎯 الحالات الاستخدام

✅ الكتاب والمدونون - إنشاء محتوى نصي وصور  
✅ المصممون - تحرير الصور والفيديوهات  
✅ منتجو الموسيقى - إنشاء أغاني وأصوات  
✅ صناع المحتوى - إنشاء فيديوهات احترافية  
✅ رجال الأعمال - تحليل البيانات والتقارير  

---

## 📋 النماذج المدعومة

### نماذج النصوص
- OpenAI GPT-4 / GPT-3.5
- Google Gemini
- Anthropic Claude
- وغيرها...

### نماذج الصور
- DALL-E
- Stable Diffusion
- Midjourney
- وغيرها...

### نماذج الصوت
- ElevenLabs
- Google Text-to-Speech
- Azure Speech Services
- وغيرها...

### نماذج الفيديو
- Runway AI
- Synthesia
- D-ID
- وغيرها...

---

## 🔐 الأمان

- تشفير مفاتيح API
- عدم حفظ البيانات الحساسة محلياً
- التوافق مع معايير الخصوصية

---

## 🤝 المساهمة

نرحب بمساهماتك! يرجى:

1. عمل Fork للمشروع
2. إنشاء فرع جديد (`git checkout -b feature/AmazingFeature`)
3. Commit التغييرات (`git commit -m 'Add some AmazingFeature'`)
4. Push للفرع (`git push origin feature/AmazingFeature`)
5. فتح Pull Request

---

## 📄 الترخيص

هذا المشروع مرخص تحت [MIT License](LICENSE)

---

## 📞 التواصل والدعم

للإبلاغ عن الأخطاء أو الاقتراحات:
- 🐛 [Issues](https://github.com/gamemosa89-spec/App-ai-beta-/issues)
- 💬 [Discussions](https://github.com/gamemosa89-spec/App-ai-beta-/discussions)

---

## 🌟 شارك المشروع

إذا أعجبك المشروع، لا تنسى إضافة ⭐ النجمة!

---

**صنع بـ ❤️ من قبل فريق App AI**
