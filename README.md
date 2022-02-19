/*
Kirka.io Simple CSS
Made By: Exlipse_
 
Recommended Resolution: 1920x1080 FULLSCREEN
*/
 
/* Font */
@font-face {
font-family: gamefont;
src: url(https://raw.githubusercontent.com/Yadub/BoulderBox/master/fonts/Fontfabric---Mont-Heavy.otf);
}
 
* {
font-family: gamefont;
}
 
/* Animations */
@-webkit-keyframes glow {
from {
text-shadow: 0 0 5px #fff, 0 0 5px #ae50e4, 0 0 5px #ae50e4, 0 0 5px #ae50e4, 0 0 6px #ae50e4, 0 0 7px #ae50e4, 0 0 8px #ae50e4;
}
}
 
@keyframes animate {
from {
background-position: 0 0;
}
to {
background-position: 0 400px;
}
}
 
/*Background */
.bg-radial {
display: none;
}
 
.pattern-bg {
background: url(https://www.pixelstalk.net/wp-content/uploads/images4/1920x1080-Wood-Wallpaper-1080p.jpg) repeat !important;
animation: animate 10s linear infinite !important;
}
 
.interface .background{
background: linear-gradient(103.28deg, #000000 7.06%, #000000 90.75%) !important;
}
 
/* Ad Removal */
#ad-bottom, #ad-left{
visibility: hidden;
}
 
/* Stream */
.live-streams {
opacity: 0;
transition-duration: 0.5s;
}
 
.live-streams:hover {
opacity: 1;
}
 
/* Lobby */
.promo-link-btn {
display: none !important;
}
 
.interface .logo {
display: none;
}
 
.soc-group:nth-child(1) {
display: none;
}
 
.left-icons .icon-btn[style="--i:5;"] {
background: transparent !important;
border-top: transparent !important;
border-bottom: transparent !important;
}
 
#icon-store {
background: transparent !important;
border-top: transparent !important;
border-bottom: transparent !important;
box-shadow: none !important;
}
 
.left-icons .icon-btn:nth-child(1) {
background: transparent;
border-top: transparent;
border-bottom: transparent;
box-shadow: none;
}
 
.icon-btn:nth-child(3) {
background: transparent;
border-bottom: transparent;
border-top: transparent;
box-shadow: none;
}
 
.icon-btn:nth-child(4) {
background: transparent;
border-bottom: transparent;
border-top: transparent;
box-shadow: none;
}
/*
.left-icons .icon-btn[style="--i:5;"] svg, .left-icons .icon-btn[style="--i:5;"] .text-icon {
display: none;
}
 
.left-icons .icon-btn[style="--i:5;"] {
position: absolute;
width: 90px;
height: 25px;
top: 650px;
background: transparent !important;
border-top: transparent !important;
border-bottom: transparent !important;
}
 
.left-icons .icon-btn[style="--i:5;"]:after {
content: "Changelog";
}
*/
 
#icon-store:hover {
border-top: transparent;
}
 
.icon-btn:nth-child(1):hover {
border-top: transparent;
}
 
.icon-btn:nth-child(3):hover {
border-top: transparent;
}
 
.icon-btn:nth-child(4):hover {
border-top: transparent;
}
 
.right-icons .inventory-card {
-webkit-transform:translateX(-38px);
right: -96%;
margin-top: -40% !important;
transition: ease-in-out 0.4s;
}
 
.inventory-card:hover {
transform: translateX(-140px);
}
 
.right-icons .icon-btn {
display: block;
position: absolute;
right: -75%;
width: 100%;
opacity: 1;
transition: ease-in-out 0.4s;
}
 
.right-icons .icon-btn:hover {
transform: translateX(-100px);
}
 
.right-icons .svg-icon[data-v-b8de1e14] {
margin-left: -98%;
margin-bottom: -30%;
}
 
.right-icons .text-icon {
margin-right: -30%;
margin-top: 9%;
}
 
.play:before {
content: "WoodenTable is my daddy and hes hot af";
margin-right: 30px;
}
 
#app > div.interface.text-2 > div.play > button {
position: absolute;
top: 16px;
right: 111px;
background: #3b4975 !important;
border: 4px solid #26335b !important;
}
 
#app > div.interface.text-2 > div.play > button:hover {
background: #37477c !important;
color: white !important;
}
 
