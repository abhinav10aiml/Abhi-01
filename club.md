<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="style.css.css">

</head>
<body>
<br>
<nav>
 <a href="#register">Home</a>|
  <a href="#about">About </a>|
    <a href="#register">Register</a>|
      <a href="#contact">Contact</a>
   </nav>
   <h1>CODING CLUB </h1>
   
   <h2>Upcoming Events </h2>
   
 
<table border="1">
<caption>Club Events </caption >
<thead>
<tr>
<th>Event</th>
<th>Date</th>
<th>Venue</th>
</tr>
<tbody>
<tr>
<td>HTML Workshop</td>
<td>12 Nov</td>
<td>Lab 1</td>
</tr>
 <tr>
 <td>Hackathon</td>
 <td>20 Nov</td>
 <td>Seminar Hall</td>
 </tr>
 <tfoot>
 <tr><td colspan="3">Total events: 2</td></tr>
 </tfoot>
 </table>

    <h1><b> Register </b></h1>
    <form action ="/submit" method="post"  >
   

    
             <label> Name :</label>
             <input type="text" name ="username"  placeholder =" Enter your username"required >
             <br>
             <br>
             <label >EMAIL:</label>
             <input type="email" name ="email"required >
             <br>
             <br>
             
                      
  <label for="country">Country Code:</label>

<select id="country">
  <option value="+91">India (+91)</option>
  <option value="+1">USA/Canada (+1)</option>
  <option value="+44">UK (+44)</option>
  <option value="+61">Australia (+61)</option>
  <option value="+81">Japan (+81)</option>
  <option value="+86">China (+86)</option>
</select>
            
  

<br>
             <label >PHONE:</label>
             <input type="tel" name ="phone" pattern="(0-9){10}" maxlength="10">
             <br>
               <br>
             <label>DOB:</label>
             <input type="date"name ="dob"required>
             <br>
             <br>
             
             <label>PASSWORD:</label>
             <input type=" password" name ="password"required>
                 <br>
                 <br>
               <label>GENDER:</label>
               <input type="radio" name="gender">Male
               <input type ="radio" name ="gender">Female 
               <br>
               <br>
               <label for ="file">Choose file :</label>
               <input type ="file" id="file" name="file" required >
               <br>
               <br>
               
               <label>Interests:</label>
               <input type="checkbox" name ="skills">Web
               <input type="checkbox" name ="skills">DSA
               
               <br>
               <br>
               
               <label for="Branch">Branch:</label>

<select id="branch">
  <option >Btech.Ai</option>
  <option >BCA</option>
  <option >BSC</option>
  <option >BCA.AI</option>
  
</select>
<br>
<br>
                <label for="discription">why you want to join?</label>
                
           
                            <textarea id="discription" name="discription" rows="3" cols="30" min="0" max=500></textarea>
                            <br>
              
                           
                 <input type="submit" value="Submit">
                 <input type="reset" value="Reset">
                 
              </form>
        
               
             
    
</body>
</html>

