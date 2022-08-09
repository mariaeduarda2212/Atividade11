# Programa de bolsas DevSecOps CompassUol- Atividade 11- Trilha Linux e atividade de redes.

Componentes do grupo: Maria Eduarda Araújo de Oliveira.

## Projeto

O projeto em questão foi solicitado pela empresa Compass UOL especificamente como atividade prática no desenvolvimento da trilha de Certificação LPI Linux Essentials. Referente ao estágio de DevSecOps.

Os instrutores solicitaram na atividade que subíssemos um segundo servidor Oracle Linux seguindo as configurações da Maquina Virtual da atividade anterior, sem interface gráfica, adicionando algumas alterações no desenvolvimento do projeto.

Desta forma, devemos mudar a VLAN das duas de Nat para Modo Bridge realizando os ajustes necessários, realizando a relação de consiança entre as duas Máquinas Vituais.

Ainda, é necessário criar um slide respondendo as perguntas especificas feitas pelos instrutores e uma documentação explicando qual o processo para instalação do linux, bem como realizar o versionamento da atividade.

## Desenvolvimento
Para esse desenvolvimento, iremos usar virtualbox como um ambiente virtual usaremos a ISO do ORACLE LINUX.

## Tarefas
Para essa aplicação serão necessárias as seguintes tarefas:

[T-01] Subir uma segunda VM (seguindo as mesmas regras da atividade anterior);

[T-02] Mudar a VLAN das 2 para BRIGDER e fazer os ajustes necessário;

[T-03] Criar uma apresentação de slides com 1 slide para cada um dos tópicos;

[T-3.1] O que significa o "." na frente de um arquivo?

[T-3.2] O que faz o comando vdisplay?

[T-3.3] Como saber quanto espaço livre eu tenho em um Volume Group?

[T-3.4] O que o /dev/sda no comando "fdisk -l |grep sd"?

[T-04] Configurar a relação de confiança entre as duas VMs;

[T-05] Criar um projeto de versionado;

[T-06] Fazer uma documentação explicando o processo de instalação do Linux;

## Configuração de redes

# Maquina Server:
[IP] 10.0.2.17(classe A);

[Netmask] 255.255.255.0(/24);

[Gateway] 10.0.2.2;

[DNS] server;

[HOSTNAME] compass.atividade11server;

# Maquina Client
[IP] 10.0.2.17(classe A);

[Netmask] 255.255.255.0(/24);

[Gateway] 10.0.2.2;

[DNS] client;

[HOSTNAME] compass.atividade11client;

## Entrega
Deverá ser desenvolvido a aplicação em questão e entregue através do Github e com a documentação do READ.ME.

Segue-se um link mais detalhado dos comandos usados desse projeto:

[Comandos Utilizados na Atividade.docx](https://github.com/mariaeduarda2212/atividade11/files/9162607/Comandos.Utilizados.na.Atividade.docx)

[Apresentação da Atividade11.pptx](https://github.com/mariaeduarda2212/atividade11/files/9169169/Apresentacao.da.Atividade11.pptx)

[Documentação Linux.pdf](https://github.com/mariaeduarda2212/atividade11/files/9168843/Documentacao.Linux.pdf)

Documentação Linux: https://site111550.nicepage.io/?version=f547af85-b573-4d6c-909f-2d5eafb2002b&uid=a1152040-3004-4a30-acd6-d035a2012360

Video de documentação: https://youtu.be/tMB2NdOU05s

Deverá ser concluído até o dia 22/07/2022 às 14:30.
