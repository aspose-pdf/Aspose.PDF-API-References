---
title: "Aspose::Pdf::Comparison::ImagesDifference class"
linktitle: "ImagesDifference"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::ImagesDifference class. Representa la clase de resultado de comparar dos páginas PDF en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class


Representa la clase de resultado de comparar dos páginas PDF.

```cpp
class ImagesDifference : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DifferenceToImage](./differencetoimage/)(const System::SharedPtr\<Color\>\&, const System::SharedPtr\<Color\>\&) | Convierte la matriz de diferencias a una imagen bitmap usando los colores especificados. |
| [Dispose](./dispose/)() override | Ejecuta cualquier operación de limpieza necesaria antes de que el objeto sea destruido. |
| [get_Difference](./get_difference/)() const | Obtiene la matriz de diferencias. Esta matriz es similar a la matriz de datos de imagen original obtenida como resultado del método LockBits. |
| [get_Height](./get_height/)() const | La altura de la diferencia. |
| [get_SourceImage](./get_sourceimage/)() const | Obtiene la imagen de la primera página comparada. La imagen tiene un formato de píxel de 24bpp. |
| [get_Stride](./get_stride/)() const | El paso de los datos de la imagen de diferencia. |
| [GetDestinationImage](./getdestinationimage/)() | Devuelve un nuevo bitmap que representa la imagen de destino aplicando la matriz de diferencias a la imagen de origen. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
