---
title: "Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination‑metod"
linktitle: "CreateDestination"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination‑metod. Skapar destination till angiven plats på sidan med hänsyn till sidrotation om det behövs i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.annotations/xyzexplicitdestination/createdestination/
---
## XYZExplicitDestination::CreateDestination method


Skapa destination till angiven plats på sidan med hänsyn till sidrotation om det krävs.

```cpp
static System::SharedPtr<XYZExplicitDestination> Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination(const System::SharedPtr<Aspose::Pdf::Page> &page, double left, double top, double zoom, bool considerRotation)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Destinationssida. |
| left | double | [Left](../../../aspose.pdf/left/) position på sidan. |
| övre | double | Top position på sidan. |
| zoom | double | Zoomfaktor (0 för standard). |
| considerRotation | bool | Om true kommer positionen att omräknas enligt sidrotation. |

### ReturnValue

Destination‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XYZExplicitDestination](../)
* Class [Page](../../../aspose.pdf/page/)
* Class [XYZExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
