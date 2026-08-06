---
title: "is_encrypted"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document의 암호화 상태를 가져옵니다."
type: docs
url: /ko/rust-cpp/security/is_encrypted/
---

_PDF 문서의 암호화 상태를 가져옵니다._

```rust
pub fn is_encrypted(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 비밀번호로 보호된 PDF 문서를 엽니다
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // PDF 문서의 암호화 상태 가져오기
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```