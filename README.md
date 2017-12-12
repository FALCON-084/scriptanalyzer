.ui-slider-track.ui-corner-all,
.ui-page-theme-a .ui-slider-track .ui-btn-active,
html .ui-bar-a .ui-slider-track .ui-btn-active,
html .ui-body-a .ui-slider-track .ui-btn-active,
html body .ui-group-theme-a .ui-slider-track .ui-btn-active,
html body div.ui-slider-track.ui-body-a .ui-btn-active {
	background-color: #38c;
	border-color: #38c;
	color: #fff;
	text-shadow: 0 1px 0 #059
}
.ui-hide-label .ui-rangeslider label,
.ui-field-contain>.ui-rangeslider>label {
		float: left;
		width: 20%;
		margin: .5em 2% 0 0
	}
	.ui-popup .ui-field-contain>.ui-rangeslider>label {
		float: none;
		width: auto;
		margin: 0 0 .4em
	}
	div.ui-slider {
	height: 30px;
	margin: .5em 0;
	padding: 0;
	-ms-touch-action: pan-y pinch-zoom double-tap-zoom
}

div.ui-slider:before,
div.ui-slider:after {
	content: "";
	display: table
}

div.ui-slider:after {
	clear: both
}
input.ui-slider-input {
	display: block;
	float: left;
	font-size: 14px;
	font-weight: 700;
	margin: 0;
	padding: 4px;
	width: 40px;
	height: 20px;
	line-height: 20px;
	border-width: 1px;
	border-style: solid;
	outline: 0;
	text-align: center;
	vertical-align: text-bottom;
	-webkit-appearance: none;
	-moz-appearance: none;
	appearance: none;
	-webkit-box-sizing: content-box;
	-moz-box-sizing: content-box;
	box-sizing: content-box
}

.ui-slider-input::-webkit-outer-spin-button,
.ui-slider-input::-webkit-inner-spin-button {
	-webkit-appearance: none;
	margin: 0
}

.ui-slider-track {
	position: relative;
	overflow: visible;
	border-width: 1px;
	border-style: solid;
	height: 15px;
	margin: 0 15px 0 68px;
	top: 6px
}

.ui-slider-track.ui-mini {
	height: 12px;
	top: 8px
}

.ui-slider-track .ui-slider-bg {
	height: 100%
}
.ui-slider-track .ui-btn.ui-slider-handle {
	position: absolute;
	z-index: 1;
	top: 50%;
	width: 28px;
	height: 28px;
	margin: -15px 0 0 -15px;
	outline: 0;
	padding: 0
}

.ui-slider-track.ui-mini .ui-slider-handle {
	height: 14px;
	width: 14px;
	margin: -8px 0 0 -8px
}

select.ui-slider-switch {
	position: absolute!important;
	height: 1px;
	width: 1px;
	overflow: hidden;
	clip: rect(1px, 1px, 1px, 1px)
}

div.ui-slider-switch {
	display: inline-block;
	height: 32px;
	width: 5.8em;
	top: 0
}

div.ui-slider-switch:before,
div.ui-slider-switch:after {
	display: none;
	clear: none
}

div.ui-slider-switch.ui-mini {
	height: 29px;
	top: 0
}
.ui-slider-inneroffset {
	margin: 0 16px;
	position: relative;
	z-index: 1
}

.ui-slider-switch.ui-mini .ui-slider-inneroffset {
	margin: 0 15px 0 14px
}

.ui-slider-switch .ui-btn.ui-slider-handle {
	margin: 1px 0 0 -15px
}

.ui-slider-switch.ui-mini .ui-slider-handle {
	width: 25px;
	height: 25px;
	margin: 1px 0 0 -13px;
	padding: 0
}

.ui-slider-handle-snapping {
	-webkit-transition: left 70ms linear;
	-moz-transition: left 70ms linear;
	transition: left 70ms linear
}

.ui-slider-switch .ui-slider-label {
	position: absolute;
	text-align: center;
	width: 100%;
	overflow: hidden;
	font-size: 16px;
	top: 0;
	line-height: 2;
	min-height: 100%;
	white-space: nowrap;
	cursor: pointer
}

.ui-slider-switch.ui-mini .ui-slider-label {
	font-size: 14px
}

.ui-slider-switch .ui-slider-label-a {
	z-index: 1;
	left: 0;
	text-indent: -1.5em
}
.ui-slider-switch .ui-slider-label-b {
	z-index: 0;
	right: 0;
	text-indent: 1.5em
}

.ui-slider-track .ui-slider-bg,
.ui-slider-switch .ui-slider-label,
.ui-slider-switch .ui-slider-inneroffset,
.ui-slider-handle {
	-webkit-border-radius: inherit;
	border-radius: inherit
}

.ui-field-contain div.ui-slider-switch {
	margin: 0
}

.ui-field-contain div.ui-slider-switch,
.ui-field-contain.ui-hide-label div.ui-slider-switch,
html .ui-popup .ui-field-contain div.ui-slider-switch {
	display: inline-block;
	width: 5.8em
}

.ui-slider-popup {
	width: 64px;
	height: 64px;
	font-size: 36px;
	padding-top: 14px;
	opacity: .8
}

.ui-slider-popup {
	position: absolute!important;
	text-align: center;
	z-index: 100
}

.ui-slider-track .ui-btn.ui-slider-handle {
	font-size: .9em;
	line-height: 30px
}
.ui-rangeslider {
	margin: .5em 0
}

.ui-rangeslider:before,
.ui-rangeslider:after {
	content: "";
	display: table
}

.ui-rangeslider:after {
	clear: both
}

.ui-rangeslider .ui-slider-input.ui-rangeslider-last {
	float: right
}

.ui-rangeslider .ui-rangeslider-sliders {
	position: relative;
	overflow: visible;
	height: 30px;
	margin: 0 68px
}

.ui-rangeslider .ui-rangeslider-sliders .ui-slider-track {
	position: absolute;
	top: 6px;
	right: 0;
	left: 0;
	margin: 0
}

.ui-rangeslider.ui-mini .ui-rangeslider-sliders .ui-slider-track {
	top: 8px
}

.ui-rangeslider .ui-slider-track:first-child .ui-slider-bg {
	display: none
}

.ui-rangeslider .ui-rangeslider-sliders .ui-slider-track:first-child {
	background-color: transparent;
	background: 0;
	border-width: 0;
	height: 0
}
html>body .ui-rangeslider .ui-rangeslider-sliders .ui-slider-track:first-child {
	height: 15px;
	border-width: 1px
}

html>body .ui-rangeslider.ui-mini .ui-rangeslider-sliders .ui-slider-track:first-child {
	height: 12px
}

div.ui-rangeslider label {
	position: absolute!important;
	height: 1px;
	width: 1px;
	overflow: hidden;
	clip: rect(1px, 1px, 1px, 1px)
}

.ui-field-contain .ui-rangeslider input.ui-slider-input,
.ui-field-contain .ui-rangeslider.ui-mini input.ui-slider-input,
.ui-field-contain .ui-rangeslider .ui-rangeslider-sliders,
.ui-field-contain .ui-rangeslider.ui-mini .ui-rangeslider-sliders {
	margin-top: 0;
	margin-bottom: 0
}
