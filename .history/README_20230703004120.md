# Ultimative Frontend-Vorlage

![Vorschau](https://cdn.discordapp.com/attachments/797485737272541250/952208625806495815/image_5.png)


[![Mit Vercel bereitstellen](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fcristicretu%2Fts-next-tailwind-template)

## Zutaten ✨:

- NextJS 🚀
- TailwindCSS 🦄
- Typescript 🦺
- Unterstützung für Dunkelmodus 🌓
- ESLint + Prettier Konfiguration 📂
- Husky 🐶
- Selbst gehostete Inter-Schriftart ␊

Verwende den Container für jede deiner Seiten im Ordner _components_ - er bietet einen wiederverwendbaren Ausgangspunkt für jede Seite.

```jsx
<Container>...SeitenElemente</Container>
```

## Erste Schritte

1. Mit 'Als Vorlage verwenden' Repository
   ![Vorschau](https://cdn.discordapp.com/attachments/797485737272541250/952208604386189332/Group_11.png)

2. Projekt klonen

```bash
# http
git clone https://github.com/cristicretu/ts-next-tailwind-template.git
```

```bash
# ssh
git clone git@github.com:cristicretu/ts-next-tailwind-template.git
```

3. Mit `create-next-app`

```bash
npx create-next-app -e https://github.com/cristicretu/ts-next-tailwind-template project-name
```

Installiere die benötigten Pakete und starte die Vorlage

```bash
cd project-name
yarn install
```

## Enthalten

### Benutzerdefinierte classNames Funktion
> Unter `/lib/classNames`

### Pakete

1. Next-themes: Eine Abstraktion für Themes in deiner Next.js App.
2. react-use: react-hooks

### Benutzerdefinierte globals.css

1. Benutzerdefinierte Unterstreichung
2. Vercel Navigationsleiste
3. Entfernt Firefox, Edge und IE. Bugs mit Überläufen

### Absolute Importe

```tsx
import TextField from '../../../components/TextField.tsx'
```

ändert sich zu

```tsx
import TextField from 'components/TextField.tsx'
```

### SEO-Optimierung in `Container.tsx`

### Ordnerstruktur & Organisation

> Unter `/components/` & `/public/`

### Selbst gehostete Inter-Schriftart

> Unter `/public/fonts/`

### 404 Seite

### Favicons und weitere Konfigurationen

> Unter `/public/static/favicons/`

![Vorschau](https://cdn.discordapp.com/attachments/797485737272541250/952211815046197278/Frame_7.png)
