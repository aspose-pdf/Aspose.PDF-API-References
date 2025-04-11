---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: Método FontRepository. Pesquisa e retorna a fonte com o nome de fonte especificado
type: docs
weight: 40
url: /pt/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Pesquisa e retorna a fonte com o nome de fonte especificado.

```csharp
public static Font FindFont(string fontName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | String | Nome da fonte. |

### Valor de Retorno

Objeto de fonte.

## Exemplos

O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* classe [Font](../../font/)
* classe [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Pesquisa e retorna a fonte com o nome de fonte especificado, ignorando ou respeitando a sensibilidade a maiúsculas e minúsculas.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | String | Nome da fonte. |
| ignoreCase | Boolean | sensibilidade a maiúsculas e minúsculas |

### Valor de Retorno

Objeto de fonte.

## Exemplos

O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* classe [Font](../../font/)
* classe [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Pesquisa e retorna a fonte com o nome de fonte especificado e estilo de fonte.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontFamilyName | String | Nome da família da fonte. |
| stl | FontStyles | Valor do estilo da fonte. |

### Valor de Retorno

Objeto de fonte correspondente aos parâmetros da solicitação de pesquisa.

## Exemplos

O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* classe [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* classe [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Pesquisa e retorna a fonte com o nome de fonte especificado e estilo de fonte, ignorando ou respeitando a sensibilidade a maiúsculas e minúsculas.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontFamilyName | String | Nome da família da fonte. |
| stl | FontStyles | Valor do estilo da fonte. |
| ignoreCase | Boolean | sensibilidade a maiúsculas e minúsculas |

### Valor de Retorno

Objeto de fonte correspondente aos parâmetros da solicitação de pesquisa.

## Exemplos

O exemplo demonstra como encontrar a fonte e substituir a fonte do texto da primeira página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* classe [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* classe [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)