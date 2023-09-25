<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">        
    <title>Quiz2</title>
    <style>
table{
    border: black 1px solid;
    border-collapse: collapse;
    width: 900px;
}

.box{
    padding: 20px;

}

th, td{
    padding: 15px;
	background-color: rgba(255,255,255,0.2);
    border: black 1px solid;
}


input{
    padding: 10px;
}

</style>

</head>
<body>

<h1>Student Marks</h1>
    <table>
    <thead>
        <tr class="box">
            <th>Student Number</th>
            <th>Full Name</th>
            <th>CA Mark (%)</th>
            <th>Exam Mark (%)</th>
            <th>Final Mark (%)</th>
            <th>Grade (%)</th>
        </tr>
    </thead>
    
    <tbody>
        <tr>
            <td>219377673</td>
            <td>William</td>
            <td><input type="number" id="ca-0"></td>
            <td><input type="number" id="exam-0"></td>
            <td id="final-0"></td>
            <td id="grade-0"></td>
        </tr>
        <tr>
            <td>220077670</td>
            <td>Simon</td>
            <td><input type="number" id="ca-1"></td>
            <td><input type="number" id="exam-1"></td>
            <td id="final-1"></td>
            <td id="grade-1"></td>
        </tr>
        <tr>
            <td>201467453</td>
            <td>Steven</td>
            <td><input type="number" id="ca-2"></td>
            <td><input type="number" id="exam-2"></td>
            <td id="final-2"></td>
            <td id="grade-2"></td>
        </tr>
        <tr>
            <td>201778909</td>
            <td>Hellen</td>
            <td><input type="number" id="ca-3"></td>
            <td><input type="number" id="exam-3"></td>
            <td id="final-3"></td>
            <td id="grade-3"></td>
        </tr>
        <tr>
            <td>219956348</td>
            <td>Veronika</td>
            <td><input type="number" id="ca-4"></td>
            <td><input type="number" id="exam-4"></td>
            <td id="final-4"></td>
            <td id="grade-4"></td>
        </tr>
    </tbody>
   </table> 
   <table id="table">
    <thead>
        <tr class="box">
            <th>Student Number</th>
            <th>Full Name</th>
            <th>CA Mark (%)</th>
            <th>Exam Mark (%)</th>
            <th>Final Mark (%)</th>
            <th>Grade (%)</th>
        </tr>
    </thead>
    <tbody>
        
    </tbody>
   </table>
   <br>
   <button id="calcButton">Calculate Marks</button>
    <script type="text/javascript"></script>
</body>
</html>
