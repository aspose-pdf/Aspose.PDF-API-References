---
title: "Aspose::Pdf::Facades::DefaultMetadataProperties перечисление"
linktitle: "DefaultMetadataProperties"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::DefaultMetadataProperties enum. Перечисление стандартных свойств XMP в C++."
type: docs
weight: 4300
url: /ru/cpp/aspose.pdf.facades/defaultmetadataproperties/
---
## DefaultMetadataProperties enum


Перечисление стандартных свойств XMP.

```cpp
enum class DefaultMetadataProperties
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Рекомендация | 0 | xmp:Advisory property. Неупорядоченный массив, указывающий свойства, отредактированные вне приложения‑создателя. Каждый элемент должен содержать единственный /// namespace и XPath, разделённые одним ASCII‑пробелом |
| BaseURL | 1 | xmp:BaseURL property. Базовый URL для относительных URL‑ов в содержимом документа. Если этот документ содержит интернет‑ссылки, и эти ссылки относительные, /// они относительны к этому базовому URL. Это свойство предоставляет стандартный способ интерпретации вложенных относительных URL‑ов инструментами. /// Инструменты веб‑авторинга должны устанавливать значение, исходя из их представления о том, где URL‑ы будут интерпретированы |
| CreateDate | 2 | xmp:CreateDate property. Дата и время первоначального создания ресурса. |
| CreatorTool | 3 | xmp:CreatorTool property. Имя первого известного инструмента, использованного для создания ресурса. |
| Identifier | 4 | xmp:Identifier property. Неупорядоченный массив текстовых строк, однозначно идентифицирующих ресурс в заданном контексте. |
| MetadataDate | 5 | xmp:MetadataDate property. Дата и время последнего изменения любых метаданных этого ресурса. |
| ModifyDate | 6 | xmp:ModifyDate property. Дата и время последнего изменения ресурса. |
| Nickname | 7 | xmp:Nickname property. Краткое неформальное название ресурса. |
| Thumbnails | 8 | xmp:Thumbnails property. Альтернативный массив миниатюрных изображений файла, которые могут отличаться по характеристикам, таким как размер или кодировка изображения. |

## См. также

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
