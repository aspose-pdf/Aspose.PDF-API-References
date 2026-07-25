---
title: "Crop"
second_title: "Aspose.PDF per Go via C++"
description: "Ritaglia le pagine di un PDF-document."
type: docs
url: /it/go-cpp/organize/crop/
---

_Ritaglia le pagine di un documento PDF._

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
        // Open(filename string) apre un PDF-document con filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() rilascia le risorse allocate per il PDF-document
        defer pdf.Close()
        // Crop(margin float64) ritaglia le pagine di un documento PDF
        err = pdf.Crop(0)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
        err = pdf.SaveAs("sample_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
