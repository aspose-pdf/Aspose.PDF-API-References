---
title: "PageCrop"
second_title: "Aspose.PDF per Go via C++"
description: "Ritaglia la pagina."
type: docs
url: /it/go-cpp/organize/pagecrop/
---

_Ritaglia la pagina._

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
        // Open(filename string) apre un PDF-document con filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() rilascia le risorse allocate per il PDF-document
        defer pdf.Close()
        // PageCrop(num int32, margin float64) ritaglia la pagina
        err = pdf.PageCrop(1, 11.3)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
        err = pdf.SaveAs("sample_page1_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
