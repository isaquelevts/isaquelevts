# Análise dos 15 reels virais — formato "Se você… Então você… Mas…"

Baixei os 15 reels, transcrevi o áudio (Whisper, com timestamps) e analisei os frames. Publicados entre **18/10 e 03/11/2026**, ou seja, uma onda de duas semanas.

> Transcrições automáticas têm erros de ouvido (ex.: "Via Duto" = viaduto, "Cash" = cache). Os textos limpos estão em `transcricoes/`.

---

## 1. O que descobri em uma frase

Todos os 15 são **o mesmo formato**: uma animação 3D low-poly em que um boneco "reinventa" um objeto do dia a dia (telhado, motor, elevador, ar-condicionado, API…) resolvendo **um problema de cada vez**. Cada solução cria o problema seguinte. O espectador nunca recebe uma aula, recebe uma **cadeia de "e se…?"** que ele mesmo resolve na cabeça antes do narrador.

Cinco perfis usam o mesmo motor: **Desmontando o Mundo** (o maior), **Você Construiu!**, **Desconstruindo Universo**, **Desmontando SaaS** (tema API/software) e variações. Mesmo boneco (amarelo, capacete), mesma estética, mesma estrutura de roteiro.

---

## 2. Os 15 vídeos organizados

Ordenados por curtidas. Duração entre 89 s e 173 s (reels **longos**, e ainda assim viralizaram).

| # | Perfil | Tema | Data | Curtidas | Coment. | Duração |
|---|---|---|---|---|---|---|
| 1 | Desmontando o Mundo | Telhado (`DezX76zgi47`) | 22/10 | **1,88 M** | 14,8 k | 165 s |
| 2 | Desmontando o Mundo | Muro de arrimo (`DfK3j32JpGS`) | 31/10 | **1,42 M** | **23,7 k** | 143 s |
| 3 | Desmontando o Mundo | Motor de carro (`De1UcmxEpJb`) | 23/10 | 840 k | 4,1 k | 171 s |
| 4 | Desmontando o Mundo | Elevador (`De9BsRpq6Dm`) | 26/10 | 660 k | 4,1 k | 173 s |
| 5 | Desmontando o Mundo | Casa (`DfGDJfVvRlD`) | 29/10 | 565 k | 2,5 k | 169 s |
| 6 | Você Construiu! | Trevo rodoviário (`DfCYLMRSl9H`) | 28/10 | 551 k | 2,8 k | **89 s** |
| 7 | Desmontando o Mundo | Ar-condicionado (`DewJ1whAl3p`) | 21/10 | 346 k | 1,7 k | 142 s |
| 8 | Desconstruindo Universo | Peixe e anzol (`DfAlqLeBl2M`) | 27/10 | 183 k | 548 | 171 s |
| 9 | Você Construiu! | Linha de transmissão (`DfK-3TAPaol`) | 31/10 | 118 k | 350 | 96 s |
| 10 | Você Construiu! | Estação de tratamento de água (`DfHpCk1OEdm`) | 30/10 | 90 k | 398 | 112 s |
| 11 | Você Construiu! | Telhado (`DepQxtuMGSM`) | 18/10 | 53 k | 286 | 99 s |
| 12 | Você Construiu! | Posto de gasolina (`DfM2RoQhI0d`) | 01/11 | 44 k | 237 | 173 s |
| 13 | Desconstruindo Universo | El Niño (`DfS99qjRLaK`) | 03/11 | 9,3 k | 80 | 171 s |
| 14 | Desconstruindo Universo | Linha de pesca / peixe 20 kg (`DfSSII0hl1O`) | 03/11 | 9,2 k | 39 | 169 s |
| 15 | Desmontando SaaS | O que tem dentro de uma API (`DfAyGeFM_FC`) | 27/10 | 8,4 k | 84 | 146 s |

### Gancho, dúvida inicial e fecho de cada um

