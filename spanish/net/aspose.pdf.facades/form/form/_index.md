---
title: Form
second_title: Referencia de API de Aspose.PDF para .NET
description: Constructor de Formulario sin parametros.
type: docs
weight: 10
url: /es/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Constructor de Formulario sin parametros.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

---

## Form(string) {#constructor_8}

Constructor de Form.

```csharp
public Form(string srcFileName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcFileName | String | Ruta del archivo de origen. |

### Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
```

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Constructor para form.

```csharp
public Form(Stream srcStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcStream | Stream | corriente de origen. |

### Ejemplos

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Ver también

* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Inicializa nuevo[`Form`](../../form) objeto sobre la base de la*document* .

```csharp
public Form(Document document)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Document | Documento pdf. |

### Ver también

* class [Document](../../../aspose.pdf/document)
* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
