---
title: "OptimizeFileSize"
second_title: "Aspose.PDF para Go vía C++"
description: "Optimizar el tamaño de un documento PDF con calidad de compresión de imagen."
type: docs
url: /es/go-cpp/organize/optimizefilesize/
---

_Optimiza el tamaño del documento PDF con calidad de compresión de imagen._

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
        // Open(filename string) abre un PDF-documento con el nombre de archivo
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libera los recursos asignados para el PDF-documento
        defer pdf.Close()
        // OptimizeFileSize(imageQuality int32) optimiza el tamaño del documento PDF con calidad de compresión de imagen
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
