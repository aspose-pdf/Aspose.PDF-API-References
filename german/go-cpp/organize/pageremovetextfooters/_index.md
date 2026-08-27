---
title: "PageRemoveTextFooters"
second_title: "Aspose.PDF für Go über C++"
description: "Textfußzeilen auf der Seite entfernen."
type: docs
url: /de/go-cpp/organize/pageremovetextfooters/
---

_Textfußzeilen auf der Seite entfernen._

```go
func (document *Document) PageRemoveTextFooters(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
        // PageRemoveTextFooters(num int32) entfernt Textfußzeilen auf der Seite
        err = pdf.PageRemoveTextFooters(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_page1_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
