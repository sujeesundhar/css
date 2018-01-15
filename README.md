/*------------------------------------------------------------------
Theme Name: Shuttle
Theme URL: http://codnauts.com
Author: Codnauts
Author URI: http://themeforest.net/user/codnauts
Version: 1.0
License: Regular or Extended from ThemeForest only
Plugin Licenses: GPL or MIT
Last change: first release
Primary use: App & Mobile Website 
-------------------------------------------------------------------*/
/*------------------------------------------------------------------
[Table of contents]
    0. General
    1. Typography 
    2. Colors & Backgrounds
    3. Animations
    4. Input & Form Elements
    5. Layout
    6. Toolbar
    7. Drawer
    8. Sliders
    9. Elements
    5. Animation
    6. Toolbar
    7. Sidebars
    8. Elements
/*---------------------------------------------------------------- */


/*  0. General
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
/* NOTE
html is set to 62.5% so that all the REM measurements
are based on 10px sizing. So basically 1.5rem = 15px */
html {
  font-size: 62.5%;
  overflow-x: hidden;
}
html, body {
  -webkit-font-smoothing: antialiased;
  -webkit-text-size-adjust: 100%;
  text-rendering: optimizeLegibility;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
img {
  max-width: none;
  display: block;
  width: 100%;
  vertical-align: middle;
}
fieldset {
    border: 0;
    margin: 0;
    padding: 0;
}
textarea {
    resize: vertical;
}

/*  1. Typography
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
body {
  font-size: 1.5em;
  line-height: 1.6;
  font-weight: 400;
  font-family: 'Roboto', sans-serif;
  color: #666; 
  margin: 0;
  overflow-x: hidden;
}

h1, h2, h3, h4, h5, h6 {
  font-family: 'Varela Round', sans-serif;
  margin-top: 0;
  margin-bottom: 2rem;
  font-weight: 400; 
  color: #1c212a;
}
h1 { font-size: 2.4rem; line-height: 3rem; }
h2 { font-size: 2.2rem; line-height: 3rem; }
h3 { font-size: 2rem; line-height: 2.2rem; }
h4 { font-size: 1.8rem; line-height: 2.2rem; }
h5 { font-size: 1.6rem; line-height: 2rem; }
h6 { font-size: 1.4rem; line-height: 2rem; }

p { margin-top: 0; }

a { color: inherit; }
a:hover { opacity: 0.95; }

a,
a:link,
a:hover,
a:active,
a:focus {
    outline: 0;
    text-decoration: none;
}
body,
input,
textarea,
button,
select,
label,
a {
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

blockquote {
  background: #f9f9f9;
  padding: 20px;
}

input,
textarea,
button,
select,
label,
.btn, 
.btn-large, 
.btn-flat {
  font-family: 'Varela Round', sans-serif;
}
.btn.transparent,
.btn-large.transparent {
  padding-left: 40px;
  padding-right: 40px;
  border: 1px solid #fff;
  background: transparent;
  box-shadow: none;
}

[class^="mdi-"],
[class*="mdi-"] {
  font-family: "Ionicons";
}
i {
  font-size: 2.4rem;
  color: inherit;
}
i.big {
  font-size: 3.6rem;
}
input,
textarea,
select,
fieldset {
  margin-bottom: 1.5rem; 
}
pre,
blockquote,
dl,
figure,
table,
p,
ul,
ol,
form {
  margin-bottom: 2.5rem; 
}

hr {
  margin-top: 3rem;
  margin-bottom: 3.5rem;
  border-width: 0;
  border-top: 1px solid #E1E1E1; 
}

.small {
  font-size: 85% !important;
  font-weight: 300;
}

.dropcap {
  float: left;
  color: #444444;
  font-size: 75px;
  font-family: 'Varela Round', sans-serif;
  line-height: 60px;
  padding-top: 8px;
  padding-right: 8px;
  padding-left: 3px;
}

.title.big {
  font-size: 7rem;
}

/*  2. Colors & Backgrounds
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
.accent-text {
    color: #fdd835 !important;
}
.accent-color {
    background-color: #fdd835 !important;
}
.accent-border {
    border-color: #fdd835 !important;
}
.primary-text {
    color: #01acc6 !important;
}
.primary-color {
    background-color: #00897B !important;
}
.primary-border {
    border-color: #00897B !important;
}
.text-light {
    font-weight: 400;
    color: #B2B2B4;
}
.transparent {
    background-color: transparent !important;
}
.no-shadow {
  box-shadow: none;
}

/* bg */
.bg-1 {
    background: url(../img/1.jpg) no-repeat center / cover !important;
}
.bg-2 {
    background: url(../img/2.jpg) no-repeat center / cover !important;
}
.bg-3 {
    background: url(../img/3.jpg) no-repeat center / cover !important;
}
.bg-4 {
    background: url(../img/4.jpg) no-repeat center / cover !important;
}
.bg-5 {
    background: url(../img/5.jpg) no-repeat center / cover !important;
}
.bg-9 {
    background: url(../img/9.jpg) no-repeat center / cover !important;
}
.bg-material {
    background: url(../img/material.jpg) no-repeat center / cover !important;
}
.bg-blur {
    background: url(../img/blur.jpg) no-repeat center / cover !important;
}
.bg-opacity {
    background: url(../img/opacity.jpg) no-repeat center / cover !important;
}
.bg-gradient {
    background: -webkit-linear-gradient(135deg,#01acc6,#00555f);
    background: linear-gradient(135deg,#01acc6,#00555f);
}
.bg-shop {
    background: url(../img/shop.jpg) no-repeat center / cover !important;
}

/* Overlay */
.opacity-overlay {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: rgba(0,0,0,.5);
}
.opacity-overlay-gradient {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: rgba(0, 0, 0, 0) -webkit-gradient(linear, left top, left bottom, color-stop(48%, rgba(0, 0, 0, 0)), color-stop(90%, rgba(0, 0, 0, .85)), to(#000)) repeat scroll 0 0;
    background: rgba(0, 0, 0, 0) -webkit-linear-gradient(top, rgba(0, 0, 0, 0) 48%, rgba(0, 0, 0, .85) 90%, #000 100%) repeat scroll 0 0;
    background: rgba(0, 0, 0, 0) -o-linear-gradient(top, rgba(0, 0, 0, 0) 48%, rgba(0, 0, 0, .85) 90%, #000 100%) repeat scroll 0 0;
    background: rgba(0, 0, 0, 0) linear-gradient(to bottom, rgba(0, 0, 0, 0) 48%, rgba(0, 0, 0, .85) 90%, #000 100%) repeat scroll 0 0;
}
.opacity-overlay-gradient-reverse {
    opacity: 0.7;
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: rgba(0, 0, 0, 0) -webkit-gradient(linear, left bottom, left top, color-stop(70%, rgba(0, 0, 0, 0)), color-stop(95%, rgba(0, 0, 0, .75)), to(#333)) repeat scroll 0 0;
    background: rgba(0, 0, 0, 0) -webkit-linear-gradient(bottom, rgba(0, 0, 0, 0) 70%, rgba(0, 0, 0, .75) 95%, #333 100%) repeat scroll 0 0;
    background: rgba(0, 0, 0, 0) -o-linear-gradient(bottom, rgba(0, 0, 0, 0) 70%, rgba(0, 0, 0, .75) 95%, #333 100%) repeat scroll 0 0;
    background: rgba(0, 0, 0, 0) linear-gradient(to top, rgba(0, 0, 0, 0) 70%, rgba(0, 0, 0, .75) 95%, #333 100%) repeat scroll 0 0;
}

/*  3. Animations
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
.animated {
    -webkit-animation-duration: 0.5s;
    animation-duration: 0.5s;
    -webkit-transition-timing-function: ease-in;
    transition-timing-function: ease-in;
    -webkit-animation-fill-mode: both;
    animation-fill-mode: both;
}
.fadein {
    -webkit-animation-name: fadeIn;
    animation-name: fadeIn;
    -webkit-animation-duration: 0.4s;
    animation-duration: 0.4s;
}
.fadeinup {
    -webkit-animation-name: fadeInUp;
    animation-name: fadeInUp;
}
.fadeindown {
    -webkit-animation-name: fadeInDown;
    animation-name: fadeInDown;
}
.fadeinright {
    -webkit-animation-name: fadeInRight;
    animation-name: fadeInRight;
}
.bouncein {
    -webkit-animation-name: bounceIn;
    animation-name: bounceIn;
}
#main.is-exiting .animated {
    -webkit-animation-name: fadeOut;
    animation-name: fadeOut;
}
.delay-1 {
    -webkit-animation-delay: 0.1s;
    animation-delay: 0.1s;
}
.delay-2 {
    -webkit-animation-delay: 0.25s;
    animation-delay: 0.25s;
}
.delay-3 {
    -webkit-animation-delay: 0.4s;
    animation-delay: 0.4s;
}
.delay-4 {
    -webkit-animation-delay: 0.55s;
    animation-delay: 0.55s;
}
.delay-5 {
    -webkit-animation-delay: 0.45s;
    animation-delay: 0.45s;
}
.delay-6 {
    -webkit-animation-delay: 0.95s;
    animation-delay: 0.95s;
}

/*  4. Input & Form Elements
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
.input-field {
  margin-bottom: 2.5rem;
}
.input-field label {
  font-size: 1.5rem;
  top: 0.5rem;
}
.input-field label.active {
  font-size: 1.2rem;
}
label {
    font-size: 1.5rem;
}
input:not([type]), 
input[type=text], 
input[type=password], 
input[type=email], 
input[type=url], 
input[type=time], 
input[type=date], 
input[type=datetime], 
input[type=datetime-local], 
input[type=tel], 
input[type=number], 
input[type=search], 
textarea.materialize-textarea {
  font-size: 1.5rem;
  padding-left: 8px;
}
/* Searchbar */
.input-field input[type=search] ~ i,
.input-field input[type=search] ~ i {
    position: absolute;
    top: 0;
    right: 1rem;
    color: transparent;
    cursor: pointer;
    font-size: 2rem;
    transition: .3s color;
}
.input-field input[type=search]:focus + label i,
.input-field input[type=search]:focus ~ i,
.input-field input[type=search]:focus ~ i {
    color: #444;
}
.hidden-search {
  background: transparent;
  box-shadow: none;
}
.hidden-search .input-field label.active i {
  color: #444;
}
.input-field input[type=search]:focus {
  box-shadow: 0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);
}
/* Checkbox */
[type="checkbox"]+label,
[type="radio"]:not(:checked)+label, 
[type="radio"]:checked+label {
  font-size: 1.5rem;
}
[type="radio"]:checked+label:after, 
[type="radio"].with-gap:checked+label:after {
    background-color: #01acc6;
    z-index: 0;
}
[type="radio"]:checked+label:after, 
[type="radio"].with-gap:checked+label:before, 
[type="radio"].with-gap:checked+label:after {
    border: 2px solid #01acc6;
}

.side-nav nav .input-field input[type=search] {
  padding: 0 1rem;
  margin: 0;
  border-bottom: none !important;
  box-shadow: none !important;
}
nav .input-field input[type=search] {
  height: 56px;
  padding-left: 4rem;
}
nav .input-field label i {
  color: inherit;
}

/*  5. Layout
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
.relative {
  position: relative;
}
.block {
  display: block;
}
.clr {
  clear: both;
}
nav {
  background-color: #fff;
}
.page {
  padding-top: 56px;
}
.page.fullscreen {
  padding-top: 0;
  height: 100vh;
}
.page.with-tab {
  padding-top: 120px;
}
.bottom {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
}
.valign-wrapper .valign {
    width: 100%;
}
.fixed-action-btn.horizontal ul li {
    margin: 12px 15px 0 0;
}
.p-0 {
  padding: 0 !important;
}
.m-0 {
  margin: 0 !important;
}
.p-10 {
  padding: 10px !important;
}
.p-20 {
  padding: 20px !important;
}
.m-20 {
  margin: 20px !important;
}
.m-b-20 {
  margin-bottom: 20px !important;
}
.section {
  padding: 40px 20px;
  position: relative;
}
.section.featured {
  padding: 50px 20px 0;
}
.section.featured img {
  margin-top: 20px;
}
.section .heading {
  font-size: 2rem;
  margin-bottom: 0;
}
.section i.infograph {
  display: block;
  font-size: 7rem;
  height: 7rem;
  line-height: 7rem;
  margin-bottom: 1.5rem;
  color: #1c212a;
}
.section p {
  margin: 0;
}

/* Footer */
footer.page-footer {
  margin: 0;
  padding: 0;
}
.footer-icons {
  margin-top: 10px;
}
.footer-icons i {
  padding: 0 5px;
}
footer.page-footer .footer-copyright {
  font-size: 1.2rem;
}
footer.page-footer .footer-copyright i {
  font-size: inherit;
  margin: 0 3px;
}

/* Hero */
.none {
    display: none;
}
.hero-material {
    height: 212px;
    position: relative;
    z-index: 1;
}
.hero-material .parallax {
    height: 100%;
}
.hero-material .parallax img {
    display: block;
}
.banner-title {
    font-family: 'Varela Round', sans-serif;
    font-size: 22px;
    font-weight: 300;
    position: absolute;
    left: 33px;
    bottom: 30px;
    color: #fff;
    line-height: auto;
    margin-left: 9px;
    padding-left: 30px;
    text-transform: none;
    letter-spacing: normal;
    z-index: 9;
}
.banner {
    height: 300px;
    margin-top: 56px;
    position: relative;
}
.banner .parallax {
    height: 100%;
}
.nav-material {
    height: 56px;
    position: fixed;
    z-index: 2;
    top: 0px;
    background: none;
    -webkit-transition: height 0.3s;
    -moz-transition: height 0.3s;
    -ms-transition: height 0.3s;
    -o-transition: height 0.3s;
    transition: height 0.3s;
}
.nav-material {
    background: none;
}
.box-shad-none {
    box-shadow: none;
}
.nav-material.smaller {
    height: 56px;
}
.nav-material.smaller span {
    bottom: 15px;
}
.hero-material .floating-button {
    position: absolute;
    bottom: -25px;
    right: 20px;
}
.nav-material.nav-bg {
    background-color: #01acc6;
    box-shadow: 0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);
}
.subtitle {
    position: absolute;
    left: 73px;
    bottom: 71px;
    color: #fff;
    opacity: 0.6;
}
.btn-floating.btn-large i {
    font-size: 2.4rem;
    line-height: 60px;
}

/* Page Header */
.hero-header {
    position: relative;
    z-index: 1;
}
.hero-header .floating-button {
    position: absolute;
    bottom: -27px;
    right: 20px;
    z-index: 2;
}
.floating-button.scrollable-fab.scrolled-down {
    position: fixed;
    bottom: 20px;
}
.hero-header .hero-over {
    position: absolute;
    bottom: 20px;
    left: 20px;
    margin: 0;
}

/* Hero Big */
.hero-header.hero-big {
  text-align: center;
  padding-top: 100px;
}
.hero-header.hero-big .media-top-object {
  margin-bottom: 0;
}
.hero-header.hero-big .hero-author {
  padding: 20px;
  position: relative;
  z-index: 2;
}
.hero-header.hero-big .card-feedback {
  padding: 0;
  margin: 0;
  border-bottom: none;
}
.hero-header.hero-big .card-feedback i {
    font-size: 1.5rem;
}
.hero-header.hero-big .media-body > span {
  margin-bottom: 8px;
}

/*  6. Toolbar
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
/* Drag Trigger */
.drag-target {
    width: 25px !important;
    top: 56px;
}
/* Toolbar */
#toolbar {
    width: 100%;
    height: 56px;
    position: fixed;
    z-index: 99;
    top: 0;
    left: 0;
    right: 0;
    display: flex; 
    transition: all .25s ease-in-out;
}
#toolbar.with-tab {
  height: 112px;
  flex-wrap: wrap;
}
#toolbar.with-tab .open-left,
#toolbar.with-tab .open-right,
#toolbar.with-tab .title {
  height: 56px;
}
#toolbar.with-tab a.active i {
  color: #fff;
}
#toolbar .tabs {
  margin-bottom: 10px;
}
#toolbar .tabs .tab a {
  color: #fff;
}
#toolbar .tabs .tab a.active {
  color: #fff;
}
#toolbar .tabs .indicator {
  background-color: #fff;
}
#toolbar.nav-material {
  justify-content: space-between;
}
#toolbar.nav-material .title {
  margin-left: 16px;
  text-align: left;
  color: #fff;
}
#toolbar.nav-material i {
  color: #fff;
}
#toolbar.transparent {
    background-color: transparent !important;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 3;
}
.open-left {
    flex: 0 0 56px;
    line-height: 56px;
    text-align: center;
    position: relative;
}
.open-right {
    flex: 0 0 56px;
    line-height: 56px;
    text-align: center;
    position: relative;
}
#toolbar i {
    color: #fff;
}
#toolbar .title {
    font-family: 'Varela Round', sans-serif;
    font-size: 22px;
    font-weight: 400;
    color: #fff;
    line-height: 56px;
    text-align: center;
    margin: 0;
    flex-grow: 2;
}
#toolbar.left-only .title {
    text-align: left;
    margin-left: 16px;
}
#toolbar.right-only .title {
    text-align: left;
    margin-left: 16px;
}
#toolbar.transparent i,
#toolbar.transparent .title {
  color: #222;
}
#toolbar.no-title {
  justify-content: space-between;
}
.heads-up {
  transform: translateY(-212px);
  transform: translate3d(0,-212px,0);
}

