# 1. Requisitos Funcionais

| ID    | Requisito de Usuário                                                                                                                                                     | Critérios de Aceitação                                                                                                                                                | Prioridade | RF Relacionado |
|-------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|-----------------|
| RU01  | O sistema deve permitir ao usuário inserir a **idade**, **peso** e **condição do paciente** (pediátrico ou adulto) para realizar o cálculo da dose do medicamento.       | 1. O sistema deve aceitar as entradas de idade, peso e condição. <br> 2. O sistema deve validar se os dados informados são corretos e dentro das faixas aceitáveis.    | Alta       | RF01            |
| RU02  | O sistema deve calcular automaticamente a **dose do medicamento** com base nas informações fornecidas, como peso e idade do paciente.                                    | 1. O sistema deve exibir a dose calculada assim que os dados forem inseridos. <br> 2. A dose deve ser calculada com base em fórmulas ou diretrizes científicas adequadas. | Alta       | RF02            |
| RU03  | O sistema deve realizar um **ajuste na dosagem** para pacientes **pediátricos obesos**, levando em consideração limites seguros e recomendados para crianças.           | 1. O sistema deve identificar automaticamente quando o paciente é pediátrico e obeso. <br> 2. O ajuste de dose deve ser exibido de forma clara e sem ambiguidade.     | Alta       | RF03            |
| RU04  | O sistema deve exibir as **recomendações de forma de apresentação** do medicamento (comprimido, líquido, etc.), com base nas necessidades do paciente.                  | 1. O sistema deve sugerir a forma de apresentação mais adequada para o paciente. <br> 2. A forma sugerida deve ser destacada na interface.                         | Média      | RF04            |
| RU05  | O sistema deve calcular e exibir os **horários das doses**, a quantidade de frações diárias e a **duração do tratamento** de forma clara e precisa.                    | 1. O sistema deve mostrar os horários e quantidades de doses. <br> 2. O sistema deve informar a duração total do tratamento.                                       | Alta       | RF05            |
| RU06  | O sistema deve permitir ao usuário **alterar manualmente** o esquema posológico sugerido, caso haja necessidade de ajustes específicos para o tratamento.                | 1. O sistema deve permitir alterações no esquema posológico. <br> 2. O sistema deve mostrar a dose alterada antes da confirmação da mudança.                       | Média      | RF06            |
| RU07  | O sistema deve usar **fontes confiáveis e atualizadas** (como bulas, guidelines pediátricas e estudos clínicos) para calcular a dosagem dos medicamentos.                | 1. O sistema deve exibir a fonte utilizada para o cálculo. <br> 2. As fontes de informação devem ser atualizadas periodicamente, conforme as diretrizes mais recentes. | Alta       | RF07            |
| RU08  | O sistema deve armazenar e relembrar as informações inseridas sobre o **paciente** (idade, peso, condição), para que não seja necessário inserir os dados novamente.    | 1. O sistema deve salvar os dados inseridos para uso futuro. <br> 2. O usuário deve poder acessar facilmente os dados armazenados.                                  | Média      | RF08            |
| RU09  | O sistema deve exibir a **fonte de dosagem utilizada** ao calcular a dose, proporcionando transparência e confiabilidade ao usuário.                                     | 1. O sistema deve apresentar a fonte de dosagem utilizada no cálculo. <br> 2. O usuário deve ser capaz de visualizar a fonte diretamente na interface do sistema.    | Alta       | RF09            |
| RU10  | O sistema deve ser capaz de **verificar se os dados inseridos** são válidos, para evitar erros de dosagem devido a entradas incorretas, como peso ou idade errados.      | 1. O sistema deve validar automaticamente os dados inseridos. <br> 2. O sistema deve alertar o usuário se houver dados inválidos ou inconsistentes.                | Alta       | RF10            |


<div style="text-align: center">
<p>Tabela 1: Requisitosde usuários</p>
</div>

# 2. Referências


<a href="../README.md">VOLTAR INÍCIO</a>
