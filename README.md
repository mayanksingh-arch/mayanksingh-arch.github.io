# mayanksingh.github.io
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #d4af37; /* Gold */
    padding: 1rem;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 100;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: #fff;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
}

nav a {
    color: #fff;
    text-decoration: none;
    padding: 0.5rem;
    transition: background 0.3s;
}

nav a:hover {
    background-color: rgba(255, 255, 255, 0.2);
}

.hero {
    background: linear-gradient(to right, #ffb6c1, #ffe4e1); /* Pink gradient */
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding-top: 80px; /* Account for fixed header */
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero button {
    background-color: #d4af37;
    color: #fff;
    border: none;
    padding: 1rem 2rem;
    font-size: 1.2rem;
    cursor: pointer;
    border-radius: 5px;
}

.products, .about, .contact {
    max-width: 1200px;
    margin: 2rem auto;
    padding: 2rem;
    text-align: center;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.product {
    background: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    padding: 1rem;
}

.product img {
    width: 100%;
    border-radius: 10px;
}

.product button {
    background-color: #d4af37;
    color: #fff;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
    border-radius: 5px;
    margin-top: 1rem;
}

form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    max-width: 400px;
    margin: 0 auto;
}

input, textarea {
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}
