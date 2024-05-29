# Planejador de Empilhamento de Blocos em Prolog

O planejador de empilhamento de blocos em Prolog implementado aqui utiliza um algoritmo de planejamento com regressão de metas. O objetivo é gerar um plano de ação que permita empilhar os blocos de acordo com um estado inicial e uma série de metas especificadas.

## Funcionamento

O planejador utiliza um algoritmo de planejamento com regressão de metas para gerar o plano de ação. Ele considera os seguintes passos:

1. **Fatos Iniciais:** Define os blocos, lugares, tamanhos dos blocos, estado inicial e metas.

2. **Verificação de Possibilidade de Ação:** Verifica se uma ação é possível, levando em conta as condições necessárias para a ação.

3. **Efeitos de uma Ação:** Define quais relações são adicionadas ou removidas após uma ação.

4. **Regras de Planejamento:** Implementa o planejamento usando regressão de metas.

5. **Execução do Planejador:** Chama a função `solve/1` para obter o plano de ação.

6. **Impressão do Plano de Ação:** Utiliza a função `print_result/1` para imprimir o plano de ação.

# Chamada da Função de Resolução no SWI Prolog:

solve(Plan), print_result(Plan).
