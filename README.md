# alvezim.skt.github.io
meu web site de teste 

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    list-style: none;
    text-decoration: none;
}

a {color: #FFF;}

img{max-width: 100%;}

p {font-size: 1.2em; line-height: 1.4em; color: #141A28;}

h2 {color: #141A28;}

.container {
    width: 960px;
    margin: 0 auto;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

html, body {
    width: 100%;
    height: 100%;
}

body {
    font-family: 'Roboto', sans-serif;
    font-size: 16px;
    background-color: #E9F3FE;
}

header {
    width: 100%;
    background-color: #326bf1;
}

.branch, .branch img {
    width: 90px;
    
}

.menu ul { 
    display: flex;
    justify-content: space-between;
}

.menu .menu-link {
    display: block;
    margin: 10px;
    padding: 10px;
    color: #E9F3FE;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: .15em;
    transition: all .3s ease-in-out;
}

.menu .menu-link:hover {opacity: .75;}


main {width: 100%;}

.super-card {
    width: 100%;
    display: flex;
    margin-top: 20px;
}

.super-card-img, 
.super-card-img img {
    width: 800px;
    border-radius: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.super-card-img h2 {margin-top: 20px;}

.super-card-text {margin-left: 40px;}

.super-card-text p + p {margin-top: 1em;}


.card {
    max-width: 350px;
    min-height: 500px;
    border-radius: 3px;
    margin: 1em;
    background-color: #FFF;
    box-shadow: 5px 5px 5px 0px rgba(0, 0, 0, .15);
    transition: all .3s ease-in-out;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.card:hover { box-shadow: 30px 30px 5px 0px rgba(0, 0, 0, .15); }

.card-img { padding: 1em; }

.img-body,
.img-body img {
    width: 200px;
    display: table;
    margin: 0 auto; 
    border-radius: 50%;
}

.card-body { padding: 1em; }
.card-body p {
    color: #343A40;
    line-height: 1.4em;
}

.card-body p + p { margin-top: .5em;}

.card-button {
    width: 100%;
    border-bottom-left-radius: 3px;
    border-bottom-right-radius: 3px;
    padding: 1em;
    background-color: #141A28;
    display: flex;
    justify-content: center;
}

.card-button button {
    width: 250px;
    padding: 1em;
    border: none;
    border-radius: 3px;
    background-image: linear-gradient(to right bottom, #412e82, #393581, #333b7e, #2f407a, #2f4475);
    color: #E9F3FE;
    font-size: 1.2em;
    text-transform: capitalize;
    transition: all .3s ease-in-out;
}

.card-button button:hover {
    cursor: pointer;
    opacity: .75;
}

.sub-title {margin: 20px auto;}

.li-ornament { margin: 10px 0; }

.li-ornament::before {
    content: "";
    display: inline-block;
    width: 4px;
    height: 12px;
    margin-right: 10px;
    background-color: #141A28;
    border-radius: 5px;
}
.contact-link {color: #141A28;}

.map {
    margin: 20px 0;
}
