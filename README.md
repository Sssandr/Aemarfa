<!Doctype html>
<head>
<title>Order details</title>
<link rel="stylesheet-css" href="styles.css">

<body>
<h1 id="title">Order details</h1>
<p id="description">fill the form to place an order</p>
<form action="<form action="https://formsubmit.co/sturkson97@gmail.com" method="POST" />" id="survey-form">
<p>Name</p>
<label id="name-label">
<input type="text" name="name" id="name" placeholder="Ama Baidoo"required></label>
<p>Email</p>
<label id="email-label"><input type="email" placeholder="example@gmail.com" id="email" name="email"></label required>
<p>Number of orders placed</p>
<label id="number-label"><input id="number"min="1"max="10"placeholder="5" type="number" name="number" required></label>
<p>What are you ordering?</p>
<select id="dropdown" type="dropdown">
<option>Phone case</option>
<option>Earrings</option>
<option>Necklace</option>
<option>Bottle</option>
<option>bookmark</option>
<option>notebook</option>
</select>
     <fieldset>
        <legend>Account type (required)</legend>
        <label for="personal-account"><input id="personal-account" type="radio" name="account-type" class="inline" checked /> Personal</label>
        <label for="business-account"><input id="business-account" type="radio" name="account-type" class="inline" /> Business</label>
      </fieldset>
<p>What are your emotions considering the order</p>
<label> <input type="checkbox"value="happy">Happy</label>
<label><input type="checkbox" value="expectant">expectant</label>
<label><input type="checkbox" value="normal">normal</label>
<p>Product description</p>
<textarea id="product description" name="description"  placeholder="Necklace should have the letter A on it"></textarea>
<button id="submit">Submit</button>
</form>
</body>
</head>









