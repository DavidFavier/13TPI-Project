
body {
	font-family: 'helvetica', 'sans-serif';
	margin: 0;
}

/* All global style rules */
h1, h2, h3, h4, h5 {
	line-height: 1.5;
	font-weight: 300;
	margin: 0.5em 0;
}

h1 {
	font-size: 2.5em;
}
h2 {
	font-size: 2em;
}

h3 {
	font-size: 1.6em;
}

h4 {
	font-size: 1.4em;
}

h5 {
	font-size: 1.2em;
}

a {
	text-decoration: none;
}

p,label, strong {
	line-height: 2;
	font-size: 0.85em;
	font-weight: 300;
}

.flex {
	display: flex;
	max-width: 1200px;
	margin: 0 auto;
	padding: 0 15px;
	justify-content: space-between;
}

.badge {
	padding: 9px 20px;
	color: #EEEEEE;
	display: inline-block;
	text-transform: uppercase;
	font-weight: 600;
	text-align: center;
	font-size: 0.75em;
}

.badge.Rift.GG {
	background-color: #FF205F;
}

.badge.Datagraphs {
	background-color: #4EAE60;
}

.badge.RS.Com {
	background-color: #694EAE;
}

.badge.rpg,
.badge.adventure {
	background-color: #40ABF5;
}


.shade {
	position: absolute;
	z-index: 1;
	width: 100%;
	height: 100%;
	top: 0;
	left: 0;
	background: rgba(0, 0, 0, 0.7);
}

/* End all the global styling */

/* Create style for header */
header {
	background-color: #131313;
	padding: 20px 0;
	position: relative;
	border-bottom: 1px solid #FFB320;
}

.hamburger-menu {
	background-color: transparent;
	border: 1px solid #FFB320;
	padding: 3px 5px;
	width: 10px;
	cursor: pointer;
	display: none;
}

.hamburger-menu .strip {
	display: block;
	height: 1px;
	background-color: #FFB320;
	marging: 4px 0;
}

nav ul {
	list-style-type: none;
	padding: 0;
	marging: 10px 0 0;
}
nav ul li {
	display: inline-block;
	font-size: 1em;
	marging: 0 10px;
}

nav ul li a {
	color: #EEEEEE;
	font-weight: 600;
}
nav ul li a:hover {
	color: #FFB320;
}

#login-register-buttton {
	background-color: #6C01BC;
	color: #131313;
	border-radius: 20px;
	padding: 10px 15px;
	font-size: 0.85em;
	font-weight: 600;
}
/* End style for header */

/* Start champion styling */
#champion-image {
	background: url() top center no-repeat;
	height: 820px;
}

.champion-marketing-text {
	max-width: 1200px;
	margin: -30px auto 0;
	position: absolute;
	top: 40%;
	left: 0;
	right: 0;
	padding: 0 20px;
}

.champion-marketing-text h1 {
	color: #EEEEEE;
	font-size: 3.5em;
	font-weight: 300;
	margin: 0.5em 0;
}

.champion-marketing-text span {
	color: #FFB320;
}

.champion-marketing-text h5 {
	color: #EEEEEE;
	font-size: 0.85em;
	font-weight: 500px;
	lime-height: 2;
	margin-bottom: 2.5em;
}

.champion-marketing-text button {
	background-color: #FFB320;
	color: #131313;
	border-radius: 25px;
	padding: 15px 25px;
	font-size: 0.85em;
	font-weight: 600;
	border: none;
	cursor: pointer;
}
/* End champion styling */

/* start latest news style */
#latest-news {
	margin-bottom: 75px;
}

#latest-news .flex {
	justify-content: flex-start;
	max-width: 100%;
	padding: 0;
}

#latest-news .flex h5 {
	flex-basis: 25%;
	background-color: #FFB320;
	padding: 25px;
	margin: 0;
	text-align: right;
	color: #EEEEEE;
	font-size: 1.2em;
}

#latest-news-container {
	background-color: #131313;
	position: relative;
	flex-basis: 75%;
	padding: 25px;
}

#latest-news-container.badge {
	margin-right: 20px;
}

#latest-news-container .latest-news-text {
	color: #EEEEEE;
}

/* End latest news style */

/* start: game type styles */
#game-types-boxes {
	margin-bottom: 75px;
}

#latest-types-boxes .box {
	flex-basis: 25%;
	position: relative;
	height: 300px;
}
#game-types-boxes .box.Summoners-Rift {
	background: url("") top center no-repeat;
	background-size: cover;
}

#game-types-boxes .box.ARAM {
	background: url("") top center no-repeat;
	background-size: cover;
}

#game-types-boxes .box.TfT {
	background: url("") top center no-repeat;
	background-size: cover;
}

#game-types-boxes .box .badge {
	position: relative;
	z-index: 2;
	top: 20px;
	left: 20px;
}

#game-types-boxes .box .contents {
	position: absolute;
	z-index: 2;
	bottom: 20px;
	left: 0;
	color: #EEEEEE;
	padding: 0 35px 0 25px;
}

