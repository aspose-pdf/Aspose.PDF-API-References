---
title: BeginUpdates
second_title: Aspose.PDF for .NET API Referansı
description: Ertelenen güncellemeleri başlatın. Performansı artırmak için aynı yapı üzerinde birkaç değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle yapıt işleçleri yapıt özelliği değiştirildiğinde herhangi bir zamanda değiştirilir. Bu yapıt değiştirildiğinde her zaman content sayfasının değişmesine neden olur. Bu etkiyi önlemek için tüm yapı güncellemelerini StartUpdates/SaveUpdates çağrıları arasına koyun. Bu sayfa içeriğinin yalnızca bir kez değiştirilmesine izin verir.
type: docs
weight: 230
url: /tr/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

Ertelenen güncellemeleri başlatın. Performansı artırmak için aynı yapı üzerinde birkaç değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle yapıt işleçleri, yapıt özelliği değiştirildiğinde herhangi bir zamanda değiştirilir. Bu, yapıt değiştirildiğinde her zaman content sayfasının değişmesine neden olur. Bu etkiyi önlemek için, tüm yapı güncellemelerini StartUpdates/SaveUpdates çağrıları arasına koyun. Bu, sayfa içeriğinin yalnızca bir kez değiştirilmesine izin verir.

```csharp
public void BeginUpdates()
```

### Örnekler

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Ayrıca bakınız

* class [Artifact](../../artifact)
* ad alanı [Aspose.Pdf](../../artifact)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
