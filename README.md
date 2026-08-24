# Pipeline CI/CD com Python e GitHub Actions

## 1. O que representa a etapa de CI neste projeto?

A CI testa automaticamente o código para verificar se está funcionando corretamente.

## 2. O que impede a execução do Continuous Delivery quando existe um defeito?

O `needs: ci` faz o Delivery depender do sucesso do CI. Se um teste falhar, o Delivery não é executado.

## 3. Qual seria a próxima etapa necessária para transformar este pipeline em Continuous Deployment?

Seria configurar a implantação automática do código em um ambiente de produção.
