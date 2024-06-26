/*-----------------------------------------------*/
/*	REBOOT
/*-----------------------------------------------*/

 
:root {
  scroll-behavior: smooth;
--ppt-border-grey: #e0e0e0;
}
*,::after,::before{box-sizing:border-box}html{font-family:sans-serif;line-height:1.15;-webkit-text-size-adjust:100%;-webkit-tap-highlight-color:transparent}article,aside,figcaption,figure,footer,header,hgroup,main,nav,section{display:block}

body{}[tabindex="-1"]:focus{outline:0!important}hr{box-sizing:content-box;height:0;overflow:visible}h1,h2,h3,h4,h5,h6{margin-top:0;margin-bottom:.5rem}p{margin-top:0;margin-bottom:1rem}abbr[data-original-title],abbr[title]{text-decoration:underline;-webkit-text-decoration:underline dotted;text-decoration:underline dotted;cursor:help;border-bottom:0;-webkit-text-decoration-skip-ink:none;text-decoration-skip-ink:none}address{margin-bottom:1rem;font-style:normal;line-height:inherit}dl,ol,ul{margin-top:0;margin-bottom:1rem}ol ol,ol ul,ul ol,ul ul{margin-bottom:0}dt{font-weight:700}dd{margin-bottom:.5rem;margin-left:0}blockquote{margin:0 0 1rem}b,strong{font-weight:bolder}small{font-size:80%}sub,sup{position:relative;font-size:75%;line-height:0;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}a{color:#1075d3;text-decoration:none;background-color:transparent}a:hover{color:#0056b3;text-decoration:underline}a:not([href]):not([class]){color:inherit;text-decoration:none}a:not([href]):not([class]):hover{color:inherit;text-decoration:none}code,kbd,pre,samp{font-family:SFMono-Regular,Menlo,Monaco,Consolas,"Liberation Mono","Courier New",monospace;font-size:1em}pre{margin-top:0;margin-bottom:1rem;overflow:auto;-ms-overflow-style:scrollbar}figure{margin:0 0 1rem}img{vertical-align:middle;border-style:none}svg{overflow:hidden;vertical-align:middle}table{border-collapse:collapse}caption{padding-top:.75rem;padding-bottom:.75rem;color:#6c757d;text-align:left;caption-side:bottom}th{text-align:inherit;text-align:-webkit-match-parent}label{display:inline-block;margin-bottom:.5rem}button{border-radius:0}button:focus{outline:0}button,input,optgroup,select,textarea{margin:0;font-family:inherit;font-size:inherit;line-height:inherit}button,input{overflow:visible}button,select{text-transform:none}[role=button]{cursor:pointer}select{word-wrap:normal}[type=button],[type=reset],[type=submit],button{-webkit-appearance:button}[type=button]:not(:disabled),[type=reset]:not(:disabled),[type=submit]:not(:disabled),button:not(:disabled){cursor:pointer}[type=button]::-moz-focus-inner,[type=reset]::-moz-focus-inner,[type=submit]::-moz-focus-inner,button::-moz-focus-inner{padding:0;border-style:none}input[type=checkbox],input[type=radio]{box-sizing:border-box;padding:0}textarea{overflow:auto;resize:vertical}fieldset{min-width:0;padding:0;margin:0;border:0}legend{display:block;width:100%;max-width:100%;padding:0;margin-bottom:.5rem;font-size:1.5rem;line-height:inherit;color:inherit;white-space:normal}progress{vertical-align:baseline}[type=number]::-webkit-inner-spin-button,[type=number]::-webkit-outer-spin-button{height:auto}[type=search]{outline-offset:-2px;-webkit-appearance:none}[type=search]::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{font:inherit;-webkit-appearance:button}output{display:inline-block}summary{display:list-item;cursor:pointer}template{display:none}[hidden]{display:none!important}

/*-----------------------------------------------*/
/*	00 - RTL
/*-----------------------------------------------*/

body.rtl #wrapper.toggled #sidebar-wrapper{margin-right:0!important}
body.rtl .card-filter .badge-pill{margin-left:10px!important;margin-top:3px}
body.rtl .fa-angle-right:before{content:"\f104"!important} 
body.rtl .inlineicon{right:unset!important;left:10px}
body.rtl .bg-image{transform:scaleX(1)}

.bg-pos-bottom { background-position:bottom!important; }

/*------------------------------------------*/
/*	Typography
/*------------------------------------------*/

body,html{-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}
body { margin: 0; font-size: 16px;    font-weight: 400;    line-height: 1.5;    color: #212529;    text-align: left; overflow-x:hidden;background:#fafafb }

.h1,.h2,.h3,.h4,.h5,.h6,h1,h2,h3,h4,h5,h6{margin: 0; font-weight:500;line-height:1.2; }
.h1,h1{font-size:2.5rem}
.h2,h2{font-size:2rem}
.h3,h3{font-size:1.75rem}
.h4,h4{font-size:1.5rem}
.h5,h5{font-size:1.25rem}
.h6,h6{font-size:1rem}

.lead{font-size:1.25rem;font-weight:300}

hr{margin-top:1rem;margin-bottom:1rem;border:0;border-top:1px solid rgba(0,0,0,.1)}

.small,small{font-size:80%;}

date { border-bottom: 1px dotted #ddd; }

@media (max-width: 575.98px) {

h1{font-size:30px}
.hero-default h1 { font-size:36px; }
h2{font-size:26px!important}
h3{font-size:16px!important}
h4{font-size:16px!important}
h5{font-size:16px!important}
h6{font-size:16px!important}
.lead{font-size:14px!important}
p { font-size:14px; }

.block-cat-listings h2, .block-cat-store h2, .block-cat-stores h2, .block-cat-category h2, .block-cat-store h1, .block-cat-stores h1, .block-cat-category h1, .block-cat-store h4, .block-cat-stores h4, .block-cat-category h4 { font-size: 16px !important; }

}

.mr-4 { margin-right:20px; }
.mr-2 { margin-right: 0.5rem;}
.ml-4 { margin-left: 1.5rem;}
.mr-3 {  margin-right: 1rem;}
.pl-3 {  padding-left: 1rem; }
.pl-4 {  padding-left: 1.5rem;}

ul, ol {   padding-left: 0;    list-style: none; margin:0px; }
ul li { margin:0px; }
p { margin-top: 0;    margin-bottom: 15px; font-size: 16px;  }

.fs-xxl {  font-size: 4.20875rem;    line-height: 1; letter-spacing: -0.01em; }
.fs-1, .fs-xl {  font-size: calc(1.375rem + 1.4vw) !important; }
.fs-2, .fs-lg {  font-size: calc(1.325rem + 0.9vw) !important;}
.fs-3 {  font-size: calc(1.3rem + 0.6vw) !important;}
.fs-4, .fs-md {  font-size: calc(1.275rem + 0.3vw) !important;}
.fs-5 {  font-size: 1.25rem !important;}
.fs-6 {  font-size: 18px !important; }
.fs-xs {    font-size: 10px !important;}
.fs-sm {    font-size: 12px !important;}
.fs-14 {    font-size: 14px !important;}
.fs-16 {    font-size: 16px !important;}
.fs-18 {    font-size: 18px !important;}

.lh-10 { line-height:20px!important}
.lh-20 { line-height:20px!important}
.lh-30 { line-height:30px!important}
.lh-40 { line-height:40px!important}

.lh-90 { line-height:90px!important}
@media (max-width:576px){ 
.lh-40 { line-height:25px!important}
.lh-90 {    line-height: 50px!important; }
}

.text-300{font-weight:300!important}
.text-400{font-weight:400!important}
.text-600{font-weight:600!important}
.text-500{font-weight:500!important}
.text-700{font-weight:700!important}
.text-800{font-weight:800!important}

.w-100 { width:100%; }
.text-wrap {    white-space: normal!important;}
.text-truncate{overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.text-center { text-align: center;}
.text-muted a{color:#6c757d!important}

body:not(.rtl) .text-left{text-align:left}
body:not(.rtl) .text-right{text-align:right}
body:not(.rtl) .text-center{text-align:center}
@media (min-width:576px){ body:not(.rtl) .text-sm-left{text-align:left} body:not(.rtl) .text-sm-right{text-align:right} body:not(.rtl) .text-sm-center{text-align:center}}
@media (min-width:768px){ body:not(.rtl) .text-md-left{text-align:left} body:not(.rtl) .text-md-right{text-align:right} body:not(.rtl) .text-md-center{text-align:center}}
@media (min-width:992px){ body:not(.rtl) .text-lg-left{text-align:left} body:not(.rtl) .text-lg-right{text-align:right} body:not(.rtl) .text-lg-center{text-align:center}}
@media (min-width:1200px){ body:not(.rtl) .text-xl-left{text-align:left} body:not(.rtl) .text-xl-right{text-align:right} body:not(.rtl) .text-xl-center{text-align:center}}

.opacity-8{opacity:.8!important}
.opacity-5{opacity:.5}
.opacity-2{opacity:.2}

.strike { text-decoration-line: line-through; }

.position-relative { position:relative }
.position-absolute { position:absolute; }

.text-decoration-none { text-decoration: none!important; }

.link-dark a {    color: #333!important;}
.link-light a {   color: #fff!important;}

.cursor { cursor:pointer; }
.text-shadow-white {  text-shadow: 1px 1px 1px #ffffff; }

.text-shadow-sm { text-shadow: rgb(0 0 0 / 15%) 1px 1px 1px; }


.group-circle span { width:40px; height:40px; border-radius:100%; line-height: 25px; font-size:12px; font-weight:600; text-align: center; display: inline-block; border: 2px solid #fff; box-shadow: 0 1px 2px 0 rgb(0 0 0 / 5%)!important; outline-color: var(--ppt-border-grey);   outline-width: thin;    outline-style: solid; }
.group-circle.sm span { width:25px; height:25px;}
.group-circle.sm2 span { width:unset; height:25px; border-radius:10px; border:0px;     border-radius: 4px;   padding: 0px 5px;   }
.group-circle.sm span+span { margin-left:-10px; }

.ppt-line { position:relative; }
.ppt-line-10 { display:inline-block; height:1px; width: 100%;    position: absolute;    bottom: 0;    left: 0; }
.ppt-line-11 { display:inline-block; height:2px; width: 100%;    position: absolute;    bottom: 0;    left: 0; }
.ppt-line-12 { display:inline-block; height:4px; width: 100%;    position: absolute;    bottom: 0;    left: 0; }
.ppt-line-13 { display:inline-block; height:5px; width: 100%;    position: absolute;    bottom: 0;    left: 0; }

.maxh-60 { max-height: 60px;    overflow: hidden;}

.border-bottom-white-50 { border-bottom: 1px solid #ffffff66!important; }

.ppt-single-desc ul, .ppt-single-desc ol {
  padding-left: revert!important;
  list-style: revert!important;
}

/*------------------------------------------*/
/*	Gradients
/*------------------------------------------*/

.ppt-gradient1 { background-image: linear-gradient(280deg, #6787FE 0%, #0F1B63 100%); }
.ppt-gradient2 { background: #34e89e;  background: -webkit-linear-gradient(to right, #0f3443, #34e89e);background: linear-gradient(to right, #0f3443, #34e89e); }
.ppt-gradient3 { background-image: linear-gradient(to right, #6a11cb 0%, #2575fc 100%); }
.ppt-gradient4 { background-image: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
.ppt-gradient5 {  background-image: linear-gradient(to top, #e6e9f0 0%, #eef1f5 100%); }
.ppt-gradient6 { background-image: linear-gradient(to top, #accbee 0%, #e7f0fd 100%);}

.ppt-gradient7 {     background-image: linear-gradient(130.92deg, rgb(58, 28, 113) -14.59%, rgb(215, 109, 119) 38.47%, rgb(255, 175, 123) 98.62%); }

.ppt-gradient-red {  background-image: linear-gradient(to top, #860000 0%, #ee0808 100%); }
.ppt-gradient-blue { background-image: linear-gradient(to top, #4481eb 0%, #04befe 100%); }

.ppt-gradient-blue2 { background-image: linear-gradient(to top, #1e3c72 0%, #1e3c72 1%, #2a5298 100%); }



/*------------------------------------------*/
/*	 Overlays
/*------------------------------------------*/
.z-1 { z-index:1!important; }
.bg-overlay-dark, .overlay-inner{position:absolute;top:0;left:0;width:100%;height:100%;background:#000;opacity:.5;z-index:0}
.bg-overlay-grey{background:#363f48;position:absolute;top:0;left:0;width:100%;height:100%;opacity:.8;z-index:0}
.bg-overlay-primary{position:absolute;top:0;left:0;width:100%;height:100%;opacity:.8;z-index:0}
.bg-overlay-secondary{position:absolute;top:0;left:0;width:100%;height:100%;opacity:.8;z-index:0}.bg-overlay-black{background:#000;position:absolute;top:0;left:0;width:100%;height:100%;opacity:.8;z-index:0}.bg-overlay-white{background:#fff;position:absolute;top:0;left:0;width:100%;height:100%;opacity:.8;z-index:0}.bg-overlay-green{background:#02913c;position:absolute;top:0;left:0;width:100%;height:100%;opacity:.8;z-index:0}.bg-content{z-index:2;position:relative}.bg-pattern{position:absolute;top:0;left:0;width:100%;height:100%;z-index:1;background-size:cover;background-attachment:scroll;background-position:center;background-repeat:repeat;background-origin:content-box;opacity:.1}.bg-pattern-small{position:absolute;top:0;left:0;width:100%;height:100%;z-index:0;background-attachment:scroll;background-position:center;background-repeat:repeat;background-origin:content-box;opacity:.1}
.bg-image,.bg-inner{position:absolute;top:0;left:0;width:100%;height:100%;z-index:0;background-size:cover;background-attachment:scroll;background-position:center;background-repeat:repeat;background-origin:content-box}

.tall-images .bg-image {background-position:top; }

.bg-image-centered .bg-image { background-repeat:no-repeat !important; background-size:contain!important; }
.bg-h100{background-position:center;background-size:cover;background-repeat:no-repeat;height:100vh;margin:0}

.bg-cover{background-position:center center!important;background-repeat:no-repeat!important;background-size:cover!important;overflow:hidden;position:relative}

.bg-gradient,.bg-overlay-gradient{background:-webkit-gradient(linear,left top,left bottom,color-stop(0,rgba(6,27,65,0)),color-stop(100%,rgba(49,49,49,.95)));background:-webkit-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);background:-o-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);background:-ms-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);background:linear-gradient(to bottom,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);position:absolute;top:0;left:0;width:100%;height:100%;z-index:1;background-size:cover}

.bg-gradient-left, .bg-overlay-gradient-left   { background: -webkit-linear-gradient(190deg,rgba(6,27,65,0) 0,rgb(0 0 0 / 95%) 100%); background: linear-gradient(260deg,rgba(6,27,65,0) 0,rgb(0 0 0 / 95%) 100%); position: absolute;    top: 0;    left: 0;    width: 100%;    height: 100%;    z-index: 1;    background-size: cover;}

.bg-gradient-left-white, .bg-overlay-gradient-left-white   { background: -webkit-linear-gradient(190deg,rgba(6,27,65,0) 0,rgb(255 255 255 / 95%) 100%); background: linear-gradient(260deg,rgba(6,27,65,0) 0,rgb(255 255 255 / 95%) 100%); position: absolute;    top: 0;    left: 0;    width: 100%;    height: 100%;    z-index: 1;    background-size: cover;}



.bg-overlay-gradient-left-small   { background: -webkit-linear-gradient(190deg,rgba(6,27,65,0) 0,rgb(0 0 0 / 32%) 100%);
  background: linear-gradient(260deg,rgba(6,27,65,0) 0,rgb(0 0 0 / 34%) 100%); position: absolute;    top: 0;    left: 0;    width: 100%;    height: 100%;    z-index: 1;    background-size: cover;}

.bg-overlay-gradient-left-small-white  { background: -webkit-linear-gradient(190deg,rgba(6,27,65,0) 0,rgb(255 255 255 / 32%) 100%);
  background: linear-gradient(260deg,rgba(6,27,65,0) 0,rgb(255 255 255 / 34%) 100%); position: absolute;    top: 0;    left: 0;    width: 100%;    height: 100%;    z-index: 1;    background-size: cover;}



@media (max-width: 575.98px) { 
.bg-gradient-left, .bg-overlay-gradient-left { background:#000!important; opacity:0.6 }
}

.bg-gradient-none{background:-webkit-gradient(linear,left top,left bottom,color-stop(0,rgba(6,27,65,0)),color-stop(100%,rgba(49,49,49,.95)));background:-webkit-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);background:-o-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);background:-ms-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);background:linear-gradient(to bottom,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%)}

.bg-gradient-small{background:-webkit-gradient(linear,left top,left bottom,color-stop(0,rgba(6,27,65,0)),color-stop(100%,rgba(49,49,49,.2)));background:-webkit-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.2) 100%);background:-o-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.2) 100%);background:-ms-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.2) 100%);background:linear-gradient(to bottom,rgba(6,27,65,0) 0,rgba(49,49,49,.2) 100%);position:absolute;top:0;left:0;width:100%;height:100%;z-index:1;background-size:cover}.bg-wrap{float:left;width:100%;position:relative;z-index:100}

/*------------------------------------------*/
/*	Containers 
/*------------------------------------------*/

.container-slim { max-width:1000px; margin: auto; }

@media (min-width:1500px){
.container, .container-lg, .container-md, .container-sm { max-width:1300px!important; }
}

/*------------------------------------------*/
/*	resonsive
/*------------------------------------------*/

.show-mobile, .show-mobile-inline, .show-ipad { display:none; }
.show-desktop-lg { display:none; }

@media (min-width: 1300px) {  
.show-desktop-lg { display:block !important;  } 
}

/* desktop */
@media (min-width: 992px) {  
.hide-desktop, .show-mobile, .show-mobile-inline { display:none !important; }
}

/* ipad */
@media (min-width: 576px) and (max-width: 991.98px) { 

.show-desktop { display:none !important; }
.show-ipad { display:block !important; }
.hide-ipad, .show-mobile:not(.show-ipad) { display:none !important; }

}

/* mobile */
@media (max-width: 575.98px) { 

.show-desktop, .show-ipad:not(.show-mobile), .hide-ipad, .hide-desktop { display:none !important; }
.hide-mobile { display:none !important; }
.show-mobile { display:block ; }
a.show-mobile, .show-mobile-inline {  display:inline-block !important;}

.card-mobile-transparent { border:0px!important; background:none; box-shadow:none !important; background-color:transparent!important; }
.card-mobile-transparent .card-body { padding:0px; }

}


/*------------------------------------------*/
/*	Colors
/*------------------------------------------*/

.bg-white {    background-color: #fff; }
.bg-black {    background-color: #000; }
.bg-dark { background:#212122; }
.bg-soft { background-color:#fafafb; }
.bg-light{background-color:#fafafb; }

.text-light, .text-white { color:#fff; }
.text-black { color:#000; }
.text-green, .text-success { color:green; }
.text-red, .text-danger { color:red; }
.text-dark { color: #343a40; }

/*------------------------------------------*/
/*	Images
/*------------------------------------------*/

.img-fluid { max-width:100%; }
img, svg {    vertical-align: middle; }

.hover-jump {-webkit-backface-visibility: hidden;    -moz-backface-visibility: hidden;    transform: translateY(0);    transition: all .3s ease; }
.hover-jump:hover {    transform: translateY(-0.4rem);    box-shadow: 0 0.25rem 1.25rem rgb(52 63 82 / 10%); }

/*------------------------------------------*/
/*	SVG Icons
/*------------------------------------------*/


.ppt-icon-svg { width:32px; height:32px; display: inline-block; }

[ppt-icon-16] svg, [ppt-icon-size="16"] svg { width:16px; height:16px; }
[ppt-icon-20] svg, [ppt-icon-size="20"] svg { width:20px; height:20px; }
[ppt-icon-24] svg, [ppt-icon-size="24"] svg { width:24px; height:24px; }
[ppt-icon-32] svg, [ppt-icon-size="32"] svg { width:32px; height:32px; }
[ppt-icon-48] svg, [ppt-icon-size="48"] svg { width:48px; height:48px; }
[ppt-icon-64] svg, [ppt-icon-size="64"] svg { width:48px; height:48px; }

@media (min-width: 1200px) { 
[ppt-icon-64] svg, [ppt-icon-size="64"] svg { width:64px; height:64px; }

}
@media (max-width: 575.98px) { 
[ppt-icon-64] svg, [ppt-icon-size="64"] svg { width:32px; height:32px; }
}

.likesbar20 svg { 	width: 20px!important;    height: 20px!important;	}

/*------------------------------------------*/
/*	Shadows  
/*------------------------------------------*/
.shadow-0 { box-shadow:none!important }
.shadow {    box-shadow: 0 .5rem 1rem rgba(0,0,0,.15)!important; }
.shadow-sm {   box-shadow: 0 1px 2px 0 rgb(0 0 0 / 5%)!important; }
.shadow-lg {  box-shadow: 0 5px 5px 0 rgb(0 0 0 / 5%)!important; }
.shadow-xl {  box-shadow: 0 5px 5px 0 rgb(0 0 0 / 10%)!important; }
.shadow-hover-lg:hover { box-shadow: 0 5px 5px 0 rgb(0 0 0 / 5%)!important;  }

/*------------------------------------------*/
/*	Cards
/*------------------------------------------*/


.card {    position: relative;    display: -ms-flexbox;    display: flex;    -ms-flex-direction: column;    flex-direction: column;    min-width: 0;    word-wrap: break-word;    background-color: #fff;    background-clip: border-box;    border: 1px solid var(--ppt-border-grey);     border-radius: 0.25rem; }
.card-body {    -ms-flex: 1 1 auto;    flex: 1 1 auto;    min-height: 1px;    padding: 1.25rem;}

/*------------------------------------------*/
/*	Alert
/*------------------------------------------*/

[ppt-alert] { position: relative;    padding: 0.75rem 1.25rem;    margin-bottom: 1rem;    border: 1px solid transparent;    border-radius: 0.25rem; }


/*------------------------------------------*/
/*	Show/Hide
/*------------------------------------------*/

.ppt-show-hide { cursor:pointer; }
.ppt-accordion:not(.show) .hide, .ppt-show-hide:not(.show) .hide { display:none; }
.ppt-accordion.show .hide-show, .ppt-show-hide.show .hide-show { display:none; }
.ppt-accordion .show-hide, .ppt-show-hide .show-hide { display:none; }
.ppt-accordion.show .show-hide, .ppt-show-hide.show  .show-hide { display:inline-block!important; }

/*------------------------------------------*/
/*	Buttons
/*------------------------------------------*/

[data-ppt-btn] { display: inline-block; text-align: center;  white-space: nowrap;  vertical-align: middle; user-select: none;   padding: 0 20px;font-size: 16px;font-weight: 500;line-height: 40px; cursor: pointer;    z-index: 5;    transition: all 0.4s linear;  border-radius: 4px; position: relative;    background-color: transparent; }
[data-ppt-btn]:not(.btn-system)::before {    position: absolute;    content: '';    top: 50%;    left: 50%;    width: 0;    height: 0;    padding: 50%;    border-radius: 50%; background-color: rgb(255 255 255 / 15%);    z-index: -1;    color: #fff;    transform: translate3d(-50%, -50%, 0) scale(0);    transition: all 0.4s linear;}
[data-ppt-btn].btn-block, [data-ppt-btn].btn-lg { overflow:hidden; }
[data-ppt-btn]:not(.btn-system, .btn-num):hover::before { transform: translate3d(-50%, -50%, 0) scale(1.5);}
[data-ppt-btn].btn-primary, [data-ppt-btn].btn-secondary, [data-ppt-btn].btn-dark, [data-ppt-btn].btn-light, [data-ppt-btn].btn-system, [data-ppt-btn].btn-success, [data-ppt-btn].btn-danger, [data-ppt-btn].btn-orange, [data-ppt-btn].btn-warning { border: 1px solid #3636367d!important; }
[data-ppt-btn]:not(.shadow-0){box-shadow: 0 1px 2px 0 rgb(0 0 0 / 10%);}

[data-ppt-btn].btn-primary { background-color: #2371b1; color:#fff; }
[data-ppt-btn].btn-secondary { background-color: #f9ba0a; color:#fff; }
[data-ppt-btn].btn-success { background-color: #008000; color:#fff; }
[data-ppt-btn].btn-danger { background-color: #d63638; color:#fff; }
[data-ppt-btn].btn-system { border: 1px solid var(--ppt-border-grey)!important; color:#000000; }
[data-ppt-btn].btn-orange, [data-ppt-btn].btn-warning {  background: #fac106; color:#fff; }
[data-ppt-btn].btn-system:hover {    box-shadow: 0 .125rem .25rem rgba(0,0,0,.090); }
[data-ppt-btn].btn-dark { background: #212121; color:#fff; }
[data-ppt-btn].btn-light { color: #212529;    background-color: #f8f9fa;}
[data-ppt-btn],[data-ppt-btn]:hover { text-decoration:none; }
[data-ppt-btn]:not(.btn-icon) i+span { margin-left:10px; }
[data-ppt-btn].btn-sm, [data-ppt-btn].small { padding: 3px 10px; line-height:30px!important; }

[data-ppt-btn].btn-xs { font-size:12px; line-height:20px!important; padding: 0px 10px; }

[data-ppt-btn].btn-lg { font-weight:600; }
@media (min-width: 992px) {
[data-ppt-btn].btn-lg { font-size:18px; line-height:50px!important; padding: 0px 30px; }
[data-ppt-btn].btn-xl { font-size:18px; line-height:50px!important; padding: 5px 35px; } 
body:not(.rtl) [data-ppt-btn]:not(.list)+[data-ppt-btn]:not(.list) { margin-left:10px; }
body.rtl [data-ppt-btn]:not(.list)+[data-ppt-btn]:not(.list) { margin-right:10px; } 
}

.col-xl-6 > [data-ppt-btn].btn-lg { padding: 0px 0px!important; }
.btn-block+.btn-block {    margin-top: 15px!important;}

[data-ppt-btn] .num { position: absolute;    top: -5px;    right: -5px; background: #fff; border-radius: 25px; width: 25px; height: 25px;  color: #000;    font-size: 12px;    line-height: 23px; }

.btn-block {  display: block; width: 100%; }

[data-ppt-btn] .ppt-price{ position: absolute;    padding: 10px;    top: 10px;    background: #fff;    line-height: 10px;    border-radius: 5px;    right: 10px;    color: #000;    border: 1px solid #606060;    font-size: 14px;}

/* with icons */
.btn-icon:not(.icon-none) { padding:0px; text-align:left;  }
.btn-icon i, .btn-icon .icon-svg {  width:40px; height:40px; text-align:center; line-height:40px; min-width: 30px; display:inline-block;   }
.btn-icon.btn-sm i, .btn-icon.btn-sm .icon-svg {  width:30px; height:30px; text-align:center; line-height:30px; min-width: 30px; display:inline-block;   }
body:not(.rtl) .btn-icon.btn-xl i, body:not(.rtl) .btn-icon.btn-lg i, body:not(.rtl) .btn-icon.btn-lg .icon-svg  {  width:50px; height:50px; text-align:center; line-height:50px; min-width: 50px; display:inline-block;}

[data-ppt-btn]:not(.btn-block).btn-icon.icon-before { padding-right:20px; }
[data-ppt-btn]:not(.btn-block).btn-icon.icon-after { padding-left:20px; }

.btn-icon.icon-before i, .btn-icon.icon-before .icon-svg { border-right:1px solid #dddddd4d; margin-right:15px;   }
[data-ppt-btn]:not(.btn-block) .btn-icon.icon-before .icon-svg  { margin-right:20px;  }

body:not(.rtl) .btn-icon.icon-after .icon-svg { border-left:1px solid #dddddd4d;  margin:0px 20px;    }

body:not(.rtl) .btn-icon.icon-after i { border-left:1px solid #dddddd4d;  margin-left: 20px;}

.btn-icon ._icon i { font-size:100% !important; }
.btn-icon.icon-before {display: -ms-flexbox!important;    display: inline-flex!important;}
.btn-icon.btn-lg.icon-before span, .btn-icon.btn-xl.icon-before span { text-align: center;    width: 100%;    line-height: 50px;  } 

[data-ppt-btn].btn-sm.btn-icon svg { width:16px; height:16px; }
[data-ppt-btn]:not(.btn-sm, .btn-lg).btn-icon svg { width:24px; height:24px; }
[data-ppt-btn].btn-lg.btn-icon svg, [data-ppt-btn].btn-xl.btn-icon svg { width:32px; height:32px; }
[data-ppt-btn].btn-icon.icon-before .icon-svg { margin-right:20px; }

.btn-icon.icon-after span { padding-left:20px; }

/*------------------------------------------*/
/*	Rounded
/*------------------------------------------*/
.rounded-0 { border-radius:0px!important; }
.rounded { border-radius: 4px !important;}
.rounded-10 { border-radius: 10px !important; }
.rounded-20 { border-radius: 20px !important; }
.rounded-pill { border-radius: 25px !important; }

/*------------------------------------------*/
/*	Borders
/*------------------------------------------*/

[ppt-border1] { box-shadow: 0 1px 2px 0 rgb(0 0 0 / 5%);    background-color: #fff;    background-clip: border-box;    border: 1px solid var(--ppt-border-grey);    border-radius: 0.25rem; }
[ppt-border2] { border: 1px solid #e7edf3;    box-shadow: 1px 1px 0 0 rgb(196 196 196 / 24%);  background: #fff;  }


.border-top-0 {    border-top: 0!important;} 
.border-0 { border: 0!important; }
.border{border:1px solid var(--ppt-border-grey)}
.border-2{border:2px solid var(--ppt-border-grey)}
.border-top{border-top:1px solid #f2f2f2}
.border-right{border-right:1px solid #dee2e6}
.border-bottom{border-bottom:1px solid #f2f2f2}
.border-left{border-left:1px solid #dee2e6}

/*------------------------------------------*/
/*	Spacing & Alignment   
/*------------------------------------------*/

section { color:#000; }

@media (min-width: 575.98px) { 


.section-60, [data-padding="section-60"] {padding:60px 0!important}
.section-120, [data-padding="section-120"] {padding:120px 0!important}
.section-100, [data-padding="section-100"] {padding:100px 0!important}
.section-80, [data-padding="section-80"] {padding:80px 0!important}

.section-40, [data-padding="section-40"] {padding:40px 0!important}
.section-20, [data-padding="section-20"] {padding:20px 0!important}

.section-top-40, [data-padding="section-top-40"] {padding:40px 0px 0px 0px!important; }
.section-top-80, [data-padding="section-top-80"]{padding-top:80px!important}
.section-top-60, [data-padding="section-top-60"] {padding:60px 0px 0px 0px!important; }
.section-top-100, [data-padding="section-top-100"]{padding-top:100px!important}
.section-bottom-40, [data-padding="section-bottom-40"] {padding:0px 0px 40px 0px!important; }
.section-bottom-80, [data-padding="section-bottom-80"]{padding-bottom:80px!important}
.section-bottom-60, [data-padding="section-bottom-60"] {padding:0px!important; padding-bottom:60px!important;  }
.section-bottom-100, [data-padding="section-bottom-100"]{padding-bottom:100px!important}

}
@media (max-width: 575.98px) { 

[data-padding], .section-120, .section-100, .section-80, .section-60 { padding: 40px 0px !important;   }
.section-40 { padding: 20px 0px !important;}
.section-top-80 { padding-top:40px !important; }
}

.section-divider-after{padding-bottom:60px}
[data-padding="section-none"] { padding:0px; }

section.bg-dark,section.bg-dark h3{color:#fff}
section.bg-dark h3 .text-dark{color:#fff!important}
section.bg-dark .text-muted{color:#fff!important}
section.bg-dark .bg-white h2,section.bg-dark .bg-white h3{color:#222!important}
section.bg-dark .bg-white .text-muted{color:#222!important;opacity:.5}
section.bg-primary>h3{color:#fff}section.bg-primary>.text-muted{color:#fff!important}
section.bg-primary>.text-primary{color:#fff!important}

section{position:relative}
section h1, section h2, section h3 {line-height:1.5}

section .hero_box h1{font-size:34px}
section .hero_box p{margin-bottom:20px!important}
section.with-pattern .container,section.with-pattern .container-fluid{z-index:100;position:relative}

.mb-8 { margin-bottom:80px }
.mb-10 { margin-bottom:100px }

.mt-8 { margin-top:80px }
.mt-10 { margin-top:100px }

.mt-n10 { margin-top:-100px; }
.mt-n20 { margin-top:-200px; }

.mb-n10 { margin-bottom:-100px; }
.mb-n20 { margin-bottom:-200px; }

.hero-padding-top-140 { padding-top:140px; }
.hero-padding-top-200 { padding-top:200px; }

/* ipad */
@media (min-width: 576px) and (max-width: 991.98px) { 

/* padding and spacing */ 	
.mb-4 { margin-bottom:20px !important; }
.mb-5 { margin-bottom:20px !important; }
.mt-5 { margin-top:20px !important; }
.mt-4 { margin-top:20px !important; }


}

/* mobile */
@media (max-width: 575.98px) { 

.mobile-text-center { text-align:center; }

.hero-padding-top-140 { padding-top:40px; }
.hero-padding-top-200 { padding-top:70px; }

.mb-n10 { margin-bottom:0px!important; }
.mb-n20 { margin-bottom:0px!important; }
.mt-n10 { margin-top:0px!important; }
.mt-n20 { margin-top:0px!important; }


.pb-0 { padding-bottom:0px !important; }
.mobile-nopadding { padding:0px !important; }
.mb-4 { margin-bottom:15px !important; }
.mb-5 { margin-bottom:20px !important; }
.mt-5:not(.btn) { margin-top:10px !important; }
.mt-4:not(.btn) { margin-top:10px !important; }

.mobile-mt-4 { margin-top:40px; }
.mobile-mb-2 { margin-bottom:20px !important; }
.mobile-mb-4 { margin-bottom:40px !important; }
.mobile-mb-6 { margin-bottom:60px !important; }
.mobile-pt-4 { padding-top:40px; }
.mobile-pb-4 { padding-bottom:40px; }

.mobile-pt-10 { padding-top:100px!important; }

.mobile-mb-n5 { margin-bottom:-50px; }


.ppt-divider-2 { height:20px; } 


}
/*------------------------------------------*/
/*	Flex Box
/*------------------------------------------*/

.vertical-center-abs,.vertical-center-rel{top:50%;-webkit-transform:translateY(-50%);-moz-transform:translateY(-50%);-o-transform:translateY(-50%);-ms-transform:translateY(-50%);transform:translateY(-50%)}
.vertical-center-abs{position:absolute}
.vertical-center-rel{position:relative}
.vh-center{position:absolute;top:50%;left:50%;margin-right:-50%;-webkit-transform:translate(-50%,-50%);-moz-transform:translate(-50%,-50%);-o-transform:translate(-50%,-50%);-ms-transform:translate(-50%,-50%);transform:translate(-50%,-50%)}
.y-middle{display:-webkit-flex;display:-moz-flex;display:-ms-flexbox;display:flex;align-items:center;-webkit-align-items:center;justify-content:center;-webkit-justify-content:center;flex-direction:row;-webkit-flex-direction:row}


[ppt-flex-middle] {    display: flex;    flex-flow: column;    align-items: center;    justify-content: center;}
[ppt-flex-between] {    display: flex;    flex-flow: row;    align-items: center;    justify-content: space-between;}
[ppt-flex-center] {    display: flex;    flex-flow: row;    align-items: center;    justify-content: flex-start;}
[ppt-flex-end] {    display: flex;    flex-flow: row;    align-items: center;    justify-content: flex-end;}
[ppt-flex-spaced] {    display: flex;    flex: auto ; }


.align_col_center_left {    display: flex;    flex-flow: column;    align-items: flex-start;    justify-content: center;}
.align_col_bottom_left {    display: flex;    flex-flow: column;    align-items: flex-start;    justify-content: flex-end;}
.align_col_center_right {    display: flex;    flex-flow: column;    align-items: flex-end;    justify-content: center;}
.align_col_right_bottom {    display: flex;    flex-flow: column;    align-items: flex-end;    justify-content: flex-end;}
.align_col_center_bottom {    display: flex;    flex-flow: column;    align-items: center;    justify-content: flex-end;}

.align_row_left_top {    display: flex;    flex-flow: row;    align-items: flex-start;    justify-content: flex-start;}


.align_row_center_center {    display: flex;    flex-flow: row;    align-items: center;    justify-content: center;}


/*------------------------------------------*/
/*	Toggles
/*------------------------------------------*/

.filterToggle .toggle-me { cursor:pointer; }
.filterToggle .toggle-me .toggle-off { display:inline-block; }
.filterToggle .toggle-me .toggle-on { display:none; }
.filterToggle .toggle-me.on .toggle-off { display:none; }
.filterToggle .toggle-me.on .toggle-on { display:inline-block; }
.filterToggle .toggle-on, .filterToggle .toggle-off { width: 30px; cursor:pointer; margin-right:10px; }
.filterToggle .toggle-dot { width: 22px; cursor:pointer; margin-right:10px; margin-top: 2px; }
.filterToggle .toggle-favs { width: 22px; cursor:pointer; margin-right:10px; margin-top: 2px; }

.filterSortby {width:100%;  font-weight:600; position: relative;  }
.filterSortby select {   outline: none; -webkit-appearance: none;  -moz-appearance: none;  border: 0px;    background: none;    font-size: 16px;    font-weight: 500; cursor: pointer; width: 100%; padding: 0px 30px 5px 0px; } 
.filterSortby select::-ms-expand {    display: none; }
.filterSortby:after{font-family:"Font Awesome 5 Pro";content:"\f107";position:absolute;color:#000;top:-2px;right:5px;font-size:18px;font-weight:600} 
.filterToggle .toggle-me.on .toggle-dot, .filterToggle .toggle-me.on .toggle-favs { color:#35853e; }

/*-----------------------------------------------*/
/*	ALERTS AND PROCESS BARS
/*-----------------------------------------------*/

.alert{position:relative;     padding: 15px 20px; margin-bottom:1rem;border:1px solid transparent;border-radius:.25rem}
.alert-success {    color: #155724;    background-color: #d4edda;    border-color: #c3e6cb;}

/*------------------------------------------*/
/*	Empty Boxes
/*------------------------------------------*/

.ppt-empty-box { border: 2px dashed #ddd;    background: #f9f9f9;    border-radius: 10px;    line-height: 100px;    padding: 0px 50px;color: #a2a1a1;    text-shadow: 1px 1px #fff; }


/*------------------------------------------*/
/*	Navigation
/*------------------------------------------*/

.demo-nav.show { display:block!important; }

[ppt-nav]:not(.list) > ul {  display: flex; margin:0px; padding:0px; }
[ppt-nav] > ul > li { position: relative; padding: 0px 10px;  }
[ppt-nav] > ul > li a { color:#000; text-decoration:none }
@media (min-width: 1300px){ 
[ppt-nav].spacing > ul > li { padding: 0px 20px!important; }
}
@media (min-width: 991.98px){ 
[ppt-nav].spacing > ul > li { padding: 0px 15px; }
}
[ppt-nav] .new { background: red;    position: absolute;    top: -14px;    right: -10px;    font-size: 10px;    color: #fff;    border-radius: 3px;    padding: 1px 5px; box-shadow: 0 1px 2px 0 rgb(0 0 0 / 5%)!important; }

[ppt-nav].list li { display: flex; justify-content: space-between; margin-bottom: 10px; } 
[ppt-nav].list li:last-child { margin-bottom:0px; }
[ppt-nav].list.list-fbold li > span:first-child { font-weight:600; }
[ppt-nav].list li span { width: 100%; }
[ppt-nav].pl-0 > ul > li:first-child { padding-left:0px; }
[ppt-nav].d-flex > ul > li { line-height:40px; }
[ppt-nav].truncated > ul > li:not(.no-truncate) { overflow: hidden;    text-overflow: ellipsis;    white-space: nowrap;}

[ppt-nav].truncated.grid_bottom > ul > li { max-width:90px; }

[ppt-nav].faded > ul > li > a { opacity:0.5 }

[ppt-nav].active-underline > ul > li.active > a { border-bottom: 2px solid red; opacity:1; }

.list-f100 li { font-size:14px; }
.list-f100 li:first-child { font-size:18px;  }

[ppt-nav].spaced > ul  { display: flex; justify-content: space-between!important; }

body:not(.rtl) [ppt-nav].seperator > ul > li:after{position:absolute;content:'';top:-2px;right:0;bottom:0;height:12px;width:1px;margin:auto; background-color: #0000006b;}

body:not(.rtl) .navbar-dark [ppt-nav].seperator > ul > li:after{ background-color: #ffffff6b; }
body:not(.rtl) [ppt-nav].seperator > ul > li:last-child:after{display:none!important}
body:not(.rtl) [ppt-nav].seperator.crumbs > ul > li:after{ content: ">"!important;font-size: 12px;background: none; top: -7px; line-height: 20px; }


.dropdown:not(.bootstrap-select).show .dropdown-menu { display:block;  z-index: 99; overflow:hidden; padding: 0px; } 
.dropdown:not(.bootstrap-select) .dropdown-menu { position: absolute;top: 0px; left: 0; display: none; padding: 0.5rem 0;  margin: 0.125rem 0 0;  color: #212529; text-align: left; background-color: #fff; border: 1px solid rgba(0,0,0,.15); border-radius: 0.25rem; animation: fadeIn 0.2s linear 1; }

.elementor_submenu .dropdown .dropdown-menu { top: 30px!important; }

.dropdown .dropdown-menu.quick { animation:none!important; }

.dropdown.dropdown-bounce .dropdown-menu {animation: bounceIn 0.4s linear 1; }
.dropdown.dropdown-fadein .dropdown-menu {animation: fadeIn 0.6s linear 1; }

.dropdown .dropdown-menu .dropdown-item { display: block; padding: 10px 15px 10px 15px; font-size: 14px;  clear: both;min-width: 150px; width: 100%; font-weight: 500; border-bottom: 1px solid #ddd;line-height: 30px; }
.dropdown-toggle::after {display:none;  }

.dropdown .dropdown-menu .dropdown-item span {display:inline-block; padding-left:15px; position:relative; }
header .dropdown .dropdown-menu .dropdown-item span:after{ content:""; position:absolute;color:#000;top:11px;left:0px; border-top: 5px solid transparent; border-bottom: 5px solid transparent; border-left: 5px solid #ccc; width: 0;  height: 0;  } 

.dropdown-desc { min-width: 350px; opacity: .3; white-space: normal!important; font-size: 13px;line-height: 20px; margin-top: 5px; }
.dropdown-wrap { padding:10px 0px; }
.dropdown-item { font-weight:600; }
.dropdown-title { font-weight:600; }
.dropdown-wrap  [ppt-icon-24] { margin-right:20px; }

[ppt-nav].boxed:not(.no-y) { margin: -1px; }
[ppt-nav].boxed > ul > li, [ppt-nav].boxed.d-flex > ul > li { border:1px solid #000; margin-left: -1px; line-height: 45px;     padding: 0px 20px;  }
[ppt-nav].boxed > ul > li:hover, [ppt-nav].boxed > ul > li.active { box-shadow: 0 1px 1px 0 rgb(0 0 0 / 100%)!important; }
[ppt-nav].boxed.pill > ul > li:first-child { border-top-left-radius: 6px;border-bottom-left-radius: 6px;}
[ppt-nav].boxed.pill > ul > li:last-child {border-top-right-radius: 6px;border-bottom-right-radius: 6px;}
[ppt-nav].boxed.pill > ul > li { border:1px solid var(--ppt-border-grey); overflow: hidden;    text-overflow: ellipsis;    white-space: nowrap; }
[ppt-nav].boxed.pill > ul > li .num { color: #000; width: 20px; height: 20px; font-size: 12px;    position: absolute;    top: 2px;    right: 2px;    color: #000;    line-height: 20px;    text-align: center;    border-radius: 10px;} 

[ppt-nav].boxed.no-y > ul > li { border:0px; border-left:1px solid #000; border-right:1px solid #000; }

[ppt-nav].baseline > ul {     display: flex!important; -ms-flex-align: baseline!important; align-items: baseline!important; }

.dropdown .dropdown-toggle:after { display:none!important; }

.dot-sm {
  height: 3px;
  width: 3px;
  background-color: #999;
  border-radius: 50%;
  display: inline-block;
  vertical-align: middle;
}

.elementor_mainmenu nav:not(.seperator) ul > li+li { margin-left:20px;} /* old menu system */

/*------------------------------------------*/
/*	LOGO
/*------------------------------------------*/

.navbar-light .navbar-brand-light {   display: none!important;}
.navbar-light .navbar-brand-dark {    display: block!important;}
.navbar-dark .navbar-brand-dark {   display: none!important;}
.navbar-dark .navbar-brand-light {    display: block!important;}

.navbar-dark [ppt-nav] > ul > li > a { color:#fff; }
.navbar-dark { color:#FFFFFF; }
.navbar-dark a { color:#fff; }

.navbar-light a { color:#000000; }

.textlogo { font-size: 25px; font-weight:700;letter-spacing:-1px }
@media (min-width: 1200px) {
.logo-lg .textlogo { font-size: 35px !important;  }
}
.navbar-brand-dark, .navbar-brand-light { max-height:150px; }

@media (max-width: 575.98px) { 
.navbar-brand-dark, .navbar-brand-light { max-height:60px; }
}

/*------------------------------------------*/
/*	Header
/*------------------------------------------*/

header { color:#000000; }
header.fixed-top.bg-transparent-none:not(.navbar-light) a:not(.dropdown-item) { color:#fff; }

header .ppt-icons-social li { overflow: hidden;  } 


/*-----------------------------------------------*/
/*	FORMS AND FIELDS
/*-----------------------------------------------*/

.form-control{display:block;width:100%;height:calc(1.5em + .75rem + 2px);padding:.375rem .75rem;font-size:1rem;font-weight:400;line-height:1.5;color:#495057;background-color:#fff;background-clip:padding-box;border:1px solid #ced4da;border-radius:.25rem;transition:border-color .15s ease-in-out,box-shadow .15s ease-in-out}@media (prefers-reduced-motion:reduce){.form-control{transition:none}}.form-control::-ms-expand{background-color:transparent;border:0}.form-control:focus{color:#495057;background-color:#fff;border-color:#80bdff;outline:0;box-shadow:0 0 0 .2rem rgba(0,123,255,.25)}.form-control::-webkit-input-placeholder{color:#6c757d;opacity:1}.form-control::-moz-placeholder{color:#6c757d;opacity:1}.form-control:-ms-input-placeholder{color:#6c757d;opacity:1}.form-control::-ms-input-placeholder{color:#6c757d;opacity:1}.form-control::placeholder{color:#6c757d;opacity:1}.form-control:disabled,.form-control[readonly]{background-color:#e9ecef;opacity:1}

input[type=date].form-control,input[type=datetime-local].form-control,input[type=month].form-control,input[type=time].form-control{-webkit-appearance:none;-moz-appearance:none;appearance:none}select.form-control:-moz-focusring{color:transparent;text-shadow:0 0 0 #495057}select.form-control:focus::-ms-value{color:#495057;background-color:#fff}.form-control-file,.form-control-range{display:block;width:100%}.col-form-label{padding-top:calc(.375rem + 1px);padding-bottom:calc(.375rem + 1px);margin-bottom:0;font-size:inherit;line-height:1.5}.form-control-sm{height:calc(1.5em + .5rem + 2px);padding:.25rem .5rem;font-size:.875rem;line-height:1.5;border-radius:.2rem}.form-control-lg{height:calc(1.5em + 1rem + 2px);padding:.5rem 1rem;font-size:1.25rem;line-height:1.5;border-radius:.3rem}select.form-control[multiple],select.form-control[size]{height:auto}textarea.form-control{height:auto}
.form-group{margin-bottom:1rem}.form-text{display:block;margin-top:.25rem}.form-row{display:-ms-flexbox;display:flex;-ms-flex-wrap:wrap;flex-wrap:wrap;margin-right:-5px;margin-left:-5px}.form-row>.col,.form-row>[class*=col-]{padding-right:5px;padding-left:5px}.form-check{position:relative;display:block;padding-left:1.25rem}.form-check-input{position:absolute;margin-top:.3rem;margin-left:-1.25rem}.form-check-input:disabled~.form-check-label,.form-check-input[disabled]~.form-check-label{color:#6c757d}.form-check-label{margin-bottom:0}.form-check-inline{display:-ms-inline-flexbox;display:inline-flex;-ms-flex-align:center;align-items:center;padding-left:0;margin-right:.75rem}.form-check-inline .form-check-input{position:static;margin-top:0;margin-right:.3125rem;margin-left:0}.form-inline{display:-ms-flexbox;display:flex;-ms-flex-flow:row wrap;flex-flow:row wrap;-ms-flex-align:center;align-items:center}.form-inline .form-check{width:100%}@media (min-width:576px){.form-inline label{display:-ms-flexbox;display:flex;-ms-flex-align:center;align-items:center;-ms-flex-pack:center;justify-content:center;margin-bottom:0}.form-inline .form-group{display:-ms-flexbox;display:flex;-ms-flex:0 0 auto;flex:0 0 auto;-ms-flex-flow:row wrap;flex-flow:row wrap;-ms-flex-align:center;align-items:center;margin-bottom:0}.form-inline .form-control{display:inline-block;width:auto;vertical-align:middle}.form-inline .form-control-plaintext{display:inline-block}.form-inline .custom-select,.form-inline .input-group{width:auto}.form-inline .form-check{display:-ms-flexbox;display:flex;-ms-flex-align:center;align-items:center;-ms-flex-pack:center;justify-content:center;width:auto;padding-left:0}.form-inline .form-check-input{position:relative;-ms-flex-negative:0;flex-shrink:0;margin-top:0;margin-right:.25rem;margin-left:0}.form-inline .custom-control{-ms-flex-align:center;align-items:center;-ms-flex-pack:center;justify-content:center}.form-inline .custom-control-label{margin-bottom:0}}.input-group{position:relative;display:-ms-flexbox;display:flex;-ms-flex-wrap:wrap;flex-wrap:wrap;-ms-flex-align:stretch;align-items:stretch;width:100%}.input-group>.custom-file,.input-group>.custom-select,.input-group>.form-control,.input-group>.form-control-plaintext{position:relative;-ms-flex:1 1 auto;flex:1 1 auto;width:1%;min-width:0;margin-bottom:0}.input-group>.custom-file+.custom-file,.input-group>.custom-file+.custom-select,.input-group>.custom-file+.form-control,.input-group>.custom-select+.custom-file,.input-group>.custom-select+.custom-select,.input-group>.custom-select+.form-control,.input-group>.form-control+.custom-file,.input-group>.form-control+.custom-select,.input-group>.form-control+.form-control,.input-group>.form-control-plaintext+.custom-file,.input-group>.form-control-plaintext+.custom-select,.input-group>.form-control-plaintext+.form-control{margin-left:-1px}.input-group>.custom-file .custom-file-input:focus~.custom-file-label,.input-group>.custom-select:focus,.input-group>.form-control:focus{z-index:3}.input-group>.custom-file .custom-file-input:focus{z-index:4}.input-group>.custom-select:not(:first-child),.input-group>.form-control:not(:first-child){border-top-left-radius:0!important;border-bottom-left-radius:0!important;}.input-group>.custom-file{display:-ms-flexbox;display:flex;-ms-flex-align:center;align-items:center}.input-group>.custom-file:not(:last-child) .custom-file-label,.input-group>.custom-file:not(:last-child) .custom-file-label::after{border-top-right-radius:0;border-bottom-right-radius:0}.input-group>.custom-file:not(:first-child) .custom-file-label{border-top-left-radius:0!important;border-bottom-left-radius:0!important}.input-group:not(.has-validation)>.custom-file:not(:last-child) .custom-file-label,.input-group:not(.has-validation)>.custom-file:not(:last-child) .custom-file-label::after,.input-group:not(.has-validation)>.custom-select:not(:last-child),.input-group:not(.has-validation)>.form-control:not(:last-child){border-top-right-radius:0;border-bottom-right-radius:0}.input-group.has-validation>.custom-file:nth-last-child(n+3) .custom-file-label,.input-group.has-validation>.custom-file:nth-last-child(n+3) .custom-file-label::after,.input-group.has-validation>.custom-select:nth-last-child(n+3),.input-group.has-validation>.form-control:nth-last-child(n+3){border-top-right-radius:0;border-bottom-right-radius:0}.input-group-append,.input-group-prepend{display:-ms-flexbox;display:flex}.input-group-append .btn,.input-group-prepend .btn{position:relative;z-index:2}.input-group-append .btn:focus,.input-group-prepend .btn:focus{z-index:3}.input-group-append .btn+.btn,.input-group-append .btn+.input-group-text,.input-group-append .input-group-text+.btn,.input-group-append .input-group-text+.input-group-text,.input-group-prepend .btn+.btn,.input-group-prepend .btn+.input-group-text,.input-group-prepend .input-group-text+.btn,.input-group-prepend .input-group-text+.input-group-text{margin-left:-1px}.input-group-prepend{margin-right:-1px}.input-group-append{margin-left:-1px}.input-group-text{display:-ms-flexbox;display:flex;-ms-flex-align:center;align-items:center;padding:.375rem .75rem;margin-bottom:0;font-size:1rem;font-weight:400;line-height:1.5;color:#495057;text-align:center;white-space:nowrap;background-color:#e9ecef;border:1px solid #ced4da;border-radius:.25rem}.input-group-text input[type=checkbox],.input-group-text input[type=radio]{margin-top:0}.input-group-lg>.custom-select,.input-group-lg>.form-control:not(textarea){height:calc(1.5em + 1rem + 2px)}.input-group-lg>.custom-select,.input-group-lg>.form-control,.input-group-lg>.input-group-append>.btn,.input-group-lg>.input-group-append>.input-group-text,.input-group-lg>.input-group-prepend>.btn,.input-group-lg>.input-group-prepend>.input-group-text{padding:.5rem 1rem;font-size:1.25rem;line-height:1.5;border-radius:.3rem}.input-group-sm>.custom-select,.input-group-sm>.form-control:not(textarea){height:calc(1.5em + .5rem + 2px)}.input-group-sm>.custom-select,.input-group-sm>.form-control,.input-group-sm>.input-group-append>.btn,.input-group-sm>.input-group-append>.input-group-text,.input-group-sm>.input-group-prepend>.btn,.input-group-sm>.input-group-prepend>.input-group-text{padding:.25rem .5rem;font-size:.875rem;line-height:1.5;border-radius:.2rem}.input-group-lg>.custom-select,.input-group-sm>.custom-select{padding-right:1.75rem}.input-group.has-validation>.input-group-append:nth-last-child(n+3)>.btn,.input-group.has-validation>.input-group-append:nth-last-child(n+3)>.input-group-text,.input-group:not(.has-validation)>.input-group-append:not(:last-child)>.btn,.input-group:not(.has-validation)>.input-group-append:not(:last-child)>.input-group-text,.input-group>.input-group-append:last-child>.btn:not(:last-child):not(.dropdown-toggle),.input-group>.input-group-append:last-child>.input-group-text:not(:last-child),.input-group>.input-group-prepend>.btn,.input-group>.input-group-prepend>.input-group-text{border-top-right-radius:0;border-bottom-right-radius:0}.input-group>.input-group-append>.btn,.input-group>.input-group-append>.input-group-text,.input-group>.input-group-prepend:first-child>.btn:not(:first-child),.input-group>.input-group-prepend:first-child>.input-group-text:not(:first-child),.input-group>.input-group-prepend:not(:first-child)>.btn,.input-group>.input-group-prepend:not(:first-child)>.input-group-text{border-top-left-radius:0;border-bottom-left-radius:0}.custom-control{position:relative;z-index:1;display:block;min-height:1.5rem;padding-left:1.5rem;-webkit-print-color-adjust:exact;color-adjust:exact}.custom-control-inline{display:-ms-inline-flexbox;display:inline-flex;margin-right:1rem}.custom-control-input{position:absolute;left:0;z-index:-1;width:1rem;height:1.25rem;opacity:0}.custom-control-input:checked~.custom-control-label::before{color:#fff;border-color:#1075d3;background-color:#1075d3}.custom-control-input:focus~.custom-control-label::before{box-shadow:0 0 0 .2rem rgba(0,123,255,.25)}.custom-control-input:focus:not(:checked)~.custom-control-label::before{border-color:#80bdff}.custom-control-input:not(:disabled):active~.custom-control-label::before{color:#fff;background-color:#b3d7ff;border-color:#b3d7ff}.custom-control-input:disabled~.custom-control-label,.custom-control-input[disabled]~.custom-control-label{color:#6c757d}.custom-control-input:disabled~.custom-control-label::before,.custom-control-input[disabled]~.custom-control-label::before{background-color:#e9ecef}.custom-control-label{position:relative;margin-bottom:0;vertical-align:top}.custom-control-label::before{position:absolute;top:3px;left:-1.5rem;display:block;width:1rem;height:1rem;pointer-events:none;content:"";background-color:#fff;border:#adb5bd solid 1px}.custom-control-label::after{position:absolute;top:.25rem;left:-1.5rem;display:block;width:1rem;height:1rem;content:"";background:50%/50% 50% no-repeat}.custom-checkbox .custom-control-label::before{border-radius:.25rem}.custom-checkbox .custom-control-input:checked~.custom-control-label::after{background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' width='8' height='8' viewBox='0 0 8 8'%3e%3cpath fill='%23fff' d='M6.564.75l-3.59 3.612-1.538-1.55L0 4.26l2.974 2.99L8 2.193z'/%3e%3c/svg%3e")}.custom-checkbox .custom-control-input:indeterminate~.custom-control-label::before{border-color:#1075d3;background-color:#1075d3}.custom-checkbox .custom-control-input:indeterminate~.custom-control-label::after{background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' width='4' height='4' viewBox='0 0 4 4'%3e%3cpath stroke='%23fff' d='M0 2h4'/%3e%3c/svg%3e")}.custom-checkbox .custom-control-input:disabled:checked~.custom-control-label::before{background-color:rgba(0,123,255,.5)}.custom-checkbox .custom-control-input:disabled:indeterminate~.custom-control-label::before{background-color:rgba(0,123,255,.5)}.custom-radio .custom-control-label::before{border-radius:50%}.custom-radio .custom-control-input:checked~.custom-control-label::after{background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='%23fff'/%3e%3c/svg%3e")}.custom-radio .custom-control-input:disabled:checked~.custom-control-label::before{background-color:rgba(0,123,255,.5)}.custom-file{position:relative;display:inline-block;width:100%;height:calc(1.5em + .75rem + 2px);margin-bottom:0}.custom-file-input{position:relative;z-index:2;width:100%;height:calc(1.5em + .75rem + 2px);margin:0;overflow:hidden;opacity:0}.custom-file-input:focus~.custom-file-label{border-color:#80bdff;box-shadow:0 0 0 .2rem rgba(0,123,255,.25)}.custom-file-input:disabled~.custom-file-label,.custom-file-input[disabled]~.custom-file-label{background-color:#e9ecef}.custom-file-input:lang(en)~.custom-file-label::after{content:"Browse"}.custom-file-input~.custom-file-label[data-browse]::after{content:attr(data-browse)}.custom-file-label{position:absolute;top:0;right:0;left:0;z-index:1;height:calc(1.5em + .75rem + 2px);padding:.375rem .75rem;overflow:hidden;font-weight:400;line-height:1.5;color:#495057;background-color:#fff;border:1px solid #ced4da;border-radius:.25rem}.custom-file-label::after{position:absolute;top:0;right:0;bottom:0;z-index:3;display:block;height:calc(1.5em + .75rem);padding:.375rem .75rem;line-height:1.5;color:#495057;content:"Browse";background-color:#e9ecef;border-left:inherit;border-radius:0 .25rem .25rem 0}.custom-control-label::before,.custom-file-label,.custom-select{transition:background-color .15s ease-in-out,border-color .15s ease-in-out,box-shadow .15s ease-in-out}@media (prefers-reduced-motion:reduce){.custom-control-label::before,.custom-file-label,.custom-select{transition:none}}


.form-control::placeholder{color:#d2d8dd;opacity:1;font-weight:400!important}
.form-control:-ms-input-placeholder{color:#d2d8dd}
.form-control::-ms-input-placeholder{color:#d2d8dd}
.form-group label,.ppt-forms label{font-weight:600;font-size:12px}
.ppt-forms .mapboxgl-ctrl-geocoder--icon-search{display:none}

.ppt-forms .mapboxgl-ctrl-geocoder--input{padding-left:15px!important}
.ppt-forms input:-webkit-autofill,.ppt-forms input:-webkit-autofill:focus{-webkit-box-shadow:0 0 0 1000px #fafafb inset;-webkit-text-font-size:16px}
.ppt-forms .form-group .fa:not(.nopos),.ppt-forms .form-group .fal:not(.nopos){position:absolute;right: 5%;top:30%;opacity:.5}
.ppt-forms .form-group .fa-eye{right:66px!important;cursor:pointer;opacity:1!important}
.ppt-forms .iconbit{position:absolute;right:15px;top:12px;opacity:.5; color:#444; border: 0px; }
.ppt-forms .iconbit.icon-svg { right:0px;top:0px; box-shadow:none!important  }
.ppt-forms .iconbit.fal{top:15px}.ppt-forms .iconbit.btn{top:8px;right:1px}

body.rtl .ppt-forms .form-group .fa,body.rtl .ppt-forms .form-group .fal,body.rtl .ppt-forms .iconbit{right:revert!important;left:20px!important}
body.rtl .ppt-forms .form-group .fa-eye{right:revert!important;left:50px!important}

.mapboxgl-ctrl-geocoder--input:-webkit-autofill:focus,.mapboxgl-ctrl-geocoder--input::-ms-input-placeholder,.mapboxgl-ctrl-geocoder--input::placeholder,.ppt-forms .mapboxgl-ctrl-geocoder--input:-webkit-autofill{color:red!important}.ppt-forms .mapboxgl-ctrl-geocoder--input::-webkit-input-placeholder{color:#d2d8dd}.ppt-forms .mapboxgl-ctrl-geocoder--input::-moz-placeholder{color:#d2d8dd}
.ppt-forms .mapboxgl-ctrl-geocoder--input:-ms-input-placeholder{color:#d2d8dd}
.ppt-forms .mapboxgl-ctrl-geocoder--input:-moz-placeholder{color:#d2d8dd}
.ppt-forms .description{font-size:12px;margin-top:10px;color:#999;display:block}
.ppt-forms #radius{border-color:#dae1e3;font-size:14px;color:#dad8dd;background-color:#fafafb!important;height:calc(2.55rem + 5px)}
.ppt-forms #radius option{color:#656565}
.ppt-forms .bootstrap-select>.dropdown-toggle,.ppt-forms .form-control:not(.whitebg),.ppt-forms .mapboxgl-ctrl-geocoder--input{
font-size:14px;color:#656565;background-color:#fff;min-height:calc(2.55rem + 5px);font-weight:400;border-radius:4px; border:1px solid #ddd; }

@media (max-width:991.98px){
.ppt-forms.filters_col .bootstrap-select>.dropdown-toggle,.ppt-forms.filters_col .form-control,.ppt-forms.filters_col .mapboxgl-ctrl-geocoder--input{background-color:#f7f7f7!important}
.ppt-forms.filters_col .custom-control-label::before{background-color:#f7f7f7;border:#efefef solid 1px}
}


section.bg-light .ppt-forms:not(.forms-nowhitebg) .form-control{background-color:#fff!important}

.ppt-forms.dark{background:#000;color:#fff}
.ppt-forms.dark .bootstrap-select>.dropdown-toggle,.ppt-forms.dark .form-control{background:#151719!important;color:#fff!important}
.ppt-forms.dark .bootstrap-select>.dropdown-toggle,.ppt-forms.dark .form-control:not(.required-active){border:1px solid #151719!important}
.ppt-forms.dark input:-webkit-autofill,.ppt-forms.dark input:-webkit-autofill:focus{-webkit-box-shadow:0 0 0 1000px #151719 inset!important;-webkit-text-fill-color:#fff!important}
.ppt-forms.dark a{color:#fff;opacity:.8}
.ppt-forms.dark li a{color:#000}
.ppt-forms.dark .ppt_pas_meter .strength_meter_block{border:1px solid #000}
.ppt-forms.dark .ppt_pas_meter .bg-dark{background:#000!important}
.ppt-forms.dark .logo .fa,.ppt-forms.dark .logo .fal,.ppt-forms.dark .text-dark{color:#fff!important}
.ppt-forms.dark .bg-light{color:#000}
.ppt-forms.dark .btn-dark{background:#fff!important;color:#000}
.ppt-forms.dark h1:after{background-color:#fff}

.ppt-forms.style2 .bootstrap-select>.dropdown-toggle,.ppt-forms.style2 .form-control:not(.required-active){background-color:transparent!important;border:none!important;border-bottom:1px solid rgba(0,0,0,.12)!important;border-radius:0!important;padding-left:0!important;color:#000}
.ppt-forms.style2 input:-webkit-autofill,.ppt-forms.style2 input:-webkit-autofill:focus{-webkit-box-shadow:0 0 0 1000px #fff inset!important;-webkit-text-fill-color:#000!important}

.ppt-forms h1{overflow:hidden}
.ppt-forms h1:not(.title):after,.ppt-forms h1:not(.title):before{background-color:#000;content:"";display:inline-block;height:1px;position:relative;vertical-align:middle;width:50%}
.ppt-forms h1:not(.title):before{right:.5em;margin-left:-50%}
.ppt-forms h1:not(.title):after{left:.5em;margin-right:-50%}
.ppt-forms .form-usertype-fields{color:#000!important}
.ppt-forms .input-group-text{padding:0 20px;background:#facd34;color:#fff;border:0;font-weight:700}
.ppt-forms .custom-control-label::before{background-color:#f3f3f3;border:#f3f3f3 solid 1px;cursor:pointer}
.ppt-forms b.badge{padding-top:3px}

.whitebg { border:1px solid #fff!important; }
.ppt-forms.style2 #mobilenum-input { padding-left:50px !important; } 

.ppt-forms.style3 .form-control{ background-clip: padding-box;  border-radius: 0.25rem; box-shadow: inset 0 1px 2px 0 rgb(66 71 112 / 12%);     border-radius: 0.25rem; background-color: #fafafb;  }
.ppt-forms.style3 .form-control:disabled { background-color: #fff8e0!important; }


/*------------------------------------------*/
/*	Buttons
/*------------------------------------------*/

.list-info-pop-wrap:hover .buttons-wrap { opacity:0.8 }
.buttons-wrap {    position: absolute;    display: -ms-flexbox;    display: flex;    -ms-flex-direction: column;    flex-direction: column;    -ms-flex-align: end;    align-items: flex-end;    top: 18%;    z-index: 2;    z-index: 3;    right: -10px;} 
.buttons-wrap div:first-child {    margin-top: 0;    transition-delay: .36s;}
.buttons-wrap .badge-vip {    position: relative;    width: 65px;    height: 65px;}
.buttons-wrap div:not(.button-new, .button-featured, .button-video) {    display: flex;    justify-content: center;    -ms-flex-align: center;    align-items: center;    -ms-flex-direction: column;    flex-direction: column;    width: 65px;    height: 65px;    border-radius: 100%;    box-shadow: 0 1px 2px 0 rgb(0 0 0 / 30%), inset 0 2px 0 0 hsl(0deg 0% 100% / 40%);    margin: 0 5px;    text-shadow: 0 0 1px rgb(0 0 0 / 30%);    color: #fff;    text-align: center;    font-weight: 700;    text-transform: uppercase;		margin-right: -10px;}
.button-vip {	background-image: linear-gradient(180deg,#fac300,#fac300);    font-size: 25px;}
.button-online {    background-image: linear-gradient(180deg,#02a71e,#253822);    font-size: 11px;}
.button-videos {    background-image: linear-gradient(180deg,#f50e16,#8a0308);    font-size: 11px;}
.buttons-wrap div.disc+div.disc {    margin-top: -20px;    transition: all .2s ease; }
.button-new, .button-featured, .button-video {    position: relative;    display: -ms-flexbox;    display: flex;    -ms-flex-align: center;    align-items: center;    -ms-flex-pack: center;    justify-content: center;    width: auto;    min-width: 55px;    text-align: center;    margin: 0 5px 25px;    padding: 7px 5px;    font-size: 16px;    font-weight: 700;    text-transform: uppercase;    line-height: 1;    color: #fff;    border-top-left-radius: 5px;    border-bottom-left-radius: 5px;    background-color: #77ac33;}
.button-new { background:#fac300; }
.button-new:after {  border-left: 5px solid #334a16;  }
.button-new:after, .button-featured:after, .button-video:after {    content: "";    position: absolute;    width: 0;    height: 0;    bottom: -5px;    right: 0;    border-bottom: 5px solid transparent;}
.button-featured { font-size: 14px; }
.button-featured:after { border-left: 5px solid #b90006; }
.button-video { font-size: 12px; background:#000000; }
.button-video:after { border-left: 5px solid #ccc; }
.buttons-wrap div:first-child.button-new {    margin-top: -45%;}
.buttons-wrap div:first-child.button-featured {    margin-top: -35%; background:#f50e16;}
.button-featured-new {     position: relative;    display: -ms-flexbox;    display: flex;    -ms-flex-align: center;    align-items: center;    -ms-flex-pack: center;    justify-content: center;    width: auto;    min-width: 55px;    text-align: center; margin: 0 5px 25px;    padding: 7px 15px;    font-size: 14px;    font-weight: 700;    text-transform: uppercase;    line-height: 1;    color: #fff;    border-top-right-radius: 5px;    border-bottom-right-radius: 5px;    background-color: #f50e16; }

.button-featured-new-wrap.es{     position: absolute;    bottom: 60px;    z-index: 9;    left: -11px; }	
.button-featured-new:before {content: "";    position: absolute;    width: 0;    height: 0;    bottom: -5px;    left: 1px;    border-bottom: 5px solid transparent;  border-right: 5px solid #b90006;}

.button-color-green {    background-image: linear-gradient(180deg,#107500,#045328);}
.button-color-blue {background-image: linear-gradient(180deg,#00b7fa,#0092fa); }

@media (max-width: 575.98px) { 
.buttons-wrap .disc { right:0px; }
.buttons-wrap div:not(.button-new, .button-featured, .button-video) {
width: 50px;    height: 50px;    font-size: 16px;
}
}

/*------------------------------------------*/
/*	Box
/*------------------------------------------*/

[ppt-flex-row] {display: -webkit-box;    display: -ms-flexbox;    display: flex;    -webkit-box-orient: horizontal;    -webkit-box-direction: normal;    -ms-flex-direction: row;    flex-direction: row;    -webkit-box-pack: justify;    -ms-flex-pack: justify;    justify-content: space-between;    -webkit-box-align: center;    -ms-flex-align: center;    align-items: center;}

[ppt-box] ._title, [ppt-box] ._content:not(.p-0), [ppt-box] ._footer { padding: 0 15px; }
[ppt-box] {background-clip: border-box;display: flex;flex-direction: column; color: #000; position: relative;     border: 1px solid var(--ppt-border-grey);    box-shadow: 0 1px 1px rgb(0 0 0 / 4%);    background: #fff;}
[ppt-box] ._header {     line-height: 50px; z-index: 1; position:relative; }
[ppt-box] ._header:not(.shadow-none){ border-bottom: 1px solid var(--ppt-border-grey); }
[ppt-box] ._title {    font-weight: 600; overflow: hidden;    text-overflow: ellipsis;    white-space: nowrap;}
[ppt-box] ._icon {    font-size: 16px;    color: inherit;	padding-left: 10px;}
[ppt-box] ._close {    border-left: 1px solid var(--ppt-border-grey);    font-size: 16px;    color: inherit;	padding: 0px 10px; cursor:pointer; }
[ppt-box] ._footer { border-top: 1px solid var(--ppt-border-grey);} 
[ppt-box] ._footer.small{ line-height: 40px; font-size: 14px; }
[ppt-box] ._content { height: 100%; }

[ppt-box] .border-bottom { border-bottom: 1px solid var(--ppt-border-grey)!important; }
[ppt-box] .border-top { border-top: 1px solid var(--ppt-border-grey)!important; }

[ppt-box]+[ppt-box] { margin-top:30px; }



/*------------------------------------------*/
/*	Lists
/*------------------------------------------*/ 

[ppt-list-item], [ppt-list-item]:hover { display:block; text-decoration:none; color:#000; }
[ppt-list-item]:hover [ppt-icon-box] { background:#000!important; color:#fff; }
[ppt-list-item]+[ppt-list-item] { margin-top:10px; padding-top: 10px; border-top:1px solid var(--ppt-border-grey); }

[ppt-box] ._content [ppt-list-item], [ppt-box] ._content [ppt-list-box] { padding:10px; margin-top:0px;  }


/*------------------------------------------*/
/*	Popups
/*------------------------------------------*/

.card-popup-content{position:relative;text-align:center;} 
.card-popup .pop-icon {position:relative;vertical-align:middle;display:inline-block;margin:5px 0;border-radius:100%;width:44px;height:44px;background-clip:padding-box;text-align:center;transition:background .2s;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none; background:#fff; box-shadow:0 0 0 3px #fff; overflow: hidden; }
.card-popup .pop-icon:before,.card-popup .pop-icon:after{content:'';position:absolute;top:0;right:0;bottom:0;left:0;border-radius:inherit;transition:background .2s;}

.card-popup.large .side, .large .card-popup .side {width:120px;height:120px;}
.card-popup.large .middle, .large .card-popup .middle {width:150px;height:150px;}
.card-popup.medium .side, .medium .card-popup .side {width:70px;height:70px;}
.card-popup.medium .middle, .medium .card-popup .middle {width:100px;height:100px; z-index:1; }
.card-popup-content .middle { z-index:1; }
.card-popup .pop-icon + .card-popup .pop-icon, .card-popup .pop-icon + .card-popup .pop-icon{margin-left:17px;}

.card-popup .pop-icon:before{border-color:#2b65f8;}  
.card-popup .pop-icon + .card-popup .pop-icon{vertical-align:top;}
.card-popup .pop-icon + .card-popup .pop-icon{margin-left:7px;}

.card-popup .smilecode { font-size:40px; width:100px; height:100px; }
.card-popup .bg-image {position:absolute;top:0;left:0; background-size:cover;background-repeat:no-repeat;background-position:top center;}
.card-popup .pop-icon .card-popup .bg-image{right:0;bottom:0;}
.card-popup .bg-image{overflow:hidden;border-radius:inherit;width:100%;height:100%;}

.card-popup-content { min-height:130px; }
.card-popup-content, .ppt-shape-curve {position:relative; min-height:140px; background:50% calc(50% + 35px) url('data:image/svg+xml,%3Csvg%20viewBox%3D%220%200%20600%20500%22%20width%3D%22600%22%20height%3D%22500%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%20%3Cpath%20fill%3D%22%23fff%22%20d%3D%22M600%20217v282c0%20.6-.4%201-1%201H1c-.6%200-1-.4-1-1V217s115.7%2033%20300%2033%20300-33%20300-33z%22%2F%3E%20%3C%2Fsvg%3E');background-size:cover;text-align:center;}

/*------------------------------------------*/
/*	Transitions
/*------------------------------------------*/


.ppt-animate span { display: inline-block; }

.ppt-animate-repeat {
  animation-iteration-count: infinite!important;
}
.ppt-animate-bouncein {
  animation: bounceIn 0.8s linear 1;
}
.ppt-animate-bounceout {
  animation: bounceOutDown 0.8s linear 1;
}
.ppt-animate-fadein {
  animation: fadeInDown 0.4s linear 1;
}
.ppt-animate-fadeup {
  animation: fadeInUp 0.4s linear 1;
}
.ppt-animate-slidein {
  animation: slideInLeft 0.6s linear 1;
}

.ppt-animate-zoom-in {
  animation: zoomIn 0.2s linear 1;
} 
.ppt-animate-zoom-in.out {
  animation: zoomOut 0.5s linear 1;
} 

.ppt-animate-fade-in {
  animation: fadeInLeft 0.2s linear 1;
} 
.ppt-animate-fade-in.out {
  animation: fadeOutRight 0.5s linear 1;
}

.ppt-animate-typed { 
animation: rise-in 0.2s linear 1;
text-decoration:underline;
}

.ppt-animate-rise-in {
  animation: rise-in 0.2s linear 1;
} 
.ppt-animate-rise-in.out {
  animation: rise-out 0.5s linear 1;
}

.ppt-animate-pulse-in {
  animation: pulse 0.3s;
} 

.ppt-animate-rubberBand {
  animation: rubberBand 0.6s linear 1;
}
.ppt-animate-wobble {
  animation: wobble 0.6s linear 1;
}  


@keyframes pulse {
from {
  -webkit-transform: scale3d(0, 0, 0);
  transform: scale3d(0, 0, 0);
}

50% {
  -webkit-transform: scale3d(1.55, 1.55, 1.55);
  transform: scale3d(1.55, 1.55, 1.55);
}

to {
  -webkit-transform: scale3d(1, 1, 1);
  transform: scale3d(1, 1, 1);
}
}


@-webkit-keyframes rise-in {
0% {
  transform: rotateX(180deg);
  opacity: 0; }
35% {
  transform: rotateX(120deg);
  opacity: 0; }
65% {
  opacity: 0; }
100% {
  transform: rotateX(360deg);
  opacity: 1; } }
@keyframes rise-in {
0% {
  transform: rotateX(180deg);
  opacity: 0; }
35% {
  transform: rotateX(120deg);
  opacity: 0; }
65% {
  opacity: 0; }
100% {
  transform: rotateX(360deg);
  opacity: 1; } }

@-webkit-keyframes rise-out {
0% {
  transform: rotateX(0deg);
  opacity: 1; }
35% {
  transform: rotateX(-40deg);
  opacity: 1; }
65% {
  opacity: 0; }
100% {
  transform: rotateX(180deg);
  opacity: 0; } }

@keyframes rise-out {
0% {
  transform: rotateX(0deg);
  opacity: 1; }
35% {
  transform: rotateX(-40deg);
  opacity: 1; }
65% {
  opacity: 0; }
100% {
  transform: rotateX(180deg);
  opacity: 0; } } 

@-webkit-keyframes zoomIn {
from {
  opacity: 0;
  -webkit-transform: scale3d(0.3, 0.3, 0.3);
  transform: scale3d(0.3, 0.3, 0.3);
}

50% {
  opacity: 1;
}
}
@keyframes zoomIn {
from {
  opacity: 0;
  -webkit-transform: scale3d(0.3, 0.3, 0.3);
  transform: scale3d(0.3, 0.3, 0.3);
}

50% {
  opacity: 1;
}
}
@-webkit-keyframes zoomOut {
from {
  opacity: 1;
}

50% {
  opacity: 0;
  -webkit-transform: scale3d(0.3, 0.3, 0.3);
  transform: scale3d(0.3, 0.3, 0.3);
}

to {
  opacity: 0;
}
}
@keyframes zoomOut {
from {
  opacity: 1;
}

50% {
  opacity: 0;
  -webkit-transform: scale3d(0.3, 0.3, 0.3);
  transform: scale3d(0.3, 0.3, 0.3);
}

to {
  opacity: 0;
}
}

@-webkit-keyframes rubberBand {
from {
  -webkit-transform: scale3d(1, 1, 1);
  transform: scale3d(1, 1, 1);
}

30% {
  -webkit-transform: scale3d(1.25, 0.75, 1);
  transform: scale3d(1.25, 0.75, 1);
}

40% {
  -webkit-transform: scale3d(0.75, 1.25, 1);
  transform: scale3d(0.75, 1.25, 1);
}

50% {
  -webkit-transform: scale3d(1.15, 0.85, 1);
  transform: scale3d(1.15, 0.85, 1);
}

65% {
  -webkit-transform: scale3d(0.95, 1.05, 1);
  transform: scale3d(0.95, 1.05, 1);
}

75% {
  -webkit-transform: scale3d(1.05, 0.95, 1);
  transform: scale3d(1.05, 0.95, 1);
}

to {
  -webkit-transform: scale3d(1, 1, 1);
  transform: scale3d(1, 1, 1);
}
}
@keyframes rubberBand {
from {
  -webkit-transform: scale3d(1, 1, 1);
  transform: scale3d(1, 1, 1);
}

30% {
  -webkit-transform: scale3d(1.25, 0.75, 1);
  transform: scale3d(1.25, 0.75, 1);
}

40% {
  -webkit-transform: scale3d(0.75, 1.25, 1);
  transform: scale3d(0.75, 1.25, 1);
}

50% {
  -webkit-transform: scale3d(1.15, 0.85, 1);
  transform: scale3d(1.15, 0.85, 1);
}

65% {
  -webkit-transform: scale3d(0.95, 1.05, 1);
  transform: scale3d(0.95, 1.05, 1);
}

75% {
  -webkit-transform: scale3d(1.05, 0.95, 1);
  transform: scale3d(1.05, 0.95, 1);
}

to {
  -webkit-transform: scale3d(1, 1, 1);
  transform: scale3d(1, 1, 1);
}
}

@-webkit-keyframes wobble {
from {
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}

15% {
  -webkit-transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
  transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
}

30% {
  -webkit-transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
  transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
}

45% {
  -webkit-transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
  transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
}

60% {
  -webkit-transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
  transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
}

75% {
  -webkit-transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
  transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
}

to {
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}
@keyframes wobble {
from {
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}

15% {
  -webkit-transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
  transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
}

30% {
  -webkit-transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
  transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
}

45% {
  -webkit-transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
  transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
}

60% {
  -webkit-transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
  transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
}

75% {
  -webkit-transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
  transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
}

to {
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}


@-webkit-keyframes fadeInLeft {
from {
  opacity: 0;
  -webkit-transform: translate3d(-100%, 0, 0);
  transform: translate3d(-100%, 0, 0);
}

to {
  opacity: 1;
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}
@keyframes fadeInLeft {
from {
  opacity: 0;
  -webkit-transform: translate3d(-100%, 0, 0);
  transform: translate3d(-100%, 0, 0);
}
to {
  opacity: 1;
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}
@-webkit-keyframes fadeOutRight {
from {
  opacity: 1;
}

to {
  opacity: 0;
  -webkit-transform: translate3d(100%, 0, 0);
  transform: translate3d(100%, 0, 0);
}
}
@keyframes fadeOutRight {
from {
  opacity: 1;
}

to {
  opacity: 0;
  -webkit-transform: translate3d(100%, 0, 0);
  transform: translate3d(100%, 0, 0);
}
}


@keyframes ppt-note-bounce {
0 {
  opacity: 0;
  transform: translate3d(0, 0, -100px);
}
50% {
  opacity: 1;
  transform: translate3d(0, 0, 0);
}
60% {
  opacity: 1;
  transform: translate3d(0, 0, 2px);
}
70%,
100% {
  opacity: 1;
  transform: translate3d(0, 0, 0);
}
}


@-webkit-keyframes fadeInUp {
from {
  opacity: 0;
  -webkit-transform: translate3d(0, 100%, 0);
  transform: translate3d(0, 100%, 0);
}

to {
  opacity: 1;
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}
@keyframes fadeInUp {
from {
  opacity: 0;
  -webkit-transform: translate3d(0, 100%, 0);
  transform: translate3d(0, 100%, 0);
}

to {
  opacity: 1;
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}

@-webkit-keyframes slideInLeft {
from {
  -webkit-transform: translate3d(-100%, 0, 0);
  transform: translate3d(-100%, 0, 0);
  visibility: visible;
}

to {
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}
@keyframes slideInLeft {
from {
  -webkit-transform: translate3d(-100%, 0, 0);
  transform: translate3d(-100%, 0, 0);
  visibility: visible;
}

to {
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}

@keyframes fadeIn {
from {
  opacity: 0;
}

to {
  opacity: 1;
}
}
@keyframes fadeInDown {
from {
  opacity: 0;
  -webkit-transform: translate3d(0, -100%, 0);
  transform: translate3d(0, -100%, 0);
}

to {
  opacity: 1;
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
}

@keyframes bounceIn {
from,
20%,
40%,
60%,
80%,
to {
  -webkit-animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
}

0% {
  opacity: 0;
  -webkit-transform: scale3d(0.3, 0.3, 0.3);
  transform: scale3d(0.3, 0.3, 0.3);
}

20% {
  -webkit-transform: scale3d(1.1, 1.1, 1.1);
  transform: scale3d(1.1, 1.1, 1.1);
}

40% {
  -webkit-transform: scale3d(0.9, 0.9, 0.9);
  transform: scale3d(0.9, 0.9, 0.9);
}

60% {
  opacity: 1;
  -webkit-transform: scale3d(1.03, 1.03, 1.03);
  transform: scale3d(1.03, 1.03, 1.03);
}

80% {
  -webkit-transform: scale3d(0.97, 0.97, 0.97);
  transform: scale3d(0.97, 0.97, 0.97);
}

to {
  opacity: 1;
  -webkit-transform: scale3d(1, 1, 1);
  transform: scale3d(1, 1, 1);
}
}

@keyframes bounceOutDown {
20% {
  -webkit-transform: translate3d(0, 10px, 0) scaleY(0.985);
  transform: translate3d(0, 10px, 0) scaleY(0.985);
}

40%,
45% {
  opacity: 1;
  -webkit-transform: translate3d(0, -20px, 0) scaleY(0.9);
  transform: translate3d(0, -20px, 0) scaleY(0.9);
}

to {
  opacity: 0;
  -webkit-transform: translate3d(0, 2000px, 0) scaleY(3);
  transform: translate3d(0, 2000px, 0) scaleY(3);
}
}

.pop-animate{-webkit-animation-duration:.8s!important;-webkit-animation-fill-mode:both!important;animation-duration:.8s!important;animation-fill-mode:both!important;}

.popIn{-webkit-animation-name:popIn;animation-name:popIn;}
.delay-200{-webkit-animation-delay:.2s;animation-delay:.2s;}
.delay-300{-webkit-animation-delay:.3s;animation-delay:.3s;}
.delay-500{-webkit-animation-delay:.5s;animation-delay:.5s;} 



/*------------------------------------------*/
/*	Sidebar 
/*------------------------------------------*/

#page-content-wrapper{min-width:100%!important}
#wrapper.toggled #sidebar-wrapper{min-height:100vh;-webkit-transition:margin .25s ease-out;-moz-transition:margin .25s ease-out;-o-transition:margin .25s ease-out;transition:margin .25s ease-out;background:#000;z-index:99999}
#wrapper.toggled #sidebar-wrapper{margin-left:0}
#sidebar-wrapper .sidebar-content{min-width:240px;padding:20px}
#sidebar-wrapper .hederlogo { height:108px;  }
#wrapper.toggled-slim .sidebar-content{min-width:100px; }
#wrapper.toggled-slim  .sidebar-content { display:none; }
#sidebar-wrapper a{text-decoration:none}
#sidebar-wrapper .mobile-nav { margin-left:0px; }
#sidebar-wrapper .menu1 ul li{ font-size: 18px;    line-height: 40px;    text-align: center;    font-weight: 600; }
#sidebar-wrapper .menu1 ul li .nav-link{padding:10px 0;display:block;color:rgba(255,255,255,.8);border-bottom:1px solid rgba(255,255,255,.1)}
#sidebar-wrapper .text-light ul:not(.dropdown-menu) li > a:not(.dropdown-item), #sidebar-wrapper .text-light ul:not(.dropdown-menu) li > a:hover, #sidebar-wrapper .text-light > a:not(.dropdown-item) {color:#fff!important;}
#sidebar-wrapper .text-dark ul:not(.dropdown-menu) li > a:not(.dropdown-item), #sidebar-wrapper .text-dark ul:not(.dropdown-menu) li > a:hover, #sidebar-wrapper .text-dark  > a:not(.dropdown-item) {color:#000!important;}
#sidebar-wrapper .dropdown-menu a { color:#000!important; }
#sidebar-wrapper ul li svg, #sidebar-wrapper ul li [ppt-icon-size="24"] { display:none; } 
#sidebar-wrapper .sidebar-logo .textlogo{font-size:30px;text-align:center;display:block;max-width:260px;overflow:hidden}
#sidebar-wrapper .sidebar-logo img{max-width:220px}
#sidebar-wrapper .dropdown-toggle::after{float:right;margin-top:10px}


#wrapper.toggled:not(.toggled-slim) .container { margin-left: 20px; }

@media (min-width: 1500px){
#wrapper.toggled:not(.toggled-slim) .container { margin-left:5%!important; }
}
@media ( min-width: 1200px ){
#wrapper.toggled:not(.toggled-slim) .container { max-width:975px; }
#wrapper.toggled:not(.toggled-slim) .filterboxWrap li {    width: 24.6%; }
}

.nav-sm { line-height: 30px; font-weight: 600; }

.nav-icon { line-height: 40px; font-weight: 600; }
.nav-icon .icon { width:40px; display: inline-block; text-align: center; }
.nav-icon ul {  }
.nav-icon li { font-size:18px; }
.nav-icon li span { margin-right:10px; }

#main-category-wrap #navMenu {  position: relative;}
#main-category-wrap #navMenu #navMenu-wrapper {  overflow: hidden;  height: 60px; }
#main-category-wrap #navMenu #navMenu-wrapper.addon {  padding: 0 30px;}
#main-category-wrap #cat-items {  margin:0px;  padding: 0;  list-style: none;  white-space: nowrap;  overflow-x: hidden;  -webkit-overflow-scrolling: touch;} 
#main-category-wrap #navMenu ul li {  display: inline-block;  margin: 20px 24px;}
#main-category-wrap #navMenu ul li a { color:#666; }

#main-category-wrap .navMenu-paddle-left, #main-category-wrap .navMenu-paddle-right {  cursor: pointer;  border: none;  position: absolute;  top: 20px;  background-color: transparent;  width: 25px;  height: 25px;  margin-left: auto;  margin-right: auto;}
#main-category-wrap .slick-prev, .navMenu-paddle-left { left: 0; } 
#main-category-wrap .slick-next, .navMenu-paddle-right { right: 0; }

#main-category-wrap #navMenu.style2 { height:40px; }
#main-category-wrap #navMenu.style2 ul li { border: 1px solid #ddd;    padding: 5px 10px;    border-radius: 20px;    font-size: 14px; margin: 0px 10px; }
#main-category-wrap #navMenu.style2 .navMenu-paddle-left, #main-category-wrap #navMenu.style2 .navMenu-paddle-right { top:7px; }
#main-category-wrap #navMenu.style2 #cat-items { margin-top:3px; }

/*------------------------------------------*/
/*	 Modals & Popups
/*------------------------------------------*/

.ppt-modal-wrap{position:fixed;top:0;left:0;bottom:0;right:0;z-index:1000;display:none;overflow:auto;-webkit-transform:translate3d(0,0,0); color:#000000; }
.ppt-modal-wrap.show { display:block!important; }
.ppt-modal-wrap-overlay{position:fixed;top:0;left:0;top:0;left:0;bottom:0;right:0;z-index:1;background:rgba(0,0,0,.41);-webkit-transform:translate3d(0,0,0); }
.ppt-modal-item{position:relative;max-width:500px;margin:0 auto;top:10%;z-index:2; border-radius: 6px;    overflow: hidden;}

.ppt-modal-shadow { box-shadow: 0 0 0 7px rgb(255 255 255 / 10%); }

.ppt-modal-container{padding:0; }
.ppt-modal-container h3{font-size:15px}
.ppt-modal-container h3 i{padding-right:10px}

.modal-notice-new-custom { max-height: 150px;  }
.modal-notice-new-custom .ppt-modal-item { border: 1px solid #ddd; }
.modal-admin-saved .ppt-modal-wrap-overlay, .modal-notice-new-custom  .ppt-modal-wrap-overlay { background:none!important; }

.ppt-modal-mobile-close { position:absolute; bottom:0px; position: absolute; bottom: 0px;  border-top: 1px solid #ddd; background:#fff;  }

.modal-top .ppt-modal-item {    position: fixed;    max-width: 100%;    margin: 0 auto;    top: 0;    z-index: 1; top: unset; width: 100%; }
.modal-top-right .ppt-modal-item {left: unset;  top: 10px;  margin: 0px;  right: 10px;  margin-left: auto; }

.modal-bottom .ppt-modal-item {    position: fixed;    max-width: 100%;    margin: 0 auto;    bottom: 0;    z-index: 1; top: unset; width: 100%; }
.modal-bottom-right .ppt-modal-item {   z-index: 999999; position: fixed;    max-width: unset;    margin: 0 auto;    bottom: 20px;    z-index: 2;    width: unset;    top: unset;    right: 20px;    max-width: 400px;} 


@media (max-width: 575.98px) {  
.ppt-modal-wrap:not(.modal-bottom-right) .ppt-modal-item { top:0%; border-radius:0px!important; }
.ppt-modal-container:not(.modal-bottom-right) > [ppt-box] { border-radius:0px!important; height:100%; }
.ppt-modal-container:not(.modal-bottom-right) > [ppt-box] ._footer {     z-index: 11; }
.ppt-modal-wrap:not(.modal-bottom-right) .ppt-modal-container { height: 100vh; }
}

@media(max-width:575px){
  .ppt-modal-item #form_user_register {
  max-height: 700px;
  overflow: hidden;
  overflow-y: scroll;
}
}

/* window sizes */
.ppt-messenger-window { min-height: 280px; max-height:350px; }  
.ppt-notify-window  { min-height: 440px; max-height:450px; } 
@media (max-width: 575.98px) {
.ppt-messenger-window, .ppt-notify-window { min-height: 92%;    max-height: 90%; }
}

/* sizes */
.w-300 { min-width:300px; }
.ppt-modal-item.w-500, .login-modal .ppt-modal-item{max-width:500px!important}
.ppt-modal-item.w-700, .upgrade-modal .ppt-modal-item{max-width:700px!important}
.ppt-modal-item.w-900, .big-modal .ppt-modal-item{max-width:900px!important}


.extra-modal-wrap{position:fixed;top:0;left:0;bottom:0;right:0;z-index:1000;display:none;overflow:auto;-webkit-transform:translate3d(0,0,0)}
.extra-modal-wrap-overlay{position:fixed;top:0;left:0;top:0;left:0;bottom:0;right:0;z-index:1;background:rgba(0,0,0,.41);-webkit-transform:translate3d(0,0,0)}
.extra-modal-item{position:relative;max-width:650px;margin:0 auto;top:10%;z-index:2}
.extra-modal-container{padding:0;background:#fff;overflow:hidden}
.extra-modal-container h3{font-size:15px}
.extra-modal-container h3 i{padding-right:10px}
.extra-modal #locationMap{margin-bottom:0;height:500px}
.extra-modal-close{position:absolute;right:30px;bottom:16px;width:36px;height:36px;line-height:38px;border-radius:4px;color:#fff;z-index:10;cursor:pointer}
.extra-modal-wrap1{position:fixed;top:0;left:0;bottom:0;right:0;z-index:1000;display:none;overflow:auto;-webkit-transform:translate3d(0,0,0)}
.extra-modal-wrap1-overlay{position:fixed;top:0;left:0;top:0;left:0;bottom:0;right:0;z-index:1;background:rgba(0,0,0,.41);-webkit-transform:translate3d(0,0,0)}


.comment-modal-wrap{position:fixed;top:0;left:0;bottom:0;right:0;z-index:1000;display:none;overflow:auto;-webkit-transform:translate3d(0,0,0)}
.comment-modal-wrap-overlay{position:fixed;top:0;left:0;top:0;left:0;bottom:0;right:0;z-index:1;background:rgba(0,0,0,.41);-webkit-transform:translate3d(0,0,0)}
.comment-modal-item{position:relative;max-width:610px;margin:0 auto;top:10%;z-index:2}
.comment-modal-container{padding:0;background:#fff;overflow:hidden}
.comment-modal-container h3{font-size:15px}
.comment-modal-container h3 i{padding-right:10px}
.comment-modal-close{position:absolute;right:30px;top:16px;width:36px;height:36px;line-height:38px;border-radius:4px;color:#000;z-index:10;cursor:pointer}

.filter-modal-wrap{position:fixed;top:0;left:0;bottom:0;right:0;z-index:1000;display:none;overflow:auto;-webkit-transform:translate3d(0,0,0)}
.filter-modal-wrap-overlay{position:fixed;top:0;left:0;top:0;left:0;bottom:0;right:0;z-index:1;background:rgba(0,0,0,.41);-webkit-transform:translate3d(0,0,0)}
.filter-modal-item{position:relative;max-width:500px;margin:0 auto;top:10%;z-index:2}
.filter-modal-container{padding:0;background:#fff;overflow:hidden;border-radius:10px}
.filter-modal-container h3{font-size:15px}
.filter-modal-container h3 i{padding-right:10px}
.filter-modal-close{position:absolute;right:30px;top:16px;width:36px;height:36px;line-height:38px;border-radius:4px;color:#000;z-index:10;cursor:pointer}
.filter-modal-wrap .card-filter .card-title{font-size:14px!important}
.filter-modal-wrap .card-filter .card-title:before{display:none!important}
.filter-modal-wrap .collapse:not(.show){display:block!important}


/*------------------------------------------*/
/*	Headlines & animation
/*------------------------------------------ */

.ppt-headline {    overflow: visible;    display: inline-block;    position: relative;}
.ppt-headline svg {    position: absolute;    top: 50%;    left: 50%;    width: calc(100% + 20px);    height: calc(100% + 20px);    -webkit-transform: translate(-50%,-50%);    transform: translate(-50%,-50%);    overflow: visible;	z-index: 2;}
.ppt-headline svg path {    stroke: red;    stroke-width: 9;    fill: none;     stroke-linecap: round;    stroke-linejoin: round;}

/*------------------------------------------*/
/*	New Block Changes
/*------------------------------------------ */


[data-ppt-blocktype] h1, [data-ppt-blocktype] h2, [data-ppt-blocktype] h3, [data-ppt-blocktype] h4, [data-ppt-blocktype] h5, [data-ppt-blocktype] h6 { font-weight:700; }
[data-ppt-blocktype] .lead { font-weight:500; }

[data-ppt-blocktype="text"] .btn { font-weight:600; }

h1[data-title-animated] span.end { display:block; min-height: 75px; }

@media (min-width: 600px){
[data-ppt-blocktype="text"] .btn+.btn, [data-ppt-blocktype="text"] [ppt-button]+[ppt-button] { margin-left:20px; }
}

@media (max-width: 600px){
[data-ppt-blocktype]:not(data-ppt-blockid="text122") h2 { font-size:20px!important;; }

h1[data-title-animated] span.end { display:block; min-height: 45px; }
h1[data-title-animated] span.end +.typed-cursor { display:none; }
section.divider6{     height: 20px; }
}

/* hero */
body:not(.rtl) [data-ppt-blocktype="hero"] [data-ppt-btn]:not(.list)+[data-ppt-btn] { margin-left:20px!important; }

@media (max-width:575.98px){

[data-ppt-section].hide-mobile-bg ._contents { padding:0px }
[data-ppt-section].hide-mobile-bg .bg-image { display:none; }
[data-ppt-section].hide-mobile-bg .text-light, [data-ppt-section].hide-mobile-bg .text-white { color:#000000!important; }

[data-ppt-blocktype="hero"] h1 { font-size:30px; }
[data-ppt-blocktype="hero"] [data-ppt-subtitle] br, [data-ppt-blocktype="hero"] [data-ppt-desc] br, [data-ppt-blocktype="hero"] [data-ppt-title] br { display:none; }
[data-ppt-blocktype="hero"] [data-ppt-btn]+[data-ppt-btn] { margin-top:0px!important; }
[data-ppt-blocktype="hero"] [data-ppt-btn]:not(.btn-search) {     overflow: hidden;    text-overflow: ellipsis;    white-space: nowrap; display:inline-block; font-size:14px; min-width: auto; line-height:45px; height:45px; }
[data-ppt-blocktype="hero"] .h1buttonbox { margin-top:30px !important; }

[data-ppt-blockid="hero108"] img { padding-top:20px; margin-top:40px; }
[data-ppt-blockid="hero108"] { padding-bottom:0px!important; }

}


@media (min-width: 1200px){
[data-ppt-blocktype="hero"] h1:not(.fs-xxl) {    font-size: 48px;}
[data-ppt-blockid="hero4"] h1:not(.fs-xxl) { font-size:40px!important; }
}

@media (min-width: 1300px){
[data-ppt-blocktype="hero"] h1:not(.fs-xxl) {    font-size: 50px;}
}

@media (max-width:600px){
[data-ppt-blockid="hero4"] { padding:20px 0px; }
}

[data-ppt-blocktype="hero"].bg-dark .btn { box-shadow: 0 .5rem 1rem rgba(0,0,0,.15)!important; }
[data-ppt-blocktype="hero"].bg-light .btn { box-shadow: 0 .5rem 1rem rgba(0,0,0,.10)!important; }
[data-ppt-blocktype="hero"] .mapboxgl-ctrl-geocoder--input { border:0px!important; height: 50px; }

/* listings */
[data-ppt-blockid="listings101"] .card-ppt-search ._bot { font-size:12px; }


.shadow-hover:hover { box-shadow: 0 .5rem 1rem rgba(0,0,0,.15)!important;}

/*------------------------------------------*/
/*	Live Editing
/*------------------------------------------ */

.ppt-editable { border-bottom:1px dotted #ca0000; }
.woocommerce .col-1, .woocommerce .col-2{max-width:none;}


/*------------------------------------------*/
/*	Scroll
/*------------------------------------------ */

.ppt-scroll  {  position: relative;  width: 100%;  overflow: auto;}
.ps{overflow:hidden!important;overflow-anchor:none;-ms-overflow-style:none;touch-action:auto;-ms-touch-action:auto}.ps__rail-x{display:none;opacity:0;transition:background-color .2s linear,opacity .2s linear;-webkit-transition:background-color .2s linear,opacity .2s linear;height:15px;bottom:0;position:absolute}.ps__rail-y{display:none;opacity:0;transition:background-color .2s linear,opacity .2s linear;-webkit-transition:background-color .2s linear,opacity .2s linear;width:15px;right:0;position:absolute}.ps--active-x>.ps__rail-x,.ps--active-y>.ps__rail-y{display:block;background-color:transparent}.ps--focus>.ps__rail-x,.ps--focus>.ps__rail-y,.ps--scrolling-x>.ps__rail-x,.ps--scrolling-y>.ps__rail-y,.ps:hover>.ps__rail-x,.ps:hover>.ps__rail-y{opacity:.6}.ps .ps__rail-x.ps--clicking,.ps .ps__rail-x:focus,.ps .ps__rail-x:hover,.ps .ps__rail-y.ps--clicking,.ps .ps__rail-y:focus,.ps .ps__rail-y:hover{background-color:#eee;opacity:.9}.ps__thumb-x{background-color:#aaa;border-radius:6px;transition:background-color .2s linear,height .2s ease-in-out;-webkit-transition:background-color .2s linear,height .2s ease-in-out;height:6px;bottom:2px;position:absolute}.ps__thumb-y{background-color:#aaa;border-radius:6px;transition:background-color .2s linear,width .2s ease-in-out;-webkit-transition:background-color .2s linear,width .2s ease-in-out;width:6px;right:2px;position:absolute}.ps__rail-x.ps--clicking .ps__thumb-x,.ps__rail-x:focus>.ps__thumb-x,.ps__rail-x:hover>.ps__thumb-x{background-color:#999;height:11px}.ps__rail-y.ps--clicking .ps__thumb-y,.ps__rail-y:focus>.ps__thumb-y,.ps__rail-y:hover>.ps__thumb-y{background-color:#999;width:11px}@supports (-ms-overflow-style:none){.ps{overflow:auto!important}}@media screen and (-ms-high-contrast:active),(-ms-high-contrast:none){.ps{overflow:auto!important}}

/*------------------------------------------*/
/*	15 - Search Page Popups 
/*------------------------------------------*/ 

@media (max-width: 575.98px){
.card-popup .card-footer {
  position: absolute;
  bottom: 0px;
  width: 100%;
display:block!important;
}
}
.card-popup .tax_wrapper:not(.country) > div { border: 1px solid #ddd;
  padding: 10px;
  font-size: 18px;
  margin-bottom: 10px;
  border-radius: 10px; cursor:pointer; }
.card-popup .tax_wrapper:not(.country, .nohover) > div.on  { background:#efefef;  }
.card-popup .custom-control { margin:0px; }
.card-popup .custom-control-label::before, 
.card-popup .custom-control-label::after { top:6px; }

.card-popup .tax_wrapper .badge { display:nonexx; } 

.card-sidebar-filters .filter-distance .tax_wrapper > div, .card-sidebar-filters .filter-date_added .tax_wrapper > div, .card-sidebar-filters .filter-tax_country .tax_wrapper > div, .card-sidebar-filters .filter-sold .tax_wrapper > div, .card-sidebar-filters .filter-deliver .tax_wrapper > div, .card-sidebar-filters .filter-lastused .tax_wrapper > div, .card-sidebar-filters .filter-comments .tax_wrapper > div, .card-sidebar-filters .filter-ends .tax_wrapper > div  { border:1px solid #ddd; padding:3px;     margin-bottom: 10px;    border-radius: 8px;    line-height: 30px;    text-align: center;    font-weight: 600;    font-size: 12px;    background: #fafafb; cursor:pointer; }

.card-sidebar-filters .filter-distance .tax_wrapper > div.on, .card-sidebar-filters .filter-date_added .tax_wrapper > div.on, .card-sidebar-filters .filter-sold .tax_wrapper > div.on, .card-sidebar-filters .filter-deliver .tax_wrapper > div.on, .card-sidebar-filters .filter-lastused .tax_wrapper > div.on, .card-sidebar-filters .filter-comments .tax_wrapper > div.on, .card-sidebar-filters .filter-ends .tax_wrapper > div.on  { background:#fac300; }

/*------------------------------------------*/
/*	15 - Search Page 
/*------------------------------------------*/ 


.search-zoom:hover .bg-image { transform: scale(1.1); transition: all .3s;  }
.search-zoom .bg-image { transition: all .3s; }

.search-gradient {
  background: -webkit-gradient(linear,left top,left bottom,color-stop(0,rgba(6,27,65,0)),color-stop(100%,rgba(49,49,49,.95)));
  background: -webkit-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);
  background: -o-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);
  background: -ms-linear-gradient(top,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);
  background: linear-gradient(to bottom,rgba(6,27,65,0) 0,rgba(49,49,49,.95) 100%);
  position: absolute;
  left: 0;
  width: 100%;
  height: 100%;
  height: 100px;
  bottom: 0px;
  z-index: 1;
  background-size: cover; }

.featuredribbion{z-index:1; position:absolute;top:0;right:0;background:#fa0d15;color:#fff;font-size:12px;font-weight:600;text-align:center;-ms-transform:rotate(45deg);-webkit-transform:rotate(45deg);transform:rotate(45deg);width:150px;margin-top:20px;margin-right:-40px;letter-spacing:.5px; padding: 5px; }

.card-ppt-search .countdown{min-width:100px;border-radius:25px;font-size:11px;color:#fff;font-weight:700;border-radius:25px;line-height:20px;display:inline-block;text-align:center;padding:0 10px}
.card-ppt-search figure .read_more{position:absolute;top:50%;left:0;margin-top:-12px;-webkit-transform:translateY(10px);-moz-transform:translateY(10px);-ms-transform:translateY(10px);-o-transform:translateY(10px);transform:translateY(10px);text-align:center;opacity:0;visibility:hidden;width:100%;-webkit-transition:all .6s;transition:all .6s;z-index:2}

.card-ppt-search figure .read_more span{background-color:#fcfcfc;background-color:rgba(255,255,255,.8);-webkit-border-radius:20px;-moz-border-radius:20px;-ms-border-radius:20px;border-radius:20px;display:inline-block;color:#222;font-size:12px;font-size:.75rem;padding:5px 10px}.card-ppt-search figure:hover .read_more{opacity:1;visibility:visible;-webkit-transform:translateY(0);-moz-transform:translateY(0);-ms-transform:translateY(0);-o-transform:translateY(0);transform:translateY(0)}

._sfavs .icon_wrap { height: 80px; position: absolute;    top: 30%;    z-index: 1000;    width: 80px;  width: 100%;   display:none; text-align:center; }

._sfavs .icon_wrap div.save, ._sfavs .icon_wrap div.view { width: 68px;    height: 68px;    background: #FFF;    border: none;    -webkit-box-shadow: 0 5px 5px 0 rgb(0 0 0 / 12%);    box-shadow: 0 5px 5px 0 rgb(0 0 0 / 12%);    border-radius: 50%;	 margin: auto; font-size: 20px;    line-height: 75px;    color: #e0e0e0; text-align: center; display: inline-block; cursor:pointer; }

._sfavs .icon_wrap div.save { transition: all .2s; margin-right: 20px; }
._sfavs .icon_wrap div.view { transition: all .4s; }

._sfavs:not(.noFavs) figure:hover .icon_wrap {    display:block; }
._sfavs:not(.noFavs) figure:hover .icon_wrap > div {    -webkit-transform-origin: top;    -moz-animation: popIn .8s;    -webkit-animation: popIn .8s;    animation: popIn .8s; } 
._sfavs ._ok {  text-indent: 5px; }
._sfavs ._cancel { text-indent: -9999999px; }
._sfavs:not(.isFavs) ._cancel svg { display:none; }
._sfavs.isFavs ._ok { display:none; }
._sfavs svg { margin-top: -5px; }
._sfavs.isFavs ._cancel  { text-indent: -5px; }
._sfavs .btn_favs { display:none; }
._sfavs.isFavs .btn_favs { display:inline-block; }
._sfavs ._iconsmall { padding: 0px 6px 0px 5px; font-size: 10px;    line-height: 21px;    text-align: center;    border-radius: 10px;}
._sfavs.isFavs .hidefavs { display:none; }
._sfavs.isFavs .showfavs { display:inline-block; }
._sfavs:not(.isFavs) .hidefavs { display:inline-block; }
._sfavs:not(.isFavs) .showfavs { display:none; }



/* landscape */
.card-ppt-search .ppt-image-search { height:200px; }
.card-ppt-search.list .ppt-image-search { height:220px; }

/* portrait */
@media (min-width: 600px) { 

.tall-images .card-ppt-search.list .ppt-image-search { height:220px; width:200px; }
.tall-images .card-ppt-search.list .flex-sm-column { min-height:220px!important;; }
.tall-images .card-ppt-search.list .ppt-image-search { height:270px!important; }
.tall-images .card-ppt-search.list .ppt-image-search, .tall-images.theme-es .card-ppt-search.list .ppt-image-searc { height:200px; }
.tall-images .card-ppt-search.list figure { width:200px!important; }

.tall-images .card-ppt-search .ppt-image-search { height:270px; }
.tall-images.theme-es .card-ppt-search .ppt-image-search { height:380px; }
.tall-images .card-ppt-search .bg-image { background-position: top; } 


}


@media (min-width: 992px) and (max-width: 1199.98px) { 

.tall-images .card-ppt-search .ppt-image-search { height:220px; }

}
@media (min-width: 576px) and (max-width: 991.98px) { 

.tall-images .card-ppt-search .ppt-image-search { height:200px; }

}
@media (max-width: 575.98px) { 

.card-ppt-search .ppt-image-search { height:100px; }
.card-ppt-search.list .ppt-image-search { height:100px; }

body:not(.theme-pj) .card-ppt-search:not(.small,.blog,.fixed) figure { width:90px; }
body:not(.theme-pj) .card-ppt-search:not(.small,.blog,.fixed) {    min-height: 80px; }
.tall-images .card-ppt-search .ppt-image-search { height:90px; }

.tall-images .card-ppt-search.list .ppt-image-search, .tall-images.theme-es .card-ppt-search .ppt-image-search { width:100%; height:90px; }

body.theme-pj .card-ppt-search:not(.small,.blog,.fixed) { display:inline-flex; }
 body.theme-pj .card-ppt-search:not(.small,.blog,.fixed) figure { width:70px; margin-right:10px; }
body.theme-pj .frame-top { border-bottom:0px solid #ddd !important; }
body.theme-pj .frame-top img { width:45px; }

}

.card-ppt-search .pricebg {
  min-width: 100px;
  border-radius: 25px;
  color: #fff;
  font-weight: 600;
  display: inline-block;
  text-align: center;
  padding: 0 10px;
font-size:16px;
}


@media (min-width: 575.98px){
.card-ppt-search .textbg {
  min-width: 100px;
  border-radius: 4px;
  color: #fff;
  font-weight: 600;
  display: inline-block;
  text-align: center;
  padding: 5px 10px;
font-size:14px;
overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
max-width:130px;
}
.card-ppt-search .textbg a { color:#fff; }
}
@media (max-width: 575.98px){

.card-ppt-search .textbg { background:none!important; color:#333333; font-size:14px; }
.card-ppt-search .textbg a { color:#333; font-size:14px; }
}

@media (max-width: 575.98px){
.card-ppt-search .pricebg { font-size:14px; }
}


.list-info-pop-wrap:hover .list-info-pop, .card-ppt-search:hover .list-info-pop { z-index:9; opacity: 0.9!important;  cursor:pointer;  max-height:200px; }
.list-info-pop {   opacity: 0; max-height:0px;      position: absolute;   bottom: 0px;    width: 100%;	    transition: max-height 0.5s ease-in-out 0s, opacity 0.1s ease-in-out 0.1s;  overflow-y: scroll;}
.list-info-pop::-webkit-scrollbar {  width: 15px;}
.list-info-pop::-webkit-scrollbar-thumb {  background-color: rgba(36, 45, 60, 0.2);}
.list-info-pop::-webkit-scrollbar-button {  display: none;}
.list-info-pop ul {      padding: 10px 25px;    display: block;    color: #ffffff;    font-size: 14px;    text-align: left;    margin-bottom: 0px;}
.list-info-pop ul li span{    font-weight: 700;   display: inline-block; }
.list-info-pop ul li {    padding: 8px 0;    line-height: 1;}
@media(max-width:575px){
.list-info-pop ul li { font-size:10px; }
}

.fullcontainer [ppt-box] { box-shadow: none !important; }
.fullcontainer [ppt-box] ._content:not(.p-0)  {    padding: 0 8px !important;}
.fullcontainer .list-info-pop ul { padding: 8px 15px; font-size: 11px; }
.fullcontainer  .list-info-pop ul li { padding: 6px 0; line-height: 1;}
.fullcontainer .perrow4 { padding-right: 5px;    padding-left: 5px; }
.fullcontainer .card-filter .card-title { font-size: 14px;   }
.fullcontainer .card-filter label { font-size: 12px; }

.tax_wrapper { cursor: pointer !important; }
.tax-div { margin:0px 0px; padding:8px 8px; border-bottom:1px solid var(--ppt-border-grey);  }
.tax-div .custom-control-label { cursor: pointer !important; }
.tax-div .custom-control { margin-bottom:0px; }
.tax-div:hover { background-color:#fafafb; cursor: pointer; }
.tax-div .float-right {    float: none !important; }
.tax-div .filtertxt { line-height: 23px; }

.card-filter .filter-content.filter-type-tax {    padding-top: 0px !important;}
.card-filter .filter-type-not-tax { padding: 10px !important; }
.card-filter .card-title { padding: 10px 10px !important; }
.card-filter .card-title:before { right: 12px !important; }

.sidebar-search [ppt-box]+[ppt-box] {    margin-top: 10px !important; } 
.sidebar-search .card-filter .card-title { border-bottom: 1px solid #ddd; }

/*------------------------------------------*/
/*	Elementor Changes
/*------------------------------------------*/ 

.elementor-widget-container .block-listings2  .list-info-pop ul li { font-size:11px; }
.elementor-widget-container .block-listings2 .list-info-pop ul li span { display:block; margin-bottom:5px; }

@media (min-width: 575.98px) { 
.home .elementor header .container, .home elementor [data-ppt-blocktype="footer"] { padding-left:0px; padding-right:0px }
}

/*------------------------------------------*/
/*	Search Filters
/*------------------------------------------*/ 

.filterboxWrap li { display: inline-block; margin-bottom:10px; cursor:pointer;  }

@media(min-width:575px){
.filterboxWrap { margin: -5px!important;  }
}

.filterboxWrap li {  width: 24.7%; } 

@media (min-width:768px){ .filterboxWrap li {  width: 49%;} }
@media (min-width:992px){ .filterboxWrap li {  width: 33%;} } 
@media (min-width:1200px){ .filterboxWrap li {  width: 24.7%;} } 
@media(max-width:575px){.filterboxWrap li { width: 100%; display: inline-block; }}

@media (min-width: 1200px){
body.mapview .filterboxWrap li {
  width: 24.5%!important;
}
}

.filterboxWrap li._closed { display:none; }

.filterbox:after{font-family:"Font Awesome 5 Pro";content:"\f107";position:absolute;color:#000;top:20px;right:20px;font-size:18px;font-weight:600} 
.filterbox.location:after{content:"\f21d";}  
.filterbox.keyword:after{content:"\f002";}  
.filterbox.mobile:after{top:17px; }  
.filterbox:hover { box-shadow: 0 .125rem .25rem rgba(0,0,0,.035)!important;  }
.filterbox:hover:after {   }

@media (max-width:771.98px){ 
.filterboxWrap:not(._show) { display:none; }
.filterbox { margin:0px; margin-bottom:10px; }
}


.mapview .filterToggle .toggle-on, .mapview .toggle-off { width:18px; }
.mapview .filterToggle .toggle-dot, .mapview .filterToggle .toggle-favs { width: 16px; }
.mapview .filterToggle .toggle-me { font-size:14px; }

.has-sidebar .filterToggle .toggle-on, .has-sidebar .toggle-off { width:22px; }
.has-sidebar .filterToggle .toggle-dot, .has-sidebar .filterToggle .toggle-favs { width: 16px; }
.has-sidebar .filterToggle .toggle-me { font-size:16px; }



/*------------------------------------------*/
/*	23 - Badges
/*------------------------------------------*/ 


.card-ppt-search .ppt-badges   { position:absolute; top:10px; left:10px; z-index:1 }
.card-ppt-search .ppt-badges ._badge, .ppt-badges-small .ppt-badges ._badge  { font-size: 12px; padding: 8px 10px;}

/* with icons */
.ppt-badges ._badge { color:#444;     background: #fafafb;  border-radius: 4px;  padding:0px; text-align:left; font-size: 14px;  float: left; font-weight:600; padding:5px 10px;     border: 1px solid #8f8f8f; box-shadow: 0 1px 2px 0 rgb(0 0 0 / 5%)!important; }
.ppt-badges ._badge i { margin-right:5px; font-weight:600; }

.ppt-badges ._badge:hover {  }
.ppt-badges ._badge + ._badge { margin-left:10px; }
.ppt-badges ._badge:hover i { font-weight:bold; }

@media (max-width: 575.98px) { 
.ppt-badges ._badge { margin-right:10px; margin-bottom:10px; }
.ppt-badges ._badge + ._badge { margin-left:0px; }
.ppt-badges ._badge { font-size: 12px; padding: 8px 10px;}
}


.ppt-awards { margin-top:50px; }
.ppt-awards .fieldset {   border: 1px solid #f2f2f2;    padding: 25px 10px 15px 10px;    margin-bottom: 20px;    position: relative;    border-radius: 4px;    margin-top: 10px;}
.ppt-awards .fieldset ._title {    position: absolute;    top: -15px;    left: 25%;    font-size: 16px;    background: #fff;    padding: 5px 20px;    color: #919191;}
.ppt-awards .fieldset ._price {    font-size: 30px;    font-weight: 700;    text-shadow: 1px 1px #fff;}
.ppt-awards .imgs { margin-right:5px; max-width:40px; }
.ppt-awards img { margin-right:10px; }
.ppt-awards ._award { width:50px; height:50px; background: linear-gradient(189deg,#fff 0,rgb(248 249 250) 100%); border: 2px solid #f0f0f0; margin:3px; position: relative;    background-size: cover; border-radius: 8px; line-height: 50px;    text-align: center;    font-size: 25px; color: #b1b1b1; }
.ppt-awards ._award i { text-shadow: 2px 1px #fff; }
.ppt-awards ._award:hover {    box-shadow: 0 .125rem .25rem rgba(0,0,0,.090)!important; cursor:pointer; color:#333333; }
.ppt-awards ._award + ._award { margin-left:10px; }
.ppt-awards ._award:hover i { font-weight:bold; }


.badge_tooltip {  position: relative;}
.badge_tooltip__item {  position: absolute;  min-width: 100px;  padding: 20px;  visibility: hidden;  opacity: 0;  background: white;  transition: all 0.25s cubic-bezier(0, 0, 0.2, 1);  color: #484848;  border: 1px solid #cecece;  border-radius: 3px;  font-weight: 500;  box-shadow: 0 2px 1px #bcbcbc;  z-index: 4;font-size: 14px !important;    line-height: 21px;width: 200px; color:#000000 !important; }
.badge_tooltip__item:after {  content: "";  display: block;  position: absolute;  width: 0;  height: 0;  border-style: solid;}
.badge_tooltip__initiator {  cursor: pointer;  z-index: 5;}
.badge_tooltip[data-direction="left"] .badge_tooltip__initiator:hover ~ .badge_tooltip__item {  transform: translate3d(0, -50%, 0);  visibility: visible;  opacity: 1;}
.badge_tooltip[data-direction="left"] .badge_tooltip__item {  top: 50%;  right: calc(100% + 1em);  transform: translate3d(15px, -50%, 0);}
.badge_tooltip[data-direction="left"] .badge_tooltip__item:after {  top: 50%;  right: -0.5em;  transform: translate3d(0, -50%, 0);  border-width: 0.5em 0 0.5em 0.5em;  border-color: transparent transparent transparent white;  -webkit-filter: drop-shadow(0px 2px 1px #bcbcbc);  filter: drop-shadow(0px 2px 1px #bcbcbc);}
.badge_tooltip[data-direction="top"] .badge_tooltip__initiator:hover ~ .badge_tooltip__item, .badge_tooltip[data-direction="bottom"] .badge_tooltip__initiator:hover ~ .badge_tooltip__item {  transform: translate3d(-50%, 0, 0);  visibility: visible;  opacity: 1;}
.badge_tooltip[data-direction="top"] .badge_tooltip__item, .badge_tooltip[data-direction="bottom"] .badge_tooltip__item {  left: 50%;  transform: translate3d(-50%, -15px, 0);}
.badge_tooltip[data-direction="top"] .badge_tooltip__item:after, .badge_tooltip[data-direction="bottom"] .badge_tooltip__item:after {  left: 50%;  transform: translate3d(-50%, 0, 0);}
.badge_tooltip[data-direction="top"] .badge_tooltip__item {  bottom: calc(100% + 1em);}
.badge_tooltip[data-direction="top"] .badge_tooltip__item:after {  bottom: -0.5em;  border-width: 0.5em 0.5em 0 0.5em;  border-color: white transparent transparent transparent;  filter: drop-shadow(0px 2px 1px #bcbcbc);  -webkit-filter: drop-shadow(0px 2px 1px #bcbcbc);}

[ppt-search-badges]:not(.right) { bottom:10px;left:10px;position: absolute; }
[ppt-search-badges].right { bottom:10px;right:10px;position: absolute; }
[ppt-search-badges] .badge { padding:4px 10px; position:relative; }

figure [ppt-search-badges] .badge { display: block; font-size: 12px;    padding: 5px;    font-weight: 700;    text-transform: uppercase; }
figure [ppt-search-badges] .badge  span { display:none;}

@media (min-width: 575.98px) {
figure [ppt-search-badges] .badge+.badge { margin-top:10px; }
}
.search7 [ppt-search-badges] {display: flex;    flex-flow: row;    align-items: center;    justify-content: space-between;    width: 90%; z-index: 1; }


.order-status-icon{background-color:#efefef;color:#333;border-radius:9999px!important;letter-spacing:.025em!important;font-size:10px;text-transform:uppercase;padding:3px 8px}.order-status-icon .dot{height:8px!important;width:8px!important;display:inline-block;border-radius:9999px!important}
.table-orders th{border:0!important;color:#838fa1;background:#fbfdfe;line-height:30px}
.order-status-icon.status-1{background-color:#bcf0da!important;color:#014737!important}
.order-status-icon.status-1 .dot{background-color:#0e9f6e!important}
.order-status-icon.status-2{background-color:#edefee!important;color:#535454!important}.order-status-icon.status-2 .dot{background-color:#7d8c8c!important}
.order-status-icon.status-3{background-color:#d4f7ff!important;color:#535454!important}.order-status-icon.status-3 .dot{background-color:#08bdbd!important}.order-status-icon.status-4{background-color:#ebdefe!important;color:#535454!important}.order-status-icon.status-4 .dot{background-color:#8e63cd!important}.order-status-icon.status-5{background-color:#fbd5d5!important;color:#771d1d!important}
.order-status-icon.status-5 .dot{background-color:#f05252!important}.order-status-icon.status-6{background-color:#e6e3f6!important;color:#535454!important}
.order-status-icon.status-6 .dot{background-color:#5a4bb0!important}.order-status-icon.status-7{background-color:#000!important;color:#fff!important}.order-status-icon.status-7 .dot{background-color:#fff!important}
.order-status-icon.status-8{background-color:#bf0000!important;color:#fff!important}.order-status-icon.status-8 .dot{background-color:#fff!important}



/*------------------------------------------*/
/*	ICONS
/*------------------------------------------*/

.ppt-icon-online{width:16px;height:16px;background:#14e214;border-radius:20px}

.ppt-icons-social ul{padding:0;margin:0}
.ppt-icons-social li{display:inline-block;margin:0 3px}
.ppt-icons-social li a{color:#606060;text-align:center;display:block;text-decoration:none}
.ppt-icons-social li i{margin:0!important;padding:0!important}.ppt-icons-social.rounded li a{border-radius:5px}.ppt-icons-social.rounded-circle li a{border-radius:100%}.ppt-icons-social.size-xs li a{height:16px;width:16px;line-height:16px;font-size:9px}.ppt-icons-social.size-sm li a{height:24px;width:24px;line-height:24px;font-size:12px}.ppt-icons-social.size-md li a{height:32px;width:32px;line-height:32px;font-size:14px}.ppt-icons-social.size-lg li a{height:48px;width:48px;line-height:48px;font-size:18px}.ppt-icons-social.size-xl li a{height:64px;width:64px;line-height:64px;font-size:20px}.ppt-icons-social.size-lg._share li a,.ppt-icons-social.size-lg._share xl a,.ppt-icons-social.size-md._share li a,.ppt-icons-social.size-xs._share li a{width:auto!important;padding:0 15px!important}.ppt-icons-social.size-lg._share li a span,.ppt-icons-social.size-lg._share xl a span,.ppt-icons-social.size-md._share li a span,.ppt-icons-social.size-xs._share li a span{margin-left:10px}.ppt-icons-social._style1 li a{border:1px solid #fff}.ppt-icons-social._style1 li a:hover{border:1px solid #ddd}.ppt-icons-social._style1 li.facebook a:hover{color:#4c65a8!important}.ppt-icons-social._style1 li.twitter a:hover{color:#41a1f6!important}.ppt-icons-social._style1 li.instagram a:hover{color:#ba2e9a!important}.ppt-icons-social._style1 li.pinterest a:hover{color:#ff4c5b!important}
.ppt-icons-social._style1 li.linkedin a:hover{color:#2576b0!important}
.ppt-icons-social._style1 li.youtube a:hover{color:#c81121!important}
.ppt-icons-social._style1 li.tiktok a:hover{color:#000!important}
.ppt-icons-social._style1 li.vimeo a:hover{color:#1a83e2!important}
.ppt-icons-social._style2 li a{color:#fff!important}
.btn-facebook,.ppt-icons-social._style2 li.facebook a,.ppt-icons-social._style3 li.facebook a:hover:before,.ppt-icons-social._style4 li.facebook a:hover{background:#4c65a8;color:#fff!important}
.btn-twitter,.ppt-icons-social._style2 li.twitter a,.ppt-icons-social._style3 li.twitter a:hover:before,.ppt-icons-social._style4 li.twitter a:hover{background:#41a1f6;color:#fff!important}
.ppt-icons-social._style2 li.instagram a,.ppt-icons-social._style3 li.instagram a:hover:before,.ppt-icons-social._style4 li.instagram a:hover{background:#ba2e9a;color:#fff!important}
.ppt-icons-social._style2 li.tiktok a,.ppt-icons-social._style3 li.tiktok a:hover:before,.ppt-icons-social._style4 li.tiktok a:hover{background:#000;color:#fff!important}
.ppt-icons-social._style2 li.pinterest a,.ppt-icons-social._style3 li.pinterest a:hover:before,.ppt-icons-social._style4 li.pinterest a:hover{background:#ff4c5b;color:#fff!important}
.btn-linkedin,.ppt-icons-social._style2 li.linkedin a,.ppt-icons-social._style3 li.linkedin a:hover:before,.ppt-icons-social._style4 li.linkedin a:hover{background:#2576b0;color:#fff!important}
.ppt-icons-social._style2 li.youtube a,.ppt-icons-social._style3 li.youtube a:hover:before,.ppt-icons-social._style4 li.youtube a:hover{background:#c81121;color:#fff!important}
.ppt-icons-social._style2 li.vimeo a,.ppt-icons-social._style3 li.vimeo a:hover:before,.ppt-icons-social._style4 li.vimeo a:hover{background:#1a83e2;color:#fff!important}
.ppt-icons-social._style2 li a i::before{display:block;-webkit-font-smoothing:subpixel-antialiased!important;-webkit-backface-visibility:hidden;-moz-backface-visibility:hidden;-ms-backface-visibility:hidden}
.ppt-icons-social._style2 li a:hover i::before{-webkit-animation:iconTranslateY .4s forwards;-moz-animation:iconTranslateY .4s forwards;animation:iconTranslateY .4s forwards}.ppt-icons-social._style3 li a{background:#fafafb;position:relative}.ppt-icons-social._style3 li a:before{position:absolute;content:"";left:0;top:0;width:100%;height:100%;opacity:0;-webkit-transform:scale(.1);-moz-transform:scale(.1);-ms-transform:scale(.1);-o-transform:scale(.1);transform:scale(.1);z-index:0}.ppt-icons-social._style3 li a i{z-index:2;position:relative}.ppt-icons-social._style3 li a:hover:before{opacity:1;-webkit-transform:scale(1);-moz-transform:scale(1);-ms-transform:scale(1);-o-transform:scale(1);transform:scale(1)}.ppt-icons-social._style3 li a:hover{color:#fff}.ppt-icons-social._style4 li a{border:1px solid #efefef}.bg-dark .ppt-icons-social._style4 li a,.bg-primary .ppt-icons-social._style4 li a,.bg-secondary .ppt-icons-social._style4 li a{border:1px solid #ffffff63!important;color:#fff}.btn-facebook:hover,.btn-google:hover,.btn-linkedin:hover,.btn-twitter:hover{-webkit-filter:brightness(115%);filter:brightness(115%)}

.ppt-icon-onlinebar.inline{display:inline-block}.ppt-icon-onlinebar ._wrap{display:inline-block;position:relative;padding:3px 15px 3px 35px;font-weight:600}.ppt-icon-onlinebar ._wrap .ppt-icon-online{position:absolute;z-index:1}.ppt-icon-onlinebar._style1 ._wrap{border:1px solid #ddd}.ppt-icon-onlinebar._style2 ._wrap{background:#ffffff14;color:#fff;font-weight:500}.ppt-icon-onlinebar._style3 ._wrap{background:#30a745;color:#fff}.ppt-icon-onlinebar._style3 .ppt-icon-online{background:#fff!important}.ppt-icon-onlinebar.rounded ._wrap{border-radius:10px}.ppt-icon-onlinebar.size-sm{font-size:12px}.ppt-icon-onlinebar.size-sm ._wrap .ppt-icon-online{left:12px;top:7px;width:9px;height:9px}.ppt-icon-onlinebar.size-md{font-size:16px}.ppt-icon-onlinebar.size-md ._wrap .ppt-icon-online{left:12px;top:10px;width:10px;height:10px}.ppt-icon-onlinebar.size-lg{font-size:18px}.ppt-icon-onlinebar.size-lg ._wrap .ppt-icon-online{left:12px;top:11px;width:12px;height:12px}

.text-online { color:#34c434; }

.ppt-icons-social.size-sm a span { display:none; }

.single-video{padding:10px 22px;position:relative;z-index:10;background-color:#fff;margin-left:-1px;overflow:hidden;z-index:0}.single-video figure img{-webkit-transition:all1sease;-moz-transition:all 1s ease;-ms-transition:all 1s ease;-o-transition:all 1s ease;transition:all 1s ease}.single-video figure:hover img{-webkit-transform:scale(1.1);-moz-transform:scale(1.1);-ms-transform:scale(1.1);-o-transform:scale(1.1);transform:scale(1.1)}

.single-video figure i.fa-play-circle, .isVideo .vidicon {position:absolute;top:45%;left:50%;margin-left:-16px;margin-top:-16px;z-index:5;color:#fff;font-size:50px;line-height:1}
@media (max-width: 575.98px) { 
.single-video figure i.fa-play-circle{ font-size:30px; }
}
.single-video{padding:0;margin:0}
.single-video .inner{padding:5px3px}
.single-video .videobox{position:relative}
.single-video .videobox .time{position:absolute;bottom:0;left:0}
.single-video figure{position:relative}
.single-video figure{background-color:#000;z-index:2;width:100%;margin:0;overflow:hidden}
.single-video figure em{position:absolute;bottom:0;right:5px;font-style:normal}
.single-video figure span{position:absolute;bottom:0;left:0;display:block;padding:3px 8px 3px;font-weight:500;font-size:12px;color:#fff;background-color:rgba(0,0,0,.7)}


/*------------------------------------------*/
/*	14 - notication bar
/*------------------------------------------*/

.single-page-edit-button-bg{background-color:orange!important}
.single-page-edit-button{height:30px;width:30px;position:absolute;top:50%;left:50%;text-align:center;border-radius:100px;z-index:1;line-height:30px;font-size:12px;box-shadow:0 .125rem .25rem rgba(0,0,0,.1)!important}
.single-page-edit-button.bg-danger { z-index: 2; color: #fff; }
.notify-footer { position: fixed;    width: 230px;    bottom: 0;    margin-bottom: 0;    right: 10%; z-index: 99999; }
.notify-footer .chat-handle { cursor:pointer; border: 1px solid #000; border-top-right-radius: 5px;border-top-left-radius: 5px;  background: #121212; margin-bottom:-1px;  }
.notify-footer strong.bg-danger { font-size: 10px;    padding: 4px;    border-radius: 50%; padding: 3px 8px; }
.notify-footer .m_count span { margin-left: 10px; font-weight: 500;    font-size: 14px; text-shadow: 1px 1px #000; }
.notify-footer .m_count:not(.has_alert) strong { display:none; }
.notify-footer .dropdown-item {    border-bottom: 1px solid #f0f0f0 !important; padding: 10px 20px; }
.notify-footer .dropdown-item:first-child {    background: #fbfbfb; }
.notify-footer .active-contact {    background-color: transparent !important;    border-right: 0px solid #66bb6a !important;}
.notify-footer .no-msg { height:60px; line-height:50px; font-size: 14px; }
.notify-footer .fa-circle { font-size:10px; color:#34c434; margin-right:5px; }
.notify-footer small { max-width: 130px;    display: inline-block; font-size: 12px !important; line-height: 10px; }

.notify-footer ._name { font-weight:600; font-size:14px; }
.notify-footer ._desc { font-size:12px; opacity:0.5  }
.notify-footer .ppt-avatar { margin-right:20px; }


/*------------------------------------------*/
/*	24 - Footer Section 
/*------------------------------------------*/

.boxed footer{padding-left:30px;padding-right:30px}footer.bg-white{border-top:1px solid #dee2e6!important}
footer.bg-light a,footer.bg-white a{color:#333}
footer.bg-black a,footer.bg-dark a,footer.bg-primary a,footer.bg-secondary a{color:#fff}
footer.bg-black,footer.bg-dark,footer.bg-primary,footer.bg-secondary{color:#fff}

.footer-txt-light, .footer-txt-light a, .footer-txt-light .ppt-icons-social li a { color:#fff!important; }
.footer-txt-dark, .footer-txt-dark a, .footer-txt-dark .ppt-icons-social li a, .footer-txt-dark .textlogo.navbar-brand-light { color:#000!important; }

.footer-txt-dark hr { background-color:#FFFFFF; }
.footer-txt-light hr { background-color:#ffffff26; }



/*------------------------------------------*/
/*	Single Page
/*------------------------------------------*/

.btn-whatsapp {  background-color: #05cd51!important; }
.btn-whatsapp, .btn-whatsapp i {  color:#fff!important; }
.btn-favs-text { font-size: 14px !important;    color: #919191 !important; box-shadow: none!important; }

.ppt-single-datafields .title { margin-top:20px!important; opacity:0.5 }

@media (max-width: 575.98px) {
.download-bar a { display:block;   }
.download-bar { line-height:40px; }
}

/*------------------------------------------*/
/*	video
/*------------------------------------------*/

.videoplaybutton_wrap { position: absolute;top: 45%;left: 40%; }
@media (max-width: 575.98px){
.videoplaybutton_wrap { position: absolute;top: 30%!important;left: 35%!important; }
}


.videoplaybutton{position:relative}
.videoplaybutton{width:100px;height:100px;display:inline-block;text-align:center;border-radius:100px;z-index:1;top:-20px;box-shadow:0 .5rem 1rem #000!important}
.videoplaybutton i{position:absolute;top:41%;left:45%;font-size:20px}
.videoplaybutton .ripple_playbtn{position:absolute;width:160px;height:160px;z-index:-1;left:50%;top:50%;opacity:0;margin:-80px 0 0 -80px;border-radius:100px;-webkit-animation:ripple_playbtn 1.8s infinite;animation:ripple_playbtn 2s infinite;animation-iteration-count:10;animation-delay:2s}
@-webkit-keyframes ripple_playbtn{0%{opacity:1;-webkit-transform:scale(0);transform:scale(0)}100%{opacity:0;-webkit-transform:scale(1);transform:scale(1)}}@keyframes ripple_playbtn{0%{opacity:1;-webkit-transform:scale(0);transform:scale(0)}100%{opacity:0;-webkit-transform:scale(1);transform:scale(1)}}.videoplaybutton .ripple_playbtn:nth-child(2){animation-delay:.3s;-webkit-animation-delay:.3s}.videoplaybutton .ripple_playbtn:nth-child(3){animation-delay:.6s;-webkit-animation-delay:.6s}.sidebar-fixed-content .btn-light{font-size:14px;line-height:30px}


/*------------------------------------------*/
/*	23 - Rating System
/*------------------------------------------*/ 



.ppt-star-rating .bg-primary:not(.text-warning) { color: #e4e4e4!important;  background:#fafafb !important;     border: 1px solid #ddd; }
.ppt-tabs-listing .ppt-star-rating .bg-primary:not(.text-warning) { background: #e5e5e5 !important; }
.ppt-star-rating .bg-primary { padding:0px 5px;  border-radius: 4px; }
.ppt-star-rating .bg-primary.text-warning { color: #ffffff!important;    }
.ppt-star-rating .bg-primary+.bg-primary { margin-left:1px; }

.ppt-star-rating.ppt-star-rating.size-xxl .bg-primary:not(.text-warning){  padding: 10px; background: #fafafb26 !important; color: #0000002e!important; }
.ppt-star-rating.ppt-star-rating.size-xxl .bg-primary.text-warning {  padding: 10px;  }


.ppt-score-rating-xs ._rating { font-weight:600; background-color:#35853e;color:#fff;line-height:1;-webkit-border-radius:5px 5px 5px 0;-moz-border-radius:5px 5px 5px 0;-ms-border-radius:5px 5px 5px 0;border-radius:5px 5px 5px 0; padding: 5px 7px; display:inline-block }

.ppt-score-rating-xs.rating-0 ._rating, .ppt-score-rating.rating-0 strong { background:#ebebeb; }
.ppt-score-rating-xs.rating-1 ._rating, .ppt-score-rating-xs.rating-1 strong { background:#ca0000; }
.ppt-score-rating-xs.rating-2 ._rating, .ppt-score-rating-xs.rating-2 strong { background:#ebebeb; }
.ppt-score-rating-xs.rating-3 ._rating, .ppt-score-rating-xs.rating-3 strong { background:#ffc107; }

.ppt-score-rating-xs-wrap {  background: #fffef9;  }


.ppt-score-rating strong{background-color:#35853e;color:#fff;line-height:1;-webkit-border-radius:5px 5px 5px 0;-moz-border-radius:5px 5px 5px 0;-ms-border-radius:5px 5px 5px 0;border-radius:5px 5px 5px 0;padding:10px;display:inline-block}
.ppt-score-rating span{display:inline-block;position:relative;top:7px;margin-right:8px;font-size:12px;text-align:right;line-height:1.1;font-weight:500}
.ppt-score-rating span em{display:block;font-weight:400;font-size:11px;margin-top:5px;color:#666}
.ppt-score-rating.rating-0 strong { background:#f2f2f2 !important; }

.ppt-star-rating .rating-extras { padding-top:4px; }
.ppt-star-rating .svg-icon { width:16px; height:16px; margin: 0px -3px;  } 
.ppt-star-rating.size-xs .svg-icon {  width:12px; height:12px; margin-left:0px }
.ppt-star-rating.size-sm .svg-icon {  width: 16px;    height: 16px;    margin: 0px -1px; }
.ppt-star-rating.size-md .svg-icon {  width:24px; height:24px; }
.ppt-star-rating.size-lg .svg-icon {  width:32px; height:32px; }
.ppt-star-rating.size-xl .svg-icon {  width:34px; height:34px; }

.ppt-star-rating.size-xs .total { font-size:10px; } 
.ppt-star-rating.size-xs .reviews { font-size:10px; }

.ppt-star-rating.size-sm .total { font-size:12px; }   
.ppt-star-rating.size-sm .reviews { font-size:12px; }

.ppt-star-rating.size-md .total { font-size:14px; } 
.ppt-star-rating.size-md .reviews { font-size:14px;  }

.ppt-star-rating.size-lg .total { font-size:16px; } 
.ppt-star-rating.size-lg .reviews { font-size:16px;  }

.ppt-star-rating.size-xs .bg-primary .svg-icon {    width: 15px;    height: 18px;}
.ppt-star-rating.size-xs .bg-primary .svg-icon svg { margin-left: -1px;    margin-top: -6px;    width: 15px; }
.ppt-star-rating.size-sm .bg-primary .svg-icon {    width: 20px;    height: 25px;}
.ppt-star-rating.size-md .bg-primary .svg-icon {    width: 24px;    height: 24px;}


.rating-score-small strong{background-color:#35853e;color:#fff;line-height:1;-webkit-border-radius:5px 5px 5px 0;-moz-border-radius:5px 5px 5px 0;-ms-border-radius:5px 5px 5px 0;border-radius:5px 5px 5px 0;padding:10px;display:inline-block}
.rating-score-small span{display:inline-block;position:relative;top:7px;margin-right:8px;font-size:12px;font-size:.75rem;text-align:right;line-height:1.1;font-weight:500}
.rating-score-small span em{display:block;font-weight:400;font-size:11px;margin-top:5px;color:#666}

.rating-score-big{background:#18458b;color:#fff;font-weight:600;border-radius:7px 7px 0 7px;padding:22px 0;width:100%;font-size:34px}
.rating-score-big strong{display:block;font-size:14px;padding-top:6px;font-weight:400}.rating-score-small.extrasmall strong{padding:5px!important}.rating-color-1{background:#d80000!important}.rating-color-2{background:#ffc107!important}.rating-color-3{background:#07b5ff!important}.rating-color-4{background:#33ccac!important}.rating-color-5{background:#35853e!important}.rating-symbol{margin:0 1px}.rating-symbol .rating-rated{color:orange}.rating-symbol-total{font-weight:700}.rating-symbol-reviews{letter-spacing:1.5px;margin-left:2px}.rating-score-5{color:orange}


.rating_newstyle .rating-symbol{margin:0 2px;padding:2px 3px;margin-right:0;background:#efefef;color:#fff;border-radius:4px;font-size:8px}
.rating_newstyle .rating-symbol .rating-rated{color:#fff!important}.rating_newstyle.big .rating-symbol{padding:5px 10px;font-size:20px;margin-right:5px}


.ppt-comment-rating { line-height: 14px; }
.ppt-comment-rating .text-truncate {  display: inline-block; font-weight:600;  max-width: 170px; overflow:hidden; }
.ppt-comment-rating ._text { font-size: 12px; font-weight:600; }
.ppt-comment-rating ._time { font-size:11px; opacity:0.5;  }

.ppt-comment-rating.size-lg { padding:10px !important; padding: 25px 20px !important; position: relative; background: #35853e;    color: #fff; }
.ppt-comment-rating.size-lg .text-truncate { max-width:100%; }
.ppt-comment-rating.size-lg ._text { font-size:16px; max-width: 600px; }
.ppt-comment-rating.size-lg ._time { opacity:1; margin-top: 5px; }
.ppt-comment-rating.size-lg:before {
  content: " ";
  position: absolute;
  width: 10px;
  height: 10px;
  right: -6px;
  z-index: 1;
  top: auto;
  bottom: 0;
  border: 6px solid #35853e;
  border-color: transparent transparent #35853e;
}


/*------------------------------------------*/
/*	23 - Remove Later
/*------------------------------------------*/ 

.list-inline  { display: -ms-flexbox!important;    display: flex!important; }


/*------------------------------------------*/
/*	23 - WordPress Editor
/*------------------------------------------*/ 

.wp-block-image img { max-width:100%; }
.wp-block-image {	text-align: center;}

.blog_content { line-height: 35px; }
.blog_content p { margin-bottom:15px;  }

.blog_content .h1, .blog_content .h2, .blog_content .h3, .blog_content .h4, .blog_content .h5, .blog_content .h6, .blog_content h1, .blog_content h2, .blog_content h3, .blog_content h4, .blog_content h5, .blog_content h6 { margin-bottom:20px;  }
.blog_content ul  {    list-style-type: disc!important; margin-left: 30px; margin-bottom:20px; }


/*------------------------------------------*/
/*	26 - SOCIAL BAR
/*------------------------------------------*/ 

@media (min-width:1200px){.socialbar .sharertitle{min-width:100px}.socialbar .sharebutton{margin:0 10px}}
@media all{

.socialbar .sharertitle{display:inline-block;border-right:1px solid #dfdfdf;padding:0 20px 2px 5px;margin:0 20px 0 0;color:#b1a9a5;text-transform:uppercase;vertical-align:middle;text-align:center}
.total-count{color:#333;font-size:20px;font-weight:700}
.total-text{font-size:12px;display:block;margin:-5px 0 0}
.socialbar .sharebutton{display:inline-block;line-height:36px;margin:0 5px}
.social-buttons a{color:#666;text-decoration:none;font-size:14px}
@media screen and (min-width:991px){
.socialbar{width:100%;border-top:1px solid #dfdfdf; border-bottom:1px solid #dfdfdf;padding:20px 0 20px 0;margin:10px 0 20px 0;float:left;background:#fff}
}
@media screen and (max-width:500px){
.sharebutton span.count{text-indent:-9999px;padding:0 0 0 15px!important;width:0;display:inline-block}
}
@media print{.social-buttons{display:none}}}




/*------------------------------------------*/
/*	Mobile - Footer
/*------------------------------------------*/
.body-hide-footer footer { display:none; }

@media (max-width: 575.98px) { 

.footer-nav-area:not(.preview){ display:block !important; }
}

.footer-nav-area:not(.hide-mobile){-webkit-transition-duration:500ms;transition-duration:500ms;background-color:#ffffff;width:100%;height:58px;bottom:0;left:0;right:0;z-index:1000;-webkit-box-shadow:0 -6px 12px rgba(15, 15, 15, 0.15);box-shadow:0 -6px 12px rgba(15, 15, 15, 0.15);  }
.footer-nav-area:not(.preview){ position:fixed; display:none; }
.suha-footer-nav ul{width:100%;}
.suha-footer-nav ul li{-webkit-box-flex:1;-ms-flex:1 1 0px;flex:1 1 0;position:relative;z-index:1;}
.suha-footer-nav ul li a{position:relative;display:block;font-size:12px;text-align:center;font-weight:700;text-transform:capitalize;line-height:1;color:#23282d;;z-index:1; text-decoration:none; }
.suha-footer-nav ul li a i{display:block;font-size:18px;margin-bottom:4px;  }
.suha-footer-nav ul li a:hover,.suha-footer-nav ul li a:focus{color:#23282d; text-decoration:none}
.suha-footer-nav ul li.active a{color:#23282d; text-decoration:none}

.suha-footer-nav .menu-add{ height: 65px;
  width: 65px;
  background: red;
  margin-top: -26px;
  border: 5px solid #fff;
  margin-left: 10px;
  border-radius: 50%;
  line-height: 60px;}
.suha-footer-nav ul li a.menu-add i { display:inline-block; }
