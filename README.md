@import url(https://bdsources.github.io/sourcecheck/code.css);
@import url(https://tropix126.github.io/BetterDiscordStuff/friendgrid/v3/css/base.css);
@import url(https://discord-custom-covers.github.io/usrbg/snippets/userPopouts.css);
@import url(https://rsms.me/inter/inter.css);
@import url(https://fonts.googleapis.com/icon?family=Material+Icons);
@import url(https://monstrousdev.github.io/themes/addons/user-tags.css);

@font-face {
  font-family: 'Segoe UI Emoji';
  src: local('Segoe UI Emoji'), local('SegoeUIEmoji'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUIEmoji.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUIEmoji.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI Symbol';
  src: local('Segoe UI Symbol'), local('SegoeUISymbol'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUISymbol.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUISymbol.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe MDL2 Assets';
  src: local('Segoe MDL2 Assets'), local('SegoeMDL2Assets'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeMDL2Assets.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeMDL2Assets.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}


@font-face {
  font-family: 'Segoe UI';
  src: local('Segoe UI'), local('SegoeUI'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUI.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUI.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: local('Segoe UI Italic'), local('SegoeUI-Italic'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUI-Italic.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUI-Italic.woff2') format('woff2');
  font-weight: normal;
  font-style: italic;
}

@font-face {
  font-family: 'Segoe UI';
  src: local('Segoe UI Bold Italic'), local('SegoeUI-BoldItalic'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUI-BoldItalic.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUI-BoldItalic.woff2') format('woff2');
  font-weight: bold;
  font-style: italic;
}

@font-face {
  font-family: 'Segoe UI';
  src: local('Segoe UI Bold'), local('SegoeUI-Bold'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUI-Bold.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUI-Bold.woff2') format('woff2');
  font-weight: bold;
  font-style: normal;
}

  @font-face {
  font-family: 'Segoe UI';
  src: local('Segoe UI Semibold'), local('SegoeUI-Semibold'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUI-Semibold.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUI-Semibold.woff2') format('woff2');
  font-weight: 600;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: local('Segoe UI Semibold Italic'), local('SegoeUI-SemiboldItalic'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUI-SemiboldItalic.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUI-SemiboldItalic.woff2') format('woff2');
  font-weight: 600;
  font-style: italic;
}

@font-face {
  font-family: 'Segoe UI';
  src: local('Segoe UI Light'), local('SegoeUI-Light'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUI-Light.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUI-Light.woff2') format('woff2');
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: local('Segoe UI Light Italic'), local('SegoeUI-LightItalic'),
    url('https://intrnl.github.io/fluentdiscord/src/assets/fonts/SegoeUI-LightItalic.woff2') format('woff2'),
    url('https://cdn.staticaly.com/gh/intrnl/fluentdiscord/master/assets/fonts/SegoeUI-LightItalic.woff2') format('woff2');
  font-weight: 300;
  font-style: italic;
}

html, span:not([class*="spinner-"]):not([class*="spinnerItem"]) {backface-visibility: hidden;}

@keyframes loaderFade{0%{opacity:0;pointer-events:all}10%{opacity:1;pointer-events:all}90%{opacity:1;pointer-events:all}100%{opacity:0;pointer-events:none;display:none}}@keyframes loader{0%{transform:translate(-50%,-50%) scaleX(0);transform-origin:left center}100%{transform:translate(-50%);transform-origin:left center}}.full-motion body::before{content:'Loading /midnight/css/base.css';top:50%;left:50%;width:250px;height:4px;position:fixed;z-index:3000;transform:translate(-50%,-50%);box-shadow:inset 0 0 0 100vmax rgba(255,255,255,.14),inset 0 0 0 100vmax var(--lv1),0 0 0 100vmax rgba(255,255,255,.05),0 0 0 100vmax var(--lv1);color:#fff;text-align:center;line-height:50px;font-size:var(--size1);animation:loaderFade 1.5s linear forwards;opacity:0;pointer-events:none}.full-motion body::after{content:'';top:50%;left:50%;width:250px;height:4px;position:fixed;z-index:3000;transform:translate(-50%,-50%);box-shadow:0 0 24px 2px var(--accent);transform-origin:left center;background:var(--accent);animation:loader 1.5s linear,loaderFade 1.5s linear forwards;opacity:0;pointer-events:none}
/*

TABLE OF CONTENTS

1. Global Attributes
    1.a. Master Variables
    1.b. Fonts and Text Scaling + Coloration
	1.c. Selection & Links
	1.d. Scrollbars
	1.e. Tooltips
	1.f. Global Keyframes
	1.g. Spinners
	1.h. Unsupported Settings

2. Titlebar
    2.a. Windows Titlebar and Buttons
    2.b. OSX Titlebar and Buttons
    2.c. Wordmark
    
3. Header
    3.a. Outer Toolbar
    3.b. Toolbar Icons
	3.c. Message Search
	3.d. Tab Bar
	3.e. Call and DM Animation
	3.f. Avatar Positioning
	
4. Guilds
	4.a. General Wrapper
	4.b. Home Icon
	4.c. Icons
	4.d. Folders
	4.e. BetterDiscord Public Servers Button
	4.f. Badges and Indicators

5. Channels Sidebar
	5.a. Outer Sidebar Containers
	5.b. Channel Guild Header
		5.b.a Server Banners
	5.c. Account Details Container
	5.d. Guild Text Channels
	5.e. Guild Voice Channels
	5.f. Guild Channel Categories
	5.g. Call and Other Related Containers
  5.h. Unread Bars
  5.i. Powercord Spotify Container

6. Members List Sidebar
	6.a. Outer Sidebar
	6.b. Member Entries
	6.c. Member Dividers
	6.d. Loading Animations

7. Private Channels Sidebar
	7.a. Outer Sidebar
	7.b. Top Entry Tabs
	7.c. Channel Entries
	7.d. Search Bubble

8. Chat
	8.a. Outer Chat & Background System
	8.b. Messages
	8.c. Attachments
	8.d. Embeds, Invites and Gifts
	8.e. Dividers
	8.f. Textarea
	8.g. Codeblocks and Block-Quotes
	8.h. Reactions
	8.i. Side Buttons
	8.j. Typing and Slowmode
	8.k. New Messages Bar
	8.l. Mentions and Channel Links
	8.m. Spoilers
	8.n. Blocked Messages
	8.o. System Messages
	8.p. Search Results
	8.q. Call and Video
	8.r. NSFW Warning

9. Popouts
	9.a. Context Menus
	9.b. User Popouts
	9.c. Status Picker & Server Dropdown
	9.d. Selection Dropdowns
	9.e. Emoji Picker
	9.f. Autocomplete
	9.g. Gif Picker
	9.h. Toasts
	9.i. Message Popouts
	9.j. RTC Connection/Noise Reduction
	9.k. Call Region Selector
	9.l. Mention Confirmation Popout
	9.m. Role Selector
	9.n. Color Picker
	9.o. Roles Overflow
	9.p. Member Search
	9.q. Incoming Calls
	9.r. Notices
	9.s. Search Helper

10. Modals
	10.a. Replace Backdrop
	10.b. Global Modals
	10.c. User Profile Modals
	10.d. Expanded Image Modal
	10.e. Keyboard Shortcuts Modal
	10.f. Guild Invite Modal
	10.g. Upload Modal

11. Pages
	11.a. Loading Screen
	11.b. Login Screen
	11.c. Server Discovery
	11.d. Friends List
	11.e. Store
	11.f. Library
	11.g. Nitro Advertising Tab

12. Controls and Common Elements
	12.a. Checkboxes & Radios
	12.b. Radios
	12.c. Sliders
	12.d. Switches
	12.e. Buttons
	12.f. Role Entries
	12.g. Bot Tags
	12.h. Inputs
	12.i. Cards

13. Outer Settings Layers

14. Settings Sidebar
	13.a. Outer Sidebar
	13.b. Sidebar Content

15. User Settings Content
	15.a. Content Column Layout
	15.b. Common Elements
	15.c. Close Button

16. Guild Settings Content

17. General Avatars	
	17.a. Roundness and Mask
	17.b. Status

18. Plugins
	18.a. ThemeRepo and PluginRepo
	18.b. TopRoleEverywhere
	18.c. GoogleTranslateOption
	18.d. ReadAllNotification

19. BetterDiscord
	19.a. Theme and Plugin Entries

20. Reduced Motion

*/


/*Begin Source Code*/

/*1. Global Attributes*/

/*1.a. Master Variables*/

:root {
	/*Primary*/
	--lv1: #00000f;
	--accent: #1973d3;
	--hover: #135193;
	--bg: url('https://i.imgur.com/GdnbuVj.jpg');
	--tooltip-color:#f6f6f7;
	--bg-opacity: 0.25;
	--bg-fade: 80%;

	/*Support for other themes*/
	--mc: var(--accent);
	--hc: var(--hover);
	--main-color: var(--accent);
	--hover-color: var(--hover);
	--roundness: var(--user-roundness);
	--lvl-bg-opacity:var(--bg-opacity);
	--lvl-bg-fade:var(--bg-fade);	
	--online:var(--success);
	--idle:var(--caution);
	--dnd:var(--danger);
	--offline:var(--unavailable);
	--invisible:var(--invisible);
	--streaming:var(--twitch-purple);

	/*Branding*/
	--theme-name: 'Midnight UI';
	--theme-version: '3.2.2';

	/*Discord Vars*/
	--deprecated-store-bg: var(--lv1);	
	--background-primary: var(--lv1);
	--background-secondary: var(--lv1);
	--background-secondary-alt:var(--lv1);
	--background-tertiary: var(--lv1);
	--channeltextarea-background:var(--lv1);
	--background-modifier-active:transparent;

	/*Status*/
	--success: #11d85d;
	--caution: #ffd104;
	--danger: #e20b0b;
	--unavailable: #636b75;	
	--invisible: #747f8d;
	--information:#4a90e2;
	--twitch-purple: #9146FF;
	--spotify-green:#1DB954;
	--xbox-green:#0e7a0d;
	--netflix-red:#e50914;

	/*Roundness*/
	--user-roundness:0;
	--guilds-roundness:0;

	/*Fonts*/
	--sizelg:1.25rem;
	--size0: 1.15rem;
	--size1: .925rem;
	--size2: .8rem;
	--size3: .75rem;
	--size4: .7rem;
	--size5: .5rem;
	--size6: .35rem;
	--font: 'Inter', sans-serif;
	--letter-spacing: -.02rem;
	font-size: 14px !important;

	/*Toasts*/
	--toast-background:var(--lv1);
}

/*More Compatibility Variables*/
.appMount-3lHmkl,
.theme-dark {
	--primary-color: rgba(0, 0, 0, 0.75);
	--secondary-color: rgba(0, 0, 0, 0.6);
	--tertiary-color: rgba(0, 0, 0, 0.4);
	--quaternary-color: rgba(0, 0, 0, 0.7)
}

/*1.b. Fonts and Text Scaling + Coloration*/

#app-mount {
    font-family:var(--font);
    letter-spacing:var(--letter-spacing);
}

.h4-AQvcAz, 
.h5-18_1nd,
.h2-2gWE-o,
.ui-form-title {
	text-transform:none !important;
}

.size24-RIRrxO,
.large-3Q-_XB {
	font-size:var(--sizelg);
}

.h2-2gWE-o,
.h2,
.ui-form-title,
.size20-17Iy80 {
	font-size:var(--size0) !important;
}

.size16-1P40sf,
.medium-zmzTW-,
.h3-3PDeKG,
.h3,
.default-3nhoK-,
.flex-1xMQg5 {
    font-size:var(--size1) !important;
}

.size14-e6ZScH,
.size12-3R0845 {
    font-size:var(--size2);
}

.h5-18_1nd,
.h5 {
    font-size:var(--size3);
}

.size12-3cLvbJ {
    font-size:var(--size4);
}

.brand-2-tkdo,
.colorBrand-2tjs5J {
	color: var(--accent) !important;
}

.statusGrey-2odOSc {
	color: var(--unavailable) !important;
}

.error-25JxNp,
.statusRed--sZUpc,
.colorError-3RX-d6 {
	color:var(--danger) !important;
}

.statusGreen-168O6Q {
	color: var(--success) !important;
}

.statusYellow-2OFFin {
	color: var(--caution) !important;
}

/*1.c. Text Selection & Links*/

#app-mount .anchor-3Z-8Bb:not(.guildsError-b7zR5H) {
	color: var(--accent);
	text-shadow: 0 0 12px
}

::selection {
	background-color: var(--accent);
}

/*1.d. Scrollbars*/

::-webkit-scrollbar {
	width:3px !important;
}

::-webkit-scrollbar-track,
::-webkit-scrollbar-track-piece {
	background:transparent !important;
	border: none !important;
	border-radius:0 !important;
}

::-webkit-scrollbar-thumb {
	border:none !important;
	background:var(--accent) !important;
	border-radius:0 !important;
}

::-webkit-scrollbar-thumb:active {
	background:var(--hover) !important;
}

/*1.e. Tooltips*/

@keyframes tooltip {
	0% {
		transform: scale(0.85);
		opacity:0;
	}
	100% {
		transform: scale(1);
		opacity:1;
	}
}

.toolbar-2bjZV7 {
	align-items: center;
	height:26px;
	margin-left:22px;
}

.toolbar-2bjZV7:before {
	border-width:6px;
	bottom:-6px;
}

.bubble-3we2di {
	display:flex;
	align-items:center;
}

.content-i8o2vp {
	background:var(--accent);
	border-radius:0;
}

.toolbar-2bjZV7 .button-qqmJ7w svg {
	color:var(--lv1) !important;
}

#app-mount .tooltip-2QfLtc,
.bd-tooltip,
.toolbar-2bjZV7,
.bubble-3we2d {
	font-size: var(--size2);
	border-radius: 2px;
	background: var(--tooltip-color) !important;
	padding: 4px 8px;
	font-weight: 500;
	color: var(--lv1);
	transform-origin: center;
	box-shadow:0 8px 16px rgba(0,0,0,0.25);
}

.full-motion #app-mount .tooltip-2QfLtc,
.full-motion .bd-tooltip,
.full-motion .toolbar-2bjZV7,
.full-motion .bubble-3we2d {
	animation: tooltip 150ms cubic-bezier(.23, 1, .3, 1);
}

#app-mount .tooltipPointer-3ZfirK,
.toolbar-2bjZV7:before,
.bubble-3we2di:before {
	border-top-color: var(--tooltip-color) !important;
}

.tooltipLeft-3EDOk1 .tooltipPointer-3ZfirK {
	left:calc(100% - 1px);
}

.tooltipRight-2JM5PQ .tooltipPointer-3ZfirK {
	right:calc(100% - 1px);
}

.tooltipBottom-3ARrEK .tooltipPointer-3ZfirK {
	bottom:calc(100% - 1px);
}

.tooltipTop-XDDSxx .tooltipPointer-3ZfirK {
	top:calc(100% - 1px);
}

.verified-1eC5dy {
	color:var(--accent);
}

.row-2OVM4t+.row-2OVM4t {
	margin:0;
}

.moreUsers-7v8yWY {
	padding:0;
	min-width:unset;
	background:transparent;
	color:var(--lv1);
	font-size:var(--size2);
}

.userTooltip-7qZaHD {
	color:var(--lv1);
	font-size:var(--size2);
}

.content-1DpZYB {
	border-radius:2px;
}

.tooltipBrand-g03Nz8,
.content-1DpZYB {
	background:var(--accent) !important;
	color:#f6f6f7 !important;
}

.tooltipBrand-g03Nz8 .tooltipPointer-3ZfirK,
.pointer-wWcxsg,
.pointer-1eHsgh {
	border-top-color:var(--accent) !important;
}

/*1.f. Global Keyframes*/

@keyframes fadeIn {
	0% {
		opacity:0;
	}
	100% {
		opacity:1;
	}
}

@keyframes fadeOut {
	0% {
		opacity:1;
	}
	100% {
		opacity:0;
	}
}

@keyframes rotate {
	0% {
		transform: rotate(0);
	}
	100% {
		transform: rotate(360deg);
	}
}

@keyframes scale {
	0% {
		transform: scale(0);
	}
	100% {
		transform: scale(1);
	}
}

@keyframes scaleX {
	0% {
		transform: scaleX(0);
	}
	100% {
		transform: scaleX(1);
	}
}

@keyframes scaleY {
	0% {
		transform: scaleY(0);
	}
	100% {
		transform: scaleY(1);
	}
}

@keyframes hue-rotate {
	0% {
		filter:hue-rotate(0);
	}
	100% {
		filter:hue-rotate(360deg);
	}
}

/*1.g. Spinners*/

.inner-1gJC7_:not(.pulsingEllipsis-3YiXRF):not(.spinningCircleInner-mbM5zM) {
	position: relative;
	border-top: 4px solid rgba(255, 255, 255, .2);
	border-right: 4px solid rgba(255, 255, 255, .2);
	border-bottom: 4px solid rgba(255, 255, 255, .2);
	border-left: 4px solid #fff;
	width: 25px;
	height: 25px;
	animation: rotate 1s infinite linear;
	border-radius:50%;
}

.wanderingCubesItem-WPXqao,
.lowMotionItem-1DvHia {
	display: none;
}

.chasingDotsItem-2DVNUn {
	background:var(--accent);
}

.path-92Hmty,
.path2-1q7bG_ {
	stroke:var(--accent) !important;
}

/*1.h. Unsupported Settings*/

html.theme-light #app-mount::after {
	content:'Light theme is not supported on Midnight. Please deactivate it through settings.';
	background:var(--lv1);
	position:fixed;
	z-index:999999;
	right:0;
	bottom:0;
	display:flex;
	align-items:center;
	max-width:250px;
	line-height:normal;
	padding: 15px;
	padding-left:50px;
	margin-right: 10px;
	margin-bottom:10px;
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07), 0 0 12px rgba(255, 255, 255, .025);
	border: 1px solid var(--lv1);
	border-left: 2px solid var(--caution);
	color: rgba(255, 255, 255, .65);
	font-size: var(--size1);
	font-family:var(--font);
	background-image: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMSAyMWgyMkwxMiAyIDEgMjF6bTEyLTNoLTJ2LTJoMnYyem0wLTRoLTJ2LTRoMnY0eiIvPjwvc3ZnPg==);
	background-repeat: no-repeat;
	background-size: 35px;
	background-position: 10px center;
}

html.full-motion.theme-light #app-mount::after {
	animation: bd-toast-up 300ms ease;
}

body.bd-minimal #app-mount::before {
	content:'Minimal Mode is not supported on Midnight. Please deactivate it through BandagedBD settings.';
	background:var(--lv1);
	position:fixed;
	z-index:999999;
	right:0;
	bottom:0;
	display:flex;
	align-items:center;
	max-width:250px;
	line-height:normal;
	padding: 15px;
	padding-left:50px;
	margin-right: 10px;
	margin-bottom:10px;
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07), 0 0 12px rgba(255, 255, 255, .025);
	border: 1px solid var(--lv1);
	border-left: 2px solid var(--caution);
	color: rgba(255, 255, 255, .65);
	font-size: var(--size1);
	font-family:var(--font);
	background-image: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMSAyMWgyMkwxMiAyIDEgMjF6bTEyLTNoLTJ2LTJoMnYyem0wLTRoLTJ2LTRoMnY0eiIvPjwvc3ZnPg==);
	background-repeat: no-repeat;
	background-size: 35px;
	background-position: 10px center;
}

.full-motion body.bd-minimal #app-mount::before {
	animation: bd-toast-up 300ms ease;
}

html.theme-light body.bd-minimal #app-mount::before {
	bottom:70px;
}

.compact-T3H92H * {
	display:none;
}

.preview-2nSL_2,
.messagesWrapper-3lZDfY {
	transform:translateZ(0);
}

.preview-2nSL_2 .compact-T3H92H:last-of-type,
.messagesWrapper-3lZDfY .compact-T3H92H:last-of-type {
	position:fixed;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:var(--lv1) !important;
	box-sizing:border-box;
	margin:0 !important;
	padding:0 !important;
	border:none !important;
	z-index:9999999;
	display:flex;
	flex-direction:column;
	align-items:center;
	justify-content:center;
}

.preview-2nSL_2 .compact-T3H92H:last-of-type::before,
.messagesWrapper-3lZDfY .compact-T3H92H:last-of-type::before {
	content:'¯\\_(ツ)_/¯';
	color:#fff;
	font-size:82px;
	margin-bottom:15px;
	font-weight:600;
}


.preview-2nSL_2 .compact-T3H92H:last-of-type::after,
.messagesWrapper-3lZDfY .compact-T3H92H:last-of-type::after {
	content:'Compact Mode is not supported on Midnight. Please deactivate it through settings.';
	line-height:normal;
	color: rgba(255, 255, 255, .65);
	font-size: var(--size1);
}

/*2. Titlebar*/

/*2.a. Windows Titlebar and Buttons*/

.titleBar-AC4pGV {
	height: 26px;
	box-shadow: 0 0 10px var(--lv1);
	margin-top: 4px;
}

.winButton-iRh8-Z {
	height: 30px;
	transition: .1s ease background;
	transform: scale(1.01);
	width: 45px;
	top: -4px;
	cursor: default;
	color: #fff;
	z-index:3001;
}

.winButtonClose-1HsbF-:hover {
	background: #e81123;
}

.winButtonClose-1HsbF-:active {
    background:rgb(151,23,34);
}

.winButtonMinMax-PBQ2gm:active {
    background:rgba(255,255,255,0.15);
}

/*2.b. OSX Titlebar and Buttons*/

.macButtons-2MuSAC {
    height:24px;
    align-items:center;
}

.typeMacOS-3EmCyP {
    width:100%;
    background:var(--lv1);
}

.typeMacOS-3EmCyP::after {
    content:'';
    top:0;
    left:0;
    height:100%;
    width:100%;
    z-index:-1;
    background:var(--lv1);
    position:absolute;
}

.typeMacOS-3EmCyP {
	position: relative
}

.macButtons-2MuSAC::after,
.macButtons-2MuSAC::before {
	position: absolute;
	pointer-events: none;
	transform: translateX(-50%);
	opacity: .8
}

.macButtons-2MuSAC::before {
	content: var(--theme-name);
	left: calc(50% - 31px);
	text-shadow: 0 0 12px;
	font-weight: 600;
	color: var(--accent);
	font-size: 16px
}

.macButtons-2MuSAC::after {
	content:'v' var(--theme-version);
	left: calc(50% + 31px);
	text-shadow: 0 0 12px;
	font-weight: 400;
	color: rgba(255, 255, 255, .8);
	font-size: 16px
}

.platform-osx .headerBarDrag-3bf7wG,
.platform-osx .pageHeaderDrag-OPlmbm {
	-webkit-app-region: no-drag
}

/*2.c. Wordmark*/

.wordmark-2iDDfm {
	opacity: 1;
	width: 100%;
	background: var(--lv1);
	padding: 0;
	display: flex;
	align-items: center;
	height: 30px;
	padding-left: 12px;
}

.wordmark-2iDDfm svg {
	display: none;
}

.wordmark-2iDDfm:before,
.wordmark-2iDDfm:after {
  font-size:var(--size1);
}

.wordmark-2iDDfm:before {
	content: var(--theme-name);
	font-weight: 600;
	color: var(--accent);
	text-shadow: 0 0 12px;
}

.wordmark-2iDDfm:after {
	content: 'v' var(--theme-version);
	font-weight: 400;
	color: rgba(255, 255, 255, .8);
	margin-left: 5px;
}

/*3. Header*/

/*3.a. Outer Toolbar*/

.children-19S4PO:after {
	background:var(--lv1);
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07);
	-webkit-mask:linear-gradient(-90deg, var(--lv1), transparent);
	right:-1px;
	height:40px;
}

#app-mount .container-1r6BKw {	
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07);
	height: 40px;
	border-bottom: 2px solid var(--hover);
	box-sizing: border-box;
	background: var(--lv1);
	overflow: visible;
}

.children-19S4PO .iconWrapper-2OrFZ1:first-child {
	display:flex;
	align-items:center;
}

.children-19S4PO .iconWrapper-2OrFZ1:first-child .icon-22AiRD {
	color:rgba(255,255,255,0.5);
	width: 16px;
	height: 16px;
}

.status-1XNdyw {
	margin-left: 4px;
}

.title-29uC1r {
	font-weight:500;
}

.channelName-qsg_a_ {
	margin:0;
}

#app-mount .container-1MGX4D .input-2A_zIr {
	all:unset;
	cursor:text !important;
	white-space:nowrap;
	font-size:var(--size1);
	box-shadow:none !important;
	border:none !important;
	background:transparent !important;
}

.akaBadge-1M-1Gw {
	border-radius: 0;
	background: var(--hover) !important;
	color:#fff;
	font-size:var(--size3);
	font-weight:500;
	margin:0 8px;
}

.nicknames-1XK4Zt,
.topic-TCb_qw {
	font-size:var(--size3);
}

.status-1XNdyw,
.nicknames-1XK4Zt {
	margin:0;	
}

.status-1XNdyw rect {
    mask:none;
    width:8px;
    height:8px;
	y:3;
	rx:50;
}

.status-1XNdyw rect[fill*="rgba(240, 71, 71, 1)"] {
	fill:var(--danger);
}

.status-1XNdyw rect[fill*="rgba(67, 181, 129, 1)"] {
	fill:var(--success);
}

.status-1XNdyw rect[fill*="rgba(116, 127, 141, 1)"] {
	fill:var(--unavailable);
}

.status-1XNdyw rect[fill*="rgba(250, 166, 26, 1)"] {
	fill:var(--caution);
}

.status-1XNdyw rect[fill*="rgba(89, 54, 149, 1)"] {
	fill:var(--twitch-purple);
}

.content-yTz4x3:before,
.tabBody-3YRQ8W:before {
	display:none;
}

/*3.b. Toolbar Icons*/

.iconWrapper-2OrFZ1,
.search-36MZv- {
	margin: 0 4px;
}

.strikethrough-3Wiitd {
	color:var(--danger);
}

.divider-3FBTu8,
.container-1r6BKw .toolbar-1t6TWx a,
.toolbar-1t6TWx .icon-22AiRD path[d="M14 8.00598C14 10.211 12.206 12.006 10 12.006C7.795 12.006 6 10.211 6 8.00598C6 5.80098 7.794 4.00598 10 4.00598C12.206 4.00598 14 5.80098 14 8.00598ZM2 19.006C2 15.473 5.29 13.006 10 13.006C14.711 13.006 18 15.473 18 19.006V20.006H2V19.006Z"] ~ path,
.toolbar-1t6TWx .icon-22AiRD .strikethrough-3Wiitd ~ path,
.children-19S4PO path[d="M14 8.00598C14 10.211 12.206 12.006 10 12.006C7.795 12.006 6 10.211 6 8.00598C6 5.80098 7.794 4.00598 10 4.00598C12.206 4.00598 14 5.80098 14 8.00598ZM2 19.006C2 15.473 5.29 13.006 10 13.006C14.711 13.006 18 15.473 18 19.006V20.006H2V19.006Z"] ~ path {
	display: none;	
}

.toolbar-1t6TWx .icon-22AiRD path[d="M22 12L12.101 2.10101L10.686 3.51401L12.101 4.92901L7.15096 9.87801V9.88001L5.73596 8.46501L4.32196 9.88001L8.56496 14.122L2.90796 19.778L4.32196 21.192L9.97896 15.536L14.222 19.778L15.636 18.364L14.222 16.95L19.171 12H19.172L20.586 13.414L22 12Z"] {
	d:path('M 17.9,13.7 15.8,12.6 15.1,5.3 16.4,5 16.4,3 7.6,3 7.6,5 8.9,5.3 8.2,12.6 6.1,13.7 6.1,15.7   11,15.7 11,21 13,21 13,15.7 17.9,15.7 z');
}

.toolbar-1t6TWx .icon-22AiRD path[d="M14 8.00598C14 10.211 12.206 12.006 10 12.006C7.795 12.006 6 10.211 6 8.00598C6 5.80098 7.794 4.00598 10 4.00598C12.206 4.00598 14 5.80098 14 8.00598ZM2 19.006C2 15.473 5.29 13.006 10 13.006C14.711 13.006 18 15.473 18 19.006V20.006H2V19.006Z"] {
	d:path('M3 18h12v-2H3v2zM3 6v2h18V6H3zm0 7h18v-2H3v2z');
}

.toolbar-1t6TWx .icon-22AiRD path[d="M12 2C6.486 2 2 6.486 2 12C2 17.515 6.486 22 12 22C14.039 22 15.993 21.398 17.652 20.259L16.521 18.611C15.195 19.519 13.633 20 12 20C7.589 20 4 16.411 4 12C4 7.589 7.589 4 12 4C16.411 4 20 7.589 20 12V12.782C20 14.17 19.402 15 18.4 15L18.398 15.018C18.338 15.005 18.273 15 18.209 15H18C17.437 15 16.6 14.182 16.6 13.631V12C16.6 9.464 14.537 7.4 12 7.4C9.463 7.4 7.4 9.463 7.4 12C7.4 14.537 9.463 16.6 12 16.6C13.234 16.6 14.35 16.106 15.177 15.313C15.826 16.269 16.93 17 18 17L18.002 16.981C18.064 16.994 18.129 17 18.195 17H18.4C20.552 17 22 15.306 22 12.782V12C22 6.486 17.514 2 12 2ZM12 14.599C10.566 14.599 9.4 13.433 9.4 11.999C9.4 10.565 10.566 9.399 12 9.399C13.434 9.399 14.6 10.565 14.6 11.999C14.6 13.433 13.434 14.599 12 14.599Z"] {
	d:path('M12.2608,9.57136 C11.91424,9.57136 11.6072,9.67136 11.3464,9.87136 C11.0856,10.07136 10.86432,10.32496 10.68208,10.63568 C10.5,10.94288 10.36432,11.2856 10.26784,11.65712 C10.17488,12.02864 10.12496,12.38944 10.12496,12.73216 C10.12496,12.90352 10.14288,13.08576 10.17856,13.28224 C10.21424,13.47504 10.2856,13.6536 10.39632,13.82144 C10.50352,13.9856 10.64624,14.12144 10.82128,14.22864 C10.99632,14.33584 11.22848,14.38944 11.51776,14.38944 C11.91056,14.38944 12.24272,14.2928 12.51776,14.1 C12.7928,13.9072 13.01776,13.66416 13.1928,13.36784 C13.36784,13.07504 13.4928,12.7536 13.57504,12.41088 C13.6536,12.068 13.6928,11.75008 13.6928,11.46432 C13.6928,11.23568 13.67136,11.01072 13.62864,10.78576 C13.58576,10.56432 13.51088,10.36432 13.4,10.18224 C13.2928,10.00368 13.14288,9.85728 12.9536,9.74288 C12.76784,9.62864 12.53584,9.57136 12.2608,9.57136 L12.2608,9.57136 Z M18.57808,16.8728 C18.84672,17.16224 18.84672,17.63168 18.55136,17.89328 C17.81248,18.54608 16.96928,19.0408 16.02144,19.37504 C14.8464,19.7928 13.6072,20 12.30352,20 C11.05696,20 9.92128,19.80352 8.9,19.4072 C7.87856,19.0144 7.00352,18.46416 6.28208,17.7608 C5.55712,17.05728 4.99632,16.21424 4.59632,15.23216 C4.19648,14.24992 4,13.17856 4,12.01792 C4,10.87136 4.21792,9.81072 4.6536,8.83568 C5.08928,7.86064 5.68208,7.01424 6.43568,6.29632 C7.18928,5.57856 8.06784,5.01776 9.07856,4.60704 C10.08208,4.20352 11.16064,4 12.30352,4 C13.28912,4 14.2464,4.14288 15.17136,4.42864 C16.1,4.7144 16.92144,5.1464 17.63936,5.71792 C18.35712,6.29296 18.92864,7.0072 19.35712,7.86784 C19.78576,8.72864 20,9.73936 20,10.9 C20,11.76064 19.88224,12.52144 19.64288,13.17856 C19.40368,13.8392 19.08592,14.38928 18.68592,14.83568 C18.28592,15.28208 17.83232,15.61408 17.31792,15.83568 C16.80368,16.05712 16.26448,16.16768 15.70016,16.16768 C15.1216,16.16768 14.65728,16.032 14.30736,15.76064 C13.96096,15.48912 13.78592,15.14272 13.78592,14.72848 L13.67872,14.72848 C13.46096,15.07136 13.12864,15.39984 12.67872,15.70704 C12.2288,16.01424 11.67872,16.1712 11.02512,16.1712 C10.03936,16.1712 9.27872,15.84976 8.74288,15.20336 C8.2072,14.55696 7.93936,13.72112 7.93936,12.6856 C7.93936,12.08192 8.03936,11.48912 8.24288,10.89984 C8.4464,10.31056 8.73584,9.78912 9.11072,9.32848 C9.48576,8.87136 9.93568,8.49984 10.45712,8.22128 C10.97856,7.94272 11.55712,7.80352 12.19648,7.80352 C12.74656,7.80352 13.21088,7.91776 13.58928,8.1464 C13.96432,8.37504 14.21088,8.65712 14.32864,8.98576 L14.35008,8.98576 L14.38288,8.82512 C14.46144,8.4384 14.8448,8.12512 15.23936,8.12512 L15.74656,8.12512 C16.14128,8.12512 16.3952,8.43792 16.31408,8.824 L15.60736,12.19296 C15.57872,12.39296 15.53936,12.6144 15.48944,12.8608 C15.43952,13.10384 15.4144,13.33232 15.4144,13.55024 C15.4144,13.79312 15.46096,13.99664 15.55744,14.16448 C15.65024,14.3288 15.836,14.41104 16.11088,14.41104 C16.6752,14.41104 17.14304,14.11088 17.51456,13.50752 C17.8824,12.904 18.068,12.0968 18.068,11.07888 C18.068,10.21824 17.9216,9.45392 17.63232,8.7896 C17.34288,8.12176 16.93936,7.56464 16.42512,7.11104 C15.91088,6.66112 15.29648,6.31824 14.58928,6.0896 C13.87872,5.86096 13.10368,5.74672 12.26448,5.74672 C11.35008,5.74672 10.5144,5.90736 9.75376,6.22896 C8.99296,6.5504 8.34304,6.9968 7.8072,7.56112 C7.27152,8.12896 6.85376,8.79328 6.55728,9.56112 C6.25728,10.32544 6.10736,11.15408 6.10736,12.04336 C6.10736,12.98976 6.26448,13.84336 6.5752,14.604 C6.88592,15.36464 7.32528,16.0112 7.88944,16.5504 C8.4536,17.0896 9.1288,17.50048 9.91088,17.78624 C10.69312,18.07184 11.55728,18.21472 12.49664,18.21472 C13.67168,18.21472 14.6824,18.02912 15.5288,17.65408 C16.16528,17.37488 16.76304,17.01264 17.32304,16.56944 C17.632,16.3248 18.08192,16.3384 18.35056,16.62768 L18.57808,16.8728 L18.57808,16.8728 Z');
}

.toolbar-1t6TWx .icon-22AiRD path[d="M18 9V14C18 15.657 19.344 17 21 17V18H3V17C4.656 17 6 15.657 6 14V9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9ZM11.9999 21C10.5239 21 9.24793 20.19 8.55493 19H15.4449C14.7519 20.19 13.4759 21 11.9999 21Z"] {
	d:path('M12 22c1.1 0 2-.9 2-2h-4c0 1.1.89 2 2 2zm6-6v-5c0-3.07-1.64-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.63 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2z');
}

.toolbar-1t6TWx .icon-22AiRD .strikethrough-3Wiitd {
	d:path('M20 18.69L7.84 6.14 5.27 3.49 4 4.76l2.8 2.8v.01c-.52.99-.8 2.16-.8 3.42v5l-2 2v1h13.73l2 2L21 19.72l-1-1.03zM12 22c1.11 0 2-.89 2-2h-4c0 1.11.89 2 2 2zm6-7.32V11c0-3.08-1.64-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68c-.15.03-.29.08-.42.12-.1.03-.2.07-.3.11h-.01c-.01 0-.01 0-.02.01-.23.09-.46.2-.68.31 0 0-.01 0-.01.01L18 14.68z');
}

.toolbar-1t6TWx .icon-22AiRD path[d="M11 5V3C16.515 3 21 7.486 21 13H19C19 8.589 15.411 5 11 5ZM17 13H15C15 10.795 13.206 9 11 9V7C14.309 7 17 9.691 17 13ZM11 11V13H13C13 11.896 12.105 11 11 11ZM14 16H18C18.553 16 19 16.447 19 17V21C19 21.553 18.553 22 18 22H13C6.925 22 2 17.075 2 11V6C2 5.447 2.448 5 3 5H7C7.553 5 8 5.447 8 6V10C8 10.553 7.553 11 7 11H6C6.063 14.938 9 18 13 18V17C13 16.447 13.447 16 14 16Z"] {
	d:path('M7.5,10.501456 C8.94,13.331456 10.6672741,15.05 13.4972741,16.5 L15.41,15.18 C15.68,14.91 16.08,14.82 16.43,14.94 C17.55,15.31 18.76,15.51 20,15.51 C20.55,15.51 21,15.96 21,16.51 L21,20 C21,20.55 20.55,21 20,21 C10.61,21 2.78999996,13.6400003 3,4 C3.01197849,3.45013046 3.45,3 4,3 L7.5,3 C8.05,3 8.5,3.45 8.5,4 C8.5,5.25 8.7,6.45 9.07,7.57 C9.18,7.92 9.1,8.31 8.82,8.59 L7.5,10.501456 Z');
}

.toolbar-1t6TWx .icon-22AiRD path[d="M21.526 8.149C21.231 7.966 20.862 7.951 20.553 8.105L18 9.382V7C18 5.897 17.103 5 16 5H4C2.897 5 2 5.897 2 7V17C2 18.104 2.897 19 4 19H16C17.103 19 18 18.104 18 17V14.618L20.553 15.894C20.694 15.965 20.847 16 21 16C21.183 16 21.365 15.949 21.526 15.851C21.82 15.668 22 15.347 22 15V9C22 8.653 21.82 8.332 21.526 8.149Z"] {
	d:path('M17,10.5 L17,7 C17,6.45 16.55,6 16,6 L4,6 C3.45,6 3,6.45 3,7 L3,17 C3,17.55 3.45,18 4,18 L16,18 C16.55,18 17,17.55 17,17 L17,13.5 L21,17.5 L21,6.5 L17,10.5 Z');
}

.toolbar-1t6TWx .icon-22AiRD path[d="M21 3H24V5H21V8H19V5H16V3H19V0H21V3ZM10 12C12.205 12 14 10.205 14 8C14 5.795 12.205 4 10 4C7.795 4 6 5.795 6 8C6 10.205 7.795 12 10 12ZM10 13C5.289 13 2 15.467 2 19V20H18V19C18 15.467 14.711 13 10 13Z"] {
	d:path('M15 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm-9-2V7H4v3H1v2h3v3h2v-3h3v-2H6zm9 4c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z');
}

.toolbar-1t6TWx .icon-22AiRD path[d="M20.998 0V3H23.998V5H20.998V8H18.998V5H15.998V3H18.998V0H20.998ZM2.99805 20V24L8.33205 20H14.998C16.102 20 16.998 19.103 16.998 18V9C16.998 7.896 16.102 7 14.998 7H1.99805C0.894047 7 -0.00195312 7.896 -0.00195312 9V18C-0.00195312 19.103 0.894047 20 1.99805 20H2.99805Z"] {
	d:path('M15 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm-9-2V7H4v3H1v2h3v3h2v-3h3v-2H6zm9 4c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z');
}

.iconWrapper-2OrFZ1 foreignObject {
	mask:none !important;
}

.iconBadge-qZ4Ksk {
	top:2px;
	right:4px;
	background:var(--danger);
	box-shadow:0 0 0 2px rgb(240, 71, 71, 0.5);
}

.children-19S4PO path[d="M14 8.00598C14 10.211 12.206 12.006 10 12.006C7.795 12.006 6 10.211 6 8.00598C6 5.80098 7.794 4.00598 10 4.00598C12.206 4.00598 14 5.80098 14 8.00598ZM2 19.006C2 15.473 5.29 13.006 10 13.006C14.711 13.006 18 15.473 18 19.006V20.006H2V19.006Z"] {
	d:path('M12 12.041v-0.825c1.102-0.621 2-2.168 2-3.716 0-2.485 0-4.5-3-4.5s-3 2.015-3 4.5c0 1.548 0.898 3.095 2 3.716v0.825c-3.392 0.277-6 1.944-6 3.959h14c0-2.015-2.608-3.682-6-3.959z M5.112 12.427c0.864-0.565 1.939-0.994 3.122-1.256-0.235-0.278-0.449-0.588-0.633-0.922-0.475-0.863-0.726-1.813-0.726-2.748 0-1.344 0-2.614 0.478-3.653 0.464-1.008 1.299-1.633 2.488-1.867-0.264-1.195-0.968-1.98-2.841-1.98-3 0-3 2.015-3 4.5 0 1.548 0.898 3.095 2 3.716v0.825c-3.392 0.277-6 1.944-6 3.959h4.359c0.227-0.202 0.478-0.393 0.753-0.573z');
	transform:scale(1.35);
}

/*3.c. Message Search*/

@keyframes search {
	0% {
		transform: translateY(-20px);
		opacity: 0
	}
	100% {
		transform: none;
		opacity: 1
	}
}

@keyframes searchTooltip {
	0% {
		transform: scale(0.85) translateX(-50%);
		opacity:0;
	}
	100% {
		transform: scale(1) translateX(-50%);
		opacity:1;
	}
}

@keyframes searchTooltipPointer {
	0% {
		transform: scale(0.85) translateX(-50%) rotate(-90deg);
		opacity:0;
	}
	100% {
		transform: scale(1) translateX(-50%) rotate(-90deg);
		opacity:1;
	}
}

.search-36MZv- {
	order: -1;
}

.search-2oPWTC .DraftEditor-root {
	font-size:var(--size1);
}

.search-2oPWTC .searchBar-3dMhjb {
	width: 24px;
	height:24px;
	transition: none;
	background-color:transparent;
}

.searchBar-3dMhjb .icon-38sknP {
	-webkit-mask: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMTUuNSAxNGgtLjc5bC0uMjgtLjI3QzE1LjQxIDEyLjU5IDE2IDExLjExIDE2IDkuNSAxNiA1LjkxIDEzLjA5IDMgOS41IDNTMyA1LjkxIDMgOS41IDUuOTEgMTYgOS41IDE2YzEuNjEgMCAzLjA5LS41OSA0LjIzLTEuNTdsLjI3LjI4di43OWw1IDQuOTlMMjAuNDkgMTlsLTQuOTktNXptLTYgMEM3LjAxIDE0IDUgMTEuOTkgNSA5LjVTNy4wMSA1IDkuNSA1IDE0IDcuMDEgMTQgOS41IDExLjk5IDE0IDkuNSAxNHoiLz48cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+) center/110% no-repeat;
	background-color: #b9bbbe;
	cursor: pointer;
}

.open-6_Y_aH .searchBar-3dMhjb .icon-38sknP {
	-webkit-mask: none;
	background-color: transparent;
}

.open-6_Y_aH .icon-3cZ1F_.visible-3V0mGj {
	opacity:1 !important;
}

.search-36MZv- .icon-3cZ1F_.visible-3V0mGj {
	opacity:0;
}

.open-6_Y_aH .searchBar-3dMhjb .icon-38sknP {
	margin-right: 48px;
	z-index: 100;
}

.open-6_Y_aH .searchBar-3dMhjb {
	width: 100%;
}

.open-6_Y_aH.search-2oPWTC::before,
.open-6_Y_aH.search-2oPWTC::after {
	display:none;
}

.search-36MZv-:hover .search-2oPWTC::before {
	content: '';
	position: absolute;
	top:21px;
	left:50%;
	border: 5px solid transparent;
	border-left: 5px solid var(--tooltip-color);
	transform: rotate(-90deg) translateY(-50%);
	background: transparent;
	width: 0;
	height: 0;
	z-index:1;
}

.full-motion .search-36MZv-:hover .search-2oPWTC::before {
	animation: searchTooltipPointer 150ms cubic-bezier(.23, 1, .3, 1);
}

.search-36MZv-:hover .search-2oPWTC::after {
	content: 'Search';
	position: absolute;
	top: 30px;
	left: 50%;
	font-size: var(--size2);
	border-radius: 2px;
	background: var(--tooltip-color);
	padding: 4px 8px;
	font-weight: 500;
	color: var(--lv1);
	transform-origin: center;
	line-height:16px;
	transform:translateX(-50%);
	box-shadow:0 8px 16px rgba(0,0,0,0.25);
}

.full-motion .search-36MZv-:hover .search-2oPWTC::after {
	animation: searchTooltip 150ms cubic-bezier(.23, 1, .3, 1);
}

.open-6_Y_aH .search-36MZv-::after,
.open-6_Y_aH .search-36MZv-::before,
.searchBar-3dMhjb .icon-38sknP svg[name="Search"] {
	display: none;
}

.open-6_Y_aH .icon-38sknP svg[name="Search"] {
	display: block;
}

.container-1r6BKw {
	overflow: visible;
}

.open-6_Y_aH {
	position: absolute;
	left: 0;
	background: var(--lv1);
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07);
	width: 99%;
	top: 0;
	height: 38px;
	display: flex;
	align-items: center;
	z-index: 1000;
}

.full-motion .open-6_Y_aH {
	animation: search .5s ease forwards
}

.searchAnswer-3Dz2-q {
	margin-left:4px;
}

.searchAnswer-3Dz2-q, 
.searchFilter-2ESiM3 {
	background:rgba(255, 255, 255, .07) !important;
	box-shadow:0 2px 8px rgba(0, 0, 0, .25);
	padding:4px 6px;
	font-size:var(--size1);
	line-height:12px;
	border-radius:2px;
	cursor:default;
	transition:150ms ease box-shadow;
}

.searchAnswer-3Dz2-q:hover, 
.searchFilter-2ESiM3:hover {
	box-shadow:0 2px 12px rgba(0, 0, 0, .25), inset 0 0 0 1px var(--hover);
}


/*3.d. Tab Bar*/

.topPill-30KHOu .item-PXvHYJ {
	border-radius: 0;
	font-size:var(--size1);
	transition: 150ms ease all
}

.topPill-30KHOu .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ,
.topPill-30KHOu .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ:hover {
	background: var(--hover);
}

.topPill-30KHOu .themed-OHr7kt.item-PXvHYJ:hover {
	background:rgba(255,255,255,0.07);
}

/*3.e. Call and DM Animation*/

@keyframes callPulse {
	0% {
		opacity: 0;
		transform: scaleX(0)
	}
	50% {
		opacity: 1;
		transform: scaleX(1)
	}
	100% {
		opacity: 0
	}
}

@keyframes dmPulse {
	0% {
		opacity: 0;
		transform: scaleX(0)
	}
	50% {
		opacity: .4;
		transform: scaleX(1)
	}
	100% {
		opacity: 0
	}
}

.container-1giJp5::after {
	content: '';
	position: fixed;
	top: 68px;
	left: 0;
	z-index: 101;
	width: 100%;
	height: 2px;
	background: var(--accent);
	box-shadow: 0 0 12px var(--accent);
	animation: callPulse 2.25s ease infinite;
	transform-origin: left;
	pointer-events: none;
}

.reduce-motion .container-1giJp5::after,
.reduce-motion .wrapper-1Rf91z .scroller-2TZvBN>div:not(.listItem-2P_4kh)+.listItem-2P_4kh::after {
	content:none;
}

.wrapper-1Rf91z .scroller-2TZvBN>div:not(.listItem-2P_4kh)+.listItem-2P_4kh::after {
	content: '';
	position: fixed;
	top: 30px;
	left: 0;
	z-index: 1001;
	width: 100%;
	height: 40px;
	background-color: var(--accent);
	box-shadow: 0 0 12px var(--accent);
	animation: dmpulse 1.25s ease;
	opacity: 0;
	pointer-events: none;
	overflow: visible;
	transform-origin: center
}

/*3.f. Avatar Positioning*/

.panels-j1Uci_ .container-3baos1:not(.powercord-spotify) .avatarWrapper-2yR4wp {
	position: absolute;
	top: -2px;
	right: 0;
	height:40px;
	padding-left: 30px;
	z-index: 1;
	display:flex;
	align-items:center;
	cursor:pointer;
}

.panels-j1Uci_ .container-3baos1:not(.powercord-spotify) .avatarWrapper-2yR4wp .wrapper-3t9DeA {
	width: 25px !important;
	height: 25px !important;
}

.toolbar-1t6TWx {
	margin-right: 50px;
}

.panels-j1Uci_ .wrapper-3t9DeA::after {
	content: '';
	left: -20px;
	top: 12px;
	width: 0;
	height: 0;
	position: absolute;
	border: 5px solid transparent;
	color: rgba(255, 255, 255, .6);
	border-top: 5px solid currentColor;
}

.panels-j1Uci_ .avatarWrapper-2yR4wp:hover .wrapper-3t9DeA::after {
	color: rgba(255, 255, 255, .85);
	background: transparent;
	padding: 0;
	pointer-events: initial;
	left: -20px;
	box-shadow: none;
	width: 0;
}

.container-3baos1 .avatar-SmRMf2:hover {
	opacity: 1;
}

/*4. Guilds*/

/*4.a. General Wrapper*/

.base-3dtUhz {
	left:60px;
	z-index:1;
}

#app-mount .guilds-1SWlCJ {
	margin-top: 40px;
	overflow: visible
}

.guilds-1SWlCJ ::-webkit-scrollbar {
	display: none;
}

.scrollerWrap-1IAIlv .scroller-2TZvBN>.container-1ETFDs {
	position: absolute;
	top: -49px;
	left: -6px;
	width: 70px;
	display: flex;
	z-index: 1000;
	justify-content: center;
	margin-top: 5px;
	height: 42px;
}

.scroller-2TZvBN {
	padding-bottom: 50px;
	contain:none;
	display:flex;
	flex-direction:column;
}

#app-mount .wrapper-1Rf91z,
.scroller-2TZvBN,
.scrollerWrap-1IAIlv {
	width: 60px;
}

.unreadMentionsIndicatorBottom-BXS58x,
.unreadMentionsIndicatorTop-gA6RCh {
	padding: 0;
	width: 60px;
	z-index:2;
}

.mention-1f5kbO {
	background-color:var(--danger) !important;
}

.unreadMentionsIndicatorBottom-BXS58x {
	bottom: 34px;
}

.bar-30k2ka {
	font-size:var(--size3);
	border-radius:0;
}

.unreadMentionsIndicatorTop-gA6RCh .bar-30k2ka {
    border-radius:0 0 3px 3px;
}

.unreadMentionsIndicatorBottom-BXS58x .bar-30k2ka {
    border-radius:3px 3px 0 0;
}

#app-mount .guildSeparator-3s64Iy {
	background: rgba(255, 255, 255, .1);
}

/*4.b. Home Icon*/

.scroller-2TZvBN {
	position:static;
}

.childWrapper-anI2G9 {
	background:transparent !important;
	font-size:var(--size0);
	line-height:40px;
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv .tutorialContainer-1v44GL {
	position: absolute;
	top: -44px;
	display: flex;
	justify-content: center;
	height: 42px;
	border-bottom: 2px solid var(--hover);
	width:60px;
	background:rgba(255,255,255,0.07);
}

.homeIcon-tEMBK1 {
	background-color: #fff !important;
	-webkit-mask: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQAAAAEACAMAAABrrFhUAAACBFBMVEX///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////+CAoa0AAAAq3RSTlMAAQIDBAUHCAkKCwwNDg8QERIUFRcYGRocHR4fICEiIyQlJikqKywtMDIzNTg7PT5AQUJFRkdISUpLTU5PUFFSU1dZXmFiZmdoa2xtb3Byc3R1dnl6e32AgYKEhYiKjI+RkpSWl5manJ2en6ChoqOkpaaoqaqsra6xs7i5ur2+wcLDxsjKy83O0NHS09bX2Nnb3N3f4ePl5ujp6uvt7vDx8vP09fb3+Pr7/f5i9vAlAAAEEklEQVR4AezcIa6DQBCAYR5PsqhWYzktsogatiRVXLI9QEOygiwZvt+OmXxuzDS6TpIkSZIkSZIkSZIkSZIkzfnUzd3RANvJ648GyNupywkAAAAAAAAAAAAAAAAAABwPsI5D1ca1MsDSVG6pDJBTU7X0Yx8AAAAAAAAAAAAAAAAAAND+F9VGA+imR1FTNIB+KywawHdeVAYAAAAAAAAAAAAAAECQY+jiAOn53i86wN/tvtvwCglQ0HJxgJQBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQ4bn6h7z7bmoqjeI4/stuYHfZAbLsUsKaAQuMBVQEFBGxA6JYsGDvWAQUewcRlQJCUEYJaCIFApw36fj/c64zyXMfnsn5voKTz5zMnTn3jxv/Bvi8zsExb7z5lnoDFkNjjo38Db7twbF4Cy0aB9D3/b/TpCPLAfiBkh+RaIDCIIkGqFwg0QDniCQD/H6fRAMUDpFogOooiQY4SyQZwPuURAOsHiTRAJVEogHOUAIAxD5Q0hMyUKrbAKEZ51iAVUFimtFYyPUNSPc55p9kAHbNE9M+n8bSPVoA9J+oThHTp4123RRdOlI+I6bOvyAAoKCXmK4AiQ6QBuwgrlokPMCcw9N/tAiJD/Ax5RYxdaRBAMCXUWJqBgQA8O2BaIDQBogG6EyHaICrgGiAGogGmCiCaIAX/8CmPBHDANdgV8mGN2Av1LUOx95QI/hSeoYdCy6YBBgvhrLstxRX18GWSr/KIEDHv1BW9o3i7E0OP489AJeh7gjFX6TEfoAaqLtNWjpkOcD4GijL6idNtVkN8DILyrZOkLa6AvYCNEPdAdLZ92JbAeqg7iZprsFKgFARlOW8J+3dsBDgVQaUlYfJhbr9tgFchLpGcqdIqV0A9VDmaSbXqrcIYGItlGX2k4u1WgPQ+R+UVc+Tq3VlxwxAOgEuQdlvR8ntJjfFCjCpEaAWDMD6goCmdrI/r4EBmCoMOPa/NoDP62Agfw8xtagBIqaOjK99MJLnMTG9y2Re1xsBuABjHSSmSPnSAeyHwapmiakOSDMOEGH+/i6W10dMd4BZwwB/RqkjA6ZrJ6bn+SOGAbJ/qpvvMDFFvxoGCOzGklQxT3w8QAKV3y0cAHgoHQDHpAOgalo4APIGhAMA96QD4IR0AJRFhQNgZY9wAOCBdACclA6ALVPCAbC8VzgA0CIdAE3SAVA6JxwAKwaEA8BzVzgAcFw6ADaHhQMg94NwAHhbhAMATdIBUDEtHAD5fcIB4GkTDgA0SgfAtrBwACwbJApLBkBSO9EfEN15yoXsSvz40R4cCAAAAAAI8rceYYFqAAAAAAEefSZtIWsy0wAAAABJRU5ErkJggg==);
	-webkit-mask-size: 28px;
	-webkit-mask-repeat: no-repeat;
	-webkit-mask-position: center;
	margin: 0;
	height: 100%;
	width: 100%;
}

/*4.c. Icons*/

#app-mount .wrapper-1Rf91z foreignObject {
	mask: none !important;
	border-radius: 0;
	overflow:visible;
}

#app-mount .listItem-2P_4kh {
	width: 60px;
	left: 0;
	margin-bottom: 10px;
}

.listItemWrapper-3X98Pc:active {
	transform:none !important;
}

#app-mount .wrapper-1Rf91z foreignObject,
.acronym-2mOFsV,
.icon-27yU2q,
.wrapper-1BJsBx,
.wrapper-25eVIn,
.circleIconButton-jET_ig,
.closedFolderIconWrapper-15K9MK,
.folder-21wGz3,
.folderIconWrapper-226oVY,
.dragInner-_SHftW,
.guildsError-b7zR5H {
	width: 40px;
	height: 40px;
}

.icon-27yU2q,
.folderIconWrapper-226oVY,
.iconInactive-98JN5i,
#app-mount .circleIconButton-jET_ig,
.guildsError-b7zR5H,
.guildIconUnavailable-5PMHDN,
.guildIcon-lQ0uiM {
    border-radius:var(--guilds-roundness) !important;
}

#app-mount .circleIconButton-jET_ig {
	background: var(--accent);
	color: #fff;
}

.circleIcon-LvPL6c,
.circleIconButton-jET_ig svg {
	width:20px;
	height:20px;
}

.guildIconUnavailable-5PMHDN,
.guildsError-b7zR5H {
	line-height: 35px;
	box-shadow: 0 0 12px var(--danger);
	background: rgba(255, 255, 255, .1);
}

/*4.d. Folders*/

.folder-21wGz3 {
	background: transparent !important;
}

.closedFolderIconWrapper-15K9MK {
	position:relative;
	z-index:1;
}

.expandedFolderIconWrapper-1xLaU- {
	width: 40px;
	height: 40px;
	transform:none !important;
}

.expandedFolderIconWrapper-1xLaU- svg {
	transform: scale(4);
}

.expandedFolderBackground-2sPsd-.collapsed-1GMuSb {
	box-shadow:none;
}

.expandedFolderBackground-2sPsd- {
	width: 40px;
	background: rgba(255, 255, 255, .15);
	box-shadow: 0 0 12px rgba(255, 255, 255, .2);
	border-radius: var(--guilds-roundness);
	left: 10px;
}

.expandedFolderIconWrapper-1xLaU-::before {
	width: 24px;
	height: 24px;
	position: absolute;
	content: '';
	z-index: 1;
	background: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' name='Folder' aria-hidden='false' width='24' height='24' viewBox='0 0 24 24' style='color: rgb(255,255,255);'%3E%3Cpath fill='currentColor' d='M20 7H12L10.553 5.106C10.214 4.428 9.521 4 8.764 4H3C2.447 4 2 4.447 2 5V19C2 20.104 2.895 21 4 21H20C21.104 21 22 20.104 22 19V9C22 7.896 21.104 7 20 7Z'%3E%3C/path%3E%3C/svg%3E") center/cover no-repeat;
}

.folder-21wGz3 svg[style*="color: rgb(114, 137, 218)"] {
	color: var(--accent) !important;
}

.folderIconWrapper-226oVY[style*="background-color: rgba(114, 137, 218, 0.4);"] {
	background-color: transparent !important;
}

.folderIconWrapper-226oVY[style*="background-color: rgba(114, 137, 218, 0.4);"] .closedFolderIconWrapper-15K9MK::before {
	content: '';
	top: 0;
	left: 0;
	position: absolute;
	width: 100%;
	height: 100%;
	background: var(--accent);
	opacity: .4;
	z-index: -1;
	border-radius:var(--guilds-roundness);
}

.colorPickerSwatch-5GX3Ve.default-cS_caM {
	background-color: var(--accent) !important; /*Changes default folder color to accent*/
}

/*4.e. BetterDiscord Public Servers Button*/

#bd-pub-button {
	background: rgba(255, 255, 255, .1);
	text-transform: capitalize;
	transition: 150ms ease all;
	border-radius: 0;
	color: #fff;
}

#bd-pub-button:hover {
	background: var(--accent);
}

#bd-pub-li {
	margin: 3px 0;
	overflow:visible;
}

/*4.f. Badges and Indicators*/

.upperBadge-2XnnGB {
	z-index:0;
}

.lowerBadge-29hYVK {
	z-index:1;
}

.unavailableBadge-3k7iq_ .icon-3s6X1M {
	color:var(--danger);
}

.numberBadge-2s8kKX {
	background: var(--danger) !important;
	border-radius: 0;
	padding:4px 2px !important;
	height: 12px;
	position:relative;
	font-size:var(--size2);
}

.wrapper-1Rf91z .numberBadge-2s8kKX {
	top:5px;
	left:5px;
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv .tutorialContainer-1v44GL .listItem-2P_4kh:first-child .numberBadge-2s8kKX {
	position: absolute;
	transform: scale(.82);
	top: -31px;
	left: -20px;
	box-shadow: 0 0 0 4px rgba(255, 255, 255, .07), 0 0 0 4px var(--lv1) !important;
}

.wrapper-sa6paO {
	height: 40px;
	margin: 0;
}

.item-2hkk8m {
	border-radius: 0;
	opacity: 1 !important;
	background: var(--accent);
	max-height:28px;
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv .tutorialContainer-1v44GL .listItem-2P_4kh:first-child .wrapper-1BJsBx {
	height: 43px;
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv .tutorialContainer-1v44GL .listItem-2P_4kh:first-child .pill-2uzAFe {
	display: none;
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv .tutorialContainer-1v44GL .listItem-2P_4kh:first-child .upperBadge-2XnnGB {
	top: 20px;
}

.downloadProgress-3lBtPV {
	background: var(--lv1);
	border-radius: 50px;
}

.circleOverlay-2WHDjO svg {
	padding: 0;
	width: 12px;
	height: 12px;
	margin-top: 4px;
}

.circleBackground-OqqxHM,
.circleBackgroundAlt-Eohdst {
	fill: rgba(255, 255, 255, .1);
}

.circleProgress-1EBmVn {
	stroke: var(--accent);
}

.iconBadge-2wi9r4,
.unavailableBadge-3k7iq_ {
	position: absolute;
	top: 0;
	left: -40px;
	width: 40px;
	height: 40px;
	background: rgba(0, 0, 0, .5) !important;
	border-radius: var(--guilds-roundness);
}

.icon-3s6X1M {
	width: 24px;
	color: rgba(255, 255, 255, .5);
}

/*5. Channels Sidebar*/

/*5.a. Outer Sidebar Containers*/

.sidebar-2K8pFh {
	border-radius:0 !important;
}

.sidebar-2K8pFh {
	width: 265px;
}

.base-3dtUhz,
.sidebar-2K8pFh {
	overflow: visible !important;
}

/*5.b. Channel Guild Header*/

#app-mount .header-2o-2hj {
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07);
	height: 40px;
	border-bottom: 2px solid var(--hover);
	box-sizing: border-box;
	background: var(--lv1);
	overflow: hidden;
}

.header-2o-2hj:hover::before {
	opacity: .25;
	transform: scale(16);
}

.header-2o-2hj::before {
	content: '';
	position: absolute;
	pointer-events: none;
	top: 0;
	left: 0;
	transform: scale(0);
	border-radius: 50px;
	width: 50px;
	height: 50px;
	z-index: -1;
	opacity: 0;
	background: var(--hover);
	transition: fadeIn .25s ease, transform .5s ease;
}

.header-2o-2hj:active::before {
	background: var(--accent);
}

.name-3YKhmS {
	font-weight: 500;
	font-size:var(--size1);
}

.header-2o-2hj::after {
	font-family: "Segoe MDL2 Assets";
	font-size: var(--sizelg);
	content: "";
	display: flex;
	justify-content: center;
	align-items: center;
	height: 40px;
}

.button-1w5pas {
	display: none;
}

.flowerStar-1GeTsn path {
	fill: var(--accent);	
}

.iconTierNone-3xOaeG {
	color:#fff;
}

/*5.b.a. Server Banners*/

.animatedContainer-1pJv5C {
	-webkit-mask: linear-gradient(black 50%, transparent);
}

.bannerImage-1jOskm {
	width: 100%;
	margin-top: 40px
}

/*5.c. Account Details Container*/

.container-3baos1 {
	width: calc(60px + 265px);
	margin-left: -60px;
	background: var(--lv1);
	z-index: 1000;
	bottom: 0;
	box-shadow:	inset 0 0 0 100vmax rgba(255, 255, 255, .07),0 -10px 10px -10px var(--lv1);
	height:50px !important;
	margin-bottom:0;
	box-sizing:border-box;
	padding:0 10px;
	--status-color:var(--accent);
}

.panels-j1Uci_ .container-3baos1:not(.powercord-spotify) .flex-1O1GKY {
	width: 190px;
	justify-content: center;
}

.container-3baos1 .wrapper-3t9DeA::before {
	content: '';
	width: 3px;
	height: 50px;
	position: fixed;
	bottom: 0;
	left: 0;
	background: var(--status-color);
	box-shadow: 0 0 25px 1px var(--status-color);
}

#app-mount .container-3baos1 .wrapper-3t9DeA[aria-label*=", Online"] {
	--status-color:var(--success);
}

#app-mount .container-3baos1 .wrapper-3t9DeA[aria-label*=", Idle"] {
	--status-color:var(--caution);
}

#app-mount .container-3baos1 .wrapper-3t9DeA[aria-label*=", Do Not Disturb"] {
	--status-color:var(--danger);
}

#app-mount .container-3baos1 .wrapper-3t9DeA[aria-label*=", Offline"] {
	--status-color:var(--unavailable);
}

#app-mount .container-3baos1 .wrapper-3t9DeA[aria-label*=", Invisible"] {
	--status-color:var(--invisible);
}

#app-mount .container-3baos1 .wrapper-3t9DeA[aria-label*=", Streaming"] {
	--status-color:var(--twitch-purple);
}

.container-3baos1:not(.powercord-spotify) .button-14-BFJ {
	width:100% !important;
	position:relative;
	background: rgba(255, 255, 255, .1);
	margin-left: 5px;
	transition: 150ms ease all;
	border-radius: 0;
	opacity: 1 !important;
	border-bottom: 2px solid rgba(255, 255, 255, .1);
	box-sizing:border-box;
}

.container-3baos1:not(.powercord-spotify) .button-14-BFJ:hover {
	background: rgba(255, 255, 255, .15) !important;
	border-color: var(--accent);
	box-shadow: 0 4px 12px -4px var(--accent);
}

.container-3baos1:not(.powercord-spotify) .button-14-BFJ:active {
	border-bottom-color:var(--accent);
	box-shadow: none;
	color: #fff !important;
}

.container-3baos1 .contents-18-Yxp {
	z-index:1;
}

.container-3baos1 .button-14-BFJ:active:after {
	transform: scaleY(1);
	opacity: 1;
}

.container-3baos1 .button-14-BFJ:after {
	content: '';
	top: 0;
	left: 0;
	width:100%;
	height:100%;
	position:absolute;
	background:var(--accent);
	box-shadow:0 0 12px var(--accent);
	opacity:0;
	transform:scaleY(0);
	transition:150ms ease;
	transform-origin:bottom;
}

.container-3baos1 .button-14-BFJ svg {
	width:24px;
	height:24px;
	margin-top:6px;
	margin-left:6px;
}

.container-3baos1 .button-14-BFJ path[d="M14.99 11C14.99 12.66 13.66 14 12 14C10.34 14 9 12.66 9 11V5C9 3.34 10.34 2 12 2C13.66 2 15 3.34 15 5L14.99 11ZM12 16.1C14.76 16.1 17.3 14 17.3 11H19C19 14.42 16.28 17.24 13 17.72V22H11V17.72C7.72 17.23 5 14.41 5 11H6.7C6.7 14 9.24 16.1 12 16.1Z"],
.container-3baos1 .button-14-BFJ path[d="M11.7237 16.0927L10.9632 16.8531L10.2533 17.5688C10.4978 17.633 10.747 17.6839 11 17.72V22H13V17.72C16.28 17.23 19 14.41 19 11H17.3C17.3 14 14.76 16.1 12 16.1C11.9076 16.1 11.8155 16.0975 11.7237 16.0927Z"] {
	d:path('M7.5 11c1.381 0 2.5-1.119 2.5-2.5v-6c0-1.381-1.119-2.5-2.5-2.5s-2.5 1.119-2.5 2.5v6c0 1.381 1.119 2.5 2.5 2.5zM11 7v1.5c0 1.933-1.567 3.5-3.5 3.5s-3.5-1.567-3.5-3.5v-1.5h-1v1.5c0 2.316 1.75 4.223 4 4.472v2.028h-2v1h5v-1h-2v-2.028c2.25-0.249 4-2.156 4-4.472v-1.5h-1z');
}

.container-3baos1 .button-14-BFJ path[d="M12 2.00305C6.486 2.00305 2 6.48805 2 12.0031V20.0031C2 21.1071 2.895 22.0031 4 22.0031H6C7.104 22.0031 8 21.1071 8 20.0031V17.0031C8 15.8991 7.104 15.0031 6 15.0031H4V12.0031C4 7.59105 7.589 4.00305 12 4.00305C16.411 4.00305 20 7.59105 20 12.0031V15.0031H18C16.896 15.0031 16 15.8991 16 17.0031V20.0031C16 21.1071 16.896 22.0031 18 22.0031H20C21.104 22.0031 22 21.1071 22 20.0031V12.0031C22 6.48805 17.514 2.00305 12 2.00305Z"],
.container-3baos1 .button-14-BFJ path[d="M6.16204 15.0065C6.10859 15.0022 6.05455 15 6 15H4V12C4 7.588 7.589 4 12 4C13.4809 4 14.8691 4.40439 16.0599 5.10859L17.5102 3.65835C15.9292 2.61064 14.0346 2 12 2C6.486 2 2 6.485 2 12V19.1685L6.16204 15.0065Z"] {
	d:path('M4.5 9h-1v7h1c0.275 0 0.5-0.225 0.5-0.5v-6c0-0.275-0.225-0.5-0.5-0.5z M11.5 9c-0.275 0-0.5 0.225-0.5 0.5v6c0 0.275 0.225 0.5 0.5 0.5h1v-7h-1z M16 8c0-4.418-3.582-8-8-8s-8 3.582-8 8c0 0.96 0.169 1.88 0.479 2.732-0.304 0.519-0.479 1.123-0.479 1.768 0 1.763 1.304 3.222 3 3.464v-6.928c-0.499 0.071-0.963 0.248-1.371 0.506-0.084-0.417-0.129-0.849-0.129-1.292 0-3.59 2.91-6.5 6.5-6.5s6.5 2.91 6.5 6.5c0 0.442-0.044 0.874-0.128 1.292-0.408-0.259-0.873-0.435-1.372-0.507v6.929c1.696-0.243 3-1.701 3-3.464 0-0.645-0.175-1.249-0.479-1.768 0.31-0.853 0.479-1.773 0.479-2.732z');
}

.container-3baos1 .button-14-BFJ path[d="M6.16204 15.0065C6.10859 15.0022 6.05455 15 6 15H4V12C4 7.588 7.589 4 12 4C13.4809 4 14.8691 4.40439 16.0599 5.10859L17.5102 3.65835C15.9292 2.61064 14.0346 2 12 2C6.486 2 2 6.485 2 12V19.1685L6.16204 15.0065Z"],
.container-3baos1 .button-14-BFJ path[d="M11.7237 16.0927L10.9632 16.8531L10.2533 17.5688C10.4978 17.633 10.747 17.6839 11 17.72V22H13V17.72C16.28 17.23 19 14.41 19 11H17.3C17.3 14 14.76 16.1 12 16.1C11.9076 16.1 11.8155 16.0975 11.7237 16.0927Z"] {
	color:var(--danger);
}

.strikethrough-1n4ekb,
.container-3baos1 .button-14-BFJ path[d="M19.725 9.91686C19.9043 10.5813 20 11.2796 20 12V15H18C16.896 15 16 15.896 16 17V20C16 21.104 16.896 22 18 22H20C21.105 22 22 21.104 22 20V12C22 10.7075 21.7536 9.47149 21.3053 8.33658L19.725 9.91686Z"],
.container-3baos1 .button-14-BFJ path[d="M14.99 11C14.99 12.66 13.66 14 12 14C10.34 14 9 12.66 9 11V5C9 3.34 10.34 2 12 2C13.66 2 15 3.34 15 5L14.99 11ZM12 16.1C14.76 16.1 17.3 14 17.3 11H19C19 14.42 16.28 17.24 13 17.72V21H11V17.72C7.72 17.23 5 14.41 5 11H6.7C6.7 14 9.24 16.1 12 16.1ZM12 4C11.2 4 11 4.66667 11 5V11C11 11.3333 11.2 12 12 12C12.8 12 13 11.3333 13 11V5C13 4.66667 12.8 4 12 4Z"],
.container-3baos1 .button-14-BFJ path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"],
.container-3baos1 .button-14-BFJ path[d="M9.01 11.085C9.015 11.1125 9.02 11.14 9.02 11.17L15 5.18V5C15 3.34 13.66 2 12 2C10.34 2 9 3.34 9 5V11C9 11.03 9.005 11.0575 9.01 11.085Z"] {
	display:none;
}

.container-3baos1 .button-14-BFJ path[d="M19.738 10H22V14H19.739C19.498 14.931 19.1 15.798 18.565 16.564L20 18L18 20L16.565 18.564C15.797 19.099 14.932 19.498 14 19.738V22H10V19.738C9.069 19.498 8.203 19.099 7.436 18.564L6 20L4 18L5.436 16.564C4.901 15.799 4.502 14.932 4.262 14H2V10H4.262C4.502 9.068 4.9 8.202 5.436 7.436L4 6L6 4L7.436 5.436C8.202 4.9 9.068 4.502 10 4.262V2H14V4.261C14.932 4.502 15.797 4.9 16.565 5.435L18 3.999L20 5.999L18.564 7.436C19.099 8.202 19.498 9.069 19.738 10ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z"] {
	d:path('M14.59 9.535c-0.839-1.454-0.335-3.317 1.127-4.164l-1.572-2.723c-0.449 0.263-0.972 0.414-1.529 0.414-1.68 0-3.042-1.371-3.042-3.062h-3.145c0.004 0.522-0.126 1.051-0.406 1.535-0.839 1.454-2.706 1.948-4.17 1.106l-1.572 2.723c0.453 0.257 0.845 0.634 1.123 1.117 0.838 1.452 0.336 3.311-1.12 4.16l1.572 2.723c0.448-0.261 0.967-0.41 1.522-0.41 1.675 0 3.033 1.362 3.042 3.046h3.145c-0.001-0.517 0.129-1.040 0.406-1.519 0.838-1.452 2.7-1.947 4.163-1.11l1.572-2.723c-0.45-0.257-0.839-0.633-1.116-1.113zM8 11.24c-1.789 0-3.24-1.45-3.24-3.24s1.45-3.24 3.24-3.24c1.789 0 3.24 1.45 3.24 3.24s-1.45 3.24-3.24 3.24z');
}

.container-3baos1 .button-14-BFJ:active path {
	color:#fff !important;
}

.container-1giJp5 .button-14-BFJ {
	width: 35px;
	height:auto;
	background: transparent !important;
	border: none;	
	box-shadow: none !important;
}

.container-1giJp5 .flex-1O1GKY {
	width: initial;
}

/*5.d. Guild Text Channels*/

@keyframes unread {
	0% {
		box-shadow: 0 0 10px 1px var(--hover);
	}
	50% {
		box-shadow: 0 0 17px 3px var(--hover);
	}
	100% {
		box-shadow: 0 0 10px 1px var(--hover);
	}
}

.containerDefault-1ZnADq, 
.containerDragAfter-1F4fgZ, 
.containerDragBefore-31UGCO, 
.containerUserOver-1U5YnL {
	margin-top:5px;
}

.content-3at_AU {
	border-radius: 0;
	transition: 150ms all ease;
	background: rgba(255, 255, 255, .08);
	padding-bottom: 0;
	height: 27px;
	margin-left: 5px;
	margin-right: 5px;
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .08);
	border-left: 2px solid rgba(255, 255, 255, .1);
}

.wrapper-1ucjTd:hover .content-3at_AU {
	background-color: rgba(255, 255, 255, .15);
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .15);
	border-left: 2px solid rgba(255, 255, 255, .5);
}

.wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU {
	background-color: var(--accent);
	border-radius: 0;
	box-shadow: 0 0 12px 1px var(--accent);
	transition: 150ms all ease;
	height: 30px;
	border-left: 2px solid rgba(255, 255, 255, .8);
}

.modeMuted-3osy7j {
	opacity: .5;
}

#app-mount .modeSelected-1zApJ_ .icon-1_QxNX,
.modeSelected-1zApJ_ .actionIcon-2Hi9ZG,
.wrapper-1ucjTd.modeSelected-1zApJ_ .name-3_Dsmg,
.wrapper-1ucjTd.modeUnread-1zpFdA:hover .name-3_Dsmg {
	color: #fff;
}

.wrapper-1ucjTd.modeLocked-SZJhTy .children-Bmpf2Q {
	order:-1;
	margin-right:6px;
}

.wrapper-1ucjTd.modeLocked-SZJhTy .actionIcon-2Hi9ZG {
	color:#72767d;
}

.wrapper-1ucjTd.modeLocked-SZJhTy:hover .actionIcon-2Hi9ZG {
	color:#fff;
}

.wrapper-1ucjTd.modeLocked-SZJhTy .icon-1_QxNX {
	display:none !important;
}

.icon-1_QxNX {
	width: 18px;
	height: 18px;
}

.actionIcon-2Hi9ZG {
	width:14px;
	height:14px;
}

.actionIcon-2Hi9ZG path[d="M14 2H16V3H14V5H13V3H11V2H13V0H14V2Z"] {
	d:path('M6 11.5c0-2.363 1.498-4.383 3.594-5.159 0.254-0.571 0.406-1.206 0.406-1.841 0-2.485 0-4.5-3-4.5s-3 2.015-3 4.5c0 1.548 0.898 3.095 2 3.716v0.825c-3.392 0.277-6 1.944-6 3.959h6.208c-0.135-0.477-0.208-0.98-0.208-1.5z M11.5 7c-2.485 0-4.5 2.015-4.5 4.5s2.015 4.5 4.5 4.5c2.485 0 4.5-2.015 4.5-4.5s-2.015-4.5-4.5-4.5zM14 12h-2v2h-1v-2h-2v-1h2v-2h1v2h2v1z');
}

.actionIcon-2Hi9ZG path[d="M14 2H16V3H14V5H13V3H11V2H13V0H14V2Z"] ~ path {
	display:none;
}

.wrapper-1ucjTd:not(.modeSelected-1zApJ_):hover .icon-1_QxNX {
	color: #dcddde;
}

.name-3_Dsmg,
.wrapper-1ucjTd.modeUnread-1zpFdA .name-3_Dsmg {
	color: rgba(255, 255, 255, .6);
}

.wrapper-1ucjTd {
	overflow: visible;
	height: 28px;
}

#app-mount .wrapper-1ucjTd:hover .name-3_Dsmg {
	color: #f6f6f6;
}

.name-3_Dsmg {
	transition: 150ms ease;
	font-size:var(--size1);
}

.wrapper-1ucjTd:not(.modeSelected-1zApJ_):hover .name-3_Dsmg {
	padding-left: 5px;
}

.unread-3zKkbm {
	margin-top: 0;
	background: var(--accent);
	border-radius: 0;
	top: 38%;
}

.full-motion .unread-3zKkbm {
	animation:unread 2s ease infinite;
}

.unread-3zKkbm {
	top: 0;
	left: 5px;
	width: 2px;
	height: 100%;
	border-radius: 0;
	transition: 150ms ease opacity;
}

.modeUnread-1zpFdA:hover .unread-3zKkbm {
	opacity: 0;
}

.containerDragAfter-3TEhpe:before,
.containerDragBefore-3Dzc5x:before,
.containerDragAfter-1F4fgZ:after,
.containerDragBefore-31UGCO:before {
	border-radius:0;
	height:2px;
	left:0;
	box-shadow:0 0 12px 1px var(--lv1);
}

.category-2haXBH,
.channelName-2wrHHc,
.channelIcon-1TvDoP {
	border-radius:0;
	background:rgba(255,255,255,0.25);
}

.category-2haXBH,
.channelName-2wrHHc {
	height:4px;
}

/*5.e. Guild Voice Channels*/

.list-2bwCXU {
	padding-left:0;
	margin-top:6px;
}

.listDefault-2y5Z9D .clickable-23RaYz .content-3xS9Lh {
	border-radius: 0;
	transition: 150ms all ease;
	background: rgba(255, 255, 255, .08);
	margin-top: 3px;
	padding-bottom: 0;
	height: 27px;
	margin-left: 5px;
	margin-right: 5px;
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .08);
	border-left: 2px solid rgba(255, 255, 255, .1);
	padding:0 8px;
}

.listDefault-2y5Z9D .clickable-23RaYz:hover .content-3xS9Lh {
	background-color: rgba(255, 255, 255, .15);
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .15);
	border-left: 2px solid rgba(255, 255, 255, .5);
}

.username-lm8y6T {
	font-size:var(--size1);
	transition:150ms ease;
	color:rgba(255, 255, 255, .6);
}

.listDefault-2y5Z9D .clickable-23RaYz:hover .username-lm8y6T {
	color:#f6f6f6;
	padding-left:5px;
}

.listDefault-2y5Z9D .avatarContainer-2inGBK {
	margin:0;
	margin-right:6px;
}

.avatarContainer-2inGBK {
	border-radius:var(--user-roundness);
	width:18px;
	height:18px;
}

.avatar-3bWpYy,
.clickableAvatar-1wQpeh,
.emptyUser-7txhlW {
	border-radius:var(--user-roundness);
}

.avatarContainerMasked-PIJ-3L {
	margin-right:4px;
}

.avatarContainerMasked-PIJ-3L foreignObject {
	mask:none;
}

.wrapper-pZmgj4 {
	font-size:var(--size2);
	border-radius:2px;
	font-weight:600;
}

.users-i_3-kL {
	background:rgba(255,255,255,0.05);
}


/*5.f. Guild Channel Categories*/

.containerDefault-3GGEv_,
.containerDragAfter-3TEhpe,
.containerDragBefore-3Dzc5x,
.containerUserOver-1Tcb7l {
	margin:0 12px;
}

#app-mount .containerDefault-3GGEv_ .collapsed-4WdoJ7 .name-IbjUBS {
	color: rgba(255, 255, 255, .25);
	transition: 250ms color ease;
}

#app-mount .containerDefault-3GGEv_ .collapsed-4WdoJ7 {
	border-color: rgba(255, 255, 255, .25);
}

#app-mount .containerDefault-3GGEv_:hover .collapsed-4WdoJ7 .name-IbjUBS {
	color: rgba(255, 255, 255, .5);
}

#app-mount .collapsed-4WdoJ7:hover {
	border-color: rgba(255, 255, 255, .5);
}

.wrapper-CU3qI5 {
	text-align: left;
	border-image: linear-gradient(90deg, var(--hover) 90%, transparent);
	border-image-slice: 1;
	border-bottom:thin solid;
	margin-bottom: 2px;
	font-size: var(--size2);
	padding:0 4px;
	position:relative;
}

.containerDefault-3GGEv_ .icon-WnO6o2 {
	opacity: 0;
	transition: 350ms ease;
	right:0;
	left:unset;
}

.containerDefault-3GGEv_:hover .icon-WnO6o2 {
	opacity: 1;
}

.collapsed-4WdoJ7 .icon-WnO6o2 {
	transform:rotate(90deg);
}

#app-mount .name-IbjUBS {
	text-align: left;
	color: rgba(255,255,255,0.9);
	font-size: var(--size2);
	font-weight: 400;
	text-transform:none;
	width:fit-content;
	flex:unset;
}

.addButtonIcon-3u-3Hu,
.wrapper-KpKNwI .foreground-2W-aJk {
	opacity: 1;
}

.addButtonIcon-3u-3Hu {
	width:12px;
	height:12px;
}

.addButton-1BORro polygon {
	fill: var(--interactive-normal);
}

#app-mount .containerDefault-3GGEv_ .collapsed-4WdoJ7 .addButton-1BORro polygon {
	fill:rgba(255, 255, 255, .25);
}

#app-mount .containerDefault-3GGEv_ .collapsed-4WdoJ7:hover .addButton-1BORro polygon {
	fill:rgba(255, 255, 255, .5);
}

/*5.g. Call and Other Related Containers*/

@keyframes ping-counter {
	0% {
		transform: scaleY(1);
	}
	50% {
		transform: scaleY(.5);
	}
	100% {
		transform: scaleY(1);
	}
}

.container-1giJp5 {
	height: 20px;
	background: var(--lv1) !important;
	box-shadow: 0 0 12px var(--lv1);
	border-bottom: 2px solid var(--accent);
	order:-1;
	z-index:1000;
}

.rtcConnectionStatus-2-jIsi {
	padding:0;
}

.rtcConnectionStatusConnected-VRZDjy {
	font-size:var(--size1);
}

.active-2h1NLh {
	transform-origin: bottom;
	rx:0;
}

.full-motion .active-2h1NLh {
	animation: ping-counter 1s linear infinite;
}

.active-2h1NLh:nth-child(2) {
	animation-delay: .5s;
}

.active-2h1NLh:nth-child(3) {
	animation-delay: 1s;
}

.container-1giJp5 a .subtext-3CDbHg {
	display:none;
}

.panels-j1Uci_ {
	display:flex;
	flex-direction:column;
	background:var(--lv1);
}

.panel-24C3ux {
	background:rgba(255,255,255,0.07);
	border:none;
	padding:4px 8px;
}

.panel-24C3ux .button-14-BFJ {
	background:transparent !important;
}

.gameIcon-2YB8Et, 
.screenshareIcon-2redWJ {
	width:24px;
	height:24px;
}

/*5.h. Unread Bars*/

.unread-1xRYoj {
	border-radius:0;
}

.text-2e2ZyG {
	font-size:var(--size2);
	text-transform:capitalize;
}

/*5.i. Powercord Spotify Container*/

.powercord-spotify {
  height:fit-content !important;
  padding:8px;
}

.powercord-spotify .button-14-BFJ {
  background:transparent !important;
}

.powercord-spotify .avatar-SmRMf2 {
  border-radius:var(--user-roundness) !important;
}

.powercord-spotify-seek-duration {
  font-size:var(--size2);
}

/*6. Members List Sidebar*/

/*6.a. Outer Sidebar*/

.members-1998pB {
    --bulk: 300px;
    height: calc(100% + var(--bulk));
	padding-bottom: calc(20px + var(--bulk));
	position:relative;
}

.membersWrap-2h-GB4 {
	display:flex;
	flex-direction:column;
}

.membersWrap-2h-GB4,
.membersWrap-2h-GB4 .scroller-2FKFPG {
	width: 265px;
	max-width: unset;
}

.membersWrap-2h-GB4 .scrollerWrap-2lJEkd::after {
	content:'';
	width:100%;
	height:50px;
	box-shadow:0 -10px 10px -10px var(--lv1), inset 0 0 0 100vmax rgba(255,255,255,0.07);
	background:var(--lv1);
	position:absolute;
	bottom:-50px;
	z-index:100;
}
  
.membersWrap-2h-GB4 {
	border-bottom:50px solid rgba(255,255,255,0.07);
}

/*6.b. Member Entries*/

#app-mount .member-3-YXUe {
	border-radius: 0;
	transition: 150ms all ease;
	background: rgba(255, 255, 255, .08);
	padding-bottom: 0;
	height: 30px;
	border-left: 2px solid rgba(255, 255, 255, .1);
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .08);
	max-width: unset;
	min-width:unset;
	width:253px;
	margin-left:5px;
	margin-top: 7px;
	display: flex;
	align-items: center;
	white-space: nowrap;
	cursor:pointer;
	position:relative;
}

.layout-2DM8Md {
	height:100%;
}

.subText-1KtqkB:empty {
	margin:0;
}

.subText-1KtqkB,
.nameAndDecorators-5FJ2dg {
	max-width:200px;
}

#app-mount .member-3-YXUe:hover {
	background-color: rgba(255, 255, 255, .15) !important;
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .15);
	border-left: 2px solid rgba(255, 255, 255, .5);
	padding-left: 5px !important;
}

#app-mount .avatar-3uk_u9,
#app-mount .channel-2QD9_O .wrapper-3t9DeA,
.member-3-YXUe .wrapper-3t9DeA {
	width: 26px !important;
	height: 26px !important;
}

.activity-2Gy-9S {
	font-size:var(--size3);
}

#app-mount .member-3-YXUe.selected-aXhQR6 .activity-2Gy-9S {
	color: #fff;
}

#app-mount .member-3-YXUe.selected-aXhQR6 {
	background-color: var(--accent) !important;
	border-radius: 0;
	cursor: pointer;
	box-shadow: 0 0 12px 1px var(--accent);
	border-left: 2px solid rgba(255, 255, 255, .8);
	height: 58px;
	padding-left: 5px !important;
}

.activity-3mKQ-i {
	text-overflow: ellipsis;
	max-width: 180px;
}

#app-mount .member-3-YXUe .avatar-3uk_u9 {
	margin-bottom: 3px;
}

.clickable-1JJAn8:hover .layout-2DM8Md,
.selected-aXhQR6 .layout-2DM8Md {
	background: transparent;
}

/*6.c. Member Dividers*/

.membersGroup-v9BXpm {
	text-align: left;
	color: rgba(255,255,255,0.9);
	border-image: linear-gradient(90deg, var(--hover) 90%, transparent);
	border-image-slice: 1;
	border-bottom:thin solid;
	margin-bottom: 2px;
	margin:0 12px;
	font-size: var(--size2);
	font-weight: 400;
	padding:0 4px;
	padding-top:16px;
	line-height: 22px;
	text-transform: none;
	height:40px;
	position:relative;
}

/*6.d. Loading Animations*/

.memberGroupsPlaceholder-3mwPub,
.mulitplePlaceholderUsername-pogq9I,
.placeholderAvatar-damqh6,
.placeholderUsername-2B_OA9 {
	border-radius: 0;
	background: rgba(255, 255, 255, .5);
}

.placeholderAvatar-damqh6 {
	width: 20px;
	height: 20px;
}

.placeholderAvatar-damqh6 {
	position: relative;
	border-top: 2px solid rgba(255, 255, 255, .2);
	border-right: 2px solid rgba(255, 255, 255, .2);
	border-bottom: 2px solid rgba(255, 255, 255, .2);
	border-left: 2px solid #fff;
    box-sizing:border-box;
	animation: rotate 1s infinite linear;
	background:transparent;
	border-radius:50%;
}

.mulitplePlaceholderUsername-pogq9I,
.placeholderUsername-2B_OA9,
.memberGroupsPlaceholder-3mwPub {
    height:2px;
    position:relative;
}

.mulitplePlaceholderUsername-pogq9I::after,
.placeholderUsername-2B_OA9::after,
.memberGroupsPlaceholder-3mwPub::after {
	content: '';
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 2px;
	background: #fff;
	box-shadow: 0 0 12px #fff;
	transform-origin: left;
}

.full-motion .mulitplePlaceholderUsername-pogq9I::after,
.full-motion .placeholderUsername-2B_OA9::after,
.full-motion .memberGroupsPlaceholder-3mwPub::after {
	animation: callpulse 2.25s ease infinite;
}

.placeholder-3X_lzF:hover {
	padding-left:13px !important;
}

/*7. Private Channels Sidebar*/

/*7.a. Outer Sidebar*/

.privateChannels-1nO12o .scroller-2FKFPG {
	padding-top: 10px
}

.privateChannels-1nO12o .scroller-2FKFPG div[style*="width: 100%; height: 8px"]:last-child {
	height:75px !important;
	background-image:linear-gradient(var(--lv1) 80%, rgba(255,255,255,0.05));
}

/*7.b. Top Entry Tabs*/

@keyframes home-ripple {
    0% {
        transform:scale(.35) translateX(-50%) translateY(-50%);
        opacity:0;
    }
    100% {
        transform:scale(1) translateX(-50%) translateY(-50%);
        opacity:.15;
    }
}

#app-mount .sidebar-2K8pFh .privateChannels-1nO12o .privateChannelsHeaderContainer-3NB1K1 {
	text-align: left;
	color: rgba(255,255,255,0.9);
	border-image: linear-gradient(90deg, var(--hover) 90%, transparent);
	border-image-slice: 1;
	border-bottom:thin solid;
	margin-bottom: 2px;
	margin:0 12px;
	font-size: var(--size2);
	font-weight: 400;
	padding:0 4px;
	padding-top:16px;
	line-height: 22px;
	text-transform: none;
	position:relative;
	align-items:center;
}

.privateChannelRecipientsInviteButtonIcon-cXLJ7f {
	margin:0;
	width:12px;
	height:12px;
}

#app-mount .channel-2QD9_O[href="/activity"],
#app-mount .channel-2QD9_O[href="/channels/@me"]:not([href="/channels/@me/"]),
#app-mount .channel-2QD9_O[href="/library"],
#app-mount .channel-2QD9_O[href="/store"] {
	display: inline-block;
	transition: 150ms ease all;
	margin-left: 22px;
	margin-top: 0;
	padding: initial;
	width: calc(25% - 10px);
	background: transparent;
	box-shadow: none;
	border: none;
}

#app-mount .channel-2QD9_O[href="/activity"] .layout-2DM8Md,
#app-mount .channel-2QD9_O[href="/channels/@me"]:not([href="/channels/@me/"]) .layout-2DM8Md,
#app-mount .channel-2QD9_O[href="/library"] .layout-2DM8Md,
#app-mount .channel-2QD9_O[href="/store"] .layout-2DM8Md {
	flex-direction: column;
	height: 50px;
	position:relative;
}

#app-mount .channel-2QD9_O[href="/activity"] .avatar-3uk_u9,
#app-mount .channel-2QD9_O[href="/channels/@me"]:not([href="/channels/@me/"]) .avatar-3uk_u9,
#app-mount .channel-2QD9_O[href="/library"] .avatar-3uk_u9,
#app-mount .channel-2QD9_O[href="/store"] .avatar-3uk_u9 {
	margin: 0;
}

#app-mount .channel-2QD9_O.selected-aXhQR6.container-2Pjhx-[href="/activity"],
#app-mount .channel-2QD9_O.selected-aXhQR6.container-2Pjhx-[href="/channels/@me"]:not([href="/channels/@me/"]),
#app-mount .channel-2QD9_O.selected-aXhQR6.container-2Pjhx-[href="/library"],
#app-mount .channel-2QD9_O.selected-aXhQR6.container-2Pjhx-[href="/store"],
#app-mount .channel-2QD9_O[href="/activity"]:hover,
#app-mount .channel-2QD9_O[href="/channels/@me"]:not([href="/channels/@me/"]):hover,
#app-mount .channel-2QD9_O[href="/library"]:hover,
#app-mount .channel-2QD9_O[href="/store"]:hover {
	color: var(--accent);
}

#app-mount .channel-2QD9_O[href="/activity"] .layout-2DM8Md .name-uJV0GL,
#app-mount .channel-2QD9_O[href="/channels/@me"]:not([href="/channels/@me/"]) .layout-2DM8Md .name-uJV0GL,
#app-mount .channel-2QD9_O[href="/library"] .layout-2DM8Md .name-uJV0GL,
#app-mount .channel-2QD9_O[href="/store"] .layout-2DM8Md .name-uJV0GL {
	font-size:var(--size4);
}

.full-motion #app-mount .channel-2QD9_O[href="/activity"] .layout-2DM8Md::after,
.full-motion #app-mount .channel-2QD9_O[href="/channels/@me"]:not([href="/channels/@me/"]) .layout-2DM8Md::after,
.full-motion #app-mount .channel-2QD9_O[href="/library"] .layout-2DM8Md::after,
.full-motion #app-mount .channel-2QD9_O[href="/store"] .layout-2DM8Md::after {
    content:'';
    position:absolute;
    width:60px;
	height:60px;
	top:50%;
	left:50%;
    border-radius:50px;
    background:#fff;
    z-index:0;
    opacity:0;
    transform:scale(0) translateX(-50%) translateY(-50%);
    transform-origin:left top;
}

#app-mount .channel-2QD9_O[href="/activity"] .layout-2DM8Md:active::after,
#app-mount .channel-2QD9_O[href="/channels/@me"]:not([href="/channels/@me/"]) .layout-2DM8Md:active::after,
#app-mount .channel-2QD9_O[href="/library"] .layout-2DM8Md:active::after,
#app-mount .channel-2QD9_O[href="/store"] .layout-2DM8Md:active::after {
    animation:home-ripple .15s ease backwards;
    transform:scale(1) translateX(-50%) translateY(-50%);
    opacity:.15;
}

.channel-2QD9_O .numberBadge-2s8kKX {
	margin-top: -35px;
	margin-left: 5px;
	transform: scale(.75);
	z-index: 1
}

#app-mount .channel-2QD9_O[href="/library"] .downloadProgressCircle-3_wgim {
	opacity:1 !important;
	background:var(--lv1);
}

#app-mount .channel-2QD9_O[href="/library"] .children-gzQq2t {
	top:0;
	position:absolute;
	width:100%;
	height:50%;
}

/*7.c. Channel Entries*/

.channel-2QD9_O.selected-aXhQR6 {
	background-color: var(--accent);
	border-radius: 0;
	margin-top: 7px;
	padding-top: 10px;
	padding-bottom: 10px;
	box-shadow: 0 0 12px 1px var(--accent);
	border-left: 2px solid rgba(255, 255, 255, .8);
}

.channel-2QD9_O {
	border-radius: 0;
	transition: 150ms all ease;
	background: rgba(255, 255, 255, .08);
	margin: 10px;
	margin-right: 2px;
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .08);
	border-left: 2px solid rgba(255, 255, 255, .1);
	max-width:100%;
	height:36px;
}

.channel-2QD9_O:not(.selected-aXhQR6):hover,
.channel-2QD9_O:not(.selected-aXhQR6):active {
	background-color: rgba(255, 255, 255, .15);
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .15);
	border-left: 2px solid rgba(255, 255, 255, .5);
	padding-left: 5px;
}

#app-mount .channel-2QD9_O .wrapper-3t9DeA {
	width: 26px !important;
	height: 26px !important;
}

.channel-2QD9_O.selected-aXhQR6 .activity-3mKQ-i {
	color: #fff;
}

.name-uJV0GL {
	font-size:var(--size1);
}


/*7.d. Search Bubble*/

.privateChannels-1nO12o::before {
	content: 'Home';
	font-weight: 600;
	display:flex;
	align-items:center;
	justify-content:center;
	top: 0;
	color: #fff;
	z-index: 1;
	width:100%;
	font-size:var(--size1);
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07);
	min-height: 40px;
	border-bottom: 2px solid var(--hover);
	box-sizing: border-box;
	background: var(--lv1);
	padding:0 16px;
}

.privateChannels-1nO12o .searchBar-6Kv8R2 {
	position: absolute;
	bottom: 20px;
	right: 20px;
	padding: 0;
	width: 40px;
	height: 40px;
	border-radius:50%;
	box-shadow:0 0 12px var(--lv1) !important;
	background:var(--accent) url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTE1LjUgMTRoLS43OWwtLjI4LS4yN0MxNS40MSAxMi41OSAxNiAxMS4xMSAxNiA5LjUgMTYgNS45MSAxMy4wOSAzIDkuNSAzUzMgNS45MSAzIDkuNSA1LjkxIDE2IDkuNSAxNmMxLjYxIDAgMy4wOS0uNTkgNC4yMy0xLjU3bC4yNy4yOHYuNzlsNSA0Ljk5TDIwLjQ5IDE5bC00Ljk5LTV6bS02IDBDNy4wMSAxNCA1IDExLjk5IDUgOS41UzcuMDEgNSA5LjUgNSAxNCA3LjAxIDE0IDkuNSAxMS45OSAxNCA5LjUgMTR6Ii8+ICAgIDxwYXRoIGQ9Ik0wIDBoMjR2MjRIMHoiIGZpbGw9Im5vbmUiLz48L3N2Zz4=) 50%/45% no-repeat;
	transition: 150ms ease;
	z-index:100;
}

.privateChannels-1nO12o .searchBar-6Kv8R2:hover {
	background-color: var(--hover);
}

.searchBar-6Kv8R2 .searchBarComponent-32dTOx {
	background:transparent;
	font-size:0;
	height:100%;
}

/*8. Chat*/

/*8.a. Outer Chat & Background System*/

@keyframes chatslide {
	from {
		transform: translate(0, -50px);
		opacity: 0;
	}
}

.messages-3amgkR {
	background:transparent;
}

.messagesWrapper-3lZDfY::after {
	content: '';
	position: absolute;
	width: 100%;
	height: 100%;
	z-index: -3001;
	opacity: var(--bg-opacity);
	background-attachment:fixed;
	background: var(--bg) center/cover no-repeat;
	-webkit-mask-image: radial-gradient(black, transparent var(--bg-fade));
}

.full-motion .messagesWrapper-3lZDfY .scrollerWrap-2su1QI {
	animation: chatslide 350ms ease;
}

/*8.b. Messages*/

@keyframes headerBlurDelay {
	0% {
		backdrop-filter:blur(0);
	}
	100% {
		backdrop-filter:blur(10px);
	}
}

.cozy-3raOZG .header-23xsNx {
	padding: 0;
	margin: 0;
	height: 30px;
	background-color: rgba(255, 255, 255, 0.025);
	position: relative;
	display: flex;
	align-items: center;
	z-index:10;
	width:100%;
}

.full-motion .cozy-3raOZG .header-23xsNx {
	animation:headerBlurDelay 0ms ease forwards;
	animation-delay:500ms;
	backdrop-filter: blur(10px);
}

.message-2qnXI6,
.cozy-3raOZG.wrapper-2a6GCs:not(.message-2qnXI6) {
	background: rgba(255, 255, 255, 0.075) !important;
	border-left: 2px solid rgba(255, 255, 255, 0.075) !important;
	margin: 0 20px;
	padding-right:0;
}

.cozy-3raOZG.wrapper-2a6GCs {
	padding-top:0;
	padding-right:0;
}

.cozy-3raOZG.wrapper-2a6GCs,
.cozy-3raOZG .contents-2mQqc9 {
	padding-left:0;
}

.cozy-3raOZG .contents-2mQqc9 {
	margin:0;
}

.groupStart-23k01U .messageContent-2qWWxC {
	padding-top:.25rem;
}

.cozy-3raOZG .messageContent-2qWWxC {
	margin-left:0;
	padding-left:55px;
	padding-bottom:25px;
	font-size:var(--size1) !important;
	max-width:calc(100% - 125px);
	position:relative;
}

.full-motion .cozy-3raOZG .messageContent-2qWWxC {
	animation: transitionIn .35s ease-in-out;
}

.groupStart-23k01U ~ .message-2qnXI6:not(.groupStart-23k01U) .messageContent-2qWWxC {
	top:-25px;
	overflow:visible;
	padding-bottom:0 !important;
}

.cozy-3raOZG + .cozy-3raOZG:not(.groupStart-23k01U) .container-1ov-mD:not(:empty),
.isUnread-3Ef-o9 + .cozy-3raOZG:not(.groupStart-23k01U) .container-1ov-mD:not(:empty) {
    top: -25px;
    position: relative;
    width: 100%;
}

.cozy-3raOZG .contents-2mQqc9 .avatar-1BDn8e {
	z-index:1;
	left: 0;
	margin: 0 10px;
	display: block;
	margin-top: calc(30px + .25em);
	border-radius: var(--user-roundness);
	height: 32px !important;
	width: 32px !important;
	box-shadow: 0 0 0 2px rgba(255, 255, 255, .15);
	transition: 150ms ease box-shadow;
}

.cozy-3raOZG .contents-2mQqc9 .avatar-1BDn8e:hover {
	box-shadow: 0 0 0 2px var(--accent)
}

.cozy-3raOZG .header-23xsNx .username-1A8OIy {
	border-left: 3px solid currentColor;
	height: 30px;
	padding-left: 8px;
	line-height: normal;
	vertical-align: middle;
	display: flex;
	align-items: center;
	box-shadow: inset 10px 0 10px -12px currentColor;
	text-shadow: 0 0 12px currentColor;
	margin-right: 0;
	font-size: var(--size1);
}

#app-mount .header-23xsNx .botTag-2WPJ74 {
	order:0;
	margin-right:0;
	margin-left:4px;
	margin-top:2px;
}

.groupStart-23k01U .markup-2BOw-j {
    padding-bottom: 0;
}

.groupStart-23k01U {
    padding-bottom: 25px !important;
}

.container-1ov-mD {
	margin-left: 55px;
	padding-top:.65rem;
}

.isUnread-3Ef-o9 {
	top: -24px;
	margin: 0 !important;
}

.timestamp-3ZCmNB {
	font-size: var(--size3) !important;
	cursor: text;
}

.avatar-1BDn8e[src*="254362351170617345"] + h2 .timestamp-3ZCmNB::before {
	content: 'Theme Dev';
	text-transform: uppercase;
	font-size: 10px !important;
	font-weight: 500;
	padding: 2px 4px;
	line-height: normal;
	display: inline-block;
	text-align: center;
	white-space: nowrap;
	border: 2px solid #e78e4e;
	border-radius: 1px;
	background: rgba(231, 142, 78, 0.5);
	text-shadow: none;
	color: rgba(255, 255, 255, 0.95);
	position: absolute;
	right: 0px;
	margin: 0 6px;
	top: 50%;
	transform: translateY(-50%);
	cursor: default;
}

.avatar-1BDn8e + h2::after,
#app-mount .avatar-1BDn8e:hover + h2::after {
	left:36px !important;
	bottom:-50px !important;
	font-size:var(--size2) !important;
	border-radius:0;
}

.separator-42rNt0,
.timestamp-3ZCmNB.alt-1uNpEt,
.isUnread-3Ef-o9,
.mentioned-xhSam7:before,
.contents-2mQqc9 .avatar-1BDn8e[src*="402272736665272320"] + h2::before {
	display: none;
}

.wrapper-2aW0bm,
.wrapper-2aW0bm:hover {
	box-shadow: none !important;
	background: transparent !important;
}

.container-3npvBV {
	top: -30px !important;
	background: transparent !important;
}

.button-1ZiXG9:last-child path,
.button-1ZiXG9:nth-last-child(2) path,
.button-1ZiXG9:nth-last-child(3) path {
	display:none;
}

.button-1ZiXG9:last-child {
	background:url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz48c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHdpZHRoPSIxNnB4IiBoZWlnaHQ9IjE2cHgiIHZpZXdCb3g9IjAgMCAxNiAxNiIgdmVyc2lvbj0iMS4xIiBmaWxsPSIjZmZmZmZmIj4gICAgICAgIDx0aXRsZT5pY19vdmVyZmxvd192ZXJ0aWNhbF9ncmV5XzE2cHg8L3RpdGxlPiAgICA8ZGVzYz5DcmVhdGVkIHdpdGggU2tldGNoLjwvZGVzYz4gICAgPGRlZnMvPiAgICA8ZyBpZD0iUGFnZS0xIiBzdHJva2U9Im5vbmUiIHN0cm9rZS13aWR0aD0iMSIgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4gICAgICAgIDxnIGlkPSJpY19vdmVyZmxvd192ZXJ0aWNhbF9ncmV5XzE2cHgiPiAgICAgICAgICAgIDxnIGlkPSJHcm91cC0yMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOC4wMDAwMDAsIDguMDAwMDAwKSByb3RhdGUoOTAuMDAwMDAwKSB0cmFuc2xhdGUoLTguMDAwMDAwLCAtOC4wMDAwMDApICI+ICAgICAgICAgICAgICAgIDxyZWN0IGlkPSJSZWN0YW5nbGUtOCIgeD0iMCIgeT0iMCIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+ICAgICAgICAgICAgICAgIDxnIGlkPSJkb3RzLWhvcml6b250YWwtKDEpIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyLjY2NjY2NywgNi42NjY2NjcpIiBmaWxsPSIjZmZmZmZmIj4gICAgICAgICAgICAgICAgICAgIDxwYXRoIGQ9Ik04LDEuMzMzMzMzMzMgQzgsMC41OTY5NTM2NjcgOC41OTY5NTM2NywwIDkuMzMzMzMzMzMsMCBDMTAuMDY5NzEzLDAgMTAuNjY2NjY2NywwLjU5Njk1MzY2NyAxMC42NjY2NjY3LDEuMzMzMzMzMzMgQzEwLjY2NjY2NjcsMi4wNjk3MTMgMTAuMDY5NzEzLDIuNjY2NjY2NjcgOS4zMzMzMzMzMywyLjY2NjY2NjY3IEM4LjU5Njk1MzY3LDIuNjY2NjY2NjcgOCwyLjA2OTcxMyA4LDEuMzMzMzMzMzMgTDgsMS4zMzMzMzMzMyBaIE00LDEuMzMzMzMzMzMgQzQsMC41OTY5NTM2NjcgNC41OTY5NTM2NywwIDUuMzMzMzMzMzMsMCBDNi4wNjk3MTMsMCA2LjY2NjY2NjY3LDAuNTk2OTUzNjY3IDYuNjY2NjY2NjcsMS4zMzMzMzMzMyBDNi42NjY2NjY2NywyLjA2OTcxMyA2LjA2OTcxMywyLjY2NjY2NjY3IDUuMzMzMzMzMzMsMi42NjY2NjY2NyBDNC41OTY5NTM2NywyLjY2NjY2NjY3IDQsMi4wNjk3MTMgNCwxLjMzMzMzMzMzIEw0LDEuMzMzMzMzMzMgWiBNMCwxLjMzMzMzMzMzIEMwLDAuNTk2OTUzNjY3IDAuNTk2OTUzNjY3LDAgMS4zMzMzMzMzMywwIEMyLjA2OTcxMywwIDIuNjY2NjY2NjcsMC41OTY5NTM2NjcgMi42NjY2NjY2NywxLjMzMzMzMzMzIEMyLjY2NjY2NjY3LDIuMDY5NzEzIDIuMDY5NzEzLDIuNjY2NjY2NjcgMS4zMzMzMzMzMywyLjY2NjY2NjY3IEMwLjU5Njk1MzY2NywyLjY2NjY2NjY3IDAsMi4wNjk3MTMgMCwxLjMzMzMzMzMzIEwwLDEuMzMzMzMzMzMgWiIgaWQ9IlNoYXBlIi8+ICAgICAgICAgICAgICAgIDwvZz4gICAgICAgICAgICA8L2c+ICAgICAgICA8L2c+ICAgIDwvZz48L3N2Zz4=') center/14px no-repeat;
}

.button-1ZiXG9:nth-last-child(2),
.button-1ZiXG9:nth-last-child(3) {
	background:url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz48c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHdpZHRoPSIxNnB4IiBoZWlnaHQ9IjE2cHgiIHZpZXdCb3g9IjAgMCAxNiAxNiIgdmVyc2lvbj0iMS4xIiBmaWxsPSIjZmZmZmZmIj4gICAgICAgIDx0aXRsZT5pY19yZWFjdGlvbnNfZ3JleV8xNnB4PC90aXRsZT4gICAgPGRlc2M+Q3JlYXRlZCB3aXRoIFNrZXRjaC48L2Rlc2M+ICAgIDxkZWZzLz4gICAgPGcgaWQ9IlBhZ2UtMSIgc3Ryb2tlPSJub25lIiBzdHJva2Utd2lkdGg9IjEiIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+ICAgICAgICA8ZyBpZD0iaWNfcmVhY3Rpb25zX2dyZXlfMTZweCI+ICAgICAgICAgICAgPGcgaWQ9Ikdyb3VwLTIiPiAgICAgICAgICAgICAgICA8ZyBpZD0iMDowOjA6MCI+ICAgICAgICAgICAgICAgICAgICA8cmVjdCBpZD0iUmVjdGFuZ2xlLTUiIHg9IjAiIHk9IjAiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIvPiAgICAgICAgICAgICAgICAgICAgPGcgaWQ9ImVtb3RpY29uIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxLjMzMzMzMywgMS4zMzMzMzMpIi8+ICAgICAgICAgICAgICAgICAgICA8cGF0aCBkPSJNMTQuNjMzMjcwNSw3LjMzMzMzMzMzIEMxNC42NTU0MzA0LDcuNTUzODkzODggMTQuNjY2NjY2Nyw3Ljc3NjM2NzY5IDE0LjY2NjY2NjcsOCBDMTQuNjY2NjY2NywxMS42ODE4OTgzIDExLjY4MTg5ODMsMTQuNjY2NjY2NyA4LDE0LjY2NjY2NjcgQzYuMjMxODkwMDcsMTQuNjY2NjY2NyA0LjUzNjE5NzMyLDEzLjk2NDI4NzcgMy4yODU5NTQ3OSwxMi43MTQwNDUyIEMyLjAzNTcxMjI3LDExLjQ2MzgwMjcgMS4zMzMzMzMzMyw5Ljc2ODEwOTkzIDEuMzMzMzMzMzMsOCBDMS4zMzMzMzMzMyw0LjMzMzMzMzMzIDQuMzEzMzMzMzMsMS4zMzMzMzMzMyA4LDEuMzMzMzMzMzMgTDgsMS4zMzMzMzMzMyBDOC4yMjM2MzIzMSwxLjMzMzMzMzMzIDguNDQ2MTA2MTIsMS4zNDQ1Njk2IDguNjY2NjY2NjcsMS4zNjY3Mjk0OSBMOC42NjY2NjY2NywyLjcwODQ3NjkzIEM4LjQ0NjY4OTEyLDIuNjgwNzY3MjIgOC4yMjQwNzE0NiwyLjY2NjY2NjY3IDgsMi42NjY2NjY2NyBDNS4wNTQ0ODEzMywyLjY2NjY2NjY3IDIuNjY2NjY2NjcsNS4wNTQ0ODEzMyAyLjY2NjY2NjY3LDggQzIuNjY2NjY2NjcsMTAuOTQ1NTE4NyA1LjA1NDQ4MTMzLDEzLjMzMzMzMzMgOCwxMy4zMzMzMzMzIEMxMC45NDU1MTg3LDEzLjMzMzMzMzMgMTMuMzMzMzMzMywxMC45NDU1MTg3IDEzLjMzMzMzMzMsOCBDMTMuMzMzMzMzMyw3Ljc3NTkyODU0IDEzLjMxOTIzMjgsNy41NTMzMTA4OCAxMy4yOTE1MjMxLDcuMzMzMzMzMzMgTDE0LjYzMzI3MDUsNy4zMzMzMzMzMyBaIE04LDExLjY2NjY2NjcgQzkuNTUzMzMzMzMsMTEuNjY2NjY2NyAxMC44NjY2NjY3LDEwLjY5MzMzMzMgMTEuNDA2NjY2Nyw5LjMzMzMzMzMzIEw0LjU5MzMzMzMzLDkuMzMzMzMzMzMgQzUuMTI2NjY2NjcsMTAuNjkzMzMzMyA2LjQ0NjY2NjY3LDExLjY2NjY2NjcgOCwxMS42NjY2NjY3IFogTTEwLjMzMzMzMzMsNy4zMzMzMzMzMyBDMTAuODg1NjE4MSw3LjMzMzMzMzMzIDExLjMzMzMzMzMsNi44ODU2MTgwOCAxMS4zMzMzMzMzLDYuMzMzMzMzMzMgQzExLjMzMzMzMzMsNS43ODEwNDg1OCAxMC44ODU2MTgxLDUuMzMzMzMzMzMgMTAuMzMzMzMzMyw1LjMzMzMzMzMzIEM5Ljc4MTA0ODU4LDUuMzMzMzMzMzMgOS4zMzMzMzMzMyw1Ljc4MTA0ODU4IDkuMzMzMzMzMzMsNi4zMzMzMzMzMyBDOS4zMzMzMzMzMyw2Ljg4NTYxODA4IDkuNzgxMDQ4NTgsNy4zMzMzMzMzMyAxMC4zMzMzMzMzLDcuMzMzMzMzMzMgTDEwLjMzMzMzMzMsNy4zMzMzMzMzMyBaIE01LjY2NjY2NjY3LDcuMzMzMzMzMzMgQzYuMjE4OTUxNDIsNy4zMzMzMzMzMyA2LjY2NjY2NjY3LDYuODg1NjE4MDggNi42NjY2NjY2Nyw2LjMzMzMzMzMzIEM2LjY2NjY2NjY3LDUuNzgxMDQ4NTggNi4yMTg5NTE0Miw1LjMzMzMzMzMzIDUuNjY2NjY2NjcsNS4zMzMzMzMzMyBDNS4xMTQzODE5Miw1LjMzMzMzMzMzIDQuNjY2NjY2NjcsNS43ODEwNDg1OCA0LjY2NjY2NjY3LDYuMzMzMzMzMzMgQzQuNjY2NjY2NjcsNi44ODU2MTgwOCA1LjExNDM4MTkyLDcuMzMzMzMzMzMgNS42NjY2NjY2Nyw3LjMzMzMzMzMzIFoiIGlkPSJDb21iaW5lZC1TaGFwZSIgZmlsbD0iI2ZmZmZmZiIvPiAgICAgICAgICAgICAgICA8L2c+ICAgICAgICAgICAgICAgIDxnIGlkPSJHcm91cC0xNSIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTAuNjY2NjY3LCAwLjAwMDAwMCkiIGZpbGw9IiNmZmZmZmYiPiAgICAgICAgICAgICAgICAgICAgPHBvbHlnb24gaWQ9IlBhdGgiIHBvaW50cz0iMy4zMzMzMzMzMyAyIDMuMzMzMzMzMzMgMCAyIDAgMiAyIDAgMiAwIDMuMzMzMzMzMzMgMiAzLjMzMzMzMzMzIDIgNS4zMzMzMzMzMyAzLjMzMzMzMzMzIDUuMzMzMzMzMzMgMy4zMzMzMzMzMyAzLjMzMzMzMzMzIDUuMzMzMzMzMzMgMy4zMzMzMzMzMyA1LjMzMzMzMzMzIDIiLz4gICAgICAgICAgICAgICAgPC9nPiAgICAgICAgICAgIDwvZz4gICAgICAgIDwvZz4gICAgPC9nPjwvc3ZnPg==') center/14px no-repeat;
}

.button-1ZiXG9:nth-last-child(3) + .button-1ZiXG9:nth-last-child(2) {
	background:url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiIHdpZHRoPSIxOHB4IiBoZWlnaHQ9IjE4cHgiPjxwYXRoIGQ9Ik0wIDBoMjR2MjRIMFYweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0zIDE3LjI1VjIxaDMuNzVMMTcuODEgOS45NGwtMy43NS0zLjc1TDMgMTcuMjV6TTUuOTIgMTlINXYtLjkybDkuMDYtOS4wNi45Mi45Mkw1LjkyIDE5ek0yMC43MSA1LjYzbC0yLjM0LTIuMzRjLS4yLS4yLS40NS0uMjktLjcxLS4yOXMtLjUxLjEtLjcuMjlsLTEuODMgMS44MyAzLjc1IDMuNzUgMS44My0xLjgzYy4zOS0uMzkuMzktMS4wMiAwLTEuNDF6Ii8+PC9zdmc+') center/16px no-repeat;
}

.buttonContainer-DHceWr .buttons-cl5qTG .button-1ZiXG9 {
	background-color: transparent;
	top: 0;
	min-height: 16px !important;
	min-width: 20px !important;
	padding:0;
	opacity:.6;
	transition:250ms ease opacity;
}

.buttonContainer-DHceWr .buttons-cl5qTG .button-1ZiXG9:hover {
	opacity:1;
}

.icon-3Gkjwa {
	height: 14px;
	width: 14px;
}

.isHeader-2dII4U {
	top: 28px !important;
}

.beforeGroup-1rH1F0 {
	display: flex !important;
}

.emoji.jumboable {
	width: 2rem;
	height: 2rem;
	margin-right: 2px;
	min-height: unset;
}

.fav {
	background-color:var(--accent);
	border-radius:50px;
	background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0Ij48cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTExLjk5IDJDNi40NyAyIDIgNi40OCAyIDEyczQuNDcgMTAgOS45OSAxMEMxNy41MiAyMiAyMiAxNy41MiAyMiAxMlMxNy41MiAyIDExLjk5IDJ6bTQuMjQgMTZMMTIgMTUuNDUgNy43NyAxOGwxLjEyLTQuODEtMy43My0zLjIzIDQuOTItLjQyTDEyIDVsMS45MiA0LjUzIDQuOTIuNDItMy43MyAzLjIzTDE2LjIzIDE4eiIvPjwvc3ZnPg==);
	background-size:cover;
	background-repeat:no-repeat;
	top:-2px;
	width:12px;
	height:12px;
}

.edited-3sfAzf {
	background: var(--hover);
	width: 13px !important;
	height: 13px !important;
	font-size: 0;
	display: inline-block;
	line-height: 26px;
	margin-left: 5px;
	transition: 150ms ease all;
	-webkit-mask-size: cover;
	-webkit-mask-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IiB3aWR0aD0iNTI4Ljg5OXB4IiBoZWlnaHQ9IjUyOC44OTlweCIgdmlld0JveD0iMCAwIDUyOC44OTkgNTI4Ljg5OSIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTI4Ljg5OSA1MjguODk5OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+PGc+PHBhdGggZD0iTTMyOC44ODMsODkuMTI1bDEwNy41OSwxMDcuNTg5bC0yNzIuMzQsMjcyLjM0TDU2LjYwNCwzNjEuNDY1TDMyOC44ODMsODkuMTI1eiBNNTE4LjExMyw2My4xNzdsLTQ3Ljk4MS00Ny45ODFjLTE4LjU0My0xOC41NDMtNDguNjUzLTE4LjU0My02Ny4yNTksMGwtNDUuOTYxLDQ1Ljk2MWwxMDcuNTksMTA3LjU5bDUzLjYxMS01My42MTFDNTMyLjQ5NSwxMDAuNzUzLDUzMi40OTUsNzcuNTU5LDUxOC4xMTMsNjMuMTc3eiBNMC4zLDUxMi42OWMtMS45NTgsOC44MTIsNS45OTgsMTYuNzA4LDE0LjgxMSwxNC41NjVsMTE5Ljg5MS0yOS4wNjlMMjcuNDczLDM5MC41OTdMMC4zLDUxMi42OXoiLz48L2c+PGc+PC9nPjxnPjwvZz48Zz48L2c+PGc+PC9nPjxnPjwvZz48Zz48L2c+PGc+PC9nPjxnPjwvZz48Zz48L2c+PGc+PC9nPjxnPjwvZz48Zz48L2c+PGc+PC9nPjxnPjwvZz48Zz48L2c+PC9zdmc+);
}

.edited-DL9ECl:hover {
	background: var(--accent)
}

.avatar-VxgULZ {
	border-radius:var(--user-roundness);
}

.message-2qnXI6:not(.groupStart-23k01U) .message-2qnXI6.groupStart-23k01U {
	position:relative;
}

.backgroundFlash-24qWLN {
	background:transparent !important;
	padding-bottom:0 !important;
	margin:0 20px; 
	position:relative;
}

.backgroundFlash-24qWLN .cozy-3raOZG.wrapper-2a6GCs {
	margin:0;
}

.backgroundFlash-24qWLN::after {
	content:'';
	position:absolute;
	top:0;
	left:0;
	width:100%;
	height:100%;
	opacity:.25;
	background: var(--accent) !important;
	transition: background-color .3s ease;
	z-index:-1;
}

/*8.c. Attachments*/

.wrapper-2TxpI8 {
	background:transparent !important;
}

.imageWrapper-2p5ogY {
	box-shadow: 0 3px 7px rgba(0, 0, 0, 0.4);
    transition: 200ms cubic-bezier(0.2, 0, 0, 1) !important;
    background: rgba(255,255,255,0.075);
	border-radius: 0;
}

.full-motion {
	backdrop-filter:blur(10px);
}

.imageWrapper-2p5ogY:hover {
	box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
}

.embedImage-2W1cML img {
	border-radius:0;
}

.attachment-33OFj0 {
	border-radius: 0;
	box-shadow: 0 4px 15px var(--lv1), inset 0 0 1000px rgba(255, 255, 255, .1) !important;
	padding: 15px;
	max-width: 375px;
	border: none !important;
	background: var(--lv1) !important;
	position: relative;
	overflow:hidden;
}

.attachmentInner-3vEpKt::before {
	content: '';
	display: flex;
	position: absolute;
	top:50%;
	transform:translateY(-50%);
	left:0;
	margin-left:10px;
	width: 50px;
	height: 50px;
	background:rgba(255, 255, 255, .05) url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgOTYgOTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDk2IDk2OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSIgZmlsbD0iI2ZmZmZmZiI+CjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+Cgkuc3Qwe2ZpbGw6ICNmZmZmZmY7fQo8L3N0eWxlPgo8ZyBpZD0iWE1MSURfNV8iPgoJPHBhdGggaWQ9IlhNTElEXzlfIiBjbGFzcz0ic3QwIiBkPSJNMzkuMyw2MS4xaDE3LjVWNDMuNmgxMS43TDQ4LDIzLjJMMjcuNiw0My42aDExLjdWNjEuMXogTTI3LjYsNjdoNDAuOHY1LjhIMjcuNlY2N3oiLz4KPC9nPgo8L3N2Zz4K) center/70% no-repeat;
}

.attachmentInner-3vEpKt {
	overflow: visible;
	padding-left:60px;
	width:100%;
	box-sizing:border-box;
}

.icon-1kp3fr {
	display: none;
}

.metadata-3WGS0M {
	color: #fff;
	text-shadow: 0 0 12px;
	margin-top: 5px;
}

.metadata-3WGS0M:before {
	content: 'File Size: ';
	color: rgba(255, 255, 255, .5);
	opacity: 1;
	text-shadow: none;
}

.filenameLinkWrapper-1-14c5 a {
	color: rgba(255, 255, 255, 1) !important;
	text-shadow: none !important;
	font-size: var(--size1);
	font-weight: 500;
	text-decoration: none !important;
}

.attachment-33OFj0 .fileNameLink-9GuxCo::after {
	content: 'Download';
	font-size: 12px;
	transition: 150ms ease;
	background: var(--accent);
	box-shadow: 0 0 12px var(--accent);
	position: absolute;
	padding: 7px 10px;
	bottom: 10px;
	right: 10px;
}

.attachment-33OFj0 .fileNameLink-9GuxCo:hover::after {
	box-shadow: 0 0 12px var(--hover);
	background: var(--hover);
}

.downloadButton-23tKQp {
	display: none;
}

.filenameLinkWrapper-1-14c5 {
	max-width:180px;
	overflow:hidden;
	color: rgba(255, 255, 255, 1) !important;
}

.progressContainer-3ao-eu::before {
	display:none;
}

.filename-3eBB_v {
	max-width:180px;
	color: rgba(255, 255, 255, 1) !important;
	text-shadow: none !important;
	font-size: var(--size1);
	font-weight: 500;
	text-decoration: none !important;
}

.cancelButton-3hVEV6 {
	position:relative;
}

.size-1Arx_I {
	position:static;
}

.small-1CUeBa, 
.xsmall-3czJwD {
	border-radius:0;
	height:4px;
}

.attachment-33OFj0 .progress-3Rbvu0 {
	background:rgba(255,255,255,0.07) !important;
}

.attachment-33OFj0 .small-1CUeBa[style*="rgb(114, 137, 218)"] {
	background:var(--accent) !important;
}

.metadataName-14STf- {
	font-size:var(--size1);
}

.metadataSize-2UOOLK {
	font-size:var(--size3);
}

.durationTimeDisplay-jww5fr, .durationTimeSeparator-2_xpJ7 {
	font-size:var(--size3);
	font-family:var(--font);
}

.fakeEdges-27pgtp:before,
.fakeEdges-27pgtp:after {
	border-radius:0;
}

/*8.d. Embeds, Invites and Gifts*/

.embedFull-2tM8-- {
	border-color: var(--hover);
}

.artwork-1vrmJ_,
.embedImage-2W1cML img, .embedImage-2W1cML video,
.embedThumbnail-2Y84-K img, 
.embedThumbnail-2Y84-K video, 
.embedVideo-3nf0O9 img, 
.embedVideo-3nf0O9 video {
	border-radius:0;
}

.embedFull-2tM8--,
.markup-2BOw-j code.inline,
.wrapper-35wsBm,
#app-mount .invite-18yqGF {
	box-shadow: 0 2px 4px rgba(0, 0, 0, .35);
	background-color: rgba(0, 0, 0, .45);
	backdrop-filter: blur(10px);
	border-left-width: 2px;
	border-radius: 0;
	box-sizing: border-box;
	position: relative;
	overflow: hidden;
}

#app-mount .invite-18yqGF {
	border: none;
}

.guildDetail-1nRKNE {	
	font-size:var(--size2);
}

.partyAvatar-34PPpo {
	margin-right: 10px;
}

#app-mount .chat-3bRxxu .invite-18yqGF .wrapper-3t9DeA,
.partyMemberEmpty-2iyh5g,
.moreUsers-1sZP3U {
	height: 24px !important;
	width: 24px !important;
	border-radius: var(--user-roundness) !important;
}

.avatarMasked-3y6o4j {
	mask: none !important;
	-webkit-mask: none !important;
}

#app-mount .wrapper-35wsBm .guildIconImage-3qTk45 {
	margin-right: 15px !important;
	display: block;
}

.partyMemberEmpty-2iyh5g,
.moreUsers-1sZP3U {
	background: rgba(255, 255, 255, 0.075) !important;
}

.helpIcon-2EyVTp {
	background: rgba(255, 255, 255, 0.075) !important;
	border-radius: 0;
	padding: 4px;
}

.wrapper-35wsBm .lookFilled-1Gx00P.colorGreen-29iAKY {
	box-shadow: none;
}

.wrapper-35wsBm .guildIconImage-3qTk45 {
	overflow: visible;
	position: initial;
}

.partyStatus-6AjDud {
	padding: 0;
}

#app-mount .header-Hg_qNF {
	font-weight: 600;
	color: rgba(255, 255, 255, 0.75);
	font-size:var(--size1);
	text-transform:none;
}

.partyStatus-6AjDud,
.details-3NqflA, 
.state-2dqgON {
	font-size:var(--size2);
	line-height:normal;
}

.wrapper-35wsBm .guildIconImage-3qTk45::after {
	content: '';
	background-image: inherit;
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	z-index: -1;
	opacity: .1;
	filter: blur(15px);
	background-size: 100%;
	background-position: center;
	transition: transform 150ms ease;
}

.wrapper-35wsBm:hover .guildIconImage-3qTk45::after {
	transform: scale(1.15);
}

.guildIconExpired-2Qcq05 {
	display: none;
}

.embedFull-2tM8--[style*="rgb(114, 137, 218)"] {
	border-color: var(--hover) !important;
}

.embedAuthorIcon--1zR3L {
	border-radius:var(--user-roundness);
}

.embedTitle-3OXDkz {
	font-size:var(--size1);
}

.gifTag-31zFY8 {
	border-radius:2px;
	background:var(--lv1);
	display:flex;
	justify-content:center;
	align-items:center;
	box-shadow:0 2px 6px var(--lv1);
}

.gifTag-31zFY8::after {
	content:'GIF';
	color:#fff;
	font-size:var(--size2);
}

/*8.e. Dividers*/

.hasMore-3e72_v,
.divider-JfaTT5:not(.isUnread-3Ef-o9) {
	box-shadow: 0 0 2px 2px rgba(255, 255, 255, .07);
	background:rgba(255,255,255,0.07) !important;
	border-radius:0;
	margin-left:20px;
	margin-right:20px;
	color:#f6f6f7;
	text-transform:capitalize;
}

.full-motion .hasMore-3e72_v,
.full-motion .divider-JfaTT5:not(.isUnread-3Ef-o9) {
	backdrop-filter:blur(10px);
}

.divider-JfaTT5:not(.isUnread-3Ef-o9) {
	border:none;
	width:auto;
	height:auto;
	padding:6px 8px;
}

.divider-JfaTT5 .content-1o0f9g {
	font-size:var(--size2);
	background:transparent;
	color:#f6f6f7;
	margin:0;
}

.welcomeMessage-ULm0mo .itemContainer-1tq6cd,
.placeholder-3PlVv6,
.emptyMessage-3-SPAD.base-19D3Qq {
	display:none;
}

.base-19D3Qq,
.welcomeMessage-ULm0mo {
	border: 2px solid var(--success) !important;
	height: 48px;
	border-radius:2px;
	margin: 15px 20px;
	margin-bottom:0;
	background: rgba(17, 216, 93, .25);
	background-image: none !important;
	box-sizing:border-box;
	align-items:center;
	justify-content:flex-start;
	flex-direction:row;
	padding-bottom:0;
}

.base-19D3Qq .description-wKrf4z {
	font-size:0 !important;
	display:flex;
	flex-grow:1;
	justify-content:flex-end;
	margin:0 15px;
}

.editChannelButton-1dYN-G {
	padding:0;
}

.base-19D3Qq h1,
#app-mount .welcomeMessage-ULm0mo h1 {
	color: #dadada;
	font-weight: 500;
	text-transform: none;
	text-overflow:ellipsis;
	white-space:nowrap;
	overflow:hidden;
	line-height:normal;
	margin:0 15px;
	display:block;
	font-size:var(--size1);
}

#app-mount .welcomeMessage-ULm0mo {
	border-color:#9146FF !important;
	background:rgba(145, 70, 255, .25);
	padding-top:0;
}

#app-mount .welcomeMessage-ULm0mo h1 {
	margin:0;
	max-width:100%;
}

.base-19D3Qq strong {
    margin:0 .1em;
}

.base-19D3Qq h1::before,
#app-mount .welcomeMessage-ULm0mo h1::before {
	content: '  ';
	font-family: 'Segoe MDL2 Assets';
	margin:4px;
}

/*8.f. Textarea*/

@keyframes textarea {
    0% {
        transform:scale(.25);
    }
    100% {
        transform:none;
    }
}

.webkit-HjD9Er .buttons-3JBrkn {
	margin:0;
}

.channelTextArea-rNsIhG {
	padding-top: 0;
	margin-bottom: 0;
	height: unset;
	border: none;
}

.chat-3bRxxu form {
	margin: 0;
	padding:0;
}

.attachWrapper-1_D-pj {
    align-items:center;
    display:flex;
}

.placeholder-37qJjk,
.slateTextArea-1Mkdgw {
	left:5px;
	padding:0 !important;
	font-size:var(--size1);
}

.channelTextAreaDisabled-8rmlrp .scrollableContainer-2NUZem {
	opacity:1;
}

.innerDisabled-1YTFPN::before {
    content:'block';
    color:var(--danger);
    opacity:.4;
    font-family:'Material Icons';
    width:50px;
    height:50px;
    display:flex;
    justify-content:center;
    font-size:22px;
    font-weight:bold;
    align-items:center;
    transition:250ms ease opacity;
}

.innerDisabled-1YTFPN:hover::before {
    opacity:.8;
}

.attachButton-2WznTc {
	opacity: .45;
	background-size: 80%;
	background-position: 50%;
	transform: none !important;
	transition: .2s ease all;
	background-repeat: no-repeat;
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgOTYgOTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDk2IDk2OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSIgZmlsbD0iI2ZmZmZmZiI+CjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+Cgkuc3Qwe2ZpbGw6ICNmZmZmZmY7fQo8L3N0eWxlPgo8ZyBpZD0iWE1MSURfNV8iPgoJPHBhdGggaWQ9IlhNTElEXzlfIiBjbGFzcz0ic3QwIiBkPSJNMzkuMyw2MS4xaDE3LjVWNDMuNmgxMS43TDQ4LDIzLjJMMjcuNiw0My42aDExLjdWNjEuMXogTTI3LjYsNjdoNDAuOHY1LjhIMjcuNlY2N3oiLz4KPC9nPgo8L3N2Zz4K) !important;
}

.attachButton-2WznTc:hover {
	opacity: .9;
}

.attachButton-2WznTc svg {
	visibility: hidden;
}

.textArea-12jD-V {
	margin-bottom: 5px;
	padding: 0;
	padding-top: 14px
}

.inner-MADQqc {
	z-index: 101;
	min-height: 50px
}

.scrollableContainer-2NUZem {
	border-radius: 0;
	background:rgba(255,255,255,0.07) !important;
}

.form-2fGMdU {
    box-shadow: 0 -10px 10px -10px var(--lv1);
}

.form-2fGMdU,
.attachWrapper-1_D-pj{
    border:0;
}

.inner-zqa7da .textArea-2Spzkt {
	transition: 150ms ease border, 150ms ease box-shadow;
	border:none;
}

.characterCount-1cRDo2 {
	font-size:var(--size1);
	font-weight:600;
	background:rgba(255,255,255,0.05);
	border-radius:2px;
	height:fit-content;
	padding:4px 8px;
	bottom:15px;
	box-shadow:0 2px 12px var(--lv1);
	z-index:1000;
}

.full-motion .characterCount-1cRDo2 {
	backdrop-filter:blur(10px);
}

#app-mount .error-1M5Do5 {
	color:var(--danger);
}

.attachWrapper-2TRKBi {
    position:sticky;
    border:none;
    top:10px;
    height:fit-content !important;
    margin-bottom:4px;
}

.slateTextArea-1Mkdgw:focus::before {
    background:var(--accent);
    box-shadow:0 0 12px var(--accent);
    opacity:1;
}

.full-motion .slateTextArea-1Mkdgw:focus::before {
    animation:textarea 250ms ease;
}

.slateTextArea-1Mkdgw::before {
    opacity:0;
    transition:250ms ease opacity;
}

.slateTextArea-1Mkdgw::after {
    transition:150ms ease;
    background:rgba(255, 255, 255, .1);
}

.syntaxAfter-3XEjdd,
.syntaxBefore-lQw8oT {
    color:var(--hover);
}

.slateContainer-3rqVBl {
    position: static;
}

.slateTextArea-1Mkdgw::after,
.slateTextArea-1Mkdgw::before {
    content:'';
    bottom:-8px;
    height:2px;
	width:calc(100% - 4px);
    position:absolute;
    left:0;
}

.placeholder-37qJjk{
	font-size:var(--size1) !important;
    color:rgba(255,255,255,0.36);
}

.message-2qnXI6 .channelTextArea-2VhZ6z {
	margin-left:55px;
	width:calc(100% - 105px);
	border-radius:2px;
	padding-bottom:0;
}

.full-motion .message-2qnXI6 .channelTextArea-2VhZ6z {
	backdrop-filter:blur(10px);
}

.operations-36ENbA {
	padding-left:55px;
	position:relative;
}

.message-2qnXI6 .channelTextArea-2VhZ6z .buttons-3JBrkn {
	margin-right:6px;
}

.wrapper-39oAo3 {
	margin:0;
	padding:15px 0;
	border-radius:0;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.07);
}

.wrapper-39oAo3 .image-3XsqGc {
	display:none;
}

.cozy-3raOZG.wrapper-2a6GCs .slateTextArea-1Mkdgw::after, 
.cozy-3raOZG.wrapper-2a6GCs .slateTextArea-1Mkdgw::before {
	content:none;
}

.cozy-3raOZG.wrapper-2a6GCs .textArea-12jD-V {
	margin:0;
	padding:12px;
	height:100% !important;
	min-height:unset;
}

.cozy-3raOZG.wrapper-2a6GCs .inner-MADQqc {
	min-height:94px;
}

.cozy-3raOZG.wrapper-2a6GCs .placeholder-37qJjk, 
.cozy-3raOZG.wrapper-2a6GCs .slateTextArea-1Mkdgw {
	left:0;
	height:94px;
	position:relative;
}

.cozy-3raOZG.wrapper-2a6GCs .scrollableContainer-2NUZem {
	background:rgba(255,255,255,0.1) !important;
	box-shadow:0 0 4px var(--lv1);
	border-radius:3px;
}

.cozy-3raOZG.wrapper-2a6GCs .webkit-HjD9Er .buttons-3JBrkn {
	margin-top:4px;
}

/*8.g. Codeblocks and Block-Quotes*/

.powercord-codeblock-lang,
.hljs .powercord-lines {
  display:none;
}

.hljs {
	--codeblockcolor: #747f8d;
	position: relative;
	box-sizing: border-box;
	padding-left: 32px !important;
	padding-right: .25em !important;
	padding-bottom: .25em;
	padding-top: 30px !important;
	border-radius: 0;
	border: none !important;
	background: transparent !important;
}

.container-206Blv {
	position: relative;
}

.hljs::before {
	content: 'Unknown Language';
	width: 100%;
	height: 26px;
	top: 0;
	left: 0;
	color: #fff;
	font-size: var(--size3);
	padding: 0 30px;
	line-height: 0;
	position: absolute;
	display: flex;
	align-items: center;
	font-family: var(--font);
	letter-spacing:0;
	background-color: var(--codeblockcolor);
	background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAABkCAMAAABHPGVmAAAA+VBMVEUAAAD///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////9BnGuhAAAAUnRSTlMAAgMEBRobHB0eHyAkJSYnKS0uMzc4OTpFRkdISUpLTFBRUlNUVldYWW9wcXJzdHV2d3p7f4CBh4iJioyNjo+oq8XGx8je3+Hj5Oru9vf4+fr8vTsUbAAAAjdJREFUeAHt2VlPU1EUxfElqGhxEBykUBRwQJECVdGCs0hVpLXd3//DGOLqzbXbuPZ5OImB83/l4ZcTsrKTW5TORKVSabrLbiBfl43dQr7uGruAfD2mMTyHfLWJfEXG3hP5hIx9JPIBGftC5A0y9p3IBvJ1fkTkwWncYtnixjX8vXdEPsN1/SmS2rejudQtzh3ZfpphVGJbpGFUwgaV8BbnTwwqYeNEmY9vkQaVuEEltMWbP2zcHgK9sKpBC5PdMXYR9ZZ/WtXz2DvY8QJcj8ZbnMIfLRybeIs29BabfadEjGboLqYre1bVb8otakUbcota0Ub6XVwUijL8FqWijMXAXdSKMPRd5BZdSzWlGzf0FrXijaXwXdSKNvQWtSINvUWt7IJ1haG26GoNaoo3WnDpLWqFhr8feotxZVcZeotaCf1D3F2ckUjfql4DHasaroAlbtG1MrSqDqAVtUVh7ABa0Vt0rXoD2NGK3qIwtKK3KAynrMa3qIxtIFmZHm/xYarBtgPKJbVFYWhF3EVhxBW5xbWasQWfVvQW10fSALaEIraoDaespW7xiTTYK6sa3MNkB/zTW8B3353DyFtG68Etune0IWp7RW8x0fjXqZwxdhuTLQ+s6iVY7C292egWr36zcZsI1faG3OJsL2ywzd9GI75FKjTiymEjbYuNHo24QiO2RSqH9iz5U5TYovgU9d9+RxVbTE/fxVy5LWZIbFFXftPI0cFp+U2jbDGpKx02hVKpVDoL/QKk+Asua0/jMQAAAABJRU5ErkJggg==) !important;
	background-size: 15px;
	background-position: 8px center;
	background-repeat: no-repeat;
	border-top: 2px solid rgba(255, 255, 255, 0.1);
	box-shadow: 0 0 12px rgba(0, 0, 0, 0.5);
	box-sizing: border-box;
}

.markup-2BOw-j pre {
	position: relative;
	overflow: hidden;
	margin-bottom: 5px;
	border-radius: 0;
	box-shadow: 0 0 2px 2px rgba(0, 0, 0, .1);
	background-color: rgba(0, 0, 0, .25);
	backdrop-filter: blur(10px);
}

.markup-2BOw-j pre:before {
	content: "1\a 2\a 3\a 4\a 5\a 6\a 7\a 8\a 9\a 10\a 11\a 12\a 13\a 14\a 15\a 16\a 17\a 18\a 19\a 20\a 21\a 22\a 23\a 24\a 25\a 26\a 27\a 28\a 29\a 30\a 31\a 32\a 33\a 34\a 35\a 36\a 37\a 38\a 39\a 40\a 41\a 42\a 43\a 44\a 45\a 46\a 47\a 48\a 49\a 50\a 51\a 52\a 53\a 54\a 55\a 56\a 57\a 58\a 59\a 60\a 61\a 62\a 63\a 64\a 65\a 66\a 67\a 68\a 69\a 70\a 71\a 72\a 73\a 74\a 75\a 76\a 77\a 78\a 79\a 80\a 81\a 82\a 83\a 84\a 85\a 86\a 87\a 88\a 89\a 90\a 91\a 92\a 93\a 94\a 95\a 96\a 97\a 98\a 99\a 100\a 101\a 102\a 103\a 104\a 105\a 106\a 107\a 108\a 109\a 110\a 111\a 112\a 113\a 114\a 115\a 116\a 117\a 118\a 119\a 120\a 121\a 122\a 123\a 124\a 125\a 126\a 127\a 128\a 129\a 130\a 131\a 132\a 133\a 134\a 135\a 136\a 137\a 138\a 139\a 140\a 141\a 142\a 143\a 144\a 145\a 146\a 147\a 148\a 149\a 150\a 151\a 152\a 153\a 154\a 155\a 156\a 157\a 158\a 159\a 160\a 161\a 162\a 163\a 164\a 165\a 166\a 167\a 168\a 169\a 170\a 171\a 172\a 173\a 174\a 175\a 176\a 177\a 178\a 179\a 180\a 181\a 182\a 183\a 184\a 185\a 186\a 187\a 188\a 189\a 190\a 191\a 192\a 193\a 194\a 195\a 196\a 197\a 198\a 199\a 200\a 201\a 202\a 203\a 204\a 205\a 206\a 207\a 208\a 209\a 210\a 211\a 212\a 213\a 214\a 215\a 216\a 217\a 218\a 219\a 220\a 221\a 222\a 223\a 224\a 225\a 226\a 227\a 228\a 229\a 230\a 231\a 232\a 233\a 234\a 235\a 236\a 237\a 238\a 239\a 240\a 241\a 242\a 243\a 244\a 245\a 246\a 247\a 248\a 249\a 250\a 251\a 252\a 253\a 254\a 255\a 256\a 257\a 258\a 259\a 260\a 261\a 262\a 263\a 264\a 265\a 266\a 267\a 268\a 269\a 270\a 271\a 272\a 273\a 274\a 275\a 276\a 277\a 278\a 279\a 280\a 281\a 282\a 283\a 284\a 285\a 286\a 287\a 288\a 289\a 290\a 291\a 292\a 293\a 294\a 295\a 296\a 297\a 298\a 299\a 300\a 301\a 302\a 303\a 304\a 305\a 306\a 307\a 308\a 309\a 310\a 311\a 312\a 313\a 314\a 315\a 316\a 317\a 318\a 319\a 320\a 321\a 322\a 323\a 324\a 325\a 326\a 327\a 328\a 329\a 330\a 331\a 332\a 333\a 334\a 335\a 336\a 337\a 338\a 339\a 340\a 341\a 342\a 343\a 344\a 345\a 346\a 347\a 348\a 349\a 350\a 351\a 352\a 353\a 354\a 355\a 356\a 357\a 358\a 359\a 360\a 361\a 362\a 363\a 364\a 365\a 366\a 367\a 368\a 369\a 370\a 371\a 372\a 373\a 374\a 375\a 376\a 377\a 378\a 379\a 380\a 381\a 382\a 383\a 384\a 385\a 386\a 387\a 388\a 389\a 390\a 391\a 392\a 393\a 394\a 395\a 396\a 397\a 398\a 399\a 400\a 401\a 402\a 403\a 404\a 405\a 406\a 407\a 408\a 409\a 410\a 411\a 412\a 413\a 414\a 415\a 416\a 417\a 418\a 419\a 420\a 421\a 422\a 423\a 424\a 425\a 426\a 427\a 428\a 429\a 430\a 431\a 432\a 433\a 434\a 435\a 436\a 437\a 438\a 439\a 440\a 441\a 442\a 443\a 444\a 445\a 446\a 447\a 448\a 449\a 450\a 451\a 452\a 453\a 454\a 455\a 456\a 457\a 458\a 459\a 460\a 461\a 462\a 463\a 464\a 465\a 466\a 467\a 468\a 469\a 470\a 471\a 472\a 473\a 474\a 475\a 476\a 477\a 478\a 479\a 480\a 481\a 482\a 483\a 484\a 485\a 486\a 487\a 488\a 489\a 490\a 491\a 492\a 493\a 494\a 495\a 496\a 497\a 498\a 499\a 500\a 501\a 502\a 503\a 504\a 505\a 506\a 507\a 508\a 509\a 510\a 511\a 512\a 513\a 514\a 515\a 516\a 517\a 518\a 519\a 520\a 521\a 522\a 523\a 524\a 525\a 526\a 527\a 528\a 529\a 530\a 531\a 532\a 533\a 534\a 535\a 536\a 537\a 538\a 539\a 540\a 541\a 542\a 543\a 544\a 545\a 546\a 547\a 548\a 549\a 550\a 551\a 552\a 553\a 554\a 555\a 556\a 557\a 558\a 559\a 560\a 561\a 562\a 563\a 564\a 565\a 566\a 567\a 568\a 569\a 570\a 571\a 572\a 573\a 574\a 575\a 576\a 577\a 578\a 579\a 580\a 581\a 582\a 583\a 584\a 585\a 586\a 587\a 588\a 589\a 590\a 591\a 592\a 593\a 594\a 595\a 596\a 597\a 598\a 599\a 600\a 601\a 602\a 603\a 604\a 605\a 606\a 607\a 608\a 609\a 610\a 611\a 612\a 613\a 614\a 615\a 616\a 617\a 618\a 619\a 620\a 621\a 622\a 623\a 624\a 625\a 626\a 627\a 628\a 629\a 630\a 631\a 632\a 633\a 634\a 635\a 636\a 637\a 638\a 639\a 640\a 641\a 642\a 643\a 644\a 645\a 646\a 647\a 648\a 649\a 650\a 651\a 652\a 653\a 654\a 655\a 656\a 657\a 658\a 659\a 660\a 661\a 662\a 663\a 664\a 665\a 666\a 667\a 668\a 669\a 670\a 671\a 672\a 673\a 674\a 675\a 676\a 677\a 678\a 679\a 680\a 681\a 682\a 683\a 684\a 685\a 686\a 687\a 688\a 689\a 690\a 691\a 692\a 693\a 694\a 695\a 696\a 697\a 698\a 699\a 700\a 701\a 702\a 703\a 704\a 705\a 706\a 707\a 708\a 709\a 710\a 711\a 712\a 713\a 714\a 715\a 716\a 717\a 718\a 719\a 720\a 721\a 722\a 723\a 724\a 725\a 726\a 727\a 728\a 729\a 730\a 731\a 732\a 733\a 734\a 735\a 736\a 737\a 738\a 739\a 740\a 741\a 742\a 743\a 744\a 745\a 746\a 747\a 748\a 749\a 750\a 751\a 752\a 753\a 754\a 755\a 756\a 757\a 758\a 759\a 760\a 761\a 762\a 763\a 764\a 765\a 766\a 767\a 768\a 769\a 770\a 771\a 772\a 773\a 774\a 775\a 776\a 777\a 778\a 779\a 780\a 781\a 782\a 783\a 784\a 785\a 786\a 787\a 788\a 789\a 790\a 791\a 792\a 793\a 794\a 795\a 796\a 797\a 798\a 799\a 800\a 801\a 802\a 803\a 804\a 805\a 806\a 807\a 808\a 809\a 810\a 811\a 812\a 813\a 814\a 815\a 816\a 817\a 818\a 819\a 820\a 821\a 822\a 823\a 824\a 825\a 826\a 827\a 828\a 829\a 830\a 831\a 832\a 833\a 834\a 835\a 836\a 837\a 838\a 839\a 840\a 841\a 842\a 843\a 844\a 845\a 846\a 847\a 848\a 849\a 850\a 851\a 852\a 853\a 854\a 855\a 856\a 857\a 858\a 859\a 860\a 861\a 862\a 863\a 864\a 865\a 866\a 867\a 868\a 869\a 870\a 871\a 872\a 873\a 874\a 875\a 876\a 877\a 878\a 879\a 880\a 881\a 882\a 883\a 884\a 885\a 886\a 887\a 888\a 889\a 890\a 891\a 892\a 893\a 894\a 895\a 896\a 897\a 898\a 899\a 900\a 901\a 902\a 903\a 904\a 905\a 906\a 907\a 908\a 909\a 910\a 911\a 912\a 913\a 914\a 915\a 916\a 917\a 918\a 919\a 920\a 921\a 922\a 923\a 924\a 925\a 926\a 927\a 928\a 929\a 930\a 931\a 932\a 933\a 934\a 935\a 936\a 937\a 938\a 939\a 940\a 941\a 942\a 943\a 944\a 945\a 946\a 947\a 948\a 949\a 950\a 951\a 952\a 953\a 954\a 955\a 956\a 957\a 958\a 959\a 960\a 961\a 962\a 963\a 964\a 965\a 966\a 967\a 968\a 969\a 970\a 971\a 972\a 973\a 974\a 975\a 976\a 977\a 978\a 979\a 980\a 981\a 982\a 983\a 984\a 985\a 986\a 987\a 988\a 989\a 990\a 991\a 992\a 993\a 994\a 995\a 996\a 997\a 998\a 999\a";
	width: 20px;
	padding: 0 4px;
	position: absolute;
	left: 0;
	text-align: right;
	padding-top: 30px;
	line-height: 1.125rem;
	height: calc(100% - 30px);
	overflow: hidden;
	color: rgba(255, 255, 255, 0.75);
	box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);
	background: rgba(255, 255, 255, 0.05);
}

.hljs[class$="hljs"]::before {
	content: 'Plain Text';
}

.hljs[class~=diff i]::before {
	content: "Diff";
	--codeblockcolor: #81c529;
}

.hljs[class~=cs i]::before,
.hljs[class~=csharp i]::before {
	content: "C#";
	--codeblockcolor: #f4b41c;
}

.hljs[class~=ini i]::before {
	content: "Initialization File";
	--codeblockcolor: #5d91ff;
}

.hljs[class~=autohotkey i]::before {
	content: "AutoHotkey";
	--codeblockcolor: #dc5159;
}

.hljs[class~=asciidoc i]::before {
	content: "Ascii";
	--codeblockcolor: #5c87e2;
}

.hljs[class~=TOML i]::before {
	content: "TOML";
	--codeblockcolor: #30088f;
}

.hljs[class~=nginx i]::before {
	content: "NGINX";
	--codeblockcolor: #4bd1a9;
}

.hljs[class~=perl i]::before {
	content: "Perl";
	--codeblockcolor: #a462d0;
}

.hljs[class~=d i]::before {
	content: "d";
	--codeblockcolor: #B03931;
}

.hljs[class~=javascript i]::before,
.hljs[class~=js i]::before {
	content: "Javascript";
	--codeblockcolor: #165eab;
}

.hljs[class~=css i]::before {
	content: "Cascading Style Sheet";
	--codeblockcolor: #1973d3;
}

.hljs[class~=bash i]::before {
	content: "Bash";
	--codeblockcolor: #ab1663;
}

.hljs[class~=markdown i]::before,
.hljs[class~=md i]::before {
	content: "Markdown";
	--codeblockcolor: #ab2e16;
}

.hljs[class~=html i]::before {
	content: "HTML";
	--codeblockcolor: #f16529
}

.hljs[class~=xl i]::before {
	content: "eXtensible Language";
	--codeblockcolor: #16ab6f;
}

.hljs[class~=coffee i]::before {
	content: "CoffeeScript";
	--codeblockcolor: #3a1b1b;
}

.hljs[class~=ruby i]::before {
	content: "Ruby";
	--codeblockcolor: #e73e3e;
}

.hljs[class~=sql i]::before {
	content: "SQL";
	--codeblockcolor: #4474ca;
}

.hljs[class~=java i]::before {
	content: "Java";
	--codeblockcolor: #eb2d2f;
}

.hljs[class~=py i]::before,
.hljs[class~=python i]::before {
	content: "Python";
	--codeblockcolor: #eb2d2f;
}

.hljs[class~=vb i]::before,
.hljs[class~=visualbasic i]::before,
.hljs[class~=vbs i]::before {
	content: "Visual Basic";
	--codeblockcolor: #839700;
}

.hljs[class~=lua i]::before {
	content: "Lua";
	--codeblockcolor: #2ecc71;
}

.hljs[class~=php i]::before {
	content: "Php";
	--codeblockcolor: #6e81b6;
}

.hljs[class~=swift i]::before {
	content: "Swift";
	--codeblockcolor: #fd7837;
}

.hljs[class~=makefile i]::before {
	content: "Makefile";
	--codeblockcolor: #8a2b0f;
}

.hljs[class~=go i]::before {
	content: "Go";
	--codeblockcolor: #75cede;
}

.hljs[class~=rust i]::before {
	content: "Rust";
	--codeblockcolor: #000000;
}

.hljs[class~=prolog i]::before {
	content: "Prolog";
	--codeblockcolor: #ef4d25;
}

.hljs[class~=ts i]::before,
.hljs[class~=typescript i]::before {
	content: "TypeScript";
	--codeblockcolor: #03324c;
}

.hljs[class~=http i]::before {
	content: "HyperText Transfer Protocol";
	--codeblockcolor: #618f10;
}

.hljs[class~=json i]::before {
	content: "JSON";
	--codeblockcolor: #108f66;
}

.hljs[class~=xml i]::before {
	content: "XML";
	--codeblockcolor: #8444af;
}

.hljs[class~=less i]::before {
	content: "Less";
	--codeblockcolor: #1d365d;
}

.hljs[class~=sass i]::before,
.hljs[class~=scss i]::before {
	content: "SCSS";
	--codeblockcolor: #bf4080;
}

.hljs[class~=elm i]::before {
	content: "Elm";
	--codeblockcolor: #50d4ee;
}

.hljs[class~=cpp i]::before {
	content: "C++";
	--codeblockcolor: #99182E;
}

.hljs[class~=hbs i]::before {
	content: "Handlebars";
	--codeblockcolor: #f0772b;
}

.hljs[class~=1c i]::before {
	content: "1c";
	--codeblockcolor: #703B30;
}

.hljs[class~=abnf i]::before {
	content: "ABNF";
	--codeblockcolor: #227A70;
}

.hljs[class~=clojure i]::before {
	content: "Clojure";
	--codeblockcolor: #5cc70c;
}

.hljs[class~=objc i]::before {
	content: "Objective-C";
	--codeblockcolor: #0092db;
}

.hljs[class~=yaml i]::before {
	content: "YAML";
	--codeblockcolor: #0295a5;
}

.hljs[class~=shell i]::before,
.hljs[class~=sh i]::before {
	content: "Shell";
	--codeblockcolor: #99b9f9;
}

.hljs[class~=kotlin i]::before {
	content: "Kotlin";
	--codeblockcolor: #497bbc;
}

.hljs[class~=apache i]::before {
	content: "Apache";
	--codeblockcolor: #402a72;
}

.hljs[class~=stylus i]::before {
	content: "Stylus";
	--codeblockcolor: #8205b4;
}

.hljs[class~=avrasm i]::before {
	content: "AVR Assembler";
	--codeblockcolor: #8205b4;
}

.hljs[class~=llvm i]::before {
	content: "LLVM IR";
	--codeblockcolor: #0014a5;
}

.hljs[class~=mipsasm i]::before {
	content: "MIPS Assembly";
	--codeblockcolor: #fc6675;
}

.hljs[class~=x86asm i]::before {
	content: "Intel x86 Assembly";
	--codeblockcolor: #0071c5;
}

.hljs[class~=crmsh i]::before {
	content: "crmsh";
	--codeblockcolor: #be0078;
}

.hljs[class~=dns i]::before {
	content: "DNS Zone File";
	--codeblockcolor: #00c704;
}

.hljs[class~=dockerfile i]::before {
	content: "Dockerfile";
	--codeblockcolor: #c70000;
}

.hljs[class~=dsconfig i]::before {
	content: "dsconfig";
	--codeblockcolor: #2cb0cc;
}

.hljs[class~=jboss-cli i]::before {
	content: "jboss-cli";
	--codeblockcolor: #e2bb88;
}

.hljs[class~=ldif i]::before {
	content: "LDIF";
	--codeblockcolor: #a32ec5;
}

.hljs[class~="pf.conf" i]::before {
	content: "pf.conf";
	--codeblockcolor: #ff845e;
}

.hljs[class~="puppet" i]::before {
	content: "Puppet";
	--codeblockcolor: #804d7f;
}

.hljs[class~="roboconf" i]::before {
	content: "Roboconf";
	--codeblockcolor: #81150e;
}

.hljs[class~="axapta" i]::before {
	content: "Microsoft Dynamics AX";
	--codeblockcolor: #8c7e8d;
}

.hljs[class~="cos" i]::before {
	content: "Caché Object Script";
	--codeblockcolor: #47553c;
}

.hljs[class~="isbl" i]::before {
	content: "ISBL";
	--codeblockcolor: #a6e3d9;
}

.hljs[class~="livecodeserver" i]::before {
	content: "LiveCode";
	--codeblockcolor: #aad036;
}

.hljs[class~="ldif" i]::before {
	content: "LDIF";
	--codeblockcolor: #3e04c1;
}

.hljs[class~="ruleslanguage" i]::before {
	content: "Oracle Rules Language";
	--codeblockcolor: #010640;
}

.hljs[class~="clean" i]::before {
	content: "Clean";
	--codeblockcolor: #f51b70;
}

.hljs[class~="coq" i]::before {
	content: "Coq";
	--codeblockcolor: #40deb2;
}

.hljs[class~="elixir" i]::before {
	content: "Elixir";
	--codeblockcolor: #fc3cf1;
}

.hljs[class~="erlang-repl" i]::before {
	content: "Erlang REPL";
	--codeblockcolor: #a8c348;
}

.hljs[class~="erlang" i]::before {
	content: "Erlang";
	--codeblockcolor: #611cfb;
}

.hljs[class~="flix" i]::before {
	content: "Flix";
	--codeblockcolor: #e50914;
}

.hljs[class~="fsharp" i]::before,
.hljs[class~="fs" i]::before {
	content: "F#";
	--codeblockcolor: #6f1023;
}

.hljs[class~="haskell" i]::before {
	content: "Haskell";
	--codeblockcolor: #a213ad;
}

.hljs[class~="ocaml" i]::before {
	content: "OCaml";
	--codeblockcolor: #34a3a3;
}

.hljs[class~="scala" i]::before {
	content: "Scala";
	--codeblockcolor: #e00000;
}

.hljs[class~="sml" i]::before {
	content: "SML (Standard ML)";
	--codeblockcolor: #3d59b1;
}

.hljs[class~="xquery" i]::before {
	content: "XQuery";
	--codeblockcolor: #a64fe3;
}

.hljs[class~="glsl" i]::before {
	content: "GLSL";
	--codeblockcolor: #353771;
}

.hljs[class~="mel" i]::before {
	content: "MEL";
	--codeblockcolor: #367e3e;
}

.hljs[class~="processing" i]::before {
	content: "Processing";
	--codeblockcolor: #04a8a7;
}

.hljs[class~="rib" i]::before {
	content: "RenderMan RIB";
	--codeblockcolor: #e2cc08;
}

.hljs[class~="rsl" i]::before {
	content: "RenderMan RSL";
	--codeblockcolor: #77a805;
}

.hljs[class~="armasm" i]::before {
	content: "Arm Assembly";
	--codeblockcolor: #b44142;
}

.hljs[class~="asm" i]::before,
.hljs[class~="assembly" i]::before {
	content: "Assembly";
	--codeblockcolor: #25344c;
}

.hljs-selector-tag {
	color: #b2ccd6 !important;
}

.hljs-selector-class {
	color: #ffcb6b !important;
}

.hljs-attr,
.hljs-keyword,
.hljs-meta,
.hljs-selector-id {
	color: #c792ea !important;
}

.hljs-selector-attr {
	color: #89ddf3 !important;
}

.hljs-attribute,
.hljs-doctag,
.hljs-literal,
.hljs-meta-string,
.hljs-regexp,
.hljs-selector-pseudo {
	color: #73d1c8 !important;
}

.hljs-number {
	color: #ffe082 !important;
}

.hljs-bullet,
.hljs-subst,
.hljs-symbol,
.hljs-template-variable,
.hljs-type,
.hljs-variable {
	color: #f07178 !important;
}

.hljs-link,
.hljs-string {
	color: #c3e88d !important;
}

.hljs-built_in,
.hljs-name,
.hljs-section,
.hljs-title {
	color: #82aaff !important;
}

.blockquoteContainer-U5TVEi .blockquoteDivider-2hH8H6 {
	border-radius:0;
	background:var(--hover);
}

.blockquoteContainer-U5TVEi:hover .blockquoteDivider-2hH8H6 {
	background:var(--accent);
}

.blockquoteContainer-U5TVEi blockquote {
	padding:0 4px 0 6px;
}

/*8.h. Reactions*/

.reactionInner-15NvIl {
	flex-direction: column !important;
	padding: 3px 8px;
}

.reaction-1hd86g {
	margin-right: var(--size5);
	margin-bottom: var(--size5)
}

.reactions-12N0jA {
	max-width: calc(100% - 55px);
	min-width:calc(100% - 55px);
	margin-top: 5px;
	position:relative;
	width:100%;
}

.reactionCount-2mvXRV {
	margin: 0;
	font-size: var(--size3);
}

.reaction-1hd86g .emoji {
	width: 1.25rem;
	height: 1.25rem;
}

.reaction-1hd86g {
	border-radius: 0;
	background: rgba(255, 255, 255, 0.1);
	box-shadow: 0 2px 12px rgba(0, 0, 0, 0.25), 0 0 4px rgba(255, 255, 255, 0.1);
	transition: 250ms ease box-shadow, 250ms ease transform;
	position: relative;
	border-radius: 2px;
	overflow: hidden;
}

.reaction-1hd86g:hover {
	box-shadow: 0 4px 18px 1px rgba(0, 0, 0, 0.5);
	transform: translateY(-1px);
}

.reactionMe-wv5HKu {
	background: transparent !important;
}

.reactionMe-wv5HKu::before {
	content: '';
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	position: absolute;
	opacity: .35;
	z-index: -1;
	background: var(--accent);
}

.reactionMe-wv5HKu .reactionCount-2mvXRV {
	color: var(--accent) !important;
}

/*8.i. Side Buttons*/

.chat-3bRxxu form .buttons-3JBrkn {
	position: fixed;
	right: 0;
	bottom: 0;
	height: 52px;
	display:flex;
    justify-content:center;
	align-items:center;
    top:unset;
    margin-right:5px;
}

.bd-detached-editor .chat-3bRxxu form .buttons-3JBrkn {
    right:30%;
}

.chatContent-a9vAAp:only-child .inner-MADQqc {
    padding-right:125px;
}

.buttons-3JBrkn .buttonContainer-21MN7J,
.buttons-3JBrkn button {
    width:42px;
    height:42px;
    border-radius:50% !important;
    margin:0;
    transition:250ms ease background;
}

.buttons-3JBrkn .buttonContainer-21MN7J:hover,
.buttons-3JBrkn button:hover {
    background:rgba(255,255,255,0.07);
}

.buttons-3JBrkn .buttonContainer-21MN7J:active,
.buttons-3JBrkn button:active {
    background:rgba(255,255,255,0.2);
}

.chatContent-a9vAAp:only-child .inner-MADQqc {
    padding-right:125px;
}

.emojiButton-3uL3Aw .sprite-2iCowe {
	visibility: hidden;
}

.emojiButton-3uL3Aw {
	background-position: center !important;
	background-image: url("data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPiAgICA8cGF0aCBkPSJNMTEuOTkgMkM2LjQ3IDIgMiA2LjQ4IDIgMTJzNC40NyAxMCA5Ljk5IDEwQzE3LjUyIDIyIDIyIDE3LjUyIDIyIDEyUzE3LjUyIDIgMTEuOTkgMnpNMTIgMjBjLTQuNDIgMC04LTMuNTgtOC04czMuNTgtOCA4LTggOCAzLjU4IDggOC0zLjU4IDgtOCA4em0zLjUtOWMuODMgMCAxLjUtLjY3IDEuNS0xLjVTMTYuMzMgOCAxNS41IDggMTQgOC42NyAxNCA5LjVzLjY3IDEuNSAxLjUgMS41em0tNyAwYy44MyAwIDEuNS0uNjcgMS41LTEuNVM5LjMzIDggOC41IDggNyA4LjY3IDcgOS41IDcuNjcgMTEgOC41IDExem0zLjUgNi41YzIuMzMgMCA0LjMxLTEuNDYgNS4xMS0zLjVINi44OWMuOCAyLjA0IDIuNzggMy41IDUuMTEgMy41eiIvPjwvc3ZnPg==") !important;
	background-repeat: no-repeat !important;
	transition: .2s ease all;
	opacity: .4 !important;
}

.emojiButton-3uL3Aw:hover {
	opacity: .9 !important;
}

.button-3AYNKb {
	color: rgba(255, 255, 255, .4);
	transition: .2s ease all
}

.button-3AYNKb:hover {
	color: rgba(255, 255, 255, .9)
}

.icon-3D60ES {
	width:22px;
	height:22px;
}

.buttons-3JBrkn .buttonContainer-21MN7J,
.buttons-3JBrkn button {
    width:42px;
    height:42px;
    border-radius:50% !important;
    margin:0;
    transition:250ms ease background;
}

.buttons-3JBrkn .buttonContainer-21MN7J:hover,
.buttons-3JBrkn button:hover {
    background:rgba(255,255,255,0.07);
}

.buttons-3JBrkn .buttonContainer-21MN7J:active,
.buttons-3JBrkn button:active {
    background:rgba(255,255,255,0.2);
}

/*8.j. Typing and Slowmode*/

.chat-3bRxxu form .typing-2GQL18,
.base-gE7OpD .cooldownWrapper-3joyFc {
    height: 32px;
    background: var(--lv1);
    box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .08), 0 0 10px #000;
	width: fit-content;
    top: -40px;
    margin: 0;
    max-width: 400px;
	opacity: 1;
    z-index: 1;
    transition: all .25s ease;
    text-overflow: ellipsis;
	display: flex;
	overflow-y:visible;
	align-items: center;
	font-size:var(--size1);
}

.full-motion .base-gE7OpD .cooldownWrapper-3joyFc {
    animation: fadeIn .3s ease;
}

.base-gE7OpD .text-1y-e8- {
	padding:0 20px;
}

.base-gE7OpD .text-1y-e8-:empty,
.typing-2GQL18 .ellipsis-19qdx6 {
	display:none;
}

.base-gE7OpD .cooldownWrapper-3joyFc {
	padding:0 10px;
	top:0;
	left:unset;
	right:-40px !important;
}

.base-gE7OpD .slowModeIcon-1BPDC_ {
	margin:0;
}

.chatContent-a9vAAp .typing-2GQL18 {
	margin-bottom: 10px;
	opacity: 1;
	transition: 250ms linear;
}

.chatContent-a9vAAp:hover .typing-2GQL18 {
	opacity: .7;
}

/*8.k. New Messages Bar*/

.newMessagesBar-mujexs {
	background: var(--accent);
	border-radius: 0;
	left:0;
	width:calc(100% - 6px);
	transition: 150ms ease all;
	padding: 3px;
	z-index:30;
	opacity:1;
}

.newMessagesBar-mujexs:hover {
	background: var(--hover);
}

.newMessagesBar-mujexs button {
	color: #fff;
}

.newMessagesBar-mujexs button:first-child {
	font-size:var(--size1);
	max-width:calc(100% - 120px);
	padding:0;
}

.newMessagesBar-mujexs::before {
	content:'';
	width:22px;
	height:22px;
	transform:scale(0.8);
	-webkit-mask:url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAeCAYAAAA7MK6iAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAFySURBVEhL7de/K0ZRHMfxmx8D5WcZWEQZDBZGg5RNMclCKYv/gCz+BQOLxeDHYGAxKJkslP/AIGIikSjkx/tze04dp+s+91wndev51Gs457nnfp/b9z73nifKkVZs4B7nmMW/ZB9fjjEETRVaLJ1QoTu0Ya403oN9XANypRHreIJ9ZcYDerFozbkuMAWvbEKL36BeGo9wC8g77OP0xTT/iSFkSg1eSto1YaUPblE5hpsF6LOVeJQhTdCCy3j0M/U4gX11t5iHm1HoPFvxKEPSCvukUrhsfivcjO4UXaiGSZDCmjM/kTRrMAlSuBa7OCvDfm4Xv8cdGHD0ow5JCVJYN9YzNO/aQVKCFNbdqnew29NTzCApxe9xD0ZSDMN+Dwfr8Ss0n8YuEqzHqzhMcYBxmBS/x77xLqwbRAtu4lH+aOep82gblTnX0H5Jm7mJHCZxBBVeQuZM4wNa+BdX0B8ArwxiGXok+tqGNnveRSsJnCj6Bnlr2owdvxxcAAAAAElFTkSuQmCC') center/cover no-repeat;
	background:#fff;
	margin:0 4px;
}

.newMessagesBar-mujexs button:last-child {
	position: absolute;
	right: 5px;
	border: 1px solid #fff;
	font-size:var(--size2);
	font-weight:500;
	transition:150ms ease;
}

.newMessagesBar-mujexs:hover button:last-child {
	color:var(--hover);
	background:#fff;
}

.jumpToPresentBar-9P20AM {
	z-index:10;
	margin-bottom:8px;
	border-radius:2px;
	background:var(--lv1);
	padding:4px;
	width:fit-content;
	border:2px solid var(--hover);
	opacity:1;
	transition:150ms ease;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.07)
}

.jumpToPresentBar-9P20AM:active {
	margin-bottom:7px;
}

.jumpToPresentBar-9P20AM:hover {
	box-shadow:none;
	background:var(--hover)
}

.jumpToPresentBar-9P20AM button {
	font-size:var(--size1);
}

.barButtonIcon-3FGqPD {
	display:none;
}

/*8.l. Mentions and Channel Links*/

.wrapper-3WhCwL {
	color:var(--accent) !important;
	background:rgba(255,255,255,0.07);
	box-shadow:0 2px 6px rgba(0, 0, 0, 0.6);
	padding: 2px 3px;
	border-radius:2px;
}

.wrapper-3WhCwL:hover {
	background:var(--accent);
	color:#fff !important;
	box-shadow:0 2px 10px rgba(0, 0, 0, 0.8);
}

.mentioned-xhSam7 .mention {
	box-shadow:none;
	color:var(--accent) !important;
}

.mentioned-xhSam7 .messageContent-2qWWxC {
	padding-left:65px;
}

.mentioned-xhSam7 .messageContent-2qWWxC::after {
	content:'';
	position:absolute;
	top:0;
	left:55px;
	width:calc(100% - 65px);
	height:calc(100% - 25px);
	z-index:-1;
	background:rgba(255,255,255,0.07);
	border-left:4px solid var(--hover);
}

.full-motion .mentioned-xhSam7 .messageContent-2qWWxC::after {
	backdrop-filter:blur(10px);
}

.groupStart-23k01U .messageContent-2qWWxC::after {
	height:calc(100% - .25rem);
	top:.25rem;
}

/*8.m. Spoilers*/

.spoilerText-3p6IlD.hidden-HHr2R9 {
	filter:blur(4px);
	transition:150ms ease filter;
	background:transparent;
}
  
.spoilerText-3p6IlD {
	background:transparent !important;
}
  
.spoilerText-3p6IlD.hidden-HHr2R9 .inlineContent-3ZjPuv {
	opacity:1;
}

.spoilerWarning-2aAZq1 {
	text-transform:none;
	font-size:var(--size1);
	border-radius:2px;
	font-size:var(--size3);
	border-radius:2px !important;
	font-weight:400;
	transition:150ms ease;
}

/*8.n. Blocked Messages*/

.blockedSystemMessage-2Rk1ek {
	margin:0 20px;
}

.blockedMessageText-1fRjos {
	color:var(--danger);
	font-size:var(--size1);
}

.blockedSystemMessage-2Rk1ek:hover .blockedAction-2ZyU8z {
	color:#72767d;
}

.blockedSystemMessage-2Rk1ek .blockedAction-2ZyU8z:hover {
	color:var(--accent);
}

/*8.o. System Messages*/

.message-2qnXI6.localBot-GrCgVt .header-23xsNx,
.localBot-GrCgVt:before,
.message-2qnXI6.localBot-GrCgVt .avatar-1BDn8e {
	display:none;
}

.systemMessage-1I9LCe,
.message-2qnXI6.localBot-GrCgVt {
	margin-top:20px;
}

.message-2qnXI6.localBot-GrCgVt,
.systemMessage-1I9LCe {
	border:2px solid var(--caution) !important;
	background:rgba(255,209,4,0.25) !important;
	border-radius:2px;
	padding:8px !important;
	position:relative;
	display:flex;
	justify-content:center;
	min-height:unset;
	transform:translateZ(0);
	flex-direction:column;
}

.localBotMessage-3cUzun {
	font-size:0;
}

.message-2qnXI6.localBot-GrCgVt .container-1ov-mD,
.systemMessage-1I9LCe .container-1ov-mD {
	position:relative;
	top:0 !important;
	left:0;
	margin:0 !important;
	padding:0 !important;
	width:unset !important;
}

.systemMessage-1I9LCe .reactions-12N0jA {
	margin-left:5px;
}

.message-2qnXI6.localBot-GrCgVt .anchor-3Z-8Bb {
	position:fixed;
	right:5px;
	top:50%;
	transform:translateY(-50%);
	width:25px;
	height:25px;
	background:url("data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIj8+PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBmaWxsPSIjZmZmZmZmIj4gIDxwYXRoIGQ9Ik0xOSA2LjQxTDE3LjU5IDUgMTIgMTAuNTkgNi40MSA1IDUgNi40MSAxMC41OSAxMiA1IDE3LjU5IDYuNDEgMTkgMTIgMTMuNDEgMTcuNTkgMTkgMTkgMTcuNTkgMTMuNDEgMTJ6Ii8+ICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PC9zdmc+") center/75% no-repeat;
}

.message-2qnXI6.localBot-GrCgVt .messageContent-2qWWxC,
.systemMessage-1I9LCe .messageContent-2qWWxC {
	color: #dadada;
	font-weight: 500;
	margin:0 15px;
	display:block;
	max-width:unset;
	margin-right:30px;
	padding-bottom:0 !important;
	padding-top:0 !important;
	margin-top:0 !important;
	padding-left:0;
}

.systemMessage-1I9LCe .messageContent-2qWWxC {
	padding-left:28px;
	margin-right:0;
	top:0 !important;
}

.iconContainer-3GkGRf {
	margin-right:8px;
}

.iconContainer-3GkGRf div[style*='url("/assets/c30220457097b064286a8759a9b6c4af.svg")'] {
	-webkit-mask:url("/assets/c30220457097b064286a8759a9b6c4af.svg") center/1rem no-repeat;
	background:var(--success) !important;
}

.content-2M3n_H {
	color: #dadada !important;
	font-weight: 500 !important;
	display:flex;
	align-items:center;
	font-size:var(--size1);
}

.systemMessage-1I9LCe {
	padding-bottom:8px !important;
	border: 2px solid var(--success) !important;
	background: rgba(70, 207, 104, .25) !important;
}

.systemMessage-1I9LCe .buttonContainer-DHceWr {
	top:34px;
}

/*8.p. Search Results*/

.searchResultsWrap-2DKFzt {
	z-index:101;
	box-shadow:0 0 12px var(--lv1);
}

.searchResult-3pzFAB .messageGroupCozy-1BZuO8 {
	background: rgba(255, 255, 255, 0.075) !important;
	border-left: 2px solid rgba(255, 255, 255, 0.075) !important;
	margin:5px 20px;
	padding-top:0;
}

.searchResultMessage-2VxO12.after-2g0jjc {
	margin-top:10px;
}

.searchResultMessage-2VxO12.before-1x1q5S {
	margin-bottom:10px;
}

.searchResult-3pzFAB.expanded-v2Szsz .messageGroupCozy-1BZuO8 {
	margin-bottom:15px;
}

.searchResult-3pzFAB .hit-NLlWXA .messageGroupCozy-1BZuO8 {
	padding:0;
}

.searchResult-3pzFAB .cozy-3raOZG .messageContent-2qWWxC {
	max-width:100%;
}

.jumpButton-Ia2hRJ {
	z-index:10;
	top:4px;
	right:26px;
	border-radius:0;
	padding:4px 6px;
	line-height:normal;
	transition:150ms ease;
	background:var(--hover);
	box-shadow:0 0 2px rgba(0,0,0,0.5);
	color:#fff;
}

.jumpButton-Ia2hRJ:hover {
	background:var(--accent);
	color:#fff;
}

.searchResultMessage-2VxO12.hit-NLlWXA {
	box-shadow:none;
}

.searchResult-3pzFAB .avatar-1BDn8e[src*="254362351170617345"]+ .header-23xsNx .timestamp-3ZCmNB::before,
.channelSeparator-1X1FuH:before {
	display:none;
}

.channelSeparator-1X1FuH {
	margin:0 20px;
}

.channelName-1QajIf {
	color:var(--accent);
	cursor:pointer;
	font-size:var(--size1);
}

.searchHeader-1l-wpR {
	position:absolute;
	box-sizing: border-box;
	backdrop-filter: blur(20px);
	box-shadow: 0 2px 10px rgba(0,0,0,0.1);
	width:100%;
	font-size:var(--size1);
	color:rgba(255,255,255,0.65);
	display:flex;
	align-items:center;
}

.tab-2Ixsn0.selected-16te-P {
	background:var(--hover);
}

.tab-2Ixsn0 {
	padding:4px 6px;
	transition:150ms ease;
}

.searchResultsWrap-2DKFzt .scroller-2FKFPG {
	padding-top:50px;
}

.searchResultsWrap-2DKFzt .scroller-2FKFPG::-webkit-scrollbar {
	display:none;
}

.tab-2Ixsn0.selected-16te-P, .tab-2Ixsn0:hover {
	border:none;
}

.searchResult-3pzFAB.expanded-v2Szsz {
	background:transparent;
}

.totalResults-gxvzgw {
	font-weight:600;
}

.emptyResultsText-1RCul5 {
	font-size:var(--size1);
	color:rgba(255,255,255,0.5);
}

.pagination-eQpqgk {
	font-size:var(--size2);
	color:rgba(255,255,255,0.5);
}

.paginationButton-1RB6mQ {
	border:none;
}

/*8.q. Call and Video*/

.video-1FfuMD,
#app-mount .wrapper-29NfPK {
	background-color:var(--lv1);
}

.wrapper-29NfPK {
	box-shadow:0 0 12px var(--lv1);
}

.wrapper-29NfPK.minimum-2d6zH6 .actions-2vadYq .center-1Vp33r {
	background:rgba(255,255,255,0.1) !important;
	box-shadow:0 2px 12px rgba(255,255,255,0.1);
	border:none;
	border-radius:0;
}

.medium-2JR8YY {
	width:20px;
	height:20px;
	background-size:20px;
}

.videoHeight-Qp_9vC.fullScreen-lH2Q2c {
	z-index:1000;
}

.wrapper-29NfPK .actions-2vadYq .exitButton-1DkWLl {
	text-transform:none;
}

.callAvatarBorder-uWp8Ga.video-3SrWSI.selected-2tLJQ6.notSpeaking-a3bIkW.notSoundsharing-2sYlLk {
	box-shadow: inset 0 0 0 2px var(--accent);
}

.callAvatarVideo-2ItXvV,
.callAvatarBorder-uWp8Ga {
	border-radius:var(--user-roundness);
}

/*8.r. NSFW Warning*/

.gatedContent-3-B7qB {
	padding-bottom:70px;
}

.title-1VcOOr {
	font-size:var(--size0);
}

.description-2ydcYn {
	font-size:var(--size1);
}

.separator-2IZ9ro {
	background:rgba(255,255,255,0.25);
	margin-bottom:20px;
}

.gatedContent-3-B7qB::after {	
	content:'To send messages, please verify you are over the age of 18.';
	height:50px;
	width:calc(100% - 590px);
	box-shadow:0 -10px 10px -10px var(--lv1), inset 0 0 0 100vmax rgba(255,255,255,0.07);
	background:var(--lv1);
	z-index:100;
	position:fixed;
	bottom:0;
	left:325px;
	color:rgba(255,255,255,0.25);
	font-size:var(--size1);
	display:flex;
	padding:0 8px;
	align-items:center;
	cursor:not-allowed;
}

.gatedContent-3-B7qB .image-2LqJex {
	width:150px;
	height:150px;
	opacity:.8;
}

/*9. Popouts*/

/*9.a. Context Menus*/

@keyframes contextMenu {
	0% {
		transform:scaleY(.75);
	}
	100% {
		transform:scaleY(1);
	}
}

.itemGroup-1tL0uz {
	border: none;
}

.itemBase-tz5SeC.brand-3igrJY, 
.itemBase-tz5SeC.brand-3igrJY:hover {
	color:var(--accent);
}

.itemBase-tz5SeC.danger-2dXSTE,
.item-1GzJrl.leave-1DRJfn {
	color:var(--danger);
}

.itemBase-tz5SeC.danger-2dXSTE:hover,
.item-1GzJrl.leave-1DRJfn:hover {
	border-color:var(--danger) !important;
	box-shadow: inset 15px 0 15px -15px var(--danger) !important;
}

.container-3cGP6G,
.contextMenu-HLZMGh {
	padding:0;
	border-radius: 0 !important;
	background: var(--lv1) !important;
	box-shadow:inset 0 0 0 100vmax rgba(255, 255, 255, .06), 0 2px 12px var(--lv1) !important;
	transform-origin: top;
}

.full-motion .container-3cGP6G,
.full-motion .contextMenu-HLZMGh {
	animation: contextMenu .3s cubic-bezier(0, 0, 0, 1);
}

.contextMenu-HLZMGh .item-1Yvehc,
.item-2J1YMK,
.itemSlider-FZeYw0,
.itemSubMenu-1vN_Yn,
.wrapper-35dUTv {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0 !important;
	border-left: 2px solid rgba(255, 255, 255, .2);
}

.wrapper-35dUTv {
	padding:0 !important;
}

.button-1I8KM5 {
	background:transparent !important;
}

.contextMenu-HLZMGh .item-1Yvehc:hover,
.item-2J1YMK:hover,
.itemSlider-FZeYw0:hover,
.itemSubMenu-1vN_Yn.selected-BYpGTS,
.contextMenu-HLZMGh .item-1Yvehc.selected {
	background-color: rgba(255, 255, 255, .06) !important;
	border-color: var(--accent);
	box-shadow: inset 15px 0 15px -15px var(--accent)
}

.itemSubMenu-1vN_Yn .caret-UIZBlm {
    transition:150ms ease transform;
    transform-origin:center;
}

.selected-BYpGTS .caret-UIZBlm {
    transform:rotate(0);
}

.item-1Yvehc .hint-22uc-R,
.label-JWQiNe {
	font-size:var(--size2);
}

.itemSlider-FZeYw0 .mini-dmm9yo .grabber-3mFHz2 {
	margin-top:10px;
}

/*9.b. User Popouts*/

@keyframes userPopout {
	0% {
		transform: translateX(10%) scale(.95);
		transform-origin: right center
	}
	100% {
		transform: none;
	}
}

.userPopout-3XzG_A {
	border-radius: 0;
	background: var(--lv1) !important;
	box-shadow: 0 0 12px 1px var(--lv1);
	transform:translateZ(0);
}

.full-motion .userPopout-3XzG_A {
	animation: userPopout 350ms;
}

.footer-1fjuF6 {
	padding: 0;
	border: none;
}

.body-3iLsc4,
.activityUserPopout-2yItg2 {
	background: rgba(255, 255, 255, .04) !important;
}

.bodyInner-245q0L,
.footer-1fjuF6 {
	background: transparent !important;
}

.quickMessage-1yeL4E {
	transition: 150ms ease border, 150ms ease box-shadow;
	box-shadow: none !important;
	border-radius: 0;
	font-size: var(--size1);
	border:none;
	border-bottom: 2px solid rgba(255, 255, 255, .1) !important;
	background: rgba(255, 255, 255, .08) !important;
}

.full-motion .quickMessage-1yeL4E {
	backdrop-filter:blur(10px);
}

.inline-136HKr .pro-1T8RK7, .inline-136HKr .tip-2ab612 {
	display:none;
}

.quickMessage-1yeL4E + .protip-YaFfgO {
	position:absolute;
	bottom:0;
	left:0;
	background:var(--accent);
	box-shadow:0 0 8px var(--accent);
	opacity:0;
	width:100%;
	height:2px;
	opacity:0;
	transition:250ms ease opacity;
}

.quickMessage-1yeL4E:focus + .protip-YaFfgO {
	opacity:1;
}

.full-motion .quickMessage-1yeL4E:focus + .protip-YaFfgO {
	animation:textarea 250ms ease;
}

.userPopout-3XzG_A .header-2BwW8b {
	position: relative;
	background: transparent !important;
}

.userPopout-3XzG_A .assetsLargeImageUserPopout-3Pp8BK {
	width: auto;
	height: 70px;
}

.userPopout-3XzG_A .headerXbox-3G-4PF .headerTop-3C2Zn0 {
	background-image: linear-gradient(var(--xbox-green), rgba(0, 0, 0, 0.75)) !important;
	background-color: var(--xbox-green) !important;
}

.userPopout-3XzG_A .headerSpotify-zpWxgT .headerTop-3C2Zn0 {
	background-image: linear-gradient(var(--spotify-green), rgba(0, 0, 0, 0.75)) !important;
	background-color: var(--spotify-green) !important;
}

.userPopout-3XzG_A .headerStreaming-2FjmGz .headerTop-3C2Zn0 {
	background-image: linear-gradient(var(--twitch-purple), rgba(0, 0, 0, 0.75)) !important;
	background-color: var(--twitch-purple) !important;
}

#app-mount .headerPlaying-j0WQBV .headerTop-3C2Zn0 {
	background-image: linear-gradient(var(--accent), rgba(0, 0, 0, 0.75)) !important;
	background-color: var(--accent) !important;
}

.activityStreamPreview-3r3GiX .textRow-19NEd_,
.activityUserPopout-2yItg2 .textRow-19NEd_,
.customStatus-1bh2V9 {
	font-size: var(--size1);
}

.barInner-3NDaY_ {
	background:var(--spotify-green);
	box-shadow:0 0 12px var(--spotify-green);
}

.content-3JfFJh a {
	text-shadow:none !important;
}

.actionsStreamPreview-2lARcx,
.actionsUserPopout-2xcO1O {
	margin-top: 0;
}

.HintHint-1qgaV3,
.userPopout-3XzG_A .activity-11LB_k * {
	border-radius: 0 !important;
}

.userPopout-3XzG_A .headerTop-3C2Zn0 {
	padding: 10px;
	padding-top: 40px;
	background: rgba(255, 255, 255, 0.07);
	align-items: flex-start;
}

.userPopout-3XzG_A .headerTag-2pZJzA {
	font-size: var(--size2);
	font-weight: 500;
	text-transform: capitalize;
	color: rgba(255, 255, 255, .5) !important;
	height: 28px;
	align-items: center;
	justify-content: flex-start;
	position: absolute;
	left: 0;
	width: 100%;
	display: flex;
	top: 0;
	background: rgba(0, 0, 0, 0.5);
	box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);
	backdrop-filter: blur(10px);
	text-align: left;
	z-index: 1;
}

.userPopout-3XzG_A .headerTag-2pZJzA span+span {
	line-height: normal;
}

.userPopout-3XzG_A .username-2b1r56 {
	margin-left: 10px;
	line-height: normal;
	white-space: nowrap;
	overflow: hidden;
	max-width: 80%;
	font-size:var(--size2);
}

.userPopout-3XzG_A .username-2b1r56:before {
	content: '';
	margin-right: 5px;
	font-family: 'Segoe MDL2 Assets';
	position: relative;
	top: 1px;
}

.userPopout-3XzG_A .headerName-fajvi9 {
	font-size: var(--size0);
}

.userPopout-3XzG_A .username-2b1r56 {
	color: #fff;
	font-weight: 600;
}

.userPopout-3XzG_A .customStatus-1bh2V9,
.userPopout-3XzG_A .headerNameWrapper-3res2c {
	text-align: left;
	font-weight:500;
}

.userPopout-3XzG_A .customStatus-1bh2V9 .customStatusEmoji-7MXCgv.customStatusSoloEmoji-XOvnMc {
	width: 25px;
	height: 25px;
}

.avatarHintInner-Dco91E {
	background:url("data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIj8+PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBmaWxsPSIjZmZmZmZmIj4gIDxwYXRoIGQ9Ik0xMiAxMmMyLjIxIDAgNC0xLjc5IDQtNHMtMS43OS00LTQtNC00IDEuNzktNCA0IDEuNzkgNCA0IDR6bTAgMmMtMi42NyAwLTggMS4zNC04IDR2MmgxNnYtMmMwLTIuNjYtNS4zMy00LTgtNHoiLz4gIDxwYXRoIGQ9Ik0wIDBoMjR2MjRIMHoiIGZpbGw9Im5vbmUiLz48L3N2Zz4=") center/60% no-repeat !important;
	box-shadow:none;
	background-color:rgba(0,0,0,0.5) !important;
	font-size:0;
	border-radius:var(--user-roundness);
}

.activityUserPopout-2yItg2 .headerText-1HLrL7,
.bodyTitle-Y0qMQz {
	margin: 0;
	background: rgba(255, 255, 255, .07) !important;
	height: 28px !important;
	line-height: 28px;
	padding: 0 10px;
	font-size: var(--size2);
	font-weight: 500;
	text-transform: capitalize;
	color: rgba(255, 255, 255, .5) !important;
	backdrop-filter: blur(10px);
	display: flex;
}

.rolesList-22qj2L {
	max-height:250px;
	min-height:unset;
	overflow:auto;
}

.activityUserPopout-2yItg2 .body-ZAhrcj {
	padding: 10px;
	align-items:center;
}

#app-mount .userPopout-3XzG_A .bot-2Fta1w {
	position: absolute;
	right: 10px;
	margin: 0;
	width:fit-content;
	font-size: var(--size4);
	border-radius: 2px;
	height: 1.28em;
	padding: .072rem .275rem;
	background:#fff;
	color:var(--accent);
}

.userPopout-3XzG_A .avatarWrapper-3H_478[user_by_bdfdb*="254362351170617345"]+.headerText-2sdzFM .headerTag-2pZJzA:after {
	content: 'Dev';
	position: absolute;
	right: 10px;
	border-radius: 2px;
	color: var(--accent);
	font-size: var(--size4);
	font-weight: 500;
	height: 1.28em;
	padding: .072rem .275rem;
	line-height: 1.28em;
	background: #fff;
	z-index: 2;
}

.userPopout-3XzG_A .timeBarUserPopout-AWPFf2 {
	padding: 0 10px;
}

.userPopout-3XzG_A .activityUserPopout-2yItg2 .body-ZAhrcj a {
	text-shadow: none;
}

.userPopout-3XzG_A .headerSpotify-zpWxgT a {
	color:var(--spotify-green) !important;
}

.userPopout-3XzG_A .fullWidth-1orjjo {
	margin: 0;
}

.assetsLargeMaskUserPopout-12EBBc {
	mask: none !important;
	-webkit-mask: none;
}

.bodyInner-245q0L {
	padding: 0;
}

.bodyInner-245q0L::-webkit-scrollbar {
	display: none;
}

.note-3HfJZ5 {
	margin-bottom: 8px !important;
}

.userPopout-3XzG_A .note-3HfJZ5 textarea {
	font-size: var(--size2) !important;
	background:transparent !important;
	padding:0;
	height:unset !important;
	line-height:normal;
}

.activityUserPopout-2yItg2 {
	padding: 0;
	position: relative;
}

.bodyTitle-Y0qMQz:first-child:before {
	content: '';
}

.bodyTitle-Y0qMQz:before {
	content: '';
	margin-right: 5px;
	font-family: 'Segoe MDL2 Assets';
}

.activityUserPopout-2yItg2 .headerText-1HLrL7:before {
	content: '';
	margin-right: 5px;
	font-family: 'Segoe MDL2 Assets';
}

.note-3HfJZ5,
.rolesList-22qj2L,
.actionsStreamPreview-2JlX14,
.actionsUserPopout-2MrzCa, 
.listeningActionsUserPopout-Ga2V_N {
	margin: 10px;
}

.actionsStreamPreview-2JlX14,
.actionsUserPopout-2MrzCa, 
.listeningActionsUserPopout-Ga2V_N {
	margin-bottom:0;
	padding-bottom:10px;
}

.guildPopout-3CgKqR {
	border-radius: 0;
	background: var(--lv1) !important;
	box-shadow: 0 0 12px 1px var(--lv1), inset 0 0 0 100vmax rgba(255, 255, 255, 0.07) !important;
}

.full-motion .guildPopout-3CgKqR {
	animation: userPopout 350ms;
}

.guildPopout-3CgKqR .guildNameWrapper-1Mauc8 {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 28px;
	background: rgba(0, 0, 0, 0.5);
	box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);
	padding: 0 10px;
	color: rgba(255, 255, 255, .5) !important;
}

.guildPopout-3CgKqR .guildName-vhRkcC {
	font-size: 12px !important;
	font-weight: 500;
	text-transform: capitalize;
}

.guildPopout-3CgKqR .guildIconBase-2U7aA8 {
	margin: 15px 0;
}

.wumpusWrapper-yrvoR3 {
	position: fixed;
	top: 0;
	right: 0;
	margin: 0;
	width: 75px;
	height: 75px;
}

.wumpus-3VDMUi img {
	display: none;
}

.wumpus-3VDMUi {
	animation: none;
	transition: none;
	transform: none;
	width: 100%;
	height: 100%;
	left: 0;
}

.wumpusTooltip-65YlMT::after {
	display: none;
}

#app-mount .wumpusTooltip-65YlMT::before {
	content: 'New';
	font-size: var(--size2);
	color: #fff;
	position: relative;
	transform: rotate(45deg);
	transform-origin: center;
	top: 12px;
	left: -12px
}

#app-mount .wumpusTooltip-65YlMT {
	font-size: 0;
	background: var(--danger);
	position: absolute;
	width: 100%;
	height: 100%;
	padding: 0;
	top: 0;
	left: 0;
	display: flex;
	justify-content: center;
	border-radius: 0;
	clip-path: polygon(0% 0%, 50% 0, 100% 50%, 100% 100%);
}

.creationDate {
	font-size:var(--size1);
}

/*9.c. Status Picker & Server Dropdown*/

.item-1GzJrl.invite-271nFU {
	color:var(--accent) !important;
}

.menu-Sp6bN1[role="listbox"] {
	left:8px;
	top:-8px;
	width:180px;
}

.menu-Sp6bN1 {
	top:-4px;
	position:relative;
}

.scale-3iLZhb.didRender-33z1u8 {
	transform:none !important;
	transition:none !important;
}

.helper-2c73HK, 
.separator-2zcjq8 {
	display:none;
}

.menu-Sp6bN1 {
	border-radius: 0 !important;
	background: var(--lv1) !important;
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .06), 0 2px 12px #000 !important;
	transform-origin: top;
	padding:0;
}

.full-motion .menu-Sp6bN1 {
	animation: contextMenu .3s cubic-bezier(0, 0, 0, 1);
}

.itemBase-1Qj4z6 {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0;
	border-left: 2px solid rgba(255, 255, 255, .2);
}

.itemActive-2V2HNc {
  opacity:.5;
  cursor:default;
}

.itemBase-1Qj4z6 {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0;
	border-left: 2px solid rgba(255, 255, 255, .2);
}

.itemBase-1Qj4z6:hover {
	background-color: rgba(255, 255, 255, .07) !important;
	border-color: var(--accent);
	box-shadow: inset 15px 0 15px -15px var(--accent);
}

.customStatusContentIcon-2sionu,
.statusIconText-3b4TkH,
.label-1Y-LW5,
.customStatus-1KPfFb {
  height:auto;
  font-size:var(--size2);
  display:flex;
  align-items:center;
}

.clearStatus-2hmUqc {
	order:-1;
	position:relative;
	margin-right:16px;
}

.item-1GzJrl {
	justify-content:flex-start;
}

.clearStatusIcon-3-MDNF {
	margin:0;
	width:10px;
	height:10px;
}

.customStatusEmojiPlaceholder-1NdyxH {
	opacity:.6;
	transition:150ms ease opacity;
	background-image:url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIj8+PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBmaWxsPSIjZmZmZmZmIj4gIDxwYXRoIGQ9Ik0wIDBoMjR2MjRIMHoiIGZpbGw9Im5vbmUiLz4gIDxwYXRoIGQ9Ik0xMS45OSAyQzYuNDcgMiAyIDYuNDggMiAxMnM0LjQ3IDEwIDkuOTkgMTBDMTcuNTIgMjIgMjIgMTcuNTIgMjIgMTJTMTcuNTIgMiAxMS45OSAyek0xMiAyMGMtNC40MiAwLTgtMy41OC04LThzMy41OC04IDgtOCA4IDMuNTggOCA4LTMuNTggOC04IDh6bTMuNS05Yy44MyAwIDEuNS0uNjcgMS41LTEuNVMxNi4zMyA4IDE1LjUgOCAxNCA4LjY3IDE0IDkuNXMuNjcgMS41IDEuNSAxLjV6bS03IDBjLjgzIDAgMS41LS42NyAxLjUtMS41UzkuMzMgOCA4LjUgOCA3IDguNjcgNyA5LjUgNy42NyAxMSA4LjUgMTF6bTMuNSA2LjVjMi4zMyAwIDQuMzEtMS40NiA1LjExLTMuNUg2Ljg5Yy44IDIuMDQgMi43OCAzLjUgNS4xMSAzLjV6Ii8+PC9zdmc+');
}

.itemBase-1Qj4z6:hover .customStatusEmojiPlaceholder-1NdyxH {
	opacity:.8;
}

.status-1AY8sU[style*="background-color: rgb(67, 181, 129);"] {
	background:var(--success) !important;
}

.status-1AY8sU[style*="background-color: rgb(250, 166, 26);"] {
	background:var(--caution) !important;
}

.status-1AY8sU[style*="background-color: rgb(240, 71, 71);"] {
	background:var(--danger) !important;
}

.status-1AY8sU[style*="background-color: rgb(116, 127, 141);"] {
	background:var(--unavailable) !important;
}

/*9.d. Selection Dropdowns*/

.css-15ejc46-control,
.css-2yldzf-control,
.lookFilled-1h1y05.select-1Pkeg4 {
	border:2px solid rgba(255,255,255,0.15) !important;
	border-radius:2px;
	box-sizing:border-box;
	transition:none;
	cursor:pointer;
}

.css-15ejc46-control:hover,
.lookFilled-1h1y05.select-1Pkeg4:hover {
	border:2px solid var(--hover) !important;
}

.css-1yegjoj-control,
.css-2yldzf-control,
.lookFilled-1h1y05.select-1Pkeg4:focus {
	transition:150ms ease;
	border:2px solid var(--accent) !important;
}

.css-181m2lf-menu,
.popout-2sKjHu,
.css-1rckt42-menu {
	padding:0;
	margin-top:0 !important; 
	border-radius: 0 !important;
	background: var(--lv1) !important;
	box-shadow:inset 0 0 0 100vmax rgba(255, 255, 255, .06), 0 2px 12px var(--lv1) !important;
	animation: contextMenu .3s cubic-bezier(0, 0, 0, 1);
	transform-origin: top;
	border:none;
}

.css-1k00wn6-singleValue {
	padding: 2px 0;
}

.popout-2sKjHu {
	margin-top:6px !important;
}

.deviceOptionLabel-22FM_u,
.sizeMedium-6vZ9JV.popout-2sKjHu,
.sizeMedium-6vZ9JV.select-1Pkeg4 {
	font-size:var(--size2);
}

.css-12o7ek3-option,
.css-1aymab5-option,
.optionNormal-12VR9V {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0;
	border-left: 2px solid rgba(255, 255, 255, .2);
	font-size:var(--size2) !important;
	cursor:pointer;
}

.css-12o7ek3-option:hover,
.css-1aymab5-option:hover,
.css-1gnr91b-option,
.optionActive-KkAdqq,
.css-12o7ek3-option,
.optionNormal-12VR9V:hover {
	background-color: rgba(255, 255, 255, .06) !important;
	border-left: 2px solid var(--accent);
	box-shadow: inset 15px 0 15px -15px var(--accent);
	font-size:var(--size2) !important;
	padding: 7px 15px !important;
}

/*9.e. Emoji Picker*/

@keyframes emojiPicker {
	0% {
		transform:translateY(-10px);
		opacity:.5;
	}
	100% {
		opacity:1;
		transform:none;
	}
}

.full-motion .layer-v9HyYc[style*="right: 5px;"] {
	animation:emojiPicker 150ms ease;
}

.layer-v9HyYc {
	z-index:10;
}

.emojiPicker-3m1S-j {
	display:flex;
	flex-direction:row;
	flex-wrap:wrap;
	justify-content:flex-end;
	border:1px solid rgba(255,255,255,0.2) !important;
	box-shadow:0 2px 10px var(--lv1);
	width:420px;
	max-width:unset;
	box-sizing:border-box;
	border-radius: 0 0 3px 3px;
	border-top:none !important;
	background:var(--lv1);
}

#bda-qem-twitch-container, 
#bda-qem-favourite-container {
	width:420px;
	height:401px;
	border:1px solid rgba(255,255,255,0.2);
	border-top:none;
	box-shadow:0 2px 10px var(--lv1);
	background:var(--lv1);
	box-sizing:border-box;
}

.emojiPicker-3m1S-j::before {
	content:'Select an Emote';
	position:absolute;
	top:-30px;
	left:0;
	width:100%;
	height:30px;
	font-size:var(--size2);
	border-radius: 3px 3px 0 0;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.1);
	background:var(--lv1);
	box-sizing:border-box;
	border:1px solid rgba(255,255,255,0.2) !important;
	border-bottom:none !important;
	display:flex;
	align-items:center;
	padding:0 16px;
	font-weight:600;
	color:rgba(255,255,255,0.85) !important;
}

.emojiPicker-3m1S-j .scrollerWrap-2lJEkd,
.emojiPicker-3m1S-j .noSearchResultsContainer-3Dee0U {
	width:calc(100% - 50px);
}

.emojiPicker-3m1S-j .noSearchResultsContainer-3Dee0U {
	padding:0;
}

.emojiPicker-3m1S-j .noSearchResultsContainer-3Dee0U {
	height:300px;	
}

.wrapper-1GJGVj {
	font-size:var(--size1);
}

.emojiPicker-3m1S-j .scroller-3vODG7 {
	width:100%;
	height:280px;
	padding:0 10px;
	padding-bottom:20px;
}

.emojiPicker-3m1S-j .scroller-3vODG7 .row-3j9Kuo {
    display: inline-flex;
	align-items: center;
	justify-content:flex-start;
    width: 100%;
    height: 40px !important;	
	white-space: nowrap;
}

.infoBar-U6oBFk {
	order:-1;
	z-index:1;
	box-shadow:0 1px 4px var(--lv1);
	height:50px;
	background:rgba(255,255,255,0.1);
	border-bottom:1px solid rgba(255,255,255,0.1);
	box-sizing:border-box;
}

.infoBar-U6oBFk .infoBarEmojiName-3t926M {
	position:relative;
}

.infoBar-U6oBFk .infoBarEmojiName-3t926M:empty::before {
	content:'Unknown';
}

.infoBar-U6oBFk .infoBarEmojiName-3t926M:empty::after {
	content:'';
	width:18px;
	height:18px;
	position:absolute;
	right:0;
	background:#fff;
	-webkit-mask:url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTggMS40NWw2LjcwNSAxMy4zNjNoLTEzLjQwOWw2LjcwNS0xMy4zNjN6TTggMGMtMC4zNDUgMC0wLjY5IDAuMjMzLTAuOTUxIDAuNjk4bC02LjgyOSAxMy42MTFjLTAuNTIzIDAuOTMtMC4wNzggMS42OTEgMC45ODkgMS42OTFoMTMuNTgzYzEuMDY3IDAgMS41MTItMC43NjEgMC45ODktMS42OTFoMGwtNi44MjktMTMuNjExYy0wLjI2Mi0wLjQ2NS0wLjYwNi0wLjY5OC0wLjk1MS0wLjY5OHYweiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik05IDEzYzAgMC41NTItMC40NDggMS0xIDFzLTEtMC40NDgtMS0xYzAtMC41NTIgMC40NDgtMSAxLTFzMSAwLjQ0OCAxIDF6Ij48L3BhdGg+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTggMTFjLTAuNTUyIDAtMS0wLjQ0OC0xLTF2LTNjMC0wLjU1MiAwLjQ0OC0xIDEtMXMxIDAuNDQ4IDEgMXYzYzAgMC41NTItMC40NDggMS0xIDF6Ij48L3BhdGg+PC9zdmc+') center/cover no-repeat;
}

.emojiPicker-3m1S-j .sadImage-2ph8SI {
	background:#fff;
	-webkit-mask-size:cover;
	-webkit-mask-repeat:no-repeat;
	-webkit-mask-image:url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTEgMGg2djFoLTZ6TTkgMGg2djFoLTZ6TTE0Ljg3NSA1aC0wLjg3NXYtNGgtNHY0aC00di00aC00djRoLTAuODc1Yy0wLjYxOSAwLTEuMTI1IDAuNTA2LTEuMTI1IDEuMTI1djguNzVjMCAwLjYxOSAwLjUwNiAxLjEyNSAxLjEyNSAxLjEyNWg0Ljc1YzAuNjE5IDAgMS4xMjUtMC41MDYgMS4xMjUtMS4xMjV2LTUuODc1aDJ2NS44NzVjMCAwLjYxOSAwLjUwNiAxLjEyNSAxLjEyNSAxLjEyNWg0Ljc1YzAuNjE5IDAgMS4xMjUtMC41MDYgMS4xMjUtMS4xMjV2LTguNzVjMC0wLjYxOS0wLjUwNi0xLjEyNS0xLjEyNS0xLjEyNXpNNS40MzggMTVoLTMuODc1Yy0wLjMwOSAwLTAuNTYzLTAuMjI1LTAuNTYzLTAuNXMwLjI1My0wLjUgMC41NjMtMC41aDMuODc1YzAuMzA5IDAgMC41NjMgMC4yMjUgMC41NjMgMC41cy0wLjI1MyAwLjUtMC41NjMgMC41ek04LjUgOGgtMWMtMC4yNzUgMC0wLjUtMC4yMjUtMC41LTAuNXMwLjIyNS0wLjUgMC41LTAuNWgxYzAuMjc1IDAgMC41IDAuMjI1IDAuNSAwLjVzLTAuMjI1IDAuNS0wLjUgMC41ek0xNC40MzggMTVoLTMuODc1Yy0wLjMwOSAwLTAuNTYzLTAuMjI1LTAuNTYzLTAuNXMwLjI1My0wLjUgMC41NjMtMC41aDMuODc1YzAuMzA5IDAgMC41NjMgMC4yMjUgMC41NjMgMC41cy0wLjI1MyAwLjUtMC41NjMgMC41eiI+PC9wYXRoPjwvc3ZnPg==');
}

.emojiPicker-3m1S-j .header-1nkwgG {
	flex: 1 0 100%;
	order:1;
	height:50px;
	background:rgba(255,255,255,0.1);
	border-top:1px solid rgba(255,255,255,0.1);
	box-sizing:border-box;
	position:relative;
	box-shadow:0 -1px 4px var(--lv1);
}

.emojiPicker-3m1S-j .categories-1feg4n {
	flex-direction:column;
	align-items:flex-start;
	justify-content:center;
	order:-1;
	padding:0;
	width:50px;
	height:100%;
	box-sizing:border-box;
	padding: 10px 0;
	background:rgba(255,255,255,0.06);
	border-right:1px solid rgba(255,255,255,0.05);
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq {
	opacity: .4;
	background-repeat: no-repeat;
	background-size: 20px;
	background-position: 50%;
	margin:0;
	border-left:2px solid transparent;
	border-bottom:none;
	box-sizing:border-box;
	height:28px;
	width:calc(100% - 2px);
}

.emojiPicker-3m1S-j .categories-1feg4n .selected-39BZ4S {
	border-left-color:var(--accent) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq svg {
	display: none;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:hover {
	opacity:.75;
}

.emojiPicker-3m1S-j .categories-1feg4n .selected-39BZ4S {
	opacity: 1;
}

.emojiPicker-3m1S-j .emojiItem-109bjA {
	flex:0 0 auto;
	position:relative;
	margin:4px !important;
	background-size:72% !important;
	width:27px !important;
	border-radius:1px;
	box-sizing:border-box;
}

.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S,
.emote-container:hover {
	background-color:rgba(255,255,255,0.15) !important;
}

.emojiPicker-3m1S-j .category-2U57w6 {
	padding:0;
	text-transform:none;
	font-size:var(--size2);
	font-weight:500;
	padding-top:10px;
	border-bottom:1px solid rgba(255,255,255,0.1);
}

.infoBar-U6oBFk .infoBarEmoji-3Ab8rZ {
	border-radius:var(--guilds-roundness);
}

.infoBar-U6oBFk .iconSizeSmaller-2whVAO {
	width:28px;
	height:28px;
	background-size:contain;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(1) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzFfIj4NCgk8cGF0aCBpZD0iWE1MSURfMTNfIiBjbGFzcz0ic3QxIiBkPSJNLTkzNSw1MzJjLTUsMC05LDQtOSw5czQsOSw5LDlzOS00LDktOVMtOTMwLDUzMi05MzUsNTMyeiBNLTkzNSw1NDhjLTMuOSwwLTctMy4xLTctNw0KCQlzMy4xLTcsNy03czcsMy4xLDcsN1MtOTMxLjEsNTQ4LTkzNSw1NDh6Ii8+DQoJPHBvbHlnb24gaWQ9IlhNTElEXzEyXyIgY2xhc3M9InN0MSIgcG9pbnRzPSItOTMxLjUsNTQzLjEgLTkzMi45LDU0NC41IC05MzYsNTQxLjQgLTkzNiw1MzUuNyAtOTM0LDUzNS43IC05MzQsNTQwLjYgCSIvPg0KPC9nPg0KPC9zdmc+DQo=) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(2) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzg3LDI4OWgyNHYyNGgtMjRWMjg5eiIvPg0KPGcgaWQ9IlhNTElEXzEwMF8iPg0KCTxwYXRoIGlkPSJYTUxJRF8xMDdfIiBjbGFzcz0ic3QxIiBkPSJNLTM3Mi44LDI5NC44bDQsNGwtOS4yLDkuMmgtNHYtNEwtMzcyLjgsMjk0LjggTS0zNzIuOCwyOTJsLTExLjIsMTEuMnY2LjhoNi44bDExLjItMTEuMg0KCQlMLTM3Mi44LDI5MnoiLz4NCjwvZz4NCjwvc3ZnPg0K) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(3) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzNfIj4NCgk8cGF0aCBpZD0iWE1MSURfNTlfIiBjbGFzcz0ic3QxIiBkPSJNLTkzNSw1MzEuNWMtNSwwLTksNC05LDljMCwzLDEuNSw1LjcsMy44LDcuM3YtMi43Yy0xLjEtMS4yLTEuOC0yLjktMS44LTQuN2MwLTMuOSwzLjEtNyw3LTcNCgkJczcsMy4xLDcsN2MwLDEuOC0wLjcsMy40LTEuOCw0Ljd2Mi43YzIuMy0xLjYsMy44LTQuMywzLjgtNy4zQy05MjYsNTM1LjUtOTMwLDUzMS41LTkzNSw1MzEuNXoiLz4NCgk8ZyBpZD0iWE1MSURfNTVfIj4NCgkJPHBhdGggaWQ9IlhNTElEXzU2XyIgY2xhc3M9InN0MSIgZD0iTS05MzIuOCw1NDUuNXYwLjhjMCwxLjItMSwyLjItMi4yLDIuMnMtMi4yLTEtMi4yLTIuMnYtMC44SC05MzIuOCBNLTkzMC44LDU0My41aC04LjR2Mi44DQoJCQljMCwyLjMsMS45LDQuMiw0LjIsNC4yczQuMi0xLjksNC4yLTQuMlY1NDMuNXoiLz4NCgk8L2c+DQoJPHJlY3QgaWQ9IlhNTElEXzU0XyIgeD0iLTk0MC4yIiB5PSI1NDAuMiIgY2xhc3M9InN0MSIgd2lkdGg9IjIiIGhlaWdodD0iMiIvPg0KCTxyZWN0IGlkPSJYTUxJRF81M18iIHg9Ii05MzEuOCIgeT0iNTQwLjIiIGNsYXNzPSJzdDEiIHdpZHRoPSIyIiBoZWlnaHQ9IjIiLz4NCjwvZz4NCjwvc3ZnPg0K) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(4) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItMzg3IDI4OSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtMzg3IDI4OSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tMzg3LDI4OWgyNHYyNGgtMjRWMjg5eiIvPg0KPHBhdGggY2xhc3M9InN0MSIgZD0iTS0zNjcuNywyOTQuOGwxLjQtMS40bC0xLjEtMS4xbC0xLjQsMS40Yy0xLjEtMC45LTIuNS0xLjQtNC0xLjRoMGMtNiwwLTEwLjksNC45LTEwLjksMTAuOXY2LjRoNi40DQoJYzYsMCwxMC45LTQuOSwxMC45LTEwLjloMEMtMzY2LjQsMjk3LjMtMzY2LjksMjk1LjktMzY3LjcsMjk0Ljh6IE0tMzc3LjIsMzA3LjdoLTQuNHYtNC40YzAtNC45LDQtOC45LDguOS04LjloMA0KCWMwLjksMCwxLjgsMC4zLDIuNSwwLjhsLTEuMiwxLjJoLTUuNXYxLjVoNGwtMi4zLDIuM2gtMy42djEuNWgyLjFsLTMuMiwzLjJsMS4xLDEuMWwzLjItMy4ydjIuMWgxLjV2LTMuNmwyLjMtMi4zdjRoMS41di01LjUNCglsMS4yLTEuMmMwLjUsMC43LDAuOCwxLjYsMC44LDIuNUMtMzY4LjQsMzAzLjctMzcyLjMsMzA3LjctMzc3LjIsMzA3Ljd6Ii8+DQo8L3N2Zz4NCg==) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(5) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzVfIj4NCgk8cGF0aCBpZD0iWE1MSURfNDRfIiBjbGFzcz0ic3QxIiBkPSJNLTkyOS40LDUzNy42YzAtMy4xLTIuNS01LjYtNS42LTUuNnMtNS42LDIuNS01LjYsNS42djguNWgyLjd2My44aDUuOHYtMy44aDIuN1Y1MzcuNnoNCgkJIE0tOTM0LjEsNTQ4aC0xLjh2LTEuOGgxLjhWNTQ4eiBNLTkzMS40LDU0NC4yaC0wLjdoLTUuOGgtMC43di02LjVjMC0yLDEuNi0zLjYsMy42LTMuNnMzLjYsMS42LDMuNiwzLjZWNTQ0LjJ6Ii8+DQo8L2c+DQo8L3N2Zz4NCg==) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(6) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzZfIj4NCgk8cGF0aCBpZD0iWE1MSURfNDBfIiBjbGFzcz0ic3QxIiBkPSJNLTkzMCw1MzUuOWgtNHYtM2gtMnYzaC00Yy0yLjIsMC00LDEuOC00LDR2NC4ydjIuMWMwLDEuOCwxLjUsMywzLDNjMC44LDAsMS42LTAuMywyLjItMQ0KCQlsMS42LTEuN2MwLjYtMC42LDEuNC0xLDIuMi0xczEuNiwwLjMsMi4yLDFsMS42LDEuN2MwLjYsMC43LDEuNCwxLDIuMiwxYzEuNSwwLDMtMS4yLDMtM1Y1NDR2LTQuMg0KCQlDLTkyNiw1MzcuNy05MjcuOCw1MzUuOS05MzAsNTM1Ljl6IE0tOTI4LDU0NHYyLjFjMCwwLjctMC42LDEtMSwxYy0wLjMsMC0wLjUtMC4xLTAuNy0wLjNsLTEuNi0xLjdjLTAuOS0xLTIuMy0xLjYtMy43LTEuNg0KCQlzLTIuNywwLjYtMy43LDEuNmwtMS42LDEuN2MtMC4yLDAuMi0wLjQsMC4zLTAuNywwLjNjLTAuNCwwLTEtMC4zLTEtMVY1NDR2LTQuMmMwLTEuMSwwLjktMiwyLTJoMTBjMS4xLDAsMiwwLjksMiwyVjU0NHoiLz4NCjwvZz4NCjwvc3ZnPg0K) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(7) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzdfIj4NCgk8cGF0aCBpZD0iWE1MSURfMzZfIiBjbGFzcz0ic3QxIiBkPSJNLTkyNiw1NDEuMWMwLTEuMS0wLjktMi0yLTJoLTEuOHYtMy4yYzAtMS4xLTAuOS0yLTItMmgtNi41Yy0xLjEsMC0yLDAuOS0yLDJ2My4yaC0xLjgNCgkJYy0xLjEsMC0yLDAuOS0yLDJ2NWgxLjdjMC40LDEuMiwxLjUsMiwyLjgsMmMxLjMsMCwyLjQtMC44LDIuOC0yaDMuMmMwLjQsMS4yLDEuNSwyLDIuOCwyYzEuMywwLDIuNC0wLjgsMi44LTJoMS43VjU0MS4xeg0KCQkgTS05MjgsNTQ0LjFoLTAuN2MwLDAsMCwwLDAsMGgtNS43YzAsMCwwLDAsMCwwaC0xLjJjMCwwLDAsMCwwLDBoLTUuN2MwLDAsMCwwLDAsMGgtMC43di0zaDMuOHYtNS4yaDYuNXY1LjJoMy44VjU0NC4xeiIvPg0KPC9nPg0KPC9zdmc+DQo=) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(8) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzhfIj4NCgk8cGF0aCBpZD0iWE1MSURfMzFfIiBjbGFzcz0ic3QxIiBkPSJNLTkyOC42LDU0NC44di00LjVjMC0zLjEtMi4xLTUuNi01LTYuMmMwLDAsMC0wLjEsMC0wLjFjMC0wLjgtMC42LTEuNC0xLjQtMS40DQoJCXMtMS40LDAuNi0xLjQsMS40YzAsMC4xLDAsMC4xLDAsMC4xYy0yLjksMC42LTUsMy4yLTUsNi4ydjQuNWgtMXYyaDFoMy42YzAsMS41LDEuMiwyLjgsMi44LDIuOHMyLjgtMS4yLDIuOC0yLjhoMy42aDF2LTJILTkyOC42eg0KCQkgTS05MzUsNTQ3LjVjLTAuNCwwLTAuOC0wLjMtMC44LTAuOGgxLjVDLTkzNC4zLDU0Ny4yLTkzNC42LDU0Ny41LTkzNSw1NDcuNXogTS05MzAuNiw1NDQuOGgtOC44di00LjVjMC0yLjQsMi00LjQsNC40LTQuNA0KCQljMi40LDAsNC40LDIsNC40LDQuNFY1NDQuOHoiLz4NCjwvZz4NCjwvc3ZnPg0K) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(9) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzI2XyI+DQoJPHBhdGggaWQ9IlhNTElEXzI3XyIgY2xhc3M9InN0MSIgZD0iTS05MzEuMyw1MzUuNWMxLjQsMCwyLjUsMS4xLDIuNSwyLjVjMCwyLjEtMi40LDQuNC02LjEsNy43Yy0zLjctMy40LTYuMS01LjYtNi4xLTcuNw0KCQljMC0xLjUsMS4yLTIuNiwyLjctMi41YzAuOCwwLjEsMS41LDAuNSwyLDEuMWwwLjcsMC44YzAuNCwwLjUsMS4xLDAuNSwxLjUsMGwwLjgtMC45Qy05MzIuOSw1MzUuOS05MzIuMSw1MzUuNS05MzEuMyw1MzUuNQ0KCQkgTS05MzEuMyw1MzMuNWMtMS40LDAtMi44LDAuNy0zLjcsMS43Yy0wLjktMS0yLjItMS43LTMuNy0xLjdjLTIuNSwwLTQuNSwyLTQuNSw0LjVjMCwzLjEsMi44LDUuNiw3LDkuNGwxLjIsMS4xbDEuMi0xLjENCgkJYzQuMi0zLjgsNy02LjMsNy05LjRDLTkyNi45LDUzNS41LTkyOC44LDUzMy41LTkzMS4zLDUzMy41eiIvPg0KPC9nPg0KPC9zdmc+DQo=) !important;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq:nth-of-type(10) {
	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxOS4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FscXVlXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSItOTQ3IDUyOSAyNCAyNCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAtOTQ3IDUyOSAyNCAyNDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6bm9uZTt9DQoJLnN0MXtmaWxsOiNGRkZGRkY7fQ0KPC9zdHlsZT4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0tOTQ3LDUyOWgyNHYyNGgtMjRWNTI5eiIvPg0KPGcgaWQ9IlhNTElEXzlfIj4NCgk8cGF0aCBpZD0iWE1MSURfMjNfIiBjbGFzcz0ic3QxIiBkPSJNLTkyOSw1MzQuMWgtMTJ2LTEuNmgtMnYxN2gydi01LjFoMTJjMS4xLDAsMi0wLjksMi0ydi02LjNDLTkyNyw1MzUtOTI3LjksNTM0LjEtOTI5LDUzNC4xeg0KCQkgTS05MjksNTQyLjRoLTEydi02LjNoMTJWNTQyLjR6Ii8+DQo8L2c+DQo8L3N2Zz4NCg==) !important;
}

.emojiPicker-3m1S-j .input-1Rv96N {
	font-size:var(--size1) !important;
}

.emojiPicker-3m1S-j .medium-2-DE5M .iconContainer-O4O2CN {
	height:16px;
	width:16px;
}

.diversitySelector-tmmMv0 .popout-2nUePc {
	flex-direction:row;
	margin:0;
	position:absolute;
	top:0;
	left:0;
	width:100%;
	border:none;
	background:var(--lv1);
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.1);
	height:100% !important;
	align-items:center;
	justify-content:center;
	z-index:100;
	cursor:default;
}

.diversitySelector-tmmMv0 .popout-2nUePc .item-16cXuq {
	background-color:transparent !important;
	flex-grow:1;
}

#bda-qem::before {
	content:'Select an Emote';
	color:rgba(255,255,255,0.85);
	height:100%;
	display:flex;
	align-items:center;
	margin:0 16px;
	font-size:var(--size2);
	font-weight:600;
	flex-grow:1;
}

#bda-qem {
	border-radius: 3px 3px 0 0;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.1), 0 2px 10px var(--lv1);
	background:var(--lv1);
	box-sizing:border-box;
	border:1px solid rgba(255,255,255,0.2) !important;
	border-bottom:none !important;
	justify-content:flex-end;
	overflow:hidden;
	position:relative;
	padding:0 !important;
}

#bda-qem button {
	font-size:var(--size2);
	background:transparent;
	flex-grow:0;
	border-radius:0;
	padding:0 12px;
	box-sizing:border-box;
	box-shadow:none;
	border:none;
	position:relative;
	border-bottom:2px solid transparent;
}

#bda-qem button:hover {
	background:rgba(255,255,255,0.05);
}

#bda-qem button:last-child {
	border-top-right-radius:3px;
}

#bda-qem button.active, 
#bda-qem button.active:hover {
	border-bottom:2px solid var(--accent);
	background-color:transparent;
	cursor:default;
}

.emojiPicker-3m1S-j::after,
#bda-qem-twitch-container::after, 
#bda-qem-favourite-container::after {
	content:'';
	position:absolute;
	bottom:-7px;
	right:14px;
	width:15px;
	height:15px;
	background:var(--lv1);
	pointer-events:none;
	z-index:100;
	transform:rotate(45deg);
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.1);
	box-sizing:border-box;
	border:1px solid rgba(255,255,255,0.2);
	border-top:none;
	border-left:none;
}

#bda-qem-twitch-container::after, 
#bda-qem-favourite-container::after {
	box-shadow:none;
}

.emojiPicker-3m1S-j .searchBar-2pWH0_ {
	background:transparent;
}

#bda-qem + .emojiPicker-3m1S-j::before {
	display:none;
}

/*9.f. Autocomplete*/

.channelTextArea-2VhZ6z.hasAutocomplete-2vGV2Z {
	z-index:20000 !important;
}

.autocomplete-1vrmpx {
	background:var(--lv1) !important;
	border-radius:0;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.07), 0 0 10px var(--lv1);
	z-index:1000;
}

.small-29zrCQ {
	font-size:var(--size2);
	font-weight:500;
}

.autocomplete-1vrmpx {	
	color:rgba(255,255,255,0.5) !important;
	text-transform:none;
}

.small-29zrCQ.statusRed--sZUpc {
	color:var(--danger) !important;
}

.divider-23swzi {
	display:none;
}

.autocompleteRowVertical-q1K4ky,
.autocompleteInner-zh20B_ {
	padding:0;
}

.selector-2IcQBU {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0;
	border-left: 2px solid rgba(255, 255, 255, .2)
}

.selector-2IcQBU .marginLeft8-1YseBe,
.selector-2IcQBU .flexChild-faoVW3 {
	font-size:var(--size2);
}

.selector-2IcQBU.selectorSelected-1_M1WV {
	background-color: rgba(216, 176, 176, 0.06) !important;
	border-color: var(--accent);
	box-shadow: inset 15px 0 15px -15px var(--accent);
}

.description-11DmNu,
.descriptionUsername-J_75O8,
.selector-2IcQBU .marginLeft4-3VaXdt {
	font-size:var(--size1);
}

.icon-3ZzoN7 {
	width:var(--size1);
	height:var(--size1);
}

/*9.g. Gif Picker*/



/*9.h. Toasts*/

body .bd-toasts {
	top: 0 !important;
	left: 0 !important;
	width: 100% !important;
	height: 100%;
	align-items: flex-end;
	justify-content: flex-end;
}

.bd-toasts .bd-toast::before {
	content: var(--toast-content);
	white-space:nowrap;
	overflow:hidden;
	text-overflow: ellipsis;
	position: absolute;
	top: 0;
	border-bottom: 1px solid rgba(0, 0, 0, .1);
	padding: 10px;
	left: 0;
	width: 100%;
	color: rgba(255, 255, 255, .8);
	background: rgba(0, 0, 0, .2);
	font-size: var(--size1);
	text-align:left;;
}

.bd-toasts .bd-toast::after {
	content: 'This notice will close in a few seconds.';
	font-size: var(--size2);
	font-weight:400;
	padding-top:5px;
}

.bd-toasts .bd-toast {
	--toast-content:'Notice';
	overflow: hidden;
	padding: 15px;
	padding-left: 15px;
	padding-top: 45px;
	padding-bottom:15px;
	position: relative;
	display:flex;
	flex-direction:column;
	margin-right: 10px;
	background-color: var(--lv1) !important;
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07), 0 0 12px rgba(255, 255, 255, .025);
	border: 1px solid var(--lv1);
	border-left: 2px solid var(--accent);
	border-radius: 0;
	height: auto;
	color: rgba(255, 255, 255, .65);
	font-size: var(--size1);
	font-weight:500;
}

.bd-toasts .bd-toast.icon {
	padding-left:55px !important;
}

.bd-toasts .bd-toast.icon {
	background-repeat: no-repeat;
	background-size: 35px;
	background-position: 10px 45px;
}

.bd-toasts .toast-success {
	border-left: 2px solid var(--success);
	--toast-content:'Success';
}

.bd-toasts .toast-info {
	border-left: 2px solid var(--information);
	--toast-content:'Information';
}

.bd-toasts .toast-danger,
.bd-toasts .toast-error {
	border-left: 2px solid var(--danger);
	--toast-content:'Error';
}

.bd-toasts .toast-warn,
.bd-toasts .toast-warning {
	border-left: 2px solid var(--caution);
	--toast-content:'Warning';
}

.friendnotifications-dnd-toast,
.friendnotifications-idle-toast,
.friendnotifications-mobile-toast,
.friendnotifications-offline-toast,
.friendnotifications-online-toast,
.friendnotifications-streaming-toast {
	background-color: var(--lv1) !important;
}

.bd-toasts .friendnotifications-online-toast {
	border-left-color: var(--success);
}

.bd-toasts .friendnotifications-offline-toast {
	border-left-color: var(--unavailable);
}

.bd-toasts .friendnotifications-idle-toast {
	border-left-color: var(--caution);
}

.bd-toasts .friendnotifications-dnd-toast {
	border-left-color: var(--danger);
}

.bd-toasts .friendnotifications-streaming-toast {
	border-left-color: var(--twitch-purple);
}

.bd-toasts .toast-inner {
	margin-left: 15px;
	text-align: left;
	text-indent: none;
	padding-bottom: 15px
}

.bd-toasts .toast-inner .toast-avatar {
	border-radius: var(--user-roundness);
	margin-right: -10px;
}

.powercord-toast {
	border:none;
	border-radius:0;
	bottom:10px;
	right:10px;
	border-left:2px solid var(--accent);
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07), 0 0 12px rgba(255, 255, 255, .025);
	z-index:3000;
}

.powercord-toast[data-toast-type=info] .icon {
  color:var(--accent) !important;
}

.powercord-toast .header {
	border-bottom: 1px solid rgba(0, 0, 0, .1);
	padding:10px 20px;
	padding-right:40px;
	color: rgba(255, 255, 255, .8);
	background: rgba(0, 0, 0, .2);
	color: rgba(255, 255, 255, .65);
	font-size: var(--size1);
	font-weight:500;
	align-items:center;
	border-radius:0;
	box-shadow:none !important;
}
  
.powercord-toast .header .dismiss {
	right:10px;
	position:absolute;
	margin-left:0;
}

.powercord-toast .contents .inner {
	color: rgba(255, 255, 255, .65);
	border:none;
	background:transparent;
	text-align:left;
	font-size: var(--size1);
	padding:0 5px;
}

/*9.i. Message Popouts*/

.messagesPopoutWrap-1MQ1bW {
	min-height:400px;
	margin-top:6px;
	box-shadow:0 2px 12px var(--lv1) !important;
	border-radius:0;
}

.messagesPopoutWrap-1MQ1bW .header-ykumBX {
	padding:8px 16px;
	font-size:var(--size1);
	box-sizing:border-box;
	background:rgba(255,255,255,0.15);
	box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

.full-motion .messagesPopoutWrap-1MQ1bW .header-ykumBX {
	backdrop-filter:blur(20px);
}

.messageGroupWrapper-o-Zw7G {
	border-radius:0;
	border:none;
	margin:10px 15px;
}

.messageGroupWrapper-o-Zw7G .messageGroupCozy-2iY6cT {
	background: rgba(255, 255, 255, 0.075) !important;
	border-left: 2px solid rgba(255, 255, 255, 0.075) !important;
}

.messagesPopoutWrap-1MQ1bW .header-ykumBX .wrapper-1sSZUt {
	font-weight:600;
	text-align:center;
}

.messagesPopoutWrap-1MQ1bW .header-ykumBX::after {
	content:'';
	position:absolute;
	z-index:-1;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:var(--lv1);
	opacity:.5;
}

.messagesPopoutWrap-1MQ1bW .scroller-3-yaBL {
	position:absolute;
	width:100%;
	padding-left:0;
}

.messagesPopoutWrap-1MQ1bW .scroller-3-yaBL ::-webkit-scrollbar {
	display:none;
}

.messagesPopoutWrap-1MQ1bW .scroller-3-yaBL .scroller-2FKFPG {
	padding-top:40px;
	padding-left:0;
}

.recentMentionsPopout-2fmau1 .scroller-3-yaBL .scroller-2FKFPG {
	padding-top:80px;
}

.actionButtons-1sUUug {
	top:4px;
	right:6px;	
	z-index:10;
}

.jumpButton-3DTcS_ {
	border-radius:0;
	padding:4px 6px;
	line-height:14px;
	transition:150ms ease;
	background:var(--lv1);
	box-shadow:0 2px 6px rgba(0,0,0,0.5);
}

.headerTabBarWrapper-27xBDe .tabBar-2UKwcE .tabBarItem-1Cg-MI,
.mentionFilter-1PQ6ey .label-12YslM,
.mentionFilter-1PQ6ey .value-2k8Drt,
.channelName-3kBz6H {
	font-size:var(--size1);
}

.channelSeparator-1MxuvT {
	margin:0 15px;
}

.hasMoreButton-1MELpI {
	background:rgba(255,255,255,0.07);
	transition:150ms ease;
	border-radius:0;
	color:#f6f6f7;
	text-transform:capitalize;
	margin:0;
	border:none !important;
	width:100%;
	position:absolute;
	bottom:0;
	left:0;
}

.full-motion .hasMoreButton-1MELpI {
	backdrop-filter:blur(10px);
}

.hasMoreButton-1MELpI:hover {
	background:var(--hover);
}

.hasMoreButton-1MELpI:active {
	height:28px;
}

.emptyPlaceholder-1zh-Eu {
	display:none;
}

.messagesPopoutWrap-1MQ1bW .avatar-1BDn8e[src*="254362351170617345"] + .header-23xsNx .timestamp-3ZCmNB::before {
	display:none;
}

/*9.j. RTC Connection/Noise Reduction*/



/*9.k. Call Region Selector*/

.quickSelectPopoutOption-opKBx9 {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0;
	border-left: 2px solid rgba(255, 255, 255, .2)
}

.quickSelectPopoutOption-opKBx9:hover {
	background-color: rgba(255, 255, 255, .06) !important;
	border-color: var(--accent);
	box-shadow: inset 15px 0 15px -15px var(--accent)
}

.quickSelectPopout-X1hvgV {
	direction:ltr;
	padding:0 !important;
	border-radius: 0 !important;
	background: var(--lv1) !important;
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .06), 0 2px 12px var(--lv1) !important;
	transform-origin: top !important;
}

.full-motion .quickSelectPopout-X1hvgV {
	animation: contextMenu .3s cubic-bezier(0, 0, 0, 1);
}

.check-2by_h9 {
	-webkit-mask:url(/assets/6acb20d5e709b34b6a7f36ec13648666.svg);
	background:var(--accent);
}

.regionSelectName-c5qL8O {
	text-align:left;
}

/*9.l. Mention Confirmation Popout*/

.everyonePopout-nEbJY3 {
	background:var(--lv1) !important;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.05), 0 0 12px rgba(255,255,255,0.07) !important;
	border-radius:0;
}

.everyonePopout-nEbJY3 .footer-2aTx0s {
	background:rgba(255,255,255,0.05) !important;
	font-size:var(--size2);
	border-top:1px solid var(--lv1);
}

.everyonePopout-nEbJY3 .footer-2aTx0s,
.everyonePopout-nEbJY3 .icon-2qOzDL {
	color:rgba(255,255,255,0.9) !important;
}

.everyonePopout-nEbJY3 .header-3_S6dz {
	font-size:var(--size1);
}

.everyonePopout-nEbJY3 .header-3_S6dz + div {
	font-size:var(--size2);
}

.everyonePopout-nEbJY3 .lookFilled-1Gx00P.colorBrand-3pXr91 {
	background:var(--success) !important;
	border-radius:0;
}

.everyonePopout-nEbJY3 .lookOutlined-3sRXeN.colorBrand-3pXr91 {
	background:var(--danger) !important;
	color:#fff;
	border:none;
	border-radius:0;
}

.buttonHint-2OxJB8 {
	margin-top:15px;
	font-size:var(--size2);
}

.buttonHint-2OxJB8 strong {
	background:rgba(255, 255, 255, .07) !important;
	box-shadow:0 2px 8px rgba(0, 0, 0, .25);
	padding:4px 6px;
	font-size:var(--size1);
	line-height:12px;
	border-radius:2px;
	cursor:default;
	transition:150ms ease box-shadow;
}

/*9.m. Role Selector*/

.container-VSDcQc {
	padding:0;
	border-radius: 0 !important;
	background: var(--lv1) !important;
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .06), 0 2px 12px var(--lv1) !important;
	transform-origin: top;
	padding:0;
	overflow:hidden;
	width:188px;
}

.full-motion .container-VSDcQc {
	animation: contextMenu .3s cubic-bezier(0, 0, 0, 1);
}

.container-VSDcQc .sectionTag-pXyto9,
.positionTop-3e-X1p .autocompleteHeaderBackground-30T70q {
	background:transparent !important;
	border-radius:0;
}

.container-VSDcQc .row-rrHHJU {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0;
	border-left: 2px solid rgba(255, 255, 255, .2);
	height:22px !important;
	line-height:22px;
}

.container-VSDcQc .header-2bNvm4 {
	position:absolute;
	top:0;
	left:0;
	background:transparent;
	background:rgba(255,255,255,0.15);
	box-shadow:0 2px 10px rgba(0,0,0,0.1);
	border-left: 2px solid rgba(255, 255, 255, .2);
	z-index:1;
	width:100%;
	height:35px;
	padding: 0 55px !important;
	box-sizing:border-box;
}

.full-motion .container-VSDcQc .header-2bNvm4 {
	backdrop-filter:blur(20px);
}

.container-VSDcQc .header-2bNvm4::after {
	content:'';
	position:absolute;
	z-index:-1;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:var(--lv1);
	opacity:.5;
}

.autocompleteHeaderBackground-30T70q,
.autocompleteShadow-iiGWFU {
	display:none;
}

.container-VSDcQc .scrollerWrap-2lJEkd .scroller-2FKFPG {
	padding-top:35px;
}

.autocompleteHeaderBackground-30T70q {
	padding: 0 10px;
}

.container-VSDcQc ::-webkit-scrollbar,
.autocompleteArrow-Zxoy9H {
	display:none;
}

.container-VSDcQc .row-rrHHJU.selected-1pIgLL {
	background: rgba(255, 255, 255, .06);
	border-color: var(--accent);
	box-shadow: inset 15px 0 15px -15px var(--accent)
}

.container-VSDcQc .row-rrHHJU span {
	font-size:var(--size2);
}

.container-VSDcQc .headerText-3i6A8K,	
.theme-dark .container-VSDcQc .input-1ppKdn,
.empty-3hoe1g .noResultsHeader-pqW4H-,
.empty-3hoe1g p {
	font-size:var(--size1);
	margin-bottom:0;
}

.container-VSDcQc .headerText-3i6A8K {
	color:var(--accent) !important;
}

/*9.n. Color Picker*/

#app-mount .colorPickerCustom-2CWBn2 {
	background: var(--lv1);
	border: none;
	transform:translateZ(0);
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .07), 0 2px 12px var(--lv1);
}

.saturation-1FDvtn>div, .saturation-1FDvtn>div>div {
	border-radius:0;
}

.hue-13HAGb>div>div {
	border-radius:8px;
}

.saturation-1FDvtn div[style*="position: absolute;"]::after {
	content:'';
	position:fixed;
	bottom:0;
	left:0;
	width:100%;
	z-index:100;
	height:2px;
	background:inherit;
}

.full-motion .saturation-1FDvtn div[style*="position: absolute;"]::after {
	animation:scaleX 250ms ease;
}

.hue-13HAGb>div>div>div>div {
	width: 14px !important;
	height: 14px !important;
	border-radius: 50% !important;
	box-shadow: 0 2px 12px rgba(0, 0, 0, 0.5) !important;
	transition: 250ms ease;
}

.hue-13HAGb>div>div>div>div:after {
	content: '';
	position: absolute;
	width: 100%;
	height: 100%;
	top:0;
	left:0;
	transform:scale(0);
	background: #fff;
	opacity: 0;
	transition: 250ms ease;
	border-radius: inherit;
	z-index: -1;
}

.hue-13HAGb>div>div>div>div:active:after {
	transform: scale(2.5);
	opacity: .25;
}

/*9.o. Roles Overflow*/

.overflowRolesPopout-140n9i .overflowRolesPopoutArrowWrapper-2Dx30g {
	display:none;
}

#app-mount .overflowRolesPopout-140n9i {
	background:var(--lv1);
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.04);
	padding:0;
	border-radius:0;
}

.overflowRolesPopout-140n9i .overflowRolesPopoutHeader-ciqDLE {
	margin: 0;
    background: rgba(255, 255, 255, .07) !important;
    height: 28px !important;
    line-height: 28px;
    padding: 0 10px;
    font-size: var(--size2);
    font-weight: 500;
    text-transform: capitalize;
    color: rgba(255, 255, 255, .5) !important;
    backdrop-filter: blur(10px);
    display: flex;
}

.overflowRolesPopout-140n9i .root-3-B5F3 {
	margin:5px;
}

/*9.p. Member Search*/

.popoutList-T9CKZQ {
	padding:0;
	border-radius: 0 !important;
	background: var(--lv1) !important;
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .06), 0 2px 12px var(--lv1) !important;
	transform-origin: top;
	padding:0;
}

.full-motion .popoutList-T9CKZQ {
	animation: contextMenu .3s cubic-bezier(0, 0, 0, 1);
}

.popoutList-T9CKZQ .selectableItem-1MP3MQ {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0;
	border-left: 2px solid rgba(255, 255, 255, .2);
}

.popoutList-T9CKZQ .selectableItem-1MP3MQ:hover,
.popoutList-T9CKZQ .selectableItem-1MP3MQ[style*="114, 137, 218"] {
	background-color: rgba(255, 255, 255, .06) !important;
	border-color: var(--accent);
	box-shadow: inset 15px 0 15px -15px var(--accent)
}

.scroller-2CvAgC {
	padding-bottom:0;
}

.popoutList-T9CKZQ .selectableItemLabel-1RKQjD {
	font-size:var(--size2);
}

.popoutList-T9CKZQ .container-cMG81i {
	background:transparent;
}

.popoutList-T9CKZQ .marginBottom8-AtZOdT,
.popoutList-T9CKZQ .iconLayout-3OgqU3 {
	display:none;
}

.popoutListInput-1l9TUI {
	background:rgba(255,255,255,0.07);
	box-shadow:0 2px 10px rgba(0,0,0,0.1);
	border-left: 2px solid rgba(255, 255, 255, .2);
	border-radius:0;
}

.popoutListEmpty-voOEBJ {
	background:transparent;
	border-radius:0;
	width:240px;
	height:30px;
}

.popoutList-T9CKZQ .small-2oHLgT .input-3Xdcic,
.popoutList-T9CKZQ .small-2oHLgT .tag-2gZFdE {
	height:30px;
}

.popoutList-T9CKZQ .small-2oHLgT .input-3Xdcic::-webkit-input-placeholder {
	font-size:var(--size1);
	color:rgba(255,255,255,0.5);
}

.popoutList-T9CKZQ .small-2oHLgT .input-3Xdcic {
	font-size:var(--size1);
	color:rgba(255,255,255,0.95);
}

/*9.q. Incoming Calls*/

.incomingCall-14zLcL {
	box-shadow:none !important;
	border-radius:0;
}

.actionButtons-3P85gM {
	display:flex;
}

.incomingCallInner-2VmFiR {
	border-radius:0;
	box-shadow:0 0 12px rgba(0,0,0,0.5);
	border:none;
	background:transparent;
	padding:20px !important;
	padding-top:10px !important;
}

.full-motion .incomingCallInner-2VmFiR {
	backdrop-filter:blur(10px);
}

.incomingCallInner-2VmFiR::after {
	content:'';
	top:0;
	left:0;
	width:100%;
	height:100%;
	position:absolute;
	z-index:-2;
	background:var(--lv1);
	opacity:.75;
}

.incomingCall-14zLcL::before {
	content:'';
	bottom:0;
	left:0;
	width:50%;
	height:2px;
	position:absolute;
	background:var(--success);
	box-shadow:0 0 12px var(--success);
	z-index:1;
}

.incomingCall-14zLcL::after {
	content:'';
	bottom:0;
	left:50%;
	width:50%;
	height:2px;
	position:absolute;
	background:var(--danger);
	box-shadow:0 0 12px var(--danger);
	z-index:1;
}

.incomingCall-14zLcL .incomingCallInner-2VmFiR .button-38aScr {
	margin:0 6px;
	min-width:unset;
	min-height:30px;
	max-height:30px !important;
	border-radius:0;
}

.incomingCall-14zLcL .incomingCallInner-2VmFiR .button-38aScr .actionIcon--D_WrW {
	display:none;
}

.incomingCall-14zLcL .incomingCallInner-2VmFiR .lookFilled-1Gx00P.colorPrimary-3b3xI6 {
	background:var(--danger);
}

.incomingCall-14zLcL .callAvatarWrapper-3Ax_xH,
.incomingCall-14zLcL .callAvatarMask-1SLlRi {
	height:75px !important;
	width:75px !important;
}

.callAvatarMask-1SLlRi foreignObject {
	mask:none;
}

.callAvatarVoice-29N_wG,
.callAvatarWrapper-3Ax_xH.voice-3bPYC- .ripple-1B3VJU {
	border-radius:var(--user-roundness);
}

.members-2BNiuX {
	font-size:var(--size1);
	margin-top:4px;
}

.subtitle-1H8FPn {
	font-size:var(--size2);
	margin-top:2px;
}

/*9.r. Notices*/

.platformIcon-2NdO9F {
	transform:scale(.75);
}

.notice-2FJMB4 {
	font-size:var(--size1);
	height:40px;
}

.noticeDanger-7u-yT9 {
	background:var(--danger);
}

.noticeInfo-3_iTE1 {
	background:var(--information);
}

.button-1MICoQ,
.notice-2FJMB4 {
	border-radius:0;
}

/*9.s. Search Helper*/

#app-mount .container-3ayLPN {
	padding:0 !important;
	border-radius: 0 !important;
	background: var(--lv1) !important;
	box-shadow: inset 0 0 0 100vmax rgba(255, 255, 255, .06), 0 2px 12px var(--lv1) !important;
	transform-origin: top;
	margin-top:15px;
}

.full-motion .container-3ayLPN {
	animation: contextMenu .3s cubic-bezier(0, 0, 0, 1);
}

.option-96V44q {
	margin: 0 !important;
	transition: 150ms ease all;
	padding: 7px 15px !important;
	border-radius: 0;
	height:18px;
	border-left: 2px solid rgba(255, 255, 255, .2);
	overflow:hidden;
	text-overflow:ellipsis;
}

.option-96V44q.selected-rZcOL- {
	background-color: rgba(255, 255, 255, .06) !important;
	border-color: var(--accent);
	box-shadow: inset 15px 0 15px -15px var(--accent);
}

.option-96V44q:after,
.resultsGroup-r_nuzN:before {
	display:none;
}

.plusIcon-v0BTrL {
	top:unset;
}

.option-96V44q span,
.resultsGroup-r_nuzN .header-2N-gMV,
.queryText-3xoOY7,
.queryText-3xoOY7 strong {
	text-transform:none;
	font-size:var(--size1);
	overflow:visible;
}

.option-96V44q {
	text-transform:none;
	font-size:var(--size1);
}

#app-mount .keybindShortcutSearchPopout-1MAfqq span {
	color:#fff !important;
	background:rgba(255,255,255,0.07);
	box-shadow:0 2px 6px rgba(0, 0, 0, 0.6);
	padding: 2px 3px;
	border-radius:2px;
	font-size:var(--size2);
	line-height:16px;
	transition:250ms ease;
	cursor:pointer;
}

#app-mount .keybindShortcutSearchPopout-1MAfqq span:hover {
	box-shadow:0 2px 10px rgba(0, 0, 0, 0.8), inset 0 0 0 1px var(--hover);
}

.resultsGroup-r_nuzN .header-2N-gMV {
	padding: 10px 14px;
	color: rgba(255, 255, 255, .8);
	background: rgba(255, 255, 255, .07);
	border-left: 2px solid rgba(255, 255, 255, .2);
}

.resultsGroup-r_nuzN {
	margin:0;
	padding:0;
}

.resultsGroup-r_nuzN .searchClearHistory-2cSSMO,
.resultsGroup-r_nuzN .searchLearnMore-3SQUAj {
	top:8px;
}

.queryContainer-RKFJW- {
	background:rgba(255,255,255,0.05) !important;
	border:none;
	padding:10px 16px;
	cursor:pointer;
}

.queryContainer-RKFJW-:hover {
	background:rgba(255,255,255,0.075) !important;
}

.datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z {
	background:rgba(255, 255, 255, .07) !important;
	box-shadow:0 2px 8px rgba(0, 0, 0, .25);
	padding:4px 6px;
	font-size:var(--size1);
	line-height:12px;
	border-radius:2px;
	cursor:default;
	transition:150ms ease box-shadow;
}

.datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z:hover {
	box-shadow:0 2px 12px rgba(0, 0, 0, .25), inset 0 0 0 1px var(--hover);
}

.react-datepicker__day--selected:after,
.react-datepicker__day:hover {
	background: var(--accent) !important;
}

.channelSeparator-1X1FuH .channelName-1QajIf,
.react-datepicker,
.react-datepicker__header,
.searchResult-3pzFAB .hit-NLlWXA {
	background:transparent !important;
}

.react-datepicker__day {
	border-color: transparent !important;
	background: rgba(0, 0, 0, .5) !important;
	transition: 150ms ease all !important;
}

.calendarPicker-2yf6Ci .react-datepicker__day-name,
.calendarPicker-2yf6Ci .react-datepicker__day,
.react-datepicker__day,
.searchResult-3pzFAB .hit-NLlWXA,
#app-mount .calendarPicker-2yf6Ci .react-datepicker__current-month,
.datePicker--XZbmJ .datePickerHint-3Q1Udw .hint-165cR4 {
	font-size:var(--size1);
	text-transform:none;
}

.calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--next,
.calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--previous,
#app-mount .datePicker--XZbmJ .datePickerHint-3Q1Udw,
#app-mount .calendarPicker-2yf6Ci .react-datepicker__current-month,
.searchResult-3pzFAB .hit-NLlWXA {
	border:none;
}

.displayAvatar-1wWlVM {
	border-radius:var(--user-roundness) !important;
}

/*10. Modals*/

/*10.a. Replace Backdrop*/

.backdrop-1wrmKB,
.backdropWithLayer-3_uhz4 {
	opacity: .75 !important;
	background: var(--lv1) !important;
}

/*10.b. Global Modals*/

.modal-yWgWj-,
.root-1gCeng {
  background:var(--lv1) !important;
  box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.04), 0 4px 24px 8px var(--lv1) !important;
}

.content-1EtbQh {
	border-radius:0;
}

.modal-yWgWj-::before,
.root-1gCeng::before {
  content:'';
  position:absolute;
  top:0;
  left:0;
  width:100%;
  z-index:100;
  height:2px;
  background:var(--accent);
  box-shadow:0 0 12px var(--accent);
}

.header-2tA9Os,
.footer-3rDWdC {
  background:var(--lv1) !important;
  box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.1), 0 0 12px rgba(0,0,0,0.25) !important;
  border-radius:0 !important; 
  padding:12px 20px;
}

.header-2tA9Os .defaultColor-1_ajX0,
.header-2tA9Os .small-29zrCQ {
  font-weight:500;
  text-transform:none;
  text-align:center;
}

.checked-3_4uQ9[style*="background-color: rgb(114, 137, 218)"] {
    background:var(--accent) !important;
}

.title-18-Ds0,
.headerText-2uyvpY {
	font-size:var(--size0);
	font-weight:600;
}

.titleDefault-a8-ZSr,
.header-2tA9Os .defaultColor-1_ajX0,
.content-8biNdB,
.content-8biNdB h1,
.block-2RXqH9 .pro-1T8RK7, 
.block-2RXqH9 .tip-2ab612, 
.tip-2ab612 {
    font-size:var(--size1);
}

.content-8biNdB h1 {
	text-transform:none ;
}

.close-1kwMUs {
  border-radius:3px !important;
  color:#fff;
}

.close-1kwMUs:active {
  box-shadow:0 0 6px var(--hover);
}

.guildName-3WI6ml,
.date-2WJGyu {
  text-align:center;
}

.inner-ZyuQk0 {
  padding:20px;
}

.small-3iVZYw {
	max-height:600px;
}

.close-1kwMUs {
	position:absolute;
	right:15px;
	top:50%;
	transforM:translateY(-50%) scale(.75);
}

.minorAction-OVxOke {
	font-size:var(--size4);
	padding-bottom:4px;
}

#app-mount .message-2qRu38 {
	background:transparent;
	box-shadow:none;
}

/*10.c. User Profile Modals*/

@keyframes profileModalIn {
	0% {
		transform:scale(.85);
		opacity:.5;
	}
	100% {
		transform:scale(1);
		opacity:1;
	}
}

@keyframes listRowIn {
	0% {
		transform:translateY(25px);
		opacity:0;
	}
	100% {
		transform:translateZ(0);
		opacity:1;
	}
}

@keyframes statusBarIn {
	0% {
		transform:scaleX(0);
		opacity:0;
	}
	100% {
		transform:none;
		opacity:1;
	}
}

@keyframes profileHeaderTop {
	0% {
		transform:translateY(-20px);
		opacity:0;
	}
	100% {
		transform:none;
		opacity:1;
	}
}

@keyframes profileHeaderBottom {
	0% {
		transform:translateY(20px);
		opacity:0;
	}
	100% {
		transform:none;
		opacity:1;
	}
}

@keyframes profileSide {
	0% {
		transform:translateX(-20px);
		opacity:0;
	}
	100% {
		transform:none;
		opacity:1;
	}
}

.root-SR8cQa {
	border-radius:0;
	box-shadow:0 2px 18px var(--lv1);
	transform-origin:bottom center;
}

.full-motion .root-SR8cQa {
	animation:profileModalIn 500ms ease;
}

.header-QKLPzZ {
	height:175px;
	align-items:flex-end;
	transform:translateZ(0);
	position:relative;
	z-index:2;
}

.header-QKLPzZ+div {
	display:flex;
	flex-direction:column;
}

.header-QKLPzZ+div:empty {
	background:rgba(255,255,255,0.1);
	border-top:1px solid rgba(255,255,255,0.05) !important;
	box-shadow:0 0 12px var(--lv1);
	height:45px;
}

.full-motion .header-QKLPzZ+div:empty {
	backdrop-filter:blur(20px);
}

.header-QKLPzZ+div:empty:after {
	content:'User Info';
	color:rgba(255,255,255,0.75);
	font-weight: 500;
	font-size:var(--size1);
	padding:0 15px;
	height:45px;
	display:flex;
	align-items:center;
	border-bottom:4px solid var(--hover);
	width:fit-content;
}

.header-QKLPzZ::after {
	content:'';
	position:absolute;
	top:0;
	left:0;
	width:100%;
	height:100%;
	z-index:-2;
	background-image: linear-gradient(to bottom, var(--lv1), rgba(255, 255, 255, 0.15) 100%), url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADwAAAA8CAMAAAANIilAAAAAHlBMVEX///////////////////////////////////////8V2MxSAAAACnRSTlMAAgYHCAoLDRAT6dja9gAAAHtJREFUSMft1DcSgEAMQ1FbCwX3vy7MUpA2UDi0cqnxa79uu4ynOGybrD9/xbhh3rRaN/xs1bohYQUJO2Cf7bHTdthrW+y2DfbbDwfsiyP2wSF745i9cNAKElaQsIKEFSSsLFCd/kq1bWwYG8aGsWFsGBvGhrFhbFi4YScBnULqiGhGjQAAAABJRU5ErkJggg==);
	background-size: 10%;
}

.body-3ND3kc {
	height:325px;
	background:rgba(255,255,255,0.05);
}

.header-QKLPzZ .avatar-3EQepX::before {
	content: '';
	position:fixed;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:var(--user-background) center/cover no-repeat;
	z-index:-1;
	box-sizing:border-box;
	box-shadow:inset 0 0 100vmax var(--lv1);
}

.header-QKLPzZ .avatar-3EQepX::after {
	content: '';
	position:fixed;
	top:0;
	left:0;
	width:100%;
	height:2px;
	--status-color:var(--accent);
	background-color:var(--status-color);
	box-shadow:0 0 12px var(--status-color);
	animation-delay:200ms;
	transform-origin:left;
}

.full-motion .header-QKLPzZ .avatar-3EQepX::after {
	animation:statusBarIn 500ms linear forwards;
	transform:scaleX(0);
	opacity:0;
}

.header-QKLPzZ .avatar-3EQepX[aria-label*=", Online"]::after {
	--status-color:var(--success);
}

.header-QKLPzZ .avatar-3EQepX[aria-label*=", Idle"]::after {
	--status-color:var(--caution);
}

.header-QKLPzZ .avatar-3EQepX[aria-label*=", Do Not Disturb"]::after {
	--status-color:var(--danger);
}

.header-QKLPzZ .avatar-3EQepX[aria-label*=", Offline"]::after {
	--status-color:var(--unavailable);
}

.header-QKLPzZ .avatar-3EQepX[aria-label*=", Invisible"]::after {
	--status-color:var(--invisible);
}

.header-QKLPzZ .avatar-3EQepX[aria-label*=", Streaming"]::after {
	--status-color:var(--twitch-purple);
}

.tabBarContainer-1s1u-z {
	background:rgba(255,255,255,0.1);
	border-top:1px solid rgba(255,255,255,0.05) !important;
	box-shadow:0 0 12px var(--lv1);
	z-index:1;
	padding:0;
	order:-1;
}

.full-motion .tabBarContainer-1s1u-z {
	backdrop-filter:blur(20px);
}

.root-SR8cQa .tabBar-2MuP6-,
.root-SR8cQa .tabBarItem-1b8RUP,
.root-SR8cQa .tabBarContainer-1s1u-z {
	height:45px;
	box-sizing:border-box;
}

.root-SR8cQa .tabBar-2MuP6- {
	position:relative;
	align-items:center;
}

.root-SR8cQa .tabBarItem-1b8RUP {
	margin:0;
	padding:0 15px;
	font-size:var(--size1);
	color:rgba(255,255,255,0.75) !important;
	font-weight:500;
	transition:150ms ease;
	height:25px;
	border-bottom:none;
	overflow:visible;
	box-sizing:border-box;
}

.root-SR8cQa .tabBarItem-1b8RUP.selected-3s45Ha {
	color:#fff;
}

.root-SR8cQa .tabBarItem-1b8RUP::before,
.root-SR8cQa .tabBarItem-1b8RUP::after {
	content:'';
	border-bottom:4px solid;
	height:calc(100% + 15px);
	width:100%;
	position:absolute;
	bottom:-9px;
	left:0;
	opacity:0;
}

.root-SR8cQa .tabBarItem-1b8RUP::after {
	border-color:var(--hover);
	transition:150ms ease opacity, 300ms ease transform;
	transform:scaleX(.5);
	z-index:2;
}

.root-SR8cQa .tabBarItem-1b8RUP.selected-3s45Ha::after,
.root-SR8cQa .tabBarItem-1b8RUP[style*="rgb(255, 255, 255);"]::after {
	opacity:1;
	transform:none;
}

.root-SR8cQa .tabBarItem-1b8RUP::before {
	border-color:rgba(255,255,255,0.07);
	transition:150ms ease opacity;
	z-index:1;
}

.root-SR8cQa .tabBarItem-1b8RUP:hover::before {
	opacity:1 !important;
}

.root-SR8cQa .tabBarItem-1b8RUP:nth-child(2) {
	border-left:1px solid rgba(255,255,255,0.1) !important;
	border-right:1px solid rgba(255,255,255,0.1) !important;
}

#app-mount .root-SR8cQa .actionButton-3W1xZa {
	position:absolute;
	right:12px;
	bottom:-36px;
}

.root-SR8cQa .additionalActionsIcon-1FoUlE {
	position:absolute;
	right:0;
	margin:20px;
	top:0;
	color:rgba(255,255,255,0.6) !important;
	padding:2px;
	border-radius:2px;
	width:18px;
	height:18px;
	transition:150ms ease;
	opacity:1 !important;
}

.full-motion .root-SR8cQa .additionalActionsIcon-1FoUlE {
	animation:profileHeaderTop 500ms ease forwards;
	transform:translateY(20px);
	animation-delay:350ms;
	opacity:0 !important;
}

.root-SR8cQa .additionalActionsIcon-1FoUlE:hover {
	color:#fff !important;
}

.root-SR8cQa .profileBadges-2vWUYb {
	margin:20px;
	position:absolute;
	bottom:0;
	right:0;
}

.full-motion .root-SR8cQa .profileBadges-2vWUYb {
	animation:profileHeaderBottom 500ms ease forwards;
	animation-delay:350ms;
	transform:translateY(20px);
	opacity:0;
}

.profileBadgeWrapper-rl_RO6:last-child {
	margin:0;
}

.profileBadge-2BqF-Z {
	width:20px;
	height:20px;
	transition:200ms ease;
}

.root-SR8cQa .profileBadges-2vWUYb:hover .profileBadge-2BqF-Z {
	opacity:.5;
}

.root-SR8cQa .profileBadges-2vWUYb .profileBadge-2BqF-Z:hover {
	opacity:1;
}

#app-mount .profileBadgeStaff-13GO7z {
	-webkit-mask: url(/assets/4358ad1fb423b346324516453750f569.svg) center/18px no-repeat;
	background:var(--accent) !important;
}

#app-mount .profileBadgePartner-SjK6L2 {
	background-image: url(/assets/33fedf082addb91d88abc272b4b18daa.svg);
}

#app-mount .profileBadgeHypesquad-1YIe7Z {
	background-image: url(/assets/6c73f47daf179ffade99f501bfc5101b.svg);
}

#app-mount .profileBadgeHypeSquadOnlineHouse1-xN6tES {
	background-image: url(/assets/64ae1208b6aefc0a0c3681e6be36f0ff.svg);
}

#app-mount .profileBadgeHypeSquadOnlineHouse2-3jBpXR {
	background-image: url(/assets/48cf0556d93901c8cb16317be2436523.svg);
}

#app-mount .profileBadgeHypeSquadOnlineHouse3-1YbjMX {
	background-image: url(/assets/9fdc63ef8a3cc1617c7586286c34e4f1.svg);
}

#app-mount .profileBadgeHypeSquadOnlineHouse1Winner-3OGyO6 {
	background-image: url(/assets/26a2dc8c9d70955a988cb377eec84c22.svg);
}

#app-mount .profileBadgeHypeSquadOnlineHouse2Winner-3GW5Sm {
	background-image: url(/assets/88d4f11bee9ea34fee59973b33353da0.svg);
}

#app-mount .profileBadgeHypeSquadOnlineHouse3Winner-2iVu11 {
	background-image: url(/assets/3245b2cd85b787b195ea8f6e10ef5790.svg);
}

#app-mount .profileBadgeEarlySupporter-PQB_0a {
	background-image: url(/assets/23e59d799436a73c024819f84ea0b627.svg);
}

#app-mount .profileBadgePremium-3kZ9Qj {
	background-image: url(/assets/386884eecd36164487505ddfbac35a9d.svg);
}

#app-mount .profileBadgeBugHunterLevel1-3oBv8Z {
	background-image: url(/assets/f61b8981e92feead854f52e5a1ba14f0.svg);
}

#app-mount .profileBadgeBugHunterLevel2-3tFzet {
	background-image: url(/assets/9286332d6e947c91fa91569efce431b0.svg);
}

#app-mount .profileGuildSubscriberlvl1-pKd1EZ {
	background-image: url(/assets/fbb6f1e160280f0e9aeb5d7c452eefe1.svg);
}

#app-mount .profileGuildSubscriberlvl2-1aIFve {
	background-image: url(/assets/b4b741bef6c3de9b29e2e0653e294620.svg);
}

#app-mount .profileGuildSubscriberlvl3-33AROf {
	background-image: url(/assets/93f5a393e22796a850931483166d7cb9.svg);
}

#app-mount .profileGuildSubscriberlvl4-2yY8EG {
	background-image: url(/assets/4c380650960c2b1e1584115d5e9ad63b.svg);
}

#app-mount .profileGuildSubscriberlvl5-1mIKQ8 {
	background-image: url(/assets/438dd7ecbffcf21b6cbf2773ade51a04.svg);
}

#app-mount .profileGuildSubscriberlvl6-2tCBLE {
	background-image: url(/assets/7a5f78de816fcecbbd1d5d6e635cc7dd.svg);
}

#app-mount .profileGuildSubscriberlvl7-3M0RQX {
	background-image: url(/assets/5a24b20b84fb3eafc138916729386e76.svg);
}

#app-mount .profileGuildSubscriberlvl8-2ot52H {
	background-image: url(/assets/f31d590e1f3629cd0b614330f4a8ee2a.svg);
}

#app-mount .profileGuildSubscriberlvl9-1qrrRa {
	background-image: url(/assets/9ba64f1fa91ccde0eba506c1c33f3d1a.svg);
}

.root-SR8cQa .nameTag-2IFDfL {
	margin:0 10px;
	position:relative;
	padding-bottom:var(--size1);
}

.full-motion .root-SR8cQa .nameTag-2IFDfL {
	animation:profileHeaderBottom 500ms ease forwards;
	animation-delay:350ms;
	transform:translateY(20px);
	opacity:0;
}

.username-3gJmXY {
	font-size:var(--sizelg);
}

.discriminator-xUhQkU {
	font-size:var(--size2);
	position:absolute;
	bottom:-4px;
}

.root-SR8cQa .bot-2Fta1w {
	margin:0;
	margin-right:4px;
}

.root-SR8cQa .content-3JfFJh {
	overflow:visible;
}

.headerFill-adLl4x,
.root-SR8cQa .topSectionPlaying-1J5E4n,
.root-SR8cQa .topSectionSpotify-1lI0-P,
.root-SR8cQa .topSectionStreaming-1Tpf5X,
.root-SR8cQa .topSectionXbox-3fWLjS {
	background:transparent;
	display:flex;
	flex-direction:column;
}

.activityProfile-2bJRaP {
	--activity-color:var(--accent);
	background:rgba(255,255,255,0.025);
	border-bottom:1px solid rgba(255, 255, 255, 0.075);
	padding:0;
	overflow:hidden;
}

.activityProfile-2bJRaP .activityName-1IaRLn {
	font-weight:600;
}

.activityProfile-2bJRaP .details-38sfDr, 
.activityProfile-2bJRaP .nameNormal-2lqVQK, 
.activityProfile-2bJRaP .playTime-2uWd1Z, 
.activityProfile-2bJRaP .state-Tt0LO3, 
.activityProfile-2bJRaP .timestamp-VjAZmo,
.activityProfile-2bJRaP .textRow-19NEd_,
.activityProfile-2bJRaP .activityName-1IaRLn {
	font-size:var(--size2);
}

.activityProfile-2bJRaP .textRow-19NEd_ {
	margin:0;
}

.assetsLargeImageActivityFeed-25vA7H, 
.assetsLargeImageActivityFeedXbox-3Tr-tf, 
.assetsLargeImageProfile-3YXDex {
	width: 50px;
	height:50px;
	border-radius:0; 
}

.assetsLargeMaskActivityFeed-3eznI9, 
.assetsLargeMaskProfile-1Qkfen {
	mask:none;
}

.assetsSmallImageActivityFeed-2LNxrO, 
.assetsSmallImageProfile-3JcsV1 {
	width: 18px;
	height:18px;
	border-radius:0;
}

.activityProfile-2bJRaP .headerText-1HLrL7 {
	display:none;
}

.activityProfile-2bJRaP .body-ZAhrcj {
	padding:10px 20px;
	align-items:center;
	justify-content:space-between;
}

.activityProfile-2bJRaP .assets-VMAukC,
.activityProfile-2bJRaP .gameIcon-_0rmMm {
	order:1;
	box-shadow:0 2px 14px var(--lv1);
}

.root-SR8cQa .contentNoImagesProfile-371_Rv {
	margin:0;
}

.root-SR8cQa .contentNoImagesProfile-371_Rv:empty:after {
    content:'Unknown';
	color:#fff;
	font-size:var(--size1);
	line-height:25px;
}

.root-SR8cQa .contentNoImagesProfile-371_Rv .textRow-19NEd_ {
	display:flex;
	align-items:center;
}

.contentImagesProfile-1Mz07W,
.contentGameImageProfile-WTVbI0 {
	margin:0;
}

.root-SR8cQa .topSectionSpotify-1lI0-P a  {
	color:var(--spotify-green) !important;
}

.root-SR8cQa .customStatusText-39gdCI {
	position:absolute;
	top:0;
	left:0;
	margin:20px;
	z-index:2;
	width:80%;
}

.full-motion .root-SR8cQa .customStatusText-39gdCI {
	animation:profileHeaderTop 500ms ease forwards;
	animation-delay:350ms;
	opacity:0;
	transform:translateY(20px);
}

.root-SR8cQa .activity-1ythUs:not(.activityProfile-2bJRaP) {
	padding:0;
}

.root-SR8cQa .activity-1ythUs:not(.activityProfile-2bJRaP) .activityHeader-1PExlk {
	display:none;
}

.listeningActionsProfile-1fYwru {
  margin-right:8px;
}

.topSectionSpotify-1lI0-P .activityProfile-2bJRaP .button-1Pkqso {
    border-radius:8px;
    box-shadow:0 0 6px rgba(0,0,0,0.35);
    width:30px;
	height:30px;
    min-height:unset;
    display:flex;
    align-items:center;
    min-width:unset;
	margin-right:8px;
	padding:0;
	background:rgba(255,255,255,0.1);
	border:none;
	color:var(--spotify-green);
}

.topSectionSpotify-1lI0-P .activityProfile-2bJRaP .button-1Pkqso:hover {
	background:rgba(255,255,255,0.15);
	box-shadow: 0 0 12px rgba(0,0,0,0.45);
}

.topSectionSpotify-1lI0-P .activityProfile-2bJRaP .button-1Pkqso .contents-18-Yxp div {
	overflow:visible;
	font-size:0 !important;
}

.root-SR8cQa .buttonSize-2Pmk-w {
    height:unset;
    min-height:unset;
}

.root-SR8cQa .disabledButtonOverlay {
    width:100%;
    height:100%;
}

.root-SR8cQa .spotifyButtonLogo-1El5JQ {
	margin:0;
}

.timeBarProfile-10b-fm {
	position:relative;
}

.timeBarProfile-10b-fm .bar-3urHkF,
.timeBarProfile-10b-fm .barInner-3NDaY_ {
	height:18px;
	border-radius:0;
	overflow:visible;
}

.timeBarProfile-10b-fm .bar-3urHkF + .flex-1xMQg5 {
	position:absolute;
	top:0;
	left:0;
	z-index:1;
	height:18px;
	display:flex;
	align-items:center;
	justify-content:space-between;
	width:calc(100% - 24px);
	margin:0 12px;
}

.connectedAccount-36nQx7 {
	background:rgba(255,255,255,0.1);
	box-shadow:0 0 6px var(--lv1);
	border-radius:2px;
	border:none;
	transition:250ms ease;
}

.connectedAccount-36nQx7:hover {
	box-shadow:0 2px 12px var(--lv1);
	transform:translateY(-2px);
}

.connectedAccountName-f8AEe2 {
	font-size:var(--size1);
	overflow:visible;
}

.userInfoSectionHeader-CBvMDh {
	font-size:var(--sizelg);
	text-transform:none;
	font-weight:500;
	color:rgba(255,255,255,0.75);
	display:flex;
	align-items:center;
	margin-bottom:14px;
}

.full-motion .userInfoSectionHeader-CBvMDh {
	animation:profileSide 500ms ease forwards;
	animation-delay:350ms;
	transform:translateX(-20px);
	opacity:0;
}

.userInfoSection-2acyCx+.userInfoSection-2acyCx {
	border-top:1px solid rgba(255,255,255,0.05);
}

.userInfoSection-2acyCx .note-QfFU8y textarea {
	background:transparent !important;
	font-size:var(--size1);
}

.full-motion .userInfoSection-2acyCx .note-QfFU8y textarea {
	animation:profileSide 500ms ease forwards;
	animation-delay:500ms;
	transform:translateX(-20px);
	opacity:0;
}

.userInfoSection-2acyCx .note-QfFU8y textarea::-webkit-input-placeholder {
	color:rgba(255,255,255,0.5) !important;
}

.userInfoSectionHeader-CBvMDh:before {
    content: '';
    margin-right: 5px;
    font-family: 'Segoe MDL2 Assets';
}

.listScroller-2_vlfo {
	display:flex;
	flex-wrap:wrap;
	padding:0 20px;
	padding-top:20px;
}

.listRow-hutiT_ {
	margin:8px;
	height:175px;
	width:calc(50% - 16px);
	box-sizing:border-box;
	overflow:hidden;
	justify-content:flex-start;
	align-items:flex-end;
	padding:20px;
	background:transparent !important;
	transition:250ms ease;
	box-shadow:0 1px 4px rgba(0,0,0,0.25);
	transform:translateZ(0);
}

.full-motion .listRow-hutiT_,
.full-motion .connectedAccount-36nQx7 {
	animation:listRowIn 250ms ease forwards;
	transform:translateY(25px);
	opacity:0;
}

.listName-3w10cx {
	flex-direction:column;
	align-items:flex-start;
}

.listRow-hutiT_:nth-child(2),
.connectedAccount-36nQx7:nth-child(2) {
	animation-delay:100ms;
}

.listRow-hutiT_:nth-child(3),
.connectedAccount-36nQx7:nth-child(3) {
	animation-delay:200ms;
}

.listRow-hutiT_:nth-child(4),
.connectedAccount-36nQx7:nth-child(4) {
	animation-delay:300ms;
}

.listRow-hutiT_:nth-child(5),
.connectedAccount-36nQx7:nth-child(5) {
	animation-delay:400ms;
}

.listRow-hutiT_:nth-child(6),
.connectedAccount-36nQx7:nth-child(6) {
	animation-delay:500ms;
}

.listRow-hutiT_:nth-child(7),
.connectedAccount-36nQx7:nth-child(7) {
	animation-delay:600ms;
}

.listRow-hutiT_:nth-child(8),
.connectedAccount-36nQx7:nth-child(8) {
	animation-delay:700ms;
}

.listName-3w10cx {
	font-weight:500;
	font-size:var(--size1);
	color:#fff;
}

.listRow-hutiT_ .listAvatar-1NlAhb:after {
	content:'';
	position:fixed;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background-image:inherit;
	background-size:100%;
	background-position:center;
	z-index:-1;
	filter:blur(25px);
	box-shadow:inset 0 0 0 100vmax rgba(0,0,0,0.4);
	transition:250ms ease;
}

.listRow-hutiT_:hover .listAvatar-1NlAhb:after {
	box-shadow:inset 0 0 0 100vmax rgba(0,0,0,0.5);
}

.listRow-hutiT_ .listAvatar-1NlAhb:not(.icon-3o6xvg)::after {
	box-shadow:none !important;
	filter:none;
	background:rgba(255,255,255,0.07);
}

.listRow-hutiT_:hover .listAvatar-1NlAhb:not(.icon-3o6xvg)::after {
	background:rgba(255,255,255,0.09);
}

.listAvatar-1NlAhb {
	height:50px;
	width:50px;
}

.guildNick-3uAm3i:empty::after {
	content:'No Nickname Set';
}

.emptyText-6tYmO5,
.username-2b1r56 {
	font-size:var(--size1);
	text-transform:none;
}

.listDiscriminator-253zfw,
.guildNick-3uAm3i {
	font-size:var(--size2);
}

.emptyIcon-pGTAhd {
	opacity:.8;
}

/*10.d. Expanded Image Modal*/

.downloadLink-1ywL9o {
	font-size:var(--size1);
}

/*10.e. Keyboard Shortcuts Modal*/

.keyboardShortcutsModal-3piNz7 {
	background:var(--lv1) !important;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.04) !important;
	border-radius:0;
	display:flex;
	flex-direction:column;
	max-width:750px;
	min-width:750px;
}

.modalSubtitle-1Pj5nv {  
	order:1;
}

.modalTitle-37O4n6,
.modalSubtitle-1Pj5nv {
	background:var(--lv1) !important;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.1), 0 0 12px rgba(0,0,0,0.25) !important;
	border-radius:0 !important; 
	padding:12px 20px;
	margin:0;
	font-size:var(--size1);
	font-weight:500;
}

.modalTitle-37O4n6 {
	font-size:var(--size0);
	justify-content:center;
}

.modalTitle-37O4n6 .content-2Add9f {
	margin-right:5px;
}

.keyboardShortcutsModal-3piNz7::before {
  content:'';
  position:absolute;
  top:0;
  left:0;
  width:100%;
  z-index:100;
  height:2px;
  background:var(--accent);
  box-shadow:0 0 12px var(--accent);
}

.ddrArrows-lSnH7P {
	bottom:0;
	right:0;
	top:unset;
	padding:12px 20px;
	height:21px;
	display:flex;
	align-items:center;
}

.ddrArrows-lSnH7P .arrow-2enltQ {
	height:25px;
	width:25px;
	background-size:25px;
	margin:0 20px;
}

#app-mount .keybindShortcut-1BD6Z1 span {
	color:#fff !important;
	background:rgba(255,255,255,0.07);
	box-shadow:0 2px 6px rgba(0, 0, 0, 0.6);
	padding: 2px 3px;
	border-radius:2px;
	font-size:var(--size2);
	line-height:16px;
	transition:250ms ease;
	border:none;
	display:flex;
	align-items:center;
	justify-content:center;
}

#app-mount .keybindShortcut-1BD6Z1 span:hover {
	box-shadow:0 2px 10px rgba(0, 0, 0, 0.8), inset 0 0 0 1px var(--hover) !important;
}

.ddrArrows-lSnH7P .arrow-2enltQ.down-2Ju7Q_ {
	transform: rotate(270deg);
}

.ddrArrows-lSnH7P .arrow-2enltQ.up-fkTose {
	transform: rotate(90deg);
}

.ddrArrows-lSnH7P .arrow-2enltQ.right-1AEPK3 {
	transform: rotate(180deg);
}

.ddrArrows-lSnH7P .arrow-2enltQ.active-2X6Ewx::before {
	background: var(--hover) !important;
}

.ddrArrows-lSnH7P .arrow-2enltQ,
.ddrArrows-lSnH7P .arrow-2enltQ:after,
.ddrArrows-lSnH7P .arrow-2enltQ:before {
	height: 25px !important;
	width: 25px !important;
}

.ddrArrows-lSnH7P .arrow-2enltQ:after,
.ddrArrows-lSnH7P .arrow-2enltQ:before {
	content: "";
	position: absolute;
	top: 0;
	left: 0;
}

.ddrArrows-lSnH7P .arrow-2enltQ {
	position: relative!important;
	animation: none!important;
	background: url(data:image/svg+xml;base64,IDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iNTAiIGhlaWdodD0iNTAiPjxnIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTMuMjIzOCAyMi40NDE5bC0xLjIyNCAxLjIyNHYyLjY0MWwxLjIyNCAxLjIyNCA0LjQzOCA0LjQzOCAxNy4wMzEgMTcuMDMxaDQuOTc4bDMuNDc4LTMuNTg5LjAxMi00LjY5LTguNTMyLTguNTMxaDE3LjYwMWwzLjkzMi0zLjkzMyAyLjM2Ni0yLjM2NXYtMS43OTdsLTYuMjk4LTYuMjk5aC0xNy41ODdsOC41MTgtOC41MTctLjAxMi00LjY4OS0zLjQ3OC0zLjU5aC00Ljk3OCIvPjxwYXRoIHN0cm9rZT0iI0ZGRiIgc3Ryb2tlLXdpZHRoPSIyIiBkPSJNMy4yMjM4IDIyLjQ0MTlsLTEuMjI0IDEuMjI0djIuNjQxbDEuMjI0IDEuMjI0IDQuNDM4IDQuNDM4IDE3LjAzMSAxNy4wMzFoNC45NzhsMy40NzgtMy41ODkuMDEyLTQuNjktOC41MzItOC41MzFoMTcuNjAxbDMuOTMyLTMuOTMzIDIuMzY2LTIuMzY1di0xLjc5N2wtNi4yOTgtNi4yOTloLTE3LjU4N2w4LjUxOC04LjUxNy0uMDEyLTQuNjg5LTMuNDc4LTMuNTloLTQuOTc4eiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTEwLjIwNjEgMjAuNTQ4NGwtNC40MzggNC40MzggNC40MzggNC40MzggMTQuMzY3IDE0LjM2N2gzLjU5OHYtMi45N2wtOC42MzYtOC42MzZ2LTIuMzA4bC00LjE3MS00LjE3MXYtMS40NGw0LjE3MS00LjE3MXYtMi4zMDhsOC42MzYtOC42MzZ2LTIuOTdoLTMuNTk4Ii8+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTE3LjE2MjggMjQuMjczNHYxLjQzOWwyLjg3OSAyLjg3OWgxMC4yNTVsLTIuODc5LTIuODc5di0xLjQzOWwyLjg3OS0yLjg3OWgtMTAuMjU1Ii8+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTI5LjI3NzIgMjQuMjczNHYxLjQzOWwyLjQzMiAyLjQzMy40NDcuNDQ2aDcuODYzbDIuODc5LTIuODc5di0xLjQzOWwtMi44NzktMi44NzloLTcuODYzbC0uNDQ3LjQ0NyIvPjxwYXRoIGQ9Ik0wIDBoNTB2NTBIMHoiLz48cGF0aCBkPSJNMCAxMDBoNTB2NTBIMHoiLz48L2c+PC9zdmc+) center/contain no-repeat!important
}

.ddrArrows-lSnH7P .arrow-2enltQ:before {
	-webkit-mask-size: cover;
	-webkit-mask: url(data:image/svg+xml;base64,IDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iNTAiIGhlaWdodD0iNTAiPjxnIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+PHBhdGggb3BhY2l0eT0iLjYiIGZpbGw9IiNDNkQ4RjUiIGQ9Ik0zLjIyMzggMjIuNDQxOWwtMS4yMjQgMS4yMjR2Mi42NDFsMS4yMjQgMS4yMjQgNC40MzggNC40MzggMTcuMDMxIDE3LjAzMWg0Ljk3OGwzLjQ3OC0zLjU4OS4wMTItNC42OS04LjUzMi04LjUzMWgxNy42MDFsMy45MzItMy45MzMgMi4zNjYtMi4zNjV2LTEuNzk3bC02LjI5OC02LjI5OWgtMTcuNTg3bDguNTE4LTguNTE3LS4wMTItNC42ODktMy40NzgtMy41OWgtNC45NzgiLz48cGF0aCBzdHJva2U9IiMyRjQ3NzciIHN0cm9rZS13aWR0aD0iMiIgZD0iTTMuMjIzOCAyMi40NDE5bC0xLjIyNCAxLjIyNHYyLjY0MWwxLjIyNCAxLjIyNCA0LjQzOCA0LjQzOCAxNy4wMzEgMTcuMDMxaDQuOTc4bDMuNDc4LTMuNTg5LjAxMi00LjY5LTguNTMyLTguNTMxaDE3LjYwMWwzLjkzMi0zLjkzMyAyLjM2Ni0yLjM2NXYtMS43OTdsLTYuMjk4LTYuMjk5aC0xNy41ODdsOC41MTgtOC41MTctLjAxMi00LjY4OS0zLjQ3OC0zLjU5aC00Ljk3OHoiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIvPjwvZz48L3N2Zz4=) center/contain no-repeat!important;
	background: var(--accent) !important;
}

.ddrArrows-lSnH7P .arrow-2enltQ:after {
	background: url(data:image/svg+xml;base64,IDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iNTAiIGhlaWdodD0iNTAiPjxnIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTEwLjIwNjEgMjAuNTQ4NGwtNC40MzggNC40MzggNC40MzggNC40MzggMTQuMzY3IDE0LjM2N2gzLjU5OHYtMi45N2wtOC42MzYtOC42MzZ2LTIuMzA4bC00LjE3MS00LjE3MXYtMS40NGw0LjE3MS00LjE3MXYtMi4zMDhsOC42MzYtOC42MzZ2LTIuOTdoLTMuNTk4Ii8+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTE3LjE2MjggMjQuMjczNHYxLjQzOWwyLjg3OSAyLjg3OWgxMC4yNTVsLTIuODc5LTIuODc5di0xLjQzOWwyLjg3OS0yLjg3OWgtMTAuMjU1Ii8+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTI5LjI3NzIgMjQuMjczNHYxLjQzOWwyLjQzMiAyLjQzMy40NDcuNDQ2aDcuODYzbDIuODc5LTIuODc5di0xLjQzOWwtMi44NzktMi44NzloLTcuODYzbC0uNDQ3LjQ0NyIvPjxwYXRoIGQ9Ik0wIDBoNTB2NTBIMHoiLz48L2c+PC9zdmc+) center/contain no-repeat!important
}

.keyboardShortcutList-13cQ-8 .keybindGroup--6Qp-w .keybindDescription-2RDbC2 {
	font-weight:500;
	font-size:var(--size2);
	text-transform:none;
}

.ragingDemon-bDcoXE .symbol-3ffeCr img {
    display:none;
}

.ragingDemon-bDcoXE .symbol-3ffeCr::after {
    content:'im too lazy to theme this lol';
    text-align:center;
    font-size:120px;
    font-weight:700;
}

/*10.f. Guild Invite Modal*/

#app-mount .contentWrapper-3WC1ID {
	border-radius:0;
	background:var(--lv1);
	transform:translateZ(0);
	overflow:hidden;
}

.contentWrapper-3WC1ID::before {
	content:'Invite';
	width:120px;
	height:30px;
	top:12px;
	left:-30px;
	background:var(--danger);
	position:absolute;
	color:#fff;
	display:flex;
	align-items:center;
	justify-content:center;
	transform:rotate(-45deg);
}

.contentWrapper-3WC1ID .inviteLargeIcon-HrAH61::after {
	content:'';
	position:fixed;
	top:0;
	left:0;
	width:100%;
	height:100%;
	transform:scale(1.2);
	background-image:inherit;
	z-index:-1;
	pointer-events:none;
	background-size:100%;
	background-position:center;
	background-repeat:no-repeat;
	filter:blur(15px);
	box-shadow:inset 0 0 0 100vmax rgba(0,0,0,0.5);
}

.pill-1dHPfk {
	border-radius:0;
}

/*10.g. Upload Modal*/

.uploadModal-2ifh8j {
    background: var(--lv1) !important;
    box-shadow: inset 0 0 0 100vmax rgba(255,255,255,0.04) !important;
    border-radius: 3px;
    display: flex;
	flex-direction: column;
	overflow:hidden;
}

.uploadModal-2ifh8j .inner-3nWsbo {
	margin:0;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K {
	flex-direction:column-reverse;
	height:fit-content;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .description-2ug5H_ .filename-ovv3c5 {
	font-size:var(--size1);
	font-weight:500;
	height:unset;
	margin:0 8px;
	overflow:visible;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .description-2ug5H_ {
    background: var(--success) !important;
    box-shadow:0 0 12px rgba(0,0,0,0.25) !important;
    border-radius: 0 !important;
	height:40px;
    padding: 0 12px;
	display:flex;
	align-items:center;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .description-2ug5H_::before {
	content:'';
	width:15px;
	height:15px;
	display:block
	position:relative;
	background:#fff;
	-webkit-mask:url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTEwLjQwNCA1LjExbC0xLjAxNS0xLjAxNC01LjA3NSA1LjA3NGMtMC44NDEgMC44NDEtMC44NDEgMi4yMDQgMCAzLjA0NHMyLjIwNCAwLjg0MSAzLjA0NSAwbDYuMDkwLTYuMDg5YzEuNDAyLTEuNDAxIDEuNDAyLTMuNjczIDAtNS4wNzRzLTMuNjc0LTEuNDAyLTUuMDc1IDBsLTYuMzk0IDYuMzkzYy0wLjAwNSAwLjAwNS0wLjAxMCAwLjAwOS0wLjAxNCAwLjAxMy0xLjk1NSAxLjk1NS0xLjk1NSA1LjEyMyAwIDcuMDc3czUuMTIzIDEuOTU0IDcuMDc4IDBjMC4wMDQtMC4wMDQgMC4wMDgtMC4wMDkgMC4wMTMtMC4wMTRsMC4wMDEgMC4wMDEgNC4zNjUtNC4zNjQtMS4wMTUtMS4wMTQtNC4zNjUgNC4zNjNjLTAuMDA1IDAuMDA0LTAuMDA5IDAuMDA5LTAuMDEzIDAuMDEzLTEuMzkyIDEuMzkyLTMuNjU2IDEuMzkyLTUuMDQ4IDBzLTEuMzkyLTMuNjU1IDAtNS4wNDdjMC4wMDUtMC4wMDUgMC4wMDktMC4wMDkgMC4wMTQtMC4wMTNsLTAuMDAxLTAuMDAxIDYuMzk1LTYuMzkzYzAuODM5LTAuODQgMi4yMDUtMC44NCAzLjA0NSAwczAuODM5IDIuMjA1IDAgMy4wNDRsLTYuMDkwIDYuMDg5Yy0wLjI4IDAuMjgtMC43MzUgMC4yOC0xLjAxNSAwcy0wLjI4LTAuNzM1IDAtMS4wMTRsNS4wNzUtNS4wNzV6Ij48L3BhdGg+PC9zdmc+') center/cover no-repeat;
}

.uploadModal-2ifh8j .footer-3mqk7D {
    background: var(--lv1) !important;
    box-shadow: inset 0 0 0 100vmax rgba(255,255,255,0.1), 0 0 12px rgba(0,0,0,0.25) !important;
	border-radius: 0 !important;
	padding:0 12px;
	height:50px;
}

#app-mount .uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr {
	margin:34px 16px !important;
	width:100px;
	height:100px;
	border-radius:0;
	position:relative;
}

.uploadModal-2ifh8j .inner-3nWsbo .comment-4IWttf {
	position:absolute;
	top:55px;
	left:125px;
	width:calc(100% - 175px);
}

.uploadModal-2ifh8j .primary-jw0I4K {
	font-size:var(--size1);
}

.uploadModal-2ifh8j .inner-3nWsbo .comment-4IWttf .label-3aiqT2 {
	text-transform:none;
	font-size:var(--size2);
}

.uploadModal-2ifh8j .slateTextArea-1Mkdgw::after, 
.uploadModal-2ifh8j .slateTextArea-1Mkdgw::before {
	content:none;
}

.uploadModal-2ifh8j .textArea-12jD-V {
	margin:0;
	padding:4px;
	height:100% !important;
	min-height:unset;
}

.uploadModal-2ifh8j .inner-MADQqc {
	min-height:94px;
}

.uploadModal-2ifh8j .placeholder-37qJjk, 
.uploadModal-2ifh8j .slateTextArea-1Mkdgw {
	left:0;
	height:94px;
	position:relative;
}

.uploadModal-2ifh8j .scrollableContainer-2NUZem {
	background:rgba(255,255,255,0.1) !important;
	box-shadow:0 0 4px var(--lv1);
	border-radius:3px;
}

.uploadModal-2ifh8j .webkit-HjD9Er .buttons-3JBrkn {
	margin-top:4px;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr:not(.image-2yrs5j) {
	opacity:.5;
	transition:100ms linear;
	cusror:pointer;
	background:#fff !important;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.image-2yrs5j::after {
	content:'';
	position:absolute;
	top:0;
	left:0;
	width:100%;
	height:100%;
	background:rgba(0,0,0,0.25) url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgOTYgOTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDk2IDk2OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSIgZmlsbD0iI2ZmZmZmZiI+CjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+Cgkuc3Qwe2ZpbGw6ICNmZmZmZmY7fQo8L3N0eWxlPgo8ZyBpZD0iWE1MSURfNV8iPgoJPHBhdGggaWQ9IlhNTElEXzlfIiBjbGFzcz0ic3QwIiBkPSJNMzkuMyw2MS4xaDE3LjVWNDMuNmgxMS43TDQ4LDIzLjJMMjcuNiw0My42aDExLjdWNjEuMXogTTI3LjYsNjdoNDAuOHY1LjhIMjcuNlY2N3oiLz4KPC9nPgo8L3N2Zz4K) center/50% no-repeat;
	opacity:1;
	transition:150ms ease;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.image-2yrs5j:hover::after {
	opacity:0;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr:hover {
	opacity:1;
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-3nWsbo .icon-kyxXVr {
	display:none;
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-3nWsbo .icons-1w691d {
	height:75px;
	background:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgOTYgOTYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDk2IDk2OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSIgZmlsbD0iI2ZmZmZmZiI+CjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+Cgkuc3Qwe2ZpbGw6ICNmZmZmZmY7fQo8L3N0eWxlPgo8ZyBpZD0iWE1MSURfNV8iPgoJPHBhdGggaWQ9IlhNTElEXzlfIiBjbGFzcz0ic3QwIiBkPSJNMzkuMyw2MS4xaDE3LjVWNDMuNmgxMS43TDQ4LDIzLjJMMjcuNiw0My42aDExLjdWNjEuMXogTTI3LjYsNjdoNDAuOHY1LjhIMjcuNlY2N3oiLz4KPC9nPgo8L3N2Zz4K) center/cover no-repeat;
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-3nWsbo .title-2Vtl4y {
	font-size:var(--sizelg);
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-3nWsbo .instructions-2Du9gG {
	font-size:var(--size2);
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.video-27RLEH {
	-webkit-mask: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTE0LjM0MSAzLjU3OWMtMC4zNDctMC40NzMtMC44MzEtMS4wMjctMS4zNjItMS41NThzLTEuMDg1LTEuMDE1LTEuNTU4LTEuMzYyYy0wLjgwNi0wLjU5MS0xLjE5Ny0wLjY1OS0xLjQyMS0wLjY1OWgtNy43NWMtMC42ODkgMC0xLjI1IDAuNTYxLTEuMjUgMS4yNXYxMy41YzAgMC42ODkgMC41NjEgMS4yNSAxLjI1IDEuMjVoMTEuNWMwLjY4OSAwIDEuMjUtMC41NjEgMS4yNS0xLjI1di05Ljc1YzAtMC4yMjQtMC4wNjgtMC42MTUtMC42NTktMS40MjF2MCAwek0xMi4yNzEgMi43MjljMC40OCAwLjQ4IDAuODU2IDAuOTEyIDEuMTM0IDEuMjcxaC0yLjQwNnYtMi40MDVjMC4zNTkgMC4yNzggMC43OTIgMC42NTQgMS4yNzEgMS4xMzR2MCAwek0xNCAxNC43NWMwIDAuMTM2LTAuMTE0IDAuMjUtMC4yNSAwLjI1aC0xMS41Yy0wLjEzNSAwLTAuMjUtMC4xMTQtMC4yNS0wLjI1di0xMy41YzAtMC4xMzUgMC4xMTUtMC4yNSAwLjI1LTAuMjUgMCAwIDcuNzQ5LTAgNy43NSAwdjMuNWMwIDAuMjc2IDAuMjI0IDAuNSAwLjUgMC41aDMuNXY5Ljc1eiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik00IDhoNXY1aC01di01eiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik05IDEwbDMtMnY1bC0zLTJ6Ij48L3BhdGg+PC9zdmc+) center/50% no-repeat;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.acrobat-3K1PC6 {
	-webkit-mask: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTEzLjE1NiA5LjIxMWMtMC4yMTMtMC4yMS0wLjY4Ni0wLjMyMS0xLjQwNi0wLjMzMS0wLjQ4Ny0wLjAwNS0xLjA3MyAwLjAzOC0xLjY5IDAuMTI0LTAuMjc2LTAuMTU5LTAuNTYxLTAuMzMzLTAuNzg0LTAuNTQyLTAuNjAxLTAuNTYxLTEuMTAzLTEuMzQtMS40MTUtMi4xOTcgMC4wMjAtMC4wODAgMC4wMzgtMC4xNSAwLjA1NC0wLjIyMiAwIDAgMC4zMzktMS45MjMgMC4yNDktMi41NzMtMC4wMTItMC4wODktMC4wMjAtMC4xMTUtMC4wNDQtMC4xODRsLTAuMDI5LTAuMDc2Yy0wLjA5Mi0wLjIxMi0wLjI3My0wLjQzNy0wLjU1Ni0wLjQyNWwtMC4xNzEtMC4wMDVjLTAuMzE2IDAtMC41NzMgMC4xNjEtMC42NCAwLjQwMy0wLjIwNSAwLjc1NyAwLjAwNyAxLjg4OSAwLjM5IDMuMzU1bC0wLjA5OCAwLjIzOWMtMC4yNzUgMC42Ny0wLjYxOSAxLjM0NS0wLjkyMyAxLjk0bC0wLjA0MCAwLjA3N2MtMC4zMiAwLjYyNi0wLjYxIDEuMTU3LTAuODczIDEuNjA3bC0wLjI3MSAwLjE0NGMtMC4wMjAgMC4wMTAtMC40ODUgMC4yNTctMC41OTQgMC4zMjMtMC45MjYgMC41NTMtMS41MzkgMS4xOC0xLjY0MSAxLjY3OC0wLjAzMiAwLjE1OS0wLjAwOCAwLjM2MiAwLjE1NiAwLjQ1NmwwLjI2MyAwLjEzMmMwLjExNCAwLjA1NyAwLjIzNCAwLjA4NiAwLjM1NyAwLjA4NiAwLjY1OSAwIDEuNDI1LTAuODIxIDIuNDgtMi42NjIgMS4yMTgtMC4zOTYgMi42MDQtMC43MjYgMy44MTktMC45MDggMC45MjYgMC41MjEgMi4wNjUgMC44ODMgMi43ODMgMC44ODMgMC4xMjggMCAwLjIzOC0wLjAxMiAwLjMyNy0wLjAzNiAwLjEzOC0wLjAzNyAwLjI1NC0wLjExNSAwLjMyNS0wLjIyMiAwLjEzOS0wLjIxIDAuMTY4LTAuNDk5IDAuMTMtMC43OTUtMC4wMTEtMC4wODgtMC4wODEtMC4xOTYtMC4xNTctMC4yNzF6TTMuMzA3IDEyLjcyYzAuMTItMC4zMjkgMC41OTYtMC45NzkgMS4zLTEuNTU2IDAuMDQ0LTAuMDM2IDAuMTUzLTAuMTM4IDAuMjUzLTAuMjMzLTAuNzM2IDEuMTc0LTEuMjI5IDEuNjQyLTEuNTUzIDEuNzg4ek03LjQ3NiAzLjEyYzAuMjEyIDAgMC4zMzMgMC41MzQgMC4zNDMgMS4wMzVzLTAuMTA3IDAuODUzLTAuMjUyIDEuMTEzYy0wLjEyLTAuMzg1LTAuMTc5LTAuOTkyLTAuMTc5LTEuMzg5IDAgMC0wLjAwOS0wLjc1OSAwLjA4OC0wLjc1OXYwek02LjIzMiA5Ljk2MWMwLjE0OC0wLjI2NCAwLjMwMS0wLjU0MyAwLjQ1OC0wLjgzOSAwLjM4My0wLjcyNCAwLjYyNC0xLjI5IDAuODA0LTEuNzU1IDAuMzU4IDAuNjUxIDAuODA0IDEuMjA1IDEuMzI4IDEuNjQ5IDAuMDY1IDAuMDU1IDAuMTM1IDAuMTExIDAuMjA3IDAuMTY2LTEuMDY2IDAuMjExLTEuOTg3IDAuNDY3LTIuNzk4IDAuNzc5djB6TTEyLjk1MiA5LjkwMWMtMC4wNjUgMC4wNDEtMC4yNTEgMC4wNjQtMC4zNyAwLjA2NC0wLjM4NiAwLTAuODY0LTAuMTc2LTEuNTMzLTAuNDY0IDAuMjU3LTAuMDE5IDAuNDkzLTAuMDI5IDAuNzA1LTAuMDI5IDAuMzg3IDAgMC41MDItMC4wMDIgMC44OCAwLjA5NXMwLjM4MyAwLjI5MyAwLjMxOCAwLjMzM3YweiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik0xNC4zNDEgMy41NzljLTAuMzQ3LTAuNDczLTAuODMxLTEuMDI3LTEuMzYyLTEuNTU4cy0xLjA4NS0xLjAxNS0xLjU1OC0xLjM2MmMtMC44MDYtMC41OTEtMS4xOTctMC42NTktMS40MjEtMC42NTloLTcuNzVjLTAuNjg5IDAtMS4yNSAwLjU2MS0xLjI1IDEuMjV2MTMuNWMwIDAuNjg5IDAuNTYxIDEuMjUgMS4yNSAxLjI1aDExLjVjMC42ODkgMCAxLjI1LTAuNTYxIDEuMjUtMS4yNXYtOS43NWMwLTAuMjI0LTAuMDY4LTAuNjE1LTAuNjU5LTEuNDIxdjB6TTEyLjI3MSAyLjcyOWMwLjQ4IDAuNDggMC44NTYgMC45MTIgMS4xMzQgMS4yNzFoLTIuNDA2di0yLjQwNWMwLjM1OSAwLjI3OCAwLjc5MiAwLjY1NCAxLjI3MSAxLjEzNHYwek0xNCAxNC43NWMwIDAuMTM2LTAuMTE0IDAuMjUtMC4yNSAwLjI1aC0xMS41Yy0wLjEzNSAwLTAuMjUtMC4xMTQtMC4yNS0wLjI1di0xMy41YzAtMC4xMzUgMC4xMTUtMC4yNSAwLjI1LTAuMjUgMCAwIDcuNzQ5LTAgNy43NSAwdjMuNWMwIDAuMjc2IDAuMjI0IDAuNSAwLjUgMC41aDMuNXY5Ljc1eiI+PC9wYXRoPjwvc3ZnPg==) center/50% no-repeat;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.ae-1Y5Jq3 {
	-webkit-mask: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTYgNmw1IDMuNS01IDMuNXYtN3oiPjwvcGF0aD48cGF0aCBmaWxsPSIjMDAwMDAwIiBkPSJNMTQuMzQxIDMuNTc5Yy0wLjM0Ny0wLjQ3My0wLjgzMS0xLjAyNy0xLjM2Mi0xLjU1OHMtMS4wODUtMS4wMTUtMS41NTgtMS4zNjJjLTAuODA2LTAuNTkxLTEuMTk3LTAuNjU5LTEuNDIxLTAuNjU5aC03Ljc1Yy0wLjY4OSAwLTEuMjUgMC41NjEtMS4yNSAxLjI1djEzLjVjMCAwLjY4OSAwLjU2MSAxLjI1IDEuMjUgMS4yNWgxMS41YzAuNjg5IDAgMS4yNS0wLjU2MSAxLjI1LTEuMjV2LTkuNzVjMC0wLjIyNC0wLjA2OC0wLjYxNS0wLjY1OS0xLjQyMXpNMTIuMjcxIDIuNzI5YzAuNDggMC40OCAwLjg1NiAwLjkxMiAxLjEzNCAxLjI3MWgtMi40MDZ2LTIuNDA1YzAuMzU5IDAuMjc4IDAuNzkyIDAuNjU0IDEuMjcxIDEuMTM0ek0xNCAxNC43NWMwIDAuMTM2LTAuMTE0IDAuMjUtMC4yNSAwLjI1aC0xMS41Yy0wLjEzNSAwLTAuMjUtMC4xMTQtMC4yNS0wLjI1di0xMy41YzAtMC4xMzUgMC4xMTUtMC4yNSAwLjI1LTAuMjUgMCAwIDcuNzQ5LTAgNy43NSAwdjMuNWMwIDAuMjc2IDAuMjI0IDAuNSAwLjUgMC41aDMuNXY5Ljc1eiI+PC9wYXRoPjwvc3ZnPg==) center/50% no-repeat;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.sketch-ZMuo7D,
.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.ai-11KAaB,
.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.photoshop-1UWfyZ,
.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.ps-2T6Jrl {
	-webkit-mask: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTEzIDE0aC0xMHYtMmwzLTUgNC4xMDkgNSAyLjg5MS0ydjR6Ij48L3BhdGg+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTEzIDcuNWMwIDAuODI4LTAuNjcyIDEuNS0xLjUgMS41cy0xLjUtMC42NzItMS41LTEuNSAwLjY3Mi0xLjUgMS41LTEuNWMwLjgyOCAwIDEuNSAwLjY3MiAxLjUgMS41eiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik0xNC4zNDEgMy41NzljLTAuMzQ3LTAuNDczLTAuODMxLTEuMDI3LTEuMzYyLTEuNTU4cy0xLjA4NS0xLjAxNS0xLjU1OC0xLjM2MmMtMC44MDYtMC41OTEtMS4xOTctMC42NTktMS40MjEtMC42NTloLTcuNzVjLTAuNjg5IDAtMS4yNSAwLjU2MS0xLjI1IDEuMjV2MTMuNWMwIDAuNjg5IDAuNTYxIDEuMjUgMS4yNSAxLjI1aDExLjVjMC42ODkgMCAxLjI1LTAuNTYxIDEuMjUtMS4yNXYtOS43NWMwLTAuMjI0LTAuMDY4LTAuNjE1LTAuNjU5LTEuNDIxek0xMi4yNzEgMi43MjljMC40OCAwLjQ4IDAuODU2IDAuOTEyIDEuMTM0IDEuMjcxaC0yLjQwNnYtMi40MDVjMC4zNTkgMC4yNzggMC43OTIgMC42NTQgMS4yNzEgMS4xMzR6TTE0IDE0Ljc1YzAgMC4xMzYtMC4xMTQgMC4yNS0wLjI1IDAuMjVoLTExLjVjLTAuMTM1IDAtMC4yNS0wLjExNC0wLjI1LTAuMjV2LTEzLjVjMC0wLjEzNSAwLjExNS0wLjI1IDAuMjUtMC4yNSAwIDAgNy43NDktMCA3Ljc1IDB2My41YzAgMC4yNzYgMC4yMjQgMC41IDAuNSAwLjVoMy41djkuNzV6Ij48L3BhdGg+PC9zdmc+) center/50% no-repeat;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.archive-2hqXug {
	-webkit-mask: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTE0LjM0MSAzLjU3OWMtMC4zNDctMC40NzMtMC44MzEtMS4wMjctMS4zNjItMS41NThzLTEuMDg1LTEuMDE1LTEuNTU4LTEuMzYyYy0wLjgwNi0wLjU5MS0xLjE5Ny0wLjY1OS0xLjQyMS0wLjY1OWgtNy43NWMtMC42ODkgMC0xLjI1IDAuNTYxLTEuMjUgMS4yNXYxMy41YzAgMC42ODkgMC41NjEgMS4yNSAxLjI1IDEuMjVoMTEuNWMwLjY4OSAwIDEuMjUtMC41NjEgMS4yNS0xLjI1di05Ljc1YzAtMC4yMjQtMC4wNjgtMC42MTUtMC42NTktMS40MjF2MCAwek0xMi4yNzEgMi43MjljMC40OCAwLjQ4IDAuODU2IDAuOTEyIDEuMTM0IDEuMjcxaC0yLjQwNnYtMi40MDVjMC4zNTkgMC4yNzggMC43OTIgMC42NTQgMS4yNzEgMS4xMzR2MCAwek0xNCAxNC43NWMwIDAuMTM2LTAuMTE0IDAuMjUtMC4yNSAwLjI1aC0xMS41Yy0wLjEzNSAwLTAuMjUtMC4xMTQtMC4yNS0wLjI1di0xMy41YzAtMC4xMzUgMC4xMTUtMC4yNSAwLjI1LTAuMjUgMCAwIDcuNzQ5LTAgNy43NSAwdjMuNWMwIDAuMjc2IDAuMjI0IDAuNSAwLjUgMC41aDMuNXY5Ljc1eiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik00IDFoMnYxaC0ydi0xeiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik02IDJoMnYxaC0ydi0xeiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik00IDNoMnYxaC0ydi0xeiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik02IDRoMnYxaC0ydi0xeiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik00IDVoMnYxaC0ydi0xeiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik02IDZoMnYxaC0ydi0xeiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik00IDdoMnYxaC0ydi0xeiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik02IDhoMnYxaC0ydi0xeiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik00IDEzLjI1YzAgMC40MTIgMC4zMzggMC43NSAwLjc1IDAuNzVoMi41YzAuNDEyIDAgMC43NS0wLjMzOCAwLjc1LTAuNzV2LTIuNWMwLTAuNDEyLTAuMzM4LTAuNzUtMC43NS0wLjc1aC0xLjI1di0xaC0ydjQuMjV6TTcgMTJ2MWgtMnYtMWgyeiI+PC9wYXRoPjwvc3ZnPg==) center/50% no-repeat;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.code-aoB-kL,
.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.webcode-22GGLX,
.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.document-2cvI0u {
	-webkit-mask: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTE0LjM0MSAzLjU3OWMtMC4zNDctMC40NzMtMC44MzEtMS4wMjctMS4zNjItMS41NThzLTEuMDg1LTEuMDE1LTEuNTU4LTEuMzYyYy0wLjgwNi0wLjU5MS0xLjE5Ny0wLjY1OS0xLjQyMS0wLjY1OWgtNy43NWMtMC42ODkgMC0xLjI1IDAuNTYxLTEuMjUgMS4yNXYxMy41YzAgMC42ODkgMC41NjEgMS4yNSAxLjI1IDEuMjVoMTEuNWMwLjY4OSAwIDEuMjUtMC41NjEgMS4yNS0xLjI1di05Ljc1YzAtMC4yMjQtMC4wNjgtMC42MTUtMC42NTktMS40MjF6TTEyLjI3MSAyLjcyOWMwLjQ4IDAuNDggMC44NTYgMC45MTIgMS4xMzQgMS4yNzFoLTIuNDA2di0yLjQwNWMwLjM1OSAwLjI3OCAwLjc5MiAwLjY1NCAxLjI3MSAxLjEzNHpNMTQgMTQuNzVjMCAwLjEzNi0wLjExNCAwLjI1LTAuMjUgMC4yNWgtMTEuNWMtMC4xMzUgMC0wLjI1LTAuMTE0LTAuMjUtMC4yNXYtMTMuNWMwLTAuMTM1IDAuMTE1LTAuMjUgMC4yNS0wLjI1IDAgMCA3Ljc0OS0wIDcuNzUgMHYzLjVjMCAwLjI3NiAwLjIyNCAwLjUgMC41IDAuNWgzLjV2OS43NXoiPjwvcGF0aD48cGF0aCBmaWxsPSIjMDAwMDAwIiBkPSJNMTEuNSAxM2gtN2MtMC4yNzYgMC0wLjUtMC4yMjQtMC41LTAuNXMwLjIyNC0wLjUgMC41LTAuNWg3YzAuMjc2IDAgMC41IDAuMjI0IDAuNSAwLjVzLTAuMjI0IDAuNS0wLjUgMC41eiI+PC9wYXRoPjxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik0xMS41IDExaC03Yy0wLjI3NiAwLTAuNS0wLjIyNC0wLjUtMC41czAuMjI0LTAuNSAwLjUtMC41aDdjMC4yNzYgMCAwLjUgMC4yMjQgMC41IDAuNXMtMC4yMjQgMC41LTAuNSAwLjV6Ij48L3BhdGg+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTExLjUgOWgtN2MtMC4yNzYgMC0wLjUtMC4yMjQtMC41LTAuNXMwLjIyNC0wLjUgMC41LTAuNWg3YzAuMjc2IDAgMC41IDAuMjI0IDAuNSAwLjVzLTAuMjI0IDAuNS0wLjUgMC41eiI+PC9wYXRoPjwvc3ZnPg==) center/50% no-repeat;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.audio-14DQXq {
	margin:0;
	-webkit-mask: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTE0LjM0MSAzLjU3OWMtMC4zNDctMC40NzMtMC44MzEtMS4wMjctMS4zNjItMS41NThzLTEuMDg1LTEuMDE1LTEuNTU4LTEuMzYyYy0wLjgwNi0wLjU5MS0xLjE5Ny0wLjY1OS0xLjQyMS0wLjY1OWgtNy43NWMtMC42ODkgMC0xLjI1IDAuNTYxLTEuMjUgMS4yNXYxMy41YzAgMC42ODkgMC41NjEgMS4yNSAxLjI1IDEuMjVoMTEuNWMwLjY4OSAwIDEuMjUtMC41NjEgMS4yNS0xLjI1di05Ljc1YzAtMC4yMjQtMC4wNjgtMC42MTUtMC42NTktMS40MjF2MHpNMTIuMjcxIDIuNzI5YzAuNDggMC40OCAwLjg1NiAwLjkxMiAxLjEzNCAxLjI3MWgtMi40MDZ2LTIuNDA1YzAuMzU5IDAuMjc4IDAuNzkyIDAuNjU0IDEuMjcxIDEuMTM0djB6TTE0IDE0Ljc1YzAgMC4xMzYtMC4xMTQgMC4yNS0wLjI1IDAuMjVoLTExLjVjLTAuMTM1IDAtMC4yNS0wLjExNC0wLjI1LTAuMjV2LTEzLjVjMC0wLjEzNSAwLjExNS0wLjI1IDAuMjUtMC4yNSAwIDAgNy43NDktMCA3Ljc1IDB2My41YzAgMC4yNzYgMC4yMjQgMC41IDAuNSAwLjVoMy41djkuNzV6Ij48L3BhdGg+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTExLjgxNyA2LjExM2MtMC4xMTYtMC4wOTUtMC4yNjgtMC4xMzMtMC40MTUtMC4xMDRsLTUgMWMtMC4yMzQgMC4wNDctMC40MDIgMC4yNTItMC40MDIgMC40OXYzLjcwMWMtMC4yOTQtMC4xMjgtMC42MzYtMC4yMDEtMS0wLjIwMS0xLjEwNSAwLTIgMC42NzItMiAxLjVzMC44OTUgMS41IDIgMS41IDItMC42NzIgMi0xLjV2LTMuNTlsNC0wLjh2Mi4wOTFjLTAuMjk0LTAuMTI4LTAuNjM2LTAuMjAxLTEtMC4yMDEtMS4xMDUgMC0yIDAuNjcyLTIgMS41czAuODk1IDEuNSAyIDEuNSAyLTAuNjcyIDItMS41di01YzAtMC4xNS0wLjA2Ny0wLjI5Mi0wLjE4My0wLjM4N3oiPjwvcGF0aD48L3N2Zz4=) center/50% no-repeat;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.unknown-3TPTMr {
	-webkit-mask: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iIzAwMDAwMCIgZD0iTTE0LjM0MSAzLjU3OWMtMC4zNDctMC40NzMtMC44MzEtMS4wMjctMS4zNjItMS41NThzLTEuMDg1LTEuMDE1LTEuNTU4LTEuMzYyYy0wLjgwNi0wLjU5MS0xLjE5Ny0wLjY1OS0xLjQyMS0wLjY1OWgtNy43NWMtMC42ODkgMC0xLjI1IDAuNTYxLTEuMjUgMS4yNXYxMy41YzAgMC42ODkgMC41NjEgMS4yNSAxLjI1IDEuMjVoMTEuNWMwLjY4OSAwIDEuMjUtMC41NjEgMS4yNS0xLjI1di05Ljc1YzAtMC4yMjQtMC4wNjgtMC42MTUtMC42NTktMS40MjF6TTEyLjI3MSAyLjcyOWMwLjQ4IDAuNDggMC44NTYgMC45MTIgMS4xMzQgMS4yNzFoLTIuNDA2di0yLjQwNWMwLjM1OSAwLjI3OCAwLjc5MiAwLjY1NCAxLjI3MSAxLjEzNHpNMTQgMTQuNzVjMCAwLjEzNi0wLjExNCAwLjI1LTAuMjUgMC4yNWgtMTEuNWMtMC4xMzUgMC0wLjI1LTAuMTE0LTAuMjUtMC4yNXYtMTMuNWMwLTAuMTM1IDAuMTE1LTAuMjUgMC4yNS0wLjI1IDAgMCA3Ljc0OS0wIDcuNzUgMHYzLjVjMCAwLjI3NiAwLjIyNCAwLjUgMC41IDAuNWgzLjV2OS43NXoiPjwvcGF0aD48L3N2Zz4=) center/50% no-repeat;
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .bgScale-1otPtc {
	background:var(--accent);
	border-radius:0;
}

/*11. Pages*/

/*11.a. Loading Screen*/

@keyframes loadingBar {
    0% {
        left:10%;   
    }
    50% {
        left:90%;
    }
    100% {
        left:10%;
    }
}

.platform-win .container-16j22k {
	top:-30px;
	padding-top:30px;
}

.container-16j22k video.ready-36e6Vk {
	display:none;
}

.quote-3aooyW {
    position:relative;
    margin-bottom:28px;
	font-size:var(--size1);
	font-style:normal;
	text-transform:none;
	width:200px;
}

.quote-3aooyW::before {
    content:'';
    position:absolute;
    bottom:-30px;
    left:0;
    display:block;
    width:25%;
    height:4px;
    background:var(--accent);
    box-shadow:0 0 24px 2px var(--accent);
    margin-bottom:14px;
    transform:translateX(-50%);
    transform-origin:center;
    animation:loadingBar 2s linear infinite forwards;
}

.quote-3aooyW::after {
    content:'';
    position:absolute;
    bottom:-30px;
    left:0;
    display:block;
    width:100%;
    height:4px;
    background:rgba(255,255,255,0.07);
    margin-bottom:14px;
}
    
.container-16j22k {
    box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.05);
}

.problemsText-1Yx-Kl,
.links-3Ldd4A {
	font-size:var(--size1);
}

.icon-3N9Bhy {
	width:12px;
	color:inherit;
}

.problems-3mgf6w {
	width:fit-content;
	border-radius:3px;
	background:rgba(255,255,255,0.05);
	transition:250ms ease all;
	transform:translate3d(-50%,100%,0);
	left:50%;
	z-index:1;
	box-shadow:0 2px 12px var(--lv1);
}

.full-motion .problems-3mgf6w {
	backdrop-filter:blur(10px);
}

.problems-3mgf6w.slideIn-sCvzGz {
	margin-bottom:14px;
	padding:8px;
	transform:translate3d(-50%,0,0);
}

.problems-3mgf6w .statusLink-gFXhrL {
	color:var(--success) !important;
}

.problems-3mgf6w .twitterLink-3NsWMp {
	color:#1da1f2 !important;
}

/*11.b. Login Screen*/


@keyframes loginBackgroundBottomLayer {
	0% {
		transform: rotate(10deg) translateY(-50%);
	}
	50% {
		transform:translateX(-60px) rotate(10deg) translateY(-50%);
	}
	100% {
		transform:none rotate(10deg) translateY(-50%);
	}
}

@keyframes loginBackgroundTopLayer {
	0% {
		transform: rotate(10deg) translateY(-50%);
	}
	50% {
		transform:translateX(-40px) rotate(10deg) translateY(-50%);
	}
	100% {
		transform:none rotate(10deg) translateY(-50%);
	}
}

@keyframes authBox {
	0% {
		transform:translateY(45px);
	}
	100% {
		transform:none;
	}
}

.image-2jyRAK,
.rightSplit-2US0xy + canvas,
.wrapper-3Q5DdO::before {
	display:none;
}

.wrapper-3Q5DdO {
	overflow:hidden;
	background: linear-gradient(to bottom, var(--lv1), rgba(255, 255, 255, 0.1) 100%), url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADwAAAA8CAMAAAANIilAAAAAHlBMVEX///////////////////////////////////////8V2MxSAAAACnRSTlMAAgYHCAoLDRAT6dja9gAAAHtJREFUSMft1DcSgEAMQ1FbCwX3vy7MUpA2UDi0cqnxa79uu4ynOGybrD9/xbhh3rRaN/xs1bohYQUJO2Cf7bHTdthrW+y2DfbbDwfsiyP2wSF745i9cNAKElaQsIKEFSSsLFCd/kq1bWwYG8aGsWFsGBvGhrFhbFi4YScBnULqiGhGjQAAAABJRU5ErkJggg==) center/75px !important;
}

.leftSplit-1qOwnR {
	max-height:unset !important;
	min-height:unset !important;
	max-width:unset;
	height:100vh;
	width:100vw;
	overflow:hidden;
	position:static;
}

.leftSplit-1qOwnR::before,
.leftSplit-1qOwnR::after {
	content:'';
	position:absolute;
	top:50%;
	right:0;
	width:60%;
	height:300%;
	background:var(--accent);
	opacity:.25;
	transform:rotate(10deg) translateY(-50%);
	animation:loginBackgroundBottomLayer 10s ease infinite;
	pointer-events:none;
	box-shadow:0 0 12px var(--lv1);
}

.leftSplit-1qOwnR::after {
	width:45%;
	animation:loginBackgroundTopLayer 10s ease infinite;
	animation-delay:150ms;
	transform:rotate(10deg) translateY(-50%);
}

.reduce-motion .leftSplit-1qOwnR::before,
.reduce-motion .leftSplit-1qOwnR::after {
	animation:none;
	z-index:-1;
}

.subTitle-3TUjmF {
	font-size:var(--size1);
}

.needAccount-23l_Wh,
.smallRegisterLink-2LCrMe {
	font-size:var(--size2);
	line-height:normal;
	font-weight:500;
	vertical-align:unset;
}

.authBox-hW6HRx .h5-18_1nd {
	margin:0;
}

.authBox-hW6HRx .linkButton-wzh5kV {
	margin-bottom:4px;
}

.authBox-hW6HRx .title-jXR8lp,
.smallRegisterLink-2LCrMe {
	margin-bottom:0 !important;
	display:flex;
	flex-direction:column;
	align-items:center;
}

.authBox-hW6HRx .marginTop4-2BNfKC {
	display:flex;
	align-items:center;
}

.authBox-hW6HRx .title-jXR8lp::before {
	content:'';
	position:relative;
	background:red;
	width:100px;
	height:100px;
	display:block;
	margin-bottom:12px;
	border-radius:var(--user-roundness);
	border:1px solid var(--lv1);
	background:rgba(255,255,255,0.07) url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiI+PHBhdGggZmlsbD0iI0ZGRkZGRiIgZD0iTTkgMTEuMDQxdi0wLjgyNWMxLjEwMi0wLjYyMSAyLTIuMTY4IDItMy43MTYgMC0yLjQ4NSAwLTQuNS0zLTQuNXMtMyAyLjAxNS0zIDQuNWMwIDEuNTQ4IDAuODk4IDMuMDk1IDIgMy43MTZ2MC44MjVjLTMuMzkyIDAuMjc3LTYgMS45NDQtNiAzLjk1OWgxNGMwLTIuMDE1LTIuNjA4LTMuNjgyLTYtMy45NTl6Ij48L3BhdGg+PC9zdmc+') center/75% no-repeat;
}

.errorMessage-3Guw2R {
	font-size:var(--size2);
}

.qrLogin-1AOZMt,
.verticalSeparator-3huAjp {
	display:none;
}

.wrapper-6URcxg {
	position:fixed;
	min-height:unset;
	width:100vw;
	height:100vh;
	transform:none !important;
}

#app-mount .authBox-hW6HRx {
	background:var(--lv1);
	width:400px;
	border-radius:0;
	padding:0;
	box-shadow:0 4px 24px 8px var(--lv1) !important;
	overflow:hidden;
}

.full-motion #app-mount .authBox-hW6HRx {
	animation:authBox 500ms ease;
}

.centeringWrapper-2Rs1dR {
	padding:32px;
	background:rgba(255,255,255,0.07);
	border-top:2px solid var(--accent);
	box-sizing:border-box;
}

@media screen and (max-width: 1000px) {
	.authBox-hW6HRx .title-jXR8lp::before {
		content:none;
	}

	.leftSplit-1qOwnR::after {
		z-index:-1;
	}
}

/*11.c. Server Discovery*/

@keyframes discoveryDownIndicator {
	0% {
		transform:none;
	}
	50% {
		transform:translateY(-5px);
	}
	100% {
		transform:none;
	}
}

.pageWrapper-1PgVDX {
	background:var(--lv1) !important;
	transform:translateZ(0);
}

.pageWrapper-1PgVDX::after {
	content:'';
	bottom:0;
	left:-60px;
	background:var(--lv1);
	position:fixed;
	width:60px;
	height:50px;
}

.full-motion .pageWrapper-1PgVDX::after {
	backdrop-filter:blur(10px);
}

.pageWrapper-1PgVDX::before {
	content:'Server Discovery';
	font-weight:500;
	color:#fff;
	background:var(--lv1);
	height:40px;
	border-bottom:2px solid var(--hover);
	position:absolute;
	box-sizing:border-box;
	display:flex;
	align-items:center;
	width:100%;
	z-index:100;
	font-size:var(--size1);
	padding:0 16px;
	box-shadow:inset 0 0 0 100vmax rgba(255, 255, 255, .07);
}

.bg-AYqtMd {
	-webkit-mask:linear-gradient(#000,transparent);
}

.mainHeader-1i17pL {
	font-size:25px;
	font-weight:500;
}

.searchBox-3Y2Vi7 {
	background:transparent !important;
	box-shadow:none !important;
}

.searchHelpText-19imBp {
	top:50px;
	font-size:var(--size2);
}

.searchHelpText-19imBp strong {
	color:#fff !important;
	background:rgba(255,255,255,0.07);
	box-shadow:0 2px 6px rgba(0, 0, 0, 0.6);
	padding: 4px;
	border-radius:2px;
	line-height:16px;
	transition:250ms ease;
	cursor:pointer;
}

.searchBox-3Y2Vi7 .searchBoxInput-uJtBcv,
.sectionHeader-1Hee-5 {
	font-size:var(--size0);
}

.searchBox-3Y2Vi7 .searchBoxInput-uJtBcv::-webkit-input-placehodler {
	color:rgba(255,255,255,0.5);
	font-weight:500;
}

#app-mount .searchBox-3Y2Vi7 .searchBoxInput-uJtBcv {
	background:transparent !important;
	border:none !important;
	box-shadow:none !important;
}

.clearIcon-2N9YIn, .searchIcon-1a1-yA {
	height:var(--sizelg);
	width:var(--sizelg);
}

.pageHeader-3615mp {
	height:38vh;
}

.languageSelector-1R8fPE {
	position:fixed;
	top:0;
	right:0;
	width:180px;
	z-index:100;
	margin:0;
	height:fit-content;
}

.languageSelector-1R8fPE .css-1k00wn6-singleValue {
	overflow:visible;
}

.languageSelector-1R8fPE .css-1k00wn6-singleValue div {
	font-size:var(--size1);
}

.languageSelector-1R8fPE .css-1wqqa50-container {
	background:transparent;
	box-shadow:none;
	border-radius:0;
}

.search-JQJ-3r {
	margin-bottom:56vh;
}

.search-JQJ-3r::after {
	content:'';
	position:absolute;
	bottom:35px;
	left:50%;
	transform:translateX(-50%);
	width:25px;
	height:25px;
	border-radius:50%;
	background:url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIj8+PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBmaWxsPSIjZmZmZmZmIj4gIDxwYXRoIGQ9Ik03LjQxIDguNTlMMTIgMTMuMTdsNC41OS00LjU4TDE4IDEwbC02IDYtNi02IDEuNDEtMS40MXoiLz4gIDxwYXRoIGQ9Ik0wIDBoMjR2MjRIMFYweiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==	) center/cover no-repeat;
}

.full-motion .search-JQJ-3r::after {
	animation:discoveryDownIndicator 2s ease infinite;
}

.emptySearchTitle-2zDhhZ {
	font-size:var(--size0);
	color:rgba(255,255,255,0.75) !important;
	margin:0;
}

.emptySearchDescription-2AmfE4 {
	font-size:var(--size1);
	color:rgba(255,255,255,0.5) !important;
}

.emptySearchImage-1qOMLW {
	display:none;
}

.emptySearchResults-1ba__I {
	margin-top:0;
}

.guildList-1ItbxP {
	display:flex;
	flex-wrap:wrap;
	flex-direction:row;
	justify-content:center;
}

.guildCard-2arfcG {
	width:unset;
	background:transparent !important;
}

.card-3DjzTQ,
.cardPlaceholder-1zrbbe {
	border-radius:3px;
	overflow:hidden;
	background:transparent !important;
	box-shadow:none !important;
	margin:8px;
	min-width:520px;
	min-height:unset;
	height:272px;
	transform:translateZ(0) !important;
}

#app-mount .splash-3N0nhD {
	width:100%;
	height:100%;
	position:relative;
	top:0;
	left:0;
	border-radius:5px;
	overflow:hidden;
}

.splash-3N0nhD svg,
.splash-3N0nhD foreignObject {
	width:100%;
	height:100%;
	mask:none;
}

.pageWrapper-1PgVDX .cardHeader-Int16m {
	flex:0 0 auto;
}

.pageWrapper-1PgVDX .description-2QALGo {
	height:auto;
	margin:0;
}

.pageWrapper-1PgVDX .splashImage-1wJ3Sk {
	filter:blur(5px) brightness(.75);
	transform:scale(1.15);
	background:rgba(255,255,255,0.1) !important;
}

.pageWrapper-1PgVDX .guildInfo-2wGKIg {
	position:absolute;
	bottom:0;
	left:0;
	padding:0;
	margin:16px;
}

.guildIcon-3W0pfo {
	top:16px;
}

.viewButton-3jDZqV {
	top:50%;
	left:50%;
	transform:translateX(-50%) translateY(-50%);
	z-index:10;
}

.card-3DjzTQ:hover::after {
	content:'';
	top:0;
	left:0;
	width: 100%;
	height:100%;
	background:var(--lv1);
	opacity:.5;
	position:absolute;
}

.sectionSeparator-2OWiNT {
	border-color:rgba(255,255,255,0.075) !important;
}

.guildInfo-2wGKIg {
	position:static;
}

.roundButton-2CW1Hh {
	border-radius: 2px;
	font-size:var(--size1);
}

#app-mount .activeButton-1BJAiN {
	background: var(--accent) !important;
}

#app-mount .roundButton-2CW1Hh:hover {
	background: rgba(255, 255, 255, .075);
}

#app-mount .pageControlContainer-3czZwE .colorTransparent-1ewNp9 {
	background: transparent !important;
}

#app-mount .pageControlContainer-3czZwE .colorTransparent-1ewNp9:hover {
	background: var(--accent);
}

.guildIcon-3W0pfo foreignObject {
	mask:none;
}

.card-3DjzTQ .guildIcon-3W0pfo {
	border-radius:var(--guilds-roundness);
}

.dotOnline-8Ag7EB {
	background:var(--success);
}

.dotOffline-3DXoDy {
	background:var(--unavailable);
}

/*11.d. Friends List*/

@keyframes slide-out-enable {
    0% {
        pointer-events:none;
    }
    100% {
        pointer-events:all;
    }
}

.container-1D34oG {
	background:var(--lv1) !important;
}

.title-30qZAO {
	font-size:var(--size1);
	text-transform:none;
	margin-top:0;
	margin:0 30px;
	margin-bottom:20px;
	display:flex;
	align-items:center;
}

.title-30qZAO::before {
	content:'';
	width:10px;
	height:10px;
	background:var(--success);
	border-radius:50px;
	position:relative;
	display:inline-block;
	margin-right:5px;
}

.container-1D34oG .peopleColumn-29fq28 .scroller-2FKFPG::before {
	content:'Friends';
	color:#fff;
	font-size:52px;
	margin:30px;
	font-weight:600;
}

.container-1D34oG .peopleColumn-29fq28 .scroller-2FKFPG {
	padding-top:30px;
}

.nowPlayingColumn-2sl4cE {
    min-width:unset;
    position:absolute;
    right:0;
    height:100%;
    width:300px;
    transform:translateX(250px);
    background:var(--lv1);
	transition:250ms cubic-bezier(.52,0,.74,0);
	z-index:1;
}

.nowPlayingColumn-2sl4cE::after {
    content:'|||';
    color:#fff;
    font-size:12px;
    position:absolute;
    left:25px;
    top:50%;
	transform:translateY(-50%) translateX(-50%);
	transition:450ms ease;
}

.nowPlayingColumn-2sl4cE:hover::after {
    opacity:0;
}

.nowPlayingColumn-2sl4cE:hover {
    transform:none;
    background:var(--lv1);
    box-shadow:0 0 12px var(--lv1);
}

.nowPlayingColumn-2sl4cE .scroller-2FKFPG {
    pointer-events:none;
    opacity:0;
    transform:scale(.95);
    transition:250ms cubic-bezier(.52,0,.74,0);
}

.nowPlayingColumn-2sl4cE:hover .scroller-2FKFPG {
    opacity:1;
    transform:none;
}

.nowPlayingColumn-2sl4cE:hover .itemCard-v9viV7 {
    animation:slide-out-enable 450ms linear forwards;
}

.peopleColumn-29fq28 {
    margin-right:50px;
}

@media (max-width: 1200px) {
    .peopleColumn-29fq28 {
        margin-right:0;
    }
}

.peopleColumn-29fq28 .scroller-2FKFPG {
	padding-bottom:25px;
}

.peopleListItem-2nzedh {
	border:none;
	position:relative;
	border-radius:0 !important;
	background:rgba(255,255,255,0.07);
	box-sizing:border-box;
	margin:0 16px !important;
	padding:0 16px !important;
	border-left:1px solid rgba(255,255,255,0.07) !important;
	border-right:1px solid rgba(255,255,255,0.07) !important;
	overflow:visible;
	z-index:1;
	transition:150ms ease;
}

.peopleListItem-2nzedh:hover,
.peopleListItem-2nzedh.active-rhSpJJ {
	background:rgba(255,255,255,0.05);
}

header + .peopleListItem-2nzedh {
	border-top-left-radius:3px !important;
	border-top-right-radius:3px !important;
	border-top:1px solid rgba(255,255,255,0.07) !important;
}

.peopleListItem-2nzedh:nth-last-child(2) {
	border-bottom-left-radius:3px !important;
	border-bottom-right-radius:3px !important;
	border-bottom:1px solid rgba(255,255,255,0.07) !important;
}

.peopleListItem-2nzedh .wrapper-3t9DeA {
	height:28px !important;
	width:28px !important;
}

.peopleListItem-2nzedh .discriminator-22Okc1 {
	visibility:visible;
	font-size:var(--size1);
}

.text-3MU_QQ {
	font-size:var(--size2);
}

.text-GwUZgS,
.description-1EvxpH {
	font-size:var(--size1);
	font-weight:500;
	text-transform:none;
}

.image-1GzsFd {
	filter:grayscale(1) brightness(1.25);
	opacity:.5;
}

.header-1-dBpZ {
	color:#fff;
	font-size:52px;
	font-weight:700;
	text-transform:none;
	margin-top:30px;
}

.addInputWrapper-1BOZ3d {
	padding-top:0;
}

.wrapper-1cBijl {
	background:transparent;
	border:none;
	border-radius:0;
	padding:0;
	height:28px;
}

.addFriendInput-4bcerK {
	border-radius: 2px;
	border: none;
	transition:150ms ease all;
	background: rgba(255,255,255,0.07);
	font-size:var(--size2);
	box-sizing:border-box;
	box-shadow:0 1px 3px var(--lv1), 0 0 0 1px var(--lv1);
	padding:2px 6px;
	height:28px;
	letter-spacing:.015em;
}

.addFriendInput-4bcerK:hover {
	box-shadow:0 1px 4px var(--lv1), 0 0 0 1px var(--lv1);
}

.addFriendInput-4bcerK:focus {
	box-shadow:0 0 2px var(--lv1), inset 0 0 0 1px var(--accent);
}

.addFriendInput-4bcerK::-webkit-input-placeholder {
	color:rgba(255,255,255,0.4);
}

.addFriendHint-3Y70FX {
	color:rgba(255,255,255,0.35);
	font-size:var(--size2);
	top:0;
	left:0;
	padding:2px 6px;
	line-height:normal;
	height:28px;
	align-items:center;
	display:flex;
	box-sizing:border-box;
	letter-spacing:var(--letter-spacing);
}

/*11.e. Store*/


																										
/*11.f. Library*/

.usageInfo-2WQAwr {
	font-size:var(--size2);
}

.foreground-2aE44H {
	stroke:var(--accent);
}

.background-yZEZik {
	stroke:rgba(255,255,255,0.15) !important;
}

.defaultIndicator-3WqGFB {
	background:var(--hover) !important;
	border-radius:2px;
	padding:2px 4px;
	font-size:var(--size4);
	margin-left:4px;	
}

.installationPath-3cStrB {
	box-shadow:none !important;
}

.divider-3573oO {
	display:none;
}

.headerCellContent-1pLtOr {
	font-size:var(--size2);
}

.small-4dgL9e {
	border-radius:0;
}

.small-4dgL9e[style*="var(--interactive-normal)"] {
	background:rgba(255,255,255,0.15) !important;
}


.small-4dgL9e[style*="rgb(0, 176, 244)"] {
	background:var(--accent) !important;
	box-shadow:0 0 12px var(--accent);
}

.gameIcon-gg34Dz {
	border-radius:var(--user-roundness);
}

/*11.g. Nitro Advertising Tab*/



/*12. Controls*/

/*12.a. Checkboxes & Radios*/

@keyframes checkbox {
	0% {
		transform: scale(1);
	}
	25% {
		transform: scale(0.8);
	}
	100% {
		transform: scale(1);
	}
}

.checkbox-3kaeSU .checkboxInner-3yjcPe .checkboxElement-1qV33p:checked+span {
	background-color: var(--accent);
	border-color: var(--accent);
	box-shadow: 0 0 5px var(--hover);
}

.full-motion .checkbox-3kaeSU .checkboxInner-3yjcPe .checkboxElement-1qV33p:checked+span {
	animation: checkbox 400ms cubic-bezier(0.52, 0.01, 0, 1);
}

.radioGroup-1GBvlr {
	padding: 16px;
	background: rgba(255, 255, 255, 0.07);
	border-radius: 2px;
	box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
}

.checkbox-1ix_J3 {
	height: 22px !important;
	width: 22px !important;
	position: relative;
}

.checkbox-1ix_J3 svg {
	display: none;
}

.item-26Dhrx {
	background: rgba(255, 255, 255, 0.07) !important;
	border: none !important;
	margin-bottom: 8px;
	box-shadow: 0 2px 4px var(--lv1);
	transition: 150ms ease;
	border-radius:2px;
}

.item-26Dhrx:hover {
	box-shadow: 0 2px 12px var(--lv1);
}

.checked-3_4uQ9 {
	border-color: var(--accent) !important;
	background: transparent !important;
}

.checkbox-1ix_J3::after {
	content: '';
	position: absolute;
	width: 100%;
	height: 100%;
	transform-origin: 50%;
	top: 0;
	left: 0;
	transform: scale(0);
	border-radius: 50%;
	background: var(--accent);
	transition: 250ms transform ease;
}

.checkbox-1ix_J3.checked-3_4uQ9::after {
	transform: scale(.725);
}

.checkbox-1ix_J3 {
	border-radius: 50px;
	background: transparent;
	box-sizing: border-box;
	border: 2px solid;
}

.desc-2Dttbk {
	margin:0;
	font-size:var(--size2);
	color: rgba(255, 255, 255, 0.8);
}

.title-3BE6m5 {
	font-size: var(--size1);
	color: rgba(255, 255, 255, 0.8);
}

.checkboxWrapper-SkhIWG {
	display:flex;
	align-items:center;
}

[style^="color: rgb(240, 71, 71)"] {
	color:var(--danger) !important;
}

[style^="color: rgb(250, 166, 26)"] {
	color:var(--caution) !important;
}

[style^="color: rgb(67, 181, 129)"] {
	color:var(--success) !important;
}

/*12.b. Radios*/



/*12.c. Sliders*/

.grabber-3mFHz2 {
	width: 20px;
	height: 20px;
	border: none;
	border-radius: 50%;
	margin-top: 0;
	margin-left: -8px;
	top: unset;
	background: var(--accent);
	box-shadow: 0 2px 12px rgba(0, 0, 0, 0.5);
	transition: 250ms ease;
	cursor: pointer;
	display: flex;
	align-items: center;
	justify-content: center;
}

.grabber-3mFHz2:after {
	transform: scale(0);
	content: '';
	position: absolute;
	width: 30px;
	height: 30px;
	background: #fff;
	opacity: 0;
	transition: 250ms ease;
	border-radius: inherit;
	z-index: -1;
}

.grabber-3mFHz2:active:after {
	transform: scale(1.5);
	opacity: .25;
}

.track-11EASc {
	display: flex;
	align-items: center;
}

.bar-2Qqk5Z {
	border-radius: 50px;
}

.barFill-23-gu- {
	transition: 250ms ease;
	background: var(--hover) !important;
}

.markDash-3hAolZ {
	display: none;
}

.defaultValue-3gC7yw .markValue-2DwdXI {
	text-shadow: 0 0 12px;
}

/*12.d. Switches*/

.themeDefault-24hCdX {
	background: rgba(255, 255, 255, .35);
}

#app-mount #bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch.checked,
#app-mount .themeDefault-24hCdX.valueChecked-m-4IJZ {
	background: var(--accent);
	box-shadow: 0 0 12px var(--accent);
}

#app-mount #bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch.checked:before,
#app-mount .themeDefault-24hCdX.valueChecked-m-4IJZ:after {
	margin-left: 6px;
}

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch:before,
.themeDefault-24hCdX:after {
	height: 100%;
	margin-top: 0;
	top: 0;
	left: 0;
	margin: 0;
}

.ui-switch:before {
	height: 23px;
}

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch:before,
.themeDefault-24hCdX,
.themeDefault-24hCdX:after {
	border-radius: 0;
}

/*12.e. Buttons*/

.lookFilled-1Gx00P,
.lookLink-9FtZy-,
.lookOutlined-3sRXeN,
.lookGhost-2Fn_0-,
.lookInverted-2D7oAl,
.bd-pfbtn,
.bda-slist .bda-footer button {
	font-size:var(--size3);
	border-radius:2px !important;
	font-weight:400;
	height:28px;
	min-height:28px;
	transition:150ms ease;
}

.lookFilled-1Gx00P:active,
.lookLink-9FtZy-:active,
.lookOutlined-3sRXeN:active,
.lookGhost-2Fn_0-:active,
.lookInverted-2D7oAl:active,
.bd-pfbtn:active,
.bda-slist .bda-footer button:active {
	transform:translateY(1px);
}

.lookFilled-1Gx00P:not(.button-qqmJ7w):hover,
.lookFilled-1Gx00P:not(.button-qqmJ7w):active,
.bd-pfbtn:hover,
.bd-pfbtn:active,
.bda-slist .bda-footer button:hover,
.bda-slist .bda-footer button::active {
	box-shadow:0 2px 8px rgba(0,0,0,0.5);
	color:#fff !important; 
}

.lookFilled-1Gx00P:not(.button-qqmJ7w),
.bd-pfbtn,
.bda-slist .bda-footer button {
	box-shadow:0 1px 5px rgba(0,0,0,0.5);
	color:#f1f1f1 !important;
}

.lookFilled-1Gx00P.colorBrand-3pXr91,
.lookFilled-1Gx00P.colorBrand-3pXr91:hover,
.lookFilled-1Gx00P.hoverBrand-1_Fxlk.hasHover-3X1-zV:hover,
.lookLink-9FtZy-.colorBrand-3pXr91 .spinnerItem-3GlVyU,
.bd-pfbtn,
.bda-slist .bda-footer button:not(.button-38aScr) {
	background:var(--accent) !important;
}

.lookFilled-1Gx00P.colorBrand-3pXr91:active,
.bd-pfbtn:active,
.bda-slist .bda-footer button:not(.button-38aScr) {
	background:var(--hover) !important;
}

.lookFilled-1Gx00P.colorPrimary-3b3xI6 {
	background:rgba(255,255,255,0.1) !important;
}

.lookFilled-1Gx00P.colorPrimary-3b3xI6:hover,
.lookFilled-1Gx00P.colorPrimary-3b3xI6:active {
	background:rgba(255,255,255,0.15) !important;
}

.lookOutlined-3sRXeN.colorBrand-3pXr91 {
	color:var(--accent) !important;
	border-color:var(--hover) !important;
}

.lookOutlined-3sRXeN.colorBrand-3pXr91:hover,
.lookOutlined-3sRXeN.colorBrand-3pXr91:active {
	border-color:var(--accent) !important;
	background:transparent !important
}

.lookGhost-2Fn_0-.colorBrand-3pXr91 {
	color: var(--accent);
	background: rgba(255,255,255,0.05);
}

.lookGhost-2Fn_0-.colorBrand-3pXr91:hover,
.lookGhost-2Fn_0-.colorBrand-3pXr91:active {
	background-color:rgba(255,255,255,0.065);
}

.lookLink-9FtZy-.colorBrand-3pXr91,
.lookInverted-2D7oAl.colorBrand-3pXr91 {
	color: var(--accent) !important;
}

.lookInverted-2D7oAl.colorBrand-3pXr91:active {
	background:#fff !important;
}

.lookLink-9FtZy-.colorBrand-3pXr91:hover .contents-18-Yxp,
.lookLink-9FtZy-.hoverBrand-1_Fxlk.hasHover-3X1-zV:hover .contents-18-Yxp {
	background-image: linear-gradient(0deg, transparent, transparent 1px, var(--accent) 0, var(--accent) 2px, transparent 0) !important;
}

.lookFilled-1Gx00P.hoverBrand-1_Fxlk {
	box-shadow:none !important;
}

.lookLink-9FtZy- {
	padding:0 !important;
	min-height:unset !important;
}

.lookGhost-2Fn_0-.colorGrey-2DXtkV {
	color: rgba(255,255,255,0.65);
	background-color: rgba(255, 255, 255, .05);
}

.lookGhost-2Fn_0-.colorGrey-2DXtkV:active,
.lookGhost-2Fn_0-.colorGrey-2DXtkV:hover {
	background-color: rgba(255, 255, 255, .075);
}

.lookFilled-1Gx00P.colorWhite-rEQuAQ {
  color:var(--lv1) !important;
}

/*12.f. Role Entries*/

.role-2irmRk {
	border-width: 1px;
	border-style: solid;
	border-radius: 0;
	box-sizing: content-box;
	height: 16px;
	margin: 3px;
	padding: 2px;
	position: relative;
	font-size: var(--size3);
	font-weight: 400;
	overflow: visible;
	display:flex;
	align-items:center;
}

.role-2irmRk::before {
	content: '';
	position: absolute;
	top: 0;
	left: -1px;
	height: calc(100% - 21px);
	width: calc(100% + 1px);
	border-top: 21px solid;
	border-color: inherit;
	opacity: 0.5;
}

.roleName-32vpEy {
	margin: 0 4px;
	z-index: unset !important;
}

.roleCircleButton-377y0l {
	padding: 0;
	position: absolute;
	z-index: 2;
	height: 22px;
	top: -1px;
	left: -1px;
	border-radius: 2px 0 0 2px;
	width: 0px;
	display: flex !important;
	transition: width 0.2s;
}

.roleCircle-3xAZ1j {
	display: none;
}

.addButton-pcyyf6 {
	line-height: 10px;
	width: 22px;
	box-sizing: border-box;
	height: 22px;
}

.roleRemoveIcon-2-TeGW {
	display: block;
	opacity: 0;
	transition: opacity 200ms ease-in-out;
}

.role-2irmRk:hover .roleCircleButton-377y0l {
	transition: width 0.2s;
	width: 22px;
}

.role-2irmRk:hover .roleRemoveIcon-2-TeGW {
	opacity: 1;
}

.addButtonIcon-1NMJ8u {
	height: 7px;
	width: 7px;
}

/*13. Outer Settings Layers*/

.platform-win .layer-3QrUeG {
	top:-30px;
	padding-top:30px;
}

.layer-3QrUeG.baseLayer-35bLyl {
	opacity:1 !important;
	transform:none !important;
}

#app-mount .standardSidebarView-3F1I7i {
	top:42px;
}

.platform-win #app-mount .standardSidebarView-3F1I7i {
	top:70px;
}

.layer-3QrUeG[aria-label="GUILD_SETTINGS"],
.layer-3QrUeG[aria-label="USER_SETTINGS"],
.layer-3QrUeG[aria-label="RTC_DEBUG"] {
	z-index:1000;
}

.layer-3QrUeG {
	background:transparent;
}

.closeButton-1tv5uR:active {
	transform:none;
}

.platform-win .closeButton-1tv5uR::after {
	top:30px;
}

.closeButton-1tv5uR::after {
	content:'';
	position:fixed;
	width:100vw;
	height:40px;
	top:0;
	left:0;
	cursor:default;
}

/*12.g. Bot Tags*/

.botTag-2WPJ74:not(.tag-wWVHyf) {
	margin:0;
	margin-right:4px;
	font-size:0;
	background:url('data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIj8+PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiB2aWV3Qm94PSIwIDAgMTQgMTYiIHZlcnNpb249IjEuMSIgYXJpYS1oaWRkZW49InRydWUiIGZpbGw9IiNmZmZmZmYiPiAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMTQgOC43N3YtMS42bC0xLjk0LS42NC0uNDUtMS4wOS44OC0xLjg0LTEuMTMtMS4xMy0xLjgxLjkxLTEuMDktLjQ1LS42OS0xLjkyaC0xLjZsLS42MyAxLjk0LTEuMTEuNDUtMS44NC0uODgtMS4xMyAxLjEzLjkxIDEuODEtLjQ1IDEuMDlMMCA3LjIzdjEuNTlsMS45NC42NC40NSAxLjA5LS44OCAxLjg0IDEuMTMgMS4xMyAxLjgxLS45MSAxLjA5LjQ1LjY5IDEuOTJoMS41OWwuNjMtMS45NCAxLjExLS40NSAxLjg0Ljg4IDEuMTMtMS4xMy0uOTItMS44MS40Ny0xLjA5TDE0IDguNzV2LjAyek03IDExYy0xLjY2IDAtMy0xLjM0LTMtM3MxLjM0LTMgMy0zIDMgMS4zNCAzIDMtMS4zNCAzLTMgM3oiLz48L3N2Zz4=') center/var(--size1) no-repeat;
	width:18px;
	height:18px;
	padding:0;
	background-color:var(--lv1);
	box-sizing:border-box;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.2), 0 0 10px rgba(0,0,0,0.25);
	border-radius:3px;
	display:flex;
	order:-1;
}

.px-10SIf7 .botText-1526X_ {
	font-size:inherit;
}

/*12.h. Inputs*/

.input-2A_zIr,
.input-cIJ7To:not(.multiInput-1e2xJ7) {
	border-radius: 2px;
	transition:150ms ease;
	background: rgba(255,255,255,0.07) !important;
	font-size:var(--size1);
	box-shadow:0 1px 3px var(--lv1);
	border:1px solid var(--lv1) !important;
	box-sizing:border-box;
	color:#fff;
}

.input-2A_zIr:hover,
.input-cIJ7To:not(.multiInput-1e2xJ7):hover {
	box-shadow:0 1px 4px var(--lv1);
	border:1px solid var(--lv1) !important;
}

.input-cIJ7To:not(.multiInput-1e2xJ7).focused-1mmYsC,
.input-cIJ7To:not(.multiInput-1e2xJ7):focus {
	box-shadow:0 0 2px var(--lv1);
	border:1px solid var(--accent) !important;
}

.multiInput-1e2xJ7 {
	border:none;
	background:transparent;
	box-shadow:none;
}

.input-2A_zIr::-webkit-input-placeholder,
.input-cIJ7To::-webkit-input-placeholder {
	color:rgba(255,255,255,0.4);
}

.inputContainer-1SpwlU {
	display:flex;
	align-items:center;
}

.inputContainer-1SpwlU .emojiButtonContainer-3d6DFV {
	position:relative;
	margin-left:0;
}

.input-cIJ7To .emoji-MCvpgl {
	background:var(--lv1);
}

.inputDefault-_djjkz {
	padding:2px 6px;
	height:28px;
}

.inputPrefix-2VAOGg {
	height:28px;
	display:flex;
	align-items:center;
	margin-left:16px;
	color:rgba(255,255,255,0.35);
	padding:0;
	font-size:var(--size1);
}

.inputWrapper-31_8H8 {
	flex-grow:1;
}

.clearIcon-xXwSFS {
	width:14px;
	height:14px;
}

.multiInputLast-1aQ3YA:before {
	content:none;
}

.multiInputLast-1aQ3YA input {
	padding:2px 6px;
	padding-left:18px;
	margin-left:10px;
	width:54px;
}

.multiInputLast-1aQ3YA {
	flex-grow:0;
}

/*12.i. Cards*/

/*14. Settings Sidebar*/

/*14.a. Outer Sidebar*/

#app-mount .sidebarRegion-VFTUkN .scrollerWrap-2lJEkd {
	justify-content: center;
	margin:0;
	padding:0;
}

.sidebarRegionScroller-3MXcoP {
	padding:0 20px;
}	

.sidebar-CFHs9e {
	padding:20px 0;
    width:100%;
}

.sidebarRegion-VFTUkN {
	flex:unset;
}

/*14.b. Sidebar Content*/

#bd-settings-sidebar .ui-tab-bar-item,
.standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ {
	border-radius: 0;
	margin:1px 0 1px 8px;
    background: rgba(255, 255, 255, .08);
    margin-top: 7px;
    height: 27px;
    margin-left: 5px;
    margin-right: 5px;
    box-shadow: 0 0 2px 2px rgba(255, 255, 255, .08);
	border-left: 2px solid rgba(255, 255, 255, .1);
	display:flex;
	align-items:center;
	line-height:normal;
	padding:0 8px;
	transition:150ms ease;
	width:265px;
	box-sizing:border-box;
	color:rgba(255, 255, 255, .6);
	font-weight:500;
	font-size:var(--size1);
}

.standardSidebarView-3F1I7i #bd-settings-sidebar .ui-tab-bar-item:not(.selected-3s45Ha):hover,
.standardSidebarView-3F1I7i .themed-OHr7kt.item-PXvHYJ:not(.selected):hover,
.standardSidebarView-3F1I7i #bd-settings-sidebar .ui-tab-bar-item:not(.selected-3s45Ha):active,
.standardSidebarView-3F1I7i .themed-OHr7kt.item-PXvHYJ:not(.selected):active {
    background-color: rgba(255, 255, 255, .15);
    box-shadow: 0 0 2px 2px rgba(255, 255, 255, .15);
	border-left: 2px solid rgba(255, 255, 255, .5);
	padding-left:13px;
	color:#f6f6f6;
}

#app-mount .standardSidebarView-3F1I7i .selected-3s45Ha,
#app-mount .standardSidebarView-3F1I7i .side-8zPYf6 #bd-settings-sidebar .selected {
	background-color: var(--accent);
    border-radius: 0;
    box-shadow: 0 0 12px 1px var(--accent);
    height: 36px;
	border-left: 2px solid rgba(255, 255, 255, .8);
	padding-left:8px;
	color:#fff;
}

#bd-settings-sidebar .ui-tab-bar-separator,
.side-8zPYf6 .separator-gCa7yv {
	display: none;
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .side-8zPYf6 .item-PXvHYJ:before,
.layer-3QrUeG[aria-label="USER_SETTINGS"] .side-8zPYf6 .ui-tab-bar-item:before {
	font-family: 'Material Icons';
	content: 'settings ';
	margin-right: 8px;
	font-size:var(--size0);
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(2):before {
	content: 'person ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(3):before {
	content: 'security ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(4):before {
	content: 'input ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(5):before {
	content: 'rss_feed ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(6):before {
	content: 'credit_card ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(8):before {
	content: 'favorite ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(9):before {
	content: 'card_giftcard ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(10):before {
	content: 'flight_takeoff ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(11):before {
	content: 'flag ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(14):before {
	content: 'mic ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(15):before {
	content: 'aspect_ratio ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(16):before {
	content: 'notifications ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(17):before {
	content: 'keyboard ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(18):before {
	content: 'games ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(19):before {
	content: 'text_format ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(20):before {
	content: 'dashboard ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(21):before {
	content: 'airplay ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ:nth-of-type(22):before {
	content: 'language ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .ui-tab-bar-item:nth-of-type(3):before {
	content: 'build ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .ui-tab-bar-item:nth-of-type(4):before {
	content: 'tag_faces ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .ui-tab-bar-item:nth-of-type(5):before {
	content: 'extension ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .ui-tab-bar-item:nth-of-type(6):before {
	content: 'format_paint ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .ui-tab-bar-item:nth-of-type(7):before {
	content: 'edit ';
}

.layer-3QrUeG[aria-label="USER_SETTINGS"] .standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ[style*="rgb(240, 71, 71)"]:before {
	content: 'exit_to_app ';
}

.side-8zPYf6 .header-2RyJ0Y,
.side-8zPYf6 .header-2RyJ0Y:first-child,
#bd-settings-sidebar .ui-tab-bar-header {
	text-align: left;
	color: rgba(255,255,255,0.9) !important;
	border-image: linear-gradient(90deg, var(--hover) 90%, transparent);
	border-image-slice: 1;
	border-bottom:thin solid;
	margin-bottom: 2px;
	margin:0 12px;
	font-size: var(--size2);
	font-weight: 400;
	padding:0 4px;
	padding-top:16px;
	line-height: 22px;
	text-transform: none;
	height:40px;
	position:relative;
}

.side-8zPYf6 .header-2RyJ0Y .addRoleIcon-3YjErH {
	width:16px;
	height:16px;
}

.socialLinks-3jqNFy {
	position:relative;
	padding:8px 12px;
	padding-top:28px;
}

.socialLinks-3jqNFy::before {
	content:'';
	position:absolute;
	top:14px;
	left:0;
	width:calc(100% - 20px);
	height:1px;
	margin:0 12px;
	background:linear-gradient(90deg, var(--hover) 90%, transparent);
}

.info-1VyQPT .colorMuted-HdFt4q:last-child:after {
	content:var(--theme-name) ' v' var(--theme-version) ' by Tropical';
	text-transform:none;
	display:block;
}

.standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ[style*="color: rgb(114, 137, 218)"] {
	color:var(--accent) !important;
} 

.standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ[style*="background-color: rgba(114, 137, 218, 0.1)"] {
	color:var(--accent) !important;
    background-color: rgba(255, 255, 255, .15) !important;
	padding-left:13px;
}

.standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ[style*="background-color: rgb(114, 137, 218)"] {
	background-color: var(--accent) !important;
    box-shadow: 0 0 12px 1px var(--accent);
    height: 36px;
	border-left: 2px solid rgba(255, 255, 255, .8);
	padding-left:8px;
	color:#fff !important;
}

.standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ[style*="background-color: rgba(240, 71, 71, 0.1)"] {
	background-color: rgba(255, 255, 255, .15) !important;
    box-shadow: 0 0 2px 2px rgba(255, 255, 255, .15);
	border-left: 2px solid rgba(255, 255, 255, .5);
	padding-left:13px;
	color:#f6f6f6;
}

.standardSidebarView-3F1I7i .side-8zPYf6 .item-PXvHYJ[style*="background-color: rgb(240, 71, 71)"] {
    box-shadow: 0 0 12px 1px rgb(240, 71, 71);
    height: 36px;
	border-left: 2px solid rgba(255, 255, 255, .8);
	padding-left:8px;
	color:#fff !important;
}

/*15. User Settings Content*/

/*15.a. Content Column Layout*/

.standardSidebarView-3F1I7i .contentRegionScroller-26nc1e {
  width: 100%;
}

.standardSidebarView-3F1I7i .contentColumn-2hrIYH, 
.standardSidebarView-3F1I7i .customColumn-Rb6toI {
  flex: 1 1 auto;
  max-width: 100%;
  min-height: 100%;
  min-width: 460px;
}

.standardSidebarView-3F1I7i .customScroller-26gWhv>div {
  max-width: 100%;
  margin-right: 98px;
}

/*15.b. Common Elements*/

.description-3_Ncsb, 
.labelDescriptor-1PqHgD,
.style-description {
	font-size:var(--size2) !important;
}

/*15.c. Close Button*/

#app-mount .closeButton-1tv5uR path:last-child {
	fill:rgba(255,255,255,0.7);
}

#app-mount .closeButton-1tv5uR{
	border:none;
	transition:200ms all linear;
}

#app-mount .closeButton-1tv5uR:hover {
	background:rgba(255,255,255,0.07);
}

#app-mount .closeButton-1tv5uR:active {
	background:rgba(255,255,255,0.1);
}

#app-mount .keybind-KpFkfr {
	font-size:var(--size2);
}

/*16. Guild Settings Content*/



/*17. General Avatars*/

/*17.a. Roundness and Mask*/

#app-mount .avatarHint-1qgaV3 foreignObject {
	mask: none;
}

#app-mount .wrapper-3t9DeA * {
	overflow: visible;
	mask: none;
}

/*17.b. Status*/

#app-mount .wrapper-3t9DeA .mask-1l8v16>rect[x="22"] {
	x: 0;
	y: 0;
}

#app-mount .wrapper-3t9DeA .cursorDefault-dsQJ1n rect {
	x: -49;
	y: -53;
}

#app-mount .wrapper-3t9DeA[style*="width: 80px;"] {
	position: relative;
	margin-right: 0 !important;
}

#app-mount .wrapper-3t9DeA[style*="width: 80px;"] rect {
	width: 80px;
	height: 80px;
}

#app-mount .wrapper-3t9DeA[style*="width: 32px;"] rect {
	width: 32px;
	height: 32px;
	overflow: visible;
	x: -14.5;
	y: -17;
}

#app-mount .wrapper-3t9DeA rect {
	x: 0;
	y: 0;
	width: 100%;
	height: 100%;
	rx:var(--user-roundness);
	ry: var(--user-roundness);
	fill: transparent;
	stroke-width: 2px;
}

#app-mount .wrapper-3t9DeA rect[fill="#43b581"],
#app-mount .wrapper-3t9DeA rect[fill="rgba(67, 181, 129, 1)"],
#app-mount .wrapper-3t9DeA rect[mask*="online"] {
	stroke: var(--success);
}

#app-mount .wrapper-3t9DeA rect[fill="#faa61a"],
#app-mount .wrapper-3t9DeA rect[fill="rgba(250, 166, 26, 1)"],
#app-mount .wrapper-3t9DeA rect[mask*="idle"] {
	stroke: var(--caution);
}

#app-mount .wrapper-3t9DeA rect[fill="#f04747"],
#app-mount .wrapper-3t9DeA rect[fill="rgba(240, 71, 71, 1)"],
#app-mount .wrapper-3t9DeA rect[mask*="dnd"] {
	stroke: var(--danger);	
}

#app-mount .wrapper-3t9DeA rect[fill="#593695"],
#app-mount .wrapper-3t9DeA rect[mask*="streaming"] {
	stroke: var(--twitch-purple);
}

#app-mount .wrapper-3t9DeA rect[fill="#747f8d"],
#app-mount .wrapper-3t9DeA rect[mask*="offline"] {
	stroke: var(--unavailable);
}

#app-mount .wrapper-3t9DeA rect[mask*="invisible"],
#app-mount .wrapper-3t9DeA rect[fill="rgba(116, 127, 141, 1)"] {
	stroke: var(--invisible);
}

#app-mount .wrapper-3t9DeA rect[x="16"] {
	width: 24px;
	height: 24px;
}

#app-mount .wrapper-3t9DeA rect[x="28"] {
	width: 40px;
	height: 40px;
	overflow: visible;
}

#app-mount .wrapper-3t9DeA[style*="height: 32px"] foreignObject + svg + rect[width="25"] {
	fill: rgba(0, 0, 0, .5);
	x: 0 !important;
	y: 0 !important;
	rx: var(--user-roundness);
	height: 32px;
	width: 32px;
	opacity: 1;
	transition: fill 500ms ease-in-out;
	position: absolute;
	top: 0;
	left: 0;
	opacity: 1;
}

.dots-3Bkt3k circle:nth-child(1) {
	cy: -8;
	cx: -8.5;
}

.dots-3Bkt3k circle:nth-child(2) {
	cy: -8;
	cx: -2.25;
}

.dots-3Bkt3k circle:nth-child(3) {
	cy: -8;
	cx: 4;
}

.wrapper-3t9DeA .pointerEvents-2zdfdO[x="14.5"] {
	fill: rgba(0, 0, 0, 0.5);
	width:28px;
	height:28px;
	x: 2px;
	y: 2px;
	rx:50;
	display:block;
}

/*18. Plugins*/

/*18.a. ThemeRepo and PluginRepo*/

.themerepo-loadingicon path:first-child,
.pluginrepo-loadingicon path:first-child {
	fill:var(--accent);
}

.loadingIconWrapper-PsVJ9m .loadingIcon-cOYMPl {
	height:22px;
	width:22px;
}


.repo-modal .tabBarContainer-1s1u-z {
	border-top:1px solid rgba(255,255,255,0.05) !important;
	box-shadow:0 0 12px var(--lv1) !important;
}

.repo-modal .tabBar-2MuP6-,
.repo-modal .tabBarItem-1b8RUP,
.repo-modal .tabBarContainer-1s1u-z {
	height:45px;
	box-sizing:border-box;
}

.repo-modal .tabBar-2MuP6- {
	position:relative;
	align-items:center;
}

.repo-modal .tabBarItem-1b8RUP {
	margin:0;
	padding:0 15px;
	font-size:var(--size1);
	color:rgba(255,255,255,0.75) !important;
	font-weight:500;
	transition:150ms ease;
	height:25px;
	border-bottom:none;
	overflow:visible;
	box-sizing:border-box;
}

.repo-modal .tabBarItem-1b8RUP.selected-3s45Ha {
	color:#fff;
}

.repo-modal .tabBarItem-1b8RUP::before,
.repo-modal .tabBarItem-1b8RUP::after {
	content:'';
	border-bottom:4px solid;
	height:calc(100% + 15px);
	width:100%;
	position:absolute;
	bottom:-9px;
	left:0;
	opacity:0;
}

.repo-modal .tabBarItem-1b8RUP::after {
	border-color:var(--hover);
	transition:150ms ease opacity, 300ms ease transform;
	transform:scaleX(.5);
	z-index:2;
}

.repo-modal .tabBarItem-1b8RUP.selected-3s45Ha::after,
.repo-modal .tabBarItem-1b8RUP[style*="rgb(255, 255, 255);"]::after {
	opacity:1;
	transform:none;
}

.repo-modal .tabBarItem-1b8RUP::before {
	border-color:rgba(255,255,255,0.07);
	transition:150ms ease opacity;
	z-index:1;
}

.repo-modal .tabBarItem-1b8RUP:hover::before {
	opacity:1 !important;
}

.repo-modal .tabBarItem-1b8RUP:nth-child(2) {
	border-left:1px solid rgba(255,255,255,0.1) !important;
	border-right:1px solid rgba(255,255,255,0.1) !important;
}

.improved-1F5LIN {
	color:var(--accent);
}

.improved-1F5LIN:after {
	background:currentColor;
}

.content-8biNdB ul li:before {
	border-radius:0;
}

.small-2oHLgT .input-3Xdcic,
.small-2oHLgT .tag-2gZFdE {
	color:rgba(255,255,255,0.85);
}

.container-cMG81i {
	background:transparent;
}

.quickSelectLabel-2r3iJ_,
.quickSelectValue-lImyM6,
.small-2oHLgT .input-3Xdcic,
.small-2oHLgT .tag-2gZFdE {
	font-size:var(--size2);
}

/*18.b. TopRoleEverywhere*/

.tag-wWVHyf {
	margin:0;
	margin-right:4px;
	height:18px;
	padding:4px;
	background-color:var(--lv1);
	box-sizing:border-box;
	box-shadow:0 0 10px rgba(0,0,0,0.25);
	border-radius:2px;
	display:flex;
	align-items:center;
	text-overflow:ellipsis;
	font-size:var(--size4);
	text-transform:none;
	max-width:unset;
}

/*18.c. GoogleTranslateOption*/

#app-mount .themedPopout-1TrfdI {
	background:var(--lv1);
	border-radius:0;
	box-shadow:inset 0 0 0 100vmax rgba(255,255,255,0.07), 0 2px 12px var(--lv1);
	border-bottom:2px solid var(--accent);
}

/*18.d. ReadAllNotifications*/

.button-Jt-tIg {
	font-size:var(--size4);
	line-height:normal;
	background: rgba(255, 255, 255, .1) !important;
    text-transform: capitalize;
    transition: 150ms ease all;
    border-radius: 0;
	color: #fff;
	white-space:nowrap;
	overflow:hidden;
	order:-1;
}

.button-Jt-tIg:hover {
	background:var(--accent) !important;
}

.listItem-2P_4kh[style*="height: 20px;"] {
	order:-1;
}

/*19. BetterDiscord*/

/*19.a. Theme and Plugin Entries*/

.bda-slist .bda-footer button,
.bd-pfbtn {
	height:20px !important;
	min-height:20px !important;
}

.bda-slist .bda-footer {
	overflow:visible;
}

.bda-slist .bda-footer a {
	color:var(--accent);
	text-shadow:0 0 12px;
}

.bda-slist .bda-header,
.plugin-settings .title-3sZWYQ {
	font-size:var(--size1) !important;
}

.bda-slist .bda-description,
.bda-slist .bda-footer,
.plugin-settings .titleDefault-a8-ZSr {
	font-size:var(--size2);
}
