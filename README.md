# ForNewFolder

React + TypeScript + Tailwind CSS + Vite Starter Project  
สำหรับพัฒนาเว็บแอปและพร้อม deploy ขึ้น **Vercel**

---

## 🚀 Stack ที่ใช้

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

---

## 📦 ติดตั้งโปรเจกต์

1. ดาวน์โหลดหรือ clone โปรเจกต์นี้
2. ติดตั้ง dependencies

```bash
npm install
```

---

## 💻 รันโปรเจกต์แบบ local

```bash
npm run dev
```

- เปิดเว็บเบราว์เซอร์ที่ `http://localhost:5173` (หรือพอร์ตอื่นที่แสดงใน terminal)

---

## 🛠️ โครงสร้างโฟลเดอร์

```
ProjectPi3/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Admin/
│   │   ├── Contact/
│   │   └── ...
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── public/
├── index.html
├── package.json
├── vite.config.ts
├── tailwind.config.js
├── postcss.config.js
├── tsconfig.json
└── .gitattributes
```

---

## 🌐 Deploy ขึ้น Vercel

1. [สมัคร / ล็อกอิน Vercel](https://vercel.com/)
2. คลิก **"New Project"** แล้วเชื่อมต่อกับ GitHub repo นี้
3. ตรวจสอบว่า build command และ output directory ถูกต้อง:

```txt
Build Command: npm run build
Output Directory: dist
```

4. คลิก Deploy 🎉

---

## ⚙️ คำสั่ง NPM อื่น ๆ

| คำสั่ง | ใช้ทำอะไร |
|--------|------------|
| `npm run dev` | รันเซิร์ฟเวอร์ development |
| `npm run build` | สร้าง production build |
| `npm run preview` | รัน preview แบบ production (หลัง build แล้ว) |

---

## 🧹 การตั้งค่ากับ Git บน Windows

เพื่อป้องกันปัญหา CRLF/LF:

```bash
git config --global core.autocrlf true
```

และ `.gitattributes` จะควบคุม line endings อัตโนมัติ

---

## 📝 License

MIT
