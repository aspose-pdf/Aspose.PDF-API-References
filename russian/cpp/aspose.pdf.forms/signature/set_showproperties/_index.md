---
title: "Метод Aspose::Pdf::Forms::Signature::set_ShowProperties"
linktitle: "set_ShowProperties"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Forms::Signature::set_ShowProperties. Принудительно отображает/скрывает свойства подписи в C++."
type: docs
weight: 2700
url: /ru/cpp/aspose.pdf.forms/signature/set_showproperties/
---
## Signature::set_ShowProperties method


Принудительно показывать/скрывать свойства подписи.

```cpp
void Aspose::Pdf::Forms::Signature::set_ShowProperties(bool value)
```

## Примечания


## In case ShowProperties is true signature field has predefined format of appearance (strings to represent): 



Электронно подписано {certificate subject} Дата: {signature.Date} Причина: {signature.Reason} ## Местоположение: {signature.Location}



где {X} — заполнитель для значения X. Также подпись может содержать изображение, в этом случае перечисленные строки размещаются поверх изображения. ShowProperties по умолчанию равно true.
## См. также

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