/*  7. Drawer
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
.side-nav {
  border: none;
}
.side-nav a:hover {
  background: transparent;
}
.sidenav-avatar {
  width: 100%;
  height: 158px; /* 16:9 aspect ratio if sidebar have 280px width */ 
  position: relative;
}
.sidenav-avatar .opacity-overlay-gradient {
  opacity: 0.5;
}
.sidenav-avatar .bottom .avatar {
  width: 64px;
  height: 64px;
  margin: 0 0 10px 30px;
}
.side-nav .dropdown-button {
  display: block;
  width: 100%;
  font-weight: 700;
  font-size: 1.3rem;
  padding: 0 16px 0 30px;
  height: 50px;
  line-height: 50px;
  color: #fff;
}
.side-nav .dropdown-content.active {
  z-index: 999;
}
.side-nav .dropdown-content i {
  margin-top: 1px;
}
.sidenav-header {
  width: 100%;
  position: relative;
  overflow: auto;
}
.sidenav-header form {
  margin-bottom: 0;
}
.sidenav-header .input-field {
  height: 56px;
  padding: 0 30px;
}
.side-nav .collapsible-header {
  line-height: initial;
  height: auto;
  padding: 18px 30px 17px;
  font-weight: 700;
  font-size: 1.3rem;
  color: #333;
}
.side-nav .collapsible-header.active {
    color: #01acc6;
}
.side-nav .collapsible-header i {
  margin-top: -2px;
}
.side-nav li {
  line-height: inherit;
}
.side-nav li a {
  font-size: 1.3rem;
  font-weight: 700;
  color: #222;
  line-height: initial;
  height: auto;
  padding: 18px 30px 17px;
}
.side-nav li a i {
  width: 2rem;
  font-size: 1.6rem;
  line-height: inherit;
  display: block;
  float: left;
  text-align: center;
  margin-right: 1rem;
  top: -2px;
  position: relative;
}
.side-nav .collapsible-body li a, 
.side-nav.fixed .collapsible-body li a {
  line-height: initial;
  height: auto;
  padding: 16px 30px 15px 72px;
  font-weight: 400;
  font-size: 1.3rem;
  color: #333;
}
.side-nav li.active,
.side-nav .collapsible-header:hover, 
.side-nav.fixed .collapsible-header:hover {
  background-color: transparent;
  color: #01acc6;
}

