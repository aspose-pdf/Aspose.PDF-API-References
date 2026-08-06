---
title: "open_with_password"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "비밀번호로 보호된 PDF-document를 엽니다."
type: docs
url: /ko/rust-cpp/security/open_with_password/
---

_비밀번호로 보호된 PDF 문서를 엽니다._

```rust
pub fn open_with_password(filename: &str, password: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open
  * **password** - user/owner password of the password-protected PDF-document

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 비밀번호로 보호된 PDF 문서를 엽니다
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // 작업 중...

    Ok(())
}

```