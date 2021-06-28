<html>
    <head>
        <title>Date Time Vatidation</title>
    </head>
    <body>
        <form action="?php echo $_SERVER['PHP_SELF'] ?" method="GET">
        <p>Enter your name and select date and time for the appointment</p>
            <?php
                if(array_key_exists("date", $_GET)){
                    $name = $_GET["fname"];
                    $datee = $_GET["date"];
                    $month = $_GET["month"];
                    $year = $_GET["year"];
                    $hour = $_GET["hour"];
                    $minute = $_GET["minute"];
                    $second = $_GET["second"];
                    $maxdate = 31;
                }
                else{
                    $name = "";
                    $datee = 1;
                    $month = 1;
                    $year = 1;
                    $hour = 0;
                    $minute = 0;
                    $second = 0;
                }
                $maxdate = 31;
                switch($month){
                    case 4:
                    case 6:
                    case 11:
                    case 9:
                        $maxdate = 30;
                        break;
                    case 2:
                        $maxdate = 28;
                        if(($year % 4 == 0 && $year % 100) || $year % 400 == 0){
                            $maxdate = 29;
                        }
                        break;
                    default:
                        $maxdate = 31;
                        break;
                }
            ?>

            <table>
                <tr>
                    <td>Your name: </td>
                    <td colspan = 3><input type="text" name="fname" value="<?php echo $name; ?>"></td>
                </tr>
                <tr>
                    <td>Date:</td> 
                    <td><select name="date">
                        <?php
                            for($i=1; $i<=$maxdate; $i++){
                                if($datee == $i) print "<option selected>$i</option>";
                                // else if($datee > $maxdate){
                                //     // $datee = $maxdate;
                                //     print "<option selected>$maxdatee</option>";
                                // }
                                else print "<option>$i</option>";
                            }
                        ?>
                    </select>
                    </td>
                    <td><select name="month">
                        <?php
                            for($i=1; $i<=12; $i++){
                                if($month == $i) print "<option selected>$i</option>";
                                else print "<option>$i</option>";
                            }
                        ?>
                    </select>
                    <td><select name="year">
                        <?php
                            for($i=101; $i<=3000; $i++){
                                if($year == $i) print "<option selected>$i</option>";
                                else print "<option>$i</option>";
                            }
                        ?>
                    </select>
                </tr>
                <tr>
                    <td>Time:</td> 
                    <td><select name="hour">
                        <?php
                            for($i=0; $i<=23; $i++){
                                if($hour == $i) print "<option selected>$i</option>";
                                else print "<option>$i</option>";
                            }
                        ?>
                    </select>
                    </td>
                    <td><select name="minute">
                        <?php
                            for($i=0; $i<=59; $i++){
                                if($minute == $i) print "<option selected>$i</option>";
                                else print "<option>$i</option>";
                            }
                        ?>
                    </select>
                    <td><select name="second">
                        <?php
                            for($i=0; $i<=59; $i++){
                                if($second == $i) print "<option selected>$i</option>";
                                else print "<option>$i</option>";
                            }
                        ?>
                    </select>
                </tr>
                <tr>
                    <td align="right"><INPUT TYPE="SUBMIT" value="Submit"></td>
                    <td align="left"><INPUT TYPE="RESET" value="Reset"></td>
                </tr>
            </table>
            <?php
                if(array_key_exists("date", $_GET) > 0){
                    if($datee > $maxdate)
                    {
                        print "Hi ".$name."!"."<br>";
                        print "This month has $maxdate day!";
                    } 
                    else{
                        print "Hi ".$name."!"."<br>";
                        print "You have choose to have an appointment on ";
                        echo date("$hour:$minute:$second") . ", ";
                        echo date("$datee/$month/$year") . "<br><br>";
                        print "More information <br><br>";
                        $dateint = mktime($hour + 12, $minute, $second, $month, $datee, $year);
                        print "In 12 hours, the time and date is ";
                        echo date('H:i:s', $dateint).", ";
                        echo date('d/m/Y', $dateint)."<br>";
                        print "This month has $maxdate day!";
                    }
                }
            ?>
        </form>
</body>
</html>
