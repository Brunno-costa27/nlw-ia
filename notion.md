# Assunto: NLW IA
## Vídeo: UI da aplicação

### (22:08) 
Instalando o shadcn/ui
```bash
npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p
```

Adicionando configuração no tsconfig.json

```bash

"baseUrl": ".",
"paths": {
  "@/*": ["./src/*"]
}

```

Instalação do type/node para permitir importações internas do node.js

```bash
npm i -D @types/node
```

Executa o shadcn/ui para usar os componentes

```bash
npx shadcn-ui@latest init

```
Agora podemos adicionar componentes no nosso projeto.

```bash
npx shadcn-ui@latest add button

```

Importando biblioteca de icons

```bash
npm i lucide-react
```

Instalando mais um componente 

```bash
npx shadcn-ui@latest add separator
```

Instalando mais um componente 

```bash
npx shadcn-ui@latest add textarea
```

Instalando mais um componente 

```bash
npx shadcn-ui@latest add label
```

Instalando mais um componente 

```bash
npx shadcn-ui@latest add select
```

Instalando mais um componente 

```bash
npx shadcn-ui@latest add slider
```