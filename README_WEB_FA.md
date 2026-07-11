# DigiHealth Lab - Web Version with Official Learning Resources

این نسخه وب برای کاربرد دانشگاهی طراحی شده است و بخش  به منابع آموزشی اصلی و تخصصی متصل شده است.

## بخش‌های اصلی

- Dashboard
-  با لینک مستقیم به منابع رسمی
- Terminology Dictionary
- HIS Simulation Lab
- Medical Coding Lab
- EMR Documentation Simulator
- Audit & Missing Documents Tracker
- Telehealth & mHealth Simulator
- Analytics & Student Portfolio

## منابع متصل‌شده در 

- WHO Digital Health
- WHO Global Strategy on Digital Health
- WHO ICD-11 Browser
- CDC ICD-10-CM Browser Tool
- ONC Health IT Playbook
- ONC Health IT Curriculum Resources for Educators
- HL7 FHIR Specification
- ONC FHIR Fact Sheets
- SNOMED CT
- LOINC
- DICOM
- HHS HIPAA Privacy Rule
- HHS HIPAA Security Rule
- AHIMA Data Quality and Integrity
- FDA Software as a Medical Device
- WHO Ethics and Governance of AI for Health
- NLM MeSH Browser
- MedlinePlus Medical Words

## نکته مهم

این اپ برای آموزش، تمرین دانشگاهی و شبیه‌سازی است. تمام داده‌های بیمار fictional هستند. منابع خارجی فقط وقتی کار می‌کنند که کاربر اینترنت داشته باشد.

## اجرا

فایل `index.html` را در مرورگر باز کنید. برای استفاده حرفه‌ای، پوشه را روی Netlify، GitHub Pages، Vercel یا هاست دانشگاه آپلود کنید.


## Update: Expanded Terminology Dictionary
This version includes an expanded categorized dictionary with 1165 entries covering medical terminology, prefixes, suffixes, roots, anatomy, symptoms, diseases, procedures, diagnostics, abbreviations, coding, digital health, medical technology, HIS/EMR workflow, interoperability, privacy, data analytics and healthcare AI.

## آپدیت Medical Coding Lab

در این نسخه بخش Medical Coding Practice Case کامل‌تر شد و اکنون شامل کیس‌های تمرینی، انتخاب کدهای تشخیص، تشخیص‌های ثانویه، اقدامات، اعمال جراحی، آزمایش‌ها، تصویربرداری، داروها، نمایش نتیجه، امتیازدهی، پیشنهاد آموزشی، راهنمای کدگذاری و جستجوی Code Library است.

توجه مهم: این اپ برای آموزش دانشگاهی است و شامل یک کتابخانه کد آموزشی و لینک به منابع رسمی است. همه کدهای رسمی جهان داخل فایل قرار داده نشده‌اند، چون سیستم‌هایی مثل CPT نیاز به دسترسی رسمی/لایسنس دارند و ICD، RxNorm، LOINC و سایر code set ها به‌روزرسانی می‌شوند. برای استفاده واقعی باید همیشه منبع رسمی و قوانین محلی بررسی شود.

## آپدیت UI، Login و راهنمای صفحات

در این نسخه موارد زیر اضافه شد:

- صفحه ورود و ساخت حساب کاربری با username و password برای هر دانشجو یا کاربر
- ذخیره حساب و پیشرفت کاربر در همان مرورگر با localStorage
- صفحه معرفی کامل پلتفرم با مسیر استفاده از ابتدا
- راهنمای کاربردی در ابتدای همه صفحات برای توضیح نحوه استفاده از همان بخش
- داشبورد بصری‌تر با نقشه آموزشی بیمارستان دیجیتال، آیکون‌ها و کارت‌های مرتبط با HIS، EMR، Coding، Privacy، Analytics و Digital Health
- نمایش نام و نقش کاربر واردشده در نوار بالای صفحه
- دکمه Logout

## نکته امنیتی مهم

سیستم username/password این نسخه برای prototype آموزشی و دمو دانشگاهی است و اطلاعات را فقط در مرورگر همان کاربر ذخیره می‌کند. برای نسخه واقعی دانشگاهی باید authentication سمت سرور، دیتابیس امن، رمزنگاری، مدیریت نقش استاد/دانشجو و backup رسمی طراحی شود.


## آپدیت جدید Mini Quiz Game

در این نسخه یک صفحه مستقل به نام Mini Quiz Game اضافه شده است. این صفحه برای تمرین دانشگاهی به شکل بازی طراحی شده و برای هر کورس 100 سؤال دارد. کورس‌ها شامل Medical Terminology، Medical Coding، Medical Technology، Health Technology Laws، Health Informatics Standards و Healthcare Data Analysis هستند.

بعد از هر پاسخ، سیستم بلافاصله نشان می‌دهد جواب درست است یا غلط، پاسخ صحیح و توضیح آموزشی را نمایش می‌دهد و برای جواب غلط هشدار بصری نشان می‌دهد. در موبایل‌هایی که پشتیبانی کنند، هشدار لرزشی هم فعال می‌شود.


## آخرین تغییرات نسخه Dashboard, About, Feedback & Collaboration

در این نسخه، صفحه داشبورد از نظر بصری بهبود داده شد و بخش **About Us / درباره ما** فقط در داشبورد قرار گرفت. اطلاعات حرفه‌ای زیر در همان بخش نمایش داده می‌شود:

Prepared by Motahhareh Khorshidzadeh  
Health IT Specialist | HIS & EMR Systems Consultant  
Researcher in Digital Health  
Email: motahhareh.khorshidzadeh@gmail.com

همچنین دو صفحه جدید به منو اضافه شد:

1. **Feedback & Suggestions** برای ارسال انتقادات، پیشنهادات، اصلاح محتوا، گزارش خطا و ایده‌های آموزشی به ایمیل طراح.
2. **Collaboration** برای ارسال درخواست همکاری از طرف متخصصین، شرکت‌ها، مراکز آموزشی و دانشگاه‌ها.

نکته فنی: چون این نسخه یک وب‌اپ استاتیک است، فرم‌ها با `mailto:` کار می‌کنند و برنامه ایمیل کاربر را با متن آماده باز می‌کنند. برای ارسال مستقیم بدون باز شدن ایمیل کاربر، در نسخه رسمی باید یک سرویس backend یا سرویس فرم مثل Formspree, EmailJS یا سرور دانشگاه متصل شود.


## Update: Final dashboard, recovery, clickable map and coding expansion
- Dashboard hero text/buttons removed and replaced with a professional DigiHealth Lab welcome design.
- Digital Hospital Learning Map is now the main clickable dashboard area and includes all platform sections.
- About Us is larger and includes full platform explanation plus designer/specialist profile.
- Local username/password recovery added: username lookup by email and password reset by email + username.
- Medical Coding Lab now includes 100 fictional academic practice cases.
- Mortality coding practice is included through dedicated death-certificate style training cases.


## Update: Medical Library Replacement

In this version, HIS Simulation Lab and Telehealth Simulator are hidden from the main navigation and replaced by a Medical Library section. The library links to official, open-access and publisher reference resources by specialty. It does not include unauthorized textbook PDFs.


## Latest update
- Added official hospital statistics website icon links.
- Renamed Analytics & Portfolio to Portfolio & Certificate.
- Certificates are issued per Mini Quiz course only after 100/100 questions completed and score >= 70%.
- Added  section for paid handbooks/articles/templates; connect real payment links before publishing.
