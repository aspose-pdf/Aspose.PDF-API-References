---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sayfa yapısı nesneleri gibi bölümler ve paragraflar için bir emici nesneyi temsil eder.<br/>            Metin bölümleri ve paragrafları arar ve metin koordinat uzayında tanımlayan dikdörtgenler ve çokgenlere erişim sağlar. <br/>            Ayrıca metin segmentleri araması yapar ve yapı öğeleriyle gruplanmış TextFragments koleksiyonları aracılığıyla arama sonuçlarına erişim sağlar."
type: docs
weight: 240
url: /tr/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Sayfa yapısı nesneleri gibi bölümler ve paragraflar için bir emici nesneyi temsil eder.<br/>            Metin bölümleri ve paragrafları arar ve metin koordinat uzayında tanımlayan dikdörtgenler ve çokgenlere erişim sağlar. <br/>            Ayrıca metin segmentleri araması yapar ve yapı öğeleriyle gruplanmış TextFragments koleksiyonları aracılığıyla arama sonuçlarına erişim sağlar.

ParagraphAbsorber türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| ParagraphAbsorber() | Belge ya da sayfanın bölümlerini/paragraflarını arayan [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) sınıfının yeni bir örneğini başlatır. |
| ParagraphAbsorber(sections_search_depth) | ParagraphAbsorber sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| page_markups | [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) tarafından emilen koleksiyonu alır. |
| sections_search_depth | Yapısal daha ince öğeler için kaç kez ardışık arama yapılacağını belirten değeri alır veya ayarlar.<br/>            Varsayılan arama derinliği 3'tür.<br/>            Bu, yatay olarak bölünmüş bölümler (başlıklar, paragraflar vb.) için üç arama ve dikey olarak bölünmüş bölümler (sütunlar) için üç arama anlamına gelir. |
| is_multicolumn_paragraphs_allowed | Bir sonraki bölümün başlangıç metin satırlarının önceki bölümün son paragrafının devamı olarak kabul edilip edilmeyeceğini gösteren değeri alır veya ayarlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| visit(doc) | Belirtilen [Document](/pdf/python-net/aspose.pdf/document/) üzerinde bölümler ve paragraflar için arama yapar. |
| visit(page) | Belirtilen [Page](/pdf/python-net/aspose.pdf/page/) üzerinde arama yapar. |

### Ayrıca Bakınız

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

