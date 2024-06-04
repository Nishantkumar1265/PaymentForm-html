# PaymentForm-html
<!DOCTYPE html>
<html>
<head>
    <title>Payment Form</title>
    <style>
        h1{
            color: blue;
        }
        p{
            color: mediumblue;
        }
    </style>
</head>
<body>
    <form action="">
        <h1>Payment Form</h1>
        <h2>User Details</h2>
        <p>Name: * <input type="text" name="name" required></p>
        <h3>Gender * </h3>
        <p>
            Male <input type="radio" name="gender" id="male" required> Female <input type="radio" name="gender" id="female" required>
        </p>
        <p>
            Address: <textarea name="address" id="address" cols="100" rows="7"></textarea>
        </p>
        <p>
            Email:  * <input type="email" name="email" id="email"required>
        </p>
        <p>
            Contact Number: <input type="number" name="cno" id="cno">
        </p>
        <p>
            Pin Code:   *  <input type="number" name="pincode" id="pincode"required>
        </p>
        <h2>Bank Details</h2>
        <p> Card Type: *
            <select name="card_" id="card_type"required>
                <option value="">--Select a card type--</option>
                <option value="Visa">Visa</option>
                <option value="Rupay">Rupay</option>
                <option value="Mastercard">Mastercard</option>
            </select>
        </p> 
        <p>
            Card Number: * <input type="number" name="cardno" id="cardno"required>
        </p>
        <p>
            Expiry Date: * <input type="date" name="expirydate" id="expirydate"required>
        </p>
        <p>
            CVV: * <input type="password" name="cvv" id="cvv" required> 
        </p>
        <input type="button" value="Submit Now">
    </form>
</body>
</html>
