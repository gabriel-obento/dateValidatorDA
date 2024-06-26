# Oracle Apex Date Validator Plugin

https://github.com/gabriel-obento/dateValidatorDA/assets/168774661/62961f2b-55f6-43db-a690-25f8040f410a

#### Plugin desenvolvido em Oracle APEX para validar a datas no padrão informado, não permitindo que o usuário saia do campo se a data estiver inválida.

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabrielbento-devapex/)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gabriel-obento)

### Recursos e Linguagens
![Oracle](https://img.shields.io/badge/Oracle-F80000??style=for-the-badge&logo=Oracle&logoColor=white)
![APEX Community](https://cdn.rawgit.com/Dani3lSun/apex-github-badges/78c5adbe/badges/apex-community-badge.svg)

![APEX Plugin](https://cdn.rawgit.com/Dani3lSun/apex-github-badges/b7e95341/badges/apex-plugin-badge.svg)
![APEX javascript](https://cdn.rawgit.com/Dani3lSun/apex-github-badges/6ed914a1/badges/apex-javascript-badge.svg)
![APEX PL/SQL](https://cdn.rawgit.com/Dani3lSun/apex-github-badges/6ed914a1/badges/apex-plsql-badge.svg)

![APEX Build With](https://cdn.rawgit.com/Dani3lSun/apex-github-badges/7919f913/badges/apex-love-badge.svg)

## Como usar:
### Instalação
1 - Faça download do ZIP que contém o arquivo do plugin.

2 - Instale o Plugin no Oracle Apex.

### Configuração
1 - Na página que deseja utilizar, crie uma nova ação dinâmica no ``` Page Load ```.

2 - Em ``` True Action ```, selecione o Plugin ``` datevalitadorDA ```.

3 - Em ``` configurações ``` na opção ```Botões```, adicione o(s) ```Static ID``` do(s) botão(ões) que desabilita(m) ao preencher a data. *(Não obrigatório)*

4 - ```Text Fields:``` Caso o tipo do item seja ```text field``` é obrigatório o preenchimento do atributo ```Format Mask``` *no Plugin*.

5 - ```Date Pickers:``` Caso o tipo do item seja ```Date Picker``` é obrigatório o preenchimento do atributo ```Format Mask``` *diretamente no item*.

6 - Selecione o item afetado pela ação dinâmica. *(Selecione somente UM ITEM por ação.)*

<img width="838" alt="image" src="https://github.com/gabriel-obento/dateValidatorDA/assets/168774661/b499d5a7-f8b9-4e23-b360-40eebc1c157b">

*Obs.: Verifique a seção Ajuda nos atributos do plugin para mais informações sobre quais padrões utilizar.*

[Ver Demonstração](https://apex.oracle.com/pls/apex/r/gabriel_bento/date-validator-plugin-da/tela-demonstracao)
#
### Compatibilidade
![Google Chrome](https://img.shields.io/badge/Google_chrome-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white)
![Google Chrome](https://img.shields.io/badge/Safari-FF1B2D?style=for-the-badge&logo=Safari&logoColor=white)

(Não testado em outros navegadores)
#
### Oracle APEX Version
Suporte para versão **22** e **23** do Oracle Application Express.
#
Se tiver alguma dúvida de utilização ou sugestão de melhoria, estou à disposição!

Fique à vontade para me contatar.

Obrigado por sua visita!
