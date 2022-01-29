# Assigment-of-floxus
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AssignmentOfFloxus</title>
    <style>
        body {
            font-weight: bold;
        }
    </style>

</head>

<body>
    <pre>
    <h2> 1. to find the table with id = "age-table" :- </h2>

        i. let table = document.getElementById(`age-table`);
        ii. let table = document.querySelector(`#age-table`);

    <h2>2. to find all the label elements :- </h2>

        i. let labels = document.getElementsByName(`label`); 
           this gives us the HTML collection of all labels. to access 
           individual we can use the labels[i] where i is the index 
           of the label element which we want to access.
        ii. let labels = document.querySelectorAll(`label`);
           this gives us the NodeList of all labels. to access 
           individual we can use the labels[i] where i is the index 
           of the label element which we want to access.

    <h2>3. to find the first td in that table with the word "age" :-</h2>    
        
        i. let td = document.getElementsByTagName(`td`);
            this gives us the HTML collection of all td. to access 
            first we can use the td[0].
        ii. let td = document.querySelectorAll(`td`);
            this gives us the NodeList of all td. to access 
            first we can use the td[0].

    <h2>4. to find the form with name = "search"</h2>        

        i. let ele = document.getElementsByName(`search`);
            this gives us the NodeList of all Elements with name "search". to access 
            form we can use the ele[0]. because form with name "search" is the first
            element of ele.

    <h2>5. to find the first and last input in that form</h2>
    
        i. let x = document.getElementsByTagName(`input`);
            This gives us the HTML collection of all the inputs present
            in the DOM and as we know that the form with name "search" has two 
            inputs. So if we want to access the first input we can use x[0] 
            because the first input of the DOM and the first input of form with
            name 'search' is same.
                And to find the last input of the DOM we can use x[x.length - 1]
                where x.length is the length of the HTML collection of all the inputs.
                so x.length - 1 will be the index of last input.
            And if want the last input of the form with name "search" we can use 
            x[1] because the last input of the form is the 2nd input of the DOM.
             
    </pre>
</body>

</html>
