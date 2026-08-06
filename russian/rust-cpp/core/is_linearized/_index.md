---
title: "is_linearized"
second_title: "Aspose.PDF для Rust через C++"
description: "Получает значение, указывающее, линейзован ли документ."
type: docs
url: /ru/rust-cpp/core/is_linearized/
---

_Получает значение, указывающее, линейзован ли документ._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Получить значение, указывающее, линейзован ли документ
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```