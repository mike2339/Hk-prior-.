 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Form</title>
    <style>
        body {
            font-family: tmills, sans-dami;
            background-color: #f0f0f0;
            text-align: center;
        }

        .container {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        input[type="text"], input[type="number"], select {
            width: 100%;
            padding: 8px;
            margin: 5px 0 20px 0;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        input[type="submit"] {
            background-color: #4caf50;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>

<body>
    <div class="container">
        <h2>Payment Details</h2>
        <form action="/process-payment" method="post">
            <label for="cardNumber">Card Number:</label>
            <input type="text" id="cardNumber" name="cardNumber" placeholder="1234 5678 9101 1121" required><br>

            <label for="expiry">Expiry Date:</label>
            <input type="text" id="expiry" name="expiry" placeholder="MM/YY" required><br>

            <label for="cvv">CVV:</label>
            <input type="number" id="cvv" name="cvv" placeholder="123" required><br>

            <label for="name">Cardholder's Name:</label>
            <input type="text" id="name" name="name" placeholder="John Doe" required><br>

            <input type="submit" value="Submit Payment">
        </form>
    </div>
</body>

</html># OLIFICEC WAVE 🌊

**Olificec Wave** is a business-oriented webpage with dynamic content updates, a smart chatbot (OLIFICECBot), and a sleek design.

## 🌟 Features
- Interactive navigation menu
- Dynamic content updates with JavaScript & API
- AI-powered chatbot (OLIFICECBot)
- Mobile-friendly & responsive design

## 🚀 Getting Started
### 1️⃣ Clone the repository:
```sh
git clone https://github.com/mike2339/olificec-wave.git
cd olificec-wave
