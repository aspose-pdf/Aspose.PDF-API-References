---
title: TextSegment
second_title: Referencia de API de Aspose.PDF para .NET
description: Crea el objeto TextSegment.
type: docs
weight: 10
url: /es/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Crea el objeto TextSegment.

```csharp
public TextSegment()
```

### Ejemplos

El ejemplo muestra cómo crear un objeto de fragmento de texto, agregar un segmento de texto a la colección de fragmentos de texto y adjuntarlo a la página PDF.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// crea un fragmento de texto
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// establecer sus propiedades de texto
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// agregar un segmento más a la colección Segmentos del fragmento de texto
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// crea el objeto TextBuilder
TextBuilder builder = new TextBuilder(page);

// agregar el fragmento de texto a la página PDF
builder.AppendText(tf);

//guardar documento
doc.Save(outFile);
```

### Ver también

* class [TextSegment](../../textsegment)
* espacio de nombres [Aspose.Pdf.Text](../../textsegment)
* asamblea [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Crea el objeto TextSegment.

```csharp
public TextSegment(string text)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| text | String | Texto del segmento de texto. |

### Ejemplos

El ejemplo muestra cómo crear un objeto de fragmento de texto, agregar un segmento de texto a la colección de fragmentos de texto y adjuntarlo a la página PDF.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// crea un fragmento de texto
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// establecer sus propiedades de texto
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// agregar un segmento más a la colección Segmentos del fragmento de texto
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// crea el objeto TextBuilder
TextBuilder builder = new TextBuilder(page);

// agregar el fragmento de texto a la página PDF
builder.AppendText(tf);

//guardar documento
doc.Save(outFile);
```

### Ver también

* class [TextSegment](../../textsegment)
* espacio de nombres [Aspose.Pdf.Text](../../textsegment)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->