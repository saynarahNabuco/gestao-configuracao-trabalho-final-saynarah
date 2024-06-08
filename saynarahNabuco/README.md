## Configuração de Variáveis de Ambiente

Para configurar a aplicação corretamente, é necessário definir algumas variáveis de ambiente. Estas variáveis devem ser definidas no arquivo `.env` localizado no diretório raiz do projeto. Abaixo está a descrição de cada variável:

- `DATABASE_URL`: URL de conexão com o banco de dados. Formato: `mysql://user:password@localhost:3306/database`
  - Exemplo: `mysql://root:senha123@localhost:3306/meubanco`

- `SECRET_KEY`: Chave secreta usada pela aplicação para várias funcionalidades de segurança.
  - Exemplo: `your_secret_key_here`

- `API_KEY`: Chave de acesso para APIs externas usadas pela aplicação.
  - Exemplo: `123456789abcdef`

- `DEBUG_MODE`: Define se a aplicação deve rodar em modo de depuração. Pode ser `True` ou `False`.
  - Exemplo: `True`

- `TIMEZONE`: Define o fuso horário padrão para a aplicação.
  - Exemplo: `America/Sao_Paulo`

Certifique-se de configurar corretamente todas as variáveis acima antes de iniciar a aplicação.
