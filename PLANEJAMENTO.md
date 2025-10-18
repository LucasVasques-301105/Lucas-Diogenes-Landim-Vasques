# PLANEJAMENTO do Repositório

> Documento de planejamento e roteiro para organizar o repositório que vai atender ao *Desafio - Entrega Intermediária*.

---

## 1. Objetivo

Organizar e apresentar um portfólio técnico no GitHub que comprove: planejamento claro, projetos versionados (commits/branches), evidências de colaboração (forks & PRs), documentação por projeto, deployment de pelo menos um projeto e uma apresentação em vídeo. Esse repositório será público e linkado no LinkedIn.

---

## 2. Escopo

- Implementar **mínimo 1 projeto funcional** (frontend ou fullstack) com README detalhado.
- Adicionar pelo menos **mais 1 artefato** (script, API ou página estática) para mostrar diversidade.
- Criar documentação geral (README raiz, PLANEJAMENTO.md, LICENSE, CONTRIBUTING).
- Realizar 1 fork externo + 1 pull request (pode ser correção simples) e documentar a PR.
- Gerar evidências: commits, branches, screenshots, links de PR, link de deploy e vídeo de 3–5 min.

---

## 3. Estrutura de diretórios sugerida

/README.md # Apresentação do portfólio (raiz)
/PLANEJAMENTO.md # Este arquivo
/.github/
PULL_REQUEST_TEMPLATE.md
CONTRIBUTING.md
/projects/
projeto-1/ # Projeto principal (app ou site)
README.md
src/
assets/
docs/
projeto-2/ # Outro projeto (script, API, etc.)
README.md
src/
docs/ # Documentos adicionais (prints, evidências)
assets/ # Imagens, logos, screenshots usados no README
/LICENSE
.gitignore


---

## 4. Tecnologias (stack a demonstrar)

Escolha 2–3 das tecnologias abaixo que você já domina e as declare no README: HTML, CSS, JavaScript, React, Node.js/Express, Python, GitHub Pages, Vercel, PostgreSQL (ou outro DB), Docker (opcional).

---

## 5. Cronograma e milestones (sugestão rápida)

- **Dia 0 (hoje)**: Puxar repositório, criar PLANEJAMENTO.md e estrutura inicial. (feito)
- **Dia 1**: Projeto 1 — estrutura + README + primeiro commit (branch `feat/projeto-1`).
- **Dia 2**: Implementação do projeto 1 — commits incrementais + push + abrir PR e merge.
- **Dia 3**: Projeto 2 — adicionar artefato simples (script/API) + README.
- **Dia 4**: Deploy do projeto 1 (GitHub Pages / Vercel) e documentação do link no README.
- **Dia 5**: Fazer fork de repo público e submeter PR; documentar evidência.
- **Dia 6**: Gravar vídeo de 3–5 minutos; gerar PDF de entrega com links e screenshots.

Ajuste o cronograma conforme sua disponibilidade.

---

## 6. Estratégia de versionamento e branches

- `main` — branch principal (deployable). Sempre protegido (merge via PR).
- `dev` — branch de integração (opcional).
- Features: `feat/nome-da-feature` (ex.: `feat/login`).
- Correções: `fix/descricao`.
- Documentação: `docs/*`.

Boas práticas: commits pequenos e descritivos; mensagens no padrão `type(scope): descrição` (ex.: `feat(projeto-1): adiciona layout responsivo`).

---

## 7. Critérios de aceitação / checklist por projeto

Cada pasta de projeto deve conter:
- `README.md` com descrição, tecnologias, passos de instalação e execução, screenshots e link de demo (se houver).
- Código fonte organizado em `src/`.
- `.gitignore` específico (se aplicável).
- Histórico de commits visível com pelo menos 5 commits relevantes (dependendo da complexidade).

Checklist no README raiz antes de submeter:
- [ ] Repositório público
- [ ] PLANEJAMENTO.md presente
- [ ] README raiz com índice para cada projeto
- [ ] Pelo menos 1 projeto deployado com link
- [ ] Fork & PR realizado (link colocado em /docs/)
- [ ] Vídeo no YouTube (não listado) com link no README
- [ ] LICENSE e CONTRIBUTING

---

## 8. Evidências exigidas (o que coletar)

- Links diretos para commits importantes (ex.: `https://github.com/usuario/repo/commit/<sha>`).
- Link para PR do fork (ex.: `https://github.com/outro/repo/pull/<num>`) e print da aceitação/review.
- Print do histórico de commits (GitHub history) como imagem em `/docs/`.
- Link do deploy (Vercel/GitHub Pages) e print da aplicação rodando.
- Link do vídeo YouTube e script / roteiro curto do vídeo.

---

## 9. Template rápido de README de projeto (exemplo mínimo)

- Título do projeto
- Descrição curta
- Tecnologias
- Instalação
- Execução
- Demo (link)
- Screenshots
- Status
- Licença

(Ainda posso gerar um README pronto para colar em cada projeto.)

---

## 10. Próximos passos recomendados (imediatos)

1. Criar a estrutura de pastas e adicionar este arquivo (já criado).
2. Implementar o projeto principal em uma branch `feat/projeto-1` com commits claros.
3. Criar README do projeto 1 com instruções e screenshots.
4. Fazer deploy e registrar o link.
5. Executar um fork de um repo público e abrir PR.
6. Preparar vídeo de apresentação e PDF final.

---

## 11. Contatos e notas finais

Se quiser, eu posso gerar agora:
- README.md raiz pronto;
- README template para cada projeto;
- PULL_REQUEST_TEMPLATE.md e CONTRIBUTING.md;
- Um roteiro curto para o vídeo (script de 3–4 minutos).

Escolha qual desses quer que eu gere em seguida e eu crio o conteúdo pronto para você colar no repositório.

---

*Fim do PLANEJAMENTO.*