#game-types-boxes .box .contents a {
	font-size: 0.8em;
	font-weight: 300;
	color: #999999;
}
/* end: game type styles */

/* start recent games styles */
#recent-games {
	background: url("") top center no-repeat;
	background-color: #EEF2F6;
	border-top: 1px solid #d6dee7;
	padding: 70px 0 120px;
}

#recent-games h1 {
	text-align: center;
}

#recent-games .box {
	position: relative;
	flex-basis: 31%;
	background-color: #FFFFFF;
}

#recent-games .box .badge {
	position: absolute;
	top: 20px;
	left: 20px;
	z-index: 2;
}

#recent-games .box img {
	width: 100%;
}

#recent-games .box .box-lower-section {
	padding: 20px;
}

#recent-games .box .box-lower-section p {
	color: #999999;
}

#recent-games .box .box-lower-section a {
	color: #999999;
	font-size: 0.8em;
}
/* end recent games styles */

/* start tournament styles */
#tournaments {
	background: url("") 0 0 repeat;
	padding: 125px 0 105px;
}

#tournaments .flex {
	position: relative;
}

#tournaments .badge {
	position: absolute;
	top: 0;
	left: 0;
	z-index: 2;
}

#tournaments .badge.tournaments {
	top: -32px;
	left: 15px;
}

#tournaments .box {
	background-color: #252525;
	padding: 70px 20px 40px;
	flex-basis: 45%;
	position: relative;
}

#tournaments .box .tournaments-image {
	float: left;
	width: 30%;
}

#tournaments .box .tournaments-image img {
	width: 100%;
}
#tournaments .box .tournaments-content {
	flaot: left;
	margin-left: 25px;
	width: 60%;
}

#tournaments .box .tournaments-content h3 {
	color: #FFB320;
	margin-top: 0;
}

#tournaments .box .tournaments-content label {
	color: #999999;
	font-size: 0.75em;
}

#tournaments .box .tournaments-content label.prizes {
	color: #FFB320;
	display: inline-block;
	margin-top: 12px;
}

#tournament .box .tournaments-content strong {
	color: #EEEEEE;
	font-size: 0.75em;
}
/* end tournament styles */

/* start posts/comments styles */
#posts-comments {
	background: url("") 0 0 repeat;
	padding: 75px 0;
}

#posts-comments .game-warrior {
	flex-basis: 32%;
	position: relative;
}

#posts-comments .game-warrior p {
	color: #EEEEEE;
	font-weight: 600;
}
#posts-comments .game-warrior img {
	margin-bottom: 0.5em;
}
#posts-comments .game-warrior img.footer-graphic {
	position: absolute;
	margin-bottom: 0;
	width: 115%;
}
#posts-comment .posts-comment-box {
	flex-basis: 28%;
	background-color: #252525;
	padding: 20px 20px 25px;
	border: 1px solid #4a4a4a;
}

#posts-comment .posts-comment-box-h3 {
	color: #EEEEEE;
}

.post-item {
	margin-top: 25px;
}

.post-item:first-child {
	margin-top: 0;
}

.post-item:after {
	content: "";
	display: table;
	clear: both;
}

.post-item img {
	float: left;
	width: 30%;
}

.post-item > div {
	float: left;
	margin-left: 5%;
	width: 65%
}

.post-item > div h5 {
	color: #FFB320;
	font-size: 0.8em;
	margin-top: 0;
}

.post-item > div p {
	color: #EEEEEE;
	margin: 5px 0;
	font-size: 0.8em;
}

.post-item > div small {
	color: #999999;
	font-size: 0.75em;
}

.comments-item {
	margin-top: 1em;
}

.comments-item:first-child {
	margin-top: 0;
}

.comments-item:after {
	content: "";
	display: table;
	clear: both;
}

.comments-items img {
	width: 23%;
	height: auto;
	border-radius: 50%;
	float: left;
}

.comments-items > div {
	float: left;
	margin-left: 7%;
	width: 70%;
}

.comment-items > div p {
	color: #EEEEEE;
	font-size: 0.8em;
	margin: 0 0 5px;
}

.comment-items > div p span {
	color: #999999;
}

.comment-items > div p span.author {
	color: #E92159; 
}

.comment-item > div h5 {
	color: #FFB320;
	font-size: 0.8em;
	margin-top: 0;
}
/* end posts/comments styles */

/* start footer styles */
footer {
	background-color: #252525;
	padding: 25px 0 20px;
}

footer small {
	color: #DDDDDD;
	font-size: 0.9em;
}

footer small .footer-heart {
	font-size: 16px;
}

footer small a {
	color: #007BDC;
}

footer ul {
	list-style-type: none;
	margin: 0;
}

footer ul li {
	display: inline-block;
	margin: 0 12px;
}

footer ul li a {
	color: #DDDDDD;
	font-size: 0.8em;
}
/* end footer styles */
