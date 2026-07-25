---
title: "PageRemoveWatermarks"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort vattenstämplar på sidan."
type: docs
url: /sv/go-cpp/organize/pageremovewatermarks/
---

_Ta bort vattenstämplar på sidan._

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
        // Open(filename string) öppnar ett PDF-dokument med filnamn
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() frigör allokerade resurser för PDF-dokument
        defer pdf.Close()
        // PageRemoveWatermarks(num int32) tar bort vattenstämplar på sidan
        err = pdf.PageRemoveWatermarks(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
        err = pdf.SaveAs("sample_page1_RemoveWatermarks.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
