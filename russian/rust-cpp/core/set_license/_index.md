---
title: "set_license"
second_title: "Aspose.PDF для Rust через C++"
description: "Устанавливает лицензию с помощью имени файла."
type: docs
url: /ru/rust-cpp/core/set_license/
---

_Устанавливает лицензию с помощью имени файла._

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Установить лицензию с именем файла
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Теперь вы можете работать с лицензированным PDF‑документом
    // ...

    Ok(())
}

```