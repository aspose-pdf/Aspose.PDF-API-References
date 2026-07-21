---
title: "Clase Aspose::Pdf::Forms::BarcodeField"
linktitle: "BarcodeField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Forms::BarcodeField. La clase representa un campo de código de barras en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.forms/barcodefield/
---
## BarcodeField class


Clase que representa un campo de código de barras.

```cpp
class BarcodeField : public Aspose::Pdf::Forms::TextBoxField
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BarcodeField](./barcodefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Inicializa una nueva instancia de la clase [BarcodeField](./). |
| [BarcodeField](./barcodefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Inicializa una nueva instancia de la clase [BarcodeField](./). |
| [get_Caption](./get_caption/)() | Obtiene el título del objeto de código de barras. |
| [get_ECC](./get_ecc/)() | Obtiene un valor entero que representa el coeficiente de corrección de errores. Para PDF417, debe estar entre 0 y 8. Para QRCode, debe estar entre 0 y 3 (0 para 'L', 1 para 'M', 2 para 'Q' y 3 para 'H'). |
| [get_Resolution](./get_resolution/)() | Obtiene la resolución, en puntos por pulgada (dpi), a la que se renderiza el objeto de código de barras. |
| [get_Symbology](./get_symbology/)() | Especifica qué tecnología de código de barras o glifo se debe usar en esta anotación, vea [Symbology](../symbology/) para más detalles. |
| [get_XSymHeight](./get_xsymheight/)() | Obtiene la distancia vertical entre dos módulos de código de barras, medida en píxeles. La razón XSymHeight/XSymWidth debe ser un valor entero. Para PDF417, el rango aceptable de la razón es de 1 a 4. Para QRCode y DataMatrix, esta razón siempre debe ser 1. |
| [get_XSymWidth](./get_xsymwidth/)() | Obtiene la distancia horizontal, en píxeles, entre dos módulos de código de barras. |
## Ver también

* Class [TextBoxField](../textboxfield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
