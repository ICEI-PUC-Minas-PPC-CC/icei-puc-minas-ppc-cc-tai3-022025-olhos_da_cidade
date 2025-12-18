# 📌 Olhos da Cidade
As cidades sofrem com problemas de infraestrutura, segurança e higiene urbana, como: buracos no asfalto, calçadas danificadas, iluminação precária, terrenos baldios, trânsito desordenado e falta de fiscalização em obras. A resposta do poder público costuma ser lenta pela falta de dados atualizados.
Uma possível solução seria um aplicativo móvel para registrar, mapear e enviar informações urbanas em tempo real. Técnicos em campo coletam dados (com GPS e fotos), que são enviados a uma central de monitoramento, gerando relatórios, mapas e estatísticas para cada setor responsável.

---

## 👥 Integrantes

- Matheus Brunheroto – RA: 804791  
- Bruno Albarez Dias Barbosa – RA: 804580
- Leonardo Bonilha Lima - RA: 770404
- Ana Leticia Sandy do Prado – RA: 803009  

---

## 🧭 Etapas do Projeto

### 1️⃣ Definição do Problema e da Solução
- **Problema identificado:** Falta de fiscalização de demandas dos bairros da cidade (condições do asfalto, buracos nas ruas, terrenos baldios, iluminação, arborização e jardins, etc...)
- **Público-alvo:** Moradores da cidade 
- **Impacto esperado:** Aproximar mais a prefeitura dos problemas dos cidadãos
- **Solução proposta:** Uma câmera utilizando um programa (YOLO) para identificar e reconhecer problemas nos bairros

### 2️⃣ Lean Canvas / Missão, Visão e Valores
<img src="/docs/lean_canvas.png" width="500">

- **Missão:**  Acelerar o reconhecimento de problemas da cidade para a prefeitura
- **Visão:**  Investimento da prefeitura e resolução de problemáticas dos moradores
- **Valores:**  Sustentabilidade, inovação e foco em resultados

### 3️⃣ Custos e Tributos

[Custos e Despesas](./docs/custos_estudo.md)
- **Custos fixos:** Servidores iniciais da aplicação – R$30/mês (serviço necessário ao funcionamento).
- **Custos variáveis:** Cerca de R$160 por unidade (câmera, impressão 3D, Wi-Fi, GPS e placa de circuito).
- **Tributos aplicáveis:** Não especificados no momento.
<img width="874" height="329" alt="image" src="https://github.com/user-attachments/assets/9c36dc2b-e0d4-462d-8f73-f99500044471" />

### 4️⃣ Investimentos e Precificação

[Plano de Negócio](./docs/plano_de_negocio.md)
- **Investimento inicial:** Desenvolvimento do protótipo, cerca de R$480 (Raspberry Pi, câmera, GPS, Wi-Fi e modelo 3D para suporte). Patente e taxas pré-operacionais estimadas em R$436.
- **Estratégia de precificação:** Baseada no custo de produção e operação do equipamento.
- **Justificativa:** Sistema agrega valor ao automatizar a detecção de problemas urbanos, reduzindo custos com vistoria manual e acelerando decisões. Preço reflete economia operacional e eficiência administrativa para a prefeitura.
<img width="885" height="369" alt="image" src="https://github.com/user-attachments/assets/18c3a255-a718-4242-8fa2-8da3a7d1f5a3" />

### 5️⃣ SWOT (Análise de Ambientes)
[Análise de Ambiente](./docs/analise_ambiente.md)
- **Forças:** Uso de YOLO para identificação automática de problemas urbanos; redução de custos de fiscalização; geração de dados em tempo real; potencial de escalabilidade e integração.
- **Fraquezas:** Dependência de infraestrutura tecnológica (internet, servidores, câmeras de qualidade); custo inicial elevado de protótipo e equipamentos; necessidade de manutenção contínua; vulnerabilidades em dispositivos IoT e proteção de dados.
- **Oportunidades:** Crescente demanda por cidades inteligentes; parcerias com prefeituras e órgãos de segurança; expansão para análise de mobilidade urbana, segurança e fiscalização de obras; integração com sistemas de denúncia cidadã; avanços em IA e geolocalização.
- **Ameaças:** Resistência de gestores públicos à adoção de novas tecnologias; risco de falhas técnicas e cibersegurança; concorrência de soluções mais simples; mudanças legais e tributárias; preocupações com privacidade e ética da IA.

