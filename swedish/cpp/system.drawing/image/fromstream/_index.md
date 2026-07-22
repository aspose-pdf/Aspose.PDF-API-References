---
title: "System::Drawing::Image::FromStream metod"
linktitle: "FromStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Image::FromStream metod. Skapar ett Image‑objekt från den angivna strömmen i C++."
type: docs
weight: 2900
url: /sv/cpp/system.drawing/image/fromstream/
---
## Image::FromStream method


Skapar ett [Image](../)‑objekt från den angivna strömmen.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=true)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<System::IO::Stream\>\& | En ström som innehåller bilddata |
| use_embedded_color_management | bool | IGNORED |
| validate_image_data | bool | IGNORED |

### ReturnValue

En delad pekare till det skapade [Image](../)‑objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
