# react-shadcn-tailwind-vite
Testing out this combo for a thin client

## Getting Started

```sh
cd vite-project
npm install
npm run dev
```

## ShadCN Example

```sh
npx shadcn@latest add button
```

The command above will add the Button component to your project. You can then import it like this:

```
import { Button } from "@/components/ui/button"
 
export default function Home() {
  return (
    <div>
      <Button>Click me</Button>
    </div>
  )
}
```