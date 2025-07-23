# 🎬 Movie Explorer

A modern and responsive **movie browsing website** built with **Next.js** and **Tailwind CSS**.  
It uses **Server-Side Rendering (SSR)** for optimal SEO and performance, **lazy loads images** to improve initial load time, and includes **pagination** to navigate through movies efficiently.

---

## 🔗 Live Demo

👉 [View Live Website](https://hianime7.netlify.app/)

> 🚨 If the live site is unavailable, check the [GitHub repository](https://github.com/Abhiishek-Choudhary/Hianime) and run it locally using the instructions below.
> you cannot see the movies here I just created it for learning nextjs it's just the implementation of next js with some featured libraries.

---

## ⚙️ Tech Stack

- ⚡ **Next.js** (App Router or Pages Router)
- 🎨 **Tailwind CSS** – Rapid utility-first UI styling
- 🌐 **Server-Side Rendering (SSR)** – For better SEO and faster first paint
- 🖼️ **Image Lazy Loading** – Optimized image loading using Next.js `Image` component
- 🔄 **Pagination** – Navigate through movie listings
- 🎞️ **TMDb API** or any custom movie API

---

## ✨ Features

- 🔍 Browse latest/popular/top-rated movies
- 🧠 **SSR-enabled pages** for SEO-friendly metadata and fast loading
- 🖼️ Optimized, **lazy-loaded movie posters**
- ⏩ **Pagination** support for smooth navigation
- 🎥 Click any movie to view details, cast, release date, and overview
- 📱 Fully responsive and mobile-first layout

---

## 🚀 Getting Started Locally

### 1. Clone the repository

```bash
git clone https://github.com/Abhiishek-Choudhary/Hianime.git
cd movie-app

2. Install dependencies
bash
npm install

3. Set up environment variables
Create a .env.local file at the root with your movie API key:
Edit
NEXT_PUBLIC_TMDB_API_KEY=your_tmdb_api_key
You can get a free API key from https://www.themoviedb.org.

4. Run the development server
bash
npm run dev
Open http://localhost:3000 in your browser.

📁 Folder Structure (Simplified)

movie-app/
├── public/
├── src/
│   ├── pages/             # or app/ if using App Router
│   ├── components/
│   ├── hooks/
│   ├── lib/               # API fetch utilities
│   └── styles/
├── .env.local
├── tailwind.config.js
└── next.config.js
🧠 Key Implementation Details
✅ Server-Side Rendering (SSR)
Movie data is fetched on the server using getServerSideProps() (or generateMetadata() + fetch() if using App Router), ensuring search engines can crawl dynamic content.

🖼️ Lazy Loading
Poster images use Next.js <Image /> with built-in lazy loading and optimization:
tsx
<Image
  src={movie.poster_path}
  alt={movie.title}
  width={300}
  height={450}
  loading="lazy"
/>


📄 Pagination
Each page displays a limited number of movies. Pagination is handled via query parameters like:
bash
/movies?page=2


📬 Contact
📧 Email: akc64016@gmail.com

🐙 GitHub: @Abhiishek-Choudhary

🔗 LinkedIn: https://www.linkedin.com/in/abhishek-chaudhary-2b276324b/

