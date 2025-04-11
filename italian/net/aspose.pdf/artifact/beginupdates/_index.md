---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Metodo Artifact. Inizia aggiornamenti ritardati. Usa questa funzione se hai bisogno di apportare diverse modifiche allo stesso artefatto per migliorare le prestazioni. Di solito, gli operatori dell'artefatto vengono cambiati ogni volta che la proprietà dell'artefatto viene modificata. Questo causa la modifica dei contenuti della pagina ogni volta che l'artefatto viene cambiato. Per evitare questo effetto, metti tutti gli aggiornamenti dell'artefatto tra le chiamate StartUpdates/SaveUpdates. Questo consente di modificare i contenuti della pagina solo una volta.
type: docs
weight: 230
url: /it/net/aspose.pdf/artifact/beginupdates/
---
## Metodo Artifact.BeginUpdates

Inizia aggiornamenti ritardati. Usa questa funzione se hai bisogno di apportare diverse modifiche allo stesso artefatto per migliorare le prestazioni. Di solito, gli operatori dell'artefatto vengono cambiati ogni volta che la proprietà dell'artefatto viene modificata. Questo causa la modifica dei contenuti della pagina ogni volta che l'artefatto viene cambiato. Per evitare questo effetto, metti tutti gli aggiornamenti dell'artefatto tra le chiamate StartUpdates/SaveUpdates. Questo consente di modificare i contenuti della pagina solo una volta.

```csharp
public void BeginUpdates()
```

## Esempi

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Vedi Anche

* classe [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)