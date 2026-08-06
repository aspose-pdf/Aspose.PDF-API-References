---
title: "복호화"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document를 복호화합니다."
type: docs
url: /ko/rust-cpp/security/decrypt/
---

_PDF 문서를 복호화합니다._

```rust
pub fn decrypt(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 비밀번호로 보호된 PDF 문서를 엽니다
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // PDF 문서 복호화
    pdf.decrypt()?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```