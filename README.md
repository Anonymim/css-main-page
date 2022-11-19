# css-main-page
Main page


@import url('https://fonts.googleapis.com/css?family=Exo+2:600,800|Open+Sans:300,400,600,700');
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    -webkit-transition: none;
    transition: none
}

html {
    font-size: 14px
}

body {
    background: #1a2a65;
    background: radial-gradient(circle at 60% 20%, #0e41a0, #1a2a65, #20123a);
    color: #fff;
    font-family: Open Sans, sans-serif;
    overflow-y: scroll;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    min-height: 100vh
}

body.hidden {
    overflow: hidden;
    height: 100vh;
    position: relative
}

::-moz-selection {
    background: #000;
    color: #fff
}

::selection {
    background: #000;
    color: #fff
}

a,
button {
    font: inherit;
    text-decoration: none;
    cursor: pointer;
}

a {
    color: #4986f5
}

a:hover {
    color: #79a6f8
}

a:active,
a:focus {
    outline: none
}

.wrapper {
    min-height: 100vh;
    min-width: 320px;
    position: relative;
    width: 100%
}

.wrapper .page {
    position: relative;
    padding-left: 280px;
    -webkit-flex: auto;
    flex: auto;
}

.wrapper .main-content {
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    min-height: 100vh;
}

.wrapper .main-content .main-content-top {
    -webkit-flex: auto;
    flex: auto;
    position: relative;
    min-height: 280px
}

.wrapper .main-content .main-content-footer {
    -webkit-flex: none;
    flex: none;
    padding-left: 40px;
    padding-right: 40px
}

.wrapper .main-content .section {
    padding-left: 40px;
    padding-right: 40px;
    padding-bottom: 40px;
    max-width: 1250px;
    margin: 0 auto
}

.wrapper .main-content .section.promo {
    padding-bottom: 0;
    margin-bottom: 40px
}

.blue-bg {
    background: #4986f5!important
}

.color-blue {
    color: #4986f5!important
}

.primary-bg {
    background: #4986f5!important
}

.color-primary {
    color: #4986f5!important
}

.green-bg {
    background: #62ca5b!important
}

.color-green {
    color: #62ca5b!important
}

.pink-bg {
    background: #e86376!important
}

.color-pink {
    color: #e86376!important
}

.light-bg {
    background: #828f9a!important
}

.color-light {
    color: #828f9a!important
}

.medium-bg {
    background: #20242d!important
}

.color-medium {
    color: #20242d!important
}

.middark-bg {
    background: #2c323f!important
}

.color-middark {
    color: #2c323f!important
}

.dark-bg {
    background: #1c2028!important
}

.color-dark {
    color: #1c2028!important
}

.white-bg {
    background: #fff!important
}

.color-white {
    color: #fff!important;
}

.ethereum-bg {
    background: #616991!important
}

.color-ethereum {
    color: #616991!important
}

.warning-bg {
    background: #ffc645!important
}

.color-warning {
    color: #ffc645!important
}

.orange-bg {
    background: #fd9e35!important
}

.color-orange {
    color: #fd9e35!important
}

.no-top-radius {
    border-top-left-radius: 0!important;
    border-top-right-radius: 0!important
}

.no-bottom-radius {
    border-bottom-left-radius: 0!important;
    border-bottom-right-radius: 0!important
}

.relative {
    position: relative
}

.text-center {
    text-align: center!important
}

.text-right {
    text-align: right!important
}

.negative {
    color: #e86376!important
}

.positive {
    color: #62ca5b!important
}

.heading {
    color: #fff;
    font-size: 24px;
    line-height: 30px;
    margin-bottom: 15px;
    font-weight: 600;
    letter-spacing: .3px
}

.typography p {
    font-size: 14px;
    line-height: 22px;
    margin-bottom: 18px;
    color: #c6d0e8;
    font-weight: 300;
    letter-spacing: .15px
}

.typography p:last-child {
    margin-bottom: 0
}

.typography h1:last-child,
.typography h2:last-child {
    margin-bottom: 20px
}

.typography a {
    color: #6bceff
}

.tick-list {
    list-style: none;
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap
}

.tick-list,
.tick-list .tick-badge {
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center
}

.tick-list .tick-badge {
    -webkit-align-items: center;
    background: #3584fd;
    height: 30px;
    width: 72px;
    margin: 0 auto 12px;
    align-items: center;
    border-radius: 100px
}

.tick-list li {
    padding: 0;
    position: relative;
    margin-bottom: 25px;
    font-size: 14px;
    font-weight: 400;
    color: #fff;
    letter-spacing: .15px;
    text-align: center;
    width: 100%
}

.tick-list li:last-child {
    margin-bottom: 0
}

.tick-list li i {
    display: block;
    font-size: 28px;
    margin-bottom: 12px;
    color: #4986f5
}

.form-label {
    margin-bottom: 10px;
    font-size: 13px;
    line-height: 14px;
    color: #7f8596;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.form-label.big {
    color: #fff;
    font-size: 14px;
    font-weight: 600
}

.form-field {
    position: relative
}

.form-field:hover .right-icon {
    color: #4986f5
}

.form-field:hover .right-icon svg {
    fill: #4986f5
}

.form-field .right-icon {
    position: absolute;
    right: 1px;
    top: 1px;
    width: 45px;
    height: calc(100% - 2px);
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    color: #fff;
    pointer-events: none;
    border-radius: 6px;
    background: #333a4a
}

.form-field .right-icon svg {
    -webkit-transition: all .2s ease-out 0s;
    transition: all .2s ease-out 0s;
    display: block
}

.form-field .right-icon.reversed svg {
    -webkit-transform: rotate(180deg);
    transform: rotate(180deg)
}

.form-field.hasArrow:after {
    width: 0;
    height: 0;
    content: "";
    position: absolute;
    right: .75em;
    bottom: 50%;
    -webkit-transform: translateY(50%);
    transform: translateY(50%);
    pointer-events: none;
    border-color: #717787 transparent transparent;
    border-style: solid;
    border-width: 4px 4px 0
}

.form-field select {
    height: 44px;
    font-size: 14px;
    padding: 0 12px;
    width: 100%;
    outline: none!important;
    border-radius: 6px;
    color: #fff;
    background: #2f3542;
    border: 1px solid transparent;
    font-family: Open Sans, sans-serif;
    -webkit-border-image: none;
    border-image: none;
    -webkit-border-image: initial;
    border-image: initial;
    overflow: hidden;
    -webkit-appearance: none
}

.form-field select:focus {
    border-color: #4986f5
}

.form-row {
    margin-bottom: 20px
}

.form-row.inline {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    width: 100%;
    -webkit-justify-content: space-between;
    justify-content: space-between
}

.form-row.inline .form-field,
.form-row.inline .form-label {
    -webkit-flex-basis: 50%;
    flex-basis: 50%
}

.form-row.inline .form-label {
    padding-right: 20px
}

.hasError .input-field {
    border-color: #e86376!important
}

.input-field {
    height: 44px;
    font-size: 14px;
    padding: 0 12px;
    width: 100%;
    outline: none!important;
    border-radius: 6px;
    color: #fff;
    background-color: rgba(255, 255, 255, 0.05);
    border: 1px solid transparent;
    font-family: Open Sans, sans-serif
}

.input-field:not([readonly]):focus {
    border-color: #4986f5
}

.input-field.input-green:not([readonly]):focus {
    border-color: #62ca5b
}

.input-field::-webkit-input-placeholder {
    color: #4e5a61
}

.input-field::-ms-input-placeholder {
    color: #4e5a61
}

.input-field::placeholder {
    color: #4e5a61
}

.input-field[type=button] {
    cursor: pointer;
    text-align: left;
    -webkit-appearance: button;
    -webkit-border-image: none;
    border-image: none;
    -webkit-border-image: initial;
    border-image: initial;
    overflow: hidden;
    outline: none
}

.input-field:disabled {
    background: #212833
}

.input-field.text-gray {
    color: #99a3b8
}

.input-field.small-text {
    font-size: 11px
}

.buttons-group {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    width: 100%;
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    border-radius: 6px;
    overflow: hidden
}

.buttons-group.isMobile {
    position: absolute;
    z-index: 3;
    border: 1px solid #4986f5;
    top: -21px;
    -webkit-transition: opacity .2s ease-in;
    transition: opacity .2s ease-in;
    opacity: 0;
    visibility: hidden;
    will-change: opacity, visibility
}

.buttons-group.isMobile.focus {
    opacity: 1;
    visibility: visible
}

.buttons-group.isMobile .btn-action {
    padding: 12px 5px;
    color: #93a5c5;
    border-right: 1px solid #3e4654
}

.buttons-group.isMobile .btn-action:last-child {
    border-right: 0
}

.buttons-group .btn-action {
    -webkit-flex: auto;
    flex: auto;
    -webkit-flex-grow: 10;
    flex-grow: 10;
    -webkit-flex-shrink: 0;
    flex-shrink: 0;
    font-size: 11px;
    line-height: 12px;
    color: #959fb1;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    padding: 9px 5px;
    cursor: pointer;
    -webkit-transition: all .3s;
    transition: all .3s;
    border: none;
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    outline: none!important;
    font-weight: 400;
    border-radius: 0
}

.buttons-group .btn-action:hover {
    background: rgba(255, 255, 255, 0.10);
    color: #fff
}

.buttons-group .btn-action.isActive {
    color: #fff;
    background-color: rgba(255, 255, 255, 0.10);
    cursor: default;
    border-radius: 3px
}

.buttons-group.buttons-group--tall .btn-action {
    min-height: 36px;
    font-size: 12px;
    color: #fff
}

.btn-edit {
    padding: 0!important
}

.btn-edit.isActive .form-row {
    opacity: 1;
    visibility: visible
}

.btn-edit.isActive .input-field {
    cursor: text
}

.btn-edit .form-row {
    max-width: 100%;
    height: 100%;
    margin: 0;
    position: absolute;
    opacity: 0
}

.btn-edit .form-field,
.btn-edit .input-valid {
    height: 100%
}

.btn-edit .input-field {
    height: 100%;
    cursor: pointer;
    border-radius: 0 6px 6px 0
}

.input-with-icon {
    position: relative;
    width: 100%
}

.input-with-icon.input-with-left-icon input {
    padding-left: 35px
}

.input-with-icon.input-with-left-icon .input-left-icon {
    position: absolute;
    left: 13px;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    margin-right: 6px
}

.input-with-icon.input-with-left-icon .input-left-icon i {
    font-size: 16px;
    display: block
}

.input-with-icon.input-with-left-icon .input-left-icon img {
    width: 16px;
    display: block
}

.grouped-fields {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: stretch;
    align-items: stretch;
    width: 100%;
    margin-bottom: 15px
}

.grouped-fields .form-row {
    width: 100%;
    margin: 0 -6px 0 0
}

.grouped-fields .input-field {
    border-radius: 0;
    -webkit-flex: auto;
    flex: auto;
    margin-right: -6px
}

.grouped-fields .input-field:first-child {
    border-radius: 6px 0 0 6px
}

.grouped-fields .input-field:last-child {
    border-radius: 0 6px 6px 0;
    margin-right: 0
}

.grouped-fields .input-with-icon {
    margin-right: -6px
}

.grouped-fields .btn {
    -webkit-flex: none;
    flex: none;
    position: relative;
    z-index: 2;
    font-weight: 600
}

.rotating {
    -webkit-animation: rotating 2s linear infinite;
    animation: rotating 2s linear infinite
}

.ps {
    overflow: hidden!important;
    overflow-anchor: none;
    touch-action: auto
}

.ps__rail-x {
    height: 15px;
    bottom: 0
}

.ps__rail-x,
.ps__rail-y {
    display: none;
    opacity: 0;
    -webkit-transition: background-color .2s linear, opacity .2s linear;
    transition: background-color .2s linear, opacity .2s linear;
    position: absolute
}

.ps__rail-y {
    width: 15px;
    right: 0;
    left: auto!important
}

.ps--active-x>.ps__rail-x,
.ps--active-y>.ps__rail-y {
    display: block;
    background-color: initial
}

.ps--focus>.ps__rail-x,
.ps--focus>.ps__rail-y,
.ps--scrolling-x>.ps__rail-x,
.ps--scrolling-y>.ps__rail-y,
.ps:hover>.ps__rail-x,
.ps:hover>.ps__rail-y {
    opacity: .6
}

.ps .ps__rail-x.ps--clicking,
.ps .ps__rail-x:focus,
.ps .ps__rail-x:hover,
.ps .ps__rail-y.ps--clicking,
.ps .ps__rail-y:focus,
.ps .ps__rail-y:hover {
    opacity: .9
}

.ps__thumb-x {
    transition: background-color .2s linear, height .2s ease-in-out;
    -webkit-transition: background-color .2s linear, height .2s ease-in-out;
    height: 6px;
    bottom: 2px
}

.ps__thumb-x,
.ps__thumb-y {
    background-color: #434b53;
    border-radius: 6px;
    position: absolute
}

.ps__thumb-y {
    transition: background-color .2s linear, width .2s ease-in-out;
    -webkit-transition: background-color .2s linear, width .2s ease-in-out;
    width: 6px;
    right: 2px
}

.ps__rail-x.ps--clicking .ps__thumb-x,
.ps__rail-x:focus>.ps__thumb-x,
.ps__rail-x:hover>.ps__thumb-x {
    background-color: #434b53;
    height: 8px
}

.ps__rail-y.ps--clicking .ps__thumb-y,
.ps__rail-y:focus>.ps__thumb-y,
.ps__rail-y:hover>.ps__thumb-y {
    background-color: #434b53;
    width: 8px
}

.scrollbar-container {
    position: relative;
    height: 100%
}

.popover {
    top: 0;
    left: 0;
    z-index: 1060;
    max-width: 276px;
    font-size: .875rem;
    word-wrap: break-word;
    background-color: rgba(26, 42, 101, .95);
    background-clip: padding-box;
    border: 1px solid #242932;
    border-radius: .3rem;
}

.popover,
.popover .arrow {
    position: absolute;
    display: block
}

.popover .arrow {
    width: 1rem;
    height: .5rem;
    margin: 0 .3rem
}

.popover .arrow:after,
.popover .arrow:before {
    position: absolute;
    display: block;
    content: "";
    border-color: transparent;
    border-style: solid
}

.bs-popover-auto[x-placement^=top],
.bs-popover-top {
    margin-bottom: .5rem
}

.bs-popover-auto[x-placement^=top] .arrow,
.bs-popover-top .arrow {
    bottom: calc(-.5rem + -1px)
}

.bs-popover-auto[x-placement^=top] .arrow:after,
.bs-popover-auto[x-placement^=top] .arrow:before,
.bs-popover-top .arrow:after,
.bs-popover-top .arrow:before {
    border-width: .5rem .5rem 0
}

.bs-popover-auto[x-placement^=top] .arrow:before,
.bs-popover-top .arrow:before {
    bottom: 0;
    border-top-color: rgba(26, 42, 101, .95);
}

.bs-popover-auto[x-placement^=top] .arrow:after,
.bs-popover-top .arrow:after {
    bottom: 1px;
    border-top-color: rgba(26, 42, 101, .95);
}

.bs-popover-auto[x-placement^=right],
.bs-popover-right {
    margin-left: .5rem
}

.bs-popover-auto[x-placement^=right] .arrow,
.bs-popover-right .arrow {
    left: calc(-.5rem + -1px);
    width: .5rem;
    height: 1rem;
    margin: .3rem 0
}

.bs-popover-auto[x-placement^=right] .arrow:after,
.bs-popover-auto[x-placement^=right] .arrow:before,
.bs-popover-right .arrow:after,
.bs-popover-right .arrow:before {
    border-width: .5rem .5rem .5rem 0
}

.bs-popover-auto[x-placement^=right] .arrow:before,
.bs-popover-right .arrow:before {
    left: 0;
    border-right-color: #242932
}

.bs-popover-auto[x-placement^=right] .arrow:after,
.bs-popover-right .arrow:after {
    left: 1px;
    border-right-color: rgba(47, 57, 70, .95)
}

.bs-popover-auto[x-placement^=bottom],
.bs-popover-bottom {
    margin-top: .5rem
}

.bs-popover-auto[x-placement^=bottom] .arrow,
.bs-popover-bottom .arrow {
    top: calc(-.5rem + -1px)
}

.bs-popover-auto[x-placement^=bottom] .arrow:after,
.bs-popover-auto[x-placement^=bottom] .arrow:before,
.bs-popover-bottom .arrow:after,
.bs-popover-bottom .arrow:before {
    border-width: 0 .5rem .5rem
}

.bs-popover-auto[x-placement^=bottom] .arrow:before,
.bs-popover-bottom .arrow:before {
    top: 0;
    border-bottom-color: #242932
}

.bs-popover-auto[x-placement^=bottom] .arrow:after,
.bs-popover-bottom .arrow:after {
    top: 1px;
    border-bottom-color: rgba(47, 57, 70, .95)
}

.bs-popover-auto[x-placement^=bottom] .popover-header:before,
.bs-popover-bottom .popover-header:before {
    position: absolute;
    top: 0;
    left: 50%;
    display: block;
    width: 1rem;
    margin-left: -.5rem;
    content: "";
    border-bottom: 1px solid rgba(41, 50, 61, .95)
}

.bs-popover-auto[x-placement^=left],
.bs-popover-left {
    margin-right: .5rem
}

.bs-popover-auto[x-placement^=left] .arrow,
.bs-popover-left .arrow {
    right: calc(-.5rem + -1px);
    width: .5rem;
    height: 1rem;
    margin: .3rem 0
}

.bs-popover-auto[x-placement^=left] .arrow:after,
.bs-popover-auto[x-placement^=left] .arrow:before,
.bs-popover-left .arrow:after,
.bs-popover-left .arrow:before {
    border-width: .5rem 0 .5rem .5rem
}

.bs-popover-auto[x-placement^=left] .arrow:before,
.bs-popover-left .arrow:before {
    right: 0;
    border-left-color: #242932
}

.bs-popover-auto[x-placement^=left] .arrow:after,
.bs-popover-left .arrow:after {
    right: 1px;
    border-left-color: rgba(47, 57, 70, .95)
}

.popover-header {
    padding: .5rem .75rem;
    margin-bottom: 0;
    font-size: 1rem;
    color: inherit;
    background-color: rgba(41, 50, 61, .95);
    border-bottom: 1px solid rgba(31, 37, 46, .95);
    border-top-left-radius: calc(.3rem - 1px);
    border-top-right-radius: calc(.3rem - 1px)
}

.popover-header:empty {
    display: none
}

.popover-body {
    padding: .5rem .75rem;
    color: #212529
}

.btn {
    font-size: 13px;
    font-weight: 500;
    line-height: 18px;
    display: -webkit-inline-flex;
    display: inline-flex;
    font-family: Open Sans, sans-serif;
    padding: 9px 20px;
    cursor: pointer;
    -webkit-transition: all .3s;
    transition: all .3s;
    text-decoration: none;
    color: #fff;
    border: 1px solid transparent;
    border-radius: 6px;
    outline: none;
    background: #4986f5;
    -webkit-align-items: center;
    align-items: center;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.auth-buttons .btn .icon {
    margin-left: 5px;
}

.btn:hover {
    background: #1966f2;
    color: inherit
}

.btn[disabled] {
    opacity: .8;
    pointer-events: none;
    cursor: not-allowed
}

.btn.hasP span:first-letter {
    color: #6bceff
}

.btn.lg {
    padding: 13px 30px
}

.btn.sm {
    font-size: 11px;
    padding: 5px 13px;
    letter-spacing: .28px
}

.btn-block {
    display: block;
    width: 100%
}

.btn.withBadge {
    position: relative
}

.btn-with-input {
    background-color: #1c2028;
    padding: 6px
}

.btn-with-input.isActive {
    background-color: #4986f5
}

.btn-with-input .input-field {
    height: 28px;
    line-height: 28px
}

.btn-reset {
    background-color: #1c2028;
    -webkit-justify-content: center;
    justify-content: center
}

.btn-reset.isActive {
    background-color: #4986f5
}

.btn-clear {
    width: 100%;
    -webkit-justify-content: center;
    justify-content: center;
    padding: 11px 20px;
    background: #333a48;
    color: #959fb1;
    font-weight: 400
}

.btn-clear.isMobile {
    margin-top: auto;
    margin-bottom: 20px;
    height: 44px;
    width: calc(50% - 5px)
}

.btn-clear:hover {
    background: #373e4c;
    color: #4986f5
}

.btn.isActive {
    cursor: default
}

.btn:not(.btn-light).btn-blue {
    background: #4986f5
}

.btn:not(.btn-light).btn-blue:not(.disabled):hover {
    background: #1966f2
}

.btn:not(.btn-light).btn-primary {
    background: #4986f5
}

.btn:not(.btn-light).btn-primary:not(.disabled):hover {
    background: #1966f2
}

.btn:not(.btn-light).btn-warning {
    background: #ffc645
}

.btn:not(.btn-light).btn-warning:not(.disabled):hover {
    background: #ffb612
}

.btn:not(.btn-light).btn-green {
    background: #62ca5b
}

.btn:not(.btn-light).btn-green:not(.disabled):hover {
    background: #43b73b
}

.btn:not(.btn-light).btn-gray {
    background: #272d39
}

.btn:not(.btn-light).btn-gray:not(.disabled):hover {
    background: #12151b
}

.btn:not(.btn-light).btn-black {
    background: #1c2028
}

.btn:not(.btn-light).btn-black:not(.disabled):hover {
    background: #07080a
}

.btn:not(.btn-light).btn-yellow {
    background: #ffd000
}

.btn:not(.btn-light).btn-yellow:not(.disabled):hover {
    background: #cca600
}

.btn:not(.btn-light).btn-red {
    background: #e86376
}

.btn:not(.btn-light).btn-red:not(.disabled):hover {
    background: #e1374f
}

.btn:not(.btn-light).btn-light-gray {
    background: #3a4151
}

.btn:not(.btn-light).btn-light-gray:not(.disabled):hover {
    background: #252933
}

.btn:not(.btn-light).btn-transparent,
.btn:not(.btn-light).btn-transparent:not(.disabled):hover {
    background: transparent
}

.btn:not(.btn-light).btn-yellow {
    color: #65550e
}

.btn:not(.btn-light).btn-yellow:not(.disabled):hover {
    background: #ffd933
}

.btn:not(.btn-light).btn-warning {
    color: rgba(0, 0, 0, .6)
}

.btn:not(.btn-light).btn-transparent {
    color: #7d8a98
}

.btn:not(.btn-light).btn-transparent:hover {
    color: #fff
}

.btn-link {
    padding: 0;
    background-color: initial;
    font-weight: inherit;
    font-size: inherit;
    border: none;
    border-radius: 0;
    color: #4986f5;
    height: inherit!important;
    width: inherit!important;
}

.btn-link:hover {
    background: transparent!important;
    color: #fff!important
}

.btn.btn-light {
    background: transparent;
    color: #959fb1;
    border: 1px solid hsla(0, 0%, 100%, .08);
    box-shadow: none
}

.btn.btn-light:not(.disabled):hover {
    background: #4986f5;
    border-color: #4986f5;
    color: #fff
}

.btn.btn-light.btn-blue {
    color: #fff;
    border-color: #4986f5
}

.btn.btn-light.btn-blue:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #4986f5;
    color: #4986f5
}

.btn.btn-light.btn-blue.isActive {
    background: #4986f5;
    border-color: #4986f5;
    color: #fff
}

.btn.btn-light.btn-primary {
    color: #fff;
    border-color: #4986f5
}

.btn.btn-light.btn-primary:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #4986f5;
    color: #4986f5
}

