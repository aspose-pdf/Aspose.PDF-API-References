---
title: "SetPermissions"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document에 대한 권한을 설정합니다."
type: docs
url: /ko/go-cpp/security/setpermissions/
---

_PDF-document에 대한 권한을 설정합니다._

```go
func (document *Document) SetPermissions(userPassword string, ownerPassword string, permissions Permissions) error
```

**Parameters**: 
  * **userPassword** - user password
  * **ownerPassword** - owner password
  * **permissions** - bitmask of allowed PDF permissions (combine flags using `|`):
```go
type Permissions int32
const (
    PrintDocument                  Permissions = 1 << 2  // 4
    ModifyContent                  Permissions = 1 << 3  // 8
    ExtractContent                 Permissions = 1 << 4  // 16
    ModifyTextAnnotations          Permissions = 1 << 5  // 32
    FillForm                       Permissions = 1 << 8  // 256
    ExtractContentWithDisabilities Permissions = 1 << 9  // 512
    AssembleDocument               Permissions = 1 << 10 // 1024
    PrintingQuality                Permissions = 1 << 11 // 2048
)
```

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New는 새로운 PDF-document를 생성합니다
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()

	// SetPermissions(userPassword, ownerPassword, permissions) 은 PDF-document에 대한 권한을 설정합니다
	err = pdf.SetPermissions(
		"userpass",
		"ownerpass",
		asposepdf.PrintDocument|
			asposepdf.ModifyContent|
			asposepdf.FillForm,
	)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_with_permissions.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
