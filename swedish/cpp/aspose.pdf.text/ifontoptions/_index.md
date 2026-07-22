---
title: "Aspose::Pdf::Text::IFontOptions-klass"
linktitle: "IFontOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::IFontOptions-klass. Användbara egenskaper för att finjustera Font-beteende i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.pdf.text/ifontoptions/
---
## IFontOptions class


Användbara egenskaper för att finjustera [Font](../font/) beteende.

```cpp
class IFontOptions : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_NotifyAboutFontEmbeddingError](./get_notifyaboutfontembeddingerror/)() | Ibland är det inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många orsaker, till exempel licensrestriktioner eller när det önskade teckensnittet inte hittades på mål‑datorn. När denna situation uppstår är den inte enkel att upptäcka, eftersom det önskade teckensnittet bäddas in via egendomsflaggan Font.IsEmbedded = true; Naturligtvis är det möjligt att läsa denna egenskap omedelbart efter att den satts, men det är inte ett bekvämt tillvägagångssätt. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall då försök att bädda in teckensnittet misslyckas. Om denna flagga är satt kommer ett undantag av typen [Aspose::Pdf::FontEmbeddingException](../../aspose.pdf/fontembeddingexception/) att kastas. Standardvärdet är false. |
| virtual [set_NotifyAboutFontEmbeddingError](./set_notifyaboutfontembeddingerror/)(bool) | Ibland är det inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många orsaker, till exempel licensrestriktioner eller när det önskade teckensnittet inte hittades på mål‑datorn. När denna situation uppstår är den inte enkel att upptäcka, eftersom det önskade teckensnittet bäddas in via egendomsflaggan Font.IsEmbedded = true; Naturligtvis är det möjligt att läsa denna egenskap omedelbart efter att den satts, men det är inte ett bekvämt tillvägagångssätt. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall då försök att bädda in teckensnittet misslyckas. Om denna flagga är satt kommer ett undantag av typen [Aspose::Pdf::FontEmbeddingException](../../aspose.pdf/fontembeddingexception/) att kastas. Standardvärdet är false. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
