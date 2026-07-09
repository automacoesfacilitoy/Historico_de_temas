# Rotina Quinzenal — Temas de Live Isabel Tunas

Este repositório guarda o histórico e a curadoria dos temas de live gerados a cada ciclo
quinzenal. **Leia este arquivo no início de cada execução da rotina** — ele define o fluxo
completo e os passos que precisam acontecer todo ciclo.

## Objetivo
Gerar, a cada ciclo, **10 temas candidatos** para as lives da Isabel Tunas (escopo
estratégico, não roteiro):
- **Bloco 1 — Empreendedorismo (5 temas):** grounded em notícias/dados atuais de
  mercado/negócios/economia/liderança feminina (priorizar Brasil, últimos 15–30 dias).
  Cada tema DEVE indicar a fonte/gatilho de atualidade. Objetivo: autoridade.
- **Bloco 2 — Tema Livre (5 temas):** grounded na trajetória/cotidiano/princípios da Isabel.
  Cada tema DEVE ter um "elemento de proximidade" explícito. Notícia externa é só pano de
  fundo leve. Objetivo: proximidade. Pelo menos 3 dos 5 devem vir de Reconstruir ou Princípios.

Cada um dos 10 temas é mapeado a exatamente 1 dos 4 territórios (Reconstruir, Construir
Princípios, Construir Negócios, Construir Legados) e não pode violar as proibições da marca
(dinheiro fácil/fórmula mágica, romantização, empresa acima da família, fé como estratégia
comercial, falsa dicotomia carreira x família, conteúdo raso). Marque `[incerto]` em dados
externos sem certeza. Responda sempre em português do Brasil.

## Passos de cada ciclo
1. **Pesquisar na web** atualidades para o Bloco 1 (mercado/gestão/economia/negócios, Brasil,
   15–30 dias) e tendências comportamentais para o Bloco 2 (pano de fundo leve).
2. **Ler os arquivos de histórico** (`historico-temas-lives-empreendedorismo.md` e
   `historico-temas-lives-livre.md`) para NÃO repetir território/ângulo dos últimos 2 ciclos.
3. **Selecionar 5 temas** para o Bloco 1 (territórios variados quando possível).
4. **Selecionar 5 temas** para o Bloco 2 (≥3 de Reconstruir/Princípios).
5. **Rodar o checklist da marca** nos 10 temas e substituir qualquer um que falhe.
6. **Gerar o .docx** (título de capa "Temas de Live — Isabel Tunas — [DATA]") e enviá-lo ao
   Google Drive via `create_file` com:
   - `parentId = "1MvfdH0_E_8rVBFvVsNiHcot0_F5y9pjA"` (pasta "Temas")
   - `title = "Temas-de-Live-Isabel-Tunas-[DATA].docx"`
   - `contentMimeType = "application/vnd.openxmlformats-officedocument.wordprocessingml.document"`
   - `disableConversionToGoogleType = true` (manter como .docx, não virar Google Docs)
7. **Atualizar os dois arquivos de histórico** com os temas deste ciclo + data.
8. **Atualizar `selecao-temas-lives.md`** (curadoria): inserir, LOGO ABAIXO DO CABEÇALHO
   (temas mais recentes no topo), um novo bloco `## Ciclo [DATA]` listando os 10 títulos como
   checkboxes (5 Empreendedorismo + 5 Tema Livre), mais a linha "🏆 Vencedores deste ciclo"
   em branco. Um analista entra depois e marca o tema vencedor de cada bloco. Use o modelo
   comentado no fim daquele arquivo. **Não apague ciclos anteriores nem as marcações do analista.**
9. **Commit e push** no `main` (mensagem ex.: "docs: temas de live - ciclo [DATA]").

## Arquivos do repositório
- `historico-temas-lives-empreendedorismo.md` — histórico do Bloco 1 (anti-repetição).
- `historico-temas-lives-livre.md` — histórico do Bloco 2 (anti-repetição).
- `selecao-temas-lives.md` — curadoria: analista marca os vencedores de cada ciclo.

## Notas operacionais
- A escrita no GitHub exige que o GitHub App tenha permissão `contents: write` neste repo.
  Push é feito para o branch `main`.
- O contexto completo da marca (crenças, valores, territórios, público, proibições) e o
  formato de saída detalhado vêm no prompt agendado da rotina.
