---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.ExplicitDestinationType enum. Enumerates the types of explicit destinations
type: docs
weight: 1690
url: /it/net/aspose.pdf.annotations/explicitdestinationtype/
---
## Enumerazione ExplicitDestinationType

Enumera i tipi di destinazioni esplicite.

```csharp
public enum ExplicitDestinationType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| XYZ | `0` | Visualizza la pagina con le coordinate (sinistra, sopra) posizionate nell'angolo in alto a sinistra della finestra e i contenuti della pagina ingranditi dal fattore di zoom. Un valore nullo per uno qualsiasi dei parametri sinistra, sopra o zoom specifica che il valore attuale di quel parametro deve rimanere invariato. Un valore di zoom di 0 ha lo stesso significato di un valore nullo. |
| Fit | `1` | Visualizza la pagina con i suoi contenuti ingranditi appena sufficientemente per adattare l'intera pagina all'interno della finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando la pagina all'interno della finestra nell'altra dimensione. |
| FitH | `2` | Visualizza la pagina con la coordinata verticale sopra posizionata al bordo superiore della finestra e i contenuti della pagina ingranditi appena sufficientemente per adattare l'intera larghezza della pagina all'interno della finestra. Un valore nullo per sopra specifica che il valore attuale di quel parametro deve rimanere invariato. |
| FitV | `3` | Visualizza la pagina con la coordinata orizzontale sinistra posizionata al bordo sinistro della finestra e i contenuti della pagina ingranditi appena sufficientemente per adattare l'intera altezza della pagina all'interno della finestra. Un valore nullo per sinistra specifica che il valore attuale di quel parametro deve rimanere invariato. |
| FitR | `4` | Visualizza la pagina con i suoi contenuti ingranditi appena sufficientemente per adattare il rettangolo specificato dalle coordinate sinistra, in basso, destra e sopra interamente all'interno della finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo all'interno della finestra nell'altra dimensione. Un valore nullo per uno qualsiasi dei parametri può comportare un comportamento imprevedibile. |
| FitB | `5` | Visualizza la pagina con i suoi contenuti ingranditi appena sufficientemente per adattare completamente la sua bounding box all'interno della finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando la bounding box all'interno della finestra nell'altra dimensione. |
| FitBH | `6` | Visualizza la pagina con la coordinata verticale sopra posizionata al bordo superiore della finestra e i contenuti della pagina ingranditi appena sufficientemente per adattare l'intera larghezza della sua bounding box all'interno della finestra. Un valore nullo per sopra specifica che il valore attuale di quel parametro deve rimanere invariato. |
| FitBV | `7` | Visualizza la pagina con la coordinata orizzontale sinistra posizionata al bordo sinistro della finestra e i contenuti della pagina ingranditi appena sufficientemente per adattare l'intera altezza della sua bounding box all'interno della finestra. Un valore nullo per sinistra specifica che il valore attuale di quel parametro deve rimanere invariato. |

### Vedi Anche

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)