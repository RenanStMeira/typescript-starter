## typescript-starter
Aplicação para salvar arquivos e instalação de dependências

## TSCONFIG.JSON 

  "compilerOptions": {
  
    "module": "commonjs",
    "declaration": true,
    "removeComments": true,
    "emitDecoratorMetadata": true,
    "experimentalDecorators": true,
    "allowSyntheticDefaultImports": true,
    "target": "ES2016",
    "sourceMap": true,
    "outDir": "./dist",
    "baseUrl": "./",
    "incremental": true,
    "skipLibCheck": true,
    "strictNullChecks": false,
    "noImplicitAny": false,
    "strictBindCallApply": false,
    "forceConsistentCasingInFileNames": false,
    "noFallthroughCasesInSwitch": false,
    // "types": ["node", "@prisma/client"],
    "esModuleInterop": true,
    "resolveJsonModule": true
  }
  
}

## Instalação do TypeScript
**Inicialização**
* yarn install
* yarn init
* yarn add typescript --dev

**Inicialização do TypeScript**
* npx tsc --init

**Instalação do Express:**
https://expressjs.com/pt-br/
* yarn add express

**Tipagem**
* yarn add --dev @types/express

## Instalação do Prisma:
https://www.prisma.io/
* yarn add prisma --dev
**Inicialização**
* npx prisma init
* yarn add pg

**Geração do Prisma Client:**
* npx prisma generate





