@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@500&display=swap');
*{
margin: 0;
padding: 0;
box-sizing: border-box;
scroll-behavior: smooth;
}
:root{
--nav:whitesmoke;
--nav-text:maroon;
--white:aliceblue;
--faint-text:rgb(110, 109, 109);
--nav-hover:rgb(37, 36, 36);
--mobile-nav:black;
--paragraph-text:rgb(163, 112, 112);
}

body{
font-family: "Helvetica Neue",Helvetica,Arial,
sans-serif;

}

nav{
display:flex;
justify-content: space-between;
background: whitesmoke;
padding: 1rem;
position: fixed;
width: 100%;
}
h1 {
background: var(--nav-text);


}
h2, h4{
font-family: 'Rubik', sans-serif;
color: var(--nav-text);
font-size: 2rem;
}
p{
color: rgb(163, 112, 112);
font-size: 1.1rem;
line-height: 1.8rem;
}
ul{
display: flex;
flex-direction: row;
gap: 2rem;
align-items: center;
margin-right: 0.5rem;
    
}
ul li{ 
list-style: none;

}
a{
color: aliceblue;
text-decoration: none;
}
ul li a{
color: maroon;
font-weight: 600;
}

.mobile{
display: none;
}
.logo {
border-radius: 10px;
padding: 0.4rem 1rem;
margin-left: 0.6rem;
margin-top: 0.2rem;
position: static;

}
.bar{
display: none;
}
.num a{
color: aliceblue;
background: maroon;
padding: 0.3rem;

}
img {
object-fit: cover;
}
.good-food{
background: url('./images/proto2.png');
background-size: cover;
display: flex;


}
.good-food-div{
margin: 10rem 1rem 10rem 2rem;
}
.header1{
width: 45%;
font-size: 3rem;
color:var(--nav-text);
padding-bottom: 2rem;
}
.paragraph1{
width:45% ;
color: rgb(163, 112, 112);
font-size: 1.1rem;
padding-bottom: 2rem;
}
.order{
padding: 0.9rem 1.6rem;
background: var(--nav-text);
color: aliceblue;
font-weight: bold;
border: 1px solid var(--nav-text);
margin-right:1rem ;
}
.learn{
padding: 0.9rem 1.6rem;
color:var(--nav-text);
font-weight: bold;
border: none;
box-shadow: 1px 1px 10px 1px rgba(0, 0, 0, 0.5);
}
.order:hover{
border: 3px solid var(--nav-text); 
background: white;
color: var(--nav-text);
}
.learn:hover{
border: 3px solid var(--nav-text);
}
.basket:hover{
color: var(--nav-text);

}
.numbers{
width: 100%;
background: var(--nav-text);
padding: 2.4rem;
margin-bottom: 2rem;
}
.numbers ul{
display: flex;
align-items: center;
justify-content: center;
gap:10rem;


}
.numbers ul li{
font-size: 2rem;
color: aliceblue;
font-family: 'Rubik', sans-serif;
}
.number-text{
font-family: "Helvetica Neue", Helvetica, Arial,
        sans-serif;
font-size: 1.2rem;
font-weight: bold;
text-transform: capitalize;
}
.lemon{
display: flex;
flex-direction: row;
margin: 4rem;
gap: 3rem;
padding-top: 6rem;
}
.lemon-img-div{
width: 90%;
height: 400px;
border-radius: 1rem;
background: url('./images/4.png');
background-size: cover;


}
.lemon-text{
width: 80%;
}
.lemon-text h2{
width: 80%;
margin-bottom: 2rem;
padding-left: 3rem;
}
.lemon-text p{
width: 70%;
margin-bottom: 2rem;
padding-left: 3rem;
}
.learn2{
padding: 0.9rem 1.6rem;
background: var(--nav-text);
display: flex;
color: aliceblue;
font-weight: bold;
border: 1px solid var(--nav-text);
margin-left: 3rem;

}
.learn2:hover{
border: 3px solid var(--nav-text);
background: white;
color: var(--nav-text);
}
.hand-made{
display: flex;
flex-direction: row;
margin: 6rem 0 0  4rem;
gap: 3rem;
margin-bottom: 4rem;
}
.hand-made-text{
width: 60%;
}
.hand-made-text h2{
margin-top: 3rem;
margin-bottom: 2rem;
}
.hand-made-text p{
width: 100%;
margin-bottom: 2rem;
}

.hand-made-img{
background: url('./images/7.png');
width: 90%;
height: 600px;
border-radius: 1rem;
background-size: cover;
}
.hand-made-text ul{
display: block;
margin-bottom: 2rem;

}
.hand-made-text ul li{
font-size: 1.1rem;
color: var(--paragraph-text);


}
.tick{
font-weight: bolder;
font-size: 1.5rem;
margin-right: 0.5rem;

}
.learn2 {
padding: 0.9rem 1.6rem;
background: var(--nav-text);
display: flex;
color: aliceblue;
font-weight: bold;
border: 1px solid var(--nav-text);
margin-right: 1rem;
}

