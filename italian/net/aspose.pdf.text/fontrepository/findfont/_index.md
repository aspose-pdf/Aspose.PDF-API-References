---
title: FindFont
second_title: Aspose.PDF per .NET API Reference
description: Cerca e restituisce il font con il nome del font specificato.
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
| fontName | String | Nome del carattere. |

### Valore di ritorno

Oggetto carattere.

### Esempi

L'esempio mostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Trova carattere
Font font = FontRepository.FindFont("Arial");

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova carattere
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Apri documento
doc.Pages[1].Accept(absorber);

// Trova carattere
absorber.TextFragments[1].TextState.Font = font;

// Apri documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Guarda anche

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* spazio dei nomi [Aspose.Pdf.Text](../../fontrepository)
* assemblea [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Cerca e restituisce il font con il nome del font specificato ignorando o rispettando la distinzione tra maiuscole e minuscole.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Nome del carattere. |
| ignoreCase | Boolean | sensibilità alle maiuscole |

### Valore di ritorno

Oggetto carattere.

### Esempi

L'esempio mostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Trova carattere
Font font = FontRepository.FindFont("Arial");

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova carattere
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Apri documento
doc.Pages[1].Accept(absorber);

// Trova carattere
absorber.TextFragments[1].TextState.Font = font;

// Apri documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Guarda anche

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* spazio dei nomi [Aspose.Pdf.Text](../../fontrepository)
* assemblea [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Cerca e restituisce il carattere con il nome del carattere e lo stile del carattere specificati.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFamilyName | String | Nome della famiglia del carattere. |
| stl | FontStyles | Valore dello stile del carattere. |

### Valore di ritorno

Oggetto font corrispondente ai parametri della richiesta di ricerca.

### Esempi

L'esempio mostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Modifica il carattere della prima occorrenza del testo
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Modifica il carattere della prima occorrenza del testo
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Apri documento
doc.Pages[1].Accept(absorber);

// Trova carattere
absorber.TextFragments[1].TextState.Font = font;

// Apri documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Guarda anche

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* spazio dei nomi [Aspose.Pdf.Text](../../fontrepository)
* assemblea [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Cerca e restituisce il carattere con il nome del carattere e lo stile del carattere specificati ignorando o rispettando la distinzione tra maiuscole e minuscole.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFamilyName | String | Nome della famiglia del carattere. |
| stl | FontStyles | Valore dello stile del carattere. |
| ignoreCase | Boolean | sensibilità alle maiuscole |

### Valore di ritorno

Oggetto font corrispondente ai parametri della richiesta di ricerca.

### Esempi

L'esempio mostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Trova carattere
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova carattere
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Apri documento
doc.Pages[1].Accept(absorber);

// Trova carattere
absorber.TextFragments[1].TextState.Font = font;

// Apri documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Guarda anche

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* spazio dei nomi [Aspose.Pdf.Text](../../fontrepository)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
