---
title: Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF method
linktitle: SaveAsTIFF
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF method. Converts each pages of a pdf document to images and saves images to a single TIFF stream in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.facades/pdfconverter/saveastiff/
---
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>) method


Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, Devices::CompressionType) method


Converts each pages of a pdf document to images and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, Devices::CompressionType compressionType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The output stream. |
| compressionType | Devices::CompressionType | Type of the compression. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t) method


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, int32_t imageWidth, int32_t imageHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |
| imageWidth | int32_t | The image width, the unit is pixel. |
| imageHeight | int32_t | The image height, the unit is pixel. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, Devices::CompressionType) method


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, int32_t imageWidth, int32_t imageHeight, Devices::CompressionType compressionType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |
| imageWidth | int32_t | The image width, the unit is pixel. |
| imageHeight | int32_t | The image height, the unit is pixel. |
| compressionType | Devices::CompressionType | Type of the compression. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<Devices::TiffSettings\>) method


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, int32_t imageWidth, int32_t imageHeight, System::SharedPtr<Devices::TiffSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |
| imageWidth | int32_t | The image width, the unit is pixel. |
| imageHeight | int32_t | The image height, the unit is pixel. |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<Devices::TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) method


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, int32_t imageWidth, int32_t imageHeight, System::SharedPtr<Devices::TiffSettings> settings, System::SharedPtr<IIndexBitmapConverter> converter)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |
| imageWidth | int32_t | The image width, the unit is pixel. |
| imageHeight | int32_t | The image height, the unit is pixel. |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |
| converter | System::SharedPtr\<IIndexBitmapConverter\> | External converter |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Devices::TiffSettings\>) method


Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Devices::TiffSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Devices::TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) method


Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Devices::TiffSettings> settings, System::SharedPtr<IIndexBitmapConverter> converter)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |
| converter | System::SharedPtr\<IIndexBitmapConverter\> | External converter |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>) method


Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the image. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::SharedPtr\<Devices::TiffSettings\>) method


Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<PageSize> pageSize, System::SharedPtr<Devices::TiffSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | The stream to save the TIFF image. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the image. |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String) method


Converts each pages of a pdf document to images and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file to save the TIFF image. |

## See Also

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, Devices::CompressionType) method


Converts each pages of a pdf document to images and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, Devices::CompressionType compressionType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The output file. |
| compressionType | Devices::CompressionType | Type of the compression. |

## See Also

* Class [String](../../../system/string/)
* Enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, int32_t, int32_t) method


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, int32_t imageWidth, int32_t imageHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file name to save the TIFF image |
| imageWidth | int32_t | The image width, the unit is pixel. |
| imageHeight | int32_t | The image height, the unit is pixel. |

## See Also

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, int32_t, int32_t, Devices::CompressionType) method


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, int32_t imageWidth, int32_t imageHeight, Devices::CompressionType compressionType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file name to save the TIFF image |
| imageWidth | int32_t | The image width, the unit is pixel. |
| imageHeight | int32_t | The image height, the unit is pixel. |
| compressionType | Devices::CompressionType | Type of the compression. |

## See Also

* Class [String](../../../system/string/)
* Enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, int32_t, int32_t, System::SharedPtr\<Devices::TiffSettings\>) method


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, int32_t imageWidth, int32_t imageHeight, System::SharedPtr<Devices::TiffSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file name to save the TIFF image |
| imageWidth | int32_t | The image width, the unit is pixel. |
| imageHeight | int32_t | The image height, the unit is pixel. |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, int32_t, int32_t, System::SharedPtr\<Devices::TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) method


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, int32_t imageWidth, int32_t imageHeight, System::SharedPtr<Devices::TiffSettings> settings, System::SharedPtr<IIndexBitmapConverter> converter)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file name to save the TIFF image |
| imageWidth | int32_t | The image width, the unit is pixel. |
| imageHeight | int32_t | The image height, the unit is pixel. |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |
| converter | System::SharedPtr\<IIndexBitmapConverter\> | External converter |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, System::SharedPtr\<Devices::TiffSettings\>) method


Converts each pages of a pdf document to images with and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, System::SharedPtr<Devices::TiffSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file name to save the TIFF image |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, System::SharedPtr\<Devices::TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) method


Converts each pages of a pdf document to images with and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, System::SharedPtr<Devices::TiffSettings> settings, System::SharedPtr<IIndexBitmapConverter> converter)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file name to save the TIFF image |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |
| converter | System::SharedPtr\<IIndexBitmapConverter\> | External converter |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, System::SharedPtr\<PageSize\>) method


Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file name to save the TIFF image |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the image. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::SaveAsTIFF(System::String, System::SharedPtr\<PageSize\>, System::SharedPtr\<Devices::TiffSettings\>) method


Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

```cpp
void Aspose::Pdf::Facades::PdfConverter::SaveAsTIFF(System::String outputFile, System::SharedPtr<PageSize> pageSize, System::SharedPtr<Devices::TiffSettings> settings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | The file name to save the TIFF image |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the image. |
| settings | System::SharedPtr\<Devices::TiffSettings\> | Settings object that defines TIFF parameters. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
