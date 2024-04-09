
# TS-OSINT (TLER AL-SHAHRANI-OSINT)
## أداة (استخبارات المصادر المفتوحة-OSINT (Open-Source Intelligence 

<img src="https://github.com/tlersa/G00TR-IG/assets/111729973/c792dae0-5494-4457-b680-6fee3a12e640" width="800">

### أوامر التثبيت
```
sudo git clone https://github.com/tlersa/TS-OSINT.git
cd /home/kali/TS-OSINT/
python3 TS-OSINT.py
```

### المميزات
- مجانية ومفتوحة المصدر ✔️
- إذا لم تكن مثبت المكاتب المطلوبة (os, requests, json, time, sys, bs4, datetime, telethon.sync, praw, socket, PIL.Image, PIL.ExifTags, phonenumbers, googlesearch) سيتم تثبيتها تلقائياً ✔️
- المصداقية بالمعلومات المستخرجة بنسبة 💯

### شرح الأوامر
- خيار [1] Dorks
- خيار [2] Username OSINT : يستخرج معلومات المستخدمين الآتية لمنصات التواصل الآتية
  - منصة Instagram
    - اسم المستخدم
    - معرّف المستخدم
    - كنية المستخدم
    - وصف الحساب
    - روابط الوصف
    - هل هو حساب أعمال؟
    - هل الحساب موثق بالعلامة الزرقاء؟
    - هل الحساب خاص؟
    - عدد المتابعين
    - عدد الذين يتابعهم
    - هل تم إنشاء الحساب قبل 30 يوم؟
    - هل لديه حساب بمنصة Threads؟
    - هل لديه فيديوهات؟
    - عدد المنشورات
    - عدد فيديوهات الـIGTV
    - هل الحساب موقعه كندا؟
    - هل حالة الحساب إحياء الذكرى؟
    - هل الحساب جديد؟
    - البريد الإلكتروني العام
    - رقم الهاتف العام
    - هل المستخدم يملك حساب آخر؟
    - موقع الحساب
    - تاريخ إنشاء الحساب بالسنة والشهر
    - صورة الحساب
    - تاريخ آخر تغيير لصورة الحساب
  - منصة Telegram
    - اسم المستخدم
    - معرف المستخدم
    - الاسم الأول
    - الاسم الأخير
    - الرقم
  - منصة TikTok
    - اسم المستخدم
    - معرّف المستخدم
    - كنية المستخدم
    - هل الحساب موثق بالعلامة الزرقاء؟
    - هل الحساب خاص؟
    - معرّف الحساب الثاني
    - عدد المتابعين
    - عدد الذين يتابعهم
    - عدد الإعجابات الإجمالي
    - عدد المنشورات
    - هل الحساب يسمح برؤية الآخرين للمنشورات المحفوظة؟
    - هل الحساب يسمح برؤية الآخرين للذين يتابعهم؟
    - لغة الحساب
    - تاريخ إنشاء الحساب بالسنة والشهر
    - تاريخ آخر تغيير للكنية
    - موقع الحساب
  - منصة Github
    - اسم المستخدم
    - معرّف المستخدم
    - صورة الحساب
    - رابط HTML
    - نوع الحساب
    - كنية المستخدم
    - الشركة
    - المدونات
    - موقع الحساب
    - البريد العام
    - الـHireable
    - الوصف
    - رابط حساب X
    - المستودعات العامة
    - الـgits العامة
    - عدد المتابعين
    - عدد الذين يتابعهم
    - تاريخ إنشاء الحساب
    - آخر تحديث للحساب
  - منصة Reddit
    - اسم المستخدم
    - معرّف المستخدم
    - كنية المستخدم
    - تاريخ إنشاء الحساب
    - صورة الحساب
    - الرقم العام
    - البريد الإلكتروني العام
    - الوصف
    - روابط الوصف
