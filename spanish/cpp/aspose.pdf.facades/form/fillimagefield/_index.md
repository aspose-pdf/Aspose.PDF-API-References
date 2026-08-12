---
title: "Aspose::Pdf::Facades::Form::FillImageField método"
linktitle: "FillImageField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::Form::FillImageField método. Sobrecarga la función FillImageField. La entrada es una secuencia de imagen en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.pdf.facades/form/fillimagefield/
---
## Form::FillImageField(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Sobrecarga la función FillImageField. La entrada es un flujo de imagen.

```cpp
void Aspose::Pdf::Facades::Form::FillImageField(const System::String &fieldName, const System::SharedPtr<System::IO::Stream> &imageStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | El nombre de campo totalmente calificado. |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | La secuencia de la imagen. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillImageField(const System::String\&, const System::String\&) method


Pega una imagen en el campo de botón existente como su apariencia según su nombre de campo totalmente calificado.

```cpp
void Aspose::Pdf::Facades::Form::FillImageField(const System::String &fieldName, const System::String &imageFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | const System::String\& | El nombre de campo totalmente calificado del campo de botón de imagen. |
| imageFileName | const System::String\& | La ruta del archivo de imagen, tanto relativa como absoluta son válidas. |

## Ver también

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
