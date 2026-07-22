---
title: "Aspose::Pdf::Document::set_EmbedStandardFonts metod"
linktitle: "set_EmbedStandardFonts"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::set_EmbedStandardFonts metod. Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑teckensnitt där flaggan IsEmbedded är satt till true. Alla PDF‑teckensnitt kan enkelt bäddas in i dokumentet genom att sätta flaggan IsEmbedded till true, men PDF‑standard‑Type1‑teckensnitt är ett undantag från denna regel. Inbäddning av standard‑Type1‑teckensnitt kräver mycket tid, så för att bädda in dessa teckensnitt är det nödvändigt inte bara att sätta flaggan IsEmbedded till true för det angivna teckensnittet utan också att sätta en ytterligare flagga på dokumentnivå – EmbedStandardFonts = true; Denna egenskap kan endast sättas en gång för alla teckensnitt. Standardvärdet är false i C++."
type: docs
weight: 9400
url: /sv/cpp/aspose.pdf/document/set_embedstandardfonts/
---
## Document::set_EmbedStandardFonts method


Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑teckensnitt som har flaggan IsEmbedded satt till true. Alla PDF‑teckensnitt kan enkelt bäddas in i dokumentet genom att sätta flaggan IsEmbedded till true, men PDF‑standard‑Type1‑teckensnitt är ett undantag från denna regel. Inbäddning av standard‑Type1‑teckensnitt kräver mycket tid, så för att bädda in dessa teckensnitt måste man inte bara sätta flaggan IsEmbedded till true för det specifika teckensnittet utan även sätta en ytterligare flagga på dokumentnivå – EmbedStandardFonts = true; Denna egenskap kan endast sättas en gång för alla teckensnitt. Som standard false.

```cpp
void Aspose::Pdf::Document::set_EmbedStandardFonts(bool value)
```

## Se även

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