.learn2:hover {
border: 3px solid var(--nav-text);
background: white;
color: var(--nav-text);
}
.man{
background: url('./images/cobs2.jpg');
background-size: cover;
display:flex;
justify-content: center;
}
.man-text h2{
padding-top: 7rem;
width: 40rem;
margin-left: 3rem;
text-align: center;
padding-bottom: 1.5rem;

}
.man-text p{
width: 35rem;
margin-left: 5rem;
text-align: center;
padding-bottom: 10rem;
}
.play-paragraph a{
color: black;
font-weight: bolder;

}
.play-paragraph a:hover{
color: var(--nav-text);
}
.explore-div
{
padding: 0 4rem ;

}
.meals{
display: flex;
gap: 3rem;
}
.explore h2{
padding-top: 5rem;
text-align: center; 
padding-bottom: 2rem; 

}
.explore p{
padding: 0 12rem;
text-align: center;
font-size: 1rem;
padding-bottom: 2rem;
}
.image-text{
width: 30%;
}
.explore-img{
margin-top: 2rem;
width: 22rem;
border-radius: 0.5rem;
}
.price h4{
font-size: 1.1rem;
}
.price h3{
font-size: 1.5rem;
padding-bottom: 1rem;
}
.fade{
color: grey;
text-decoration: line-through;
} 
.price a{
padding: 0.9rem 1.6rem;
background: var(--nav-text);
color: aliceblue;
font-weight: bold;
border: 1px solid var(--nav-text);
margin-right: 1rem;
} 
.price a:hover {
border: 3px solid var(--nav-text);
background: white;
color: var(--nav-text);
}
.slideshow-container{
margin-top: 5rem;
background:var(--nav-text);
height: 100vh;

}
.slideshow-container h2{
color: var(--white);
padding: 5rem 0;
text-align: center;
}
.mySlides{
background: var(--white);
width: 80%;
border-radius: 1rem;
margin: auto;
}
.image2{
display: flex;
justify-content: center;
padding: 2rem;
}
.profile-img{
width: 5rem;
height: 5rem;
border-radius: 2.5rem;

}
.mySlides p{
display: flex;
text-align: center;
align-items: center;
padding: 0 12rem;
margin-bottom: 3rem;
font-size: 1.3rem;
}
.mySlides h5{
text-align: center;
color: var(--nav-text);
font-size: 1.1rem;
padding-bottom: 2rem;
}
.dot-container {
text-align: center;
width: 80%;
padding: 20px;
margin: auto;
border-radius: 2rem;
}
.dot {
cursor: pointer;
height: 15px;
width: 15px;
margin: 0 2px;
background-color: #bbb;
border-radius: 50%;
display: inline-block;
transition: background-color 0.6s ease;
}
.active,
.dot:hover {
background-color: #717171;
}
.prev,
.next {
cursor: pointer;
position: absolute;
width: auto;
margin-top: -200px;
padding: 16px;
color: var(--nav-text);
font-weight: bold;
font-size: 30px;
border-radius: 0 3px 3px 0;
user-select: none;
display: none;
}
.next {
position: absolute;
right: 10rem;
border-radius: 3px 0 0 3px;
}
.prev{
left: 10rem;

}
.faq h2{
text-align: center;
margin: 5rem 0;
}
.faq-text{
display: grid;
grid-template-columns: auto auto;
width: 80%;
margin: auto;
}
.faq-text h3{
color: var(--nav-text);
}
.faq-text p{
font-size: 1rem;
}
.faq-span{
margin-bottom: 2rem;
padding-right: 2rem;
}
.baked-fresh{
margin-top: 3rem;
}
.baked-image-div{
background: url('./images/10.jpg');
background-color: rgba(0, 0, 0, 0.6);
width: 100%;
background-blend-mode: multiply;
background-size: cover;
background-attachment: fixed;
padding: 5rem;

}
.baked-image-div h2{
color: var(--white);
}
.learn-baked{
padding: 0.9rem 1.6rem;
background: var(--nav-text);
display: flex;
color: aliceblue;
font-weight: bold;
border: 1px solid var(--nav-text);
float: right;
margin-top:-2.5rem ;
margin-right: 3rem;
}
.learn-baked:hover{
border: 3px solid var(--nav-text);
background: white;
color: var(--nav-text);
}











