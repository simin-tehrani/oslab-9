OS9-simin tehranchi

Question 1:
<br>
<br>
chown :
<div dir="rtl">
 با استفاده از این دستور  مالکیت، گروه، دایرکتوری و لینک فایل تغییر می کند
</div>
chown -R
<div dir="rtl">
اعمال را به صورت بازگشتی روی فایل ها و دایرکتوری ها انجام می دهد
</div>
chown -f
<br>
<div dir="rtl">
   این دستور برای جلوگیری از نمایش خطاهای احتمالی است
</div>
gpasswd:
<div dir="rtl">
به وسیله این دستور می توانید در سیستم عامل لینوکس گروه های خود را مدیریت کنید
 </div>
 gpasswd -r
<div dir="rtl">
این دستور برای پاک کردن پسورد گروه استفاده می شود
 </div>
  gpasswd:
<div dir="rtl">
به وسیله این دستور می توانید در سیستم عامل لینوکس گروه های خود را مدیریت کنید
 </div>
  gpasswd-r:
<div dir="rtl">
به وسیله این دستور می توانید در سیستم عامل لینوکس گروه های خود را مدیریت کنید
 </div>
 gpasswd-d
  <div dir="rtl">
به وسیله این دستور کاربر از گروه حذف می شود
 </div>
 <br>
  <br>
Question 2:
<br>
<br>
id -u -n
<div dir="rtl">
به وسیله این دستور نام کاربر نشان داده می شود
</div>
id 
<div dir="rtl">
به وسیله این دستورشناسه اصلی کاربر نشان داده می شود
</div>
<br>
  <br>
Question 3:
<br>
<br>
sudo useradd oslab
<div dir="rtl">
ایجاد حساب کاربری
</div>
sudo passwd oslab
<div dir="rtl">
 ایجاد پسورد برای حساب کاربری 
</div>
  <br>
  <br>
Question 4:
<br>
<br>
sudo groupadd sadjad
<div dir="rtl">
  "ایجاد گروه "سجاد
</div>
sudo groupadd Uni
<div dir="rtl">
  "ایجاد گروه "یونی
</div>
sudo usermod -G sadjad,Uni oslab
<div dir="rtl">
  در هر دو گروه کاربر را اضافه میکنیم
</div>
sudo gpasswd -A oslab sadjad
<div dir="rtl">
  کاربر ادمین گروه میشود
</div>
<br>
<br>
Question 5:
<br>
<br>
sudo useradd os2
<div dir="rtl">
 ایجاد کاربر
</div>
sudo usermod -G sadjad os2
<div dir="rtl">
 اد کردن کاربر به گروه
</div>
sudo userdel os2
<div dir="rtl">
  حذف کردن کاربر از گروه
</div>
