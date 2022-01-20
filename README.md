<!DOCTYPE html>
<html>
<style>
input[type=text], select {
  width: 100%;
  padding: 15px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #2A4740;
  border-radius: 4px;
  box-sizing: border-box;
  autocomplete:on;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #DBE7E4;
  padding: 20px;
}

h3{
	color:#265A4D;
    font-family: cursive;
    }
    
label{
	color: #3B8F7A;
    }
    
input{
	color:#347162;
    }
    
</style>
<body>

<h3>Join Us Today</h3>

<div>
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="country">Country</label>
    <select id="country" name="country">
      <option value="united kingdom">United Kingdom</option>
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>
  
    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>


