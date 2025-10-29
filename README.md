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
- **Solução proposta:** Uma câmera utilizando um programa(YOLO) para identificar e reconhecer problemas nos bairros

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
- Forças: Uso do YOLO para identificação automática de problemas urbanas; redução de custos de fiscalização
- Fraquezas: Dependência de infraestrutura tecnológica (internet, servidores, câmeras de qualidade)
- Oportunidades: Crescente demanda por cidades inteligentes; parceiria com a prefeitura da cidade e órgãos de segurança; expansão para análise de mobilidade urbana, segurança e obras públicas; possibilidade de integrar com sistemas de denúncia cidadã e participação popular 
- Ameaças: Resistência de gestores públicos à adoçao de novas tecnologias; risco de falhas técnicas; concorrência de soluções mais simples (aplicativo de denúncia manual; mudanças legais/tributárias que afetem a prestação de serviços tecnológicos ao setor público

### 6️⃣ Planejamento Estratégico (BSC)
[Planejamento Estratégico](./docs/planejamento_estrategico.xlsx)
- Objetivos estratégicos: Melhorar a eficiência da fiscalização urbana por meio de IA e geolocalização; reduzir custos e tempo de resposta às demandas da cidade; aumentar a transparência e a integração entre poder público e cidadãos; expandir o sistema para diferentes áreas da gestão urbana (mobilidade, segurança, obras)
- Indicadores e metas: Porcentagem de problemas urbanos identificados automaticamente; tempo médio de resposta das secretarias responsáveis; número de ocorrências mapeadas por mês; taxa de satisfação dos gestores municipais
- Ações planejadas: Desenvolver e validar o aplicativo; implementar em caminhões da coleta de lixo em um bairro/cidade média para ajustes; estabelecer parcerias com prefeituras e órgãos públicos; investir em melhorias contínuas do modelo YOLO para diferentes condições ambientais.

### 7️⃣ Fluxo de Caixa
[Fluxo de Caixa](./docs/fluxo_de_caixa.xlsx)
- Planilha ou print do fluxo projetado:  
- Principais considerações:  

### 8️⃣ Valuation
- Método utilizado: Smart Cities que oferecem soluções de monitoramento urbano, visão computacional e gestão pública. 
- Valor estimado: de R$1,500 à R$2,000

### 9️⃣ Segurança Cibernética
- Riscos identificados: Vulnerabilidades em dispositivos IoT; vazamento de dados sensíveis (imagens, localização, relatórios de segurança pública); 
- Medidas de segurança: Armazenamento seguro em nuvem; monitoramento contínuo de rede e detecção de intrusos;

---

## 📅 Diário de Bordo

| Data       | Conteúdo/Etapa                     | Status     | Observações |
|------------|------------------------------------|------------|-------------|
| 06/08/2025 | Apresentação Disciplina + Start    | ✅ Concluído | — |
| 13/08/2025 | Definição dos Grupos e Propostas   | ✅ Concluído | Ajustar proposta com feedback do professor |

---

## 📦 Entregas

| Entrega                                | Data       | Descrição                                                         | Status |
|----------------------------------------|------------|-------------------------------------------------------------------|--------|
| Lean Canvas                            | 20/08/2025 | Documento e imagem do canvas                                      |✅|
| Custos e Tributos                      | 27/08/2025 | Planilha com custos fixos, variáveis e tributos                   |✅|
| Análise SWOT / Plano de Negócios       | 24/09/2025 | Análise de ambientes SWOT e entrega do Plano de Negócios          | —      |
| Fluxo de Caixa / Planejamento Estratégico | 15/10/2025 | Planilha de fluxo de caixa e entrega do Planejamento Estratégico  | —      |
| Valuation                              | 05/11/2025 | Relatório com cálculo de valuation                                | —      |
| Valuation      | 12/11/2025 | Valuation | —      |

---

## 🗣️ Feedbacks Recebidos

| Data       | De Quem     | Feedback                                                        | Ação Tomada |
|------------|-------------|----------------------------------------------------------------|-------------|
| 24/09/2025 | Professor X | Melhorar clareza da análise SWOT                                | Revisão feita |

---

## 📚 Lições Aprendidas
- O que a equipe aprendeu durante cada fase.  

---

## 📁 Organização do Repositório

```
📦 projeto/
 ┣ 📂 docs/
 ┃ ┣ lean_canvas.png
 ┃ ┣ custos_tributos.xlsx
 ┃ ┣ swot_plano_negocios.pdf
 ┃ ┣ fluxo_caixa_planejamento.xlsx
 ┃ ┗ valuation.pdf
 ┣ 📂 src/
 ┃ ┣ prototipo/
 ┃ ┗ documentos_planejamento/
 ┣ README.md
```

---
## PNBOX

[Link PNBOX](https://pnbox.sebrae.com.br/planoNegocio/invite/OO1DzP_-4)
