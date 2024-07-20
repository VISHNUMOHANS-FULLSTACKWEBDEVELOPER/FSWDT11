# FSWDT11
DAY11
<!DOCTYPE html>
<html>
    <head>
        <title>Flex box Animations and Media queries</title>
        <link rel="stylesheet" href="./day11.css"/>
    </head>
    <body>
        <!-- <h3>Flex box</h3> -->
        <!-- Flex box are mainly used for creating layouts they are mainly 1d layout -->
         <!-- horizonal:justify-content
          vertical:align-items
          gap-10px
          flex direction:row/column
          flex-wrap:wrap(dynamic feature) -->

        <!-- <div class="parent">
            <div class="child">1</div>
            <div class="child">2</div>
            <div class="child">3</div>
            <div class="child">4</div>
            <div class="child">5</div>
            <div class="child">6</div>
            <div class="child">7</div>
            <div class="child">8</div>
            <div class="demo">hello</div>
        </div> -->

        <button>Click Me</button>
        
    </body>
</html>
/* /* .parent{
    /* height: 1150px; */
    /* background-color: blue;
    display: flex;
    flex-direction: centre;
    /* flex-direction: column-reverse; */
    /* flex-direction: row-reverse; */
    /* gap: 10px;
    /* flex-start,flex-end,center,space-around,space-between,space-evenly */
    /* justify-content: center;
    /* flex-start,flex-end,center,stretch */
    /* align-items: center;
    flex-wrap: wrap; */ 
/* }  */
/* .child{
    background-color: blueviolet;
     height: 100px;
    width: 100px; 
    border: 2px solid black; 
    justify-content: center;
} */
/* .demo{
    background-color: brown;
     flex: 1;
} */ 
 button{
    background-color: black;
    color: white;
    padding: 10px;
    margin: 20px;
    font-size: 20px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    /* Transition properties */
    /* transition-duration: 300ms;
    transition-delay: 500ms;
    transition-property: background-color;
    /* ease-in,ease-out,ease,linear, */
    /* transition-timing-function: cubic-bezier(0, 1.03, 0, 0.36); */ 
    transition: all cubic-bezier(0, 1.03, 0, 0.36) 300ms 500ms ;
 }
 button:hover{
    background-color: aqua;
    color: black;
    cursor: pointer;
 }
