---
title: "ReplaceFont"
second_title: "Aspose.PDF für Go über C++"
description: "Schriftart in einem PDF-Dokument ersetzen."
type: docs
url: /de/go-cpp/organize/replacefont/
---

_Ersetzt die Schriftart in einem PDF-Dokument._

```go
func (document *Document) ReplaceFont(findFontName, replaceFontName string) error
```

**Parameters**: 
  * **findFontName** - font name to search
  * **replaceFontName** - font name to replace

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
        // ReplaceFont(findFontName, replaceFontName string) ersetzt die Schriftart in einem PDF-Dokument
        err = pdf.ReplaceFont("Helvetica", "Courier")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
