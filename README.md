# Hello-World-autentica
Aprendendo sobre autenticação via Token

1 - Novo repositório
2 - Marcar como privado
3 - ADD readme
4 - Simular tentativa de clonagem deste repositorio sem autenticação
5 - Clicar em Código >> e copiar a url da opção HTTPS
6 - No Git Bash >> entrar com git clone e colar a url
7 - O git pede o nome e senha de usuário
8 - O git deveria retorna um erro informando que o suporte para essa forma de auteticação foi removida desde 2021, mas para mim isso não ocorreu!!
9 - Em tese para realizar essa altenticação seria necessária criar um token aqui no github
10 - para criar o toke >> Clicar no perfil do (rosto do usuário localizado no canto superior direito)
11 - Em Configuração, clicar em configaração do desenvolvedor depois em Tokens(Classicos)
12 - Clicar me Gerar novo token depois em gerar novo token (classico)
13 - Será solicitada a senha do guihub
14 - Preencher o campo de descrição
15 - Definir tempo de validade do token e escopo
16 - Ao final das possibilidades de escopo clicar em Gerar Token
17 - Copiar o código de acesso gerado (Depois que sair da pagina perde-se o acesso ao código gerado)
18 - No git bash >> tentar clonar novamente o repositório
19 - Seria solicitado o nome do usuário >> entar com o nome do usuário
20 - Quando o git pedir a senha >> entrar con o tokem gerado e copiado do github 
21 - Feito isso o repositório será clonado
22 - É possíel salvar estas credenciais no computador
23 - Existem duas opsões >> salvamento temporário ou permanete
24 - Temporário >> git config --global credential.helper cach
25 - Permanente >> git config --global credential.helper store
26 - Excluir o repositorio clonado 
27 - Fazer um novo clone >> as credencias serão solicitadas >> o repositóro será colnado e as credencias serão salvas
28 - Para visualisar todos os tokes criados >> seguir o caminho para a criação do tokem
29 - é possível excluir os tokens gerados
