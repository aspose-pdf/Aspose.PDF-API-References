---
title: FillBarcodeField
second_title: Aspose.PDF для справочника API .NET
description: Заполните поле штрих-кода в соответствии с полным именем поля.
type: docs
weight: 150
url: /ru/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

Заполните поле штрих-кода в соответствии с полным именем поля.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля. |
| data | String | Новое значение штрих-кода. |

### Возвращаемое значение

Если заполнение прошло успешно, вернуть true; в противном случае ложно.

### Примеры

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
