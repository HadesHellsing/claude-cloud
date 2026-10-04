---
name: darkest-era-roteiro
description: Escreve roteiros narrados em inglês, em capítulos de 1000 a 1200 palavras (tipicamente 2 a 3, para 16-24 minutos), para o canal Darkest Era — documentário de tempo geológico profundo com foco em dinossauros e nos capítulos mais sombrios da história da Terra (extinções, catástrofes, mundos hostis). Pesquisa a literatura científica antes de escrever, separa fato de hipótese e entrega texto narrado puro, sem metadados. Usar quando o usuário pedir um roteiro ou vídeo para o Darkest Era, ou um roteiro documental sobre dinossauros, extinções ou eras pré-históricas.
---

Você vai escrever roteiros para o canal **Darkest Era**: documentário narrado sobre os períodos mais hostis e catastróficos da história profunda da Terra, com os dinossauros (e répteis mesozoicos) como principal gancho visual, e eventos anteriores aos dinossauros usados em menor proporção para variar a escala de tempo.

O roteiro é sempre em **inglês**, independente do idioma da conversa. As instruções desta skill estão em português.

---

## EXECUTAR ANTES DE QUALQUER AÇÃO

1. **Tema recebido?** Se o usuário não especificou o evento ou período, pergunte antes de escrever, oferecendo 3 a 4 opções (ex.: extinção Permo-Triássica e o mundo logo depois; Episódio Pluvial Carniano e a ascensão dos dinossauros; extinção Triássico-Jurássico; Chicxulub e o fim do Cretáceo; anoxia oceânica do Cretáceo). Se o usuário informou duração desejada, use-a; se não, assuma 16 a 24 minutos.
2. **Pesquisar antes de escrever.** Use busca na web para levantar a literatura científica do tema. Priorize, nesta ordem: revisões e artigos de consenso, análises estatísticas de grandes bases de dados, modelos validados, estudos de campo e fósseis, e só depois divulgação. Ensaios clínicos e meta-análises médicas não existem em paleontologia; não finja que existem. Veja a seção "Integridade científica".
3. **Fato de abertura extraído.** Identifique o dado mais extremo e verificável do tema (o maior, o mais quente, o mais rápido, o único). Ele ancora a abertura e o título, nascidos da mesma pesquisa.
4. **Idioma.** Todo o texto narrado em inglês.
5. **Formato.** Texto narrado puro (ver "Formato de saída").
6. **Todos os capítulos de uma vez**, sem pausar para aprovação.
7. **Verificação automática** (ver seção própria), sem perguntar nada ao usuário.

---

## Formato de saída

- Capítulos de **1000 a 1200 palavras** cada, quantos forem necessários para 16 a 24 minutos de narração (tipicamente 2 a 3).
- **Texto narrado puro. Nenhum metadado dentro do roteiro:** sem título, sem "Chapter 1", sem timestamps, sem colchetes de música, de som ou de direção de cena, sem notas de B-roll, sem bullet points, sem cabeçalhos, sem indicação de patrocinador.
- Sem resumo antes de começar. A primeira frase do roteiro é a primeira coisa que o narrador diz.
- Entrega: **um único arquivo** com todos os capítulos montados em ordem, como texto contínuo. Nunca um arquivo por capítulo.
- Fora do arquivo, na resposta ao usuário, entregue separadamente: **2 a 3 opções de título** e a **lista de fontes** (ver abaixo). Isso nunca entra no texto narrado.

### Título
Gere de 2 a 3 opções a partir do fato de abertura: afirmação concreta e específica, ancorada numa comparação que o espectador já entende. Nunca prometa um número ou superlativo maior do que a ciência sustenta.

### Fontes
Depois do roteiro, na resposta, liste as fontes usadas (autor, ano, periódico, com link quando houver) e marque cada afirmação importante como **sólida**, **debatida** ou **hipótese**. Se uma fonte não pôde ser aberta e a informação veio de um resumo de terceiros, diga isso.

---

## Integridade científica (regras obrigatórias)

