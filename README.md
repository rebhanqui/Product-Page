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
      <img id="header-img" src="https://images.unsplash.com/photo-1526489561696-1a5a2b82de4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80" width="100px" height="100px">
        <nav id="nav-bar">
                <ul>
                    <li> <a class="nav-link" href="#products">
                            <h2>The Products</h2>
                        </a></li>

                    <li>  <a class="nav-link" href="#health-benefits">
                            <h2>The Benefits</h2>
                        </a></li>

                    <li> <a class="nav-link" href="#how-its-made">
                            <h2>The Making</h2>
                        </a></li>

                    <li> <a class="nav-link" href="#contact">
                            <h2>The Contact</h2>
                        </a></li>
                    <li> <a class="nav-link"  href="#header">
                            <h2 style="color: darkgreen">Sheedy Weedy</h2>
                        </a>
                    </li>
                </ul>
        </nav>
    </header>
    <br>
    <img id="header-img-2" src="https://images.unsplash.com/photo-1563660322566-e9bc3441b70c?ixlib=rb-1.2.1&auto=format&fit=crop&w=1352&q=80" maxwidth="1294.25px"
        height="861px">

    <main>
        <div id="products">
            <h2>The Products</h2>
            <ul class="product-list">
                <li>

                    <p>Drink</p>>
                    <a href="/drink"><img
                            src="https://images.unsplash.com/photo-1585146233431-90325d13060b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
                            width="400px" height="400px"></a>

                </li>

                <li>

                    <p>Eat</p>
                    <a href="/eat"><img
                            src="https://images.unsplash.com/photo-1579803987949-4cd894b2210c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
                            width="400px" height="400px"></a>
                </li>

                <li>
                    <p>Use</p>
                    <a href="/Use"><img src="https://images.unsplash.com/photo-1518603889836-db9dda0bc02a?ixlib=rb-1.2.1&auto=format&fit=crop&w=837&q=80"
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
            <div id="video-1">
                <iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/5qEl2bsHgYo" frameborder="0"
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
            <form action="https://www.freecodecamp.com/email-submit" id="form" name="action" >
                

                <label for="name">Name:
                    <input type="text" placeholder="John Doe" value="John Doe" required>
                </label>
                <label for="email">
                    Email:<input name="email" type="email" id="email" placeholder="johndoe@email.com" value="johndoe@email.com" required>
                </label>
                <label for="telephone">Phone:
                    <input type="tel" placeholder="Mobile/Landline" value="Mobile/Landline" >
                </label>
                <label for="text-box">
                    <textarea id="text-box" name="txtArea" rows="5" cols="46" style="align-self: center;"
                            placeholder="Comment" value="Comment"></textarea>
                </label>
                <label for="button">
                 <input type="submit" id="submit" value="Submit">  
              </label>
                
            </form>
        </div>
        <footer>

        </footer>
    </main>
</body>

</html>
