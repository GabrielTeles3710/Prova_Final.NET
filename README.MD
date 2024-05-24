# RELATÓRIO DE ANÁLISE DE DESENVOLVIMENTO

## PROJETO E-COMMERCE - AVALIAÇÃO AP004

**TIME 3**

**DATA 24/05/2024**

---

## EQUIPE E PAPÉIS

- **Gabriel dos Santos Teles** - Líder Técnico
- **Alan Prates dos Santos** - Desenvolvedor
- **Daniel Andrade Penedo Santos** - Desenvolvedor
- **Giuseppe Mota Araújo** - Desenvolvedor
- **Luann Firme Bomfim** - Desenvolvedor

---

## SUGESTÃO DE ALTERAÇÕES EM MÓDULOS

- Melhorias de performance
- Melhorias de segurança
- Melhorias de escalabilidade

---

## JUSTIFICATIVA DE ALTERAÇÕES EM MÓDULOS

### 1. Quanto à performance:
- A utilização de caching reduz a carga do servidor e melhora o tempo de resposta. Implementar cache para armazenar dados frequentemente acessados pode reduzir significativamente a quantidade de requisições ao banco de dados.
- O uso do Refit melhora o consumo de APIs, facilitando a comunicação com serviços externos e tornando o código mais limpo e fácil de manter. O Refit permite a criação de clientes de API de forma declarativa, reduzindo a quantidade de código boilerplate e aumentando a eficiência.

### 2. Quanto à segurança:
- Implementação de autenticação OAuth para garantir que apenas usuários autorizados possam acessar recursos sensíveis.
- Criptografia de dados sensíveis para proteger informações confidenciais.
- Adoção de práticas de desenvolvimento seguro para prevenir vulnerabilidades comuns.

### 3. Quanto à escalabilidade:
- O uso de Arquitetura de Microserviços permite que a aplicação evolua de forma mais efetiva, possibilitando a escalabilidade independente de componentes do sistema. Isso facilita a adição de novas funcionalidades e a adaptação às demandas crescentes sem impactar negativamente outras partes do sistema.
- Adição de processos de Failover para recuperação automática de falhas, incluindo balanceamento de carga, uso de Kubernetes ou Docker Swarm para gerenciamento de ciclo de vida da aplicação, e políticas de interrupção de circuito e tentativas/tempo limite.
- Implementar a Arquitetura de Camadas evita acoplamento e facilita a criação de testes unitários eficientes, visando uma melhor manutenção do código. Isso também permite mais liberdade no desenvolvimento do Front-end, possibilitando o uso de diversas linguagens para múltiplas plataformas (ex.: mobile, web, etc.).
- Implementação de HTML via framework para obter uma identidade visual mais agradável e de fácil modificação.

---

## RELATÓRIO DE ATIVIDADES

| TAREFA                      | RESPONSÁVEL                        | TEMPO PREVISTO | TEMPO EXECUTADO |
|-----------------------------|------------------------------------|----------------|-----------------|
| Atualizar Pacotes           | Alan Prates, Gabriel Teles         | 8 horas        | 8 horas         |
| Separar Camadas             | Daniel Penedo, Giuseppe Mota       | 12 horas       | 12 horas        |
| Refatorar Entidades         | Alan Prates, Luann Firme           | 10 horas       | 10 horas        |
| Refatorar Controllers       | Giuseppe Mota, Luann Firme         | 14 horas       | 14 horas        |
| Adicionar Testes Unitários  | Gabriel Teles                      | 8 horas        | 8 horas         |
| Adicionar Front (Angular 17)| Luann Firme, Gabriel Teles         | 8 horas        | 8 horas         |




