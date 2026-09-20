# Códigos e Ideias

Um blog pessoal do Felipe sobre desenvolvimento de software, tecnologia e projetos pessoais. Um espaço para registrar descobertas, decisões e aprendizados ao longo do caminho.

Feito com Jekyll, com textos em Markdown e publicação no GitHub Pages.

Sugestões e textos são bem-vindos por [issue](https://github.com/Felipe-Cavalca/blog/issues/new/choose) ou [pull request](https://github.com/Felipe-Cavalca/blog/compare), com crédito para quem contribuiu. A decisão final de publicação é sempre do Felipe, conforme o que ele considerar relevante para o blog.

## Formatação

Instale as dependências com `npm ci`, aplique o Prettier com `npm run format` e valide sem alterar arquivos com `npm run format:check`.

Os templates HTML com Liquid/Jekyll estão documentados no `.prettierignore` e permanecem fora da formatação automática. O parser HTML padrão do Prettier não interpreta Liquid com segurança; essa exclusão evita alterações que possam corromper os templates até que um plugin compatível seja adotado.
