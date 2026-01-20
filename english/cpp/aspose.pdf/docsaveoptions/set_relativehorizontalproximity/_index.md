---
title: Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity method
linktitle: set_RelativeHorizontalProximity
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity method. In Pdf words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It''s normed to font size - 1.0 means 100% of supposed word''s font size. ATTENTION!It''s used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document in C++.'
type: docs
weight: 2400
url: /cpp/aspose.pdf/docsaveoptions/set_relativehorizontalproximity/
---
## DocSaveOptions::set_RelativeHorizontalProximity method


In [Pdf](../../) words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document.

```cpp
void Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity(float value)
```

## See Also

* Class [DocSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
