---
title: "Метод Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer::SanitizeAllToImages"
linktitle: "SanitizeAllToImages"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer::SanitizeAllToImages. Заменяет содержимое страниц изображениями и удаляет остальные скрытые данные. Позволяет удалить скрытый текст с фоновым цветом, а также текст, скрытый под изображениями. Также полностью удаляет все интерактивные элементы. Документ преобразуется в изображения в исходном виде, после чего очищается от оставшихся скрытых данных. Если необходимо сначала очистить, а затем выполнить конвертацию, используйте основной метод класса в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/sanitizealltoimages/
---
## HiddenDataSanitizer::SanitizeAllToImages method


Заменяет содержимое страниц изображениями и удаляет другие скрытые данные. Позволяет удалять скрытый текст с фоновым цветом, а также текст, скрытый под изображениями. Также полностью удаляет все интерактивные элементы. Документ конвертируется в изображения в текущем виде, а затем очищается от оставшихся скрытых данных. Если необходимо сначала очистить, а затем конвертировать, используйте метод главного класса.

```cpp
static void Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer::SanitizeAllToImages(const System::SharedPtr<Document> &document, int32_t dpi=150)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | const System::SharedPtr\<Document\>\& | Объект документа. |
| dpi | int32_t | Разрешение (dpi) изображений страниц. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [HiddenDataSanitizer](../)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../../)
* Library [Aspose.PDF for C++](../../../)
