---
title: "SaveTiff"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "이전에 열었던 PDF-document를 Tiff-document로 변환하고 저장합니다."
type: docs
url: /ko/go-cpp/convert/savetiff/
---

_이전에 열려 있던 PDF 문서를 Tiff 문서로 변환하고 저장합니다._

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
        // Open(filename string) filename을 사용하여 PDF-document을 엽니다
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() PDF-document에 할당된 리소스를 해제합니다
        defer pdf.Close()
        // SaveTiff(filename string) 이전에 열려 있던 PDF 문서를 Tiff 문서로 파일 이름과 함께 저장합니다
        err = pdf.SaveTiff("sample.tiff")
        if err != nil {
                log.Fatal(err)
        }
}
```
