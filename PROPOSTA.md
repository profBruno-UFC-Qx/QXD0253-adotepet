# :checkered_flag: AdotePet

O projeto visa criar uma plataforma organizada para intermediar o contato entre doadores — sejam ONGs ou protetores independentes — e adotantes de animais, trazendo estrutura e facilidade a um processo hoje dependente de redes sociais e divulgação informal.

## :technologist: Membros da equipe

Matrícula: 579925
Nome: Vicente de Paulo da Silva Neto
Curso: Engenharia de Software

## :bulb: Objetivo Geral
Desenvolver uma plataforma digital centralizada para conectar ONGs e doadores independentes a potenciais adotantes, otimizando a comunicação e promovendo a organização do processo de adoção de animais

## :eyes: Público-Alvo

- **ONGs e Protetores Independentes:** Organizações e voluntários que necessitam de um canal centralizado para divulgar resgates e gerenciar solicitações de adoção.
- **Doadores Pessoais:** Indivíduos que precisam encontrar um novo lar para um animal de forma segura e organizada.
- **Potenciais Adotantes:** Pessoas e famílias que buscam adotar um animal de estimação filtrando por região, espécie e características do pet.
- **Comunidade Geral:** Pessoas interessadas em acompanhar, apoiar ou entrar em contato com ONGs e protetores da sua região.

## :star2: Impacto Esperado
Espera-se que o projeto centralize e otimize a divulgação de animais para adoção, aumente a taxa de adoções bem-sucedidas e reduza a dependência de métodos informais de divulgação, proporcionando maior segurança, alcance e organização para ONGs e doadores independentes.lvo

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

- **Visitante (Não Autenticado):**
  - Usuário que navega pela plataforma sem realizar login.
  - Pode buscar, filtrar e visualizar anúncios de animais, além de consultar perfis públicos de doadores e ONGs.

- **Adotante (Usuário Autenticado):**
  - Pessoa física cadastrada na plataforma interessada em adotar um pet.
  - Pode enviar solicitações formais de adoção, conversar diretamente com doadores/ONGs e denunciar conteúdos ou perfis suspeitos.

- **Doador / Protetor Independente (Usuário Autenticado):**
  - Pessoa física cadastrada com permissão para anunciar animais para doação.
  - Pode cadastrar e gerenciar anúncios de pets, avaliar e responder a solicitações de adoção e utilizar o chat para o acompanhamento pós-adoção.

- **ONG / Instituição (Usuário Autenticado):**
  - Perfil jurídico ou organização parceira dedicada à causa animal.
  - Possui as mesmas permissões do doador, acrescido de selo/perfil institucional e espaço para divulgação de informações da entidade.

- **Administrador / Moderador:**
  - Usuário interno responsável pela gestão e integridade da plataforma.
  - Gerencia e analisa denúncias de usuários/anúncios, modera conteúdos impróprios e administra o status de cadastros na plataforma.

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
