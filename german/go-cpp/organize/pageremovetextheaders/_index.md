---
title: "PageRemoveTextHeaders"
second_title: "Aspose.PDF für Go über C++"
description: "Textkopfzeilen auf der Seite entfernen."
type: docs
url: /de/go-cpp/organize/pageremovetextheaders/
---

_Entferne Textüberschriften auf Seite._

```go
func (document *Document) PageRemoveTextHeaders(num int32) error
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
        // PageRemoveTextHeaders(num int32) entfernt Textüberschriften auf Seite
        err = pdf.PageRemoveTextHeaders(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_page1_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
