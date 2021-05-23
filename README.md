# html-form
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body style="font-size:120%;margin-left:615px;margin-top:35px;background-color:#659DBD;">
    <form>
        <label for="fname">First Name:</label><br>
        <input type="text" size="25"><br><br>
        <label for="lname">Last Name:</label><br>
        <input type="text" size="25"><br><br>
        <label for="gender">Gender:</label><br>
        <input type="radio" name="gender">
        <label for="Male">Male</label><br>
        <input type="radio" name="gender" >
        <label for="Female">Female</label><br>
        <input type="radio" name="gender">
        <label for="Others">Others</label><br><br>
        <label>Highest Qualification:</label>
        <select  name="qualifications">
          <option value="SSC">SSC</option>
          <option value="Inter">Inter</option>
          <option value="B.Tech">B.Tech</option>
          <option value="M.Tech">M.Tech</option>
          <option value="PhD">PhD</option>
        </select><br><br>
        <label for="email">Email:</label><br>
        <input type="email" size="25"><br><br>
        <label for="phno">Phone number:</label><br>
        <input type="number" size="2"><br><br>
        <label for="address">Address:</label><br>
        <textarea rows="8" cols="25"></textarea><br>
        <input type="submit">
        <input type="reset">
    </form>
</body>
</html>
