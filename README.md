# بيستاهل – BISTAHEL

تطبيق جوال لاكتشاف وتقييم المطاعم والمقاهي ومحلات الحلويات والطعام. **ليس تطبيق توصيل.**

## المبادئ
- واجهات عربية بالكامل، اتجاه RTL.
- تقييم المكان منفصل تماماً عن تقييم الطبق أو المنتج.
- قوالب التصميم فارغة دون بيانات تجريبية.

## هيكل المجلدات
- ملفات `.html`: كود كل شاشة (ملف مستقل، CSS مضمّن، الخط IBM Plex Sans Arabic من Google Fonts)
- ملفات `.png`: صورة كل شاشة بنفس الرقم والاسم (كل شاشة ملفان متجاوران)
- `DESIGN_SYSTEM.md` الهوية البصرية
- `logo.png` و`logo-mark.png`: الشعار (شفاف)

## الشاشات
| # | الشاشة | الكود | الصورة | المصدر |
|---|---|---|---|---|
| 00 | نظام التصميم (مرجع) | 00_design_system.html | 00_design_system.png | من Stitch |
| 01 | البداية | 01_splash.html | 01_splash.png | من Stitch |
| 02 | تسجيل الدخول | 02_login.html | 02_login.png | مبنية مباشرة بنفس نظام التصميم |
| 03 | إنشاء حساب | 03_signup.html | 03_signup.png | مبنية مباشرة بنفس نظام التصميم |
| 04 | الرئيسية | 04_home.html | 04_home.png | مبنية مباشرة بنفس نظام التصميم |
| 05 | البحث والنتائج | 05_search.html | 05_search.png | مبنية مباشرة بنفس نظام التصميم |
| 06 | الخريطة | 06_map.html | 06_map.png | من Stitch |
| 07 | تفاصيل المكان – التقييمات | 07_place_ratings.html | 07_place_ratings.png | مبنية مباشرة بنفس نظام التصميم |
| 08 | تفاصيل المكان – الأطباق | 08_place_dishes.html | 08_place_disches.png | مبنية مباشرة بنفس نظام التصميم |
| 09 | تفاصيل المكان – الآراء | 09_place_reviews.html | 09_place_reviews.png | مبنية مباشرة بنفس نظام التصميم |
| 10 | تفاصيل الطبق | 10_dish.html | 10_dish.png | أُعيد بناؤها بنفس نظام التصميم (v1.1) |
| 11 | إضافة تقييم | 11_add_review.html | 11_add_review.png | مبنية مباشرة بنفس نظام التصميم |
| 12 | الملف الشخصي – تقييماتي | 12_profile_reviews.html | 12_profile_reviews.png | مبنية مباشرة بنفس نظام التصميم |
| 13 | الملف الشخصي – المحفوظات | 13_profile_saved.html | 13_profile_saved.png | مبنية مباشرة بنفس نظام التصميم |
| 14 | الملف الشخصي – النشاط | 14_profile_activity.html | 14_profile_activity.png | مبنية مباشرة بنفس نظام التصميم |
| 15 | البحث – لا توجد نتائج | 15_search_empty.html | 15_search_empty.png | حالة فارغة |
| 16 | المحفوظات – فارغة | 16_saved_empty.html | 16_saved_empty.png | حالة فارغة |
| 17 | إضافة تقييم – معبّأة | 17_add_review_filled.html | 17_add_review_filled.png | حالة تفاعلية (نجوم مختارة، حقول مفعّلة) |
| 18 | تسجيل الدخول – خطأ | 18_login_error.html | 18_login_error.png | حالة خطأ في حقل |
| 19 | تم نشر التقييم | 19_review_published.html | 19_review_published.png | شاشة تأكيد |
| 20 | الرئيسية – تحميل | 20_home_loading.html | 20_home_loading.png | حالة تحميل (Skeleton متحرك) |
| 21 | لا يوجد اتصال | 21_no_connection.html | 21_no_connection.png | حالة خطأ شبكة |
| 22 | المكان – لا توجد آراء | 22_place_no_reviews.html | 22_place_no_reviews.png | حالة فارغة |
| 23 | تصفية النتائج | 23_filter_sheet.html | 23_filter_sheet.png | ورقة سفلية (Bottom sheet) |
| 24 | تأكيد الحذف | 24_confirm_delete.html | 24_confirm_delete.png | نافذة تأكيد |

ملاحظة: صور الشاشات المبنية مباشرة مولَّدة بخط احتياطي، والخط الحقيقي يظهر عند فتح ملفات HTML مع اتصال بالإنترنت.

الشاشات 15–24 هي حالات (فارغة، تفاعلية، خطأ، تأكيد). نصوصها رسائل واجهة فقط وليست بيانات تجريبية.
