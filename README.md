## 💻 Winforms-Crud
Exemplo de criação de CRUD em Windows Form C# com banco de dados MySQL.

#### O que voçê vai ver nesse Projeto
| Tecnologia | Descrição |
|-----------|-----------|
|  **DAO** | Componente (Data Access Object) é um padrão de projeto que centraliza e isola toda a lógica de persistência e acesso a dados. |
|  **VO** | Value Object (Objeto de Valor), um conceito do Domain-Driven Design (DDD) usado para representar um valor descritivo sem identidade conceitual própria |

#### Requisitos do Projeto
- Para executar a aplicação é necessário a executar o Script do MySQL.

#### 🔄 Executar a aplicação
- Necessário varinha mágica na Solução do Visual Studio

#### ⚠️ String de conexão do banco
Modifique a string de conexão no arquivo **app.config**, no trecho indicado:

```bash
connectionString="server=127.0.0.1;userid=root;password=SUASENHA;database=SEUBANCO;persistsecurityinfo=True"
```
O script para criação da tabela do exemplo encontra-se na pasta **Database**.