| Tema | Gancho (primeira fala / título na tela) | Dúvida que o espectador já tinha | Fecho / CTA |
|---|---|---|---|
| Telhado | "Se você levanta as paredes e fecha em cima com uma laje reta, a chuva não tem pra onde ir." | Por que telhado tem esse formato e tantas peças (ripa, caibro, rufo, calha)? | "Se sabia, comente **engenheiro**. Se não sabia, comente **estagiário**." |
| Muro de arrimo | "Se você cortar o barranco pra fazer vaga pro carro, você não vai ter uma garagem, vai ter um **carro enterrado**." | Por que alguns muros caem e aqueles canos ficam pingando? | "Comenta **Criador** se quer aprender a criar um vídeo desses em um dia." |
| Motor | "Se você quer ir longe sem cansar as pernas, precisa de uma força que não cansa." (boneco de bicicleta) | Como a gasolina vira movimento? | "Se sabia, comente **motorista**. Se não, **autoescola**." |
| Elevador | "Se você precisa subir um monte de andares e só tem uma escada…" | Como o elevador não cai? | "Comenta **quero** e segue" (oferta de ensinar a fazer o vídeo) |
| Casa | "Se você levantar quatro paredes de tijolo, não vai ter um quarto, vai ter um monte de inclinado." | O que existe antes e dentro da parede? | "Se sabia, comente **pedreiro**. Se não, **servente**." |
| Trevo | "Se você cruzar a Avenida direto com a Rodovia, os carros já entram. Mas quem atravessa de frente leva batida de lado." | Por que um trevo tem aquele desenho "esquisito"? | "Manda a palavra **3D** na DM." |
| Ar-condicionado | "Se você tá morrendo de calor e põe um balde de gelo na frente do ventilador…" | De onde vem o frio? Por que pinga? Por que recarregar gás? | "Comente **frio** se você não sabia dessa." |
| Peixe/anzol | **Título na tela:** "Como o peixe morde a isca com o anzol à mostra?" | O peixe não vê o anzol? | "Qual coisa do dia a dia a gente desconstrói? **A mais curtida vira vídeo.**" |
| Transmissão | "Se você puxar um fio da usina até a cidade, a energia chega nas casas. Mas…" | Por que as torres são altas e a tensão é "absurda"? | "Quer aprender a fazer vídeos assim? Link na bio." |
| Água (ETA) | "Se você puxar a água do rio e mandar direto pras casas…" | O que acontece com a água antes da torneira? | "Link na bio." |
| Telhado (Você Construiu) | "Se você deitar tábuas por cima das paredes, vai ter um telhado, mas a chuva vai…" | Por que tem calha, rufo, "represa de gelo"? | "Comente **3D**" (na legenda) |
| Posto | "Se você deixar a gasolina num tambor na beira da rua, os carros já abastecem." | Por que tanta coisa num posto? | "Link na bio." |
| El Niño | "Por que o mundo inteiro está com medo do El Niño?" + notícia: "Em outubro, a Inglaterra pediu para o povo guardar água e comida…" | O que é o El Niño e por que mexe com o preço do chocolate? | "E aí na sua cidade? Seca? Enchente? **Comenta aí.**" |
| Linha de pesca | **Título na tela:** "Como uma linha tão fina segura 20 kg?" | Como 6 kg de linha seguram 20 kg de peixe? | "Qual foi o maior peixe que já escapou de você?" |
| API | "O que tem dentro de uma API? **14 peças!** E a primeira existe por um motivo." | O que são rota, controller, model? | "Comenta qual peça você quer ver desmontada." |

---

## 3. A estrutura de roteiro (a fórmula)

### Esqueleto repetido em todos

```
[0–5 s]    GANCHO: "Se você [faz a coisa mais ingênua possível]…" + consequência visceral
[5–10 s]   1º PROBLEMA aparece no mesmo fôlego
LOOP (repete 5–16×, uma volta a cada ~10–15 s):
           "Então você [solução simples, em linguagem de criança]."
           "Esse(a) é o(a) [NOME TÉCNICO]."        ← o nome só vem DEPOIS da função
           "Mas [a solução cria um problema novo]…"
[~85–90%]  "É por isso que…" (liga ao que o espectador já viu na vida real)
[fim]      "Coloque [piada: sofá, cachorro, musiquinha chata]."
           "Parabéns! Você construiu um [objeto]."
           CTA (identidade/comentário ou palavra-chave no DM)
```

### Contagem real por vídeo (do roteiro transcrito)

| Vídeo | "Mas…" | "Então você…" | "Esse é o X" | "É por isso que…" | Palavras |
|---|---|---|---|---|---|
| Telhado (1,88 M) | 10 | 11 | 10 | 0 | 541 |
| Muro (1,42 M) | 6 | 6 | 6 | **4** | 511 |
| Motor | 6 | 10 | 12 | 0 | 559 |
| Elevador | 10 | 10 | 11 | 0 | 552 |
| Casa | 8 | 7 | 10 | 3 | 575 |
| Trevo | 7 | 7 | 7 | 0 | 251 |
| Posto | 16 | 16 | 16 | 0 | 746 |

Cadência de fala: **~190–200 palavras/min** (541 palavras em 165 s). Rápido, coloquial, sem pausas dramáticas.

