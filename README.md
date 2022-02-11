<svg fill="none" viewBox="0 0 300 120" width="300" height="120" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
}
body{
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    background-color: #0d1117;
}
.wrapper{
    display: inline-flex;
}
.static-text{
    color:white;
    font-size: 60px;
    font-weight:400px ;
}
.dynamic-text{
    color: #FC6D6D;
    font-size: 60px;
    font-weight: 400px;
    position: relative;
}

.dynamic-text::after{
    content: "";
    position: absolute;
    left: 0;
    height: 100%;
    width: 100%;
    border-left: 2px solid #FC6D6D ;
    animation: typing 4s steps(30) infinite;
    background-color: #0d1117;
}
@keyframes typing{
    100%{
        left: 100%;
        margin: 0 -35px 0 35px;
    }
}

</style>
    <div class="wrapper">
        <div class="static-text">console.log</div>
        <span class="dynamic-text">("Hi there, I'm Tarik!"). . .</span>
    </div>


      

    </div>
  </foreignObject>
</svg>
