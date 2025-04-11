<center>

# __Padronização das Branches e dos Commits__

</center>

## __Branches__

Este documento serve como um guia para a definição dos padrões de organização das branches e dos commits no que tange o repositório do projeto EuMeAmo, a fim de facilitar a colaboração entre os membros do grupo e garantir a rastreabilidade e organização da contribuição dos estudantes.

## __Commits__

Os padrões de commits serão definidos conforme a documentação do [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).


## __Definição da padronização das Branches__

No atual momento, o padrão de branches do projeto é ramificado a partir da branch **main**. 

<center>

| Prefixo da branch       | Nome da branch       | Quando usar | Exemplo |
| ----------------------- | -------------------- | ----------- | ------- |
| DOCS                  | Nome do artefato     | Construção de documentação | DOCS/5W2H |
| FEAT                    | Nome da feature      | Construção de features | FEAT/contador-calorias |
| FIX                    | Nome da feature      | Correção de erros/bugs | FIX/contador-calorias | 

</center>

## __Definição da padronização dos Commits__

<center>

| Prefixo do commit | Nome do commit | Quando usar | Exemplo | 
| ----------------- | -------------- | ----------- | ------- | 
| docs              | Nome do artefato/documento | Construir artefato/documento | docs: construção do diagrama BPMN | 
| feat              | Nome da feature a ser implementada | Construir novas features | feat: construção da página de login | 
| style             | Nome da feature sendo estilizada | Aplicar estilo em uma feature | style: adicionando bootstrap na tela principal | 
| test              | Nome da feature sendo testada | Construir testes para uma feature | test: adicionando testes para a automatização do sistema de login | 
| fix               | Nome da feature sendo corrigida | Corrigir erros ou bugs em uma feature | fix: corrigindo laço for na lista de clientes | 
| refactor | Nome da feature que será refatorada | Mudança de código para fins de melhor legibilidade | refactor: autenticação do usuário | 

</center>

## Histórico de Versão

| Versão | Data | Descrição | Autor | Revisor
|:-:|:-:|:-:|:-:|:-:|
|`1.0`| 08/04/2025 | Criação do documento| [Lucas Bottino]()| [Luiza Maluf]()|