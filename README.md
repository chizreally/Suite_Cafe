body {
    background-color: #f3e9dc;
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center; /* centers content */
}

#main-title {
    color: #6b3e26;
    font-family: 'Times New Roman', Times, serif;
    margin-top: 5rem;
}

.nav {
    position: absolute;
    top: 20px;
    right: 40px;
}

.nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
    padding: 0;
}

.nav li {
    background: #d9b99b;
    padding: 10px 15px;
    border-radius: 8px;
    transition: 0.3s;
    cursor: pointer;
}

.nav li:hover {
    background: #c89f72;
}

.img {
    display: block;
    margin: 2rem auto;
}

.card {
    background: white;
    border: 2px solid #c89f72;
    padding: 1rem;
    width: 280px;
    margin-top: 20px;
    border-radius: 10px;
    box-shadow: 0 3px 10px rgba(0, 0, 0, 0.15);
    text-align: center;
}

.contact-area {
    margin-top: 20px;
    text-align: center;
}

.contact-area input {
    display: block;
    margin: 10px auto;
    padding: 7px;
    width: 250px;
    border-radius: 5px;
    border: 1px solid #b48b63;
}

#order-btn {
    display: block;
    margin: 20px auto;
    background: #6b3e26;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1rem;
    transition: 0.3s;
}

#order-btn:hover {
    background: #57331f;
}

.footer-box {
    width: 100%;
    background-color: #d9b99b;
    margin-top: 40px;
    padding: 12px;
    text-align: center;
    border-radius: 5px 5px 0 0;
}