/* Sidebar Chat */
.chat-sidebar {
    display: flex;
    align-items: flex-start;
    padding: 10px 0;
    position: relative;
}
.chat-img img {
    margin-right: 10px;
    margin-top: 4px;
    width: 32px;
    height: 32px;
    color: #fff;
    border-radius: 50%;
    line-height: 48px;
    text-align: center;
    position: relative;
    flex: 1;
}
.chat-img .dot {
    width: 12px;
    height: 12px;
    border-radius: 100%;
    border: 2px solid #fff;
    position: absolute;
    top: 35px;
    left: 22px;
}
.chat-message {
    flex: 1;
    font-size: 12px;
}
.chat-message p {
    margin: 0;
    font-family: 'Varela Round', sans-serif;
    font-size: 14px;
    color: #444;
}
.chat-message .small {
    display: block;
}

/* badge */
.side-nav span.more {
    min-width: auto;
    width: 1.5rem;
    height: 1.5rem;
    text-align: center;
    line-height: 1.5rem;
    font-size: 0.8rem;
    font-weight: 700;
    border-radius: 2px;
    color: initial;
    margin: 2px 0 0;
    padding: 0;
    opacity: 0.3;
    position: absolute;
    right: 15px;
    box-sizing: border-box;
}
.side-nav span.more i {
  -webkit-transition: all 0.2s ease-in;
  transition: all 0.2s ease-in;
}
.side-nav .collapsible-header.active span.more i {
  -webkit-transform: rotate(-90deg);
  -moz-transform: rotate(-90deg);
  transform: rotate(-90deg);
}

