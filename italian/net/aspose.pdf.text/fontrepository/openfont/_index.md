---
title: "FontRepository.OpenFont"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FontRepository. Apre il font con lo stream di font specificato"
type: docs
weight: 60
url: /it/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Apre il font con lo stream del font specificato.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontStream | Stream | Stream del font. |
| fontType | FontTypes | Valore del tipo di carattere. |

### Valore di ritorno

Oggetto font.

## Esempi

L'esempio dimostra come aprire il font e sostituire il font del testo della prima pagina.

```csharp
// Apri font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

    // Apri documento
    Document doc = new Document(@"D:\Tests\input.pdf");

    // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

    // Accetta l'assorbitore per la prima pagina
    doc.Pages[1].Accept(absorber);

    // Cambia il font della prima occorrenza di testo
    absorber.TextFragments[1].TextState.Font = font;

    // Salva documento
    doc.Save(@"D:\Tests\output.pdf"); 
}
```

### Vedi anche

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Apre il font con il percorso del file font specificato.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFilePath | String | Percorso del file del font. |

### Valore di ritorno

Oggetto font.

## Esempi

L'esempio dimostra come aprire il font e sostituire il font del testo della prima pagina.

```csharp
// Apri font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Cambia il font della prima occorrenza di testo
absorber.TextFragments[1].TextState.Font = font;

// Salva documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Apre il font con il percorso del file font specificato e il percorso del file metriche.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFilePath | String | Percorso del file del font. |
| metricsFilePath | String | Percorso del file delle metriche del font. |

### Valore di ritorno

Oggetto font.

## Esempi

L'esempio dimostra come aprire un font Type1 con metriche e sostituire il font del testo della prima pagina.

```csharp
// Apri font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Cambia il font della prima occorrenza di testo
absorber.TextFragments[1].TextState.Font = font;

// Salva documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


