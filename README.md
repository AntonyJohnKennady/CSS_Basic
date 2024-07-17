
# CSS-Basic-Project
### html code
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - JK TECH</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>JK TECH</h1>
        <nav>
            <ul>
                <li><a href="index.html" class="active">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
        </nav>
        <div class="search-container">
            <input type="text" placeholder="Enter to Search">
            <button type="button">Search</button>
        </div>
    </header>
    <main class="main">
        <div class="main-content">
            <h1 class="main-content-h1">"Driving progress through precision engineering and boundless creativity."</h1>
            <div class="buttons">
                <button class="login-btn">Log In</button>
                <button class="signup-btn">Sign Up</button>
            </div>
        </div>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED BY ANTONYJOHNKENNADY D</p>
    </footer>
</body>
</html>

```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People - JK TECH</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>JK TECH</h1>
        <nav>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html" class="active">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
        </nav>
        <div class="search-container">
            <input type="text" placeholder="Enter to Search">
            <button>Search</button>
        </div>
    </header>
    <main>
        <section class="people-grid">
            <div class="person-card">
                <img src="https://imgs.search.brave.com/_H_eGMMdAlj0y0hSc63YquF_kj48PGAk456hOlpCOcs/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pLnBp/bmltZy5jb20vb3Jp/Z2luYWxzL2MzL2M2/L2FhL2MzYzZhYTBl/OTgyYTJhYzUzZjYw/MDM3NGQ4NzcyZTU4/LmpwZw" alt="Roop Sagar">
                <h3>VIJAY</h3>
                <p>CEO</p>
            </div>
            <div class="person-card">
                <img src="https://imgs.search.brave.com/afWAu6FuVuLwKlTBQOkl1mqqf1yYFzt5iXmDy2j7l4A/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9hc3Nl/dHMtaW4uYm1zY2Ru/LmNvbS9pZWRiL2Fy/dGlzdC9pbWFnZXMv/d2Vic2l0ZS9wb3N0/ZXIvbGFyZ2UvYWpp/dGgta3VtYXItODgt/MjQtMDMtMjAxNy0x/Ny00OC01Ni5qcGc" alt="Ratan Tata">
                <h3>AJITH KUMAR</h3>
                <p>CEO, Co-Founder</p>
            </div>
            <div class="person-card">
                <img src="https://imgs.search.brave.com/4jfj2X0gemxMQn7FxhhM-sr3pcPn8_8kjuT9BMyriBE/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9hc3Nl/dHMtaW4uYm1zY2Ru/LmNvbS9pZWRiL2Fy/dGlzdC9pbWFnZXMv/d2Vic2l0ZS9wb3N0/ZXIvbGFyZ2Uvc2l2/YWthcnRoaWtleWFu/LTEwNDI5NjktMTgt/MDktMjAxNy0wMy0z/Ny0yMy5qcGc" alt="Steve Jobs">
                <h3>SIVAKARTHIKEYAN</h3>
                <p>CTO, Co-Founder</p>
            </div>
            <div class="person-card">
                <img src="https://imgs.search.brave.com/pEgk4DzG-qolvfYCEEyjYYJJdjeKy0Wi1Xa4_aEGZn4/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly93YWxs/cGFwZXJjYXZlLmNv/bS93cC93cDQyNTA0/MzEuanBn" alt="Sundar">
                <h3>VIJAY SETHUPATHI</h3>
                <p>DIRECTOR</p>
            </div>
            <div class="person-card">
                <img src="https://imgs.search.brave.com/5wjkY0CXhjRFSOT5lOSBZlymf4JtGfFYghib6RQYo_o/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly91cGxv/YWQud2lraW1lZGlh/Lm9yZy93aWtpcGVk/aWEvY29tbW9ucy83/LzdkL1Nvb3J5YV9z/aXZha3VtYXIuanBn" alt="Walt Disney">
                <h3>SURYA</h3>
                <p>Asst. Director</p>
            </div>
            <div class="person-card">
                <img src="https://imgs.search.brave.com/b1JhouZMGz2DJ911etvOjr2Pg9DnzrNUI7DRS1i3U74/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tLm1l/ZGlhLWFtYXpvbi5j/b20vaW1hZ2VzL00v/TVY1QllUa3paVFkx/TWpVdFkySmtaUzAw/TTJVMUxUZzFPVEV0/TWpVMU1tUTRPV0Ux/TXpFelhrRXlYa0Zx/Y0dkZVFYVnlOamt3/T1RnNE1UQUAuanBn" alt="Elon Musk">
                <h3>KARTHI</h3>
                <p>Dy. Director</p>
            </div>
        </section>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED BY ANTONYJOHNKENNADY D</p>
    </footer>
</body>
</html>

```

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - JK Tech</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>JK TECH</h1>
            <nav>
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="products.html">PRODUCTS</a></li>
                    <li><a href="council.html">PEOPLE</a></li>
                    <li><a href="contact.html" class="active">CONTACT</a></li>
                </ul>
            </nav>
            <div class="search-container">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </header>
        <main>
            <section class="contact-us">
                <div class="contact-form">
                    <h2>Contact Us</h2>
                    <form action="#">
                        <input type="text" name="name" placeholder="Your Name">
                        <input type="email" name="email" placeholder="Your Email">
                        <button type="submit">Submit</button>
                    </form>
                </div>
                <div class="contact-info">
                    <h2>Contact Information</h2>
                    <p><strong>Address:</strong> 3RD Floor, Tower 12, FCA Building No. 18, ROOP DEVELOP CITY Phase-I, SECUNDERABAD HR IN 1888546</p>
                    <p><strong>Email:</strong> jktech.official@gmail.com</p>
                    <p><strong>Phone:</strong> 1234567890</p>
                </div>
            </section>
        </main>
        <footer>
            <p>DESIGNED AND DEVELOPED BY ANTONYJOHNKENNADY D</p>
        </footer>
    </div>
