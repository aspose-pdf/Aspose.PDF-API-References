---
title: "암호화"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document를 암호화합니다."
type: docs
url: /ko/go-cpp/security/encrypt/
---

_PDF-document을 암호화합니다._

```go
func (document *Document) Encrypt(userPassword string, ownerPassword string, permissions Permissions, cryptoAlgorithm CryptoAlgorithm, usePdf20 bool) error
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
  * **cryptoAlgorithm** - encryption algorithm:
```go
type CryptoAlgorithm int32
const (
	RC4x40  CryptoAlgorithm = 0 // RC4 with key length 40.
	RC4x128 CryptoAlgorithm = 1 // RC4 with key length 128.
	AESx128 CryptoAlgorithm = 2 // AES with key length 128.
	AESx256 CryptoAlgorithm = 3 // AES with key length 256.
)
```
  * **usePdf20** - if true, uses PDF 2.0 encryption (for AESx128/256); otherwise uses standard PDF 1.x encryption

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
	// Encrypt(userPassword, ownerPassword, permissions, cryptoAlgorithm, usePdf20) 은 PDF-document을 암호화합니다
	err = pdf.Encrypt(
		"userpass",
		"ownerpass",
		asposepdf.PrintDocument|asposepdf.ModifyContent|asposepdf.FillForm,
		asposepdf.AESx128,
		true,
	)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_with_password.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
