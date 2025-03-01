# Projeto Insight

## Visão Geral
O **Projeto Insight** é um site desenvolvido em Python utilizando a biblioteca Django. O site irá implementar todas as operações de CRUD do Django com duas ou mais entidades relacionadas. Além disso, ele irá consumir a 'Advice Slip API' como API externa: [Advice Slip API](http://api.adviceslip.com/advice).

### Documentação Requerida
O projeto contará com os seguintes documentos:
1. `.gitignore` - Arquivo para ignorar arquivos específicos no Git.
2. `requirements.txt` - Lista de dependências do projeto.
3. `README.md` - Documento de introdução e instruções do projeto.
4. `Dockerfile` - Arquivo de configuração para containerização do projeto.

### Diferenciais do Projeto
- **Banco de Dados Externo**: Utilização do MySQL como banco de dados externo.
- **Commits Semânticos**: Uso de commits semânticos para um histórico de alterações claro e significativo.
- **Boas Práticas**: Seguir as melhores práticas de programação com uma boa organização de diretórios e branches.
- **Nomenclatura Correta**: Arquivos devidamente nomeados de forma clara e padronizada.
- **Simplicidade**: Funções e entidades simples para melhor manutenção e entendimento.
- **Repositório Organizado**: O repositório do GitHub será organizado e a documentação será bem detalhada.
- **Front-end Conceitual**: A interface será desenvolvida de forma simples e conceitual.
- **Tokens de Autenticação**: Implementação de tokens de autenticação para segurança do usuário.

### Funcionalidade do Site
O **Insight** permitirá que os usuários:
1. Digitem uma palavra-chave para receber um conselho relacionado a essa palavra.
2. Salvem, editem e excluam conselhos personalizados na aba "Meus Conselhos".

## Fluxo do Usuário
1. **Inserir Palavra-Chave**: O usuário digita uma palavra-chave no campo de busca.
2. **Receber Conselho**: O site fornece um conselho relacionado à palavra-chave.
3. **Salvar Conselho**: O usuário pode salvar o conselho na aba "Meus Conselhos".
4. **Editar/Excluir Conselho**: O usuário poderá editar ou excluir conselhos salvos conforme sua necessidade.
