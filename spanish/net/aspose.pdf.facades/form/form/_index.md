---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Constructor de Form. Constructor de Form sin parámetros
type: docs
weight: 10
url: /es/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Constructor de Form sin parámetros.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Constructor de Form.

```csharp
public Form(string srcFileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | String | Ruta del archivo fuente. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Constructor para formulario.

```csharp
public Form(Stream srcStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcStream | Stream | flujo fuente. |

## Ejemplos

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Inicializa un nuevo objeto [`Form`](../) basado en el *documento*.

```csharp
public Form(Document document)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | Document | Documento Pdf. |

### Ver También

* clase [Document](../../../aspose.pdf/document/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)