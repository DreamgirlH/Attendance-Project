# Attendance-Project
Attendance list sample
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css" />
    <title>Students</title>

</head>

<body>
    <h1>Students</h1>
    <input type="text" id="filterInput" placeholder="Search 
    names...">
    <ul id="names" class="collection.with-header">
        <li class="collection-header">
            <h5>A</h5>
        </li>
        <li class="collection items">
            <a href="#">Amna</a>
        </li>
        <li class="collection items">
            <a href="#">Aliza</a>
        </li>
        <li class="collection items">
            <a href="#">Affira</a>
        </li>
        <li class="collection items">
            <a href="#">Aimon</a>
        </li>
        <li class="collection items">
            <a href="#">Anum</a>
        </li>
        <li class="collection items">
            <a href="#">Ammara</a>
        </li>

        <li class="collection-header">
            <h5>B</h5>
        </li>
        <li class="collection items">
            <a href="#">Bushra</a>
        </li>

        <li class="collection-header">
            <h5>E</h5>
        </li>

        <li class="collection items">
            <a href="#">Eesha</a>
        </li>

        <li class="collection-header">
            <h5>F</h5>
        </li>
        <li class="collection items">
            <a href="#">Farzana</a>
        </li>
        <li class="collection items">
            <a href="#">Faina</a>
        </li>

        <li class="collection-header">
            <h5>H</h5>
        </li>
        <li class="collection items">
            <a href="#">Habiba</a>
        </li>
        <li class="collection items">
            <a href="#">Harmain</a>
        </li>
        <li class="collection items">
            <a href="#">Hurain</a>
        </li>
        <li class="collection items">
            <a href="#">Hania </a>
        </li>

        <li class="collection-header">
            <h5>L</h5>
        </li>
        <li class="collection items">
            <a href="#">Laraib</a>
        </li>
        <li class="collection items">
            <a href="#">Laiba</a>
        </li>

        <li class="collection-header">
            <h5>N</h5>
        </li>

        <li class="collection items">
            <a href="#">Noor Saba</a>
        </li>

        <li class="collection-header">
            <h5>Q</h5>
        </li>
        <li class="collection items">
            <a href="#">Quratullainr</a>
        <li class="collection-header">
            <h5>R</h5>
        </li>
        <li class="collection items">
            <a href="#"> Ramla</a>
        </li>

        <li class="collection-header">
            <h5>S</h5>
        </li>
        <li class="collection items">
            <a href="#"> Sara</a>
        </li>
    </ul>
    </div>

    <script>
        //get input element
        let filterInput = document.getElementById('filterInput');
        console.log('hye');
        //add events listner
       let filterInput.addEventListner('keyup'), () => {
            console.log('yesss');
            //get value of input
            let filterValue =
                document.getElementById("filterInput").value.toUpperCase();
            console.log('filterValue');
            //get names ul
            let names = document.getElementById('names');
            //get its from ul
            let it = ul.querySelectorAll('li.collection-item');
            // loop through collection items its
            for (let i = 0; i < li.length; i++) {
                let a = li[i].getElementByTagName('a')[0];
                //if matched
                if (a.innerHtml.touppercase().indexOf(filterValue) > -1) {
                    li[i].style.display = '';


                } else {
                    li[i].style.display = 'none';

                }
            }
        })

    </script>


</body>

</html>
