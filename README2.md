# mock-api

A mock REST API for prototyping, testing, and development — powered by my-json-server from @typicode.

This repo contains a simple `db.json` file that acts as a fake API backend. It can be accessed online without any setup using the Typicode-hosted my-json-server.

---

## 🔗 Live API URL

You can use this fake API via:

https://my-json-server.typicode.com/uptype/mock-api

> Replace `/posts`, `/users`, etc. as needed.

Example:
GET https://my-json-server.typicode.com/uptype/mock-api/posts

---

## 📁 Contents

The API is based on the structure of `db.json` in this repo. You can add or modify the data as needed to suit your testing.

---

## ✅ Use Cases

- Front-end prototyping
- Demo projects
- Testing API integrations without a real backend
- Quick mocking in dev environments

---

## 🙏 Credit

This project is built using:

- json-server by @typicode → https://github.com/typicode/json-server
- my-json-server → https://my-json-server.typicode.com/

---

## 🛠 Want to self-host?

If you'd rather run a local version instead of using the hosted version, clone this repo and run:

npm install -g json-server
json-server --watch db.json

Then access it at:
http://localhost:3000

---

## 📘 License

This repo is open source and available under the MIT License.
