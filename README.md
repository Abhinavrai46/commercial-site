* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}

/* font-family: 'Dancing Script', cursive;*/
.nav1 {
    width: 100%;
    height: 50px;
    color: aliceblue;
    background: #222f3e;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.nav1 i {
    margin: 0 5px;
}

.nav1 a {
    text-decoration: none;
    color: white;
    padding: 5px 10px;
    background: #e67e22;
}

.nav2 {
    width: 100%;
    height: 60px;
    background: white;
    color: black;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0px 70px;
}

.menu a {
    text-decoration: none;
    color: black;
    padding: 10px 20px;

}

header {
    width: 100%;
    height: 100vh;
    background: linear-gradient(rgba(0, 0, 0, 0.7)85%,rgb(153, 245, 214,0.3)), url('bg.jpg');
    background-size: 100% 100%;
}

.text {
    max-width: 600px;
    color: white;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
}

.text h1 {
    font-size: 3em;
    font-family: 'Dancing Script', cursive;
}

.text span {
    color: aquamarine;
    font-family: 'Dancing Script', cursive;
}

.text p {
    font-size: 20px;
    margin: 40px 0;
    line-height: 30px;
}

.text a {
    text-decoration: none;
    color: white;
    background: #e67e22;
    padding: 10px 20px;
    margin: 0 15px;
}
