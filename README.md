<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Gateway</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div class="container">
        <h1>Secure Payment Gateway</h1>
        <form id="payment-form">
            <label for="card-number">Card Number:</label>
            <input type="text" id="card-number" name="card-number" required>
            
            <label for="expiry-date">Expiry Date:</label>
            <input type="text" id="expiry-date" name="expiry-date" placeholder="MM/YY" required>
            
            <label for="cvv">CVV:</label>
            <input type="text" id="cvv" name="cvv" required>
            
            <button type="submit">Submit Payment</button>
        </form>

        <!-- Authorize.Net Seal -->
        <div class="AuthorizeNetSeal">
            <script type="text/javascript" language="javascript">
                var ANS_customer_id = "468a26b2-b84a-4021-8c7a-8f49ef142351";
            </script>
            <script type="text/javascript" language="javascript" src="//verify.authorize.net:443/anetseal/seal.js"></script>
        </div>
    </div>

</body>
</html>