- خيار [3] Domain OSINT : استخراج المعلومات الآتية لأي موقع بواسطة الـIP او الـDomain الخاص به
  - الـDomain
  - الـIP
  - معلومات الاستضافة
  - حالة الموقع
  - القارة
  - رمز القارة
  - الدولة
  - رمز الدولة
  - موقع الموقع
  - اسم منطقة الموقع
  - المدينة
  - المنطقة/المقاطعة/الحي/الدائرة/المحافظة/القضاء/الجزئية/الإقليم/المديرية/القسم
  - الرمز البريدي
  - العملة
  - مزود خدمة الانترنت
  - الـAs
  - اسم الـAs
  - الاستعلام
  - خطوط الطول
  - خطوط العرض
  - الـOffset
  - الهاتف
  - الـProxy
  - مكان الاستضافة
- خيار [4] IP OSINT
  - خيار Target : استخراج معلومات الـIP الآتية للضحية بواسطة الـIP الخاص به
    - الـIP
    - مزود خدمة الانرنت
    - النطاق
    - الدولة
    - المنطقة
    - المدينة
    - الرمز البريدي
    - خطوط الطول
    - خطوط العرض
  - خيار الـYour device : استخراج اامعلومات الآتية لجهاز مستخدم الأداة
    - الاستضافة
    - الـIP
    - معلومات الاستضافة
- خيار [5] Images OSINT : استخراج المعلومات الآتية للصور (بشرط أن تكون الصورة المحددة مصورة من الكاميرا فقط)
  - اسم الجهاز الذي صور الصورة
  - تشفير الصورة
  - الـExifOffset
  - الـSubsecTimeOriginal
  - تاريخ التقاط الصورة بالسنة والشهر واليوم والساعة والدقيقة والثانية وأجزاء الثانية
  - فئة الصورة
  - المدينة الطبيعية
  - نوع الصورة
  - القارة
  - الدولة
  - رمز الدولة
  - المقاطع
  - رمز المقاطعة
  - الاتحاد السياسي
  - السكك الحديدية
  - لطريق
  - الولاية
  - القرية
  - الطريق السريع
  - رابط موقع تصوير الصورة بخرائط Google
  - خيار [6] Phonenumbers OSINT : استخراج المعلومات الآتية لأرقام الهاتف العالمية
    - موقع الرقم
    - المنطقة الزمنية
    - شركة الاتصالات
  - خيار [7] Search engine : محرك بحث Google، تستطيع البحث عن أي شيء تريده وعدد نتائج البحث
 
  
### ملاحظات ⚠️
- خيار [1] Dorks و[7] Search engine قد تواجه بهم مشكلة الـHTTP ERORR 429 وهذه مشكلة طبيعية سببها كثرة الطلبات (Requests) على المواقع، لتجنبها حاول ألا تستخدم هذه الخيارين كثيرا بمدة قصيرة أو استخدمهم أثناء استخدامك لـTOR
- خيار [2] Username OSINT منصة Telegram ستحتاج لمعرّف الـAPI والـAPI hash وهذه تحصل عليها من [هنا](https://my.telegram.org/apps)
- خيار [2] Username OSINT منصة Reddit ستحتاج للـClient ID والـClient secert والـUser agent وهذه تحصل عليها من [هنا](https://www.reddit.com/prefs/apps/)
- خيار [5] Images OSINT يجب أن تحدد الصور المصورة من الكاميرا مباشرة فقط
- خيار [5] Images OSINT قد تكون المعلومات من (تاريخ التقاط الصورة... ~ رابط موقع تصوير...) غير دقيقة/غير صحيحة وهذا بسبب محتوى الصورة أولا وثانيا من المكتبة PIL المستخدمة

### تثبيت المكاتب (إذا كنت تستخدم KALI Linux فلا تحتاج لتثبيتها)

```
pip install os requests json time sys bs4 datetime telethon.sync praw socket PIL.Image PIL.ExifTags phonenumbers googlesearch
```
