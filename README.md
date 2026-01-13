# Medicine-Reminder
Medicine Reminder is a Flutter &amp; Dart application that allows users to add medicines with dosage and time, receive scheduled reminders, and view a neatly sorted daily medicine list with a clean, user-friendly UI.


lib/
├── main.dart
├── data/
│   ├── models/
│   │   └── medicine.dart
│   └── repositories/
│       └── medicine_repository.dart
├── presentation/
│   ├── pages/
│   │   ├── home_page.dart
│   │   └── add_medicine_page.dart
│   └── widgets/
│       ├── medicine_card.dart
│       └── time_picker_field.dart
└── core/
    ├── theme/
    │   └── app_theme.dart
    └── utils/
        └── notifications.dart
