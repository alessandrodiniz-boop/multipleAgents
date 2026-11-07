# Pipeline Potencial 2027: potencial calculado e plano de abertura

Proposta para substituir o slide 12 do deck "Planejamento 2027 - Comercial". Data: 07/11/2026.

Convenções:
- **Potencial calculado** = número de unidades de compra × ticket da oferta, nas contas-alvo. Não é o tamanho do mercado.
- **Abertura de pipeline** = meta de oportunidades abertas ao longo de 2027, e não de contratos fechados.
- Valores em R$ milhões, pelo valor do primeiro contrato (no caso de oferta recorrente, um ano).
- **[Estimativa]** marca uma premissa minha que ainda não foi validada pela Zukk.

---

## 1. Área urbana das concessões: potencial de Poda e Risco Climático

### Método

1. **Municípios de cada distribuidora.** A base IndQual Município da ANEEL liga cada município aos conjuntos elétricos que o atendem. Os limites de continuidade da ANEEL dizem a qual distribuidora pertence cada conjunto (anos de 2024 a 2026). Usei os dois arquivos com geração em 05/11/2026.
2. **Área urbanizada por município.** Tabela "Áreas Urbanizadas do Brasil 2022" do IBGE, publicada em 14/09/2026. Usei a coluna "Áreas urbanizadas" (densas + pouco densas), que no Brasil soma 48.844 km². Ficam de fora os loteamentos vazios, os vazios intraurbanos e outros equipamentos urbanos.
3. **Município atendido por mais de uma distribuidora.** A área foi dividida pela proporção de conjuntos elétricos de cada empresa no município. Exemplo: na cidade de São Paulo, a Enel SP tem 111 conjuntos e a cooperativa Ceris tem 1, então 99% da área vai para a Enel SP. Sem essa divisão (área cheia), o total dos 4 grupos sobe de 20.553 para 21.898 km².
4. **Valor.** Ticket de R$ 0,8 mi por lote de 750 km², ou seja, R$ 1.067 por km².

### Resultado

| Grupo | Distribuidoras | Municípios | Área urbana (km²) | Potencial calculado (R$ mi) |
|---|---|---|---|---|
| Neoenergia | Coelba 3.133 · Elektro 1.713 · Neoenergia PE 1.539 · Cosern 852 · Neoenergia Brasília 633 | 1.001 | **7.870** | 8,4 |
| CPFL | CPFL Paulista 2.730 · RGE 2.247 · CPFL Piratininga 962 · CPFL Santa Cruz 293 | 688 | **6.232** | 6,6 |
| Enel | Enel CE 1.837 · Enel SP 1.609 · Enel RJ 1.337 | 272 | **4.783** | 5,1 |
| EDP | EDP SP 887 · EDP ES 781 | 105 | **1.668** | 1,8 |
| **Total dos 4 grupos** | 14 distribuidoras | 2.066 | **20.553** | **21,9** |
| Extensão: Energisa | 9 distribuidoras | 879 | 5.281 | 5,6 |
| **Total com Energisa** | 23 distribuidoras | 2.945 | **25.834** | **27,6** |

Os 4 grupos concentram 42% da área urbanizada do Brasil, o equivalente a cerca de 27 lotes de 750 km². Com a Energisa, a fatia chega a 53% (34 lotes).

**Equatorial fora do cálculo:** a Imagem Geosistemas já faz o mapeamento de árvores para a Equatorial (informação do autor do deck). Duas consequências: a Equatorial não entra no potencial nem na abertura de Poda, e a Imagem atua como **concorrente** em Poda. Isso pesa na decisão pendente "Imagem: canal ou concorrente" (seção 3 do Documento de Revisão) e deve entrar no acordo de não conflito que a diretoria propôs.

**Cuidados com o número:**
- R$ 21,9 mi é um teto bruto, porque supõe mapear 100% da área urbana. Na prática o serviço cobre os trechos com rede aérea, e o preço por km² tende a cair com a escala. Antes de usar como meta, aplique um fator de cobertura (por exemplo, a fração da área urbana com rede aérea, se a distribuidora informar).
- Enel SP: a decisão sobre a caducidade está pendente, então a área conta no potencial mas não na abertura de 2027.
- A CPFL Santa Cruz aparece na ANEEL com a sigla antiga "CPFL JAGUARI".

