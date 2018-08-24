




article{display:block}

#slider, #slider2, #slider3 {text-align:center}
#slider, #slider2, #slider3 {margin:0 auto}
input{}
#slide1:checked ~ #slides .inner{margin-left:0}
#slide2:checked ~ #slides .inner{margin-left:-100%}
#slide3:checked ~ #slides .inner{margin-left:-200%}
#slide4:checked ~ #slides .inner{margin-left:-300%}
#slide5:checked ~ #slides .inner{margin-left:-400%}

#slide10:checked ~ #slides2 .inner{margin-left:0}
#slide11:checked ~ #slides2 .inner{margin-left:-100%}
#slide12:checked ~ #slides2 .inner{margin-left:-200%}
#slide13:checked ~ #slides2 .inner{margin-left:-300%}
#slide14:checked ~ #slides2 .inner{margin-left:-400%}

#slide20:checked ~ #slides3 .inner{margin-left:0}
#slide21:checked ~ #slides3 .inner{margin-left:-100%}
#slide22:checked ~ #slides3 .inner{margin-left:-200%}
#slide23:checked ~ #slides3 .inner{margin-left:-300%}
#slide24:checked ~ #slides3 .inner{margin-left:-400%}


#container {width:100%;overflow:hidden; padding-left: 30px;}
#container2 {width:100%;overflow:hidden; }
#container3 {width:100%;overflow:hidden; }
article img{width:100%}

#slides .inner{width:500%;line-height:0}
#slides article{width:20%;float:left}
#commands{margin:-25% 0 0 0;width:100%;height:50px}
#commands label{display:none;width:80px;height:80px;opacity:0.5}
#commands label:hover{opacity:0.8}
#active{position:relative;z-index:5;margin:16% 0 0;text-align:center}
#active label{-webkit-border-radius:5px;-moz-border-radius:5px;border-radius:5px;display:inline-block;width:10px;height:10px;background:#bbb}
#active label:hover{background:#333;border-color:#777!important}
#slide1:checked ~ #commands label:nth-child(2),#slide2:checked ~ #commands label:nth-child(3),
#slide3:checked ~ #commands label:nth-child(4),#slide4:checked ~ #commands label:nth-child(5),
#slide5:checked ~ #commands label:nth-child(1){background: url("../../images/zarpe_flecha2b.png") no-repeat;float:right;margin:-20px -20px 0px 0px;display:block}
#slide1:checked ~ #commands label:nth-child(5),#slide2:checked ~ #commands label:nth-child(1),#slide3:checked ~ #commands label:nth-child(2),
#slide4:checked ~ #commands label:nth-child(3),#slide5:checked ~ #commands label:nth-child(4){background:url("../../images/zarpe_flecha1b.png") no-repeat;float:left;margin:-20px 30px 0px 0px;display:block}
#slide1:checked ~ #active label:nth-child(1),#slide2:checked ~ #active label:nth-child(2),#slide3:checked ~ #active label:nth-child(3),#slide4:checked ~ #active label:nth-child(4),#slide5:checked ~ #active label:nth-child(5){background:#000;opacity:0.6;border-color:#fff!important;border:2px solid #fff}
.caption{line-height:20px;margin:0 0 -150%;position:absolute;padding:320px 12px;opacity:0;color:#fff;text-transform:none;font-family:'Open Sans',Arial,Helvetica,sans-serif;text-align:left;font-size:18px}
.caption bar{display:inline-block;padding:10px;background:#000;border-radius:3px 3px 3px 3px;-moz-border-radius:3px 3px 3px 3px;-webkit-border-radius:3px 3px 3px 3px;opacity:0.7;filter:progid:DXImageTransform.Microsoft.Alpha(opacity=70)}

#slides2 .inner{width:500%;line-height:0}
#slides2 article{width:20%;float:left}
#commands2{margin:-25% 0 0 0;width:100%;height:50px}
#commands2 label{display:none;width:80px;height:80px;opacity:0.5}
#commands2 label:hover{opacity:0.8}
#active2{position:relative;z-index:5;margin:16% 0 0;text-align:center}
#active2 label{-webkit-border-radius:5px;-moz-border-radius:5px;border-radius:5px;display: none;width:10px;height:10px;background:#bbb}
#active2 label:hover{background:#333;border-color:#777!important}
#slide10:checked ~ #commands2 label:nth-child(2),#slide11:checked ~ #commands2 label:nth-child(3),
#slide12:checked ~ #commands2 label:nth-child(4),#slide13:checked ~ #commands2 label:nth-child(5),
#slide14:checked ~ #commands2 label:nth-child(1){background:url("../../images/zarpe_flecha2b.png") no-repeat;float:right;margin:0px -100px 0px 0px;display:block}
#slide10:checked ~ #commands2 label:nth-child(5),#slide11:checked ~ #commands2 label:nth-child(1),#slide12:checked ~ #commands2 label:nth-child(2),
#slide13:checked ~ #commands2 label:nth-child(3),#slide14:checked ~ #commands2 label:nth-child(4){background:url("../../images/zarpe_flecha1b.png") no-repeat;float:left;margin:0px 0px 0px -50px;display:block}
#slide10:checked ~ #active2 label:nth-child(1),#slide11:checked ~ #active2 label:nth-child(2),#slide12:checked ~ #active2 label:nth-child(3),
#slide13:checked ~ #active2 label:nth-child(4),#slide14:checked ~ #active2 label:nth-child(5){background:#000;opacity:0.6;border-color:#fff!important;border:2px solid #fff}

#slides3 .inner{width:500%;line-height:0}
#slides3 article{width:20%;float:left}
#commands3{margin:-25% 0 0 0;width:100%;height:50px}
#commands3 label{display:none;width:80px;height:150px;opacity:0.5}
#commands3 label:hover{opacity:0.8}
#active3{position:relative;z-index:5;margin:16% 0 0;text-align:center}
#active3 label{-webkit-border-radius:5px;-moz-border-radius:5px;border-radius:5px;display: none;width:10px;height:10px;background:#bbb}
#active3 label:hover{background:#333;border-color:#777!important}
#slide20:checked ~ #commands3 label:nth-child(2),#slide21:checked ~ #commands3 label:nth-child(3),
#slide22:checked ~ #commands3 label:nth-child(4),#slide23:checked ~ #commands3 label:nth-child(5),
#slide24:checked ~ #commands3 label:nth-child(1){background:url("../../images/zarpe_flecha2b.png") no-repeat;float:right;margin:0px -100px 0px 0px;display:block}
#slide20:checked ~ #commands3 label:nth-child(5),#slide21:checked ~ #commands3 label:nth-child(1),#slide22:checked ~ #commands3 label:nth-child(2),
#slide23:checked ~ #commands3 label:nth-child(3),#slide24:checked ~ #commands3 label:nth-child(4){background:url("../../images/zarpe_flecha1b.png") no-repeat;float:left;margin:0px 0px 0px -50px;display:block}
#slide20:checked ~ #active3 label:nth-child(1),#slide21:checked ~ #active3 label:nth-child(2),#slide22:checked ~ #active3 label:nth-child(3),
#slide23:checked ~ #active3 label:nth-child(4),#slide24:checked ~ #active3 label:nth-child(5){background:#000;opacity:0.6;border-color:#fff!important;border:2px solid #fff}



#slider, #slider2, #slider3 {-webkit-transform:translateZ(0);-webkit-transition:all 0.5s ease-out;-moz-transition:all 0.5s ease-out;-o-transition:all 0.5s ease-out;transition:all 0.5s ease-out}
#slider, #slider2, #slider3 {max-width:1100px}
#slides, #slides2, #slider3 {position:relative;padding:0px;margin:0px 0 0;}
#slides .inner{-webkit-transform:translateZ(0);-webkit-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -moz-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);-ms-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -o-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -webkit-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -moz-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -ms-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -o-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000)}
#commands label{-webkit-transform:translateZ(0);-webkit-transition:opacity 0.2s ease-out;-moz-transition:opacity 0.2s ease-out;-o-transition:opacity 0.2s ease-out;transition:opacity 0.2s ease-out}
#slide1:checked ~ #slides article:nth-child(1) .caption,#slide2:checked ~ #slides article:nth-child(2) .caption,#slide3:checked ~ #slides article:nth-child(3) .caption,#slide4:checked ~ #slides article:nth-child(4) .caption,#slide5:checked ~ #slides article:nth-child(5) .caption{opacity:1;-webkit-transition:all 1s ease-out 0.6s;-moz-transition:all 1s ease-out 0.6s;-o-transition:all 1s ease-out 0.6s;transition:all 1s ease-out 0.6s}
#commands,#commands label,#slides,#active,#active label{-webkit-transform:translateZ(0);-webkit-transition:all 0.5s ease-out;-moz-transition:all 0.5s ease-out;-o-transition:all 0.5s ease-out;transition:all 0.5s ease-out}
               
               
#slides2 .inner{-webkit-transform:translateZ(0);-webkit-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -moz-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);-ms-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -o-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -webkit-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -moz-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -ms-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -o-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000)}              
#commands2 label{-webkit-transform:translateZ(0);-webkit-transition:opacity 0.2s ease-out;-moz-transition:opacity 0.2s ease-out;-o-transition:opacity 0.2s ease-out;transition:opacity 0.2s ease-out}
#slide10:checked ~ #slides2 article:nth-child(1) .caption,#slide11:checked ~ #slides2 article:nth-child(2) .caption,
#slide12:checked ~ #slides2 article:nth-child(3) .caption,#slide13:checked ~ #slides2 article:nth-child(4) .caption,
#slide14:checked ~ #slides2 article:nth-child(5) .caption{opacity:1;-webkit-transition:all 1s ease-out 0.6s;-moz-transition:all 1s ease-out 0.6s;-o-transition:all 1s ease-out 0.6s;transition:all 1s ease-out 0.6s}
#commands2,#commands2 label,#slides2,#active,#active label{-webkit-transform:translateZ(0);-webkit-transition:all 0.5s ease-out;-moz-transition:all 0.5s ease-out;-o-transition:all 0.5s ease-out;transition:all 0.5s ease-out}


#slides3 .inner{-webkit-transform:translateZ(0);-webkit-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -moz-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);-ms-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -o-transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);transition:all 800ms cubic-bezier(0.770,0.000,0.175,1.000);
               -webkit-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -moz-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -ms-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               -o-transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000);
               transition-timing-function:cubic-bezier(0.770,0.000,0.175,1.000)}              
#commands3 label{-webkit-transform:translateZ(0);-webkit-transition:opacity 0.2s ease-out;-moz-transition:opacity 0.2s ease-out;-o-transition:opacity 0.2s ease-out;transition:opacity 0.2s ease-out}
#slide20:checked ~ #slides3 article:nth-child(1) .caption,#slide21:checked ~ #slides3 article:nth-child(2) .caption,
#slide22:checked ~ #slides3 article:nth-child(3) .caption,#slide23:checked ~ #slides3 article:nth-child(4) .caption,
#slide24:checked ~ #slides3 article:nth-child(5) .caption{opacity:1;-webkit-transition:all 1s ease-out 0.6s;-moz-transition:all 1s ease-out 0.6s;-o-transition:all 1s ease-out 0.6s;transition:all 1s ease-out 0.6s}
#commands3,#commands3 label,#slides3,#active3,#active3 label{-webkit-transform:translateZ(0);-webkit-transition:all 0.5s ease-out;-moz-transition:all 0.5s ease-out;-o-transition:all 0.5s ease-out;transition:all 0.5s ease-out}



/* Estilo externos  */
.cc_container .cc_btn, .cc_container .cc_btn {background:#75c6ca!important; color: #000000!important;}
.cc_container a, .cc_container a:visited {color: #75c6ca!important;}
.cc_container {background:#042743!important; }



/* Pagina de trnasicion */
.zarpe_transicion_panel {float:right; position:absolute; top:40px; right:40px; padding:7px;  }
.zarpe_transicion_boton {float:right; position:absolute; top:560px; left:10%; }
.zarpe_transicion_panel_padding {padding:15px; border:1px solid #8193a1  }

@media only screen and (max-width:4000px) and (min-width:2501px){
.zarpe_transicion_boton {float:right; position:absolute; top:700px; left:27%; }
.zarpe_transicion_panel {float:right; position:absolute; top:40px; right:620px;  }
}
@media only screen and (max-width:2500px) and (min-width:2001px){
.zarpe_transicion_boton {float:right; position:absolute; top:700px; left:19%; }
.zarpe_transicion_panel {float:right; position:absolute; top:40px; right:270px;  }
}
@media only screen and (max-width:2000px) and (min-width:1701px){
.zarpe_transicion_boton {float:right; position:absolute; top:680px; left:14%; }
.zarpe_transicion_panel {float:right; position:absolute; top:40px; right:140px;  }
}

@media only screen and (max-width:1600px) and (min-width:1401px){
.zarpe_transicion_boton {float:right; position:absolute; top:620px; left:10%; }

}

@media only screen and (max-width:1400px) and (min-width:1025px){
.zarpe_transicion_boton {float:right; position:absolute; top:560px; left:10%; }
}

@media only screen and (max-width:1024px) and (min-width:1101px){
.zarpe_transicion_boton {float:right; position:absolute; top:510px; left:10%; }

}


@media only screen and (max-width:1100px) and (min-width:851px){
.zarpe_transicion_boton {float:right; position:absolute; top:440px; left:10%; }

}

@media only screen and (max-width:1200px) and (min-width:851px){
 
#slide20:checked ~ #commands3 label:nth-child(2),#slide21:checked ~ #commands3 label:nth-child(3),
#slide22:checked ~ #commands3 label:nth-child(4),#slide23:checked ~ #commands3 label:nth-child(5),
#slide24:checked ~ #commands3 label:nth-child(1){ margin:50px 0px 0px 20px;}
#slide20:checked ~ #commands3 label:nth-child(5),#slide21:checked ~ #commands3 label:nth-child(1),#slide22:checked ~ #commands3 label:nth-child(2),
#slide23:checked ~ #commands3 label:nth-child(3),#slide24:checked ~ #commands3 label:nth-child(4) { margin:50px 0px 0px 20px;}

}



@media only screen and (max-width:850px) and (min-width:450px){
  #slider #commands{margin:-70px 0 0 5%;width:90%;height:50px}
  #slider #commands label{-moz-transform:scale(0.9);-webkit-transform:scale(0.9);-o-transform:scale(0.9);-ms-transform:scale(0.9);transform:scale(0.9)}
  #slider #slides .caption{padding:280px 12px}
  #slider #slides{padding:2px 0;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0; height: 130px;}
  #slider #active{margin:15% 0 0; display:none;}
  
  
#slide20:checked ~ #commands3 label:nth-child(2),#slide21:checked ~ #commands3 label:nth-child(3),
#slide22:checked ~ #commands3 label:nth-child(4),#slide23:checked ~ #commands3 label:nth-child(5),
#slide24:checked ~ #commands3 label:nth-child(1){margin:50px 0px 0px 30px;}
#slide20:checked ~ #commands3 label:nth-child(5),#slide21:checked ~ #commands3 label:nth-child(1),#slide22:checked ~ #commands3 label:nth-child(2),
#slide23:checked ~ #commands3 label:nth-child(3),#slide24:checked ~ #commands3 label:nth-child(4) {margin:50px 0px 0px 30px;}

.zarpe_transicion_boton {float:right; position:absolute; top:340px; left:10%; }
}


@media only screen and (max-width:450px){
  #slider #commands{margin:-70px 0 0 1%;width:100%;height:70px}
  #slider #active{margin:12% 0 0; display:none;}
  #slider #slides{padding:2px 0;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0; height: 110px;}
  #slider #slides .caption{opacity:0!important}
  #slider #commands label{-moz-transform:scale(0.7);-webkit-transform:scale(0.7);-o-transform:scale(0.7);-ms-transform:scale(0.7);transform:scale(0.7)}
}




@charset "UTF-8";
/*!
 * Bootstrap v3.3.6 (http://getbootstrap.com)
 * Copyright 2011-2015 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */

/* Graviola Soft  */
@font-face { font-family: 'graviola_softblack'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_black-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_black-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softbold_italic'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_bold_italic-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_bold_italic-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softbold'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_bold-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_bold-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softbook_italic'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_book_italic-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_book_italic-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softbook'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_book-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_book-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softheavy'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_heavy-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_heavy-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softlight'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_light-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_light-webfont.woff') format('woff');}
         
@font-face { font-family: 'graviola_softlight_italic'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_light_italic-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_light_italic-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softmedium_italic'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_medium_italic-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_medium_italic-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softmedium'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_medium-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_medium-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softregular'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_regular-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_regular-webfont.woff') format('woff');}

@font-face { font-family: 'graviola_softthin'; font-weight: normal; font-style: normal;
    src: url('../../Font-Graviola/graviola_soft_thin-webfont.woff2') format('woff2'),
         url('../../Font-Graviola/graviola_soft_thin-webfont.woff') format('woff');}



/*  Menu responsive  */
.drawer-nav li a, .drawer-fullnav li a { padding: 6px 15px!important; font-size: 13px; }


/*  Modal  */
.modalDialog {position: fixed;top: 0;right: 0;bottom: 0;left: 0;background: rgba(255, 255, 255, 0.7);z-index: 99999;opacity:0;
	-webkit-transition: opacity 400ms ease-in;-moz-transition: opacity 400ms ease-in;transition: opacity 400ms ease-in;pointer-events: none;}
.modalDialog:target {opacity:1;pointer-events: auto;}
.modalDialog > div {width: 650px; position: relative; text-align:center; margin: 10% auto; padding: 5px 20px 13px 20px; background: #F4F5F7; 
                    box-shadow: 5px 5px 25px #B3B4B8;}
.close2 {
	background: #606061;color: #FFFFFF;line-height: 25px;position: absolute;right: -12px;text-align: center;top: -10px;width: 24px;
	text-decoration: none;font-weight: bold;-webkit-border-radius: 12px;-moz-border-radius: 12px; text-decoration:none!important;
	border-radius: 12px;-moz-box-shadow: 1px 1px 3px #000;-webkit-box-shadow: 1px 1px 3px #000; box-shadow: 1px 1px 3px #000;}

.close2:hover { background: #606061;  color:#ffffff;}



/*  Zarpe  */
.logo_zarpe_3 { width:100%; max-width:160px; margin-top:10px;}
.logo_zarpe_2 { width:100%; max-width:340px; }
.titulo_1 { font-size: 20px;font-family: graviola_softbold; color:#052844; line-height: 20px;}
.titulo_1b { font-size: 16px;color:#052844; line-height: 20px;}
.titulo_2 { font-size: 32px;font-family: graviola_softregular; letter-spacing: -1px; line-height: 34px;}
.titulo_3 { font-size: 36px;font-family: graviola_softmedium_italic; color:#ffffff; line-height: 34px;}
.titulo_4 { font-size: 31px;font-family: graviola_softbold; color:#052844; letter-spacing: -1px; line-height: 22px; }
.titulo_4b { font-size: 31px;font-family: Montserrat; color:#052844; letter-spacing: -1px; line-height: 22px; }
.titulo_5 { font-size: 20px;font-family: graviola_softmedium_italic; line-height: 21px;}
.titulo_6 { font-size: 17px;font-family: graviola_softmedium_italic; color:#052844; }
.titulo_7 { font-size: 28px;font-family: graviola_softmedium_italic; letter-spacing: -1px; line-height: 28px;}
.titulo_7b { font-size: 28px;font-family: graviola_softmedium_italic; }
.titulo_7c { font-size: 23px;font-family: graviola_softmedium_italic; }
.titulo_8 { font-size: 24px;font-family: graviola_softbold; color:#052844; letter-spacing: -1px; line-height: 22px;}
.titulo_8b { font-size: 24px;font-family: Montserrat; color:#052844; letter-spacing: -1px; line-height: 22px;}
.titulo_9, .titulo_9b, .titulo_9c { font-size: 25px;font-family: graviola_softregular; color:#052844; letter-spacing: -1px; line-height: 22px;}
.titulo_10 { font-size: 27px;font-family: graviola_softheavy; color:#052844; letter-spacing: -1px; }
.titulo_11 { font-size: 23px;font-family: graviola_softmedium_italic; line-height: 21px;}
.titulo_12 { font-size: 30px;font-family: graviola_softbold_italic; letter-spacing: -1px; line-height: 28px;}
.titulo_13 { font-size: 31px;font-family: graviola_softbook_italic; letter-spacing: 0px; line-height: 28px;}
.titulo_14 { font-size: 44px;font-family: graviola_softbold_italic; letter-spacing: -1px; line-height: 40px;}
.titulo_15 { font-size: 26px;font-family: graviola_softlight_italic; letter-spacing: -1px; line-height: 28px;}



.texto_2 { font-size: 19px;font-family: graviola_softbold; }
.texto_1 { font-size: 18px;font-family: graviola_softheavy; color:#929397; line-height: 18px;}
.texto_3, .texto_3b { font-size: 19px;font-family: graviola_softmedium_italic; color:#929395; line-height: 18px;}
.texto_4 { font-size: 12px;font-family: graviola_softmedium; color:#999999; line-height: 10px;}
.texto_4b { font-size: 10px; color:#042842; line-height: 10px; text-decoration:underline}
.texto_4c, .texto_4c[disabled] { font-size: 10px!important; color:#042842; line-height: 10px; text-decoration:underline; font-family:Montserrat!important;}
.texto_5 { font-size: 19px;font-family: graviola_softbold; color:#999999;}
.texto_6 { font-size: 17px;font-family: graviola_softmedium; color:#929397;  }
.texto_6b, .texto_6c { font-size: 17px;font-family: graviola_softmedium; color:#929397;  }
.texto_7 { font-size: 13px;font-family: graviola_softmedium; color:#929397; letter-spacing: -0.5px; line-height: 11px;}
.texto_8 { font-size: 20px;font-family: graviola_softmedium; color:#929397; line-height: 25px; letter-spacing: -0.5px; }
.texto_8b { font-size: 20px!important;font-family: graviola_softmedium!important; color:#929397; line-height: 25px; letter-spacing: -0.5px; }
.texto_9 { font-size: 15px;font-family: graviola_softmedium_italic; color:#929395; letter-spacing: 0px; }
.texto_9c { font-size: 15px;font-family: graviola_softmedium_italic; color:#929395; letter-spacing: 0px; }
.texto_9b { font-size: 17px;font-family: graviola_softlight_italic; color:#929395; letter-spacing: 0px; }
.texto_10 { font-size: 12px;font-family: graviola_softmedium_italic; color:#929395; letter-spacing: -1px; }
.texto_11 { font-size: 22px;font-family: graviola_softmedium; color:#929397; line-height: 25px; letter-spacing: -0.5px; }
.texto_12 { font-size: 22px;font-family: graviola_softbook; color:#6B6C6E; line-height: 12px;}
.texto_13 { font-size: 17px;font-family: graviola_softmedium; color:#929397; line-height: 15px; letter-spacing: -1px;}
.texto_14 { font-size: 19px;font-family: graviola_softmedium_italic; color:#929395; line-height: 18px;}
.texto_15 { font-size: 17px;font-family: graviola_softmedium; color:#929397; line-height: 15px; letter-spacing: -1px;}
.texto_16 { font-size: 21px;font-family: graviola_softmedium; color:#929397; line-height: 25px; letter-spacing: -0.5px; }
.texto_17 { font-size: 19px;font-family: graviola_softlight_italic; color:#929395; }

.texto_18 { font-size: 12px!important;font-family: graviola_softmedium; line-height: 8px;}
.texto_19 { font-size: 13px!important;font-family: graviola_softmedium_italic; line-height: 9px; }
.texto_21 { font-size: 18px;font-family: graviola_softlight; color:#929395; }
.texto_22 { font-size: 13px;font-family: graviola_softlight; color:#929395; }


.tachadodiagonal { position: relative;}
 
.tachadodiagonal:before { position: absolute; content: ""; left: 0; top: 50%; right: 0; border-top: 1px solid; border-color: #022d4f;    
    -webkit-transform:rotate(-10deg);
    -moz-transform:rotate(-10deg);
    -ms-transform:rotate(-10deg);
    -o-transform:rotate(-10deg);
    transform:rotate(-10deg);
}

.caja_zarpe::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
    color: #adadad;
}

.texto_menu { font-size: 11px;font-family: Montserrat; color:#728191; line-height: 9px!important;}
.texto_20 { font-size: 11px;font-family: graviola_softmedium; color:#a7a8ac; line-height: 9px!important;}
.texto_20b { font-size: 11px;font-family: graviola_softmedium; color:#a7a8ac; line-height: 9px!important;}
.menu_padding { margin-left:18px; float:left; width:100px; margin-right:18px; text-decoration:none; margin-top:10px; margin-bottom:10px;}
.menu_padding:hover { text-decoration:none;}

.zarpe_iconomenu { width:24px;}
.menu_padding2 { margin-left:38px; float:left; width:100px; margin-right:38px; text-decoration:none; margin-top:10px; margin-bottom:10px;}
.menu_padding2:hover { text-decoration:none;}

.tabla_padding td { padding:5px!important; }
.nav2 > li { position: relative !important;display: inline-block !important; height: 70px;}
.nav2 > li > a { background: #E4E5E7; border-radius:100px; padding: 10px 10px;color:#052943; text-decoration: none; }

.tabs_zarpe { background: #E4E5E7; border-radius:100px; padding:6px; color:#A6A7AB; margin:10px; }
.tabs_zarpe:hover { background: #a4cde1!important; color:#052943;}
.tabs_zarpe_activo, .tabs_zarpe_activo:hover { background: #a4cde1!important; border-radius:100px; padding: 10px 10px;color:#052943; margin-bottom:160px!important;}
.tab_activo { height:80px!important; background-image: url("../../images/icono_flecha6.png"); background-repeat: no-repeat; background-position: 50% 34px;}
.borde_div_zarpe { border:1px solid #DCDCDC; padding:8px; text-align:left; border-radius:100px; padding-left:25px; padding-right:25px; margin-bottom:8px; }
.borde_div_zarpe2 { border:1px solid #DCDCDC; padding:12px;text-align:left; border-radius:40px; padding-left:25px; padding-right:25px; margin-bottom:8px; }
.borde_div_zarpe3 { border:1px solid #DCDCDC; padding:9px;text-align:left; padding-right:90px; border-radius:12px; padding-left:25px; margin-bottom:8px; }
.borde_texto_zarpe { border:1px solid #999999; padding-left:7px; padding-right:7px; border-radius:40px; min-width:40px; 
                     display: inline-block; padding-top: 5px; padding-bottom: 2px;}
.borde_texto_zarpe2 { border:1px solid #999999; padding:2px;  padding-left:17px; padding-right:17px; border-radius:40px; min-width:40px; }
.borde_texto_zarpe3 { border:1px solid #999999; padding:2px;  padding-left:10px; padding-right:10px; border-radius:40px; min-width:40px; }

.borde_producto_zarpe2 { border:2px solid #8CC63E; padding:6px; border-radius:44px; width:100%; max-width:700px;margin-bottom:8px; }
.borde_producto_zarpe { border:0px solid #999999; padding:3px;width:100%; margin-bottom:8px; max-width:190px; }
.borde_imagen_zarpe { border:2px solid #D6D7D9; padding:0px; border-radius:18px; background:#E7E8EA; }
.borde_imagen_zarpe:hover { border:2px solid #8CC63E; padding:0px; border-radius:18px; text-decoration:none; }
.borde_sombra_zarpe { box-shadow: 0px 1px 6px rgba(0, 0, 0, 0.64); }
.sombra_texto_zarpe { text-shadow: 0px 4px 15px rgba(0, 0, 0, 0.64); }

.alienar_boton  { float:right; position: relative; margin-right:250px; margin-top:-110px; }
.alienar_boton2  { float:right; position: relative; margin-right:60px; margin-top:-110px; }

.boton_producto_zarpe:hover .borde_imagen { border:2px solid #8CC63E; padding:3px; border-radius:12px; text-decoration:none; }
.boton_producto_zarpe, .boton_producto_zarpe:hover { text-decoration:none; text-align:left; width:100%; display: block; margin-bottom:15px;}
.borde_imagen { border:2px solid #D6D7D9; padding:3px; border-radius:12px; text-decoration:none;}
.boton_producto_zarpe:hover .boton_zarpe5 { display:  inline-block; }

.foto_compartir { width:100%; max-width:550px; border:1px solid #cdcdcd; padding:4px;  }
.icono_compartir { width:32px; padding:1px;  }
.icono_compartir2 { width:44px; padding:1px;  }

.fondo_div_nombre { background-image: url("../../images/slider_texto_zarpe.jpg"); background-position: 0px -10px; background-size: 440px 62px ;
                    background-repeat: no-repeat; padding-top: 12px; padding-bottom: 22px; } 
 




.zarpe_campo_texto_select { background:#e1e2e4;border:0px solid #ffffff; line-height: 21px; border-radius:30px; width:100%; padding:5px; 
                            padding-left:16px;color:#032842; }
.zarpe_campo_texto { background:#e1e2e4;border:0px solid #ffffff; border-radius:30px; width:100%; padding:7px; padding-left:16px;color:#032842;}


.zarpe_campo_texto2 { width:100%; }




.paquete_on { margin:20px; padding:8px; border-radius:30px; text-decoration:none!important; border:1px solid #e7ecf2; text-align:center; }
.paquete_off { margin:20px; padding:8px; border-radius:30px; text-decoration:none!important; border:1px solid #ffffff; text-align:center; }

.boton_transparente { margin-top:410px; background-color: rgba(255, 255,255, 0.3); width:206px; text-align:center; border-radius:20px; 
                      color:#ffffff!important; padding:8px 1px 7px 1px; margin-left:10px; text-decoration: none:}
.boton_transparente a {  color:#ffffff!important; text-decoration: none!important;}
.menu_1 { height: 160px; padding-top: 0px; font-family: graviola_softlight; font-size: 15px; background: linear-gradient(to right, #fdfdfd , #ebeff0); }
.menu_1 a { color:#052742!important; }
.menu_1 .logo_menu_1 { display:block; } .menu_1 .logo_menu_2, .menu_1 .boton_transparente { display:none; } 

.menu_8 { height: 160px; padding-top: 0px; font-family: graviola_softlight; font-size: 15px; background: #ffffff; }
.menu_8 a { color:#052742!important; }
.menu_8 .logo_menu_1 { display:block; } .menu_8 .logo_menu_2, .menu_8 .boton_transparente { display:none; } 


.menu_2 { background-image: url("../../images/zarpe_fondo40.jpg"); background-position: -10px 0px; font-family: graviola_softlight; font-size: 15px; 
    background-repeat: no-repeat; background-size: 1400px  ; height: 650px; padding-top: 0px;   }
.menu_2 a { color:#ffffff!important; }
.menu_2 .logo_menu_2 { display:block; } .menu_2 .logo_menu_1 { display:none; }

.menu_3 { background-image: url("../../images/zarpe_fondo45.jpg"); background-position: -10px 0px; font-family: graviola_softlight; font-size: 15px; 
    background-repeat: no-repeat; background-size: 1400px  ; height: 650px; padding-top: 0px;   }
.menu_3 a { color:#ffffff!important; }
.menu_3 .logo_menu_2 { display:block; } .menu_3 .logo_menu_1, .menu_3 .boton_transparente { display:none; }

.menu_4 { background-image: url("../../images/zarpe_fondo48.jpg"); background-position: -10px 0px; font-family: graviola_softlight; font-size: 15px; 
    background-repeat: no-repeat; background-size: 1400px  ; height: 650px; padding-top: 0px;   }
.menu_4 a { color:#ffffff!important; }
.menu_4 .logo_menu_2 { display:block; } .menu_4 .logo_menu_1, .menu_4 .boton_transparente { display:none; }

.menu_5 { height: 160px; padding-top: 0px; font-family: graviola_softlight; font-size: 15px; background-color:#f0f1f3; }
.menu_5 a { color:#052742!important; }
.menu_5 .logo_menu_1 { display:block; } .menu_5 .logo_menu_2, .menu_5 .boton_transparente { display:none; } 

.menu_6 { background-image: url("../../images/zarpe_fondo50.jpg"); background-position: -10px 0px; font-family: graviola_softlight; font-size: 15px; 
    background-repeat: no-repeat; background-size: 1400px  ; height: 640px; padding-top: 0px;   }
.menu_6 a { color:#ffffff!important; }
.menu_6 .logo_menu_2 { display:block; } .menu_6 .logo_menu_1, .menu_6 .boton_transparente { display:none; }

.menu_7 { background-image: url("../../images/zarpe_fondo52.jpg"); background-position: -10px 0px; font-family: graviola_softlight; font-size: 15px; 
    background-repeat: no-repeat; background-size: 1400px  ; height: 650px; padding-top: 0px;   }
.menu_7 a { color:#ffffff!important; }
.menu_7 .logo_menu_2 { display:block; } .menu_7 .logo_menu_1, .menu_7 .boton_transparente { display:none; }



.ancho_video { width:90%; max-width:720px; height:400px; padding:14px; }
.ancho_video_social { margin-top:-165px; margin-left:770px;  }
.ancho_video_social2 { margin-top:-195px; margin-left:770px;  }
.ancho_video_social_icono  { width:32px; } 

.ancho_productos { padding:20px; float:left; width:25%; vertical-align: baseline; }
.ancho_productos2 { padding:20px; float:left; width:33%; vertical-align: baseline; }
.ancho_productos3 { width:40%; }
.ancho_productos4 { width:58%; }
.boton_celeste { background: #a4cde1 !important;  margin:10px;  padding:12px; width:170px!important;  border-radius:30px;  }
.boton_celeste2 { background: #a0bbd6; margin:10px; font-family: graviola_softmedium_italic; 
                  padding:12px; border-radius:30px; text-decoration:none!important; font-size: 28px;letter-spacing: -1px;}
.boton_celeste4 { background: #a4cde1 !important;  margin:10px;  padding:8px; width:170px!important; padding-left:20px; padding-right:20px;  
                  text-decoration:none!important; border-radius:30px;  }


.ancho_flecha { width:170px; }
.ancho_zarpe1 { width:380px; }
.ancho_zarpe2 { width:230px; }
.ancho_zarpe3 { width:640px; }

.ancho_zarpe10 { width:24%; float:left; text-align:left; padding:15px; padding-top:30px; line-height:30px;}
.ancho_zarpe11 { width:48%; float:left; text-align:left; padding:15px; padding-top:30px; line-height:30px;}
.ancho_zarpe12 { width:24%; float:left; padding:15px; padding-top:30px; line-height:30px;}

.ancho_zarpe20 { width:20%; float:left; text-align:left; padding:5px; padding-top:0px; line-height:30px;}
.ancho_zarpe21 { width:20%; float:left; text-align:left; padding:5px; padding-top:44px; line-height:30px;}
.ancho_zarpe22 { width:30%; float:left; text-align:left; padding:5px; padding-top:44px; line-height:30px;}
.ancho_zarpe23 { width:30%; float:left; text-align:left; padding:5px; padding-top:44px; line-height:30px;}

.ancho_zarpe30 { width:30%; float:left; text-align:left; padding:5px; }
.bajar_movil { margin-top:20px; }

.ancho_popup { width:600px; text-align:left; }
.ancho_icono_carrito { width:25px;}
.ancho_carrito_boton { background:#ffffff; border-radius:9px;width:55px;text-align:center;display: inline-block; height: 23px; margin-left:5px;}

.zarpe_float_movil { float:left; width:240px; margin:30px; } 
.zarpe_imagen_productos { width:100%; max-width:210px;  }
.fondo_blanco_verde  { background: #ffffff;  }
.margen_izq9 {margin-left:-100px!important; width:290px!important; min-width: 290px!important;}


@media (min-width: 1001px) and (max-width: 1300px)  { 
.menu_7, .menu_6 ,.menu_3, .menu_4 { height: 670px; padding-top: 0px;   }   
.boton_transparente { margin-top:500px; }
}
@media (min-width: 801px) and (max-width: 1000px)  { 
.menu_7, .menu_6 ,.menu_3, .menu_4  { height: 520px; padding-top: 0px; margin-bottom: 20px;  }   
.boton_transparente { margin-top:500px; }
}
@media (min-width: 769px) and (max-width: 800px)  { 
.menu_7, .menu_6 ,.menu_3, .menu_4  { height: 500px; padding-top: 0px;  margin-bottom: 20px; }   
.boton_transparente { margin-top:500px; }
}
@media (min-width: 500px) and (max-width: 768px)  { 
.menu_7, .menu_6 ,.menu_3, .menu_4  { height: 450px; padding-top: 0px; }   
.boton_transparente { margin-top:500px; }
}

/*  Ancho imagen de fondo */
@media (min-width: 1200px) and (max-width: 8000px)  { 
.menu_7, .menu_6 ,.menu_3, .menu_4  { background-size: 108%!important ; padding-top: 0px;   }   
.boton_transparente { margin-top:500px; }
}
@media (min-width: 500px) and (max-width: 1200px)  { 
.menu_7, .menu_6 ,.menu_3, .menu_4  { background-size: 108% !important ;   }   
.boton_transparente { margin-top:500px; }
.menu_padding { margin-left:11px; float:left; width:100px; margin-right:11px; text-decoration:none; margin-top:10px; margin-bottom:10px;}
}



@media (min-width: 1400px) and (max-width: 1600px)  { 
.menu_2 { background-size: 1600px !important ; height: 750px; padding-top: 0px;   }
.menu_7, .menu_6,.menu_4,.menu_3 { height: 750px; padding-top: 0px;   }   
.boton_transparente { margin-top:500px; }
}

@media (min-width: 1601px) and (max-width: 1750px)  { 
.menu_2 { background-size: 1750px !important ; height: 800px; padding-top: 0px;   }
.menu_7, .menu_6,.menu_4,.menu_3  { height: 800px; padding-top: 0px;   }

.boton_transparente { margin-top:540px; }
}


@media (min-width: 1751px) and (max-width: 2000px)  { 
.menu_2 { background-size: 2000px !important ; height: 870px; padding-top: 0px;   }
.menu_7, .menu_6,.menu_4,.menu_3  { height: 870px; padding-top: 0px;   }
.boton_transparente { margin-top:600px; }
}

@media (min-width: 2001px) and (max-width: 8000px)  { 
.menu_2 { background-size: 2000px !important ; height: 870px; padding-top: 0px;   }
.menu_7, .menu_6,.menu_4,.menu_3  { height: 900px; padding-top: 0px;   }   
.boton_transparente { margin-top:600px; }
}

.ancho_footer1 { float:left; text-align:left; width:40%; margin-top:40px; }
.ancho_footer2 { float:right; text-align:right; width:40%; margin-top:40px; }
.linea_alto { height:180px; }
.subir_tablet5 { margin-top:20px;  } 
.suscripcion_letra { width:40px; background:#d6d7d9; padding:7px; border-radius:110px; float:left; margin-left:-20px; } 
.icono_social { width:29px; }
.icono_social2 { width:38px; }


/*  Movil   and (orientation : portrait) */
@media (max-device-width: 1200px)  {
.menu_1 { display:none; }
.menu_1 .logo_menu_2 { display:none; } .menu_1 .logo_menu_1 { display:none; }  

.menu_2 { background-image: url("../../images/zarpe_fondo40_movil.jpg"); background-repeat: no-repeat; background-position: 0px 0px; 
          background-size: 100% !important; padding-top: 0px; height: 547px; }
.menu_2 .logo_menu_2 { display:none; } .menu_2 .logo_menu_1 { display:none; }

.menu_3 { background-image: url("../../images/zarpe_fondo45_movil.jpg"); background-repeat: no-repeat; background-position: 0px 0px; 
          background-size: 100% !important; padding-top: 0px; height: 547px; }
.menu_3 .logo_menu_2 { display:none; } .menu_3 .logo_menu_1 { display:none; }

.menu_4 { background-image: url("../../images/zarpe_fondo48_movil.jpg"); background-repeat: no-repeat; background-position: 0px 0px; 
          background-size: 100% !important; padding-top: 0px; height: 547px; }
.menu_4 .logo_menu_2 { display:none; } .menu_4 .logo_menu_1 { display:none; }

.menu_5 { display:none; }
.menu_5 .logo_menu_2 { display:none; } .menu_5 .logo_menu_1 { display:none; }

.menu_6 { background-image: url("../../images/zarpe_fondo50_movil.jpg"); background-repeat: no-repeat; background-position: 0px 0px; 
          background-size: 100% !important; padding-top: 0px; height: 547px; }
.menu_6 .logo_menu_2 { display:none; } .menu_6 .logo_menu_1 { display:none; }
 
.menu_7 { background-image: url("../../images/zarpe_fondo52_movil.jpg"); background-repeat: no-repeat; background-position: 0px 0px; 
          background-size: 100% !important; padding-top: 0px; height: 547px; }
.menu_7 .logo_menu_2 { display:none; } .menu_7 .logo_menu_1 { display:none; }

.menu_8 { display:none; }
.menu_8 .logo_menu_2 { display:none; } .menu_8 .logo_menu_1 { display:none; }         

.margen_izq9 {margin-left:-210px!important; width:290px!important; min-width: 290px!important;} 

.ancho_video { width:90%; max-width:570px; height:340px; padding:7px; } 
.ancho_video_social { margin-top:-175px; margin-left:630px;  width: 30px; } 
.ancho_video_social2 { margin-top:-172px; margin-left:630px; width: 30px; }  
.ancho_video_social_icono  { width:22px; }  
.subir_tablet { margin-top:-670px;  }         
.bajar_tablet { margin-top:110px;  }

.ancho_productos { padding:10px; float:left; width:25%; }
.ancho_productos2 { padding:10px; float:left; width:33%; }
.ancho_footer1 { float:left; text-align:center; width:100%; margin-top:0px;} 
.ancho_productos3 { width:44%;  }
.ancho_productos4 { width:53%;  }

.boton_celeste { background: #a4cde1 !important;  margin:5px;  padding:10px; width:130px!important;  border-radius:30px; margin-top:30px;  }
.boton_celeste2 { margin:5px; padding:8px; border-radius:30px; text-decoration:none!important; font-size: 18px;}
.boton_celeste3 { background: #a4cde1 !important;  margin:10px;  padding:12px; width:170px!important;  border-radius:30px;  }
.boton_celeste4 { background: #a4cde1 !important;  margin:10px;  padding:7px; width:170px!important; padding-left:20px; padding-right:20px;
                  text-decoration:none!important; border-radius:30px;  }
                  
.ancho_zarpe1 { width:100%; }
.ancho_zarpe2 { width:80%; }
.ancho_zarpe3 { width:640px; }
.zarpe_float_movil { float:none; width:50%; } 

.campo_texto_zarpe_select4 {width:210px!important;border-radius:40px;margin-top:10px;margin-bottom:6px; background:#ffffff; 
                     padding-left:18px; padding-right:8px; padding-top:7px!important; padding-bottom:4px; height:38px!important;
                            background-position:
                            calc(100% - 16px) calc(1em - 6px),
                            calc(100% - 15px) calc(1em + 2px),
                            calc(100% - 2.5em) 0.5em!important; background-repeat: no-repeat;}
.campo_texto_zarpe_select5 { width:60px!important;border-radius:40px;border:0px solid #ADAEB0;margin-top:20px!important;margin-bottom:8px; 
                     margin-left:5px; color:#58595B; padding-left:15px!important; padding-right:10px; padding-top:4px!important; padding-bottom:2px; 
                     height:30px!important;  background:#ffffff;  
                     background-image: url("../../images/zarpe_flecha7b.png")!important; 
                            background-position:
                            calc(100% - 10px) calc(1em - 4px),
                            calc(100% - 15px) calc(1em + 2px),
                            calc(100% - 2.5em) 0.5em!important; background-repeat: no-repeat; background-size: 10px 7px;  }
                            

.zarpe_imagen_productos_margen { margin-left:354px!important; }  
.ancho_zarpe12 { width:34%;}
.ancho_zarpe11 { width:42%; }    
.ancho_zarpe22 { width:40%; float:left; text-align:left; padding:5px; padding-top:24px; line-height:30px;}
.ancho_zarpe23 { width:40%; float:left; text-align:left; padding:5px; padding-top:47px; line-height:30px;}
.linea_alto { height:120px; }    
.bajar_movil { margin-top:0px; }    
.dropdown-menu { min-width: 130px!important; margin-left: -120px!important }

.zarpe_transicion_panel {float:right; position:absolute; top:450px; right:320px; padding:9px;  }
.zarpe_transicion_panel_padding {padding:20px; border:1px solid #8193a1  } 
.zarpe_transicion_boton {float:right; position:absolute; top:1180px; left:24%; }


}



@media (max-device-width: 768px)  {

.zarpe_imagen_productos_margen { margin-left:230px!important; }  
.subir_tablet { margin-top:-500px;  } 
.bajar_tablet { margin-top:70px;  }
.ancho_video { width:90%; max-width:410px; height:230px; padding:7px; } 
.ancho_video_social { margin-top:-145px; margin-left:400px; width: 30px; } 
.ancho_video_social2 { margin-top:-142px; margin-left:450px;  width: 30px;}  
.ancho_video_social_icono  { width:18px; }  
.menu_3, .menu_4, .menu_6 { height: 450px; } 
.margen_izq9 {margin-left:-110px!important; width:290px!important; min-width: 290px!important;} 
.ancho_zarpe22 { width:40%; float:left; text-align:left; padding:5px; padding-top:14px; line-height:30px;}
.ancho_zarpe23 { width:40%; float:left; text-align:left; padding:5px; padding-top:48px; line-height:30px;}
.ancho_popup { width:500px; }
.ancho_zarpe30 { width:90%; float:left; text-align:left; padding:5px; }

.zarpe_transicion_panel {float:right; position:absolute; top:360px; right:195px; padding:7px; }
.zarpe_transicion_panel_padding {padding:16px; border:1px solid #8193a1; } 
.zarpe_transicion_boton {float:right; position:absolute; top:880px; left:22%; }
}               

 
  
@media (max-device-width: 425px)  {
.menu_2 { height: 280px; }
.menu_3, .menu_4, .menu_5 { height: 252px; } 
.menu_6 { height: 306px; } 
.menu_7 { height: 320px; } 
.subir_tablet { margin-top:-275px;  } 
.bajar_tablet { margin-top:65px;  }   
.ancho_productos { padding:8px; float:left; width:24%; } 
.ancho_productos2 { padding:8px; float:left; width:33%; }    
.ancho_productos3 { width:32%;  } 
.ancho_productos4 { width:44%;  }
.texto_22 { font-size: 9px; line-height:9px; }
.campo_texto_zarpe_select4 {width:160px!important;border-radius:40px;margin-top:10px;margin-bottom:6px; 
                     padding-left:18px; padding-right:8px; padding-top:3px!important; padding-bottom:4px; height:32px!important;
                            background-position:
                            calc(100% - 16px) calc(1em - 5px),
                            calc(100% - 15px) calc(1em + 2px),
                            calc(100% - 2.5em) 0.5em!important; background-repeat: no-repeat;}
                            
.campo_texto_zarpe_select5 { width:46px!important;border-radius:40px;border:0px solid #ADAEB0;margin-top:2px!important;margin-bottom:8px; 
                     margin-left:5px; color:#58595B; padding-left:10px!important; padding-right:10px; padding-top:1px!important; padding-bottom:2px; 
                     height:24px!important;
                     background-image: url("../../images/zarpe_flecha7b.png")!important; 
                            background-position:
                            calc(100% - 6px) calc(1em - 6px),
                            calc(100% - 15px) calc(1em + 2px),
                            calc(100% - 2.5em) 0.5em!important; background-repeat: no-repeat; background-size: 10px 7px;  }
.ancho_flecha { width:100px; }
.ancho_zarpe3 { width:380px; }

.zarpe_float_movil { float:none; width:54%; line-height: 1;} 

.zarpe_imagen_productos { width:100%; max-width:210px;  }
.zarpe_imagen_productos_margen { margin-left:82px!important; }
.boton_celeste3 { background: #a4cde1 !important;  margin:10px;  padding:12px; width:170px!important;  border-radius:30px;  }

.ancho_zarpe10 { width:100%; float:left; text-align:center; padding:0px; line-height:25px;}
.ancho_zarpe11 { width:100%; float:left; text-align:center; padding:0px; line-height:25px;}
.ancho_zarpe12 { width:100%; float:left; padding:0px; line-height:25px;}

.ancho_zarpe20 { width:100%; float:left; text-align:center; padding:5px; padding-top:0px; line-height:10px; padding-left:110px; padding-right:110px;}
.ancho_zarpe21 { width:100%; float:left; text-align:center; padding:5px; padding-top:0px; line-height:5px;}
.ancho_zarpe22 { width:100%; float:left; text-align:center; padding:5px; padding-top:0px; line-height:5px;}
.ancho_zarpe23 { width:100%; float:left; text-align:center; padding:5px; padding-top:0px; line-height:5px;}

.ancho_video { width:90%; max-width:300px; height:175px; padding:7px; } 
.ancho_video_social { margin-top:-145px; margin-left:330px;  } 
.ancho_video_social2 { margin-top:-142px; margin-left:330px;  }  
.ancho_video_social_icono  { width:18px; }  
.subir_tablet { margin-top:-270px;  } 

.fondo_blanco_verde  { background: rgba(255, 255, 255, .0)!important;;  }
.paquete_off { margin:8px;  }
.boton_celeste { background: #a4cde1 !important;  margin:5px;  padding:4px; width:90px!important;  border-radius:30px; margin-top:30px;  }
.boton_celeste2 { margin:5px; padding:4px; padding-left:8px; padding-right:8px; border-radius:30px; text-decoration:none!important; font-size: 12px;}
.boton_celeste4 { background: #a4cde1 !important;  margin:10px;  padding:7px; width:170px!important; padding-left:20px; padding-right:20px;
                  text-decoration:none!important; border-radius:30px;  }
.zarpe_transicion_boton {float:right; position:absolute; top:480px; left:10%; }
.margen_izq9 {margin-left:-110px!important; width:290px!important; min-width: 290px!important;}
.linea_alto { height:100px; } 
.subir_tablet5 { margin-top:3px!important;  }
.suscripcion_letra { width:30px; background:#d6d7d9; padding:2px; border-radius:110px; float:left; margin-left:-10px; }
.ancho_popup { width:390px; }
.dropdown-menu { width: 100%!important;padding-left: 10px!important; padding: 10px 5px!important; min-width: 230px!important;
    margin-left: -120px!important;}
.ancho_icono_carrito { width:18px;}
.ancho_carrito_boton { background:#ffffff; border-radius:9px;width:45px;padding-left: 5px;display: inline-block; height: 22px; margin-left:-5px;}
.zarpe_transicion_panel {float:right; position:absolute; top:180px; right:62px; padding:5px; }
.zarpe_transicion_panel_padding {padding:7px; border:1px solid #8193a1  } 
.icono_social { width:22px; }
.icono_social2 { width:30px; }
}



@media (max-device-width: 375px)  {
.menu_2 { height: 246px; }
.menu_3, .menu_4, .menu_5 { height: 220px; }
.menu_6 { height: 276px; } 
.ancho_video { width:90%; max-width:260px; height:153px;  } 
.ancho_video_social { margin-top:-140px; margin-left:290px;  } 
.ancho_video_social2 { margin-top:-140px; margin-left:290px;  }  
.ancho_video_social_icono  { width:18px; }     
.subir_tablet { margin-top:-245px;  }
.bajar_tablet { margin-top:40px;  } 
.ancho_flecha { width:50px; }
.ancho_zarpe3 { width:320px; }
.zarpe_imagen_productos_margen { margin-left:60px!important; }
.zarpe_transicion_boton {float:right; position:absolute; top:430px; left:10%; }
.margen_izq9 {margin-left:-130px!important; width:290px!important; min-width: 290px!important;}
.campo_texto_zarpe_select5 { width:45px!important;border-radius:40px;border:0px solid #ADAEB0;margin-top:2px!important;margin-bottom:8px; 
                     margin-left:5px; color:#58595B; padding-left:10px!important; padding-right:10px; padding-top:0px!important; padding-bottom:2px; 
                     height:22px!important; background-image: url("../../images/zarpe_flecha7b.png")!important; 
                     background-position:
                     calc(100% - 6px) calc(1em - 6px),
                     calc(100% - 15px) calc(1em + 2px),
                     calc(100% - 2.5em) 0.5em!important; background-repeat: no-repeat; background-size: 10px 7px;  }
.boton_celeste2 { margin:3px; padding:4px; padding-left:8px; padding-right:8px; border-radius:30px; text-decoration:none!important; font-size: 11px;}
.zarpe_float_movil { float:none; width:64%; line-height: 1;}  
.ancho_popup { width:340px; }
.suscripcion_letra { width:25px; background:#d6d7d9; padding:2px; border-radius:110px; float:left; margin-left:-7px; } 

.zarpe_transicion_panel {float:right; position:absolute; top:150px; right:54px; padding:4px; }
.zarpe_transicion_panel_padding {padding:5px; border:1px solid #8193a1  }  
                       
}



@media (max-device-width: 320px)  {
.menu_2 { height: 210px; }
.menu_3, .menu_4, .menu_5 { height: 190px; }
.menu_6 { height: 238px; } 
.ancho_video { width:90%; max-width:240px; height:143px; } 
.ancho_video_social { margin-top:-126px; margin-left:270px;  }  
.ancho_video_social2 { margin-top:-130px; margin-left:270px;  }  
.ancho_video_social_icono  { width:14px; }
.subir_tablet { margin-top:-210px;  }  
.subir_tablet5 { margin-top:-40px;  }  
.bajar_tablet { margin-top:0px;  } 
.bajar_tablet2 { margin-top:30px;  } 
.boton_celeste2 { margin:2px; padding:2px; border-radius:20px; text-decoration:none!important; font-size: 10px; padding-left:8px; padding-right:8px; }
.ancho_zarpe3 { width:300px; }

.dropdown-menu > li > a { line-height: 0.8!important;}
.zarpe_imagen_productos_margen { margin-left:35px!important; }
.ancho_zarpe20 { width:100%; float:left; text-align:center; padding:5px; padding-top:0px; line-height:10px; padding-left:80px; padding-right:80px;}
.zarpe_transicion_boton {float:right; position:absolute; top:360px; left:10%; }
.margen_izq9 {margin-left:-130px!important; width:290px!important; min-width: 290px!important;}
.campo_texto_zarpe_select5 { width:45px!important;border-radius:40px;border:0px solid #ADAEB0;margin-top:2px!important;margin-bottom:8px; 
                     margin-left:5px; color:#58595B; padding-left:10px!important; padding-right:10px; padding-top:2px!important; padding-bottom:2px; 
                     height:22px!important; background-image: url("../../images/zarpe_flecha7b.png")!important; 
                     background-position:
                     calc(100% - 6px) calc(1em - 6px),
                     calc(100% - 15px) calc(1em + 2px),
                     calc(100% - 2.5em) 0.5em!important; background-repeat: no-repeat; background-size: 10px 7px;  }
.zarpe_float_movil { float:none; width:72%; line-height: 1;} 
.ancho_popup { width:300px; }
.suscripcion_letra { width:23px; background:#d6d7d9; padding:2px; border-radius:110px; float:left; margin-left:-7px; }
.dropdown-menu { width: 100%!important;padding-left: 10px!important; padding: 10px 5px!important;}

.zarpe_transicion_panel {float:right; position:absolute; top:120px; right:47px; padding:4px; }
.zarpe_transicion_panel_padding {padding:2px; border:1px solid #8193a1  }

.radio_button_plan_texto4 {  margin-left: 0px!important;}
}



.bajar_tablet4 { margin-top:-200px;}  

/* OTRAS resoluciones */
@media (min-device-width: 426px) and (max-device-width: 1023px) {  
.ancho_zarpe3 { width:96%; }
.subir_tablet { margin-top: -60%!important; }
.ancho_video { width: 90%; max-width: 350px; }

.menu_2 { height: 100%; }
.boton_transparente { margin-top: 50%; margin-bottom: 40px; }

}  



@media (min-device-width: 426px) and (max-device-width: 600px) {  
.menu_3, .menu_4, .menu_6, .menu_7 { height: 100%; min-height: 260px;}
.ancho_video_social { margin-top: -145px;  margin-left: 94%;}
.ancho_video_social2 { margin-top: -145px; margin-left: 94%;}
.bajar_tablet2 { margin-top: -25%;}
.bajar_tablet3 { margin-top: 11%!important;}
.campo_texto_zarpe_3 { width: 220px!important; margin-top: 4px!important; margin-bottom: 5px!important; font-size: 12px!important; 
                       height: 30px!important;}
                       
.bajar_tablet4 { margin-top: -26%!important;}   
.zarpe_imagen_productos_margen { margin-left: 44%!important;}               
.zarpe_imagen_productos { max-width: 240px; width: 240px;}

.ancho_zarpe20, .ancho_zarpe21, .ancho_zarpe23 { width: 100%; float: left; text-align: center; padding: 5px; padding-top: 0px; line-height: 5px;}
} 
 

@media (min-device-width: 601px) and (max-device-width: 767px) {  
.menu_3, .menu_4, .menu_6, .menu_7 { height: 100%; min-height: 330px;}
.ancho_video_social { margin-top: -165px;  margin-left: 83%;}
.ancho_video_social2 { margin-top: -145px; margin-left: 83%;}
.bajar_tablet2 { margin-top: -25%;}
.bajar_tablet3 { margin-top: 7%!important;}
.campo_texto_zarpe_3 { width: 220px!important; margin-top: 4px!important; margin-bottom: 5px!important; font-size: 12px!important; 
                       height: 30px!important;}
                       
.bajar_tablet4 { margin-top: -20%!important;} 
.zarpe_imagen_productos_margen { margin-left: 56%!important;}               
.zarpe_imagen_productos { max-width: 240px; width: 240px;}
} 
  
@media (min-device-width: 769px) and (max-device-width: 1023px) {  
.bajar_tablet2 { margin-top: -10%;}
.menu_3, .menu_4, .menu_6 { height: 100%; min-height: 350px; margin-bottom: 0px;}
.ancho_video_social { margin-top: -185px;  margin-left: 65%;}
.ancho_video_social2 { margin-top: -185px; margin-left: 65%;}
.bajar_tablet3 { margin-top: 7%!important;}
.campo_texto_zarpe_3 { width: 220px!important; margin-top: 4px!important; margin-bottom: 5px!important; font-size: 12px!important; 
                       height: 30px!important;}
.zarpe_imagen_productos_margen { margin-left: 90%!important;}               
.zarpe_imagen_productos { max-width: 240px; width: 240px;}

.tabla_totales { width: 100% !important;}
}  
    
/* bajas resoluciones */
@media (min-width: 1px) and (max-width: 319px) {  
.no_ver_en_movil2 { display: none !important;}
.boton_transparente { margin-top: 50%; margin-bottom: 20px; width: 100%;}
.ancho_video { width: 90%; max-width: 140px; height: 130px;}
.ancho_video_social { margin-top: -126px; margin-left: 86%;}
.ancho_video_social2 { margin-top: -126px; margin-left: 86%;}
.subir_tablet { margin-top: -64%;}
.bajar_tablet3 { margin-top: 18%!important;}
.campo_texto_zarpe_3 { width: 180px!important; margin-top: 4px!important; margin-bottom: 5px!important; font-size: 12px!important; 
                       height: 30px!important;}
.menu_2 { height: 100%; }
.menu_3, .menu_4 { height: 100%; min-height: 120px; margin-bottom: 0px;}
.menu_6, .menu_7 { height: 100%; min-height: 210px; margin-bottom: 0px;}
.ancho_zarpe3 { width: 100%;}
.alinear_zarpe4 { text-align: center!important;}

.bajar_tablet4 { margin-top: -40%!important;} 
.alinear_zarpe2 { text-align: center!important;}
.zarpe_imagen_productos_margen { margin-left: 36%!important;}               
.zarpe_imagen_productos { max-width: 120px; width: 100%;} 

.tabla_totales { width: 100% !important;}
} 
 


.dropdown-menu { position: absolute; top: 100%; left: 0; z-index: 1000; display: none; float: left;
    min-width: 210px; padding: 10px 20px; margin: 2px 0 0; font-size: 15px!important; text-align: left; list-style: none;
    background-color: rgba(255, 255, 255, .8)!important; -webkit-background-clip: padding-box; background-clip: padding-box;
    border: 1px solid #ccc; border: 1px solid rgba(0, 0, 0, .15); border-radius: 4px;
    -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, .175); box-shadow: 0 6px 12px rgba(0, 0, 0, .175);
}

.dropdown-menu > li > a { display: block; padding: 3px 10px; clear: both; font-weight: normal; line-height: 1.2!important; color: #333; white-space: nowrap;}







select { 
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  -webkit-appearance: none;
  -moz-appearance: none;
}


/* arrows */

select.classic {
  background-image:
    linear-gradient(45deg, transparent 50%, blue 50%),
    linear-gradient(135deg, blue 50%, transparent 50%),
    linear-gradient(to right, skyblue, skyblue);
  background-position:
    calc(100% - 20px) calc(1em + 2px),
    calc(100% - 15px) calc(1em + 2px),
    100% 0;
  background-size:
    5px 5px,
    5px 5px,
    2.5em 2.5em;
  background-repeat: no-repeat;
}

select.classic:focus {
  background-image:
    linear-gradient(45deg, white 50%, transparent 50%),
    linear-gradient(135deg, transparent 50%, white 50%),
    linear-gradient(to right, gray, gray);
  background-position:
    calc(100% - 15px) 1em,
    calc(100% - 20px) 1em,
    100% 0;
  background-size:
    5px 5px,
    5px 5px,
    2.5em 2.5em;
  background-repeat: no-repeat;
  border-color: grey;
  outline: 0;
}




select.round {
  background-image:
    linear-gradient(45deg, transparent 50%, gray 50%),
    linear-gradient(135deg, gray 50%, transparent 50%),
    radial-gradient(#ddd 70%, transparent 72%);
  background-position:
    calc(100% - 20px) calc(1em + 2px),
    calc(100% - 15px) calc(1em + 2px),
    calc(100% - .5em) .5em;
  background-size:
    5px 5px,
    5px 5px,
    1.5em 1.5em;
  background-repeat: no-repeat;
}

select.round:focus {
  background-image:
    linear-gradient(45deg, white 50%, transparent 50%),
    linear-gradient(135deg, transparent 50%, white 50%),
    radial-gradient(gray 70%, transparent 72%);
  background-position:
    calc(100% - 15px) 1em,
    calc(100% - 20px) 1em,
    calc(100% - .5em) .5em;
  background-size:
    5px 5px,
    5px 5px,
    1.5em 1.5em;
  background-repeat: no-repeat;
  border-color: green;
  outline: 0;
}

select.minimal { 
  background-image: url("../../images/zarpe_flecha6.png"); 
  background-position:
    calc(100% - 14px) calc(1em - 5px),
    calc(100% - 15px) calc(1em + 2px),
    calc(100% - 2.5em) 0.5em;
  background-repeat: no-repeat;
}

select.minimal:focus {
  background-image: background-image: url("../../images/zarpe_flecha6.png"); 
  background-position:
    calc(100% - 14px) calc(1em - 5px),
    calc(100% - 15px) calc(1em + 2px),
    calc(100% - 2.5em) 0.5em;
  background-repeat: no-repeat;
  border-color: green;
  outline: 0;
}











.fondo_1 { background-image: url("../../images/slider_zarpe.jpg"); background-position: -10px 0px; text-align:center;
    background-repeat: no-repeat; background-size: 1460px  ; height: 580px; padding-top: 10px;   }
.fondo_2 { background-image: url("../../images/fondo_zarpe.jpg");  background-position: -60px -40px; text-align:right; background-size: 1340px 1280px ; 
     height: 550px; padding-top: 10px;  }  
.fondo_3linea { background-image: url("../../images/zarpe_linea1.jpg"); background-position: 0px -21px; text-align:center;
    background-repeat: no-repeat;   }
.fondo_4 { background-image: url("../../images/slider_zarpe.jpg"); background-position: -10px 0px; text-align:center;
    background-repeat: no-repeat; background-size: 1460px  ; height: 500px; padding-top: 10px;   }
    
.fondo_5 { background-image: url("../../images/zarpe_fondo31.jpg"); background-position: -10px 0px; text-align:center;
    background-repeat: no-repeat; background-size: 1200px  ; height: 800px; padding-top: 10px;   }
    
.form-control_2 {
  display: block; width: 100%; height: 34px; padding: 6px 12px; font-size: 14px; line-height: 1.42857; color: #555555; background-color: #fff;
  background-image: none; border: 1px solid #ccc; border-radius: 4px; 
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s; -o-transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;
  transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s; }
  
.banner_1 { background-image: url("../../images/zarpe_fondo1.jpg"); text-align:center; width:100%; max-width:670px; height:473px;}  
.banner_2 { background-image: url("../../images/zarpe_fondo2.jpg"); text-align:center; width:100%; max-width:670px; }  
.banner_3 { background-image: url("../../images/zarpe_fondo3.jpg"); text-align:center; width:100%; max-width:1600px; }  
.banner_4 { background-image: url("../../images/zarpe_fondo8.jpg"); text-align:center; width:100%; background-size: 1400px 500px;}
.banner_5 { background-image: url("../../images/zarpe_fondo10.jpg"); text-align:center; width:100%; background-size: 1200px 490px;}
.banner_6 { background-image: url("../../images/zarpe_fondo_logo1.jpg"); text-align:center; width:100%;  } 
.banner_7 { background-image: url("../../images/zarpe_fondo10.jpg"); text-align:center; width:100%; background-size: 1200px 490px;}
.banner_8 { background-image: url("../../images/zarpe_fondo24.jpg"); width:100%; background-size: 100% 900px; display: inline-block;} 
.banner_9 { background-image: url("../../images/zarpe_fondo28.jpg"); text-align:center; width:100%; background-size: 1300px 650px; 
            background-position: 0px -140px;}
.banner_10 { background-image: url("../../images/zarpe_fondofooter.jpg"); text-align:center; width:100%; background-size: 1700px 650px; 
            background-position: 0px -140px;}

.ancho_tabla_2 { width:42%; }
.ancho_tabla_compartir { width:100%; max-width:550px;}
.ancho_tabla_compartir2 { width:100%; max-width:550px;}
.ancho_mitad { width:40%; padding:10px; float:left }
.ancho_mitad2 { width:47%; margin-right:15px; float:left }
.ancho_mitad3 { width:47%; margin-left:15px; float:left }
.ancho_tabla_comentarios { width:840px;}
.popup_ancho3 { width:700px; height:380px}

.ancho_6 { width:64%; padding:2px; float:left; }
.ancho_4 { width:30%; padding:2px; float:left; margin-bottom:40px; }

.ancho_select { width:250px!important; }
.ancho_correo1 { width:36%; padding:10px; float:left; }
.ancho_correo2 { width:26%; padding:10px; float:left; margin-top:10px; }

.zarpe_videos { width:33%; max-width:400px; float:left; padding:18px; height: 350px; line-height: 1;}
.zarpe_videos2 { width:12%; max-width:220px; float:left; padding:18px; height: 450px; line-height: 1;}

.zarpe_video_popup { width:170px;}

.padding_za.rpe { padding-bottom:2px; }

.alinear_zarpe { text-align:right; }
.alinear_zarpe2 { text-align:left; }
.alinear_zarpe3 { margin-left:60px; }
.alinear_zarpe4 { text-align:right; } 

.alinear_zarpe5 { float: left; margin-left:480px; width:400px; }

.alinear_zarpe6 { float: left; }
.alinear_zarpe7 { float: right; }

.alinear_zarpe8 { text-align:right; } 


.alinear_ver_zarpe { margin-top:0px; }

.campo_texto_zarpe_3 {width:394px; border-radius:40px;border:1px solid #ADAEB0;margin-top:8px;margin-bottom:8px;font-family: graviola_softbold;
                      font-size:16px; padding-top:4px; color:#58595B; background:#ffffff; height:48px;}
.campo_texto_zarpe_3:read-only, .campo_texto_zarpe_3:disabled {background:#CFD1DD; color:#58595B; }

.campo_texto_zarpe {width:100%;border-radius:40px;border:1px solid #ADAEB0;margin-top:8px;margin-bottom:8px;font-family: graviola_softbold;font-size:16px;
                     color:#58595B; padding-left:20px; padding-right:20px; padding-top:7px; padding-bottom:5px; background:#ffffff; height:48px;}
.campo_texto_zarpe:read-only, .campo_texto_zarpe:disabled {background:#F0F0F0; color:#58595B; }
.campo_texto_zarpe_select {width:100%;border-radius:40px;border:1px solid #ADAEB0;margin-top:8px;margin-bottom:8px;font-family: graviola_softbold;font-size:19px;
                     color:#58595B; background:#F0F0F0; padding-left:20px; padding-right:20px; padding-top:7px; padding-bottom:5px; height: auto!important;}
.campo_texto_zarpe_select:disabled {width:100%;border-radius:40px;border: 1px solid #ADAEB0;margin-top:8px;margin-bottom:8px;font-family: graviola_softbold;font-size:19px;
                     color:#58595B; background:#EFF0F2; padding-left:20px; padding-right:20px; padding-top:7px; padding-bottom:5px; height: auto!important;}
.campo_texto_zarpe_select2 {width:100%;border-radius:40px;border:1px solid #ADAEB0;margin-top:8px;margin-bottom:8px;font-family: graviola_softbold;
                            font-size:19px; background-size: 44px 30px!important; background-position:7px 5px!important;
                     color:#58595B; background-image: url("../../images/icono_colocacion.jpg")!important; background-repeat: no-repeat!important; 
                     background:#F0F0F0; padding-left:50px; padding-right:20px; padding-top:7px; padding-bottom:5px; height: auto!important;}
                     
.campo_texto_zarpe_2 {width:100%;border-radius:40px;border:1px solid #d9d9d9;margin-top:8px;margin-bottom:8px;font-family: graviola_softbold;
                      font-size:15px;color:#58595B; padding-left:20px; padding-right:20px; padding-top:6px; padding-bottom:5px; background:#ffffff;
                      height:40px;}
.campo_texto_zarpe_select_3 {width:70%;border-radius:40px;border:1px solid #d9d9d9;margin-top:8px;margin-bottom:8px;font-family: graviola_softbold;font-size:15px;
                     color:#58595B; background:#ffffff; padding-left:20px; padding-right:20px; padding-top:7px; padding-bottom:5px; height: auto!important;}
.campo_texto_zarpe_select_3:disabled {width:70%;border-radius:40px;border:0px solid #d9d9d9;margin-top:8px;margin-bottom:8px;font-family: graviola_softbold;font-size:19px;
                     color:#58595B; background:#ffffff; padding-left:20px; padding-right:20px; padding-top:7px; padding-bottom:5px; height: auto!important;}                    

.campo_texto_zarpe_select4 {width:220px;border-radius:40px;border:0px solid #ADAEB0;margin-top:12px;margin-bottom:8px; 
                     color:#58595B; padding-left:20px; padding-right:10px; padding-top:6px; padding-bottom:5px; height:38px;
                      background-image: url("../../images/zarpe_flecha7.png"); 
                            background-position:
                            calc(100% - 14px) calc(1em - 15px),
                            calc(100% - 15px) calc(1em + 2px),
                            calc(100% - 2.5em) 0.5em; background-repeat: no-repeat;}
.campo_texto_zarpe_select4:disabled {width:100%;border-radius:40px;border:0px solid #cdcdcd;
                     color:#58595B; padding-left:20px; padding-right:10px; padding-top:2px; padding-bottom:5px; height:38px;}



.campo_texto_zarpe_select5 {width:80px;border-radius:40px;border:0px solid #ADAEB0;margin-top:12px;margin-bottom:8px; 
                     color:#58595B; padding-left:20px; padding-right:10px; padding-top:6px; padding-bottom:5px; height:38px;
                      background-image: url("../../images/zarpe_flecha7.png"); 
                            background-position:
                            calc(100% - 14px) calc(1em - 15px),
                            calc(100% - 15px) calc(1em + 2px),
                            calc(100% - 2.5em) 0.5em; background-repeat: no-repeat;}
.campo_texto_zarpe_select5:disabled {width:80px;border-radius:40px;border:0px solid #cdcdcd;
                     color:#58595B; padding-left:20px; padding-right:10px; padding-top:2px; padding-bottom:5px; height:38px;}
                                          
                                                           
.check_button_zarpe > input[type=checkbox] + label { padding-left:54px !important; padding-top:15px!important; height:42px; text-align: left;
background-image: url("../../images/check_box_zarpe_off.png")!important; background-repeat: no-repeat; font-weight:normal; background-size: 52px 46px; }
.check_button_zarpe {text-align:center; margin-left:14px!important;margin-right:10px !important; }
.check_button_zarpe > input[type=checkbox]  {display:none;} 
.check_button_zarpe > input[type=checkbox]:checked + label,
.check_button_zarpe:hover > input[type=checkbox]:checked + label {
background-image: url("../../images/check_box_zarpe_on.png")!important; background-repeat: no-repeat;}



.check_button_zarpe2 > input[type=checkbox] + label  {padding-top:5px!important; padding-left:22px; padding-right:22px; font-size:18px; 
border: 1px solid #ADAEB0; padding-top:4px;padding-bottom: 3px; border-radius:14px; color:#6F6F71; } 
.check_button_zarpe2 {text-align:center;  }
.check_button_zarpe2 > input[type=checkbox]  {display:none;} 
.check_button_zarpe2> input[type=checkbox]:checked + label,
.check_button_zarpe2 > input[type=checkbox]:checked + label {
background: #036B3A!important; color:#ffffff; border:1px solid rgba(0,0,0,0);
background: -moz-linear-gradient(left,  #4EB657 0%, #1CA297 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #4EB657), color-stop(100%, #1CA297))!important;
background: -webkit-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -o-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -ms-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: linear-gradient(to right, #4EB657 0%, #1CA297 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4EB657', endColorstr='#1CA297', GradientType=1 )!important;
padding-left:22px; padding-right:22px; padding-top:4px;padding-bottom: 3px; text-align:center; text-decoration: none!important;}

.check_button_zarpe3 > input[type=checkbox] + label { padding-left:44px !important; padding-top:10px!important; height:44px; text-align: left;
background-image: url("../../images/check_box_zarpe2_off.jpg")!important; background-repeat: no-repeat;  background-size: 40px 32px; }
.check_button_zarpe3 {text-align:center; margin-left:14px!important;margin-right:10px !important; }
.check_button_zarpe3 > input[type=checkbox]  {display:none;} 
.check_button_zarpe3 > input[type=checkbox]:checked + label,
.check_button_zarpe3:hover > input[type=checkbox]:checked + label {
background-image: url("../../images/check_box_zarpe2_on.jpg")!important; background-repeat: no-repeat;}


.check_button_zarpe4 {
    text-align: center;
    margin-left: 0px!important;
    margin-right: 10px !important;
    background-image: url("../../images/check_box_zarpe222_off.jpg"); 
    width: 26px; height: 50px; display: block; margin-top: 16px;
}

.check_button_zarpe4.checked { text-align: center;
    margin-left: 14px!important;
    margin-right: 10px !important;
    background-image: url("../../images/check_box_zarpe222_on.jpg")!important;
    width: 50px; height: 50px; display: block; margin-top: 16px;
}

.check_button_zarpe4 > input[type=checkbox]  {} 
.check_button_zarpe4 > input[type=checkbox]:checked + label,
.check_button_zarpe4:hover > input[type=checkbox]:checked + label:before {
text-align: center;
    margin-left: 14px!important;
    margin-right: 10px !important;
    background-image: url("../../images/check_box_zarpe222_on.jpg")!important; 
    width: 50px;
    height: 50px;
    display: block;}

    
    

.radio_button_plan_texto6 {text-align:center; margin-top:18px!important; margin-left:8px!important;margin-right:0px !important; font-size: 17px;}
.radio_button_plan_texto6 > input[type=radio]  {display:none;}
.radio_button_plan_texto6 > input[type=radio] + label {font-family:'Montserrat'!important;font-weight: normal;width:120px!important;
padding-top:5px!important;text-align:center; background:#999999; color:#ffffff; border: 1px solid #ADAEB0; min-height:36px; border-radius:14px; }  
.radio_button_plan_texto6 > input[type=radio]:checked + label,
.radio_button_plan_texto6:hover > input[type=radio]:checked + label {border:1px solid rgba(0,0,0,0);min-height:36px; color:#ffffff;
background: #036B3A; font-family: 'Montserrat'!important; font-weight: normal;
background: -moz-linear-gradient(left,  #4EB657 0%, #1CA297 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #4EB657), color-stop(100%, #1CA297))!important;
background: -webkit-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -o-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -ms-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: linear-gradient(to right, #4EB657 0%, #1CA297 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4EB657', endColorstr='#1CA297', GradientType=1 )!important;}  
.radio_button_plan_texto6 > input[type=radio]:hover + label { min-height:36px; border-radius:14px; border:1px solid rgba(0,0,0,0) }



.boton_zarpe1 { background: #dcdcdc; border:0px solid #cdcdcd; border-radius:100px; padding:4px; color:#052844; padding-left:10px; padding-right:10px; text-align:center; }
.boton_zarpe2 { background: #BBDBD6; border-radius:100px; padding:10px; color:#052844; padding-left:15px; padding-right:15px; }
.boton_zarpe3 { background: #052844; border-radius:100px; padding:10px; color:#ffffff; font-size: 16px;font-family: graviola_softheavy; 
                padding-left:15px; padding-right:15px; width:260px; display: block; text-decoration: none!important;}
.boton_zarpe4 { background: #E6EAED; color:#1E5E8C; text-decoration: none!important; letter-spacing: -1px;
font-family: graviola_softmedium_italic; font-size:18px; border-radius:40px!important;border:0px solid rgba(0,0,0,0)!important;
padding-top:8px;padding-bottom: 8px; padding-left:18px; padding-right:18px;}
.boton_zarpe4:hover, .boton_zarpe4:focus { background: #DBDBE3!important; color:#5A595E; } 
.boton_zarpe5 { background: #8CB743; border-radius:20px; padding:4px; color:#ffffff; padding-left:10px; padding-right:10px; display:none; }
.boton_zarpe6 { background: #EEEBE4; color:#042743; text-decoration: none!important; letter-spacing: -1px; font-family: graviola_softmedium; 
                font-size:19px; border-radius:10px!important; padding-top:6px;padding-bottom: 4px; padding-left:14px; padding-right:14px;} 
.boton_zarpe7 { background: #BBDBD6; border:0px solid #cdcdcd; border-radius:100px; padding:3px; color:#052844; padding-left:10px; padding-right:10px; text-align:center; }

.boton_zarpe8 { background: #E7E8EA; color: #949597; border-radius:20px; font-size:23px; text-decoration: none!important; 
                 border: 4px solid #F4F5F7; padding: 12px; padding-left:32px; padding-right:32px; }
.boton_zarpe8:hover, .boton_zarpe8:focus { background: #E7E8EA; color: #949597; border: 4px solid #ffffff; box-shadow: 0px 0px 1px 1px #53B956; }

.boton_zarpe9 { background: #052844; border-radius:100px; padding:6px; color:#ffffff; font-size: 15px; text-align:center; width:220px;
                padding-left:10px; padding-right:10px; display: block; text-decoration: none!important;}
.boton_zarpe10 { background: #ffffff; border:1px solid #3f5a6f; border-radius:12px; padding:6px; color:#052844; font-size: 15px; text-align:center; width:100%;
                padding-left:10px; padding-right:10px; display: block; text-decoration: none!important; margin-right:30px;}      
.boton_zarpe11 { background: #052844; border-radius:20px; padding:10px; color:#ffffff; width:160px; text-align:center; 
                padding-left:15px; padding-right:15px; display: block; text-decoration: none!important;}
                
.boton_zarpe12, .boton_zarpe_degrade12:hover, .boton_zarpe_degrade12:focus  {
background: #eaebed!important; font-size: 23px;font-family: graviola_softmedium_italic; color:#042743; border-radius:45px;border:0px solid rgba(0,0,0,0);
padding-left:28px; padding-right:28px; padding-top:9px;padding-bottom: 8px; text-align:center; text-decoration: none!important; display: inline-block;}

.boton_zarpe13 { width:100px; background:#eaebed; border-radius:30px; text-align:center; padding:8px; margin-top:10px; text-decoration: none!important; font-size:13px!important;   }
.boton_zarpe13:hover, .boton_zarpe13:focus { background: #eaebed!important;  }

                              
.boton_zarpe_degrade, .boton_zarpe_degrade:hover, .boton_zarpe_degrade:focus  {
background: #036B3A!important; font-size: 20px;font-family: graviola_softbold; color:#ffffff; border-radius:15px;border:0px solid rgba(0,0,0,0);
background: -moz-linear-gradient(left,  #4EB657 0%, #1CA297 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #4EB657), color-stop(100%, #1CA297))!important;
background: -webkit-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -o-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -ms-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: linear-gradient(to right, #4EB657 0%, #1CA297 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4EB657', endColorstr='#1CA297', GradientType=1 )!important;
padding-left:28px; padding-right:28px; padding-top:9px;padding-bottom: 8px; text-align:center; text-decoration: none!important;}

.boton_zarpe_degrade2, .boton_zarpe_degrade2:hover, .boton_zarpe_degrade2:focus  {
background: #036B3A!important; font-size: 19px;font-family: graviola_softbold; color:#5B595E; border-radius:10px;border:0px solid rgba(0,0,0,0);
background: -moz-linear-gradient(left,  #99D9B7 0%, #80D1CB 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #99D9B7), color-stop(100%, #80D1CB))!important;
background: -webkit-linear-gradient(left, #99D9B7 0%, #80D1CB 100%)!important;
background: -o-linear-gradient(left, #99D9B7 0%, #80D1CB 100%)!important;
background: -ms-linear-gradient(left, #99D9B7 0%, #80D1CB 100%)!important;
background: linear-gradient(to right, #99D9B7 0%, #80D1CB 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#99D9B7', endColorstr='#80D1CB', GradientType=1 )!important;
padding-left:18px; padding-right:18px; padding-top:4px;padding-bottom: 3px; text-align:center; text-decoration: none!important;}

.boton_zarpe_degrade3, .boton_zarpe_degrade3:hover, .boton_zarpe_degrade3:focus  {
background: #036B3A!important; font-size: 16px;font-family: graviola_softbold; color:#ffffff; border-radius:15px;border:0px solid rgba(0,0,0,0);
background: -moz-linear-gradient(left,  #4EB657 0%, #1CA297 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #4EB657), color-stop(100%, #1CA297))!important;
background: -webkit-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -o-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -ms-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: linear-gradient(to right, #4EB657 0%, #1CA297 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4EB657', endColorstr='#1CA297', GradientType=1 )!important;
padding-left:20px; padding-right:20px; padding-top:9px;padding-bottom: 8px; text-align:center; text-decoration: none!important; display: inline-block;}

.boton_zarpe_degrade4, .boton_zarpe_degrade4:hover, .boton_zarpe_degrade4:focus  {
background: #036B3A!important; font-size: 24px;font-family: graviola_softbold; color:#ffffff; border-radius:15px;border:0px solid rgba(0,0,0,0);
padding-left:28px; padding-right:28px; padding-top:9px;padding-bottom: 8px; text-align:center; text-decoration: none!important;}

.boton_zarpe_degrade5, .boton_zarpe_degrade5:hover, .boton_zarpe_degrade5:focus  {
background: #036B3A!important; font-size: 25px;font-family: graviola_softmedium_italic; color:#ffffff; border-radius:15px;border:0px solid rgba(0,0,0,0);
background: -moz-linear-gradient(left,  #4EB657 0%, #1CA297 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #4EB657), color-stop(100%, #1CA297))!important;
background: -webkit-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -o-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -ms-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: linear-gradient(to right, #4EB657 0%, #1CA297 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4EB657', endColorstr='#1CA297', GradientType=1 )!important;
padding-left:28px; padding-right:28px; padding-top:9px;padding-bottom: 8px; text-align:center; text-decoration: none!important; display: inline-block;}

.boton_zarpe_degrade6, .boton_zarpe_degrade6:hover, .boton_zarpe_degrade6:focus  {
background:#8BC43F;color:#042943; font-size: 15px;font-family: graviola_softbook;border-radius:15px;border:0px solid rgba(0,0,0,0);
padding-left:15px; padding-right:15px; padding-top:8px;padding-bottom: 7px; text-align:center; text-decoration: none!important; display: inline-block;}

.boton_zarpe_degrade7, .boton_zarpe_degrade7:hover, .boton_zarpe_degrade7:focus  {
background: #036B3A!important; font-size: 27px;font-family: graviola_softmedium; color:#ffffff; border-radius:15px;border:0px solid rgba(0,0,0,0);
background: -moz-linear-gradient(left,  #4EB657 0%, #1CA297 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #4EB657), color-stop(100%, #1CA297))!important;
background: -webkit-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -o-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: -ms-linear-gradient(left, #4EB657 0%, #1CA297 100%)!important;
background: linear-gradient(to right, #4EB657 0%, #1CA297 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4EB657', endColorstr='#1CA297', GradientType=1 )!important;
padding-left:28px; padding-right:28px; padding-top:9px;padding-bottom: 8px; text-align:center; text-decoration: none!important; }

.boton_zarpe_degrade8, .boton_zarpe_degrade8:hover, .boton_zarpe_degrade8:focus  {
background: #00A49B!important; font-size: 25px;font-family: graviola_softmedium_italic; color:#ffffff; border-radius:15px;border:0px solid rgba(0,0,0,0);
background: -moz-linear-gradient(left,  #26A2D6 0%, #00A49B 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #26A2D6), color-stop(100%, #00A49B))!important;
background: -webkit-linear-gradient(left, #26A2D6 0%, #00A49B 100%)!important;
background: -o-linear-gradient(left, #26A2D6 0%, #00A49B 100%)!important;
background: -ms-linear-gradient(left, #26A2D6 0%, #00A49B 100%)!important;
background: linear-gradient(to right, #26A2D6 0%, #00A49B 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#26A2D6', endColorstr='#00A49B', GradientType=1 )!important;
padding-left:19px; padding-right:19px; padding-top:5px;padding-bottom: 4px; text-align:center; text-decoration: none!important; display: inline-block; margin-top:20px;}

.nav .open > a, .nav .open > a:hover, .nav .open > a:focus {background-color: rgba(0,0,0,0)!important; border-color: rgba(0,0,0,0)!important;}

.margen_izq {margin-left:140px;} 
.margen_izq2 {margin-left:170px;} 
.margen_izq3 {margin-left:-70px;} 
.margen_izq4 {padding-left:60px;} 
.margen_izq5 {padding-left:45px;} 

.margen_izq6 {margin-left:-130px;} 
.margen_izq7 {margin-left:-70px;} 

.margen_der {margin-right:70px; float: right; margin-top:300px;} 
.logo_zarpe { max-width:310px; width:100%; } 
.linea_zarpe { max-width:600px; margin-left:-40px; } 
.linea_zarpe2 { max-width:540px; margin-left:-40px; } 
.margen_top {margin-top:-40px;} 
.margen_top3 {margin-top:0px; margin-left: 6px; } 


.zarpe_movil {display:none;} 
.zarpe_pc {display:table;} 

.subir_comillas  { margin-top:-250px; }
.caja_comentarios { background:#E6E7E9; padding:20px; padding-left:50px; padding-right:50px;  }
.icono_compartir3 { width: 40px;}
.icono_compartir4 { width: 32px;}

.ancho_td { width: 20%;}
.ancho_td2 { width: 29%;}
.ancho_td3 { width: 29%;}
.ancho_td4 { width: 16%;}
.padding_1 { padding-right:26px;}
.gratis { width: 180px; margin-top:-40px; margin-left:150px;}


.container > .navbar-header, .container-fluid > .navbar-header, .container > .navbar-collapse, .container-fluid > .navbar-collapse {
    margin-right: 0px!important; margin-left: -15px;}
.margen_menu { padding-left: 0px; margin-left: 7px!important;}

.zarpe_ancho_producto { width: 160px;}

.zarpe_imagen  { border:1px solid #d5e9e8; padding:13px; text-decoration:none; }
.zarpe_imagen2  { border:1px solid #80c1b9; padding:7px; text-decoration:none; }
.zarpe_productos_ancho { width:18%!important; float:left; margin:10px; margin-top:-50px;}




/*  Zarpe Acordeon tabs   */
.tab-wrap {
  -webkit-transition: 0.3s box-shadow ease;
  transition: 0.3s box-shadow ease;
  border-radius: 6px;
  max-width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: block;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  position: relative;
  list-style: none;
  margin: 0px 0;
  text-align:center;
}

.tab-wrap:hover { box-shadow: 0 12px 23px rgba(0, 0, 0, 0.0), 0 10px 10px rgba(0, 0, 0, 0.0); text-align:center;  }

.tab { display: none; }

.tab:checked:nth-of-type(1) ~ .tab-content2:nth-of-type(1) {
  opacity: 1;
  -webkit-transition: 0.5s opacity ease-in, 0.8s -webkit-transform ease;
  transition: 0.5s opacity ease-in, 0.8s transform ease;
  position: relative;
  top: 0;
  z-index: 100;
  -webkit-transform: translateY(0px);
  -ms-transform: translateY(0px);
  transform: translateY(0px);
  text-shadow: 0 0 0;
}

.tab:checked:nth-of-type(2) ~ .tab-content2:nth-of-type(2) {
  opacity: 1;
  -webkit-transition: 0.5s opacity ease-in, 0.8s -webkit-transform ease;
  transition: 0.5s opacity ease-in, 0.8s transform ease;
  position: relative;
  top: 0;
  z-index: 100;
  -webkit-transform: translateY(0px);
  -ms-transform: translateY(0px);
  transform: translateY(0px);
  text-shadow: 0 0 0;
}

.tab:checked:nth-of-type(3) ~ .tab-content2:nth-of-type(3) {
  opacity: 1;
  -webkit-transition: 0.5s opacity ease-in, 0.8s -webkit-transform ease;
  transition: 0.5s opacity ease-in, 0.8s transform ease;
  position: relative;
  top: 0;
  z-index: 100;
  -webkit-transform: translateY(0px);
  -ms-transform: translateY(0px);
  transform: translateY(0px);
  text-shadow: 0 0 0;
}

.tab:checked:nth-of-type(4) ~ .tab-content2:nth-of-type(4) {
  opacity: 1;
  -webkit-transition: 0.5s opacity ease-in, 0.8s -webkit-transform ease;
  transition: 0.5s opacity ease-in, 0.8s transform ease;
  position: relative;
  top: 0;
  z-index: 100;
  -webkit-transform: translateY(0px);
  -ms-transform: translateY(0px);
  transform: translateY(0px);
  text-shadow: 0 0 0;
}

.tab:checked:nth-of-type(5) ~ .tab-content2:nth-of-type(5) {
  opacity: 1;
  -webkit-transition: 0.5s opacity ease-in, 0.8s -webkit-transform ease;
  transition: 0.5s opacity ease-in, 0.8s transform ease;
  position: relative;
  top: 0;
  z-index: 100;
  -webkit-transform: translateY(0px);
  -ms-transform: translateY(0px);
  transform: translateY(0px);
  text-shadow: 0 0 0;
}

.tab:first-of-type:not(:last-of-type) + label {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0;
}

.tab:not(:first-of-type):not(:last-of-type) + label { border-radius: 0; }

.tab:last-of-type:not(:first-of-type) + label {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0;
}

.tab:checked + label {
  background-color: #fff;
  box-shadow: 0 -1px 0 #fff inset;
  cursor: default;
}

.tab:checked + label:hover {
  box-shadow: 0 -1px 0 #fff inset;
  background-color: #fff;
}

.tab + label {
  box-shadow: 0 -1px 0 #eee inset;
  border-radius: 6px 6px 0 0;
  cursor: pointer;
  display: block;
  text-decoration: none;
  color: #333;
  -webkit-box-flex: 3;
  -webkit-flex-grow: 3;
  -ms-flex-positive: 3;
  flex-grow: 3;
  text-align: center;
  background-color: #f2f2f2;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  text-align: center;
  -webkit-transition: 0.3s background-color ease, 0.3s box-shadow ease;
  transition: 0.3s background-color ease, 0.3s box-shadow ease;
  height: 50px;
  box-sizing: border-box;
  padding: 15px;
}

.tab + label:hover {
  background-color: #f9f9f9;
  box-shadow: 0 1px 0 #f4f4f4 inset;
}

.tab-content2 {
  background-color: transparent;
  position: absolute;
  width: 100%;
  z-index: -1;
  opacity: 0;
  left: 0;
  -webkit-transform: translateY(-3px);
  -ms-transform: translateY(-3px);
  transform: translateY(-3px);
  border-radius: 6px;
}






/*  Zarpe Acordeon   */
.ac-container{

	margin: 10px auto 30px auto;
	text-align: center;
}
.ac-container label{
	position: relative;
	z-index: 0;
	display: block;
	cursor: pointer; width:200px; color: #001e3a; padding:10px; margin:10px;
}
.ac-container label:hover{
	
}
.ac-container input:checked + label,
.ac-container input:checked + label:hover{
	color: #001e3a;
}
.ac-container label:hover:after,
.ac-container input:checked + label:hover:after{
	content: '';
	position: absolute;
	width: 24px;
	height: 24px;
	right: 13px;
	top: 7px;
	background: transparent url(../images/arrow_down.png) no-repeat center center;	
}
.ac-container input:checked + label:hover:after{
	background-image: url(../images/arrow_up.png);
}
.ac-container input{
	display: none;
}
.ac-container article{
	background: rgba(255, 255, 255, 0.5); text-align:center; line-height:1.4;
	margin-top: -1px; width:800px;
	overflow: hidden;
	height: 0px;
	position: relative;
	z-index: 10;
	-webkit-transition: height 0.3s ease-in-out, box-shadow 0.6s linear;
	-moz-transition: height 0.3s ease-in-out, box-shadow 0.6s linear;
	-o-transition: height 0.3s ease-in-out, box-shadow 0.6s linear;
	-ms-transition: height 0.3s ease-in-out, box-shadow 0.6s linear;
	transition: height 0.3s ease-in-out, box-shadow 0.6s linear;
}
.ac-container article p{
	padding: 20px; text-align:center; line-height:1.4;
	text-shadow: 1px 1px 1px rgba(255,255,255,0.8);
}
.ac-container input:checked ~ article{
	-webkit-transition: height 0.5s ease-in-out, box-shadow 0.1s linear;
	-moz-transition: height 0.5s ease-in-out, box-shadow 0.1s linear;
	-o-transition: height 0.5s ease-in-out, box-shadow 0.1s linear;
	-ms-transition: height 0.5s ease-in-out, box-shadow 0.1s linear;
	transition: height 0.5s ease-in-out, box-shadow 0.1s linear;
	box-shadow: 0px 0px 0px 1px rgba(155,155,155,0); text-align:center; line-height:1.4;
}
.ac-container input:checked ~ article.ac-small{
	height: 240px; text-align:center; line-height:1.4;
}
.ac-container input:checked ~ article.ac-small2{
	height: 80px; text-align:center; line-height:1.4;
}
.ac-container input:checked ~ article.ac-medium{
	height: 180px; width:500px;
}
.ac-container input:checked ~ article.ac-large{
	height: 230px;
}


/* Dropmenu movil */
.interior {
  display: table-cell;
  vertical-align: middle;
  text-align: center;
}

.btn {
  background-color: #fff;
  padding: 1em 3em;
  border-radius: 3px;
  text-decoration: none;
}

.modal-window {
  position: fixed;
  background-color: rgba(0, 0, 0, 0.6);
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 999;
  opacity: 0;
  pointer-events: none;
  -webkit-transition: all 0.3s;
  -moz-transition: all 0.3s;
  transition: all 0.3s;
}

.modal-window:target {
  opacity: 1;
  pointer-events: auto;
}


.modal-window>div {
  width: 100%; bottom: 0px; position: absolute; padding: 20px; background: #fff; color: #444;
}

.modal-window header {
  font-weight: bold;
}

.modal-close {
  width: 100%; height:600px; background: rgba(0,0,0,0); display:block;

}

.modal-close:hover {
  color: #000;
}

.modal-window h1 {
  font-size: 150%;
  margin: 0 0 15px;
}




@media (min-width: 320px) and (max-width: 712px)  {
.altura_div_contenedor { height: auto; }
.alinear_zarpe { text-align:left; }
.alinear_zarpe2 { text-align:center; } 
.alinear_zarpe3 { margin-left:0px; }
.alinear_zarpe4 { text-align:center; } 
.alinear_zarpe8 { text-align:center; } 
.alinear_ver_zarpe { margin-top:-28px; }
.ancho_6 { width:50%; padding:2px; float: none;  }
.ancho_4 { width:50%; padding:2px; float:none }
.zarpe_productos_ancho { width:98%!important; float:left; margin:9px; margin-top:-50px;}
.ver_en_movil { visibility: visible !important;  display: inline-block!important;}
.margen_top3 {margin-top:0px; margin-left: -110px!important;} 
.dropdown-menu  {min-width: 180px!important; margin-left: -100px!important}

.menu_pais {min-width: 110px!important;}
}

@media (min-width: 375px) and (max-width: 712px)  {
.altura_div_contenedor { height: auto; }
.alinear_zarpe { text-align:left; }
.alinear_zarpe2 { text-align:center; } 
.alinear_zarpe3 { margin-left:0px; }
.alinear_zarpe4 { text-align:center; } 
.alinear_zarpe8 { text-align:center; } 
.alinear_ver_zarpe { margin-top:-28px; }
.ancho_6 { width:50%; padding:2px; float: none;  }
.ancho_4 { width:50%; padding:2px; float:none }
.zarpe_movil {display:block;}
.zarpe_pc {display:none!important;} 
.zarpe_productos_ancho { width:98%!important; float:left; margin:9px; margin-top:-50px;}
.ver_en_movil { visibility: visible !important;  display: inline-block!important;}
.margen_top3 {margin-top:0px; margin-left: -110px!important;} 
}

@media (min-width: 425px) and (max-width: 712px) {
.boton_zarpe3 { padding:10px; font-size: 15px; width:220px; display: block; }
.alinear_zarpe { text-align:left; }
.alinear_zarpe2 { text-align:center; }
.alinear_zarpe3 { margin-left:0px; }
.alinear_zarpe4 { text-align:center; } 
.alinear_zarpe8 { text-align:center; } 
.alinear_ver_zarpe { margin-top:-28px; }
.ancho_6 { width:50%; padding:2px; float: none;  }
.ancho_4 { width:50%; padding:2px; float:none }
.ocultar_en_movil {display:none; }
.ancho_tabla_comentarios { width:590px;}
.carousel_comentarios-inner {max-width:620px; padding:30px;}
.boton_producto_zarpe, .boton_producto_zarpe:hover { width:100%; }
.banner_5 { background-image: url("../../images/zarpe_fondo10b.jpg"); width:100%; background-size: 830px 700px; background-position: -196px -20px;}
.banner_7 { background-image: url("../../images/zarpe_fondo10b.jpg"); width:100%; background-size: 830px 700px; background-position: -196px -20px;}
.titulo_11 { font-size: 20px;}
.texto_11 { font-size: 18px;}
.texto_6 { font-size: 16px;}
.ancho_td { width: 16%;}
.ancho_td2 { width: 36%;}
.ancho_td3 { width: 36%;}
.alienar_boton  { float:right; position: relative; margin-right:50px; margin-top:-130px; }
.alienar_boton2  { float:right; position: relative; margin-right:50px; margin-top:-80px; }
.boton_zarpe6 {  font-size: 20px;}
.popup_ancho3 { width:550px; height:380px}
.banner_9 { background-image: url("../../images/zarpe_fondo28.jpg"); background-size: 1300px 650px;  background-position: 0px -110px;}



}


@media (min-width: 1001px) and (max-width: 1080px)  {
.alinear_zarpe5 { float: left; margin-left:20px; width:100%; }
}
@media (min-width: 775px) and (max-width: 1000px)  {
.alinear_zarpe5 { float: left; margin-left:488px; width:100%; }
.menu_padding { margin-left:18px; float:left; width:100px; margin-right:18px;}
}
@media (min-width: 713px) and (max-width: 774px)  {
.alinear_zarpe5 { float: left; margin-left:20px; width:100%; }
}


@media (min-width: 713px) and (max-width: 768px)  {
.boton_zarpe3 { padding:10px; font-size: 15px; width:220px; display: block; }
.borde_producto_zarpe { border:2px solid #999999; padding:3px; border-radius:18px; width:100%; max-width:700px;margin-bottom:8px; }
.alinear_zarpe { text-align:left; }
.alinear_zarpe2 { text-align:center; }
.alinear_zarpe3 { margin-left:0px; }
.alinear_zarpe4 { text-align:center; } 
.alinear_zarpe8 { text-align:center; } 
.alinear_ver_zarpe { margin-top:-28px; }
.ancho_6 { width:50%; padding:2px; float: none;  }
.ancho_4 { width:50%; padding:2px; float:none }

.titulo_2 { font-size: 18px; letter-spacing: -1px; line-height: 18px;}
.titulo_3 { font-size: 20px; color:#ffffff;}
.titulo_4 { font-size: 15px; color:#052844; letter-spacing: -1px; }
.fondo_div_nombre { background-position: 0px -10px; background-size: 240px 60px ;padding-top: 8px; padding-bottom: 12px; } 
.fondo_1 { background-position: -40px 0px; background-size: 1100px  ; height: 500px; padding-top: 10px;   }
.fondo_2 { background-position: -90px -40px; text-align:right; background-size: 1100px 1060px;  height: 550px; padding-top: 10px;  }  
.fondo_4 { background-position: -40px 0px; background-size: 1100px  ; height: 500px; padding-top: 10px;   }
.margen_izq {margin-left:40px;} 
.margen_izq2 {margin-left:20px;} 
.margen_top {margin-top:-100px;} 
.logo_zarpe { max-width:200px; width:100%; } 
.linea_zarpe { max-width:350px; margin-left:-40px; }
.linea_zarpe2 { max-width:350px; margin-left:0px; }
.ancho_tabla_comentarios { width:640px;}
.carousel_comentarios-inner {max-width:690px; padding:30px;}

.boton_producto_zarpe, .boton_producto_zarpe:hover { width:100%; }
.titulo_11 { font-size: 20px;}
.texto_11 { font-size: 18px;}
.texto_6 { font-size: 16px;}
.ancho_td { width: 16%;}
.ancho_td2 { width: 35%;}
.ancho_td3 { width: 35%;}
.popup_ancho3 { width:700px; height:380px}
.ver_en_movil  { visibility: visible !important;  display: inline-block!important;}
.dropdown-menu  {min-width: 110px!important; margin-left: -120px!important}
}

@media (min-width: 769px) and (max-width: 1024px)  {
.boton_zarpe3 { padding:10px; font-size: 15px; width:220px; display: block; }
.alinear_zarpe { text-align:left; }
.alinear_zarpe2 { text-align:center; }
.alinear_zarpe3 { margin-left:0px; }
.alinear_zarpe4 { text-align:center; } 
.alinear_zarpe8 { text-align:center; } 
.alinear_ver_zarpe { margin-top:-28px; }
.ancho_6 { width:55%; padding:2px; float: none;  }
.ancho_4 { width:40%; padding:2px; float:none }

.menu_padding { margin-left:18px; float:left; width:100px; margin-right:18px; }
.titulo_2 { font-size: 22px; letter-spacing: -1px; line-height: 22px;}
.titulo_3 { font-size: 24px; color:#ffffff; line-height: 22px;}
.titulo_4 { font-size: 19px; color:#052844; letter-spacing: -1px; }
.texto_16 { font-size: 20px;line-height: 20px; letter-spacing: -0.5px; }
.fondo_div_nombre { background-position: 0px -10px; background-size: 320px 60px ;padding-top: 8px; padding-bottom: 12px; } 
.fondo_1 { background-position: -40px 0px; background-size: 1100px  ; height: 500px; padding-top: 10px;   }
.fondo_2 { background-position: -90px -40px; text-align:right; background-size: 1100px 1060px;  height: 550px; padding-top: 10px;  }  
.fondo_4 { background-position: -40px 0px; background-size: 1100px  ; height: 400px; padding-top: 10px;   }
.margen_izq {margin-left:100px;} 
.margen_izq2 {margin-left:110px;}
.margen_izq9 {margin-left:-130px; width:290px!important;} 
.margen_top {margin-top:-100px;} 
.logo_zarpe { max-width:250px; width:100%; } 
.linea_zarpe { max-width:400px; margin-left:-40px; }
.linea_zarpe2 { max-width:400px; margin-left:-40px; }
.ancho_tabla_comentarios { width:780px;}
.carousel_comentarios-inner {max-width:820px; padding:30px;}

.boton_producto_zarpe, .boton_producto_zarpe:hover {  width:100%; }

.banner_5 { background-image: url("../../images/zarpe_fondo10.jpg"); width:100%; background-size: 1100px 490px; background-position: -100px 0px;}
.banner_7 { background-image: url("../../images/zarpe_fondo16.jpg"); width:100%; background-size: 900px 520px; background-position: -70px 0px;margin-top:-2px;}
.banner_9 { background-image: url("../../images/zarpe_fondo28.jpg"); background-size: 1300px 650px;  background-position: -300px -110px;}
.titulo_11 { font-size: 20px;}
.texto_11 { font-size: 18px;}
.texto_6 { font-size: 16px;}
.gratis { width: 100px; margin-top:-22px; margin-left:110px;}
.margen_der {margin-right:70px; float: right; margin-top:-60px;} 
.zarpe_productos_ancho { width:17%!important; float:left; margin:9px; margin-top:-50px;}

}

@media (min-width: 100px) and (max-width: 1200px)  {

.padding_zarpe { padding-bottom:30px; }
.boton_producto_zarpe, .boton_producto_zarpe:hover { margin-bottom:15px;}
.titulo_7 {  }
.texto_16 {  }

.alinear_zarpe2 {       }

}




@media (min-width: 1024px) and (max-width: 1200px)  {
.ancho_6 { width:55%; padding:2px; float: left;  }
.ancho_4 { width:36%; padding:2px; float:left } 
.boton_zarpe3 { padding:10px; font-size: 15px; width:220px; display: block; }
.titulo_2 { font-size: 26px; letter-spacing: -1px; line-height: 28px;}
.titulo_3 { font-size: 30px; color:#ffffff;}
.titulo_4 { font-size: 25px; color:#052844; letter-spacing: -1px; }
.fondo_div_nombre { background-position: 0px -10px; background-size: 420px 70px ;padding-top: 10px; padding-bottom: 20px; } 
.fondo_1 { background-position: 0px 0px; background-size: 1240px  ; height: 500px; padding-top: 10px;   }
.fondo_2 { background-position: -40px -40px; text-align:right; background-size: 1100px 1060px;  height: 550px; padding-top: 10px;  }  
.fondo_4 { background-position: 0px 0px; background-size: 1240px  ; height: 440px; padding-top: 10px;   }
.margen_izq {margin-left:140px;} 
.margen_izq2 {margin-left:170px;} 
.margen_der {margin-right:70px; float: right; margin-top:300px;} 
.ancho_tabla_comentarios { width:640px;}
.carousel_comentarios-inner {max-width:690px; padding:30px;}
.gratis { width: 120px; margin-top:-28px; margin-left:137px;}
.banner_7 { background-image: url("../../images/zarpe_fondo16.jpg"); width:100%; background-size: 1000px 580px; background-position: -60px -20px;}
.banner_9 { background-image: url("../../images/zarpe_fondo28.jpg"); background-size: 1300px 650px;  background-position: -260px -110px;}
.texto_16 { font-size: 20px;line-height: 20px; letter-spacing: -0.5px; }
.zarpe_productos_ancho { width:17%!important; float:left; margin:9px; margin-top:-50px;}

}

@media (min-width: 1500px) and (max-width: 2000px)  { 
.fondo_1 { background-position: 0px 0px; background-size: 1900px  ; height: 590px; padding-top: 10px;   }
.fondo_4 { background-position: 0px 0px; background-size: 1900px  ; height: 590px; padding-top: 10px;   }
.banner_4 { background-image: url("../../images/zarpe_fondo8.jpg"); text-align:center; width:100%; background-size: 2200px 500px;}
.margen_izq {margin-left:280px;} 
.margen_izq2 {margin-left:310px;} 
.fondo_div_nombre { background-position: 130px -4px; background-size: 420px 70px ;padding-top: 10px; padding-bottom: 20px; }
.linea_zarpe { max-width:690px; margin-left:-40px; } 
.linea_zarpe2 { max-width:690px; margin-left:-40px; }
.banner_10 { background-size: 2000px 650px; } 
}

@media (min-width: 2010px) and (max-width: 3000px)  { 
.fondo_1 { background-position: 0px 0px; background-size: 2300px  ; height: 680px; padding-top: 10px;   }
.fondo_4 { background-position: 0px 0px; background-size: 2300px  ; height: 680px; padding-top: 10px;   }
.banner_4 { background-image: url("../../images/zarpe_fondo8.jpg"); text-align:center; width:100%; background-size: 3000px 500px;}
.banner_7 { background-image: url("../../images/zarpe_fondo10.jpg"); text-align:center; width:100%; background-size: 1500px 600px;background-position: 100px -90px;}
.margen_izq {margin-left:500px;} 
.margen_izq2 {margin-left:540px;} 
.fondo_div_nombre { background-position: 400px -4px; background-size: 420px 70px ;padding-top: 10px; padding-bottom: 20px; }
.linea_zarpe { max-width:660px; margin-left:240px; } 
.linea_zarpe2 { max-width:660px; margin-left:240px; } 
.col-md-2, .col-md-4 { width: 23%!important; }
.banner_9 { background-image: url("../../images/zarpe_fondo28.jpg"); text-align:center; width:100%; background-size: 1900px 900px; 
            background-position: -210px -290px;}
.banner_3 { width:100%; max-width:2600px; background-size: 2600px 400px;} 
.banner_5 { width:100%; background-size: 1750px 720px; background-position: 100px -100px;}
.banner_10 { background-size: 3000px 650px; }
}


.ancho_estado  { width:46px;  }
.modalBackground2 { background-color: Black; filter: alpha(opacity=40); opacity: 0.4;}
.subir_popup { margin-top:-18px;  }
.zarpe_margen_izquierda5 { margin-left: -90px; }



@media (min-device-width: 780px) and (max-device-width: 1024px) {
.no_ver_en_movil2 { display: none!important; }   
.ver_en_movil { visibility: visible !important;  display:block!important;}    

}  


/*  Movil   and (orientation : portrait) */
@media (max-device-width: 1200px)  {

.boton_zarpe8 { background: #E7E8EA; color: #949597; border-radius:20px; font-size:19px; text-decoration: none!important; 
                 border: 4px solid #F4F5F7; padding: 10px; padding-left:25px; padding-right:25px; }
.boton_zarpe9 { background: #052844; border-radius:100px; padding:6px; color:#ffffff; font-size: 15px; text-align:center; width:220px;
                padding-left:10px; padding-right:10px; display: block; text-decoration: none!important;} 
.modalDialog > div {width: 92%;  text-align:center; padding: 5px 20px 13px 20px; background: #F4F5F7; margin-top:200px; }
.ancho_6 { width:55%; padding:2px; float: left;  }
.ancho_4 { width:36%; padding:2px; float:left } 
.ancho_select { width:250px; }
.boton_zarpe3 { padding:10px; font-size: 15px; width:220px; display: block; }
.boton_zarpe4 { font-size: 20px; }
.borde_texto_zarpe { padding-left: 17px; padding-right: 17px; padding-top: 10px; padding-bottom: 7px; margin-top: -20px!important;}
.boton_producto_zarpe, .boton_producto_zarpe:hover { width:100%; }
.boton_zarpe_degrade3 { font-size: 16px; }
.boton_zarpe_degrade7, .boton_zarpe_degrade7:hover, .boton_zarpe_degrade7:focus  {font-size: 20px; padding-left: 12px;padding-right: 12px;
    padding-top: 8px; padding-bottom: 7px;display: block;}
.borde_imagen   {  margin-bottom: 10px; }
.titulo_2 { font-size: 26px; letter-spacing: -1px; line-height: 28px;}
.titulo_3 { font-size: 30px; color:#ffffff;}
.titulo_4 { font-size: 25px; color:#052844; letter-spacing: -1px; }
.titulo_5 { font-size: 28px; }
.titulo_7 { font-size: 23px; }
.titulo_7c { font-size: 23px; }
.titulo_7b { font-size: 26px; }
.titulo_8 { font-size: 22px; line-height: 22px;}
.titulo_9 { font-size: 26px; }
.titulo_9b { font-size: 26px; }
.titulo_9c { font-size: 26px; }
.texto_4 { font-size: 14px; line-height: 12px; letter-spacing: -0.5px;}
.texto_1 { font-size: 22px; line-height: 22px;}
.texto_3 { font-size: 22px; line-height: 20px; letter-spacing: -0.5px;}
.texto_8b { font-size: 20px;font-family: graviola_softmedium; color:#929397; line-height: 25px; letter-spacing: -0.5px; }
.texto_9 { font-size: 18px; line-height: 20px;}
.texto_9c { font-size: 24px; line-height: 23px;}
.texto_10 { font-size: 20px; }
.texto_13 { font-size: 15px;}
.titulo_11 { font-size: 20px;}
.texto_11 { font-size: 18px;}
.texto_6 { font-size: 14px;}
.texto_7 { font-size: 20px; line-height: 24px;}
.texto_6b { font-size: 14px;}
.texto_6c { font-size: 14px;}
.texto_menu { font-size: 15px;}
.texto_20 { font-size: 15px;}
.texto_20b { font-size: 15px;}
.fondo_div_nombre { background-position: 0px -10px; background-size: 360px 70px ;padding-top: 10px; padding-bottom: 20px; } 
.fondo_1 { background-position: -180px 0px; background-size: 1240px  ; height: 500px; padding-top: 10px;   }
.fondo_2 { background-position: -320px -40px; text-align:right; background-size: 1100px 1060px;  height: 550px; padding-top: 10px;  }  
.fondo_4 { background-position: -180px 0px; background-size: 1240px  ; height: 500px; padding-top: 10px;   }
.fondo_5 { background-position: -420px 0px; background-size: 1000px  ; height: 690px; padding-top: 10px;   }
.margen_izq {margin-left:90px;} 
.margen_izq2 {margin-left:120px;} 

.margen_top {margin-top:-60px;}
.linea_zarpe { max-width:450px; margin-left:-40px; }
.linea_zarpe2 { max-width:100%; margin-left:0px; }
.ver_en_movil  { visibility: visible !important;  display: inline-block!important;}
.zarpe_movil {display:inline-table!important;}
.zarpe_pc {display:none!important;} 
.banner_5 { background-image: url("../../images/zarpe_fondo10c.jpg"); width:100%; background-size: 1000px 1200px; background-position: -230px -430px;}
.banner_7 { background-image: url("../../images/zarpe_fondo16b.jpg"); width:100%; background-size: 1000px 1200px; background-position: -160px -370px; margin-top: -2px;}
.banner_9 { background-image: url("../../images/zarpe_fondo28.jpg"); background-size: 1300px 650px;  background-position: -340px -80px;}
.ancho_td { width: 16%;}
.ancho_td2 { width: 36%;}
.ancho_td3 { width: 36%;}
.ancho_td5 { width: 16%;}
.gratis2 { width: 210px; margin-top: -46px;margin-left: 114px;}
.carousel_comentarios { max-width:340px;}
.carousel_comentarios-item img { width:130px!important;}
.zarpe_margen_izquierda { margin-left: -50px; margin-top: -110px;}
.zarpe_margen_izquierda2 { margin-left: -290px; margin-top: 160px; width: 400px;}
.zarpe_margen_izquierda4 { padding-left: 0px!important; }
.alinear_zarpe5 { float: left; margin-left:20px; width:100%; }
.ancho_tablet_1 {width:62%!important; margin-left: 5%!important; padding-right: 5px!important;}
.btn-ganolife3 {font-size:13px; padding:13px; color:#ffffff; line-height:65px; padding-top: 15px; }
.ancho_estado  { width:46px;  }
.alinear_zarpe6 { float: left;  width:100%!important;}
.alinear_zarpe7 { float: left; margin-top:40px; }



.modalBackground2 { background-color: Black; filter: alpha(opacity=00); opacity: 0.0;}
.popup_titulo_video { margin-top: 14px; margin-top: 15px; display: inline-block;}
.popup_contactos { left: 20px; margin-top: -245px; width:80%!important;}
.popup_contactos2 { left: 20px; margin-top: 90px; width:80%!important; border: 1px solid #ADAEB0; line-height: 1; display: block;}
.popup_contactos3 { left: 20px; margin-top: 144px; width:80%!important; }
.zarpe_video_popup_mascara {width: 130px; height: 130px; overflow: hidden; margin-left: 15px; margin-top: 20px;}
.zarpe_video_popuptexto {width: 94%; display: block;}
.zarpe_boton_popup {display: block; margin-top:40px}
.zarpe_videos { width:800px!important;max-width:800px!important; float:left; padding:18px; height:320px; } 

.zarpe_productos_ancho { width:18%!important; float:left; margin:10px; margin-top:0px;}
.ocultar_en_movil {display:none; }

.campo_texto_zarpe_select, .campo_texto_zarpe_select:disabled {font-size: 16px; border: 1px solid #ADAEB0; }
}

.popup_contactos2, .popup_contactos3 { width: 90%;}
.popup_contactos { width:86%;}
.zarpe_tabla { border: 1px solid #ffffff; border-bottom: 1px solid #dedede;}


  
  

@media (max-device-width: 768px)   {

.fondo_preload { width: 400px!important; background:#000000; border-radius:10px; padding:20px;}
.btn-ganolife8 { background: #4c8bb9!important; width:100%!important; padding:11px!important;  }
.btn-ganolife9 { width:100%!important; background:#e9e9e9!important;  padding:11px!important; color:#555555!important; font-size: 14px!important; text-align:right; }

#slider, #slider2{max-width:640px}
#slide10:checked ~ #commands2 label:nth-child(2), #slide11:checked ~ #commands2 label:nth-child(3), #slide12:checked ~ #commands2 label:nth-child(4), #slide13:checked ~ #commands2 label:nth-child(5), #slide14:checked ~ #commands2 label:nth-child(1) {
    background: url(../../images/zarpe_flecha2b.png) no-repeat; float: right; margin: 0px -50px 0px 0px; display: block;  width: 30px;}
#slide1:checked ~ #commands label:nth-child(2), #slide2:checked ~ #commands label:nth-child(3), #slide3:checked ~ #commands label:nth-child(4), #slide4:checked ~ #commands label:nth-child(5), #slide5:checked ~ #commands label:nth-child(1) {
        margin: -30px -20px 0px 0px; width: 30px;}
.menu_padding2 { margin-left: 25px; width: 100px; margin-right: 25px; }

.tooltip3:hover:after{ background: rgba(0,0,0,0)!important; color: rgba(0,0,0,0) !important; content: attr(title);   }

.tooltip3:hover:before{
    border: solid; border-color: rgba(0,0,0,0) !important; border-width: 8px 8px 0 8px; bottom: -2px; content: ""; left: 10%; position: absolute;z-index: 1!important;}

.radio_button_plan_texto7 > input[type=radio]:checked + label,
.radio_button_plan_texto7:hover > input[type=radio]:checked + label  {color:#ffffff; background: #4c8bb9!important; }  
.form-control_2 {
  display: block; width: 100%; height: 34px; padding: 20px 0px; font-size: 17px; line-height: 1.42857; color: #555555; background-color: #e9e9e9;
  background-image: none; border-bottom: 1px solid #ccc; border-radius: 4px; border-left: 1px solid #e9e9e9; border-top: 1px solid #e9e9e9; 
  border-right: 1px solid #e9e9e9;  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.0); }
.wrapper-siginup .nav-tabs .active a { background: transparent !important; border-bottom: solid 1px #4c8bb9 !important; color: #4c8bb9;font-weight: bold; }
      
.zarpe_margen { margin-top: 130px;}
.zarpe_productos_ancho { width:17%!important; }
.zarpe_videos { width:600px!important; max-width:600px!important;float:left; padding:18px; height:320px; } 

.ancho_tabla_2 { width:60%; } 
.ancho_6 { width:96%; padding:2px; float: none; margin-left: -10px; }
.ancho_4 { width:100%; padding:2px; float:none; margin-left: 0px; } 
.texto_3 { font-size: 16px;}
.texto_4 { font-size: 12px; line-height: 12px;}
.texto_4c, .texto_4c[disabled] { font-size: 12px!important; line-height: 10px;}
.texto_21 { font-size: 16px;line-height: 14px; }
.texto_menu { font-size: 13px;}
.texto_20 { font-size: 13px;}
.texto_20b { font-size: 13px;}
.titulo_7 { font-size: 16px; }
.titulo_7c { font-size: 16px; }
.texto_7 { font-size: 15px; line-height: 22px;}
.texto_9c { font-size: 18px; line-height: 20px;}
.texto_16 { font-size: 16px;line-height: 18px; letter-spacing: -0.5px; }
.boton_zarpe3 { margin-bottom: 0px; }
.boton_zarpe_degrade4 { margin-top: 20px; }
.icono_compartir3 { margin-left: 20px;}
.icono_compartir4 { width: 20px;}
.borde_div_zarpe { width:100%;  }
.nav2 { margin-left: -50px;}

.ver_en_movil { visibility: visible !important; display: inline-block!important;}
.ancho_tabla_compartir2 { width:100%; max-width:280px;}
.subir_comillas  { margin-top:-330px; }
.banner_5 { background-size: 1000px 1200px; background-position: -170px -430px;}
.ocultar_en_movil {display:none; }
.gratis { width: 140px; margin-top: -32px; margin-left: 134px;}
.gratis2 { width: 210px; margin-top: -46px;margin-left: 114px;}
.banner_7 { background-image: url("../../images/zarpe_fondo16b.jpg"); width:100%; background-size: 1000px 1200px; background-position: -40px -340px;}
.banner_9 { background-image: url("../../images/zarpe_fondo28b.jpg"); background-size: 900px 950px;  background-position: -240px -180px;}
.alienar_boton  { float:right; position: relative; margin-right:60px; margin-top:-150px; }
.alienar_boton2  { float:right; position: relative; margin-right:60px; margin-top:-90px; }
.zarpe_pc {display:none!important;} 
.margen_menu { padding-left: 20px; margin-left: 17px!important;}
.boton_producto_zarpe, .boton_producto_zarpe:hover {margin-bottom:15px; width:300px; }
.fondo_4 { background-position: -120px 0px; background-size: 1240px  ; height: 500px; padding-top: 10px;   }
.ancho_mitad2 { width:98%; margin-right:0px; float:left }
.ancho_mitad3 { width:98%; margin-left:0px; float:left }

.popup_ancho {width:100%!important; height:740px!important; margin-top: 150px;}
.subir_popup { margin-top:0px;  }
.zarpe_margen_izquierda5 { margin-left: -170px!important; }
}


.fondo_preload { width: 500px; background:#000000; border-radius:10px; padding:20px;}
.icono_preload { background-image: url("../../images/preload.gif"); background-repeat: no-repeat; background-position: 30px 0px; width: 160px ; height:83px ;  margin: 0 auto; }
.comentarios_productos { margin-left:-30px; }
.ancho_td5 { width: 16%;}
.margen_derecha1  { top:-32px; right:-530px;  }
.zarpe_logo { width:100%; max-width:300px; }
.zarpe_anchotexto { width:250px!important;  }
.zarpe_anchotd { width:40%; }


@media (max-device-width: 425px)  {

.fondo_preload { width: 300px!important; background:#000000; border-radius:10px; padding:20px;}
.zarpe_logo { width:100%; max-width:140px; margin-top: -20px; }
.zarpe_anchotexto { width:150px!important; margin-top: 20px; }
.zarpe_anchotd { width:44%; }

.margen_top3 {margin-top:-120px; margin-left: -30px!important;} 
.margen_derecha1  { top:-25px; right:-350px;  }
#slides2 article { width: 20%; padding: 30px; float: inherit;}
.alinear_zarpe10 { margin-top: 25px!important; margin-left: -141px; position:absolute; }
#container2 { width: 100%; margin-left: 0px; }
#slides2 {position:relative;padding:12px;margin:0px 0 0;}
#slide10:checked ~ #commands2 label:nth-child(2),#slide11:checked ~ #commands2 label:nth-child(3),
#slide12:checked ~ #commands2 label:nth-child(4),#slide13:checked ~ #commands2 label:nth-child(5),
#slide14:checked ~ #commands2 label:nth-child(1){background:url("../../images/zarpe_flecha2b.png") no-repeat;float:right;margin:0px 20px 0px 0px; 
                                                 width: 30px; display:none}
#slide10:checked ~ #commands2 label:nth-child(5),#slide11:checked ~ #commands2 label:nth-child(1),#slide12:checked ~ #commands2 label:nth-child(2),
#slide13:checked ~ #commands2 label:nth-child(3),#slide14:checked ~ #commands2 label:nth-child(4){background:url("../../images/zarpe_flecha1b.png") no-repeat;
                                                                                                  float:left;margin:0px 0px 0px 15px;display:none}
#slide10:checked ~ #active2 label:nth-child(1),#slide11:checked ~ #active2 label:nth-child(2),#slide12:checked ~ #active2 label:nth-child(3),
#slide13:checked ~ #active2 label:nth-child(4),#slide14:checked ~ #active2 label:nth-child(5){background:#000;opacity:0.6;border-color:#fff!important;border:2px solid #fff}

#slide1:checked ~ #commands label:nth-child(2), #slide2:checked ~ #commands label:nth-child(3), #slide3:checked ~ #commands label:nth-child(4), #slide4:checked ~ #commands label:nth-child(5), #slide5:checked ~ #commands label:nth-child(1) {
        margin: -30px 20px 0px 0px; width: 30px; background-size: 25px;}
#slide1:checked ~ #commands label:nth-child(5), #slide2:checked ~ #commands label:nth-child(1), #slide3:checked ~ #commands label:nth-child(2), #slide4:checked ~ #commands label:nth-child(3), #slide5:checked ~ #commands label:nth-child(4) {
    margin: -30px 30px 0px 0px; display: block; background-size: 25px;}
     
#slide20:checked ~ #commands3 label:nth-child(2),#slide21:checked ~ #commands3 label:nth-child(3),
#slide22:checked ~ #commands3 label:nth-child(4),#slide23:checked ~ #commands3 label:nth-child(5),
#slide24:checked ~ #commands3 label:nth-child(1){ margin:-330px 0px 0px 0px;}
#slide20:checked ~ #commands3 label:nth-child(5),#slide21:checked ~ #commands3 label:nth-child(1),#slide22:checked ~ #commands3 label:nth-child(2),
#slide23:checked ~ #commands3 label:nth-child(3),#slide24:checked ~ #commands3 label:nth-child(4) { margin:-330px 0px 0px 30px;}

.zarpe_videos { width:99%!important; max-width:400px!important; float:left; padding:18px; height:350px; } 
.zarpe_video_popup { padding-left: 15px; padding-top:15px; width: auto;height: 100%; margin-left: -70px;}   
.zarpe_productos_ancho { width:94%!important; float:left; margin:10px;}
.zarpe_margen_izquierda4 { margin-left: 0px!important; }

.boton_zarpe13 { width:80px; background:#eaebed; border-radius:30px; padding:8px; margin-top:10px;  font-size:12px!important;  }
.zarpe_margen { margin-top: 170px;}
.menu_padding2 { margin-left:7px; float:left; width:74px; margin-right:8px; text-decoration:none; margin-top:10px; margin-bottom:10px;}
.texto_20 { font-size: 12px;font-family: graviola_softmedium; line-height: 9px!important;}
.texto_20b { font-size: 11px;font-family: graviola_softmedium; line-height: 9px!important;}
.texto_menu { font-size: 9px;font-family: Montserrat; line-height: 12px!important;}

.ancho_tabla_2 { width:82%; } 
.banner_4 { background-size: 600px 500px;}
.ancho_nombre_comentarios {width: 300px;}
.comentarios_foto { margin-top: -220px; margin-left: 118px;}
.comentarios_nombre { margin-left: 130px; margin-top: -260px;}
.comentarios_productos {  margin-left: -235px!important; margin-top: 340px;  }
.caja_comentarios { padding:0px; padding-left:10px; padding-right:10px; padding-top:10px; padding-bottom:10px; text-align:center; width:370px; margin-left:-170px; margin-top:70px;}
.ancho_tabla_comentarios {width: 400px; margin-bottom: 20px; }
.ancho_select { width:170px!important; font-size: 16px; }
.campo_texto_zarpe { font-size: 16px;  font-family: graviola_softbook; }
.campo_texto_zarpe_3 { width:250px; font-size: 15px;  font-family: graviola_softbook; height:32px; padding-top:1px;}
.zarpe_margen_izquierda { margin-left: -35px; margin-top: -230px;}
.zarpe_margen_izquierda2 { margin-left: -304px; margin-top: 100px; width: 400px;}
.zarpe_margen_izquierda3 { margin-left: -360px!important; margin-top: 310px; width: 400px;}
.zarpe_margen_izquierda5 { margin-left: -170px!important; }

.carousel_comentarios-open:checked + .carousel_comentarios-item { height: 440px!important;}
.boton_producto_zarpe, .boton_producto_zarpe:hover {  width:100%; padding: 10px;}
.boton_zarpe4 { margin-top:30px; font-size: 13px; display: block;}
.boton_zarpe12 { font-size: 18px; }
.boton_zarpe_degrade5, .boton_zarpe_degrade5_hover, .boton_zarpe_degrade5:focus  { font-size: 22px;}
.boton_zarpe_degrade6, .boton_zarpe_degrade6:hover, .boton_zarpe_degrade6:focus {
    font-size: 14px; letter-spacing: -1px; padding-left: 16px; padding-right: 16px; padding-top: 7px; padding-bottom: 6px;}
.boton_zarpe_degrade7, .boton_zarpe_degrade7:hover, .boton_zarpe_degrade7:focus {
    font-size: 16px; letter-spacing: -1px; padding-left: 5px; padding-right: 5px; padding-top: 8px; padding-bottom: 7px;}
.fondo_div_nombre { background-position: 0px -10px; background-size: 210px 60px ;padding-top: 10px; padding-bottom: 20px; } 
.fondo_1 { background-position: -180px 0px; background-size: 800px  ; height: 350px; padding-top: 10px;   }
.fondo_4 { background-position: -240px 0px; background-size: 890px  ; height: 350px; padding-top: 10px;   }
.margen_izq {margin-left:20px;} 
.margen_izq2 {margin-left:40px;}
.margen_izq3 {margin-left:0px;} 

.margen_izq6 {margin-left:-180px;} 
.margen_izq7 {margin-left:-120px;} 

.margen_top {margin-top:-40px;}
.margen_top2 { top: 40px; position: relative;}
.logo_zarpe { max-width:200px; width:100%; } 
.linea_zarpe { max-width:340px; margin-left:-40px; }
.ocultar_en_movil {display:none; }
.ancho_tabla_compartir { max-width:320px; } 
.ancho_6 { width:96%; padding:2px; float: none; margin-left: -10px; }
.ancho_4 { width:100%; padding:2px; float:none; margin-left: 0px; } 
.ancho_td5 { width: 12%; }
.ancho_estado  { width:44px;  }
.ancho_correo1 { width:50%; padding:5px; float:left; margin-top:-10px;}
.ancho_correo2 { width:100%; padding:5px; float:left; margin-top:-2px; margin-bottom:40px; }
.boton_zarpe3 { margin-bottom: 0px; }
.icono_compartir3 { margin-left: 30px; width:36px;}
.icono_compartir4 { margin-left: 30px; width: 28px;}
.borde_div_zarpe { width:280px;  }
.borde_div_zarpe3 { width:300px;  }
.nav2 { margin-left: -50px;}
.ver_en_movil  { visibility: visible !important;  display: inline-block!important;}
.subir_comillas  { margin-top:-330px; }
.banner_1 { background-image: url("../../images/zarpe_fondo1.jpg"); width:100%; background-size: 400px 282px; background-position: 0px 0px;}  
.banner_5 { background-image: url("../../images/zarpe_fondo10c.jpg"); width:100%; background-size: 600px 770px; background-position: -170px -60px;}
.banner_7 { background-image: url("../../images/zarpe_fondo16b.jpg"); width:100%; background-size: 700px 800px; background-position: -290px -110px; height: 640px;}
.banner_9 { background-image: url("../../images/zarpe_fondo28b.jpg"); background-size: 800px 850px;  background-position: -350px -70px;}
.titulo_1 { font-size: 12px;line-height: 12px;}
.titulo_2 { font-size: 22px; letter-spacing: -1px; line-height: 28px;}
.titulo_3 { font-size: 26px; color:#ffffff; line-height: 25px;}
.titulo_4 { font-size: 21px; color:#052844; letter-spacing: -1px; }
.titulo_4b { font-size: 22px;  }
.titulo_8b { font-size: 16px; }
.titulo_5 { font-size: 17px; line-height: 15px; letter-spacing: -1px; }
.titulo_7 { font-size: 16px; line-height: 1.6;}
.titulo_7c { font-size: 16px; line-height: 1.6;}
.titulo_7b { font-size: 18px; }
.titulo_9 { font-size: 14px; line-height: 17px;}
.titulo_9b { font-size: 19px; }
.titulo_9c { font-size: 19px; }
.titulo_11 { font-size: 16px;}
.titulo_15 { font-size: 20px;}
.texto_11 { font-size: 13px; font-family:graviola_softthin;}
.texto_12 { font-size: 15px; }
.texto_10 { font-size: 17px;}
.texto_7 { font-size: 12px; line-height: 10px;}
.texto_8 { font-size: 13px; line-height: 15px; letter-spacing: -1px;}
.texto_4 { font-size: 13px; line-height: 10px;}
.texto_4c, .texto_4c[disabled] { font-size: 10px!important; line-height: 10px;}
.texto_8b { font-size: 17px!important; line-height: 25px; letter-spacing: -0.5px; }
.texto_9c { font-size: 13px;line-height: 13px;}
.texto_6 { font-size: 8px; letter-spacing: -0.5px;}
.texto_6b { font-size: 12px; }
.texto_6c { font-size: 15px; }
.texto_3 { font-size: 15px; line-height:17px;}
.texto_2 { font-size: 16px; }
.texto_3b { font-size: 10px; line-height: 13px;}
.texto_13 { font-size: 12px;font-family: graviola_softthin;}
.texto_14 { font-size: 15px; line-height:15px;}
.texto_1 { font-size: 18px; line-height: 18px;}
.texto_15 { font-size: 15px;}
.texto_16 { font-size: 17px;line-height: 20px; letter-spacing: -0.5px; }
.texto_17 { font-size: 14px; letter-spacing: -0.5px;}
.texto_18, .texto_19 { font-size: 10px!important;line-height: 9px;}
.nav > li > a { position: relative;display: block; padding: 5px 5px!important;}

.gratis { width: 110px; margin-top: -24px;margin-left: 120px;}
.gratis2 { width: 160px; margin-top: -42px;margin-left: 106px;}
.alienar_boton  { float:right; position: relative; margin-right:30px; margin-top:-100px; }
.alienar_boton2  { float:right; position: relative; margin-right:30px; margin-top:-50px; }
.boton_zarpe6 {  font-size: 15px;}
.boton_zarpe9 {  border-radius:50px; padding:4px; color:#ffffff; font-size: 12px; text-align:center; width:120px;
                padding-left:6px; padding-right:6px; display: block; text-decoration: none!important;} 
.ancho_td3 { width: 36%;}
.ancho_td4 { width: 12%;}
.padding_1 { padding-right:5px;}
.popup_ancho3 { width:370px; height:380px}
.popup_ancho {width:100%!important; height:740px!important; margin-top: 50px;}
.ocultar_en_movil3 { display:none!important;}
.ancho_tablet_1 {width:60%; margin-left: 0.5%; padding-right: 5px!important;}
.btn-ganolife3 {font-size:16px!important; padding:16px; color:#ffffff; line-height:65px; padding-top: 15px; }
.margen_menu { padding-left: 0px!important; margin-left: 7px!important;}
.margen_izq4 {padding-left:10px;} 
.margen_izq5 {padding-left:10px;} 

.campo_texto_zarpe {font-size: 13px; height: 38px;}
.campo_texto_zarpe_select, .campo_texto_zarpe_select:disabled {font-size: 13px; font-family: graviola_softbook; border: 1px solid #ADAEB0; }
.popup_contactos { left: 20px; margin-top: -205px; width:80%!important;}
.zarpe_video_popup_mascara {width: 125px; height: 125px; overflow: hidden; margin-left: 15px;  margin-top: 0px;}
.popup_titulo_video { margin-top: 14px; margin-top: 15px; display: inline-block;}
.popup_contactos2 { left: 20px; margin-top: 120px; width:80%!important; border: 1px solid #ADAEB0; line-height: 1;}
.popup_contactos3 { left: 20px; margin-top: 114px; width:80%!important; }
.zarpe_video_popuptexto {width: 94%; display: block;}
.zarpe_boton_popup {display: block; margin-top:40px}
.zarpe_popup_contacto { position: fixed; margin-top: -25px; margin-left: -132px; } 
.zarpe_popup_contacto2 { position: fixed; margin-top: -25px; margin-left: -98px; } 
.zarpe_popup_contacto3 { position: fixed; margin-top: -25px; margin-left: -64px; } 
.zarpe_popup_contacto4 { position: fixed; margin-top: -25px; margin-left: -30px; } 

select.minimal { 
  background-image: url("../../images/zarpe_flecha6.png"); 
  background-position:
    calc(100% - 14px) calc(1em - 1px),
    calc(100% - 15px) calc(1em + 2px),
    calc(100% - 2.5em) 0.5em;
  background-repeat: no-repeat;
}

select.minimal:focus {
  background-image: background-image: url("../../images/zarpe_flecha6.png"); 
  background-position:
    calc(100% - 14px) calc(1em - 1px),
    calc(100% - 15px) calc(1em + 2px),
    calc(100% - 2.5em) 0.5em;
  background-repeat: no-repeat;
  border-color: green;
  outline: 0;
}


}



@media (max-device-width: 375px)  {
.fondo_preload { width: 280px!important; background:#000000; border-radius:10px; padding:20px;}
.menu_padding2 { margin-left:3px; float:left; width:74px; margin-right:3px; text-decoration:none; margin-top:10px; margin-bottom:10px;}

#slide1:checked ~ #commands label:nth-child(2), #slide2:checked ~ #commands label:nth-child(3), #slide3:checked ~ #commands label:nth-child(4), #slide4:checked ~ #commands label:nth-child(5), #slide5:checked ~ #commands label:nth-child(1) {
    margin: -30px 10px 0px 0px; }
#slides2 { padding: 0px; margin: 0px 0 0;}

.margen_derecha1  { top:-25px; right:-300px;  }
.zarpe_iconomenu { width:15px;}
.ancho_tabla_comentarios { width: 375px;}
.caja_comentarios { width:320px; margin-left:-235px; margin-top:110px;}
.comentarios_foto { margin-top: -200px;  width: 140px;}
.comentarios_productos { margin-left: -235px!important; margin-top: 350px;}
.boton_zarpe4 { margin-top:30px; font-size: 12px; display: block;}
.boton_producto_zarpe, .boton_producto_zarpe:hover { }
.titulo_1 { font-size: 12px;line-height: 12px;}
.titulo_2 { font-size: 20px; letter-spacing: -1px; line-height: 28px;}
.titulo_3 { font-size: 24px; color:#ffffff;}
.titulo_4 { font-size: 19px; color:#052844; letter-spacing: -1px; }
.titulo_5 { font-size: 17px;}
.titulo_7 { font-size: 14px; }
.titulo_7c { font-size: 14px; }
.titulo_9 { font-size: 13px; line-height: 13px;}
.titulo_9b { font-size: 16px; }
.titulo_9c { font-size: 18px; }
.titulo_13 { font-size: 23px;}
.titulo_14 { font-size: 32px;}
.texto_17 { font-size: 11px;}
.texto_3 { font-size: 14px; line-height: 18px;}
.texto_8 { font-size: 11px; line-height: 13px; letter-spacing: -1px;}
.texto_6 { font-size: 8px; }
.texto_6c { font-size: 14px; }
.texto_11 { font-size: 11px; letter-spacing: -1px; font-family:graviola_softthin;}
.texto_12 { font-size: 14px; }
.texto_16 { font-size: 16px;line-height: 16px; letter-spacing: -0.5px; }
.texto_4c, .texto_4c[disabled] { font-size: 9px!important; line-height: 10px;}
.fondo_div_nombre { background-position: 0px -5px; background-size: 210px 42px ;padding-top: 7px; padding-bottom: 10px; } 
.fondo_1 { background-position: -280px  0px; background-size: 860px  ; height: 350px; padding-top: 10px;   }
.fondo_4 { background-position: -320px  0px; background-size: 860px  ; height: 350px; padding-top: 10px;   }
.margen_izq {margin-left:20px;} 
.margen_izq2 {margin-left:40px;} 
.margen_top {margin-top:-40px;}
.logo_zarpe { max-width:200px; width:100%; } 
.linea_zarpe { max-width:320px; margin-left:-40px; }
.ocultar_en_movil {display:none; }
.ancho_6 { width:100%; padding:2px; float: none; margin-left: -25px; }
.ancho_4 { width:100%; padding:2px; float:none; margin-left: 0px; }
.ancho_select { width:130px!important; font-size: 15px; }
.ancho_estado  { width:35px;  }
.ancho_correo1 { width:48%; padding:4px; float:left; margin-top:-10px;}
.ancho_correo2 { width:90%; }
.ancho_td2 { width: 32%;}
.ancho_td3 { width: 36%;}
.ancho_td5 { width: 10%;}
.borde_div_zarpe {padding-left: 20px;padding-right: 20px; width:250px;}
.icono_compartir3 { margin-left: 30px; width: 36px;}
.icono_compartir4 { margin-left: 30px; width: 28px;}
.nav2 { margin-left: -20px; }
.subir_comillas  { margin-top:-330px; }
.banner_5 { background-image: url("../../images/zarpe_fondo10c.jpg"); width:100%; background-size: 600px 770px; background-position: -200px -170px; 
            margin-bottom: 40px; height: 590px;}
.banner_7 { background-image: url("../../images/zarpe_fondo16b.jpg"); width:100%; background-size: 600px 680px; background-position: -234px -10px; height: 650px;}
.banner_9 { background-image: url("../../images/zarpe_fondo28b.jpg"); background-size: 700px 750px;  background-position: -304px 0px;}
.gratis { width: 110px; margin-top: -24px;margin-left: 110px;}
.gratis2 { width: 160px; margin-top: -42px;margin-left: 90px;}
.popup_ancho3 { width:340px; height:380px}
.btn-ganolife3 {font-size:13px!important; padding:13px; color:#ffffff; line-height:65px; padding-top: 15px; }
.fondo_3linea {background-position: 0px -25px;}
.radio_button_plan_texto6 { margin-left: 22px!important; font-size: 17px;}

.zarpe_margen_izquierda4 { margin-left: 4px!important; }

.popup_contactos { left: 20px; margin-top: -225px; width:80%!important; }
.popup_contactos2 { left: 20px; margin-top: 120px; width:80%!important; border: 1px solid #ADAEB0; line-height: 1; display: block;}
.popup_contactos3 { left: 20px; margin-top: 134px; width:80%!important; }
.zarpe_video_popup_mascara {width: 110px; height: 110px; overflow: hidden; margin-left: 15px;  margin-top: 0px;}
.zarpe_video_popup { margin-left: -40px;}

}



@media (max-device-width: 320px)  {
.fondo_preload { width: 250px!important; background:#000000; border-radius:10px; padding:20px;}
.carousel_comentarios { max-width: 300px;}
.ancho_tabla_comentarios { width: 300px;}
.caja_comentarios { width:290px; margin-left:-205px; margin-top:50px;}
.comentarios_foto { margin-top: -200px; margin-left: 90px; width: 120px;}
.comentarios_productos { margin-left: -215px!important; margin-top: 320px;}



.margen_derecha1  { top: -25px; right: -250px;  }
.boton_zarpe9 {  border-radius:50px; padding:4px; color:#ffffff; font-size: 12px; text-align:center; width:100px;
                padding-left:5px; padding-right:5px; display: block; text-decoration: none!important;} 
.boton_producto_zarpe, .boton_producto_zarpe:hover { }
.zarpe_margen_izquierda { margin-left: -50px; }
.zarpe_margen_izquierda2 { width: 360px; margin-left: -280px;}
.zarpe_margen_izquierda3 { margin-left: -310px!important; margin-top: 310px; width: 200px;}
.ancho_tabla_compartir { max-width:254px; margin-left: 0px;} 
.borde_div_zarpe { padding-left: 10px; padding-right: 10px;  width:210px;}
.borde_div_zarpe3 { width:220px;  }
.boton_zarpe_degrade3 { font-size: 13px;}
.boton_zarpe_degrade5, .boton_zarpe_degrade5_hover, .boton_zarpe_degrade5:focus { font-size: 20px!important;}
.icono_compartir3 { margin-left: 30px;}
.icono_compartir4 { margin-left: 30px;}
.titulo_1 { font-size: 11px;line-height: 12px;}
.titulo_7 { font-size: 13px;}
.titulo_7c { font-size: 13px;}
.texto_7 { font-size: 12px;}
.texto_1 { font-size: 15px;}
.texto_3 { font-size: 13px;}
.texto_3b { font-size: 12px; line-height: 13px;}
.texto_4 {font-size: 10px; line-height: 11px;}
.texto_9 { font-size: 15px;line-height: 15px;}
.texto_9c { font-size: 10px;line-height: 13px;}
.texto_18, .texto_19 { font-size: 7px!important;line-height: 9px;}
.texto_11 { font-size: 11px; letter-spacing: -1px; font-family:graviola_softthin;}
.ancho_6 { width:100%; padding:2px; float: none; margin-left: -20px; }
.ancho_4 { width:100%; padding:2px; float:none; margin-left: 0px; } 
.icono_compartir2 { width:40px; padding:0px;  }
.banner_5 { background-image: url("../../images/zarpe_fondo10c.jpg"); width:100%; background-size: 600px 770px; background-position: -235px -120px;}
.banner_7 { background-image: url("../../images/zarpe_fondo16b.jpg"); width:100%; background-size: 600px 700px; background-position: -270px -20px;}
.banner_9 { background-image: url("../../images/zarpe_fondo28b.jpg"); background-size: 700px 750px;  background-position: -333px 0px;}
.gratis2 { width: 170px; margin-top: -40px;margin-left: 80px;}
.texto_10 { font-size: 15px;}
.boton_zarpe6 {  font-size: 13px;}
.ancho_tablet_1 {width:62%!important; margin-left: 0.5%; padding-right: 5px!important;}
.btn-ganolife3 {font-size:13px!important; padding:10px!important; padding-top: 15px!important; }
.ancho_estado  { width:30px;  }
.fondo_3linea { background-position: 0px -28px;}
.ancho_td2 { width: 100px;}
.ancho_td3 { width: 100px;}
.ancho_td5 { width: 34px;}
.ancho_td4 { width: 34px;}
.zarpe_ancho_producto { width: 100px;}
.ancho_mitad2 { width:98%; } 
.ancho_mitad3 { width:98%; }
.boton_zarpe10 {font-size:13px; }
.margen_izq6 {margin-left:-140px;} 
.margen_izq7 {margin-left:-80px;} 
.menu_padding2 { margin-left: 5px; width: 40px; margin-right: 18px;}
.margen_izq8 {margin-left:8px;} 
.texto_20 { font-size: 12px; line-height: 9px!important;}
.texto_20b { font-size: 7px; line-height: 7px!important;}
.texto_menu { font-size: 9px;line-height: 9px!important;}

#slider #slides { height: 90px;}
#slide1:checked ~ #commands label:nth-child(2), #slide2:checked ~ #commands label:nth-child(3), #slide3:checked ~ #commands label:nth-child(4), #slide4:checked ~ #commands label:nth-child(5), #slide5:checked ~ #commands label:nth-child(1) {
    margin: -10px 10px 0px 0px;}
#slide1:checked ~ #commands label:nth-child(5), #slide2:checked ~ #commands label:nth-child(1), #slide3:checked ~ #commands label:nth-child(2), #slide4:checked ~ #commands label:nth-child(3), #slide5:checked ~ #commands label:nth-child(4) {
    margin: -10px 30px 0px 0px;}
    
.texto_4c, .texto_4c[disabled] { font-size: 8px!important; line-height: 10px;}
.texto_8b { font-size: 15px!important; line-height: 15px; letter-spacing: -0.5px; }
.texto_8 { font-size: 10px!important;  }
.popup_contactos { left: 20px; margin-top: -210px; width:80%!important; }
.popup_contactos3 { margin-top: 120px; }
.campo_texto_zarpe { font-size: 13px; height: 30px;} 
.zarpe_video_popup_mascara {width: 90px; height: 90px; overflow: hidden; margin-left: 15px;  margin-top: 0px;}

.zarpe_margen_izquierda4 { margin-left: 4px!important; }
.check_button_zarpe > input[type=checkbox] + label { height: 35px; background-size: 35px 30px; 
                                                     background-position: 0px 4px; padding-left: 38px !important;}

}






body { margin: 0;  }
article, aside, details, figcaption, figure, footer, header, hgroup, main, menu, nav, section, summary { display: block;  }
audio,canvas,progress,video { display: inline-block; vertical-align: baseline; }
audio:not([controls]) { display: none;  height: 0; }
[hidden], template {  display: none; }

a {  background-color: transparent; }
a:active, a:hover {  outline: 0; }
abbr[title] {  border-bottom: 1px dotted; }
b,strong {  font-weight: bold; }
dfn {  font-style: italic; }
h1 { font-size: 2em;  margin: 0.67em 0; }
mark {  background: #ff0;  color: #000; }
small { font-size: 80%; }

sub,sup { font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; }
sup {  top: -0.5em; }
sub {  bottom: -0.25em; }
img {  border: 0; }
svg:not(:root) { overflow: hidden; }
figure { margin: 1em 40px; }
hr { box-sizing: content-box; height: 0; }

pre { overflow: auto; }
code,kbd,pre,samp {  font-size: 1em; }
button,input,optgroup,select,textarea { color: inherit; font: inherit; margin: 0; }
button { overflow: visible; }
button,select {  text-transform: none; }
button,html input[type="button"],input[type="reset"],input[type="submit"] {  -webkit-appearance: button;  cursor: pointer; }
button[disabled],
html input[disabled] {  cursor: default; }
button::-moz-focus-inner,
input::-moz-focus-inner {  border: 0;  padding: 0; }
input { line-height: normal; }
input[type="checkbox"],
input[type="radio"] {  box-sizing: border-box;  padding: 0; }
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button { height: auto; }
input[type="search"] { -webkit-appearance: textfield; box-sizing: content-box; }
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration { -webkit-appearance: none; }

.wrapper-siginup .btn-facebook, .wrapper-siginup .btn-facebook:hover { font-size: 18px; color: #ffffff !important; border:1px solid #ffffff !important;}
    
fieldset { border: 1px solid #c0c0c0; margin: 0 2px; padding: 0.35em 0.625em 0.75em; }
legend { border: 0; padding: 0; }
textarea { overflow: auto; }
optgroup { font-weight: bold; }
table { border-collapse: collapse; border-spacing: 0; }
td,th { padding: 0; }

/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *, *:before, *:after { background: transparent !important; color: #000 !important; box-shadow: none !important; text-shadow: none !important; }
  a,  a:visited { text-decoration: underline; }
  a[href]:after { content: " (" attr(href) ")"; }
  abbr[title]:after { content: " (" attr(title) ")"; }
  a[href^="#"]:after,
  a[href^="javascript:"]:after { content: ""; }
  pre, blockquote { border: 1px solid #999; page-break-inside: avoid; }
  thead { display: table-header-group; }
  tr, img { page-break-inside: avoid; }
  img { max-width: 100% !important; }
  p, h2, h3 { orphans: 3; widows: 3; }
  h2, h3 { page-break-after: avoid; }
  .navbar { display: none; }
  .btn > .caret,  .dropup > .btn > .caret { border-top-color: #000 !important; }
  .label { border: 1px solid #000; }
  .table { border-collapse: collapse !important; }
  .table td,.table th { background-color: #fff !important; }
  .table-bordered th,  .table-bordered td { border: 1px solid #ddd !important; } }


@font-face {
  font-family: 'Glyphicons Halflings'; src: url("../fonts/bootstrap/glyphicons-halflings-regular.eot");
  src: url("../fonts/bootstrap/glyphicons-halflings-regular.eot?#iefix") format("embedded-opentype"), url("../fonts/bootstrap/glyphicons-halflings-regular.woff2") format("woff2"), url("../fonts/bootstrap/glyphicons-halflings-regular.woff") format("woff"), url("../fonts/bootstrap/glyphicons-halflings-regular.ttf") format("truetype"), url("../fonts/bootstrap/glyphicons-halflings-regular.svg#glyphicons_halflingsregular") format("svg"); }

.glyphicon { position: relative; top: 1px; display: inline-block; font-family: 'Glyphicons Halflings'; font-style: normal; font-weight: normal;
  line-height: 1; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; }

.glyphicon-asterisk:before { content: "\002a"; } 
.glyphicon-plus:before { content: "\002b"; }
.glyphicon-euro:before, .glyphicon-eur:before { content: "\20ac"; }
.glyphicon-minus:before { content: "\2212"; }
.glyphicon-cloud:before { content: "\2601"; }
.glyphicon-envelope:before { content: "\2709"; }
.glyphicon-pencil:before { content: "\270f"; }
.glyphicon-glass:before { content: "\e001"; }
.glyphicon-music:before { content: "\e002"; }
.glyphicon-search:before { content: "\e003"; }
.glyphicon-heart:before { content: "\e005"; }
.glyphicon-star:before { content: "\e006"; }
.glyphicon-star-empty:before { content: "\e007"; }
.glyphicon-user:before { content: "\e008"; }
.glyphicon-film:before { content: "\e009"; }
.glyphicon-th-large:before { content: "\e010"; }
.glyphicon-th:before { content: "\e011"; }
.glyphicon-th-list:before { content: "\e012"; }
.glyphicon-ok:before { content: "\e013"; }
.glyphicon-remove:before { content: "\e014"; }
.glyphicon-zoom-in:before { content: "\e015"; }
.glyphicon-zoom-out:before { content: "\e016"; }
.glyphicon-off:before { content: "\e017"; }
.glyphicon-signal:before { content: "\e018"; }
.glyphicon-cog:before { content: "\e019"; }
.glyphicon-trash:before { content: "\e020"; }
.glyphicon-home:before { content: "\e021"; }
.glyphicon-file:before { content: "\e022"; }
.glyphicon-time:before { content: "\e023"; }
.glyphicon-road:before { content: "\e024"; }
.glyphicon-download-alt:before { content: "\e025"; }
.glyphicon-download:before { content: "\e026"; }
.glyphicon-upload:before { content: "\e027"; }
.glyphicon-inbox:before { content: "\e028"; }
.glyphicon-play-circle:before { content: "\e029"; }
.glyphicon-repeat:before { content: "\e030"; }
.glyphicon-refresh:before {  content: "\e031"; }
.glyphicon-list-alt:before {  content: "\e032"; }
.glyphicon-lock:before {  content: "\e033"; }
.glyphicon-flag:before {  content: "\e034"; }
.glyphicon-headphones:before {  content: "\e035"; }
.glyphicon-volume-off:before { content: "\e036"; }
.glyphicon-volume-down:before {  content: "\e037"; }
.glyphicon-volume-up:before {  content: "\e038"; }
.glyphicon-qrcode:before {  content: "\e039"; }
.glyphicon-barcode:before {  content: "\e040"; }
.glyphicon-tag:before {  content: "\e041"; }
.glyphicon-tags:before {  content: "\e042"; }
.glyphicon-book:before { content: "\e043"; }
.glyphicon-bookmark:before {  content: "\e044"; }
.glyphicon-print:before {  content: "\e045"; }
.glyphicon-camera:before {  content: "\e046"; }
.glyphicon-font:before {  content: "\e047"; }
.glyphicon-bold:before {  content: "\e048"; }
.glyphicon-italic:before {  content: "\e049"; }
.glyphicon-text-height:before { content: "\e050"; }
.glyphicon-text-width:before {  content: "\e051"; }
.glyphicon-align-left:before { content: "\e052"; }
.glyphicon-align-center:before {  content: "\e053"; }
.glyphicon-align-right:before {  content: "\e054"; }
.glyphicon-align-justify:before {  content: "\e055"; }
.glyphicon-list:before {  content: "\e056"; }
.glyphicon-indent-left:before {  content: "\e057"; }
.glyphicon-indent-right:before {  content: "\e058"; }
.glyphicon-facetime-video:before {  content: "\e059"; }
.glyphicon-picture:before { content: "\e060"; }
.glyphicon-map-marker:before {  content: "\e062"; }
.glyphicon-adjust:before {  content: "\e063"; }
.glyphicon-tint:before {  content: "\e064"; }
.glyphicon-edit:before {  content: "\e065"; }
.glyphicon-share:before {  content: "\e066"; }
.glyphicon-check:before { content: "\e067"; }
.glyphicon-move:before {  content: "\e068"; }
.glyphicon-step-backward:before {  content: "\e069"; }
.glyphicon-fast-backward:before { content: "\e070"; }
.glyphicon-backward:before {  content: "\e071"; }
.glyphicon-play:before {  content: "\e072"; }
.glyphicon-pause:before {  content: "\e073"; }
.glyphicon-stop:before {  content: "\e074"; }
.glyphicon-forward:before { content: "\e075"; }
.glyphicon-fast-forward:before {  content: "\e076"; }
.glyphicon-step-forward:before {  content: "\e077"; }
.glyphicon-eject:before {  content: "\e078"; }
.glyphicon-chevron-left:before {  content: "\e079"; }
.glyphicon-chevron-right:before {  content: "\e080"; }
.glyphicon-plus-sign:before {  content: "\e081"; }
.glyphicon-minus-sign:before {  content: "\e082"; }
.glyphicon-remove-sign:before {  content: "\e083"; }
.glyphicon-ok-sign:before {  content: "\e084"; }
.glyphicon-question-sign:before {  content: "\e085"; }
.glyphicon-info-sign:before {  content: "\e086"; }
.glyphicon-screenshot:before {  content: "\e087"; }
.glyphicon-remove-circle:before {  content: "\e088"; }
.glyphicon-ok-circle:before {  content: "\e089"; }
.glyphicon-ban-circle:before {  content: "\e090"; }
.glyphicon-arrow-left:before {  content: "\e091"; }
.glyphicon-arrow-right:before {  content: "\e092"; }
.glyphicon-arrow-up:before {  content: "\e093"; }
.glyphicon-arrow-down:before {  content: "\e094"; }
.glyphicon-share-alt:before {  content: "\e095"; }
.glyphicon-resize-full:before {  content: "\e096"; }
.glyphicon-resize-small:before {  content: "\e097"; }
.glyphicon-exclamation-sign:before {  content: "\e101"; }
.glyphicon-gift:before {  content: "\e102"; }
.glyphicon-leaf:before {  content: "\e103"; }
.glyphicon-fire:before {  content: "\e104"; }
.glyphicon-eye-open:before {  content: "\e105"; }
.glyphicon-eye-close:before {  content: "\e106"; }
.glyphicon-warning-sign:before {  content: "\e107"; }
.glyphicon-plane:before {  content: "\e108"; }
.glyphicon-calendar:before {  content: "\e109"; }
.glyphicon-random:before {  content: "\e110"; }
.glyphicon-comment:before {  content: "\e111"; }
.glyphicon-magnet:before {  content: "\e112"; }
.glyphicon-chevron-up:before {  content: "\e113"; }
.glyphicon-chevron-down:before {  content: "\e114"; }
.glyphicon-retweet:before {  content: "\e115"; }
.glyphicon-shopping-cart:before {  content: "\e116"; }
.glyphicon-folder-close:before {  content: "\e117"; }
.glyphicon-folder-open:before {  content: "\e118"; }
.glyphicon-resize-vertical:before {  content: "\e119"; }
.glyphicon-resize-horizontal:before {  content: "\e120"; }
.glyphicon-hdd:before {  content: "\e121"; }
.glyphicon-bullhorn:before {  content: "\e122"; }
.glyphicon-bell:before {  content: "\e123"; }
.glyphicon-certificate:before {  content: "\e124"; }
.glyphicon-thumbs-up:before {  content: "\e125"; }
.glyphicon-thumbs-down:before {  content: "\e126"; }
.glyphicon-hand-right:before {  content: "\e127"; }
.glyphicon-hand-left:before {  content: "\e128"; }
.glyphicon-hand-up:before {  content: "\e129"; }
.glyphicon-hand-down:before {  content: "\e130"; }
.glyphicon-circle-arrow-right:before { content: "\e131"; }
.glyphicon-circle-arrow-left:before {  content: "\e132"; }
.glyphicon-circle-arrow-up:before {  content: "\e133"; }
.glyphicon-circle-arrow-down:before {  content: "\e134"; }
.glyphicon-globe:before {  content: "\e135"; }
.glyphicon-wrench:before {  content: "\e136"; }
.glyphicon-tasks:before {  content: "\e137"; }
.glyphicon-filter:before {  content: "\e138"; }
.glyphicon-briefcase:before {  content: "\e139"; }
.glyphicon-fullscreen:before {  content: "\e140"; }
.glyphicon-dashboard:before {  content: "\e141"; }
.glyphicon-paperclip:before {  content: "\e142"; }
.glyphicon-heart-empty:before {  content: "\e143"; }
.glyphicon-link:before {  content: "\e144"; }
.glyphicon-phone:before {  content: "\e145"; }
.glyphicon-pushpin:before {  content: "\e146"; }
.glyphicon-usd:before {  content: "\e148"; }
.glyphicon-gbp:before {  content: "\e149"; }
.glyphicon-sort:before {  content: "\e150"; }
.glyphicon-sort-by-alphabet:before {  content: "\e151"; }
.glyphicon-sort-by-alphabet-alt:before {  content: "\e152"; }
.glyphicon-sort-by-order:before {  content: "\e153"; }
.glyphicon-sort-by-order-alt:before {  content: "\e154"; }
.glyphicon-sort-by-attributes:before {  content: "\e155"; }
.glyphicon-sort-by-attributes-alt:before {  content: "\e156"; }
.glyphicon-unchecked:before {  content: "\e157"; }
.glyphicon-expand:before {  content: "\e158"; }
.glyphicon-collapse-down:before {  content: "\e159"; }
.glyphicon-collapse-up:before {  content: "\e160"; }
.glyphicon-log-in:before {  content: "\e161"; }
.glyphicon-flash:before {  content: "\e162"; }
.glyphicon-log-out:before {  content: "\e163"; }
.glyphicon-new-window:before {  content: "\e164"; }
.glyphicon-record:before {  content: "\e165"; }
.glyphicon-save:before {  content: "\e166"; }
.glyphicon-open:before {  content: "\e167"; }
.glyphicon-saved:before {  content: "\e168"; }
.glyphicon-import:before {  content: "\e169"; }
.glyphicon-export:before {  content: "\e170"; }
.glyphicon-send:before { content: "\e171"; }
.glyphicon-floppy-disk:before {  content: "\e172"; }
.glyphicon-floppy-saved:before {  content: "\e173"; }
.glyphicon-floppy-remove:before {  content: "\e174"; }
.glyphicon-floppy-save:before {  content: "\e175"; }
.glyphicon-floppy-open:before {  content: "\e176"; }
.glyphicon-credit-card:before {  content: "\e177"; }
.glyphicon-transfer:before {  content: "\e178"; }
.glyphicon-cutlery:before {  content: "\e179"; }
.glyphicon-header:before {  content: "\e180"; }
.glyphicon-compressed:before {  content: "\e181"; }
.glyphicon-earphone:before {  content: "\e182"; }
.glyphicon-phone-alt:before {  content: "\e183"; }
.glyphicon-tower:before {  content: "\e184"; }
.glyphicon-stats:before {  content: "\e185"; }
.glyphicon-sd-video:before {  content: "\e186"; }
.glyphicon-hd-video:before {  content: "\e187"; }
.glyphicon-subtitles:before {  content: "\e188"; }
.glyphicon-sound-stereo:before { content: "\e189"; }
.glyphicon-sound-dolby:before {  content: "\e190"; }
.glyphicon-sound-5-1:before {  content: "\e191"; }
.glyphicon-sound-6-1:before {  content: "\e192"; }
.glyphicon-sound-7-1:before {  content: "\e193"; }
.glyphicon-copyright-mark:before {  content: "\e194"; }
.glyphicon-registration-mark:before {  content: "\e195"; }
.glyphicon-cloud-download:before {  content: "\e197"; }
.glyphicon-cloud-upload:before {  content: "\e198"; }
.glyphicon-tree-conifer:before {  content: "\e199"; }
.glyphicon-tree-deciduous:before {  content: "\e200"; }
.glyphicon-cd:before {  content: "\e201"; }
.glyphicon-save-file:before {  content: "\e202"; }
.glyphicon-open-file:before {  content: "\e203"; }
.glyphicon-level-up:before {  content: "\e204"; }
.glyphicon-copy:before {  content: "\e205"; }
.glyphicon-paste:before {  content: "\e206"; }
.glyphicon-alert:before {  content: "\e209"; }
.glyphicon-equalizer:before {  content: "\e210"; }
.glyphicon-king:before {  content: "\e211"; }
.glyphicon-queen:before {  content: "\e212"; }
.glyphicon-pawn:before {  content: "\e213"; }
.glyphicon-bishop:before {  content: "\e214"; }
.glyphicon-knight:before {  content: "\e215"; }
.glyphicon-baby-formula:before {  content: "\e216"; }
.glyphicon-tent:before { content: "\26fa"; }
.glyphicon-blackboard:before {  content: "\e218"; }
.glyphicon-bed:before {  content: "\e219"; }
.glyphicon-apple:before { content: "\f8ff"; }
.glyphicon-erase:before {  content: "\e221"; }
.glyphicon-hourglass:before {  content: "\231b"; }
.glyphicon-lamp:before {  content: "\e223"; }
.glyphicon-duplicate:before { content: "\e224"; }
.glyphicon-piggy-bank:before {  content: "\e225"; }
.glyphicon-scissors:before {  content: "\e226"; }
.glyphicon-bitcoin:before {  content: "\e227"; }
.glyphicon-btc:before {  content: "\e227"; }
.glyphicon-xbt:before { content: "\e227"; }
.glyphicon-yen:before {  content: "\00a5"; }
.glyphicon-jpy:before {  content: "\00a5"; }
.glyphicon-ruble:before {  content: "\20bd"; }
.glyphicon-rub:before {  content: "\20bd"; }
.glyphicon-scale:before {  content: "\e230"; }
.glyphicon-ice-lolly:before {  content: "\e231"; }
.glyphicon-ice-lolly-tasted:before {  content: "\e232"; }
.glyphicon-education:before {  content: "\e233"; }
.glyphicon-option-horizontal:before {  content: "\e234"; }
.glyphicon-option-vertical:before { content: "\e235"; }
.glyphicon-menu-hamburger:before {  content: "\e236"; }
.glyphicon-modal-window:before {  content: "\e237"; }
.glyphicon-oil:before { content: "\e238"; }
.glyphicon-grain:before {  content: "\e239"; }
.glyphicon-sunglasses:before {  content: "\e240"; }
.glyphicon-text-size:before {  content: "\e241"; }
.glyphicon-text-color:before { content: "\e242"; }
.glyphicon-text-background:before {  content: "\e243"; }
.glyphicon-object-align-top:before {  content: "\e244"; }
.glyphicon-object-align-bottom:before {  content: "\e245"; }
.glyphicon-object-align-horizontal:before {  content: "\e246"; }
.glyphicon-object-align-left:before {  content: "\e247"; }
.glyphicon-object-align-vertical:before {  content: "\e248"; }
.glyphicon-object-align-right:before {  content: "\e249"; }
.glyphicon-triangle-right:before {  content: "\e250"; }
.glyphicon-triangle-left:before {  content: "\e251"; }
.glyphicon-triangle-bottom:before {  content: "\e252"; }
.glyphicon-triangle-top:before {  content: "\e253"; }
.glyphicon-console:before {  content: "\e254"; }
.glyphicon-superscript:before {  content: "\e255"; }
.glyphicon-subscript:before {  content: "\e256"; }
.glyphicon-menu-left:before {  content: "\e257"; }
.glyphicon-menu-right:before {  content: "\e258"; }
.glyphicon-menu-down:before {  content: "\e259"; }
.glyphicon-menu-up:before {  content: "\e260"; }


/* Fuente    font-family: "Montserrat",sans-serif;  */
@font-face {
    font-family: 'Montserratthin'; font-weight: normal; font-style: normal;
    src: url('../../webfontkit/Montserratthin-webfont.eot');
    src: url('../../webfontkit/Montserratthin-webfont.eot?#iefix') format('embedded-opentype'),
         url('../../webfontkit/Montserratthin-webfont.woff2') format('woff2'),
         url('../../webfontkit/Montserratthin-webfont.woff') format('woff'),
         url('../../webfontkit/Montserratthin-webfont.ttf') format('truetype'),
         url('../../webfontkit/Montserratthin-webfont.svg#Montserratthinuploaded_file') format('svg');    
}

@font-face {
    font-family: 'Montserratlight'; font-weight: normal; font-style: normal;
    src: url('../../webfontkit/Montserratlight-webfont.eot');
    src: url('../../webfontkit/Montserratlight-webfont.eot?#iefix') format('embedded-opentype'),
         url('../../webfontkit/Montserratlight-webfont.woff2') format('woff2'),
         url('../../webfontkit/Montserratlight-webfont.woff') format('woff'),
         url('../../webfontkit/Montserratlight-webfont.ttf') format('truetype'),
         url('../../webfontkit/Montserratlight-webfont.svg#Montserratlightuploaded_file') format('svg');    
}

@font-face {
    font-family: 'Montserratbold'; font-weight: normal; font-style: normal;
    src: url('../../webfontkit/Montserrat-bold-webfont.eot');
    src: url('../../webfontkit/Montserrat-bold-webfont.eot?#iefix') format('embedded-opentype'),
         url('../../webfontkit/Montserrat-bold-webfont.woff2') format('woff2'),
         url('../../webfontkit/Montserrat-bold-webfont.woff') format('woff'),
         url('../../webfontkit/Montserrat-bold-webfont.ttf') format('truetype'),
         url('../../webfontkit/Montserrat-bold-webfont.svg#Montserrat-bolduploaded_file') format('svg');
}

@font-face {
    font-family: 'Montserratdemibold'; font-weight: normal; font-style: normal;
    src: url('../../webfontkit/Montserratdemibold-webfont.eot');
    src: url('../../webfontkit/Montserratdemibold-webfont.eot?#iefix') format('embedded-opentype'),
         url('../../webfontkit/Montserratdemibold-webfont.woff2') format('woff2'),
         url('../../webfontkit/Montserratdemibold-webfont.woff') format('woff'),
         url('../../webfontkit/Montserratdemibold-webfont.ttf') format('truetype'),
         url('../../webfontkit/Montserratdemibold-webfont.svg#Montserratdemibolduploaded_file') format('svg');
}

@font-face {
    font-family: 'Montserratextrabold'; font-weight: normal; font-style: normal;
    src: url('../../webfontkit/Montserratextrabold-webfont.eot');
    src: url('../../webfontkit/Montserratextrabold-webfont.eot?#iefix') format('embedded-opentype'),
         url('../../webfontkit/Montserratextrabold-webfont.woff2') format('woff2'),
         url('../../webfontkit/Montserratextrabold-webfont.woff') format('woff'),
         url('../../webfontkit/Montserratextrabold-webfont.ttf') format('truetype'),
         url('../../webfontkit/Montserratextrabold-webfont.svg#Montserratextrabolduploaded_file') format('svg');
}

@font-face {
    font-family: 'Montserratsemibold'; font-weight: normal; font-style: normal;
    src: url('../../webfontkit/Montserratsemibold-webfont.eot');
    src: url('../../webfontkit/Montserratsemibold-webfont.eot?#iefix') format('embedded-opentype'),
         url('../../webfontkit/Montserratsemibold-webfont.woff2') format('woff2'),
         url('../../webfontkit/Montserratsemibold-webfont.woff') format('woff'),
         url('../../webfontkit/Montserratsemibold-webfont.ttf') format('truetype'),
         url('../../webfontkit/Montserratsemibold-webfont.svg#Montserratsemibolduploaded_file') format('svg');
}

@font-face {
    font-family: 'Montserrat'; font-weight: normal; font-style: normal;
    src: url('../../webfontkit/Montserrat-webfont.eot');
    src: url('../../webfontkit/Montserrat-webfont.eot?#iefix') format('embedded-opentype'),
         url('../../webfontkit/Montserrat-webfont.woff2') format('woff2'),
         url('../../webfontkit/Montserrat-webfont.woff') format('woff'),
         url('../../webfontkit/Montserrat-webfont.ttf') format('truetype'),
         url('../../webfontkit/Montserrat-webfont.svg#Montserratuploaded_file') format('svg');
}



/* Tabs vertical  */
.tabordion { color: #777777; display: block; font-family: arial, sans-serif; margin: auto; position: relative; width: 80%; }
.tabordion input[name="sections"] { left: -9999px; position: absolute; top: -9999px;}
.tabordion section { display: block;}
.tabordion section label { cursor: pointer; display: block;  border-bottom: 1px solid #cdcdcd; margin:0px;
  padding: 15px 10px; position: relative; width: 200px; z-index:100; left: -290px; text-align: left;}
.tabordion section article { display: none; left: 120px; width: 96%; padding: 0 0 0 21px; position: absolute; top: 0;text-align: left;}
.tabordion section article:after { bottom: 0; content: ""; display: block; left:-229px; position: absolute; top: 0; width: 220px; z-index:1;}
.tabordion input[name="sections"]:checked + label {  background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
padding: 15px 10px;color: #ffffff; text-decoration:none;border-bottom:1px solid #cdcdcd;
}
.tabordion input[name="sections"]:checked ~ article { display: block;}

.tabordion section label:hover { background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
padding: 15px 10px;color: #ffffff; text-decoration:none;border-bottom:1px solid #cdcdcd;}
.article_altura { height: 740px!important; }
.altura_div_contenedor { height: 570px; }



@media (min-width: 320px) and (max-width: 712px)  {
.tabordion section label { margin: 0px; padding: 10px 10px!important; position: relative; width: 280px;left: 0px;}
.tabordion section article { width: 100%; height: 260px; position: relative; left: -4px; margin-top:10px;}
.tabordion { width: 100%!important;} 
.btn-ganolife_degrade2 {  font-size: 12px!important;width: 44%!important; margin-left:7px!important;padding:5px!important;height:258px!important;}
.altura_div_contenedor { height: auto; }
}

@media (min-width: 375px) and (max-width: 712px)  {
.tabordion section label { margin: 0px; padding: 10px 10px!important; position: relative; width: 320px;left: 0px;}
.tabordion section article { width: 100%; height: 260px; position: relative; left: 0px; margin-top:10px;}
.tabordion { width: 100%!important;} 
.btn-ganolife_degrade2 {  font-size: 12px!important;width: 44%!important; margin-left:7px!important;padding:5px!important;height:240px!important;}
.altura_div_contenedor { height: auto; }
}

@media (min-width: 425px) and (max-width: 712px) {
.tabordion section label { margin:0px;padding : 10px 10px; position: relative; width: 380px; z-index:0; left: 0px;} 
.tabordion section label:hover, .tabordion input[name="sections"]:checked + label  { padding : 10px 10px; } 
.tabordion section article { height: 260px; position: relative; left: 0px; margin-top:10px; margin-left: 16px;}
.article_altura { height: 740px!important; }
.article_altura2 { height: 490px!important; }
.altura_div_contenedor { height: auto; }
.tabordion section article { padding: 0 0 0 0px;}
.tabordion { width: 100%!important;} 
.btn-ganolife_degrade2 {background:#ffffff;padding:10px;font-size:14px!important;color:#777777;width: 44%; margin-left: 15px;display:block;
                        border:1px solid #cdcdcd;float:left; margin-bottom:10px; text-align:left; height:240px;}

}


@media (min-width: 862px) and (max-width: 1024px)  {
.tabordion section article {  left: 150px; width: 88%; }
}


@media (min-width: 713px) and (max-width: 768px)  {
.tabordion section label { left: -254px; width: 200px;}
.tabordion section article {  left: 142px; width: 88%; }
.btn-ganolife_degrade2 {  width: 40%;}
}


@media (min-width: 1366px) { .tabordion { width: 70% }   }


/* Quitar borde en webkit  */
textarea:focus, input:focus{ outline: none!important;}
    
/* Oportunidad  */
.oportunidad_header_boton { width:296px;color:#ffffff; font-size:25px; font-family:'Montserratlight';font-weight:normal; border-left:1px solid #036B3A!important;
border:1px solid rgba(0, 0, 0, 0); height:54px; background-image:url("../../images/oportunidad_boton.jpg"); background-size: 296px 54px;  }
.oportunidad_header_boton2 { width:100%; max-width:400px; border:1px solid rgba(0, 0, 0, 0); height:103px; margin-top:-205px; margin-left:405px; }
.oportunidad_header_tabla { width:100%; max-width:420px; margin-top:-196px; margin-bottom: 130px; b }
.caja_texto_blanco2 { background-color:#ffffff; padding: 12px; font-size: 16px; width: 95%;border:1px solid rgba(0, 0, 0, 0);}
.flecha_gris { width:100%; max-width:240px; margin-top:-10px;}
.header_altura { height: 57px!important;}



@media (min-width: 862px) and (max-width: 1024px) {
.oportunidad_header_boton { width: 210px; height: 38px; margin-top: -11px; background-size: 210px 38px; }
.oportunidad_header_boton2 { width:100%; max-width: 288px; height: 74px; margin-top: -155px; margin-left: 290px; }
.oportunidad_header_tabla { width:100%; max-width:400px; margin-top:-146px; margin-bottom: 130px; }
}

@media (min-width: 713px) and (max-width: 768px) {
.oportunidad_header_boton { width: 160px; height: 29px; margin-top: -32px; background-size: 160px 29px; }
.oportunidad_header_boton2 { width:100%; max-width: 216px; height: 55px; margin-top: -122px; margin-left: 218px;}
.oportunidad_header_tabla { width:100%; max-width: 300px; margin-top: -110px; margin-bottom: 80px; }
.caja_texto_blanco2 { padding: 5px; font-size: 12px; }

}

@media (min-width: 425px) and (max-width: 712px) {
.oportunidad_header_boton { width: 176px;height: 32px; margin-top: -26px; background-size: 176px 32px;}
.oportunidad_header_boton2 { width:100%; max-width: 192px; height: 48px; margin-top: -112px; margin-left: 154px;}
.oportunidad_header_tabla { width:100%; max-width: 320px; margin-top: -116px; margin-bottom: 80px; }
.caja_texto_blanco2 { padding: 6px!important; font-size: 12px!important; }
.flecha_gris { width:100%; max-width:140px; margin-top:-10px;}
.mensajes_oportunidad { margin-top:2px;}
.header_altura { height: 50px!important;}
}

@media (min-width: 321px) and (max-width: 375px) {
.oportunidad_header_boton { width: 156px;height: 28px; margin-top: -44px; background-size: 156px 28px;}
.oportunidad_header_boton2 { width:100%; max-width: 172px;height: 44px; margin-top: -100px; margin-left: 138px;}
.oportunidad_header_tabla { width:100%; max-width: 340px; margin-top: -110px; margin-bottom: 80px; }
.caja_texto_blanco2 { padding: 6px!important; font-size: 12px!important; }
.flecha_gris { width:100%; max-width:110px; margin-top:-10px;}
.header_altura { height: 50px!important;}
}

@media (min-width: 100px) and (max-width: 320px) {
.oportunidad_header_boton { width: 134px; height: 26px; margin-top: -48px; margin-left: -20px; background-size: 134px 26px;}
.oportunidad_header_boton2 { width:100%; max-width: 144px; height: 36px; margin-top: -88px; margin-left: 118px;}
.oportunidad_header_tabla { width:100%; max-width: 280px; margin-top: -94px; margin-bottom: 45px; margin-left: 20px;}
.caja_texto_blanco2 { padding: 5px!important; font-size: 11px!important; margin-bottom: -8px;}
.flecha_gris { width:100%; max-width:110px; margin-top:-10px;}
.header_altura { height: 50px!important;}
}

.efecto_zoom2 {
    box-shadow: 0 0 0px 0 #ffffff !important; -webkit-transform: scale(1.0) perspective(400px) rotateY(0deg) rotateX(0deg); 
    -moz-transform: scale(1.0) perspective(400px) rotateY(0deg) rotateX(0deg);
	-ms-transform: scale(1.0) perspective(400px) rotateY(0deg) rotateX(0deg);  z-index:1;
	transform: scale(1.0) perspective(100px) rotateY(0deg) rotateX(0deg); transition: all 0.16s ease-in-out; }
.efecto_zoom2:hover {
    -webkit-transform: scale(1.1) perspective(100px) rotateY(0deg) rotateX(0deg) !important; 
    -moz-transform: scale(1.1) perspective(100px) rotateY(0deg) rotateX(0deg) !important;transition:all 0.16s ease-in-out;
	-ms-transform:scale(1.1) perspective(100px) rotateY(0deg) rotateX(0deg) !important; z-index:1;
	transform:scale(1.1) perspective(100px) rotateY(0deg) rotateX(0deg) !important;
}


* {  -webkit-box-sizing: border-box;  -moz-box-sizing: border-box;  box-sizing: border-box; }
*:before, *:after { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; }

html {  font-size: 10px;  -webkit-tap-highlight-color: transparent; }
body {  font-size: 14px;   line-height: 1.42857;  color: #333333;  background-color: #fff; }

input, button, select, textarea {  font-size: inherit;  line-height: inherit; }
a {  color: #337ab7;  text-decoration: none; }
a:hover, a:focus {    color: #23527c;    text-decoration: underline; }
a:focus {    outline: thin dotted;    outline: 5px auto -webkit-focus-ring-color;    outline-offset: -2px; }
figure {  margin: 0; }
img {  vertical-align: middle; }
.img-responsive {  display: block;  max-width: 100%;  height: auto; }
.img-rounded {  border-radius: 6px; }
.img-thumbnail { padding: 4px; line-height: 1.42857; background-color: #fff; border: 1px solid #ddd; border-radius: 4px; max-width: 100%; height: auto;
  -webkit-transition: all 0.2s ease-in-out; -o-transition: all 0.2s ease-in-out; transition: all 0.2s ease-in-out; display: inline-block;  }

.img-circle { border-radius: 50%; }

hr { border-top: 1px solid #ccc!important;}
hr { margin-top: 20px; margin-bottom: 20px; border: 0; border-top: 1px solid #eeeeee; }

.sr-only { position: absolute; width: 1px; height: 1px; margin: -1px; padding: 0; overflow: hidden; clip: rect(0, 0, 0, 0); border: 0; }
.sr-only-focusable:active, .sr-only-focusable:focus { position: static; width: auto; height: auto; margin: 0; overflow: visible; clip: auto; }

[role="button"] { cursor: pointer; }

h1, h2, h3, h4, h5, h6,
.h1, .h2, .h3, .h4, .h5, .h6 { line-height: 1.1; color: inherit; }
h1 small, h1 .small, h2 small, h2 .small, h3 small, h3 .small, h4 small, h4 .small, h5 small, h5 .small, h6 small, h6 .small,
.h1 small, .h1 .small, .h2 small, .h2 .small, .h3 small, .h3 .small, .h4 small, .h4 .small, .h5 small, .h5 .small, .h6 small, .h6 .small  {
    font-weight: normal; line-height: 1; color: #777777; }

h1, .h1, h2, .h2, h3, .h3 { margin-top: 20px; margin-bottom: 10px; }
h1 small, h1 .small, .h1 small, .h1 .small, h2 small, h2 .small, .h2 small, .h2 .small, h3 small, h3 .small, .h3 small, .h3 .small { font-size: 65%; }
h4, .h4, h5, .h5, h6, .h6 { margin-top: 10px; margin-bottom: 10px; }
h4 small, h4 .small, .h4 small, .h4 .small, h5 small, h5 .small, .h5 small, .h5 .small, h6 small,
h6 .small, .h6 small, .h6 .small { font-size: 75%; }
h1, .h1 { font-size: 36px; }
h2, .h2 { font-size: 30px; font-family: 'Montserrat' !important;}
h3, .h3 { font-size: 24px; }
h4, .h4 { font-size: 18px; }
h5, .h5 { font-size: 14px; }
h6, .h6 { font-size: 12px; }
h8, .h8 { font-family: "Montserrat" !important; }
p { margin: 0 0 10px; }
.lead { margin-bottom: 20px; font-size: 16px; font-weight: 300; line-height: 1.4; }


@media (min-width: 768px) {
.lead { font-size: 21px; } 
}

small, .small { font-size: 85%; }
mark, .mark { background-color: #fcf8e3; padding: .2em; }
.text-left { text-align: left; }
.text-right { text-align: right; }
.text-center { text-align: center; }
.text-justify { text-align: justify; }
.text-nowrap { white-space: nowrap; }
.text-lowercase { text-transform: lowercase; }
.text-uppercase, .initialism { text-transform: uppercase; }
.text-capitalize { text-transform: capitalize; }
.text-muted { color: #777777; }
.text-primary { color: #337ab7; }
a.text-primary:hover, a.text-primary:focus { color: #286090; }
.text-success { color: #3c763d; }
a.text-success:hover, a.text-success:focus { color: #2b542c; }
.text-info { color: #31708f; }
a.text-info:hover, a.text-info:focus { color: #245269; }
.text-warning { color: #8a6d3b; }
a.text-warning:hover, a.text-warning:focus { color: #66512c; }
.text-danger { color: #a94442; }
a.text-danger:hover, a.text-danger:focus { color: #843534; }
.bg-primary { color: #fff; }
.bg-primary { background-color: #337ab7; }
a.bg-primary:hover, a.bg-primary:focus { background-color: #286090; }
.bg-success { background-color: #dff0d8; }
a.bg-success:hover, a.bg-success:focus { background-color: #c1e2b3; }
.bg-info { background-color: #d9edf7; }
a.bg-info:hover, a.bg-info:focus { background-color: #afd9ee; }
.bg-warning { background-color: #fcf8e3; }
a.bg-warning:hover, a.bg-warning:focus { background-color: #f7ecb5; }
.bg-danger {  background-color: #f2dede; }
a.bg-danger:hover, a.bg-danger:focus {  background-color: #e4b9b9; }
.page-header { padding-bottom: 9px; margin: 40px 0 20px; border-bottom: 1px solid #eeeeee; }

ul, ol { margin-top: 0; margin-bottom: 10px; }
ul ul, ul ol, ol ul, ol ol { margin-bottom: 0; }
.list-unstyled { padding-left: 0; list-style: none; }
.list-inline { padding-left: 0; list-style: none; margin-left: -5px; }
.list-inline > li { display: inline-block; padding-left: 5px; padding-right: 5px; }
dl { margin-top: 0; margin-bottom: 20px; }
dt, dd { line-height: 1.42857; }
dt { font-weight: bold; }
dd { margin-left: 0; }
.dl-horizontal dd:before, .dl-horizontal dd:after { content: " "; display: table; }
.dl-horizontal dd:after { clear: both; }


@media (min-width: 768px) {
.dl-horizontal dt { float: left; width: 160px; clear: left; text-align: right; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; }
.dl-horizontal dd { margin-left: 180px; } 
}

abbr[title], abbr[data-original-title] { cursor: help; border-bottom: 1px dotted #777777; }
.initialism { font-size: 90%; }
blockquote { padding: 10px 20px; margin: 0 0 20px; font-size: 17.5px; border-left: 5px solid #eeeeee; }
blockquote p:last-child, blockquote ul:last-child, blockquote ol:last-child {  margin-bottom: 0; }
blockquote footer, blockquote small, blockquote .small { display: block; font-size: 80%; line-height: 1.42857; color: #777777; }
blockquote footer:before, blockquote small:before, blockquote .small:before { content: '\2014 \00A0'; }
.blockquote-reverse, blockquote.pull-right { padding-right: 15px; padding-left: 0; border-right: 5px solid #eeeeee; border-left: 0; text-align: right; }
.blockquote-reverse footer:before, .blockquote-reverse small:before, .blockquote-reverse .small:before, blockquote.pull-right footer:before,
blockquote.pull-right small:before, blockquote.pull-right .small:before { content: ''; }
.blockquote-reverse footer:after, .blockquote-reverse small:after, .blockquote-reverse .small:after, blockquote.pull-right footer:after,
blockquote.pull-right small:after, blockquote.pull-right .small:after {  content: '\00A0 \2014'; }
address { margin-bottom: 20px; font-style: normal; line-height: 1.42857; }
code, kbd, pre, samp { font-family: "Montserrat",sans-serif; }
code { padding: 2px 4px; font-size: 90%; color: #c7254e; background-color: #f9f2f4; border-radius: 4px; }
kbd { padding: 2px 4px; font-size: 90%; color: #fff; background-color: #333; border-radius: 3px; box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25); }
kbd kbd { padding: 0; font-size: 100%; font-weight: bold; box-shadow: none; }
pre { display: block; padding: 9.5px; margin: 0 0 10px; font-size: 13px; line-height: 1.42857; word-break: break-all; word-wrap: break-word;
  color: #333333; background-color: #f5f5f5; border: 1px solid #ccc; border-radius: 4px; }
pre code { padding: 0; font-size: inherit;  color: inherit;  white-space: pre-wrap;  background-color: transparent;  border-radius: 0; }
.pre-scrollable { max-height: 340px; overflow-y: scroll; }
.container { margin-right: auto; margin-left: auto; padding-left: 15px; padding-right: 15px; }
.container:before, .container:after { content: " "; display: table; }
.container:after {  clear: both; }

@media (min-width: 768px) {
    .container { width: 750px; } }

@media (min-width: 992px) {
    .container { width: 970px; } }

@media (min-width: 1200px) {
    .container { width: 1170px; } }

.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 15px;
  padding-right: 15px; }
  .container-fluid:before, .container-fluid:after {
    content: " ";
    display: table; }
  .container-fluid:after {
    clear: both; }

.row {
  margin-left: -15px;
  margin-right: -15px; }
  .row:before, .row:after {
    content: " ";
    display: table; }
  .row:after {
    clear: both; }

.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 15px;
  padding-right: 15px; }

.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left; }

.col-xs-1 {
  width: 8.33333%; }

.col-xs-2 {
  width: 16.66667%; }

.col-xs-3 {
  width: 25%; }

.col-xs-4 {
  width: 33.33333%; }

.col-xs-5 {
  width: 41.66667%; }

.col-xs-6 {
  width: 50%; }

.col-xs-7 {
  width: 58.33333%; }

.col-xs-8 {
  width: 66.66667%; }

.col-xs-9 {
  width: 75%; }

.col-xs-10 {
  width: 83.33333%; }

.col-xs-11 {
  width: 91.66667%; }

.col-xs-12 {
  width: 100%; }

.col-xs-pull-0 {
  right: auto; }

.col-xs-pull-1 {
  right: 8.33333%; }

.col-xs-pull-2 {
  right: 16.66667%; }

.col-xs-pull-3 {
  right: 25%; }

.col-xs-pull-4 {
  right: 33.33333%; }

.col-xs-pull-5 {
  right: 41.66667%; }

.col-xs-pull-6 {
  right: 50%; }

.col-xs-pull-7 {
  right: 58.33333%; }

.col-xs-pull-8 {
  right: 66.66667%; }

.col-xs-pull-9 {
  right: 75%; }

.col-xs-pull-10 {
  right: 83.33333%; }

.col-xs-pull-11 {
  right: 91.66667%; }

.col-xs-pull-12 {
  right: 100%; }

.col-xs-push-0 {
  left: auto; }

.col-xs-push-1 {
  left: 8.33333%; }

.col-xs-push-2 {
  left: 16.66667%; }

.col-xs-push-3 {
  left: 25%; }

.col-xs-push-4 {
  left: 33.33333%; }

.col-xs-push-5 {
  left: 41.66667%; }

.col-xs-push-6 {
  left: 50%; }

.col-xs-push-7 {
  left: 58.33333%; }

.col-xs-push-8 {
  left: 66.66667%; }

.col-xs-push-9 {
  left: 75%; }

.col-xs-push-10 {
  left: 83.33333%; }

.col-xs-push-11 {
  left: 91.66667%; }

.col-xs-push-12 {
  left: 100%; }

.col-xs-offset-0 {
  margin-left: 0%; }

.col-xs-offset-1 {
  margin-left: 8.33333%; }

.col-xs-offset-2 {
  margin-left: 16.66667%; }

.col-xs-offset-3 {
  margin-left: 25%; }

.col-xs-offset-4 {
  margin-left: 33.33333%; }

.col-xs-offset-5 {
  margin-left: 41.66667%; }

.col-xs-offset-6 {
  margin-left: 50%; }

.col-xs-offset-7 {
  margin-left: 58.33333%; }

.col-xs-offset-8 {
  margin-left: 66.66667%; }

.col-xs-offset-9 {
  margin-left: 75%; }

.col-xs-offset-10 {
  margin-left: 83.33333%; }

.col-xs-offset-11 {
  margin-left: 91.66667%; }

.col-xs-offset-12 {
  margin-left: 100%; }

@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left; }
  .col-sm-1 {
    width: 8.33333%; }
  .col-sm-2 {
    width: 16.66667%; }
  .col-sm-3 {
    width: 25%; }
  .col-sm-4 {
    width: 33.33333%; }
  .col-sm-5 {
    width: 41.66667%; }
  .col-sm-6 {
    width: 50%; }
  .col-sm-7 {
    width: 58.33333%; }
  .col-sm-8 {
    width: 66.66667%; }
  .col-sm-9 {
    width: 75%; }
  .col-sm-10 {
    width: 83.33333%; }
  .col-sm-11 {
    width: 91.66667%; }
  .col-sm-12 {
    width: 100%; }
  .col-sm-pull-0 {
    right: auto; }
  .col-sm-pull-1 {
    right: 8.33333%; }
  .col-sm-pull-2 {
    right: 16.66667%; }
  .col-sm-pull-3 {
    right: 25%; }
  .col-sm-pull-4 {
    right: 33.33333%; }
  .col-sm-pull-5 {
    right: 41.66667%; }
  .col-sm-pull-6 {
    right: 50%; }
  .col-sm-pull-7 {
    right: 58.33333%; }
  .col-sm-pull-8 {
    right: 66.66667%; }
  .col-sm-pull-9 {
    right: 75%; }
  .col-sm-pull-10 {
    right: 83.33333%; }
  .col-sm-pull-11 {
    right: 91.66667%; }
  .col-sm-pull-12 {
    right: 100%; }
  .col-sm-push-0 {
    left: auto; }
  .col-sm-push-1 {
    left: 8.33333%; }
  .col-sm-push-2 {
    left: 16.66667%; }
  .col-sm-push-3 {
    left: 25%; }
  .col-sm-push-4 {
    left: 33.33333%; }
  .col-sm-push-5 {
    left: 41.66667%; }
  .col-sm-push-6 {
    left: 50%; }
  .col-sm-push-7 {
    left: 58.33333%; }
  .col-sm-push-8 {
    left: 66.66667%; }
  .col-sm-push-9 {
    left: 75%; }
  .col-sm-push-10 {
    left: 83.33333%; }
  .col-sm-push-11 {
    left: 91.66667%; }
  .col-sm-push-12 {
    left: 100%; }
  .col-sm-offset-0 {
    margin-left: 0%; }
  .col-sm-offset-1 {
    margin-left: 8.33333%; }
  .col-sm-offset-2 {
    margin-left: 16.66667%; }
  .col-sm-offset-3 {
    margin-left: 25%; }
  .col-sm-offset-4 {
    margin-left: 33.33333%; }
  .col-sm-offset-5 {
    margin-left: 41.66667%; }
  .col-sm-offset-6 {
    margin-left: 50%; }
  .col-sm-offset-7 {
    margin-left: 58.33333%; }
  .col-sm-offset-8 {
    margin-left: 66.66667%; }
  .col-sm-offset-9 {
    margin-left: 75%; }
  .col-sm-offset-10 {
    margin-left: 83.33333%; }
  .col-sm-offset-11 {
    margin-left: 91.66667%; }
  .col-sm-offset-12 {
    margin-left: 100%; } }

@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left; }
  .col-md-1 {
    width: 8.33333%; }
  .col-md-2 {
    width: 16.66667%; }
  .col-md-3 {
    width: 25%; }
  .col-md-4 {
    width: 33.33333%; }
  .col-md-5 {
    width: 41.66667%; }
  .col-md-6 {
    width: 50%; }
  .col-md-7 {
    width: 58.33333%; }
  .col-md-8 {
    width: 66.66667%; }
  .col-md-9 {
    width: 75%; }
  .col-md-10 {
    width: 83.33333%; }
  .col-md-11 {
    width: 91.66667%; }
  .col-md-12 {
    width: 100%; }
  .col-md-pull-0 {
    right: auto; }
  .col-md-pull-1 {
    right: 8.33333%; }
  .col-md-pull-2 {
    right: 16.66667%; }
  .col-md-pull-3 {
    right: 25%; }
  .col-md-pull-4 {
    right: 33.33333%; }
  .col-md-pull-5 {
    right: 41.66667%; }
  .col-md-pull-6 {
    right: 50%; }
  .col-md-pull-7 {
    right: 58.33333%; }
  .col-md-pull-8 {
    right: 66.66667%; }
  .col-md-pull-9 {
    right: 75%; }
  .col-md-pull-10 {
    right: 83.33333%; }
  .col-md-pull-11 {
    right: 91.66667%; }
  .col-md-pull-12 {
    right: 100%; }
  .col-md-push-0 {
    left: auto; }
  .col-md-push-1 {
    left: 8.33333%; }
  .col-md-push-2 {
    left: 16.66667%; }
  .col-md-push-3 {
    left: 25%; }
  .col-md-push-4 {
    left: 33.33333%; }
  .col-md-push-5 {
    left: 41.66667%; }
  .col-md-push-6 {
    left: 50%; }
  .col-md-push-7 {
    left: 58.33333%; }
  .col-md-push-8 {
    left: 66.66667%; }
  .col-md-push-9 {
    left: 75%; }
  .col-md-push-10 {
    left: 83.33333%; }
  .col-md-push-11 {
    left: 91.66667%; }
  .col-md-push-12 {
    left: 100%; }
  .col-md-offset-0 {
    margin-left: 0%; }
  .col-md-offset-1 {
    margin-left: 8.33333%; }
  .col-md-offset-2 {
    margin-left: 16.66667%; }
  .col-md-offset-3 {
    margin-left: 25%; }
  .col-md-offset-4 {
    margin-left: 33.33333%; }
  .col-md-offset-5 {
    margin-left: 41.66667%; }
  .col-md-offset-6 {
    margin-left: 50%; }
  .col-md-offset-7 {
    margin-left: 58.33333%; }
  .col-md-offset-8 {
    margin-left: 66.66667%; }
  .col-md-offset-9 {
    margin-left: 75%; }
  .col-md-offset-10 {
    margin-left: 83.33333%; }
  .col-md-offset-11 {
    margin-left: 91.66667%; }
  .col-md-offset-12 {
    margin-left: 100%; } }

@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left; }
  .col-lg-1 {
    width: 8.33333%; }
  .col-lg-2 {
    width: 16.66667%; }
  .col-lg-3 {
    width: 25%; }
  .col-lg-4 {
    width: 33.33333%; }
  .col-lg-5 {
    width: 41.66667%; }
  .col-lg-6 {
    width: 50%; }
  .col-lg-7 {
    width: 58.33333%; }
  .col-lg-8 {
    width: 66.66667%; }
  .col-lg-9 {
    width: 75%; }
  .col-lg-10 {
    width: 83.33333%; }
  .col-lg-11 {
    width: 91.66667%; }
  .col-lg-12 {
    width: 100%; }
  .col-lg-pull-0 {
    right: auto; }
  .col-lg-pull-1 {
    right: 8.33333%; }
  .col-lg-pull-2 {
    right: 16.66667%; }
  .col-lg-pull-3 {
    right: 25%; }
  .col-lg-pull-4 {
    right: 33.33333%; }
  .col-lg-pull-5 {
    right: 41.66667%; }
  .col-lg-pull-6 {
    right: 50%; }
  .col-lg-pull-7 {
    right: 58.33333%; }
  .col-lg-pull-8 {
    right: 66.66667%; }
  .col-lg-pull-9 {
    right: 75%; }
  .col-lg-pull-10 {
    right: 83.33333%; }
  .col-lg-pull-11 {
    right: 91.66667%; }
  .col-lg-pull-12 {
    right: 100%; }
  .col-lg-push-0 {
    left: auto; }
  .col-lg-push-1 {
    left: 8.33333%; }
  .col-lg-push-2 {
    left: 16.66667%; }
  .col-lg-push-3 {
    left: 25%; }
  .col-lg-push-4 {
    left: 33.33333%; }
  .col-lg-push-5 {
    left: 41.66667%; }
  .col-lg-push-6 {
    left: 50%; }
  .col-lg-push-7 {
    left: 58.33333%; }
  .col-lg-push-8 {
    left: 66.66667%; }
  .col-lg-push-9 {
    left: 75%; }
  .col-lg-push-10 {
    left: 83.33333%; }
  .col-lg-push-11 {
    left: 91.66667%; }
  .col-lg-push-12 {
    left: 100%; }
  .col-lg-offset-0 {
    margin-left: 0%; }
  .col-lg-offset-1 {
    margin-left: 8.33333%; }
  .col-lg-offset-2 {
    margin-left: 16.66667%; }
  .col-lg-offset-3 {
    margin-left: 25%; }
  .col-lg-offset-4 {
    margin-left: 33.33333%; }
  .col-lg-offset-5 {
    margin-left: 41.66667%; }
  .col-lg-offset-6 {
    margin-left: 50%; }
  .col-lg-offset-7 {
    margin-left: 58.33333%; }
  .col-lg-offset-8 {
    margin-left: 66.66667%; }
  .col-lg-offset-9 {
    margin-left: 75%; }
  .col-lg-offset-10 {
    margin-left: 83.33333%; }
  .col-lg-offset-11 {
    margin-left: 91.66667%; }
  .col-lg-offset-12 {
    margin-left: 100%; } }

table { background-color: transparent; }
caption { padding-top: 8px; padding-bottom: 8px; color: #777777; text-align: left; }
th { text-align: left; }
.table { width: 100%; max-width: 100%; margin-bottom: 20px; }
  .table > thead > tr > th,
  .table > thead > tr > td,
  .table > tbody > tr > th,
  .table > tbody > tr > td,
  .table > tfoot > tr > th,
  .table > tfoot > tr > td { padding: 8px; line-height: 1.42857; vertical-align: top; border-top: 1px solid #ddd; }
  .table > thead > tr > th { vertical-align: bottom; border-bottom: 2px solid #ddd; }
  .table > caption + thead > tr:first-child > th,
  .table > caption + thead > tr:first-child > td,
  .table > colgroup + thead > tr:first-child > th,
  .table > colgroup + thead > tr:first-child > td,
  .table > thead:first-child > tr:first-child > th,
  .table > thead:first-child > tr:first-child > td { border-top: 0; }
  .table > tbody + tbody { border-top: 2px solid #ddd; }
  .table .table { background-color: #fff; }

.table-condensed > thead > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > th,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > th,
.table-condensed > tfoot > tr > td { padding: 5px; }

.table-bordered { border: 1px solid #ddd; }
  .table-bordered > thead > tr > th,
  .table-bordered > thead > tr > td,
  .table-bordered > tbody > tr > th,
  .table-bordered > tbody > tr > td,
  .table-bordered > tfoot > tr > th,
  .table-bordered > tfoot > tr > td { border: 1px solid #ddd; }
  .table-bordered > thead > tr > th,
  .table-bordered > thead > tr > td {  border-bottom-width: 2px; }

.table-striped > tbody > tr:nth-of-type(odd) { background-color: #f9f9f9; }
.table-hover > tbody > tr:hover { background-color: #f5f5f5; }
table col[class*="col-"] { position: static; float: none; display: table-column; }
table td[class*="col-"],
table th[class*="col-"] { position: static; float: none; display: table-cell; }
.table > thead > tr > td.active,
.table > thead > tr > th.active,
.table > thead > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr > td.active,
.table > tbody > tr > th.active,
.table > tbody > tr.active > td,
.table > tbody > tr.active > th,
.table > tfoot > tr > td.active,
.table > tfoot > tr > th.active,
.table > tfoot > tr.active > td,
.table > tfoot > tr.active > th { background-color: #f5f5f5; }
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th { background-color: #e8e8e8; }

.table > thead > tr > td.success,
.table > thead > tr > th.success,
.table > thead > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr > td.success,
.table > tbody > tr > th.success,
.table > tbody > tr.success > td,
.table > tbody > tr.success > th,
.table > tfoot > tr > td.success,
.table > tfoot > tr > th.success,
.table > tfoot > tr.success > td,
.table > tfoot > tr.success > th { background-color: #dff0d8; }

.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th { background-color: #d0e9c6; }

.table > thead > tr > td.info,
.table > thead > tr > th.info,
.table > thead > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr > td.info,
.table > tbody > tr > th.info,
.table > tbody > tr.info > td,
.table > tbody > tr.info > th,
.table > tfoot > tr > td.info,
.table > tfoot > tr > th.info,
.table > tfoot > tr.info > td,
.table > tfoot > tr.info > th { background-color: #d9edf7; }

.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th { background-color: #c4e3f3; }

.table > thead > tr > td.warning,
.table > thead > tr > th.warning,
.table > thead > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr > td.warning,
.table > tbody > tr > th.warning,
.table > tbody > tr.warning > td,
.table > tbody > tr.warning > th,
.table > tfoot > tr > td.warning,
.table > tfoot > tr > th.warning,
.table > tfoot > tr.warning > td,
.table > tfoot > tr.warning > th { background-color: #fcf8e3; }

.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th { background-color: #faf2cc; }

.table > thead > tr > td.danger,
.table > thead > tr > th.danger,
.table > thead > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr > td.danger,
.table > tbody > tr > th.danger,
.table > tbody > tr.danger > td,
.table > tbody > tr.danger > th,
.table > tfoot > tr > td.danger,
.table > tfoot > tr > th.danger,
.table > tfoot > tr.danger > td,
.table > tfoot > tr.danger > th { background-color: #f2dede; }

.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th { background-color: #ebcccc; }

.table-responsive { overflow-x: auto; min-height: 0.01%; }

  @media screen and (max-width: 767px) {
    .table-responsive { width: 100%; margin-bottom: 15px; overflow-y: hidden; -ms-overflow-style: -ms-autohiding-scrollbar; border: 1px solid #ddd; }
      .table-responsive > .table { margin-bottom: 0; }
        .table-responsive > .table > thead > tr > th,
        .table-responsive > .table > thead > tr > td,
        .table-responsive > .table > tbody > tr > th,
        .table-responsive > .table > tbody > tr > td,
        .table-responsive > .table > tfoot > tr > th,
        .table-responsive > .table > tfoot > tr > td { white-space: nowrap; }
      .table-responsive > .table-bordered { border: 0; }
        .table-responsive > .table-bordered > thead > tr > th:first-child,
        .table-responsive > .table-bordered > thead > tr > td:first-child,
        .table-responsive > .table-bordered > tbody > tr > th:first-child,
        .table-responsive > .table-bordered > tbody > tr > td:first-child,
        .table-responsive > .table-bordered > tfoot > tr > th:first-child,
        .table-responsive > .table-bordered > tfoot > tr > td:first-child {
          border-left: 0; }
        .table-responsive > .table-bordered > thead > tr > th:last-child,
        .table-responsive > .table-bordered > thead > tr > td:last-child,
        .table-responsive > .table-bordered > tbody > tr > th:last-child,
        .table-responsive > .table-bordered > tbody > tr > td:last-child,
        .table-responsive > .table-bordered > tfoot > tr > th:last-child,
        .table-responsive > .table-bordered > tfoot > tr > td:last-child {
          border-right: 0; }
        .table-responsive > .table-bordered > tbody > tr:last-child > th,
        .table-responsive > .table-bordered > tbody > tr:last-child > td,
        .table-responsive > .table-bordered > tfoot > tr:last-child > th,
        .table-responsive > .table-bordered > tfoot > tr:last-child > td {
          border-bottom: 0; } }

fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0; }

legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 20px;
  font-size: 21px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5; }

label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold; }

input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box; }

input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal; }

input[type="file"] {
  display: block; }

input[type="range"] {
  display: block;
  width: 100%; }

select[multiple],
select[size] {
  height: auto; }

input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px; }

output {
  display: block;
  padding-top: 7px;
  font-size: 14px;
  line-height: 1.42857;
  color: #555555; }



.form-control {
  display: block; width: 100%; height: 34px; padding: 6px 12px; font-size: 14px; line-height: 1.42857; color: #555555; background-color: #fff;
  background-image: none; border: 1px solid #ccc; border-radius: 4px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s; -o-transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;
  transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s; }
  
  
  .form-control:focus {
    border-color: #66afe9;
    outline: 0;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px rgba(102, 175, 233, 0.6);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px rgba(102, 175, 233, 0.6); }
  .form-control::-moz-placeholder {
    color: #999;
    opacity: 1; }
  .form-control:-ms-input-placeholder {
    color: #999; }
  .form-control::-webkit-input-placeholder {
    color: #999; }
  .form-control::-ms-expand {
    border: 0;
    background-color: transparent; }
  .form-control[disabled], .form-control[readonly],
  fieldset[disabled] .form-control {
    background-color: #eeeeee;
    opacity: 1; }
  .form-control[disabled],
  fieldset[disabled] .form-control {
    cursor: not-allowed; }

textarea.form-control {
  height: auto; }

input[type="search"] {
  -webkit-appearance: none; }

@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 34px; }
  input[type="date"].input-sm, .input-group-sm > input[type="date"].form-control,
  .input-group-sm > input[type="date"].input-group-addon,
  .input-group-sm > .input-group-btn > input[type="date"].btn,
  .input-group-sm input[type="date"],
  input[type="time"].input-sm,
  .input-group-sm > input[type="time"].form-control,
  .input-group-sm > input[type="time"].input-group-addon,
  .input-group-sm > .input-group-btn > input[type="time"].btn,
  .input-group-sm
  input[type="time"],
  input[type="datetime-local"].input-sm,
  .input-group-sm > input[type="datetime-local"].form-control,
  .input-group-sm > input[type="datetime-local"].input-group-addon,
  .input-group-sm > .input-group-btn > input[type="datetime-local"].btn,
  .input-group-sm
  input[type="datetime-local"],
  input[type="month"].input-sm,
  .input-group-sm > input[type="month"].form-control,
  .input-group-sm > input[type="month"].input-group-addon,
  .input-group-sm > .input-group-btn > input[type="month"].btn,
  .input-group-sm
  input[type="month"] {
    line-height: 30px; }
  input[type="date"].input-lg, .input-group-lg > input[type="date"].form-control,
  .input-group-lg > input[type="date"].input-group-addon,
  .input-group-lg > .input-group-btn > input[type="date"].btn,
  .input-group-lg input[type="date"],
  input[type="time"].input-lg,
  .input-group-lg > input[type="time"].form-control,
  .input-group-lg > input[type="time"].input-group-addon,
  .input-group-lg > .input-group-btn > input[type="time"].btn,
  .input-group-lg
  input[type="time"],
  input[type="datetime-local"].input-lg,
  .input-group-lg > input[type="datetime-local"].form-control,
  .input-group-lg > input[type="datetime-local"].input-group-addon,
  .input-group-lg > .input-group-btn > input[type="datetime-local"].btn,
  .input-group-lg
  input[type="datetime-local"],
  input[type="month"].input-lg,
  .input-group-lg > input[type="month"].form-control,
  .input-group-lg > input[type="month"].input-group-addon,
  .input-group-lg > .input-group-btn > input[type="month"].btn,
  .input-group-lg
  input[type="month"] {
    line-height: 46px; } }

.form-group {
  margin-bottom: 15px; }

.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px; }
  .radio label,
  .checkbox label {
    min-height: 20px;
    padding-left: 20px;
    margin-bottom: 0;
    font-weight: normal;
    cursor: pointer; }

.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9; }

.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px; }

.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer; }

.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px; }


desabilitado { background-color: blue; }
select[disabled] { 
    display: block;
    width: 100%;
    height: 34px;
    padding: 6px 12px;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555;
    background-color: #cdcdcd;
    border: 1px solid #ccc;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    -webkit-transition: border-color ease-in-out .15s, -webkit-box-shadow ease-in-out .15s;
    -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}

input[type="radio"][disabled], input[type="radio"].disabled,
fieldset[disabled] input[type="radio"],
input[type="checkbox"][disabled],
input[type="checkbox"].disabled,
fieldset[disabled]
input[type="checkbox"] {
  cursor: not-allowed; }

.radio-inline.disabled,
fieldset[disabled] .radio-inline,
.checkbox-inline.disabled,
fieldset[disabled]
.checkbox-inline {
  cursor: not-allowed; }

.radio.disabled label,
fieldset[disabled] .radio label,
.checkbox.disabled label,
fieldset[disabled]
.checkbox label {
  cursor: not-allowed; }

.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 34px; }
  .form-control-static.input-lg, .input-group-lg > .form-control-static.form-control,
  .input-group-lg > .form-control-static.input-group-addon,
  .input-group-lg > .input-group-btn > .form-control-static.btn, .form-control-static.input-sm, .input-group-sm > .form-control-static.form-control,
  .input-group-sm > .form-control-static.input-group-addon,
  .input-group-sm > .input-group-btn > .form-control-static.btn {
    padding-left: 0;
    padding-right: 0; }

.input-sm, .input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 3px; }

select.input-sm, .input-group-sm > select.form-control,
.input-group-sm > select.input-group-addon,
.input-group-sm > .input-group-btn > select.btn {
  height: 30px;
  line-height: 30px; }

textarea.input-sm, .input-group-sm > textarea.form-control,
.input-group-sm > textarea.input-group-addon,
.input-group-sm > .input-group-btn > textarea.btn,
select[multiple].input-sm,
.input-group-sm > select[multiple].form-control,
.input-group-sm > select[multiple].input-group-addon,
.input-group-sm > .input-group-btn > select[multiple].btn {
  height: auto; }

.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 3px; }

.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px; }

.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto; }

.form-group-sm .form-control-static {
  height: 30px;
  min-height: 32px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5; }

.input-lg, .input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 46px;
  padding: 10px 16px;
  font-size: 18px;
  line-height: 1.33333;
  border-radius: 6px; }

select.input-lg, .input-group-lg > select.form-control,
.input-group-lg > select.input-group-addon,
.input-group-lg > .input-group-btn > select.btn {
  height: 46px;
  line-height: 46px; }

textarea.input-lg, .input-group-lg > textarea.form-control,
.input-group-lg > textarea.input-group-addon,
.input-group-lg > .input-group-btn > textarea.btn,
select[multiple].input-lg,
.input-group-lg > select[multiple].form-control,
.input-group-lg > select[multiple].input-group-addon,
.input-group-lg > .input-group-btn > select[multiple].btn {
  height: auto; }

.form-group-lg .form-control {
  height: 46px;
  padding: 10px 16px;
  font-size: 18px;
  line-height: 1.33333;
  border-radius: 6px; }

.form-group-lg select.form-control {
  height: 46px;
  line-height: 46px; }

.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto; }

.form-group-lg .form-control-static {
  height: 46px;
  min-height: 38px;
  padding: 11px 16px;
  font-size: 18px;
  line-height: 1.33333; }

.has-feedback {
  position: relative; }
  .has-feedback .form-control {
    padding-right: 42.5px; }

.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 34px;
  height: 34px;
  line-height: 34px;
  text-align: center;
  pointer-events: none; }

.input-lg + .form-control-feedback, .input-group-lg > .form-control + .form-control-feedback,
.input-group-lg > .input-group-addon + .form-control-feedback,
.input-group-lg > .input-group-btn > .btn + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 46px;
  height: 46px;
  line-height: 46px; }

.input-sm + .form-control-feedback, .input-group-sm > .form-control + .form-control-feedback,
.input-group-sm > .input-group-addon + .form-control-feedback,
.input-group-sm > .input-group-btn > .btn + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px; }

.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d; }

.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); }
  .has-success .form-control:focus {
    border-color: #2b542c;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168; }

.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8; }

.has-success .form-control-feedback {
  color: #3c763d; }

.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b; }

.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); }
  .has-warning .form-control:focus {
    border-color: #66512c;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b; }

.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3; }

.has-warning .form-control-feedback {
  color: #8a6d3b; }

.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442; }

.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); }
  .has-error .form-control:focus {
    border-color: #843534;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483; }

.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede; }

.has-error .form-control-feedback {
  color: #a94442; }

.has-feedback label ~ .form-control-feedback {
  top: 25px; }

.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0; }

.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #737373; }

@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle; }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle; }
  .form-inline .form-control-static {
    display: inline-block; }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle; }
    .form-inline .input-group .input-group-addon,
    .form-inline .input-group .input-group-btn,
    .form-inline .input-group .form-control {
      width: auto; }
  .form-inline .input-group > .form-control {
    width: 100%; }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle; }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle; }
    .form-inline .radio label,
    .form-inline .checkbox label {
      padding-left: 0; }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0; }
  .form-inline .has-feedback .form-control-feedback {
    top: 0; } }

.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px; }

.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 27px; }

.form-horizontal .form-group {
  margin-left: -15px;
  margin-right: -15px; }
  .form-horizontal .form-group:before, .form-horizontal .form-group:after {
    content: " ";
    display: table; }
  .form-horizontal .form-group:after {
    clear: both; }

@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px; } }

.form-horizontal .has-feedback .form-control-feedback {
  right: 15px; }

@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 18px; } }

@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px; } }

.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 14px;
  line-height: 1.42857;
  border-radius: 4px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none; }
  .btn:focus, .btn.focus, .btn:active:focus, .btn:active.focus, .btn.active:focus, .btn.active.focus {
    outline: thin dotted;
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px; }
  .btn:hover, .btn:focus, .btn.focus {
    color: #333;
    text-decoration: none; }
  .btn:active, .btn.active {
    outline: 0;
    background-image: none;
    -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
    box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); }
  .btn.disabled, .btn[disabled],
  fieldset[disabled] .btn {
    cursor: not-allowed;
    opacity: 0.65;
    filter: alpha(opacity=65);
    -webkit-box-shadow: none;
    box-shadow: none; }

a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none; }


.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc; }
  .btn-default:focus, .btn-default.focus {
    color: #333;
    background-color: #e6e6e6;
    border-color: #8c8c8c; }
  .btn-default:hover {
    color: #333;
    background-color: #e6e6e6;
    border-color: #adadad; }
  .btn-default:active, .btn-default.active,
  .open > .btn-default.dropdown-toggle {
    color: #333;
    background-color: #e6e6e6;
    border-color: #adadad; }
    .btn-default:active:hover, .btn-default:active:focus, .btn-default:active.focus, .btn-default.active:hover, .btn-default.active:focus, .btn-default.active.focus,
    .open > .btn-default.dropdown-toggle:hover,
    .open > .btn-default.dropdown-toggle:focus,
    .open > .btn-default.dropdown-toggle.focus {
      color: #333;
      background-color: #d4d4d4;
      border-color: #8c8c8c; }
  .btn-default:active, .btn-default.active,
  .open > .btn-default.dropdown-toggle {
    background-image: none; }
  .btn-default.disabled:hover, .btn-default.disabled:focus, .btn-default.disabled.focus, .btn-default[disabled]:hover, .btn-default[disabled]:focus, .btn-default[disabled].focus,
  fieldset[disabled] .btn-default:hover,
  fieldset[disabled] .btn-default:focus,
  fieldset[disabled] .btn-default.focus {
    background-color: #fff;
    border-color: #ccc; }
  .btn-default .badge {
    color: #fff;
    background-color: #333; }

.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4; }
  .btn-primary:focus, .btn-primary.focus {
    color: #fff;
    background-color: #286090;
    border-color: #122b40; }
  .btn-primary:hover {
    color: #fff;
    background-color: #286090;
    border-color: #204d74; }
  .btn-primary:active, .btn-primary.active,
  .open > .btn-primary.dropdown-toggle {
    color: #fff;
    background-color: #286090;
    border-color: #204d74; }
    .btn-primary:active:hover, .btn-primary:active:focus, .btn-primary:active.focus, .btn-primary.active:hover, .btn-primary.active:focus, .btn-primary.active.focus,
    .open > .btn-primary.dropdown-toggle:hover,
    .open > .btn-primary.dropdown-toggle:focus,
    .open > .btn-primary.dropdown-toggle.focus {
      color: #fff;
      background-color: #204d74;
      border-color: #122b40; }
  .btn-primary:active, .btn-primary.active,
  .open > .btn-primary.dropdown-toggle {
    background-image: none; }
  .btn-primary.disabled:hover, .btn-primary.disabled:focus, .btn-primary.disabled.focus, .btn-primary[disabled]:hover, .btn-primary[disabled]:focus, .btn-primary[disabled].focus,
  fieldset[disabled] .btn-primary:hover,
  fieldset[disabled] .btn-primary:focus,
  fieldset[disabled] .btn-primary.focus {
    background-color: #337ab7;
    border-color: #2e6da4; }
  .btn-primary .badge {
    color: #337ab7;
    background-color: #fff; }

.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c; }
  .btn-success:focus, .btn-success.focus {
    color: #fff;
    background-color: #449d44;
    border-color: #255625; }
  .btn-success:hover {
    color: #fff;
    background-color: #449d44;
    border-color: #398439; }
  .btn-success:active, .btn-success.active,
  .open > .btn-success.dropdown-toggle {
    color: #fff;
    background-color: #449d44;
    border-color: #398439; }
    .btn-success:active:hover, .btn-success:active:focus, .btn-success:active.focus, .btn-success.active:hover, .btn-success.active:focus, .btn-success.active.focus,
    .open > .btn-success.dropdown-toggle:hover,
    .open > .btn-success.dropdown-toggle:focus,
    .open > .btn-success.dropdown-toggle.focus {
      color: #fff;
      background-color: #398439;
      border-color: #255625; }
  .btn-success:active, .btn-success.active,
  .open > .btn-success.dropdown-toggle {
    background-image: none; }
  .btn-success.disabled:hover, .btn-success.disabled:focus, .btn-success.disabled.focus, .btn-success[disabled]:hover, .btn-success[disabled]:focus, .btn-success[disabled].focus,
  fieldset[disabled] .btn-success:hover,
  fieldset[disabled] .btn-success:focus,
  fieldset[disabled] .btn-success.focus {
    background-color: #5cb85c;
    border-color: #4cae4c; }
  .btn-success .badge {
    color: #5cb85c;
    background-color: #fff; }

.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da; }
  .btn-info:focus, .btn-info.focus {
    color: #fff;
    background-color: #31b0d5;
    border-color: #1b6d85; }
  .btn-info:hover {
    color: #fff;
    background-color: #31b0d5;
    border-color: #269abc; }
  .btn-info:active, .btn-info.active,
  .open > .btn-info.dropdown-toggle {
    color: #fff;
    background-color: #31b0d5;
    border-color: #269abc; }
    .btn-info:active:hover, .btn-info:active:focus, .btn-info:active.focus, .btn-info.active:hover, .btn-info.active:focus, .btn-info.active.focus,
    .open > .btn-info.dropdown-toggle:hover,
    .open > .btn-info.dropdown-toggle:focus,
    .open > .btn-info.dropdown-toggle.focus {
      color: #fff;
      background-color: #269abc;
      border-color: #1b6d85; }
  .btn-info:active, .btn-info.active,
  .open > .btn-info.dropdown-toggle {
    background-image: none; }
  .btn-info.disabled:hover, .btn-info.disabled:focus, .btn-info.disabled.focus, .btn-info[disabled]:hover, .btn-info[disabled]:focus, .btn-info[disabled].focus,
  fieldset[disabled] .btn-info:hover,
  fieldset[disabled] .btn-info:focus,
  fieldset[disabled] .btn-info.focus {
    background-color: #5bc0de;
    border-color: #46b8da; }
  .btn-info .badge {
    color: #5bc0de;
    background-color: #fff; }

.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236; }
  .btn-warning:focus, .btn-warning.focus {
    color: #fff;
    background-color: #ec971f;
    border-color: #985f0d; }
  .btn-warning:hover {
    color: #fff;
    background-color: #ec971f;
    border-color: #d58512; }
  .btn-warning:active, .btn-warning.active,
  .open > .btn-warning.dropdown-toggle {
    color: #fff;
    background-color: #ec971f;
    border-color: #d58512; }
    .btn-warning:active:hover, .btn-warning:active:focus, .btn-warning:active.focus, .btn-warning.active:hover, .btn-warning.active:focus, .btn-warning.active.focus,
    .open > .btn-warning.dropdown-toggle:hover,
    .open > .btn-warning.dropdown-toggle:focus,
    .open > .btn-warning.dropdown-toggle.focus {
      color: #fff;
      background-color: #d58512;
      border-color: #985f0d; }
  .btn-warning:active, .btn-warning.active,
  .open > .btn-warning.dropdown-toggle {
    background-image: none; }
  .btn-warning.disabled:hover, .btn-warning.disabled:focus, .btn-warning.disabled.focus, .btn-warning[disabled]:hover, .btn-warning[disabled]:focus, .btn-warning[disabled].focus,
  fieldset[disabled] .btn-warning:hover,
  fieldset[disabled] .btn-warning:focus,
  fieldset[disabled] .btn-warning.focus {
    background-color: #f0ad4e;
    border-color: #eea236; }
  .btn-warning .badge {
    color: #f0ad4e;
    background-color: #fff; }

.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a; }
  .btn-danger:focus, .btn-danger.focus {
    color: #fff;
    background-color: #c9302c;
    border-color: #761c19; }
  .btn-danger:hover {
    color: #fff;
    background-color: #c9302c;
    border-color: #ac2925; }
  .btn-danger:active, .btn-danger.active,
  .open > .btn-danger.dropdown-toggle {
    color: #fff;
    background-color: #c9302c;
    border-color: #ac2925; }
    .btn-danger:active:hover, .btn-danger:active:focus, .btn-danger:active.focus, .btn-danger.active:hover, .btn-danger.active:focus, .btn-danger.active.focus,
    .open > .btn-danger.dropdown-toggle:hover,
    .open > .btn-danger.dropdown-toggle:focus,
    .open > .btn-danger.dropdown-toggle.focus {
      color: #fff;
      background-color: #ac2925;
      border-color: #761c19; }
  .btn-danger:active, .btn-danger.active,
  .open > .btn-danger.dropdown-toggle {
    background-image: none; }
  .btn-danger.disabled:hover, .btn-danger.disabled:focus, .btn-danger.disabled.focus, .btn-danger[disabled]:hover, .btn-danger[disabled]:focus, .btn-danger[disabled].focus,
  fieldset[disabled] .btn-danger:hover,
  fieldset[disabled] .btn-danger:focus,
  fieldset[disabled] .btn-danger.focus {
    background-color: #d9534f;
    border-color: #d43f3a; }
  .btn-danger .badge {
    color: #d9534f;
    background-color: #fff; }

.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0; }
  .btn-link, .btn-link:active, .btn-link.active, .btn-link[disabled],
  fieldset[disabled] .btn-link {
    background-color: transparent;
    -webkit-box-shadow: none;
    box-shadow: none; }
  .btn-link, .btn-link:hover, .btn-link:focus, .btn-link:active {
    border-color: transparent; }
  .btn-link:hover, .btn-link:focus {
    color: #23527c;
    text-decoration: underline;
    background-color: transparent; }
  .btn-link[disabled]:hover, .btn-link[disabled]:focus,
  fieldset[disabled] .btn-link:hover,
  fieldset[disabled] .btn-link:focus {
    color: #777777;
    text-decoration: none; }

.btn-lg, .btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 18px;
  line-height: 1.33333;
  border-radius: 6px; }

.btn-sm, .btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 3px; }

.btn-xs, .btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 3px; }

.btn-block {
  display: block;
  width: 100%; }

.btn-block + .btn-block {
  margin-top: 5px; }

input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%; }

.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear; }
  .fade.in {
    opacity: 1; }

.collapse {
  display: none; }
  .collapse.in {
    display: block; }

tr.collapse.in {
  display: table-row; }

tbody.collapse.in {
  display: table-row-group; }

.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease; }

.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent; }

.dropup,
.dropdown {
  position: relative; }

.dropdown-toggle:focus {
  outline: 0; }

.zarpe_dropdown-menu {
  min-width: 340px!important; 
  background-color: rgba(0, 0, 0, 0.0)!important;
  border: 0px solid rgba(0, 0, 0, 0.0)!important;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.0)!important;
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.0)!important; }

.zarpe_dropdown-menu2 {
  min-width: 100%!important; text-align:center!important;
  background-color: rgba(0, 0, 0, 0.0)!important;
  border: 0px solid rgba(0, 0, 0, 0.0)!important;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.0)!important;
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.0)!important; }
   
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 270px;
  padding: 5px 10px!important;
  margin: 2px 0 0;
  list-style: none;
  font-size: 14px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 4px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box; }
  
  .dropdown-menu.pull-right {
    right: 0;
    left: auto; }
  .dropdown-menu .divider {
    height: 1px;
    margin: 9px 0;
    overflow: hidden;
    background-color: #e5e5e5; }
  .dropdown-menu > li > a {
    display: block;
    padding: 6px 16px!important;
    clear: both;
    font-weight: normal;
    line-height: 1.42857;
    color: #333333;
    white-space: nowrap; }

.dropdown-menu > li > a:hover, .dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5; }

.dropdown-menu > .active > a, .dropdown-menu > .active > a:hover, .dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7; }

.dropdown-menu > .disabled > a, .dropdown-menu > .disabled > a:hover, .dropdown-menu > .disabled > a:focus {
  color: #777777; }

.dropdown-menu > .disabled > a:hover, .dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed; }

.open > .dropdown-menu {
  display: block; }

.open > a {
  outline: 0; }

.dropdown-menu-right {
  left: auto;
  right: 0; }

.dropdown-menu-left {
  left: 0;
  right: auto; }

.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857;
  color: #777777;
  white-space: nowrap; }

.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990; }

.pull-right > .dropdown-menu {
  right: 0;
  left: auto; }

.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: ""; }

.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px; }

.menu_carrito_texto1 { font-size:17px; }


@media (min-width:1900px) {
.menu_carrito_texto1 { font-size:22px; color:#ffffff;}

}
   
   
@media (min-width: 768px) { 
.menu_carrito { right: -100% !important; left: auto; }
.menu_carrito_texto1 { font-size:17px; color:#ffffff;}
.navbar-right .dropdown-menu-left { left: 0; right: auto; } 
    
}


.caja_texto_blanco {
border:0px solid #ffffff!important;padding:12px;font-size: 16px;background:rgba(0, 0, 0, 0.0); width:95%; }
.caja_texto_blanco:focus { border:0px solid #ffffff!important; }



.btn-ganolife2  { width : 70%;}
.btn-success, .btn-primary { color: #fff; font-size:17px !important; font-weight:500!important; }

.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle; }
  .btn-group > .btn,
  .btn-group-vertical > .btn {
    position: relative;
    float: left; }
    .btn-group > .btn:hover, .btn-group > .btn:focus, .btn-group > .btn:active, .btn-group > .btn.active,
    .btn-group-vertical > .btn:hover,
    .btn-group-vertical > .btn:focus,
    .btn-group-vertical > .btn:active,
    .btn-group-vertical > .btn.active {
      z-index: 2; }

.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px; }

.btn-toolbar {
  margin-left: -5px; }
  .btn-toolbar:before, .btn-toolbar:after {
    content: " ";
    display: table; }
  .btn-toolbar:after {
    clear: both; }
  .btn-toolbar .btn,
  .btn-toolbar .btn-group,
  .btn-toolbar .input-group {
    float: left; }
  .btn-toolbar > .btn,
  .btn-toolbar > .btn-group,
  .btn-toolbar > .input-group {
    margin-left: 5px; }

.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0; }

.btn-group > .btn:first-child {
  margin-left: 0; }
  .btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
    border-bottom-right-radius: 0;
    border-top-right-radius: 0; }

.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0; }

.btn-group > .btn-group {
  float: left; }

.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0; }

.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0; }

.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0; }

.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0; }

.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px; }

.btn-group > .btn-lg + .dropdown-toggle, .btn-group-lg.btn-group > .btn + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px; }

.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); }
  .btn-group.open .dropdown-toggle.btn-link {
    -webkit-box-shadow: none;
    box-shadow: none; }

.btn .caret {
  margin-left: 0; }

.btn-lg .caret, .btn-group-lg > .btn .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0; }

.dropup .btn-lg .caret, .dropup .btn-group-lg > .btn .caret {
  border-width: 0 5px 5px; }

.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%; }

.btn-group-vertical > .btn-group:before, .btn-group-vertical > .btn-group:after {
  content: " ";
  display: table; }

.btn-group-vertical > .btn-group:after {
  clear: both; }

.btn-group-vertical > .btn-group > .btn {
  float: none; }

.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0; }

.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0; }

.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 4px;
  border-top-left-radius: 4px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0; }

.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 4px;
  border-bottom-left-radius: 4px; }

.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0; }

.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0; }

.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0; }

.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate; }
  .btn-group-justified > .btn,
  .btn-group-justified > .btn-group {
    float: none;
    display: table-cell;
    width: 1%; }
  .btn-group-justified > .btn-group .btn {
    width: 100%; }
  .btn-group-justified > .btn-group .dropdown-menu {
    left: auto; }

[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none; }

.input-group {
  position: relative;
  display: table;
  border-collapse: separate; }
  .input-group[class*="col-"] {
    float: none;
    padding-left: 0;
    padding-right: 0; }
  .input-group .form-control {
    position: relative;
    z-index: 2;
    float: left;
    width: 100%;
    margin-bottom: 0; }
    .input-group .form-control:focus {
      z-index: 3; }

.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell; }
  .input-group-addon:not(:first-child):not(:last-child),
  .input-group-btn:not(:first-child):not(:last-child),
  .input-group .form-control:not(:first-child):not(:last-child) {
    border-radius: 0; }

.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle; }

.input-group-addon {
  padding: 6px 12px;
  font-size: 14px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 4px; }
  .input-group-addon.input-sm,
  .input-group-sm > .input-group-addon,
  .input-group-sm > .input-group-btn > .input-group-addon.btn {
    padding: 5px 10px;
    font-size: 12px;
    border-radius: 3px; }
  .input-group-addon.input-lg,
  .input-group-lg > .input-group-addon,
  .input-group-lg > .input-group-btn > .input-group-addon.btn {
    padding: 10px 16px;
    font-size: 18px;
    border-radius: 6px; }
  .input-group-addon input[type="radio"],
  .input-group-addon input[type="checkbox"] {
    margin-top: 0; }

.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0; }

.input-group-addon:first-child {
  border-right: 0; }

.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0; }

.input-group-addon:last-child {
  border-left: 0; }

.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap; }
  .input-group-btn > .btn {
    position: relative; }
    .input-group-btn > .btn + .btn {
      margin-left: -1px; }
    .input-group-btn > .btn:hover, .input-group-btn > .btn:focus, .input-group-btn > .btn:active {
      z-index: 2; }
  .input-group-btn:first-child > .btn,
  .input-group-btn:first-child > .btn-group {
    margin-right: -1px; }
  .input-group-btn:last-child > .btn,
  .input-group-btn:last-child > .btn-group {
    z-index: 2;
    margin-left: -1px; }

.nav { margin-bottom: 0; padding-left: 0; list-style: none; }
.nav:before, .nav:after {  content: " "; display: table; }
.nav:after { clear: both; }
.nav > li { position: relative; display: block; }
.nav > li > a { position: relative; display: block; padding: 10px 10px; }
.nav > li > a:hover, .nav > li > a:focus { text-decoration: none; background-color: transparent!important; }
        
        
        
    .nav > li.disabled > a {
      color: #777777; }
      .nav > li.disabled > a:hover, .nav > li.disabled > a:focus {
        color: #777777;
        text-decoration: none;
        background-color: transparent;
        cursor: not-allowed; }
  .nav .open > a, .nav .open > a:hover, .nav .open > a:focus {
    background-color: #eeeeee;
    border-color: #337ab7; }
  .nav .nav-divider {
    height: 1px;
    margin: 9px 0;
    overflow: hidden;
    background-color: #e5e5e5; }
  .nav > li > a > img {
    max-width: none; }

.nav-tabs { border-bottom: 1px solid #bbbbbb!important; }
.nav-tabs .activo {background-color:#ffffff!important; border: 1px solid #bbb; border-bottom-color: transparent;}
.nav-tabs .activo a {color:#333333!important;}
.nav-tabs > li {float: left; margin-bottom: -1px; background-color: #ECEDEF; }
.nav-tabs > li > a { margin-right: 2px; line-height: 1.42857; border: 1px solid transparent; border-radius: 4px 4px 0 0; color:#888888!important;}
.nav-tabs > li > a:hover { }
    .nav-tabs > li.active > a, .nav-tabs > li.active > a:hover, .nav-tabs > li.active > a:focus {
      color: #555555;
      background-color: #fff;
      cursor: default; }

.nav-pills > li {
  float: left; }
  .nav-pills > li > a {
    border-radius: 4px; }
  .nav-pills > li + li {
    margin-left: 2px; }
  .nav-pills > li.active > a, .nav-pills > li.active > a:hover, .nav-pills > li.active > a:focus {
    color: #fff;
    background-color: #337ab7; }

.nav-stacked > li {
  float: none; }
  .nav-stacked > li + li {
    margin-top: 2px;
    margin-left: 0; }

.nav-justified, .nav-tabs.nav-justified {
  width: 100%; }
  .nav-justified > li, .nav-tabs.nav-justified > li {
    float: none; }
    .nav-justified > li > a, .nav-tabs.nav-justified > li > a {
      text-align: center;
      margin-bottom: 5px; }
  .nav-justified > .dropdown .dropdown-menu {
    top: auto;
    left: auto; }
  @media (min-width: 768px) {
    .nav-justified > li, .nav-tabs.nav-justified > li {
      display: table-cell;
      width: 1%; }
      .nav-justified > li > a, .nav-tabs.nav-justified > li > a {
        margin-bottom: 0; } }

.nav-tabs-justified, .nav-tabs.nav-justified {
  border-bottom: 0; }
  .nav-tabs-justified > li > a, .nav-tabs.nav-justified > li > a {
    margin-right: 0;
    border-radius: 4px; }
  .nav-tabs-justified > .active > a, .nav-tabs.nav-justified > .active > a,
  .nav-tabs-justified > .active > a:hover, .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus, .nav-tabs.nav-justified > .active > a:focus {
    border: 1px solid #ddd; }
  @media (min-width: 768px) {
    .nav-tabs-justified > li > a, .nav-tabs.nav-justified > li > a {
      border-bottom: 1px solid #ddd;
      border-radius: 4px 4px 0 0; }
    .nav-tabs-justified > .active > a, .nav-tabs.nav-justified > .active > a,
    .nav-tabs-justified > .active > a:hover, .nav-tabs.nav-justified > .active > a:hover,
    .nav-tabs-justified > .active > a:focus, .nav-tabs.nav-justified > .active > a:focus {
      border-bottom-color: #fff; } }

.tab-content > .tab-pane {
  display: none; }

.tab-content > .active {
  display: block; }

.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0; }

.navbar {
  position: relative;
  min-height: 50px;
  margin-bottom: 20px;
  border: 1px solid transparent; }
  .navbar:before, .navbar:after {
    content: " ";
    display: table; }
  .navbar:after {
    clear: both; }
  @media (min-width: 768px) {
    .navbar {
      border-radius: 4px; } }

.navbar-header:before, .navbar-header:after {
  content: " ";
  display: table; }

.navbar-header:after {
  clear: both; }

@media (min-width: 768px) {
  .navbar-header {
    float: left; } }

.navbar-collapse {
  overflow-x: visible;
  padding-right: 15px;
  padding-left: 15px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch; }
  .navbar-collapse:before, .navbar-collapse:after {
    content: " ";
    display: table; }
  .navbar-collapse:after {
    clear: both; }
  .navbar-collapse.in {
    overflow-y: auto; }
  @media (min-width: 768px) {
    .navbar-collapse {
      width: auto;
      border-top: 0;
      box-shadow: none; }
      .navbar-collapse.collapse {
        display: block !important;
        height: auto !important;
        padding-bottom: 0;
        overflow: visible !important; }
      .navbar-collapse.in {
        overflow-y: visible; }
      .navbar-fixed-top .navbar-collapse,
      .navbar-static-top .navbar-collapse,
      .navbar-fixed-bottom .navbar-collapse {
        padding-left: 0;
        padding-right: 0; } }

.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px; }
  @media (max-device-width: 480px) and (orientation: landscape) {
    .navbar-fixed-top .navbar-collapse,
    .navbar-fixed-bottom .navbar-collapse {
      max-height: 200px; } }

.container > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-header,
.container-fluid > .navbar-collapse {
  margin-right: -15px;
  margin-left: -15px; }
  @media (min-width: 768px) {
    .container > .navbar-header,
    .container > .navbar-collapse,
    .container-fluid > .navbar-header,
    .container-fluid > .navbar-collapse {
      margin-right: 0;
      margin-left: 0; } }

.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px; }
  @media (min-width: 768px) {
    .navbar-static-top {
      border-radius: 0; } }

.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030; }
  @media (min-width: 768px) {
    .navbar-fixed-top,
    .navbar-fixed-bottom {
      border-radius: 0; } }

.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px; }

.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0; }

.navbar-brand {
  float: left;
  padding: 15px 15px;
  font-size: 18px;
  line-height: 20px;
  height: 50px; }
  .navbar-brand:hover, .navbar-brand:focus {
    text-decoration: none; }
  .navbar-brand > img {
    display: block; }
  @media (min-width: 768px) {
    .navbar > .container .navbar-brand,
    .navbar > .container-fluid .navbar-brand {
      margin-left: -15px; } }

.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 15px;
  padding: 9px 10px;
  margin-top: 8px;
  margin-bottom: 8px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 4px; }
  .navbar-toggle:focus {
    outline: 0; }
  .navbar-toggle .icon-bar {
    display: block;
    width: 22px;
    height: 2px;
    border-radius: 1px; }
  .navbar-toggle .icon-bar + .icon-bar {
    margin-top: 4px; }
  @media (min-width: 768px) {
    .navbar-toggle {
      display: block!important; } }

.navbar-nav {
  margin: 7.5px -15px; }
  .navbar-nav > li > a {
    padding-top: 10px;
    padding-bottom: 10px;
    line-height: 20px; }
  @media (max-width: 767px) {
    .navbar-nav .open .dropdown-menu {
      position: static;
      float: none;
      width: auto;
      margin-top: 0;
      background-color: transparent;
      border: 0;
      box-shadow: none; }
      .navbar-nav .open .dropdown-menu > li > a,
      .navbar-nav .open .dropdown-menu .dropdown-header {
        padding: 5px 15px 5px 25px; }
      .navbar-nav .open .dropdown-menu > li > a {
        line-height: 20px; }
        .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-nav .open .dropdown-menu > li > a:focus {
          background-image: none; } }
  @media (min-width: 768px) {
    .navbar-nav {
      float: left;
      margin: 0; }
      .navbar-nav > li {
        float: left; }
        .navbar-nav > li > a {
          padding-top: 15px;
          padding-bottom: 15px; } }

.navbar-form {
  margin-left: -15px;
  margin-right: -15px;
  padding: 10px 15px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: 8px;
  margin-bottom: 8px; }
  @media (min-width: 768px) {
    .navbar-form .form-group {
      display: inline-block;
      margin-bottom: 0;
      vertical-align: middle; }
    .navbar-form .form-control {
      display: inline-block;
      width: auto;
      vertical-align: middle; }
    .navbar-form .form-control-static {
      display: inline-block; }
    .navbar-form .input-group {
      display: inline-table;
      vertical-align: middle; }
      .navbar-form .input-group .input-group-addon,
      .navbar-form .input-group .input-group-btn,
      .navbar-form .input-group .form-control {
        width: auto; }
    .navbar-form .input-group > .form-control {
      width: 100%; }
    .navbar-form .control-label {
      margin-bottom: 0;
      vertical-align: middle; }
    .navbar-form .radio,
    .navbar-form .checkbox {
      display: inline-block;
      margin-top: 0;
      margin-bottom: 0;
      vertical-align: middle; }
      .navbar-form .radio label,
      .navbar-form .checkbox label {
        padding-left: 0; }
    .navbar-form .radio input[type="radio"],
    .navbar-form .checkbox input[type="checkbox"] {
      position: relative;
      margin-left: 0; }
    .navbar-form .has-feedback .form-control-feedback {
      top: 0; } }
  @media (max-width: 767px) {
    .navbar-form .form-group {
      margin-bottom: 5px; }
      .navbar-form .form-group:last-child {
        margin-bottom: 0; } }
  @media (min-width: 768px) {
    .navbar-form {
      width: auto;
      border: 0;
      margin-left: 0;
      margin-right: 0;
      padding-top: 0;
      padding-bottom: 0;
      -webkit-box-shadow: none;
      box-shadow: none; } }

.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0; }

.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 4px;
  border-top-left-radius: 4px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0; }

.navbar-btn {
  margin-top: 8px;
  margin-bottom: 8px; }
  .navbar-btn.btn-sm, .btn-group-sm > .navbar-btn.btn {
    margin-top: 10px;
    margin-bottom: 10px; }
  .navbar-btn.btn-xs, .btn-group-xs > .navbar-btn.btn {
    margin-top: 14px;
    margin-bottom: 14px; }

.navbar-text {
  margin-top: 15px;
  margin-bottom: 15px; }
  @media (min-width: 768px) {
    .navbar-text {
      float: left;
      margin-left: 15px;
      margin-right: 15px; } }

@media (min-width: 768px) {
  .navbar-left {
    float: left !important; }
  .navbar-right {
    float: right !important;
    margin-right: -15px; }
    .navbar-right ~ .navbar-right {
      margin-right: 0; } }

.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7; }
  .navbar-default .navbar-brand {
    color: #777; }
    .navbar-default .navbar-brand:hover, .navbar-default .navbar-brand:focus {
      color: #5e5e5e;
      background-color: transparent; }
  .navbar-default .navbar-text {
    color: #777; }
  .navbar-default .navbar-nav > li > a {
    color: #999 !important; }
    .navbar-default .navbar-nav > li > a:hover, .navbar-default .navbar-nav > li > a:focus {
      color: #333;
      background-color: transparent; }
  .navbar-default .navbar-nav > .active > a, .navbar-default .navbar-nav > .active > a:hover, .navbar-default .navbar-nav > .active > a:focus {
    color: #555;
    background-color: #e7e7e7; }
  .navbar-default .navbar-nav > .disabled > a, .navbar-default .navbar-nav > .disabled > a:hover, .navbar-default .navbar-nav > .disabled > a:focus {
    color: #ccc;
    background-color: transparent; }
  .navbar-default .navbar-toggle {
    border-color: #ddd; }
    .navbar-default .navbar-toggle:hover, .navbar-default .navbar-toggle:focus {
      background-color: #ddd; }
    .navbar-default .navbar-toggle .icon-bar {
      background-color: #888; }
  .navbar-default .navbar-collapse,
  .navbar-default .navbar-form {
    border-color: #e7e7e7; }
  .navbar-default .navbar-nav > .open > a, .navbar-default .navbar-nav > .open > a:hover, .navbar-default .navbar-nav > .open > a:focus {
    background-color: #e7e7e7;
    color: #555; }
  @media (max-width: 767px) {
    .navbar-default .navbar-nav .open .dropdown-menu > li > a {
      color: #777; }
      .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
        color: #333;
        background-color: transparent; }
    .navbar-default .navbar-nav .open .dropdown-menu > .active > a, .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
      color: #555;
      background-color: #e7e7e7; }
    .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a, .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
      color: #ccc;
      background-color: transparent; } }
  .navbar-default .navbar-link {
    color: #777; }
    .navbar-default .navbar-link:hover {
      color: #333; }
  .navbar-default .btn-link {
    color: #777; }
    .navbar-default .btn-link:hover, .navbar-default .btn-link:focus {
      color: #333; }
    .navbar-default .btn-link[disabled]:hover, .navbar-default .btn-link[disabled]:focus,
    fieldset[disabled] .navbar-default .btn-link:hover,
    fieldset[disabled] .navbar-default .btn-link:focus {
      color: #ccc; }

.navbar-inverse {
  background-color: #222;
  border-color: #090909; }
  .navbar-inverse .navbar-brand {
    color: #9d9d9d; }
    .navbar-inverse .navbar-brand:hover, .navbar-inverse .navbar-brand:focus {
      color: #fff;
      background-color: transparent; }
  .navbar-inverse .navbar-text {
    color: #9d9d9d; }
  .navbar-inverse .navbar-nav > li > a {
    color: #9d9d9d; }
    .navbar-inverse .navbar-nav > li > a:hover, .navbar-inverse .navbar-nav > li > a:focus {
      color: #fff;
      background-color: transparent; }
  .navbar-inverse .navbar-nav > .active > a, .navbar-inverse .navbar-nav > .active > a:hover, .navbar-inverse .navbar-nav > .active > a:focus {
    color: #fff;
    background-color: #090909; }
  .navbar-inverse .navbar-nav > .disabled > a, .navbar-inverse .navbar-nav > .disabled > a:hover, .navbar-inverse .navbar-nav > .disabled > a:focus {
    color: #444;
    background-color: transparent; }
  .navbar-inverse .navbar-toggle {
    border-color: #333; }
    .navbar-inverse .navbar-toggle:hover, .navbar-inverse .navbar-toggle:focus {
      background-color: #333; }
    .navbar-inverse .navbar-toggle .icon-bar {
      background-color: #fff; }
  .navbar-inverse .navbar-collapse,
  .navbar-inverse .navbar-form {
    border-color: #101010; }
  .navbar-inverse .navbar-nav > .open > a, .navbar-inverse .navbar-nav > .open > a:hover, .navbar-inverse .navbar-nav > .open > a:focus {
    background-color: #090909;
    color: #fff; }
  @media (max-width: 767px) {
    .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
      border-color: #090909; }
    .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
      background-color: #090909; }
    .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
      color: #9d9d9d; }
      .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
        color: #fff;
        background-color: transparent; }
    .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a, .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
      color: #fff;
      background-color: #090909; }
    .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a, .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
      color: #444;
      background-color: transparent; } }
  .navbar-inverse .navbar-link {
    color: #9d9d9d; }
    .navbar-inverse .navbar-link:hover {
      color: #fff; }
  .navbar-inverse .btn-link {
    color: #9d9d9d; }
    .navbar-inverse .btn-link:hover, .navbar-inverse .btn-link:focus {
      color: #fff; }
    .navbar-inverse .btn-link[disabled]:hover, .navbar-inverse .btn-link[disabled]:focus,
    fieldset[disabled] .navbar-inverse .btn-link:hover,
    fieldset[disabled] .navbar-inverse .btn-link:focus {
      color: #444; }

.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 20px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 4px; }
  .breadcrumb > li {
    display: inline-block; }
    .breadcrumb > li + li:before {
      content: "/ ";
      padding: 0 5px;
      color: #ccc; }
  .breadcrumb > .active {
    color: #777777; }

.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 20px 0;
  border-radius: 4px; }
  .pagination > li {
    display: inline; }
    .pagination > li > a,
    .pagination > li > span {
      position: relative;
      float: left;
      padding: 6px 12px;
      line-height: 1.42857;
      text-decoration: none;
      color: #337ab7;
      background-color: #fff;
      border: 1px solid #ddd;
      margin-left: -1px; }
    .pagination > li:first-child > a,
    .pagination > li:first-child > span {
      margin-left: 0;
      border-bottom-left-radius: 4px;
      border-top-left-radius: 4px; }
    .pagination > li:last-child > a,
    .pagination > li:last-child > span {
      border-bottom-right-radius: 4px;
      border-top-right-radius: 4px; }
  .pagination > li > a:hover, .pagination > li > a:focus,
  .pagination > li > span:hover,
  .pagination > li > span:focus {
    z-index: 2;
    color: #23527c;
    background-color: #eeeeee;
    border-color: #ddd; }
  .pagination > .active > a, .pagination > .active > a:hover, .pagination > .active > a:focus,
  .pagination > .active > span,
  .pagination > .active > span:hover,
  .pagination > .active > span:focus {
    z-index: 3;
    color: #fff;
    background-color: #337ab7;
    border-color: #337ab7;
    cursor: default; }
  .pagination > .disabled > span,
  .pagination > .disabled > span:hover,
  .pagination > .disabled > span:focus,
  .pagination > .disabled > a,
  .pagination > .disabled > a:hover,
  .pagination > .disabled > a:focus {
    color: #777777;
    background-color: #fff;
    border-color: #ddd;
    cursor: not-allowed; }

.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 18px;
  line-height: 1.33333; }

.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 6px;
  border-top-left-radius: 6px; }

.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 6px;
  border-top-right-radius: 6px; }

.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5; }

.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px; }

.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px; }

.pager {
  padding-left: 0;
  margin: 20px 0;
  list-style: none;
  text-align: center; }
  .pager:before, .pager:after {
    content: " ";
    display: table; }
  .pager:after {
    clear: both; }
  .pager li {
    display: inline; }
    .pager li > a,
    .pager li > span {
      display: inline-block;
      padding: 5px 14px;
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 15px; }
    .pager li > a:hover,
    .pager li > a:focus {
      text-decoration: none;
      background-color: #eeeeee; }
  .pager .next > a,
  .pager .next > span {
    float: right; }
  .pager .previous > a,
  .pager .previous > span {
    float: left; }
  .pager .disabled > a,
  .pager .disabled > a:hover,
  .pager .disabled > a:focus,
  .pager .disabled > span {
    color: #777777;
    background-color: #fff;
    cursor: not-allowed; }

.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em; }
  .label:empty {
    display: none; }
  .btn .label {
    position: relative;
    top: -1px; }

a.label:hover, a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer; }

.label-default {
  background-color: #777777; }
  .label-default[href]:hover, .label-default[href]:focus {
    background-color: #5e5e5e; }

.label-primary {
  background-color: #337ab7; }
  .label-primary[href]:hover, .label-primary[href]:focus {
    background-color: #286090; }

.label-success {
  background-color: #5cb85c; }
  .label-success[href]:hover, .label-success[href]:focus {
    background-color: #449d44; }

.label-info {
  background-color: #5bc0de; }
  .label-info[href]:hover, .label-info[href]:focus {
    background-color: #31b0d5; }

.label-warning {
  background-color: #f0ad4e; }
  .label-warning[href]:hover, .label-warning[href]:focus {
    background-color: #ec971f; }

.label-danger {
  background-color: #d9534f; }
  .label-danger[href]:hover, .label-danger[href]:focus {
    background-color: #c9302c; }

.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px; }
  .badge:empty {
    display: none; }
  .btn .badge {
    position: relative;
    top: -1px; }
  .btn-xs .badge, .btn-group-xs > .btn .badge,
  .btn-group-xs > .btn .badge {
    top: 0;
    padding: 1px 5px; }
  .list-group-item.active > .badge,
  .nav-pills > .active > a > .badge {
    color: #337ab7;
    background-color: #fff; }
  .list-group-item > .badge {
    float: right; }
  .list-group-item > .badge + .badge {
    margin-right: 5px; }
  .nav-pills > li > a > .badge {
    margin-left: 3px; }

a.badge:hover, a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer; }

.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee; }
  .jumbotron h1,
  .jumbotron .h1 {
    color: inherit; }
  .jumbotron p {
    margin-bottom: 15px;
    font-size: 21px;
    font-weight: 200; }
  .jumbotron > hr {
    border-top-color: #d5d5d5; }
  .container .jumbotron,
  .container-fluid .jumbotron {
    border-radius: 6px;
    padding-left: 15px;
    padding-right: 15px; }
  .jumbotron .container {
    max-width: 100%; }
  @media screen and (min-width: 768px) {
    .jumbotron {
      padding-top: 48px;
      padding-bottom: 48px; }
      .container .jumbotron,
      .container-fluid .jumbotron {
        padding-left: 60px;
        padding-right: 60px; }
      .jumbotron h1,
      .jumbotron .h1 {
        font-size: 63px; } }

.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 20px;
  line-height: 1.42857;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 4px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out; }
  .thumbnail > img,
  .thumbnail a > img {
    display: block;
    max-width: 100%;
    height: auto;
    margin-left: auto;
    margin-right: auto; }
  .thumbnail .caption {
    padding: 9px;
    color: #333333; }

a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7; }

.alert {
  padding: 15px;
  margin-bottom: 20px;
  border: 1px solid transparent;
  border-radius: 4px; }
  .alert h4 {
    margin-top: 0;
    color: inherit; }
  .alert .alert-link {
    font-weight: bold; }
  .alert > p,
  .alert > ul {
    margin-bottom: 0; }
  .alert > p + p {
    margin-top: 5px; }

.alert-dismissable,
.alert-dismissible {
  padding-right: 35px; }
  .alert-dismissable .close,
  .alert-dismissible .close {
    position: relative;
    top: -2px;
    right: -21px;
    color: inherit; }

.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d; }
  .alert-success hr {
    border-top-color: #c9e2b3; }
  .alert-success .alert-link {
    color: #2b542c; }

.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f; }
  .alert-info hr {
    border-top-color: #a6e1ec; }
  .alert-info .alert-link {
    color: #245269; }

.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b; }
  .alert-warning hr {
    border-top-color: #f7e1b5; }
  .alert-warning .alert-link {
    color: #66512c; }

.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442; }
  .alert-danger hr {
    border-top-color: #e4b9c0; }
  .alert-danger .alert-link {
    color: #843534; }

@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0; }
  to {
    background-position: 0 0; } }

@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0; }
  to {
    background-position: 0 0; } }

.progress {
  overflow: hidden;
  height: 20px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border-radius: 4px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1); }

.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 20px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease; }

.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px; }

.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite; }

.progress-bar-success {
  background-color: #5cb85c; }
  .progress-striped .progress-bar-success {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); }

.progress-bar-info {
  background-color: #5bc0de; }
  .progress-striped .progress-bar-info {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); }

.progress-bar-warning {
  background-color: #f0ad4e; }
  .progress-striped .progress-bar-warning {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); }

.progress-bar-danger {
  background-color: #d9534f; }
  .progress-striped .progress-bar-danger {
    background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
    background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); }

.media {
  margin-top: 15px; }
  .media:first-child {
    margin-top: 0; }

.media,
.media-body {
  zoom: 1;
  overflow: hidden; }

.media-body {
  width: 10000px; }

.media-object {
  display: block; }
  .media-object.img-thumbnail {
    max-width: none; }

.media-right,
.media > .pull-right {
  padding-left: 10px; }

.media-left,
.media > .pull-left {
  padding-right: 10px; }

.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top; }

.media-middle {
  vertical-align: middle; }

.media-bottom {
  vertical-align: bottom; }

.media-heading {
  margin-top: 0;
  margin-bottom: 5px; }

.media-list {
  padding-left: 0;
  list-style: none; }

.list-group {
  margin-bottom: 20px;
  padding-left: 0; }

.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd; }
  .list-group-item:first-child {
    border-top-right-radius: 4px;
    border-top-left-radius: 4px; }
  .list-group-item:last-child {
    margin-bottom: 0;
    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px; }

a.list-group-item,
button.list-group-item {
  color: #555; }
  a.list-group-item .list-group-item-heading,
  button.list-group-item .list-group-item-heading {
    color: #333; }
  a.list-group-item:hover, a.list-group-item:focus,
  button.list-group-item:hover,
  button.list-group-item:focus {
    text-decoration: none;
    color: #555;
    background-color: #f5f5f5; }

button.list-group-item {
  width: 100%;
  text-align: left; }

.list-group-item.disabled, .list-group-item.disabled:hover, .list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed; }
  .list-group-item.disabled .list-group-item-heading, .list-group-item.disabled:hover .list-group-item-heading, .list-group-item.disabled:focus .list-group-item-heading {
    color: inherit; }
  .list-group-item.disabled .list-group-item-text, .list-group-item.disabled:hover .list-group-item-text, .list-group-item.disabled:focus .list-group-item-text {
    color: #777777; }

.list-group-item.active, .list-group-item.active:hover, .list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7; }
  .list-group-item.active .list-group-item-heading,
  .list-group-item.active .list-group-item-heading > small,
  .list-group-item.active .list-group-item-heading > .small, .list-group-item.active:hover .list-group-item-heading,
  .list-group-item.active:hover .list-group-item-heading > small,
  .list-group-item.active:hover .list-group-item-heading > .small, .list-group-item.active:focus .list-group-item-heading,
  .list-group-item.active:focus .list-group-item-heading > small,
  .list-group-item.active:focus .list-group-item-heading > .small {
    color: inherit; }
  .list-group-item.active .list-group-item-text, .list-group-item.active:hover .list-group-item-text, .list-group-item.active:focus .list-group-item-text {
    color: #c7ddef; }

.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8; }

a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d; }
  a.list-group-item-success .list-group-item-heading,
  button.list-group-item-success .list-group-item-heading {
    color: inherit; }
  a.list-group-item-success:hover, a.list-group-item-success:focus,
  button.list-group-item-success:hover,
  button.list-group-item-success:focus {
    color: #3c763d;
    background-color: #d0e9c6; }
  a.list-group-item-success.active, a.list-group-item-success.active:hover, a.list-group-item-success.active:focus,
  button.list-group-item-success.active,
  button.list-group-item-success.active:hover,
  button.list-group-item-success.active:focus {
    color: #fff;
    background-color: #3c763d;
    border-color: #3c763d; }

.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7; }

a.list-group-item-info,
button.list-group-item-info {
  color: #31708f; }
  a.list-group-item-info .list-group-item-heading,
  button.list-group-item-info .list-group-item-heading {
    color: inherit; }
  a.list-group-item-info:hover, a.list-group-item-info:focus,
  button.list-group-item-info:hover,
  button.list-group-item-info:focus {
    color: #31708f;
    background-color: #c4e3f3; }
  a.list-group-item-info.active, a.list-group-item-info.active:hover, a.list-group-item-info.active:focus,
  button.list-group-item-info.active,
  button.list-group-item-info.active:hover,
  button.list-group-item-info.active:focus {
    color: #fff;
    background-color: #31708f;
    border-color: #31708f; }

.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3; }

a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b; }
  a.list-group-item-warning .list-group-item-heading,
  button.list-group-item-warning .list-group-item-heading {
    color: inherit; }
  a.list-group-item-warning:hover, a.list-group-item-warning:focus,
  button.list-group-item-warning:hover,
  button.list-group-item-warning:focus {
    color: #8a6d3b;
    background-color: #faf2cc; }
  a.list-group-item-warning.active, a.list-group-item-warning.active:hover, a.list-group-item-warning.active:focus,
  button.list-group-item-warning.active,
  button.list-group-item-warning.active:hover,
  button.list-group-item-warning.active:focus {
    color: #fff;
    background-color: #8a6d3b;
    border-color: #8a6d3b; }

.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede; }

a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442; }
  a.list-group-item-danger .list-group-item-heading,
  button.list-group-item-danger .list-group-item-heading {
    color: inherit; }
  a.list-group-item-danger:hover, a.list-group-item-danger:focus,
  button.list-group-item-danger:hover,
  button.list-group-item-danger:focus {
    color: #a94442;
    background-color: #ebcccc; }
  a.list-group-item-danger.active, a.list-group-item-danger.active:hover, a.list-group-item-danger.active:focus,
  button.list-group-item-danger.active,
  button.list-group-item-danger.active:hover,
  button.list-group-item-danger.active:focus {
    color: #fff;
    background-color: #a94442;
    border-color: #a94442; }

.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px; }

.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3; }

.panel {
  margin-bottom: 20px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 4px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05); }

.panel-body {
  padding: 15px; }
  .panel-body:before, .panel-body:after {
    content: " ";
    display: table; }
  .panel-body:after {
    clear: both; }

.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 3px;
  border-top-left-radius: 3px; }
  .panel-heading > .dropdown .dropdown-toggle {
    color: inherit; }

.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 16px;
  color: inherit; }
  .panel-title > a,
  .panel-title > small,
  .panel-title > .small,
  .panel-title > small > a,
  .panel-title > .small > a {
    color: inherit; }

.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 3px;
  border-bottom-left-radius: 3px; }

.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0; }
  .panel > .list-group .list-group-item,
  .panel > .panel-collapse > .list-group .list-group-item {
    border-width: 1px 0;
    border-radius: 0; }
  .panel > .list-group:first-child .list-group-item:first-child,
  .panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
    border-top: 0;
    border-top-right-radius: 3px;
    border-top-left-radius: 3px; }
  .panel > .list-group:last-child .list-group-item:last-child,
  .panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
    border-bottom: 0;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px; }

.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0; }

.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0; }

.list-group + .panel-footer {
  border-top-width: 0; }

.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0; }
  .panel > .table caption,
  .panel > .table-responsive > .table caption,
  .panel > .panel-collapse > .table caption {
    padding-left: 15px;
    padding-right: 15px; }

.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 3px;
  border-top-left-radius: 3px; }
  .panel > .table:first-child > thead:first-child > tr:first-child,
  .panel > .table:first-child > tbody:first-child > tr:first-child,
  .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
  .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
    border-top-left-radius: 3px;
    border-top-right-radius: 3px; }
    .panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
    .panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
    .panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
    .panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
    .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
    .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
    .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
    .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
      border-top-left-radius: 3px; }
    .panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
    .panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
    .panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
    .panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
    .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
    .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
    .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
    .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
      border-top-right-radius: 3px; }

.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 3px;
  border-bottom-left-radius: 3px; }
  .panel > .table:last-child > tbody:last-child > tr:last-child,
  .panel > .table:last-child > tfoot:last-child > tr:last-child,
  .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
  .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
    border-bottom-left-radius: 3px;
    border-bottom-right-radius: 3px; }
    .panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
    .panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
    .panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
    .panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
    .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
    .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
    .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
    .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
      border-bottom-left-radius: 3px; }
    .panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
    .panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
    .panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
    .panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
    .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
    .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
    .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
    .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
      border-bottom-right-radius: 3px; }

.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd; }

.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0; }

.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0; }
  .panel > .table-bordered > thead > tr > th:first-child,
  .panel > .table-bordered > thead > tr > td:first-child,
  .panel > .table-bordered > tbody > tr > th:first-child,
  .panel > .table-bordered > tbody > tr > td:first-child,
  .panel > .table-bordered > tfoot > tr > th:first-child,
  .panel > .table-bordered > tfoot > tr > td:first-child,
  .panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
  .panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
  .panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0; }
  .panel > .table-bordered > thead > tr > th:last-child,
  .panel > .table-bordered > thead > tr > td:last-child,
  .panel > .table-bordered > tbody > tr > th:last-child,
  .panel > .table-bordered > tbody > tr > td:last-child,
  .panel > .table-bordered > tfoot > tr > th:last-child,
  .panel > .table-bordered > tfoot > tr > td:last-child,
  .panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
  .panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
  .panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0; }
  .panel > .table-bordered > thead > tr:first-child > td,
  .panel > .table-bordered > thead > tr:first-child > th,
  .panel > .table-bordered > tbody > tr:first-child > td,
  .panel > .table-bordered > tbody > tr:first-child > th,
  .panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
  .panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
  .panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
  .panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
    border-bottom: 0; }
  .panel > .table-bordered > tbody > tr:last-child > td,
  .panel > .table-bordered > tbody > tr:last-child > th,
  .panel > .table-bordered > tfoot > tr:last-child > td,
  .panel > .table-bordered > tfoot > tr:last-child > th,
  .panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
  .panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
    border-bottom: 0; }

.panel > .table-responsive {
  border: 0;
  margin-bottom: 0; }

.panel-group {
  margin-bottom: 20px; }
  .panel-group .panel {
    margin-bottom: 0;
    border-radius: 4px; }
    .panel-group .panel + .panel {
      margin-top: 5px; }
  .panel-group .panel-heading {
    border-bottom: 0; }
    .panel-group .panel-heading + .panel-collapse > .panel-body,
    .panel-group .panel-heading + .panel-collapse > .list-group {
      border-top: 1px solid #ddd; }
  .panel-group .panel-footer {
    border-top: 0; }
    .panel-group .panel-footer + .panel-collapse .panel-body {
      border-bottom: 1px solid #ddd; }

.panel-default {
  border-color: #ddd; }
  .panel-default > .panel-heading {
    color: #333333;
    background-color: #f5f5f5;
    border-color: #ddd; }
    .panel-default > .panel-heading + .panel-collapse > .panel-body {
      border-top-color: #ddd; }
    .panel-default > .panel-heading .badge {
      color: #f5f5f5;
      background-color: #333333; }
  .panel-default > .panel-footer + .panel-collapse > .panel-body {
    border-bottom-color: #ddd; }

.panel-primary {
  border-color: #337ab7; }
  .panel-primary > .panel-heading {
    color: #fff;
    background-color: #337ab7;
    border-color: #337ab7; }
    .panel-primary > .panel-heading + .panel-collapse > .panel-body {
      border-top-color: #337ab7; }
    .panel-primary > .panel-heading .badge {
      color: #337ab7;
      background-color: #fff; }
  .panel-primary > .panel-footer + .panel-collapse > .panel-body {
    border-bottom-color: #337ab7; }

.panel-success {
  border-color: #d6e9c6; }
  .panel-success > .panel-heading {
    color: #3c763d;
    background-color: #dff0d8;
    border-color: #d6e9c6; }
    .panel-success > .panel-heading + .panel-collapse > .panel-body {
      border-top-color: #d6e9c6; }
    .panel-success > .panel-heading .badge {
      color: #dff0d8;
      background-color: #3c763d; }
  .panel-success > .panel-footer + .panel-collapse > .panel-body {
    border-bottom-color: #d6e9c6; }

.panel-info {
  border-color: #bce8f1; }
  .panel-info > .panel-heading {
    color: #31708f;
    background-color: #d9edf7;
    border-color: #bce8f1; }
    .panel-info > .panel-heading + .panel-collapse > .panel-body {
      border-top-color: #bce8f1; }
    .panel-info > .panel-heading .badge {
      color: #d9edf7;
      background-color: #31708f; }
  .panel-info > .panel-footer + .panel-collapse > .panel-body {
    border-bottom-color: #bce8f1; }

.panel-warning {
  border-color: #faebcc; }
  .panel-warning > .panel-heading {
    color: #8a6d3b;
    background-color: #fcf8e3;
    border-color: #faebcc; }
    .panel-warning > .panel-heading + .panel-collapse > .panel-body {
      border-top-color: #faebcc; }
    .panel-warning > .panel-heading .badge {
      color: #fcf8e3;
      background-color: #8a6d3b; }
  .panel-warning > .panel-footer + .panel-collapse > .panel-body {
    border-bottom-color: #faebcc; }

.panel-danger {
  border-color: #ebccd1; }
  .panel-danger > .panel-heading {
    color: #a94442;
    background-color: #f2dede;
    border-color: #ebccd1; }
    .panel-danger > .panel-heading + .panel-collapse > .panel-body {
      border-top-color: #ebccd1; }
    .panel-danger > .panel-heading .badge {
      color: #f2dede;
      background-color: #a94442; }
  .panel-danger > .panel-footer + .panel-collapse > .panel-body {
    border-bottom-color: #ebccd1; }

.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden; }
  .embed-responsive .embed-responsive-item,
  .embed-responsive iframe,
  .embed-responsive embed,
  .embed-responsive object,
  .embed-responsive video {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    height: 100%;
    width: 100%;
    border: 0; }

.embed-responsive-16by9 {
  padding-bottom: 56.25%; }

.embed-responsive-4by3 {
  padding-bottom: 75%; }

.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 4px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05); }
  .well blockquote {
    border-color: #ddd;
    border-color: rgba(0, 0, 0, 0.15); }

.well-lg {
  padding: 24px;
  border-radius: 6px; }

.well-sm {
  padding: 9px;
  border-radius: 3px; }

.close {
  float: right;
  font-size: 21px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20); }
  .close:hover, .close:focus {
    color: #000;
    text-decoration: none;
    cursor: pointer;
    opacity: 0.5;
    filter: alpha(opacity=50); }

button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none; }

.modal-open {
  overflow: hidden; }

.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0; }
  .modal.fade .modal-dialog {
    -webkit-transform: translate(0, -25%);
    -ms-transform: translate(0, -25%);
    -o-transform: translate(0, -25%);
    transform: translate(0, -25%);
    -webkit-transition: -webkit-transform 0.3s ease-out;
    -moz-transition: -moz-transform 0.3s ease-out;
    -o-transition: -o-transform 0.3s ease-out;
    transition: transform 0.3s ease-out; }
  .modal.in .modal-dialog {
    -webkit-transform: translate(0, 0);
    -ms-transform: translate(0, 0);
    -o-transform: translate(0, 0);
    transform: translate(0, 0); }

.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto; }

.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px; }

.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 6px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0; }

.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000; }
  .modal-backdrop.fade {
    opacity: 0;
    filter: alpha(opacity=0); }
  .modal-backdrop.in {
    opacity: 0.5;
    filter: alpha(opacity=50); }

.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5; }
  .modal-header:before, .modal-header:after {
    content: " ";
    display: table; }
  .modal-header:after {
    clear: both; }

.modal-header .close {
  margin-top: -2px; }

.modal-title {
  margin: 0;
  line-height: 1.42857; }

.modal-body {
  position: relative;
  padding: 15px; }

.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5; }
  .modal-footer:before, .modal-footer:after {
    content: " ";
    display: table; }
  .modal-footer:after {
    clear: both; }
  .modal-footer .btn + .btn {
    margin-left: 5px;
    margin-bottom: 0; }
  .modal-footer .btn-group .btn + .btn {
    margin-left: -1px; }
  .modal-footer .btn-block + .btn-block {
    margin-left: 0; }

.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll; }

@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto; }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5); }
  .modal-sm {
    width: 300px; } }

@media (min-width: 992px) {
  .modal-lg {
    width: 900px; } }

.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857;
  text-align: center;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0); }
  .tooltip.in {
    opacity: 0.9;
    filter: alpha(opacity=90); }
  .tooltip.top {
    margin-top: -93px;
    padding: 5px 0; }
  .tooltip.right {
    margin-left: 3px;
    padding: 0 5px; }
  .tooltip.bottom {
    margin-top: 3px;
    padding: 5px 0; }
  .tooltip.left {
    margin-left: -3px;
    padding: 0 5px; }

.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 4px; }

.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid; }

.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000; }

.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000; }

.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000; }

.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000; }

.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000; }

.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000; }

.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000; }

.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000; }

.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Montserrat", sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 14px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 6px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2); }
  .popover.top {
    margin-top: -10px; }
  .popover.right {
    margin-left: 10px; }
  .popover.bottom {
    margin-top: 10px; }
  .popover.left {
    margin-left: -10px; }

.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 14px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 5px 5px 0 0; }

.popover-content {
  padding: 9px 14px; }

.popover > .arrow, .popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid; }

.popover > .arrow {
  border-width: 11px; }

.popover > .arrow:after {
  border-width: 10px;
  content: ""; }

.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px; }
  .popover.top > .arrow:after {
    content: " ";
    bottom: 1px;
    margin-left: -10px;
    border-bottom-width: 0;
    border-top-color: #fff; }

.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25); }
  .popover.right > .arrow:after {
    content: " ";
    left: 1px;
    bottom: -10px;
    border-left-width: 0;
    border-right-color: #fff; }

.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px; }
  .popover.bottom > .arrow:after {
    content: " ";
    top: 1px;
    margin-left: -10px;
    border-top-width: 0;
    border-bottom-color: #fff; }

.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25); }
  .popover.left > .arrow:after {
    content: " ";
    right: 1px;
    border-right-width: 0;
    border-left-color: #fff;
    bottom: -10px; }

.carousel {
  position: relative; }

.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%; }
  .carousel-inner > .item {
    display: none;
    position: relative;
    -webkit-transition: 0.6s ease-in-out left;
    -o-transition: 0.6s ease-in-out left;
    transition: 0.6s ease-in-out left; }
    .carousel-inner > .item > img,
    .carousel-inner > .item > a > img {
      display: block;
      max-width: 100%;
      height: auto;
      line-height: 1; }
    @media all and (transform-3d), (-webkit-transform-3d) {
      .carousel-inner > .item {
        -webkit-transition: -webkit-transform 0.6s ease-in-out;
        -moz-transition: -moz-transform 0.6s ease-in-out;
        -o-transition: -o-transform 0.6s ease-in-out;
        transition: transform 0.6s ease-in-out;
        -webkit-backface-visibility: hidden;
        -moz-backface-visibility: hidden;
        backface-visibility: hidden;
        -webkit-perspective: 1000px;
        -moz-perspective: 1000px;
        perspective: 1000px; }
        .carousel-inner > .item.next, .carousel-inner > .item.active.right {
          -webkit-transform: translate3d(100%, 0, 0);
          transform: translate3d(100%, 0, 0);
          left: 0; }
        .carousel-inner > .item.prev, .carousel-inner > .item.active.left {
          -webkit-transform: translate3d(-100%, 0, 0);
          transform: translate3d(-100%, 0, 0);
          left: 0; }
        .carousel-inner > .item.next.left, .carousel-inner > .item.prev.right, .carousel-inner > .item.active {
          -webkit-transform: translate3d(0, 0, 0);
          transform: translate3d(0, 0, 0);
          left: 0; } }
  .carousel-inner > .active,
  .carousel-inner > .next,
  .carousel-inner > .prev {
    display: block; }
  .carousel-inner > .active {
    left: 0; }
  .carousel-inner > .next,
  .carousel-inner > .prev {
    position: absolute;
    top: 0;
    width: 100%; }
  .carousel-inner > .next {
    left: 100%; }
  .carousel-inner > .prev {
    left: -100%; }
  .carousel-inner > .next.left,
  .carousel-inner > .prev.right {
    left: 0; }
  .carousel-inner > .active.left {
    left: -100%; }
  .carousel-inner > .active.right {
    left: 100%; }

.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: transparent; }
  .carousel-control.left {
    background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
    background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
    background-repeat: repeat-x;
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1); }
  .carousel-control.right {
    left: auto;
    right: 0;
    background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
    background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
    background-repeat: repeat-x;
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1); }
  .carousel-control:hover, .carousel-control:focus {
    outline: 0;
    color: #fff;
    text-decoration: none;
    opacity: 0.9;
    filter: alpha(opacity=90); }
  .carousel-control .icon-prev,
  .carousel-control .icon-next,
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right {
    position: absolute;
    top: 50%;
    margin-top: -10px;
    z-index: 5;
    display: inline-block; }
  .carousel-control .icon-prev,
  .carousel-control .glyphicon-chevron-left {
    left: 50%;
    margin-left: -10px; }
  .carousel-control .icon-next,
  .carousel-control .glyphicon-chevron-right {
    right: 50%;
    margin-right: -10px; }
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 20px;
    height: 20px;
    line-height: 1;
    font-family: "Montserrat",sans-serif; }
  .carousel-control .icon-prev:before {
    content: '\2039'; }
  .carousel-control .icon-next:before {
    content: '\203a'; }

.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center; }
  .carousel-indicators li {
    display: inline-block;
    width: 10px;
    height: 10px;
    margin: 1px;
    text-indent: -999px;
    border: 1px solid #fff;
    border-radius: 10px;
    cursor: pointer;
    background-color: #000 \9;
    background-color: transparent; }
  .carousel-indicators .active {
    margin: 0;
    width: 12px;
    height: 12px;
    background-color: #fff; }

.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6); }
  .carousel-caption .btn {
    text-shadow: none; }

@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px; }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px; }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px; }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px; }
  .carousel-indicators {
    bottom: 20px; } }

.clearfix:before, .clearfix:after {
  content: " ";
  display: table; }

.clearfix:after {
  clear: both; }

.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto; }

.pull-right {
  float: right !important; }

.pull-left {
  float: left !important; }

.hide {
  display: none !important; }

.show {
  display: block !important; }

.invisible {
  visibility: hidden; }

.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0; }

.hidden {
  display: none !important; }

.affix {
  position: fixed; }

@-ms-viewport {
  width: device-width; }

.visible-xs {
  display: none !important; }

.visible-sm {
  display: none !important; }

.visible-md {
  display: none !important; }

.visible-lg {
  display: none !important; }

.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important; }

@media (max-width: 767px) {
  .visible-xs {
    display: block !important; }
  table.visible-xs {
    display: table !important; }
  tr.visible-xs {
    display: table-row !important; }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important; } }

@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important; } }

@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important; } }

@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important; } }

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important; }
  table.visible-sm {
    display: table !important; }
  tr.visible-sm {
    display: table-row !important; }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important; } }

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important; } }

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important; } }

@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important; } }

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important; }
  table.visible-md {
    display: table !important; }
  tr.visible-md {
    display: table-row !important; }
  th.visible-md,
  td.visible-md {
    display: table-cell !important; } }

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important; } }

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important; } }

@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important; } }

@media (min-width: 1200px) {
  .visible-lg {
    display: block !important; }
  table.visible-lg {
    display: table !important; }
  tr.visible-lg {
    display: table-row !important; }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important; } }

@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important; } }

@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important; } }

@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important; } }

@media (max-width: 767px) {
  .hidden-xs {
    display: none !important; } }

@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important; } }

@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important; } }

@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important; } }

.visible-print {
  display: none !important; }

@media print {
  .visible-print {
    display: block !important; }
  table.visible-print {
    display: table !important; }
  tr.visible-print {
    display: table-row !important; }
  th.visible-print,
  td.visible-print {
    display: table-cell !important; } }

.visible-print-block {
  display: none !important; }
  @media print {
    .visible-print-block {
      display: block !important; } }

.visible-print-inline {
  display: none !important; }
  @media print {
    .visible-print-inline {
      display: inline !important; } }

.visible-print-inline-block {
  display: none !important; }
  @media print {
    .visible-print-inline-block {
      display: inline-block !important; } }

@media print {
  .hidden-print {
    display: none !important; } }



.circle__item {
  background-image: url("../../images/icono_circulo2.png");
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
  width: 100%;
  height: 260px;
  display: table;
  text-align: center;
  margin-bottom: 40px; }
  .circle__item h4 {
    text-transform: uppercase;
    display: table-cell;
    vertical-align: middle;
    color: #FFFFFF;
    font-family: "Montserrat",sans-serif; }

@media only screen and (max-width: 425px) {
  .circle__item {
    height: 320px; }
    .circle__item h4 {
      font-size: 3em; } }

@media only screen and (max-width: 768px) {
  .circle__item { height: 320px; }
  .circle__item h4 { font-size: 3em; } 
}


hr {
background-image: linear-gradient(left,  #036B3A 0%, #53FEA2 100%)!important;
background-image: #036B3A; border: 0px!important; height: 1px!important; border-top: 0px solid #ffffff!important;
background-image: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%)!important;
background-image: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2))!important;
background-image: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background-image: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background-image: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background-image: linear-gradient(to right, #036B3A 0%, #53FEA2 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 )!important;
}

.linea_degrade  {
background-image: linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background-image: #036B3A; border: 0px; height: 1px; border-top: 0px solid #ffffff!important;
background-image: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background-image: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background-image: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background-image: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background-image: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background-image: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
}


.btn-ganolife_degrade2 {background:#ffffff;padding:10px;font-size:14px;color:#777777;width:30%;display:block;
                        border:1px solid #cdcdcd;float:left; margin-left:10px; margin-bottom:10px; text-align:left; height:230px;}
.btn-ganolife_degrade2:hover, .btn-ganolife_degrade2:focus  {
  border-left: 1px solid #036B3A; border-right: 1px solid #53FEA2; border-top: 1px solid #ffffff; border-bottom: 1px solid #ffffff;
  -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; background-position: 0 0, 0 100% ;
  background-repeat: no-repeat; -webkit-background-size: 100% 1px; -moz-background-size: 100% 1px; background-size: 100% 1px;
  background-image: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%), -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
  background-image: -moz-linear-gradient(left, #036B3A 0%, #53FEA2 100%), -moz-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
  background-image: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%), -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
  background-image: linear-gradient(to right, #036B3A 0%, #53FEA2 100%), linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
  color: #777777; text-decoration:none; }

.btn-ganolife_degrade {background:#ffffff;padding:10px;font-size:14px;color:#777777;width:100%;display:block;
                       border-bottom:1px solid #cdcdcd;margin-right:32px;}
.btn-ganolife_degrade:hover, .btn-ganolife_degrade:focus { background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
padding:10px; color: #ffffff; text-decoration:none;border-bottom:1px solid #ffffff;
}


.degrade_horizontal { background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
}

.check-green { background:#5EB825; width:38px; height:38px; top:10px; right:10px; position:absolute; background-size:100% 100%; border-radius:50%;
  text-align:center; }
.check-green i { width:20px; height:20px; margin:0 auto; margin-top:10px; background-size:cover; display:block;background-image:url("../../images/check-green.png"); }


.btn-success {
    color: #fff; margin-top: 20px; font-family: "Montserrat",sans-serif; background-color: #5EB825!important; border-color: #5EB825!important; }


.btn-ganolife {
background: #036B3A!important;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2))!important;
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 )!important;
font-family: 'Montserrat'!important; font-size:18px!important; border-radius:0px!important;border:0px solid rgba(0,0,0,0)!important;
padding-top:4px;padding-bottom: 4px; }
.btn-ganolife:hover, .btn-ganolife:focus { border-color: #ffffffimportant; } 

.btn-ganolife-perfil {
background: #036B3A!important;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2))!important;
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 )!important;
font-family:'Montserrat'!important;font-size:15px!important;border-radius:0px!important;border-color:#ffffff!important;padding-top:4px;padding-bottom:4px; }
  


.btn-ganolife3 {
background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
font-family: 'Montserrat'!important; font-size:22px; padding:20px; color:#ffffff; line-height:60px; }
.btn-ganolife3:hover, .btn-ganolife3:focus { color:#ffffff; text-decoration:none; }  


.btn-ganolife4 {
background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
font-family: 'Montserrat'!important; font-size:16px; padding:16px; color:#ffffff; line-height:60px; padding-left:30px;padding-right:30px;   }
.btn-ganolife4:hover, .btn-ganolife4:focus { color:#ffffff; text-decoration:none; }  



 /* 
.btn-ganolife {
  background: rgba(96,189,34,1)!important;
background: -moz-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(96,189,34,1)), color-stop(46%, rgba(96,189,34,1)), color-stop(58%, rgba(58,173,0,1)), color-stop(100%, rgba(58,173,0,1)))!important;
background: -webkit-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -o-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -ms-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: linear-gradient(to bottom, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#60bd22', endColorstr='#3aad00', GradientType=0 );
font-size: 18px !important; 
border-radius: 0; border-color: #5EB825 !important; padding-top: 4px; padding-bottom: 4px; }
  
.btn-ganolife-perfil {
  background: rgba(96,189,34,1)!important;
background: -moz-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(96,189,34,1)), color-stop(46%, rgba(96,189,34,1)), color-stop(58%, rgba(58,173,0,1)), color-stop(100%, rgba(58,173,0,1)))!important;
background: -webkit-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -o-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -ms-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: linear-gradient(to bottom, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#60bd22', endColorstr='#3aad00', GradientType=0 );font-size: 15px !important; 
border-radius: 4px!important; border-color: #5EB825 !important; padding-top: 4px; padding-bottom: 4px; }
  
.btn-ganolife:hover { border-color: #649219; background: #649219; }

.btn-ganolife3 {
  background-image:url("../../images/boton_verde.png"); font-size:22px; padding:20px; color:#ffffff; line-height:60px; background-size: 380px 64px;
    background-repeat: no-repeat;   }
.btn-ganolife3:hover { color:#ffffff; text-decoration:none; }  

.btn-ganolife4 {
  background-image:url("../../images/boton_verde.png"); font-size:16px; padding:16px; color:#ffffff; line-height:60px; background-size: 222px 50px;
    background-repeat: no-repeat; padding-left:30px;padding-right:30px;   }
.btn-ganolife4:hover { color:#ffffff; text-decoration:none; }  

.btn-ganolife5 {
  background-image:url("../../images/boton_verdeb.png"); font-size:22px; padding:20px; color:#ffffff; line-height:60px; background-size: 230px 64px;
    background-repeat: no-repeat; padding-left:30px;padding-right:30px;  }

.btn-ganolife6 {
  background-image:url("../../images/boton_verde.png"); font-size:16px; padding:16px; color:#ffffff; line-height:60px; background-size: 222px 50px;
    background-repeat: no-repeat; padding-left:30px;padding-right:30px;   }
*/
.btn-ganolife5 {
background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
font-family: 'Montserrat'!important; font-size:22px; padding:20px; color:#ffffff; line-height:60px; padding-left:30px;padding-right:30px;  }
.btn-ganolife5:hover, .btn-ganolife5:focus { color:#ffffff; text-decoration:none; } 

.btn-ganolife6 {
background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
font-family: 'Montserrat'!important; font-size:16px; padding:16px; color:#ffffff; line-height:60px; padding-left:30px;padding-right:30px;   }
.btn-ganolife6:hover, .btn-ganolife6:focus { color:#ffffff; text-decoration:none; }

.btn-ganolife7 {
  background-image:url("../../images/boton_verde.png"); font-family: 'Montserrat'!important; font-size:16px; padding:10px; color:#ffffff; line-height:34px; background-size: 170px 50px;
    background-repeat: no-repeat; padding-left:20px;padding-right:20px;   }
.btn-ganolife7:hover { color:#ffffff; text-decoration:none; }


.btn-ganolife8 {
background: #036B3A; width:50%; padding:11px; color:#ffffff; display:block!important;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 );
font-family: 'Montserrat'!important; font-size:16px; border-radius:0px!important;border:0px solid rgba(0,0,0,0);}
.btn-ganolife8:hover, .btn-ganolife8:focus { color:#ffffff; text-decoration:none; }

.btn-ganolife9 { width:50%; background:#555555; font-size:16px; border:0px solid #555555!important; padding:11px; color:#ffffff; display:block!important;}

.radio_button_plan_texto7 {text-align:center; margin-left:8px!important;margin-right:10px !important; font-size: 17px;}
.radio_button_plan_texto7 > input[type=radio]  {display:none;}
.radio_button_plan_texto7 > input[type=radio] + label {width:50px !important; padding-top:5px !important;  text-align:center; background:#999999; color:#ffffff;  
                                                      border: 0px solid #f7f7f7; min-height:36px; border-radius:6px; }  
.radio_button_plan_texto7 > input[type=radio]:checked + label,
.radio_button_plan_texto7:hover > input[type=radio]:checked + label {border: 0px solid #f7f7f7;min-height:36px; color:#ffffff;
background: #4c8bb9;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2));
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%);
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 ); }  
.radio_button_plan_texto7 > input[type=radio]:hover + label { min-height:36px; border-radius:6px; border:0px dashed #a2a2a2; }



/*
.btn-ganolife, .btn-ganolife--c1 { background: #5EB825; border-color: #5EB825; } 
.btn-ganolife--c1:hover { border-color: #649219; background: #649219; }
.btn-ganolife--c1:focus { border-color: #649219 !important; background: rgba(96,189,34,1)!important;
background: -moz-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(96,189,34,1)), color-stop(46%, rgba(96,189,34,1)), color-stop(58%, rgba(58,173,0,1)), color-stop(100%, rgba(58,173,0,1)))!important;
background: -webkit-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -o-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: -ms-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important;
background: linear-gradient(to bottom, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%)!important; }
*/

.btn-ganogrey {
  background: #d6d6d6;
  border-radius: 0; }

.custom-checkbox {
  /* Base for label styling */
  /* checkbox aspect */
  /* checked mark aspect */
  /* checked mark aspect changes */
  /* disabled checkbox */
  /* accessibility */
  /* hover style just for information */ }
  .custom-checkbox [type="checkbox"]:checked,
  .custom-checkbox [type="checkbox"]:not(:checked) {
    position: absolute;
    left: -9999px; }
  .custom-checkbox [type="checkbox"]:checked + label,
  .custom-checkbox [type="checkbox"]:not(:checked) + label {
    position: relative;
    padding-left: 25px;
    cursor: pointer; }
  .custom-checkbox [type="checkbox"]:checked + label:before,
  .custom-checkbox [type="checkbox"]:not(:checked) + label:before {
    content: '';
    position: absolute;
    left: 0;
    width: 17px;
    height: 17px;
    border: 1px solid #aaa;
    background: #f8f8f8;
    box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.3); }
  .custom-checkbox [type="checkbox"]:checked + label:after,
  .custom-checkbox [type="checkbox"]:not(:checked) + label:after {
    content: '✔';
    position: absolute;
    top: 0;
    left: 4px;
    font-size: 18px;
    line-height: 0.8;
    color: #555;
    transition: all 0.2s; }
  .custom-checkbox [type="checkbox"]:not(:checked) + label:after {
    opacity: 0;
    transform: scale(0); }
  .custom-checkbox [type="checkbox"]:checked + label:after {
    opacity: 1;
    transform: scale(1); }
  .custom-checkbox [type="checkbox"]:disabled:checked + label:before,
  .custom-checkbox [type="checkbox"]:disabled:not(:checked) + label:before {
    box-shadow: none;
    border-color: #bbb;
    background-color: #ddd; }
  .custom-checkbox [type="checkbox"]:disabled:checked + label:after {
    color: #999; }
  .custom-checkbox [type="checkbox"]:disabled + label {
    color: #aaa; }
  .custom-checkbox label:hover:before {
    border: 1px solid #888 !important; }

.btn-back {
  -moz-transform: rotate(-135deg);
  -o-transform: rotate(-135deg);
  -ms-transform: rotate(-135deg);
  -webkit-transform: rotate(-135deg);
  transform: rotate(-135deg);
  border-top: 1px solid grey;
  border-right: 1px solid grey;
  width: 10px;
  height: 10px;
  display: inline-block; }

.parent-step--grey {
  background: #E9E9E9; }

@media (min-width: 320px) and (max-width: 425px) {
  .step-wrapper .step-wrapper__items {
    text-align: center;
    padding: 5px 0 !important; }
    .step-wrapper .step-wrapper__items .resp {
      display: inline !important; }
    .step-wrapper .step-wrapper__items .nresp {
      display: none; } }

.step-wrapper .step-wrapper__items {
  padding: 30px 10px;
  text-align: center; }
  .step-wrapper .step-wrapper__items .items {
    padding-left: 0; }
    .step-wrapper .step-wrapper__items .items .active {
      color: #5EB825; }
    .step-wrapper .step-wrapper__items .items .resp {
      display: none; }
    .step-wrapper .step-wrapper__items .items li {
      list-style: none;
      display: inline-block;
      margin: 10px;
      vertical-align: middle;
      font-size: 16px; }
      .step-wrapper .step-wrapper__items .items li .separator {
        width: 15px;
        height: 15px;
        display: block;
        border-top: solid 1px grey;
        border-right: solid 1px grey; }
        .step-wrapper .step-wrapper__items .items li .separator, .step-wrapper .step-wrapper__items .items li .separator desktop {
          -moz-transform: rotate(45deg);
          -o-transform: rotate(45deg);
          -ms-transform: rotate(45deg);
          -webkit-transform: rotate(45deg);
          transform: rotate(45deg); }
        @media (min-width: 320px) and (max-width: 425px) {
          .step-wrapper .step-wrapper__items .items li .separator.down {
            -moz-transform: rotate(135deg);
            -o-transform: rotate(135deg);
            -ms-transform: rotate(135deg);
            -webkit-transform: rotate(135deg);
            transform: rotate(135deg); } }

.modal {
  text-align: center;
  padding: 0 !important; }

.modal:before {
  content: '';
  display: inline-block;
  height: 100%;
  vertical-align: middle;
  margin-right: -4px; }

.modal-dialog {
  display: inline-block;
  text-align: left;
  vertical-align: middle; }

.modal--home .modal-header {
  border: none;
  position: absolute;
  right: 15px;
  top: 10px;
  z-index: 1000; }

.modal--home .modal-body {
  padding: 0; }
  .modal--home .modal-body .body__select .select__title p {
    font-family: "Montserrat",sans-serif;
    font-size: 16px;
    font-weight: bold;
    margin: 0; }
  .modal--home .modal-body .body__select .select__countries .flag-icon {
    font-size: 20px; }
  .modal--home .modal-body .body__select ul {
    margin: 50px 0;
    padding: 0; }
    .modal--home .modal-body .body__select ul li {
      list-style: none;
      display: inline-block;
      width: 150px;
      margin: 5px; }
      .modal--home .modal-body .body__select ul li a {
        text-decoration: none;
        color: #555; }
      .modal--home .modal-body .body__select ul li span {
        margin-right: 8px; }
  .modal--home .modal-body .body__form {
    background: white;
    position: absolute;
    right: 0;
    top: 0;
    bottom: 0;
    padding-top: 50px !important;
    padding-bottom: 80px !important; }
    .modal--home .modal-body .body__form strong {
      margin: 0 5px; }
      .modal--home .modal-body .body__form strong a {
        color: #555; }
    .modal--home .modal-body .body__form ul.dropdown-menu {
      height: 220px; overflow: auto; }
      .modal--home .modal-body .body__form ul.dropdown-menu a span 
      {
          
          
        }


@media (-webkit-min-device-pixel-ratio:0){
.modal--home .modal-body .body__form .form-ganolife .list-c {
    padding: 8px;
}

}     
  

.caja_texto_posicion {  margin-top:-65px;  }
.ver_en_movil  { display: none;  }
.no_ver_en_movil2  { visibility: visible !important; } 
.no_ver_en_movil4  { visibility: visible !important; }  
.alinear_en_movil {text-align:left }
.mover_izquierda_2 {margin-left:100px!important }
.tabla_totales { width: 30% ;}
.tabla_totales2 { width: 50% !important;}
.alinear_derecha { text-align:right; padding:20px  }
.img_gratis { width: 18%;}
.minus { width: 40px !important;}
.plus { width: 40px !important;}
.radio_button_plan_texto > input[type=radio] + label {width:220px !important; padding-top:5px !important;  text-align:center; background:#f7f7f7;  
                                                      border: 1px solid #f7f7f7; border-width: 1.5px;  min-height:30px; border-radius:6px; }
.radio_button_plan_texto {text-align:center; margin-left:10px!important;margin-right:10px !important; font-size: 18px;}
.radio_button_plan_texto > label{margin-left:-40px;margin-top:-20px;}
.radio_button_plan_texto > input[type=radio]  {display:none;}  

.radio_button_plan_texto2 > input[type=radio] + label {width:220px !important; padding-top:5px !important;  text-align:center; background:#f7f7f7;  
                                                      border: 1px solid #f7f7f7; border-width: 1.5px;  min-height:30px; border-radius:6px; }
.radio_button_plan_texto2 {text-align:center; margin-left:10px!important;margin-right:10px !important; font-size: 18px;}
.radio_button_plan_texto2 > label{margin-left:-40px;margin-top:-20px;}
.radio_button_plan_texto2 > input[type=radio]  {display:none;} 


.radio_button_plan_texto3 {text-align:center; margin-left:8px!important;margin-right:10px !important; font-size: 17px;}
.radio_button_plan_texto3 > input[type=radio]  {display:none;}
.radio_button_plan_texto3 > input[type=radio] + label {width:50px !important; padding-top:5px !important;  text-align:center; background:#999999; color:#ffffff;  
                                                      border: 0px solid #f7f7f7; min-height:36px; border-radius:6px; }  
.radio_button_plan_texto3 > input[type=radio]:checked + label,
.radio_button_plan_texto3:hover > input[type=radio]:checked + label {border: 0px solid #f7f7f7;min-height:36px; color:#ffffff;
background: #036B3A; 
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2))!important;
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 )!important; }  
.radio_button_plan_texto3 > input[type=radio]:hover + label { min-height:36px; border-radius:6px; border:0px dashed #a2a2a2; }

.radio_button_plan_texto4 {text-align:center; margin-top:18px!important; margin-left:8px;margin-right:0px !important; }
.radio_button_plan_texto4 > input[type=radio]  {display:none;}
.radio_button_plan_texto4 > input[type=radio] + label {font-size: 15px;font-family: graviola_softmedium_italic; width:120px!important;color:#042842;
padding-top:8px!important;text-align:center; background: #d1d5d8;border: 0px solid #f7f7f7; min-height:36px;  border-radius:30px;  }  
.radio_button_plan_texto4 > input[type=radio]:checked + label,
.radio_button_plan_texto4:hover > input[type=radio]:checked + label {border: 0px solid #f7f7f7;min-height:36px; color:#042842;
background: #a4cde1; }  
.radio_button_plan_texto4 > input[type=radio]:hover + label { min-height:36px; border-radius:30px; border:0px dashed #a2a2a2; }

.radio_button_plan_texto5 > input[type=radio] + label { padding-left:34px !important; padding-top:5px!important; height:42px; text-align: left;
background-image: url("../../images/check_box_1_off.jpg")!important; background-repeat: no-repeat; font-weight:normal; }
.radio_button_plan_texto5 {text-align:center; margin-left:14px!important;margin-right:10px !important; }
.radio_button_plan_texto5 > input[type=radio]  {display:none;} 
.radio_button_plan_texto5 > input[type=radio]:checked + label,
.radio_button_plan_texto5:hover > input[type=radio]:checked + label {
background-image: url("../../images/check_box_1_on.jpg")!important; background-repeat: no-repeat;}



.check_button_plan_texto6 > input[type=checkbox] + label { padding-left:34px !important; padding-top:5px!important; height:42px; text-align: left;
background-image: url("../../images/check_box_1_off.jpg")!important; background-repeat: no-repeat; font-weight:normal; }
.check_button_plan_texto6 {text-align:center; margin-left:14px!important;margin-right:10px !important; }
.check_button_plan_texto6 > input[type=checkbox]  {display:none;} 
.check_button_plan_texto6 > input[type=checkbox]:checked + label,
.check_button_plan_texto6:hover > input[type=checkbox]:checked + label {
background-image: url("../../images/check_box_1_on.jpg")!important; background-repeat: no-repeat;}




#hwslider ul li:last-child{background: #F7F7F7; text-align: center;}
#hwslider ul li:last-child h4{height:42px; margin: 20% auto;font-size: 48px; color:#fff;}
.intro{position:absolute; left:15%; top:71%; width:42%; min-width: 240px; background: rgba(0,0,0,.5); 
       padding: 1px;z-index: 2; color: #fff;line-height: 26px}
#otherhwSlider ul li:first-child{background:#F7F7F7;text-align: center;}
#otherhwSlider pre{padding-top:10%;padding-left:15%;display:block;height:100%;background:#F7F7F7; color: #fff}
#otherhwSlider ul li:last-child{background:#F7F7F7;color:#fff; text-align: center;}

.btn-primary { color: #fff; background-color: #337ab7; border-color: #2e6da4 !important;}

.popup_ancho {width:600px; height:280px;}
.popup_ancho2 {width:720px; height:320px;}
.select_2 {width:100%; padding: 9px ; border-radius: 40px; font-size: 14px;font-family: graviola_softmedium; color:#58595B; 
           line-height: 11px; font-weight:bold; height:40px; border:solid 1px #d9d9d9 !important;}

.imagen-producto {width:400px; }
.imagen-producto2 {width:100%; }
.imagen-producto3 {width:100%; }
.imagen-header {width:100%; }



/*
.btn_comprar, .btn_comprar:hover {  
background: rgba(96,189,34,1);
background: -moz-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%);
background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(96,189,34,1)), color-stop(46%, rgba(96,189,34,1)), color-stop(58%, rgba(58,173,0,1)), color-stop(100%, rgba(58,173,0,1)));
background: -webkit-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%);
background: -o-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%);
background: -ms-linear-gradient(top, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%);
background: linear-gradient(to bottom, rgba(96,189,34,1) 0%, rgba(96,189,34,1) 46%, rgba(58,173,0,1) 58%, rgba(58,173,0,1) 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#60bd22', endColorstr='#3aad00', GradientType=0 );
padding:6px; border-radius:4px; margin-top:7px; text-decoration:none; }
.btn_comprar a { text-decoration: none!important;}
*/
.btn_comprar, .btn_comprar:hover, .btn_comprar:focus {  
background: #036B3A;
background: -moz-linear-gradient(left,  #036B3A 0%, #53FEA2 100%)!important;
background: -webkit-gradient(left top, right top, color-stop(0%, #036B3A), color-stop(100%, #53FEA2))!important;
background: -webkit-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: -o-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: -ms-linear-gradient(left, #036B3A 0%, #53FEA2 100%)!important;
background: linear-gradient(to right, #036B3A 0%, #53FEA2 100%)!important;
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#036B3A', endColorstr='#53FEA2', GradientType=1 )!important;
padding:6px; border-radius:4px; margin-top:7px; text-decoration:none; }

.btn_comprar a { text-decoration: none!important;}


.texto_signo {font-size: 48px;  font-weight: lighter;}
.imagen-signo {width:40px; }
.ancho_tabla_1 {width:80%; }

.drawer-footer { padding: 70px 15px!important; }

.ancho_1 {width:2%; float:left; display: list-item; color: rgba(0,0,0,0.0);}
.ancho_2 {width:18%; float:left; display: list-item; color: rgba(0,0,0,0.0);}
.ancho_3 {width:20%; float:left; margin-bottom:50px;}


.tooltip{ display: inline; position: relative!important; opacity: 1!important; width: 100%;z-index: 1!important;}

.tooltip:hover:after{  background: #333;  background: rgba(0,0,0,.75);  border-radius: 5px; bottom: 64px; color: #fff; content: attr(title); left: 0%;
    padding: 5px 15px; position: absolute; z-index: 1!important; width: 180px;}

.tooltip:hover:before{
    border: solid;
    border-color: #333 transparent;
    border-width: 8px 8px 0 8px;
    bottom: 56px;
    content: "";
    left: 10%;
    position: absolute;
    z-index: 1!important;
}

.tooltip3{ display: inline; position: relative!important; opacity: 1!important; width: 100%;z-index: 1!important;}
.tooltip3:hover:after{  background: #333;  background: rgba(0,0,0,.75); border-radius: 5px; bottom: 90px; color: #fff; content: attr(title); 
                        left: 0%; padding: 5px 15px; position: absolute; z-index: 1!important; width: 150px; text-align:center; font-size:12px;}
.tooltip3:hover:before{
    border: solid; border-color: #333 transparent; border-width: 8px 8px 0 8px; bottom: 84px; content: ""; left: 10%; position: absolute; z-index: 1!important;}



.tooltip_der{ display: inline; position: relative!important; opacity: 1!important; width: 100%;z-index: 1!important; font-size:12px; font-family:Arial;}

.tooltip_der:hover:after{  background: #333;  background: rgba(0,0,0,.75);  border-radius: 5px; bottom: 38px; color: #fff; content: attr(title); left: 0%;
    padding: 5px 15px; position: absolute; z-index: 1!important; width: 200px; margin-left:-40px;}
.tooltip_der:hover:before {
    border: solid;
    border-color: #333 transparent;
    border-width: 8px 8px 0 8px;
    bottom: 30px;
    content: "";
    left: 80%;
    position: absolute;
    z-index: 1!important;
}



@media (min-width: 426px) and (max-width: 768px) {
.imagen-producto2 {width:100%; max-width:380px; }
.imagen-producto3 {width:100%; max-width:640px; }
.imagen-header {width:100%; }
.wrapper-home .section-last { padding-top: 110px!important; background-position-x: 0px; background-position-y: -0px!important; min-height:400px!important;
background-image: url("../../images/banner3.jpg")!important; background-size: 900px 430px!important; }
.btn-ganolife5 { font-size: 22px!important; }
.ancho_1 {width:100%; float:left; display: list-item;}
.ancho_2 {width:100%; float:left; display: list-item;}
.ancho_3 {width:90%; float:left; margin-left:5%;margin-bottom:50px; }
                                                   
}   



@media (min-width: 1800px) and (max-width: 4500px) {
.modal--home .modal-body { height: 480px!important;} 
.wrapper-home .section-last2 { background-size: 3000px 660px!important; }
} 


@media (min-width: 120px) and (max-width: 320px)   {
.imagen-producto {width:220px!important; }    
    
}
    
    
@media (min-width: 320px) and (max-width: 425px) {

hr { margin: 10px!important;}
                        
.caja_texto_posicion {  margin-top:-52px;  }    
.ancho_texto_imagen_1 {width:340px!important; margin-top:88px!important;}

.wrapper-home .section-last { padding-top: 10px!important; background-position-x: -0px; background-position-y: -0px!important; min-height:600px!important;
                              background-image: url("../../images/banner3b.jpg")!important;  }
.wrapper-home .section-last2 { padding-top: 10px!important; background-position-x: -40px!important; background-position-y: -80px!important; min-height:470px!important;
                              background-image: url("../../images/banner2c.jpg")!important; background-size: 490px 560px!important; }
.wrapper-home .section-last3 { padding-top: 10px!important; background-position-x: -0px;  height:400px!important;
                              background-image: url("../../images/slider_detalles_productos.jpg")!important; background-size: 1700px 500px!important; }
.wrapper-home .section-last4 { padding-top: 10px!important; background-position-x: -0px;  height:400px!important;
                              background-image: url("../../images/slider_superalimentos.jpg")!important; background-size: 1700px 500px!important; }

.container { padding-left: 5px!important; padding-right: 5px!important; }
                               
.mover_izq3 {margin-left:-20px !important; }
.wrapper-home .section-last .message {text-align: center; }
.wrapper-home .section-last .container { text-align:left;width:100%; margin-left:10px; margin-top:150px;}
.wrapper-home .section-last .container .wrapper--btns {padding: 0; text-align: center!important; }

.wrapper-home .section-last2 .message {text-align: center; }
.wrapper-home .section-last2 .container { text-align:left;width:100%; margin-left:10px; margin-top:20px;}
.wrapper-home .section-last2 .container .wrapper--btns {padding: 0; text-align: center!important; }

.alineado_centro_tablet {text-align: center !important; }
.mover_izquierda_2 {margin-left:0px!important; }

.btn-ganolife6 {font-size:14px; padding:16px; color:#ffffff; line-height:60px; background-size: 130px 48px; padding-left:20px;padding-right:20px;   }

.btn-ganolife7 {font-size:14px; padding:16px; color:#ffffff; line-height:14px; background-size: 130px 44px; padding-left:10px;padding-right:50px;   }
.bajar_boton {position:absolute;margin-left:-240px; margin-top:90px; }
.ancho_tabla_1 {width:100%; margin-top:60px!important;}

.ancho_1 {width:100%; float:left; display: list-item;}
.ancho_2 {width:100%; float:left; display: list-item;}
.ancho_3 {width:90%; float:left; margin-left:5%;margin-bottom:50px; }

.imagen-producto {width:300px; }
.imagen-producto2 {width:100%; max-width:300px; }
.imagen-producto3 {width:100%; }
.imagen-header {width:100%; }
.popup_ancho {width:94%; height:340px;}
.popup_ancho2 {width:300px; height:620px; margin-top:48px;}
.popup_ancho h2 {font-size: 22px!important ;}

.select_2 {width:100%; padding: 9px ; border-radius: 40px; margin-bottom:10px; margin-top:-16px;}

.modal--home .modal-body .body__form .form-ganolife {text-align: center; }    
.modal--home .modal-content .body__form,
.modal--home .modal-content .body__select {padding: 20px 20px 2px !important; }
.caret {   margin-left: 40px!important;}
.margen_banderas  {margin-top: 10px!important; }
.no_ver_en_movil2  { display: none !important; }  
.ver_en_movil  { visibility: visible !important;  display: inline-block!important;} 
.altura_modal  { height:530px; } 
.bajar_en_tablet {margin-top:208px !important; }
.bajar_en_tablet2 {margin-top:50px !important; }
.subir_en_tablet3 {margin-top:-28px !important; }
.subir_en_tablet4 {margin-top:-38px !important;  margin-left:56px !important;}
.subir_en_tablet5 {margin-top:-58px !important; }
.subir_en_tablet6 {margin-top:-38px !important; }
.subir_en_tablet7 {margin-top:-14px !important; }
.form-ganolife2 {margin-top:-40px !important; }
.form-ganolife {margin-left:20px !important; }
.mover_izq2 {margin-left:-16px !important; }
.mover_izq4 {margin-left:12px !important; height: 90px!important;}
.mover_izq5 {margin-left:-45px !important; height: 190px; }
.mover_izq6 {margin-left:15px !important; margin-top:30px !important; }
.alinear_en_movil {text-align:center; }
.modal--home .modal-body .body__form ul.dropdown-menu {height: 220px; width:310px; margin-top:-40px !important; overflow: auto;}
.form__selects {bottom: 50px !important;}
.logopopup { display:none}
.texto_tablet2 { font-size:13px;}

.mover_izq6{ margin-left: 10px !important;}

.modal--home .modal-body .body__form .form-ganolife .form-ganolife { margin-top: 10px !important; }
.modal--home .modal-body .body__form .form-ganolife .btn-success { margin-left: 0 !important; padding: 5px 25px !important; margin-bottom: 10px;
          display: inline-block !important; float: none !important; } 
.modal--home .modal-body .body__form input, .modal--home .modal-body .body__form mobile-large input { width: 220px !important;margin-bottom:10px; }     
.modal--home .modal-body .body__form .form-ganolife .list-c { width: 220px !important; margin-right: 0px!important; text-align: left!important;  }
.form-group { margin-left:20px; margin-right:20px;}
.modal--home .modal-body .body__form .form-ganolife .btn-success { margin-left:-20px !important;}

.margen_radios_tablet  {margin-left: 28px!important; }
.margen_radios_tablet2  {margin-left: 58px!important; }
.radio_button_plan {text-align:center; margin-left:10px!important;margin-right:10px !important;}
.radio_button_plan > label{margin-left:-20px;margin-top:10px;}
.radio_button_plan > input[type=radio] + label {width:120px !important; padding-top:45px !important;  text-align:center; border: 1px solid #f7f7f7; 
                     border-width: 1.5px; min-height:100px!important; border-radius:6px; }  
.radio_button_plan > input[type=radio]:checked + label,
.radio_button_plan:hover > input[type=radio]:checked + label {border: 1px dashed #a2a2a2;border-width: 1.5px;
       background:url("../../images/icono_check.jpg") no-repeat;background-position: top right;min-height:100px!important; }  
.radio_button_plan > input[type=radio]:hover + label { min-height:100px!important; border-radius:6px; border: 1px dashed #a2a2a2; border-width: 1.5px;}



.radio_button_plan_2 {text-align:center; margin-left:10px!important;margin-right:10px !important;}
.radio_button_plan_2 > label{margin-left:-20px;margin-top:10px;}
.radio_button_plan_2 > input[type=radio] + label {width:120px !important; padding-top:15px!important;padding-bottom:10px!important;padding-left:10px!important; 
                     text-align:center; border: 1px solid #f7f7f7; border-width: 1.5px; min-height:70px!important; border-radius:6px; }  
.radio_button_plan_2 > input[type=radio]:checked + label,
.radio_button_plan_2:hover > input[type=radio]:checked + label {border: 1px dashed #a2a2a2;border-width: 1.5px;
       background:url("../../images/icono_check.jpg") no-repeat;background-position: top right;min-height:70px!important; }  
.radio_button_plan_2 > input[type=radio]:hover + label { min-height:70px!important; border-radius:6px; border: 1px dashed #a2a2a2; border-width: 1.5px;}



.radio_button_plan_texto {text-align:center; margin-left:8px!important;margin-right:10px !important; font-size: 15px;}
.radio_button_plan_texto > label{margin-left:-30px;margin-top:-20px;}
.radio_button_plan_texto > input[type=radio]  {display:none;}
.radio_button_plan_texto > input[type=radio] + label {width:140px !important; padding-top:5px !important;  text-align:center; background:#f7f7f7;  
                                                      border: 1px solid #f7f7f7; border-width: 1.5px;  min-height:30px; border-radius:6px; }  
.radio_button_plan_texto > input[type=radio]:checked + label,
.radio_button_plan_texto:hover > input[type=radio]:checked + label {border: 1px solid #f7f7f7;border-width: 1.5px;min-height:30px; }  
.radio_button_plan_texto > input[type=radio]:hover + label { min-height:30px; border-radius:6px; border: 1px dashed #a2a2a2; border-width: 1.5px;}

.radio_button_plan_texto2 {text-align:center; margin-left:8px!important;margin-right:10px !important; font-size: 15px;}
.radio_button_plan_texto2 > label{margin-left:-10px;margin-top:-20px;}
.radio_button_plan_texto2 > input[type=radio]  {display:none;}
.radio_button_plan_texto2 > input[type=radio] + label {width:90px !important; padding-top:5px !important;  text-align:center; background:#f7f7f7;  
                                                      border: 1px solid #f7f7f7; border-width: 1.5px;  min-height:30px; border-radius:6px; }  
.radio_button_plan_texto2 > input[type=radio]:checked + label,
.radio_button_plan_texto2:hover > input[type=radio]:checked + label {border: 1px solid #f7f7f7;border-width: 1.5px;min-height:30px; }  
.radio_button_plan_texto2 > input[type=radio]:hover + label { min-height:30px; border-radius:6px; border: 1px dashed #a2a2a2; border-width: 1.5px;}

.radio_button_plan_texto3 {text-align:center; margin-left:8px!important;margin-right:10px !important; font-size: 17px;}
.radio_button_plan_texto3 > input[type=radio]  {display:none;}
.radio_button_plan_texto3 > input[type=radio] + label {width:50px !important; padding-top:5px !important;  text-align:center; background:#999999; color:#ffffff;  
                                                      border: 0px solid #f7f7f7; min-height:36px; border-radius:6px; }  
.radio_button_plan_texto3 > input[type=radio]:checked + label,
.radio_button_plan_texto3:hover > input[type=radio]:checked + label {border: 0px solid #f7f7f7;min-height:36px; background:#5EB825; color:#ffffff;}  
.radio_button_plan_texto3 > input[type=radio]:hover + label { min-height:36px; border-radius:6px; border:0px dashed #a2a2a2; }



.margen_radios_tablet3 { margin-left: 8px!important;}

.imagensmall {width:90px; }
.imagen_1 { width: 50% !important;}
.imagen_2 { width: 66px !important;}

.logo { margin-left:-15px!important; }
header .navbar-header .responsive .logo img { opacity: 1;}

.minus { width: 25px !important;}
.plus { width: 25px !important;}

ul.desc__properties li span { margin-left: 3px!important; }
ul.desc__properties li img { width: 55px!important;}

.tabla_totales { width: 100% !important;}
.tabla_totales2 { width: 100% !important;}

.alinear_derecha { text-align:center; padding:20px  }
.img_gratis { width: 30%;}
.margenes_tablet { padding-right: 1px!important; padding-left: 1px!important;}


.hwslider { width: 80%!important; min-width: 230px!important;}
.hwslider ul li img { width: 260px !important; max-width: 100%!important; height: auto;  display: block; text-align: center; }
.hwslider ul li {  display: none;position: absolute; left: 0; top: 0; width: 100%; height: 100%; overflow: hidden; text-align: center; }
.intro { position: absolute;left: 0%;  min-width: 230px!important;background: rgba(0,0,0,.5); line-height: 26px;}
.main2{border:1px solid #d3d3d3; background:#F7F7F7; max-width:230px!important; text-align:center}
#hwslider ul li:last-child { background: none!important; text-align: center;}

.rw-ui-mobile-wrapper .rw-action-area .rw-mobile-action-area .rw-ui-mobile-stars {
    width: 200%!important; font-size: 18px !important; padding: 10px !important; padding-right: 30px !important; line-height: 40px !important; }

.btn-ganolife { font-size: 17px !important;  }
.wrapper-home .principal .principal__dialog .wrapper h3 { font-size: 30px!important; }

.dropdown-menu { width: 100%!important;padding-left: 4px!important;}
.menu_carrito_texto1 { font-size: 17px!important;}
           
}




@media (min-width: 120px) and (max-width: 320px) {

.ancho_texto_imagen_1 {width:260px!important; margin-top:98px!important;}
}




@media (min-width: 120px) and (max-width: 320px) {
.imagensmall {width:70px; }
.radio_button_plan > input[type=radio] + label {width:96px !important; padding-top:65px !important;  text-align:center; border: 1px solid #f7f7f7; border-width: 1.5px; 
       min-height:200px; border-radius:6px; }

.margen_radios_tablet { margin-left: 38px!important;}
.margen_radios_tablet3 { margin-left: 8px!important;}

h12 {font-size: 13px!important;}

}




@media (min-width: 769px) and (max-width: 1440px) {   
.form__selects {bottom: 50px }
.logopopup { display:none}

}



@media (min-width: 2500px) and (max-width: 4000px) {       
.modal--home .modal-body { height: 440px;}
}



@media (max-width: 320px) {
      .modal--home .modal-body .body__form .list-c,
      .modal--home .modal-body .body__form input {
        margin: 5px;
         width: 220px !important; } }
    .modal--home .modal-body .body__form .form-ganolife {
      margin-top: 50px;
      margin-left: 6px; }
      .modal--home .modal-body .body__form .form-ganolife .list-c,
      .modal--home .modal-body .body__form .form-ganolife input {
        display: inline-block; }
      .modal--home .modal-body .body__form .form-ganolife input {
        width: 220px; padding: 8px!important; height:38px !important; }
      .modal--home .modal-body .body__form .form-ganolife .btn,
      .modal--home .modal-body .body__form .form-ganolife .form-group {
        float: left; }
      .modal--home .modal-body .body__form .form-ganolife .btn-ganolife {
        margin-left: 6px;
        padding: 2px; }
        @media (min-width: 769px) and (max-width: 1440px) {
          .modal--home .modal-body .body__form .form-ganolife .btn-ganolife {
            clear: both;
            width: 150px;
            margin-left: 0;
            padding: 2px;
            margin-bottom: 20px; } }
      .modal--home .modal-body .body__form .form-ganolife .list-c {
        border: solid 1px #ccc;
        padding: 8px;
        position: relative; 
        margin-right:4px; height: 38px!important ;}
        .modal--home .modal-body .body__form .form-ganolife .list-c a {
          text-decoration: none;
          color: darkgray; }
    .modal--home .modal-body .body__form .form__selects {
      position: absolute;
      bottom: 10px;
      right: 0;
      left: 0; }
      .modal--home .modal-body .body__form .form__selects a {
        color: #333; }
      .modal--home .modal-body .body__form .form__selects a.dropdown-toggle {
        text-decoration: none; }
      .modal--home .modal-body .body__form .form__selects .link-ganolife {
        float: right; font-family: "Montserrat",sans-serif;
        text-decoration: underline; }
      @media (min-width: 320px) and (max-width: 425px) {
        .modal--home .modal-body .body__form .form__selects span {
          font-size: 12px !important; } }
      @media (max-width: 320px) {
        .modal--home .modal-body .body__form .form__selects span {
          font-size: 14px !important; } }

.modal--home .modal-dialog {
  width: 924px; }
  @media (min-width: 769px) and (max-width: 1024px) {
    .modal--home .modal-dialog {
      width: 85%; } }
  @media (min-width: 426px) and (max-width: 768px) {
    .modal--home .modal-dialog {
      width: 85%; }
      .modal--home .modal-dialog .body__form {
        position: relative; } }
  @media (min-width: 769px) and (max-width: 1440px) {
    .modal--home .modal-dialog {
      width: 80%; }
      .modal--home .modal-dialog .body__form {
        position: relative; } }
  @media (min-width: 320px) and (max-width: 425px) {
    .modal--home .modal-dialog {
      width: 90%; }
      .modal--home .modal-dialog .body__form {
        position: relative;
        padding-top: 10px !important; }
      .modal--home .modal-dialog .select__countries ul {
        width: 300px;
        margin: 0 auto; }
        .modal--home .modal-dialog .select__countries ul li {
          display: inline-block;
          width: 130px; } }
  @media (max-width: 320px) {
    .modal--home .modal-dialog {
      width: 300px; } }

.modal--home .modal-content .body__form,
.modal--home .modal-content .body__select {
  padding: 40px 20px 2px; }

.modal--home .modal-content .wrapper {
  background: #ffffff;
  border-radius: 0 !important; }

.modal:before {
  height: 100% !important; }

.align-right {
  text-align: right; }

.align-left {
  text-align: left; }

header {
  width: 100%;
  z-index: 999; }
  header .navbar-nav--top img {
    display: inline-block;
    width: 34px; }
  header .navbar-nav--top li a {
    text-transform: uppercase;
    font-size: 10px;
    display: inline-block;
    line-height: 32px; }
  header .navbar-header .no-responsive {
    display: block; }
    @media (min-width: 320px) and (max-width: 425px) {
      header .navbar-header .no-responsive {
         } }
  header .navbar-header .responsive {
     }
     
    


@media (min-width: 320px) and (max-width: 375px) {
     header .navbar-header .responsive a { margin: 5px 8px; }
}    
         
        
    @media (min-width: 375px) and (max-width: 425px) {
      header .navbar-header .responsive {
        display: block; } }
    header .navbar-header .responsive .logo img {
      width: 90px;
      opacity: 1; }
    header .navbar-header .responsive .responsive__opt {
      margin-top: 10px; }
    header .navbar-header .responsive a {
      display: inline-block;
      margin: 5px 6px;
      position: relative; }
      header .navbar-header .responsive a img {
        opacity: 0.6; }
      header .navbar-header .responsive a .badge {
        background: #5EB825;
        padding: 2px;
        position: absolute;
        top: -5px;
        right: -7px;
        font-size: 10px; }
    header .navbar-header .responsive .dropdown {
      display: inline-block; }
      header .navbar-header .responsive .dropdown ul {
        text-align: center;
        position: fixed;
        right: 0;
        top: 48px; }
        
        
header .navbar-nav--bottom { font-size: 15px; font-family: 'Montserrat'; font-weight: bold;}



    header .navbar-nav--bottom .active a {
      color: #5EB825 !important;
      background: transparent !important; }
  header .wrapper {
    overflow: inherit; }
  header .flag-icon--caret {
    margin: 0 5px; }
  header .navbar-toggle.collapsed {
    float: left;
    margin-left: 10px;
    border-radius: 0;
    z-index: 100; }
  header .navbar-brand {
    overflow: inherit;
    padding: 0;
    position: absolute;
    bottom: 0;
    cursor: pointer; }
    @media (min-width: 320px) and (max-width: 425px) {
      header .navbar-brand {
        width: 100%;
        display: block;
        text-align: center; }
        header .navbar-brand img {
          margin: 0 auto; } }
          
          

          
@media (min-width: 426px) and (max-width: 768px) {     
header .navbar-brand { margin-bottom: 0px; width: 38px; overflow: hidden; } 
.no_ver_en_movil4 { display: none!important; } 
header .navbar-nav--top li a { font-size: 8px; }  
.menu_1 { height:10px;}  
.menu_1 .logo_menu_1 { display: none;}    
.ocultar_en_movil { display: none;} 
}
        

@media (max-device-width: 1200px) and (orientation : portrait) {
.no_ver_en_movil4 { display: none!important; }   
.ver_en_movil { visibility: visible !important;  display: inline-block!important;}  
 
}
       
@media (max-device-width: 1200px) and (orientation : landscape)      {
.ver_en_movil { visibility: visible !important;  display: inline-block!important;} 
.no_ver_en_movil2 { display: none!important; }  
}      
       
/*  Estilos para tablet 768 / 1024*/ 
@media (min-width: 426px) and (max-width: 768px) {
   
.ver_en_movil { visibility: visible !important;  display: inline-block!important;}    
.no_ver_en_movil2 { display: none!important; }   
.tabla_totales {width: 100% !important;}
}        

@media (min-width: 769px) and (max-width: 1200px) {

.ver_en_movil { display: none;}
.titulo_7 { font-size: 22px;}
}  


@media (min-width: 1200px) and (max-width: 2200px) {
.ver_en_movil { display: none;}

}  





        
  header .nav-bang {
    background-color: #5EB825;
    border-radius: 50%;
    color: white;
    display: block;
    font-size: 16px;
    font-weight: 600;
    height: 20px;
    line-height: 18px;
    position: absolute;
    right: -5px;
    text-align: center;
    top: 20px;
    width: 20px; }
    header .nav-bang span {
      vertical-align: middle; }
  header .navbar--custom {
    background-color: white;
    border-radius: 0;
    border: none;
    margin-bottom: 0;
    box-shadow: 0 6px 6px -6px rgba(0, 0, 0, 0.5);
    z-index: 5; }
  header .dropdown-menu--cart {
    padding: 40px; }
    header .dropdown-menu--cart .img img {
      width: 160px;
      margin: 0 60px; }
      @media (min-width: 320px) and (max-width: 425px) {
        header .dropdown-menu--cart .img img {
          width: 80px; } }
    header .dropdown-menu--cart p {
      color: #333333;
      text-align: center;
      font-size: 18px; }
    header .dropdown-menu--cart p {
          font-size: 16px; } 

    header .dropdown-menu--cart .btn {
      margin: 0 auto;
      display: block; }
  header .dropdown-menu--black {
    background: #ffffff;
    border-radius: 0; }
    header .dropdown-menu--black li {
      margin: 5px; }
      header .dropdown-menu--black li a {
        color: #333333; }
        header .dropdown-menu--black li a .flag-icon {
          margin-right: 6px; }
        header .dropdown-menu--black li a:hover {
          color: #22A462;
          background: transparent; }

.drawer-nav {
  padding: 0 !important; }
  .drawer-nav li {
    text-transform: uppercase; }

.drawer-footer {
  position: fixed !important;
  bottom: 0; }
  .drawer-footer img {
    width: 20px; }

.header--fixed {
  height: 100px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .header--fixed {
      height: 50px; } }
  .header--fixed nav {
    width: 100%;
    position: fixed; }
  .header--fixed:before {
    content: "";
    position: relative;
    display: block; }
  .header--fixed .navbar-brand {
    padding-top: 4px; }

.green-line {
  height: 50px;
  background: #5EB825;
  width: 100%;
  clear: both;
  position: absolute;
  bottom: 0; }

.clear {
  clear: both; }

.categories span {
  cursor: pointer; }

.dinamyc-desc p {
  text-align: justify; }

ul.desc__properties {
  clear: both;
  margin: 0;
  padding: 0;
  text-align: left; }
  ul.desc__properties .img {
    border-radius: 50%;
    display: inline-block;
    overflow: hidden;
    vertical-align: middle; }
  ul.desc__properties span {
    display: inline-block;
    vertical-align: middle; }
  ul.desc__properties li {
    list-style: none; }
    ul.desc__properties li img {
      width: 80px; }
    ul.desc__properties li span {
      margin-left: 15px; }
  @media (min-width: 320px) and (max-width: 425px) {
    ul.desc__properties {} }

.group_items {
  text-align: center;
  min-height: 25px;
  max-height: 50px;
   }
  .group_items span {
    border-color: transparent;
    font-style: normal;
    vertical-align: middle; }
    
    .group_items a {
    color: #5EB825 !important; }
    .group_items a:hover, .group_item a:active  {
    color: #84aa46 !important; }
    
    
    
    
  .group_items i {
    height: 20px;
    width: 20px;
    display: inline-block;
    border: solid 1px transparent;
    border-radius: 4px;
    vertical-align: middle; }
  .group_items .subcategory {
    cursor: pointer; }
  .group_items .subcategory.active i:before {
    content: '';
    border-radius: 5px;
    display: block;
    width: 18px;
    height: 18px;
    border: solid 1px white; }
  .group_items .black {
    background: black; }
  .group_items .candy {
    background: #603913; }
  .group_items .latte {
    background: #a67c52; }
  .group_items .green {
    background: #5EB825; }
  .group_items .pink {
    background: pink; }

.group_items--block {
  text-align: justify; }
  .group_items--block .subcategory--block {
    display: block; }
  .group_items--block .subcategory {
    font-size: 18px; }
    .group_items--block .subcategory i {
      margin-right: 8px;
      width: 22px;
      height: 22px; }
      .group_items--block .subcategory i:before {
        width: 17px;
        height: 17px;
        margin: 1px; }

.green-line--footer {
  height: auto !important;
  padding: 15px 0;
  position: relative !important; }
  .green-line--footer p {
    text-align: center !important;
    color: white;
    font-size: 30px; }
    .green-line--footer p span {
      display: block;
      font-size: 16px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .green-line--footer .col-xs-6 p {
      font-size: 17px; }
      .green-line--footer .col-xs-6 p span {
        font-size: 13px; } }





.wrapper-home { height: 100%; }
  
.wrapper-home .principal { height: 100%; min-height: 990px; position: relative; background: url("../../images/slider.jpg");
 background-size: cover;  background-repeat: no-repeat; }
    
.wrapper-home .secreto { height: 100%; min-height: 690px!important; position: relative; background: url("../../images/slider_secreto.jpg")!important;
 background-size: cover;  background-repeat: no-repeat; background-position: -400px -32px!important;}   
.ancho_tabla_slider { width: 60%;  }

   
.wrapper-home .productos { height: 100%; min-height: 390px!important; position: relative; background: url("../../images/slider_productos.jpg")!important;
 background-size: cover;  background-repeat: no-repeat; background-size: 1460px 620px!important; background-position: 0px 40px;}  
 
   
@media (min-width: 862px) and (max-width: 1024px) {
.wrapper-home .secreto { background-position: -460px -32px!important;} 
.ancho_tabla_slider { width: 90%;  }
}

@media (min-width: 712px) and (max-width: 768px) {
.wrapper-home .secreto { height: 100%; min-height: 690px!important; position: relative; background: url("../../images/slider_secreto.jpg")!important;
 background-size: cover;  background-repeat: no-repeat; background-position: -660px -32px!important;} 
.ancho_tabla_slider { width: 90%;  }
}
 
@media (min-width: 320px) and (max-width: 425px) {
.wrapper-home .principal { background-size: cover; background-position: center center; } 
.wrapper-home .secreto { height: 100%; min-height: 690px!important; position: relative; background: url("../../images/slider_secreto.jpg")!important;
 background-size: cover;  background-repeat: no-repeat; background-position: -1100px -32px!important;  }     
.ancho_tabla_slider { width: 80%;  }
}

@media (min-width: 376px) and (max-width: 425px) {
.wrapper-home .productos { height: 100%; min-height: 460px!important; background-size: 425px 460px!important;}
}
@media (min-width: 321px) and (max-width: 375px) {
.wrapper-home .productos { height: 100%; min-height: 460px!important; background-size: 375px 460px!important;}
}
@media (min-width: 100px) and (max-width: 320px) {
.wrapper-home .productos { height: 100%; min-height: 460px!important; background-size: 320px 460px!important;}
}





.wrapper-home .principal .principal__dialog { position: absolute; right: 0; width: 100%;  bottom: 200px; }
      
   
      
@media (min-width: 426px) and (max-width: 768px) {
.popup_ancho2 {width:700px; height:660px; margin-top:48px;}
}
      
      
            
      
.wrapper-home .principal .principal__dialog .wrapper { position: relative;  background: rgba(0, 0, 0, 0.0); color: white;
        top: 1em; margin: 0 auto; padding: 30px; text-align:left; }
        
.wrapper-home .principal .principal__dialog .wrapper, 
.wrapper-home .principal .principal__dialog .wrapper laptop, 
.wrapper-home .principal .principal__dialog .wrapper tablet { left: -15em; width: 650px; }
          
.wrapper-home .principal .principal__dialog .wrapper h3 {margin:0;font-size:42px;font-family:"Montserrat",sans-serif;text-shadow:2px 2px rgba(0, 0, 0, 0.4);}        
           
          
          
          
          
          
        @media (min-width: 769px) and (max-width: 1024px) {
          .wrapper-home .principal .principal__dialog .wrapper {
            bottom: 50px; } }
        @media (min-width: 426px) and (max-width: 768px) {
          .wrapper-home .principal .principal__dialog .wrapper {
            bottom: 50px;
            width: 500px;
            left: 100px; } }
        @media (min-width: 320px) and (max-width: 425px) {
          .wrapper-home .principal .principal__dialog .wrapper {
            left: 0;
            width: 350px; } }
        .wrapper-home .principal .principal__dialog .wrapper p {
          font-family: "Montserrat",sans-serif;
          font-weight: bold;
          font-size: 20px;
          color: #ccc; }
          
          
          @media (min-width: 320px) and (max-width: 425px) {
            .wrapper-home .principal .principal__dialog .wrapper p {
              font-size: 16px; } }
              
              
       
          
          
         
        .wrapper-home .principal .principal__dialog .wrapper img {
          width: 70px; }
          @media (min-width: 320px) and (max-width: 425px) {
            .wrapper-home .principal .principal__dialog .wrapper img {
              width: 50px; } }
  .wrapper-home .section {
    text-align: center;
    min-height: 650px;
    position: relative;
    background: white; }
    .wrapper-home .section, .wrapper-home .section mobile {
      overflow: hidden; }
  .wrapper-home .ball-wrapper {
    margin-bottom: 25px; }
    .wrapper-home .ball-wrapper .subtitle {
      font-size: 20px;
      text-transform: uppercase;
      width: 180px;
      margin: 0 auto; }
  .wrapper-home .section--bggrey {
    background: #f7f7f7; }
  .wrapper-home .section-clock {
    color: black;
    padding-top: 120px;
    background-size: cover;
    background-repeat: no-repeat;
    background-image: url("../../images/history-layer.png"); }
    .wrapper-home .section-clock .justify {
      text-align: justify;
      font-size: 18px;
      font-family: "Montserrat",sans-serif;
      color: #222;
      font-weight: bolder; }
    .wrapper-home .section-clock .container-pad {
      padding: 0 50px; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-home .section-clock .container-pad {
          padding: 0 20px; } }
    .wrapper-home .section-clock .clock img {
      width: 80px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-clock .clock .h3 {
        font-size: 35px; } }
    .wrapper-home .section-clock, .wrapper-home .section-clock mobile {
      padding-top: 60px;
      padding-bottom: 60px; }
    @media (min-width: 1441px) {
      .wrapper-home .section-clock {
        padding-top: 180px; } }
    @media (min-width: 769px) and (max-width: 1440px) {
      .wrapper-home .section-clock {
        padding-top: 150px; } }
  .wrapper-home .section-superfoods {
    padding-top: 60px;
    background: #5EB825;
    color: white; }
    .wrapper-home .section-superfoods .superfoods__title {
      font-size: 40px;
      font-family: 'Shadows Into Light', cursive; }
    .wrapper-home .section-superfoods .container {
      text-align: justify;
      font-family:"Montserrat",sans-serif;
      font-weight: bold; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-home .section-superfoods .container {
          padding: 0; }
          .wrapper-home .section-superfoods .container .text {
            margin-top: 6px;
            font-size: 14px;
            text-align: center; } }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-superfoods {
        padding-top: 15px; } }
    @media (min-width: 769px) and (max-width: 1440px) {
      .wrapper-home .section-superfoods {
        padding-top: 80px; } }
    @media (min-width: 1441px) {
      .wrapper-home .section-superfoods {
        padding-top: 120px; } }
    .wrapper-home .section-superfoods .section-products .wrap {
      border-radius: 50%;
      overflow: hidden;
      width: 100%; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-home .section-superfoods .section-products .wrap {
          width: 60px;
          margin: 10px; }
          .wrapper-home .section-superfoods .section-products .wrap img {
            width: 60px;
            height: 60px;
            margin: 0; } }
    .wrapper-home .section-superfoods .text {
      margin-top: 11px;
      font-size: 17px;
      font-weight: bolder; }
  @media (min-width: 769px) and (max-width: 1440px) {
    .wrapper-home .section-formula {
      padding-top: 5%; } }
  @media (min-width: 1441px) {
    .wrapper-home .section-formula {
      padding-top: 140px; } }
  .wrapper-home .section-formula .h3 {
    font-family: "Montserrat",sans-serif;
    font-size: 25px;
    margin-top: 120px;
    clear: both;
    margin-top: 30px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-formula .h3 {
        margin-top: -25px;
        margin-bottom: -5px; } }
  .wrapper-home .section-formula .formula__title {
    margin-top: 70px;
    font-weight: bold;
    color: black; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-formula .formula__title {
        margin-top: 20px; } }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-home .section-formula .circle__item {
      height: 140px !important; } }
  .wrapper-home .section-formula .description {
    font-size: 20px;
    font-family: "Montserrat",sans-serif;
    font-weight: bolder;
    padding: 0 70px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-formula .description {
        font-size: 16px;
        font-weight: bold; } }
    .wrapper-home .section-formula .description, .wrapper-home .section-formula .description mobile-small {
      padding: 0; }
    .wrapper-home .section-formula .description p {
      margin: 0;
      display: inline-block; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-home .section-formula .description p {
          display: block; } }
    .wrapper-home .section-formula .description .green {
      color: #5EB825;
      font-family: "Montserrat",sans-serif; }
  .wrapper-home .section-formula .plus-container {
    height: 260px;
    display: table; }
    .wrapper-home .section-formula .plus-container .plus {
      display: table-cell;
      vertical-align: middle;
      font-size: 25px;
      color: black; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-home .section-formula .plus-container .plus {
          display: inline-block;
          text-align: center; } }
    .wrapper-home .section-formula .plus-container .eq, .wrapper-home .section-formula .plus-container .eq mobile-small {
      display: none !important; }
    .wrapper-home .section-formula .plus-container .eq, .wrapper-home .section-formula .plus-container .eq laptop, .wrapper-home .section-formula .plus-container .eq desktop {
      opacity: 1;
      display: table-cell !important; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-formula .plus-container {
        height: 55px;
        display: block;
        text-align: center; } }
  .wrapper-home .section-formula .equal {
    display: table-cell;
    vertical-align: middle; }
    .wrapper-home .section-formula .equal h3 {
      margin-bottom: 0;
      font-weight: bold;
      font-family: "Montserrat",sans-serif; }
    .wrapper-home .section-formula .equal .btn-ganolife {
      margin-top: 10px;
      font-size: 20px;
      padding: 6px 40px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-formula .equal {
        display: inline-block;
        margin: -60px auto 0;
        padding-top: 0 !important; } }
    .wrapper-home .section-formula .equal, .wrapper-home .section-formula .equal laptop {
      padding-top: 60px; }
  @media (min-width: 426px) and (max-width: 768px) {
    .wrapper-home .section-formula .ball h4 {
      font-size: 22px; } }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-home .section-formula .ball h4 {
      font-size: 16px; } }
  @media (max-width: 320px) {
    .wrapper-home .section-formula .ball h4 {
      font-size: 12px; } }
  @media (min-width: 426px) and (max-width: 768px) {
    .wrapper-home .section-formula .ball .circle__item {
      height: 260px; } }
  .wrapper-home .section-formula .ball .circle__item span.parentesis {
    font-size: 16px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-home .section-formula .ball .circle__item span.parentesis {
      font-size: 8px; } }
  @media (max-width: 320px) {
    .wrapper-home .section-formula .ball .circle__item span.parentesis {
      font-size: 6px; } }
  .wrapper-home .section-formula .ball:last-child, .wrapper-home .section-formula .ball:last-child mobile {
    margin-bottom: 10px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-home .section-formula .ball.plus-container {
      margin-top: 54px; } }
  .wrapper-home .section-products .wrapper .img {
    display: inline-block; }
  .wrapper-home .section-routine {
    padding-top: 100px;
    background: white; }
    .wrapper-home .section-routine .wrapper-desc {
      color: #555; }
    @media (min-width: 769px) and (max-width: 1440px) {
      .wrapper-home .section-routine {
        padding-top: 120px; } }
    @media (min-width: 1441px) {
      .wrapper-home .section-routine {
        padding-top: 140px; } }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-routine {
        padding-top: 5px; }
        .wrapper-home .section-routine .container {
          padding: 0; }
          .wrapper-home .section-routine .container .routine__group h3 {
            font-size: 20px; }
          .wrapper-home .section-routine .container .routine__group span {
            font-size: 14px; }
        .wrapper-home .section-routine .wrapper-desc {
          color: #555;
          clear: both;
          
          width: 80%;
          margin: 0 30px; }
          .wrapper-home .section-routine .wrapper-desc h3 {
            margin: 0; } }
    .wrapper-home .section-routine .container {
      margin: 0 auto; }
    .wrapper-home .section-routine .active {
      color: #5EB825; }
    .wrapper-home .section-routine .wrapslider {
      position: relative; }
      .wrapper-home .section-routine .wrapslider .back,
      .wrapper-home .section-routine .wrapslider .next {
        position: absolute;
        top: 45%;
        width: 15px;
        height: 15px;
        cursor: pointer; }
      .wrapper-home .section-routine .wrapslider .slick-disabled {
        display: none !important; }
      .wrapper-home .section-routine .wrapslider .back {
        left: -10px;
        border-top: solid 2px grey;
        border-left: solid 2px grey;
        -moz-transform: rotate(-45deg);
        -o-transform: rotate(-45deg);
        -ms-transform: rotate(-45deg);
        -webkit-transform: rotate(-45deg);
        transform: rotate(-45deg); }
      .wrapper-home .section-routine .wrapslider .next {
        right: -10px;
        border-top: solid 1px grey;
        border-left: solid 1px grey;
        -moz-transform: rotate(135deg);
        -o-transform: rotate(135deg);
        -ms-transform: rotate(135deg);
        -webkit-transform: rotate(135deg);
        transform: rotate(135deg); }
    .wrapper-home .section-routine .slider {
      height: 250px;
      width: 350px;
      background: #E9E9E9;
      margin: 0 auto;
      overflow: hidden; }
      .wrapper-home .section-routine .slider .slick-list,
      .wrapper-home .section-routine .slider .slick-track {
        height: 100% !important; }
      .wrapper-home .section-routine .slider .slick-slide:focus {
        border-color: transparent !important; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-home .section-routine .slider {
          width: 290px; } }
      .wrapper-home .section-routine .slider .item {
        height: 100%;
        width: 100%;
        background-size: 100% 100% !important; }
    .wrapper-home .section-routine .routine__group {
      margin-top: 2px; }
      .wrapper-home .section-routine .routine__group span {
        border-right: solid 1px;
        padding: 2px 6px;
        border-color: #ccc;
        font-weight: bold;
        font-size: 14px; }
        .wrapper-home .section-routine .routine__group span:last-child {
          border-color: transparent; }
      @media (min-width: 426px) and (max-width: 768px) {
        .wrapper-home .section-routine .routine__group {
          text-align: center; } }
    .wrapper-home .section-routine .list .list-title {
      color: black;
      font-family: "Montserrat" !important;
      overflow: hidden;
      margin-bottom: 15px; }
      .wrapper-home .section-routine .list .list-title .left {
        float: left; }
      .wrapper-home .section-routine .list .list-title .rigth {
        float: right; }
    .wrapper-home .section-routine h3 {
      font-family: "Montserrat" !important;
      font-size: 22px;
      font-weight: bolder; }
    .wrapper-home .section-routine .btn-wrapper {
      margin: 0 30px;
      clear: both;
      margin-bottom: 30px;
      margin-top: 25px; }
      .wrapper-home .section-routine .btn-wrapper .btn {
        margin-top: 8px; margin-bottom: 18px; }
        
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-home .section-routine .btn-wrapper {
          margin-top: 0;
          margin-bottom: 5px;
          overflow: hidden; }
          
          .img_tablet {
          width:60% !important; }
           }
           

  
@media (max-width: 1024px)   {
.wrapper-home .section-last {padding-top: 220px; background-position-x: -310px;background-position-y: 0px!important; } 
.wrapper-home .section-last2 {padding-top: 220px; background-position-x: -310px; }
.wrapper-home .section-last3 {padding-top: 220px; background-position-x: -310px; }
.wrapper-home .section-last4 {padding-top: 220px; background-position-x: -310px; } 
}

@media (max-width: 800px)   {
.wrapper-home .section-last { padding-top: 220px; background-position-x: -400px;} 
.wrapper-home .section-last2 { padding-top: 220px; background-position-x: -400px;} 
.wrapper-home .section-last3 { padding-top: 220px; background-position-x: -400px;} 
.wrapper-home .section-last4 { padding-top: 220px; background-position-x: -400px;} 
.mover_izq3 {margin-left:-220px !important; }

}





.ancho_texto_imagen_1 {width:440px; margin-top:-65px;margin-right:5px }

.wrapper-home .section-last .message { font-size: 20px; margin: 5px 0; }     
.wrapper-home .section-last { background-image: url("../../images/banner3.jpg"); background-position: 0px -140px; 
    background-size: cover; background-repeat: no-repeat; height: 320px; padding-top: 150px; font-family: "Montserrat" !important;   }
    
.wrapper-home .section-last2 { background-image: url("../../images/banner2.jpg"); background-position: 0px -20px;  width:100%;
    background-repeat: no-repeat; height: 350px; padding-top: 110px; font-family: "Montserrat" !important; background-size: 1700px 380px; }
.wrapper-home .section-last3 { background-image: url("../../images/slider_detalles_productos.jpg"); background-position: 0px -10px; text-align:center;
    background-repeat: no-repeat; height: 380px; padding-top: 10px; font-family: "Montserrat" !important; background-size: 1700px 460px; }
.wrapper-home .section-last4 { background-image: url("../../images/slider_superalimentos.jpg"); background-position: 0px -10px; text-align:center;
    background-repeat: no-repeat; height: 380px; padding-top: 10px; font-family: "Montserrat" !important;  }

.wrapper-home .section-last5 { background-image: url("../../images/slider_secreto2.jpg"); background-position: 0px -10px; text-align:center;
    background-repeat: no-repeat; height: 380px; padding-top: 10px; font-family: "Montserrat" !important;  }
.wrapper-home .section-last6{ background-image: url("../../images/slider_secreto3.jpg"); background-position: 0px -10px; text-align:center;
    background-repeat: no-repeat; height: 380px; padding-top: 10px; font-family: "Montserrat" !important;  }
    
    
    
.wrapper-home .section-last h3,
.wrapper-home .section-last2 h3,
.wrapper-home .section-last3 h3, .wrapper-home .section-last4 h3 { font-size: 34px; font-family: "Montserrat" !important; text-shadow: 2px 2px  rgba(0, 0, 0, 0.4);}  
.wrapper-home .section-last3, .wrapper-home .section-last4 { font-size: 14px; text-shadow: 1px 1px  rgba(0, 0, 0, 0.7);}       
.imagen_1 {width:70% !important; margin-bottom:10px}
.nav > li {  position: relative !important; display: inline-block !important; }
.nav-tabs > li { float:none !important; margin-bottom: -1px;}


.plan_icono1 { background: url("../images/365_1.jpg") no-repeat;  background-position: bottom center; padding-top:200px; }
.plan_icono2 { background: url("../images/365_2.jpg") no-repeat;  background-position: bottom center; padding-top:100px; }
.plan_icono3 { background: url("../images/365_3.jpg") no-repeat;  background-position: bottom center; padding-top:200px; }
.plan_icono4 { background: url("../images/365_4.jpg") no-repeat;  background-position: bottom center; padding-top:200px; }

.plan_icono5 { background: url("../images/365_5.jpg") no-repeat;  background-position: bottom center; padding-top:200px; }
.plan_icono6 { background: url("../images/365_6.jpg") no-repeat;  background-position: bottom center; padding-top:200px; }
.plan_icono7 { background: url("../images/365_7.jpg") no-repeat;  background-position: bottom center; padding-top:200px; }

input[type=checkbox] { height:25px; width:25px; margin:10px; padding:5px; color: #fafafa !important; }

.radio_button_plan > input[type=radio] {visibility: hidden}
.radio_button_plan {text-align:center; margin-left:-20px;margin-right:30px !important;}
.radio_button_plan > label{margin-left:-20px;margin-top:10px;}
.radio_button_plan > input[type=radio] + label {width:200px; padding-top:45px; text-align:center; border: 1px solid #f7f7f7; border-width: 1.5px; 
       min-height:200px; border-radius:6px; }  
.radio_button_plan > input[type=radio]:checked + label,
.radio_button_plan:hover > input[type=radio]:checked + label {border: 1px dashed #a2a2a2;border-width: 1.5px;
       background:url("../../images/icono_check.jpg") no-repeat;background-position: top right;min-height:200px; }  
.radio_button_plan > input[type=radio]:hover + label { min-height:200px; border-radius:6px; border: 1px dashed #a2a2a2; border-width: 1.5px;}

.radio_button_plan_2 > input[type=radio] {visibility: hidden}
.radio_button_plan_2 {text-align:center; margin-left:-20px;margin-right:30px !important;}
.radio_button_plan_2 > label{margin-left:-20px;margin-top:10px;}
.radio_button_plan_2 > input[type=radio] + label {width:200px; padding-top:20px;padding-bottom:15px; text-align:left; border: 1px solid #f7f7f7; 
       border-width: 1.5px;  min-height:30px; border-radius:6px; padding-left:20px;}  
.radio_button_plan_2 > input[type=radio]:checked + label,
.radio_button_plan_2:hover > input[type=radio]:checked + label {border: 1px dashed #a2a2a2;border-width: 1.5px;
       background:url("../../images/icono_check.jpg") no-repeat;background-position: top right;min-height:30px; }  
.radio_button_plan_2 > input[type=radio]:hover + label { min-height:30px; border-radius:6px; border: 1px dashed #a2a2a2; border-width: 1.5px;}


.link_productos, .link_productos a, .link_productos a:hover { font-size:11px !important; color:#444444; text-decoration:none!important;line-height:12px;}  
.link_productos { text-decoration:none!important; border:1px solid #cdcdcd; } 
.link_productos:hover { text-decoration:none!important; border:1px solid #777777; } 


    
@media (min-width: 426px) and (max-width: 768px) {
     .wrapper-home .section-last .message  { text-align: center; } 
     }
      
@media (min-width: 320px) and (max-width: 425px) {
    .wrapper-home .section-last .message { font-size: 16px !important; } }
    .wrapper-home .section-last .message--gren { color: #5EB825; }
    .wrapper-home .section-last .wrapper { margin-top: 15px; text-align: center; }
    .wrapper-home .section-last a { font-family: "Montserrat" !important; }
      @media (min-width: 426px) and (max-width: 768px) {
        .wrapper-home .section-last a {
          font-size: 25px; margin-top: 40px; } }
    @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-home .section-last .container .message { font-size: 18px; }
        .wrapper-home .section-last .container .wrapper--btns {
          padding: 0; text-align: left; } }
          
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-home .section-last .container .wrapper--btns .btn-ganolife span {
        display: block !important; } }
    .wrapper-home .section-last .container .wrapper--btns, .wrapper-home .section-last .container .wrapper--btns laptop, .wrapper-home .section-last .container .wrapper--btns desktop {
      float: none;
      margin: 0 auto; }
      .wrapper-home .section-last .container .wrapper--btns .btn-ganolife, .wrapper-home .section-last .container .wrapper--btns laptop .btn-ganolife, .wrapper-home .section-last .container .wrapper--btns desktop .btn-ganolife {
        float: none;
        margin: 0 auto;
        padding: 4px 40px; }
        .wrapper-home .section-last .container .wrapper--btns .btn-ganolife span, .wrapper-home .section-last .container .wrapper--btns laptop .btn-ganolife span, .wrapper-home .section-last .container .wrapper--btns desktop .btn-ganolife span {
          display: inline-block;
          margin: 0 2px; }
    .wrapper-home .section-last .container .message--gren {
      font-style: italic;
      font-family: "Montserrat" !important;
      font-weight: bold; }

.wrap {
  width: 70%;
  margin: 0 auto; }

.txt-l {
  text-align: left !important; }

.txt-r {
  text-align: right !important; }

.footer-container {
  background: #2f3132;
  clear: both; }
  .footer-container .footer {
    background: #2f3132;
    padding: 50px 0;
    height: auto; }
    .footer-container .footer .footer-content .footer-content__data--join {
      padding: 0 20px; }
      .footer-container .footer .footer-content .footer-content__data--join .footer-content__data__title {
        font-size: 14px !important;
        font-family: "Montserrat",sans-serif; }
        .footer-container .footer .footer-content .footer-content__data--join .footer-content__data__title, .footer-container .footer .footer-content .footer-content__data--join .footer-content__data__title tablet {
          border-right: solid #ccc 1px;
          padding-right: 5px; }
        .footer-container .footer .footer-content .footer-content__data--join .footer-content__data__title a {
          color: #aaa;
          margin-left: 10px; }
      .footer-container .footer .footer-content .footer-content__data--join .last {
        border-right: solid transparent 1px; }
    .footer-container .footer .footer-content .txt-r span {
      font-size: 16px !important; }
    .footer-container .footer .footer-content .footer-content__data {
      display: inline-block;
      vertical-align: top;
      width: 32%;
      color: #dddddd;
      text-align: center; }
      .footer-container .footer .footer-content .footer-content__data .footer-content__data__socials {
        padding: 0; }
        .footer-container .footer .footer-content .footer-content__data .footer-content__data__socials li {
          display: inline-block;
          width: auto;
          margin: 4px;
          vertical-align: middle; }
      .footer-container .footer .footer-content .footer-content__data .footer-content__data__title {
        font-size: 16px;}
        .footer-container .footer .footer-content .footer-content__data .footer-content__data__title.contact {
          margin-bottom: 8px;
          display: inline-block; }
      .footer-container .footer .footer-content .footer-content__data .footer-content__data__subtitle {
        text-transform: uppercase;
        font-size: 1.5em; }
      .footer-container .footer .footer-content .footer-content__data .footer-content__data__correo a {
        color: #FFFFFF; }
        .footer-container .footer .footer-content .footer-content__data .footer-content__data__correo a:hover {
          text-decoration: none; }
      .footer-container .footer .footer-content .footer-content__data, .footer-container .footer .footer-content .footer-content__data tablet {
        margin-bottom: 10px !important; }

@media only screen and (max-width: 768px) {
  .wrap {
    width: 100%; }
  .footer-container {
    width: 100%; }
    .footer-container .footer {
      padding: 45px 0; }
      .footer-container .footer .footer-content .footer-content__data {
        display: block;
        width: 100%;
        text-align: center !important;
        margin-bottom: 60px; } }

.fb_iframe_widget {
  display: block !important;
  overflow: hidden; }

.wrapper-profile {
  background: #e9e9e9;
  overflow: auto;
  padding-top: 60px;
  padding-bottom: 230px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-profile {
      padding-bottom: 50px; } }
  .wrapper-profile .form-group {
    overflow: hidden; }

.drawer {
  width: 250px !important; }

.profile-container {
  background: #e9e9e9;
  max-width: 750px;
  margin: 0 auto; }
  .profile-container .container__title {
    text-align: center;
    margin-bottom: 20px; }
    .profile-container .container__title h4 {
      font-size: 30px;
      font-family: "Montserrat" !important;
      font-weight: bold; }
  .profile-container .form-horizontal {
    font-family: "Montserrat" !important; }
  .profile-container .form-group label {
    font-family: "Montserrat" !important;
    font-size: 20px;
    font-weight: bolder !important;
    color: #000; }
  .profile-container .form-group p {
    font-family: "Montserrat" !important;
    font-weight: 600;
    color: #555;
    font-size: 18px; }
  .profile-container .form-group--check .custom-checkbox {
    display: inline-block;
    width: auto; }
    .profile-container .form-group--check .custom-checkbox span {
      position: relative;
      top: -10px; }
    .profile-container .form-group--check .custom-checkbox p {
      padding-top: 10px;
      display: inline-block; }
      @media (min-width: 320px) and (max-width: 425px) {
        .profile-container .form-group--check .custom-checkbox p {
          margin-top: 10px;
          font-size: 12px; } }

.history-container .history {
  width: 100%;
  background: #FFFFFF; }
  .history-container .history .history-head {
    background: #FFFFFF;
    width: 100%; }
    .history-container .history .history-head .history-head__content .history-head__cover,
    .history-container .history .history-head .history-head__content .history-head__data {
      display: inline-block;
      vertical-align: middle;
      width: 48%; }
    .history-container .history .history-head .history-head__content .history-head__data {
      text-align: right; }
      .history-container .history .history-head .history-head__content .history-head__data .history-head__data__link {
        background: #5EB825;
        width: 100%;
        padding: 10px 80px;
        color: #FFFFFF;
        font-size: 1.5em;
        font-family: "Montserrat" !important; }
        .history-container .history .history-head .history-head__content .history-head__data .history-head__data__link:hover {
          text-decoration: none; }
        @media (min-width: 320px) and (max-width: 425px) {
          .history-container .history .history-head .history-head__content .history-head__data .history-head__data__link {
            width: 100%;
            padding: 8px;
            display: block; } }
      .history-container .history .history-head .history-head__content .history-head__data .part-init {
        font-family: "Montserrat",sans-serif;
        font-size: 2.5em;
        color: #5EB825;
        text-align: right;
        line-height: 35px; }
        .history-container .history .history-head .history-head__content .history-head__data .part-init .part-two {
          font-family: "Montserrat",sans-serif;
          color: #1e1d1d; }
        .history-container .history .history-head .history-head__content .history-head__data .part-init .part-three {
          text-transform: uppercase;
          color: #5EB825;
          font-family: "Montserrat",sans-serif;}
        .history-container .history .history-head .history-head__content .history-head__data .part-init .part-four {
          font-family: "Montserrat",sans-serif;
          color: #1e1d1d; }
      .history-container .history .history-head .history-head__content .history-head__data .part-two-init {
        font-size: 2.5em;
        font-family: "Montserrat",sans-serif;
        text-align: right; }
        .history-container .history .history-head .history-head__content .history-head__data .part-two-init .part-t-two {
          font-family:  "Montserrat",sans-serif;
          text-transform: uppercase; }
  .history-container .history .history-banner {
    background: #5EB825; }
    .history-container .history .history-banner .history-banner__content {
      text-align: center; }
      .history-container .history .history-banner .history-banner__content h2 {
        color: #FFFFFF; }
        .history-container .history .history-banner .history-banner__content h2 .bld {
          font-family:  "Montserrat",sans-serif;}
  .history-container .history .history-body {
    background: #E9E9E9; }
    .history-container .history .history-body .history-body__content .history-body__content__description h3 {
      text-transform: uppercase;
      font-family:  "Montserrat",sans-serif;
      text-align: center; }
    .history-container .history .history-body .history-body__content .history-body__content__description p {
      font-family:  "Montserrat",sans-serif;
      font-size: 1.5em;
      text-align: justify; }
    .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list {
      text-align: center; }
      @media (min-width: 320px) and (max-width: 425px) {
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .circle__item {
          width: 200px;
          height: 250px;
          margin: 0 auto; }
          .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .circle__item h4 {
            font-size: 20px; }
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign1 {
          margin-top: 25px; } }
      .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list h1 {
        text-transform: uppercase;
        font-family:  "Montserrat",sans-serif; }
      .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign1 {
        position: relative;
        top: 9em; }
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign1:after, .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign1:before {
          content: "";
          position: absolute;
          top: 0;
          width: 25px;
          height: 4px;
          background-color: #1e1d1d; }
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign1:after {
          transform: rotate(90deg); }
      .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign2 {
        position: relative;
        top: 9em; }
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign2:after {
          content: "";
          position: absolute;
          top: 0;
          width: 25px;
          height: 4px;
          background-color: #1e1d1d; }
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign2:before {
          content: "";
          position: absolute;
          top: 10px;
          width: 25px;
          height: 4px;
          background-color: #1e1d1d; }
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign2:after {
          transform: rotate(0deg); }
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign2:before {
          transform: rotate(0deg); }
    .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result {
      text-align: center;
      margin-top: 10em; }
      .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result span {
        font-size: 1.8em;
        font-family:  "Montserrat",sans-serif;
        text-transform: uppercase; }
      .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result a {
        background: #5EB825;
        color: #fff;
        padding: 10px 40px;
        width: 100%;
        font-size: 1.5em; }
        .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result a:hover {
          text-decoration: none; }

@media only screen and (max-width: 425px) {
  .history-container .history .history-head .history-head__content {
    padding-top: 50px;
    height: auto; }
    .history-container .history .history-head .history-head__content .history-head__cover {
      padding-top: 0;
      width: 100%; }
      .history-container .history .history-head .history-head__content .history-head__cover img {
        width: 100%; }
    .history-container .history .history-head .history-head__content .history-head__data {
      margin-top: 20px;
      margin-bottom: 40px;
      width: 100%;
      text-align: center; }
      .history-container .history .history-head .history-head__content .history-head__data .part-init {
        font-size: 2em;
        text-align: center; }
      .history-container .history .history-head .history-head__content .history-head__data .part-two-init {
        font-size: 2em;
        text-align: center; }
  .history-container .history .history-body .history-body__content .history-body__content__description {
    padding: 10px; }
  .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign1 {
    z-index: 1;
    top: -20px;
    left: -10px; }
  .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign2 {
    top: -20px;
    left: -10px; }
  .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result {
    margin-top: 20px;
    margin-bottom: 40px;
    font-size: 10px; }
    .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result span {
      font-size: 2.5em; }
    .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result a {
      font-size: 1.5em;
      display: block;
      padding: 8px; } }

@media only screen and (min-width: 426px) and (max-width: 768px) {
  .history-container .history .history-head .history-head__content {
    padding-top: 50px; }
    .history-container .history .history-head .history-head__content .history-head__cover {
      padding-top: 105px; }
      .history-container .history .history-head .history-head__content .history-head__cover img {
        width: 100%; }
    .history-container .history .history-head .history-head__content .history-head__data .part-init {
      font-size: 2em; }
    .history-container .history .history-head .history-head__content .history-head__data .part-two-init {
      font-size: 2em; }
  .history-container .history .history-body .history-body__content .history-body__content__description {
    padding: 40px; }
  .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign1 {
    z-index: 1;
    top: -20px;
    left: -10px; }
  .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__list .sign2 {
    top: -20px;
    left: -10px; }
  .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result {
    margin-top: 20px;
    margin-bottom: 40px; }
    .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result span {
      font-size: 2.5em; }
    .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result a {
      font-size: 2.5em; } }

@media only screen and (min-width: 1024px) and (max-width: 1439px) {
  .history-container .history .history-head .history-head__content {
    height: 400px; }
    .history-container .history .history-head .history-head__content .history-head__cover {
      padding-top: 80px; }
      .history-container .history .history-head .history-head__content .history-head__cover img {
        width: 100%; }
  .history-container .history .history-body .history-body__content .history-body__content__description {
    padding: 40px 80px; }
  .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result span {
    font-size: 1.5em; }
  .history-container .history .history-body .history-body__content .history-body__content__formule .history-body__content__formule__result a {
    font-size: 1.1em; } }

.wrapper-orders {
  background: #E9E9E9; }
  .wrapper-orders .title {
    text-align: center;
    color: #5EB825;
    font-weight: bold;
    font-size: 28px;
    margin-bottom: 80px; }
  .wrapper-orders .container {
    padding-top: 50px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-orders .container {
        padding-top: 20px; }
        .wrapper-orders .container .title {
          margin-bottom: 20px; } }
  .wrapper-orders .total-header {
    margin-top: 30px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-orders .total-header {
        margin-top: 5px; } }
    .wrapper-orders .total-header .header__title {
      font-size: 15px;
      font-weight: bold; }
  .wrapper-orders .dropdown.time {
    float: right; }
  .wrapper-orders .dropdown .your-orders {
    font-size: 26px;
    text-decoration: none !important;
    color: #5EB825;
    font-family:  "Montserrat",sans-serif; }
  .wrapper-orders .dropdown .dropdown-menu {
    border-radius: 0;
    background: rgba(0, 0, 0, 0.85); }
    .wrapper-orders .dropdown .dropdown-menu li a {
      color: #5EB825; }
  .wrapper-orders .dropdown-menu--green {
    background: #5EB825 !important; }
    .wrapper-orders .dropdown-menu--green a {
      color: white !important; }
      @media (min-width: 426px) and (max-width: 768px) {
        .wrapper-orders .dropdown-menu--green a {
          font-size: 20px; } }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-orders .dropdown-menu--green a {
          font-size: 16px; } }
    .wrapper-orders .dropdown-menu--green, .wrapper-orders .dropdown-menu--green mobile-medium {
      min-width: 120px;
      width: 108px; }
  @media (min-width: 426px) and (max-width: 768px) {
    .wrapper-orders .dropdown {
      width: 100%; } }

.wrapper-product {
  margin-top: 60px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-product {
      margin-top: 0; } }

.product__detail {
  margin: 50px 0; }
  @media (min-width: 320px) and (max-width: 425px) {
    .product__detail {
      margin: 0 0 30px; } }
  .product__detail hr {
    margin-top: -15px;
    margin-bottom: 10px;
    clear: both;
    border-top: solid #BFBFBF 1px;
    margin: 15px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .product__detail hr {
        margin-top: 10px;
        margin-bottom: 10px; } }
  .product__detail .detail__head {
   }
    .product__detail .detail__head .wrapper {
      margin-top: 5px;
      overflow: hidden; }
    .product__detail .detail__head .head__date {
      font-family:  "Montserrat",sans-serif;
      font-weight: bold; }
  .product__detail .product__resume .resume__voucher {
    border-left: solid 1px grey;
    padding-left: 10px;
    margin-left: 10px;
    color: #5EB825; }
  .product__detail .product-desc .desc__name,
  .product__detail .product-desc .desc__price {
    color: #5EB825;
    font-weight: bold; }
  .product__detail .product-desc h4 {
    font-family:  "Montserrat",sans-serif;
    font-weight: bold;
    color: black; }
  .product__detail .product-desc p {
    font-weight: bold;
    margin: 0; }
  .product__detail .product-desc .img img {
    width: 100%; }
  .product__detail .product-desc .btn-ganolife {
    display: block;
    margin-bottom: 5px; }

.btn-ganolife--right,
.tool-item--right {
  float: right; }

.tool-item {
  color: #777;
  text-decoration: underline;
  font-size: 14px;
  margin-bottom: 15px; }

.card-num {
  font-weight: bold; }
  .card-num img {
    margin-top: -5px; }

.card-title {
  font-size: 1.5em;
  text-align: center;
  font-weight: 100; }

@media (min-width: 320px) and (max-width: 425px) {
  .payments__form--interact .detail--default,
  .payments__form--interact .form-ganolife,
  .payments__form--interact .form-title {
    display: none; } }

.payments__form--interact .resp-default {
  display: none; }
  @media (min-width: 320px) and (max-width: 425px) {
    .payments__form--interact .resp-default {
      display: block; } }

.payments__form--interact .btns-nav {
  font-weight: bold; }
  .payments__form--interact .btns-nav a {
    display: inline-block;
    color: #5EB825; }
    .payments__form--interact .btns-nav a span {
      border-color: #5EB825; }

.payments__form--interact .selected-card {
  display: none; }
  @media (min-width: 320px) and (max-width: 425px) {
    .payments__form--interact .selected-card {
      display: block; } }

.payments__form--interact .select-cards .table-one {
  display: none; }

@media (min-width: 320px) and (max-width: 425px) {
  .payments__form--interact .select-cards {
    display: none; } }

@media (min-width: 426px) and (max-width: 768px) {
  .payments__form--interact .select-cards {
    margin-top: 20px; } }

.payments__form--interact .form-ganolife .btn-sv {
  display: none; }

@media (min-width: 320px) and (max-width: 425px) {
  .payments__form--interact .form-ganolife {
    display: none; }
    .payments__form--interact .form-ganolife .btn-ganolife,
    .payments__form--interact .form-ganolife .btn-save {
      display: block;
      margin-bottom: 20px; }
    .payments__form--interact .form-ganolife .btn-save {
      display: none; } }

.payments__form--interact .detail--firstopt {
  display: none; }
  @media (min-width: 320px) and (max-width: 425px) {
    .payments__form--interact .detail--firstopt {
      display: block; }
      .payments__form--interact .detail--firstopt .btn {
        display: block;
        width: 100%;
        margin-top: 35px !important;
        margin-bottom: 25px !important; }
      .payments__form--interact .detail--firstopt .detail__options {
        text-align: center;
        margin-top: 20px;
        float: none !important; }
      .payments__form--interact .detail--firstopt .wrapper {
        width: 80%;
        margin: 0 auto !important; } }

.payments__form {
  background: #E9E9E9;
  padding-bottom: 280px; }
  .payments__form .resp {
    display: none; }
    @media (min-width: 320px) and (max-width: 425px) {
      .payments__form .resp {
        display: block; } }
  .payments__form .nresp {
    display: block; }
    @media (min-width: 320px) and (max-width: 425px) {
      .payments__form .nresp {
        display: none; } }
  @media (min-width: 320px) and (max-width: 425px) {
    .payments__form {
      padding-bottom: 0; } }
  .payments__form h3,
  .payments__form h4 {
    margin: 0; }
  .payments__form h4 {
    margin: 10px 0;
    color: #5EB825;
    font-weight: bold; }
  .payments__form h5 {
    position: relative; }
    .payments__form h5 .check-green {
      top: 0; }
  .payments__form .body-tablet {
    padding-bottom: 20px !important;
    border-bottom: solid #ddd 1px;
    margin-bottom: 30px !important; }
    .payments__form .body-tablet li {
      padding-top: 10px;
      font-size: 16px; }
  .payments__form .check-green {
    width: 25px;
    height: 25px; }
    .payments__form .check-green i {
      width: 18px;
      height: 18px;
      margin-top: 2px; }
  .payments__form .form-inline input {
    width: 100%; }
  .payments__form .form-inline, .payments__form .form-inline tablet {
    margin-top: -15px; }
    .payments__form .form-inline input.first-child, .payments__form .form-inline tablet input.first-child {
      margin: 15px 0; }
  .payments__form .form-inline div.mg, .payments__form .form-inline desktop div.mg {
    margin-top: 15px; }
  .payments__form .form-inline input.first-child, .payments__form .form-inline desktop input.first-child {
    margin: 0; }
  .payments__form .title {
    color: #5EB825;
    text-align: center;
    margin-bottom: 50px;
    font-family:  "Montserrat",sans-serif;
    clear: both;
    overflow: hidden; }
  .payments__form .btn-ganolife--dopay {
    float: right;
    width: 164px; }
  .payments__form .btn-ganolife--right {
    margin-top: 30px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .payments__form .btn-ganolife--right {
        display: block;
        width: 100%;
        margin-bottom: 20px; } }
  .payments__form .head .head-text-first {
    display: inline; }
  .payments__form .head .head-text {
    font-size: 20px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .payments__form .head {
      margin-bottom: 10px; }
      .payments__form .head .head-text,
      .payments__form .head .head-text-first {
        display: inline;
        font-size: 14px; }
      .payments__form .head .head-text {
        margin-left: 5px; } }
  .payments__form form .select-anio {
    width: 100%;
    background: #fff;
    padding: 5px;
    border: 1px solid #ccc;
    color: #aaa; }
  .payments__form .detail .wrapper {
    margin: 15px 0; }
  .payments__form .detail .detail_fact {
    color: black;
    font-family:  "Montserrat",sans-serif;
    margin-bottom: -15px; }
  .payments__form .detail .detail__options {
    float: right; }
    .payments__form .detail .detail__options a {
      color: black;
      cursor: pointer;
      text-decoration: none;
      margin: 5px;
      padding: 0 15px;
      border-left: solid 1px #ccc; }
      .payments__form .detail .detail__options a:first-child {
        border-color: transparent; }
    .payments__form .detail .detail__options.active .use {
      display: none; }
  .payments__form .detail .detail__next a {
    margin-top: 80px;
    float: right; }
    @media (min-width: 320px) and (max-width: 425px) {
      .payments__form .detail .detail__next a {
        display: block;
        margin: 35px auto;
        float: none;
        width: 90%;
        font-size: 14px; } }
  .payments__form .detail .detail__next--right {
    float: right; }
  .payments__form .detail h5 {
    clear: both;
    margin-top: 35px;
    font-weight: bold;
    font-family:  "Montserrat",sans-serif; }
  .payments__form .table {
    border: solid 1px #ccc;
    background: #f7f7f7; }
    .payments__form .table td {
      border-top: 0; }
  .payments__form .product__list ul.head {
    margin-top: 10px;
    padding: 10px 0;
    border-top: solid #ddd 1px;
    border-bottom: solid #ddd 1px;
    font-size: 18px;
    font-family:  "Montserrat",sans-serif;
    font-weight: bold;
    margin-bottom: 15px; }
  .payments__form .product__list .total {
    display: inline-block; }
    @media (min-width: 320px) and (max-width: 425px) {
      .payments__form .product__list .total {
        display: none; } }
    @media (min-width: 426px) and (max-width: 768px) {
      .payments__form .product__list .total {
        display: none; } }
  .payments__form .product__list li {
    list-style: none;
    display: inline-block;
    vertical-align: middle;
    float: none;
    display: inline-block;
    margin: -2px;
    text-align: center; }
  .payments__form .product__list .list__image img {
    max-width: 150px;
    width: 100%; }
  .payments__form .product__list .list__desc {
    padding-top: 20px; }
    .payments__form .product__list .list__desc h5 {
      font-family:  "Montserrat",sans-serif;
      font-size: 16px; }
    .payments__form .product__list .list__desc h4 {
      text-transform: uppercase;
      font-size: 16px; }
  .payments__form .product__list .ul {
    font-size: 18px;
    font-weight: bold; }
    .payments__form .product__list .ul .discount {
      color: #5EB825; }
    .payments__form .product__list .ul .strong {
      font-weight: bold; }

.payments__form--second .head-text,
.payments__form--second h3 {
  font-family:  "Montserrat",sans-serif;
  font-weight: bold;
  font-size: 20px; }

.payments__form--second .nresp-tablet {
  display: block; }
  @media (min-width: 320px) and (max-width: 425px) {
    .payments__form--second .nresp-tablet {
      display: none; } }
  @media (min-width: 426px) and (max-width: 768px) {
    .payments__form--second .nresp-tablet {
      display: none; } }

.payments__form--thankyou {
  margin-top: 100px; }
  .payments__form--thankyou .title {
    font-size: 20px;
    font-family:  "Montserrat",sans-serif; }
  .payments__form--thankyou .head {
    font-family:  "Montserrat",sans-serif;
    font-weight: 600;
    text-align: center; }
    .payments__form--thankyou .head .head__text {
      font-size: 17px; }
      .payments__form--thankyou .head .head__text .text-green {
        margin: 0 5px;
        color: #5EB825;
        font-weight: bold;
        font-family:  "Montserrat",sans-serif; }
    .payments__form--thankyou .head .head__desc {
      font-size: 16px; }
      .payments__form--thankyou .head .head__desc .desc-here {
        margin: 0 5px;
        color: #5EB825;
        font-size: 16px; }
  .payments__form--thankyou .form {
    margin-top: 80px;
    text-align: center;
    font-family:  "Montserrat",sans-serif;
    font-weight: bold; }
    .payments__form--thankyou .form .form__head {
      font-size: 17px; }
    .payments__form--thankyou .form .form__question {
      font-size: 17px;
      margin: 30px 0; }
    .payments__form--thankyou .form select option {
      font-family:  "Montserrat",sans-serif;
      font-weight: bold !important;
      font-size: 18px; }
    .payments__form--thankyou .form .btn {
      font-family:  "Montserrat",sans-serif; }

.wrapper-siginup {
  background: #E9E9E9; }
  .wrapper-siginup .form-group {
    overflow: hidden; }
  .wrapper-siginup .section {
    padding-top: 120px; }
  .wrapper-siginup .tabs__loginopts {
    text-align: center;
    padding-top: 10px; }
    .wrapper-siginup .tabs__loginopts .fb-login-button {
      margin: 0 auto; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-siginup .section {
      padding-top: 50px !important; }
    .wrapper-siginup .nav-tabs li a {
      margin: 0;
      padding: 5px; }
    .wrapper-siginup .register-text, .wrapper-siginup .btn-facebook, .wrapper-siginup .or-option {
      font-size: 18px !important; }
    .wrapper-siginup .btn-ganolife {
      display: block; } }
  @media (min-width: 426px) and (max-width: 768px) {
    .wrapper-siginup .btn-ganolife {
      clear: both;
      margin-top: 10px;
      display: block; } }
      
      
  .wrapper-siginup .promotion, .wrapper-siginup .promotion mobile, .wrapper-siginup .policy, .wrapper-siginup .policy mobile {
    display: block;
    padding: 0;
    margin-top: 10px; }
  .wrapper-siginup .promotion, .wrapper-siginup .promotion desktop, .wrapper-siginup .policy, .wrapper-siginup .policy desktop {
    display: inline; }
  .wrapper-siginup .policy, .wrapper-siginup .policy desktop {
    margin-left: 10px; }
  .wrapper-siginup .form-ganolife .form-group {
    overflow: hidden; }
  .wrapper-siginup .nav-tabs {
    border-bottom: 0 !important;
    margin-bottom: 30px;
    text-align: center;
    display: block;
    margin: 0 auto; }
    .wrapper-siginup .nav-tabs li a {
      font-size: 14px;
      color: grey; }
      
    .wrapper-siginup .nav-tabs .active a {
      background: transparent !important; border-bottom: solid 1px #000000 ; color: black; font-weight: bold; }
      
      
  .wrapper-siginup .register-text {
    color: #5EB825;
    text-align: center;
    font-size: 22px;
    font-family:  "Montserrat",sans-serif;
    margin: 15px 0; }
  .wrapper-siginup .btn-facebook {
    background: #3e3e3e !important;
    font-size: 18px;
    color: white;
    border-radius: 0; }
  .wrapper-siginup .or-option {
    text-align: center;
    margin: 10px 0;
    font-family:  "Montserrat",sans-serif;
    font-size: 20px; }
  .wrapper-siginup .custom-checkbox label:before {
    top: 0 !important; }
  .wrapper-siginup .custom-checkbox label:after {
    top: 0 !important; }
  .wrapper-siginup .custom-checkbox p {
    font-family:  "Montserrat",sans-serif; }
  .wrapper-siginup .custom-checkbox .policy {
    color: #5EB825;
    float: none; }
  .wrapper-siginup .custom-checkbox .promotion {
    display: inline; }
  .wrapper-siginup .btn-ganolife {
    margin-top: 30px; }

.wrapper-contact iframe {
  height: 280px !important; }

.wrapper-contact .contact__form {
  background-color: #E9E9E9;
  padding: 0;
  margin: 0; }
  .wrapper-contact .contact__form .container .subtitle,
  .wrapper-contact .contact__form .container .title {
    text-align: center;
    margin-bottom: 20px; }
  .wrapper-contact .contact__form .container .head .form .form-send {
    float: right;
    background-color: #5EB825;
    color: #FFF;
    padding: 5px 45px;
    border: 0;
    font-size: 1.5em;
    font-family:  "Montserrat",sans-serif; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-contact .contact__form .container .head .form .form-send {
        margin-bottom: 50px;
        padding: 2px 45px; } }
  .wrapper-contact .contact__form .container .head .form .form-group textarea {
    resize: none; }
  .wrapper-contact .contact__form .container .head .form .form-group .form-control {
    background-color: #FFFFFF; }
  .wrapper-contact .contact__form .container .body .contact-content {
    margin-bottom: 50px; }
    .wrapper-contact .contact__form .container .body .contact-content .content-address,
    .wrapper-contact .contact__form .container .body .contact-content .content-phone,
    .wrapper-contact .contact__form .container .body .contact-content .content-schedule {
      margin-bottom: 30px; }
      .wrapper-contact .contact__form .container .body .contact-content .content-address p .p,
      .wrapper-contact .contact__form .container .body .contact-content .content-phone p .p,
      .wrapper-contact .contact__form .container .body .contact-content .content-schedule p .p {
        font-family:  "Montserrat",sans-serif;
        font-size: 1.2em; }
      .wrapper-contact .contact__form .container .body .contact-content .content-address p span,
      .wrapper-contact .contact__form .container .body .contact-content .content-phone p span,
      .wrapper-contact .contact__form .container .body .contact-content .content-schedule p span {
        font-family: "Montserrat",sans-serif; }
      .wrapper-contact .contact__form .container .body .contact-content .content-address p .block,
      .wrapper-contact .contact__form .container .body .contact-content .content-phone p .block,
      .wrapper-contact .contact__form .container .body .contact-content .content-schedule p .block {
        display: block; }
    .wrapper-contact .contact__form .container .body .contact-content .content-link p {
      font-size: 1.2em; }
      .wrapper-contact .contact__form .container .body .contact-content .content-link p a {
        color: #5EB825; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-contact .contact__form .container .body .contact-content .content-phone span {
        display: inline;
        margin-left: 0; }
      .wrapper-contact .contact__form .container .body .contact-content p span {
        display: block; }
      .wrapper-contact .contact__form .container .body .contact-content .content-link,
      .wrapper-contact .contact__form .container .body .contact-content span {
        font-family:  "Montserrat",sans-serif;
        font-weight: bold; } }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-contact .title {
    font-size: 32px;
    margin-bottom: 10px !important; }
  .wrapper-contact .subtitle {
    font-size: 17px;
    font-family:  "Montserrat",sans-serif;
    font-weight: bolder;
    color: #888; }
  .wrapper-contact .form-send {
    display: block; }
  .wrapper-contact .head .form .form-ganolife .form-control {
    margin-bottom: 20px; } }

.line-t {
  text-decoration: line-through; }

.bold {
  font-weight: bold; }

.green {
  color: #5EB825; }

.wrapper-plan .container--desc {
  margin-top: -125px;
  padding-top: 125px; }

.wrapper-plan .begin-now--mod a {
  padding: 10px 25px;
  font-size: 20px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-plan .begin-now--mod a {
      padding: 2px 25px; } }

.wrapper-plan .begin-now {
  margin-top: 20px; }

.wrapper-plan .content-head__descrip {
  text-align: center; }
  .wrapper-plan .content-head__descrip p {
    text-align: center;
    margin: 0; }

.wrapper-plan .plan-content {
  padding: 40px;
  overflow: hidden; }
  .wrapper-plan .plan-content .content-head__descrip {
    text-align: center;
    margin-right: 10%;
    margin-left: 10%;
    margin-top: 150px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-plan .plan-content .content-head__descrip {
        margin-top: 20px !important; } }
    .wrapper-plan .plan-content .content-head__descrip p {
      font-weight: 500;
      font-size: 1.2em; }
      .wrapper-plan .plan-content .content-head__descrip p span {
        text-transform: uppercase;
        font-size: 2em;
        color: #5EB825;
        font-weight: 700;
        font-family:  "Montserrat",sans-serif; }
    .wrapper-plan .plan-content .content-head__descrip .descrip_resalt {
      font-size: 18px;
      color: #000 !important;
      font-weight: 700;
      text-transform: none !important;
      margin-bottom: 15px;
      display: block; }
  .wrapper-plan .plan-content .content-head__image img {
    width: 100%; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-plan .plan-content .content-head__image {
      width: 320px;
      margin: 0 auto; } }

.wrapper-plan .step-content {
  text-align: center; }
  .wrapper-plan .step-content .step-content__title {
    text-align: center;
    font-size: 2.3em; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-plan .step-content .step-content__title {
        padding-top: 20px;
        font-size: 20px;
        font-weight: bold; } }
  .wrapper-plan .step-content .step-content__items {
    text-align: center;
    margin-bottom: 40px; }
    .wrapper-plan .step-content .step-content__items .items__content {
      background-color: #FFF;
      padding: 15px;
      height: auto; }
      .wrapper-plan .step-content .step-content__items .items__content h2 {
        line-height: 35px; }
        .wrapper-plan .step-content .step-content__items .items__content h2 span {
          color: #5EB825;
          text-transform: uppercase; }
      .wrapper-plan .step-content .step-content__items .items__content p {
        font-size: 1.2em; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-plan .step-content .step-content__items .items__content {
          padding: 1px; }
          .wrapper-plan .step-content .step-content__items .items__content h2 {
            margin: 0;
            font-size: 26px; }
            .wrapper-plan .step-content .step-content__items .items__content h2 span {
              font-size: 27px; }
          .wrapper-plan .step-content .step-content__items .items__content p {
            padding: 5px;
            font-size: 15px;
            line-height: 17px;
            font-weight: normal; } }

.wrapper-plan .get-plan .get-plan__title p {
  font-size: 2.3em;
  color: #000;
  font-weight: 500; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-plan .get-plan .get-plan__title p {
      font-size: 24px; } }

.wrapper-plan .get-plan .get-plan__link {
  margin-top: 20px;
  margin-bottom: 50px; }

.wrapper-plan .get-plan .get-plan__items img {
  width: 100%;
  height: auto; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-plan .get-plan .get-plan__items img {
      height: 155px; } }

.wrapper-plan .get-plan .get-plan__items .nresp, .wrapper-plan .get-plan .get-plan__items .nresp laptop, .wrapper-plan .get-plan .get-plan__items .nresp desktop {
  display: block; }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-plan .get-plan .get-plan__items .nresp {
    display: none; } }

.wrapper-plan .get-plan .get-plan__items .resp {
  display: none; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-plan .get-plan .get-plan__items .resp {
      font-size: 18px;
      padding: 21px 10px;
      width: 80%;
      display: block;
      margin: 0 auto;
      border-bottom: 1px solid grey;
      margin-bottom: 40px;
      color: grey; } }

.wrapper-plan .get-plan .get-plan__items .items__descrip h3 {
  text-transform: uppercase;
  color: #5EB825;
  font-weight: 700; }
  .wrapper-plan .get-plan .get-plan__items .items__descrip h3 span {
    font-weight: bold; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-plan .get-plan .get-plan__items .items__descrip h3 {
      font-size: 20px;
      margin-top: 10px; } }

.wrapper-plan .get-plan .get-plan__items .items__descrip p {
  font-size: 1.5em; }
  .wrapper-plan .get-plan .get-plan__items .items__descrip p span {
    color: #000;
    font-weight: 700; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-plan .get-plan .get-plan__items .items__descrip p span {
        } }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-plan .get-plan .get-plan__items .items__descrip p {
      font-size: 18px;
      font-family:  "Montserrat",sans-serif;
      font-weight: bold;
      color: grey; } }

@media (min-width: 769px) and (max-width: 1440px) {
  .wrapper-plan .get-plan .get-plan__items .row {
    margin-bottom: 10px; }
  .wrapper-plan .get-plan .get-plan__items img {
    width: 100%; }
  .wrapper-plan .get-plan .get-plan__items .items__descrip {
    font-size: 0.8em; }
    .wrapper-plan .get-plan .get-plan__items .items__descrip .btn-ganolife {
      color: #FFFFFF;
      padding: 15px 45px; }
      .wrapper-plan .get-plan .get-plan__items .items__descrip .btn-ganolife:hover {
        text-decoration: none;
        cursor: pointer; }
    .wrapper-plan .get-plan .get-plan__items .items__descrip h3 {
      text-transform: uppercase;
      color: #5EB825;
      font-weight: 700; }
      .wrapper-plan .get-plan .get-plan__items .items__descrip h3 span {
        font-weight: bold; }
    .wrapper-plan .get-plan .get-plan__items .items__descrip p {
      font-size: 1.5em; }
      .wrapper-plan .get-plan .get-plan__items .items__descrip p span {
        color: #000;
        font-weight: 700; }
  .wrapper-plan .plan-content .content-head__descrip {
    margin-top: 50px; }
  .wrapper-plan .step-content .step-content__items .items__content {
    padding: 30px;
    height: 300px; }
    .wrapper-plan .step-content .step-content__items .items__content h2 {
      font-size: 2em;
      padding-bottom: 20px; } }

@media (min-width: 426px) and (max-width: 768px) {
  .wrapper-plan .get-plan .get-plan__items .row {
    margin-bottom: 10px; }
  .wrapper-plan .get-plan .get-plan__items img {
    width: 100%; }
  .wrapper-plan .get-plan .get-plan__items .items__descrip {
    font-size: 0.7em; }
    .wrapper-plan .get-plan .get-plan__items .items__descrip h3 {
      text-transform: uppercase;
      color: #5EB825;
      font-weight: 700; }
      .wrapper-plan .get-plan .get-plan__items .items__descrip h3 span {
        font-weight: bold; }
    .wrapper-plan .get-plan .get-plan__items .items__descrip p {
      font-size: 1.5em; }
      .wrapper-plan .get-plan .get-plan__items .items__descrip p span {
        color: #000;
        font-weight: 700; }
  .wrapper-plan .plan-content .content-head__descrip {
    margin-top: 50px; }
  .wrapper-plan .step-content .step-content__items .items__content {
    padding: 30px;
    height: 400px; }
    .wrapper-plan .step-content .step-content__items .items__content h2 {
      font-size: 1.3em;
      font-weight: 700;
      padding-bottom: 20px; }
    .wrapper-plan .step-content .step-content__items .items__content p {
      text-align: justify; } }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-plan .container {
    background: #FFFFFF; }
    .wrapper-plan .container .step-content .step-content__title {
      margin-top: 20px; }
    .wrapper-plan .container .step-content .step-content__items .items__content {
      margin-bottom: 20px;
      background: #E9E9E9; }
      .wrapper-plan .container .step-content .step-content__items .items__content h2 {
        font-family:  "Montserrat",sans-serif; }
        .wrapper-plan .container .step-content .step-content__items .items__content h2 span {
          font-family:  "Montserrat",sans-serif; }
  .wrapper-plan .plan-content {
    padding: 0;
    background: #E9E9E9; }
    .wrapper-plan .plan-content .content-head__descrip {
      margin-top: 40px;
      margin-bottom: 40px; }
  .wrapper-plan .get-plan {
    text-align: center; }
    .wrapper-plan .get-plan .get-plan__link {
      margin: 40px 0; } }

.wrapper-plan365 .desc {
  margin-top: 10px;
  margin-bottom: 20px; }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-plan365 {
    padding-top: 0 !important; }
    .wrapper-plan365 .container {
      background: transparent !important; }
    .wrapper-plan365 .content__body {
      padding: 0 !important; }
      .wrapper-plan365 .content__body .box {
        padding-top: 0 !important;
        height: 165px !important; }
        .wrapper-plan365 .content__body .box img {
          width: 100px; }
    .wrapper-plan365 .exchange h3 {
      font-size: 25px !important;
      margin-bottom: 15px !important;
      text-align: center; }
    .wrapper-plan365 .exchange:nth-of-type(1) {
      margin-top: -40px; }
    .wrapper-plan365 .exchange:nth-of-type(2) {
      margin: 20px 0; }
    .wrapper-plan365 .exchange img {
      width: 240px !important;
      height: auto !important;
      margin: 0 auto;
      display: block; } }

.wrapper-plan365 .continue-btn a, .wrapper-plan365 mobile .continue-btn a {
  display: block;
  margin-bottom: 40px; }

.wrapper-plan365--4 .title {
  color: #5EB825;
  margin-bottom: 50px; }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-plan365--4 .product__list ul {
    border-bottom: solid 1px #D6D6D6; } }

.wrapper-plan365--4 .list__pricedetail p {
  font-size: 16px;
  font-family:  "Montserrat",sans-serif;
  font-weight: bold; }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-plan365--4 .list__pricedetail ul li p {
    text-align: center; } }

.wrapper-plan365--4 .list__pricedetail strong {
  font-weight: bold;
  font-family:  "Montserrat",sans-serif; }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-plan365--3.second {
    clear: both;
    margin-top: 40px; } }

.wrapper-plan365--3 .img img {
  width: 100%; }

.wrapper-plan365--3 .green strong {
  margin: 0 4px; }

.wrapper-plan365--3 .bold .green {
  margin: 0 4px; }

.wrapper-plan365--3 .btn {
  display: block; }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-plan365--1 .title {
    margin-top: 0 !important;
    font-size: 30px !important; }
  .wrapper-plan365--1 .box {
    margin-top: 0 !important; }
    .wrapper-plan365--1 .box p {
      font-size: 14px !important; } }

.wrapper-plan365--1 .btn-ganolife--c1, .wrapper-plan365--1 mobile .btn-ganolife--c1 {
  display: block;
  margin-bottom: 20px; }

.wrapper-plan365--2 {
  padding-top: 80px; }
  .wrapper-plan365--2 .img img {
    max-width: 350px;
    height: 250px; }
  .wrapper-plan365--2 h3.green {
    color: #5EB825;
    font-size: 30px;
    font-family:  "Montserrat",sans-serif;
    margin-bottom: 50px; }
  .wrapper-plan365--2 .container p {
    margin: 0;
    font-size: 16px; }
  .wrapper-plan365--2 .content__price {
    font-size: 20px; }
    .wrapper-plan365--2 .content__price .price {
      font-weight: bold;
      font-family:  "Montserrat",sans-serif; }
    .wrapper-plan365--2 .content__price .strong {
      font-family:  "Montserrat",sans-serif;
      font-weight: bold; }
    .wrapper-plan365--2 .content__price .green {
      color: #5EB825; }
  .wrapper-plan365--2 .selectfooter {
    clear: both;
    margin-top: 20px; }
    .wrapper-plan365--2 .selectfooter h3 {
      color: #5EB825;
      margin-bottom: 20px; }
  .wrapper-plan365--2 .continue-btn {
    margin-top: 50px; }
    .wrapper-plan365--2 .continue-btn .btn {
      font-size: 18px; }

.plan365-content .title {
  margin-top: 60px;
  text-align: center;
  font-family:  "Montserrat",sans-serif;
  font-size: 35px;
  font-weight: bold; }
  @media (min-width: 320px) and (max-width: 425px) {
    .plan365-content .title {
      font-size: 25px; } }

.plan365-content .head .head__text {
  text-align: center;
  font-size: 17px;
  font-weight: bold; }

.plan365-content .content__body {
  padding: 0 50px; }
  .plan365-content .content__body .wrap-box strong {
    font-weight: bold;
    text-align: center;
    display: block;
    margin-top: 14px;
    font-size: 16px; }
  .plan365-content .content__body .box {
    margin-top: 40px;
    height: 340px;
    padding-top: 90px;
    overflow: hidden;
    text-align: center;
    position: relative; }
    .plan365-content .content__body .box.active {
      background-image: url("../../images/border.png");
      background-size: 100% 100%;
      background-repeat: no-repeat; }
      .plan365-content .content__body .box.active .check-green {
        display: block; }
    .plan365-content .content__body .box .check-green {
      display: none; }
    .plan365-content .content__body .box p {
      font-size: 20px;
      font-family:  "Montserrat",sans-serif;
      font-weight: 600; }
      @media (min-width: 320px) and (max-width: 425px) {
        .plan365-content .content__body .box p {
          font-size: 18px; } }

.wrapper-segcancel {
  padding-top: 80px; }
  .wrapper-segcancel .header__back {
    position: absolute;
    right: 0;
    top: 0; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-segcancel {
      padding-top: 0; }
      .wrapper-segcancel .title {
        margin-bottom: 65px; }
      .wrapper-segcancel .payments__form {
        padding-bottom: 0 !important; }
      .wrapper-segcancel .header__back {
        position: absolute;
        right: 20px;
        top: -40px; } }
  .wrapper-segcancel .text-desc {
    text-align: justify; }
  .wrapper-segcancel .step-wrapper__items {
    border: solid #D8D8D8 1px;
    margin-bottom: 50px; }
    .wrapper-segcancel .step-wrapper__items .check-green, .wrapper-segcancel .step-wrapper__items tablet .check-green {
      right: 15px !important; }
    .wrapper-segcancel .step-wrapper__items .col-xs-12, .wrapper-segcancel .step-wrapper__items tablet .col-xs-12 {
      text-align: center; }
    .wrapper-segcancel .step-wrapper__items .items li i.separator, .wrapper-segcancel .step-wrapper__items tablet .items li i.separator {
      margin: 20px auto; }
    .wrapper-segcancel .step-wrapper__items .items li i.separator, .wrapper-segcancel .step-wrapper__items desktop .items li i.separator {
      margin: 20px auto; }
  .wrapper-segcancel .header__title {
    font-size: 15px;
    margin-bottom: 20px; }
    .wrapper-segcancel .header__title.header__title--state {
      margin-top: 60px; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-segcancel .header__title.header__title--state {
          margin-top: 0 !important; } }
    .wrapper-segcancel .header__title strong {
      margin-left: 5px;
      font-family:  "Montserrat",sans-serif; }
  .wrapper-segcancel .step-wrapper__items li {
    margin: -2px !important;
    float: none;
    text-align: center;
    color: #666; }
    .wrapper-segcancel .step-wrapper__items li .check-green {
      display: none; }
    .wrapper-segcancel .step-wrapper__items li.active .check-green {
      display: block !important;
      width: 25px;
      height: 25px;
      position: absolute;
      top: 0;
      right: 0; }
      .wrapper-segcancel .step-wrapper__items li.active .check-green i {
        width: 14px;
        margin-top: 5px;
        height: 14px; }

.plus-minus {
  margin: 0 8px;
  background: #E9E9E9;
  padding: 6px 12px; }

.cart-track {
  padding-top: 100px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .cart-track {
      padding-top: 25px; } }
  .cart-track .nresp {
    display: block; }
    @media (min-width: 320px) and (max-width: 425px) {
      .cart-track .nresp {
        display: none; } }
  .cart-track .detail__next.last a {
    float: right; }
    @media (min-width: 320px) and (max-width: 425px) {
      .cart-track .detail__next.last a {
        display: block;
        float: none;
        margin-top: 0px; } }
  .cart-track .resp--sum {
    margin-bottom: 50px; }
    .cart-track .resp--sum li {
      font-size: 16px; }
    .cart-track .resp--sum .first {
      text-align: justify; }
  .cart-track .resp-tablet {
    text-align: center; }
    .cart-track .resp-tablet, .cart-track .resp-tablet desktop {
      display: none; }
    @media (min-width: 320px) and (max-width: 425px) {
      .cart-track .resp-tablet {
        display: block; } }
    @media (min-width: 426px) and (max-width: 768px) {
      .cart-track .resp-tablet {
        display: block; } }
  .cart-track .cart-track__title h3 {
    color: #5EB825;
    font-size: 18px;
    text-transform: uppercase;
    font-weight: bold;
    font-family:  "Montserrat",sans-serif; }
    @media (min-width: 320px) and (max-width: 425px) {
      .cart-track .cart-track__title h3 {
        text-align: center; } }
  .cart-track .cart-track__options a {
    color: #444;
    font-weight: bold; }
  .cart-track .cart-track__options a:first-child {
    border-right: solid 1px grey; }
  .cart-track .cart-track__options--last {
    margin-bottom: 25px;
    margin-top: 25px; }
  .cart-track .product__list ul {
    margin: 0;
    padding: 0;
    position: relative; }
    .cart-track .product__list ul.item {
      clear: both; }
  .cart-track .product__list .delete {
    font-family: "Montserrat",sans-serif;
    color: #5EB825;
    position: absolute;
    bottom: 10px;
    font-size: 17px;
    right: 70px;
    cursor: pointer;
    text-decoration: none; }
    @media (min-width: 320px) and (max-width: 425px) {
      .cart-track .product__list .delete {
        top: -12px;
        right: 10px; } }
    @media (min-width: 426px) and (max-width: 768px) {
      .cart-track .product__list .delete {
        top: -10px; } }

.btn--return {
  float: right;
  display: none;
  margin: 10px 0 !important; }
  @media (min-width: 320px) and (max-width: 425px) {
    .btn--return {
      display: block; } }

.cancelation {
  padding-top: 90px; }
  .cancelation .custom-checkbox .green {
    color: #5EB825;
    text-decoration: underline; }
  .cancelation .product-desc img {
    width: 100%; }
  .cancelation .motive-text {
    font-size: 16px;
    font-family:  "Montserrat",sans-serif; }
  .cancelation .detail__head {
    font-size: 17px;
    font-family: "Montserrat",sans-serif;
    font-weight: bold; }
    .cancelation .detail__head strong {
      margin-left: 10px;
      font-family:  "Montserrat",sans-serif;
      font-weight: bolder; }
  .cancelation .btn-ganolife {
    margin-top: 20px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .cancelation {
      padding-top: 0; }
      .cancelation h2 {
        font-size: 28px;
        font-family:  "Montserrat",sans-serif; }
      .cancelation .title {
        margin-bottom: 10px; }
      .cancelation .product__detail {
        margin-top: 0; }
      .cancelation.payments__form {
        padding-bottom: 0 !important; }
      .cancelation .btn-ganolife {
        margin-bottom: 50px;
        display: block; }
      .cancelation .product-desc h4 {
        font-size: 14px;
        font-family:  "Montserrat",sans-serif; }
      .cancelation .product-desc .col-xs-12 {
        margin-top: 20px; }
      .cancelation .large-desc p {
        margin: 0;
        font-size: 16px;
        color: #888; } }

.wrapper-detailproduct {
  font-size: 16px; }
  .wrapper-detailproduct .container {
    padding-top: 100px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-detailproduct .container {
        padding-top: 0; } }
  @media (min-width: 426px) and (max-width: 768px) {
    .wrapper-detailproduct .thumbnails {
      clear: none; }
    .wrapper-detailproduct .wrapper-prop {
      clear: both; } }
  .wrapper-detailproduct .slider {
    text-align: center; }
    .wrapper-detailproduct .slider .slick-track {
      height: 250px; }
    .wrapper-detailproduct .slider .slick-slide {
      background-size: 100% 100%; }
  .wrapper-detailproduct .container__review {
    font-family:  "Montserrat",sans-serif;
    font-weight: bold; }
    .wrapper-detailproduct .container__review .item {
      border-top: 1px solid #C7C7C7;
      padding: 20px 0;
      font-size: 15px;
      font-weight: bold;
      color: grey; }
      .wrapper-detailproduct .container__review .item h5 {
        font-family:  "Montserrat",sans-serif;
        font-size: 25px;
        font-weight: bold; }
      .wrapper-detailproduct .container__review .item .item__opinion {
        margin: 30px 0; }
        .wrapper-detailproduct .container__review .item .item__opinion h4 {
          font-family:  "Montserrat",sans-serif;
          font-weight: bold; }
        .wrapper-detailproduct .container__review .item .item__opinion strong {
          font-weight: bold;
          font-family:  "Montserrat",sans-serif;
          font-size: 18px;
          color: black; }
  .wrapper-detailproduct .wrapper-prop {
    margin-top: -50px;
    margin-bottom: 20px; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-detailproduct .wrapper-prop {
        padding-top: 25px;
        clear: both; }
        .wrapper-detailproduct .wrapper-prop .desc__properties {
          display: block; } }
  .wrapper-detailproduct .thumbnails .list {
    padding-top: 20px; }
    .wrapper-detailproduct .thumbnails .list .item {
      display: inline-block;
      margin: 10px; }
  @media (min-width: 320px) and (max-width: 425px) {
    .wrapper-detailproduct .thumbnails {
      display: none; } }
  .wrapper-detailproduct .wrap-addcar {
    text-align: center; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-detailproduct .wrap-addcar {
        text-align: center; } }
    @media (min-width: 426px) and (max-width: 768px) {
      .wrapper-detailproduct .wrap-addcar {
        text-align: left;
        margin-bottom: 20px; } }
    .wrapper-detailproduct .wrap-addcar .add-cart {
      width: 165px;
      text-align: center;
      margin: 10px auto; }
      @media (min-width: 320px) and (max-width: 425px) {
        .wrapper-detailproduct .wrap-addcar .add-cart {
          margin: 10px auto; } }
      @media (min-width: 426px) and (max-width: 768px) {
        .wrapper-detailproduct .wrap-addcar .add-cart {
          margin: 10px; } }
    .wrapper-detailproduct .wrap-addcar .add-cart-btn img {
      margin: 0 10px; }
  .wrapper-detailproduct .score-chapter__star-ratings {
    font-size: 20px;
    height: auto;
    display: inline-block;
    margin-right: 10px;
    position: relative;
    padding: 0; }
    .wrapper-detailproduct .score-chapter__star-ratings .star-ratings__top {
      color: #fff100;
      padding: 0;
      position: absolute;
      z-index: 1;
      display: block;
      left: 0;
      overflow: hidden; }
    .wrapper-detailproduct .score-chapter__star-ratings .star-ratings__bottom {
      z-index: 0; }
  .wrapper-detailproduct .score-chapter__chapter {
    text-align: center;
    position: absolute;
    bottom: 0;
    padding: 30px; }
    .wrapper-detailproduct .score-chapter__chapter h5 {
      font-size: 2em;
      color: white; }

.wrapper-moddir .container {
  padding-top: 50px; }

@media (min-width: 320px) and (max-width: 425px) {
  .wrapper-moddir .btn-ganolife {
    display: block;
    float: none; } }

@media (min-width: 769px) and (max-width: 1440px) {
  .wrapper-moddir .btn-ganolife {
    float: right; } }

.wrapper-policy--terms .strong, .wrapper-policy--terms strong {
  font-weight: bold;}

.wrapper-policy {
  background-color: #f7f7f7; }
  .wrapper-policy .container {
    padding-top: 100px;
    font-size: 20px;
    font-weight: bold;
    text-align: justify; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-policy .container {
        padding-top: 20px;
        font-size: 18px; } }
  .wrapper-policy h4 {
    font-size: 28px;
    margin-bottom: 40px;
    text-align: center;
    font-weight: bold;
    color: #555; }
    @media (min-width: 320px) and (max-width: 425px) {
      .wrapper-policy h4 {
        padding-top: 20px;
        font-size: 20px; } }
  .wrapper-policy .subtitle {
    margin: 20px 0px;
    display: block;
    color: #777; }
  .wrapper-policy p, .wrapper-policy ul, .wrapper-policy ol {
    color: grey; }
  .wrapper-policy .last {
    margin-bottom: 50px; }

body,
html {
  height: 100%; }

/*Opera Fix*/
body:before {
  content: "";
  height: 100%;
  float: left;
  width: 0;
  margin-top: -32767px; }

.wrapper-general { min-height: 100%; background:#ffffff;}

.wrapper-content {
  overflow: auto; }

.form-ganolife input, .form-ganolife textarea, .form-ganolife select {
  outline: none !important;
  border-radius: 0  }

.form-ganolife .form-control:focus {
  box-shadow: inherit !important;
  border-color: #ccc; }

.form-ganolife .error-input {
  border: solid #FF6666 1px; }

.clear {
  overflow: hidden; }

body,
html {

  background: #E9E9E9; }


