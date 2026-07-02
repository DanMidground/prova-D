1- Quais comandos você utilizaria para garantir que está no branch
correto antes de começar a codificação?

Resposta: eu comecei usando "git branch feature-ia-inimigo" para criar a branch pedida no enunciado. Após isso usei " git checkout feature-ia-inimigo" para alternar para essa branch.

----------------------~--------------------

2- RESUMO--> Nesta questão eu usei o "git log" para garantir que a HEAD estava na branch certa, após isso eu usei o "git status" para olhar o que não havia sido incluído,depois eu fiz um "git add ." e escrevi uma mensagem usando "git commit" e escrevendo as alterações dentro do commit de forma clara....

-----------------------~--------------------

3- Questão 03: Com o commit já realizado, você precisa garantir que a alteração
foi registrada corretamente no histórico do projeto. Qual comando você
utilizaria para listar os commits realizados no branch atual, permitindo visualizar
o autor, a data e a mensagem da alteração que você acabou de fazer?

Resposta: Git log.

-----------------------~--------------------

4- Você terminou o desenvolvimento da IA no branch
feature-ia-inimigo. Agora, você deve voltar ao branch main e realizar o merge
das suas alterações. Caso ocorra um conflito ao tentar realizar esse merge,
quais comandos você utilizaria para identificar o arquivo conflitante e finalizar o
processo de merge após a correção?

Resposta: Eu usaria "git status" para ver quem seria o arquivo conflitante.

-----------------------~--------------------

5- Refatore o código abaixo (que representa uma extensão da IA, o
arquivo InimigoIA.cs) adicionando um método para verificar a saúde do inimigo.
Após a modificação, adicione o arquivo ao stage e faça um commit com a
mensagem "Refatoração: Adicionado método de verificação de saúde". Quais
comandos específicos você usaria para cada etapa desse processo?

Resposta: usei "git add ." para atualizar as modificações, "git status" para verificar e "git commit" com a mensagem pedida no enunciado.

-----------------------~--------------------

Questão 06: Você realizou uma alteração no arquivo InimigoIA.cs mas
percebeu que cometeu um erro e deseja descartar essas alterações locais
antes de realizar o commit (reverter o arquivo para o estado do último commit).
Qual comando do Git você utilizaria para descartar as modificações locais
especificamente neste arquivo?

Resposta: Letra A, git revert InimigoIA.cs.

-----------------------~--------------------

Questão 07: Após finalizar a implementação da IA do inimigo, você precisa
marcar esse ponto no histórico do projeto como uma versão estável chamada
"v1.0". Quais comandos Git você usaria para criar uma tag leve (lightweight) e uma tag anotada para essa versão?

Resposta: usando o comando "git tag" e usar "git log" para verificar se estaria tudo certo.

-----------------------~--------------------

Questão 08: Você terminou seu código localmente e agora precisa conectá-lo
a um repositório no GitHub. Qual comando você utiliza para adicionar um
servidor remoto chamado 'origin' apontando para a URL do seu repositório no GitHub?

Resposta: Usamos o "git remote add origin (link do SSH)..."

-----------------------~--------------------

Questão 09: Após conectar seu repositório local ao remoto, você precisa
enviar a branch 'feature-ia-inimigo' para o GitHub. Qual comando você utiliza
para realizar o push dessa branch e, ao mesmo tempo, configurar o
rastreamento ('upstream') para essa branch no repositório remoto?

Resposta: você vai usar "git push (link do SSH)" mas antes vc vai dar um commit.