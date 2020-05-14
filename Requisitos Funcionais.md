# Levantamento-de-Requisitos
Levantamento de Requisitos de um sistema voltado à gestão de condomínios

ID:	RF01

Título:	Entrar

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário pode acessar a aplicação web com o seu e-mail e CPF já cadastrados. O usuário deve selecionar seu perfil: funcionário ou morador. Caso o usuário selecione um perfil que não seja compatível com o seu cadastro ele não poderá entrar no sistema e uma mensagem de erro deve ser exibida.
Esta função deve conter campos de dados capacitados para receber as seguintes informações obrigatórias:
- E-mail;
- CPF;
- Perfil.
Após usuário preencher todas informações solicitadas ele deve clicar na opção “ENTRAR”.


                           

ID:	RF02

Título:	Criar Mensagem

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário pode criar uma mensagem, com visualização para todos os usuários de seu condomínio.
 Esta função deve estar disponível dentro da opção “MENSAGENS”, para o usuário acessá-la basta clicar na opção “CRIAR MENSAGEM”.
Esta função deve conter campos de dados capacitados para receber as seguintes informações obrigatórias:
- CPF;
- Título;
- Data (DD/MM/AAAA);
- Descrição.
Após o usuário preencher todas informações solicitadas ele deve clicar na opção “CRIAR”.



ID:	RF03

Título:	Visualizar Mensagens

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário pode visualizar todas mensagens criadas. Esta função deve estar disponível dentro da opção “MENSAGENS”, para o usuário acessá-la basta clicar na opção “VISUALIZAR MENSAGENS” e deve ser mostrado as mensagens e o ID pertencente.



ID:	RF04

Título:	Reservar Espaço

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário (funcionário síndico e morador) pode realizar a reserva de qualquer espaço disponível do condomínio. Esta função deve estar disponível dentro da opção “ESPAÇO”, para o usuário acessá-la basta clicar na opção “RESERVAR ESPAÇO”. Todas as áreas comuns são configuradas individualmente, automatizando processos e garantindo uma gestão tranquila. 
Esta função deve conter campos de dados capacitados para receber as seguintes informações obrigatórias:
- Nome do Evento;
- CPF;
- Data;
- Local (espaço gourmet, salão de festas, quadra de tênis, quadra de futebol, churrasqueira, salão de beleza);
- Início (8:00 ás 22:00);
- Término (8:00 ás 22:00);
- Convidados;
- Descrição do evento;
- As reservas do espaço gourmet, salão de festas e churrasqueira podem apenas ter no máximo 6 (seis) horas de duração;
- As reservas do espaço gourmet, salão de festas e churrasqueira podem apenas ter no máximo 50 convidados;
- As reservas da quadra de tênis, quadra de futebol e salão de beleza podem apenas ter no máximo 3 (três) horas de duração; 
- As reservas da quadra de tênis, quadra de futebol e salão de beleza podem apenas ter no máximo 15 convidados;
Após o usuário preencher todas informações solicitadas ele deve clicar na opção “CONCLUIR”.



ID:	RF05

Título:	Visualizar Reservas

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário (funcionário síndico ou morador) pode visualizar todas reservas realizadas. Esta função deve estar disponível dentro da opção “ESPAÇO”, para o usuário acessá-la basta clicar na opção “VIZUALIZAR RESERVAR” e deve ser mostrado as reservas e o ID pertencente.



ID:	RF06

Título:	Registrar (Ocorrência)

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário (funcionário síndico e morador) pode registrar uma mensagem de ocorrência, com visualização para todos os usuários de seu condomínio. Esta função deve estar disponível dentro da opção “OCORRÊNCIA”, para o usuário acessá-la basta clicar na opção “REGISTRAR OCORRÊNCIA”.
Esta função deve conter campos de dados capacitados para receber as seguintes informações obrigatórias:
- CPF;
- Título;
- Data;
- Descrição.
Após o usuário preencher todas informações solicitadas ele deve clicar na opção “REGISTRAR”.



ID:	RF07

Título:	Visualizar (Ocorrências )

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário (funcionário síndico e morador) pode visualizar todas as ocorrências registradas.
Esta função deve estar disponível dentro da opção “OCORRÊNCIA”, para o usuário acessá-la basta clicar na opção “VIZUALIZAR OCORRÊNCIAS”.



ID:	RF08

Título:	Selecionar Documento (Controle Financeiro)

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário (síndico) pode selecionar um documento pertencente ao condomínio, com visualização para todos os usuários de seu condomínio. Esta função deve estar disponível dentro da opção “CONTROLE FINANCEIRO”, deve existir as seguintes opções: conta de luz, conta de água, despesas de manutenção e taxa de condomínio. 
Esta função deve exibir ao usuário a opção “SELECIONAR ARQUIVO”, após o usuário selecionar o arquivo desejado ele deve digitar a data e clicar na opção “PUBLICAR”. 



ID:	RF09

Título:	Visualizar Documentos (Controle Financeiro)

Tipo:	Funcional

Responsável:	Vinicius Vidal
Descrição:	Através desta função o usuário pode visualizar todos documentos publicados de seu condomínio. Esta função deve estar disponível dentro da opção “CONTROLE FINANCEIRO”, para o usuário acessá-la basta clicar na opção “VISUALIZAR DOCUMENTOS” e deve-se selecionar de qual mês deseja-se encontrar os documentos, após escolher o mês todos os documentos postados naquele mês devem ser mostrados para o usuário.




ID:	RF10

Título:	Excluir Conta

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através desta função o usuário pode excluir seu cadastro do sistema. Ela deve estar disponível para todos os usuários e o sistema deve solicitar as seguintes informações para concluir a exclusão:
- CPF;
- E-mail.
O usuário deve clicar em “EXCLUIR CONTA” e uma mensagem de confirmação perguntando se o usuário realmente deseja excluir sua conta deve ser mostrada com as seguintes opções “SIM” e “NÂO”. Se o usuário clicar em “SIM” a conta deve ser excluída, caso contrário o procedimento deve ser encerrado.



ID:	RF11

Título:	Contato

Tipo:	Funcional

Responsável:	Vinicius Vidal

Descrição:	Através dessa função qualquer pessoa que entre no site https://blueskyadm.000webhostapp.com/, acesse  a aba “Contato”, na mesma o usuário deve preencher os seguintes campos “Opções: Contato / Reclamações / Sugestões”, “Nome”, “Telefone”, “E-mail” e “Assunto”, obrigatório preenchimento de todos os campos*, o usuário deve clicar no botão “Enviar” para que todas as informações sejam armazenadas no banco de dados da empresa Bluesky.
                           
