# shamir-app

The official Shamir application in the **Krunixbase Ecosystem**.  
This repository serves as the primary, actively maintained application built on top of Shamir cryptographic modules, Envelope format, and CLI tooling.

---

## 🎯 Purpose

`shamir-app` is the central end‑user application providing:

- Shamir Secret Sharing (SSS) operations  
- integration with `shamir-core`  
- envelope creation and parsing via `shamir-envelope`  
- CLI integration through `shamir-cli`  
- threshold operations and validation  
- full offline mode and local‑only cryptography  

It is designed for end users, auditors, security teams, and system integrators.

---

## 🧩 Architecture Overview

The application is built on top of the following Krunixbase modules:

- **shamir-core** — core Shamir Secret Sharing algorithms  
- **shamir-envelope** — envelope format and serialization  
- **shamir-cli** — command‑line tooling  
- **threshold-operations** — threshold and helper cryptographic operations  

`shamir-app` acts as the application layer (GUI / API / operator interface).

---

## 🚀 Features

- generate Shamir Secret Sharing shares  
- reconstruct secrets from shares  
- create and read envelope files  
- import/export data  
- integrate with CLI tools  
- operate fully offline  
- support multiple data formats  

---

## 📦 Installation

Installation depends on the chosen technology stack. Example workflow:

```
git clone https://github.com/krunixbase/shamir-app
cd shamir-app
npm install
npm start
```

---

## ▶️ Running the Application

```
npm start
```

---

## 🔗 Related Repositories

- https://github.com/krunixbase/shamir-core  
- https://github.com/krunixbase/shamir-envelope  
- https://github.com/krunixbase/shamir-cli  
- https://github.com/krunixbase/threshold-operations  

---

## 🛡️ Security

- fully offline operation  
- no telemetry  
- no external cryptographic dependencies  
- all cryptographic operations executed locally  

---

## 🗺️ Roadmap

### Version 2.1
- full envelope integration  
- redesigned user interface  
- multi‑secret support  

### Version 2.2
- local API  
- automated security tests  

### Version 3.0
- full modularization  
- integration with Krunixbase Ecosystem Dashboard  

---

## 📄 License

Open‑source project. License will be defined in a later stage.

---

## 📝 Status

Actively maintained and under continuous development.

---

## 📬 Contact

Krunixbase Ecosystem Project.
