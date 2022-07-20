*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    text-transform: uppercase;
}
div>img{
    width: 100%;
    height: 100%;
}
body button{
    background-color: white;
}

#box{
    display: flex;
    position: sticky;
  
    top: 1%;
    left: 20%;
    background-color:#333333;
    justify-content: center;
    align-items: center;
   
    border-radius: 5px;
    padding: 2%;
}
#searchbox{
    height:50px;
    border-radius: 10px;
    border: transparent;
}
#btn{
    height:50px;
    
    margin-left: 10px;
    border-radius: 10px;
    border: transparent;
     padding:1%
}
#jadu{
    position: fixed;
    left: 20%;
}
/* navbarcss------------------------------------------------- */
/* navbar css ---------------------------------------------*/
#navbar{
    height: 45px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color:rgba(255,255, 255, 1);
    background-position: fixed;
    padding-left: 20px;
    padding-right: 20px;
    position: sticky;
    top:0px;
    
    
}

#navbar>div:nth-child(3){
    width:35%;
    display: flex;

    justify-content: space-between;
    font-size: 14px;

    
}
#navbar>div:nth-child(5){
    width:35%;
    display: flex;

    justify-content: space-around;
    font-size: 14px;

    
}
#navbar>div:nth-child(2){
    
    display: flex;
background-color: white;
    justify-content: space-around;
    font-size: 20px;
    
}


#navbar>div>a:hover{
    font-size: 15px;
    cursor: pointer;
}
#navbar>div:nth-child(2)>a:hover{
    font-size: 23px;
    cursor: pointer;
}
#toggle{
    display: none;
}
#navbar>label{
    display: none;
}
a{
    text-decoration: none;
    color: black;
}
.sale{
    position: relative;
    width: 100%;
}
.sale>div:nth-child(1){
    display: flex;
    height: fit-content;
    /* width: 90%; */
   
    /* font-size: 120px; */
    justify-content: center;
    margin-top: 30px;
}
.sale>div>img{
    width: 94%;
}
.sale>div:nth-child(2){
   display: flex;
    font-size: 70px;
    justify-content: space-around;
    margin-top: 110px;
    margin-bottom: 20px;
    /* color: gray; */

}
.sale>div:nth-child(2)>a{
    color: gray;
}
.upper>div:nth-child(1){
    width: 100%;
    display: grid;
    grid-template-columns: repeat(2,1fr);
    grid-template-rows: auto;
    gap:40px;
    padding:4%;
}
.upper>div:nth-child(1)>div>label{
    font-size: 10px;
    color: #333333;
    margin-right: 20px;
}
.upper>div:nth-child(1)>div>span{
    font-size: 20px;
    margin: 1%;
}
.upper>div:nth-child(1)>div>p{
    display: block;
    font-size: 15px;
    margin: 1%;
}
.linux{
  
    display: grid;
    grid-template-columns: repeat(3,1fr);
    grid-template-rows: auto;
    gap:40px;
    padding:5%;
   
}
.linux>div>img+label{
    display: block;
    font-size: 17px;
    color: #333333;
    margin: 1%;
}
.linux>div>span{
    display: block;
font-size: 23px;

margin: 1%;
}
.linux>div>p>label{
    font-size: 13px;
    color: #333333;
    margin-right: 10px;
}
.upper>div:nth-child(3){
    width: 100%;
    display: grid;
    grid-template-columns: repeat(2,1fr);
    grid-template-rows: auto;
    gap:40px;
    padding:3%;
}
.middle{
    margin-top: 50px;
    margin-bottom: 0px;
    display: grid;
    grid-template-columns: repeat(5,1fr);
    grid-template-rows: auto;
    gap:20px;

}
.middle>div{
    border-top: 1px solid;
    border-bottom: 1px solid;
    display: grid;
    grid-template-columns: repeat(2,1fr);
    grid-template-rows: auto;
    gap:20px;
    padding: 5%;


}
.middle>div>div{
    display: grid;
    justify-content: space-between;
}
#buttn>button{
    display: none;
    width: 20%;
    height: 40px;
    border: 1px solid;
    margin: auto;
    border-radius: 10px;
}
.bottom{
    display: grid;
    grid-template-columns: 60% 40%;
    gap:10px;
}

.bottom>div:first-child>div{
   display: grid;
   grid-template-columns: repeat(2,1fr);
   gap:2%;
   margin: 2%;
}
.bottom>div:first-child>div>:last-child>h4{
    font-size: 28.5px;
    margin: 0px 20px;
}
.bottom>div:first-child>div>:last-child>label{
    font-size: 13px;
    margin: 0px 20px;
}
.bottom>div:first-child>div>:last-child>p{
    font-size: 18.5px;
    margin: 20px 20px 0px;
}

.bottom>div:last-child{
    display: grid;
    grid-template-columns: 50% 50%;
    gap:2%;
    margin: 2%;
 }
 .bottom>div:last-child>:first-child>img{
    height: 50%;
 }
