---
title: "com.aspose.pdf.vector"
linktitle: "com.aspose.pdf.vector"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il namespace radice Aspose.Pdf.Vector è un namespace di base per le operazioni grafiche."
type: docs
weight: 390
url: /it/java/com.aspose.pdf.vector/
---
Il namespace radice Aspose.Pdf.Vector è un namespace di base per le operazioni grafiche.

## Classi

| Classe | Descrizione |
| --- | --- |
| [GraphicElement](./graphicelement/) | Rappresenta la classe base per l'oggetto grafico nella pagina. |
| [GraphicElementCollection](./graphicelementcollection/) | Rappresenta la collezione {@link GraphicElement}. |
| [GraphicsAbsorber](./graphicsabsorber/) | Rappresenta un oggetto assorbitore di elementi grafici. Esegue la ricerca grafica e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}). |
| [GraphicState](./graphicstate/) | Rappresenta lo stato grafico dell'attuale {@link GraphicElement}. |
| [InternalHelper](./internalhelper/) |  |
| [SubPath](./subpath/) | Rappresenta un oggetto grafico vettoriale nella pagina. Fondamentalmente, gli oggetti grafici vettoriali sono rappresentati da due gruppi di SubPath. Uno di essi è rappresentato da un insieme di linee e curve. Gli altri sono presentati come rettangoli e a volte possono creare confusione. Di solito è un'area rettangolare che ha un colore, ma molto spesso questo rettangolo è posizionato all'inizio della pagina e definisce l'intero spazio della pagina in bianco. Quindi ottieni il SubPath, ma visivamente vedi solo il testo nella pagina. |
| [XFormPlacement](./xformplacement/) | Rappresenta il posizionamento di XForm. Se XForm viene visualizzato nella pagina più di una volta, tutti gli XformPlacements associati a questo XForm avranno elementi grafici comuni, ma stati grafici diversi. |
