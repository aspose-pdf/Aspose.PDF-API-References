---
title: "Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages method"
linktitle: "set_ExplicitListOfSavedPages"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages method. Con esta propiedad puede definir explícitamente qué páginas del documento deben convertirse. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre irán en el orden en que aparecen en el PDF de origen. Si esta lista es nula (como es por defecto), se convertirán todas las páginas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]), se lanzará una excepción en C++."
type: docs
weight: 3100
url: /es/cpp/aspose.pdf/htmlsaveoptions/set_explicitlistofsavedpages/
---
## HtmlSaveOptions::set_ExplicitListOfSavedPages method


Con esta propiedad puedes definir explícitamente qué páginas del documento deben convertirse. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre se mantendrá el orden en que aparecen en el PDF de origen. Si esta lista es nula (como es por defecto), se convertirán todas las páginas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]) se lanzará una excepción.

```cpp
void Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages(System::ArrayPtr<int32_t> value) override
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
