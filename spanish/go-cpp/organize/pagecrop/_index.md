---
title: "PageCrop"
second_title: "Aspose.PDF para Go vía C++"
description: "Recortar página."
type: docs
url: /es/go-cpp/organize/pagecrop/
---

_Recortar página._

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
        // Open(filename string) abre un PDF-documento con el nombre de archivo
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libera los recursos asignados para el PDF-documento
        defer pdf.Close()
        // PageCrop(num int32, margin float64) recorta la página
        err = pdf.PageCrop(1, 11.3)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_page1_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
