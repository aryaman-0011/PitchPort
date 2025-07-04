# 🚀 PitchPort

**PitchPort** is a modern web platform where users can register and share their startup ideas. Designed with performance and scalability in mind, PitchPort leverages the power of **Next.js**, **Sanity**, and other cutting-edge technologies to deliver a seamless user experience.

---

## 🌐 Live Demo

> 🔗 [Visit PitchPort on Vercel](https://pitch-port.vercel.app/)

---

## ✨ Features

- 🔐 User Authentication with NextAuth
- 💡 Share and manage startup ideas
- 🔍 Search by category, author, or name
- ⚡️ Powered by ISR (Incremental Static Regeneration) and PPR (Partial Prerendering)
- 📦 CMS-backed data storage via Sanity
- 🎨 Beautiful UI using Tailwind CSS + Shadcn UI components
- 📈 Production error monitoring with Sentry
- ☁️ Deployed on Vercel for scalability

---

## 🛠️ Tech Stack

| Technology     | Description                                      |
|----------------|--------------------------------------------------|
| **Next.js**    | React framework with advanced routing/rendering |
| **React**      | UI library                                       |
| **NextAuth.js**| Secure authentication                           |
| **Tailwind CSS** | Utility-first styling framework               |
| **Shadcn UI**  | Prebuilt accessible components for Tailwind     |
| **Sanity CMS** | Content and idea storage                        |
| **Sentry**     | Error logging & monitoring                      |
| **Vercel**     | Hosting and deployment                          |

---

## ⚙️ Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/aryaman-0011/PitchPort.git
cd pitchport
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Environment Configuration

Create a `.env.local` file in the root directory and add:

```env
AUTH_SECRET=""
AUTH_GITHUB_ID =""
AUTH_GITHUB_SECRET =""
NEXT_PUBLIC_SANITY_PROJECT_ID=""
NEXT_PUBLIC_SANITY_DATASET=""
NEXT_PUBLIC_SANITY_API_VERSION=""
SANITY_WRITE_TOKEN=""
```

### 4. Start the Development Server

```bash
npm run dev
```

Visit `http://localhost:3000` to see the app running.

---

## Contributing
Feel free to open issues or submit pull requests for improvements. Contributions are always welcome!


## Contact
For questions or feedback, please reach out at : 

[![Email](https://skillicons.dev/icons?i=gmail&theme=dark)](mailto:kushwaha.aryaman21@gmail.com)
[![Email](https://skillicons.dev/icons?i=linkedin&theme=dark)](https://www.linkedin.com/in/aryaman-kushwaha-b60b2028a/)