.bottom>div:last-child>:first-child>h4{
    font-size: 28.5px;
  
 }
 .bottom>div:last-child>div:last-child{
    display: grid;
    grid-template-rows: repeat(4,190px);
    gap:1%;
 }
 .bottom>div:last-child>div:last-child>div{
    border-top: 1px solid;
    
    display: grid;
    grid-template-columns: repeat(2,1fr);
    grid-template-rows: auto;
    gap:20px;
    margin-bottom: 10px;
   

 }

 .bottom>div:last-child>div:last-child>div>div{
    display: grid;
    justify-content: space-between;
 }
 .kali{
    width: 100%;
    display: grid;
    grid-template-columns: repeat(2,1fr);
    grid-template-rows: auto;
    gap:40px;
    padding:1%;
    margin-bottom: 15px;
 }
 .kali>div{
    padding: 5%;
 }
 .kali>div>label{
    display: block;
font-size: 13px;
color: #333333;
margin: 1%;
 }
 .kali>div>span{
    display: block;
font-size: 18px;

margin: 1%;
 }
 .kali>div>button{
    display: block;
font-size: 15px;
padding: 10px 35px;
margin: 1%;
border-radius: 10px;
 }
 #vinit{
     /* border: 1px solid red; */
     text-align: center;
     margin: 70px;
     width: 100%;
     height: 200px;
     font-size: x-large;
     /* margin-bottom: 15px; */
     width: 95%;
 }
 #vinit button{
    font-size: 20px;
    border-radius: 15px;
    padding: 15px;
    margin-top: 20px;
    
   
 }
 /* -------------------------------------------------------- */
 #foot{
    margin-top: 90px;
    margin-bottom: 90px;
 }
 #foot>div:first-child{display: flex;
    width: 90%;
    height: 50px;
    
    margin: auto;
    
    }
#up{
    
    display: grid;
    grid-template-columns: repeat(8,1fr);
    gap:2%;
    font-size: 11px;
    align-items: center;
    justify-content: center;
    }
    #foot>div:first-child>div+div{
        width:12%;
        display:flex ;
        align-items: center ;
        justify-content: space-around;

    }

#down>ul{
    width: 55%;
    display: grid;
    grid-template-columns: repeat(5,1fr);
    gap:2%;
    font-size: 12px;
    justify-content: center;
    color: rgb(124, 124, 248);
    list-style: none;
    margin: auto;
}
#foot>div:first-child>div>img{
    width: 20px;
    height: 44%;


}
#up>a{
    text-decoration: none;
    color:#333333;
    margin-right: 5px;
    margin-left: 0%;
   font-size: 14px;
}
/* ------------------------------------------------- */
#komal{
    width: 70%;
    display: grid;
    grid-template-columns: repeat(4,1fr);
    grid-template-rows: repeat(4,auto);
    gap: 12px;
     /* margin-left: 100px;  */
     margin:auto;
}
#komal>div{
    box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px;
    padding: 10px;
    height: fit-content;
}
#komal>div>img{
    height: fit-content;
}
#komal>div>span{
    display: block;
} 



@media all and (min-width:320px) and (max-width:800px) {
    #navbar{
        display: flex;
        width:100%;
        
    
       }
        #navbar>div:nth-child(3){
            margin-top: 200px;
          width: 100%;
           line-height: 30px;
          
           background-color:white;
            display: none;
            
        }
        #navbar>div:nth-child(5){
            width: 100%;
            line-height: 30px;
            
            display: none;
        }
        #navbar>div:nth-child(4){
           display: inherit;
        }
        #navbar a{
            display: block;
        }
        #toggle{
            display: none;
        }
        #navbar>label{
            display: inherit;
        }
        #toggle:checked +  .dis{
            display: block;
            
        }
       
    

    /* ------------------------------------ */
   
    .sale>div:nth-child(1){
        height: 60px;
        font-size: 60px; 
        display: none; 
    }
    .upper>div:nth-child(1){
        width: 100%;
        display: grid;
        grid-template-columns: repeat(1,1fr);
        grid-template-rows: repeat(2,auto);
        gap:10%;
        padding:3%;
        margin-bottom: 24%;
    }
    .linux{
  
        display: grid;
        grid-template-columns: repeat(1,1fr);
        grid-template-rows: repeat(3,auto);
        gap:6%;
        padding:5%;
        margin-bottom: 60%;
       
    }
    .upper>div:nth-child(3){
        grid-template-columns: repeat(1,1fr);
        grid-template-rows: repeat(2,auto);
        gap:6%;
        padding:3%;
        margin-bottom: 24%;
    }
    .middle{
      
        grid-template-columns: repeat(2,1fr);
        grid-template-rows: repeat(1,auto);
        gap:20px;
        margin-bottom: 2%;
    
    }
    .middle>div:nth-child(3){
        display: none;
    }
    .middle>div:nth-child(4){
        display: none;
    }
    .middle>div:nth-child(5){
        display: none;
    }
    #buttn>button{
        width: 90%;
        height: 50px;
        background-color: white;
        margin-bottom: 3%;
    }
    .bottom{
        
        grid-template-columns: 100%;
        gap:10px;
    }
    .bottom>div:last-child{
        grid-template-columns: 100%;
        margin: 0%;
        padding: 0%;
        gap: 0%;
        margin-bottom: -60%;
     }
     .bottom>div:last-child>div:last-child{
        display: none;
      
     }
     .kali{
       
        width: 100%;
        display: grid;
        grid-template-columns: 100%;
        grid-template-rows: auto;
        gap:55px;
        padding:1%;
        margin-bottom: 10%;
     }
     .kali button{
        width: 90%;
        background-color: white;
}
/* -------------------------------------- */
#foot{
    display: none;
}
/* ----------------------------------------- */
#komal{
    width: 100%;
    display: grid;
    grid-template-columns: repeat(1,1fr);
    grid-template-rows: auto;
    gap: 12px;
     /* margin-left: 100px;  */
     margin:auto;
}
}
