# Build-a-check-out-page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Checkout Page</title>
        <style>
            body {
                  font-family: Arial, sans-serif;
                        margin: 20px;
                              line-height: 1.6;
                                  }
                                      h1, h2 {
                                            margin-bottom: 10px;
                                                }
                                                    section {
                                                          border: 1px solid #ccc;
                                                                border-radius: 8px;
                                                                      padding: 16px;
                                                                            margin-bottom: 20px;
                                                                                }
                                                                                    img {
                                                                                          max-width: 150px;
                                                                                                display: block;
                                                                                                      margin-top: 10px;
                                                                                                          }
                                                                                                              label {
                                                                                                                    display: block;
                                                                                                                          margin: 8px 0 4px;
                                                                                                                              }
                                                                                                                                  input {
                                                                                                                                        width: 100%;
                                                                                                                                              padding: 8px;
                                                                                                                                                    margin-bottom: 12px;
                                                                                                                                                          border: 1px solid #aaa;
                                                                                                                                                                border-radius: 4px;
                                                                                                                                                                    }
                                                                                                                                                                        button {
                                                                                                                                                                              background-color: #4CAF50;
                                                                                                                                                                                    color: white;
                                                                                                                                                                                          padding: 10px 15px;
                                                                                                                                                                                                border: none;
                                                                                                                                                                                                      border-radius: 4px;
                                                                                                                                                                                                            cursor: pointer;
                                                                                                                                                                                                                }
                                                                                                                                                                                                                    button:hover {
                                                                                                                                                                                                                          background-color: #45a049;
                                                                                                                                                                                                                              }
                                                                                                                                                                                                                                </style>
                                                                                                                                                                                                                                </head>
                                                                                                                                                                                                                                <body>

                                                                                                                                                                                                                                  <h1>Checkout</h1>

                                                                                                                                                                                                                                    <section>
                                                                                                                                                                                                                                        <h2>Your Cart</h2>
                                                                                                                                                                                                                                            <p>Item: Rubrics Cube</p>
                                                                                                                                                                                                                                                <img src="https://cdn.freecodecamp.org/curriculum/labs/cube.jpg" alt="Rubrics Cube">
                                                                                                                                                                                                                                                  </section>

                                                                                                                                                                                                                                                    <section>
                                                                                                                                                                                                                                                        <h2>Payment Information</h2>
                                                                                                                                                                                                                                                            <form>
                                                                                                                                                                                                                                                                  <label for="card-name">Name on Card</label>
                                                                                                                                                                                                                                                                        <input type="text" id="card-name" name="card-name" required aria-required="true">

                                                                                                                                                                                                                                                                              <label for="card-number">Card Number</label>
                                                                                                                                                                                                                                                                                    <input type="text" id="card-number" name="card-number" required aria-required="true">

                                                                                                                                                                                                                                                                                          <label for="expiry">Expiry Date</label>
                                                                                                                                                                                                                                                                                                <input type="text" id="expiry" name="expiry" placeholder="MM/YY">

                                                                                                                                                                                                                                                                                                      <label for="cvv">CVV</label>
                                                                                                                                                                                                                                                                                                            <input type="text" id="cvv" name="cvv" placeholder="123">

                                                                                                                                                                                                                                                                                                                  <button type="submit">Complete Purchase</button>
                                                                                                                                                                                                                                                                                                                      </form>
                                                                                                                                                                                                                                                                                                                        </section>

                                                                                                                                                                                                                                                                                                                        </body>
                                                                                                                                                                                                                                                                                                                        </html>


