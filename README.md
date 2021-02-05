# FCC-project-1-2
Created a survey page as part of the assignments. 
<!DOCTYPE html>
<html>
  <style>
    body {
  background-color: #eef1e6;
  font-family: garamond, cooperplate, arial;
  font-size: 10;
  line-height: 2;
  text-align: center;
  color: black;
  margin: 0;
  padding: 20px;
  text-align: center;
  justify-content: center;
 }
#survey-form{
  max-width: 575px;
  background-color: #bfd4db;
  text-align: left;
  padding: 20px;
  justify-content: center;
  margin: 0 auto 50px auto;
  border-radius: 5px;
} 
#name{
  width: 100%;
  height: 20px;
  border-radius: 5px;
  border-color: grey;
  border-width: 1px;
  border-style: solid;
  font-family: garamond;
}
#number{
  width : 100%;
  height: 20px;
  border-radius: 5px;
  border-color: grey;
  border-width: 1px;
  border-style: solid;
  font-family: garamond;
}
#email{
  width : 100%;
  height: 20px;
  border-radius: 5px;
  border-color: grey;
  border-width: 1px;
  border-style: solid;
  font-family: garamond;
}
#dropdown{
  font-family: garamond;
  border-radius: 5px;
}
#favourite{
  font-family: garamond;
  border-radius: 5px;
}
#message{
  width: 100% ;
  font-family: garamond;
  border-radius: 5px;
}
#submit{
  border-radius: 5px;
  font-family: garamond;
  border-color: grey;
  border-width: 1px;
  border-style: solid;
}
  </style>
  
  <main id="main">
  <h1 id="title">
    Website development survey
 </h1>    
    <p id="description">
      <em>Thank you for taking this survey and helping us to improve our services!</em>
    </p>
  
    <form id="survey-form">
      
      <label id="name-label" for="name"><strong>Name</strong></label><br>
      <input type="text" id="name" placeholder=" Enter your name" required><br>
      
      <label id="number-label" for="age"><strong>Age</strong></label><br>
      <input type="number" id="number" placeholder= " Enter your age" min="0" max="115" required><br>
      
      <label id="email-label" for="email"><strong>Email</strong></label><br>
      <input type="email" id="email" placeholder= " Enter your Email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$" required><br>               <br>
            
      <label for="role"><strong>What describes best your current role</strong></label><br>
      <select id="dropdown">
      <option hidden selected> Select Current Role</option>
      <option value="Unemployed">Unemployed</option>
      <option value="Student">Student</option>
      <option value="Part-time employed">Part-time employed</option>
      <option value="Full-time employed">Full-time employed</option>
      <option value="Retired">Retired</option>
      <option value="Other">Other</option>
      </select><br><br>
      
      <label for="recommend"><strong>Would you recommend this website to a friend?</strong></label><br>
      <label for="No"><input id="no" value="no" type="radio" name="recommend"> No</label><br>
      <label for="Maybe"><input id="maybe" value="no" type="radio" name="recommend"> Maybe</label><br>
      <label for="Yes"><input id="yes" value="no" type="radio" name="recommend"> Yes</label><br><br>
      
      <label for="feature"><strong>What is your favourite feauture of this website?</strong></label><br>
      <select id="favourite">     
      <option hidden selected>Select Option</option>
      <option value="Buttons">Buttons</option>
      <option value="Drop-down menus">Drop-down menus</option>
      <option value="Multiple buttons">Multiple buttons</option>
      </select><br><br>
        
      <label for="improvement"><strong>What would you like to see improved?</strong><br><em>(Check all that apply)</em></label><br>
      <input type="checkbox" id="improvement1" name="improvement1" value="Questions">
      <label for="Front-End"> Questions</label><br>
      <input type="checkbox" id="improvement2" name="improvement2" value="Lay-out">
      <label for="improvement3"> Lay-out</label><br>
      <input type="checkbox" id="improvement3" name="improvement3" value="Colors">
      <label for="improvement3"> Colors</label><br><br>
      
      <label for="message"><strong>Any comments or suggestions?</strong></label><br>
      <textarea placeholder=" Write any comments or suggestions here" name="message" id="message"></textarea><br><br>
        
      <button type="submit" id="submit">Submit</input><br>
  </form>
   
</main>
<footer>
  This page is created <a id="tribute-link" href="https://github.com/HaakSan" target="_blank">HaakSan</a> for <a id0"fcc-link" href="https://www.freecodecamp.org/""_blank">FreeCodeCamp</a> - 2021</p>
  </footer>
</html>