.btn.btn-light.btn-primary.isActive {
    background: #4986f5;
    border-color: #4986f5;
    color: #fff
}

.btn.btn-light.btn-warning {
    color: #fff;
    border-color: #ffc645
}

.btn.btn-light.btn-warning:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #ffc645;
    color: #ffc645
}

.btn.btn-light.btn-warning.isActive {
    background: #ffc645;
    border-color: #ffc645;
    color: #fff
}

.btn.btn-light.btn-green {
    color: #fff;
    border-color: #62ca5b
}

.btn.btn-light.btn-green:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #62ca5b;
    color: #62ca5b
}

.btn.btn-light.btn-green.isActive {
    background: #62ca5b;
    border-color: #62ca5b;
    color: #fff
}

.btn.btn-light.btn-gray {
    color: #fff;
    border-color: #272d39
}

.btn.btn-light.btn-gray:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #272d39;
    color: #272d39
}

.btn.btn-light.btn-gray.isActive {
    background: #272d39;
    border-color: #272d39;
    color: #fff
}

.btn.btn-light.btn-black {
    border-color: #1c2028
}

.btn.btn-light.btn-black:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #1c2028;
    color: #1c2028
}

.btn.btn-light.btn-black.isActive {
    background: #1c2028;
    border-color: #1c2028;
    color: #fff
}

.btn.btn-light.btn-yellow {
    color: #fff;
    border-color: #ffd000
}

.btn.btn-light.btn-yellow:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #ffd000;
    color: #ffd000
}

.btn.btn-light.btn-yellow.isActive {
    background: #ffd000;
    border-color: #ffd000;
    color: #fff
}

.btn.btn-light.btn-red {
    color: #fff;
    border-color: #e86376
}

.btn.btn-light.btn-red:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #e86376;
    color: #e86376
}

.btn.btn-light.btn-red.isActive {
    background: #e86376;
    border-color: #e86376;
    color: #fff
}

.btn.btn-light.btn-light-gray {
    color: #fff;
    border-color: #3a4151
}

.btn.btn-light.btn-light-gray:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: #3a4151;
    color: #3a4151
}

.btn.btn-light.btn-light-gray.isActive {
    background: #3a4151;
    border-color: #3a4151;
    color: #fff
}

.btn.btn-light.btn-transparent {
    color: #fff;
    border-color: transparent
}

.btn.btn-light.btn-transparent:not(.disabled):not(.isActive):hover {
    background: transparent;
    border-color: transparent;
    color: transparent
}

.btn.btn-light.btn-transparent.isActive {
    background: transparent;
    border-color: transparent;
    color: #fff
}

.btn.btn-light.btn-black {
    color: #fff
}

.btn.btn-light.btn-black:not(.disabled):not(.isActive):hover {
    color: #8a96ab
}

.btn .btn-badge {
    position: absolute;
    -webkit-transition: all .3s ease 0s;
    transition: all .3s ease 0s;
    background-color: #4986f5;
    top: -13px;
    right: -8px;
    width: 23px;
    height: 23px;
    font-size: 12px;
    line-height: 23px;
    border-radius: 50%;
    color: #fff
}

.btn.btn-bet-clear {
    position: absolute;
    background: transparent;
    right: 6px;
    top: 11px;
    font-size: 10px;
    padding: 5px;
    color: #7f8596;
    -webkit-transition: .3s ease-in;
    transition: .3s ease-in;
    opacity: 0.5;
}

.btn.btn-bet-clear.isActive {
    opacity: 1
}

.btn.btn-bet-clear:hover {
    color: #9ba0ad;
    opacity: 1;
}

