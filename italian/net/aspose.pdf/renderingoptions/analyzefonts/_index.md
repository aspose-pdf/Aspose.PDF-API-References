---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: Proprietà RenderingOptions. Sostituisce i caratteri secondo necessità per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei caratteri segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, controlla se il carattere specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun carattere definito dall'utente, cerca tra i caratteri aggiunti tramite FontRepository.Sources. 3. Analizza il testo per identificare il suo alfabeto o script e suggerire nomi di caratteri di conseguenza. Tenta di localizzare e utilizzare questi caratteri dal sistema. 4. Come fallback, cerca nel sistema qualsiasi carattere in grado di visualizzare i caratteri richiesti.
type: docs
weight: 20
url: /it/net/aspose.pdf/renderingoptions/analyzefonts/
---
## Proprietà RenderingOptions.AnalyzeFonts

Sostituisce i caratteri secondo necessità per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei caratteri segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, controlla se il carattere specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun carattere definito dall'utente, cerca tra i caratteri aggiunti tramite la !:FontRepository.Sources. 3. Analizza il testo per identificare il suo alfabeto o script e suggerire nomi di caratteri di conseguenza. Tenta di localizzare e utilizzare questi caratteri dal sistema. 4. Come fallback, cerca nel sistema qualsiasi carattere in grado di visualizzare i caratteri richiesti.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Vedi Anche

* classe [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)