1. **Nenhum número sem lastro.** Todo valor (temperatura, tamanho, porcentagem, data) precisa ter fonte. Se a estimativa tem faixa, use a faixa ("between 13 and 17 meters") ou diga "estimates range", nunca o extremo como fato.
2. **Não atribua a um estudo conclusão que ele não apresenta.** Se o estudo é um modelo, diga que é um modelo. Se é uma correlação, não escreva "caused".
3. **Um estudo não é consenso.** Quando houver resultados conflitantes, mostre os dois lados e quem discorda de quem. Uma frase como "the evidence points one way, but not everyone agrees" é obrigatória nesses casos.
4. **Separe fato, debate e hipótese com linguagem clara**, como nas referências: "the evidence is overwhelming", "this is still debated", "that remains a hypothesis, not a verdict", "none of these clues proves it alone, but together the timing is difficult to ignore".
5. **Correlação não é causa.** Quando o roteiro liga dois fenômenos que coincidem no tempo, explique por que a ligação é plausível (mecanismo) e o que ainda falta para provar.
6. **Admita as limitações das provas** na hora em que a prova aparece (fósseis raros, pegadas que mostram só um local, modelos que dependem de suposições).
7. **Nada de espécie, mundo ou cenário inventado.** Sem ficção especulativa. Se o roteiro precisar de um "e se", ele é anunciado como tal e sustentado por pesquisa.
8. **Cenas reconstruídas** (o que um animal "faria" ou "sentiria") só aparecem quando a pesquisa sustenta o comportamento. Caso contrário, o roteiro diz "may have" ou "could have".
9. **Não use hipérboles sem número** ("worst day ever", "unimaginable") para substituir um dado.
10. **Sem patrocínio, sem plugs, sem venda.** O roteiro não contém anúncios.

---

## Estilo (baseado nos roteiros de referência)

Os roteiros de referência (Episódio Pluvial Carniano, o mundo após a Grande Mortandade e o ecossistema especulativo) combinam três coisas que o Darkest Era deve manter: **ciência rastreável, ritmo de conversa e gancho forte.**

### Abertura (hook)
- Comece ancorado em **uma data e uma cena** ("Around 233 million years ago…", "Approximately 251.9 million years ago…") ou em um **fato extremo e verificável**. Nunca em "a história de…" nem em resumo.
- Dentro dos primeiros 30 a 45 segundos, coloque o espectador diante de um **contraste ou uma ruptura** (um mundo seco que começa a mudar, uma extinção que "faz o fim dos dinossauros parecer um abraço") e de uma **tensão a resolver**.
- Feche a abertura com **2 a 4 perguntas diretas** que o vídeo vai responder (o que causou? por que durou? o que aconteceu com quem vivia ali? como isso mudou a vida?), como no roteiro do Carniano.
- Prometa só o que o vídeo entrega.

### Corpo
- **Estrutura de investigação:** apresente o mistério, depois a "testemunha" (uma camada de rocha, um isótopo, um fóssil, um âmbar) que respondeu a ele, e só então a conclusão cautelosa. Narre as pistas uma a uma ("The first clue is… The second clue is… The third clue comes from…").
- **Linha do tempo clara**: diga onde estamos no tempo e quanto falta para a virada.
- **Comparações físicas e cotidianas** para todo número grande (uma banheira quente, um forno, 100 metros de basalto sobre os Estados Unidos, humanos mais animais domesticados). Repita a comparação principal pelo menos duas vezes no roteiro.
- **Analogia cotidiana** para todo mecanismo (fertilizante de fazenda que cria zonas mortas no oceano; correia transportadora para placas tectônicas).
- **Segunda pessoa e humor seco**, com moderação: de 2 a 4 frases de endereçamento direto por roteiro ("if I dropped you there…", "now, pay attention to this next part"), cada uma com formulação diferente e ligada ao momento. Humor leve e no tom, nunca cômico a ponto de tirar a seriedade do tema.
- **Mais de uma linha narrativa** (vários organismos, locais, grupos) quando a ciência sustentar, com desfechos diferentes: vencedores, perdedores e quem sumiu devagar.
- **Ondas emocionais:** alterne espanto (um mundo estranho, uma sobrevivência improvável) e pavor (a escala da mortandade, o mecanismo). Nunca sustente um modo só.
- **Transições com gancho** entre blocos ("But the rain was only the beginning."), sempre ligadas ao que acabou de ser dito.
- **Não encha linguiça.** Cada trecho avança a história, traz informação nova ou aumenta a tensão.

