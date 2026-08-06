---
title: "get_permissions"
second_title: "Aspose.PDF for Rust via C++"
description: "获取 PDF-document 的当前权限。"
type: docs
url: /zh/rust-cpp/security/get_permissions/
---

_获取 PDF 文档的当前权限。_

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
    // 打开受密码保护的 PDF 文档
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // 获取 PDF 文档的当前权限
    let permissions: Permissions = pdf.get_permissions()?;

    // 打印权限
    println!("Permissions: {}", permissions);

    Ok(())
}

```