/*  8. Sliders
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
/* Paginations */
.swiper-pagination.swiper-pagination-progress {
  bottom: 0;
  top: auto;
}
.swiper-pagination-progress .swiper-pagination-progressbar {
  background: #01acc6;
  opacity: 0.9;
}
.swiper-pagination-bullet {
  width: 15px;
  height: 3px;
  border-radius: 0;
}
.swiper-pagination-bullet-active {
  background: #01acc6;
}
.swiper-button-next, 
.swiper-container-rtl .swiper-button-prev {
  background-image: none;
  right: 20px;
  width: auto;
  height: auto;
}
.swiper-button-prev, 
.swiper-container-rtl .swiper-button-next {
  background-image: none;
  left: 20px;
  width: auto;
  height: auto;
}
.swiper-container-horizontal>.swiper-pagination-bullets, 
.swiper-pagination-custom, 
.swiper-pagination-fraction {
    bottom: 20px;
}
/* Sliders */
.swiper-slide .bottom {
  padding: 20px 20px 40px !important;
}
/* Slider Sliced */
.slider-sliced .swiper-slide {
    width: 100%;
    height: 100vh;
    background-color: transparent;
    overflow: hidden;
}
.slider-sliced .valign {
  padding: 0 0 40px;
}
.slider-sliced .valign p {
  font-weight: 100;
}
.slider-sliced .slider-bottom-right {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: 1;
    background-color: #fff;
    padding: 0 50px;
}
.slider-sliced .slider-bottom-right:before {
    position: absolute;
    content: '';
    width: 0;
    height: 0;
    right: 0;
    top: -90px;
    border-bottom: 90px solid #fff;
    border-left: 768px solid rgba(255, 255, 255, 0);
    -moz-transform: scale(.9999);
}
.slider-sliced .slider-bottom-left {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: 1;
    background-color: #fff;
    padding: 0 50px;
}
.slider-sliced .slider-bottom-left:before {
    position: absolute;
    content: '';
    width: 0;
    height: 0;
    left: 0;
    top: -90px;
    border-bottom: 90px solid #fff;
    border-right: 768px solid rgba(255, 255, 255, 0);
    -moz-transform: scale(.9999);
}
.slider-sliced .swiper-container-horizontal>.swiper-pagination .swiper-pagination-bullet {
    margin: 0 10px;
}
/* Slider Steps */
.slider-steps {
    width: 100%;
    height: 100vh;
}
.slider-steps img {
  width: 50%;
  margin: 0 auto 30px;
}
.slider-steps .valign-wrapper {
    height: 100%;
}
.slider-steps .valign {
    margin-top: -100px;
    width: 100%;
}
.steps-controllers {
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: 10;
}
.steps .swiper-pagination {
  margin-bottom: 60px;
}
.steps .swiper-pagination .swiper-pagination-bullet {
  margin: 5px;
}
/* Drawer */
.swiper-container.slider-drawer {
    height: calc(100vh - 56px);
}
.slider-drawer .swiper-slide {
    width: calc(100% - 16px) !important;
    height: calc(100vh - 112px);
    overflow: hidden;
    margin: 8px 8px 32px;
    padding: 16px;
    box-sizing: border-box;
    background-color: rgba(255,255,255,.92);
}
.slider-drawer .drawer-pagination {
    position: fixed;
    bottom: 6px;
}
.slider-drawer .swiper-pagination-bullet-active {
    background: #fff;
}
.slider-drawer .row .col {
  text-align: center;
}
.slider-drawer .row .col span {
    font-size: 0.7em;
    display: block;
}
.slider-drawer .row .col i {
    font-size: 40px;
}
.grandparent {
    display: flex;
    flex-wrap: wrap;
    align-items: stretch;
    height: 100%;
}
.grandparent .row {
  flex: 0 0 100%;
  flex-wrap: wrap;
  align-items: center;
}
.child {
    margin-bottom: 0;
} 
/* Testimonial */
.testimonials {
  margin: 30px 0;
  padding: 30px 40px;
}
.testimonials .avatar {
  margin: 40px auto 10px;
  width: 72px;
  height: 72px;
}
.testimonials .testimonial {
  padding: 20px;
  border-radius: 6px;
  background: #01acc6;
  color: #fff;
  position: relative;
  opacity: 0.3;
  -webkit-transition: opacity 0.3s ease;
  transition: opacity 0.3s ease;
  font-style: italic;
}
.swiper-slide.swiper-slide-active .testimonial {
  opacity: 1;
}
.testimonials .testimonial:after {
  content: '';
  width: 30px;
  height: 30px;
  border-radius: 3px;
  background: #01acc6;
  position: absolute;
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
  bottom: -12px;
  left: 50%;
  margin-left: -15px;
}

