# Next14 blog with Sanity CMS

## Sanity
```sh
npm create sanity@latest -- --template clean --create-project "Sanity Project" --dataset production

# after creating schemas
cd sanity
npm run dev

# sanity studio query cheatsheet
[sanity query cheatsheet](https://www.sanity.io/docs/query-cheat-sheet)

# fetch data
npm i next-sanity @sanity/image-url @portabletext/react

# deploy to sanity (ensure in sanity dir)
npm run deploy
```

## Shadcn UI
```sh
npx shadcn-ui@latest init

# dark mode
npm install next-themes
```

## Tailwind
```sh
npm i -D @tailwindcss/typography

# update tailwind.config.ts
plugins: [require("@tailwindcss/typography")]
```