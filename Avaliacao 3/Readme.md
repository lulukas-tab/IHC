# acessibilidade-digital-ihc

##Link do site: https://chic-kitsune-37e54f.netlify.app

# Avaliação 3 — IHC Lab: Grandes Desafios de IHC no Brasil (2025-2035)

Este repositório contém o relatório acadêmico detalhado e a implementação do protótipo de jogo educacional interativo focando na prospecção de soluções para as barreiras de acessibilidade digital e os eixos estratégicos do **GranDIHC-BR**, desenvolvidos para a **Oficina "IHC Lab: Challenges & Desafios"** do Centro Universitário de Brasília (CEUB).

---

##  Informações do Projeto
* **Instituição:** Centro Universitário de Brasília (CEUB)
* **Unidade:** IHC Lab – Grandes Desafios de IHC no Brasil
* **Disciplina:** Interação Humano-Computador
* **Docente Orientadora:** Profa. Kadidja Valéria de Oliveira
* **Contexto Acadêmico:** Conecta CEUB 2026 ([Link Oficial](https://institucional.uniceub.br/conecta2026))
* **Componentes do Grupo:** [Inserir Nomes dos Alunos]

---

## O Protótipo Desenvolvido: "Missão GranDIHC-BR"
O entregável prático desta avaliação consiste em um jogo digital interativo hospedado no arquivo `index.html`. 

###  Características de IHC Implementadas no Jogo:
1. **Acessibilidade Nativa (IHC na Prática):** O próprio jogo possui um painel funcional contendo controles de **Alto Contraste** dinâmico e botões para **Dimensionamento de Fonte (A+ / A-)** para simular as boas práticas ensinadas.
2. **Inclusão Sonora:** Utilização da *Web Audio API* nativa do navegador para prover feedbacks sonoros (tons de acerto, erro e vitória) sem dependência de bibliotecas ou arquivos externos lentos, garantindo semântica multimodal.
3. **Design Responsivo & Semântico:** Estruturado em HTML5 semântico com marcações de acessibilidade (`role="banner"`, `role="main"`, `aria-label`, `aria-valuenow`), alinhado aos padrões do **eMAG**.

---

##  Relatório Técnico-Científico

### 1. Introdução e Contextualização (GranDIHC-BR)
A Interação Humano-Computador (IHC) contemporânea no Brasil é balizada pelo documento de macrodiretrizes da Sociedade Brasileira de Computação (SBC): o **GranDIHC-BR (Grandes Desafios de IHC no Brasil para o decênio 2025-2035)**. Este manifesto científico propõe sete eixos estratégicos transversais focados em colocar a tecnologia, a ciência e a educação a serviço do bem-estar social de forma inclusiva:
* **Ética / IA:** Sistemas preditivos e generativos pautados em responsabilidade, mitigação de preconceitos algorítmicos e transparência.
* **Decolonialidade:** Superação de padrões de interface importados do Norte Global, adequando a tecnologia às realidades comunitárias e locais brasileiras.
* **Humano-dados:** Controle, compreensão e visualização inteligente do tratamento massivo de dados sensíveis e privacidade.
* **Tecnologias emergentes:** Inclusão e design universal aplicados a Realidades Estendidas (XR), Metaverso e IoT.
* **Abordagens teóricas:** Adaptação e evolução epistemológica das metodologias de IHC nacionais.
* **Impactos socioculturais:** Análise crítica sobre como a digitalização afeta a estrutura do cotidiano e do trabalho no Brasil.
* **Inclusão:** Redução ativa da exclusão digital e de barreiras para PCDs (Pessoas com Deficiência) e idosos.

### 2. Barreiras de Acessibilidade e Políticas Públicas Nacionais
O cenário brasileiro de inclusão digital baseia-se em regulamentações estritas como a **LBI (Lei Brasileira de Inclusão - Lei nº 13.146/2015)**, operacionalizada através de duas frentes fundamentais:
* **eMAG (Modelo de Acessibilidade em Governo Eletrônico):** Normatiza os parâmetros de desenvolvimento para portais do setor público brasileiro. Ele adapta as regras globais e padroniza a obrigatoriedade de atalhos de teclado unificados, links de salto de conteúdo, e correta indexação semântica para o ecossistema do governo federal.
* **WCAG Adaptado (Web Content Accessibility Guidelines):** Consiste em um framework internacional transposto para a realidade nacional que define quatro pilares de design universal: as interfaces digitais precisam ser **Perceptíveis, Operáveis, Compreensíveis e Robustas**.

Mesmo amparadas por lei, persistem barreiras críticas no Brasil: falta de audiodescrição e tags `alt` em portais essenciais (como saúde e previdência), formulários complexos que punem erros de digitação e ausência de suporte offline-first para regiões de conectividade instável.

### 3. Metodologia de Desenvolvimento
A concepção da oficina e a consolidação deste repositório seguiram quatro etapas integradas do ciclo de design de IHC:
1. **Pesquisa Orientada:** Extração e leitura de artigos científicos indexados na **Biblioteca Digital SOL da SBC**, identificando jogos sérios e mapeando cenários críticos de exclusão.
2. **Brainstorming e Ideação:** Discussão em grupo focada em criar uma metáfora interativa de aprendizado que condensasse múltiplos dilemas de IHC (desde falhas de acessibilidade básica até vieses de IA).
3. **Prototipagem de Alta Fidelidade:** Codificação direta em HTML5/CSS3/JavaScript, assegurando que o protótipo não fosse apenas uma representação conceitual, mas sim um artefato interativo acessível.
4. **Avaliação por Heurísticas:** Testes de usabilidade e aplicação prática dos controles de alto contraste e redimensionamento textual inseridos na interface do jogo.

### 4. Análise dos Resultados do Jogo
O jogo simula 5 fases críticas da jornada de um designer de IHC no Brasil:
* **Cenário 1:** Aborda a falta de HTML semântico sob a regulamentação do **eMAG** em portais de saúde pública.
* **Cenário 2:** Trata do viés algorítmico em seleção pública de currículos, conectando-se ao eixo **Ética/IA**.
* **Cenário 3:** Expõe o fracasso de interfaces urbanocêntricas quando implantadas no interior do Nordeste sem perspectiva de **Decolonialidade**.
* **Cenário 4:** Demonstra os problemas de formulários excludentes sob os princípios da **WCAG**.
* **Cenário 5:** Discute a necessidade de painéis intuitivos de privacidade e transparência (**Humano-Dados**).

Os testes demonstraram que a aplicação de storytelling gamificado reduz a barreira cognitiva no entendimento de normas técnicas complexas, gerando reflexão imediata no desenvolvedor através de feedbacks corretivos/explicativos rápidos.

### 5. Conclusão e Prática Socialmente Responsável
O desenvolvimento deste projeto evidencia que a usabilidade e a acessibilidade não podem ser tratadas como "etapas cosméticas de pós-produção", mas sim como pré-requisitos éticos fundamentais do design de software. Compreender os Desafios de IHC no Brasil no horizonte 2025-2035 obriga a comunidade técnica a criar artefatos flexíveis, multimodais e sensíveis à diversidade econômica, cognitiva e física do povo brasileiro.

---

##  Como Executar o Jogo Localmente

1. Faça o clone deste repositório para sua máquina local.
2. Abra o arquivo `index.html` em qualquer navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, etc.).
3. Não é necessário instalar nenhum servidor local ou dependência externa. O projeto roda de forma 100% autônoma e offline.

---

##  Referências Bibliográficas
* **Sociedade Brasileira de Computação (SBC).** *GranDIHC-BR — Grandes Desafios de IHC no Brasil (2025-2035)*. Biblioteca Digital SOL, SBC, 2025.
* **Governo Federal do Brasil.** *Modelo de Acessibilidade em Governo Eletrônico (eMAG)*. Departamento de Órgãos Centrais, Ministério da Gestão e da Inovação em Serviços Públicos.
* **W3C.** *Web Content Accessibility Guidelines (WCAG 2.2)*. Web Accessibility Initiative (WAI), 2023.
* **VALÉRIA DE OLIVEIRA, Kadidja.** *IHC Lab: Challenges & Desafios*. Oficina Acadêmica, Conecta CEUB, 2026.

 O foco inicial deste repositório é o desenvolvimento de formulários web semânticos, 100% acessíveis e responsivos.
> **⚠️ AVISO LEGAL:** Este repositório trata-se **exclusivamente de uma atividade acadêmica**, desenvolvida para a disciplina de Interação-Humano-Computador (IHC) do curso de Ciência da Computação. Este projeto não possui fins lucrativos ou comerciais e **não tem qualquer vínculo com o Ministério da Saúde, Governo Federal ou o Sistema Único de Saúde (SUS) real**. Trata-se apenas de um protótipo de estudo e simulação técnica.

