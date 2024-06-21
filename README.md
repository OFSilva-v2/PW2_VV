# Trabalho final da cadeira de PW2_VVS

# Accounts Manager - planilhas para controle de gastos.

## Plano de testes
Como a aplicacao *nao possui front-end desenvolvido*, os seguintes requisitos do projeto final da disciplina foram implementados:
- [x] Escrever um **plano de teste**, ou seja, um documento que descreva cada teste juntamente com as entradas e saidas esperadas. 
- [x] Implementar uma **verificacao estatica** no projeto (**PMD** e/ou **SonarClould** - foi instalado o PMD no projeto e utilizado SonarLint no VS Code)
- [x] Implementar um **conjunto de testes unitarios**
- [x] Configure um ambiente de integracao continua de sua escolha, por exemplo, **Github Actions**, Jekins, Travis, Circle-CI, GitLab, entre outros.

### Verificacao estatica
A verificacao estatica foi feita atraves da adicao do plugin e da extensao do PMD juntamente com a adiaoo da extencao do Sonarlint ao projeto no VS Code, foi seguido o passo-a-passo para a implementacao do Github Actions.

### Testes Unitarios
Pasta de testes contem testes para os metodos basicos das classes, verificando se os mesmos funcionam confirme esperado.

### Github Actions CI/CD
Foram implementadas actions de build com Java CI com Maven e Revisao de dependencias.