---

## 2. Crítica aos números do slide atual

### Críticas gerais
1. **As bases de cálculo se misturam.** O slide usa unidade de compra, companhia, grupo, lote de km², valor anual e "total no saneamento". Assim não dá para somar nem comparar. Cada linha precisa de uma fórmula explícita (unidades × ticket).
2. **O potencial estava incompleto.** Sem Poda, o total era de R$ 26,65 mi. Com Poda calculada (R$ 21,9 mi) e as correções de Novas ligações e Postes, o potencial calculado passa a R$ 62,8 mi. A Poda vira a maior linha, com 35% do total.
3. **A abertura não segue uma regra.** Algumas ofertas abrem 100% do potencial no ano (AHP, Painel, InfoSuite) e outras abrem 7,5% (Novas ligações). A regra que proponho: **oferta pronta abre na carteira inteira e oferta nova entra por piloto nas contas prioritárias.**
4. **A prioridade número 1 do estudo de energia ficou com o menor potencial.** Postes aparece com R$ 0,6 mi de potencial e de abertura, mas o estudo de outubro diz "concentrar a primeira validação em postes".
5. **A janela mais curta ficou sem número.** As comercializadoras não têm ticket, e a data de 25/11/2027 pede contratos assinados até 31/07.
6. **Energisa aparece duas vezes.** A Sustentação Energisa (R$ 1,2 mi) já está no CRM como RFP AMS Smallworld.

### Linha a linha

| Oferta | Slide atual (potencial → abertura) | Crítica | Proposta |
|---|---|---|---|
| Poda e risco climático | "a calcular" → R$ 4,8 mi (6 lotes) | Faltava o cálculo. Com o lote de 750 km², a área dos 4 grupos comporta cerca de 27 lotes | Potencial de R$ 21,9 mi (4 grupos). Abertura mantida em 6 lotes, R$ 4,8 mi (22% do potencial) |
| Novas ligações, energia | 20 unidades → 6 pilotos (R$ 1,2 mi) | A Neoenergia tem 5 distribuidoras, não 4. A Equatorial tem 7, não 6 | 22 unidades × 0,8 = R$ 17,6 mi. Abertura com 6 pilotos e 1 projeto (Neoenergia, pelo contrato bolsão) |
| Novas ligações, gás | 2 × 0,8 → 2 pilotos | Coerente | Manter |
| Compartilhamento de postes | 0,6 → 0,6 | O potencial estava restrito a um piloto. A regra de postes (ANEEL/Anatel, 1º sem./2027) abre as 22 distribuidoras e, depois, os posteiros | Potencial mínimo de 22 × 0,6 = R$ 13,2 mi [Estimativa, com o ticket de piloto como piso]. Abertura de 3 pilotos no 2º semestre |
| AHP | 9 × 0,15 → 100% | Ticket baixo e oferta pronta: abrir 100% faz sentido | Manter, distribuído do T1 ao T3 |
| Painel de perdas (Esri PT) | 4 × 0,5 → 100% | Coerente. A Sabesp já é cliente da Esri PT, então lá é expansão | Manter, em co-venda com a Esri PT |
| InfoSuite (Autodesk) | 1,5 "total" → 100% | Não tem base de cálculo | Definir companhias × ticket até 18/11. Usei 3 oportunidades × R$ 0,5 mi [Estimativa] |
| Sustentação e fábrica | 3 grupos × 1,2 → 3,6 | Energisa duplicada com o CRM | 3 × 1,2 = R$ 3,6 mi/ano de potencial. Abertura só com CPFL e EDP (R$ 2,4 mi) |
| Comercializadoras | Sem ticket | Janela de 25/11/2027 | Abrir 4 oportunidades até o T2. Ticket a definir até 18/11 (fora da soma) |

---

## 3. Plano de abertura 2027: arrojado, mas factível

