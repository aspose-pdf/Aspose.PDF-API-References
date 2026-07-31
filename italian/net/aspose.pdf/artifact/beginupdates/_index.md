---
title: "Artifact.BeginUpdates"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Artifact. Avvia aggiornamenti ritardati. Usa questa funzionalità se devi apportare diverse modifiche allo stesso artifact per migliorare le prestazioni. Di solito gli operatori dell'artifact vengono modificati ogni volta che la proprietà dell'artifact è cambiata. Ciò provoca la modifica del contenuto della pagina ogni volta che l'artifact è cambiato. Per evitare questo effetto, inserisci tutti gli aggiornamenti dell'artifact tra le chiamate StartUpdates/SaveUpdates. Questo consente di modificare il contenuto della pagina una sola volta."
type: docs
weight: 230
url: /it/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

Avvia gli aggiornamenti differiti. Usa questa funzionalità se devi apportare diverse modifiche allo stesso artefatto per migliorare le prestazioni. Di solito gli operatori dell'artefatto vengono modificati ogni volta che una proprietà dell'artefatto è cambiata. Ciò provoca la modifica del contenuto della pagina ogni volta che l'artefatto è cambiato. Per evitare questo effetto, inserisci tutti gli aggiornamenti dell'artefatto tra le chiamate StartUpdates/SaveUpdates. Questo consente di modificare il contenuto della pagina una sola volta.

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

### Vedi anche

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


