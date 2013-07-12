grey_layout
Emote grey layout

<!DOCTYPE HTML>

My Blog
Logo
Home
|
Categories
|
Contact

Select a category.
Category1
Category2
Category3
Category4
Category5
Category6
Category7
Category8
Category9
Category10
Category11
Category12
Footer links here

Normalize: /*! normalize.css v1.1.0 | MIT License | git.io/normalize */

/* ========================================================================== HTML5 display definitions ========================================================================== */

/**

Correct block display not defined in IE 6/7/8/9 and Firefox 3. */
article, aside, details, figcaption, figure, footer, header, hgroup, main, nav, section, summary { display: block; }

/**

Correct inline-block display not defined in IE 6/7/8/9 and Firefox 3. */
audio, canvas, video { display: inline-block; *display: inline; *zoom: 1; }

/**

Prevent modern browsers from displaying audio without controls.
Remove excess height in iOS 5 devices. */
audio:not([controls]) { display: none; height: 0; }

/**

Address styling not present in IE 7/8/9, Firefox 3, and Safari 4.
Known issue: no IE 6 support. */
[hidden] { display: none; }

/* ========================================================================== Base ========================================================================== */

/**

1. Correct text resizing oddly in IE 6/7 when body font-size is set using
em units.
2. Prevent iOS text size adjust after orientation change, without disabling
user zoom. */
html { font-size: 100%; /* 1 / -webkit-text-size-adjust: 100%; / 2 / -ms-text-size-adjust: 100%; / 2 */ }

/**

Address font-family inconsistency between textarea and other form
elements. */
html, button, input, select, textarea { font-family: sans-serif; }

/**

Address margins handled incorrectly in IE 6/7. */
body { margin: 0; }

/* ========================================================================== Links ========================================================================== */

/**

Address outline inconsistency between Chrome and other browsers. */
a:focus { outline: thin dotted; }

/**

Improve readability when focused and also mouse hovered in all browsers. */
a:active, a:hover { outline: 0; }

/* ========================================================================== Typography ========================================================================== */

/**

Address font sizes and margins set differently in IE 6/7.
Address font sizes within section and article in Firefox 4+, Safari 5,
and Chrome. */
h1 { font-size: 2em; margin: 0.67em 0; }

h2 { font-size: 1.5em; margin: 0.83em 0; }

h3 { font-size: 1.17em; margin: 1em 0; }

h4 { font-size: 1em; margin: 1.33em 0; }

h5 { font-size: 0.83em; margin: 1.67em 0; }

h6 { font-size: 0.67em; margin: 2.33em 0; }

/**

Address styling not present in IE 7/8/9, Safari 5, and Chrome. */
abbr[title] { border-bottom: 1px dotted; }

/**

Address style set to bolder in Firefox 3+, Safari 4/5, and Chrome. */
b, strong { font-weight: bold; }

blockquote { margin: 1em 40px; }

/**

Address styling not present in Safari 5 and Chrome. */
dfn { font-style: italic; }

/**

Address differences between Firefox and other browsers.
Known issue: no IE 6/7 normalization. */
hr { -moz-box-sizing: content-box; box-sizing: content-box; height: 0; }

