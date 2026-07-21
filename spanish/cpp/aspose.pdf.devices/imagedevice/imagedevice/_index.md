---
title: "Aspose::Pdf::Devices::ImageDevice::ImageDevice constructor"
linktitle: "ImageDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Devices::ImageDevice::ImageDevice constructor. Inicializador abstracto para descendientes de ImageDevice, establece la resolución a 150x150 en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.devices/imagedevice/imagedevice/
---
## ImageDevice::ImageDevice() constructor


Inicializador abstracto para [ImageDevice](../) descendientes, establece la resolución a 150x150.

```cpp
Aspose::Pdf::Devices::ImageDevice::ImageDevice()
```

## Ver también

* Class [ImageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageDevice::ImageDevice(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) constructor


Inicializador abstracto para [ImageDevice](../) descendientes.

```cpp
Aspose::Pdf::Devices::ImageDevice::ImageDevice(const System::SharedPtr<Aspose::Pdf::Devices::Resolution> &resolution)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Resolution](../../resolution/)
* Class [ImageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageDevice::ImageDevice(const System::SharedPtr\<PageSize\>\&) constructor


Inicializa una nueva instancia de la clase [JpegDevice](../../jpegdevice/) con las dimensiones de imagen proporcionadas y resolución predeterminada (=150).

```cpp
Aspose::Pdf::Devices::ImageDevice::ImageDevice(const System::SharedPtr<PageSize> &pageSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageSize | const System::SharedPtr\<PageSize\>\& | Tamaño de [Page](../../../aspose.pdf/page/) de la imagen de salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageDevice::ImageDevice(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) constructor


Inicializa una nueva instancia de la clase [JpegDevice](../../jpegdevice/) con las dimensiones de imagen proporcionadas y resolución.

```cpp
Aspose::Pdf::Devices::ImageDevice::ImageDevice(const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<Aspose::Pdf::Devices::Resolution> &resolution)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageSize | const System::SharedPtr\<PageSize\>\& | Tamaño de [Page](../../../aspose.pdf/page/) de la imagen de salida. |
| resolution | const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\& | [Resolution](../../resolution/) para el archivo de imagen resultante, vea la clase [Resolution](../../resolution/). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [Resolution](../../resolution/)
* Class [ImageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageDevice::ImageDevice(int32_t, int32_t) constructor


Inicializa una nueva instancia de la clase [JpegDevice](../../jpegdevice/) con las dimensiones de imagen proporcionadas y resolución predeterminada (=150).

```cpp
Aspose::Pdf::Devices::ImageDevice::ImageDevice(int32_t width, int32_t height)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int32_t | Ancho de salida de [Image](../../../aspose.pdf/image/). |
| height | int32_t | Altura de salida de [Image](../../../aspose.pdf/image/). |

## Ver también

* Class [ImageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageDevice::ImageDevice(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) constructor


Inicializa una nueva instancia de la clase [JpegDevice](../../jpegdevice/) con las dimensiones de imagen proporcionadas y resolución.

```cpp
Aspose::Pdf::Devices::ImageDevice::ImageDevice(int32_t width, int32_t height, const System::SharedPtr<Aspose::Pdf::Devices::Resolution> &resolution)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int32_t | Ancho de salida de [Image](../../../aspose.pdf/image/). |
| height | int32_t | Altura de salida de [Image](../../../aspose.pdf/image/). |
| resolution | const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\& | [Resolution](../../resolution/) para el archivo de imagen resultante, vea la clase [Resolution](../../resolution/). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Resolution](../../resolution/)
* Class [ImageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
