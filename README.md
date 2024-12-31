# npm-scrapper-faris

<p align="center">
  <img src="https://img.shields.io/npm/v/npm-scrapper-faris?color=blue&style=flat-square" alt="npm version" />
  <img src="https://img.shields.io/npm/dw/npm-scrapper-faris?color=brightgreen&style=flat-square" alt="downloads" />
  <img src="https://img.shields.io/npm/l/npm-scrapper-faris?style=flat-square" alt="license" />
</p>

---

### 📝 About
**npm-scrapper-faris** is a lightweight npm package designed to scrape and extract information about any npm package. Whether you're a developer exploring package metadata or an enthusiast curious about npm stats, this tool simplifies the process with ease.

---

## 🚀 Features

- 🗂 Fetch detailed metadata for any npm package.
- 📊 Extract details like description, version, author, license, keywords, and more.
- ⚡ Simple and intuitive API.
- ✅ Fully asynchronous for seamless integration.

---

## 📦 Installation

```bash
npm install npm-scrapper-faris
```

---

## 🔧 Usage

```javascript
const { pkgInfo } = require('npm-scrapper-faris');

(async (name) => {
  const result = await pkgInfo(name);
  console.log(result);
})("axios");
```

### Example Output:

```json
{
  Name: "axios",
  packageUrl: "https://www.npmjs.com/package/axios",
  Github_Repo: "https://github.com/axios/axios",
  Weekly_Downloads: "22,384,608",
  Last_Published: "a month ago",
  Homepage: "axios-http.com",
  Version: "1.7.9",
  License: "MIT",
  Unpacked_Size: "2.13 MB",
  Total_Files: "86",
  Keywords: "xhr, http, ajax, promise, node"
}
```

---

## 🌟 Why npm-scrapper-faris?

- **Easy to use**: One-liner integration into your projects.
- **Lightweight**: Focused and optimized for speed.
- **Detailed Insights**: Get all the key information you need in one go.

---

## 📚 API Reference

### `pkgInfo(packageName)`

Fetches metadata for the specified npm package.

#### Parameters:
- `packageName` *(string)*: The name of the npm package you want to scrape.

#### Returns:
- A promise that resolves to an object containing package details.

---


## 🤝 Contributing

Contributions are currently not accepted as the code is proprietary and encrypted.

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---

<p align="center">Made with ❤️ by Faris</p>
