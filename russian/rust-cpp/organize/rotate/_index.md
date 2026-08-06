---
title: "rotate"
second_title: "Aspose.PDF для Rust через C++"
description: "Поворачивает PDF-документ."
type: docs
url: /ru/rust-cpp/organize/rotate/
---

_Поворачивает PDF-документ._

```rust
pub fn rotate(&self, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Повернуть PDF-документ
    pdf.rotate(Rotation::On270)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```