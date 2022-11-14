# Learning next blog app with no 3rd party
## Setup
- uses `pnpm` for package management
- install tailwind 
```
pnpm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p
```
- then follow tailwind setup page to setup
- install headless ui and heroicon with `pnpm install @headlessui/react @heroicons/react`

## Things to Note
- Might get `Image with src "https://thrangra.sirv.com/Final_Unity_2D_Small.jpg" has legacy prop "objectFit". Did you forget to run the codemod?`. Read [https://nextjs.org/docs/messages/next-image-upgrade-to-13](https://nextjs.org/docs/messages/next-image-upgrade-to-13)

## Running in dev
- `npm run dev`