## This is an unofficial wrapper around Deepseek

---

## Build & Run Instructions

1. **Install dependencies**

   Using npm:
   ```sh
   npm install
   ```

2. **Build the app**

   ```sh
   npm run build
   ```
   This will compile the TypeScript and package the Electron app.

3. **Run the app in development**

   ```sh
   npm start
   ```

---

### Troubleshooting
- If you encounter errors related to missing modules, try deleting `node_modules`, `package-lock.json`, and `bun.lock`, then run `npm install` again.
- Make sure you are using a compatible Node.js version (LTS recommended).
- For issues with Electron or native dependencies, try running:
  ```sh
  npm rebuild
  ```

---