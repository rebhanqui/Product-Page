# Product-Page
WIP

<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
<!DOCTYPE html>
<html>

<head>
    <meta lang="8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <link rel="stylesheet" type="text/css"
        href="C://Users/Rebekah Quinn/Documents/Studio Ninty/Studio Ninty Online/HTML/product-landing-page.css">
    <link href="https://fonts.googleapis.com/css2?family=Poiret+One&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300&family=Poiret+One&display=swap"
        rel="stylesheet">
</head>

<body>
    <header id="header">
        <nav id="nav-bar">
            <div class="nav-link">
                <ul>
                    <li><a href="#products">
                            <h2>The Products</h2>
                        </a></li>

                    <li><a href="#health-benefits">
                            <h2>The Benefits</h2>
                        </a></li>

                    <li><a href="#how-its-made">
                            <h2>The Making</h2>
                        </a></li>

                    <li><a href="#contact">
                            <h2>The Contact</h2>
                        </a></li>
                    <li>
                        <a href="#header">
                            <h2 style="color: darkgreen">Sheedy Weedy</h2>
                        </a>
                    </li>

                </ul>
            </div>
        </nav>
    </header>
    <br>
    <img id="header-img" src="C:/Users/Rebekah Quinn/Downloads/cbd-infos-uQEr4uWxvJc-unsplash.jpg" maxwidth="1294.25px"
        height="861px">

    <main>
        <div id="products">
            <h2>The Products</h2>
            <ul class="product-list">
                <li>

                    <p>Drink</p>>
                    <a href="/drink"><img
                            src="C:/Users/Rebekah Quinn/Downloads/pot-head-coffee-FTI10pjP344-unsplash.jpg"
                            width="400px" height="400px"></a>

                </li>

                <li>

                    <p>Eat</p>
                    <a href="/eat"><img
                            src="C:/Users/Rebekah Quinn/Downloads/pharma-hemp-complex-H9Oto_H3qig-unsplash.jpg"
                            width="400px" height="400px"></a>
                </li>

                <li>
                    <p>Use</p>
                    <a href="/Use"><img src="C:/Users/Rebekah Quinn/Downloads/till-kraus-dSLcc4_cd4M-unsplash.jpg"
                            width="400px" height="400px"></a>
                </li>
        </div>
        </ul>
        </div>

        <div id="health-benefits">
            <h3>The Benefits</h3>
            <div id="benefits">
                <table>
                    <tr>
                        <td>Relief of chronic pain</td>
                        <td>Improves lung capacity</td>
                    </tr>
                    <tr>
                        <td>Help lose weight</td>
                        <td>Regulate and prevent diabetes</td>
                    </tr>
                    <tr>
                        <td>Fight cancer</td>
                        <td>Helps treat depression</td>
                    </tr>
                    <tr>
                        <td>Shows promise in autism treatment</td>
                        <td>Regulate seizures</td>
                    </tr>
                    <tr>
                        <td>Mend bones</td>
                        <td>Helps with ADHD/ADD</td>
                    </tr>
                    <tr>
                        <td>Treatment for glaucoma</td>
                        <td>Alleviate anxiety</td>
                    </tr>
                </table>
            </div>
        </div>

        <div id="how-its-made">
            <h4>The Making</h4>
            <div id="video">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/5qEl2bsHgYo" frameborder="0"
                    allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen></iframe>
            </div>
            <h3>A look at how we extract the good from the bad!</h3>
            <p id="video-descrip" style="text-align:justify">Arguably the best method for CBD extraction, the supercritical CO₂ is an advanced, highly customizable
                way to get the best out of the hemp plant. This is the method we use here at Cibdol.

                In this method, CO₂ is manipulated such that it enters a supercritical state, where it possesses
                qualities of both a liquid and a gas. It’s then pumped through the cannabis flower at multiple
                temperatures and angles in order to dissolve terpenes and cannabinoids at their various solubilities, in
                a process called fractionation.

                It allows for the extraction of clean and safe concentrates, without the use of additional additives or
                potential contaminants. It also allows for highly efficient yields, getting the most out of the hemp
                plant.

                It is, however, an industrial process, making it highly expensive and impractical for any but the most
                dedicated CBD producers.</p>
        </div>

        <div id="contact">
            <h5>The Contact</h5>
            <form id="form">
                

                <label for=name>Name:
                    <input type="text" placeholder="John Doe" value="John Doe" required>
                </label>
                <label for="email">
                    Email:<input id="email" type="email" placeholder="johndoe@email.com" value="johndoe@email.com" required>
                </label>
                <label for=telephone>Phone:
                    <input type="tel" placeholder="Mobile/Landline" value="Mobile/Landline" >
                </label>
                <label>
                    <textarea id="text-box" name="txtArea" rows="5" cols="46" style="align-self: center;"
                            placeholder="Comment" value="Comment"></textarea>
                </label>
                <button id="submit" type="submit" formaction=" https://www.freecodecamp.com/email-submit" >Submit</button>

                
            </form>
        </div>
        <footer>

        </footer>
    </main>
    <!--fix all layout and move header back-->
</body>

</html>
