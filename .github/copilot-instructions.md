## Propósito

Este arquivo dá orientações concisas para agentes de codificação (ex.: GitHub Copilot, agentes automatizados) sobre como trabalhar produtivamente neste repositório "Santander Code Girls 2025 AWS (DIO)".

## Visão rápida do repositório

- Estrutura principal:
  - `desafios/` — desafios práticos (cada desafio em sua própria pasta, ex.: `desafios/gerenciando-instâncias-na-EC2/desafio.md`).
  - `certificados/` — certificados organizados por módulo.
  - `Readme.md` — descrição pessoal do repositório (em pt-br).

O repositório é um diário de aprendizado; mudanças devem preservar conteúdo histórico e estilo em português.

## Regras práticas para o agente

1. Produza mudanças pequenas e explícitas. Prefira criar novos arquivos em vez de alterar conteúdo histórico sem necessidade.
2. Use pt-br em todos os textos adicionados (mensagens de commit, descrições, docs). O projeto está em português.
3. Não remova ou reorganize pastas `certificados/` ou conteúdo de `desafios/` sem confirmar — são artefatos da jornada da autora.
4. Quando adicionar instruções ou soluções em `desafios/`, atualize também o `Readme.md` se e somente se fizer sentido (ex.: adicionar link para o novo desafio resolvido).

## Onde procurar contexto / exemplos

- Exemplos de desafio e estilo de escrita: `desafios/gerenciando-instâncias-na-EC2/desafio.md`.
- Estrutura de certificados: `certificados/` (cada subpasta é um módulo/certificado).
- Descrição do projeto: `Readme.md`.

## Como formatar sugestões de código

- Ao propor alteração em um desafio, inclua:
  - Resumo de 1-2 linhas dizendo o porquê da mudança.
  - Arquivos afetados listados.
  - Exemplo mínimo de alteração (trecho) e explicação curta.

Exemplo de cabeçalho de PR sugerido:

"Melhora no desafio 'Gerenciando instâncias na EC2' — adiciona passo a passo com comandos AWS CLI e exemplos de screenshots. Arquivos: `desafios/gerenciando-instâncias-na-EC2/desafio.md`"

## Contrato mínimo (entrada/saída)

- Entrada: solicitação do usuário (issue/PR) ou tarefa interna.
- Saída esperada: arquivo(s) adicionados/atualizados, descrição em pt-br, testes não aplicáveis (conteúdo documental).

## Limites e o que evitar

- Não adicionar credenciais, chaves ou scripts que façam chamadas externas sem autorização explícita.
- Evitar mudanças profundas de estrutura (mover/renomear pastas) sem autorização da autora.

## Onde deixar notas e sugestões

- Prefira abrir um PR com descrição detalhada. Se não for possível, cobrir mudanças em um arquivo dentro de `desafios/` ou criar um `docs/` se o conteúdo for extenso.

---
Se alguma seção estiver incompleta ou você quiser que eu adicione exemplos de commits/PRs mais específicos, diga quais partes prefere detalhar e eu itero.
