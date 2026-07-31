---
title: "Enumerazione ExplicitDestinationType"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Annotations.ExplicitDestinationType enumerazione. Elenca i tipi di destinazioni esplicite."
type: docs
weight: 1780
url: /it/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enumeration

Enumera i tipi di destinazioni esplicite.

```csharp
public enum ExplicitDestinationType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| XYZ | `0` | Visualizza la pagina con le coordinate (left, top) posizionate nell'angolo superiore sinistro della finestra e il contenuto della pagina ingrandito del fattore zoom. Un valore null per uno qualsiasi dei parametri left, top o zoom indica che il valore corrente di quel parametro deve rimanere invariato. Un valore di zoom pari a 0 ha lo stesso significato di un valore null. |
| Fit | `1` | Visualizza la pagina con il suo contenuto ingrandito appena a sufficienza per far entrare l'intera pagina nella finestra sia in orizzontale che in verticale. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando la pagina nella finestra nell'altra dimensione. |
| FitH | `2` | Visualizza la pagina con la coordinata verticale top posizionata sul bordo superiore della finestra e il contenuto della pagina ingrandito appena a sufficienza per far entrare l'intera larghezza della pagina nella finestra. Un valore null per top indica che il valore corrente di quel parametro deve rimanere invariato. |
| FitV | `3` | Visualizza la pagina con la coordinata orizzontale left posizionata sul bordo sinistro della finestra e il contenuto della pagina ingrandito appena a sufficienza per far entrare l'intera altezza della pagina nella finestra. Un valore null per left indica che il valore corrente di quel parametro deve rimanere invariato. |
| FitR | `4` | Visualizza la pagina con il suo contenuto ingrandito appena a sufficienza per far entrare il rettangolo specificato dalle coordinate left, bottom, right e topentirely interamente nella finestra sia in orizzontale che in verticale. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo nella finestra nell'altra dimensione. Un valore null per uno qualsiasi dei parametri può provocare un comportamento imprevedibile. |
| FitB | `5` | Visualizza la pagina con il suo contenuto ingrandito appena a sufficienza per far entrare il suo riquadro di delimitazione interamente nella finestra sia in orizzontale che in verticale. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il riquadro di delimitazione nella finestra nell'altra dimensione. |
| FitBH | `6` | Visualizza la pagina con la coordinata verticale top posizionata sul bordo superiore della finestra e il contenuto della pagina ingrandito appena a sufficienza per far entrare l'intera larghezza del suo riquadro di delimitazione nella finestra. Un valore null per top indica che il valore corrente di quel parametro deve rimanere invariato. |
| FitBV | `7` | Visualizza la pagina con la coordinata orizzontale left posizionata sul bordo sinistro della finestra e il contenuto della pagina ingrandito appena a sufficienza per far entrare l'intera altezza del suo riquadro di delimitazione nella finestra. Un valore null per left indica che il valore corrente di quel parametro deve rimanere invariato. |

### Vedi anche

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


