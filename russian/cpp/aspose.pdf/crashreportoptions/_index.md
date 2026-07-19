---
title: "Aspose::Pdf::CrashReportOptions класс"
linktitle: "CrashReportOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::CrashReportOptions класс. Параметры генерации отчёта о сбое в C++."
type: docs
weight: 3300
url: /ru/cpp/aspose.pdf/crashreportoptions/
---
## CrashReportOptions class


Параметры генерации отчёта о сбое.

```cpp
class CrashReportOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [CrashReportOptions](./crashreportoptions/)(System::Exception) | Создаёт [CrashReportOptions](./) с параметрами по умолчанию. |
| [get_ApplicationTitle](./get_applicationtitle/)() const | Имя библиотеки, в которой произошла ошибка. |
| [get_CrashReportDirectory](./get_crashreportdirectory/)() const | Каталог вывода для отчёта о сбое. По умолчанию установлен в текущий каталог. |
| [get_CrashReportFilename](./get_crashreportfilename/)() const | Имя файла для отчёта о сбое. По умолчанию генерируется автоматически в формате CrashReport_<date>_<ticks>.html". |
| [get_CrashReportPath](./get_crashreportpath/)() | Полный путь к файлу отчёта о сбое. |
| [get_CustomMessage](./get_custommessage/)() const | Пользовательское сообщение для включения в отчёт. Это может быть, например, значение переменных или другие детали, которые вы хотите отправить. |
| [get_Exception](./get_exception/)() const | Исключение, на основе которого будет сформирован отчёт о сбое. |
| [get_LibraryVersion](./get_libraryversion/)() const | Версия используемой библиотеки. |
| [set_CrashReportDirectory](./set_crashreportdirectory/)(const System::String\&) | Каталог вывода для отчёта о сбое. По умолчанию установлен в текущий каталог. |
| [set_CrashReportFilename](./set_crashreportfilename/)(const System::String\&) | Имя файла для отчёта о сбое. По умолчанию генерируется автоматически в формате CrashReport_<date>_<ticks>.html". |
| [set_CustomMessage](./set_custommessage/)(const System::String\&) | Пользовательское сообщение для включения в отчёт. Это может быть, например, значение переменных или другие детали, которые вы хотите отправить. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
