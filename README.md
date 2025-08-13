# Step-by-Step Directions for Creating a Next.js App

This guide walks you through creating a basic **Next.js** application using JavaScript and Tailwind CSS.

---

## 📋 Prerequisites

Make sure you have these installed **before** starting:

1. [Node.js (includes npm)](https://nodejs.org/) — **LTS version recommended**  
   - Check installation:  
     ```bash
     node -v
     npm -v
     ```

2. [Git](https://git-scm.com/downloads) — for version control  
   - Check installation:  
     ```bash
     git --version
     ```

3. A GitHub account — [Sign up here](https://github.com/join)  

4. A code editor such as [Visual Studio Code](https://code.visualstudio.com/)

---

## 🚀 Initialize Your Next.js App

1. **Open your terminal** in the folder where you want your project.  
2. Run:
   ```bash
   npx create-next-app@latest
   ```

---

## ⚙️ Configure the Setup

When prompted, use these settings:

1. **TypeScript** → **NO** (For simplicity, use JavaScript)  
2. **ESLint** → **YES** (Helps catch coding errors)  
3. **Tailwind CSS** → **YES** (For styling)  
4. **src/** folder → **NO** (Simpler structure for beginners)  
5. **App Router** → **YES** (Latest routing system)  
6. **TurboPack** → **YES** (Faster builds)  
7. **Customize import alias** → **NO**

---

## 📂 Navigate into the New Project Folder

```bash
cd [foldername]
```

Replace `[foldername]` with the name you chose during setup.

---

## ▶️ Start the Development Server

```bash
npm run dev
```

Your app will now be running at:  
[http://localhost:3000](http://localhost:3000)

---

## 🎯 What’s Next?

- Edit `app/page.js` (or `pages/index.js` in older versions) and save — the browser will update automatically.  
- Learn more from the official [Next.js Documentation](https://nextjs.org/docs).  
- For Tailwind CSS styling tips, visit [Tailwind Docs](https://tailwindcss.com/docs).

---
