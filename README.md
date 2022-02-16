# Situação de Aprendizagem 1: Solução em software

A empresa na qual você trabalha precisa de uma solução em software para gerenciar as vagas em aberto no departamento de recursos humanos. Os requisitos desta funcionalidade são:

RF01 – Deve permitir o cadastramento das vagas de emprego em aberto, informando: identificador da vaga (idvaga), descrição do cargo, requisitos obrigatórios, requisitos desejáveis, remuneração mensal (R$), benefícios e local de trabalho.
RF02 – Deve permitir alterações nos dados das vagas, inclusive indicando se foram preenchidas ou não.
RF03 – Deve permitir a exclusão de vagas.
RF04 – Deve exibir todas as vagas em formato de lista;

## Passo 1

Faça um clone deste projeto em uma pasta vazia da sua máquina.

## Passo 2

Abra o terminal e digite `npm install`. Este comando irá instalar/atualizar todas as dependências necessárias para rodar este projeto na sua máquina. No final, a pastinha 'node_modules' deverá aparecer no projeto.

## Passo 3

Abra o terminal e digite `json-server --watch vagas-db.json`. O JSON Server é uma biblioteca capaz de criar uma API Fake em 30 segundos, sem precisar escrever nenhuma linha de código. Você só precisa rodar o comando acima e seu servidor estará iniciado. Lembrando que por padrão a API vai funcionar no enderço: http://localhost:3000.

## Passo 4

último passo! Abra o terminal e digite `ng serve`. Este comando faz com que sua aplicação frontend fique disponível localmente. Para ver o projeto funcionando, acesse este link: http://localhost:4200/