| Oferta | Base de cálculo | Potencial calculado (R$ mi) | Oport. a abrir | Abertura 2027 (R$ mi) | % do potencial | Entrada |
|---|---|---|---|---|---|---|
| Poda e risco climático | 20.553 km² × R$ 1.067/km² | 21,9 | 6 | 4,8 | 22% | Lote de 750 km² |
| Novas ligações, energia | 22 distribuidoras × 0,8 | 17,6 | 7 | 2,0 | 11% | 6 pilotos de 0,2 + 1 projeto de 0,8 |
| Compartilhamento de postes | 22 distribuidoras × 0,6 | 13,2 | 3 | 1,8 | 14% | Piloto |
| Sustentação e fábrica | 3 grupos × 1,2/ano | 3,6 | 2 | 2,4 | 67% | Recorrente |
| Painel de perdas | 4 companhias × 0,5 | 2,0 | 4 | 2,0 | 100% | Oferta completa |
| Novas ligações, gás | 2 companhias × 0,8 | 1,6 | 2 | 0,4 | 25% | Piloto |
| InfoSuite | a definir (1,5) | 1,5 | 3 | 1,5 | 100% | Oferta completa |
| AHP | 9 companhias × 0,15 | 1,35 | 9 | 1,35 | 100% | Oferta completa |
| Comercializadoras | ticket a definir | n/d | 4 | n/d | n/d | Campanha "Pronto para 25/11" |
| **Total** | | **62,8** (40,9 sem Poda) | **40** | **16,25** | **26%** | |

**Onde abrir os lotes de Poda:** Neoenergia 2 (maior área urbana, 10,5 lotes possíveis), CPFL 1, Enel 1 (CE ou RJ), EDP 1 e Energisa 1. São 4.500 km². Cinco lotes ficam nos 4 grupos (3.750 km², 18% da área deles). A Equatorial fica fora, porque a Imagem já faz esse trabalho lá. Abrir 10 lotes (36% do potencial em um ano) seria agressivo demais para uma oferta nova; 8 lotes (R$ 6,4 mi) ficam como meta de superação.

**Por que é arrojado:** o plano abre R$ 16,25 mi, 5% acima dos R$ 15,45 mi atuais e 14% acima dos R$ 14,25 mi depois de tirar a duplicação da Energisa. O avanço maior está no volume: são 40 oportunidades novas contra cerca de 34 no funil do CMO, quase uma por semana, e com 3 pilotos de Postes e 1 projeto de Novas ligações que o slide atual não tinha.

**Por que é factível:**
- **Ofertas prontas, carteira inteira.** AHP, Painel e Sustentação têm escopo e preço conhecidos, então dá para abrir todas as contas.
- **Ofertas novas, só piloto.** Poda, Novas ligações e Postes entram por piloto, onde o patrocinador já tem obrigação regulatória com prazo: a REN 1.137 para poda e a regra de postes.
- **Calendário encaixado nos gatilhos:** one-pagers prontos até 31/03, eventos de junho, regra de postes no 1º semestre, prazo das comercializadoras em 31/07 e Fenasan em outubro.

**Condições para dar certo:**
- ofertas empacotadas até 31/03;
- um responsável de pré-venda por segmento;
- ABM ativo nas contas Tier 1;
- definir o que conta como "abertura": oportunidade no Salesforce com patrocinador identificado, escopo e ticket estimados.

### Cadência trimestral (oportunidades a abrir)

| Oferta | T1 | T2 | T3 | T4 | Total |
|---|---|---|---|---|---|
| Poda e risco climático | 0 | 3 | 2 | 1 | 6 |
| Novas ligações, energia | 2 | 2 | 2 | 1 | 7 |
| Novas ligações, gás | 0 | 1 | 1 | 0 | 2 |
| Compartilhamento de postes | 0 | 0 | 2 | 1 | 3 |
| AHP | 4 | 3 | 2 | 0 | 9 |
| Painel de perdas | 2 | 2 | 0 | 0 | 4 |
| InfoSuite | 0 | 1 | 1 | 1 | 3 |
| Sustentação e fábrica | 2 | 0 | 0 | 0 | 2 |
| Comercializadoras | 2 | 2 | 0 | 0 | 4 |
| **Total** | **12** | **14** | **10** | **4** | **40** |

**Gatilhos de cada trimestre:**
- **T1:** renovações de Sustentação, ofertas prontas e o projeto Neoenergia pelo contrato bolsão.
- **T2:** Poda entra antes do planejamento do período chuvoso [Inferência]. Também é o trimestre dos eventos (CITEENEL 9 a 11/06, SENDI 14 a 18/06, ENASE 16 e 17/06) e das comercializadoras.
- **T3:** Postes, depois da aprovação da regra.
- **T4:** Fenasan (26 a 28/10) e a segunda rodada de Poda.

