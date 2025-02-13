# MPU (Analista do MPU - Desenvolvimento de Sistemas) Passo Estratégico de Conhecimentos Específicos - 2025 (Pós-Edital)

**Autor:** Fernando Pedrosa Lopes  
**Data:** 09 de Janeiro de 2025  
**Produto:** MPU (Analista do MPU - Desenvolvimento de Sistemas) Pacote Passo Estratégico - 2025 (Pós-Edital)  
**Professor(a):** Fernando Pedrosa  
**Matéria:** Tecnologia da Informação  
**Cargo:** Desenvolvimento de Sistemas  
**Simulado:** Simulado 01

## Questões de Bancos de Dados e SGBD

### 1. Qual dos seguintes conceitos refere-se à capacidade de um banco de dados de estar sempre disponível para os usuários, evitando tempo de inatividade?

- A) Confiabilidade
- B) Escalabilidade
- C) Disponibilidade
- D) Integridade
- E) Flexibilidade

### 2. No contexto de um banco de dados relacional, o que é uma chave estrangeira?

- A) Um identificador exclusivo para cada registro em uma tabela.
- B) Uma técnica para melhorar o desempenho de consultas.
- C) Um campo utilizado para estabelecer um relacionamento entre tabelas.
- D) Uma estrutura de dados para armazenar informações hierárquicas.
- E) Uma função que garante a integridade dos dados.

### 3. Considere as afirmações a seguir e identifique quais são Verdadeiras (V) ou Falsas (F):

- I) Um SGBD NoSQL é ideal para ambientes que requerem alta escalabilidade e flexibilidade no esquema de dados.
- II) A segurança de um banco de dados é responsável por proteger os dados contra acessos não autorizados e manipulação inadequada.
- III) O modelo de SGBD hierárquico é conhecido por permitir múltiplos relacionamentos complexos entre registros de diferentes níveis.

- A) V, F, V
- B) F, V, F
- C) V, V, F
- D) F, F, V
- E) V, F, F

### 4. Em um contexto de banco de dados, o que caracteriza a disponibilidade e como ela pode ser garantida em um sistema de gerenciamento de banco de dados que precisa estar sempre acessível para operações comerciais em tempo real?

- A) A capacidade de proteger os dados contra acesso não autorizado através de medidas de segurança robustas.
- B) A garantia de que os dados armazenados são precisos e consistentes através da integridade dos dados.
- C) A capacidade do sistema de estar sempre acessível aos usuários, minimizando o tempo de inatividade e garantindo operações comerciais ininterruptas.
- D) A flexibilidade do sistema para adaptar-se a novos requisitos de negócios sem grandes reestruturações.
- E) A capacidade do sistema de lidar com grandes volumes de dados e consultas complexas de forma eficiente.

### 5. Considere o seguinte padrão de consulta SQL que busca por registros específicos em uma tabela de clientes. Com base no padrão abaixo, qual alternativa contém a consulta correta que seleciona todos os clientes cuja idade seja maior que 30 anos e residam na cidade de São Paulo?

- A) SELECT * FROM clientes WHERE idade > 30 AND cidade = 'São Paulo';
- B) SELECT * FROM clientes WHERE cidade = 'São Paulo' AND idade > 30;
- C) SELECT FROM clientes WHERE idade > 30, cidade = 'São Paulo';
- D) SELECT * FROM clientes WHERE idade > 30 OR cidade = 'São Paulo';
- E) SELECT * FROM clientes WHERE idade >= 30 AND cidade = 'São Paulo';

## Questões de Modelagem de Dados e BD Relacional

### 6. Preencha a lacuna: No processo de modelagem de dados, o _______________ é responsável por definir a estrutura abstrata das entidades e relacionamentos, sem considerar aspectos de implementação, enquanto o ___________ detalha essa estrutura, especificando tabelas e colunas em um nível técnico.

- A) Modelo Conceitual / Modelo Físico
- B) Modelo Conceitual / Modelo Lógico
- C) Modelo Lógico / Modelo Conceitual
- D) Modelo Físico / Modelo Lógico
- E) Modelo Físico / Modelo Conceitual

### 7. No modelo de três esquemas (ANSI/SPARC), qual é a função do esquema externo?

- A) Descrever a estrutura física dos dados.
- B) Definir a organização lógica dos dados.
- C) Implementar as restrições de integridade.
- D) Estabelecer as políticas de segurança do banco de dados.
- E) Representar a visão do usuário ou aplicação sobre os dados.

### 8. Em um modelo Entidade-Relacionamento (ER), qual dos seguintes atributos é tipicamente considerado derivado?

- A) Data de nascimento.
- B) Endereço.
- C) Número de telefone.
- D) Idade.
- E) Nome completo.

### 9. Preencha a lacuna: Durante o processo de migração de dados de um sistema antigo para um novo banco de dados, a utilização de _____________ é essencial para garantir que os dados sejam corretamente extraídos, transformados e carregados, mantendo a integridade e a consistência dos dados.

- A) Ferramentas de ETL
- B) Modelos ER
- C) Índices
- D) Chaves Primárias
- E) Partições

### 10. Qual é a principal vantagem de utilizar um SGBD (Sistema de Gerenciamento de Banco de Dados) em vez de sistemas de arquivos tradicionais?

- A) Melhor desempenho em consultas simples.
- B) Maior facilidade de backup e recuperação.
- C) Controle centralizado de integridade e segurança dos dados.
- D) Menor necessidade de armazenamento físico.
- E) Melhor suporte a dados não estruturados.

---

## Gabaritos e Comentários

### Questões de Bancos de Dados e SGBD

1. C - Disponibilidade é a capacidade de um banco de dados estar sempre acessível aos usuários, minimizando o tempo de inatividade.
2. C - A chave estrangeira é um campo em uma tabela que cria um vínculo entre dois registros de diferentes tabelas.
3. C - SGBDs NoSQL são escaláveis e flexíveis, e a segurança de banco de dados protege contra acesso não autorizado. O modelo hierárquico não permite múltiplos relacionamentos complexos entre níveis.
4. C - Disponibilidade refere-se à capacidade do sistema de estar sempre acessível aos usuários, minimizando o tempo de inatividade.
5. A - A consulta correta é: `SELECT * FROM clientes WHERE idade > 30 AND cidade = 'São Paulo';`

### Questões de Modelagem de Dados e BD Relacional

6. B - O Modelo Conceitual mapeia as entidades e relacionamentos, enquanto o Modelo Lógico especifica tabelas e colunas.
7. E - O esquema externo representa a visão do usuário ou da aplicação sobre os dados.
8. D - A idade é um atributo derivado, pois pode ser calculada a partir da data de nascimento.
9. A - Ferramentas de ETL (Extract, Transform, Load) são utilizadas para garantir que os dados sejam migrados corretamente.
10. C - A principal vantagem de um SGBD é o controle centralizado de integridade e segurança dos dados, além de outras funcionalidades avançadas.

---

## Gabaritos Finais

- 1. C
- 2. C
- 3. C
- 4. C
- 5. A
- 6. B
- 7. E
- 8. D
- 9. A
- 10. C
