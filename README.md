# Trilha Dev - Pixel - 23.1 
## Exercício 1 
### Introdução
No primeiro exercício você irá praticar o uso do git com o flow básico.
Para isso, você irá baixar este repositório para sua máquina local, criar um arquivo nome_sobrenome.txt, escrever o nome de sua comida favorita dentro dele e enviar seu arquivo para atualizar este repositório.

### Flow básico
1. Para baixar o repositório você deve criar um *clone*
   - `git clone https://github.com/pixel-ufsc/trilha-dev-ex1-23.1.git`
   - ou
   - `git clone git@github.com:pixel-ufsc/trilha-dev-ex1-23.1`
   - ou
   - Baixar zip e descompactar
1. Vá para a pasta /trilha-dev-ex1-23.1
   - `cd trilha-dev-ex1-23.1`
1. Crie uma branch seguindo o seguinte padrão para nome: new/nome-sobrenome (Extra: Por que não é recomendado mexer na branch main diretamente quando há mais de um colaborador em um repositório?)
   - `git branch new/matheus-antonio`
1. Altere da branch main para a sua nova branch criada
   - `git checkout new/matheus-antonio`
1. Crie um arquivo nome_sobrenome.txt e coloque sua comida favorita lá
   - vide arquivo matheus_antonio.txt
1. Adicione o arquivo criado ao índice
   - `git add matheus_antonio.txt`
1. Faça um commit de sua alteração, adicionando uma mensagem
   - `git commit -m "Add comida favorita de Matheus Antonio"`
1. Publique a branch e envie sua adição para o repositório remoto
   - `git push -u origin new/matheus-antonio`
1. Faça uma solitação de merge na main (*pull request*) pelo site do Github para que um instrutor revise e faça o merge :)
