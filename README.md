# Docket - Trabalhe conosco | Dev. Front-end

## Proposta
Este é um teste para a área de desenvolvimento Front-end. A partir deste briefing, a Docket propõe a você, criar um sistema de solicitação de documentos.

**Links úteis**
- [Layout - Adobe XD](https://xd.adobe.com/view/de1c9231-1542-41b5-ad00-355ebf402162-8b4f/grid/)

## Briefing
Uma empresa com a proposta de desburocratizar os serviços cartorários para pessoas físicas e pequenas empresas, precisa solicitar documentos a um cartório. 

Para o operador do sistema solicitar os documentos, ele deve:

- Cadastrar novos documentos a serem solicitados ao cartório
- Visualizar uma lista de todos os documentos que serão solicitados ao cartório com os seguintes informações:
    - Nome do documento
    - Tipo de pessoa (Física ou Jurídica)
    - Nome da pessoa (PF) ou razão social (PJ)
    - Documento CPF ou CNPJ
    - CEP do cartório a ser solicitado
    - Endereço completo do cartório (rua, número, cidade e estado)
    - Data de criação do documento
- Visualizar todas as informações do meu pedido
- Remover algum documento da lista de solicitações ao cartório

#### Requisitos obrigatórios de desenvolvimento
- A listagem, o cadastro e a exclusão de documentos devem ser feitas através de uma API REST. Para criar essa API, utilize o pacote NPM [Json Server](https://www.npmjs.com/package/json-server).
- Utilizar algum pré-porcessador CSS (Exemplo: sass ou less)
- Realizar validação de campos com preenchimento obrigatório
- Adicionar máscaras de CNPJ, CPF e CEP
- Retornar feedback de cadastro e exclusão de documento
- Adicionar Empty Space com a mensagem de "Nenhum documento criado" quando não houver documentos na listagem
- Atualizar contagem de documentos no título da listagem, conforme os itens forem adicionados ou removidos

**ATENÇÃO**
- O teste precisa ser desenvolvido em HTML e JavaScript Vanila

#### Requisitos opcionais
- Realizar preenchimento automático dos campos de endereço após o usuário digitar o CEP. Utilize a API do [Via CEP](https://viacep.com.br/)
- Criar uma páginação de documentos, caso a listagem ultrapasse mais de 10 itens
- Exibir uma mensagem indicando ao usuário que a aplicação esta processando a requisição, enquanto realiza a criação de um novo de documento. (Loading)

#### Será avaliado
- Conclusão dos requisitos obrigatórios
- Fidelidade ao layout
- Organização do código
- Responsividade
- Semântica

É importante: 
- Documentar como executar o projeto, iremos seguir o passo a passo descrito 

# Como participar
- Crie um repositório público no github e coloque o código fonte do projeto.
- Envie uma mensagem de email para o endereço brenda.araujo@docket.com.br, com o seguinte conteúdo:
    - Link do repositório criado para o teste do github
    - Currículo em anexo ou link do perfil no linkedin.com
    
#### Atenção:
Não conseguiu finalizar o teste? Não tem problema. Mande mesmo assim que iremos avaliar o seu esforço. Boa sorte!
