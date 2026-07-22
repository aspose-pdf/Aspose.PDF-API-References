---
title: "Aspose::Pdf::Document::get_EmbedStandardFonts‑metod"
linktitle: "get_EmbedStandardFonts"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::get_EmbedStandardFonts‑metod. Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt som har flaggan IsEmbedded satt till true. Alla PDF‑typsnitt kan enkelt bäddas in i dokumentet genom att sätta flaggan IsEmbedded till true, men PDF‑standard‑Type1‑typsnitt är ett undantag från denna regel. Inbäddning av standard‑Type1‑typsnitt kräver mycket tid, så för att bädda in dessa typsnitt är det nödvändigt inte bara att sätta flaggan IsEmbedded till true för det angivna typsnittet utan också att sätta ett ytterligare flagga på dokumentnivå – EmbedStandardFonts = true; Denna egenskap kan endast sättas en gång för alla typsnitt. Standardvärdet är false i C++."
type: docs
weight: 2700
url: /sv/cpp/aspose.pdf/document/get_embedstandardfonts/
---
## Document::get_EmbedStandardFonts method


Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑teckensnitt som har flaggan IsEmbedded satt till true. Alla PDF‑teckensnitt kan enkelt bäddas in i dokumentet genom att sätta flaggan IsEmbedded till true, men PDF‑standard‑Type1‑teckensnitt är ett undantag från denna regel. Inbäddning av standard‑Type1‑teckensnitt kräver mycket tid, så för att bädda in dessa teckensnitt måste man inte bara sätta flaggan IsEmbedded till true för det specifika teckensnittet utan även sätta en ytterligare flagga på dokumentnivå – EmbedStandardFonts = true; Denna egenskap kan endast sättas en gång för alla teckensnitt. Som standard false.

```cpp
bool Aspose::Pdf::Document::get_EmbedStandardFonts() const
```

## Se även

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
