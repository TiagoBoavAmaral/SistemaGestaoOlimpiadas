# Sistema de Gestão das Olimpíadas (SGO)

[cite_start]Projeto 1 da disciplina de Projeto de Software do curso de Engenharia de Software da PUC Minas[cite: 1, 4].

## 1. Descrição do Sistema

[cite_start]Com a chegada das Olimpíadas, um novo sistema de gestão é necessário para coordenar os diferentes aspectos do evento[cite: 6]. [cite_start]Este sistema deve permitir o gerenciamento de competições, inscrições de atletas, alocação de locais para as provas, e controle de resultados[cite: 7].

## 2. Histórias de Usuário

[cite_start]Abaixo estão as histórias de usuário que descrevem as funcionalidades do sistema, baseadas nas regras de negócio [cite: 8-20].

* [cite_start]**US01 (Cadastrar Competição):** Eu, como Administrador, quero cadastrar uma nova competição (com modalidade, data, horário e local), para que o evento possa ser organizado e os atletas possam se inscrever[cite: 10].
* [cite_start]**US02 (Inscrever Atleta):** Eu, como Administrador, quero inscrever um atleta (de um país específico) em uma ou mais competições, para que ele possa participar[cite: 12, 13].
* [cite_start]**US03 (Validação de Inscrição):** Eu, como Administrador, quero que o sistema valide que um atleta só possa representar um país por modalidade, para garantir a conformidade com as regras olímpicas[cite: 13].
* [cite_start]**US04 (Alocar Local):** Eu, como Administrador, quero alocar um local para uma competição em um horário específico, para que as provas possam ocorrer[cite: 15].
* [cite_start]**US05 (Validação de Alocação):** Eu, como Administrador, quero que o sistema me impeça de alocar um local que já esteja em uso no mesmo horário, para evitar conflitos de agendamento[cite: 15, 16].
* [cite_start]**US06 (Registrar Resultados):** Eu, como Administrador, quero registrar os resultados de uma competição finalizada, para determinar os atletas em primeiro (ouro), segundo (prata) e terceiro (bronze) lugares[cite: 18, 19].
* [cite_start]**US07 (Gerar Relatório de Medalhas):** Eu, como Administrador (ou Público), quero gerar um relatório de medalhas, mostrando o desempenho de cada país com base nas medalhas conquistadas, para acompanhar o ranking geral[cite: 20].

## 3. Diagramas UML

[cite_start]Conforme solicitado[cite: 39], seguem os diagramas de modelagem do sistema.

### Diagrama de Caso de Uso
*Modele os casos de uso principais, como "Cadastrar Competição", "Inscrever Atleta", "Alocar Local", e "Registrar Resultados". Identifique os atores e as interações principais.* [cite: 25, 26]

<img width="500px" height="500px" src="imagens/diagrama-de-caso-de-uso.png"/>

### Diagrama de Classes e de Pacotes
*Crie um diagrama de classes que reflita a estrutura do sistema, incluindo classes como Competição, Atleta, Local, Resultado e País. Organize o sistema em pacotes para separar as diferentes responsabilidades.* [cite: 27, 28]

**Diagrama de Classes:**
<img width="500px" height="500px" src="imagens/diagrama-de-classes.png"/>

**Diagrama de Pacotes:**
<img width="500px" height="500px" src="imagens/diagrama-de-pacotes.png"/>

### Diagrama de Componentes
[cite_start]*Modele os componentes principais do sistema, como Interface de Usuário, Módulo de Inscrições, Módulo de Alocação, e Módulo de Relatórios, mostrando como eles interagem entre si.* [cite: 29]

<img width="500px" height="500px" src="imagens/diagrama-de-componentes.png"/>

### Diagrama de Implantação
[cite_start]*Desenvolva um diagrama de implantação que ilustre a arquitetura física do sistema, incluindo servidores, bancos de dados, e dispositivos dos usuários.* [cite: 30]

<img width="500px" height="500px" src="imagens/diagrama-de-implantação.png"/>

## 4. Estrutura do Repositório

[cite_start]A estrutura de arquivos deste repositório segue as instruções fornecidas[cite: 43]:
