# بيستاهل – BISTAHEL

تطبيق جوال لاكتشاف وتقييم المطاعم والمقاهي ومحلات الحلويات والطعام. **ليس تطبيق توصيل.**

## المبادئ
- واجهات عربية بالكامل، اتجاه RTL.
- تقييم المكان منفصل تماماً عن تقييم الطبق أو المنتج.
- قوالب التصميم فارغة دون بيانات تجريبية.

## هيكل المجلدات
- `html/` كود كل شاشة (ملف واحد مستقل، CSS مضمّن، الخط IBM Plex Sans Arabic من Google Fonts)
- `screens/` صورة كل شاشة بنفس اسم الملف
- `DESIGN_SYSTEM.md` الهوية البصرية

## الشاشات
| # | الشاشة | الكود | الصورة | المصدر |
|---|---|---|---|---|
| 00 | نظام التصميم (مرجع) | html/00_design_system.html | screens/00_design_system.png | من Stitch |
| 01 | البداية | html/01_splash.html | screens/01_splash.png | من Stitch |
| 02 | تسجيل الدخول | html/02_login.html | screens/02_login.png | مبنية مباشرة بنفس نظام التصميم |
| 03 | إنشاء حساب | html/03_signup.html | screens/03_signup.png | مبنية مباشرة بنفس نظام التصميم |
| 04 | الرئيسية | html/04_home.html | screens/04_home.png | مبنية مباشرة بنفس نظام التصميم |
| 05 | البحث والنتائج | html/05_search.html | screens/05_search.png | مبنية مباشرة بنفس نظام التصميم |
| 06 | الخريطة | html/06_map.html | screens/06_map.png | من Stitch |
| 07 | تفاصيل المكان – التقييمات | html/07_place_ratings.html | screens/07_place_ratings.png | مبنية مباشرة بنفس نظام التصميم |
| 08 | تفاصيل المكان – الأطباق | html/08_place_dishes.html | screens/08_place_dishes.png | مبنية مباشرة بنفس نظام التصميم |
| 09 | تفاصيل المكان – الآراء | html/09_place_reviews.html | screens/09_place_reviews.png | مبنية مباشرة بنفس نظام التصميم |
| 10 | تفاصيل الطبق | html/10_dish.html | screens/10_dish.png | من Stitch (تحتاج تعديل ألوان/نص) |
| 11 | إضافة تقييم | html/11_add_review.html | screens/11_add_review.png | مبنية مباشرة بنفس نظام التصميم |
| 12 | الملف الشخصي – تقييماتي | html/12_profile_reviews.html | screens/12_profile_reviews.png | مبنية مباشرة بنفس نظام التصميم |
| 13 | الملف الشخصي – المحفوظات | html/13_profile_saved.html | screens/13_profile_saved.png | مبنية مباشرة بنفس نظام التصميم |
| 14 | الملف الشخصي – النشاط | html/14_profile_activity.html | screens/14_profile_activity.png | مبنية مباشرة بنفس نظام التصميم |

ملاحظة: صور الشاشات المبنية مباشرة مولَّدة بخط احتياطي، والخط الحقيقي يظهر عند فتح ملفات HTML مع اتصال بالإنترنت.
