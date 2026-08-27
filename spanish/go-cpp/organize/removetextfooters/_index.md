---
title: "RemoveTextFooters"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar pies de página de texto de un documento PDF."
type: docs
url: /es/go-cpp/organize/removetextfooters/
---

_Eliminar los pies de texto del documento PDF._

```go
func (document *Document) RemoveTextFooters() error
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
        // RemoveTextFooters() elimina los pies de texto del documento PDF
        err = pdf.RemoveTextFooters()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
