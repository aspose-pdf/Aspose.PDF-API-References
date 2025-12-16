---
title: Aspose::Pdf::CrashReportOptions class
linktitle: CrashReportOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CrashReportOptions class. Options for crash report generating in C++.'
type: docs
weight: 3500
url: /cpp/aspose.pdf/crashreportoptions/
---
## CrashReportOptions class


Options for crash report generating.

```cpp
class CrashReportOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [CrashReportOptions](./crashreportoptions/)(System::Exception) | Creates [CrashReportOptions](./) with default parameters. |
| [get_ApplicationTitle](./get_applicationtitle/)() const | Name of library where exception occured. |
| [get_CrashReportDirectory](./get_crashreportdirectory/)() const | Output directory for crash report. By default is set to current directory. |
| [get_CrashReportFilename](./get_crashreportfilename/)() const | Filename for crash report. By default is auto-generated in format CrashReport_<date>_<ticks>.html". |
| [get_CrashReportPath](./get_crashreportpath/)() | Full path of crash report file. |
| [get_CustomMessage](./get_custommessage/)() const | Custom message to include into the report. It can be something like value of variables or other details you want to send. |
| [get_Exception](./get_exception/)() const | Exception that crash report will be based on. |
| [get_LibraryVersion](./get_libraryversion/)() const | Version of library used. |
| [set_CrashReportDirectory](./set_crashreportdirectory/)(System::String) | Output directory for crash report. By default is set to current directory. |
| [set_CrashReportFilename](./set_crashreportfilename/)(System::String) | Filename for crash report. By default is auto-generated in format CrashReport_<date>_<ticks>.html". |
| [set_CustomMessage](./set_custommessage/)(System::String) | Custom message to include into the report. It can be something like value of variables or other details you want to send. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
