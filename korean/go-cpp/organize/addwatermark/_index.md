---
title: "AddWatermark"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document에 워터마크를 추가합니다."
type: docs
url: /ko/go-cpp/organize/addwatermark/
---

_PDF 문서에 워터마크를 추가합니다._

```go
func (document *Document) AddWatermark(text string, fontName string, fontSize float64, foregroundColor string, xPosition int32, yPosition int32, rotation int32, isBackground bool, opacity float64) error
```

**Parameters**: 
  * **text** - watermark text
  * **fontName** - font name
  * **fontSize** - font size
  * **foregroundColor** - text color (hexadecimal format "#RRGGBB", where RR-red, GG-green and BB-blue hexadecimal integers)
  * **xPosition** - x watermark position
  * **yPosition** - y watermark position
  * **rotation** - watermark rotation (0-360)
  * **isBackground** - background
  * **opacity** - opacity (decimal)

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
        // AddWatermark(text string, fontName string, fontSize float64, foregroundColor string, xPosition int32, yPosition int32, rotation int32, isBackground bool, opacity float64) PDF 문서에 워터마크를 추가합니다
        err = pdf.AddWatermark("Watermark", "Arial", 16, "#010101", 100, 100, 45, true, 0.5)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
        err = pdf.SaveAs("sample_AddWatermark.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
