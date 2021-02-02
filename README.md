# New_Project


@{
    ViewBag.Title = "Login";
    <link href="~/css.Project/EstilosLogin.css" rel="stylesheet" />
    <link href="~/JavaScript/JavaScriptCarrusel.js" rel="stylesheet" />
}



<body>

    <section class="w3l-login">
        <div class="overlay">

            <div class="wrapper">
                @*<div class="logo">
                          <a class="brand-logo" href="prueba.cshtml">PETDEVOPS</a>
                    </div>*@
                <div class="perritosbb">
                    <section class="awSlider">
                        <div class="carousel slide" data-ride="carousel">
                            <!-- Indicators -->
                            <ol class="carousel-indicators">
                                <li data-target=".carousel" data-slide-to="0" class="active"></li>
                                <li data-target=".carousel" data-slide-to="1"></li>
                                <li data-target=".carousel" data-slide-to="2"></li>
                                <li data-target=".carousel" data-slide-to="3"></li>
                            </ol>

                            <!-- Wrapper for slides -->
                            <div class="carousel-inner" role="listbox">
                                <div class="item active">
                                    <img src="https://as01.epimg.net/mexico/imagenes/2019/01/19/tikitakas/1547933521_851367_1547933683_noticia_normal_recorte1.jpg">
                                    <div class="carousel-caption"></div>
                                </div>
                                <div class="item">
                                    <img src="https://www.losperritosbonitos.com/wp-content/uploads/2020/12/platano-perro-pueden-comer-720x405.jpg">
                                    <div class="carousel-caption"></div>
                                </div>
                                <div class="item">
                                    <img src="https://www.vivanicaragua.com.ni/contenido/archivos/2020/02/tips-cuidar-amigo-cachorro1-720x405.jpg">
                                    <div class="carousel-caption"></div>
                                </div>
                                <div class="item">
                                    <img src="https://prod.media.wapa.pe/720x405/wapa/imagen/2019/10/23/noticia-1571865232-perrito-durmiendo-portada.png">
                                    <div class="carousel-caption"></div>
                                </div>
                            </div>

                            <!-- Controls -->
                            <a class="left carousel-control" href=".carousel" role="button" data-slide="prev">
                                <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
                                <span class="sr-only">Geri</span>
                            </a>
                            <a class="right carousel-control" href=".carousel" role="button" data-slide="next">
                                <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
                                <span class="sr-only">İleri</span>
                            </a>
                        </div>
                    </section>
                </div>
                <div class="form-section">
                    <h3>LOGIN PETDEVOPS</h3>
                    <form action="Verify" method="post" class="signin-form">
                        <div class="form-input">
                            <input type="text" name="LoginName" placeholder="Usuario" required="" autofocus>
                        </div>
                        <div class="form-input">
                            <input type="password" name="Password" placeholder="Contraseña" required="">
                        </div>
                        <label class="check-remaind">
                            <input type="checkbox">
                            <span class="checkmark"></span>
                            <p class="remember">Recuérdame</p>
                        </label>
                        <button type="submit" class="btn btn-primary theme-button mt-4">INGRESAR</button>
                        <div class="new-signup">
                            <a href="#reload" class="signuplink">¿Olvidaste tu usuario o contraseña?</a>
                        </div>
                    </form>
                    <p class="signup">¿Aún no tienes una cuenta?<a href="#signup.html" class="signuplink">Regístrese</a></p>
                </div>
            </div>
        </div>
        <div id='stars'></div>
        <div id='stars2'></div>
        <div id='stars3'></div>


        @*<div class="copy-right">
                <p>&copy; 2021 Snow Login Form. All rights reserved | Design by <a href="http://w3layouts.com/" target="_blank">W3Layouts</a></p>
            </div>*@
    </section>
</body>
