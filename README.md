# Survey-Form
Ну тут что-то будет
<link href="https://fonts.googleapis.com/css2?family=Architects+Daughter&family=Comfortaa:wght@600&display=swap" rel="stylesheet"
<html>
                                                             
  <head>
  </head>
  <style>
    
    body{

 font-family: 'Architects Daughter', cursive;
font-family: 'Comfortaa', cursive;url(http://fullhdwallpapers.ru/image/abstract/6855/sirenevyy-fon.jpg);
}
h1{font-size: 40px;
  font-style:italic;
color:rgb(184, 237, 252);
}
p{font-size: 20px;
  background-color:lightblue;}
form{font-size: 17px;
  background-color:lightblue;}
 </style>
  <body>
<h1 id="title"><center> А вот и ты</h1>
      <p id="description">В данный момент вы оставите данные, дабы лицезреть чудо.</p>
        <form id="survey-form">
          <label id="name-label">Name:</label><br>
          <input type="text" id="name" name="name" required placeholder="Who are you"><br> 
          <label id="email-label">Email:</label><br>
          <input type="email" id="email" name"email"  required placeholder="Enter your mail"><br>
          <label id="number-label">Skill:</label>
          <br><input type="number" id="number" name="number" min="0" max="99999999999999" required placeholder="Your skill lvl"><br>
     
          <select id="dropdown" name="Классы">
         <option value="Low">Low</option>
         <option value="Middle">Middle</option>
         <option value="High">High</option>
          </select>
         <br> <input type="radio" name="gender" value=male>Male<br>
          <input type="radio" name="gender" value=female>Female<br>
           <input type="radio" name="gender" value=ogurec>Ogurec<br>
          <input type="checkbox" name="two" value="Apple">I have a Apple notebook
          <input type="checkbox" name="three" value="HP">I have a HP notebook
         <input type="checkbox" name="one" value="Asus">I have a Asus notebook
          <br><textarea placeholder="Additional information"></textarea>
           <br> <input type="submit" id="submit">
          
        </form>
  </body>
</html>