---

## 4. Anatomia do gancho

Três tipos aparecem na amostra:

**A. "Se você [ação ingênua]…" (sem título na tela).** É o dos 7 maiores. A promessa não está numa pergunta, está numa **situação** que o espectador visualiza: *carro enterrado*, *balde de gelo no ventilador*, *quatro paredes de tijolo sem fundação*. A frase termina antes de explicar. Cria dois sentimentos juntos: "eu faria isso" e "o que vai dar errado?".

**B. Pergunta-curiosidade com título gigante.** "Como o peixe morde a isca com o anzol à mostra?", "Como uma linha tão fina segura 20 kg?". Título em caixa alta, palavra-chave destacada em amarelo, **círculo vermelho** no ponto da dúvida. A pergunta contradiz o senso comum (peixe *vê* o anzol; 6 kg segurando 20 kg).

**C. Notícia/medo + promessa numerada.** "Por que o mundo inteiro está com medo do El Niño?" (apoiado em notícia real) e "O que tem dentro de uma API? **14 peças!**". O número promete escopo fechado.

Em todos os casos, **o primeiro frame já tem o cenário e o boneco**; não há intro, logo ou "oi, pessoal".

---

## 5. Por que isso viraliza (os mecanismos)

1. **Loop aberto permanente.** Cada "Mas…" abre uma pergunta antes de fechar a anterior. Num vídeo de 2–3 minutos há uma nova tensão a cada ~10–15 s. É isso que sustenta retenção em reel longo.
2. **O espectador "inventa" o objeto.** Antes de a solução aparecer, quem assiste já pensa "ah, precisa de um suporte". Acertar na cabeça dá prazer, errar dá curiosidade. Por isso o tom é "**você** construiu", não "o engenheiro projetou".
3. **Nome depois da função.** "Aí você põe um eixo cheio de calombos… esse é o comando de válvulas." O termo técnico vira **recompensa**, não barreira. Cada vídeo ensina 6–16 palavras sem parecer aula.
4. **Consequência concreta e meio engraçada.** Carro enterrado, cabine que desce sozinha "cada vez mais rápido", "um tio jurando que é o fim do mundo". Risco físico ou prejuízo causa tensão imediata sem precisar de explicação.
5. **Fatos contraintuitivos pontuais.** "Parece ao contrário, mas é virando à direita que você vai pra esquerda" (trevo); alta tensão esquenta *menos* o cabo (transmissão); o ar-condicionado "não fabrica frio, só transporta calor"; o peixe quase não pesa dentro d'água. São as frases que as pessoas **compartilham e salvam**.
6. **"É por isso que…" liga ao cotidiano.** Mofo no pé da parede, rachadura torta saindo do canto da janela, canos pingando depois da chuva, pescador que cospe no nó. O espectador reconhece algo que já viu e sente que "agora entendo o mundo". Aparece mais nos vídeos de maior engajamento (muro: 4×, casa: 3×).
7. **Quase todo mundo é "dono" do assunto.** Casa, telhado, carro, ar-condicionado, elevador: coisas que todos usam e nunca entenderam. Amplo, sem nicho.
8. **Comentário fácil, com identidade e provocação leve.** "Sabia → engenheiro / não sabia → **estagiário**", "motorista / autoescola", "pedreiro / servente". Binário, zero esforço, um pouco de zoeira. Gera comentário em massa, o que empurra o algoritmo.
9. **Palavra-chave no comentário → DM (a "máquina" de comentários).** O muro de arrimo tem **23,7 mil comentários** (o maior), com CTA "comenta *Criador*". Os perfis Você Construiu!, Desmontando o Mundo e correlatos usam "3D", "quero", "link na bio" para vender o **método de criar esse tipo de vídeo**.
10. **Formato serial e replicável.** O mesmo esqueleto serve para qualquer tema, então dá para publicar várias vezes por dia/semana. Isso treina o algoritmo e a audiência ("mais um daqueles").

---

## 6. Produção visual

- **9:16, 1080×1920, 30 fps.** Animação 3D low-poly, cores saturadas (céu azul, grama verde), boneco amarelo com capacete.
- **Legenda palavra por palavra**, branca, fonte grossa, centralizada abaixo do meio da tela. Mantém o olho preso e funciona sem som.
- **Cortes de seção (cutaway)** mostrando o interior (terra, concreto, tubulação), com **setas vermelhas** indicando força e **etiquetas** que aparecem quando o nome é dito (ex.: "CANALETA").
- **Construção cumulativa**: a cena vai ganhando peças; a "falha" é mostrada visualmente antes da correção (carro com vidro trincado, muro tombando).
- **Câmera orbitando/isométrica** e ícones de avance rápido (⏩) em partes repetitivas.
- **Confete no "Parabéns"** do final.
- Títulos em caixa alta com **palavra-chave amarela** e círculo vermelho apenas nos formatos B/C.
- Nenhum rosto real, nenhum apresentador; narrador em off.

