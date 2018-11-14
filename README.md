# w0409355

.headerStyle{
    background-color: black;
    text-align: center;
    height: 50px;
}
.headerDiv{
    color: deepskyblue;
    font-size: 30px;
}

.nameDiv{
    float: left;
}

.navDiv{
    float: right;
    width: 70%;
}

.navLi{
    width: 20%;
    font-size: large;
    float: right;
}
.navOptions{
    list-style-type: none;
    margin: 0;
    padding-top: 10px;
    overflow: hidden;
}

li a {
    display: block;
    color: black;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}
li {
    float: left;
}

li a:hover {
    background-color: lightgreen;
}

.commonHeaders{
    height: 70px;
    margin-top: 5px;
    margin-bottom: 10px;
    background: linear-gradient(to left,deepskyblue 1%,#e7eaec 99%);
    box-shadow: 5px 5px 2px #888888;
    animation-name: headerAnimation;
    animation-duration: 4s;
}

.formInputs{
    width: 60%;
    margin-top: 20px;
    margin-left: 30px;
}

.legend{
    color: red;
    font-weight: bold;
    animation-name: legendAnimation;
    animation-duration: 4s;
}

.button{
    background-color: red;
}

input,textarea,select{
    animation-name: inputAnimation;
    animation-duration: 4s;
}

.page-footer{
    background-color: deepskyblue;
    height: 50px;
    padding-top: 15px;
    animation-name: footerAnimation;
    animation-duration: 4s;
}

@keyframes headerAnimation {
    0%   {background: linear-gradient(to left,deepskyblue 1%,#e7eaec 99%);}
    25%  {background: linear-gradient(to left,yellow 1%,#e7eaec 99%);}
    50%  {background: linear-gradient(to left,blue 1%,#e7eaec 99%);}
    100% {background: linear-gradient(to left,green 1%,#e7eaec 99%);}
}
@keyframes legendAnimation {
    0%   {color: red;}
    25%  {color: yellow;}
    50%  {color: blue;}
    100% {color: green;}
}
@keyframes inputAnimation {
    0%   {border: 1px solid red;}
    25%  {border: 1px solid yellow;}
    50%  {border: 1px solid blue;}
    100% {border: 1px solid green;}
}

@keyframes footerAnimation {
    0%   {background-color: red;}
    25%  {background-color: yellow;}
    50%  {background-color: blue;}
    100% {background-color: green;}
}


