# odoo-live-price-formatter

![Odoo](https://img.shields.io/badge/Odoo-18.0-714B67?style=for-the-badge&logo=odoo&logoColor=white)
![Tested](https://img.shields.io/badge/Tested%20On-Odoo%2018-22C55E?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Odoo%20Addon-3B82F6?style=for-the-badge)
![Feature](https://img.shields.io/badge/Feature-Real--Time%20Price%20Formatting-22C55E?style=for-the-badge)
![Feature](https://img.shields.io/badge/Feature-Thousands%20Separator-22C55E?style=for-the-badge)
![Frontend](https://img.shields.io/badge/Frontend-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-22C55E?style=for-the-badge)

<img width="1376" height="688" alt="Odoo Live Price Formatter - Real-time thousands separator formatting for Odoo price fields" src="https://github.com/user-attachments/assets/4345d9dc-a1cb-4d6a-a104-b856979fcc14" />

## Overview

This module automatically formats numeric price inputs while the user is typing. As soon as a value is entered, thousands separators (`,`) are added in real time, improving readability and reducing input errors.

### Example

Input:

```text
1000000
```

Displayed instantly as:

```text
1,000,000
```

## Features

* Real-time formatting while typing
* Automatic thousands separator insertion
* Better user experience for price and amount fields
* No need to leave the field or save the record
* Lightweight and easy to integrate with existing Odoo forms

## Supported Examples

| User Input | Displayed Value |
| :--------- | :-------------- |
| 1000       | 1,000           |
| 25000      | 25,000          |
| 1234567    | 1,234,567       |
| 999999999  | 999,999,999     |

## Installation

1. Copy the `OdooLivePriceFormatter` directory into your Odoo addons path.
2. Restart the Odoo server.
3. Enable Developer Mode.
4. Go to **Apps** and click **Update Apps List**.
5. Search for **Odoo Live Price Formatter** and install the module.

> [!NOTE]
> **Versions**
>
> Available in two flavors:
>
> - **MAINv** — main development version (latest features).
> - **OCAv** — OCA-compliant version (community standards).

## Author

[**Fouad Salehi**](https://github.com/fouad-salehi)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
