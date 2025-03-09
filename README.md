<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<!--     <link rel="stylesheet" href="style.css"> -->
<style>
  *{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
#outer{
    height: 600px;
    width: 600px;
    border: 1px solid black;
    margin: auto;
}
#upper{
    height: 250px;
    width: 600px;
}
#upper-left{
    height: 250px;
    width: 250px;   
    float: left;
    background-color: red;
}
#red1{
    height: 125px;
    width: 250px;
    margin-top: 10px;
}
.r1{
    height: 100px;
    width: 100px;
    border-radius: 250px;
    background-color: white;
    float: left;
    margin-left: 15px;
}
.r2{
    height: 100px;
    width: 100px;
    border-radius: 250px;
    background-color: white;
    float: left;
    margin-left: 15px;    
}

#upper-middle{
    height: 250px;
    width: 100px;
    float: left;
}
#row1{
    height: 250px;
    width: 30px;
    background-color: white;
    float: left;
}
.p3{
    height: 41.5px;
    width: 30px;
    border: 1px solid black;
    float: left;
}
#row2{
    height: 250px;
    width: 30px;
    background-color: green;
    float: left;

}
.p9{
    height: 41.5px;
    width: 41.5px;
    border: 1px solid black;
    float: left;
}
#row3{
    height: 250px;
    width: 30px;
    background-color: white;
    float: left;
}
.p4{
    height: 41.5px;
    width: 40px;
    border: 1px solid black;
    float: left;
}
#upper-right{
    height: 250px;
    width: 250px;
    background-color: green;
    float: left;
}
#green1{
    height: 125px;
    width: 250px;
    margin-top: 10px;
}
.g1{
    height: 100px;
    width: 100px;
    border-radius: 250px;
    background-color: white;
    float: left;
    margin-left: 15px;
}
.g2{
    height: 100px;
    width: 100px;
    border-radius: 250px;
    background-color: white;
    float: left;
    margin-left: 15px;    
}
#middle{
    height: 100px;
    width: 600px;
}
#middle-left{
    height: 100px;
    width: 250px;
    background-color: white;
    float: left;
}
#row7{
    height: 30px;
    width: 250px;
    background-color: white;
    float: left;
}
.p1{
    height: 31px;
    width: 41.65px;
    border: 1px solid black;
    float: left;
}
#row8{
    height: 30px;
    width: 250px;
    background-color: red;
    float: left;
}
.p10{
    height: 30px;
    width: 41.6px;
    border: 1px solid black;
    float: left;
}
#row9{
    height: 30px;
    width: 250px;
    background-color: white;
    float: left;
}
.p2{
    height: 40px;
    width: 41.6px;
    border: 1px solid black;
    float: left;
}
#middle-middle{
    height: 100px;
    width: 100px;
    /* border-radius: 600px; */
    background-color: yellowgreen;
    float: left;
    text-align: center;
}
p{
    text-align: center;
    margin-top: 40px;
}
#middle-right{
    height: 100px;
    width: 250px;
    background-color: white;
    float: left;
}
#row10{
    height: 30px;
    width: 250px;
    background-color: white;
    float: left;
}
.p5{
    height: 30px;
    width: 41.6px;
    border: 1px solid black;
    float: left;
}
#row11{
    height: 30px;
    width: 250px;
    background-color: blue;
    float: left;

}
.p12{
    height: 30px;
    width: 41.6px;
    border: 1px solid black;
    float: left;
}
#row12{
    height: 30px;
    width: 250px;
    background-color: white;
    float: left;
}
.p6{
    height: 40px;
    width: 41.6px;
    border: 1px solid black;
    float: left;
}
#lower{
    height: 250px;
    width: 600px;
}
#lower-left{
    height: 250px;
    width: 250px;   
    float: left;
    background-color: yellow;
}
#yellow1{
    height: 125px;
    width: 250px;
    margin-top: 10px;
}
.y1{
    height: 100px;
    width: 100px;
    border-radius: 250px;
    background-color: white;
    float: left;
    margin-left: 15px;
}
.y2{
    height: 100px;
    width: 100px;
    border-radius: 250px;
    background-color: white;
    float: left;
    margin-left: 15px;    
}
#lower-middle{
    height: 250px;
    width: 100px;
    float: left;
}
#row4{
    height: 250px;
    width: 30px;
    background-color: white;
    float: left;
}
.p7{
    height: 41.5px;
    width: 30px;
    border: 1px solid black;
    float: left;
}
#row5{
    height: 250px;
    width: 30px;
    background-color: yellow;
    float: left;

}
.p11{
    height: 41.5px;
    width: 30px;
    border: 1px solid black;
    float: left;
}
#row6{
    height: 250px;
    width: 30px;
    background-color: white;
    float: left;
}
.p8{
    height: 41.5px;
    width: 40px;
    border: 1px solid black;
    float: left;
}
#lower-right{
    height: 250px;
    width: 250px;
    background-color: blue;
    float: left;
}
#blue1{
    height: 125px;
    width: 250px;
    margin-top: 10px;
}
.b1{
    height: 100px;
    width: 100px;
    border-radius: 250px;
    background-color: white;
    float: left;
    margin-left: 15px;
}
.b2{
    height: 100px;
    width: 100px;
    border-radius: 250px;
    background-color: white;
    float: left;
    margin-left: 15px;    
}
</style>  
</head>
<body>
    <div id="outer">
        <div id="upper">
            <!-- red part -->
            <div id="upper-left">
                <div id="red1">
                    <div class="r1"></div>
                    <div class="r1"></div>
                </div>
                <div id="red2">
                    <div class="r2"></div>
                    <div class="r2"></div>
                </div>
            </div>
            <div id="upper-middle">
                <div id="row1">
                    <div class="p3"></div>
                    <div class="p3"></div>
                    <div class="p3"></div>
                    <div class="p3"></div>
                    <div class="p3"></div>
                    <div class="p3"></div>
                </div>
                <div id="row2">
                    <div class="p9" style="background-color: white;"></div>
                    <div class="p9"></div>
                    <div class="p9"></div>
                    <div class="p9"></div>
                    <div class="p9"></div>
                    <div class="p9"></div>
                </div>
                <div id="row3">
                    <div class="p4"></div>
                    <div class="p4" style="background-color: green;"></div>
                    <div class="p4"></div>
                    <div class="p4"></div>
                    <div class="p4"></div>
                    <div class="p4"></div>
                </div>
            </div>
            <!-- green part -->
            <div id="upper-right">
                <div id="green1">
                    <div class="g1"></div>
                    <div class="g1"></div>
                </div>
                <div id="green2">
                    <div class="g2"></div>
                    <div class="g2"></div>
                </div>
            </div>
        </div>
        <div id="middle">
            <div id="middle-left">
                <div id="row7">
                    <div class="p1"></div>
                    <div class="p1" style="background-color: red;"></div>
                    <div class="p1"></div>
                    <div class="p1"></div>
                    <div class="p1"></div>
                    <div class="p1"></div>
                </div>
                <div id="row8">
                    <div class="p10" style="background-color: white;"></div>
                    <div class="p10"></div>
                    <div class="p10"></div>
                    <div class="p10"></div>
                    <div class="p10"></div>
                    <div class="p10"></div>
                </div>
                <div id="row9">
                    <div class="p2"></div>
                    <div class="p2"></div>
                    <div class="p2"></div>
                    <div class="p2"></div>
                    <div class="p2"></div>
                    <div class="p2"></div>
                </div>
            </div>
            <div id="middle-middle"><p>WINNER</p></div>
            <div id="middle-right">
                <div id="row10">
                    <div class="p5"></div>
                    <div class="p5"></div>
                    <div class="p5"></div>
                    <div class="p5"></div>
                    <div class="p5"></div>
                    <div class="p5"></div>
                </div>
                <div id="row11">
                    <div class="p12"></div>
                    <div class="p12"></div>
                    <div class="p12"></div>
                    <div class="p12"></div>
                    <div class="p12"></div>
                    <div class="p12"  style="background-color: white;"></div>
                </div>
                <div id="row12">
                    <div class="p6"></div>
                    <div class="p6"></div>
                    <div class="p6"></div>
                    <div class="p6"></div>
                    <div class="p6" style="background-color: blue;"></div>
                    <div class="p6"></div>
                </div>
            </div>
        </div>
        <div id="lower">
            <!-- yellow part -->
            <div id="lower-left">
                <div id="yellow1">
                    <div class="y1"></div>
                    <div class="y1"></div>
                </div>
                <div id="yellow2">
                    <div class="y2"></div>
                    <div class="y2"></div>
                </div>
            </div>
            <div id="lower-middle">
                <div id="row4">
                    <div class="p7"></div>
                    <div class="p7"></div>
                    <div class="p7"></div>
                    <div class="p7"></div>
                    <div class="p7" style="background-color: yellow;"></div>
                    <div class="p7"></div>
                </div>
                <div id="row5">
                    <div class="p11"></div>
                    <div class="p11"></div>
                    <div class="p11"></div>
                    <div class="p11"></div>
                    <div class="p11"></div>
                    <div class="p11" style="background-color: white;"></div>
                </div>
                <div id="row6">
                    <div class="p8"></div>
                    <div class="p8"></div>
                    <div class="p8"></div>
                    <div class="p8"></div>
                    <div class="p8"></div>
                    <div class="p8"></div>
                </div>
            </div>
            <!-- blue part -->
            <div id="lower-right">
                <div id="blue1">
                    <div class="b1"></div>
                    <div class="b1"></div>
                </div>
                <div id="blue2">
                    <div class="b2"></div>
                    <div class="b2"></div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
