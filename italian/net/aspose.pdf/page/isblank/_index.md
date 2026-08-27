---
title: "Page.IsBlank"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Page. Ottiene il flag che indica se la pagina è vuota o meno"
type: docs
weight: 490
url: /it/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

Ottiene l'indicatore se la pagina è vuota o meno.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillThresholdFactor | Double | Il valore di soglia di riempimento che gestisce la sensibilità del rilevamento. Deve essere nell'intervallo [0..1). |

### Valore di ritorno

True - se la pagina è vuota; altrimenti, false.

## Osservazioni

Per determinare se una pagina è vuota o meno, viene calcolato il rapporto tra lo spazio riempito e lo spazio totale della pagina. Questo rapporto viene confrontato con il parametro fillThresholdFactor e, se è inferiore, la pagina è considerata vuota.

### Vedi anche

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


