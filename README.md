# Laravel-E-Commerce-Admin-Dashboard-AdminLTE-QR-Barcodes-
منصّة إدارة متجر إلكتروني


 المزايا الأساسية:

لوحة إدارة جاهزة: مبنية على AdminLTE باندماج نظيف مع Laravel UI.

نظام صلاحيات مبسّط: حقل role داخل جدول المستخدمين لتفريق صلاحيات الإدارة/المستخدم.

وحدات المتجر:

Categories: إنشاء/تعديل/حذف الفئات.

Products: إدارة المنتجات مع صور متعددة وخصائص إضافية.

Product Images: رفع وإدارة صور المنتجات.

Reviews: حفظ تقييمات/تعليقات المستخدمين على المنتجات.

Customers: إدارة بيانات العملاء، مع جدول مستقل لصور العملاء (Customer Images).

QR/Barcodes: توليد أكواد (QR/Barcode) للمنتجات أو السجلات المطلوبة لتسهيل التتبع والفوترة.

Localization بسيط: حقول عربية في المنتجات (مثل name_ar) لعرض أسماء المنتجات بالعربية.

Seeders ومهاجرات كاملة: قواعد البيانات تُجهّز عبر مهاجرات مرتبة وSeeders افتراضية (مثل UsersTableSeeder).

قاعدة البيانات (نماذج وMigrations ملحوظة)

Users (+ role)

Categories

Products (+ name_ar)

Product Images

Reviews

Customers

Customer Images

يوجد ملفّات مهاجرات متعددة تُنشئ هذه الجداول مع ترتيب زمني واضح، بالإضافة إلى Seeders مثل UsersTableSeeder.