/*  9. Elements
    â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“â€“ */
/* Avatar */
.avatar {
    width: 40px;
    height: 40px;
    border-radius: 50%;
}
.avatar.small {
  width: 32px;
  height: 32px;
}
.avatar.big {
  width: 62px;
  height: 62px;
}
.avatar.big.center {
  margin: 0 auto 10px;
}
.unknow-avatar {
    position: absolute;
    top: 10px;
    left: 10px;
    border-radius: 50%;
}
.unknow-avatar span {
    display: block;
    font-size: 24px;
    color: #ffffff;
    width: 40px;
    height: 40px;
    line-height: 40px;
    text-align: center;
    font-weight: 100;
}
.avatar.with-letter span {
    line-height: 40px;
    width: 40px;
    height: 40px;
    text-align: center;
    font-size: 20px;
    font-weight: 100;
    display: block;
}

/* Media Object */
.media-top-object {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  margin-bottom: 1em;
}
.media-top-object.middle {
  align-items: center;
}
.media-top-object .media-left {
  display: block;
}
.media-top-object .media-body {
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  padding-left: 20px;
}
.media-top-object .media-body p {
  margin: 0;
}
.media-top-object .media-body span {
  display: block;
}

.media-top-object.v-center {
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

/* Social Share */
.project-social-share {
    position: absolute;
    right: 0;
    top: -4px;
}
.project-social-share i {
    margin-left: 10px;
}
.social-share-author {
    position: relative;
    margin: 0;
    padding: 0;
}
.social-share-author .avatar {
    width: 30px;
    height: 30px;
    position: absolute;
    left: 0;
    top: 0;
}
.social-share-author span {
    padding-left: 38px;
    padding-top: 4px;
    display: block;
}
.project-author.social-share-author {
    margin: 0 20px 20px;
}

/* Share Counter */
.share-counter {
  display: flex;
  align-items: center;
}
.share-counter > div {
  flex-grow: 1;
  text-align: center;
  border-right: 1px solid #eee;
  padding: 0 20px;
  margin: 20px 0;
}
.share-counter > div:last-child {
  border: none;
}
.share-counter > div h3,
.share-counter > div p {
  margin: 0;
}

/* Music Player */
.player-info {
    padding: 24px 20px;
}
.player-info h4 {
    margin: 0 0 8px;
    font-size: 24px;
    font-weight: 300;
    color: #ffffff;
}
.player-info span {
    color: #ffffff;
    font-size: 14px;
    font-weight: 100;
    opacity: 0.85;
}
.player-controllers {
    padding: 20px;
    display: flex;
}
.player-controllers i {
    color: #ffffff;
    flex-grow: 1;
}
.upnext {
    padding: 20px;
}
.next-song {
    padding: 20px 0;
    position: relative;
}
.next-song span:first-child {
    margin-right: 16px;
}
.next-song i {
    position: absolute;
    right: 0;
    top: 12px;
}

/* Masonry and Filters */
/* Masonry */
.grid {
  margin: 0;
}
.grid-item {
    width: 50%;
    height: auto;
    float: left;
    margin: 0;
    padding: 1px;
}
/* Filter */
.controls button {
    display: inline-block;
    padding: 7px 12px;
    font-size: 14px;
    border: 1px solid #ddd;
    background: transparent;
    color: inherit;
    border-radius: 2px;
    cursor: pointer;
    color: inherit;
    transition: all 0.3s ease-in;
    -webkit-transition: all 0.3s ease-in
}
.controls button.active {
    background: #01acc6;
    color: #fff;
    border-color: #01acc6;
}
.controls label {
    margin-right: 8px;
}
.mix,
.gap {
    float: left;
    width: 50%;
    margin: 0;
}
.mix {
    display: none;
    padding: 1px;
}
.mix figure {
    display: none;
}
#filter.grid .mix {
    width: 50%;
}
#filter .mix {
    width: 100%;
}

/* Card */
.card {
  margin: 0.5rem; /*1rem 1rem 1.5rem 1rem*/
}
.card.fullscreen {
  margin: 0.5rem 0 1rem;
}
.card h5,
.card h4,
.card h3,
.card h2 {
  margin: 0 0 5px;
}
.card-feedback {
  display: flex;
  justify-content: space-between;
  padding: 5px;
  margin: 0 20px;
  border-bottom: 1px solid #eee;
}
.card-feedback .card-users,
.card-feedback .card-share {
  display: flex;
  align-items: center;
}
.card-feedback span {
  margin-right: 15px;
}
.card-feedback .card-share span {
  margin-right: 0;
}
.card-feedback i {
  font-size: 2.2rem;
  margin-right: 5px;
}
.card-author {
  padding: 0 20px 1px;
}

