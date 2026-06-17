# Desafio da UA1: 

Este repositório contém a minha solução para um desafio de refatoração de interface focado em melhorar a **navegabilidade** e a **experiência do usuário (UX)** em um sistema corporativo de folha de pagamento.

##  O Desafio

Fui incumbido de reprogramar uma parte sensível de uma aplicação de gerenciamento de folha de pagamento. A interface original estava recebendo duras críticas dos clientes, como:
Dificuldade em entender a ação que seria realizada.
Baixa conversão (usuários com medo de avançar e travarem na tela).
 Falta de clareza nas opções.

**O Problema Específico:** 
A tela apresentava um modal (caixa de diálogo) de exclusão de usuário perguntando "Tem certeza de que deseja apagar a entrada deste usuário?", acompanhado de dois botões com rótulos extremamente ambíguos: **"Avançar"** e **"Retornar"**. 

Em ações destrutivas (como apagar dados de folha de pagamento), botões genéricos sem hierarquia visual causam confusão e insegurança, justificando as reclamações dos clientes.

##  A Solução e Melhorias Aplicadas

Para aperfeiçoar a navegabilidade e resolver os problemas relatados, reescrevi o HTML e o CSS do componente aplicando boas práticas de UX/UI e Microcopy:

1. **Alteração dos Rótulos (Labels) dos Botões:**
    O botão "Retornar" foi substituído por **"Cancelar"**.
   - O botão "Avançar" foi substituído por **"Excluir Usuário"**, deixando a ação 100% clara para o usuário.

2. **Hierarquia Visual e Cores Semânticas:**
    O botão de "Excluir" recebeu a cor **vermelha**, alertando o usuário de que se trata de uma ação destrutiva e irreversível.
    O botão de "Cancelar" recebeu uma cor neutra (cinza), sendo a rota de fuga segura.

3. **Aprimoramento do Microcopy (Textos):**
    A pergunta principal foi reescrita para: *"Tem certeza de que deseja excluir o registro deste usuário?"*.
    Adicionei um subtítulo de alerta em destaque: *"Atenção: Esta ação é permanente e não poderá ser desfeita."* para garantir que o usuário tenha plena consciência das consequências do clique.

##  Tecnologias Utilizadas

 **HTML5**: Estruturação semântica do modal.
 **CSS3**: Estilização, layout em Flexbox e design responsivo.

##  Como visualizar o projeto
Minha solução:
<img width="1179" height="732" alt="image" src="https://github.com/user-attachments/assets/2d12935d-b8c3-44cb-a1e7-718823c9487f" />

## Declaração

Declaro que este trabalho foi desenvolvido por mim, respeitando as normas acadêmicas e de integridade estabelecidas pela instituição.

- **Nome do Estudante:** Lucas Almeida
- **RA:** 22403149



