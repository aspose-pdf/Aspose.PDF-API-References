---
title: "OptimizeFileSize"
second_title: "Aspose.PDF für Go über C++"
description: "Größe eines PDF-Dokuments mit Bildkomprimierungsqualität optimieren."
type: docs
url: /de/go-cpp/organize/optimizefilesize/
---

_Größe des PDF-Dokuments mit Bildkomprimierungsqualität optimieren._

```go
func (document *Document) OptimizeFileSize(imageQuality int32) error
```

**Parameters**: 
  * **imageQuality** - image compression quality 

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
        // OptimizeFileSize(imageQuality int32) optimiert die Größe des PDF-Dokuments mit Bildkomprimierungsqualität
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
