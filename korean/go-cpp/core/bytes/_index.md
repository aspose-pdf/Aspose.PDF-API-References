---
title: "Bytes"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF 문서의 내용을 바이트 슬라이스로 반환합니다."
type: docs
url: /ko/go-cpp/core/bytes/
---

_PDF 문서의 내용을 바이트 슬라이스로 반환합니다._

```go
func (document *Document) Bytes() ([]byte, error)
```

**Parameters**: 

**Return**:
  * **\[\]byte** - raw bytes of the PDF-document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
        "github.com/aspose-pdf/aspose-pdf-go-cpp"
        "log"
        "os"
)

func main() {
        // New는 새로운 PDF-document를 생성합니다
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes PDF 문서의 내용을 바이트 슬라이스로 반환합니다
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // 바이트 슬라이스를 파일에 저장합니다.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
