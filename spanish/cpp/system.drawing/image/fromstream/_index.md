---
title: "Método System::Drawing::Image::FromStream"
linktitle: "FromStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Drawing::Image::FromStream. Crea un objeto Image a partir del flujo especificado en C++."
type: docs
weight: 2900
url: /es/cpp/system.drawing/image/fromstream/
---
## Image::FromStream method


Crea un objeto [Image](../) a partir del flujo especificado.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=true)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<System::IO::Stream\>\& | Un flujo que contiene datos de imagen |
| use_embedded_color_management | bool | IGNORED |
| validate_image_data | bool | IGNORED |

### ReturnValue

Un puntero compartido al objeto [Image](../) creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
