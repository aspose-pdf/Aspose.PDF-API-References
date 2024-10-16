---
title: Aspose::Pdf::LoadOptions::ResourceLoadingResult class
linktitle: ResourceLoadingResult
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LoadOptions::ResourceLoadingResult class. Result of custom loading of resource in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf/loadoptions/resourceloadingresult/
---
## ResourceLoadingResult class


Result of custom loading of resource.

```cpp
class ResourceLoadingResult : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Data](./get_data/)() const | Bynary data that loaded with custom loader - it must be set after loading. |
| [ResourceLoadingResult](./resourceloadingresult/)(System::ArrayPtr\<uint8_t\>) | Creates instance of loading result. |
## Fields

| Field | Description |
| --- | --- |
| [EncodingIfKnown](./encodingifknown/) | Sometimes encoding of resource is known after or during loading. In such case custom code can provide converter with that knowledge via this parameter. You can leave null in this parameter if encoding is unknown or does not matter. |
| [ExceptionOfLoadingIfAny](./exceptionofloadingifany/) | Sometimes it's impossible to load requested resource for some reason. Unavailability of resource often does not lead to crash of conversiov and result document can be created anyway(but maybe in a bit worse quality, without images etc.). If exception occured during loading, just catch it and put in this parameter - sometimes that information is usefull for converter for rendering of result. |
| [LoadingCancelled](./loadingcancelled/) | Sometimes for some reasons loading should not occure custom code. In such case please set this flag as True. In such case converter will try use internal default resource loader to get that result(as it behave in situation when custom strategy not supplied). |
| [MIMETypeIfKnown](./mimetypeifknown/) | Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. Please leave parameter equal to null when MIME type unknown or it's not necessary to supply it. |
## See Also

* Class [Object](../../../system/object/)
* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
