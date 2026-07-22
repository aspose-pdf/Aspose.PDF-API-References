---
title: "Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError-metod"
linktitle: "set_NotifyAboutFontEmbeddingError"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError-metod. Ibland är det inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många orsaker, till exempel licensrestriktioner eller när det önskade teckensnittet inte hittades på mål-datorn. När denna situation uppstår är den inte enkel att upptäcka, eftersom det önskade teckensnittet bäddas in via egendomsflaggan Font.IsEmbedded = true; Naturligtvis är det möjligt att läsa denna egenskap omedelbart efter att den satts, men det är inte ett bekvämt tillvägagångssätt. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall då ett försök att bädda in teckensnittet misslyckas. Om denna flagga är satt kastas ett undantag av typen Aspose::Pdf::FontEmbeddingException. Standardvärdet är falskt i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.text/ifontoptions/set_notifyaboutfontembeddingerror/
---
## IFontOptions::set_NotifyAboutFontEmbeddingError method


Ibland är det inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många orsaker, till exempel licensrestriktioner eller när det önskade teckensnittet inte hittades på mål-datorn. När denna situation uppstår är den inte enkel att upptäcka, eftersom det önskade teckensnittet bäddas in via egendomsflaggan Font.IsEmbedded = true; Naturligtvis är det möjligt att läsa denna egenskap omedelbart efter att den satts, men det är inte ett bekvämt tillvägagångssätt. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall då ett försök att bädda in teckensnittet misslyckas. Om denna flagga är satt kastas ett undantag av typen [Aspose::Pdf::FontEmbeddingException](../../../aspose.pdf/fontembeddingexception/). Standardvärdet är falskt.

```cpp
virtual void Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError(bool value)=0
```

## Se även

* Class [IFontOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
