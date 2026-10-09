# Portfolio

Static Next.js portfolio · EN + FR · content in JSON/MDX · 3D with React Three Fiber · hosted on Vercel.
Progress checklist: [PLAN.md](PLAN.md)

## Commands

```bash
npm run dev     # dev server → http://localhost:3000
npm run build   # production build (static export)
npm run lint    # check code
```

## Libraries

### Framework
| Library | Version | Purpose |
|---|---|---|
| `next` | 15.5 | Framework: pages, routing, build |
| `react` / `react-dom` | 19.1 | UI library |

### Features
| Library | Version | Purpose |
|---|---|---|
| `next-intl` | 4.14 | EN/FR translations and `/en`, `/fr` routes |
| `next-themes` | 0.4 | Dark/light mode |
| `framer-motion` | 14.0 | Scroll and hover animations |
| `next-mdx-remote` | 6.0 | Blog posts and project case studies in MDX |

### 3D
| Library | Version | Purpose |
|---|---|---|
| `three` | 0.186 | 3D engine (WebGL) |
| `@react-three/fiber` | 9.8 | Write three.js scenes as React components |
| `@react-three/drei` | 10.7 | Ready-made 3D helpers: controls, text, model loading, effects |

### Dev only
| Library | Purpose |
|---|---|
| `tailwindcss` 4, `@tailwindcss/postcss` | Styling |
| `typescript`, `@types/*` | Type checking |
| `eslint`, `eslint-config-next` | Linting |

## Content

Edit the JSON files in `data/` (profile, projects, experience, skills, socials) and the MDX files in `content/`, then push. Vercel redeploys automatically.
