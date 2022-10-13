.container-center{
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: black;
}

.login{
    z-index: 1001 !important;
    color: white;
    width: 30%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    border-radius: 20px;
    position: absolute;
    margin-bottom: 15em;
}
/*
.login .nav{
    padding: 15px;
    margin-right: 15em;
    height: 10em;
    width: 75vw;
    display: flex;
    flex-direction: row;
    position: absolute;
    color: white;
    bottom: 39.5em;
}

.login .nav h1{
    font-size: 45px;
}
.login .nav h3{
    font-size: 30px;
    font-weight: 600;
    position: relative;
    top: 1.5em;
    right: 4.5em;
}

.login .nav img{
    position: relative;
    bottom: 0.5em;
    right: 1.9em;
}*/
 
.login-logo img{
    width: 100%;
    padding: 5px;
    padding-bottom: 0%;
}

.login input{
    margin-bottom: 1em;
    height: 50px;
    border: 0;
    border-radius: 15px;
    padding: 10px;
    font-size: 20px;
    background-color: white;
}

form{
    z-index: 1001 !important;
    margin-top: 1em;
    width: 100%;
    display: flex;
    flex-direction: column;
}

form h1{
    text-align: center;
    margin-bottom: 0.5em;
    color: white;
}

form .input{
    display: flex;
    flex-direction: row;
    align-items: baseline;
}
form .input a{
    z-index: 1001 !important;
    border: 0;
    background-color: #222;
    width: 0;
}
form .input .icon{
    position: relative;
    right: 2em;
    font-size: 25px;
    top: 5px;
    color: white;
    cursor: pointer;
}
form .input .icon :nth-child(1):hover{
    color: #3cb62c;
}

form .email-label{
    padding: 10px;
    font-size: 20px;
    transition: color 0.4s linear;
}

form .inputEmail {
    box-shadow: 0px 0px 25px 1px transparent;
    transition:  box-shadow 0.4s linear, border-color 0.4s linear;
    outline: none;
    padding: 15px;
    color: white;
    border: 2px solid #3cb62c;
    background-color : #222;
    width: 100%;
}

form .inputEmail:focus {
    box-shadow: 0px 0px 25px 1px #3cb62c;
    color: #3cb62c;
}

form .password-label {
    padding: 10px;
    font-size: 20px;
    transition: color 0.4s linear;
}

form .inputPassword {
    box-shadow: 0px 0px 25px 1px transparent;
    transition:  box-shadow 0.4s linear, border-color 0.4s linear;
    outline: none;
    padding: 15px;
    color: white;
    border: 2px solid #3cb62c;
    background-color : #222;
    width: 100%;
}
form .inputPassword::placeholder{
    position: relative;
    top: 3px;
}

form .inputPassword:focus {
    box-shadow: 0px 0px 25px 1px #3cb62c;
    color: #3cb62c;
}

form .viewPassword-Container{
    position: relative;
    align-self: end;
    bottom: 5em;
}

form .viewPassword-Container .viewPassword{
    border: 0;
    color: white;
    background-color: transparent;
}

form button{
    margin-top: 0.5em;
    justify-content: center;
    text-align: center;
    height: 50px;
    width: 100%;
    border: 0;
    border-radius: 15px;
    background-color: #3cb62c;
    color: white;
    font-size: 30px;
    transition: 0.2s ease-in-out;
}

form button:hover{
    transform: scale(102%);
    background-color: #3cb62c;
    box-shadow: 0px 0px 25px 1px #3cb62c;
}

.container-waves .waves {
    position: relative;
    min-width: 100vw;
    top: 30.8vh;
    bottom: 0%;
    }
    
    .parallax > use {
    animation: move-forever 25s cubic-bezier(.45,.5,.45,.5) infinite;
    }
    .parallax > use:nth-child(1) {
    animation-delay: -2s;
    animation-duration: 7s;
    }
    .parallax > use:nth-child(2) {
    animation-delay: -3s;
    animation-duration: 10s;
    }
    .parallax > use:nth-child(3) {
    animation-delay: -4s;
    animation-duration: 13s;
    }
    .parallax > use:nth-child(4) {
    animation-delay: -5s;
    animation-duration: 16s;
    }


@keyframes move-forever {
    0% {
    transform: translate3d(-90px,0,0);
    }
    100% {
    transform: translate3d(85px,0,0);
    }
}