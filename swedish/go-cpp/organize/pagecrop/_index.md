---
title: "PageCrop"
second_title: "Aspose.PDF för Go via C++"
description: "Beskär sidan."
type: docs
url: /sv/go-cpp/organize/pagecrop/
---

_Beskär sidan._

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
        // Open(filename string) öppnar ett PDF-dokument med filnamn
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() frigör allokerade resurser för PDF-dokument
        defer pdf.Close()
        // PageCrop(num int32, margin float64) beskär sidan
        err = pdf.PageCrop(1, 11.3)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
        err = pdf.SaveAs("sample_page1_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
