---
title: "Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages method"
linktitle: "get_ExplicitListOfSavedPages"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages method. Con esta propiedad puede definir explícitamente qué páginas del documento deben convertirse. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre se mantendrá el orden en que aparecen en el PDF original. Si esta lista es nula (como es por defecto), se convertirán todas las páginas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]) se lanzará una excepción en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf/htmlsaveoptions/get_explicitlistofsavedpages/
---
## HtmlSaveOptions::get_ExplicitListOfSavedPages method


Con esta propiedad puedes definir explícitamente qué páginas del documento deben convertirse. Las páginas en esta lista deben tener números basados en 1. Es decir, los números válidos de páginas deben tomarse del rango (1...[NumberOfPagesInConvertedDocument]). El orden de aparición de las páginas en esta lista no afecta su orden en la(s) página(s) HTML resultante(s); en las páginas resultantes siempre se mantendrá el orden en que aparecen en el PDF de origen. Si esta lista es nula (como es por defecto), se convertirán todas las páginas. Si algún número de página de esta lista está fuera del rango de páginas presentes (1-[amountOfPagesInDocument]) se lanzará una excepción.

```cpp
System::ArrayPtr<int32_t> Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages() override
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