.logo {
    cursor: pointer;
    -webkit-transition: all .3s;
    transition: all .3s;
    color: #fff;
    font-size: 24px;
    display: block;
    /* max-width: 100%; */
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

.logo,
.logo:focus {
    outline: none
}

.logo img {
    display: block;
    max-width: 100%;
    padding: 0;
    height: auto
}

.logo:hover {
    color: #4986f5;
    opacity: .8
}

.header .logo {
    display: none
}

.header .logo img {
    width: 119px;
    max-width: 100%;
    padding: 0 5%
}

.dropdown {
    position: relative;
    display: inline-block
}

.dropdown .dropdown-toggle {
    padding: 10px 30px 10px 15px;
    -webkit-transition: none;
    transition: none
}

.dropdown .dropdown-toggle,
.dropdown .dropdown-toggle .image {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.dropdown .dropdown-toggle .image {
    position: relative;
    margin-right: 9px
}

.dropdown .dropdown-toggle .image img {
    width: 16px
}

.dropdown .opener {
    border: none;
    width: 14px;
    height: 14px;
    -webkit-transition: -webkit-transform .2s ease-out;
    transition: -webkit-transform .2s ease-out;
    transition: transform .2s ease-out;
    transition: transform .2s ease-out, -webkit-transform .2s ease-out;
    position: absolute;
    right: 12px;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%)
}

.dropdown.show .dropdown-menu {
    display: block;
    max-height: 150px;
    overflow-x: hidden;
    overflow-y: scroll;
}

.dropdown.show .dropdown-menu::-webkit-scrollbar-track {
    background-color: rgba(255, 255, 255, .05);
}

.dropdown.show .dropdown-menu::-webkit-scrollbar {
    width: 2px;
    background-color: rgba(255, 255, 255, .05);
}

.dropdown.show .dropdown-menu::-webkit-scrollbar-thumb {
    background-color: #4986f5;
}

.dropdown.show .opener {
    -webkit-transform: translateY(-50%) rotate(-180deg);
    transform: translateY(-50%) rotate(-180deg)
}

.dropdown .dropdown-error {
    padding: .5em;
    text-align: center;
    font-weight: 700;
    color: #e86376
}

.dropdown-menu {
    position: absolute;
    top: 100%;
    left: 0;
    z-index: 1000;
    display: none;
    width: 100%;
    min-width: 10rem;
    margin: 0;
    color: #fff;
    text-align: left;
    list-style: none;
    background-color: #1a2a65;
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    background-clip: padding-box;
    will-change: max-height;
    border-radius: 6px;
}

.dropdown-menu:focus {
    outline: none
}

.dropdown-menu[x-placement^=bottom],
.dropdown-menu[x-placement^=left],
.dropdown-menu[x-placement^=right],
.dropdown-menu[x-placement^=top] {
    right: auto;
    bottom: auto
}

.dropdown-item {
    display: -webkit-flex;
    display: flex;
    width: 100%;
    padding: .75rem;
    cursor: pointer;
    outline: none;
    clear: both;
    font-weight: 400;
    color: #7f8596;
    text-align: inherit;
    white-space: nowrap;
    background-color: initial;
    border: 0
}

.dropdown-item:focus,
.dropdown-item:hover {
    text-decoration: none;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.dropdown-item.active,
.dropdown-item:active {
    color: #fff;
    text-decoration: none;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.dropdown-item.disabled,
.dropdown-item:disabled {
    color: #6c757d;
    background-color: initial
}

.dropdown-item .image {
    height: 19px;
    position: relative;
    width: 27px;
    margin-right: 15px
}

.dropdown-item .image img {
    bottom: 0;
    height: auto;
    left: 0;
    margin: auto;
    max-height: 100%;
    max-width: 100%;
    position: absolute;
    right: 0;
    top: 0;
    width: auto
}

.bottom-start.dropdown.show .btn {
    border-radius: 6px 6px 0 0;
    border-bottom: 1px solid #3a4152
}

.bottom-start.dropdown.show .dropdown-item:last-child,
.bottom-start.dropdown.show .dropdown-menu {
    border-radius: 0 0 6px 6px
}

.top-start.dropdown.show .btn {
    border-top: 1px solid #3a4152;
    border-radius: 0 0 6px 6px
}

.top-start.dropdown.show .dropdown-item:first-child,
.top-start.dropdown.show .dropdown-menu {
    border-radius: 6px 6px 0 0
}

.rounded.dropdown.show .dropdown-menu {
    margin-top: 3px;
    border-radius: 6px
}

.rounded.dropdown.show .dropdown-item:first-child,
.rounded.dropdown.show .dropdown-item:last-child {
    border-radius: 6px
}

.animated-number {
    position: relative
}

.animated-number .animated-block {
    position: absolute;
    left: 0;
    bottom: 0;
    opacity: 0;
    font-size: inherit;
    font-weight: inherit;
    white-space: nowrap;
    color: #e86376;
    -webkit-animation-duration: .7s;
    animation-duration: .7s;
    -webkit-animation-name: balance;
    animation-name: balance;
    -webkit-animation-timing-function: ease-out;
    animation-timing-function: ease-out;
    -webkit-animation-direction: normal;
    animation-direction: normal;
    width: 100%
}

.animated-number.isPositive .animated-block {
    color: #62ca5b;
    animation-direction: reverse
}

.animated-number.isAnimate .animated-block {
    -webkit-animation-name: isSlidingFrame;
    animation-name: isSlidingFrame
}

.deposit-wrap .tooltip-helper {
    position: absolute;
    top: 100%;
    margin-top: 3px;
    visibility: hidden;
    opacity: 0;
    -webkit-transform: scale(0);
    transform: scale(0)
}

.deposit-wrap .tooltip-helper .wrap {
    padding: 7px 15px;
    font-size: 14px;
    background: #20242d;
    border: 1px solid #4986f5;
    position: relative;
    border-radius: 6px;
    box-shadow: 7px 9px 20px 0 rgba(0, 0, 0, .7)
}

.deposit-wrap .tooltip-helper .wrap:after,
.deposit-wrap .tooltip-helper .wrap:before {
    bottom: 100%;
    left: 18px;
    border: solid transparent;
    content: " ";
    height: 0;
    width: 0;
    position: absolute;
    pointer-events: none
}

.deposit-wrap .tooltip-helper .wrap:after {
    border-color: rgba(32, 36, 45, 0);
    border-right-width: 5px;
    border-left-width: 5px;
    border-bottom: 7px solid #20242d;
    margin-left: -7px
}

.deposit-wrap .tooltip-helper .wrap:before {
    border-color: rgba(73, 134, 245, 0);
    border-right-width: 6px;
    border-left-width: 6px;
    border-bottom: 8px solid #4986f5;
    margin-left: -8px
}

.deposit-wrap .tooltip-helper .value {
    color: #ffc645;
    font-weight: 700
}

.deposit-wrap .tooltip-helper.visible {
    visibility: visible;
    opacity: 1;
    -webkit-transition: .2s ease-out;
    transition: .2s ease-out;
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-animation: swing .3s ease-out;
    animation: swing .3s ease-out;
    -webkit-animation-iteration-count: 2;
    animation-iteration-count: 2;
    -webkit-animation-delay: 1s;
    animation-delay: 1s
}

.deposit-wrap {
    display: -webkit-flex;
    display: flex;
    position: relative
}

.deposit-wrap .dropdown {
    position: static
}

.deposit-wrap .dropdown>.btn {
    background-color: rgba(255, 255, 255, 0.10);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    border-radius: 6px 0 0 6px!important;
    border-bottom: 0!important;
    padding: 0 25px 0 8px;
    height: 100%;
    position: relative
}

.deposit-wrap .dropdown>.btn .selected {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.deposit-wrap .dropdown>.btn .selected.balance svg {
    fill: #62ca5b
}

.deposit-wrap .dropdown>.btn .selected.bonus svg {
    fill: #ffc645
}

.deposit-wrap .dropdown>.btn .selected svg {
    width: 14px;
    height: 14px
}

.deposit-wrap .dropdown>.btn .opener {
    width: 14px;
    height: 14px;
    right: 6px
}

.deposit-wrap .dropdown>.btn .opener svg {
    height: 100%;
    width: 100%;
    display: block;
    fill: #7f8596
}

.deposit-wrap .dropdown>.btn:hover {
    background-color: rgba(255, 255, 255, 0.15);
}

.deposit-wrap .dropdown-item {
    padding: 10px 15px
}

.deposit-wrap .balance-item {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    color: #fff;
    width: 100%
}

.deposit-wrap .balance-item.balance svg {
    fill: #62ca5b
}

.deposit-wrap .balance-item.balance .value {
    color: #62ca5b
}

.deposit-wrap .balance-item.bonus svg {
    fill: #ffc645
}

.deposit-wrap .balance-item.bonus .value {
    color: #ffc645
}

.deposit-wrap .balance-item svg {
    margin-right: 8px
}

.deposit-wrap .balance-item .value {
    margin-left: auto;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    border-radius: 6px;
    padding: 4px 8px;
    font-size: 12px
}

.deposit-wrap .btn-light-gray {
    background: #3a4151
}

.deposit-wrap .btn-light-gray:focus,
.deposit-wrap .btn-light-gray:hover {
    background: #454d60!important
}

.deposit-block {
    border-radius: 0 6px 6px 0;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-transition: all .3s;
    transition: all .3s
}

.deposit-block .btn {
    width: 104px;
    -webkit-justify-content: center;
    justify-content: center;
}

.deposit-block .select-field {
    cursor: default;
    padding: 0 10px;
    font-family: Exo\ 2, Open Sans, sans-serif;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    width: 120px;
    font-size: 14px;
}

.deposit-block .select-field svg {
    margin: 1px 7px 0 0;
    width: 16px;
    height: 16px;
    color: #959fb1
}

.top-nav {
    display: -webkit-flex;
    display: flex;
    list-style: none;
    -webkit-align-items: center;
    align-items: center
}

.top-nav .icon {
    width: 14px;
    height: 14px;
    margin: -2px 5px 0 0
}

.top-nav .icon-gamepad {
    width: 16px;
    height: 16px;
    margin-top: -1px
}

.top-nav .icon-tasks {
    margin-top: 0
}

.top-nav li {
    margin-right: 3px;
    position: relative
}

.top-nav li:last-child {
    margin-right: 0
}

.top-nav li .badge {
    color: #fff;
    position: absolute;
    top: -2px;
    right: -5px;
    background: #4986f5;
    border-radius: 50%;
    height: 15px;
    width: 15px;
    text-align: center;
    font-size: 10px;
    line-height: 14px;
    z-index: 1
}

.top-nav li .btn,
.top-nav li a {
    display: -webkit-flex;
    display: flex;
    border-radius: 3px;
    -webkit-align-items: center;
    align-items: center;
    padding: 8px 10px;
    font-size: 12px;
    line-height: 16px;
    color: #828f9a;
    letter-spacing: -.21px;
    border: 0;
    font-weight: 400;
    background-color: initial
}

.top-nav li .btn i,
.top-nav li a i {
    margin-right: 5px;
    font-size: 16px;
    display: block
}

.top-nav li .btn i.icon-shopping-basket,
.top-nav li a i.icon-shopping-basket {
    font-size: 13px;
    position: relative;
    top: -1px
}

.top-nav li .btn.isActive,
.top-nav li .btn:focus,
.top-nav li .btn:hover,
.top-nav li a.isActive,
.top-nav li a:focus,
.top-nav li a:hover {
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    color: #fff
}

.top-nav li .btn.isActive,
.top-nav li a.isActive {
    cursor: default
}

.top-nav li.current a {
    background: #242932;
    color: #fff
}

.top-nav li:focus {
    outline: none
}

.top-nav li .toggle {
    position: relative
}

.top-nav li .toggle .btn {
    padding: 8px 28px 8px 13px;
    width: 100%
}

.top-nav li .toggle.isOpen .icon-down {
    -webkit-transform: translateY(-50%) rotate(-180deg);
    transform: translateY(-50%) rotate(-180deg)
}

.top-nav li .toggle .icon-down {
    margin: 0;
    width: 14px;
    height: 14px;
    position: absolute;
    right: 10px;
    -webkit-transition: -webkit-transform .15s ease-out;
    transition: -webkit-transform .15s ease-out;
    transition: transform .15s ease-out;
    transition: transform .15s ease-out, -webkit-transform .15s ease-out;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%)
}

.top-nav li .toggle>ul {
    position: absolute;
    left: 0;
    top: 37px;
    min-width: 120px;
    background-color: rgba(255, 255, 255, 0.15);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-align-items: stretch;
    align-items: stretch;
    border-radius: 3px;
    box-shadow: 0 0 1px hsla(0, 0%, 100%, .1);
    overflow: hidden;
    max-height: 0;
    -webkit-transition: max-height .15s ease-out;
    transition: max-height .15s ease-out;
    z-index: 3
}

.top-nav li .toggle>ul.isOpen {
    max-height: 250px
}

.top-nav li .toggle>ul li {
    margin-right: 0
}

.top-nav li .toggle>ul li a {
    white-space: nowrap;
    padding: 15px 13px
}

.top-nav li .toggle>ul li a:hover {
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    color: #fff
}

.top-nav-wrapper {
    position: relative
}

.top-nav-wrapper .opener {
    display: none;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-align-items: stretch;
    align-items: stretch;
    width: 20px;
    cursor: pointer;
    -webkit-transition: all .3s;
    transition: all .3s;
    border: 0;
    outline: none;
    background-color: initial
}

.top-nav-wrapper .opener .bar {
    height: 2px;
    width: 100%;
    background: #fff;
    margin-bottom: 5px;
    border-radius: 1px;
    -webkit-transition: all .3s;
    transition: all .3s
}

.top-nav-wrapper .opener .bar:last-child {
    margin-bottom: 0
}

.top-nav-wrapper .opener.opened .bar:first-child {
    -webkit-transform-origin: 0 1px;
    transform-origin: 0 1px;
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg)
}

.top-nav-wrapper .opener.opened .bar:nth-child(2) {
    width: 0
}

.top-nav-wrapper .opener.opened .bar:nth-child(3) {
    -webkit-transform-origin: 0 1px;
    transform-origin: 0 1px;
    -webkit-transform: rotate(-45deg);
    transform: rotate(-45deg)
}

.header {
    -webkit-justify-content: center;
    justify-content: center;
    padding: 40px;
    -webkit-transition: padding .3s;
    transition: padding .3s;
    min-width: 320px;
    position: fixed;
    top: 0;
    width: calc(100% - 280px);
    z-index: 100;
}

.header,
.header .header-inner {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.header .header-inner {
    -webkit-justify-content: space-between;
    justify-content: space-between;
    max-width: 1170px;
    width: 100%
}

.header.sticky {
    padding: 22px 40px;
    background: #1a2a65;
}

.header .auth-buttons .btn:first-child {
    /* margin-right: 10px */
}

.modal-open {
    overflow: hidden
}

.modal-open .modal {
    overflow-x: hidden;
    overflow-y: auto
}

.modal {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 1050;
    display: none;
    overflow: hidden;
    outline: 0
}

.modal-dialog {
    position: relative;
    width: auto;
    margin: .5rem;
    pointer-events: none
}

.modal.fade .modal-dialog {
    -webkit-transition: -webkit-transform .3s ease-out;
    transition: -webkit-transform .3s ease-out;
    transition: transform .3s ease-out;
    transition: transform .3s ease-out, -webkit-transform .3s ease-out;
    -webkit-transform: translateY(-50px);
    transform: translateY(-50px)
}

.modal.show .modal-dialog {
    -webkit-transform: none;
    transform: none
}

.modal-dialog-centered {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    min-height: calc(100% - 1rem)
}

.modal-dialog-centered:before {
    display: block;
    height: calc(100vh - 1rem);
    content: ""
}

.modal-content {
    position: relative;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    pointer-events: auto;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid rgba(0, 0, 0, .2);
    border-radius: .3rem;
    outline: 0
}

.modal-backdrop {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 1040;
    background-color: #000
}

.modal-backdrop.fade {
    opacity: 0
}

.modal-backdrop.show {
    opacity: .5
}

.modal-header {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: flex-start;
    align-items: flex-start;
    -webkit-justify-content: space-between;
    justify-content: space-between;
    padding: 1rem;
    border-bottom: 1px solid #e9ecef;
    border-top-left-radius: .3rem;
    border-top-right-radius: .3rem
}

.modal-header .close {
    padding: 1rem;
    margin: -1rem -1rem -1rem auto
}

.modal-title {
    margin-bottom: 0;
    line-height: 1.5
}

.modal-body {
    position: relative;
    -webkit-flex: 1 1 auto;
    flex: 1 1 auto;
    padding: 1rem
}

.modal-footer {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: flex-end;
    justify-content: flex-end;
    padding: 1rem;
    border-top: 1px solid #e9ecef;
    border-bottom-right-radius: .3rem;
    border-bottom-left-radius: .3rem
}

.modal-footer>:not(:first-child) {
    margin-left: .25rem
}

.modal-footer>:not(:last-child) {
    margin-right: .25rem
}

.modal-scrollbar-measure {
    position: absolute;
    top: -9999px;
    width: 50px;
    height: 50px;
    overflow: scroll
}

.fade {
    -webkit-transition: opacity .15s linear;
    transition: opacity .15s linear
}

.fade:not(.show) {
    opacity: 0
}

.modal-content {
    background: linear-gradient(to right top, #1d1034, #19275b);
    width: 100%;
    max-width: 900px;
    border-radius: 6px;
    border: none
}

.modal-body {
    padding: 0
}

.modal-dialog {
    max-width: 900px
}

.modal-close {
    position: absolute;
    right: 10px;
    top: 10px;
    z-index: 5;
    width: 31px;
    height: 31px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    cursor: pointer;
    outline: none;
    background: transparent;
    border: none
}

.modal-close svg {
    width: 11px;
    height: 11px;
    display: block;
    fill: hsla(0, 0%, 100%, .13);
    -webkit-transition: all .3s;
    transition: all .3s
}

.modal-close:hover svg {
    fill: #fff
}

.container {
    width: 100%;
    max-width: 1170px;
    margin: 0 auto
}

.wrapper .main-content .bets-section {
    max-width: 100%;
}

.section-page {
    padding: 30px;
    border-radius: 6px;
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.bets-section {
    /* background: #262b37; */
    padding: 30px 0;
}

.row {
    display: -webkit-flex;
    display: flex;
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap;
    width: calc(100% + 30px);
    margin-left: -15px;
    margin-right: -15px
}

.row .col-1 {
    width: 8.33333%
}

.row .col-1,
.row .col-2 {
    -webkit-flex-grow: 0;
    flex-grow: 0
}

.row .col-2 {
    width: 16.66667%
}

.row .col-3 {
    width: 25%
}

.row .col-3,
.row .col-4 {
    -webkit-flex-grow: 0;
    flex-grow: 0
}

.row .col-4 {
    width: 33.33333%
}

.row .col-5 {
    width: 41.66667%
}

.row .col-5,
.row .col-6 {
    -webkit-flex-grow: 0;
    flex-grow: 0
}

.row .col-6 {
    width: 50%
}

.row .col-7 {
    width: 58.33333%
}

.row .col-7,
.row .col-8 {
    -webkit-flex-grow: 0;
    flex-grow: 0
}

.row .col-8 {
    width: 66.66667%
}

.row .col-9 {
    width: 75%
}

.row .col-9,
.row .col-10 {
    -webkit-flex-grow: 0;
    flex-grow: 0
}

.row .col-10 {
    width: 83.33333%
}

.row .col-11 {
    width: 91.66667%
}

.row .col-11,
.row .col-12 {
    -webkit-flex-grow: 0;
    flex-grow: 0
}

.row .col-12 {
    width: 100%
}

.row .col {
    padding: 0 15px
}

.main-content-top .error-fallback {
    margin: auto
}

.error-fallback {
    background: #3a4152;
    padding: 20px;
    text-align: center;
    font-size: 13px;
    max-width: 450px;
    min-width: 320px;
    border-radius: 10px
}

.error-fallback h2 {
    font-size: 20px;
    margin-bottom: 15px
}

.error-fallback svg {
    width: 55px;
    height: 55px;
    display: block;
    margin: auto auto 20px
}

.left-sidebar {
    z-index: 120;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: row;
    flex-direction: row;
    -webkit-align-items: center;
    align-items: center;
    padding-left: 40px;
    padding-right: 40px;
    padding-bottom: 20px;
    padding-top: 118px;
    max-width: 1250px;
    margin: 0 auto;
}

.left-sidebar,
.left-sidebar .logo {
    -webkit-transition: all .3s;
    transition: all .3s
}

.left-sidebar .logo {
    max-width: 100px;
    margin-right: 30px;
}

.left-sidebar .logo .logotype {
    max-width: 70px;
    max-height: 25px;
}

.left-sidebar .side-nav {
    width: 100%;
    /* max-height: calc(100vh - 130px); */
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}

.left-sidebar.sticky .logo {
    -webkit-transform: translateY(-18px);
    transform: translateY(-18px)
}

.side-nav {
    list-style: none
}

.side-nav li {
    /* margin-right: 45px; */
}

.side-nav li:last-child {
    margin-bottom: 0
}

.side-nav li a {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    height: 34px;
    color: #959fb1;
    text-decoration: none;
    font-size: 24px;
    position: relative;
    border-bottom: 2px solid transparent;
    font-weight: bold;
}

.side-nav li .icon {
    width: 19px;
    height: 19px;
}

.side-nav li.current a,
.side-nav li a:hover {
    color: #ff4ba1;
    border-bottom: 2px solid #ff4ba1;
}

.side-nav li .side-nav-tooltip {
    /* position: absolute; */
    /* left: 45px; */
    /* margin-top: -1px; */
    font-size: 14px;
    font-weight: 600;
    padding: 0 5px;
    border-radius: 4px;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
}

.side-nav li:hover .side-nav-tooltip {
    display: -webkit-flex;
    display: flex
}

.button-like {
    width: 100%;
    text-align: center;
    line-height: 12px;
    font-size: 10px;
    font-weight: 600;
    cursor: pointer;
    background-color: initial;
    border: 0;
    color: #828f9a
}

.button-like[disabled] {
    pointer-events: none;
    opacity: .8
}

.button-like:focus,
.button-like:hover {
    outline: none
}

.button-like:hover svg {
    fill: #62ca5b;
    opacity: 1
}

.button-like.dislike {
    margin-top: 8px
}

.button-like.dislike:hover svg {
    fill: #e86376
}

.button-like svg {
    fill: #fff;
    width: 16px;
    height: 16px;
    opacity: .15
}

.message-game {
    width: 100%;
    border: 1px solid rgba(58, 63, 68, .35);
    margin-top: 8px;
    border-radius: 6px;
    position: relative;
    cursor: pointer
}

.message-game .message-info {
    padding: 6px 10px;
    color: #fff
}

.message-game .message-info>span {
    color: #7f8596
}

.message-game .message-info .payout {
    color: #fff
}

.message-game .message-info .payout.win {
    color: #62ca5b
}

.message-game .message-info .payout.lose {
    color: #e86376
}

.message-game .message-info:hover {
    opacity: .8
}

.message-game .likes-block {
    width: 28px;
    position: absolute;
    left: -34px;
    top: 3px
}

.sanitize-user {
    white-space: nowrap;
    display: inline;
    line-height: 22px;
}

.sanitize-avatar {
    width: 24px;
    height: 24px;
    display: inline-block;
    cursor: pointer;
    float: left;
    margin-right: 10px;
}

.sanitize-avatar img {
    border-radius: 3px;
    display: block;
    border: 1px solid rgba(255, 255, 255, 0.05);
    padding: 2px;
    width: 24px;
    height: 24px;
}

.sanitize-name,
.sanitize-user {
    position: relative;
    white-space: nowrap;
    -webkit-transition: all .3s;
    transition: all .3s;
}

.sanitize-name.hasVip .sanitize-text,
.sanitize-user.hasVip .sanitize-text {
    padding-left: 19px
}

.sanitize-name.hasP:first-letter,
.sanitize-user.hasP:first-letter {
    color: #6bceff
}

.sanitize-name .icon-crown,
.sanitize-user .icon-crown {
    color: #ffc645;
    position: absolute;
    top: 50%;
    margin-left: -2px;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%)
}

.tooltip {
    position: absolute;
    z-index: 1070;
    display: block;
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
    font-style: normal;
    font-weight: 400;
    line-height: 1.5;
    text-align: left;
    text-align: start;
    text-decoration: none;
    text-shadow: none;
    text-transform: none;
    letter-spacing: normal;
    word-break: normal;
    word-spacing: normal;
    white-space: normal;
    line-break: auto;
    font-size: .875rem;
    word-wrap: break-word;
    opacity: 0
}

.tooltip.show {
    opacity: .9
}

.tooltip .arrow {
    position: absolute;
    display: block;
    width: .8rem;
    height: .4rem
}

.tooltip .arrow:before {
    position: absolute;
    content: "";
    border-color: transparent;
    border-style: solid
}

.bs-tooltip-auto[x-placement^=top],
.bs-tooltip-top {
    padding: .4rem 0
}

.bs-tooltip-auto[x-placement^=top] .arrow,
.bs-tooltip-top .arrow {
    bottom: 0
}

.bs-tooltip-auto[x-placement^=top] .arrow:before,
.bs-tooltip-top .arrow:before {
    top: 0;
    border-width: .4rem .4rem 0;
    border-top-color: #000
}

.bs-tooltip-auto[x-placement^=right],
.bs-tooltip-right {
    padding: 0 .4rem
}

.bs-tooltip-auto[x-placement^=right] .arrow,
.bs-tooltip-right .arrow {
    left: 0;
    width: .4rem;
    height: .8rem
}

.bs-tooltip-auto[x-placement^=right] .arrow:before,
.bs-tooltip-right .arrow:before {
    right: 0;
    border-width: .4rem .4rem .4rem 0;
    border-right-color: #000
}

.bs-tooltip-auto[x-placement^=bottom],
.bs-tooltip-bottom {
    padding: .4rem 0
}

.bs-tooltip-auto[x-placement^=bottom] .arrow,
.bs-tooltip-bottom .arrow {
    top: 0
}

.bs-tooltip-auto[x-placement^=bottom] .arrow:before,
.bs-tooltip-bottom .arrow:before {
    bottom: 0;
    border-width: 0 .4rem .4rem;
    border-bottom-color: #000
}

.bs-tooltip-auto[x-placement^=left],
.bs-tooltip-left {
    padding: 0 .4rem
}

.bs-tooltip-auto[x-placement^=left] .arrow,
.bs-tooltip-left .arrow {
    right: 0;
    width: .4rem;
    height: .8rem
}

.bs-tooltip-auto[x-placement^=left] .arrow:before,
.bs-tooltip-left .arrow:before {
    left: 0;
    border-width: .4rem 0 .4rem .4rem;
    border-left-color: #000
}

.tooltip-inner {
    max-width: 200px;
    padding: .25rem .5rem;
    color: #fff;
    text-align: center;
    background-color: #000;
    border-radius: .25rem
}

.tooltip.premium-tip {
    margin-left: 9px!important
}

.tooltip.ghost-mode {
    pointer-events: none
}

.ghost-mode .tooltip-inner {
    max-width: 150px;
    background-color: #303642;
    box-shadow: 0 0 20px 0 rgba(0, 0, 0, .4)
}

.bs-tooltip-auto[x-placement^=top].ghost-mode .arrow:before,
.bs-tooltip-top.ghost-mode .arrow:before,
.ghost-mode.bs-tooltip-auto[x-placement^=top] .arrow:before {
    border-top-color: #303642
}

.admin-badge {
    margin-right: 6px;
    color: #f44336;
    cursor: help;
    font-size: 11px
}

.admin-badge.isModerator {
    color: #4986f5
}

.admin-badge .icon-a {
    width: 10px;
    height: 10px
}

.message-block:hover .admin-actions {
    opacity: 1
}

.admin-actions {
    opacity: 0
}

.admin-actions>.btn {
    position: absolute;
    right: 10px;
    color: #434b53;
    z-index: 9999
}

.popover-body {
    padding: 0
}

.popover-body .muted-form {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    margin-top: 5px;
    color: #fff
}

.popover-body .muted-form input {
    width: 50%;
    border: 0;
    height: 20px;
    padding: 0 5px;
    font-size: 10px;
    border-radius: 3px 0 0 3px;
    background: #191d24;
    color: #fff
}

.popover-body .muted-form input:focus {
    outline: none
}

.popover-body .muted-form button {
    height: 20px;
    width: 50%;
    padding: 0 5px;
    font-size: 9px!important;
    border: 0;
    -webkit-justify-content: center;
    justify-content: center;
    border-radius: 0 3px 3px 0
}

.popover-body ul {
    list-style: none;
    padding: 6px 0
}

.popover-body ul li {
    padding: 0 8px 6px;
    border-bottom: 1px solid #2b303e;
    margin-bottom: 6px;
    max-width: 160px
}

.popover-body ul li:last-child {
    border-bottom: 0;
    margin-bottom: 0;
    padding-bottom: 0
}

.popover-body ul li>.btn {
    width: 100%!important;
    font-weight: 700;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 1px
}

.chat {
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    width: 100%;
    -webkit-flex: 1 1;
    flex: 1 1;
    padding: 0 20px
}

.chat .chat-empty-block {
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    -webkit-justify-content: center;
    justify-content: center;
    text-align: center;
    position: relative;
    min-height: 65px;
    padding: 10px;
    font-size: 14px
}

.chat .chat-ban-block {
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    -webkit-justify-content: center;
    justify-content: center;
    text-align: center;
    position: relative;
    min-height: 65px;
    padding: 10px;
    font-size: 14px;
    height: 80px;
}

.chat .chat-empty-block,
.chat .chat-params {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.chat .chat-ban-block {
    display: -webkit-flex;
    display: flex;
    justify-content: center;
    -webkit-align-items: center;
    align-items: center;
    flex-direction: column;
    margin-top: 10px;
}

.chat .chat-ban-block button {
    margin: 5px 0;
    border-radius: 15px;
    background: transparent;
    color: #959fb1;
    border: 1px solid rgba(255, 255, 255, 0.05);
    box-shadow: none;
    text-transform: uppercase;
    font-size: 11px;
    letter-spacing: .28px;
    padding: 5px 13px;
    white-space: nowrap;
    height: 30px;
    -webkit-justify-content: center;
    justify-content: center;
}

.chat .chat-params {
    -webkit-justify-content: space-between;
    justify-content: space-between;
    padding-bottom: 20px;
    -webkit-flex: none;
    flex: none
}

.chat .chat-params>.item {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.chat .chat-online {
    font-size: 16px;
    color: #5b6271
}

.chat .chat-online span {
    color: #74df42;
}

.chat .chat-conversation {
    flex: auto;
    -webkit-transition: all .3s;
    transition: all .3s;
    min-height: 100px;
    display: flex;
    height: 120px;
    flex-direction: column-reverse;
    position: relative
}

.chat .chat-conversation .chat-conversation-inner {
    position: relative;
    margin-right: -15px;
    padding-right: 15px
}

.chat .chat-editable {
    outline: 0;
    min-height: 80px;
    width: 100%;
    max-width: 190px;
    resize: none;
    max-height: 80px;
    overflow-y: auto;
    overflow-x: hidden;
    border-radius: 6px;
    line-height: 17px;
    padding: 15px;
    margin-bottom: 0;
    word-wrap: break-word;
    box-sizing: border-box;
    border: none;
    -webkit-font-smoothing: subpixel-antialiased
}

.chat .chat-editable img {
    vertical-align: -3px;
    margin: 0 1px;
    display: inline-block;
    overflow: hidden
}

.chat .chat-editable:focus {
    border-color: #c9d0d6;
    outline: none
}

.chat .chat-message-input {
    margin-top: 10px;
    -webkit-flex: none;
    flex: none;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    border-radius: 3px;
    display: -webkit-flex;
    display: flex;
    position: relative;
    height: 80px
}

.chat .chat-message-input.p {
    box-shadow: 0 0 0 2px red
}

.chat .chat-textarea {
    -webkit-flex: auto;
    flex: auto;
    max-width: calc(100% - 20px)
}

.chat .chat-params>.item button {
    margin-left: 5px;
}

.toggle a.active,
.chat .chat-params>.item button:hover,
.chat .chat-params>.item a:hover {
    background: #4986f5;
    border-color: #4986f5;
    color: #fff
}

.chat-transaction__icon {
    font-size: 37px;
    margin: 0 14px 0 0;
}

.align-center {
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
}

.flex-row {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -ms-flex-direction: row;
    flex-direction: row;
}

.flex-column_align-start {
    -webkit-box-align: start;
    -ms-flex-align: start;
    align-items: flex-start;
}

.flex-column {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
}

.share button {
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    border: none;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    font-size: 14px;
    line-height: 16px;
    border-radius: 6px;
    letter-spacing: .3px;
    font-weight: 400;
    color: #fff;
    padding: 8px;
    outline: none!important;
    cursor: pointer;
}

.share button i {
    color: #4b5562;
    font-size: 7px
}

.share button:after {
    display: none
}

.share img {
    width: 20px
}

.toggle a {
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    border: none;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    font-size: 14px;
    line-height: 16px;
    border-radius: 6px;
    letter-spacing: .3px;
    font-weight: 400;
    color: #fff;
    padding: 8px;
    outline: none!important;
    cursor: pointer;
}

.toggle a i {
    color: #4b5562;
    font-size: 7px
}

.toggle a:after {
    display: none
}

.toggle img {
    width: 20px
}

.list button {
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    border: none;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    font-size: 14px;
    line-height: 16px;
    border-radius: 6px;
    letter-spacing: .3px;
    font-weight: 400;
    color: #fff;
    padding: 8px;
    outline: none!important;
    cursor: pointer;
}

.list button i {
    color: #4b5562;
    font-size: 7px
}

.list button:after {
    display: none
}

.list img {
    width: 20px
}

.clear button {
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    border: none;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    font-size: 14px;
    line-height: 16px;
    border-radius: 6px;
    letter-spacing: .3px;
    font-weight: 400;
    color: #fff;
    padding: 8px;
    outline: none!important;
    cursor: pointer;
}

.clear button i {
    color: #4b5562;
    font-size: 7px
}

.clear button:after {
    display: none
}

.clear img {
    width: 20px
}

.chat .chat-controls {
    -webkit-flex: none;
    flex: none;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-justify-content: space-between;
    justify-content: space-between;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    width: 44px;
    border-radius: 0 3px 3px 0
}

.chat .chat-controls,
.chat .chat-controls .item {
    -webkit-align-items: center;
    align-items: center;
    display: -webkit-flex;
    display: flex
}

.chat .chat-controls .item {
    font-size: 20px;
    cursor: pointer;
    -webkit-flex: auto;
    flex: auto;
    -webkit-justify-content: center;
    justify-content: center;
    background: none;
    border: none;
    outline: none!important;
    width: 100%
}

.chat .chat-controls .item[disabled] {
    opacity: .5;
    cursor: not-allowed
}

.chat .chat-controls .item .icon-smile {
    color: #8395b6;
}

.chat .chat-controls .item .icon-send {
    color: #4986f5
}

.smile-popover {
    max-width: 214px
}

.smile-popover .wrong-access {
    color: #fff;
    padding: 15px;
    font-size: 14px
}

.smiles-list {
    padding: 10px
}

.smiles-list>span {
    margin: 4px;
    cursor: pointer;
    position: relative
}

.smiles-list>span:before {
    content: "";
    position: absolute;
    height: 100%;
    width: 100%;
    background: #394453;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    margin: -5px;
    padding: 5px;
    border-radius: 6px;
    opacity: 0;
    z-index: -1
}

.smiles-list>span:hover:before {
    opacity: 1
}

.s {
    background-image: url(../img/smiles.png);
    background-size: 16px 1120px;
    display: inline-block;
    width: 16px;
    height: 16px;
    border: 0!important
}

.s-1f60a {
    background-position: 0 -16px
}

.s-1f60b {
    background-position: 0 -32px
}

.s-1f60c {
    background-position: 0 -48px
}

.s-1f60d {
    background-position: 0 -64px
}

.s-1f60e {
    background-position: 0 -80px
}

.s-1f60f {
    background-position: 0 -96px
}

.s-1f61a {
    background-position: 0 -112px
}

.s-1f61b {
    background-position: 0 -128px
}

.s-1f61c {
    background-position: 0 -144px
}

.s-1f61d {
    background-position: 0 -160px
}

.s-1f61f {
    background-position: 0 -176px
}

.s-1f61e {
    background-position: 0 -192px
}

.s-1f62a {
    background-position: 0 -208px
}

.s-1f62b {
    background-position: 0 -224px
}

.s-1f62c {
    background-position: 0 -240px
}

.s-1f62d {
    background-position: 0 -256px
}

.s-1f62e {
    background-position: 0 -272px
}

.s-1f62f {
    background-position: 0 -288px
}

.s-1f92a {
    background-position: 0 -304px
}

.s-1f92b {
    background-position: 0 -320px
}

.s-1f92c {
    background-position: 0 -336px
}

.s-1f92e {
    background-position: 0 -352px
}

.s-1f92d {
    background-position: 0 -368px
}

.s-1f600 {
    background-position: 0 -384px
}

.s-1f601 {
    background-position: 0 -400px
}

.s-1f92f {
    background-position: 0 -416px
}

.s-1f603 {
    background-position: 0 -432px
}

.s-1f602 {
    background-position: 0 -448px
}

.s-1f604 {
    background-position: 0 -464px
}

.s-1f605 {
    background-position: 0 -480px
}

.s-1f606 {
    background-position: 0 -496px
}

.s-1f607 {
    background-position: 0 -512px
}

.s-1f608 {
    background-position: 0 -528px
}

.s-1f609 {
    background-position: 0 -544px
}

.s-1f610 {
    background-position: 0 -560px
}

.s-1f611 {
    background-position: 0 -576px
}

.s-1f612 {
    background-position: 0 -592px
}

.s-1f613 {
    background-position: 0 -608px
}

.s-1f614 {
    background-position: 0 -624px
}

.s-1f615 {
    background-position: 0 -640px
}

.s-1f618 {
    background-position: 0 -656px
}

.s-1f620 {
    background-position: 0 -672px
}

.s-1f622 {
    background-position: 0 -688px
}

.s-1f621 {
    background-position: 0 -704px
}

.s-1f623 {
    background-position: 0 -720px
}

.s-1f624 {
    background-position: 0 -736px
}

.s-1f625 {
    background-position: 0 -752px
}

.s-1f626 {
    background-position: 0 -768px
}

.s-1f628 {
    background-position: 0 -784px
}

.s-1f629 {
    background-position: 0 -800px
}

.s-1f630 {
    background-position: 0 -816px
}

.s-1f631 {
    background-position: 0 -832px
}

.s-1f627 {
    background-position: 0 -848px
}

.s-1f632 {
    background-position: 0 -864px
}

.s-1f633 {
    background-position: 0 -880px
}

.s-1f636 {
    background-position: 0 -896px
}

.s-1f643 {
    background-position: 0 -912px
}

.s-1f642 {
    background-position: 0 -928px
}

.s-1f641 {
    background-position: 0 -944px
}

.s-1f644 {
    background-position: 0 -960px
}

.s-1f910 {
    background-position: 0 -976px
}

.s-1f911 {
    background-position: 0 -992px
}

.s-1f914 {
    background-position: 0 -1008px
}

.s-1f913 {
    background-position: 0 -1024px
}

.s-1f915 {
    background-position: 0 -1040px
}

.s-1f923 {
    background-position: 0 -1056px
}

.s-1f925 {
    background-position: 0 -1072px
}

.s-1f929 {
    background-position: 0 -1088px
}

.s-1f928 {
    background-position: 0 -1104px
}

.s-2764 {
    background-position: 0 -1120px
}

.message-block {
    position: relative;
    padding: 10px;
    background: rgba(0, 0, 0, .1);
    margin-bottom: 10px;
    border-radius: 6px;
    width: 100%;
    min-height: 44px
}

.message-block .message-avatar {
    width: 24px;
    height: 24px;
    display: inline-block;
    cursor: pointer;
    position: absolute;
    top: 10px;
    left: 10px
}

.message-block .message-avatar.isAdmin img {
    border-color: #f44336
}

.message-block .message-avatar.isModerator img {
    border-color: #4986f5
}

.message-block .message-avatar img {
    border-radius: 3px;
    display: block;
    border: 1px solid #2b323e;
    padding: 2px;
    width: 24px;
    height: 24px
}

.message-block .delete {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    margin-top: 10px;
}

.message-block .delete button {
    margin: auto;
    border-radius: 15px;
    background: transparent;
    color: #959fb1;
    border: none;
    box-shadow: none;
    text-transform: uppercase;
    font-size: 11px;
    padding: 1px;
    width: calc(50% - 5px);
    white-space: nowrap;
    -webkit-justify-content: center;
    justify-content: center;
}

.message-block .delete button svg {
    width: 11px;
    height: 11px;
    margin-right: 4px;
}

.message-block .message-content {
    font-size: 13px;
    line-height: 20px;
    width: calc(100% - 31px);
    margin-left: 31px;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: space-between;
    justify-content: space-between;
    position: relative;
    word-break: break-word;
    padding-top: 2px
}

.message-block .message-content>div {
    width: 100%
}

.message-block .message-content .user-link {
    border: 0;
    padding: 0;
    touch-action: manipulation;
    text-transform: none;
    -webkit-appearance: button;
    margin: 0;
    background: transparent;
    color: #828f9a;
    outline: none;
    cursor: pointer;
    font-weight: 700
}

.message-block .message-content .user-link:focus,
.message-block .message-content .user-link:hover {
    outline: none;
    color: #fff
}

.message-block .message-content>span {
    color: #828f9a
}

.message-block .message-text {
    display: inline;
    word-wrap: break-word
}

.message-block .message-text span {
    border: none;
    vertical-align: -4px;
    margin: 0 1px;
    display: inline-block;
    overflow: hidden;
}

.user-profile {
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    width: 100%;
    overflow: hidden;
    -webkit-flex: 1 1;
    flex: 1 1;
    padding: 0 20px
}

.user-profile .user-avatar {
    margin-bottom: 20px
}

.user-profile .user-avatar .close-btn {
    position: absolute;
    right: 15px;
    top: 25px
}

.user-profile .user-name {
    margin-bottom: 20px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.user-profile .user-name .nickname {
    font-size: 18px;
    color: #fff;
    overflow: hidden;
    text-overflow: ellipsis;
    width: 100%;
    white-space: nowrap;
    max-width: 200px
}

.user-profile .profile-nav {
    list-style: none;
    width: 100%
}

.user-profile .profile-nav li {
    margin-bottom: 20px
}

.user-profile .profile-nav li a {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    color: #626d7e;
    line-height: 20px;
    font-size: 14px
}

.user-profile .profile-nav li a .number-badge {
    position: static;
    top: 0;
    right: 0;
    margin-left: 5px
}

.user-profile .profile-nav li a svg {
    width: 18px;
    height: 18px;
    display: block
}

.user-profile .profile-nav li a .icon-affiliate {
    width: 14px;
    height: 14px
}

.user-profile .profile-nav li a .item-icon {
    width: 20px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    margin-right: 15px
}

.user-profile .profile-nav li.current a,
.user-profile .profile-nav li a:hover {
    color: #fff
}

.user-profile .profile-nav li:last-child {
    margin-bottom: 25px
}

.user-profile .btn-logout {
    color: #626d7e;
    width: 100%;
    padding: 0;
    background: transparent;
    font-weight: 400;
    font-size: 14px
}

.user-profile .btn-logout .item-icon {
    width: 20px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    margin-right: 15px;
    font-size: 16px
}

.user-profile .btn-logout:hover {
    background: transparent;
    color: #fff
}

.user-profile .user-block {
    width: 100%;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center
}

.user-profile .avatar {
    width: 104px;
    height: 104px;
    border-radius: 50%;
    padding: 5px;
    background: hsla(0, 0%, 84.7%, .06);
    display: -webkit-flex;
    display: flex
}

.user-profile .avatar img {
    max-width: 100%;
    border-radius: 50%;
    display: block;
    height: 100%;
    width: 100%
}

.tab {
    display: none;
}

.tab.current {
    display: flex;
}

.tab.active {
    display: block;
}

.tabs-nav {
    width: 100%
}

.tabs-nav,
.tabs-nav>.item {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.tabs-nav>.item {
    margin-right: 10px;
    cursor: pointer;
    -webkit-flex: auto;
    flex: auto;
    -webkit-justify-content: center;
    justify-content: center;
    color: #828f9a;
    font-size: 13px;
    line-height: 18px;
    padding: 10px 15px;
    -webkit-transition: all .3s;
    transition: all .3s;
    border-radius: 3px;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.tabs-nav>.item:last-child {
    margin-right: 0
}

.tabs-nav>.item svg {
    margin-right: 8px
}

.tabs-nav>.item.current,
.tabs-nav>.item:hover {
    color: #fff;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.tabs-nav.big-tabs {
    width: 100%;
    background: #1c212a;
    border-radius: 6px 6px 0 0;
    margin-bottom: 20px
}

.tabs-nav.big-tabs>.item {
    -webkit-flex: auto;
    flex: auto;
    padding: 20px;
    font-size: 12px;
    line-height: 14px;
    font-weight: 600;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    border-radius: 6px 6px 0 0;
    background: transparent;
    text-transform: uppercase;
    letter-spacing: .5px;
    color: #5b656f;
    margin: 0
}

.tabs-nav.big-tabs>.item:hover {
    color: #f1f1f2
}

.tabs-nav.big-tabs>.item.current {
    background: #272d39
}

.right-sidebar {
    z-index: 1002;
    background: #1a2a65;
    background: radial-gradient(circle at 100% 0%, #19265a, #1d1034);
}

.right-sidebar,
.right-sidebar .sidebar-container {
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    display: -webkit-flex;
    display: flex;
    width: 280px;
    height: 100%;
    will-change: transform;
}

.right-sidebar .sidebar-container {
    padding: 40px 0 15px;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-justify-content: space-between;
    justify-content: space-between;
    -webkit-transition: padding .3s;
    transition: padding .3s
}

.right-sidebar.sticky .sidebar-container {
    padding-top: 22px
}

.right-sidebar .tabs-nav {
    padding: 0 20px;
    margin-bottom: 40px;
    -webkit-flex: none;
    flex: none
}

.right-sidebar .tabs-nav>.item {
    width: 50%;
    position: relative
}

.right-sidebar .tabs-nav>.item svg {
    width: 14px;
    height: 14px
}

.right-sidebar .number-badge {
    position: absolute;
    -webkit-transition: all .3s ease 0s;
    transition: all .3s ease 0s;
    background-color: #4986f5;
    top: -5px;
    right: -5px;
    width: 20px;
    height: 20px;
    font-size: 11px;
    line-height: 20px;
    border-radius: 50%;
    color: #fff;
    text-align: center;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center;
    -webkit-align-items: center;
    align-items: center
}

.close-btn {
    color: #979797;
    width: 34px;
    height: 34px;
    display: none;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    cursor: pointer;
    border: none;
    outline: none;
    background: transparent
}

.close-btn svg {
    width: 13px;
    height: 13px
}

.bets-tabs-row {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: space-between;
    justify-content: space-between;
    margin-bottom: 40px;
    width: 100%;
    position: relative
}

.bets-tabs-row .btn {
    line-height: 18px;
    font-size: 13px;
    font-weight: 400;
    padding: 9px 17px;
    color: #505961;
    border: 1px solid #353d48;
    background-color: initial
}

.bets-tabs-row .btn[disabled] {
    opacity: 1
}

.bets-tabs-row .btn.isActive {
    color: #fff;
    background-color: #4986f5;
    border: 1px solid #4986f5
}

.bets-tabs-row .btn:not(.isActive):hover {
    color: #fff;
    background-color: initial
}

.bets-tabs-row .btn:first-child {
    margin-right: 10px
}

.bets-tabs-row .close-btn {
    position: absolute;
    right: -5px
}

.table-heading {
    display: table;
    width: 100%;
    border-collapse: initial;
    border-spacing: 0;
    table-layout: fixed;
    position: relative;
    z-index: 2
}

.table-heading .thead {
    display: table-header-group;
    vertical-align: middle
}

.table-heading .tr {
    display: table-row;
    vertical-align: inherit
}

.table-heading .th {
    display: table-cell;
    vertical-align: inherit;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    color: #959fb1;
    font-size: 11px;
    text-transform: uppercase;
    padding: 10px 20px
}

.table-heading .th:first-child {
    border-radius: 6px 0 0 0
}

.table-heading .th:last-child {
    border-radius: 0 6px 0 0;
    text-align: right
}

.table-heading.tournaments-history .th:nth-last-child(2) {
    text-align: center
}

.table-wrap {
    position: relative
}

.table,
.table-wrap {
    overflow: hidden;
    border-radius: 0 0 6px 6px
}

.table {
    color: #fff;
    width: 100%;
    border-spacing: 0;
    border-collapse: initial;
    table-layout: fixed;
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.table tr {
    padding: 0 12px
}

.table tr td,
.table tr th {
    padding: 10px 20px
}

.table tr th {
    text-align: left;
    font-size: 11px;
    line-height: 14px;
    font-weight: 700;
    color: #959fb1;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    text-transform: uppercase
}

.table tr th:first-child {
    border-radius: 6px 0 0 0
}

.table tr th:last-child {
    border-radius: 0 6px 0 0
}

.table tr td {
    font-size: 14px;
    line-height: 16px;
    font-weight: 400;
    border-bottom: 1px solid rgba(255, 255, 255, 0.05);
    letter-spacing: .2px;
}

.table td .btnUnBan {
    float: right;
    border-radius: 15px;
    background: transparent;
    color: #959fb1;
    border: none;
    box-shadow: none;
    text-transform: uppercase;
    font-size: 11px;
    padding: 1px 7px;
    width: auto;
    white-space: nowrap;
    -webkit-justify-content: center;
    justify-content: center;
}

.table td .btnUnBan svg {
    width: 11px;
    height: 11px;
    margin-right: 4px;
}

.table tr:last-child td:first-child {
    border-radius: 0 0 0 6px;
}

.table tr:last-child td:last-child {
    border-radius: 0 0 6px 0
}

.table.hoverable tr:hover {
    background: #303643
}

.table .btn-link {
    color: #7d8a98;
    font-weight: 600;
    font-size: 13px;
    padding: 0
}

.empty-table-list {
    padding: 30px 0;
    background: #2c323f;
    border-radius: 6px;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center;
    font-size: 18px;
    margin: 30px 0 0
}

.bet-number {
    display: inline-block;
    padding-left: 22px
}

.bet-number.rtl {
    padding: 0 20px 0 0
}

.bet-number.rtl svg {
    left: auto;
    right: -21px
}

.bet-number .bet-wrap {
    display: inline-block;
    position: relative
}

.bet-number .bet-wrap .pre {
    position: absolute;
    left: -4px;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%)
}

.bet-number .bet-wrap>span {
    display: -webkit-flex;
    display: flex
}

.bet-number .bet-wrap .tied,
.bet-number .bet-wrap .won {
    color: #62ca5b
}

.bet-number .bet-wrap .lost {
    color: #828f9a
}

.bet-number svg {
    position: absolute;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    left: -21px;
    font-size: 15px;
    color: #959fb1
}

.bet-number.golden svg {
    fill: #ffc645
}

.game-stats {
    width: 100%;
    position: relative;
    border-radius: 6px
}

.game-stats,
.game-stats .table-stats-wrap {
    overflow: hidden
}

.game-stats .table-wrap {
    will-change: transform
}

.game-stats .th:nth-last-child(2) {
    text-align: center
}

.game-stats table {
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.game-stats table tbody tr {
    height: 53px
}

.game-stats table tbody tr td {
    font-size: 14px;
    color: #fff;
    font-weight: 400;
    border-bottom: 1px solid rgba(255, 255, 255, 0.05);
    letter-spacing: .2px;
    padding: 8px 20px;
}

.game-stats table tbody tr td:nth-last-child(2) {
    text-align: center
}

.game-stats table tbody tr td:last-child {
    text-align: right
}

.game-stats table tbody tr:last-child td {
    border-bottom: 0
}

.game-stats .game-data {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.game-stats .game-data .btn-icon {
    padding: 0;
    background: transparent
}

.game-stats .game-data .game-icon {
    color: #959fb1;
    margin-right: 12px;
    width: 24px;
    text-align: center
}

.game-stats .game-data .game-icon svg {
    width: 22px;
    height: 22px
}

.game-stats .game-data .game-info .btn-name {
    background: transparent;
    padding: 0;
    font-size: 14px;
    line-height: 16px;
    color: #fff;
    text-transform: capitalize;
    display: block
}

.game-stats .game-data .game-info button {
    color: #545b70;
    font-size: 12px;
    font-weight: 400
}

.game-stats .username .btn-link.hasP>span:first-letter {
    color: #6bceff
}

.game-stats .username.anonymous span {
    font-style: italic;
    border-bottom: 1px dotted;
    line-height: 1.2;
    cursor: help;
    font-size: 13px;
    color: #7d8a98
}

.promo-counters .counter-block {
    padding: 25px 0;
    width: 100%;
    position: relative;
    text-align: center;
    background: #262b37;
    border-radius: 10px;
    border: 2px solid #262b37;
    box-shadow: inset 0 0 0 3px #1f242e
}

.promo-counters .counter-num {
    color: #fff;
    font-size: 21px;
    line-height: 21px;
    font-weight: 600;
    font-family: Exo\ 2, Open Sans, sans-serif;
    margin-bottom: 5px
}

.promo-counters .counter-text {
    color: #828f9a;
    text-transform: uppercase;
    font-size: 12px;
    font-weight: 600
}

.footer-counters {
    padding-top: 40px
}

.footer-counters .counter-block {
    border: 1px solid rgba(255, 255, 255, 0.05);
    border-radius: 6px;
    padding: 15px 0;
    width: 100%;
    overflow: hidden;
    position: relative;
    text-align: center;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column-reverse;
    flex-direction: column-reverse;
}

.footer-counters .counter-block .counter-text {
    color: #828f9a;
    margin-bottom: 2px;
    text-transform: uppercase;
    font-size: 12px;
    font-weight: 600
}

.footer-counters .counter-block .counter-num {
    font-size: 16px;
    font-weight: 600;
    color: #ff4ba1;
}

.footer {
    /* background: #20242d; */
    padding-top: 40px;
    padding-bottom: 40px;
    font-size: 11px;
    line-height: 14px;
    color: #525c71;
}

.footer .col {
    position: relative
}

.footer .row {
    -webkit-align-items: flex-end;
    align-items: flex-end
}

.footer .license {
    text-align: right
}

.footer-nav {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    list-style: none
}

.footer-nav li {
    margin-right: 25px
}

.footer-nav li:last-child {
    margin-right: 0
}

.footer-nav li a {
    font-size: 11px;
    line-height: 14px;
    color: #525c71;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.footer-nav li a svg {
    margin-right: 5px
}

.footer-nav li a:hover {
    color: #fff
}

.copyright {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: flex-end;
    align-items: flex-end;
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-flex-direction: column;
    flex-direction: column
}

.copyright .footer-logo {
    padding-bottom: 20px
}

.copyright .footer-logo img {
    display: block;
    max-width: 80px;
    -webkit-filter: grayscale(100%);
    filter: grayscale(100%);
    opacity: .3
}

.copyright .text {
    display: block;
    font-size: 11px;
    line-height: 16px;
    color: #525c71;
    text-align: right
}

.copyright .icon {
    margin-left: 25px
}

.copyright .icon img {
    display: block
}

.socials-list {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    list-style: none;
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap;
    padding-bottom: 30px
}

.socials-list li {
    margin-right: 8px;
    margin-bottom: 8px
}

.socials-list li:last-child {
    margin-right: 0
}

.socials-list li a {
    border-radius: 3px;
    background: #272d39;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    color: #878f9e;
    font-size: 11px;
    line-height: 14px;
    padding: 6px 12px
}

.socials-list li a:hover {
    background: #444d5f;
    color: #fff
}

.socials-list li a i {
    margin-right: 8px;
    font-size: 12px;
    display: block
}

.socials-list li a span {
    display: block;
    margin-bottom: 2px
}

.mobile-nav-component {
    position: fixed;
    display: none;
    left: 0;
    bottom: -1px;
    width: 100%;
    background: #20242d;
    z-index: 100;
}

.mobile-nav-component .pull-out {
    position: absolute;
    bottom: 100%;
    left: 0;
    z-index: -1;
    background: #1a2a65;
    width: 100%;
    -webkit-transform: translateY(100%);
    transform: translateY(100%);
    -webkit-transition: all .3s;
    transition: all .3s;
}

.mobile-nav-component .pull-out .close-btn {
    position: absolute;
    top: 5px;
    right: 5px;
    z-index: 3
}

.mobile-nav-component .pull-out.opened {
    -webkit-transform: translateY(0);
    transform: translateY(0)
}

.mobile-nav-component .pull-out-nav {
    display: -webkit-flex;
    display: flex;
    list-style: none;
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-align-items: center;
    align-items: center;
    width: calc(100% + 10px);
    margin-left: -5px;
    margin-right: -5px
}

.mobile-nav-component .pull-out.other .pull-out-nav>li {
    width: 50%;
    padding: 0 15px;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    border-right: 1px solid rgba(255, 255, 255, 0.1);
}

.mobile-nav-component .pull-out.game .pull-out-nav>li {
    width: 100%;
    padding: 0 15px;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    border-right: 1px solid rgba(255, 255, 255, 0.1);
}

.mobile-nav-component .pull-out-nav>li>a,
.mobile-nav-component .pull-out-nav>li>button {
    font-size: 13px;
    letter-spacing: -.1px;
    color: #828f9a;
    text-decoration: none;
    line-height: 14px;
    padding: 20px 15px 20px 30px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    border: none;
    outline: none;
    background: transparent;
    width: 100%;
    position: relative
}

.mobile-nav-component .pull-out-nav>li>a svg,
.mobile-nav-component .pull-out-nav>li>button svg {
    position: absolute;
    left: 10px;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    width: 14px;
    height: 14px
}

.mobile-nav-component .pull-out-nav>li>a svg.icon-faq,
.mobile-nav-component .pull-out-nav>li>button svg.icon-faq {
    font-size: 15px
}

.mobile-nav-component .pull-out-nav>li>a svg.icon-achievements,
.mobile-nav-component .pull-out-nav>li>button svg.icon-achievements {
    font-size: 16px
}

.mobile-nav-component .pull-out-nav>li.current>a,
.mobile-nav-component .pull-out-nav>li.current>button,
.mobile-nav-component .pull-out-nav>li>a:hover,
.mobile-nav-component .pull-out-nav>li>button:hover {
    color: #fff
}

.mobile-nav-component .mobile-nav-menu-wrapper {
    width: 100%;
    background: #1a2a65;
}

.mobile-nav-component .mobile-nav-menu {
    list-style: none;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: space-between;
    justify-content: space-between;
    -webkit-align-items: center;
    align-items: center;
    padding: 15px;
    width: 100%;
    max-width: 420px;
    margin: 0 auto
}

.mobile-nav-component .mobile-nav-menu li {
    margin-right: 5px
}

.mobile-nav-component .mobile-nav-menu li:last-child {
    margin-right: 0
}

.mobile-nav-component .mobile-nav-menu li a,
.mobile-nav-component .mobile-nav-menu li button {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-flex-direction: column;
    flex-direction: column;
    color: #828f9a;
    font-size: 12px;
    line-height: 12px;
    border: none;
    outline: none;
    background: transparent;
    cursor: pointer
}

.mobile-nav-component .mobile-nav-menu li a svg,
.mobile-nav-component .mobile-nav-menu li button svg {
    display: -webkit-flex;
    display: flex;
    margin-bottom: 8px;
    width: 14px;
    height: 14px;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center
}

.mobile-nav-component .mobile-nav-menu li a:hover,
.mobile-nav-component .mobile-nav-menu li button:hover {
    color: #fff
}

.mobile-nav-component .icon-more {
    width: 16px;
    height: 16px
}

.loader {
    display: block;
    pointer-events: none;
    position: relative;
    width: 100%;
    height: 100%
}

.loader img {
    width: 40px;
    height: 40px
}

.loader-centred img {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: auto
}

.loader-md {
    height: 200px
}

.loader-full {
    height: 100vh
}

.loader-half {
    height: 50vh
}

.loader-75vh {
    height: 75vh
}

.loader-affiliate {
    min-height: 450px
}

.loader-xs img {
    width: 16px;
    height: 16px;
    -webkit-animation: rotating 2s linear infinite;
    animation: rotating 2s linear infinite
}

.loader-modal {
    min-height: 350px
}

.loader-modal img {
    width: 60px;
    height: 60px;
    position: absolute;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0;
    margin: auto
}

.loader-game {
    min-height: 560px;
    height: auto
}

.loader-game img {
    width: 60px;
    height: 60px;
    position: absolute;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0;
    margin: auto
}

.social-auth-section {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(0, 0, 0, .58);
    z-index: 9999
}

.social-auth-section .block {
    width: 100%;
    white-space: nowrap;
    position: absolute;
    max-width: 340px;
    top: 50%;
    left: 50%;
    -webkit-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    height: 33vh
}

.social-auth-section .loader {
    height: 100px
}

.social-auth-section .loader img {
    height: 80px;
    width: 80px
}

.social-auth-section .text {
    font-size: 28px
}

.error-boundary {
    background: #1d2129;
    padding: 20px;
    text-align: center;
    font-size: 23px
}

.error-boundary svg {
    width: 85px;
    height: 85px;
    display: block;
    margin: auto
}

.input-valid {
    display: inherit;
    width: inherit
}

.input-valid .valid {
    text-align: center;
    position: absolute;
    font-size: 12px;
    font-weight: 600;
    color: #e86376;
    visibility: hidden;
    opacity: 0;
    bottom: 100%;
    left: 0;
    background: #1c2028;
    border-radius: 6px;
    padding: 1em;
    -webkit-transition: .3s ease-out;
    transition: .3s ease-out
}

.input-valid .valid.inline {
    bottom: auto;
    top: 100%;
    background: rgba(220, 53, 69, .9);
    border-radius: 2px;
    font-size: 10px;
    margin: 2px 0 0;
    color: #fff;
    padding: 4px 6px;
    z-index: 3
}

.input-valid .valid.inline.top {
    top: auto;
    bottom: calc(100% + 2px);
    left: 0;
    right: auto
}

.input-valid .valid.inline.top-right {
    top: auto;
    bottom: 100%;
    left: auto;
    right: 0
}

.input-valid .valid.inline:after {
    display: none
}

.input-valid .valid.visible {
    opacity: 1;
    visibility: visible
}

.input-valid .valid:after {
    content: "";
    position: absolute;
    left: .5em;
    top: 100%;
    width: 0;
    height: 0;
    border-color: transparent;
    border-style: solid;
    border-width: 6px 4px 0;
    border-top-color: #1c2028!important
}

.input-group {
    position: relative;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-align-items: stretch;
    align-items: stretch;
    width: 100%
}

.input-group .input-field {
    position: relative;
    -webkit-flex: 1 1 auto;
    flex: 1 1 auto;
    width: 1%;
    margin-bottom: 0
}

.input-group .input-field:not([readonly]):active+.input-group-append.text,
.input-group .input-field:not([readonly]):focus+.input-group-append.text {
    border: 1px solid #4986f5;
    border-left: 0
}

.input-group .input-field:not(:first-child) {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.input-group .input-field:not(:last-child) {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-right: 0
}

.input-group-prepend {
    display: -webkit-flex;
    display: flex;
    border-radius: 0 6px 6px 0;
    position: relative
}

.input-group-prepend.text {
    background-color: #2f3542
}

.input-group-prepend .btn:first-child {
    border-radius: 6px 0 0 6px
}

.input-group-append {
    display: -webkit-flex;
    display: flex;
    border-radius: 0 6px 6px 0;
    position: relative
}

.input-group-append.text {
    background-color: #2f3542;
    color: #4986f5;
    -webkit-align-items: center;
    align-items: center;
    padding: 0 .75rem;
    text-transform: uppercase;
    font-size: 12px;
    border: 1px solid transparent
}

.input-group-append .btn {
    margin-left: -5px
}

.input-suffix {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    max-width: 100%;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    pointer-events: none;
    white-space: nowrap;
    color: #fafafa;
    overflow: hidden;
    padding: 0 13px;
    line-height: normal
}

.input-suffix>span {
    color: transparent;
    letter-spacing: normal
}

.input-with-icon {
    padding-left: 35px
}

.input-icon {
    position: absolute;
    left: 13px;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    margin-right: 6px;
    width: 16px;
    height: 16px;
}

.input-icon .icon-coin {
    margin-top: 2px;
}

.deposit-section .select-payment .dropdown {
    width: 100%
}

.deposit-section .select-payment .dropdown .btn {
    height: 46px;
    font-size: 14px;
    margin: 0;
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    color: #7f8596;
    -webkit-justify-content: flex-start;
    justify-content: flex-start
}

.deposit-section .select-payment .dropdown .btn:active,
.deposit-section .select-payment .dropdown .btn:focus,
.deposit-section .select-payment .dropdown .btn:hover {
    background: rgba(255, 255, 255, 0.10);
}

.deposit-section .select-payment .dropdown .btn .image.yandex {
    margin-top: -5px
}

.deposit-section .select-payment .dropdown .btn .image.yandex img {
    width: 14px
}

.select-payment {
    width: 100%;
    position: relative;
    margin: 0
}

.select-payment.hasError .dropdown .btn {
    border-color: #e86376!important
}

.select-payment .error-text {
    position: absolute;
    left: 0;
    top: 100%;
    background: rgba(220, 53, 69, .9);
    border-radius: 2px;
    font-size: 10px;
    margin: 2px 0 0;
    color: #fff;
    padding: 4px 6px;
    font-weight: 600
}

.modal-dialog.deposit-modal {
    width: 400px;
    margin-left: auto;
    margin-right: auto
}

.modal-dialog.deposit-modal .modal-content {
    background: linear-gradient(to right top, #1d1034, #19275b);
}

.deposit-modal-component {
    padding: 15px 25px 25px;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-align-items: center;
    align-items: center
}

.deposit-modal-component .wrap {
    width: 100%
}

.deposit-modal-component .input-field {
    height: 46px
}

.deposit-modal-component .form-label {
    color: #a5adc1;
    font-size: 14px
}

.deposit-modal-component .input-with-icon {
    padding-left: 30px
}

.deposit-modal-component .tabs {
    display: -webkit-flex;
    display: flex;
    margin-bottom: 20px
}

.deposit-modal-component .btn-tab {
    background-color: initial;
    border-radius: 0;
    width: 50%;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center;
    padding-bottom: 15px;
    color: #959fb1;
    cursor: pointer;
    font-size: 15px;
    border: 0;
    border-bottom: 2px solid transparent
}

.deposit-modal-component .btn-tab:hover {
    color: #fff
}

.deposit-modal-component .btn-tab.isActive {
    border-bottom: 2px solid #4986f5;
    color: #fff
}

.deposit-modal-component .deposit-input-box {
    margin-bottom: 10px;
    color: #959fb1
}

.deposit-modal-component .deposit-input {
    height: 46px;
    border: 1px solid #464e5f;
    margin-top: 8px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    padding: 0 15px;
    border-radius: 6px;
    color: #fff;
    font-size: 15px
}

.deposit-modal-component .deposit-input svg {
    margin-right: 5px
}

.deposit-modal-component .deposit-section .btn {
    width: 100%;
    height: 56px;
    font-size: 16px;
    font-weight: 400;
    margin-top: 8px;
    -webkit-justify-content: center;
    justify-content: center
}

.deposit-modal-component .deposit-section .btn-toggle {
    font-size: 14px;
    height: 46px;
    margin: 0;
    -webkit-justify-content: flex-start;
    justify-content: flex-start
}

.deposit-modal-component .checkbox-block {
    margin: 20px 0 0;
    position: relative;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center
}

.deposit-modal-component .checkbox-block label {
    cursor: pointer;
    color: #7f8596;
    font-size: 13px;
    display: block;
    position: relative;
    line-height: 1.3;
    padding-left: 25px;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.deposit-modal-component .checkbox-block label input:checked~.checkmark {
    background-color: #4986f5
}

.deposit-modal-component .checkbox-block label input:checked~.checkmark:after {
    display: block
}

.deposit-modal-component .checkbox-block label:hover {
    color: #8d92a1
}

.deposit-modal-component .checkbox-block input {
    position: absolute;
    opacity: 0;
    cursor: pointer;
    height: 0;
    width: 0
}

.deposit-modal-component .checkbox-block .checkmark {
    position: absolute;
    top: 0;
    left: 0;
    height: 16px;
    width: 16px;
    border: 2px solid #4986f5;
    background: transparent;
    border-radius: .25rem
}

.deposit-modal-component .checkbox-block .checkmark:after {
    content: "";
    position: absolute;
    display: none;
    left: 3px;
    top: 0;
    width: 4px;
    height: 8px;
    border: solid #fff;
    border-width: 0 2px 2px 0;
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg)
}

.deposit-modal-component .checkbox-block.hasErrors label {
    color: #e86376
}

.deposit-modal-component .checkbox-block.hasErrors label .checkmark {
    border-color: #e86376!important
}

.deposit-modal-component .problem-block {
    border-radius: 6px;
    padding: 15px;
    margin: 18px 0 0;
    border: 1px solid #62ca5b;
    text-align: center
}

.deposit-modal-component .problem-block button {
    outline: none;
    cursor: pointer;
    background: transparent;
    color: #62ca5b;
    border: 0;
    border-bottom: 1px solid transparent
}

.deposit-modal-component .problem-block button:hover {
    border-bottom: 1px solid #62ca5b
}

.caption-line {
    font-weight: 400;
    font-size: 13px;
    margin-bottom: 15px;
    color: #959fb1;
    position: relative;
    width: 100%;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center;
    overflow: hidden
}

.caption-line span {
    display: inline-block;
    vertical-align: initial;
    position: relative;
    padding: 0 10px
}

.caption-line span:after,
.caption-line span:before {
    content: "";
    display: block;
    width: calc(100% + 10px);
    position: absolute;
    top: 50%;
    border-top: 1px solid rgba(91, 98, 113, .5)
}

.caption-line span:before {
    right: 100%
}

.caption-line span:after {
    left: 100%
}

.modal-dialog.faucet-demo-modal {
    width: 380px;
    margin: auto
}

.faucet-container {
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    text-align: center;
    padding: 20px
}

.faucet-container .grouped-fields {
    margin-bottom: 0
}

.faucet-container .faucet-caption {
    font-weight: 400;
    font-size: 16px;
    margin-bottom: 12px
}

.faucet-container .caption-line span {
    padding: 0 20px
}

.faucet-container .caption-line span:after,
.faucet-container .caption-line span:before {
    width: calc(300% + 10px)
}

.faucet-container .caption-line svg {
    width: 17px;
    height: 17px;
    color: #959fb1
}

.faucet-container .faucet-text {
    font-size: 14px;
    line-height: 19px
}

.faucet-container .faucet-text .error-image {
    display: block;
    margin: 0 auto 15px;
    font-size: 40px
}

.faucet-container .faucet-modal-form {
    border-radius: 6px;
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin-bottom: 20px
}

.faucet-container .faucet-modal-form:last-child {
    margin-bottom: 0
}

.faucet-container .faucet-modal-form .faucet-amount {
    font-size: 20px;
    line-height: 23px;
    margin-bottom: 15px;
    font-family: Exo\ 2, Open Sans, sans-serif
}

.faucet-container .faucet-modal-form .faucet-reload {
    font-size: 15px
}

.faucet-container .faucet-modal-form .faucet-reload span:first-child {
    color: rgba(201, 205, 219, .54)
}

.faucet-container .faucet-modal-form .faucet-cd {
    font-size: 16px;
    color: #565e6d
}

.faucet-container .faucet-modal-form .faucet-sm-text {
    font-size: 12px;
    font-family: Open Sans, sans-serif;
    line-height: 16px;
    margin-top: 7px;
    font-weight: 600;
    color: #9ca4b3
}

.faucet-container .faucet-modal-form .btn {
    width: 100%;
    -webkit-justify-content: center;
    justify-content: center;
    height: 48px
}

.faucet-container .captcha-block {
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center;
    margin-bottom: 20px
}

.faucet-container .recharge-block {
    margin-bottom: 4px;
    text-align: center
}

.faucet-container .recharge-block>span {
    font-size: 12px;
    color: rgba(201, 205, 219, .54);
    margin-bottom: 5px
}

.faucet-container .recharge-block .time-left {
    font-family: Exo\ 2, Open Sans, sans-serif;
    font-weight: 600;
    font-size: 32px;
    line-height: 33px;
    color: #c9cddb;
    margin-top: 5px
}

.error-data-fetch {
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center;
    min-height: 200px;
    -webkit-align-items: center;
    align-items: center;
    font-size: 18px
}

.modal-dialog.user-modal {
    width: 510px
}

.user-modal__container {
    display: -webkit-flex;
    display: flex;
    width: 100%;
    -webkit-flex-direction: column;
    flex-direction: column;
    padding: 20px;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center
}

.user-modal__container .properties .rating {
    margin-left: 15px;
    color: #828f9a;
    font-size: 12px;
    font-style: italic;
    margin-top: 2px
}

.user-modal__container .properties .rating span {
    color: #fff
}

.user-modal__head {
    width: 100%;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-justify-content: center;
    justify-content: center;
    -webkit-align-items: center;
    align-items: center;
    margin-bottom: 20px
}

.user-modal .sanitize-name.hasVip .sanitize-text,
.user-modal .sanitize-user.hasVip .sanitize-text {
    padding-left: 30px
}

.user-modal .date {
    color: #828f9a;
    font-size: 12px;
    font-style: italic;
    margin-top: 2px
}

.user-modal .avatar {
    display: -webkit-flex;
    display: flex;
    padding: 0;
    margin-bottom: 20px
}

.user-modal .avatar,
.user-modal .avatar img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    position: relative
}

.user-modal .avatar img {
    max-width: 100%;
    display: block
}

.user-modal .avatar:after {
    content: "";
    position: absolute;
    display: block;
    width: 90px;
    height: 90px;
    left: 50%;
    top: 50%;
    -webkit-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    border: 1px solid hsla(0, 0%, 59.2%, .087);
    border-radius: 50%
}

.user-modal .user-block {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-flex-direction: column;
    flex-direction: column
}

.user-modal .user-name {
    position: relative;
    z-index: 2;
    font-size: 20px;
    color: #fff
}

.user-modal .user-name:hover {
    /* color: #4986f5 */
}

.user-modal .tabs {
    margin-bottom: 25px
}

.user-modal .tabs .btn {
    background-color: #1c2028;
    text-transform: uppercase;
    -webkit-transition: 0s;
    transition: 0s
}

.user-modal .tabs .btn.isActive {
    background-color: #121419
}

.user-modal .tabs .btn>img {
    margin-right: 5px;
    width: 16px;
    height: 16px
}

.user-modal .tabs .btn:first-child {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-right: 1px solid #272d39
}

.user-modal .tabs .btn:nth-child(2) {
    border-radius: 0
}

.user-modal .tabs .btn:last-child {
    border-radius: 0 6px 6px 0
}

.user-modal .tabs .btn:not([disabled]):not(.isActive):hover {
    background-color: #16191f
}

.user-modal .no-stats {
    min-height: 118px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    font-size: 20px
}

.user-modal .card-stats {
    display: -webkit-flex;
    display: flex;
    width: 100%;
    -webkit-justify-content: center;
    justify-content: center;
    margin-bottom: 15px
}

.user-modal .card-stats:last-child {
    margin-bottom: 0
}

.user-modal .card-stats .stats-item {
    width: 50%;
    margin-right: 15px;
    text-align: center;
    border: 1px solid rgba(255, 255, 255, 0.05);
    border-radius: 6px;
    padding: 10px;
}

.user-modal .card-stats .stats-item:nth-child(4),
.user-modal .card-stats .stats-item:nth-child(5),
.user-modal .card-stats .stats-item:nth-child(6) {
    margin: 0
}

.user-modal .card-stats .stats-item:last-child {
    margin-right: 0
}

.user-modal .card-stats .stats-item>.item-label {
    font-size: 14px;
    color: #959fb1;
    margin-bottom: 3px;
}

.user-modal .card-stats .stats-item>.item-value {
    font-family: Exo\ 2, Open Sans, sans-serif;
    font-size: 16px;
    font-weight: 600;
    position: relative;
    color: #ff4ba1;
    -webkit-align-items: center;
    align-items: center;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center;
}

.user-modal .card-stats .stats-item>.item-value .icon-wrapper {
    display: inline-block;
    height: 14px;
    width: 14px;
    margin-right: 5px
}

.user-modal .card-stats .stats-item>.item-value svg {
    width: 100%;
    height: 100%
}

.sr--only {
    position: absolute;
    left: -10000px;
    top: auto;
    width: 1px;
    height: 1px;
    overflow: hidden
}

.game {
    display: -webkit-flex;
    display: flex;
    width: 100%;
    -webkit-align-items: stretch;
    align-items: stretch;
    position: relative
}

.game-component {
    -webkit-align-items: stretch;
    align-items: stretch;
    width: calc(100% - 320px);
    position: relative
}

.game-block,
.game-component {
    -webkit-flex: auto;
    flex: auto;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column
}

.game-block {
    width: 100%;
    border-radius: 6px 6px 0 0;
    padding: 25px 20px;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.game-block,
.game .game-area-subsection {
    -webkit-justify-content: stretch;
    justify-content: stretch
}

.game .game-area-subsection {
    display: -webkit-flex;
    display: flex;
    -webkit-flex: auto;
    flex: auto
}

.game-sign {
    position: absolute;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0;
    z-index: 20;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    -webkit-flex-direction: column;
    flex-direction: column;
    overflow: hidden;
    padding: 10px;
    border-radius: 6px;
    background: rgba(255, 255, 255, 0.05);
}

.game-sign .game-sign-wrap {
    width: 100%;
    max-width: 330px;
    overflow: hidden;
    position: relative;
    z-index: 21;
    box-shadow: 0 0 10px rgba(28, 32, 40, .5);
    -webkit-flex: 0 1 auto;
    flex: 0 1 auto;
    border-radius: 6px
}

.game-sign .game-sign-block {
    background: linear-gradient(to right top, #1d1034, #19275b);
    position: relative;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-flex-direction: column;
    flex-direction: column;
    padding: 20px;
    text-align: center;
    font-size: 18px;
    border-radius: 6px
}

.game-sign .game-sign-block .btn {
    margin-top: 20px;
    padding: 12px 30px;
    font-size: 15px
}

.game-sign .game-sign-block .btn svg {
    margin-right: 8px
}

.game-sign form {
    width: 100%
}

.game-sign .form-row {
    margin-bottom: 10px
}

.game-sign .input-field {
    height: 36px;
    border-radius: 3px;
    background: #272d39
}

.game-area {
    position: relative;
    overflow: hidden;
    -webkit-backface-visibility: hidden;
    backface-visibility: hidden;
    width: 100%;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
}

.game-area__wrap {
    display: -webkit-flex;
    display: flex;
    -webkit-flex: auto;
    flex: auto;
    -webkit-justify-content: stretch;
    justify-content: stretch
}

.game-area .game-area-content {
    width: 100%;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-flex: auto;
    flex: auto
}

.game-area .bottom-corners,
.game-area .top-corners {
    position: absolute;
    width: 100%
}

.game-area .bottom-corners:after,
.game-area .bottom-corners:before,
.game-area .top-corners:after,
.game-area .top-corners:before {
    content: "";
    display: block;
    width: 46px;
    height: 46px;
    border-radius: 50%;
    background: rgba(105, 116, 132, .08);
    position: absolute
}

.game-area .top-corners {
    left: 0;
    top: 0
}

.game-area .top-corners:before {
    left: -27px;
    top: -27px
}

.game-area .top-corners:after {
    right: -27px;
    top: -27px
}

.game-area .bottom-corners {
    left: 0;
    bottom: 0
}

.game-area .bottom-corners:before {
    left: -27px;
    bottom: -27px
}

.game-area .bottom-corners:after {
    right: -27px;
    bottom: -27px
}

.hash {
    color: #959fb1;
    text-align: center;
}

.hash .title {
    font-weight: 800;
}

.hash .text {
    font-size: 12px
}

.collapse:not(.show) {
    display: none
}

.collapsing {
    position: relative;
    height: 0;
    overflow: hidden;
    -webkit-transition: height .35s ease;
    transition: height .35s ease
}

.collapse-component {
    border-radius: 3px;
    border: 1px solid hsla(0, 0%, 59.2%, .087);
    width: 100%;
    margin: 15px 0
}

.collapse-component .collapse-top {
    padding: 10px 15px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    cursor: pointer;
    position: relative
}

.collapse-component .collapse-top .collapse-title {
    font-size: 15px;
    line-height: 20px;
    color: #a9acb7;
    -webkit-flex: auto;
    flex: auto;
    margin-right: 20px;
    font-weight: 400;
    -webkit-transition: all .3s;
    transition: all .3s;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.collapse-component .collapse-top .collapse-title .title-icon {
    width: 24px;
    height: 24px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    margin-right: 8px
}

.collapse-component .collapse-top .collapse-title .title-icon svg {
    width: 24px;
    height: 24px;
    display: block
}

.collapse-component .collapse-top .btn {
    position: absolute;
    left: 0;
    right: 0;
    width: 100%;
    height: 100%;
    padding: 0 0 0 35px;
    font-size: 15px;
    font-weight: 400
}

.collapse-component .collapse-top .collapse-after {
    fill: #fff;
    position: absolute;
    right: 10px;
    top: 50%;
    width: 20px;
    height: 20px;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    -webkit-transition: all .3s;
    transition: all .3s;
    pointer-events: none
}

.collapse-component .collapse-top .collapse-after svg {
    width: 100%;
    height: 100%
}

.collapse-component .collapse-top:hover .collapse-title {
    color: #fff
}

.collapse-component .collapse-content {
    padding: 0 15px
}

.collapse-component .collapse-content p {
    font-size: 13px;
    line-height: 17px;
    margin-bottom: 17px;
    color: #c9cddb
}

.collapse-component .collapse-content p:last-child {
    margin-bottom: 0
}

.collapse-component.opened .collapse-top .collapse-title {
    color: #fff
}

.collapse-component.opened .collapse-top .collapse-after {
    -webkit-transform: translateY(-50%) rotate(-180deg);
    transform: translateY(-50%) rotate(-180deg)
}

.modal-dialog.fair-modal {
    width: 500px
}

.fair-modal__container {
    padding: 20px;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-align-items: center;
    align-items: center
}

.fair-modal__container h1 {
    margin-bottom: 15px
}

.fair-modal__container .btn-rotate {
    display: block;
    margin: 0 auto 15px
}

.fair-modal__container .fair-table {
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    word-break: break-all;
    width: 100%
}

.fair-modal__container .fair-table h2 {
    text-align: center;
    margin-bottom: 15px
}

.fair-modal__container .fair-table .table {
    border-radius: 6px
}

.fair-modal__container .fair-table .table th {
    text-align: center
}

.fair-modal__container .fair-table .table td {
    text-align: center;
    width: 33.33%
}

.fair-modal__container .fair-alert {
    background: #303642;
    border-radius: 6px;
    padding: 10px;
    margin: 15px 0;
    text-align: center;
    border: 1px solid red;
    font-size: 16px
}

.fair-modal__container .form-row {
    width: 100%
}

.game-sidebar {
    width: 310px;
    min-height: 560px;
    margin-right: 10px;
    -webkit-flex: none;
    flex: none;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.game-sidebar,
.game-sidebar .sidebar-block {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: stretch;
    align-items: stretch
}

.game-sidebar .sidebar-block {
    width: 100%;
    padding: 25px 20px;
    border-radius: 6px;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    -webkit-flex: auto;
    flex: auto
}

.bet-component {
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-align-items: stretch;
    align-items: stretch;
    width: 100%
}

.bet-component .bet-tabs {
    margin-top: -25px;
    width: calc(100% + 40px);
    margin-left: -20px;
    margin-right: -20px
}

.bet-component .btn.btn-play,
.bet-component .btn.btn-withdraw {
    height: 60px;
    font-size: 15px;
    display: block;
    -webkit-align-items: baseline;
    align-items: baseline;
    width: 100%
}

.bet-component .bet-form {
    -webkit-flex: auto;
    flex: auto
}

.bet-component .bet-footer {
    margin-top: 30px;
    -webkit-flex: none;
    flex: none;
    -webkit-justify-content: space-between;
    justify-content: space-between
}

.bet-component .bet-footer,
.bet-component .bet-footer .btn {
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center
}

.bet-component .bet-footer .btn {
    margin: 0 auto;
    border-radius: 15px;
    background: transparent;
    color: #959fb1;
    border: 1px solid rgba(255, 255, 255, 0.05);
    box-shadow: none;
    text-transform: uppercase;
    font-size: 11px;
    letter-spacing: .28px;
    padding: 5px 13px;
    width: calc(50% - 4px);
    white-space: nowrap;
    height: 30px;
    -webkit-justify-content: center;
    justify-content: center;
}

.bet-component .bet-footer .btn svg {
    width: 14px;
    height: 14px;
    margin-right: 5px
}

.bet-component .two-cols {
    position: relative;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: space-between;
    justify-content: space-between
}

.bet-component .two-cols>.form-row {
    width: calc(50% - 5px)
}

.pick-wrapper {
    margin-bottom: 20px;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.pick-wrapper .pick {
    padding: 6px;
    position: relative;
    background: #272d39;
    margin-bottom: 15px;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    font-size: 13px
}

.pick-wrapper .pick,
.pick-wrapper .pick.rounded {
    border-radius: 6px;
    border: 1px solid hsla(0, 0%, 59.2%, .12);
    width: 100%
}

.pick-wrapper .pick.rounded .btn {
    width: 50%;
    text-align: center;
    -webkit-justify-content: center;
    justify-content: center
}

.pick-wrapper .pick.rounded .btn:first-child {
    margin-right: 6px
}

.pick-wrapper .pick-or {
    padding: 0 15px;
    font-size: 8px;
    text-transform: uppercase;
    color: #5f6977;
    letter-spacing: .22px;
    display: block
}

.pick-wrapper .btn-auto-pick {
    -webkit-flex: auto;
    flex: auto;
    background-color: #ffd000;
    color: #665300;
    -webkit-justify-content: center;
    justify-content: center;
    font-size: inherit
}

.pick-wrapper .btn-auto-pick:hover {
    background-color: #cca600
}

.pick-wrapper .btn-auto-pick svg {
    margin-right: 5px;
    margin-top: -4px;
    margin-left: -6px;
    width: 18px;
    height: 18px;
    display: block
}

.pick-wrapper .pick-numbers {
    -webkit-flex: auto;
    flex: auto;
    color: #7d8a98;
    font-size: 11px;
    font-weight: 600;
    text-align: center
}

.input-validation {
    text-align: center;
    position: absolute;
    font-size: 12px;
    font-weight: 600;
    color: #e86376;
    visibility: hidden;
    opacity: 0;
    bottom: 100%;
    left: 0;
    background: #1c2028;
    border-radius: 3px;
    padding: 7px 10px;
    -webkit-transition: .3s ease-out;
    transition: .3s ease-out;
    z-index: 3
}

.input-validation.top:after {
    content: "";
    position: absolute;
    left: .5em;
    top: 100%;
    width: 0;
    height: 0;
    border-color: transparent;
    border-style: solid;
    border-width: 6px 4px 0;
    border-top-color: #1c2028!important
}

.input-validation.bottom {
    top: 100%;
    bottom: auto;
    margin-top: 3px
}

.input-validation.bottom:after {
    content: "";
    position: absolute;
    left: .5em;
    bottom: 100%;
    width: 0;
    height: 0;
    border-color: transparent transparent #1c2028;
    border-style: solid;
    border-width: 0 4px 6px
}

.input-validation.visible {
    opacity: 1;
    visibility: visible
}

.carousel {
    position: relative;
    width: 100%
}

.carousel.pointer-event {
    touch-action: pan-y
}

.carousel .btn-next,
.carousel .btn-prev {
    position: absolute;
    background-color: initial;
    padding: 10px;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    color: #5e687e
}

.carousel .btn-next:focus,
.carousel .btn-next:hover,
.carousel .btn-prev:focus,
.carousel .btn-prev:hover {
    background-color: initial
}

.carousel .btn-next:focus svg,
.carousel .btn-next:hover svg,
.carousel .btn-prev:focus svg,
.carousel .btn-prev:hover svg {
    fill: #939caf
}

.carousel .btn-next {
    right: -30px
}

.carousel .btn-next svg {
    -webkit-transform: scale(-1);
    transform: scale(-1)
}

.carousel .btn-prev {
    left: -30px
}

.carousel-inner {
    position: relative;
    width: 100%;
    overflow: hidden;
    min-height: 62px;
}

.carousel-inner:after {
    display: block;
    clear: both;
    content: ""
}

.carousel-item {
    width: 100%;
    min-height: 62px;
    position: relative;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: start;
    justify-content: start;
    float: left;
    -webkit-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-transition: -webkit-transform .6s ease-in-out;
    transition: -webkit-transform .6s ease-in-out;
    transition: transform .6s ease-in-out;
    transition: transform .6s ease-in-out, -webkit-transform .6s ease-in-out;
}

.carousel-item-next,
.carousel-item-prev {
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: space-between;
    justify-content: space-between
}

.active.carousel-item-right,
.carousel-item-next:not(.carousel-item-left) {
    -webkit-transform: translateX(100%);
    transform: translateX(100%)
}

.active.carousel-item-left,
.carousel-item-prev:not(.carousel-item-right) {
    -webkit-transform: translateX(-100%);
    transform: translateX(-100%)
}

.carousel-fade .carousel-item {
    opacity: 0;
    -webkit-transition-property: opacity;
    transition-property: opacity;
    -webkit-transform: none;
    transform: none
}

.carousel-fade .carousel-item-next.carousel-item-left,
.carousel-fade .carousel-item-prev.carousel-item-right,
.carousel-fade .carousel-item.active {
    z-index: 1;
    opacity: 1
}

.carousel-fade .active.carousel-item-left,
.carousel-fade .active.carousel-item-right {
    z-index: 0;
    opacity: 0;
    -webkit-transition: opacity 0s .6s;
    transition: opacity 0s .6s
}

.carousel-control-next,
.carousel-control-prev {
    position: absolute;
    top: 0;
    bottom: 0;
    z-index: 1;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    width: 15%;
    color: #fff;
    text-align: center;
    opacity: .5;
    -webkit-transition: opacity .15s ease;
    transition: opacity .15s ease
}

.carousel-control-next:focus,
.carousel-control-next:hover,
.carousel-control-prev:focus,
.carousel-control-prev:hover {
    color: #fff;
    text-decoration: none;
    outline: 0;
    opacity: .9
}

.carousel-control-prev {
    left: 0
}

.carousel-control-next {
    right: 0
}

.carousel-control-next-icon,
.carousel-control-prev-icon {
    display: inline-block;
    width: 20px;
    height: 20px;
    background: no-repeat 50%/100% 100%
}

.game-tooltip {
    position: absolute;
    left: 50%;
    top: 50%;
    -webkit-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    background: #fff;
    border-radius: 10px;
    z-index: 10;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    flex-direction: column;
    font-size: 1em;
    -webkit-flex-grow: 0;
    flex-grow: 0;
    width: auto;
    max-width: 90%;
    visibility: hidden;
    opacity: 0;
    border: 2px solid;
    padding: 1.7em 3.4em;
    box-shadow: 0px 0px 20px 10px rgba(25, 29, 36, 0.20);
}

.game-tooltip .wrap {
    text-align: center
}

.game-tooltip .badge {
    position: absolute;
    top: -1px;
    width: 100%;
    left: 0;
    text-align: center
}

.game-tooltip.won .badge .text {
    color: #2b313f;
    background: #62ca5b
}

.game-tooltip .badge .text {
    background: #ffc645;
    display: inline-block;
    color: #2b313f;
    padding: 4px 12px;
    text-transform: uppercase;
    font-size: .8em;
    font-weight: 600;
    border-radius: 0 0 6px 6px
}

.game-tooltip.won {
    color: #828f9a;
    border-color: #62ca5b;
}

.game-tooltip.won .profit {
    color: #62ca5b
}

.game-tooltip.lost {
    color: #e86376;
    border-color: #e86376
}

.game-tooltip.lost .profit {
    color: #e86376
}

.game-tooltip.tied {
    color: #ffd000;
    border-color: #ffd000
}

.game-tooltip.tied .profit {
    color: #ffd000
}

.game-tooltip.demo {
    color: #ffc645;
    border-color: #ffc645;
    padding-top: 1.85em;
    padding-bottom: 1em
}

.game-tooltip.demo .profit {
    color: #ffc645
}

.game-tooltip.demo .status {
    margin: 4px 0
}

.game-tooltip.transition {
    -webkit-transition: all .5s .3s;
    transition: all .5s .3s
}

.game-tooltip.isTransparent {
    background: linear-gradient(to right top, #1d1034, #19275b);
}

.game-tooltip.isActive {
    visibility: visible;
    opacity: 1
}

.game-tooltip .user {
    margin-top: 5px;
    font-family: Exo\ 2, Open Sans, sans-serif;
    font-weight: 700;
    white-space: nowrap;
    width: 100%;
    text-align: center;
}

.game-tooltip .user button {
    color: #7d8a98;
}

.game-tooltip .user .sanitize-user {
    margin: auto;
}

.game-tooltip .payout {
    font-size: 24px;
    margin-top: 5px;
    font-family: Exo\ 2, Open Sans, sans-serif;
    font-weight: 700;
    white-space: nowrap;
    width: 100%;
    text-align: center;
}

.game-tooltip .payout .icon {
    width: 15px;
    vertical-align: bottom;
}

.game-tooltip .status {
    font-size: 14px;
    white-space: nowrap;
    display: -webkit-flex;
    display: flex;
    -webkit-align-items: center;
    align-items: center;
    -webkit-justify-content: center;
    justify-content: center;
    font-weight: 600;
    color: #828f9a;
    margin: 4px 0 0;
}

.game-tooltip .btn-change {
    color: #62ca5b;
    white-space: nowrap;
    border-bottom: 1px dashed;
    padding: 0;
    background: transparent;
    border-radius: 0;
    display: inline;
    line-height: normal;
    font-size: inherit
}

.game-tooltip .btn-change:hover {
    color: #43b73b!important;
    border-bottom: 1px dashed transparent
}

.button-group__wrap {
    font-size: 1.3em;
    position: relative;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column-reverse;
    flex-direction: column-reverse;
    -webkit-align-items: flex-start;
    align-items: flex-start;
    width: 100%;
    margin-bottom: 20px
}

.button-group__content {
    display: -webkit-flex;
    display: flex
}

.button-group__content,
.button-group__content .btn {
    width: 100%;
    -webkit-justify-content: center;
    justify-content: center;
    border-radius: 6px;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.button-group__content .btn {
    padding: .5rem;
    text-transform: capitalize;
    font-weight: 400
}

.button-group__content .btn:hover {
    background-color: rgba(255, 255, 255, 0.10);
}

.button-group__content .btn.isActive {
    color: #fff;
    background-color: rgba(255, 255, 255, 0.15);
}

.button-group-label {
    margin-bottom: 10px;
    font-size: 13px;
    line-height: 14px;
    color: #7f8596
}

.progress-wrap {
    flex: none;
    display: flex;
    position: absolute;
    width: 100%;
    align-items: flex-start;
    justify-content: space-between;
    left: 0;
    top: 0;
}

.progress-item {
    border: 1px solid rgba(255, 255, 255, 0.05);
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    color: #959fb1;
    padding: 10px;
    -webkit-transition: all .3s;
    transition: all .3s;
    pointer-events: none;
}

.progress-item.left {
    border-radius: 0 0 15px 0;
    border-left: 0;
    border-top: 0;
}

.progress-item.right {
    border-radius: 0 0 0 15px;
    border-right: 0;
    border-top: 0;
}

.modal-dialog.confirm-age-modal {
    width: 500px;
    margin-left: auto;
    margin-right: auto
}

.confirm-age-modal-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative
}

.confirm-age-modal-container:after {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background: url(../img/bg.jpg);
    background-size: cover;
    background-position: 50% 50%;
    opacity: .1;
    border-radius: 6px
}

.confirm-age-modal-container .head,
.confirm-age-modal-container .wrap {
    position: relative;
    z-index: 2;
    width: 100%
}

.confirm-age-modal-container .head {
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
    padding: 20px;
    border-radius: 6px 6px 0 0
}

.confirm-age-modal-container .head img {
    width: 120px;
    margin: auto;
    display: block
}

.confirm-age-modal-container .body {
    padding: 25px;
    border-radius: 0 0 6px 6px;
    width: 100%
}

.confirm-age-modal-container .body .wrap {
    position: relative;
    z-index: 2
}

.confirm-age-modal-container .body .buttons {
    width: 100%;
    display: flex;
    justify-content: center
}

.confirm-age-modal-container .body .buttons .btn {
    width: 100%;
    justify-content: center;
    max-width: 240px;
    padding: 13px 0;
    font-size: 15px
}

.confirm-age-modal-container .body .disclaimer {
    color: #fff;
    margin: 20px 0 0;
    text-align: center;
    font-size: 13px
}

.confirm-age-modal-container .body .disclaimer .button-link {
    background: transparent;
    border: 0;
    border-bottom: 1px solid #4986f5;
    cursor: pointer;
    outline: none;
    color: #4986f5
}

.confirm-age-modal-container .body .disclaimer .button-link:active,
.confirm-age-modal-container .body .disclaimer .button-link:focus,
.confirm-age-modal-container .body .disclaimer .button-link:hover {
    outline: none;
    border-bottom: 1px solid transparent
}

.confirm-age-modal-container .body .leave-link {
    color: #fff;
    display: flex;
    justify-content: center;
    margin: 10px 0 15px
}

.confirm-age-modal-container .body .leave-link a {
    color: #fff;
    border-bottom: 1px solid #fff
}

.confirm-age-modal-container .body .leave-link a:hover {
    border-bottom: 1px solid transparent
}

.confirm-age-modal-container .body .info {
    text-transform: uppercase;
    color: #a1afbb;
    font-size: 11px
}

.modal-dialog.tos-modal {
    width: 550px;
    margin-left: auto;
    margin-right: auto
}

.tos-modal-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    padding: 25px;
    font-size: 12px
}

.tos-modal-container h2 {
    font-weight: 500;
    margin: 10px 0
}

.tos-modal-container h2:first-child {
    margin-top: 0
}

.tos-modal-container p {
    margin: 10px 0
}

.tos-modal-container .tos-modal-block {
    max-height: 450px
}

.modal-dialog.captcha-need-modal {
    width: 355px;
    margin-left: auto;
    margin-right: auto
}

@media screen and (max-width: 499px) {
    .modal-dialog.captcha-need-modal {
        width: calc(100% - 20px)
    }
}

.modal-dialog.captcha-need-modal .modal-content {
    background: linear-gradient(to right top, #1d1034, #19275b);
}

.captcha-need-modal-container {
    padding: 0
}

.captcha-need-modal-container .caption {
    font-family: Exo\ 2, Open Sans, sans-serif;
    font-size: 16px;
    position: relative;
    display: flex;
    width: 100%;
    padding: 20px;
    color: #fff;
    border-radius: 6px 6px 0 0;
    justify-content: center;
}

.captcha-need-modal-container .caption:after {
    content: "";
    position: absolute;
    bottom: -1px;
    left: 0;
    width: 100%;
    height: 1px;
    background: -webkit-gradient(linear, left top, right top, color-stop(0, hsla(0, 0%, 100%, 0)), color-stop(50%, #4986f5), to(hsla(0, 0%, 100%, 0)));
    background: -webkit-linear-gradient(left, hsla(0, 0%, 100%, 0), #4986f5 50%, hsla(0, 0%, 100%, 0));
    background: linear-gradient(90deg, hsla(0, 0%, 100%, 0), #4986f5 50%, hsla(0, 0%, 100%, 0))
}

.captcha-need-modal-container .form {
    padding: 15px 25px
}

.captcha-need-modal-container .form .label {
    margin-bottom: 10px;
    text-align: center
}

.captcha-need-modal-container .form .captcha {
    display: flex;
    justify-content: center
}

.captcha-need-modal-container .form .btn {
    margin-top: 15px;
    width: 100%;
    display: flex;
    text-align: center;
    padding: 13px 15px;
    font-size: 15px;
    justify-content: center
}

.message-block.quiz {
    position: relative;
    margin-bottom: 10px;
    border-radius: 6px;
    width: 100%;
    min-height: 44px;
    padding: 12px;
    border-top: 1px solid #4986f5;
    border-bottom: 1px solid #4986f5;
    background: rgba(72, 133, 243, .1)
}

.message-block.quiz .message-content {
    width: 100%;
    margin-left: 0;
}

.message-block.quiz .quizLabel {
    color: #4986f5;
    display: inline-block;
    position: relative;
    padding-left: 17px;
    font-weight: 700;
    margin: 0
}

.message-block.quiz .quizLabel svg {
    font-size: 13px;
    position: absolute;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    top: 50%;
    left: 0
}

.message-block.quiz .quizLabel>span {
    margin-left: 5px;
    font-weight: 400;
    word-break: break-word
}

.message-block.quiz .bet-number {
    margin-left: 3px;
    padding-left: 16px
}

.message-block.quiz .bet-number span {
    margin-left: 5px;
    font-weight: 400;
    word-break: break-word
}

.quizMessage .bet-number svg {
    left: -16px;
    font-size: 13px;
    fill: #62ca5b
}

.quizMessage {
    font-size: 13px;
    color: #62ca5b;
    display: flex;
    align-items: center;
    flex-direction: column;
}

.input-valid {
    display: inherit;
    width: inherit
}

.input-valid .valid {
    text-align: center;
    position: absolute;
    font-size: 12px;
    font-weight: 600;
    color: #e86376;
    visibility: hidden;
    opacity: 0;
    bottom: 100%;
    left: 0;
    background: #1c2028;
    border-radius: 6px;
    padding: 1em;
    -webkit-transition: .3s ease-out;
    transition: .3s ease-out
}

.input-valid .valid.inline {
    bottom: auto;
    top: 100%;
    background: rgba(220, 53, 69, .9);
    border-radius: 2px;
    font-size: 10px;
    margin: 2px 0 0;
    color: #fff;
    padding: 4px 6px;
    z-index: 3
}

.input-valid .valid.inline.top {
    top: auto;
    bottom: calc(100% + 2px);
    left: 0;
    right: auto;
    width: 100%;
    position: inherit;
}

.input-valid .valid.inline.top-right {
    top: auto;
    bottom: 100%;
    left: auto;
    right: 0
}

.input-valid .valid.inline:after {
    display: none
}

.input-valid .valid.visible {
    opacity: 1;
    visibility: visible
}

.input-valid .valid:after {
    content: "";
    position: absolute;
    left: .5em;
    top: 100%;
    width: 0;
    height: 0;
    border-color: transparent;
    border-style: solid;
    border-width: 6px 4px 0;
    border-top-color: #1c2028!important
}

.input-group {
    position: relative;
    display: flex;
    flex-wrap: wrap;
    align-items: stretch;
    width: 100%
}

.input-group .input-field {
    position: relative;
    flex: 1 1 auto;
    width: 1%;
    margin-bottom: 0
}

.input-group .input-field:not([readonly]):active+.input-group-append.text,
.input-group .input-field:not([readonly]):focus+.input-group-append.text {
    border: 1px solid #4986f5;
    border-left: 0
}

.input-group .input-field:not(:first-child) {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.input-group .input-field:not(:last-child) {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border-right: 0
}

.input-group-prepend {
    display: flex;
    border-radius: 0 6px 6px 0;
    position: relative
}

.input-group-prepend.text {
    background-color: #2f3542
}

.input-group-prepend .btn:first-child {
    border-radius: 6px 0 0 6px
}

.input-group-append {
    display: flex;
    border-radius: 0 6px 6px 0;
    position: relative
}

.input-group-append.text {
    background-color: #2f3542;
    color: #4986f5;
    align-items: center;
    padding: 0 .75rem;
    text-transform: uppercase;
    font-size: 12px;
    border: 1px solid transparent
}

.input-group-append .btn {
    margin-left: -5px
}

@media (max-width:1099px) {
    .input-group-append.text {
        font-size: 10px
    }
}

.input-suffix {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    max-width: 100%;
    display: flex;
    align-items: center;
    pointer-events: none;
    white-space: nowrap;
    color: #fafafa;
    overflow: hidden;
    padding: 0 13px;
    line-height: normal
}

.input-suffix>span {
    color: transparent;
    letter-spacing: normal
}

.input-with-icon {
    padding-left: 35px
}

.input-icon {
    position: absolute;
    left: 13px;
    top: 50%;
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    margin-right: 6px
}

.input-icon .icon-coin {
    /* margin-top: 5px */
}

.caption-line {
    font-weight: 400;
    font-size: 13px;
    margin-bottom: 15px;
    color: #959fb1;
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
    overflow: hidden
}

.caption-line span {
    display: inline-block;
    vertical-align: initial;
    position: relative;
    padding: 0 10px
}

.caption-line span:after,
.caption-line span:before {
    content: "";
    display: block;
    width: calc(100% + 10px);
    position: absolute;
    top: 50%;
    border-top: 1px solid rgba(91, 98, 113, .5)
}

.caption-line span:before {
    right: 100%
}

.caption-line span:after {
    left: 100%
}

.change-form {
    display: flex;
    margin-bottom: -20px;
    padding: 10px 0;
    width: 100%;
    justify-content: center
}

.change-form .or {
    margin: 7px 10px 0;
    background: #464f57;
    width: 1px;
    height: 9px
}

.change-form .btn {
    background: transparent;
    padding: 0;
    color: #828f9a;
    font-weight: 500
}

.change-form .btn:hover {
    background: transparent;
    color: #bac2c8
}

.social-auth {
    flex-wrap: wrap
}

.social-auth,
.social-auth .line {
    display: flex;
    width: 100%
}

.social-auth .btn {
    width: 100%;
    font-size: 14px;
    font-weight: 400;
    margin: 0 10px 10px 0;
    padding: 8px 20px;
    justify-content: center;
    border-radius: 3px;
}

.social-auth .btn:last-child {
    margin-right: 0
}

.social-auth .btn-vk {
    background: #507299
}

.social-auth .btn-vk:hover {
    background: #476688
}

.social-auth .btn-fb {
    background: #3b5998
}

.social-auth .btn-fb:hover {
    background: #344e86
}

.social-auth .btn-ok {
    background: #db8a37
}

.social-auth .btn-ok:hover {
    background: #d37d26
}

.social-auth .btn-gl {
    background: #db4437
}

.social-auth .btn-gl:hover {
    background: #c63024
}

.auth-form,
.auth-form form {
    width: 100%
}

.auth-form .form-row {
    margin-bottom: 10px
}

.auth-form .social-auth {
    margin-bottom: 5px
}

.auth-form .input-field {
    height: 36px;
    border-radius: 3px;
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0px 15px 15px -1px rgba(0, 0, 0, 0.1);
}

.auth-form .btn-auth {
    font-size: 14px;
    font-weight: 400;
    justify-content: center;
    width: 100%;
    margin-top: 3px;
    padding: 13px 20px;
    border-radius: 3px
}

.modal-dialog.auth-modal {
    margin-left: auto;
    margin-right: auto;
    width: 350px
}

.modal-dialog.auth-modal .modal-content {
    background: -webkit-gradient(linear, left top, left bottom, from(#1d1034), to(#19275b));
    background: -webkit-linear-gradient(to right top, #1d1034, #19275b);
    background: linear-gradient(to right top, #1d1034, #19275b)
}

@media screen and (max-width:499px) {
    .modal-dialog.auth-modal {
        max-width: 320px;
        margin: auto;
        width: calc(100% - 14px)
    }
}

.auth-modal__container {
    position: relative;
    z-index: 2;
    display: flex;
    align-items: center;
    flex-direction: column;
    padding: 20px
}

.auth-modal__container .caption {
    font-size: 16px;
    font-weight: 400;
    margin-bottom: 15px
}

.statusPending {
    color: #ffc645
}

.statusPaid {
    color: #62ca5b
}

.statusCancel {
    color: #e86376
}
