---
title: "optimize_file_size"
second_title: "Aspose.PDF для Rust через C++"
description: "Оптимизирует размер PDF-документа с качеством сжатия изображений."
type: docs
url: /ru/rust-cpp/organize/optimize_file_size/
---

_Оптимизирует размер PDF-документа с качеством сжатия изображений._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF‑документ с именем файла
    let pdf = Document::open("sample.pdf")?;

    // Оптимизировать размер PDF-документа с качеством сжатия изображений
    pdf.optimize_file_size(50)?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```