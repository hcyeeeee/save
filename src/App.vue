<template>
    <div>
        <Header />
        <COntentBanner />
        <AdditionBox />
        <ContentProcess />
        <ContentTime />
        <ContentNews />
        <ContentDistrict />
        <ContentVideo />
        <Footer />
        <!-- <AdditionSide /> -->
        <!-- <AdditionScrolltop /> -->
        <!-- <AdditionBottom /> -->
        <Share />
        <ContentProfile />
    </div>
</template>

<script>
import Header from '@/components/Header.vue'
import COntentBanner from '@/components/Content_banner.vue'
import AdditionBox from '@/components/Addition_box.vue'
import ContentProcess from '@/components/Content_process.vue'
import ContentTime from '@/components/Content_time.vue'
import ContentVideo from '@/components/Content_video.vue'
import ContentNews from '@/components/Content_news.vue'
import ContentDistrict from '@/components/Content_district.vue'
import Footer from '@/components/Footer.vue'
// import AdditionSide from '@/components/Addition_side.vue'
// import AdditionScrolltop from './components/Addition_scrolltop.vue'
import Share from './components/share.vue'
// import AdditionBottom from './components/Addition_bottom.vue'
import ContentProfile from './components/Content_profile.vue'
export default {
    name: 'App',
    components: {
        Header,
        COntentBanner,
        AdditionBox,
        ContentProcess,
        ContentTime,
        ContentNews,
        ContentDistrict,
        ContentVideo,
        Footer,
        // AdditionSide,
        // AdditionScrolltop,
        Share,
        ContentProfile
    },
}
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Noto+Sans+TC:wght@100;300&display=swap");
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@500;600;700&display=swap');


/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i {
    font-family: 'Noto Sans TC';
}

center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
    display: block;
}

body {
    line-height: 1;
}

ol,
ul {
    list-style: none;
}

blockquote,
q {
    quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
    content: '';
    content: none;
}

table {
    border-collapse: collapse;
    border-spacing: 0;
}
</style>

<style>
/* ???????????? */
* {
    scroll-behavior: smooth;
    font-family: 'Noto Sans TC'
}

body {
    margin: 0;
    width: 100%;
    overflow-x: hidden;
    background-color: #F3FFF5;
    font-family: 'Noto Sans TC'
}

#app {
    font-family: 'Noto Sans TC', sans-serif, '???????????????', '???????????????', Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #595757;
    transition: 0.3s;
    width: 100%;
    overflow-x: hidden;
}

h1,
h2 {
    font-family: 'Noto Sans TC';
    font-size: 1.8rem;
}

h3 {
    font-family: 'Noto Sans TC';
    text-align: center;
    font-size: 1.6rem;
    font-weight: bolder;
    padding: 0.6rem 0;
    margin: 2rem 0 0.1rem 0;
    color: rgb(59, 59, 59);

}

h4 {
    font-family: 'Noto Sans TC';
    font-size: 1.3rem;
}

ul li {
    font-family: 'Noto Sans TC';
    text-align: left;
    margin: 1rem 0 1rem 0;
    font-size: 1.2rem;
    line-height: 1.4rem;
}

p {
    font-family: 'Noto Sans TC';
    text-align: left;
    margin: 0.5rem 0 2rem 0;
    line-height: 1.4rem;
    font-size: 1.3rem;
}

@media screen and (max-width: 768px) {

    p,
    ul li {
        font-size: 1rem;
    }
}

a {
    font-family: 'Noto Sans TC';
    color: #595757;
    text-decoration: none !important;
}

a:hover {
    font-family: 'Noto Sans TC';
    color: black;
}

figure {
    font-family: 'Noto Sans TC';
    margin: 0;
}

.layout {
    font-family: 'Noto Sans TC';
    max-width: 1000px;
}

.section {
    font-family: 'Noto Sans TC';
    margin: 2rem auto;
    max-width: 1000px;

}

.section-box {
    font-family: 'Noto Sans TC';
    margin: 1rem auto;
    padding: 1rem;
}

@media screen and (max-width: 768px) {
    .section {
        margin: 3rem auto;
        padding: 0 1rem;
        width: 100%;
    }
}

.flex {
    display: flex;
}

@media screen and (max-width: 350px) {
    .flex {
        display: block;
    }
}

.name {
    text-align: center;
    font-weight: bolder;
    font-size: 1.6rem;
    margin: 1rem 0;
    line-height: 2rem;
}

.section-box p:nth-child(1) {
    margin-left: 0;
}

/* Tabs style */
.nav-tabs .nav-link.active {
    background-color: #A5D35E !important;
    color: rgb(45, 44, 44);
}

.nav-item {
    color: rgb(32, 32, 32);
    border-bottom: 3px solid #A5D35E;
    margin: .5rem;
}

/* ????????????????????? */
.fa.fa-circle-o {
    font-weight: lighter !important;
    color: #494949;
}

.fa-stack-1x {
    color: red;
    font-weight: bolder;
}

hr {
    color: inherit;
    border: 0;
    border-top: 2px solid;
    opacity: .9;

}

.nav-tabs {
    --bs-nav-tabs-border-color: transparent;
}
</style>
