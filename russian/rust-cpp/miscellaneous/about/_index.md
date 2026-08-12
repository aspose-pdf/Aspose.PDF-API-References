---
title: "о"
second_title: "Aspose.PDF для Rust через C++"
description: "Возвращает информацию о метаданных Aspose.PDF для Rust через C++."
type: docs
url: /ru/rust-cpp/miscellaneous/about/
---

_Возвращает информацию о метаданных Aspose.PDF для Rust через C++._

```rust
pub fn about(&self) -> Result<ProductInfo, PdfError>
```

**Arguments**


**Returns**
  * **Ok(ProductInfo)** - if the operation succeeds
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Создайте новый PDF-документ
    let pdf = Document::new()?;

    // Возвращает информацию о метаданных Aspose.PDF для Go через C++.
    let info = pdf.about()?;

    // Вывести поля метаданных
    println!("Product Info:");
    println!("  Product:      {}", info.product);
    println!("  Family:       {}", info.family);
    println!("  Version:      {}", info.version);
    println!("  ReleaseDate:  {}", info.release_date);
    println!("  Producer:     {}", info.producer);
    println!("  IsLicensed:   {}", info.is_licensed);

    Ok(())
}

```