---

## 4. Estrutura do novo slide

**Título:** 5 · Pipeline Potencial 2027: potencial calculado e plano de abertura

**Mensagem do slide (uma linha):** Vamos abrir R$ 16,3 mi em 40 oportunidades em 2027: oferta completa onde o produto está pronto e piloto onde o potencial é grande.

**Layout (16:9):**

```
┌───────────────────────────────────────────────────────────────┬──────────────────────────┐
│ TABELA (60%), agrupada por segmento                           │ 3 CARTÕES DE KPI         │
│ Oferta | Base de cálculo | Potencial | Oport. | Abertura | Entrada │ Potencial: R$ 62,8 mi  │
│ ENERGIA: Poda · Novas ligações · Postes · Sustentação         │   (R$ 40,9 mi sem Poda)  │
│ SANEAMENTO: Painel de perdas · AHP · InfoSuite                │ Abertura 2027: R$ 16,25 mi│
│ GÁS: Novas ligações                                           │ 40 oportunidades (~3/mês)│
│ COMERCIALIZADORAS: campanha 25/11 (ticket a definir)          ├──────────────────────────┤
│ Total                                                          │ BARRAS: área urbana (km²)│
│                                                                │ Neoenergia 7.870         │
│                                                                │ CPFL 6.232 · Enel 4.783  │
│                                                                │ EDP 1.668                │
│                                                                │ (cinza: Energisa 5.281)  │
│                                                                │                          │
├───────────────────────────────────────────────────────────────┴──────────────────────────┤
│ FAIXA: cadência T1 12 · T2 14 · T3 10 · T4 4, com os gatilhos de cada trimestre          │
├──────────────────────────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: definições (potencial calculado, abertura) · Sem ticket: ETR, ferramenta de      │
│ projeto em campo · Fontes: ANEEL IndQual Município e Limites de Continuidade (05/11/2026);│
│ IBGE Áreas Urbanizadas 2022 (14/09/2026)                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────┘
```

**Recomendações de design:**
- A coluna "Entrada" usa três cores: piloto, oferta completa e recorrente. É o código visual que explica a lógica.
- A barra de área urbana mostra o tamanho da oportunidade de Poda e mostra quantos lotes cabem em cada grupo.
- Os números da tabela ficam alinhados à direita, com uma casa decimal.

**Notas do apresentador sugeridas:**
- O potencial calculado multiplica as unidades de compra das contas-alvo pelo ticket de cada oferta. Não é o tamanho do mercado.
- O potencial de Poda vem do cruzamento dos municípios de cada concessão (ANEEL) com a área urbanizada do IBGE de 2022: 20.553 km² nos 4 grupos, o equivalente a 42% da área urbanizada do país. É um teto bruto e depende de um fator de cobertura de rede aérea.
- A abertura é meta de oportunidades abertas, e não de fechamento.
- A regra é abrir a carteira inteira das ofertas prontas e entrar por piloto nas ofertas novas.
- Enel SP fica fora da abertura até a decisão sobre a caducidade.

---

## Fontes

- ANEEL, Dados Abertos: [IndQual Município](https://dadosabertos.aneel.gov.br/dataset/indqual-municipio) e [Indicadores Coletivos de Continuidade, limites](https://dadosabertos.aneel.gov.br/dataset/indicadores-coletivos-de-continuidade-dec-e-fec). Arquivos com geração em 05/11/2026.
- IBGE: [Áreas Urbanizadas do Brasil 2022, tabelas](https://geoftp.ibge.gov.br/organizacao_do_territorio/tipologias_do_territorio/areas_urbanizadas_do_brasil/2022/Tabelas/), arquivo `areas_urbanizadas_2022_estatisticas_2026_09_14.xlsx`.
- Deck "Planejamento 2027 - Comercial" (slide 12 e notas) e estudo "Estratégia de aplicações para o setor elétrico" (out/2026).
- Planilha do cálculo por distribuidora: `area_urbana_concessoes.csv`, nesta pasta.
