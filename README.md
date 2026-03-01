```bash
pnpm dev            # Next.js 개발 서버
pnpm storybook      # Storybook 실행
pnpm test           # Vitest 단위 테스트
pnpm format         # Prettier 코드 정리
pnpm lint           # ESLint 검사
```

##

next-boilerplate/
├─ .storybook/
│  ├─ main.ts
│  └─ preview.ts
├─ src/
│  ├─ app/
│  │  ├─ layout.tsx
│  │  └─ page.tsx
│  ├─ components/
│  │  └─ ui/
│  │     ├─ Button.tsx
│  │     └─ Button.stories.tsx
│  ├─ lib/
│  │  └─ utils.ts
│  ├─ styles/
│  │  └─ globals.css
│  └─ tests/
│     └─ Button.test.tsx
├─ .eslintrc.cjs
├─ .prettierrc.cjs
├─ next.config.mjs
├─ postcss.config.cjs
├─ tailwind.config.ts
├─ tsconfig.json
├─ vitest.config.ts
├─ setupTests.ts
└─ package.json