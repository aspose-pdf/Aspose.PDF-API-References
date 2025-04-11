---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileStamp. Agrega encabezado a la página
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Agrega encabezado a la página.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Texto para el encabezado y propiedades del texto. |
| topMargin | Single | Margen en la parte superior de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Ver También

* clase [FormattedText](../../formattedtext/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Agrega encabezado a las páginas del archivo.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Objeto de texto formateado que contiene el texto de la página y sus propiedades. |
| topMargin | Single | Margen en la parte superior de la página. |
| leftMargin | Single | Margen en el lado izquierdo de la página. |
| rightMargin | Single | Margen en el lado derecho de la página. |

## Ejemplos

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Ver También

* clase [FormattedText](../../formattedtext/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Agrega imagen como encabezado a las páginas del archivo.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageFile | String | Ruta al archivo de imagen. |
| topMargin | Single | Margen en la parte superior de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Agrega imagen como encabezado en las páginas.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageFile | String | Ruta al archivo de imagen. |
| topMargin | Single | Margen en la parte superior de la página. |
| leftMargin | Single | Margen en el lado izquierdo de la página. |
| rightMargin | Single | Margen en el lado derecho de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Agrega imagen como encabezado en las páginas.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | Stream | Flujo de la imagen. |
| topMargin | Single | Margen en la parte superior de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Agrega imagen en la parte superior de la página.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo que contiene los datos de la imagen. |
| topMargin | Single | Margen en la parte superior de la página. |
| leftMargin | Single | Margen en el lado izquierdo de la página. |
| rightMargin | Single | Margen en el lado derecho de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)