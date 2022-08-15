---
title: TextFragmentAbsorber
second_title: Referencia de API de Aspose.PDF para .NET
description: Inicializa una nueva instancia delTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber que realiza la búsqueda de todos los segmentos de texto del documento o página.
type: docs
weight: 10
url: /es/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber) que realiza la búsqueda de todos los segmentos de texto del documento o página.

```csharp
public TextFragmentAbsorber()
```

### Observaciones

Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda a través de[`TextFragments`](../textfragments) recopilación.

### Ejemplos

El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Encuentra la fuente que se usará para cambiar la fuente del texto del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crear objeto TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Hacer que el absorbedor busque todas las apariciones de texto "hola mundo"
absorber.Phrase = "hello world";

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambia el texto de la primera aparición de texto
absorber.TextFragments[1].Text = "hi world";

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber)con opciones de edición de texto, que realiza la búsqueda de todos los segmentos de texto del documento o página.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Opciones de edición de texto (permite activar algunas funciones de edición). |

### Observaciones

Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda a través de[`TextFragments`](../textfragments) recopilación.

### Ejemplos

El ejemplo demuestra cómo encontrar todos los fragmentos de texto en la primera página del documento PDF y reemplazar la fuente por ellos.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crear objeto TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Encuentra la fuente Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Establecer la fuente para todos los fragmentos de texto
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");
```

### Ver también

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber) clase para la frase de texto especificada.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| phrase | String | Frase que el[`TextFragmentAbsorber`](../../textfragmentabsorber) búsquedas |

### Observaciones

Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda a través de[`TextFragments`](../textfragments) colección.

### Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Encuentra la fuente que se usará para cambiar la fuente del texto del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambia el texto y la fuente de la primera aparición de texto
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber) clase para el objeto de clase System.Text.RegularExpressions.Regex especificado.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| regex | Regex | Objeto de clase System.Text.RegularExpressions.Regex que el[`TextFragmentAbsorber`](../../textfragmentabsorber) búsquedas |

### Observaciones

Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda a través de[`TextFragments`](../textfragments) colección.

### Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Encuentra la fuente que se usará para cambiar la fuente del texto del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crear objeto TextAbsorber para encontrar todas las instancias de la expresión regular de entrada
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// debemos encontrar la palabra "hola" y reemplazarla con "Hola"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");
```

### Ver también

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber)clase para la frase de texto especificada y las opciones de búsqueda de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| phrase | String | Frase que el[`TextFragmentAbsorber`](../../textfragmentabsorber) búsquedas |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto (Permite activar algunas funciones de búsqueda. Por ejemplo, buscar con expresión regular) |

### Observaciones

Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda a través de[`TextFragments`](../textfragments) colección.

### Ejemplos

El ejemplo demuestra cómo encontrar texto con una expresión regular en la primera página del documento PDF y reemplazar el texto.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un objeto TextFragmentAbsorber que busca todas las palabras que comienzan con 'h' y terminan con 'o' usando una expresión regular.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// debemos encontrar la palabra "hola" y reemplazarla con "Hola"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber) clase para la frase de texto especificada y las opciones de búsqueda de texto.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| regex | Regex | Objeto de clase System.Text.RegularExpressions.Regex que el[`TextFragmentAbsorber`](../../textfragmentabsorber) búsquedas |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto (permite activar algunas funciones de búsqueda). |

### Observaciones

Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda a través de[`TextFragments`](../textfragments) colección.

### Ejemplos

El ejemplo demuestra cómo encontrar texto con una expresión regular en la primera página del documento PDF y reemplazar el texto.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un objeto TextFragmentAbsorber que busca todas las palabras que comienzan con 'h' y terminan con 'o' usando una expresión regular.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// debemos encontrar la palabra "hola" y reemplazarla con "Hola"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");
```

### Ver también

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber) clase para la frase de texto especificada, opciones de búsqueda de texto y opciones de edición de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| phrase | String | Frase que el[`TextFragmentAbsorber`](../../textfragmentabsorber) búsquedas |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto (Permite activar algunas funciones de búsqueda. Por ejemplo, buscar con expresión regular) |
| textEditOptions | TextEditOptions | Opciones de edición de texto (permite activar algunas funciones de edición). |

### Observaciones

Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda a través de[`TextFragments`](../textfragments) colección.

### Ejemplos

El ejemplo demuestra cómo encontrar texto con una expresión regular en la primera página del documento PDF y reemplazar el texto.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un objeto TextFragmentAbsorber que busca todas las palabras que comienzan con 'h' y terminan con 'o' usando una expresión regular.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// debemos encontrar la palabra "hola" y reemplazarla con "Hola"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber) clase para la frase de texto especificada y las opciones de edición de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| phrase | String | Frase que el[`TextFragmentAbsorber`](../../textfragmentabsorber) búsquedas |
| textEditOptions | TextEditOptions | Opciones de edición de texto (permite activar algunas funciones de edición). |

### Observaciones

Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda a través de[`TextFragments`](../textfragments) colección.

### Ver también

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Inicializa una nueva instancia del[`TextFragmentAbsorber`](../../textfragmentabsorber) clase para la frase de texto especificada y las opciones de edición de texto.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| regex | Regex | Objeto de clase System.Text.RegularExpressions.Regex que el[`TextFragmentAbsorber`](../../textfragmentabsorber) búsquedas |
| textEditOptions | TextEditOptions | Opciones de edición de texto (permite activar algunas funciones de edición). |

### Observaciones

Realiza una búsqueda de texto de la frase especificada y proporciona acceso a los resultados de la búsqueda a través de[`TextFragments`](../textfragments) colección.

### Ver también

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../textfragmentabsorber)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
