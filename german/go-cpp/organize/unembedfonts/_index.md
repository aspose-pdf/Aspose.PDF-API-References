---
title: "UnembedFonts"
second_title: "Aspose.PDF für Go über C++"
description: "Schriftarten aus einem PDF-Dokument entfernen."
type: docs
url: /de/go-cpp/organize/unembedfonts/
---

_Entbetten von Schriftarten eines PDF-Dokuments._

```go
func (document *Document) UnembedFonts() error
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
        // UnembedFonts() entfernt die Einbettung von Schriftarten eines PDF-Dokuments
        err = pdf.UnembedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_UnembedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
