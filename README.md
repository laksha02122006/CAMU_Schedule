# Ex08 CAMU Schedule using Bootstrap
## Date: 28\05\2026
# Name: V.B.Laksha
# Reg.no: 212224220051

## AIM:
To design a responsive and visually appealing CAMU Schedule using Bootstrap.

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Add the Bootstrap CDN link inside the ```<head>``` section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CAMU Timetable</title>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap 3 -->
    <link rel="stylesheet"
    href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

    <style>

        body{
            background-color: #d9f3f7;
            font-family: Arial, sans-serif;
        }

        .top-date{
            margin-top: 20px;
            margin-bottom: 20px;
        }

        .panel{
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
        }

        .list-group-item{
            border: none !important;
            border-bottom: 1px solid #eeeeee !important;
            padding: 18px;
        }

        .subject{
            color: #007bff;
            font-weight: bold;
            font-size: 16px;
        }

        .time{
            color: gray;
            margin-top: 5px;
        }

        .room{
            color: #666;
        }

        .attendance{
            color: green;
            font-weight: bold;
        }

        .footer{
            text-align: center;
            margin-top: 20px;
            font-size: 16px;
            color: #004085;
            font-weight: bold;
        }

    </style>

</head>

<body>

<div class="container">

    <div class="row text-center top-date">

        <div class="col-xs-12">

            <h4>

                <span class="glyphicon glyphicon-chevron-left text-primary"></span>

                &nbsp; 28 Mar 2026 &nbsp;

                <span class="glyphicon glyphicon-chevron-right text-primary"></span>

            </h4>

            <hr style="width:120px;border-top:2px solid #337ab7;">

        </div>

    </div>

    <div class="panel panel-default">

        <div class="panel-body">

            <div class="list-group">

                <div class="list-group-item">

                    <div class="subject">
                        Fundamentals of Web Application Development
                        (19AI414) (5452)
                    </div>

                    <div class="time">
                        10:00 AM - 11:00 AM (60 min) | BERLIN MAGTHALIN R 
                    </div>

                    <div class="room">
                        Room No : 5452
                    </div>

                    <div class="attendance">
                        Attendance Recorded
                    </div>

                </div>

                <div class="list-group-item">

                    <div class="subject">
                        Fundamentals of Web Application Development
                        (19AI414) (5452)
                    </div>

                    <div class="time">
                        11:00 AM - 12:00 PM (60 min) | BERLIN MAGTHALIN R 
                    </div>

                    <div class="room">
                        Room No : 5452
                    </div>

                </div>

                <!-- Subject 3 -->

                <div class="list-group-item">

                    <div class="subject">
                        Database Management System and its Applications
                        (19CS404) (2331)
                    </div>

                    <div class="time">
                        1:00 PM - 2:00 PM (60 min) | DAVID A
                    </div>

                    <div class="room">
                        Room No : 2331
                    </div>

                </div>

                <div class="list-group-item">

                    <div class="subject">
                        Database Management System and its Applications
                        (19CS404) (2331)
                    </div>

                    <div class="time">
                        2:00 PM - 3:00 PM (60 min) | DAVID A
                    </div>

                    <div class="room">
                        Room No : 2331
                    </div>

                </div>

            </div>

        </div>

    </div>

    <div class="footer">
        Created By V.B.Laksha
    </div>

</div>

</body>
</html>
```

## OUTPUT:
<img width="1919" height="1140" alt="Screenshot 2026-05-28 230016" src="https://github.com/user-attachments/assets/06e1eb50-733c-4b9a-b859-1f1cf8b71709" />


## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