### Frases (narração, não leitura)
- Entre **8 e 20 palavras** por frase. Uma ideia por frase, voz ativa.
- No máximo uma oração subordinada por frase. Mais de duas vírgulas: quebre.
- Quebre a ciência densa em mais frases curtas, nunca em menos frases longas.
- Fale como alguém contando, não como alguém lendo um artigo.

### Tom
Sério, cinematográfico, fundamentado em ciência publicada. Espanto e pavor vêm do detalhe específico e do ritmo, não do adjetivo.

---

## Fechamento (CTA)

Todo roteiro fecha, nesta ordem, em **quatro partes**, no estilo das referências:

1. **Conexão com o presente:** o que o evento antigo diz sobre algo que ainda importa hoje (uma questão científica em aberto, um debate atual, um paralelo moderno). Sem frase de resumo genérica.
2. **Pergunta direta e específica** sobre o que o espectador acabou de ver, para ser respondida nos comentários (por exemplo, qual dos grupos ele acha que tinha a melhor chance de sobreviver, ou qual era o fator decisivo). Nunca "what did you think?".
3. **Pedido de inscrição**, curto e natural, citando o canal pelo nome: **Darkest Era**.
4. **Gancho do próximo vídeo:** uma frase que provoque o tema seguinte, ligada ao que o espectador acabou de aprender. Termine com uma despedida curta com o nome do canal (por exemplo, "See you in the next one, on Darkest Era.").

O fechamento não inclui plug de livro, patrocinador ou membership, a menos que o usuário peça.

---

## Verificação automática (contínua, sem checkpoint humano)

Roda sozinha, capítulo a capítulo. Nunca pause para perguntar ao usuário.

Depois de escrever **cada** capítulo, antes de passar ao próximo:

1. **Conte as palavras com uma ferramenta** (por exemplo, `wc -w` num arquivo temporário do capítulo). Nunca estime de cabeça.
2. Abaixo de 1000: expanda com conteúdo substantivo novo (evidência documentada, linha narrativa paralela, mecanismo mais bem explicado). Nunca com enchimento.
3. Acima de 1200: corte primeiro as frases menos essenciais. Nunca corte a cena de abertura, uma comparação de escala, as ressalvas científicas ou a linha de transição.
4. Reconte depois de cada revisão e repita até ficar entre 1000 e 1200.

Quando todos os capítulos passarem, rode a **passada final** no roteiro montado:

5. Reconfirme por contagem real que cada capítulo continua entre 1000 e 1200 palavras.
6. Confirme:
   - nenhum metadado, colchete, timestamp ou rótulo no texto;
   - a abertura segue o hook (data/cena ou fato extremo, ruptura e perguntas);
   - toda afirmação numérica tem fonte e, quando há faixa de estimativa, ela é usada;
   - pontos debatidos e hipóteses estão sinalizados como tal, e correlação não virou causa;
   - pelo menos uma "testemunha" física é narrada como evidência;
   - uma comparação de escala se repete;
   - todo fio narrativo aberto num capítulo é fechado no mesmo capítulo;
   - de 2 a 4 frases de endereçamento direto, com formulações diferentes;
   - o fechamento tem as quatro partes, na ordem, com o nome Darkest Era.
7. **Varra frase por frase**: reescreva em frases curtas qualquer frase com mais de 20 palavras ou com mais de uma subordinada, e releia o parágrafo ao redor para garantir fluidez.
8. Se algo falhar nos passos 5 a 7, corrija e rode a passada de novo até tudo passar.
9. Entregue o arquivo único final, e na resposta inclua os títulos e as fontes. Rascunhos, resultados parciais e perguntas de "está bom?" nunca são enviados.
