---
title: "Clase Aspose::Pdf::Text::AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::AbsorbedCell. Representa una celda de tabla que existe en la página en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.text/absorbedcell/
---
## AbsorbedCell class


Representa una celda de tabla que existe en la página.

```cpp
class AbsorbedCell : public Aspose::Pdf::Text::ITableElement,
                     public System::IComparable<System::SharedPtr<AbsorbedCell>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<AbsorbedCell\>) override | Compara el objeto [AbsorbedCell](./) actual con otro objeto [AbsorbedCell](./) y devuelve un entero que indica si el objeto actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [get_BorderInfo](./get_borderinfo/)() const | Devuelve la información de borde de la celda cuando la propiedad FlowEngine.TableAbsorber.UseFlowEngine está establecida en true. |
| [get_ColSpan](./get_colspan/)() const | Devuelve el número de columnas que la celda debe abarcar cuando la propiedad TableAbsorber.UseFlowEngine está establecida en true. |
| [get_Rectangle](./get_rectangle/)() override | Obtiene el rectángulo que describe la posición de la celda en la página. |
| [get_TextFragments](./get_textfragments/)() const | Obtiene la colección de objetos [TextFragment](../textfragment/) que describen el texto contenido en la celda. |
## Ver también

* Class [ITableElement](../itableelement/)
* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
