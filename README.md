# custom_snackbar

A smart and customizable Snackbar widget for Flutter, built using [GetX](https://pub.dev/packages/get).  
This widget allows you to quickly show styled snackbars for different message types (success, error, info, warning).

---

## ✨ Features

- 🎯 Easy to use
- 🎨 Supports multiple types: success, error, warning, info
- ⚙️ Fully customizable (colors, icons, duration, etc.)
- 📍 Show on top or bottom of the screen
- ♻️ Reusable across projects

---

## 🚀 Getting Started

### Add dependency

```yaml
dependencies:
  custom_snackbar: ^0.0.1


#   custom_snackbar: ^0.0.1


Snackbar ذكي قابل للتخصيص باستخدام GetX. مثالي لعرض التنبيهات بطريقة أنيقة وسريعة.

## الميزات

✅ تحديد نوع التنبيه  
✅ تحديد الموقع (أعلى/أسفل)  
✅ تخصيص الألوان والأيقونة  
✅ تصميم جاهز وجذاب

## الاستخدام

```dart
CustomwSnackbar.show(
  title: 'تم',
  message: 'تمت العملية بنجاح',
  type: SnackbarType.success,
  position: SnackbarPosition.top,
);
