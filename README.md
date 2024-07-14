body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

#accounts {
    margin: 20px 0;
}

.account-list {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.account-item {
    background: white;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    width: calc(33% - 20px);
    box-sizing: border-box;
}

.account-item h3 {
    margin: 0 0 10px;
}

.account-item p {
    margin: 5px 0;
}

.account-item button {
    background: #333;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
    border-radius: 5px;
}

.account-item button:hover {
    background: #555;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em;
    position: fixed;
    bottom: 0;
    width: 100%;
}
