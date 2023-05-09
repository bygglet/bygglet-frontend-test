This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# Bygglet

## Kodtest för react

Co-pilot är ej tillåtet.

### Uppgiften

Byggare Bob jobbar på sin nya hemsida och vill kunna visa upp all sin otroliga personal för sina kunder.

Målet är att kunna presentera företagets personal i en lista. Listan ska innehåll namn, yrke och personens bild.
Vi behöver i våran POC inte designa allt utan det viktigaste är att visa för Byggarebob att react är rätt verktyg.

All information för att visa personalen finns i `public/api/employees.json` ([Länk](http://localhost:3000/api/employees.json)). Hämta json-data med `fetch` och presentera på sidan. 

```json
[
  {
      "id": 1,
      "name": "Torbjörn",
      "profession": "Designer",
      "imageUrl": "/images/Designer.svg"
    }
]
```

Bilder att visa ligger enligt exempel.

#### Observera
Detta är en parprogrammerings övning så ställa gärna frågor och google är din vän. Det är också bra att tänka högt och diskutera vad som ska göras.

### Bonuspoäng:
 - En mui component (https://mui.com/)
 - En custom hook

### Extra bonusuppgifter
 - https://bigfrontend.dev/react
 - https://bigfrontend.dev/react/useArray

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
