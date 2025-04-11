---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: Свойство OriginalFontSpecification. Получает значение, указывающее на то, что замена неизбежна
type: docs
weight: 20
url: /ru/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## Свойство CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable

Получает значение, указывающее на то, что замена неизбежна.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Примечания

Возвращает true в случае, если замена была запрошена из-за отсутствия оригинального шрифта или если оригинальный шрифт не может быть использован в контексте какой-либо задачи. В случае, если пользователь игнорирует флаг и не заменяет шрифт - выполняется процедура замены шрифта по умолчанию. Но это предоставляет возможность пользователю изменить стандартную процедуру замены шрифта и установить лучший шрифт в систему. Возвращает false в случае, если оригинальный шрифт присутствует, действителен, но пользователю разрешено его заменить.

### См. также

* класс [OriginalFontSpecification](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)