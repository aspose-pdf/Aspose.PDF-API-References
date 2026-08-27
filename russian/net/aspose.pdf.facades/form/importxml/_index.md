---
title: "Form.ImportXml"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Импортирует содержимое полей из xml‑файла и помещает его в новый pdf."
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Импортирует содержимое полей из файла xml и помещает их в новый pdf.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXmlStream | Stream | Поток, из которого читается XML для импорта. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Импортирует содержимое полей из файла xml и помещает их в новый pdf.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXmlStream | Stream | Входной xml‑поток. |
| IgnoreFormTemplateChanges | Boolean | Если этот параметр установлен в true, все изменения шаблона формы XFA не будут сохранены. |

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


