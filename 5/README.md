**ال سی دی (LCD)**

**عنوان آزمایش:** کار با LCD 

**هدف آزمایش:** نمایش داده‌ها و ایجاد و نمایش کاراکترهای سفارشی و اجرای حرکت انیمیشنی روی نمایشگر LCD .

**وسایل مورد نیاز:**

آردوینو

ماژول LCD

مقاومت

پتانسیومتر

برد بورد و سیم

**شرح آزمایش:** در آزمایش اول LCD به آردوینو متصل شده و داده‌ها روی نمایشگر نمایش داده می‌شود نمایش پیام ( Hello World ) بر روی LCD.

![Screenshot 2024-11-03 234118](https://github.com/user-attachments/assets/af08a17d-d0d2-4736-bc7d-db21b9089bd9)

در آزمایش دوم با استفاده از کتابخانه‌ی LiquidCrystal ابتدا کاراکترهای سفارشی (مانند قلب، صورت خندان و اخمو) با استفاده از دستورات lcd.createChar تعریف می‌شوند. در حلقه‌ی اصلی برنامه، کاراکترها به‌صورت انیمیشنی از چپ به راست و سپس از راست به چپ بر روی دو سطر LCD حرکت می‌کنند.


![lcd_anim](https://github.com/user-attachments/assets/8b19597b-ce5f-43a6-9caa-00468fe334cc)



نتیجه‌گیری: تسلط بر روش‌های ارتباط با نمایشگر.


============================================================================================

**مدار ultrasonic**

**عنوان آزمایش:** کار با حسگر اولتراسونیک

**هدف آزمایش:** اندازه‌گیری فاصله با دقت بالا با استفاده از حسگر اولتراسونیک.

**وسایل مورد نیاز:** 

آردوینو

پتانسیومتر

حسگر اولتراسونیک

برد بورد و سیم


**شرح آزمایش:**

در این پروژه، از یک سنسور اولتراسونیک برای اندازه‌گیری فاصله تا موانع استفاده می‌شود. پین‌های trig و echo به ترتیب به پین‌های ۶ و ۷ میکروکنترلر متصل شده‌اند. برای اندازه‌گیری فاصله، یک پالس به پین trig ارسال شده و زمان رفت و برگشت موج صوتی توسط پین echo دریافت می‌شود. سپس فاصله بر حسب سانتی‌متر محاسبه شده و مقدار آن همزمان بر روی سریال مانیتور و LCD نمایش داده می‌شود.


![ultrasonic](https://github.com/user-attachments/assets/c579011a-8952-4a69-806f-88c3b4e7770e)


**نتیجه‌گیری:**

این آزمایش نشان داد که سنسور اولتراسونیک HC-SR04 می‌تواند فاصله‌های نسبی را با دقت خوبی اندازه‌گیری کند. همچنین، نمایش مقدار فاصله بر روی LCD امکان مشاهده آسان و سریع داده‌ها را فراهم می‌کند.