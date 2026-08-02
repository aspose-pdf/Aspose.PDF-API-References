---
title: "Form.FillBarcodeField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Заполняет поле штрихкода согласно его полностью квалифицированному имени поля."
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

Заполняет поле штрихкода в соответствии с его полностью квалифицированным именем.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полностью квалифицированное имя поля. |
| data | String | Новое значение штрихкода. |

### Возвращаемое значение

Если заполнение успешно, возвращает true; иначе — false.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