@media(max-width:768px){
ul{
    display: none;
}
.mobile {
    display: block;
    position: absolute;
    top: 7rem;
    width: 100%;
    margin-left: -1.5rem;
    display: none;
    }
.mobile li{
    padding:0.7rem;
    font-size: 1.4rem;
    padding-left: 1.9rem;
    background:black;
}
.bar{
    display:flex;
    align-items: center;
    font-size: 1.5rem;
    
}

.header1 {
    width: 100%;
    font-size: 2rem;

}
.paragraph1 {
    width: 90%;
    color: rgb(131, 26, 26);
    font-size: 1.1rem;
    padding-bottom: 2rem;
}
.numbers ul li{
    font-size:1.2rem ;
}
.numbers ul{
    gap:2rem;
}
.number-text {
    font-size: 0.8rem;
}
.lemon {
flex-direction: column;
margin: 1rem;
}

.lemon-img-div {
width: 100%;
}

.lemon-text {
width: 100%;

}

.lemon-text h2 {
width: 100%;
text-align: left;
padding-left: 0;
}

.lemon-text p {
width: 100%;
text-align: left;
padding-left: 0;
}
.learn2{
    margin-left: 0;
}
.hand-made {
    flex-direction: column;
    margin: 1rem;
}

.hand-made-text {
    width: 100%;
}

.hand-made-img {
    width: 100%;
    background-size: contain;
    background-repeat: no-repeat;
}
    .man {
    background: url('./images/mobile-cobs.jpg');
    
} 
.man-text{
    padding-left: 1rem;

}

.man-text h2 {
    padding-top: 5rem;
    font-size: 2rem;
    width:100%;
    margin-left:0;
    text-align: center;
    padding-bottom: 1.5rem;

}

.man-text p {
    width: 100%;
    margin-left:0;
    text-align: center;
    padding-bottom: 2rem;
}
.explore h2 {
    padding-top: 5rem;
    font-size: 2rem;
    text-align: center;
    padding-bottom: 2rem;

}

.explore p {
    padding: 0;
    text-align: left;
    font-size: 1.1rem;
    margin-left: 1rem;
}
    .image-text {
        width: 30%;
    }
    .meals{
        flex-direction: column;
    }
.explore-div{
    padding: 0 1rem;
    width: 100%;

}

    .image-text {
        width: 100%;
    }

    .explore-img {
        margin-top: 2rem;
        width: 22rem;
        border-radius: 0.5rem;
        display: flex;

    }

    .price h4 {
        font-size: 1.1rem;
    }

    .price h3 {
        font-size: 1.5rem;
        padding-bottom: 1rem;
    }

    .fade {
        color: grey;
        text-decoration: line-through;
    }

    .price a {
        padding: 0.9rem 1.6rem;
        background: var(--nav-text);
        color: aliceblue;
        font-weight: bold;
        border: 1px solid var(--nav-text);
        margin-right: 1rem;
    }

    .price a:hover {
        border: 3px solid var(--nav-text);
        background: white;
        color: var(--nav-text);
    }
    .slideshow-container {
        width: 100%;
        height: 70vh;
    }
    .slideshow-container h2 {
        padding: 2.5rem 0;

    }

    .mySlides p {
        text-align: left;
        padding: 0 1rem;
        font-size: 1.1rem;
        margin-left: 1.2rem;
    }

    .dot {
        display: none;
    }
    .prev,
    .next {
        display:block;
    }

    .next {
        right: 2rem;
    }

    .prev {
        left: 2rem;

    }
    .faq-text {
        grid-template-columns: auto;
        width:100%;
        margin: auto;
        padding-left: 2rem;
    }

    .faq-text h3 {
        color: var(--nav-text);
    }

    .faq-text p {
        font-size: 1rem;
    }

    .faq-span {
        margin-bottom: 2rem;
        padding-right: 2rem;
    }
            .baked-image-div {
                background-color: rgba(0, 0, 0, 0.7);
                width: 100%;
                background-blend-mode: multiply;
                background-size: contain;
                background-attachment: fixed;
                padding: 2rem;

    
            }
    
            .baked-image-div h2 {
                color: var(--white);
                font-size: 1.5rem;
            }
    
            .learn-baked {
                float:none;
                margin-top: 0;
            }
    
            .learn-baked:hover {
                border: 3px solid var(--nav-text);
                background: white;
                color: var(--nav-text);
            }



}

@media(min-width:769px) and (max-width:1020px){
h1{
    font-size:0.3rem ;

}
    .logo {
        padding: 0.7rem;
        font-size: 1.2rem;
        margin-left: 0.3rem;
    

    }
    ul {
        gap: 1.2rem;
        margin-right: 0.5rem;
    
    }
    .paragraph1 {
        color: rgb(131, 26, 26);
    }
    .numbers ul li {
        font-size: 1.7rem;
    }
    
    .numbers ul {
        gap: 6rem;
    }


    .lemon {
        margin: 3rem;
        gap: 2rem;
    }

    .lemon-div {
        width: 100%;
    }

    .lemon-text {
        width: 100%;
    }

    .lemon-text h2 {
        font-size: 2rem;
        width: 100%;
    }

    .lemon-text p {
        width: 100%;
        margin-bottom: 2rem;
    }
        .hand-made {
            margin: 1rem;
        }

        .hand-made-text {
            width: 100%;
        }

        .hand-made-img {
            width: 100%;
            margin-top: 7rem;
            background-size: contain;
            background-repeat: no-repeat;
        }
        

        

        
}



