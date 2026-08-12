---
title: "Aspose::Pdf::Document::Save metod"
linktitle: "Spara"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::Save metod. Sparar dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik) i C++."
type: docs
weight: 8300
url: /sv/cpp/aspose.pdf/document/save/
---
## Document::Save() method


Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik).

```cpp
void Aspose::Pdf::Document::Save()
```

## Anmärkningar


För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför måste [Document](../) initieras med en skrivbar ström som i nästa kodexempel: [Document](../) doc = new [Document](../)(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // gör några ändringar och spara dokumentet inkrementellt doc.Save();
## Se även

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<SaveOptions\>\&) method


Sparar dokumentet med sparalternativ.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<SaveOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | const System::SharedPtr\<SaveOptions\>\& | Spara alternativ. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&) method


Lagrar dokumentet i en ström.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Ström där dokumentet ska lagras. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SaveOptions\>\&) method


Sparar dokumentet till en ström med ett sparalternativ.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<SaveOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström där dokumentet kommer att lagras. |
| options | const System::SharedPtr\<SaveOptions\>\& | Spara alternativ. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&, SaveFormat) method


Sparar dokumentet med ett nytt namn tillsammans med ett filformat.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &outputStream, SaveFormat format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::Web::HttpResponse\>\&, const System::String\&, ContentDisposition, const System::SharedPtr\<SaveOptions\>\&) method


Sparar dokumentet till en svarström med ett sparalternativ.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::Web::HttpResponse> &response, const System::String &outputFileName, ContentDisposition disposition, const System::SharedPtr<SaveOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Inkapslar HTTP-svarsinformation. |
| outputFileName | const System::String\& | Enkelt filnamn, dvs. utan sökväg. |
| disposition | ContentDisposition | Representerar en MIME-protokoll Content-Disposition-header. |
| options | const System::SharedPtr\<SaveOptions\>\& | Spara alternativ. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [String](../../../system/string/)
* Enum [ContentDisposition](../../contentdisposition/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&) method


Sparar dokumentet i den angivna filen.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | const System::String\& | Sökväg till filen där dokumentet kommer att lagras. |

## Se även

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&, const System::SharedPtr\<SaveOptions\>\&) method


Sparar dokumentet med ett nytt namn och anger dess sparalternativ.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName, const System::SharedPtr<SaveOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | const System::String\& | Sökväg till filen där dokumentet kommer att lagras. |
| options | const System::SharedPtr\<SaveOptions\>\& | Spara alternativ. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&, SaveFormat) method


Sparar dokumentet med ett nytt namn tillsammans med ett filformat.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName, SaveFormat format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | const System::String\& | Sökväg till filen där dokumentet kommer att lagras. |
| format | SaveFormat | Formatalternativ. |

## Se även

* Class [String](../../../system/string/)
* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
