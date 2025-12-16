---
title: Aspose::Pdf::FileSpecification class
linktitle: FileSpecification
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::FileSpecification class. Class representing embedded file in C++.'
type: docs
weight: 5700
url: /cpp/aspose.pdf/filespecification/
---
## FileSpecification class


Class representing embedded file.

```cpp
class FileSpecification : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Dispose contents. |
| [FileSpecification](./filespecification/)(System::String) | Constructor for [FileSpecification](./). |
| [FileSpecification](./filespecification/)(System::SharedPtr\<System::IO::Stream\>, System::String) | Constructor for file specification. |
| [FileSpecification](./filespecification/)(System::String, System::String) | Constructor for [FileSpecification](./). |
| [FileSpecification](./filespecification/)(System::SharedPtr\<System::IO::Stream\>, System::String, System::String) | Constructor for [FileSpecification](./). |
| [FileSpecification](./filespecification/)(System::String, System::SharedPtr\<Annotations::Annotation\>) | Constructor for [FileSpecification](./). |
| [FileSpecification](./filespecification/)() | Create new empty file specification. |
| [get_AFRelationship](./get_afrelationship/)() | Associated file Relationship. |
| [get_CollectionItem](./get_collectionitem/)() | Gets a collection item of the file specification. |
| [get_Contents](./get_contents/)() | Gets contents file. This property returns data loaded in memory which may cause Out of memory exception for large data. To decrease memory usage please use StreamContents. |
| [get_Description](./get_description/)() | Gets text associated with the file specification. |
| [get_Encoding](./get_encoding/)() const | Gets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed. |
| [get_EncryptedPayload](./get_encryptedpayload/)() | Gets encrypted payload. |
| [get_FileSystem](./get_filesystem/)() | Gets name of the file system. |
| [get_IncludeContents](./get_includecontents/)() const | If true, contents of the file will be included in the file specification. |
| [get_MIMEType](./get_mimetype/)() | Gets subtype of the embedded file. |
| [get_Name](./get_name/)() | Gets file specification name. |
| [get_Params](./get_params/)() | Gets file paramteres. |
| [get_StreamContents](./get_streamcontents/)() | Gets contents of file as stream. Contents is not loaded into memory which allows to decrease memory usage. But this stream does not support positioning and Length property. If you need this features please use Contents property instead. |
| [get_UnicodeName](./get_unicodename/)() | Gets file specification unicode name. |
| [GetValue](./getvalue/)(System::String) | Gets application-specific parameter. |
| [set_AFRelationship](./set_afrelationship/)(Aspose::Pdf::AFRelationship) | Associated file Relationship. |
| [set_Contents](./set_contents/)(System::SharedPtr\<System::IO::Stream\>) | Sets contents file. This property returns data loaded in memory which may cause Out of memory exception for large data. To decrease memory usage please use StreamContents. |
| [set_Description](./set_description/)(System::String) | Sets text associated with the file specification. |
| [set_Encoding](./set_encoding/)(FileEncoding) | Sets encoding format. Possible values: Zip - file is compressed with ZIP, None - file is not compressed. |
| [set_FileSystem](./set_filesystem/)(System::String) | Sets name of the file system. |
| [set_IncludeContents](./set_includecontents/)(bool) | If true, contents of the file will be included in the file specification. |
| [set_MIMEType](./set_mimetype/)(System::String) | Gets subtype of the embedded file. |
| [set_Name](./set_name/)(System::String) | Sets file specification name. |
| [set_Params](./set_params/)(System::SharedPtr\<FileParams\>) | Gets file paramteres. |
| [set_UnicodeName](./set_unicodename/)(System::String) | Sets file specification unicode name. |
| [SetValue](./setvalue/)(System::String, System::String) | Sets application-specific parameter. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
