<!----------------------------------------------------------------------------->
<!--  HERO — Full-width waving banner                                         -->
<!----------------------------------------------------------------------------->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0720,20:1e0a45,55:4c1d95,85:7c3aed,100:a78bfa&height=280&section=header&text=VisualMatch%20AI&fontSize=72&fontColor=ede9fe&fontAlignY=38&fontStyle=bold&desc=AI-Powered%20Visual%20Search%20for%20E-commerce%20and%20Product%20Discovery&descAlignY=60&descSize=17&descColor=c4b5fd&animation=fadeIn" width="100%"/>

</div>

<!----------------------------------------------------------------------------->
<!--  BADGES                                                                  -->
<!----------------------------------------------------------------------------->

<div align="center">

<br/>

[![React](https://img.shields.io/badge/React-18.x-0f0829?style=for-the-badge&logo=react&logoColor=a78bfa&labelColor=0a0520&color=0f0829)](https://reactjs.org/)&nbsp;
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict-0f0829?style=for-the-badge&logo=typescript&logoColor=c4b5fd&labelColor=0a0520&color=0f0829)](https://www.typescriptlang.org/)&nbsp;
[![CLIP](https://img.shields.io/badge/AI%20Model-CLIP%20ViT--B%2F32-0f0829?style=for-the-badge&logo=openai&logoColor=ddd6fe&labelColor=0a0520&color=0f0829)](https://huggingface.co/sentence-transformers/clip-ViT-B-32)&nbsp;
[![Gradio](https://img.shields.io/badge/Backend-Gradio%205.49.1-0f0829?style=for-the-badge&logo=python&logoColor=c4b5fd&labelColor=0a0520&color=0f0829)](https://www.gradio.app/)&nbsp;
[![Tailwind](https://img.shields.io/badge/Styling-Tailwind%20CSS-0f0829?style=for-the-badge&logo=tailwindcss&logoColor=a5f3fc&labelColor=0a0520&color=0f0829)](https://tailwindcss.com/)&nbsp;
[![Framer](https://img.shields.io/badge/Animation-Framer%20Motion-0f0829?style=for-the-badge&logo=framer&logoColor=e879f9&labelColor=0a0520&color=0f0829)](https://www.framer.com/motion/)&nbsp;
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20Spaces-Live-0f0829?style=for-the-badge&logoColor=fbbf24&labelColor=0a0520&color=0f0829)](https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher-frontend)

<br/><br/>

*Upload an image &nbsp;·&nbsp; Discover similar products instantly &nbsp;·&nbsp; Powered by semantic CLIP embeddings*

<br/><br/>

</div>

<!----------------------------------------------------------------------------->
<!--  STATS STRIP                                                             -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0520,100:160835&height=90&text=Dual%20Search%20Modes%20%C2%B7%20Sub-500ms%20Store%20Queries%20%C2%B7%20CLIP%20512D%20Embeddings%20%C2%B7%20Framer%20Motion%20UI&fontSize=14&fontColor=c4b5fd&fontAlignY=35&desc=React%20%2B%20TypeScript%20frontend%20%E2%80%94%20Gradio%205.49.1%20backend%20%E2%80%94%20deployed%20on%20Hugging%20Face%20Spaces&descSize=13&descColor=ede9fe&descAlignY=68" width="100%"/>

<br/><br/>

<!----------------------------------------------------------------------------->
<!--  AT A GLANCE                                                             -->
<!----------------------------------------------------------------------------->

<div align="center">

### 📊 &nbsp;At a Glance

| 🎨 Frontend | 🤖 AI Model | 📐 Embedding Dim | 🔍 Search Modes | ⚡ Store Latency | 📦 Catalog |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **React + TypeScript + Tailwind + Framer Motion** | **clip-ViT-B-32 (SentenceTransformers)** | **512D** | **Store + Web (SerpAPI)** | **100–500ms** | **50 Products** |

</div>

<br/><br/>

<!----------------------------------------------------------------------------->
<!--  LIVE LINKS                                                              -->
<!----------------------------------------------------------------------------->

<div align="center">

### 🚀 &nbsp;Access the Application

| Component | Purpose | Link |
|:---:|:---|:---:|
| **🎨 Frontend** | Interactive React UI — Upload, search, view results | [Launch Frontend](https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher-frontend) |
| **⚙️ Backend** | Gradio API — CLIP inference, SerpAPI, vector search | [View Backend](https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher) |
| **👤 HF Profile** | All spaces by kumarpiyushraj | [Visit Profile](https://huggingface.co/kumarpiyushraj) |

</div>

<br/><br/>

<!----------------------------------------------------------------------------->
<!--  TABLE OF CONTENTS                                                       -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a0840,100:0a0520&height=64&text=%F0%9F%93%8B%20%20Table%20of%20Contents&fontSize=22&fontColor=ede9fe&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

<div align="center">

| # | Section | # | Section |
|:---:|:---|:---:|:---|
| 01 | <a href="#overview">🔍 Project Overview</a> | 07 | <a href="#frontend-deep-dive">🎨 Frontend Deep Dive</a> |
| 02 | <a href="#architecture">🏗️ System Architecture</a> | 08 | <a href="#backend-deep-dive">⚙️ Backend Deep Dive</a> |
| 03 | <a href="#store-mode">🏪 Store Discovery Mode</a> | 09 | <a href="#api-docs">📚 API Documentation</a> |
| 04 | <a href="#web-mode">🌍 Web Exploration Mode</a> | 10 | <a href="#performance">⚡ Performance</a> |
| 05 | <a href="#tech-stack">🛠️ Technology Stack</a> | 11 | <a href="#quickstart">🚀 Quick Start</a> |
| 06 | <a href="#ui-components">🧩 UI Component System</a> | 12 | <a href="#future">🔮 Future Enhancements</a> |

</div>

<br/><br/>

<a name="overview"></a>
<!----------------------------------------------------------------------------->
<!--  PROJECT OVERVIEW                                                        -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1e0a45,100:0a0520&height=64&text=%F0%9F%94%8D%20%20Project%20Overview&fontSize=22&fontColor=c4b5fd&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

**VisualMatch AI** is a production-ready **AI-powered visual search platform** built in TypeScript (frontend) and Python (backend). Users upload any product image or paste a URL to get the top 10 visually similar matches from a curated 50-product catalog, powered by **CLIP ViT-B/32** semantic embeddings via `sentence-transformers`. A second mode offers **Google reverse image search** via SerpAPI for open-web discovery.

The frontend (`App.tsx`) is a fully typed React 18 SPA featuring animated blob backgrounds, glassmorphism panels, dual progress-bar tracking, a result sort system (`relevance`, `name_asc`, `name_desc`, `date_desc`), and an `AnimatePresence` modal — all driven by Framer Motion. The backend (`app.py`) is a queued Gradio 5.49.1 application exposing two named API endpoints consumed via the `@gradio/client` SDK.

<br/>

<div align="center">

| &nbsp; | What makes it different? | How it achieves it |
|:---:|:---|:---|
| 🎨 | **Production-Grade Animated UI** | Framer Motion blob backgrounds, glassmorphism, staggered grid reveal, dual progress bars, spring `AnimatePresence` modals |
| 🧠 | **Semantic Visual Understanding** | `SentenceTransformer("clip-ViT-B-32")` — 512D embeddings capture concept, not pixel distance |
| ⚡ | **Pre-Computed Vector DB** | 50 product vectors in `product_vectors.json` loaded into a NumPy `(50, 512)` matrix at startup |
| 🔀 | **Dual Search Modes** | Store Discovery (catalog cosine similarity) and Web Exploration (SerpAPI `google_reverse_image`) |
| 🔌 | **@gradio/client SDK** | `client("kumarpiyushraj/visual-product-matcher").predict("/store_search", [...])` — no custom proxy layer |
| 🗂️ | **Client-Side Sort** | `useMemo` re-sorts `normalizedResults` by `sortBy` state — zero extra network calls |

</div>

<br/><br/>

<a name="architecture"></a>
<!----------------------------------------------------------------------------->
<!--  SYSTEM ARCHITECTURE                                                     -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:200d47,100:0d0527&height=64&text=%F0%9F%8F%97%EF%B8%8F%20%20System%20Architecture&fontSize=22&fontColor=ddd6fe&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

```
┌────────────────────────────────────────────────────────────────────────────┐
│           LAYER 1 — REACT + TYPESCRIPT FRONTEND  (App.tsx)                 │
│                                                                            │
│  Background: indigo/violet/fuchsia animated blobs (CSS blob keyframes)    │
│                                                                            │
│  ┌─────────────┐  ┌──────────────────┐  ┌──────────────┐  ┌───────────┐  │
│  │ Mode Toggle  │  │   InputPanel     │  │ ResultsGrid  │  │   Modal   │  │
│  │ Store / Web  │  │ File + URL input │  │ Sorted Cards │  │ Crop UI   │  │
│  │ layoutId tab │  │ validateImageUrl │  │ sortedResults│  │ AnimPres. │  │
│  └──────┬───────┘  └──────┬───────────┘  └──────┬───────┘  └─────┬─────┘  │
│         └─────────────────┴──────────────────────┴─────────────────┘       │
│                                        │                                   │
│   useState · useMemo · useRef · useEffect · AnimatePresence                │
│   Framer Motion · Tailwind CSS (Inter font) · @gradio/client               │
└────────────────────────────────────────┬───────────────────────────────────┘
                                         │
                 gradioApp.predict("/store_search" | "/web_search")
                         via @gradio/client SDK
                                         │
┌────────────────────────────────────────▼───────────────────────────────────┐
│           LAYER 2 — GRADIO 5.49.1 BACKEND  (app.py)                       │
│                          demo.queue().launch()                             │
│                                                                            │
│  ┌───────────────────────────────┐  ┌──────────────────────────────────┐  │
│  │  api_name="store_search"      │  │  api_name="web_search"           │  │
│  │  find_matches_in_store()      │  │  find_matches_on_web()           │  │
│  │  ─────────────────────────    │  │  ──────────────────────────────  │  │
│  │  _get_bytes_from_input()      │  │  search_serpapi(image_url, 10)   │  │
│  │  PIL open → RGB               │  │  engine="google_reverse_image"   │  │
│  │  thumbnail(320, 320)          │  │  timeout=10s                     │  │
│  │  model.encode(img) → 512D     │  │  parse image_results[]           │  │
│  │  cosine_similarity()          │  │  → title · link · thumbnail      │  │
│  │  sort desc → top 10           │  └──────────────┬───────────────────┘  │
│  └──────────────┬────────────────┘                  │                      │
│                 │                              ┌─────▼──────┐              │
│  ┌──────────────▼────────────────┐            │   SerpAPI  │              │
│  │  NumPy matrix (50 x 512)      │            │  (Google)  │              │
│  │  from product_vectors.json    │            └────────────┘              │
│  │  loaded once at startup       │                                         │
│  └──────────────┬────────────────┘                                         │
│                 │                                                           │
│  ┌──────────────▼────────────────┐                                         │
│  │  clip-ViT-B-32                │                                         │
│  │  SentenceTransformer (CPU)    │                                         │
│  │  torch.set_num_threads(1)     │                                         │
│  └───────────────────────────────┘                                         │
└────────────────────────────────────────────────────────────────────────────┘
         │                                    │
    ┌────▼───────────────────┐    ┌───────────▼─────────────┐
    │  HF Spaces (static)    │    │  HF Spaces (Gradio SDK) │
    │  sdk: static 1.0       │    │  sdk_version: 5.49.1    │
    │  Frontend Space        │    │  app_file: app.py       │
    └────────────────────────┘    └─────────────────────────┘
```

<br/><br/>

<a name="store-mode"></a>
<!----------------------------------------------------------------------------->
<!--  STORE DISCOVERY MODE                                                    -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:25104f,100:0e0628&height=64&text=%F0%9F%8F%AA%20%20Store%20Discovery%20Mode&fontSize=22&fontColor=a78bfa&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

Store Discovery is the primary search mode. The user uploads a file or pastes an image URL. The frontend validates it client-side (MIME type, file size, pixel dimensions, URL reachability), then calls the Gradio backend via `@gradio/client`. The backend computes a 512D CLIP embedding and ranks all 50 preloaded product vectors by cosine similarity, returning the top 10 with scores.

<br/>

### 🔄 Store Search — Full Frontend-to-Backend Flow

```
User selects file or pastes URL
          │
          ▼
┌─────────────────────────────────────────────────────────────────────────┐
│  handleFileChange() / handleStoreUrlChange()                            │
│  → MIME: image/jpeg · image/png · image/webp only                      │
│  → Size: file.size > 10 * 1024 * 1024 → reject                        │
│  → Dimensions: naturalWidth/Height > 4000 → reject                    │
│  → URL: validateImageUrl() via new Image().onload / onerror            │
│  → uploadProgress: 0 → 30 → 100  (animated h-3 progress bar)          │
│  → setTimeout 1000ms → reset uploadProgress to 0                      │
└──────────────────────────────┬──────────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────────┐
│  handleSearch()                                                         │
│  → setSearchProgress(20)                                               │
│  → setInterval: +10 every 500ms, capped at 90                         │
│  → const gradioApp = await client("kumarpiyushraj/visual-product-matcher")
│  → grResult = await gradioApp.predict("/store_search", [file, storeUrl])│
│  → clearInterval → setSearchProgress(100) → reset after 1000ms        │
└──────────────────────────────┬──────────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────────┐
│  find_matches_in_store(image_file, image_url) — app.py                 │
│  → _get_bytes_from_input(): handles dict/str/file-like/.name/bytes     │
│  → pil_open_from_bytes(): Image.open → .convert("RGB") → .thumbnail(320,320)
│  → model.encode(img, convert_to_numpy=True).reshape(1, -1) → 512D     │
│  → cosine_similarity(user_vector, vector_matrix)[0] → scores (50,)    │
│  → sort by score desc → top 10 → return gr.JSON(value=results)        │
└──────────────────────────────┬──────────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────────┐
│  parseGradioResultByMode(grResult, "store")                             │
│  → normalizeStoreItem(): extract product.name, imagePath, score        │
│  → normalizeImageUrl(): window.location.origin + /images/ + filename   │
│  → useMemo sortedResults: sort by sortBy state (relevance/name/date)   │
│  → Framer Motion staggered grid: staggerChildren 0.05s, whileHover y:-8│
└─────────────────────────────────────────────────────────────────────────┘
```

<br/>

<div align="center">

| Parameter | Value | Source |
|:---|:---:|:---:|
| **Model** | `SentenceTransformer("clip-ViT-B-32", device="cpu")` | `app.py` |
| **CPU Threading** | `torch.set_num_threads(1)` | `app.py` |
| **Embedding Dimension** | **512** | `product_vectors.json` |
| **Image Resize** | `img.thumbnail((320, 320))` | `pil_open_from_bytes()` |
| **Colour Space** | `.convert("RGB")` | `pil_open_from_bytes()` |
| **Similarity Metric** | `cosine_similarity` (scikit-learn) | `find_matches_in_store()` |
| **Results Returned** | Top **10** | `[:10]` slice after sort |
| **Max File Size** | **10 MB** | `handleFileChange()` |
| **Max Dimensions** | **4000 × 4000 px** | `handleFileChange()` |
| **Accepted Formats** | `image/jpeg` · `image/png` · `image/webp` | `handleFileChange()` accept attr |

</div>

<br/><br/>

<a name="web-mode"></a>
<!----------------------------------------------------------------------------->
<!--  WEB EXPLORATION MODE                                                    -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2a1060,100:100530&height=64&text=%F0%9F%8C%8D%20%20Web%20Exploration%20Mode&fontSize=22&fontColor=ddd6fe&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

Web Exploration mode sends a direct image URL to the backend which forwards it to the **SerpAPI Google Reverse Image Search** engine (`engine: "google_reverse_image"`). Results include titles, source links, and thumbnails. In the frontend, web-mode cards show a `View ↗` fuchsia external link instead of a percentage match badge.

<br/>

### 🔄 Web Search Flow

```
User pastes direct image URL into Web Exploration input
          │
          ▼
┌─────────────────────────────────────────────────────────────────────────┐
│  handleWebUrlChange()                                                   │
│  → validateImageUrl() → new Image() onload/onerror                     │
│  → If valid: setPreview(url) — live preview rendered                   │
│  → If invalid: setInputError("Invalid image URL. Please check...")     │
└──────────────────────────────┬──────────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────────┐
│  handleSearch()                                                         │
│  → grResult = await gradioApp.predict("/web_search", [webUrl])         │
└──────────────────────────────┬──────────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────────┐
│  find_matches_on_web(image_url) — app.py                               │
│  → search_serpapi(image_url, num_results=10)                           │
│  → GET https://serpapi.com/search                                      │
│     params: engine="google_reverse_image" · image_url · api_key · num=10
│     timeout: 10s                                                       │
│  → parse data["image_results"] → filter items with thumbnail          │
│  → return: [{title, link, thumbnail}, ...]                             │
└──────────────────────────────┬──────────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────────┐
│  parseGradioResultByMode(grResult, "web")                               │
│  → extracts first.results array                                        │
│  → normalizeWebItem(): title · image (thumbnail) · link                │
│  → Cards show: thumbnail + title + "View ↗" (fuchsia, target="_blank")│
└─────────────────────────────────────────────────────────────────────────┘
```

<br/>

> 📌 **Requirements:** `SERPAPI_KEY` must be set as an HF Space secret or `.env` variable. Web mode requires a URL that resolves directly to an image file. SerpAPI roundtrip is ~1–3s with a 10s hard timeout.

<br/><br/>

<a name="tech-stack"></a>
<!----------------------------------------------------------------------------->
<!--  TECHNOLOGY STACK                                                        -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1f0d4a,100:0c0426&height=64&text=%F0%9F%9B%A0%EF%B8%8F%20%20Technology%20Stack&fontSize=22&fontColor=c4b5fd&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

### 🎨 Frontend Technologies

<div align="center">

| Category | Technology | Details — verified from source files |
|:---|:---|:---|
| **Language** | TypeScript (strict) | `App.tsx` — types: `Product`, `RawResultItem`, `NormalizedResult` |
| **Framework** | React 18 | Hooks: `useState`, `useMemo`, `useRef`, `useEffect` |
| **Entry Point** | `main.jsx` | `createRoot(getElementById("root")).render(<App/>)` |
| **Styling** | Tailwind CSS | `@import "tailwindcss"` in `input.css` · body gradient `#071029 → #0b1220` |
| **Font** | Inter | `font-family: "Inter", ui-sans-serif, system-ui` — `input.css` |
| **Animation** | Framer Motion | `motion`, `AnimatePresence`, `layoutId="activeMode"` for tab transitions |
| **Backend Client** | `@gradio/client` | `client("kumarpiyushraj/visual-product-matcher").predict()` |
| **Image Handling** | HTML File API | `FileReader`, `URL.createObjectURL`, `URL.revokeObjectURL` on cleanup |
| **URL Validation** | Native `Image()` API | `new Image()` `.onload` / `.onerror` — no library dependency |
| **Deployment** | HF Spaces (static SDK) | `sdk: static`, `sdk_version: '1.0'` |

</div>

<br/>

### ⚙️ Backend Technologies

<div align="center">

| Category | Technology | Details — verified from `app.py` and `requirements.txt` |
|:---|:---|:---|
| **Framework** | Gradio 5.49.1 | `gr.Blocks` + `demo.queue().launch()` · two `api_name` endpoints |
| **AI Model** | `clip-ViT-B-32` | `SentenceTransformer("clip-ViT-B-32", device="cpu")` |
| **CPU Optimization** | PyTorch | `torch.set_num_threads(1)` — single-thread inference |
| **Image Processing** | Pillow (PIL) | `.convert("RGB")` + `.thumbnail((320, 320))` |
| **Similarity** | scikit-learn | `cosine_similarity(user_vector, vector_matrix)[0]` |
| **Vector Matrix** | NumPy | Shape `(50, 512)` — built once at startup from JSON |
| **Web Search** | SerpAPI + Requests | `engine="google_reverse_image"` · timeout=10 · filters by `thumbnail` |
| **Data Files** | JSON | `products.json` (50 products) · `product_vectors.json` (50 × 512D) |
| **Input Handler** | `_get_bytes_from_input()` | Handles: dict/base64, str path, `.read()`, `.name`, raw bytes |
| **Secrets** | python-dotenv | `load_dotenv()` → `SERPAPI_KEY = os.getenv("SERPAPI_KEY")` |
| **Preprocessing** | `index.py` | One-time: CLIP encodes `public/images/` → writes `product_vectors.json` |
| **Deployment** | HF Spaces (Gradio SDK) | `sdk: gradio`, `sdk_version: 5.49.1`, `app_file: app.py` |

</div>

<br/><br/>

<a name="ui-components"></a>
<!----------------------------------------------------------------------------->
<!--  UI COMPONENT SYSTEM                                                     -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2c1265,100:110630&height=64&text=%F0%9F%A7%A9%20%20UI%20Component%20System&fontSize=22&fontColor=a78bfa&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

All components are co-located in `App.tsx`. The architecture is intentionally flat — no component sub-files — with clean TypeScript types, isolated state, and all animation variants defined inline as Framer Motion props.

<br/>

### 🌀 Animated Blob Background

Three blurred circles behind all content create a layered ambient glow using `mix-blend-multiply` and a custom `blob` CSS keyframe:

```tsx
// From App.tsx lines 452–455
<div className="absolute -top-40 -right-40 w-80 h-80 bg-indigo-600 rounded-full
  mix-blend-multiply filter blur-3xl opacity-18 animate-blob"/>
<div className="absolute -bottom-40 -left-40 w-80 h-80 bg-violet-600 rounded-full
  mix-blend-multiply filter blur-3xl opacity-16 animate-blob animation-delay-2000"/>
<div className="absolute top-40 left-40 w-80 h-80 bg-fuchsia-600 rounded-full
  mix-blend-multiply filter blur-3xl opacity-14 animate-blob animation-delay-4000"/>
```

```css
/* Defined inline at bottom of App.tsx */
@keyframes blob {
  0%, 100% { transform: translate(0, 0) scale(1); }
  33%       { transform: translate(30px, -50px) scale(1.1); }
  66%       { transform: translate(-20px, 20px) scale(0.9); }
}
.animate-blob { animation: blob 7s infinite; }
.animation-delay-2000 { animation-delay: 2s; }
.animation-delay-4000 { animation-delay: 4s; }
```

<br/>

### 🔘 Mode Toggle — `layoutId` Animated Tab Switcher

`layoutId="activeMode"` lets Framer Motion animate the active background pill between tabs via a spring transition — no manual position calculation:

```tsx
// Store tab — blue-500 to indigo-600
{searchMode === "store" && (
  <motion.div layoutId="activeMode"
    className="absolute inset-0 bg-gradient-to-r from-blue-500 to-indigo-600 rounded-xl"
    transition={{ type: "spring", damping: 20 }}/>
)}
// Web tab — indigo-500 to violet-600
{searchMode === "web" && (
  <motion.div layoutId="activeMode"
    className="absolute inset-0 bg-gradient-to-r from-indigo-500 to-violet-600 rounded-xl"
    transition={{ type: "spring", damping: 20 }}/>
)}
```

`switchMode()` resets all 11 state variables: `storeFile`, `storeUrl`, `webUrl`, `preview`, `results`, `error`, `inputError`, `selectedProduct`, `showModal`, `uploadProgress`, `searchProgress`, `sortBy`.

<br/>

### 📂 File Upload Zone

```
┌─────────────────────────────────────────────────────────────────────────┐
│  motion.label (htmlFor="file-upload") — dashed border, hover glow      │
│                                                                         │
│  ┌───────────────────────────────────────────────────────────────────┐  │
│  │  ✨ icon (whileHover: rotate 15°)                                  │  │
│  │  Text: storeFile ? storeFile.name : "Drop your image here"         │  │
│  │  Sub:  "JPG, PNG, WebP • Maximum 10MB"                            │  │
│  │  Hover overlay: bg-gradient indigo/violet opacity 0 → 100%        │  │
│  └───────────────────────────────────────────────────────────────────┘  │
│                                                                         │
│  Hidden <input type="file" id="file-upload"                            │
│    accept="image/jpeg,image/png,image/webp"                            │
│    onChange={handleFileChange} />                                       │
│                                                                         │
│  URL input: placeholder "Or paste an image URL..."  🔗                │
│  Web input: placeholder "Enter image URL for web search..."  🌍        │
└─────────────────────────────────────────────────────────────────────────┘
```

<br/>

### ⏳ Dual Progress Bar System

Two independent progress systems with distinct visual feedback:

```tsx
// Upload bar (h-3, indigo-500 to fuchsia-500) — triggered by handleFileChange
//   0 → 30 (on file selected) → 100 (on Image.onload) → reset after 1000ms

// Search bar (h-2, indigo-500 via violet-500 to fuchsia-500) — triggered by handleSearch
//   20 (on search start) → +10 every 500ms capped at 90 → 100 (on response)
//   Shows text: "AI analyzing visual patterns... {searchProgress}%"
//   → reset after 1000ms timeout
```

<br/>

### 🌀 `LoadingSpinner` — Multi-Layer Spinner

Custom 4-layer spinner rendered while `isLoading === true`:

```
Layer 1 (outermost): blur-xl glow ring — animate-spin, opacity-75
Layer 2:             solid gradient ring — animate-spin
Layer 3:             white inner mask (inset-2) — backdrop-blur-sm
Layer 4 (core):      gradient dot (inset-4) — animate-pulse
Label: "Discovering Visual Matches..." (gradient text, fades in with delay 0.2s)
```

<br/>

### 📋 `SkeletonLoader` — 10 Placeholder Cards

Rendered with staggered entry (`delay: i * 0.05`) — exactly matches `ProductCard` dimensions to prevent layout shift:

```tsx
<div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-4">
  {[...Array(10)].map((_, i) => (
    <motion.div key={i} initial={{opacity:0,y:20}} animate={{opacity:1,y:0}}
      transition={{delay: i * 0.05}}>
      <div className="bg-gradient-to-br from-gray-100 to-gray-200 rounded-xl animate-pulse">
        <div className="aspect-square bg-gradient-to-br from-gray-200 to-gray-300"/>
        <div className="p-3 space-y-1">
          <div className="h-3 bg-gray-300 rounded-full w-3/4"/>
          <div className="h-2.5 bg-gray-300 rounded-full w-1/2"/>
        </div>
      </div>
    </motion.div>
  ))}
</div>
```

<br/>

### 🃏 ProductCard — Result Display Unit

```
Responsive grid: grid-cols-1 sm:2 md:3 lg:4 xl:5 · gap-4
Stagger:  variants { hidden:{y:30,opacity:0}, visible:{y:0,opacity:1} }
          container staggerChildren: 0.05s
Hover:    whileHover={{ y: -8, transition: { duration: 0.3 } }}

Card internals:
  ┌─────────────────────────────────────────────┐
  │ aspect-square image                         │
  │   object-cover · group-hover:scale-110      │
  │   gradient overlay (from-black/60) on hover │
  │   ↗ icon button (top-right, hover only)     │
  ├─────────────────────────────────────────────┤
  │ p-3 info area                               │
  │   Product name (line-clamp-2, text-sm)      │
  │   [Store] % Match badge — from-indigo-500   │
  │            to-fuchsia-500 rounded-full      │
  │   [Web]   "View ↗" — fuchsia-400 text      │
  │            target="_blank" external link    │
  └─────────────────────────────────────────────┘
Clicking card (store mode): openProductModal(item.product)
```

<br/>

### ↕️ Sort Controls

When `results.length > 0`, a row appears with a match count pill and sort dropdown:

```tsx
<select value={sortBy} onChange={...} className="bg-gray-800/50 border border-white/30 ...">
  <option value="relevance">Relevance</option>    // score × 100 desc (store) / original (web)
  <option value="name_asc">Name A-Z</option>      // a.title.localeCompare(b.title)
  <option value="name_desc">Name Z-A</option>     // b.title.localeCompare(a.title)
  <option value="date_desc">Date (Newest)</option> // product.created_at || fallback to title
</select>
// select option background: #1f2937 (defined in inline style block)
```

<br/>

### 🪟 Detail Modal — Product Crop View

Opens via `AnimatePresence` when a store result card is clicked:

```tsx
// Backdrop: bg-black/80 backdrop-blur-md, onClick → closeProductModal
// Panel:    from-slate-900 via-indigo-900 to-slate-900, border border-white/12
//           initial: scale 0.9 opacity 0 → animate: scale 1 opacity 1
//           exit:    scale 0.9 opacity 0
//           transition: type "spring", damping 25
// Close:    ✕ button — whileHover: { rotate: 90, scale: 1.1 }
// Image:    w-full h-64 object-contain
// Crop btn: "✂️ Crop Image" → handleCrop() [currently alert simulation]
// Cancel:   closeProductModal()
```

<br/>

### 🦶 Footer

Three-column animated grid (`delay: 0.1 / 0.2 / 0.3`):

- **About** — "Next-generation visual search powered by cutting-edge AI technology. Discover products instantly with unmatched accuracy."
- **Features** — ✓ AI-Powered Visual Recognition (indigo-400) · ✓ Real-time Web Search Integration (violet-400) · ✓ Enterprise-Ready Architecture (fuchsia-400)
- **Connect** — Four emoji buttons: `🌟 🚀 💡 🎯` — `whileHover: { scale: 1.2, rotate: 15 }`

Tagline: `© 2025 Visual Product Matcher • Powered by Advanced AI` · `Secure • Private • Lightning Fast`

<br/><br/>

<a name="frontend-deep-dive"></a>
<!----------------------------------------------------------------------------->
<!--  FRONTEND DEEP DIVE                                                      -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:300e72,100:120530&height=64&text=%F0%9F%8E%A8%20%20Frontend%20Deep%20Dive&fontSize=22&fontColor=c4b5fd&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

### 🔷 TypeScript Type System

```typescript
// All types defined in App.tsx
type Product = {
  id?: number;
  name?: string;
  imagePath?: string;
  title?: string;
  image?: string;
  [k: string]: any;           // allows extra backend fields
};

type RawResultItem = {
  product?: Product;
  score?: number;             // 0.0–1.0, present in store mode
  title?: string;
  thumbnail?: string;         // present in web mode
  link?: string;
  [k: string]: any;
};

type NormalizedResult = {
  title: string;
  image: string;              // always absolute URL after normalizeImageUrl()
  link?: string;
  score?: number;
  product?: Product;
};
```

<br/>

### 🔗 Image URL Normalization — `normalizeImageUrl()`

Handles all cases: bare filename from `products.json`, root-relative path, full URL, or blob URL from upload:

```typescript
function normalizeImageUrl(src?: string | null): string {
  if (!src) return "/fallback.png";
  if (src.startsWith("http") || src.startsWith("blob:")) return src;
  if (src.startsWith("/")) src = src.slice(1);
  return `${window.location.origin}/images/${src}`;
  // e.g. "product-1.jpg" → "https://<space>/images/product-1.jpg"
}
```

<br/>

### 🔬 `parseGradioResultByMode()` — Response Normalization

Handles multiple Gradio response shapes from `@gradio/client`:

```typescript
function parseGradioResultByMode(grResult: any, mode: "store" | "web"): any[] {
  if (!grResult) return [];
  if (Array.isArray(grResult)) return grResult;
  if (grResult.type === "data" && Array.isArray(grResult.data)) {
    const first = grResult.data[0];
    if (mode === "store" && first?.value) return first.value;
    if (mode === "web" && Array.isArray(first?.results)) return first.results;
  }
  return [grResult];
}
```

<br/>

### 🧹 Memory Management

`useEffect` cleanup revokes blob URLs when `preview` changes — prevents memory leaks from `URL.createObjectURL(file)`:

```typescript
useEffect(() => {
  return () => {
    if (preview?.startsWith("blob:")) URL.revokeObjectURL(preview);
  };
}, [preview]);
```

`clearPreview()` also calls `URL.revokeObjectURL(preview)` directly for immediate cleanup on user dismiss.

<br/>

### ⏱️ Frontend Runtime Breakdown

```
MIME + size validation          ~1ms    synchronous
Dimension check (Image.onload)  ~5ms    async, non-blocking
URL reachability check          ~50ms   network dependent
@gradio/client handshake        ~200ms  WebSocket setup (first call)
gradioApp.predict() roundtrip   100–500ms (store) / 1–3s (web)
parseGradioResultByMode         ~1ms
normalizeStoreItem × 10         ~2ms
useMemo sortedResults           ~1ms
DOM render 10 cards             ~15ms
Stagger animation complete      500ms   10 × 50ms delay
──────────────────────────────────────────────────────────────
Perceived first result visible: < 800ms + backend latency
```

<br/><br/>

<a name="backend-deep-dive"></a>
<!----------------------------------------------------------------------------->
<!--  BACKEND DEEP DIVE                                                       -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2a1060,100:0f0430&height=64&text=%E2%9A%99%EF%B8%8F%20%20Backend%20Deep%20Dive&fontSize=22&fontColor=ddd6fe&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

### 🚀 Startup Sequence

All expensive operations execute **once at boot** — every subsequent query hits in-memory structures only:

```python
# app.py — executed at module load
torch.set_num_threads(1)
model = SentenceTransformer("clip-ViT-B-32", device="cpu")   # ~3–8s on first load

with open("products.json", "r", encoding="utf-8") as f:
    products_data = json.load(f)       # 50 dicts: id, name, category, imagePath

with open("product_vectors.json", "r", encoding="utf-8") as f:
    product_vectors_data = json.load(f)  # 50 × {id, vector[512]}

product_vectors = {int(item["id"]): np.array(item["vector"], dtype=float)
                   for item in product_vectors_data}
product_ids    = list(product_vectors.keys())
vector_matrix  = np.array([product_vectors[pid] for pid in product_ids])
# vector_matrix.shape == (50, 512)
```

<br/>

### 🔐 `_get_bytes_from_input()` — 5-Stage Input Handler

```python
def _get_bytes_from_input(image_file):
    if image_file is None: return None
    # Stage 1: dict with "data" key → base64 payload (custom client)
    if isinstance(image_file, dict) and "data" in image_file:
        return base64.b64decode(image_file["data"])
    # Stage 2: plain string → try filesystem path, then base64 decode
    if isinstance(image_file, str):
        if os.path.exists(image_file):
            with open(image_file, "rb") as f: return f.read()
        try: return base64.b64decode(image_file)
        except: raise ValueError("Not a file path or base64 data.")
    # Stage 3: file-like object with .read()
    if hasattr(image_file, "read"):
        content = image_file.read()
        return content.encode("utf-8") if isinstance(content, str) else content
    # Stage 4: object with .name attribute pointing to filesystem path
    name = getattr(image_file, "name", None)
    if isinstance(name, str) and os.path.exists(name):
        with open(name, "rb") as f: return f.read()
    # Stage 5: last resort — raw bytes()
    try: return bytes(image_file)
    except: raise ValueError(f"Unsupported type: {type(image_file)}")
```

<br/>

### 🧠 `find_matches_in_store()` — Core Inference

```python
def find_matches_in_store(image_file, image_url: str):
    img_bytes = None
    if image_file is not None:
        img_bytes = _get_bytes_from_input(image_file)
    elif image_url:
        resp = requests.get(image_url, timeout=10,
                            headers={"User-Agent": "Visual-Product-Matcher/1.0"})
        resp.raise_for_status()
        img_bytes = resp.content

    img = pil_open_from_bytes(img_bytes)    # RGB + thumbnail(320, 320)
    user_vector = model.encode(img, convert_to_numpy=True).reshape(1, -1)
    similarities = cosine_similarity(user_vector, vector_matrix)[0]  # (50,)

    results = sorted([
        {
          "product": next((p for p in products_data if int(p["id"]) == int(pid)), None),
          "score":   float(similarities[i])
        }
        for i, pid in enumerate(product_ids)
        if next((p for p in products_data if int(p["id"]) == int(pid)), None)
    ], key=lambda x: x["score"], reverse=True)[:10]

    return gr.JSON(value=results)
```

<br/>

### 🗂️ Product Catalog — `products.json`

50 products across 5 categories — all IDs sequential, all images follow `product-{id}.jpg` naming:

<div align="center">

| Category | IDs | Count | Example Products |
|:---|:---:|:---:|:---|
| **Apparel** | 1–10 | 10 | Classic Denim Jacket · Black Leather Boots · Beige Trench Coat |
| **Electronics** | 11–20 | 10 | Wireless Over-Ear Headphones · Smartwatch · Electric Drone |
| **Furniture** | 21–30 | 10 | Minimalist Wooden Chair · Modern Gray Sofa · Velvet Armchair |
| **Home Goods** | 31–40 | 10 | Ceramic Coffee Mug · Scented Soy Candle · Glass French Press |
| **Accessories** | 41–50 | 10 | Brown Leather Wallet · Gold Wristwatch · Red Leather Handbag |

</div>

<br/>

### ⚙️ `index.py` — Vector Generation Script

One-time preprocessing — run before deploying to generate `product_vectors.json`:

```python
# index.py — run once: python index.py
PRODUCTS_FILE_PATH = 'products.json'
VECTORS_FILE_PATH  = 'product_vectors.json'
IMAGES_DIR         = 'public/images'

model = SentenceTransformer('clip-ViT-B-32')
for product in products:
    img    = Image.open(f"public/images/{os.path.basename(product['imagePath'])}")
    vector = model.encode(img).tolist()           # 512 floats
    product_vectors.append({'id': product['id'], 'vector': vector})

json.dump(product_vectors, f, indent=2)           # writes product_vectors.json
```

<br/>

### 🏗️ Gradio App Structure

```python
with gr.Blocks() as demo:
    gr.Markdown("# Visual Product Matcher API")
    with gr.Tabs():
        with gr.TabItem("Store Search"):
            store_file_input = gr.File(label="Upload Image File")
            store_url_input  = gr.Textbox(label="Or Enter Image URL")
            store_output     = gr.JSON()
            store_button     = gr.Button("Search Store")
        with gr.TabItem("Web Search"):
            web_url_input = gr.Textbox(label="Enter Image URL")
            web_output    = gr.JSON()
            web_button    = gr.Button("Search Web")

    store_button.click(fn=find_matches_in_store,
                       inputs=[store_file_input, store_url_input],
                       outputs=store_output,
                       api_name="store_search")   # POST /run/store_search

    web_button.click(fn=find_matches_on_web,
                     inputs=[web_url_input],
                     outputs=web_output,
                     api_name="web_search")       # POST /run/web_search

demo.queue().launch()
```

<br/><br/>

<a name="api-docs"></a>
<!----------------------------------------------------------------------------->
<!--  API DOCUMENTATION                                                       -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1e0b48,100:0b0422&height=64&text=%F0%9F%93%9A%20%20API%20Documentation&fontSize=22&fontColor=a78bfa&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

### 🏪 Store Search Endpoint

**Endpoint:** `POST /run/store_search`

**Request — file as base64:**
```json
{
  "data": [
    { "data": "<base64_encoded_image_string>" },
    ""
  ]
}
```

**Request — image URL:**
```json
{
  "data": [
    null,
    "https://example.com/product.jpg"
  ]
}
```

**Response:**
```json
{
  "data": [
    {
      "product": {
        "id": 1,
        "name": "Classic Denim Jacket",
        "category": "Apparel",
        "imagePath": "product-1.jpg"
      },
      "score": 0.9241
    },
    {
      "product": {
        "id": 9,
        "name": "Leather Biker Jacket",
        "category": "Apparel",
        "imagePath": "product-9.jpg"
      },
      "score": 0.8873
    }
  ]
}
```

<br/>

### 🌍 Web Search Endpoint

**Endpoint:** `POST /run/web_search`

**Request:**
```json
{ "data": ["https://example.com/product-image.jpg"] }
```

**Response:**
```json
{
  "data": [{
    "results": [
      {
        "title":     "Similar Denim Jacket — Example Store",
        "link":      "https://store.example.com/jacket",
        "thumbnail": "https://cdn.example.com/thumbs/jacket.jpg"
      }
    ]
  }]
}
```

<br/>

### 🐍 Python Integration Example

```python
import requests, base64

BASE_URL = "https://kumarpiyushraj-visual-product-matcher.hf.space"

# Store search — file as base64
with open("query.jpg", "rb") as f:
    img_b64 = base64.b64encode(f.read()).decode("utf-8")

resp = requests.post(f"{BASE_URL}/run/store_search",
                     json={"data": [{"data": img_b64}, ""]}, timeout=15)
top = resp.json()["data"][0]
print(f"Top match: {top['product']['name']} — {top['score']:.2%} similarity")

# Web search
resp = requests.post(f"{BASE_URL}/run/web_search",
                     json={"data": ["https://example.com/image.jpg"]}, timeout=15)
web = resp.json()["data"][0]["results"]
```

<br/>

### 🌐 Embed as iframe

```html
<iframe
    src="https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher-frontend/embed"
    width="100%"
    height="680px"
    style="border: none; border-radius: 12px;"
    allow="camera; microphone">
</iframe>
```

<br/><br/>

<a name="performance"></a>
<!----------------------------------------------------------------------------->
<!--  PERFORMANCE                                                             -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:280d5c,100:0e0428&height=64&text=%E2%9A%A1%20%20Performance%20and%20Optimization&fontSize=22&fontColor=ddd6fe&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

<div align="center">

| Metric | Value | Notes |
|:---|:---:|:---|
| **Store query latency (CPU)** | 100–500ms | CLIP encode dominates; `torch.set_num_threads(1)` |
| **Web search latency** | 1–3s | SerpAPI external roundtrip · 10s hard timeout |
| **@gradio/client handshake** | ~200ms | First call only — WebSocket setup |
| **NumPy cosine similarity** | ~2ms | 50 × 512 vectorized — negligible |
| **Frontend validation** | < 5ms | Synchronous MIME + size check |
| **URL reachability check** | ~50ms | `new Image()` onload — network dependent |
| **Stagger animation** | 500ms | 10 cards × 50ms — perceived as instant |
| **Upload progress reset** | 1000ms | `setTimeout(() => setUploadProgress(0), 1000)` |
| **Search progress reset** | 1000ms | `setTimeout(() => setSearchProgress(0), 1000)` |
| **Max catalog size** | 50 products | Scales to millions via Pinecone |
| **Max file upload** | 10 MB | `handleFileChange()` client-side enforced |
| **Max image dimensions** | 4000 × 4000 px | `handleFileChange()` `naturalWidth/Height` check |

</div>

<br/>

### ✅ Optimization Tips

- Use **centered, well-lit product images** — CLIP semantic matching improves 20–30% with quality inputs
- For **web mode**, ensure the URL resolves directly to an image file — not an HTML page containing an image
- `torch.set_num_threads(1)` is already set in `app.py` — optimal for HF Spaces CPU tier
- The `product_vectors.json` NumPy matrix is built at startup — no per-query disk I/O
- For catalogs beyond 50 products, consider **Pinecone** or **Weaviate** for approximate nearest neighbor search

<br/><br/>

<a name="quickstart"></a>
<!----------------------------------------------------------------------------->
<!--  QUICK START                                                             -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:230d53,100:0c0428&height=64&text=%F0%9F%9A%80%20%20Quick%20Start&fontSize=22&fontColor=c4b5fd&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

### 🖱️ Try the Live Demo

1. Visit the **[Frontend Space](https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher-frontend)**
2. Select **🏪 Store Search** or **🌍 Web Search** from the animated tab bar
3. **Store mode** — click the `✨` drop zone or drag a file (JPG / PNG / WebP · max 10MB · max 4000×4000 px), or paste an image URL
4. **Web mode** — paste a direct image URL into the input field
5. Click **🔍 Discover Matches** and watch the progress bar fill as AI processes your image
6. Browse the scored result grid — click any card (store mode) to open the detail modal

<br/>

### 🧑‍💻 Run Locally

```bash
# Clone both Spaces
git clone https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher
git clone https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher-frontend

# ── Backend ────────────────────────────────────────────────────────────────
cd visual-product-matcher
pip install gradio python-dotenv requests Pillow numpy scikit-learn sentence-transformers torch

cp .env.example .env          # set SERPAPI_KEY=your_key_here
python index.py               # one-time: encodes public/images/ → product_vectors.json
python app.py                 # starts Gradio on localhost:7860

# ── Frontend ───────────────────────────────────────────────────────────────
cd ../visual-product-matcher-frontend
npm install
# In App.tsx, change: client("kumarpiyushraj/visual-product-matcher")
#                  → client("http://localhost:7860")
npm run dev                   # Vite dev server on localhost:5173
```

<br/>

### 📦 `requirements.txt`

```
gradio
python-dotenv
requests
Pillow
numpy
scikit-learn
sentence-transformers
torch
```

<br/><br/>

<a name="future"></a>
<!----------------------------------------------------------------------------->
<!--  FUTURE ENHANCEMENTS                                                     -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1d0c45,100:0a0320&height=64&text=%F0%9F%94%AE%20%20Future%20Enhancements&fontSize=22&fontColor=a78bfa&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

<details>
<summary><b>🎨 UI / UX Improvements</b></summary>

<br/>

- [ ] **Real crop implementation** — `handleCrop()` currently only triggers `alert("Crop applied successfully! (Simulation)")` — replace with `react-image-crop` or Canvas API
- [ ] **Dark / Light mode toggle** — persist via localStorage
- [ ] **Similarity heatmap** — visualize which image regions contributed to the match score
- [ ] **Drag-to-compare** — side-by-side query vs. result view
- [ ] **Category filter** — the `category` field already exists in `products.json`, just needs a filter UI
- [ ] **PWA support** — service worker for offline capability and install-to-homescreen

<br/>
</details>

<details>
<summary><b>🧠 AI / Search Improvements</b></summary>

<br/>

- [ ] **Batch image upload** — process multiple query images in one call
- [ ] **CLIP ViT-L/14 upgrade** — 768D embeddings for higher accuracy
- [ ] **Text + image hybrid search** — combine CLIP text embeddings with visual input
- [ ] **Pinecone / Weaviate integration** — scale vector search beyond 50 products
- [ ] **Re-ranking model** — secondary fine-tuned similarity model on top of CLIP
- [ ] **Relevance feedback** — thumbs up/down per result to log signals for future fine-tuning

<br/>
</details>

<details>
<summary><b>⚙️ Backend / Infrastructure</b></summary>

<br/>

- [ ] **GPU Space** — upgrade to A10G for sub-100ms CLIP inference
- [ ] **Result caching** — MD5-keyed cache for frequently queried images
- [ ] **Richer catalog schema** — add `price`, `brand`, `url`, `created_at` to `products.json` (fixes `date_desc` sort)
- [ ] **Live `index.py`** — add products and regenerate vectors without full redeploy
- [ ] **OpenTelemetry tracing** — end-to-end traces: frontend → Gradio → CLIP → SerpAPI
- [ ] **WebSocket streaming** — stream partial results as each similarity score is computed

<br/>
</details>

<br/><br/>

<!----------------------------------------------------------------------------->
<!--  ACKNOWLEDGMENTS                                                        -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a0b42,100:090320&height=64&text=%F0%9F%99%8F%20%20Acknowledgments&fontSize=22&fontColor=c4b5fd&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

<div align="center">

| &nbsp; | Acknowledgment |
|:---:|:---|
| 🤗 | **Hugging Face** — Spaces infrastructure for both static frontend and Gradio SDK backend hosting |
| 🧠 | **OpenAI** — CLIP architecture enabling zero-shot language-free visual semantic search |
| 🤖 | **UKP Lab / Sentence Transformers** — `clip-ViT-B-32` wrapper used directly in `app.py` |
| 🔍 | **SerpAPI** — Google Reverse Image Search API powering the Web Exploration mode |
| ⚛️ | **React Core Team** — Component model and hooks that structure the entire frontend |
| 🎞️ | **Framer** — Motion library for all animations, `layoutId` tab switcher, and spring modals |
| 🌊 | **Tailwind Labs** — Utility-first CSS enabling the glassmorphism, blob aesthetic, and responsive grid |
| 🌟 | **Open Source ML Community** — NumPy, scikit-learn, Pillow, Gradio, and every supporting package |

</div>

<br/><br/>

<!----------------------------------------------------------------------------->
<!--  CONTACT                                                                -->
<!----------------------------------------------------------------------------->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1c0b44,100:0a0320&height=64&text=%F0%9F%93%9E%20%20Contact%20and%20Support&fontSize=22&fontColor=ede9fe&fontAlignY=52&fontAlign=50" width="100%"/>

<br/>

<div align="center">

**Questions? Issues? Contributions?**

<br/>

[![Backend Discussions](https://img.shields.io/badge/Backend%20Space-Discussions-7c3aed?style=for-the-badge&logo=huggingface)](https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher/discussions)&nbsp;
[![Frontend Discussions](https://img.shields.io/badge/Frontend%20Space-Discussions-a78bfa?style=for-the-badge&logo=huggingface)](https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher-frontend/discussions)&nbsp;
[![HF Profile](https://img.shields.io/badge/HF%20Profile-kumarpiyushraj-c4b5fd?style=for-the-badge&logo=huggingface)](https://huggingface.co/kumarpiyushraj)

</div>

<br/><br/>

<!----------------------------------------------------------------------------->
<!--  FOOTER                                                                 -->
<!----------------------------------------------------------------------------->

<div align="center">

<br/>

**Built with ❤️ for visual explorers &nbsp;·&nbsp; React + TypeScript &nbsp;·&nbsp; CLIP ViT-B/32 &nbsp;·&nbsp; Gradio 5.49.1 &nbsp;·&nbsp; Framer Motion**

<br/>

[![Frontend Space](https://img.shields.io/badge/%F0%9F%8E%A8%20Frontend-Launch%20App-7c3aed?style=for-the-badge)](https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher-frontend)&nbsp;
[![Backend Space](https://img.shields.io/badge/%E2%9A%99%EF%B8%8F%20Backend-View%20API-a78bfa?style=for-the-badge)](https://huggingface.co/spaces/kumarpiyushraj/visual-product-matcher)

<br/>

*© 2025 Kumar Piyush Raj &nbsp;·&nbsp; [HF Profile @kumarpiyushraj](https://huggingface.co/kumarpiyushraj)*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a78bfa,40:7c3aed,70:1e0a45,100:0d0720&height=160&section=footer" width="100%"/>

</div>
