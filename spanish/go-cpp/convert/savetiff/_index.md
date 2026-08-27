---
title: "SaveTiff"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como documento Tiff."
type: docs
url: /es/go-cpp/convert/savetiff/
---

_Convierte y guarda el PDF-document previamente abierto como documento Tiff._

```go
func (document *Document) SaveTiff(filename string, resolution_dpi ...int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **resolution_dpi (optional)** - resolution in DPI of the resulting file, defaults to 100 DPI

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
        // SaveTiff(filename string) guarda el PDF-document previamente abierto como documento Tiff con filename
        err = pdf.SaveTiff("sample.tiff")
        if err != nil {
                log.Fatal(err)
        }
}
```
