# Список изменений Nova X 7.13 SE (alpha3)

## Глобальные изменения
- Исправление критической ошибки в alpha2, из-за которой происходил вылет на Android M;
- Чистка ресурсов и мелкие исправления;

---

# Список изменений Nova X 7.13 SE (alpha2)

## Глобальные изменения
- Чистка ресурсов и мелкие исправления;

## Интерфейс
- Добавлен компонент PreferenceDesc (описание к пунктам);
- Импорт перевода лабаратории из Nova X 7.12;
- Настройки Nova X:
  - Настройки панели "Избранное" перенесены в раздел "Рабочий стол";
  - Рабочий стол:
    - Добавлена возможность увеличить сетку больше стандартного значения (было 12x12 - стало 24x24);
    - Панель "Избранное":
      - Увеличено количество допустимых иконок в панели "Избранное" (было 7 - стало 14);

---

# Список изменений Nova X 7.13 SE (alpha1)

## Глобальные изменения
- Полностью переработанная база Nova Launcher 5.5.4;
- Полная поддержка файла рез. копирования от ориг. Nova Launcher;
- Почищена папка _res/_:
  - Удалена лишняя графика;
  - Удалена лишняя разметка;
  - Удалены лишние локализации (only ru);
- Почищена папка _smali/_:
  - Удалена полностью папка _tesladirect/_:
    - Удалены исходники ОТА-клиента - *ChangeLogDialog.smali*, *ChangeLogDialog$1.smali*, *ChangeLogDialog$2.smali*, *ChangeLogDialog$3.smali*, *ChangeLogDialog$4.smali*, *ChangeLogDialog$5.smali*, *ChangeLogDialog$6.smali*, *ChangeLogDialog$7.smali*, *ChangeLogDialog$7$1.smali*, *ChangeLogDialog$7$2.smali*, *ChangeLogDialog$8.smali*, *ChangeLogDialog_ViewBinding.smali*;
    - Удалены исходники проверки лицензии Google Play - *DirectLicenseEnterCode.smali*, *DirectLicenseEnterCode$1.smali*, *DirectLicenseEnterCode$2.smali*, *DirectLicenseEnterCode$3.smali*, *DirectLicenseEnterCode$4.smali*, *DirectLicenseEnterCode$5.smali*, *DirectLicenseEnterCode$6.smali*, *DirectLicenseEnterCode$7.smali*;

## Интерфейс
- Импорт _strings.xml_ из Nova X 7.12;
- Настройки NovaX:
  - Удалён пункт "Сказать спасибо" (также удалён smali-код);
  - Убран пункт "Проверить обновления";
  - Лёгкая реорганизация;

> **Обратите внимание:** Это alpha-версия и это даже не тест, а предварительный обзор. Тем не менее - баг-репорты и отзывы принимаются по адресу _rx1310@inbox.ru_.
