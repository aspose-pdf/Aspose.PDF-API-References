---
title: "EmbedFonts"
second_title: "Aspose.PDF für Go über C++"
description: "Schriftarten in ein PDF-Dokument einbetten."
type: docs
url: /de/go-cpp/organize/embedfonts/
---

_Schriftarten in ein PDF-Dokument einbetten._

```go
func (document *Document) EmbedFonts() error
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
        // EmbedFonts() bettet Schriftarten in ein PDF-Dokument ein
        err = pdf.EmbedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_EmbedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
