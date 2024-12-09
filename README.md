Desenvolvimento de Softwares Multiplataforma
Disciplina: Integração e Entrega Contínua
Prof(a). REGINALDO DONIZETI CANDIDO
Atividade - Aula 3: Práticas de Documentação e Versionamento de Software
Objetivo
Criar e manter uma documentação básica em um projeto Git, usando Markdown e práticas de
versionamento.
Instruções da Atividade
1. Preparação do Repositório
Cada grupo deve criar um novo repositório local em sua máquina. Após criar o repositório, inicializá-lo
com Git usando o comando:
git init
2. Criação do Arquivo README.md
Dentro do repositório, cada grupo deve criar um arquivo `README.md` na raiz do projeto, contendo as
seguintes seções:
- Nome do Projeto: Um título criativo para o projeto.
- Descrição: Um breve resumo explicando o propósito do projeto.
- Equipe: Lista de integrantes do grupo.
- Como Executar o Projeto: Instruções fictícias para rodar o projeto.
Exemplo de estrutura para o `README.md`:
# Gerenciador de Tarefas
Este projeto é um gerenciador de tarefas simples para ajudar os usuários a organizar suas atividades
diárias.
## Equipe
- João Silva
- Maria Oliveira
- Pedro Santos
## Como Executar o Projeto
1. Clone este repositório:
```
git clone <URL_DO_REPOSITORIO>
```
2. Navegue até o diretório do projeto:
```
cd nome-do-projeto
```
3. Execute o comando principal:
```
./iniciar.sh
```
3. Comitando e Versionando o Arquivo README.md
Após criar o arquivo `README.md`, os alunos devem versioná-lo usando os comandos:
git add README.md
git commit -m "Adicionando README inicial"
4. Simulação de Alterações
Cada integrante do grupo deve fazer uma modificação no arquivo `README.md` (como corrigir um erro
de digitação ou adicionar informações fictícias). Após fazer as alterações, cada aluno deve:
1. Realizar o commit das mudanças.
2. Explicar no commit qual alteração foi feita (exemplo: 'Corrigindo erro na descrição do projeto').
5. Histórico de Versionamento
Após todos os commits, os grupos devem verificar o histórico de alterações usando o comando:
git log
Discutam brevemente no grupo: 'Como o controle de versão ajuda na colaboração em projetos?'
Entrega
1. O professor deve verificar se os grupos:
- Criaram o arquivo `README.md` com as seções especificadas.
- Realizaram alterações e commits apropriados.
- Utilizaram mensagens claras para os commits.
2. Cada grupo deve enviar um link para do repositório do GitHub.