/**

Address styling not present in IE 6/7/8/9. */
mark { background: #ff0; color: #000; }

/**

Address margins set differently in IE 6/7. */
p, pre { margin: 1em 0; }

/**

Correct font family set oddly in IE 6, Safari 4/5, and Chrome. */
code, kbd, pre, samp { font-family: monospace, serif; _font-family: 'courier new', monospace; font-size: 1em; }

/**

Improve readability of pre-formatted text in all browsers. */
pre { white-space: pre; white-space: pre-wrap; word-wrap: break-word; }

/**

Address CSS quotes not supported in IE 6/7. */
q { quotes: none; }

/**

Address quotes property not supported in Safari 4. */
q:before, q:after { content: ''; content: none; }

/**

Address inconsistent and variable font size in all browsers. */
small { font-size: 80%; }

/**

Prevent sub and sup affecting line-height in all browsers. */
sub, sup { font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; }

sup { top: -0.5em; }

sub { bottom: -0.25em; }

/* ========================================================================== Lists ========================================================================== */

/**

Address margins set differently in IE 6/7. */
dl, menu, ol, ul { margin: 1em 0; }

dd { margin: 0 0 0 40px; }

/**

Address paddings set differently in IE 6/7. */
menu, ol{ padding: 0 0 0 40px; }

/**

Correct list images handled incorrectly in IE 7. */
nav ul, nav ol { list-style: none; list-style-image: none; }

/* ========================================================================== Embedded content ========================================================================== */

/**

1. Remove border when inside a element in IE 6/7/8/9 and Firefox 3.
2. Improve image quality when scaled in IE 7. */
img { border: 0; /* 1 / -ms-interpolation-mode: bicubic; / 2 */ }

/**

Correct overflow displayed oddly in IE 9. */
svg:not(:root) { overflow: hidden; }

/* ========================================================================== Figures ========================================================================== */

/**

Address margin not present in IE 6/7/8/9, Safari 5, and Opera 11. */
figure { margin: 0; }

/* ========================================================================== Forms ========================================================================== */

/**

Correct margin displayed oddly in IE 6/7. */
form { margin: 0; }

/**

Define consistent border, margin, and padding. */
fieldset { border: 1px solid #c0c0c0; margin: 0 2px; padding: 0.35em 0.625em 0.75em; }

/**

1. Correct color not being inherited in IE 6/7/8/9.
2. Correct text not wrapping in Firefox 3.
3. Correct alignment displayed oddly in IE 6/7. */
legend { border: 0; /* 1 / padding: 0; white-space: normal; / 2 / *margin-left: -7px; / 3 */ }

/**

1. Correct font size not being inherited in all browsers.
2. Address margins set differently in IE 6/7, Firefox 3+, Safari 5,
and Chrome.
3. Improve appearance and consistency in all browsers. */
button, input, select, textarea { font-size: 100%; /* 1 / margin: 0; / 2 / vertical-align: baseline; / 3 / *vertical-align: middle; / 3 */ }

/**

Address Firefox 3+ setting line-height on input using !important in
the UA stylesheet. */
button, input { line-height: normal; }

/**

Address inconsistent text-transform inheritance for button and select.
All other form control elements do not inherit text-transform values.
Correct button style inheritance in Chrome, Safari 5+, and IE 6+.
Correct select style inheritance in Firefox 4+ and Opera. */
button, select { text-transform: none; }

/**

1. Avoid the WebKit bug in Android 4.0.* where (2) destroys native audio
and video controls.
2. Correct inability to style clickable input types in iOS.
3. Improve usability and consistency of cursor style between image-type
input and others.
4. Remove inner spacing in IE 7 without affecting normal text inputs.
Known issue: inner spacing remains in IE 6. */
button, html input[type="button"], /* 1 / input[type="reset"], input[type="submit"] { -webkit-appearance: button; / 2 / cursor: pointer; / 3 / *overflow: visible; / 4 */ }

/**

Re-set default cursor for disabled elements. */
button[disabled], html input[disabled] { cursor: default; }

/**

1. Address box sizing set to content-box in IE 8/9.
2. Remove excess padding in IE 8/9.
3. Remove excess padding in IE 7.
Known issue: excess padding remains in IE 6. */
input[type="checkbox"], input[type="radio"] { box-sizing: border-box; /* 1 / padding: 0; / 2 / *height: 13px; / 3 / *width: 13px; / 3 */ }

/**

1. Address appearance set to searchfield in Safari 5 and Chrome.
2. Address box-sizing set to border-box in Safari 5 and Chrome
(include -moz to future-proof). */
input[type="search"] { -webkit-appearance: textfield; /* 1 / -moz-box-sizing: content-box; -webkit-box-sizing: content-box; / 2 */ box-sizing: content-box; }

/**

Remove inner padding and search cancel button in Safari 5 and Chrome
on OS X. */
input[type="search"]::-webkit-search-cancel-button, input[type="search"]::-webkit-search-decoration { -webkit-appearance: none; }

/**

Remove inner padding and border in Firefox 3+. */
button::-moz-focus-inner, input::-moz-focus-inner { border: 0; padding: 0; }

/**

1. Remove default vertical scrollbar in IE 6/7/8/9.
2. Improve readability and alignment in all browsers. */
textarea { overflow: auto; /* 1 / vertical-align: top; / 2 */ }

/* ========================================================================== Tables ========================================================================== */

/**

Remove most spacing between table cells. */
table { border-collapse: collapse; border-spacing: 0; }

My Custom CSS: @charset "utf-8"; /* CSS Document / /*Main CSS/ body {

color: #000000 /*{d-body-color}*/;
text-shadow: 0 /*{d-body-shadow-x}*/ 1px /*{d-body-shadow-y}*/ 0 /*{d-body-shadow-radius}*/ #eeeeee /*{d-body-shadow-color}*/;
background: #ffffff /*{d-body-background-color}*/;
background-image: -webkit-gradient(linear, left top, left bottom, from( #FFFFFF /*{d-body-background-start}*/), to( #e5e5e5 /*{d-body-background-end}*/)); /* Saf4+, Chrome */
background-image: -webkit-linear-gradient( #FFFFFF /*{d-body-background-start}*/, #e5e5e5 /*{d-body-background-end}*/); /* Chrome 10+, Saf5.1+ */
background-image:    -moz-linear-gradient( #FFFFFF /*{d-body-background-start}*/, #e5e5e5 /*{d-body-background-end}*/); /* FF3.6 */
background-image:     -ms-linear-gradient( #FFFFFF /*{d-body-background-start}*/, #e5e5e5 /*{d-body-background-end}*/); /* IE10 */
background-image:      -o-linear-gradient( #FFFFFF /*{d-body-background-start}*/, #e5e5e5 /*{d-body-background-end}*/); /* Opera 11.10+ */
background-image:         linear-gradient( #FFFFFF /*{d-body-background-start}*/, #e5e5e5 /*{d-body-background-end}*/);
} .container { margin-left:auto; margin-right:auto; width: 80%; max-width: 81.5em; }

header_main
{
width: 100%;
background: #0fb4e7; /* Old browsers / background: -moz-linear-gradient(top, #0fb4e7 0%, #39bde5 50%, #0fb4e7 100%); / FF3.6+ / background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#0fb4e7), color-stop(50%,#39bde5), color-stop(100%,#0fb4e7)); / Chrome,Safari4+ / background: -webkit-linear-gradient(top, #0fb4e7 0%,#39bde5 50%,#0fb4e7 100%); / Chrome10+,Safari5.1+ / background: -o-linear-gradient(top, #0fb4e7 0%,#39bde5 50%,#0fb4e7 100%); / Opera 11.10+ / background: -ms-linear-gradient(top, #0fb4e7 0%,#39bde5 50%,#0fb4e7 100%); / IE10+ / background: linear-gradient(to bottom, #0fb4e7 0%,#39bde5 50%,#0fb4e7 100%); / W3C / filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#0fb4e7', endColorstr='#0fb4e7',GradientType=0 ); / IE6-9 */ box-shadow: 2px 3px 2px #808080;

} .border { border-bottom:1px solid #c9de96; } nav { float:right; } nav a { display:block; text-decoration:none; color:#ffffff; padding:10px 20px; } nav a:hover { /*background-color:#009ec3; display:block; text-decoration:none;*/ color:#222222; text-shadow:none; } nav li { display:block;

float:left;
} .separator { color:#0079C4; padding-top: 10px; } } section { margin-left:1.041666666666667%; margin-right:1.041666666666667%; float:left; width:72.708333333333%; margin-top:1.5%; padding-bottom:5px; } .categories { display:block; width:100%; } .categories li { list-style:none; position:relative; margin-top: 3%; min-height: 10em; margin-right: 3%; float: left; border: 1px solid #c0c0c0; padding: 5px 0; text-align: center; width: 14em; -webkit-border-radius: 8px; -moz-border-radius: 8px; border-radius: 5px; -webkit-box-shadow: #808080 2px 2px 2px; -moz-box-shadow: #808080 2px 2px 3px; box-shadow: #808080 2px 2px 3px;
}
li.hover { -moz-transform: scale(1) rotate(10deg) translateX(px) translateY(px) skewX(deg) skewY(deg); -webkit-transform: scale(1) rotate(10deg) translateX(px) translateY(px) skewX(deg) skewY(deg); -o-transform: scale(1) rotate(10deg) translateX(px) translateY(px) skewX(deg) skewY(deg); -ms-transform: scale(1) rotate(10deg) translateX(px) translateY(px) skewX(deg) skewY(deg); transform: scale(1) rotate(10deg) translateX(px) translateY(px) skewX(deg) skewY(deg); } .categories ul { padding: 0 0 0 0 !important; } .category_slide { display:none; margin-top: 1.428571428571429%; height: 4.5em; margin-right: 1.428571428571429%; float: left; border: 1px solid #19546E; padding: 5px 0; text-align: center; width: 12em; -webkit-border-radius: 8px; -moz-border-radius: 8px; border-radius: 8px; -webkit-box-shadow: #666 2px 2px 3px; -moz-box-shadow: #666 2px 2px 3px; box-shadow: #666 2px 2px 3px;
background: #7c9dad; background: -webkit-gradient(linear, 0 0, 0 bottom, from(#7c9dad), to(#ffffff)); background: -webkit-linear-gradient(#7c9dad, #ffffff); background: -moz-linear-gradient(#7c9dad, #ffffff); background: -ms-linear-gradient(#7c9dad, #ffffff); background: -o-linear-gradient(#7c9dad, #ffffff); background: linear-gradient(#7c9dad, #ffffff); -pie-background: linear-gradient(#7c9dad, #ffffff); behavior: url(/PIE.htc); }

aside { margin-left:1.041666666666667%; margin-right:1.041666666666667%; float:right; width: 22.708333333333%; margin-top:1%; } footer { margin-left:1.041666666666667%; margin-right:1.041666666666667%; margin-top: 10px; clear:both; width: 97.91666666666667; border-top: 1px solid #c9de96; }

/*CSS media queries*/ @media screen and (max-width: 480px) { nav { float:left; width:100%; } nav ul li { margin-top: 3%; width:100%; margin-left:0px; } nav ul { padding: 0 0 0 0; } h1 { font-size:1.25em !important; } .categories ul { padding: 0px !important; } .categories li { display:block; width:100% border:1px solid #ccc; border-radius: 5px; } aside { float:left; width:100%; } }
