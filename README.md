<div dir='rtl'>
  
  
# GoogleBackup
بکاپ از گوگل: چه اتفاقی افتاده و چه باید کرد؟


### چه اتفاقی افتاده است؟
در هفته‌های اخیر تغییراتی در شیوه شناسایی محل کاربران از سمت گوگل اتفاق افتاده که در نتیجه آن حتی اگر از VPN برای دسترسی به سرویس‌های گوگل استفاده کنید باز هم اینکه از ایران هستید را تشخیص داده و از استفاده شده جلوگیری کند.

**چه سرویس‌هایی تا کنون از این تغییر تاثیر گرفته‌اند؟**

- Youtube: یوتبرهای ایرانی گزارش می‌کنند که بخشی از آمار بازدید آن‌ها از ایران تشخیص داده می‌شود
- Developer Services: بعضی از سرویس‌های مرتبط با برنامه‌نویسی مانند اندروید یا زبان Go 
- Youtube Premium
- Youtube Kids: دقت کنید که این سرویس رایگان می‌باشد و از سوی گوگل تحریم نیست
- Spotify: اسپاتیفای روی زیرساخت ابری گوگل (GCP) قرار دارد
- GCP
- اگر سرویس دیگری می‌شناسید لطفاً در بخش [Issues](https://github.com/Hameds/GoogleBackup/issues) اعلام کنید.

**چه خطایی دریافت می‌شود؟**

معمولاً خطای 403 گزارش شده است و در یک مورد خطای 404. لطفاً اگر تجربه‌ای در این موارد داشته‌اید آن را در بخش  [Issues](https://github.com/Hameds/GoogleBackup/issues) یا با ویرایش این فایل در بخش «تجربه شما» به اشتراک بگذارید

### بکاپ به چه معناست و چه باید بکنم؟
نسخه پشتیبان یا Backup  به معنی یک نسخه از اطلاعات شماست که روی سرویس‌های گوگل قرار دارد مثلاً یک نسخه از تمام ایمیل‌های شما یا یک نسخه از تمام مخاطبین یا فایل‌های شما که روی Google Drive قرار دارد.

برای دریافت بکاپ به آدرس [Google Takeout](https://takeout.google.com) مراجعه کنید و سرویس‌هایی که می‌خواهید یک نسخه پشتیبان از اطلاعات آن‌ها دریافت کنید را مشخص کنید. در ادامه Export once را انتخاب و تایید کنید. بعد از مدتی یک ایمیل حاوی لینک دانلود اطلاعات برای شما ارسال می‌شود.

⚠️ نکته مهم: اگر کلمات عبور خود را روی مرورگر کروم ذخیره کردید به آدرس [Google Password Manager](https://password.google.com) رفته و یک نسخه پشتیبان تهیه کنید.

**رمزنگاری فایل‌های بکاپ**
بعد از دانلود فایل‌های بکاپ به روش اشاره شده در [این توییت](https://twitter.com/oraclenik/status/1378389345955155972) آن‌ها را رمزنگاری کنید.


### سوالات متداول

- آیا جیمیل ایران را تحریم کرده؟ خیر
- آیا گوگل درایو ایران را تحریم کرده؟ خیر
- آیا گوگل ایران را تحریم کرده؟ خیر. هیچ نشانه‌ای از تغییر سیاست‌های گوگل در این خصوص وجود ندارد و این بکاپ به منظور احتیاط گرفته می‌شود
- موقع دانلود فایل بکاپ با خطای 403 مواجه می‌شوم. چه کنم؟ از VPN استفاده کنید.
- با وجود استفاده از VPN باز هم با خطای 403 در موقع دانلود بکاپ مواجه می‌شوم. چه کنم؟ از VPN دیگری استفاده کنید و نگران نباشید
- اصلاً چرا باید بکاپ گرفت؟ صرفنظر از اینکه تحریم باشیم یا نباشیم، داشتن بکاپ از اطلاعات باعث آسودگی خاطر در زمان بحران‌های احتمالی است


### تجربه شما

لطفاً اگر تجربه‌ای در این خصوص دارید، فایل `Readme.md` این مخزن را ویرایش کرده و `Pull Request`  ارسال کنید یا آن را از طریق بخش [Issues](https://github.com/Hameds/GoogleBackup/issues) به اشتراک بگذارید.


</div>
