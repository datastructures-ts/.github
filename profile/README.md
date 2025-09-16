# 📚 Data Structures in TypeScript

Welcome to **datastructures-ts** — a collection of classic and advanced **data structures implemented in TypeScript**.  
Our goal is to provide **well-typed, reusable, and documented** implementations that are easy to use in learning, teaching, and production projects.

---

## 🎯 Motivation
- Build a modern TypeScript equivalent of [datastructures-js](https://github.com/datastructures-js).  
- Ensure **type safety** with generics, strict null handling, and clean APIs.  
- Provide **educational value** through examples and tests.  
- Make it easy to use data structures in real-world TypeScript projects.

---

## 🗂️ Structure of the Organization
Each repository contains **one data structure** (or a small group of related ones), for example:

- [queue](https://github.com/datastructures-ts/queue)
- [stack](https://github.com/datastructures-ts/stack)
- [priority-queue](https://github.com/datastructures-ts/priority-queue)
- linked-list  
- hash-map  
- graph  
- trie  
- tree variants (BST, AVL, Red-Black, etc.)  

This modular approach keeps each package small, focused, and easy to consume.

---


## 📦 Installation
Each data structure is published as a separate npm package under the scope `@datastructures-ts`. Example:

```bash
pnpm add @datastructures-ts/queue
```

Then import in your code:

```ts
import { Queue } from "@datastructures-ts/queue";

const q = new Queue<number>();
q.enqueue(1);
q.enqueue(2);
console.log(q.dequeue()); // 1
```
---

## 🧪 Testing

Every repo uses Vitest for unit testing. To run tests locally:

```
pnpm install
pnpm test
```
---

## 🛠️ Contributing

We welcome contributions!

Pick a data structure that isn’t implemented yet (or improve an existing one).

Follow the established TypeScript + strict linting + Vitest testing conventions.

Open a PR with clear explanations and examples.

See the CONTRIBUTING.md

---

## 📜 License

MIT License – free to use and share.
