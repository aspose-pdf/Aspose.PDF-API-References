---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Artifact metodu. Gecikmeli güncellemeleri başlatın. Performansı artırmak için aynı artefakta birden fazla değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle artefakt operatörleri, artefakt özelliği değiştiğinde her zaman değiştirilir. Bu, artefakt değiştiğinde sayfa içeriğinin her seferinde değişmesine neden olur. Bu etkiyi önlemek için tüm artefakt güncellemelerini StartUpdates/SaveUpdates çağrıları arasında yerleştirin. Bu, sayfa içeriğini yalnızca bir kez değiştirmeye olanak tanır.
type: docs
weight: 230
url: /tr/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates metodu

Gecikmeli güncellemeleri başlatın. Performansı artırmak için aynı artefakta birden fazla değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle artefakt operatörleri, artefakt özelliği değiştiğinde her zaman değiştirilir. Bu, artefakt değiştiğinde sayfa içeriğinin her seferinde değişmesine neden olur. Bu etkiyi önlemek için tüm artefakt güncellemelerini StartUpdates/SaveUpdates çağrıları arasında yerleştirin. Bu, sayfa içeriğini yalnızca bir kez değiştirmeye olanak tanır.

```csharp
public void BeginUpdates()
```

## Örnekler

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Ayrıca Bakınız

* sınıf [Artifact](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)