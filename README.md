This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Kodtest för react

Detta är en parprogrammerings-övning så ställa gärna frågor och google är din vän. Det är också bra att tänka högt och diskutera vad som ska göras.
Co-pilot är ej tillåtet.


### Uppgiften
Byggarebob jobbar på sin nya webbplats och vill kunna visa upp all sin otroliga personal för sina kunder.
Målet är att kunna presentera företagets personal i en lista innehållande bilder, namn och yrke
Exempel på hur det kan se ut.
![image (10)](https://user-images.githubusercontent.com/8349939/227497747-3fa1c49e-cbac-4c1f-bf3d-e85845f97c57.png)

Vi behöver i våran POC inte designa allt utan det viktigaste är att visa för Byggarebob att react är rätt verktyg
för att lösa detta problem.

Informationen som behövs för att hämta personalen finns en json fil (employees.json) som ska representera utdata ifrån 
ett api, detta bör hämtas via ett "get" anrop till http://localhost:3000/api/employees.json.
Utdatan ser ut som exemplet nedan:
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

Tips för starta miljö:
npm run dev


### Bonuspoäng:
 - En mui component (se resurser för länk)
 - En react component
 - En custom hook (förslagsvis bryta ut api-anropet)

### Extra bonusuppgifter
- https://bigfrontend.dev/react
- https://bigfrontend.dev/react/useArray


### Resurser:
  - https://react.dev/learn
  - https://mui.com/
  - https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API

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
