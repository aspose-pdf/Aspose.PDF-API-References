---
title: "Aspose::Pdf::AssemblyConstants class"
linktitle: "AssemblyConstants"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::AssemblyConstants. Определяет константы, участвующие в проверке лицензии компонента. Раньше они определялись напрямую как атрибуты сборки, но я перенес их в отдельный класс, потому что в .NET Compact Framework я не могу получить доступ к атрибутам сборки. Теперь код лицензирования, когда компилируется для .NET Compact Framework, использует эти константы вместо атрибутов сборки в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf/assemblyconstants/
---
## AssemblyConstants class


Определяет константы, участвующие в проверке лицензии компонента. Раньше они определялись напрямую как атрибуты сборки, но я переместил их в отдельный класс, потому что в .NET Compact Framework я не могу получить доступ к атрибутам сборки. Теперь код лицензирования, когда компилируется для .NET Compact Framework, использует эти константы вместо атрибутов сборки.

```cpp
class AssemblyConstants : public System::Object
```

## Поля

| Поле | Описание |
| --- | --- |
| static [Family](./family/) |  |
| static [MicrosoftExtensionsDataIngestionMarkdigVersion](./microsoftextensionsdataingestionmarkdigversion/) |  |
| static [MicrosoftExtensionsDataIngestionVersion](./microsoftextensionsdataingestionversion/) |  |
| static [MicrosoftMLTokenizersDataCl100kBaseVersion](./microsoftmltokenizersdatacl100kbaseversion/) |  |
| static [Platform](./platform/) |  |
| static [Producer](./producer/) | Производитель файла [Pdf](../). |
| static [PRODUCT](./product/) |  |
| static [Product](./product/) | Это используется кодом лицензирования **Aspose** для проверки того, что лицензия предназначена для правильного продукта. |
| static [ReleaseDate](./releasedate/) | Это используется кодом лицензирования **Aspose** для проверки истечения срока подписки. Необходимо установить это значение датой публикации релиза или исправления. |
| static [Title](./title/) |  |
| static [VERSION](./version/) |  |
| static [Version](./version/) | Версия сборки. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
