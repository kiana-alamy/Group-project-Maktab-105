# Group-project-Maktab-105

هـفته22 مـکـتب93
1
پروژه کافه
بهصورت گروهی یک وبسایت برای کافی شاپ طراحی کنید. درادامهویژگی های وبسایت ذکر شده است.
الزامات فنی:
◆ Django: Framework
◆ Git: Version control
◆ PostgreSQL: Database
◆ HTML, CSS, JS : Front-end
◆ Bootstrap CSS framework
پروژهشماازدو قابلیت اصلیتشکیل شده است:
الف)Landing page:یک صفحه عمومی از وب سایت کافه که حاوی چندsub-pagesبرای مشاهده
مشتریان است:
1.Home:صفحهاصلی پروژه کهبرای جذب مشتریطراحی شدهاستوباید اطالعات کلیدی در مورد
کافه داشته باشد و طراحی گرافیکی خوبی داشته باشد (toolbar)...،
2.About:در این بخش اطالعات کاملی در مورد کافه، وب سایت، کارکنان،…داریم.
3.Contact us:حاویآدرس، شماره تلفن و سایر اطالعات تماس است.همچنین فرمی برای تعامل با
کاربران از وب سایت داشته باشید.(اختیاری) نمای نقشهکافهرا در صفحه تماس اضافه کنید.
2
4.Menu:لیست محصوالت و غذاهایی که باید توسط کافه سرو شود. بخش منو باید شامل موارد زیر باشد:
محصوالت به همراه قیمت آنهاوبخشکامنت
دکمه سفارش، برایثبتسفارشو انتخابنوع سفارش(حضوری یا آنالین)توجه شود که در
سفارش حضوری شماره میز نیز باید ذکر شود.
5.Cart:سبد خریدکه محصوالت انتخاب شدهتوسط کاربربه آن انتقال داده میشودو پس از طی مراحل
خرید سفارش مشتری ثبت میشود.
6.Orders list:پس از ثبت سفارشکاربر میتواندلیستسفارشاتخودرا به همراه وضعیتسفارش
مشاهده کند. به عنوان مثال: درحال بررسی سفارش،درحالپختو اماده سازی،درحال ارسال یا سرو
و.….
ب)Cashier Panel:اینپنل برایصندوقداراناست وبرایمدیریتسفارشات مشتریانطراحیشده است.
پنلCashierبایددارایویژگیهاییمانندموارد زیرباشد:
1.Dashboard:میانبرها و اطالعات مهم را برای صندوقدار فراهم می کند. مانند: پیام های دریافتی،
سفارشات اخیر، ...
2.Orders:دراینجاعالوه بر وضعیتسفارشو دکمهثبت سفارش،میتوانید وضعیت سفارشها را با
انجام اقداماتی مانند ارسالبه آشپزخانه،در حال پختو…تغییردهید.شما باید چندینsub pages
متناسببا انواع حاالت برایسفارشاتداشته باشید.
سفارشات جدید: لیست سفارشات جدیداز مشتریان.
سفارشاتدر حال پخت: لیست سفارشاتی که به آشپزخانه ارسال می شود.
سفارشاتارائه شده: لیست سفارشاتیکهدر روزبه مشتری ارائه می شود.
سفارشات حذف شده: لیست سفارشاتحذفشده توسط صندوقداریا مشتریان.
سفارشات پرداخت شده: فهرست سفارشات پرداخت شده.
آرشیو: تاریخچه کامل سفارشات مشتریان.
3.Tables:شمارهمیزهای کافه به همراه سفارشات فعلی آنها. صندوقدار می تواند با کلیک بر رویآنها،
لیست سفارشات هرمیزرا مشاهده کند.همچنین می تواند رسیدهای مربوط به هرمیزرا از این صفحه
صادر کنند.
3
4.Menu Items:اقالم (غذاهایی) که توسط کافه سرو می شوند را مدیریت کنید. صندوقدار می تواند هر
محصول را از این صفحه اضافه، ویرایش یا حذف کند.
افزودن اقالم: این بخش به صندوقدار اجازه می دهد تا اقالم جدید (غذاها) را با مشخصات آنها مانند
نام، قیمت، دسته، توضیحات، تخفیف (اختیاری) به منو اضافه کند.
ویرایشو حذف: تغییر قیمت محصوالت، تعیین تخفیف برای هر محصول، اضافه کردن توضیحات
برای آنها، حذف یک محصولاز منوو…
5.Receipts:لیست رسیدهای صادر شده از سامانه.صندوقدار باید به مشاهده، گزارش و مدیریت رسیدها
دسترسی داشته باشد.
جزئیات: صفحه جزئیات رسید.
پرداخت شده: رسیدهای پرداخت شده توسط مشتریان.
آرشیو: تاریخچه رسیدها.
و......
6.Charts(اختیاری): نمودارهای آماری حاوی اطالعاتی مانند:
تعداد سفارشات/ساعت
تعداد سفارشات/روزهای هفته
دسته بندی ها/ساعت سفارش
دسته بندی ها/روزهای هفته
و.......
توجه:میتوانیدبخشCashier Panelرا درپنلادمینجنگوپیاده سازی کنیدو از ویژگی های
پیشرفته تر پنل ادمین و شخصی سازی پنل ادمین استفاده کنید.درغیر این صورت بایدCashier
Panelاختصاصی خود را طراحی کنید.
4
فازهای تحویل تمرین
فازاول:
Git Configuration:یک ریپازیتوری پرایوت در گیتهاب ایجاد کرده وبههمگروهیان و مربیان خود،
دسترسی های الزم را بدهید. برنچهای الزم را ایجاد کنید.نامریپازیتوری شما باید به این صورت
باشد:Maktab93_Cafe_project_group1
ERD: جداول و روابط بین آنهارا بسازید.اتریبیوتهایتیبل هاباید به شرح زیر باشد:
● Users:
○ Id
○ First name
○ Last name
○ Phone number
○ Email
○ Password to login with
○ Extra information such as birthday
○ ...
● Tables:
○ Id
○ Table number
○ Cafe space position
○ ...
● MenuItems:
○ Id
○ Name
○ Price
○ Category
○ Discount (Optional)
○ Serving time period (Optional)
○ Estimated cooking time (Optional)
5
● Orders:
○ Id
○ Table
○ Menu Items (food)
○ Number
○ Status
○ Timestamp
○ …
● Receipts:
○ Id
○ Orders
○ Total price
○ Final price (with Discount)
○ Timestamp,
○ ...
● (Any other needed models)
Models: مدل ها را بسازید.
Home:صفحهاصلیرا ایجاد کنید.
فازدوم:
Landing pageرا به صورت کامل پیاده سازی کنید.
صفحهثبت نام و ورود کاربران عادی و صندوقدار را پیاده سازی کنید.
فازسوم:
Cashier Panelرابه صورتکاملپیاده سازی کنید.
Sessionها و کوکی هارا برای سبد خرید پیاده سازی کنید.
6
نکات
•مهلت ارسالهر فازتا پایان روزچهارشنبههر هفتهاست.
•توجهشود که نمره این پروژه به صورت گروهی محاسبه میشود.
•مسئولیتپذیری،کارتیمیومهارت های نرمکاروندان نیز دارای نمرهمیباشد.
•آدرس ریپازیتوریرا در کارتابل شخصیخوداعالم کردهو تیمتدریسرا بعنوانcollaboratorبیفزایید:
•پوریا منصوری
•الهه پاسبان
•سجاد کاشی
•آرین همدانی
•امیرحسین حسنی
•مالک و معیارارزیابیتاریخآخرینcommitشما میباشد(بصورت استاندارد و اصولیکامیتانجام شود).
•قطعا هدف از تمارین صرفا رسیدن به جواب نهایی نیست و تمیز بودن کد و خالقیتی که در انجامآن به خرج می
دهید از اهمیت و امتیاز باالیی برخوردار است. ارائه راه حل کلی و عمومی برای یک مسئله که حالت های مختلف
آن را در نظر بگیرد و فراتر از خواسته ی مسئله است(خواسته ی مسئله گسترش داده شود یا حالت های خاص
مسئله را پوشش دهد. قطعامشمول امتیاز بیشتریخواهد شد.)
در صورتیکه سوالی داریددر گروه راکت چتبپرسید.
