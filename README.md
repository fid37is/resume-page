<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">


    <!-- Latest compiled JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <title>Agba Fidelis CV</title>
    <style type="text/css">
        body {
          background-color: grey;
          padding: 14px;
        }
        .fullName {
          font-family: Arial, Helvetica, sans-serif;
          font-display: Helvetica;
          color: blueviolet;
          text-align: center;
          font-size: 50px;
        }
        .personalInfo {
          font-style: normal;
          color: red;
          text-align: center;
          font-size: 30px;
        }
        li {
          color: rgb(72, 245, 57);
          padding: 1px;
        }
        h2 {
          color: yellow;
          font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
          font-style: normal;
          font-size: 25px;
        }
        b, {
          color: red;
        }
        .skillToAward {
          background-image: url("https://res.cloudinary.com/lordefid/image/upload/v1567283598/18_jrwlfa.jpg");
          font-style: normal;
          color:  white;
          font-size: 20px;
        }

        label
        {
        width: 4em;
        float: left;
        text-align: right;
        margin-right: 0.5em;
        display: block
        }

        .submit input
        {
        margin-left: 4.5em;
        }
        input
        {
        color: black;
        background: whitesmoke;
        border: 1px solid #b12c04a6;
        }
        textarea {
          border: 1px solid #b12c04a6;
          background: whitesmoke;
        }

        .submit input
        {
        color: #000;
        background: #b12c04a6;
        border: 2px outset #d7b9c9
        }
        fieldset
        {
        border: 1px solid #b12c04a6;
        width: 50em
         ;
        }
      
        legend
        {
        color: #fff;
        background: #b12c04a6;
        border: 1px solid #b12c04a6;
        padding: 2px 6px
        }
       


    </style>
  </head>
  <body>
    <div style="background-color: black">
    <h1 class="fullName">Agba Fidelis</h1>
    </div>
    <div class="personalInfo" style="background-color: white">
    82 Shitta Street, Dopemu<br>
    Agege, Lagos  100273<br>
    (234) 808-5952266<br>
    mistarfid@gmail.com<br>
    </div>
    <div class="skillToAward">
    <h2>Skills</h2>
          Proficiency in manipulation of computer environment, computer hardware installation and maintenance,<br>
          software installation and troubleshooting, handling computer related equipment, knowledge of corel Draw,<br>
          Photoshop, internet maneuvering,  HMTL, CSS, JavaScript and PHP.<br>
    <br>
    <h2>Experience</h2>
          July 2019 - PRESENT<br>
    <b>Hapeng Computers, Lagos</b> - <i>Computer Operator/Graphics Designer</i>
        <ul>
          <li>General Computer Operation and Customer Support</li>
          <li>Graphics Designing</li>
          <li>Maintenance of computer components and internet sales.</li>
        </ul>

          2014 - January 2019<br>
    <b>Hitecpro Limited, Calabar</b>- <i>Computer Operator/Customer Support</i>
        <ul>
          <li>Customer Support and general computer equipment and peripheral management.</li>
          <li>Ensure Security of Computer systems.</li>
          <li>Provide guidance to users on how to operate new computer equipment.</li>
          <li>Organize and schedule upgrades</li>
          <li>Troubleshoot to diagnose and resolve malfunction and replaces equipment.</li>
        </ul>

    <h2>Education</h2>
      April  2009 - August 2012
    <b>Federal College of Education, Obudu</b> -<i> N.C.E</i><br>
      National Certificate in Education in Computer Science/Physics, with Credit in Computer Science,<br>
      General Studies, Education respectively and merit in Physics.<br>
    <h2>Awards</h2>
      Award of the National Certificate in Education which means I am licensed to<br>
      teacher computer Studies in High schools in Nigeria.
  
      </div><br>
      
      <section id="form" class="container">
        <div class="row-fluid">
            <form id="inquiryForm" class="inquiryForm" name="contact-form" method="post" action="">
                <fieldset class="content">
                    <legend><h4>CONTACT ME HERE</h4></legend>
                    <div class="status alert alert-success" style="display: none"></div>
                   <p>
                        <label for="name">Name</label>
                        <input id="fullName" name="fullName" type="text" class="input-block-level" required="required" placeholder="Your full name">
                    </p>
                    <p>
                        <label for="e-mail">E-mail</label>
                        <input id="mailAddr" name="mailAddr" type="email" class="input-block-level" required="required" placeholder="Your email address">
                    </p>
                    <p>
                      <label for="title">Title</label>
                      <select id="psonTitle" name="title" required="" onchange="changeData(event)">
                          <option >Select title</option>
                          <option >Official inquiry</option>
                          <option >Unofficial inquiry</option>                        
                          </option>
                      </select></p>
                    <p><div class="span7">
                        <label>Message</label>
                        <textarea name="message" id="message" required="required" class="input-block-level" rows="8" minlength="20" maxlength="200"></textarea>
                </div></p>
                    <p class="submit">
                        <input type="submit" value="Submit">
                    </p>
                </fieldset>
            </form>
        </div>

</section>

</body></html>
