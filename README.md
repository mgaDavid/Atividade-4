# Desenvolvimento Web

## Atividade 4 - Front End API

Comentários sobre o funcionamento da API:

- Não se esqueça de fazer o npm i antes de correr o programa :)

- Para aceder ao front-end: http://localhost:8000

- Após o registo de um novo utilizador, deverá ir ao terminal do seu IDE e fazer ctrl+click no URL com o formato:  https://ethereal.email/message/... e ativar a conta criada.

- Existe uma conta teste já criada:

  - email: test123@email.test
  - password: 1234

- Se fizer refresh á pagina web após ter feito login, a token não irá ser destruída, isto significa que a página vai ter um comportamento diferente do esperado.
  Terá de fazer login outravez e de seguida logout para repor o estado inicial da página.
  
- É possivel que ao clicar no botão News ou Search após fazer login, o conteúdo não seja visível. Ao clicar outravez em um dos botões o conteúdo irá aparecer.
  Pode ser algo a ver com o axios ou cheerio.
