---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Устанавливает количество комбов для обычного однострочного текстового поля, которое автоматически делится на столько же равномерно расположенных позиций или комбов, сколько значение параметра combNumber
type: docs
weight: 300
url: /ru/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## Метод FormEditor.SetFieldCombNumber

Устанавливает количество комбов для обычного однострочного текстового поля (поле автоматически делится на столько же равномерно расположенных позиций, или комбов, сколько значение параметра combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Квалифицированное имя поля. |
| combNumber | Int32 | Количество комбов, на которые нужно разделить поле. |

### Возвращаемое значение

Если успешно, возвращает true; в противном случае false.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)