# pay
Payment from
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Payment Form</title>
  </head>
  <body>
    <form action="">
      <h1>Payment Form</h1>
      <p>required field are follown by *</p>
      <h2>Contact Information</h2>
      <p>Name:* <input type="text" name="name" required></p>
      <fieldset>
        <legend>Gender*</legend>
        <p>
          Male <input type="radio" name="gender" id="Male" required> Female
          <input type="radio" name="gender" id="Female" required>
        </p>
      </fieldset>
      <p>
        Addrss *:
        <textarea name="address" id="address" cols="70" rows="6"required></textarea>
      </p>
      <p>Email *: <input type="email" name="email" id="email" required></p>
      <p>Pincode*: <input type="number" name="Pincode" id="Pincode" required></p>
      <h2>Payment Information</h2>
      <p>Card Type*:
        <select name="cardtype" id="cardtype"required>
            <option value="">-----select a Card Type--</option>
            <option value="VISA">VISA</option>
            <option value="MASTERCARD">MASTERCARD</option>
            <option value="RUPAY">RUPAY</option>
            <option value="CRED">CRED</option>
        </select>
      </p>
      <p>
        Card Number*: <input type="number" name="number" id="number"required>
      </p>
      <p>
        Expire date*: <input type="date" name="exp_date" id="exp_date"required>
      </p>
      <p>
        CVV*: <input type="password" name="cvv" id="cvv"required>
      </p>
      <input type="submit" value="Pay Now">
    </form>
  </body>
</html>
