---
title: "set_permissions"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document에 대한 권한을 설정합니다."
type: docs
url: /ko/rust-cpp/security/set_permissions/
---

_PDF-document에 대한 권한을 설정합니다._

```rust
pub fn set_permissions(
    &self,
    user_password: &str,
    owner_password: &str,
    permissions: Permissions,
) -> Result<(), PdfError>
```

**Arguments**
  * **user_password** - the user password
  * **owner_password** - the owner password
  * **permissions** - the allowed permissions (bitflags `Permissions`)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Permissions};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 새 PDF 문서를 생성합니다
    let pdf = Document::new()?;

    // PDF-document에 대한 권한을 설정합니다.
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // 업데이트된 권한으로 PDF-document을 저장합니다
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```