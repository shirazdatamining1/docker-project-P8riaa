# پروژه تپش قلب با Docker

این پروژه یک وب‌اپلیکیشن ساده است که انیمیشنی از تپش قلب رو نمایش می‌دهد و با Docker مدیریت می‌شود.

## نحوه اجرا با Docker

1. ابتدا Docker Image رو بسازید:
   ```bash
   docker build -t heart-beat-app .
   container :
   docker run -p 8080:80 heart-beat-app
   بعد از اجرای موفقیت‌آمیز، می‌توانید وب‌اپلیکیشن رو در مرورگر از طریق http://localhost:8080 مشاهده کنید.