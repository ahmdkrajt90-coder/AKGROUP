# 🚀 دليل النشر على Vercel

## خطوات النشر السريعة

### ✅ الخطوة 1: إنشاء حساب و Repository على GitHub

#### 1.1 إنشاء حساب GitHub (إذا لم يكن لديك):
- اذهب إلى https://github.com
- انقر **Sign up**
- أكمل عملية التسجيل

#### 1.2 إنشاء Repository جديد:
- بعد تسجيل الدخول، اذهب إلى https://github.com/new
- ملئ البيانات:
  - **Repository name**: `ak-group-real-estate`
  - **Description**: AK Group Real Estate Website
  - **Public** (عام)
- انقر **Create repository**

---

### ✅ الخطوة 2: دفع المشروع إلى GitHub

بعد إنشاء repository، استخدم الأوامر التالية:

```bash
cd /c/Users/ahmed/Desktop/AK\ GROUP

# استبدل YOUR_USERNAME باسم المستخدم على GitHub
git remote set-url origin https://github.com/YOUR_USERNAME/ak-group-real-estate.git

# ادفع المشروع
git branch -M main
git push -u origin main
```

**ملاحظة**: سيطلب منك كلمة مرور. استخدم Personal Access Token من:
https://github.com/settings/tokens/new

---

### ✅ الخطوة 3: النشر على Vercel

#### 3.1 إنشاء حساب Vercel:
- اذهب إلى https://vercel.com
- انقر **Sign up**
- اختر **Continue with GitHub**
- وافق على الأذونات

#### 3.2 نشر المشروع:
- بعد تسجيل الدخول، اذهب إلى https://vercel.com/new
- انقر **Import Git Repository**
- اختر `ak-group-real-estate` من القائمة
- انقر **Import**

#### 3.3 تكوين المشروع:
- **Framework Preset**: Other
- **Build Command**: (اتركها فارغة)
- **Output Directory**: (اتركها فارغة)
- **Environment Variables**: (لا توجد)

#### 3.4 انقر **Deploy** 🎉

---

### ✅ الخطوة 4: الحصول على الرابط

بعد انتهاء النشر:
- ستحصل على رابط مثل: `https://ak-group-real-estate.vercel.app`
- هذا هو موقعك المباشر! 🌐

---

## 📝 خطوات إضافية

### تحديث الموقع تلقائياً:
عند كل تعديل تقوم به محلياً:

```bash
cd /c/Users/ahmed/Desktop/AK\ GROUP
git add .
git commit -m "وصف التعديلات"
git push
```

Vercel سيحدث الموقع تلقائياً! ⚡

---

## 🔗 الروابط المهمة

- GitHub: https://github.com
- Vercel: https://vercel.com
- Settings GitHub: https://github.com/settings/tokens/new
- Dashboard Vercel: https://vercel.com/dashboard

---

## ⚠️ مشاكل شائعة وحلولها

### مشكلة: "git push" لا يعمل
**الحل**: تأكد من:
1. استخدام Personal Access Token (ليس كلمة المرور)
2. Repository موجود على GitHub
3. اسم المستخدم صحيح

### مشكلة: Vercel لا يجد المشروع
**الحل**:
1. تأكد من أن المشروع موجود على GitHub
2. وافق على الأذونات لـ Vercel الوصول إلى GitHub

### مشكلة: الموقع لا يفتح بعد النشر
**الحل**:
1. أنتظر 2-3 دقائق للنشر الكامل
2. افتح https://vercel.com/dashboard وتحقق من الحالة
3. اضغط F5 لإعادة تحميل الصفحة

---

## ✨ مبروك!

موقعك الآن مباشر على الإنترنت للجميع! 🎉
