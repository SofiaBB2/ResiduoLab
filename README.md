# ResiduoLab
Este repositório busca documentar o desenvolvimento do projeto ResiduoLab ChemSafe: Sistema Laboratorial de Resíduos Químicos, do IFPR - Campus Paranavaí. 

# Ambientes
O ambiente de desenvolvimento utilizado será o Visual Studio Code, com linguagem pyhton e framework Django. Já para staging e produção hospedaremos o código e o banco de dados no serviço PythonAnywhere, que oferece bom suporte para aplicações web e colaboração entre desenvolvedores.

# Versionamento
Seguiremos o modelo Git-flow, onde:
- a branch _main_ contém o código em produção, já testado e estável;
- a branch _develop_ contém as funcionalidades ainda em fase de teste, antes do envio para _main_;
- as branches com padrão _feature/nome-da-funcionalidade_ nascem da branch _develop_ e depois são integradas a ela.
