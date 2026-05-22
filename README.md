# EV_Challenge-Soluçoes-em-Energias-Renováveis

Plataforma de gestao inteligente para eletropostos usando energia solar

EV Challenge 2026 - Disciplina: Energias Renovaveis e Sustentabilidade - FIAP

---

## Equipe

| Nome | RM |
|------|----|
| Bryan Lugli | RM571350 |
| Beckman Lugli | RM573442 |
| Guilherme Xavier | RM573053 |

---

## Problema

Os carros elétricos estão crescendo rápido no Brasil, mas a infraestrutura de recarga ainda tem muitos problemas:

- Eletropostos ficam ligados mesmo sem nenhum carro conectado, gastando energia à toa.
- A maioria dos postos não sabe quando a energia solar está disponível e não aproveita isso.
- Donos de frotas e gestores não conseguem acompanhar em tempo real o que acontece nos postos.

Se não resolvermos isso, vamos construir uma infraestrutura cara e ineficiente, desperdiçando exatamente a energia limpa que queremos aproveitar.

---

## Justificativa

O Brasil tem meta de 1 milhão de veículos elétricos até 2030. Para isso, a rede de eletropostos precisa crescer de forma inteligente. Não adianta instalar postos que desperdiçam energia ou que dependem 100% da rede elétrica convencional.

Além disso, empresas e órgãos reguladores estão exigindo cada vez mais relatórios de impacto ambiental. Uma solução que mostre quanto CO2 foi evitado tem valor direto para o negócio.

A parceria com a GoodWe, empresa líder em inversores solares, abre uma oportunidade real: usar os dados dos painéis solares já instalados para tornar a recarga mais eficiente, sem precisar criar hardware novo.

---

## Proposta de Solução

O GreenCharge é uma plataforma que conecta eletropostos à energia solar disponível em tempo real e torna a recarga mais inteligente.

Funcionalidades principais:

**Recarga inteligente**
O sistema lê a geração solar em tempo real pela API da GoodWe e prioriza a recarga quando há sol disponível. Quando não há energia solar suficiente, usa a rede elétrica de forma controlada.

**Painel de controle**
Tela simples onde o gestor vê quantos carros estão carregando, quanta energia solar foi usada e quanto foi economizado na conta de luz.

**Alertas automáticos**
O sistema avisa quando algo está errado, como queda na geração solar ou consumo fora do padrão.

**Relatórios mensais**
Todo mês o sistema gera um relatório com energia solar aproveitada, economia em reais e estimativa de CO2 evitado.

---

## Tecnologias Utilizadas

| Tecnologia | Para que serve |
|------------|----------------|
| GoodWe SEMS Portal API | Ler os dados de geração solar dos inversores GoodWe em tempo real |
| Python | Conectar a API com o banco de dados e aplicar a lógica de recarga inteligente |
| Node.js | Servidor do painel de controle web |
| HTML, CSS e JavaScript | Interface simples para o gestor acompanhar tudo |
| SQLite | Guardar histórico de consumo, geração solar e relatórios |

Por que essas escolhas:

- A GoodWe já tem uma API gratuita para parceiros, então não precisamos criar hardware novo.
- Python é simples e eficiente para trabalhar com dados de energia.
- O painel web é direto ao ponto; qualquer pessoa consegue usar sem treinamento.
- Com o histórico salvo, dá para provar com números quanto foi economizado.

---

## Relação com Sustentabilidade e Energias Renováveis

Impactos diretos da solução:

**Menos dependência da rede elétrica**
Ao usar energia solar primeiro, o eletroposto consome menos energia de usinas, muitas delas ainda movidas a combustíveis fósseis. Isso reduz a emissão de CO2 ligada à recarga dos veículos.

**Menos desperdício**
Com a recarga inteligente, o sistema só consome energia quando realmente precisa. Nada fica ligado à toa.

**Mais transparência ambiental**
Os relatórios mostram exatamente quanto CO2 foi evitado, algo cada vez mais exigido por empresas e pelo governo.

Objetivos de Desenvolvimento Sustentável da ONU que o projeto atende:

| ODS | Como o GreenCharge contribui |
|-----|------------------------------|
| ODS 7 — Energia limpa e acessível | Maximiza o uso de energia solar nos eletropostos |
| ODS 9 — Indústria e inovação | Usa tecnologia para tornar a infraestrutura mais eficiente |
| ODS 11 — Cidades sustentáveis | Ajuda a criar uma mobilidade urbana mais limpa |
| ODS 13 — Ação climática | Reduz emissões de CO2 associadas à recarga de veículos elétricos |

Estimativa de impacto por eletroposto com painel solar de 5 kWp:

- Economia de energia da rede: cerca de 40%.
- Redução de CO2: cerca de 1,2 tonelada por ano por posto.
- Em uma rede de 100 postos: cerca de 120 toneladas de CO2 evitadas por ano.

---

## Viabilidade

Do lado técnico:

- A API da GoodWe já existe e é gratuita para parceiros, sem necessidade de hardware novo.
- O protótipo pode começar com um script Python rodando em qualquer computador ou Raspberry Pi.
- Não precisa de obras físicas; é só software conectado ao que já existe no eletroposto.

Do lado do negócio:

- **Quem paga:** empresas com frota de veículos elétricos e redes de eletropostos que querem cortar custos.
- **Qual o ganho:** economia de até 40% na conta de energia ao usar mais energia solar.
- **Mercado:** com a meta de 1 milhão de EVs até 2030, a demanda por infraestrutura inteligente só vai crescer.

---

## Impactos Esperados

- Redução de até 40% no consumo de energia da rede nos eletropostos integrados.
- Aproveitamento máximo da energia solar já gerada no local.
- Relatórios mensais automáticos de economia e CO2 evitado.
- Infraestrutura de recarga mais barata de operar e mais fácil de acompanhar.

---

*Projeto desenvolvido para o EV Challenge 2026 — Disciplina de Energias Renováveis e Sustentabilidade — FIAP*

Aproveitamento máximo da energia solar já gerada no local.
Relatórios mensais automáticos de economia e CO2 evitado.
Infraestrutura de recarga mais barata de operar e mais fácil de acompanhar.


Projeto desenvolvido para o EV Challenge 2026 — Disciplina de Energias Renováveis e Sustentabilidade — FIAP
