# Atividade Projeto Estruturado [APE]

Acadêmico: Rubens Junior Schwalemberg
RA: 0901030

#### 1. O que é GIT?
O git foi desenvolvido pela quebra de contrato entre a comunidade do Linux e a empresa Bitkeeper. O linux tinha toda o seu código nessa empresa. A ferramenta passou a exigir pagamentos e não trazia todos os recursos necessários para um desenvolvimento não linear. Então Linux Torvalds desenvolveu sua própria ferramenta com melhorias como: velocidade, projeto simples, suporte de desenvolvimento não linear, distribuído e capacidade de lidar com grandes projetos.
O git trata seus dados como um conjunto de imagens. Cada vez que é feito um commit ou salvo o estado ele tira uma foto dos arquivos. Caso o arquivo não seja alterado é feito apenas um link ao arquivo anterior armazenado. Chamamos esse tratamento de fluxo de estados.


### 2.  O que é versionamento de software?
Versionamento são as alterações que são feitas em um arquivo ou vários salvos ao longo do tempo. Permite a recuperação de versões anteriores e alteração de forma segura. O que muitos faziam antigamente eram salvar cópias e mais cópias do arquivo sem saber o que tinha sido alterado. “Controle de versão é um sistema que registra alterações em um arquivo ou conjunto de arquivos ao longo do tempo para que você possa lembrar versões específicas mais tarde”. O git trabalha com sistema distribuído de controle de versão que permite que vários usuários utilizem a versão mais recente do arquivo, salvar o repositório em sua própria máquina e depois subirem para o repositório as alterações.


### 3. Por que utilizar o Git como controle de versionamento?
Os outros sistemas de versionamento de arquivos trabalham armazenando informações com as mudanças nos arquivos. Conjunto de arquivos e suas alterações ao longo do tempo. Salvando apenas as diferenças dos arquivos em cada versão. Não é possível criar branch. Já o git trabalha com um conjunto de imagens do sistema. Uma foto de todos os arquivos armazenando numa versão. Quando um arquivo não é alterado ele salva apenas o link da versão anterior. Esse tipo de tratamento é chamado de fluxo do estado dos arquivos. O estado modificado que é a foto do trabalho que está sendo feito no momento, estado preparado:  pronto para ser salvo no banco de dados e estado consolidado: salvo no repositório.

### 4. Quais as vantagens do Git?

O Git apresenta várias vantagens em relação aos outros softwares de controle de versionamento. Possui integridade que garante que nenhuma alteração em algum conteúdo ou pasta ocorre sem o GIT saber.
Não possuindo riscos dos arquivos serem corrompidos ou perderem alterações. Salva seus arquivos num valor hash hexadecimal com 40 caracteres.
Alterações em arquivos e pastas são salvas através do comando commit assegurando a adição de dados de forma segura. 
"Facilidade de verificar alterações nos arquivos na linha do tempo, pode ser utilizado em trabalhos grandes em equipe, permite revisão, sistema de branching, merging, snapshots e autenticação criptográfica". Android, Kernel do Linux, php utilizam o git como exemplos.

### 5. Qual a importância da utilização do controle de versionamento no desenvolvimento de um software?

É de extrema importância. Você saber todo o histórico de modificações, o que foi alterado, poder baixar versões anteriores, trabalhar em equipe em tempo real salvando o arquivo na máquina e depois subir as alterações para o git, verificar o que foi modificado e quem modificou. "Assim, se qualquer servidor morrer, e esses sistemas estiverem colaborando por meio dele, qualquer um dos repositórios de clientes podem ser copiado de volta para o servidor para restaurá-lo. Cada clone é de fato um backup completo de todos os dados".
"Além disso, muitos desses sistemas trabalham muito bem com vários repositórios remotos, tal que você possa colaborar em diferentes grupos de pessoas de maneiras diferentes ao mesmo tempo dentro do mesmo projeto. Isso permite que você configure vários tipos de fluxos de trabalho que não são possíveis em sistemas centralizados, como modelos hierárquicos".

### 6. Cite pelo menos três ferramentas de controle de versão e faça um breve detalhamento sobre cada uma delas.


~

