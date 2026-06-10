# V ECF/SBF 2026

Site oficial do V Encontro Capixaba de Física (ECF/SBF 2026), evento científico realizado no Instituto Federal do Espírito Santo (IFES) - Campus Serra, em parceria com a UFES e a Sociedade Brasileira de Física.

Link do site: https://ifesserra-lab.github.io/sbf

## Objetivos

- Divulgar informações oficiais sobre o ECF/SBF 2026.
- Apresentar data, local, programação, palestrantes e orientações de hospedagem.
- Facilitar o acesso ao formulário de inscrição do evento.
- Reunir em um único portal os conteúdos de apoio para estudantes, professores, pesquisadores e participantes.

## Tecnologias

- [Astro](https://astro.build/) para construção do site estático.
- [TypeScript](https://www.typescriptlang.org/) para tipagem no projeto.
- [Tailwind CSS](https://tailwindcss.com/) para estilização.
- [Lucide Astro](https://lucide.dev/) para ícones.
- [Fontsource](https://fontsource.org/) com as fontes Inter e Space Grotesk.
- ESLint com suporte a Astro e TypeScript para verificação de código.

## Páginas

- Início
- Cronograma
- Palestrantes
- Hospedagem
- Inscrições

## Desenvolvimento

Instale as dependências:

```bash
npm install
```

Execute o servidor local:

```bash
npm run dev
```

Gere a versão de produção:

```bash
npm run build
```

Visualize o build localmente:

```bash
npm run preview
```

Execute a verificação com ESLint:

```bash
npm run lint:eslint
```

## Deploy

O projeto está configurado para publicação como site estático no GitHub Pages, com:

- `site`: `https://ifesserra-lab.github.io`
- `base`: `/sbf`
