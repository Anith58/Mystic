# Mystic

# Amazon Clone Login Page:

# Here html code :

<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
    <meta charset="utf-8">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
</head>

<body>

    <header>
        <!--Amazon Image Logo-->
        <div class="d-flex flex-row justify-content-center">
            <div class="row">
                <div class="col-md">
                    <img class="img_1" src="" alt="Amazon Logo" />
                </div>
                <!--Col 1 End-->
            </div>
            <!--Row 1 End-->
        </div>
        <!--Container End-->
        <!--Amazon Image Logo-->
    </header>


    <!--Form-->
    <div class="d-flex flex-row justify-content-center">
        <div class="row">
            <div class="col-md">
                <form>
                    <div class="sign-in">Sign In</div>
                    <div class="form-group">
                        <label id="words_1" for="exampleInputEmail1">Email(phone for mobile accounts)</label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
                        <small id="emailHelp" class="form-text text-muted"></small>
                    </div>
                    <div class="form-group">
                        <label id="words_2" for="exampleInputPassword1">Password &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp Forgot your password? </label>
                        <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
                        <div class="form-group">
                            <button type="button" class="btn btn-warning" id="sign-in">Sign In</button>
                            <input type="checkbox" class="form-check-input checkbox" id="exampleCheck1">
                            <p class="keep-sign-in">Keep me signed in. <a href="https://www.alphr.com/amazon-logging-me-out/#:~:text=Keep%20Me%20Signed%20In%20on%20Amazon&text=When%20you%20sign%20in%20to,on%20the%20log%20out%20button.">Details</a></p>

                        </div>
                    </div>
                    <div class="form-check">


                    </div>
                    <button type="button" class="btn btn-warning" id="grey-button">Create your Amazon account</button>

                </form>
            </div>
            <!--Col 1 End-->
        </div>
        <!--Row 1 End-->
    </div>
    <!--Container End-->
    <!--Form-->




    <div class="d-flex flex-row justify-content-center footer_1">
        <div class="row">
            <div class="col">
                <p class="conditions"><a>Conditions of Use &nbsp &nbsp &nbsp </a> <a>Privacy Notice&nbsp &nbsp &nbsp </a> <a>Help&nbsp &nbsp &nbsp </a></p>
            </div>
            <!--Footer Col 1 End-->
        </div>
        <!--Footer Row 1 End-->

    </div>


## Here im using css:
      .img_1 {
  height: 31px;
  width: 103px;
  margin-top: 20px;
  margin-bottom: 50px;
}

.extra-margin {
  margin-top: 200px;
}

.btn {
  width: 350px;
  margin-top: 20px;
}




form {
  border: 1px solid lightgrey;
  padding-left: 25px;
  padding-right: 25px;
  padding-top: 16px;
  padding-bottom: 25px;
  border-radius: 5px;
}

#words_1 {
  font-weight: bold;
  font-size: 14px;
}

#words_2 {
  font-weight: bold;
  font-size: 14px;
}
  
#words_3 {
  font: 7px;
}

.sign-in {
  margin-bottom: 50px;
  font-size: 30px;
  font-weight: bold;
}

.conditions {
  font-size: 8px;
  color: blue;
  margin-top: 30px;
  z-index: 2;
  
  
 
 
}

.footer_1 {
  width: max;
  height: 350px;
  background-color: #fff;
  margin-top: 30px;
  
}

#exampleCheck1 {
  margin-left: 3px;
  margin-top: 11px;
}

.keep-sign-in {
  margin-left: 24px;
  margin-top: 8px;
  font-size: 14px;
}

#sign-in {
  margin-bottom: 10px;
}

#grey-button {
  background-color: lightgrey;
  border: black;
    
  
}

    
 




## Deployment

To deploy this project run in vscode

```bash
git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin 

git push -u origin main

```


# Code Reference

For more reference :
https://codepen.io/kedric/pen/GwKJEb
