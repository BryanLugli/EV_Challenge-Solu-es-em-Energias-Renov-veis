# GreenCharge
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

## O Problema

Os carros eletricos estao crescendo rapido no Brasil, mas a infraestrutura de recarga ainda tem muitos problemas:

- Eletropostos ficam ligados mesmo sem nenhum carro conectado, gastando energia a toa.
- A maioria dos postos nao sabe quando a energia solar esta disponivel e nao aproveita isso.
- Donos de frotas e gestores nao conseguem acompanhar em tempo real o que acontece nos postos.

Se nao resolvermos isso, vamos construir uma infraestrutura cara e ineficiente, desperdicando exatamente a energia limpa que queremos aproveitar.

---

## Justificativa

O Brasil tem meta de 1 milhao de veiculos eletricos ate 2030. Para isso, a rede de eletropostos precisa crescer de forma inteligente. Nao adianta instalar postos que desperdicam energia ou que dependem 100% da rede eletrica convencional.

Alem disso, empresas e orgaos reguladores estao exigindo cada vez mais relatorios de impacto ambiental. Uma solucao que mostre quanto CO2 foi evitado tem valor direto para o negocio.

A parceria com a GoodWe, empresa lider em inversores solares, abre uma oportunidade real: usar os dados dos paineis solares ja instalados para tornar a recarga mais eficiente, sem precisar criar hardware novo.

---

## Proposta de Solucao

O GreenCharge e uma plataforma que conecta eletropostos a energia solar disponivel em tempo real e torna a recarga mais inteligente.

Funcionalidades principais:

**Recarga inteligente**
O sistema le a geracao solar em tempo real pela API da GoodWe e prioriza a recarga quando ha sol disponivel. Quando nao ha energia solar suficiente, usa a rede eletrica de forma controlada.

**Painel de controle**
Tela simples onde o gestor ve quantos carros estao carregando, quanta energia solar foi usada e quanto foi economizado na conta de luz.

**Alertas automaticos**
O sistema avisa quando algo esta errado, como queda na geracao solar ou consumo fora do padrao.

**Relatorios mensais**
Todo mes o sistema gera um relatorio com energia solar aproveitada, economia em reais e estimativa de CO2 evitado.

---

## Tecnologia Utilizadas

| Tecnologia | Para que serve |
|------------|----------------|
| GoodWe SEMS Portal API | Ler os dados de geracao solar dos inversores GoodWe em tempo real |
| Python | Conectar a API com o banco de dados e aplicar a logica de recarga inteligente |
| Node.js | Servidor do painel de controle web |
| HTML, CSS e JavaScript | Interface simples para o gestor acompanhar tudo |
| SQLite | Guardar historico de consumo, geracao solar e relatorios |

Por que essas escolhas:

- A GoodWe ja tem uma API gratuita para parceiros, entao nao precisamos criar hardware novo.
- Python e simples e eficiente para trabalhar com dados de energia.
- O painel web e direto ao ponto, qualquer pessoa consegue usar sem treinamento.
- Com o historico salvo, da para provar com numeros quanto foi economizado.

---

## Relacao com Sustentabilidade e Energias Renovaveis

Impactos diretos da solucao:

**Menos dependencia da rede eletrica**
Ao usar energia solar primeiro, o eletroposto consome menos energia de usinas, muitas delas ainda movidas a combustiveis fosseis. Isso reduz a emissao de CO2 ligada a recarga dos veiculos.

**Menos desperdicio**
Com a recarga inteligente, o sistema so consome energia quando realmente precisa. Nada fica ligado a toa.

**Mais transparencia ambiental**
Os relatorios mostram exatamente quanto CO2 foi evitado, algo cada vez mais exigido por empresas e pelo governo.

Objetivos de Desenvolvimento Sustentavel da ONU que o projeto atende:

| ODS | Como o GreenCharge contribui |
|-----|------------------------------|
| ODS 7 - Energia limpa e acessivel | Maximiza o uso de energia solar nos eletropostos |
| ODS 9 - Industria e inovacao | Usa tecnologia para tornar a infraestrutura mais eficiente |
| ODS 11 - Cidades sustentaveis | Ajuda a criar uma mobilidade urbana mais limpa |
| ODS 13 - Acao climatica | Reduz emissoes de CO2 associadas a recarga de veiculos eletricos |

Estimativa de impacto por eletroposto com painel solar de 5 kWp:

- Economia de energia da rede: cerca de 40%
- Reducao de CO2: cerca de 1,2 tonelada por ano por posto
- Em uma rede de 100 postos: cerca de 120 toneladas de CO2 evitadas por ano

---

## Viabilidade

Do lado tecnico:
- A API da GoodWe ja existe e e gratuita para parceiros, sem necessidade de hardware novo.
- O prototipo pode comecar com um script Python rodando em qualquer computador ou Raspberry Pi.
- Nao precisa de obras fisicas, e so software conectado ao que ja existe no eletroposto.

Do lado do negocio:
- Quem paga: empresas com frota de veiculos eletricos e redes de eletropostos que querem cortar custos.
- Qual o ganho: economia de ate 40% na conta de energia ao usar mais energia solar.
- Mercado: com a meta de 1 milhao de EVs ate 2030, a demanda por infraestrutura inteligente so vai crescer.

---

## Impactos Esperados

- Reducao de ate 40% no consumo de energia da rede nos eletropostos integrados
- Aproveitamento maximo da energia solar ja gerada no local
- Relatorios mensais automaticos de economia e CO2 evitado
- Infraestrutura de recarga mais barata de operar e mais facil de acompanhar

---

Projeto desenvolvido para o EV Challenge 2026 - Disciplina de Energias Renovaveis e Sustentabilidade - FIAP
nov-veis-e-Sustent-veis
