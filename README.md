# Verbex-Group-verbexg.com
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Verbex Group Trading App</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Verbex Group Trading App</h1>
    </header>
    <main>
        <section class="stock-list">
            <h2>Available Stocks</h2>
            <ul>
                <li>Apple Inc. (AAPL) - $150.50</li>
                <li>Alphabet Inc. (GOOGL) - $2800.00</li>
                <li>Microsoft Corporation (MSFT) - $300.25</li>
            </ul>
        </section>
        <section class="transactions">
            <h2>Transactions</h2>
            <ul>
                <li>Bought AAPL at $150.50</li>
                <li>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

main {
    display: flex;
    justify-content: space-around;
    padding: 2rem 0;
}

section {
    flex: 1;
    margin: 0 1rem;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    margin-bottom: 1rem;
}

/* Styling for Stock List */
.stock-list {
    border-right: 1px solid #ccc;
}

/* Styling for Transactions */
.transactions {
    border-left: 1px solid #ccc;
}

h2 {
    margin-top: 0;
}
