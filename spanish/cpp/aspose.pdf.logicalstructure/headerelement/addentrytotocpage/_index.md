---
title: "Método Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage"
linktitle: "AddEntryToTocPage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage. Crea un encabezado en la página de Tabla de Contenidos (TOC) especificada y lo asocia con un elemento TOCI en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.logicalstructure/headerelement/addentrytotocpage/
---
## HeaderElement::AddEntryToTocPage(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<ListLIElement\>\&) method


Crea un encabezado en la [Tabla](../../../aspose.pdf/table/) de Contenidos (TOC) especificada y lo asocia con un elemento TOCI.

```cpp
void Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage(const System::SharedPtr<Aspose::Pdf::Page> &tocPage, const System::SharedPtr<ListLIElement> &tocEntry)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tocPage | const System::SharedPtr\<Aspose::Pdf::Page\>\& | El objeto [Página](../../../aspose.pdf/page/) que representa la página TOC donde se debe crear el encabezado. |
| tocEntry | const System::SharedPtr\<ListLIElement\>\& | El objeto [ListLIElement](../../listlielement/) que actúa como la entrada TOCI para asociarlo con el encabezado creado en la página TOC especificada. |
## Observaciones



Esta sobrecarga aborda escenarios que involucran estructuras anidadas de [Table](../../../aspose.pdf/table/) de Contenidos (TOC), según lo especificado en los estándares PDF/UA y PDF 1.7, donde un elemento **TOCI** no puede ser hijo de otro **TOCI** o donde un **TOC** no puede anidarse directamente bajo un **TOCI**. Para mantener el cumplimiento de estos requisitos estructurales, las entradas TOC anidadas deben representarse mediante elementos **List** y **[ListLIElement](../../listlielement/)**. Este método facilita la asociación del elemento de encabezado con dicho [ListLIElement](../../listlielement/) en la página TOC designada, garantizando una estructuración lógica adecuada y mejorando las capacidades de navegación en documentos PDF etiquetados.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [ListLIElement](../../listlielement/)
* Class [HeaderElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
## HeaderElement::AddEntryToTocPage(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<TOCIElement\>\&) method


Crea un encabezado en la [Tabla](../../../aspose.pdf/table/) de Contenidos (TOC) especificada y lo asocia con un elemento TOCI.

```cpp
void Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage(const System::SharedPtr<Aspose::Pdf::Page> &tocPage, const System::SharedPtr<TOCIElement> &tocEntry)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tocPage | const System::SharedPtr\<Aspose::Pdf::Page\>\& | El objeto [Página](../../../aspose.pdf/page/) que representa la página TOC donde se debe crear el encabezado. |
| tocEntry | const System::SharedPtr\<TOCIElement\>\& | El [TOCIElement](../../tocielement/) que sirve como la entrada TOC para asociarlo con el encabezado que se está creando. |
## Observaciones



Este método garantiza que el encabezado esté correctamente vinculado a una página TOC y a un elemento TOCI, manteniendo la jerarquía lógica del documento y apoyando la navegación en estructuras PDF etiquetadas.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [TOCIElement](../../tocielement/)
* Class [HeaderElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
