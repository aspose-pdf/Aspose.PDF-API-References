---
title: "RemoveTextHeaders"
second_title: "Aspose.PDF für Go über C++"
description: "Textkopfzeilen aus einem PDF-Dokument entfernen."
type: docs
url: /de/go-cpp/organize/removetextheaders/
---

_Textkopfzeilen aus PDF-Dokument entfernen._

```go
func (document *Document) RemoveTextHeaders() error
```

**Parameters**: 

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
        // RemoveTextHeaders() entfernt Textkopfzeilen aus PDF-Dokument
        err = pdf.RemoveTextHeaders()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
