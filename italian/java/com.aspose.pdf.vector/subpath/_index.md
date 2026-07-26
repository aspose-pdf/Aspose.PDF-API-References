---
title: "SubPath"
linktitle: "SubPath"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un oggetto di grafica vettoriale nella pagina. Fondamentalmente, gli oggetti di grafica vettoriale sono rappresentati da due gruppi di SubPath. Uno di essi è rappresentato da un insieme di linee e."
type: docs
weight: 60
url: /it/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Rappresenta un oggetto grafico vettoriale nella pagina. Fondamentalmente, gli oggetti grafici vettoriali sono rappresentati da due gruppi di SubPath. Uno di essi è rappresentato da un insieme di linee e curve. Gli altri sono presentati come rettangoli e a volte possono creare confusione. Di solito è un'area rettangolare che ha un colore, ma molto spesso questo rettangolo è posizionato all'inizio della pagina e definisce l'intero spazio della pagina in bianco. Quindi ottieni il SubPath, ma visivamente vedi solo il testo nella pagina.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRectangle](#getRectangle--) | Restituisce il rettangolo di delimitazione del GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Restituisce il rettangolo di delimitazione del GraphicElement.

**Returns:**
Istanza Rectangle
