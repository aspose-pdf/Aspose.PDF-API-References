---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Método Artifact. Iniciar atualizações atrasadas. Use este recurso se precisar fazer várias alterações no mesmo artefato para melhorar o desempenho. Normalmente, os operadores de artefato são alterados sempre que a propriedade do artefato é alterada. Isso causa a alteração do conteúdo da página toda vez que o artefato é alterado. Para evitar esse efeito, coloque todas as atualizações do artefato entre as chamadas StartUpdates/SaveUpdates. Isso permite alterar o conteúdo da página apenas uma vez.
type: docs
weight: 230
url: /pt/net/aspose.pdf/artifact/beginupdates/
---
## Método Artifact.BeginUpdates

Iniciar atualizações atrasadas. Use este recurso se precisar fazer várias alterações no mesmo artefato para melhorar o desempenho. Normalmente, os operadores de artefato são alterados sempre que a propriedade do artefato é alterada. Isso causa a alteração do conteúdo da página toda vez que o artefato é alterado. Para evitar esse efeito, coloque todas as atualizações do artefato entre as chamadas StartUpdates/SaveUpdates. Isso permite alterar o conteúdo da página apenas uma vez.

```csharp
public void BeginUpdates()
```

## Exemplos

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Veja Também

* classe [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)