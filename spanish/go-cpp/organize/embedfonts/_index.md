---
title: "EmbedFonts"
second_title: "Aspose.PDF para Go vía C++"
description: "Incrustar fuentes en PDF-document."
type: docs
url: /es/go-cpp/organize/embedfonts/
---

_Incrustar fuentes en un documento PDF._

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
        // Open(filename string) abre un PDF-documento con el nombre de archivo
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libera los recursos asignados para el PDF-documento
        defer pdf.Close()
        // EmbedFonts() incrusta fuentes en un documento PDF
        err = pdf.EmbedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_EmbedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
