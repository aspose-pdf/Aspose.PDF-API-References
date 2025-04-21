---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Заполняет текстовые поля значениями текста и сохраняет документ. Актуально для подписанных документов. Обратите внимание применяется только к текстовым полям. Имена полей и значения чувствительны к регистру.
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/form/fillfields/
---
## Метод Form.FillFields

Заполняет текстовые поля значениями текста и сохраняет документ. Актуально для подписанных документов. Обратите внимание: применяется только к текстовым полям. Имена полей и значения чувствительны к регистру.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldNames | String[] | Имена полей. |
| fieldValues | String[] | Новые значения полей. |
| output | Stream& | Поток, в который будет сохранен документ. |

### Возвращаемое значение

true, если поля были найдены и успешно заполнены.

## Примеры

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)