### 6️⃣ Planejamento Estratégico (BSC)
[Planejamento Estratégico](./docs/planejamento_estrategico.xlsx)
- **Objetivos estratégicos:** Melhorar a eficiência da fiscalização urbana por meio de IA e geolocalização; reduzir custos e tempo de resposta às demandas da cidade; aumentar a transparência e a integração entre poder público e cidadãos; expandir o sistema para diferentes áreas da gestão urbana (mobilidade, segurança, obras)
- **Indicadores e metas:** Porcentagem de problemas urbanos identificados automaticamente; tempo médio de resposta das secretarias responsáveis; número de ocorrências mapeadas por mês; taxa de satisfação dos gestores municipais
- **Ações planejadas:** Desenvolver e validar o aplicativo; implementar em caminhões da coleta de lixo em um bairro/cidade média para ajustes; estabelecer parcerias com prefeituras e órgãos públicos; investir em melhorias contínuas do modelo YOLO para diferentes condições ambientais.

### 7️⃣ Fluxo de Caixa
<img width="1555" height="91" alt="image" src="https://github.com/user-attachments/assets/f952e2b8-facb-49c7-8854-03f6926420a5" />

### 8️⃣ Valuation
- **Método utilizado:** Fluxo de Caixa Descontado (FCD), com cálculo de valor terminal pelo modelo de Gordon, complementado por análise por múltiplos (Receita e EBITDA).
- **Valor estimado:** aproximadamente R$ 638.363.

### 9️⃣ Segurança Cibernética
- **Riscos identificados:** Vulnerabilidades em dispositivos IoT; vazamento de dados sensíveis (imagens, localização, relatórios de segurança pública); 
- **Medidas de segurança:** Armazenamento seguro em nuvem; monitoramento contínuo de rede e detecção de intrusos;

---

## 📅 Diário de Bordo

| Data       | Conteúdo                                        | Status        | Observações / Entregáveis |
|------------|-------------------------------------------------|---------------|---------------------------|
| 06/08/2025 | Apresentação Disciplina + Start propostas      | ✅   | — |
| 13/08/2025 | Definição dos Grupos, Propostas e Criação de Times Classroom | ✅  | — |
| 20/08/2025 | Modelagem do Problema - Lean Canvas / Missão, Visão e Valores | ✅   | — |
| 27/08/2025 | Entrevista 01 - Acompanhamento das atividades / validação | ✅  | **Entrega:** Lean Canvas - Pontos: 5 |
| 03/09/2025 | Custos e Tributos (Plano de Negócios - PNBOX) | ✅   | — |
| 10/09/2025 | Investimentos e Precificação (Plano de Negócios - PNBOX) | ✅   | **Entrega:** Custos e Despesas - Pontos: 5 |
| 17/09/2025 | Acompanhamento Plano de Negócios             | ✅   | **Entrega:** Investimentos e Precificação - Pontos: 5 |
| 24/09/2025 | Entrevista 02 - Acompanhamento das atividades / validação | ✅ | **Entrega:** Plano de Negócio (Finalização com Tributos) - Pontos: 5 |
| 01/10/2025 | Análise de Ambientes - SWOT                   | ✅  | — |
| 08/10/2025 | BSC e Planilha de Planejamento Estratégico    | ✅  | **Entrega:** Análise de Ambientes - Pontos: 5 |
| 15/10/2025 | Fluxo de Caixa / Planilha Fluxo de Caixa / Entrega Planejamento Estratégico | ✅  | **Entrega:** Planejamento Estratégico - Pontos: 10 |
| 22/10/2025 | Seminários (Segurança da Informação)         | ✅  | — |
| 29/10/2025 | Valuation (atividade)                         | ✅  | **Entrega:** Fluxo de Caixa / Planilha Fluxo - Pontos: 15 |
| 05/11/2025 | Compliance em TI: Legislação                  | ✅ | **Entrega:** Valuation - Pontos: 10 |
| 12/11/2025 | Segurança Cibernética no Produto              | ✅  | — |
| 19/11/2025 | Orientações e preparação para a apresentação à banca | ✅ | — |
| 26/11/2025 | Apresentação Banca (3 grupos)                | ✅ | **Entrega:** Apresentação Banca - Pontos: 30 |
| 03/12/2025 | Apresentação Banca (3 grupos)                | ✅ | — |
| 10/12/2025 | Apresentação Banca (3 grupos)                | ✅   | — |
| 17/12/2025 | Divulgação Melhor Produto - Concurso         | ⬜  | — |
| 17/12/2025 | Organização e estruturação do Projeto GitHub (final do semestre) | ✅  | **Entrega:** Projeto GitHub - Pontos: 10 |


