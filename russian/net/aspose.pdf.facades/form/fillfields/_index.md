---
title: "Form.FillFields"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Заполняет поля текстовых полей заданными текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Обратите внимание: применяется только к текстовым полям. И имена полей, и их значения чувствительны к регистру."
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

Заполняет поля текстового поля текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Примечание: применяется только к полю Text Box. И имена полей, и значения чувствительны к регистру.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldNames | String[] | Имена полей. |
| fieldValues | String[] | Новые значения полей. |
| output | Stream& | Поток, в котором будет сохранён документ. |

### Возвращаемое значение

true, если поля найдены и успешно заполнены.

## Примеры

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


