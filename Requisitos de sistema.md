## Requisitos Funcionais (RF)

| ID   | Requisito                                                                                      |
|------|-----------------------------------------------------------------------------------------------|
| RF01 | O sistema deve calcular a dosagem com base no peso, altura e idade do paciente.               |
| RF02 | O sistema deve identificar automaticamente se o paciente é uma criança com base na idade.     |
| RF03 | O sistema deve aplicar uma barra de corte no cálculo da dosagem para crianças acima do peso.  |
| RF04 | O sistema deve validar as entradas de peso, altura e idade para garantir valores plausíveis.   |
| RF05 | O sistema deve alertar o usuário caso a dosagem calculada ultrapasse limites seguros.          |
| RF06 | O sistema deve permitir salvar e consultar o histórico de dosagens calculadas para um paciente.|
| RF07 | O sistema deve gerar um relatório detalhado com a dosagem recomendada e os critérios utilizados.|

---

## Requisitos Não Funcionais (RNF)

| ID   | Requisito                                                                                      |
|------|-----------------------------------------------------------------------------------------------|
| RNF01 | O cálculo de dosagem deve ser realizado em menos de 2 segundos.                              |
| RNF02 | As fórmulas e barras de corte devem ser baseadas em estudos científicos confiáveis.           |
| RNF03 | A interface deve ser intuitiva, com acesso rápido às principais funcionalidades.              |
| RNF04 | O sistema deve garantir que as informações de dosagem sigam as normas de segurança médica reconhecidas e estejam baseadas em guidelines atualizadas e publicações confiáveis. |
| RNF05 | O sistema deve atender a múltiplos usuários simultaneamente sem comprometer o desempenho.     |
| RNF06 | O sistema deve ser acessível via dispositivos móveis e computadores.                          |
| RNF07 | O sistema deve registrar logs das alterações realizadas nos cálculos ou nas configurações.    |
| RNF08 | O sistema deve ser auditável, permitindo que as fontes (guidelines, estudos, bulas) de cada cálculo possam ser verificadas em caso de necessidade.    |
