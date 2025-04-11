---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Construtor de Form. Construtor de Form sem parâmetros
type: docs
weight: 10
url: /pt/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Construtor de Form sem parâmetros.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Construtor de Form.

```csharp
public Form(string srcFileName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcFileName | String | Caminho do arquivo de origem. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Construtor para formulário.

```csharp
public Form(Stream srcStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcStream | Stream | fluxo de origem. |

## Exemplos

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Inicializa um novo objeto [`Form`](../) com base no *documento*.

```csharp
public Form(Document document)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document | Document | Documento Pdf. |

### Veja Também

* classe [Document](../../../aspose.pdf/document/)
* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)