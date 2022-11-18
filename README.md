# Praticas-Pre-AC3

Exercício
1) A professora Alice precisa de um programa que auxilie na análise de performance de sua turma. 

Parte-1

Tenha uma tela parecida com a abaixo
![download](https://user-images.githubusercontent.com/111443602/202790682-6237be4b-326b-48be-8018-8264cba3db43.png)


Interface gráfica do usuário, Aplicativo

Descrição gerada automaticamente

 

Quando o botão “Registrar” for clicado:

    validar os campos de entrada sendo que o “nome” tem que estar preenchido e a “nota” tem que estar entre 0 e 10, em caso de erro emitir mensagem explicativa e não seguir em frente.

    guardar os dados (por exemplo em vetor);

    listar abaixo dos botões todas as informações guardadas, só que em ordem inversa a que foi cadastrada.


Quando o botão “Analisar” for clicado, limpar todos os elementos da Parte-1 e executar a Parte-2.

 

Parte-2

Tenha uma tela parecida com a abaixo

![download](https://user-images.githubusercontent.com/111443602/202790817-7e65dc18-1ee4-4fe4-be16-85a53675df40.png)

Interface gráfica do usuário

Descrição gerada automaticamente

Quando o botão “Pesquisar” for clicado:

    validar o intervalo de pesquisa, sendo que o campo “de” tem que estar entre 0 e 10, o campo “até” tem que estar entre 0 e 10 e o campo “de” tem que ser menor ou igual ao campo “até”. Em caso de erro emitir mensagem explicativa e não seguir em frente.

    listar todos os alunos com nota entre o intervalo informado da seguinte forma: “O aluno xxxxxxx ficou com a nota 99,9”

    abaixo da relação de alunos emitir o resumo da seguinte forma:

Total de alunos registrados: 999

Total de alunos listado: 999 (com nota no intervalo informado)

Maior Nota = 99,9

Menor Nota = 99,9

Média da Nota = 99,9




Parte-3

UTILIZE JSON PARA CADASTRAR OS ALUNOS NESSA PARTE 3.

Adicione uma lista suspensa (select) para aplicar filtros, com as opções "Nome", "Nota maior que", "Nota menor que".

Adicione uma input para o usuário inserir o valor desejado para ser filtrado.

Ao clicar em "Aplicar Filtros", deve realizar uma busca com base no filtro aplicado, listando somente os elementos que sejam compatíveis com o filtro.

Caso o usuário tenha informado um intervalo de notas (parte 2), os filtros devem ser aplicados com base nesse intervalo.

Ao final, deve continuar exibindo a relação de alunos, como: 



Exemplo de Funcionamento: 



Opção "Nota maior que" selecionado na combo, 

Valor "6" inserido na input

Deve listar todas as notas que sejam 6 ou maior.



Total de alunos registrados: 999

Total de alunos listado: 999 (com nota no intervalo informado)

Maior Nota = 99,9

Menor Nota = 99,9

Média da Nota = 99,9
