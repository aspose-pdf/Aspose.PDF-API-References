---
title: "Recortar"
second_title: "Aspose.PDF para Go vía C++"
description: "Recortar páginas de un documento PDF."
type: docs
url: /es/go-cpp/organize/crop/
---

_Recortar páginas de un documento PDF._

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
        // Open(filename string) abre un PDF-documento con el nombre de archivo
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libera los recursos asignados para el PDF-documento
        defer pdf.Close()
        // Crop(margin float64) recorta páginas de un documento PDF
        err = pdf.Crop(0)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
