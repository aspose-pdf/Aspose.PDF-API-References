---
title: "PageCrop"
second_title: "Aspose.PDF für Go über C++"
description: "Seite zuschneiden."
type: docs
url: /de/go-cpp/organize/pagecrop/
---

_Seite zuschneiden._

```go
func (document *Document) PageCrop(num int32, margin float64) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
        // PageCrop(num int32, margin float64) schneidet die Seite zu
        err = pdf.PageCrop(1, 11.3)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_page1_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
