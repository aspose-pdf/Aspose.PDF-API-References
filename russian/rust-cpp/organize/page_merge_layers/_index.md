---
title: "page_merge_layers"
second_title: "Aspose.PDF для Rust через C++"
description: "Объединяет все слои на странице в один слой с указанным новым именем слоя."
type: docs
url: /ru/rust-cpp/organize/page_merge_layers/
---

_Объединяет все слои на странице в один слой с указанным новым именем слоя._

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document из файла
    let pdf = Document::open("sample.pdf")?;

    // Объединить все слои на странице в один слой с указанным новым именем слоя
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```