---

## 📦 Entregas

| Entrega                                | Data       | Descrição                                                         | Status |
|----------------------------------------|------------|-------------------------------------------------------------------|--------|
| Lean Canvas                            | 20/08/2025 | Documento e imagem do canvas                                      |✅|
| Custos e Tributos                      | 27/08/2025 | Planilha com custos fixos, variáveis e tributos                   |✅|
| Análise SWOT / Plano de Negócios       | 24/09/2025 | Análise de ambientes SWOT e entrega do Plano de Negócios          |✅|
| Fluxo de Caixa / Planejamento Estratégico | 15/10/2025 | Planilha de fluxo de caixa e entrega do Planejamento Estratégico |✅|
| Valuation                              | 05/11/2025 | Relatório com cálculo de valuation                                |Atrasado|
| Valuation      | 12/11/2025 | Valuation |Atrasado|

---

## 🗣️ Feedbacks Recebidos

| Data       | De Quem     | Feedback                                                        | Ação Tomada |
|------------|-------------|----------------------------------------------------------------|-------------|
| 08/10/2025 | Diego Roberto Gonçalves de Pontes | Faltam detalhamento de custos e explicação clara da formação do preço | Resolvido nas próximas etapas |
| 08/10/2025 | Diego Roberto Gonçalves de Pontes | Sugere-se ajustar capital de giro, precificação e métricas para maior sustentabilidade financeira | Adição da assinatura mensal |
| 08/10/2025 | Diego Roberto Gonçalves de Pontes  | Corrigir a tributação (ICMS não aplicável), esclarecer NFS-e e detalhar melhor obrigações acessórias. | Correção e esclarecimento da tributação |


---

## 📚 Lições Aprendidas

- **Lean Canvas:** Aprendemos a importância de definir claramente o problema, público-alvo e solução proposta antes de iniciar qualquer desenvolvimento. Ter o Lean Canvas estruturado ajudou a equipe a alinhar expectativas e planejar etapas futuras de forma mais eficaz.
- **Levantamento de Custos e Despesas:** Entendemos que detalhar custos fixos e variáveis é essencial para a sustentabilidade do projeto. Esse levantamento permitiu simular diferentes cenários financeiros e avaliar a viabilidade econômica do protótipo.
- **Investimentos e Precificação:** Aprendemos a relacionar investimento inicial, custos operacionais e precificação estratégica. A fase destacou a importância de justificar o valor do produto de forma clara, considerando economia operacional e eficiência para o cliente.
- **Plano de Negócio:** Aprendemos a consolidar todas as informações do projeto em um documento estruturado, considerando tributos, obrigações legais e enquadramento empresarial. A integração dessas informações é fundamental para apresentar o projeto de forma completa e profissional.
- **Análise de Ambientes:** A análise SWOT nos mostrou a importância de mapear forças, fraquezas, oportunidades e ameaças, antecipando riscos técnicos, financeiros e estratégicos. Esse processo fortaleceu o planejamento e a tomada de decisão.
- **Planejamento Estratégico:** Aprendemos a definir objetivos estratégicos claros, indicadores de desempenho e metas mensuráveis. A fase reforçou a necessidade de organizar ações de curto e longo prazo, priorizando impacto e eficiência operacional.
- **Fluxo de Caixa / Planilha Fluxo:** Essa etapa mostrou a importância do acompanhamento financeiro detalhado. Aprendemos a projetar entradas e saídas, avaliar liquidez e garantir que o projeto pudesse se manter financeiramente sustentável ao longo do tempo.
- **Valuation:** Aprendemos a calcular o valor econômico do projeto utilizando diferentes metodologias, incluindo Fluxo de Caixa Descontado e múltiplos de mercado. Essa fase reforçou a visão estratégica sobre retorno do investimento e atratividade do projeto.

---

## 📁 Organização do Repositório

```
📦 projeto/
 ┣ 📂 docs/
 ┃ ┣ lean_canvas.png
 ┃ ┣ custos_estudo.md
 ┃ ┣ plano_de_negocios.md
 ┃ ┣ analise_ambiente.md
 ┃ ┗ planejamento_estrategico.xlsx
 ┃ ┗ fluxo_de_caixa.xlsx
 ┃ ┗ valuation.pdf
 ┃ ┗ apresentacao_banca.pptx
 ┣ README.md
```

---

## Apresentação Banca

## PNBOX

[Link PNBOX](https://pnbox.sebrae.com.br/planoNegocio/invite/OO1DzP_-4)
