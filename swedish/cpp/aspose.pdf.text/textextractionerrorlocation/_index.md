---
title: "Aspose::Pdf::Text::TextExtractionErrorLocation-klass"
linktitle: "TextExtractionErrorLocation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextExtractionErrorLocation-klass. Representerar platsen i PDF-dokumentet där ett textutvinningsfel har uppstått i C++."
type: docs
weight: 4000
url: /sv/cpp/aspose.pdf.text/textextractionerrorlocation/
---
## TextExtractionErrorLocation class


Representerar platsen i PDF-dokumentet där textutvinningsfelet har uppstått.

```cpp
class TextExtractionErrorLocation : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_FontUsedKey](./get_fontusedkey/)() const | Nyckel (namn) för PDF‑[Font](../font/)-objektet som används för att visa operatorn som orsakar textutvinningsfelet. |
| [get_FormKey](./get_formkey/)() const | Nyckel (namn) för PDF Form XObject där textutvinningsfelet i innehållsströmmen har placerats. Är inte tom om ObjectType == 'xForm'. |
| [get_ObjectType](./get_objecttype/)() const | Typ av PDF‑objekt ([Page](../../aspose.pdf/page/) eller xForm) där textutvinningsfelet i innehållsströmmen har placerats. |
| [get_OperatorIndex](./get_operatorindex/)() const | Index för textvisningsoperatorn i innehållsströmmen (operator‑samling) som orsakar textutvinningsfelet. |
| [get_OperatorString](./get_operatorstring/)() const | [Text](../)‑visningsoperator som orsakar textutvinningsfelet. |
| [get_PageNumber](./get_pagenumber/)() const | Nummer på dokumentsidan där textutvinningsfelet har placerats. |
| [get_Path](./get_path/)() const | Plats för PDF-dokumentet där fel vid textutdragning har uppstått. |
| [get_TextStartPoint](./get_textstartpoint/)() const | Nyckel (namn) för PDF‑[Font](../font/)-objektet som används för att visa operatorn som orsakar textutvinningsfelet. |
| [ToString](./tostring/)() const override | Returnerar strängrepresentation. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
