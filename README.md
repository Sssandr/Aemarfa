<style>
body {
  width: 100%;
  height: 100vh;
  margin: 0;
  background-color:violet;
  color: white;
  font-family: Tahoma;
  font-size: 16px;
}

h1, p {
  margin: 1em auto;
  text-align: center;
}

form {
  width: 60vw;
  max-width: 500px;
  min-width: 300px;
  margin: 0 auto;
  padding-bottom: 2em;
}

fieldset {
  border: none;
  padding: 2rem 0;
  border-bottom: 3px solid #3b3b4f;
}

fieldset:last-of-type {
  border-bottom: none;
}

label {
  display: block;
  margin: 0.5rem 0;
}

input,
textarea,
select {
  margin: 10px 0 0 0;
  width: 100%;
  min-height: 2em;
}

input, textarea {
  background-color: #0a0a23;
  border: 1px solid #0a0a23;
  color: #ffffff;
}

.inline {
  width: unset;
  margin: 0 0.5em 0 0;
  vertical-align: middle;
}

input[type="submit"] {
  display: block;
  width: 60%;
  margin: 1em auto;
  height: 2em;
  font-size: 1.1rem;
  background-color: #3b3b4f;
  border-color: white;
  min-width: 300px;
}

input[type="file"] {
  padding: 1px 2px;
}

.inline{
  display: inline; 
}
</style>
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









