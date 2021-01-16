# html
//Time Table of the school//



<html>
    <head>
        <title>table</title>
    </head>

    <body>
        <style>
            table,th,td{
                border:2px solid royalblue;
                border-collapse: collapse;
            }
            th,td{
                padding:10;
            }
            td{
                color:blueviolet;
                font-family:'Courier New', Courier, monospace;
            }
            th{
                color: green;
            }
        </style>
        <table>
             <tr style="text-align: center;">
                 <th colspan="6">Time Tabe</th>
             </tr>
             <tr>
               <th rowspan="6">Hours</th>
               <th>Mon</th>
               <th>Tue</th>
               <th>wed</th>
               <th>thu</th>
               <th>Fri</th>  
             </tr>
             <tr>
                 <td>Science</td>
                 <td>Maths</td>
                 <td>science</td>
                 <td>Maths</td>
                 <td>Arts</td>
             </tr>
             <tr>
                <td>Social</td>
                <td>History</td>
                <td>English</td>
                <td>Social</td>
                <td>Sports</td>
             </tr>
             <tr>
                <th colspan="5">Lunch</th>
            </tr>
            <tr>
                <td>Science</td>
                <td>Maths</td>
                <td>Science</td>
                <td>Maths</td>
                <td rowspan="2">Project</td>
            </tr>
            <tr>
                <td>Social</td>
                <td>History</td>
                <td>English</td>
                <td>Social</td>
            </tr>
        </table>
    </body>
    </html>