/* Gallery Card */
.grid-item.gallery-item-card {
    background-color: #fff;
    border-radius: 2px;
    -webkit-box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.1);
    box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.1);
    margin: 0 6px 12px;
    width: calc(50% - 12px);
}
.gallery-item-header {
    padding: 10px 20px;
    position: relative;
}
.gallery-item-header img {
    position: absolute;
    top: 20px;
    left: 20px;
}
.gallery-item-header span {
    display: block;
    font-size: 14px;
}

/* Comments */
.comments {
  border-top: 1px solid #ccc;
  padding: 20px;
} 

/* Event */
.event-header {
  width: 100%;
  height: 100vh;
  position: relative;
}
.event-header .title {
  margin: 25px 0 0;
}
.event-header .event-category {
  border: 1px solid #fff;
  margin-top: 20px;
  display: inline-block;
  padding: 5px 15px;
  border-radius: 16px;
}
.event-header .bottom {
  bottom: 40px;
}

/* Newsletter */
.newsletter {
  margin-top: 25px;
}
.newsletter .btn {
  display: block;
}
.newsletter .input-field label {
  left: 0;
}
.newsletter .input-field input {
  text-align: center;
}

/* Progress Bar */
.progress {
  margin: 0;
}

/* tabs */
.side-nav .tabs {
  border-top: 1px solid #eee;
}
.tabs {
  background-color: transparent;
}
.tabs .tab a,
.tabs .tab a:hover {
    color: #01acc6;
    opacity: 0.6;
    font-family: 'Varela Round', sans-serif;
}
.tabs .tab a.active {
    color: #01acc6;
    opacity: 1;
}
.tabs .indicator {
    background-color: #01acc6;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    margin: 0 auto;
}

/* Chat */
.chat .message p {
    margin-bottom: 0;
    font-size: 14px;
}
.chat span {
    font-size: 12px;
}
.chat ul li {
    width: 100%;
    position: relative;
    display: inline-block;
    margin-bottom: 16px;
}
.chat ul li > img {
    float: left;
}
.chat ul li .message {
    margin-left: 55px;
    position: relative;
    padding: 12px 16px;
    border-radius: 4px;
}
.chat ul li .message.first {
    border-top-right-radius: 20px;
}
.chat ul li .message.last {
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
}
.chat ul li.message-left {
    margin-bottom: 36px;
}
.chat ul li.message-right .message.first {
    border-top-left-radius: 20px;
    border-top-right-radius: 4px;
}
.chat ul li.message-right > img {
    float: right;
    width: 45px;
    height: 45px;
    border-radius: 50%;
}
.chat ul li.message-right .message {
    margin-right: 55px;
    margin-left: 0;
    margin-bottom: 2px;
    background-color: #f1f1f1 !important;
}
.chat ul li.message-left > img {
    margin-right: 0;
    width: 45px;
    height: 45px;
    border-radius: 50%;
}
.chat ul li.message-left .message {
    background-color: #f0f8ff;
    margin-bottom: 2px;
}
.message-right > span,
.message-left > span {
    margin-bottom: 20px;
    display: block;
}
.message-left > span {
    margin-left: 55px;
}
.photo-add {
    margin-top: 8px;
}
.photo-add .square-user {
    height: 48px;
    width: 48px;
    margin-right: 4px;
    float: left;
}
.chat-day {
    display: block;
    text-align: center;
    text-transform: uppercase;
    margin-bottom: 30px;
}

/* ToDo */
.choose-date p {
    margin: 0;
    padding: 10px 0;
}
.choose-date p:first-child {
    padding-top: 0;
}
.choose-date p i {
    margin-right: 25px;
    position: relative;
    font-size: 26px;
    top: 3px;
}
.todo input[type="checkbox"]:checked + label {
    text-decoration: line-through;
    color: #9e9e9e;
}
.todo input[type="checkbox"] + label {
    color: inherit;
}
.todo .todo-element {
    position: relative;
    margin: 0;
    padding: 20px;
    border-top: 1px solid #eee;
}
.todo .todo-element:first-child {
  border-top: none;
}
.todo .todo-element:last-child {
    border-bottom: 1px solid #eee;
}
.todo .todo-element span {
    display: block;
    margin-left: 35px;
    font-size: 14px;
    color: #9e9e9e;
}
.todo .todo-element img {
    position: absolute;
    width: 25px;
    height: auto;
    border-radius: 50%;
    top: 20px;
    right: 20px;
}

/* Notification */
.notification {
    padding: 10px 17px;
    border-radius: 4px;
    position: relative;
    margin-bottom: 20px;
}
.notification p {
    margin-bottom: 0;
}
.notification span {
    font-size: 12px;
}
.close-notification {
    position: absolute;
    top: 2px;
    right: 12px;
}
.notification-success {
    color: #3c763d;
    background-color: #dff0d8;
    border-color: #d6e9c6;
}
.notification-info {
    color: #31708f;
    background-color: #d9edf7;
    border-color: #bce8f1;
}
.notification-warning {
    color: #8a6d3b;
    background-color: #fcf8e3;
    border-color: #faebcc;
}
.notification-danger {
    color: #a94442;
    background-color: #f2dede;
    border-color: #ebccd1;
}

/* Tweet */
.twitter {
    padding-bottom: 10px;
    border-bottom: 1px solid #eee;
}
.tweet {
    margin-bottom: 20px;
}
.tweet h3 {
    font-size: 12px;
    margin: 0 0 5px;
    opacity: 0.4;
    webkit-transition: all 0.3s;
    transition: all 0.3s;
}
.tweet h3:hover {
    opacity: 1;
}
.tweet p {
    font-size: 12px;
}
.tweet p a {
    font-size: 12px;
    display: inline;
    height: auto;
    line-height: normal;
    padding: 0;
}

