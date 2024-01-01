# Ex-10-BOOTSTRAP
Name:HARINI.A
Registration number:212223040056
## Ex-10(a)
## AIM
Create a Responsive feedback form for a virtual workshop on Constructing Modern Websites built with Bootstrap.

## DESIGN STEPS: 10(a)
## Step 1:
     Initialize the HTML document

## Step 2:
     Create the body structure

## Step 3:
     Construct the form

## Step 4:
      Add a submit button and Link Bootstrap JavaScript.

## CODE: 10(a)
'''

'''
```
<!DOCTYPE html>
<html>
<head>
    <title>Feedback Form</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <h2 class="mt-5">Workshop Feedback Form</h2>
        <form>
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" class="form-control" id="name" placeholder="Enter your name" name="name">
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" class="form-control" id="email" placeholder="Enter your email" name="email">
            </div>
            
        
            <div class="form-group">
                <label for="feedback">Feedback:</label>
                <textarea class="form-control" id="feedback" placeholder="Enter your feedback" name="feedback"></textarea>
            </div>
            <div class="rating-details">
              <span class="rate-title">Rating :</span>
              <br>
           
              <input type="radio" name="rate" id="dot-1">
              &nbsp;&nbsp;
              <input type="radio" name="rate" id="dot-2">
              &nbsp;&nbsp;
              <input type="radio" name="rate" id="dot-3">
              &nbsp;&nbsp;
              <input type="radio" name="rate" id="dot-4">
              &nbsp;&nbsp;
              <input type="radio" name="rate" id="dot-5">
              
              
              <div class="category">
                <label for="dot-1">
                <span class="dot one"></span>
                <span class="rate">1</span>
              </label>
              &nbsp; &nbsp;
              <label for="dot-2">
                <span class="dot two"></span>
                <span class="rate">2</span>
              </label>
              &nbsp; &nbsp;
              <label for="dot-3">
                <span class="dot three"></span>
                <span class="rate">3</span>
                </label>
                &nbsp; &nbsp;
              <label for="dot-4">
                <span class="dot four"></span>
                <span class="rate">4</span>
                </label>
                &nbsp; &nbsp;
              <label for="dot-5">
                <span class="dot five"></span>
                <span class="rate">5</span>
                </label>
              </div>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
 </body>
</html>
```

