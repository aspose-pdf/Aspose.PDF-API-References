---
title: "set_permissions"
second_title: "Aspose.PDF for Rust via C++"
description: "设置 PDF-document 的权限。"
type: docs
url: /zh/rust-cpp/security/set_permissions/
---

_设置 PDF 文档的权限._

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
    // 创建一个新的 PDF-document
    let pdf = Document::new()?;

    // 设置 PDF-document 的权限。
    pdf.set_permissions(
        "userpass",  // User password
        "ownerpass", // Owner password
        Permissions::PRINT_DOCUMENT | Permissions::MODIFY_CONTENT | Permissions::FILL_FORM, // Permissions bitmask
    )?;

    // 保存已更新权限的 PDF 文档
    pdf.save_as("sample_with_permissions.pdf")?;

    Ok(())
}

```