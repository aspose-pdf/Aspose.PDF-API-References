---
title: "get_permissions"
second_title: "Aspose.PDF для Rust через C++"
description: "Получить текущие разрешения PDF-документа."
type: docs
url: /ru/rust-cpp/security/get_permissions/
---

_Получить текущие разрешения PDF‑документа._

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
    // Открыть PDF‑документ, защищённый паролем
    let pdf = Document::open_with_password("sample_with_permissions.pdf", "ownerpass")?;

    // Получить текущие разрешения PDF‑документа
    let permissions: Permissions = pdf.get_permissions()?;

    // Вывести разрешения
    println!("Permissions: {}", permissions);

    Ok(())
}

```