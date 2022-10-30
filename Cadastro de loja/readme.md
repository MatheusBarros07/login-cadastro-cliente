<h1> TELA DE LOGIN DO PROJETO CADASTRO DE CLIENTES.</h1>
<h2> Desafio: Criar uma interface de login que seja agradável aos olhos e que chame a atenção do cliente por meio de algumas animações feitas em CSS.</h2>

<p>Transformar o HTML puro em algo bem estilizado e profissional. podemos ver ver na imagem anterior como a pagina seria apenas com HTML, nada intuitivo e muito simples e digamos... feio.</p>
<h2>HTML:</h2>
<img src="HTML puro.png"> <br>
<p>percebemos que não tem dinamismo nenhum. está tudo muito "crú".</p>
<h2>Resultado pós CSS:</h2>
<img src="tela css1.png">
<h3>Ao clicar na caixa de texto "Usuário" ou "Senha", o alinhamento muda e as bordas ficam mais claras</h3>
<img src="tela css2.png">
<h3>Ao passar o mouse em cima do botão "Entrar" ele fica maior e diminui as caixas de texto, tornando a tela mais dinamica e não só, ele fica mais claro:</h3>
<img src="tela css3.png">
<h3>Para isso criei um formulário com três input, 1 do tipo "text" para o usuário, outro do tipo "password" para senha e outro tipo "submit" para botão de Entrar.</h3>
<img src="codigo html.png">
<p>Usando uma imagem da logo da empresa hipotetica que criei, coloquei o fivecon e logo depois começamos a estilizar. criamos um outro arquivo do tipo .css para iniciarmos a estilização e ligamos ele ao arquivo .html por meio da tag  "link rel="stylesheet" href="login_cliente.css"" e começamos a fazer as ligações.</p>
<img src="codigo css1.png">
<img src="codigo css2.png">
<h2>Estilização:</h2>
<p>Primeiro passo na estilização foi mudar a cor de fundo para uma mais escura e proximo ao preto, usei o atributo "background-color". depois alinhar e deixar ao centro. Por ultimo deixar a div "area_login" com cor mais escura ainda e com as bordas arredondadas.</p>
<p>Depois disso mudamos a estilização das fontes da pagina para a familia ARIAL, para isso usei a tag "font-family". depois arrendodei as bordas dos input com o atributo "border-radius: 20px" e mudei a cor das fontes deles e do fundo tambem. Deixei eles um pouco maiores para melhor harmonia e adicionei os atributos placeholder="Usuário" e placeholder="Senhas" para não usar label e ficar mais profissional. Usei tambem "autofocus" no input "Usuário" para assim que a tela é aberta o cursor para digitar já estiver piscando dentro do input e começar a digitar o usuário.</p>
<p>Para criar a animação no botão "Entrar" usei o ":hover" assim, ao passar o mouse por cima dele, ele muda o tamanho e a cor. Para criar uma animação nas caixas de texto, como a mudança de alinhamento e as bordas mais claras, usei o ":focus" </p>
<p>Por fim, estilizar o paragrafo com a pergunta se não tem cadastro e o link para iniciar o cadastro.
No link foi tirado o sublinhado e mudado a cor para ficar em harmonia com as outras cores.
Usei color: #5568FE: text-decoration: none;margin-left: 6px;  margin-right: 6px;</p>
<p>Projeto ainda inacabado. Falta concluir a area de cadastro..</p>
