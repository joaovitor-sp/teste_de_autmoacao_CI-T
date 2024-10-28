# teste_de_autmoacao_CI-T

## primeiro caso:

```
Funcionalidade: Busca no Banco de Questões
Cenário: Busca por questão inexistente
Dado que navego para a página de busca do banco de questões
E digito 'Science: Computers' no campo de busca
Quando clico no botão de buscar
Então visualizo uma mensagem de erro com o texto 'No questions found.'
```

```
Funcionalidade: Busca no Banco de Questões
Cenário: Busca por questão existente
Dado que navego para a página de busca do banco de questões
E digito 'What does GPS stand for?' no campo de busca
Quando clico no botão de buscar
Então visualizo o resultado:
(imagem)'
```
<img src="resultado existente na busca.png">
