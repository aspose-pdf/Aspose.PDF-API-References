---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileStamp. Agrega un pie de página a las páginas del documento
type: docs
weight: 110
url: /es/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Agrega un pie de página a las páginas del documento.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que contiene el texto del pie de página y las propiedades del texto. |
| bottomMargin | Single | Margen en la parte superior de la página. |

## Ejemplos

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Ver También

* clase [FormattedText](../../formattedtext/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Agrega un pie de página a las páginas del documento.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que contiene el texto del pie de página y las propiedades del texto. |
| bottomMargin | Single | Margen en la parte inferior de la página. |
| leftMargin | Single | Margen en el lado izquierdo de la página. |
| rightMargin | Single | Margen en el lado derecho de la página. |

## Ejemplos

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Ver También

* clase [FormattedText](../../formattedtext/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Agrega una imagen como pie de página a las páginas del documento.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageFile | String | Nombre y ruta del archivo de imagen. |
| bottomMargin | Single | Margen en la parte inferior de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Agrega una imagen como pie de página de las páginas.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageFile | String | Nombre y ruta del archivo de imagen. |
| bottomMargin | Single | Margen en la parte inferior de la página. |
| leftMargin | Single | Margen en el lado izquierdo de la página. |
| rightMargin | Single | Margen en el lado derecho de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Agrega una imagen como pie de página de la página.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | Stream | El flujo contiene datos de imagen. |
| bottomMargin | Single | Margen en la parte inferior de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Agrega una imagen como pie de página de la página.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | Stream | El flujo contiene datos de imagen. |
| bottomMargin | Single | Margen en la parte inferior de la página. |
| leftMargin | Single | Margen en el lado izquierdo de la página. |
| rightMargin | Single | Margen en el lado derecho de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)