</body>
</html>

```

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products - JK TECH</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>JK TECH</h1>
        <nav>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="products.html" class="active">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
        </nav>
        <div class="search-container">
            <input type="text" placeholder="Enter to Search">
            <button>Search</button>
        </div>
    </header>
    <main>
        <section class="product-grid">
            <div class="product-card"><h2>C++</h2><p>Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development</p></div>
            <div class="product-card"><h2>C</h2><p>Crafting Performance: Where Precision Meets C Programming</p></div>
            <div class="product-card"><h2>JAVASCRIPT</h2><p>Scripting Success: Unleashing the Power of JavaScript</p></div>
            <div class="product-card"><h2>PHP</h2><p>PHP is a server side scripting language that is embedded in HTML.</p></div>
            <div class="product-card"><h2>PYTHON</h2><p>Unlocking Innovation: Python Paving the Way to Progress.</p></div>
            <div class="product-card"><h2>SQL</h2><p>SQL is a standard language for accessing and manipulating databases.</p></div>
            <div class="product-card"><h2>SHELL</h2><p>Shell can be accessed by users using a command line interface.</p></div>
            <div class="product-card"><h2>RUBY</h2><p>Ruby: Where Simplicity Meets Power in Programming</p></div>
            <div class="product-card"><h2>TYPESCRIPT</h2><p>Empower Your Code: Embrace the Future with TypeScript</p></div>
            <div class="product-card"><h2>F#</h2><p>F# is an Open-source programming language with a lot of features.</p></div>
        </section>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED BY ANTONYJOHNKENNADY D</p>
    </footer>
</body>
</html>

```
### Css code

```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
    background-image: url("https://images.pexels.com/photos/176851/pexels-photo-176851.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1");
}
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #111;
}
header h1 {
    color: red;
}

nav ul {
    list-style: none;
    display: flex;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

nav ul li a.active {
    color: red;
}
nav a:hover {
    color: red;
}

.search-container {
    display: flex;
}

.search-container input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}

.search-container button {
    padding: 5px;
    border: none;
    border-radius: 0 5px 5px 0;
    background-color: red;
    color: #fff;
}

.product-grid, .people-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px;
}

.product-card, .person-card {
    background-color: #222;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

.product-card h2, .person-card h3 {
    color: red;
}

.main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    text-align: center;
}

.main-content-h1 {
    font-size: 36px;
    margin-bottom: 20px;
    max-width: 600px;
    line-height: 1.5;
}

.buttons {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.login-btn, .signup-btn {
    padding: 10px 20px;
    font-size: 18px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

.login-btn {
    background: red;
    color: #fff;
}

.signup-btn {
    background: green;
    color: #fff;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: red;
    color: #ffffff;
    position: fixed;
    width: 100%;
    bottom: 0;
}

.person-card img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

.contact-us {
    display: flex;
    justify-content: space-around;
    width: 80%;
    padding: 70px;
}

.contact-form, .contact-info {
    padding: 20px;
    width: 40%;
    border: 3px solid #fff;
    
}

.contact-form h2, .contact-info h2 {
    text-align: center;
    color: white;
}

.contact-form input[type="text"], .contact-form input[type="email"] {
    width: 95%;
    padding: 10px;
    margin: 10px 0;
    border: none;
    border-radius: 3px;
}

.contact-form button {
    width: 99%;
    padding: 10px;
    background-color: red;
    border: none;
    border-radius: 3px;
    color: white;
    cursor: pointer;
}
```
### Output
![alt text](<Screenshot 2024-07-16 085818.png>)
![alt text](<Screenshot 2024-07-16 085849.png>)
![alt text](<Screenshot 2024-07-16 085907.png>)
![alt text](<Screenshot 2024-07-16 085926.png>)