/* Facebook */
.facebook {
    padding: 10px 0;
}
.face-notification {
    display: flex;
    align-items: flex-start;
    padding: 10px 0;
}
.face-notification img {
    margin-right: 10px;
    margin-top: 4px;
    width: 32px;
    height: 32px;
    color: #fff;
    border-radius: 50%;
    line-height: 48px;
    text-align: center;
}
.face-notification div {
    flex: 1;
    font-size: 12px;
}
.face-notification p {
    margin: 0;
    font-size: 14px;
    color: #444;
    font-family: 'Varela Round', sans-serif;
}
.face-notification div .small {
    display: block;
}

/* Product */
.product.half {
  width: 50%;
  padding: 10px;
  float: left;
}
.product-info {
  text-align: center;
  padding: 10px 20px;
}
.product-description {
  border-top: 1px solid #eee;
}
.product-variation {
  padding: 0 20px 20px;
}
.product-variation h5 {
  margin-bottom: 1rem;
}
.sizes .size {
    display: inline-block;
    text-transform: uppercase;
    padding: 8px 16px;
    border: 1px solid #ddd;
    border-radius: 2px;
    margin-right: 8px;
    margin-bottom: 8px;
}
.sizes .size:hover {
    border: 1px solid #01acc6;
    background-color: #01acc6;
    color: #fff;
}
.rating {
    margin: 0;
}
.rating i {
    opacity: 0.15;
    display: inline-block;
    font-size: 1.2rem;
}
.rating i.active {
    opacity: 0.9;
    color: #fdd835;
}

/* Checkout */
.checkout-header {
    box-shadow: none;
    border: none;
    border-top: 1px solid #ddd;
    margin: 20px 0 0;
    background-color: #fafafa;
}
.checkout-header .collapsible-header {
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 20px;
    background-color: #fafafa;
}
.checkout-header .checkout-price {
    font-size: 18px;
}
.checkout-header .collapsible-body {
    padding: 20px;
}
.checkout-header .collapsible-body .checkout-details {
    display: flex;
    align-items: flex-start;
    margin-bottom: 1em;
}
.checkout-image {
    width: 64px;
    margin: 0 10px 0 0;
    border-radius: 4px;
}
.checkout-product-title {
    flex: 1;
}
.checkout-product-title,
.checkout-product-title:last-child {
    margin-bottom: 0;
}
.checkout-product-title h6 {
    margin-bottom: 0;
    margin-top: 0;
    font-weight: 700;
    text-transform: uppercase;
}
.checkout-product-title h6 .right {
    font-weight: 400;
}
.checkout-header .input-field {
    display: flex;
}
.checkout-header .discount input {
    flex: 1;
}
.checkout-header .discount .btn {
    margin-left: 10px;
}
.discount {
    padding: 20px 0;
}
.subtotal {
    padding: 10px 0 15px;
    border-top: 1px solid #eee;
    border-bottom: 1px solid #eee;
}
.subtotal h6 {
    font-size: 16px;
}
.subtotal span {
    margin: 0;
    padding: 0;
    display: block;
}
.total {
    padding: 20px 0 0;
}
.total h4 {
  margin-bottom: 0;
}
.form-inputs {
    padding: 20px;
}
.form-inputs h4 {
    margin-bottom: 25px;
}
.shipping-address {
    padding-top: 20px;
    margin-top: 20px;
    border-top: 1px solid #eee;
}
.form-inputs .remember {
    margin: 20px 0;
}

/* Follow us */
.follow-us {
    opacity: 0.6;
    text-transform: uppercase;
    -webkit-transition: all 0.3s;
    transition: all 0.3s;
}
.follow-us i {
    font-size: inherit;
}
.follow-us:hover {
    opacity: 1;
}

/* Login & Signup */
.tool-login,
.tool-signup {
    position: absolute;
    top: 0;
    height: 180px !important;
}
.login-avatar,
.signup-avatar {
    border-radius: 50%;
    border: 4px solid;
    height: 140px;
    width: 140px;
    margin: 30px auto 0;
}
.login-avatar i {
    font-size: 80px;
    line-height: 140px;
    text-align: center;
    display: block;
}
.login-form,
.signup-form {
    padding: 20px;
    margin: 20px;
    border-radius: 2px;
    background-color: #fff;
    position: absolute;
    top: 56px;
    left: 0;
    right: 0;
    z-index: 99;
}
.login-form h1,
.signup-form h1 {
    margin-top: 0;
    margin-bottom: 30px;
    text-align: center;
    padding: 20px;
}
.login-form input,
.signup-form input {
  margin-bottom: 30px;
}

/* Lockscreen */
.clock h2 {
    font-size: 48px;
    font-weight: 100;
    padding-top: 120px;
    margin-bottom: 5px;
    color: #ffffff;
}
.clock span {
    color: #ffffff;
    opacity: 0.7;
}
.collection.notify {
    border: none;
    margin: 0;
    padding: 20px;
}
.collection.notify .collection-item {
    padding: 0;
    border-radius: 2px;
    margin-bottom: 5px;
}
.notify-header {
    padding: 10px 20px 10px 65px;
    position: relative;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1;
}
.notify-header img {
    position: absolute;
    top: 10px;
    left: 10px;
}
.notify-author span {
    display: block;
    font-size: 14px;
}
.notify-author span.truncate {
    margin: 7px 0 3px;
    opacity: 0.85;
}
.notify-author span.small {
    opacity: 0.5;
    text-align: right;
    margin-top: 10px;
    display: block;
}
.unlock {
    color: #fff;
    text-align: center;
    width: 50px;
    height: 50px;
    text-align: center;
    border-radius: 50%;
    line-height: 43px;
    margin: 0 auto;
    border: 2px solid transparent;
}
.unlock:hover {
    border: 2px solid #fff;
}

