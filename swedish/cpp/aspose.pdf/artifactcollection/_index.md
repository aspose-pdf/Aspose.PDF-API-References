---
title: "Aspose::Pdf::ArtifactCollection class"
linktitle: "ArtifactCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ArtifactCollection class. Klassen representerar en artefaktssamling i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf/artifactcollection/
---
## ArtifactCollection class


Klassen representerar en samling av artefakter.

```cpp
class ArtifactCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Artifact>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Artifact\>\&) override | Lägger till artefakter i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Artifact\>\>, int32_t) override | Kopierar samlingen till en array. |
| [Delete](./delete/)(const System::SharedPtr\<Artifact\>\&) | Tar bort specificerad artefakt. |
| [Delete](./delete/)(int32_t) | Tar bort artefakt efter dess index. |
| [FindByValue](./findbyvalue/)(const System::String\&, const System::String\&) | Hittar artefakter efter anpassat värde. |
| [get_Count](./get_count/)() const override | Hämtar antalet artefakter i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar om samlingen är skrivskyddad. Returnerar alltid falskt. |
| [get_IsSynchronized](./get_issynchronized/)() | Är detta objekt synkroniserat. |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar synkroniseringsobjektet för samlingen. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar artefakt efter index. Index börjar från 1. |
| [Update](./update/)(const System::SharedPtr\<Artifact\>\&) | Uppdatera artefakt i samlingen. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
