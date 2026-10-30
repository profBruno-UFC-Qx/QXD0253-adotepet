# :checkered_flag: AdotePet

O projeto visa criar uma plataforma organizada para intermediar o contato entre doadores — sejam ONGs ou protetores independentes — e adotantes de animais, trazendo estrutura e facilidade a um processo hoje dependente de redes sociais e divulgação informal.

## :technologist: Membros da equipe

Matrícula: 579925
Nome: Vicente de Paulo da Silva Neto
Curso: Engenharia de Software

## :bulb: Objetivo Geral
Desenvolver uma plataforma digital centralizada para conectar ONGs e doadores independentes a potenciais adotantes, otimizando a comunicação e promovendo a organização do processo de adoção de animais

## :eyes: Público-Alvo
ONGs, Doadores independentes e Adotantes

## :star2: Impacto Esperado
Espera-se que o projeto centralize e otimize a divulgação de animais para adoção, aumente a taxa de adoções bem-sucedidas e reduza a dependência de métodos informais de divulgação, proporcionando maior segurança, alcance e organização para ONGs e doadores independentes.lvo

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

Adiministrador, Doadores e Adotantes

> Tenha em mente que obrigatoriamente a aplicação deve possuir funcionalidades acessíveis a todos os tipos de usuário e outra funcionalidades restritas a certos tipos de usuários.

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

### Funcionalidades Públicas (Visitantes)
- [x] **Visualização de Animais:** Navegação pelas postagens de animais disponíveis para adoção.
- [x] **Busca e Filtragem:** Pesquisa avançada por localização/região, tipo de animal e nome do doador.
- [x] **Perfis de Doadores:** Acesso aos perfis públicos de ONGs e protetores independentes.

### Funcionalidades de Usuários Autenticados
- [x] **Gestão de Anúncios:** Criação e publicação de postagens de doação de animais.
- [x] **Solicitação de Adoção:** Envio de pedidos formais de interesse para adoção.
- [x] **Chat Integrado:** Canal de conversa direta para alinhamento de detalhes e acompanhamento pós-adoção.
- [x] **Sistema de Moderação:** Denúncia de perfis ou conteúdos impróprios.

## :spiral_calendar: Entidades ou tabelas do sistema

 **Usuário (`User`):** Armazena dados de autenticação e perfil de doadores, adotantes e ONGs.
- **Animal / Anúncio (`Pet`):** Registra as informações do animal cadastrado para adoção.
- **Solicitação de Adoção (`AdoptionRequest`):** Gerencia o fluxo do pedido de adoção entre adotante e doador.
- **Mensagem / Chat (`Message`):** Canal de comunicação direta e acompanhamento pós-adoção.
- **Denúncia (`Report`):** Registra alertas de conteúdo ou comportamentos impróprios para moderação.
