---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Parametre olmadan Form oluşturucu.
type: docs
weight: 10
url: /tr/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Parametre olmadan Form oluşturucu.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Form'un oluşturucusu.

```csharp
public Form(string srcFileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcFileName | String | Kaynak dosya yolu. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Form için oluşturucu.

```csharp
public Form(Stream srcStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcStream | Stream | kaynak akış. |

## Örnekler

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

*belge* temelinde yeni [`Form`](../) nesnesini başlatır.

```csharp
public Form(Document document)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | Document | Pdf belgesi. |

### Ayrıca Bakınız

* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)