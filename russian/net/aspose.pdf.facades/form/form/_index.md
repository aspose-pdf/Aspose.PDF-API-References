---
title: "Form.Form"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор Form. Конструктор Form без параметров."
type: docs
weight: 10
url: /ru/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Конструктор Form без параметров.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Конструктор Form.

```csharp
public Form(string srcFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | String | Путь к исходному файлу. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Конструктор формы.

```csharp
public Form(Stream srcStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | Stream | Поток источника. |

## Примеры

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Инициализирует новый объект [`Form`](../) на основе *document*.

```csharp
public Form(Document document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Document | Pdf документ. |

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


