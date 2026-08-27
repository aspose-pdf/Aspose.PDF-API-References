---
title: "CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство OriginalFontSpecification. Возвращает значение, указывающее, что замена неизбежна"
type: docs
weight: 20
url: /ru/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable property

Возвращает значение, указывающее, что замена неизбежна.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Примечания

Возвращает true, если замена была запрошена из‑за отсутствия оригинального шрифта или если оригинальный шрифт нельзя использовать в контексте некоторой задачи. Если пользователь игнорирует флаг и не заменяет шрифт, выполняется процедура замены шрифта по умолчанию. Однако это предоставляет возможность пользователю изменить стандартную процедуру замены шрифта и установить более подходящий шрифт в системе. Возвращает false, если оригинальный шрифт присутствует, действителен, но пользователю разрешено его заменить.

### См. также

* class [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


