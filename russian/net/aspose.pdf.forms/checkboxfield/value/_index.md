---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: Свойство CheckboxField. Получает или устанавливает значение поля флажка
type: docs
weight: 70
url: /ru/net/aspose.pdf.forms/checkboxfield/value/
---
## Свойство CheckboxField.Value

Получает или устанавливает значение поля флажка.

```csharp
public override string Value { get; set; }
```

## Примеры

Пример демонстрирует, как получить и установить значение многофункционального флажка.

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// Allowed values may be retrieved from the AllowedStates collection
// Set the checkbox value using Value property
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// The value should be any element of AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Uncheck boxes by either setting Value to "Off" or setting Checked to false
checkbox.Value = "Off";
// or, alternately:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### См. также

* класс [CheckboxField](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)