---
title: "PageRemoveTextFooters"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar pies de página de texto en la página."
type: docs
url: /es/go-cpp/organize/pageremovetextfooters/
---

_Elimina pies de texto en la página._

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
        // Open(filename string) abre un PDF-documento con el nombre de archivo
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libera los recursos asignados para el PDF-documento
        defer pdf.Close()
        // PageRemoveTextFooters(num int32) elimina pies de texto en la página
        err = pdf.PageRemoveTextFooters(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_page1_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
