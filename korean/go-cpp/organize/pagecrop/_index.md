---
title: "PageCrop"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "페이지를 자릅니다."
type: docs
url: /ko/go-cpp/organize/pagecrop/
---

_페이지를 자릅니다._

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
        // Open(filename string) filename을 사용하여 PDF-document을 엽니다
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() PDF-document에 할당된 리소스를 해제합니다
        defer pdf.Close()
        // PageCrop(num int32, margin float64) 은 페이지를 자릅니다
        err = pdf.PageCrop(1, 11.3)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
        err = pdf.SaveAs("sample_page1_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
