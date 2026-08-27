---
title: "RenderingOptions.AnalyzeFonts"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà RenderingOptions. Sostituisce i font secondo necessità per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei font segue questi passaggi 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, verifica se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cerca tra i font aggiunti tramite FontRepository.Sources. 3. Analizza il testo per identificare il suo alfabeto o script e suggerisce i nomi dei font di conseguenza. Tenta di individuare e utilizzare questi font dal sistema. 4. Come fallback, cerca nel sistema un qualsiasi font in grado di visualizzare i caratteri richiesti."
type: docs
weight: 20
url: /it/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts property

Sostituisce i caratteri tipografici secondo necessità per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei font segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, verifica se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cerca tra i font aggiunti tramite !:FontRepository.Sources. 3. Analizza il testo per identificare il suo alfabeto o script e suggerisce i nomi dei font di conseguenza. Tenta di individuare e utilizzare questi font dal sistema. 4. Come soluzione di ripiego, cerca nel sistema un qualsiasi font in grado di visualizzare i caratteri richiesti.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Vedi anche

* class [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


