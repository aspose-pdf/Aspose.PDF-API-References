---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: Método FontRepository. Abre a fonte com o fluxo de fonte especificado
type: docs
weight: 60
url: /pt/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Abre a fonte com o fluxo de fonte especificado.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontStream | Stream | Fluxo de fonte. |
| fontType | FontTypes | Valor do tipo de fonte. |

### Valor de Retorno

Objeto de fonte.

## Exemplos

O exemplo demonstra como abrir a fonte e substituir a fonte do texto da primeira página.

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### Veja Também

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Abre a fonte com o caminho do arquivo de fonte especificado.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontFilePath | String | Caminho do arquivo de fonte. |

### Valor de Retorno

Objeto de fonte.

## Exemplos

O exemplo demonstra como abrir a fonte e substituir a fonte do texto da primeira página.

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Abre a fonte com o caminho do arquivo de fonte especificado e o caminho do arquivo de métricas.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontFilePath | String | Caminho do arquivo de fonte. |
| metricsFilePath | String | Caminho do arquivo de métricas da fonte. |

### Valor de Retorno

Objeto de fonte.

## Exemplos

O exemplo demonstra como abrir a fonte Type1 com métricas e substituir a fonte do texto da primeira página.

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)