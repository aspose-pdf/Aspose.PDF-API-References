---
title: "FontRepository.FindFont"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FontRepository. Cerca e restituisce il font con il nome del font specificato"
type: docs
weight: 40
url: /it/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Cerca e restituisce il font con il nome del font specificato.

```csharp
public static Font FindFont(string fontName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Nome del font. |

### Valore di ritorno

Oggetto font.

## Esempi

L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Trova font
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, bool) {#findfont_3}

Cerca e restituisce il font con il nome del font specificato ignorando o rispettando la sensibilità al maiuscolo/minuscolo.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Nome del font. |
| ignoreCase | Boolean | sensibilità al caso |

### Valore di ritorno

Oggetto font.

## Esempi

L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Trova font
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, FontStyles) {#findfont_1}

Cerca e restituisce il font con il nome del font e lo stile del font specificati.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFamilyName | String | Nome della famiglia di font. |
| stl | FontStyles | Valore dello stile del font. |

### Valore di ritorno

Oggetto font corrispondente ai parametri della richiesta di ricerca.

## Esempi

L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Trova font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Modifica il font della prima occorrenza di testo
absorber.TextFragments[1].TextState.Font = font;

// Salva documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Cerca e restituisce il font con il nome del font e lo stile del font specificati ignorando o rispettando la sensibilità al maiuscolo/minuscolo.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFamilyName | String | Nome della famiglia di font. |
| stl | FontStyles | Valore dello stile del font. |
| ignoreCase | Boolean | sensibilità al caso |

### Valore di ritorno

Oggetto font corrispondente ai parametri della richiesta di ricerca.

## Esempi

L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Trova font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Modifica il font della prima occorrenza di testo
absorber.TextFragments[1].TextState.Font = font;

// Salva documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


