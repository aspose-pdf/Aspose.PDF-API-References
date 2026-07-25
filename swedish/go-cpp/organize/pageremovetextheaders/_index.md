---
title: "PageRemoveTextHeaders"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort textrubriker på sidan."
type: docs
url: /sv/go-cpp/organize/pageremovetextheaders/
---

_Ta bort textrubriker på sidan._

```go
func (document *Document) PageRemoveTextHeaders(num int32) error
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
        // Open(filename string) öppnar ett PDF-dokument med filnamn
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() frigör allokerade resurser för PDF-dokument
        defer pdf.Close()
        // PageRemoveTextHeaders(num int32) tar bort textrubriker på sidan
        err = pdf.PageRemoveTextHeaders(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
        err = pdf.SaveAs("sample_page1_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
