---
title: "PageRemoveWatermarks"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar marcas de agua en la página."
type: docs
url: /es/go-cpp/organize/pageremovewatermarks/
---

_Eliminar marcas de agua en la página._

```go
func (document *Document) PageRemoveWatermarks(num int32) error
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
        // PageRemoveWatermarks(num int32) elimina marcas de agua en la página
        err = pdf.PageRemoveWatermarks(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_page1_RemoveWatermarks.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