/* Chat */
.chat .message p {
    margin-bottom: 0;
    font-size: 14px;
}
.chat span {
    font-size: 12px;
}
.chat ul li {
    width: 100%;
    position: relative;
    display: inline-block;
    margin-bottom: 16px;
}
.chat ul li > img {
    float: left;
}
.chat ul li .message {
    margin-left: 55px;
    position: relative;
    padding: 12px 16px;
    border-radius: 4px;
}
.chat ul li .message.first {
    border-top-right-radius: 20px;
}
.chat ul li .message.last {
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
}
.chat ul li.message-left {
    margin-bottom: 36px;
}
.chat ul li.message-right .message.first {
    border-top-left-radius: 20px;
    border-top-right-radius: 4px;
}
.chat ul li.message-right > img {
    float: right;
    width: 45px;
    height: 45px;
    border-radius: 50%;
}
.chat ul li.message-right .message {
    margin-right: 55px;
    margin-left: 0;
    margin-bottom: 2px;
    background-color: #f1f1f1 !important;
}
.chat ul li.message-left > img {
    margin-right: 0;
    width: 45px;
    height: 45px;
    border-radius: 50%;
}
.chat ul li.message-left .message {
    background-color: #f0f8ff;
    margin-bottom: 2px;
}
.message-right > span,
.message-left > span {
    margin-bottom: 20px;
    display: block;
}
.message-left > span {
    margin-left: 55px;
}
.photo-add {
    margin-top: 8px;
}
.photo-add .square-user {
    height: 48px;
    width: 48px;
    margin-right: 4px;
    float: left;
}
.chat-day {
    display: block;
    text-align: center;
    text-transform: uppercase;
    margin-bottom: 30px;
}

/* Calendar */
.calendar table {
    border-collapse: collapse;
    border-spacing: 0;
}
.calendar td,
.calendar th {
    padding: 0;
}
.calendar {
    text-align: center;
    padding: 0 20px 20px;
}
.calendar thead {
    color: #fff;
    opacity: 0.9;
    border: none;
}
.calendar tbody {
    color: #fff;
}
.calendar tbody td:hover {
    background-color: rgba(255, 255, 255, .2);
}
.calendar td {
    border: 2px solid transparent;
    border-radius: 50%;
    display: inline-block;
    text-align: center;
    width: calc(13vw - 16px);
    height: calc(13vw - 16px);
    line-height: calc(13vw - 18px);
    margin: 5px;
}
.calendar .prev-month,
.calendar .next-month {
    opacity: 0.4;
}
.current-day {
    background: #fff;
}
.calendar tbody td.current-day:hover {
    background-color: rgba(255, 255, 255, 1);
}
.event {
    cursor: pointer;
    position: relative;
}
.event:after {
    background: #fff;
    border-radius: 50%;
    bottom: 3px;
    display: block;
    content: '';
    height: 4px;
    left: 50%;
    margin: 0px 0 0 -2px;
    position: absolute;
    width: 4px;
}
.event.current-day:after {
    background: #fff;
}
/* Activity */
.activity {
    margin: 0 20px;
    padding: 20px 0;
    border-bottom: 1px solid #eee;
    position: relative;
}
.activity p {
    margin: 0;
}
.activity-time span,
.activity-time i {
    vertical-align: middle;
    margin-right: 5px;
}
.activity-type {
    position: absolute;
    top: 0;
    right: 0;
    width: 35px;
    height: 35px;
    line-height: 35px;
    border-radius: 50%;
    text-align: center;
    background-color: #ccc;
    margin: 20px 0 0;
}
.activity-type.second-type {
    right: 50px;
}
.activity-type i {
    font-size: 24px;
    color: #fff;
}

/* Charts */
.card.chart {
  padding: 20px;
  margin: 20px;
}
.c-widget {
    display: flex;
    align-items: center;
}
.c-widget-figure {
    margin-right: 20px;
    width: 48px;
    height: 48px;
    color: #fff;
    border-radius: 50%;
    line-height: 48px;
    text-align: center;
}
.c-widget-body {
    flex: 1;
}
.legend {
    margin-bottom: 20px;
}
.legend h5.uppercase {
    margin-top: 0;
}
.legend p {
    margin-bottom: 0;
}
span.data-color {
    width: 15px;
    height: 15px;
    display: inline-block;
    border: 1px solid;
    margin-right: 7px;
    position: relative;
    top: 1px;
}

/* News */
.news .media-top-object {
  padding: 20px 20px 0;
  border-bottom: 1px solid #eee;
  margin: 1rem;
  background: #fff;
}
.news .media-top-object:last-child {
  border-bottom: none;
}
.news .media-body a {
  color: #222;
  font-weight: 400;
}
.news .news-title {
    font-size: 1.6rem;
    margin: 0 0 5px;
    line-height: 1.3;
}
.news .media-left {
  width: 33%;
  margin-right: 0;
}
.news .news-channel {
    font-size: 12px;
}
.news .news-category {
    float: right;
    font-size: 12px;
    border-bottom: 1px solid #9e9e9e;
}
.news-main {
    position: relative;
}
.top-news {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 20px;
    color: #fff;
}
.top-news-title a {
    font-size: 22px;
    color: #fff;
    margin-left: 20px;
    margin-right: 20px;
    display: block;
}
.top-news-channel {
    float: left;
    font-size: 12px;
    margin-left: 20px;
    color: #fff;
}
.top-news-category {
    float: right;
    font-size: 85%;
    border-bottom: 1px solid #fff;
    margin-right: 20px;
    color: #fff;
}
.news .card-feedback {
  margin: 0;
  padding: 10px 0 8px;
  border: none;
}
.news .card-feedback i {
  font-size: 1.5rem;
}

/* Shop */
.shop-banner {
    width: 50%;
    float: left;
    position: relative;
}
.shop-banner.full {
  width: 100%;
  float: left;
  position: relative;
}
.shop-banner h3 {
    text-transform: uppercase;
    margin-bottom: 0;
    font-weight: 700;
    font-size: 2.2rem;
}
.shop-banner p {
    text-transform: uppercase;
    margin-bottom: 0;
    font-weight: 300;
    font-size: 1.6rem;
}
.shop-banner .opacity-overlay {
  border: 1px solid #fff;
}

/* Modal */
.modal.features .row:last-child {
  margin-bottom: 0;
}
.modal.features .col {
  text-align: center;
}
.modal.features .col i {
  font-size: 3.2rem;
}
.modal.features .col p {
  font-size: 1.2rem;
  margin: 0;
}
