# Teste

Isso é um teste para clonar o repositorio pelo git



Para clonar um repositorio na sua maquina você deve usar no bash do git que esta instalado na maquina: 
  git clone <!--link do repositorio que deseja ser clonado na maquina-->
  
Depois disso o próprio bash vai fazer a busca do repositório no site do git com o link que foi passado


Caso você queira que o arquivo/repositorio seja clonado para uma pasta de nome diferente da do nome do repositório podemos colocar na mesma estrutura de antes mas colocar um espaço depois do link e adicionar o nome desejado para a pasta
  git clone <!--link do repositorio que deseja ser clonado na maquina--> "Nome da pasta desejada"
  
ATENÇÃO:

Comandos do git:

  git init - inicia uma pasta como uma pasta de repositório, ou seja uma pasta que pode ser subida para o github
  git add <!--Nome do arquivo--> - Sobe para um armazenamento temporario o arquivo selecionado
  git add --all - Adiciona TODOS os arquivos dentro da pasta para um armazenamento temporário
  git commit -m "Mensagem que fala um pouco sobre a mudança feita" - Serve para confirmar as mudanças feitas e salvar essas mudanças
  git remote add origin <!--Link do repositório de destino--> - Faz com que o repositório tenha sido setado como destindo do upload dos arquivos
  git config <!-- --global --> user.email "seu email do git" - Esse comando permite que o git coloque seu repositório no github pelo email registrado, vale adicionar também que esse --global serve para cadastrar seu emal como global, sem ele você tem que fazer esse comando para toda a vez que tiver um repositório que deseje ser passado para o git.
  git config <!-- --global --> user.name "Seu nome" - Serve para cadastrar o nome da pessoa que esta fazendo a alteração
  git push origin <!--master--> - neste comando estamos mandando os arquivos para o git no origin que já tinha sido predefinido, e estamos mandando o arquivo "master", ou seja a pasta que esta definida como master
  **Caso as versões que estão no git e na sua maquina não sejam a mesma ele dará um erro, para corrigir isso deve-se fazer um git pull primeiro e ele fará um merge, mas caso esse merge não funcione temos que ir manualmente no trecho que ele salientar e corrigir o que deve ficar e o que não deve;
  git pull origin master - Neste caso o comando pega o que esta no github e coloca na maquina