---

## 7. O que performou melhor e o que eu *não* consigo afirmar

**Padrões nos mais curtidos:**
- Todos os **7 primeiros** usam o gancho tipo A ("Se você…"), sem título na tela.
- Temas **muito domésticos e universais** (telhado, casa, motor, elevador, ar-condicionado, muro) vencem temas de nicho (API, linha de pesca) ou técnicos (ETA, linha de transmissão).
- O muro de arrimo combina **risco de prejuízo pessoal** ("carro enterrado"), muitos "É por isso que…" e a **palavra-chave de DM**. Foi o que mais gerou comentários.
- O trevo, com **só 89 s**, rendeu 551 k: curto e denso também funciona.

**Ressalvas honestas:**
- Não tenho **visualizações nem retenção** (o Instagram não expõe), só curtidas e comentários. Não dá para afirmar nada sobre o ponto exato em que as pessoas saem.
- Os formatos B/C e os perfis Desconstruindo Universo/Desmontando SaaS são **mais novos e menores** (postados em 27/10–03/11). Então não dá para separar "o gancho é pior" de "a conta é menor e o vídeo é mais recente". É plausível que tipo A seja melhor, mas **não está provado**.
- Amostra de 15 vídeos, escolhida por você (viés de sobrevivência: só vi o que viralizou).

---

## 8. Template de roteiro para reaproveitar

```
GANCHO (0–6 s)
"Se você [ação mais ingênua possível com o objeto], você não vai ter [objeto],
 vai ter [consequência absurda/visceral]."

LOOP × 8–12
"Então você [solução em linguagem de criança, 1 frase]."
"Esse(a) é o(a) [NOME TÉCNICO]."
"Mas [problema criado pela solução, com consequência concreta]."
  → a cada 2–3 loops: "É por isso que [coisa do cotidiano que o espectador já viu]."
  → 1–2 vezes: "Parece ao contrário, mas…" (fato contraintuitivo)

FECHO (últimos 15 s)
"Coloque [3 itens banais + 1 piada]."
"Parabéns! Você construiu [objeto]."
CTA de comentário binário com identidade ("Se sabia, comente X. Se não, comente Y.")
  ou palavra-chave para DM / pergunta "qual objeto desmontamos?"
```

**Checklist antes de gravar:**
1. O objeto é algo que o público usa/vê todo dia?
2. O ingênuo "primeiro passo" é reconhecível ("eu faria assim")?
3. Cada "Mas…" é uma consequência *física e concreta*, não abstrata?
4. O nome técnico só aparece depois da função?
5. Há pelo menos 2 "É por isso que…" ligados ao cotidiano?
6. Há 1–2 fatos contraintuitivos para quem assiste salvar/compartilhar?
7. O CTA pede algo de **1 palavra**?
8. Dá para fazer em 90–170 s sem enrolar?

---

## 9. Ideias de tema com o mesmo DNA

Chuveiro elétrico, geladeira, fogão a gás, caixa d'água/bomba, barragem, ponte, tubulação de esgoto, fossa/biodigestor, microondas, torre de celular, wi-fi, pen drive, botijão de gás, extintor, para-raios, cadeado, fechadura, piscina (filtro/cloro), estrada (asfalto/drenagem), prédio (fundação/pilotis), caixa de luz/disjuntor, elevador de carga, escada rolante, porta corta-fogo.

---

## 10. Arquivos desta pasta

- `videos/` — os 15 `.mp4` originais
- `transcricoes/` — o roteiro de cada vídeo com timestamps
- `frames/00_ganchos_primeiro_frame.png` — primeiro frame de cada vídeo lado a lado
- `frames/*_timeline.png` — linha do tempo visual de 3 vídeos (muro, pesca, trevo)

A ordem dos primeiros frames em `00_ganchos…` (esquerda→direita, cima→baixo) é a ordem alfabética dos IDs: De1Ucmx, De9Bs, DepQx, DewJ1, DezX7 / DfAlq, DfAyG, DfCYL, DfGDJ, DfHpC / DfK-3, DfK3j, DfM2R, DfS99, DfSSI.
