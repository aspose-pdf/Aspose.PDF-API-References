---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Заполните поле штрих-кода в соответствии с его полным именем поля
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Метод Form.FillBarcodeField

Заполните поле штрих-кода в соответствии с его полным именем поля.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля. |
| data | String | Новое значение штрих-кода. |

### Возвращаемое значение

Если заполнение прошло успешно, возвращает true; в противном случае - false.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)