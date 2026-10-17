# 🐼 Panda Food API

A lightweight JSON-based API for the Panda Food restaurant website. It provides structured data for food categories, menu items, and special offers.

## ✨ Features

- 📂 **Categories** — Organize menu items by category.
- 🍱 **Food Menu** — Access meal names, prices, descriptions, images, and slugs.
- 🔥 **Special Offers** — Display promotional meals and prices.
- 🖼️ **Food Images** — Local images for menu items and offers.
- 🔗 **Developer Friendly** — Simple JSON data that can be integrated into React, Next.js, or other frontend applications.

## 📁 Project Structure

```text
api_panda_food/
├── images/
│   ├── salad.png
│   ├── soupe_misou.png
│   └── ...
├── categories.json
├── meunfood.json
├── offers.json
└── README.md
```

## 📡 Data Files

| File | Description |
|---|---|
| `categories.json` | Restaurant menu categories |
| `meunfood.json` | Food items, prices, descriptions, and images |
| `offers.json` | Special offers and promotional meals |
| `images/` | Food and offer images |

## 🍽️ Example Food Item

```json
{
  "id": 1,
  "title": "Salade Ceviche Fruit Mer",
  "price": 85,
  "id_categories": 1,
  "desc": "Salade fraîche aux fruits de mer.",
  "slug": "salade-ceviche-fruit-mer",
  "image": "images/salad.png"
}
```

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/Mounirazzouzi/api-panda-food.git
```

Navigate to the project directory:

```bash
cd api-panda-food
```

## 🧩 Integration

These files contain static JSON data. You can import them directly into a frontend project or serve them using a JSON server.

Example with React:

```javascript
import menu from "./meunfood.json";
import categories from "./categories.json";
import offers from "./offers.json";

console.log(menu);
console.log(categories);
console.log(offers);
```

## 🛠️ Technologies

- JSON
- JavaScript
- REST-style data structure
- Git & GitHub

## 👨‍💻 Author

**Mounir Azzouzi**

GitHub: [@Mounirazzouzi](https://github.com/Mounirazzouzi)

## 📄 License

This project is available for personal and educational use. Add a license file if you intend to distribute it under a specific open-source license.
