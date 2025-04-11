---
title: Document.EmbedStandardFonts
second_title: Aspose.PDF for .NET API Reference
description: Dokumentegenskap. Egenskap som deklarerar att dokumentet måste bädda in alla standard Type1-teckensnitt som har flaggan IsEmbedded inställd på true. Alla PDF-teckensnitt kan bäddas in i dokumentet helt enkelt genom att ställa in flaggan IsEmbedded på true, men PDF-standard Type1-teckensnitt är ett undantag från denna regel. Inbäddning av standard Type1-teckensnitt kräver mycket tid, så för att bädda in dessa teckensnitt är det nödvändigt att inte bara ställa in flaggan IsEmbedded på true för det angivna teckensnittet utan också ställa in en ytterligare flagga på dokumentnivå - EmbedStandardFonts = true; Denna egenskap kan endast ställas in en gång för alla teckensnitt. Som standard false.
type: docs
weight: 150
url: /sv/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts-egenskap

Egenskap som deklarerar att dokumentet måste bädda in alla standard Type1-teckensnitt som har flaggan IsEmbedded inställd på true. Alla PDF-teckensnitt kan bäddas in i dokumentet helt enkelt genom att ställa in flaggan IsEmbedded på true, men PDF-standard Type1-teckensnitt är ett undantag från denna regel. Inbäddning av standard Type1-teckensnitt kräver mycket tid, så för att bädda in dessa teckensnitt är det nödvändigt att inte bara ställa in flaggan IsEmbedded på true för det angivna teckensnittet utan också ställa in en ytterligare flagga på dokumentnivå - EmbedStandardFonts = true; Denna egenskap kan endast ställas in en gång för alla teckensnitt. Som standard false.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)