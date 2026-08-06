---
title: "get_permissions"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document의 현재 권한을 가져옵니다."
type: docs
url: /ko/rust-cpp/security/get_permissions/
---

_PDF 문서의 현재 권한을 가져옵니다._

```rust
pub fn get_permissions(&self) -> Result<Permissions, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Permissions)** - the bitmask of permissions, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Permissions};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 비밀번호로 보호된 PDF 문서를 엽니다
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // PDF 문서의 현재 권한 가져오기
    let permissions: Permissions = pdf.get_permissions()?;

    // 권한 출력
    println!("Permissions: {}", permissions);

    Ok(())
}

```