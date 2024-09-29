# trabalho-ifpe

Sistema Acadêmico em Python

Este é um sistema acadêmico simples implementado em Python, que permite a gestão de alunos e suas respectivas notas e frequências. O sistema também fornece relatórios com a situação de aprovação ou reprovação dos alunos.

## Funcionalidades

- **Adicionar Alunos**: Permite a inserção de novos alunos com o nome.
- **Editar Alunos**: Permite a edição do nome de alunos já cadastrados.
- **Remover Alunos**: Remove um aluno existente do sistema.
- **Adicionar Notas**: Adiciona até 4 notas para um aluno existente.
- **Adicionar Frequência**: Adiciona a frequência (número de aulas assistidas) de um aluno.
- **Relatório Geral**: Gera um relatório com a lista de todos os alunos, suas notas, frequência e a situação (Aprovado, Reprovado por Falta ou Reprovado por Nota).
- **Relatório Filtrado**: Gera um relatório filtrado com base na situação específica do aluno (Aprovado, Reprovado por Falta ou Reprovado por Nota).

## Cálculo de Situação do Aluno

- **Aprovado**: O aluno é aprovado se tiver **75% ou mais de frequência** e uma **média das notas maior ou igual a 7**.
- **Reprovado por Falta**: O aluno é reprovado por falta se tiver **menos de 75% de presença**.
- **Reprovado por Nota**: O aluno é reprovado por nota se a **média das notas for inferior a 7**, desde que não tenha sido reprovado por falta.
