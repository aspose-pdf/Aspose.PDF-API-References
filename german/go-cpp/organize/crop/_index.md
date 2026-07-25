---
title: "Crop"
second_title: "Aspose.PDF für Go über C++"
description: "Seiten eines PDF-Dokuments zuschneiden."
type: docs
url: /de/go-cpp/organize/crop/
---

_Beschneide Seiten eines PDF-Dokuments._

```go
func (document *Document) Crop(margin float64) error
```

**Parameters**: 
  * **margin** - page margin

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
        // Open(filename string) öffnet ein PDF-document mit Dateiname
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() gibt zugewiesene Ressourcen für PDF-document frei
        defer pdf.Close()
        // Crop(margin float64) schneidet Seiten eines PDF-Dokuments zu
        err = pdf.Crop(0)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
