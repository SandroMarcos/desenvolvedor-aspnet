# Sobre a Plan B
Agência de comunicação que busca promover diálogos entre marcas e pessoas. Localizada em Belo Horizonte, a [Plan B](http://planb.com.br/) tem a inovação, a criatividade e a simplicidade como premissas para a construção de relacionamento com o público.

A Plan B acredita que a troca de conhecimento é a chave para a adaptação num mundo onde é preciso estabelecer novos precedentes todos os dias. Veja algumas das nossas iniciativas no [Plan B University](http://u.planb.com.br/).

Utilizamos Ruby on Rails, ASP.NET MVC (C#) e PHP como principais plataformas de desenvolvimento, mas o time é incentivado a explorar e testar novas tecnologias para desenvolvimento, buscando mais agilidade, performance e diversão. :)

# Desenvolvedor Web 
Requisitos 
- Conhecimento intermediário/avançado em ASP.NET MVC (linguagem C#) 
- Conhecimento básico em Ruby on Rails
- Git
- Experiência com o banco de dados SQL Server e Mysql

Desejável 
- Conhecimento de processos ágeis (Scrum) 
- DevOps e/ou ChatOps

Funções
Desenvolver projetos de tecnologia para web desde a concepção até o acompanhamento e evolução em produção. Programação, análise, performance e comunicação. 


# Teste Prático - Etapa 01
Neste teste prático serão avaliados raciocínio lógico, criatividade, conhecimento técnico e interpretação. Deve ser utilizado .net framework 4.5 ou superior.

Esta etapa deve ser entregue via pull request. O prazo sugerido para entrega é de até 3 dias a partir do nosso contato. Caso seja entregue após o prazo, se a vaga ainda estiver aberta, você poderá prosseguir normalmente no processo. Note que, quanto antes entregar, maiores serão suas chances de ser avaliado antes da vaga ser preenchida.

Selecionaremos os melhores trabalhos para prosseguir no processo de seleção. Boa sorte!

#### Requisitos:
- Criar um site em ASP.NET MVC com uma área restrita para administradores (acesso restrito para Administrador). 
- Administradores poderão cadastrar novos usuários dos tipos PROGRAMADOR ou DESIGNER. Campos mínimos: Nome, Login e Senha.
- Administradores podem cadastrar Skills. Campos mínimos: Nome.
- Administradores podem atribuir/relacionar usuários (de ambos os tipos) com skills.
- Deve existir uma listagem, na área restrita para administradores, onde seja possível visualizar usuários e suas skills.
-

O banco de dados utilzado é o SQLite, que está localizado na pasta App_Data, o banco está vazio, ao realizar o primeiro acesso, é necessário criar um usuário, este primeiro usuário já será um usuário Administrador, a partir dos próximos o usuário será criado como não administrador.

O sistema foi feito em duas camadas, utilizando o conceito de DDD.
Na primeira camada que é o nosso domínio, utilizei o ORM NHibernate para o mapeamento, e também utilizamos o NInject para a Injeção de dependência.
Na segunda camada, que é a parte Web, a comunicação entre server-client, a responsabilidade ficou por conta do AngularJS e o CSS bootstrap.