.moneys {
position: fixed;
left: 8% !important;
top: 58% !important;
}
 
.moneys .money[style="--i:3;"] {
background: transparent;
border-top: transparent;
border-bottom: transparent;
box-shadow: none;
}
 
.moneys .money[style="--i:2;"] {
background: transparent;
border-top: transparent;
border-bottom: transparent;
box-shadow: none;
}
 
/* Containers */
.background, .clans, .hub-container {
background: transparent !important;
}
 
.tabs {
background: transparent !important;
border-bottom: none !important;
box-shadow: none !important;
border-right: none !important;
}
 
.active-tab {
background: transparent !important;
border-right: none !important;
border-left: none !important;
}
 
.tab {
background: transparent !important;
border-left: none !important;
border-right: none !important;
}
 
.head-text {
background: transparent !important;
box-shadow: none !important;
}
 
.add-friends {
background: transparent !important;
}
 
.limit {
border-left: none !important;
}
 
.top-bar, .close, .home, .name-page {
display: none !important;
}
 
.container {
background: transparent !important;
backdrop-filter: blur(5px);
box-shadow: none !important;
}
 
.champions-list {
box-shadow: none !important;
}
 
.reset-time, .info-awards, .news {
background: transparent !important;
box-shadow: none !important;
}
 
.settings .input {
background: transparent !important;
border: none !important;
box-shadow: none !important;
}
 
/* Inventory */
.tab-bar {
background: transparent !important;
}
 
.subjects {
background: transparent !important;
border: none !important;
}
 
.subject {
background: transparent !important;
}
 
.inventory .avatar-head {
display: none;
}
 
.inventory .avatar {
background: transparent !important;
}
 
.gun {
background: transparent !important;
border: none !important;
}
 
.inventory .bottom {
background: transparent !important;
backdrop-filter: blur(2px) !important;
background-image: linear-gradient(to left, rgba(246, 255, 0, 0), #e2e04f1c) !important;
}
 
/* End Game Screen */
.end-modal {
background: url(https://media.discordapp.net/attachments/529192409305710602/902459779144900628/FcQshr.png?width=1168&height=657) !important;
}
 
.end-modal .content {
border-bottom: none !important;
}
 
/* HUD */
.mini-map-cont .name {
display: none;
}
 
.info-key-cont {
display: none;
}
 
.list-weapons {
display: none !important;
}
 
.hp {
margin-right: 20%;
}
 
.hp-title {
display: none !important;
}
 
.state {
margin-left: 36%;
}
 
.cont-endurance {
margin-left: 2%;
}
 
.mWwn {
display: none !important;
}
 
.weapons-cont {
margin-right: 46.5%;
margin-bottom: 3%;
}
 
.instruction {
display: none !important;
}
 
.kill-death {
position: fixed;
right: 1px;
bottom: 2%;
left: unset !important;
top: unset !important;
}
 
/* Change Container */
.change-container .gun-type{
padding: 10px;
}
 
.change-container .gun-type:hover {
border: .5px solid red;
box-shadow: 0 10px 15px rgba(236, 54, 54, .5);
}
 
/* Chat */
.chat {
margin-bottom: -4%;
}
 
/* Profile */
.auth-form {
background: transparent !important;
border-bottom: transparent !important;
border-top: transparent !important;
box-shadow: none !important;
}
 
.profile .avatar-info, .profile .level, .exp-values {
display: none;
}
 
.user-info {
visibility: hidden;
}
 
.progress-lvl {
visibility: visible;
width: 1370px;
margin-right: -810%;
margin-top: -10% !important;
}
 
.heads .levels {
color: red !important;
}
 
.heads .clan-tag {
-webkit-animation: glow 2s ease-in-out infinite alternate;
-moz-animation: glow 2s ease-in-out infinite alternate;
animation: glow 2s ease-in-out infinite alternate;
}
 
.card-profile {
background: transparent !important;
box-shadow: none !important;
}
 
.profile .k-d {
background: transparent !important;
box-shadow: none !important;
}
 
.profile .statistics {
background: transparent !important;
box-shadow: none !important;
}
 
/* Timer and Score */
.timer{
position: fixed;
right: 903px;
background: transparent !important;
box-shadow: none !important;
}
 
.team-score .label {
margin: 26.5px;
margin-left: 60px;
margin-right: 60px;
