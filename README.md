# validationform
Validation form with jQuery

First: Add the following form:
 <form action="" method="post" id="contact_form">

                <div class="row">

                    <label for="name" class="col-xs-12 col-sm-3 col-md-3">Name</label>
                    <input id="name" name="name" type="text" placeholder="What's your name?" class="col-xs-3 col-sm-3  col-md-3">
                    <span id="nameInfo" class="col-xs-6 col-sm-5 col-md-5"></span>

                </div>

                <div class="row">

                    <label for="lastname" class="col-sm-3 col-md-3">Last name</label>
                    <input id="lastname" name="lastname" type="text" placeholder="What's your lastname?" class="col-xs-3 col-sm-3 col-md-3">
                    <span id="lastnameInfo" class="col-xs-6 col-sm-3 col-md-5"></span>

                </div>

                <div class="row">

                    <label for="country" class="col-sm-3 col-md-3">Country</label>
                    <select id="country" name="country" class="col-xs-3 col-sm-3 col-md-3">
                        <option value="">- Select a country -</option>
                       
                        <option value="1" selected>España</option>
                       
                    </select>
                    <span id="countryInfo" class="col-xs-6 col-sm-3 col-md-5"></span>

                </div>

                <div class="row">

                    <label for="ciudad" class="col-sm-3 col-md-3">City</label>
                    <input id="ciudad" name="ciudad" type="text" placeholder="Write your city" class="col-xs-3 col-sm-3 col-md-3">
                    <span id="ciudadInfo" class="col-xs-6 col-sm-3 col-md-5"></span>

                </div>

                <div class="row">

                    <label for="codpostal" class="col-sm-3 col-md-3">Postal Code</label>
                    <input id="codpostal" name="codpostal" type="text" placeholder="Write your postal code." class="col-xs-3 col-sm-3 col-md-3">
                    <span id="codpostalInfo" class="col-xs-6 col-sm-3 col-md-5"></span>

                </div>

                <div class="row">

                    <label for="direccion" class="col-sm-3 col-md-3">Address</label>
                    <input id="direccion" name="direccion" type="text" placeholder="Write your address" class="col-xs-3 col-sm-3 col-md-3">
                    <span id="direccionInfo" class="col-xs-6 col-sm-3 col-md-5"></span>

                </div>

                <div class="row">

                    <label for="telephone" class="col-sm-3 col-md-3">Telephone</label>
                    <input id="telephone" name="telephone" type="text" placeholder="Insert your telephone" class="col-xs-3 col-sm-3 col-md-3">
                    <span id="telephoneInfo" class="col-xs-6 col-sm-3 col-md-5"></span>

                </div>



                <div class="row">

                    <label for="email" class="col-sm-3 col-md-3">E-mail</label>
                    <input id="email" name="email" type="text" class="col-xs-3 col-sm-3 col-md-3" placeholder="Insert your email">
                    <span id="emailInfo" class="col-xs-6 col-sm-3 col-md-5"></span>

                </div>




                <div class="row">

                    <label for="user" class="col-sm-3 col-md-3">Username</label>
                    <input id="user" name="user" type="text" class="col-xs-3 col-sm-3 col-md-3" placeholder="Insert a username">
                    <span id="userInfo" class="col-xs-6 col-sm-3 col-md-5"></span>
                </div>

                <div class="row">

                    <label for="pass1" class="col-sm-3 col-md-3">Password</label>
                    <input id="pass1" name="pass1" type="text" class="col-xs-3 col-sm-3 col-md-3" placeholder="Insert a password">
                    <span id="pass1Info" class="col-xs-6 col-sm-3 col-md-5"></span>
                </div>

                <div class="row ">

                    <label for="pass2" class="col-sm-3 col-md-3">Confirm password</label>
                    <input id="pass2" name="pass2" type="text" class="col-xs-3 col-sm-3 col-md-3">
                    <span id="pass2Info" class="col-xs-6 col-sm-3 col-md-5"></span>

                </div>


                <div class="row"> 

                    <input type="submit"  id="send" name="send"  align="center" class="col-xs-3 col-sm-11  btn btn-primary btn-lg boton" value="Submit">

                </div>

            </form>

Second: link the style.css stylesheet

  <link rel="stylesheet" type="text/css" href="style.css">

Third: do not forget to add jQuery (1.5+) in the way that you prefer. For instance:

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>

Fourth: link bootstrap:
 
<link rel="stylesheet" href="css/bootstrap.min.css">
 
Fifth: link plugin.js:

 <script src="js/plugin.js"></script>

