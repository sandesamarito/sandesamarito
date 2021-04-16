<!DOCTYPE html>
<html>
<head>
<style>
    html,body{
        text-align: center;
        background-image: url("D:\\Pictures\\WALLPAPER\\sea_coast_rocks_underwater_world_vegetation_fish_53966_1280x1024.jpg");
    }
.button {
    position: relative;
    background-color: #000000;
    border: 1em;
    font-size: 15px;
    color: #fcf6f6;
    padding: 15px;
    width: 150px;
    text-align: center;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    text-decoration: none;
    overflow: hidden;
    cursor: pointer;
    border-radius: 5%;
}

.button:after {
    content: "";
    background: #ece9e9;
    display: block;
    position: absolute;
    padding-top: 300%;
    padding-left: 350%;
    margin-left: -20px!important;
    margin-top: -120%;
    opacity: 0;
    transition: all 0.8s
}

.button:active:after {
    padding: 0;
    margin: 0;
    opacity: 1;
    transition: 0s
}
</style>
</head>
<body>
<button class="button">Iolite, Ke</button>
</body>
</html>
