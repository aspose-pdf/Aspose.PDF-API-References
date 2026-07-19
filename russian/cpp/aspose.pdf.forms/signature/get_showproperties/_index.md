---
title: "Aspose::Pdf::Forms::Signature::get_ShowProperties метод"
linktitle: "get_ShowProperties"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::Signature::get_ShowProperties метод. Принудительно показывать/скрывать свойства подписи в C++."
type: docs
weight: 1300
url: /ru/cpp/aspose.pdf.forms/signature/get_showproperties/
---
## Signature::get_ShowProperties method


Принудительно показывать/скрывать свойства подписи.

```cpp
bool Aspose::Pdf::Forms::Signature::get_ShowProperties() const
```

## Примечания


## In case ShowProperties is true signature field has predefined format of appearance (strings to represent): 



Электронно подписано {certificate subject} Дата: {signature.Date} Причина: {signature.Reason} ## Местоположение: {signature.Location}



где {X} — заполнитель для значения X. Также подпись может содержать изображение, в этом случае перечисленные строки размещаются поверх изображения. ShowProperties по умолчанию равно true.
## См. также

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
