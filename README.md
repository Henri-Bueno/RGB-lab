# RGB Lab

## Sobre o projeto

Projeto pessoal criado a partir da necessidade de visualizar e escolher cores com mais facilidade durante o desenvolvimento de outros projetos. A ferramenta permite ajustar os canais RGB em tempo real, visualizar o resultado e consultar o código da cor. Também permite salvar as cores escolhidas para reutilizá-las posteriormente durante o uso da aplicação.

## Funcionalidades

- Ajuste dos canais vermelho, verde e azul por meio de entradas numéricas.
- Atualização da pré-visualização a cada alteração dos valores RGB.
- Exibição do código da cor no formato `rgb(r, g, b)`.
- Uso de uma cor inversa para manter o texto legível sobre a amostra.
- Salvamento das cores escolhidas em uma lista para consulta posterior.
- Remoção das cores salvas quando necessário.

## Tecnologias utilizadas
- React
- TypeScript
- Vite
- CSS

## Pré-requisitos

- Node.js
- npm

## Instalação

Clone o repositório e instale as dependências do projeto:

```bash
git clone <url-do-repositorio>
cd RGB-lab/app/front
npm install
```

## Como executar

Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

Depois, acesse a URL exibida no terminal. Por padrão, o Vite utiliza a porta `5173`.

## Scripts disponíveis

| Script | Função |
| --- | --- |
| `npm run dev` | Inicia o servidor de desenvolvimento. |
| `npm run build` | Verifica os tipos e gera a versão de produção. |
| `npm run lint` | Executa o ESLint. |
| `npm run preview` | Inicia uma pré-visualização do build de produção. |

## Estrutura do projeto

```text
RGB-lab/
└── app/
    └── front/
        ├── public/
        ├── src/
        │   ├── components/
        │   │   ├── Input.tsx
        │   │   ├── Outpur.tsx
        │   │   └── SavedColors.tsx
        │   ├── App.tsx
        │   ├── App.css
        │   └── main.tsx
        ├── index.html
        ├── package.json
        └── vite.config.ts
```

## Observação

As cores salvas ficam disponíveis enquanto a aplicação está aberta. No momento, elas não são persistidas após o recarregamento da página.

## Resultado

Ao executar a aplicação, o usuário pode criar uma cor ajustando os canais RGB, visualizar a amostra em tempo real, consultar seu código e salvá-la para referência durante a sessão.
O README original do front-end permanece em [`app/front/README.md`](./app/front/README.md).