## OUTPUT:10(a):
![Screenshot 2024-01-01 172818](https://github.com/NiranjaniC/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145742800/ed185508-f84d-49c9-9f0d-b1f5326fb2f1)


## RESULT:
  This code creates a responsive feedback form for a virtual workshop on constructing modern websites built with Bootstrap.

## Ex-10(b)
## AIM
Create a Responsive student registration form for ABC Engineering College built with Bootstrap.

## DESIGN STEPS: 10(b)
## Step 1:
     Initialize the HTML document with the necessary Bootstrap links.

## Step 2:
     Create a container for the form and add a heading.

## Step 3:
     Inside the form, create form groups for the student’s name, email, and course.

## Step 4:
     Add a submit button for the form.

## Step 5:
     Link the Bootstrap JavaScript file at the end of the body.

## CODE: 10(b)
'''

'''
```
<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <h2 class="mt-5">ABC Engineering College - Student Registration</h2>
        <form>
            
            <div class="form-group">
              <label for="firstName">First Name:</label>
              <input type="text" class="form-control" id="firstName" name="firstName" required>
            </div>
    
            <div class="form-group">
              <label for="lastName">Last Name:</label>
              <input type="text" class="form-control" id="lastName" name="lastName" required>
            </div>
    
            <div class="form-group">
              <label for="dob">Date of Birth:</label>
              <input type="date" class="form-control" id="dob" name="dob" required>
            </div>
    
            
            <div class="form-group">
              <label for="email">Email:</label>
              <input type="email" class="form-control" id="email" name="email" required>
            </div>
    
            <div class="form-group">
              <label for="phone">Phone Number:</label>
              <input type="tel" class="form-control" id="phone" name="phone" required>
            </div>
            

            <div class="form-group">
                <label for="course">Course:</label>
                <input type="text" class="form-control" id="course" placeholder="Enter your course" name="course">
            </div>

            <div class="gender-details">

              <span class="gender-title">Gender:</span>

              
              <div class="category">
                <label for="dot-1">
                <span class="dot one"></span>
                <span class="gender">Male</span>
                <input type="radio" name="gender" id="dot-1">
              </label>
    
              <label for="dot-2">
                <span class="dot two"></span>
                <span class="gender">Female</span>
                <input type="radio" name="gender" id="dot-2">
              </label>
              </div>
            </div>
            <br>
            <button type="submit" class="btn btn-primary">Register</button>
        </form>
    </div>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:10(b):
![Screenshot 2024-01-01 172928](https://github.com/NiranjaniC/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145742800/294d2e18-2516-486e-bd04-3e36d8d40265)



## RESULT:
This code creates a Responsive student registration form for ABC Engineering College built with Bootstrap.

## Ex-10(c)
## AIM
Develop a program to structure vertical form layouts which handle form validation in bootstrap.

## DESIGN STEPS: 10(c)
## Step 1:
    Initialize the HTML document with the necessary Bootstrap links.

## Step 2:
    Create a container for the form and add a heading.

## Step 3:
    Inside the form, create a form group for the name input field. Add the required attribute to the input field for validation.

## Step 4:
    Add a submit button for the form.

## Step 5:
    Add a script to handle the form validation on submit.

## CODE: 10(c)
'''

'''
```
<!DOCTYPE html>
<html>
<head>
    <title>Form Validation</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <h2 class="mt-5">Form with Validation</h2>
        <form class="needs-validation" novalidate>
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" class="form-control" id="name" placeholder="Enter your name" name="name" required>
                <div class="invalid-feedback">Please enter your name.</div>
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email address</label>
                <input type="email" class="form-control" id="email" name="email" required>
              </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <script>
    (function() {
        'use strict';
        window.addEventListener('load', function() {
            var forms = document.getElementsByClassName('needs-validation');
            var validation = Array.prototype.filter.call(forms, function(form) {
                form.addEventListener('submit', function(event) {
                    if (form.checkValidity() === false) {
                        event.preventDefault();
                        event.stopPropagation();
                    }
                    form.classList.add('was-validated');
                }, false);
            });
        }, false);
    })();
    </script>
</body>
</html>

```
## OUTPUT:10(c):
![Screenshot 2024-01-01 173041](https://github.com/NiranjaniC/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145742800/589309ef-28f5-46f1-bd77-c3c225608afa)



## RESULT:
This code develops a program to structure vertical form layouts which handle form validation in bootstrap.

## Ex-10(d)
## AIM
Create a basic email login form in Bootstrap with validation function.

## DESIGN STEPS: 10(d)
## Step 1:
    Initialize the HTML document with the necessary Bootstrap links.

## Step 2:
    Create a container for the form and add a heading.

## Step 3:
    Inside the form, create a form group for the email input field. Add the required attribute to the input field for validation.

## Step 4:
    Add a submit button for the form.

## Step 5:
Add a script to handle the form validation on submit.

## CODE: 10(d)
'''

'''
```
<!DOCTYPE html>
<html>
<head>
    <title>Login Form</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <h2 class="mt-5">Login Form</h2>
        <form class="needs-validation" novalidate>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" class="form-control" id="email" placeholder="Enter your email" name="email" required>
                <div class="invalid-feedback">Please enter a valid email.</div>
            </div>
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" class="form-control" id="name" placeholder="Enter your name" name="name" required>
            </div>
            <button type="submit" class="btn btn-primary">Login</button>
        </form>
    </div>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <script>
    (function() {
        'use strict';
        window.addEventListener('load', function() {
            var forms = document.getElementsByClassName('needs-validation');
            var validation = Array.prototype.filter.call(forms, function(form) {
                form.addEventListener('submit', function(event) {
                    if (form.checkValidity() === false) {
                        event.preventDefault();
                        event.stopPropagation();
                    }
                    form.classList.add('was-validated');
                }, false);
            });
        }, false);
    })();
    </script>
</body>
</html>

```

## OUTPUT:10(d):
![Screenshot 2024-01-01 173127](https://github.com/NiranjaniC/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145742800/04990d84-bb3a-4eb7-8547-5a32f12fc697)



## RESULT:
This code creates a basic email login form in Bootstrap with validation function.
