---
title: "Clase Aspose::Pdf::XfaConverter::XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::XfaConverter::XfaParserOptions. Clase para manejar la encapsulación de datos relacionados en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.xfaconverter/xfaparseroptions/
---
## XfaParserOptions class


clase para manejar la encapsulación de datos relacionados

```cpp
class XfaParserOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | Obtiene la ruta base. |
| [get_EmulateRequierdGroups](./get_emulaterequierdgroups/)() const | Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales para los "grupos excluidos" requeridos de Xfa. Esta propiedad se introdujo porque la ausencia de análogos de los grupos excluidos durante la conversión de la representación Xfa de los formularios al estándar. Es falsa por defecto. |
| [get_PageSize](./get_pagesize/)() const | Obtiene el tamaño de la página. |
| [get_Signed](./get_signed/)() const | Si esta propiedad es verdadera, el documento se convertirá utilizando el flujo de formulario xfa (si existe). Si es falsa, el flujo de formulario xfa se ignorará. Esta propiedad se introdujo porque no está claro cómo calcular la suma de verificación utilizada para comprobar la firma. |
| [get_UriResolver](./get_uriresolver/)() const | Obtiene el resolvedor de URI. |
| [set_BasePath](./set_basepath/)(const System::SharedPtr\<System::Uri\>\&) | Establece la ruta base. |
| [set_EmulateRequierdGroups](./set_emulaterequierdgroups/)(bool) | Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales para los "grupos excluidos" requeridos de Xfa. Esta propiedad se introdujo porque la ausencia de análogos de los grupos excluidos durante la conversión de la representación Xfa de los formularios al estándar. Es falsa por defecto. |
| [set_PageSize](./set_pagesize/)(System::Drawing::SizeF) | Establece el tamaño de la página. |
| [set_Signed](./set_signed/)(bool) | Si esta propiedad es verdadera, el documento se convertirá utilizando el flujo de formulario xfa (si existe). Si es falsa, el flujo de formulario xfa se ignorará. Esta propiedad se introdujo porque no está claro cómo calcular la suma de verificación utilizada para comprobar la firma. |
| [set_UriResolver](./set_uriresolver/)(const System::SharedPtr\<Aspose::Foundation::UriResolver::UriResolver\>\&) | Establece el resolvedor de URI. |
| [XfaParserOptions](./xfaparseroptions/)(System::Drawing::SizeF) | Inicializa una nueva instancia de la clase [XfaParserOptions](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::XfaConverter](../)
* Library [Aspose.PDF for C++](../../)
