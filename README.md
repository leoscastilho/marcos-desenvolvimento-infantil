# Marcos do Desenvolvimento Infantil

**Roteiro interativo de acompanhamento do desenvolvimento de 2 meses a 5 anos**, baseado na cartilha *Aprenda os Sinais. Aja cedo.* — tradução brasileira do programa **Learn the Signs. Act Early.** do CDC, publicada pela Sociedade Brasileira de Pediatria.

É uma página estática única (`index.html`), sem servidor, sem build, sem banco de dados e sem qualquer armazenamento: ao fechar a aba, todas as respostas desaparecem.

---

## O que ela faz

A cartilha original é uma lista de verificação por idade: você olha a página dos 18 meses e confere os marcos dos 18 meses. Isso tem um problema conhecido — quem responde já sabe qual é a resposta "certa" e tende a confirmá-la.

Esta página inverte a ordem. **A idade só é perguntada no fim.** Antes disso, você percorre quatro áreas do desenvolvimento respondendo etapas cada vez mais avançadas, sem saber a que idade cada uma corresponde. O perfil é montado depois, comparando o que a criança de fato faz com o que se espera para a idade informada.

### As quatro áreas

| Área | O que observa |
|---|---|
| Social e Emocional | Como a criança se relaciona, demonstra afeto e reage às pessoas |
| Linguagem e Comunicação | Como se comunica, entende e usa palavras e gestos |
| Cognitivo | Como aprende, pensa e resolve problemas |
| Movimento e Desenvolvimento Físico | Como se move, equilibra e usa as mãos |

Cada área tem **12 etapas** em ordem crescente, correspondendo às faixas da cartilha: 2, 4, 6, 9, 12, 15 e 18 meses; 2 anos; 30 meses; 3, 4 e 5 anos. São 159 marcos no total.

---

## Como funciona

### 1. A escada de dificuldade

As etapas sobem sempre. Você começa pelos marcos mais elementares da área e avança. Como as idades ficam ocultas, não há como "pular para o nível certo": para chegar aos marcos de 3 anos é preciso ter confirmado os de 2 anos e 30 meses antes.

Cada etapa aceita quatro respostas:

- **Já faz** — faz tudo o que está na lista, sozinha e com frequência
- **Faz em parte** — faz alguns itens, outros ainda não
- **Ainda não faz** — nenhum item, ou quase nenhum
- **Não sei dizer** — nunca observou ou tem dúvida

Só **Já faz** conta como etapa alcançada. *Faz em parte* aparece no resultado como etapa emergente (marcada com `+`), mas não é creditada.

### 2. Onde a escada para

A área termina quando aparecem **duas respostas seguidas** que não sejam "Já faz". A regra é deliberada: um tropeço isolado não encerra a área. Uma criança que ainda não faz nada de uma etapa mas faz tudo da seguinte continua subindo, e o crédito vai para a etapa mais alta confirmada.

Na prática, cada área custa entre 3 e 12 perguntas. Para uma criança de 2 anos, o roteiro inteiro fica em torno de 40 perguntas — de 5 a 10 minutos.

### 3. As perguntas do fim

Só depois das quatro áreas a página pede:

- **A idade real** (anos e meses)
- **Prematuridade** — se sim, com quantas semanas nasceu. Abaixo dos 2 anos, a comparação passa a usar a **idade corrigida**, como é o padrão clínico
- **Perda de habilidade já conquistada**
- **Se algo preocupa quem respondeu**

### 4. O resultado

Um gráfico de quatro pistas, uma por área, preenchida até a etapa alcançada, com um marcador vertical na etapa esperada para a idade:

- **Verde** — no esperado ou acima
- **Âmbar** — uma etapa atrás
- **Coral** — duas etapas ou mais atrás

Abaixo do gráfico vêm os alertas, nesta ordem de peso:

1. **Perda de habilidade** — tratada como o sinal mais importante da página, independentemente de qualquer outra resposta
2. **Áreas duas ou mais etapas atrás** — sugere pedir triagem do desenvolvimento e, se a preocupação persistir, encaminhamento
3. **Áreas com os marcos da idade incompletos** — não é alarme, é anotação para a próxima consulta
4. **Desenvolvimento desigual** — quando a diferença entre a área mais avançada e a mais atrasada chega a duas etapas. Estar à frente em uma área não compensa o atraso em outra, e a distância entre elas é informação clínica por si só
5. **Excesso de "não sei dizer"** — indica que o perfil ficou menos confiável e vale reobservar
6. **Janela de triagem recomendada** — lembrete aos 9, 18, 24 e 30 meses (com triagem de autismo aos 18 meses e 2 anos)

Cada área traz ainda a lista exata dos marcos que faltam para a idade, e há um botão de imprimir/salvar em PDF para levar à consulta.

---

## O que ela não é

Não é triagem, não é exame e não é diagnóstico. Os marcos representam o que a maioria das crianças (75% ou mais) faz em cada idade — são um ponto de partida para a conversa, não um corte diagnóstico. A própria cartilha original afirma que a lista **não substitui uma ferramenta de triagem do desenvolvimento padronizada e validada**.

Quem avalia o desenvolvimento de uma criança é o pediatra. A finalidade desta página é chegar à consulta com observações organizadas.

---

## Fontes

### Conteúdo dos marcos

**Learn the Signs. Act Early.** — Centers for Disease Control and Prevention (CDC), programa de identificação precoce de atraso do neurodesenvolvimento.
<https://www.cdc.gov/ncbddd/actearly/>

### Tradução brasileira

**Cartilha de Desenvolvimento — 2 meses a 5 anos. Aprenda os sinais. Aja cedo.**
Sociedade Brasileira de Pediatria (SBP) em parceria com o CDC, mediante devida autorização, e Sociedade Paraibana de Pediatria. Distribuída em eventos regionais e nacionais da SBP em 2024 e disponibilizada para download no site da SBP.

- **Tradução:** Liubiana Arantes de Araújo (Presidente do Departamento Científico de Pediatria do Desenvolvimento e Comportamento — SBP) e Flávio Melo (Sociedade Paraibana de Pediatria)
- **Revisão:** Dirceu Solé, Clóvis F. Constantino, Luciana Rodrigues Silva
- **Apresentação:** Clóvis Francisco Constantino, Presidente da SBP

Site da SBP: <https://www.sbp.com.br>

### Recomendações de triagem

As janelas de triagem citadas (9, 18, 24 e 30 meses; triagem de autismo aos 18 e 24 meses) seguem a recomendação da **Academia Americana de Pediatria**, conforme indicado na cartilha.

### Sobre o texto dos marcos

Os marcos foram reescritos para o formato de pergunta e para leitura em tela, mantendo o sentido clínico da cartilha. A ordem das faixas etárias, o agrupamento por área e as recomendações de conduta vêm do material original.

---

## Publicando

Qualquer hospedagem de arquivos estáticos serve. No GitHub Pages:

```bash
git init
git add index.html README.md
git commit -m "Marcos do Desenvolvimento Infantil"
gh repo create marcos-desenvolvimento-infantil --public --source=. --push
gh api -X POST repos/:owner/marcos-desenvolvimento-infantil/pages \
  -f 'source[branch]=main' -f 'source[path]=/'
```

O arquivo precisa se chamar `index.html` na raiz. Não há dependências externas, então funciona igualmente offline, aberto direto do disco.

## Direitos

Materiais produzidos pelo CDC são, em geral, de domínio público nos Estados Unidos. A tradução em português foi realizada pela SBP **mediante autorização do CDC** — antes de redistribuir, adaptar comercialmente ou usar institucionalmente esta página, verifique os termos com a Sociedade Brasileira de Pediatria. Mantenha os créditos ao CDC, à SBP e à Sociedade Paraibana de Pediatria visíveis, como estão no rodapé da página.