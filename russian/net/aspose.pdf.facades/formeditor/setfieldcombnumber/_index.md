---
title: "FormEditor.SetFieldCombNumber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Устанавливает количество ячеек (combs) для обычного однострочного текстового поля; поле автоматически делится на столько равноотстоящих позиций, сколько указано в параметре combNumber."
type: docs
weight: 300
url: /ru/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

Устанавливает количество ячеек (comb) для обычного однострочного текстового поля (поле автоматически делится на столько равноотстоящих позиций, или ячеек, сколько указано в параметре combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное (квалифицированное) имя поля. |
| combNumber | Int32 | Количество ячеек (combs), на которое делится поле. |

### Возвращаемое значение

Если успешно, возвращает true; иначе false.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


