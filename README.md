#https://T.me/Rahanesh 

# PersonalVPN 

ویدیوی آموزش مراحل ساخت فیلترشکن شخصی را در کانال آپارات و یوتیوب رهانش مشاهده کنید.

راه اندازی سرور VPN شخصی
ساخت یک سرور با سیستم عامل لینوکس Centos7 نسخه 64 بیتی
اتصال به سرور از طریق ssh با کمک نرم افزار PuTTY

دریافت و کلون کردن بسته نرم افزاری در سرور با دستور زیر 
cd /tmp/ && yum install git -y && git clone https://github.com/rahanesh/PersonalVPN.git && cd PersonalVPN/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh

دستورات زیر برای اضافه کردن کاربر و ایجاد پسورد کاربر در سرور می باشد

useradd [username] 
passwd [username]

بازکردن آیپی سرور در مرورگر 
مثال:
http://185.10.10.10/admin

