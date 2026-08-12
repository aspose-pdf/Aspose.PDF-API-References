---
title: "Aspose::Pdf::FileSpecification-klass"
linktitle: "FileSpecification"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::FileSpecification-klass. Klass som representerar en inbäddad fil i C++."
type: docs
weight: 5500
url: /sv/cpp/aspose.pdf/filespecification/
---
## FileSpecification class


Klass som representerar inbäddad fil.

```cpp
class FileSpecification : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() override | Rensa innehåll. |
| [FileSpecification](./filespecification/)(const System::String\&) | Konstruktor för [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Konstruktor för filspecifikation. |
| [FileSpecification](./filespecification/)(const System::String\&, const System::String\&) | Konstruktor för [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::String\&) | Konstruktor för [FileSpecification](./). |
| [FileSpecification](./filespecification/)(const System::String\&, const System::SharedPtr\<Annotations::Annotation\>\&) | Konstruktor för [FileSpecification](./). |
| [FileSpecification](./filespecification/)() | Skapa en ny tom filspecifikation. |
| [get_AFRelationship](./get_afrelationship/)() | Associerad filrelation. |
| [get_CollectionItem](./get_collectionitem/)() | Hämtar ett samlingsobjekt av filspecificeringen. |
| [get_Contents](./get_contents/)() | Hämtar innehållsfil. Denna egenskap returnerar data som laddas i minnet vilket kan orsaka Out of memory exception för stora data. För att minska minnesanvändningen, använd StreamContents. |
| [get_Description](./get_description/)() | Hämtar text som är associerad med filspecificeringen. |
| [get_Encoding](./get_encoding/)() const | Hämtar kodningsformat. Möjliga värden: Zip – filen är komprimerad med ZIP, None – filen är inte komprimerad. |
| [get_EncryptedPayload](./get_encryptedpayload/)() | Hämtar krypterad nyttolast. |
| [get_FileSystem](./get_filesystem/)() | Hämtar namn på filsystemet. |
| [get_IncludeContents](./get_includecontents/)() const | Om true, kommer filens innehåll att inkluderas i filspecificeringen. |
| [get_MIMEType](./get_mimetype/)() | Hämtar undertyp av den inbäddade filen. |
| [get_Name](./get_name/)() | Hämtar filspecificeringens namn. |
| [get_Params](./get_params/)() | Hämtar filparametrar. |
| [get_StreamContents](./get_streamcontents/)() | Hämtar filens innehåll som en ström. Innehållet laddas inte in i minnet vilket möjliggör minskad minnesanvändning. Men denna ström stödjer inte positionering och Length‑egenskapen. Om du behöver dessa funktioner, använd egenskapen Contents istället. |
| [get_UnicodeName](./get_unicodename/)() | Hämtar filspecificeringens Unicode‑namn. |
| [GetValue](./getvalue/)(const System::String\&) | Hämtar programspecifik parameter. |
| [set_AFRelationship](./set_afrelationship/)(Aspose::Pdf::AFRelationship) | Associerad filrelation. |
| [set_Contents](./set_contents/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in innehållsfil. Denna egenskap returnerar data som laddas i minnet vilket kan orsaka Out of memory exception för stora data. För att minska minnesanvändningen, använd StreamContents. |
| [set_Description](./set_description/)(const System::String\&) | Ställer in text som är associerad med filspecificeringen. |
| [set_Encoding](./set_encoding/)(FileEncoding) | Ställer in kodningsformat. Möjliga värden: Zip – filen är komprimerad med ZIP, None – filen är inte komprimerad. |
| [set_FileSystem](./set_filesystem/)(const System::String\&) | Ställer in namn på filsystemet. |
| [set_IncludeContents](./set_includecontents/)(bool) | Om true, kommer filens innehåll att inkluderas i filspecificeringen. |
| [set_MIMEType](./set_mimetype/)(const System::String\&) | Hämtar undertyp av den inbäddade filen. |
| [set_Name](./set_name/)(const System::String\&) | Ställer in filspecificeringens namn. |
| [set_Params](./set_params/)(const System::SharedPtr\<FileParams\>\&) | Hämtar filparametrar. |
| [set_UnicodeName](./set_unicodename/)(const System::String\&) | Ställer in filspecificeringens Unicode‑namn. |
| [SetValue](./setvalue/)(const System::String\&, const System::String\&) | Ställer in programspecifik parameter. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
