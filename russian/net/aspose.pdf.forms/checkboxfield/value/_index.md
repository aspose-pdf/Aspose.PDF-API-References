---
title: "CheckboxField.Value"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство CheckboxField. Получает или задает значение поля флажка"
type: docs
weight: 70
url: /ru/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

Получает или задаёт значение поля флажка.

```csharp
public override string Value { get; set; }
```

## Примеры

Пример демонстрирует, как получить и установить значение многозначного флажка.

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// Допустимые значения можно получить из коллекции AllowedStates
// Установите значение флажка, используя свойство Value
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// Значение должно быть любым элементом из AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Снимите отметку с флажков, установив Value в "Off" или установив Checked в false
checkbox.Value = "Off";
// или, альтернативно:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### См. также

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


