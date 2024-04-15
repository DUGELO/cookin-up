# cookin-up

1. **Componentização:** Começamos entendendo a importância da arquitetura baseada em componentes e construímos componentes como o componente de banner. Essa abordagem melhora a organização do código e a reutilização.

2. **Diretivas Vue:** Exploramos diretivas Vue, como `v-for` para renderização dinâmica de estruturas semelhantes e `v-if` e `v-else` para renderização condicional de elementos.

3. **Estado e Reatividade:** Compreender o estado e a reatividade foi crucial. Presenciamos como as mudanças no estado acionam a reatividade, atualizando dinamicamente a interface. Isso foi exemplificado por interações como clicar em ingredientes, alterar visuais e acionar novas renderizações.

4. **Requisições HTTP e Métodos de Ciclo de Vida:** Alavancando requisições HTTP para buscar receitas, aprendemos sobre os métodos de ciclo de vida do Vue. Percebemos a importância de fazer requisições HTTP ao atualizar o estado para manter a consistência.

5. **Desafios e Autonomia:** A segunda página do projeto foi deixada como um desafio, proporcionando uma oportunidade de prática autônoma. Munido dessas habilidades, você pode desenvolver outras aplicações web frontend com mais eficiência, aprimorando sua experiência como desenvolvedor.

6. **Vue no Mercado:** O Vue se destaca como um dos frameworks frontend mais populares ao lado do React e Angular. Dominar o Vue abre um mundo de possibilidades no cenário de desenvolvimento frontend.

---

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```
