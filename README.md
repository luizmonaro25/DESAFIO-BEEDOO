# DESAFIO-BEEDOO

## User Story 1: Cadastro de Cursos válidos na plataforma 

Ao acessar a plataforma através da URL: https://creative-sherbet-a51eac.netlify.app   
Eu quero cadastrar novos cursos na plataforma Beedoo  
Para que os usuários possam visualizar os cursos disponíveis  

### Decisões tomadas: 

 **1 - Interface intuitiva:** interface de cadastro de curso intuitiva e fácil de usar, para que os usuários possam adicionar cursos sem dificuldades.   
 **2 - Validações:** incluir validações para cada campo (por exemplo, formato da URL da imagem, datas válidas, número positivo de vagas) para assegurar a integridade dos dados.  
 **3 - Feedback ao usuário:** feedback imediato ao usuário, incluindo mensagens de sucesso ou erro, para que saibam se o curso foi cadastrado corretamente ou se há problemas a serem corrigidos.  
 **4 - Campos obrigatórios:** definir campos obrigatórios (Nome do curso, Descrição, Instrutor, URL da Imagem, Data de início, Data de fim, Número de vagas, Tipo do curso e Endereço) para garantir que todas as informações necessárias sejam preenchidas.  

## User Story 2: Cadastro de Cursos inválidos na plataforma

Como um usuário  
Eu quero cadastrar cursos inválidos na plataforma BeeDoo  
Para que esses cursos não possam ser salvos e visualizados por outros usuários  

### Decisões Tomadas:
**1 - Validação de campos:** decidi considerar grande parte dos campos como obrigatórios, no intuito de que qualquer entrada inválida seja informada para o usuário.  
**2 - Mensagens de erro claras:** Implementamos mensagens de erro claras e específicas para orientar o usuário na correção das entradas inválidas.  
**3 - Teste de limitações de campo:** Decidimos testar os limites e as restrições dos campos, como tamanho máximo e mínimo de caracteres, formatos de data, e padrões de URL.  
**4 - Bloqueio de envio:** O envio do cadastro de curso será bloqueado até que todos os campos possuam entradas válidas, garantindo assim a integridade dos dados.  

## User Story 3: 
Ao acessar a plataforma e tendo cursos cadastrados  
Eu quero realizar a exclusão de um registro  
Para que o curso deixe de ser apresentado  

### Decisões Tomadas: 
**1 - Confirmação de Exclusão:** mensagem clara de confirmação antes da exclusão.  
**2 - Permissões de Usuário:** apenas usuários com permissões adequadas podem excluir cursos.  
**3 - Curso Após a Exclusão:** o curso não deve ser mais apresentado após o processo.  

## User Story 4: Edição de registros de cursos

Ao acessar a plataforma  
Eu quero editar os registros de cursos existentes 
Para que eu possa atualizar os registros dos cursos conforme necessário

### Decisões Tomadas:
**1 - Interface de Edição:** editar as informações do curso através de uma interface de edição de curso semelhante à interface de cadastro, com campos pré-preenchidos com as informações atuais do curso.  
**2 - Validações:** manter as mesmas validações aplicadas no cadastro de curso, garantindo que as informações editadas sejam válidas.  

## Links
#### **Casos e Cenários de Testes:** https://docs.google.com/document/d/1GSmhuRpR_U-ufp4OgXQJniwVp-6KIcQW0j1_gZqTLyg/edit?usp=sharing
#### **Vídeos das Simulações Realizadas:** https://1drv.ms/f/c/a2f3b9d1c3e143ca/EkBRP6neh9xMoraZh-Oc8KsBYOcRPXgrBaWgijpbHbK_HA?e=qFyM7O
#### **Erros encontrados:** https://docs.google.com/document/d/1non-XXVclP8Z7cZY4o5Ve_cmoai3O-rCk3g1Szdj0Xs/edit?usp=sharing  
#### **Sugestões de melhorias:** https://docs.google.com/document/d/1aw6nWN_wfOs7YtRF8_5QJilOmoJPtMoc33-nXZBZy_c/edit?usp=sharing  
#### **Exemplos melhorias visuais:** https://www.figma.com/design/g2UthVXWmmT29dF5CzLBdy/Untitled?node-id=0-1&t=gtp1V6RrhiKv5tvr-1
