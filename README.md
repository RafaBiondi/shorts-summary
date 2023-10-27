# O que foi aprendido (aula 1)
- Dependencias;
- NPM e vite ´vite@latest´;
- Duplicar projeto no Figma;
- Localhost ´package.json´, ´script -> web´;
- Configuração mais útil no VSCODE, através da criação da pasta ´.vscode´ com os arquivos ´extensions.json´ e ´settings.json´;
- npm i, para instalação dos módulos do node;
- Criação da pasta styles;
- ´import ""´ no arquivo ´main.js´;
- ´npm run web´, criação e definição do script para rodar o projeto;
- npm é o gerenciador de pacotes do node;

O backend processa as requisições do frontend e então, retorna para o front. 
- - Essas requisições seguem um padrão, através do protocolo http;
- - O Node permite que o Javascript seja executado no lado do servidor sem necessariamente estar dentro do navegador;
- - Com o Node, podemos descentralizar a lógica da nossa aplicação;
- - O frontend fica responsável de pegar a solicitação do usuário e retornar a resposta;
- - Nós indicamos para o backend o a ação que ele irá executar, através dos métodos http;

# O que foi aprendido (aula 2)
- Aprendi a atualizar o node pelo nvm;
- ´nvm ls´, ´nvm ls-remote´, ´nvm instal ##.#.#´;
- Aprendi a criar um servidor pelo node e, pegar parâmetros, dentro da pasta server, no index.js;
- Aprendi a criar o backend e entendi sobre a sepração das responsabilidades;
- O servidor fica com todo o trabalho "duro";
- Aprendi a iniciar o servidor, definindo o endereço da porta;
- Aprendi a utilizar o método GET;
- Aprendi a definir o recurso, o endereço da rota para o backend, utilizar parâmetros para receber o ID do vídeo;
- Criei uma função download, para separar a responsabilidade e fazer o download em um arquivo separado;
- Aprendi a pegar o ID do vídeo, formatar a URL;
- Defini parâmetros da qualidade do vídeo que eu quero;
- Peguei informações do vídeo e validei se ele é maior que 60 segundos ou não;
- - Se for maior, erro, caso não, ele passa para as outras etapas;
- Verifiquei quando o download termina, e exibo uma mensagem no terminal, de download concluído;
- E tratei caso ocorra algum erro nesse processo, para exibir uma mensagem;
- E por fim, no pipe, eu defini onde iria salvar o arquivo;

# O que foi aprendido (aula 3)
- No ´form.js´, foi criada a função que observa o evento no formulário;
- No ´index.js´, ele recupera o ID que é passado como parâmetro, faz download, converte o vídeo e por fim, faz a transcrição, seguindo os parâmetros por mim, fornecidos;