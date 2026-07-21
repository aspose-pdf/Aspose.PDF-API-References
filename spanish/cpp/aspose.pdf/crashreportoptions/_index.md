---
title: "Aspose::Pdf::CrashReportOptions class"
linktitle: "CrashReportOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::CrashReportOptions class. Opciones para generar informes de fallos en C++."
type: docs
weight: 3300
url: /es/cpp/aspose.pdf/crashreportoptions/
---
## CrashReportOptions class


Opciones para generar informes de fallos.

```cpp
class CrashReportOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CrashReportOptions](./crashreportoptions/)(System::Exception) | Crea [CrashReportOptions](./) con parámetros predeterminados. |
| [get_ApplicationTitle](./get_applicationtitle/)() const | Nombre de la biblioteca donde ocurrió la excepción. |
| [get_CrashReportDirectory](./get_crashreportdirectory/)() const | Directorio de salida para el informe de fallos. Por defecto se establece en el directorio actual. |
| [get_CrashReportFilename](./get_crashreportfilename/)() const | Nombre de archivo para el informe de fallos. Por defecto se genera automáticamente en el formato CrashReport_<date>_<ticks>.html\". |
| [get_CrashReportPath](./get_crashreportpath/)() | Ruta completa del archivo de informe de fallos. |
| [get_CustomMessage](./get_custommessage/)() const | Mensaje personalizado para incluir en el informe. Puede ser algo como el valor de variables u otros detalles que desees enviar. |
| [get_Exception](./get_exception/)() const | Excepción en la que se basará el informe de fallos. |
| [get_LibraryVersion](./get_libraryversion/)() const | Versión de la biblioteca utilizada. |
| [set_CrashReportDirectory](./set_crashreportdirectory/)(const System::String\&) | Directorio de salida para el informe de fallos. Por defecto se establece en el directorio actual. |
| [set_CrashReportFilename](./set_crashreportfilename/)(const System::String\&) | Nombre de archivo para el informe de fallos. Por defecto se genera automáticamente en el formato CrashReport_<date>_<ticks>.html\". |
| [set_CustomMessage](./set_custommessage/)(const System::String\&) | Mensaje personalizado para incluir en el informe. Puede ser algo como el valor de variables u otros detalles que desees enviar. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
