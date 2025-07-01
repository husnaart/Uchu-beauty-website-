<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Uchu Beauty</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: #fffafc;
    }
    header {
      display: flex;
      align-items: center;
      gap: 15px;
      margin-bottom: 30px;
      justify-content: center;
    }
    header img {
      border-radius: 50%;
      width: 60px;
      height: 60px;
    }
    header h1 {
      font-size: 2em;
      margin: 0;
      color: #d63384;
    }
    h2 {
      text-align: center;
      color: #c2185b;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 30px;
      background: white;
    }
    td {
      border: 1px solid #f3c2d5;
      padding: 10px;
      text-align: center;
    }
    img.product-img {
      width: 100px;
      height: 100px;
      object-fit: cover;
    }
    form {
      max-width: 600px;
      margin: 0 auto;
      background-color: #fef1f5;
      padding: 20px;
      border-radius: 10px;
    }
    label {
      display: block;
      margin-top: 10px;
      margin-bottom: 5px;
    }
    input[type="text"],
    input[type="email"],
    input[type="tel"],
    input[type="password"],
    select {
      width: 100%;
      padding: 8px;
    }
    .gender, .category {
      display: flex;
      gap: 20px;
      margin-bottom: 10px;
    }
    button {
      margin-top: 15px;
      padding: 10px 15px;
      background-color: #e91e63;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #c2185b;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://via.placeholder.com/60?text=💋" alt="Logo">
    <h1>Uchu Beauty</h1>
  </header>

  <h2>Our Product Collection</h2>

  <table>
    <tbody>
      <!-- 32 Beauty Products -->
      <tr>
        <td><img class="product-img" src="https://via.placeholder.com/100?text=Lipstick" alt="Product"><br>ID: B001<br>Price: $10</td>
        <td><img class="product-img" src="https://via.placeholder.com/100?text=Serum" alt="Product"><br>ID: B002<br>Price: $12</td>
        <td><img class="product-img" src="https://via.placeholder.com/100?text=Palette" alt="Product"><br>ID: B003<br>Price: $15</td>
        <td><img class="product-img" src="https://via.placeholder.com/100?text=Cleanser" alt="Product"><br>ID: B004<br>Price: $8</td>
      </tr>
      <!-- Repeat rows here just like yours till B032 -->
      <!-- You can keep the rest of your rows if time is short -->
    </tbody>
  </table>

  <h2>Customer Registration Form</h2>
  <form>
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="tel">Telephone Number:</label>
    <input type="tel" id="tel" name="tel" required>

    <label for="email">Email Address:</label>
    <input type="email" id="email" name="email" required>

    <label>Gender:</label>
    <div class="gender">
      <label><input type="radio" name="gender" value="male"> Male</label>
      <label><input type="radio" name="gender" value="female"> Female</label>
      <label><input type="radio" name="gender" value="other"> Other</label>
    </div>

    <label for="country">Country of Birth:</label>
    <select id="country" name="country" required>
      <option value="">--Select Country--</option>
      <option value="Kenya">Kenya</option>
      <option value="Uganda">Uganda</option>
      <option value="Tanzania">Tanzania</option>
      <option value="Rwanda">Rwanda</option>
      <option value="Burundi">Burundi</option>
      <option value="South Sudan">South Sudan</option>
    </select>

    <label>Product Category:</label>
    <div class="category">
      <label><input type="checkbox" name="category" value="makeup"> Makeup</label>
      <label><input type="checkbox" name="category" value="skincare"> Skincare</label>
      <label><input type="checkbox" name="category" value="haircare"> Haircare</label>
      <label><input type="checkbox" name="category" value="fragrance"> Fragrance</label>
    </div>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required>

    <button type="submit">Submit</button>
  </form>

</body>
</html>
