<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>	Customer Registration Form</title>
</head>
<body>
<h2><font color="red">Customer Registration Form - Shop Stop </font></h2>
	<hr>
 <form method="POST" action="RegistrationServlet">
  <table>
   <tr>
    <td>Customer ID</td>
    <td><input type="text" name="sid" /></td>
   </tr>
   <tr>
    <td>Customer Name</td>
    <td><input type="text" name="sname" /></td>
   </tr>
   <tr>
    <td>Customer Qualification</td>
    <td><input type="checkbox" value="BSC" name="squal" />BSC<br>
     <input type="checkbox" value="MCA" name="squal" />MCA<br> <input
     type="checkbox" value=" PHD" name="squal" />PHD<br></td>
   </tr>
   <tr>
    <td>Customer Gender</td>
    <td><input type="radio" value="Male" name="sgender" />Male<br>
     <input type="radio" value="Female" name="sgender" />Female<br>
    </td>
   </tr>
   <tr>
    <td>Customer Technologies</td>
    <td><select size="5" name="stech" multiple="multiple">
      <option value="C">C</option>
      <option value="C++">C++</option>
      <option value="Java">JAVA</option>
      <option value=".Net">.Net</option>
      <option value="Oracle">Oracle</option>
      <option value="Testing Tools">Testing Tools</option>
    </select></td>
   </tr>
   <tr>
    <td><select name="branch">
      <option value="Bangalore">Bangalore</option>
      <option value="Hyderabad">Hyderabad</option>
      <option value="Mumbai">Mumbai</option>
      <option value="Pune">Pune</option>
    </select></td>
   </tr>
   <tr>
    <td>Customer Address</td>
    <td><textarea rows="10" cols="50" name="saddr"></textarea></td>
   </tr>
   <tr>
    <td><input type="submit" value="Registration" /></td>
   </tr>
  </table>
 </form>
</body>
</html>
