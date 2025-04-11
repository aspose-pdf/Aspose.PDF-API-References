---
title: DocSaveOptions.RelativeHorizontalProximity
second_title: Aspose.PDF for .NET API Reference
description: Proprietà DocSaveOptions. In Pdf le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Quindi, per rilevare le parole a volte dobbiamo rilevare gruppi di caratteri indipendenti che sono in realtà parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che devono essere trattati come distanza tra le parole durante il riconoscimento delle parole nel PDF sorgente. La presenza di uno spazio vuoto di almeno questa larghezza tra le lettere significa che gli elementi testuali appartengono a parole diverse. È normalizzato alla dimensione del carattere - 1.0 significa 100% della dimensione del carattere delle parole supposte. ATTENZIONE! È usato solo nei casi in cui il PDF sorgente contiene caratteri specifici raramente usati per i quali il valore ottimale non può essere calcolato dal carattere. Quindi, nella stragrande maggioranza dei casi, questo parametro non cambia nulla nel documento risultante.
type: docs
weight: 120
url: /it/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## Proprietà DocSaveOptions.RelativeHorizontalProximity

In Pdf le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Quindi, per rilevare le parole a volte dobbiamo rilevare gruppi di caratteri indipendenti che sono in realtà parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che devono essere trattati come distanza tra le parole durante il riconoscimento delle parole nel PDF sorgente. (La presenza di uno spazio vuoto di almeno questa larghezza tra le lettere significa che gli elementi testuali appartengono a parole diverse). È normalizzato alla dimensione del carattere - 1.0 significa 100% della dimensione del carattere delle parole supposte. ATTENZIONE! È usato solo nei casi in cui il PDF sorgente contiene caratteri specifici raramente usati per i quali il valore ottimale non può essere calcolato dal carattere. Quindi, nella stragrande maggioranza dei casi, questo parametro non cambia nulla nel documento risultante.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### Vedi Anche

* classe [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)