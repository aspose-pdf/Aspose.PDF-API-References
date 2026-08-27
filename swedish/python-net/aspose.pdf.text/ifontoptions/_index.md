---
title: "IFontOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Användbara egenskaper för att finjustera teckensnittsbeteende"
type: docs
weight: 180
url: /sv/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

Användbara egenskaper för att finjustera teckensnittsbeteende

Typen IFontOptions visar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| notify_about_font_embedding_error | Ibland är det inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många orsaker, till exempel<br/>            licensrestriktioner eller när det önskade teckensnittet inte hittades på mål‑datorn.<br/>            När denna situation uppstår är den inte enkel att upptäcka, eftersom det önskade teckensnittet bäddas in via att sätta <br/>            egendomsflaggan Font.IsEmbedded = true; Naturligtvis är det möjligt att läsa denna egenskap omedelbart efter att den satts men<br/>            det är inte ett bekvämt tillvägagångssätt. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism <br/>            för fall då försök att bädda in teckensnittet misslyckas. Om denna flagga är satt kastas ett undantag av typen<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) . Som standard falskt. |

### Se även

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

