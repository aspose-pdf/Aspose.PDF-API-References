---
title: "DocSaveOptions.RelativeHorizontalProximity"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "DocSaveOptions proprietà. In PDF le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Quindi, per rilevare le parole a volte è necessario individuare gruppi di caratteri indipendenti che in realtà sono parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che deve essere considerata come distanza tra parole durante il riconoscimento delle parole nel PDF di origine. La presenza di uno spazio vuoto di almeno questa larghezza tra le lettere indica che gli elementi testuali appartengono a parole diverse. È normalizzata alla dimensione del carattere 1,0, che corrisponde al 100 % della dimensione del carattere delle parole presunte. ATTENZIONE: è usata solo nei casi in cui il PDF di origine contiene caratteri specifici raramente usati per i quali il valore ottimale non può essere calcolato dal carattere. Pertanto, nella stragrande maggioranza dei casi questo parametro non modifica il documento risultante."
type: docs
weight: 120
url: /it/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity property

In Pdf le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Quindi, per rilevare le parole a volte è necessario individuare gruppi di caratteri indipendenti che in realtà sono parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che deve essere trattata come distanza tra parole durante il riconoscimento delle parole nel PDF di origine. (la presenza di uno spazio vuoto almeno di questa larghezza tra le lettere indica che gli elementi testuali appartengono a parole diverse). È normalizzata alla dimensione del carattere – 1,0 significa il 100 % della dimensione del carattere della parola presunta. ATTENTION!Viene utilizzata solo nei casi in cui il PDF di origine contiene font specifici raramente usati per i quali il valore ottimale non può essere calcolato dal font. Pertanto, nella stragrande maggioranza dei casi questo parametro non cambia nulla nel documento risultante.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### Vedi anche

* class [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


