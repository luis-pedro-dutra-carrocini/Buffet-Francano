# Site Buffet Francano

Site desenvolvido na linguagem HTML e CSS, com o objetivo de cumprir a segunda atividade na disciplina de Desenvolvimento WEB I, no curso de Desenvolvimento de Software Multiplataforma, passando a utilizar CSS, apresentando uma interface aprimorada e responsiva, com imagens, barra de navegação fixa, rodapé, e formulário.

## 📄 Descrição

Para obter uma cópia basta baixar os arquivos INDEX.HTML e STYLE.CSS, com a pasta IMG, executando o arquivo em um navagador (Chrome, Edge, FireFox, etc.).


## 🚀 [Link do Site](https://meusitetestefatec.000webhostapp.com/atv_dwi/Buffet_Francano/index.html)


## 📦 Aparência

<img src="/prints/print1.png">
<img src="/prints/print2.png">
<img src="/prints/print3.png">
<img src="/prints/print4.png">


## ⚙️ Código Fonte

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buffet Francano</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Cabeçalho do site-->
    <div class="w3-top">
        <div class=" w3-bar w3-white w3-padding w3-card" style="letter-spacing: 4px;">
            <a href="#home" class="w3-bar-item w3-button">Buffet Francano</a>
            <div class="w3-right w3-hide-small">
                <a href="#about" class="w3-bar-item w3-button">Sobre</a>
                <a href="#menu" class="w3-bar-item w3-button">Menu</a>
                <a href="#contact" class="w3-bar-item w3-button">Contato</a>
            </div>
        </div>
    </div>

    <!-- Imagens e nome do site-->
    <header class="w3-display-container w3-content w3-wide" style="max-width: 1600px; min-width: 500px;" id="home">
        <img src="img/imgprato3.jpg" alt="Hanburger Francano" class="w3-image" width="1600" height="500">
        <div class="w3-display-bottomleft w3-padding-lange w3-opacity">
            <h1 class="w3-xxlarge">Buffet Francano</h1>
        </div>
    </header>

    <!-- Conteudo da página-->
    <div class="w3-content" style="max-width: 1100px;">

        <!-- Sessão sobre-->
        <div class="w3-row w3-padding-64" id="about">
            <div class="w3-col m6 w3-padding-large w3-hide-small">
                <img src="img/imgprato1.jpg" alt="Uma mesa com pratos de comida vista de cima" class="w3-round w3-image w3-opacity-min" width="600" height="750">
            </div>

            <div class="w3-col m6 w3-padding-large">
                <h1 class="w3-center">Sobre o Buffet</h1>
                <h5 class="w3-center">Tradição desde 19998</h5>
                <p class="w3-large" style="text-align: justify;">O Buffet foi fundado por <span class="w3-tag w3-light-grey">Done Palmirinha</span> em 1998. Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original. Fue popularizado en los 60s con la creación de las hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más recientemente con software de autoedición, como por ejemplo Aldus PageMaker, el cual incluye versiones de Lorem Ipsum. Apenas usamos ingrsientes <span class="w3-tag w3-light-grey">frescos</span></p>

                <p class="w3-large" style="text-align: justify;">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. </p>
            </div>
        </div>

        <br>

        <!-- Sessão de Menu-->
        <div class="w3-row w3-padding-64" id="menu">
            <div class="w3-col m6 w3-padding-large">
                <h2 class="w3-center">Nosso Menu</h2><br>
                <h4 class="w3-tag w3-light-grey">Cesta de Pães</h4>
                <p class="w3-text-grey">Variedade de pães de frutas frescas e muffins | $5.50</p><br>

                <h4 class="w3-tag w3-light-grey">Granola com Mel e Amêndoa com Frutas</h4>
                <p class="w3-text-grey">Cereais naturais de aveia torrada com mel, passas, amêndoas e tâmaras | $7.00</p><br>

                <h4 class="w3-tag w3-light-grey">Waffle Belga</h4>
                <p class="w3-text-grey">Waffle sabor baunilha com farinha de malte | $7.50</p><br>

                <h4 class="w3-tag w3-light-grey">Ovos Mexidos</h4>
                <p class="w3-text-grey">Ovos mexidos com pimenta vermelha e alho assado, com cebolinha | $7.50</p><br>

                <h4 class="w3-tag w3-light-grey">Panquecas de Mirtilhos</h4>
                <p class="w3-text-grey">Com calda, manteiga e muitos frutos silvestres | $7.50</p><br>
            </div>

            <div class="w3-col m6 w3-padding-large">
                <img src="img/imgprato2.jpg" alt="Menu" class="w3-round w3-image w3-opacity-min">
            </div>
        </div>

        <!-- Sessão de Contato-->
        <div class="w3-row w3-padding-64" id="contact">
            <h1>Cantato</h1>
            <p>Oferecemos serviço completo de buffet para qualquer evento, grande ou pequeno. Entendemos sua necessidade e iremos atender a comida para satisfazer os maiores critérios de todos, tanto de aprência quanto de sabor. Não hesite em nos contactar.</p>

            <p class="w3-text-blue-grey w3-large"><b>Endereço: Av. wilson sábio de Mello, 1242 - São Joaquim, Franca - SP</b></p>

            <p>Você também pode nos contratar pelo telefone <b>00553123-2323</b> ou e-mail <b>buffet@francano.com.br</b>, ou pode nos enviar uma mensagem aqui:</p>

            <form action="" torget="_blank">
                <p>
                    <input type="text" class="w3-input w3-padding-16" placeholder="Seu nome" required name="nome">
                </p>
                <p>
                    <input type="number" class="w3-input w3-padding-16" placeholder="Quantidade de pessoas" required name="pessoas">
                </p>
                <p>
                    <input type="datetime-local" class="w3-input w3-padding-16" placeholder="Data e Hora" required name="data" value="2020-11-16T20:00">
                </p>
                <p>
                    <input type="text" class="w3-input w3-padding-16" placeholder="Mesagem \ Pedidos Especiais" required name="mensagem">
                </p>
                <p>
                    <button class="w3-button w3-light-grey w3-section" type="submit">ENVIAR</button>
                </p>
            </form>
        </div>

        <!-- Fim da página de conteudo -->
    </div>

    <!-- Rodapé -->
    <footer class="w3-center w3-light-grey w3-padding-32">
        <p>Feito por <b>Luís Pedro Dutra Carrocini</b></p>
    </footer>
</body>
</html>
```

## 🛠️ Construído com

* Visual Studio Code - Editor de Código-Fonte;
* HTML5 - Linguagem de Marcação;
* * CSS- Linguagem Web de Formatação;


## ✒️ Autor

* **Luís Pedro Dutra Carrocini** - *Desenvolvimento do Código-Fonte;*


## 🎁 Expressões de gratidão

* Conte a outras pessoas sobre este projeto 📢;
* Agradecimento ao 🫂 [Prof. Márcio](https://github.com/marciofunes);
