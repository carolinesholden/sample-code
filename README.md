# sample-code
Sample CSS from recent projects

/*
Theme Name:     Jupiter Child Theme
Theme URI:      http://themeforest.net/user/artbees
Description:    Child theme for the Jupiter WordPress theme 
Author:         Caroline S. Holden, Innovetive Petcare
Theme URI:      http://themeforest.net/user/artbees
Template:       jupiter
Version:        1.0
*/

/* -------------------- TYPOGRAPHY -------------------- */

.svc-body { font-family: Work Sans !important; }
.svc-body-size { font-size: 16px !important; }
.svc-header { font-family: Josefin Sans !important; }

.text-white { color: #ffffff !important; }
.text-off-white { color: #f7f2ec !important; }
.text-gray { color: #58595b !important; }
.text-greige-light { color: #cacfc9 !important; }

.text-left { text-align: left !important; }
.text-center { text-align: center !important; }
.text-right { text-align: right !important; }

strong { font-weight: 600 !important; }

a {
    transition: color 0.15s;
    -webkit-transition: color 0.15s;
    -mox-transition: color 0.15s;
    -ms-transition: color 0.15s;
    -o-transition: color 0.15s;
}

.lightlink { color: #cacfc9; }

.lightlink:hover { color: #b8b9b3; }

h1, h6 { letter-spacing: 2px; }

h3, h5 { letter-spacing: 1px; }

sup { top: 0px; }

.widgettitle { font-family: Josefin Sans; }

.svc-underline {
    border-bottom: 1px solid #b8b9b3;
    padding-bottom: 10px;
}

.two-column-list {
    column-count: 2;
    -webkit-column-count: 2;
    -moz-column-count: 2;
    -ms-column-count: 2;
    -o-column-count: 2;
    column-gap: 45px;
    -webkit-column-gap: 45px;
    -moz-column-gap: 45px;
    -ms-column-gap: 45px;
    -o-column-gap: 45px;
    margin-right: 45px;
    margin-left: 45px;
    margin-bottom: 23px;
}

.three-column {
    column-count: 3;
    -webkit-column-count: 3;
    -moz-column-count: 3;
    -ms-column-count: 3;
    -o-column-count: 3;
    column-gap: 45px;
    -webkit-column-gap: 45px;
    -moz-column-gap: 45px;
    -ms-column-gap: 45px;
    -o-column-gap: 45px;
}


/* -------------------- PAGE ELEMENTS -------------------- */

.bg-blue { background-color: #415671 !important; }
.bg-green { background-color: #a9b9b9 !important; }
.bg-greige { background-color: #b8b9b3 !important; }

.margin-top-zero { margin-top: 0 !important; }
.margin-top-small { margin-top: 15px !important; }
.margin-top-med { margin-top: 30px !important; }
.margin-top-large { margin-top: 45px !important; }
.margin-top-xl { margin-top: 60px !important; }
.margin-top-xxl { margin-top: 75px !important; }
.margin-top-neg { margin-top: -120px !important; }

.margin-bottom-zero { margin-bottom: 0 !important; }
.margin-bottom-small { margin-bottom: 15px !important; }
.margin-bottom-med { margin-bottom: 30px !important; }
.margin-bottom-large { margin-bottom: 45px !important; }
.margin-bottom-xl { margin-bottom: 60px !important; }

.padding-zero { padding: 0 !important; }
.padding-med { padding: 30px !important; }

.box-solid {
    border-radius: 15px;
    margin-right: 25%;
    margin-left: 25%;
}

.box-full-solid {
    border-radius: 12px;
    padding: 20px 30px;
}

.svc-page { padding-right: 30px; }

.svc-cta {
    width: 300px;
    float: right;
    border: 1px dashed #b8b9b3;
    border-radius: 12px;
    margin-top: -45px !important;
    padding: 15px 20px;
}

.svc-contact-bar {
    border-top: 4px double #58595b;
    border-bottom: 4px double #58595b;
    margin-top: -45px !important;
    padding-top: 10px;
    padding-bottom: 10px;
}

.svc-phone h5 {
    font-size: 20px !important;
    font-weight: 700;
    border-bottom: 1px solid #a9b9b9;
    padding-bottom: 12px;
}

.svc-phone h1 { font-weight: 700 !important; }

.svc-table {
    font-size: 16px !important;
    width: 60%;
    margin-right: 20%;
    margin-left: 20%;
}

.mk-shape-divider { z-index: -1; }

.thank-you-page-header {
    z-index: 0 !important;
    margin-top: -100px !important;
    padding-top: 45px;
}

.thank-you-page-header h2 {
    font-size: 34px !important;
    font-weight: 500;
}

.thank-you-page {
    z-index: 1 !important;
    margin-top: -60px !important;
}

.thank-you-page .mk-svg-icon {
    transition: fill 0.2s;
    -webkit-transition: fill 0.2s;
    -moz-transition: fill 0.2s;
    -ms-transition: fill 0.2s;
    -o-transition: fill 0.2s;
}

.thank-you-page .mk-svg-icon:hover { fill: #a9b9b9 !important; }

.svc-lmp-sidebar {
    border: 4px double #cacfc9;
    border-radius: 12px;
    padding: 10px;
}

.svc-services ul li h3 {
    font-size: 18px !important;
    font-weight: 600 !important;
    color: #58595b;
    transition: color 0.2s;
    -webkit-transition: color 0.2s;
    -moz-transition: color 0.2s;
    -ms-transition: color 0.2s;
    -o-transition: color 0.2s;
}

.svc-services ul li h3:hover { color: #a9b9b9; }


/* -------------------- HEADER -------------------- */

.mk-header {
    margin-top: 45px !important;
    margin-bottom: 300px;
}

.mk-header-nav-container { margin-top: 30px !important; }

.mk-main-navigation .menu-item-link {
    border-radius: 0;
    margin-right: 10px !important;
    margin-left: 10px !important;
    padding: 8px 12px !important;
    transition: background-color 0.5s, border-color 0.5s !important;
    -webkit-transition: background-color 0.5s, border-color 0.5s !important;
    -moz-transition: background-color 0.5s, border-color 0.5s !important;
    -ms-transition: background-color 0.5s, border-color 0.5s !important;
    -o-transition: background-color 0.5s, border-color 0.5s !important;
}

.mk-main-navigation .current-menu-item .menu-item-link, .mk-main-navigation .current-menu-parent .menu-item-link {
    color: #58595b !important;
    background-color: #ffffff !important;
    border: 1px solid #b8b9b3 !important;
}

.mk-main-navigation .sub-menu {
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 2px;
    margin-top: -5px !important;
    margin-right: 10px !important;
    margin-left: 10px !important;
}

.mk-main-navigation .sub-menu .menu-item-link {
    padding: 8px 12px !important;
    border: 0 !important;
    margin: 0 !important;
}

.mk-main-navigation .current-menu-item .sub-menu .menu-item-link, .mk-main-navigation .current-menu-parent .sub-menu .menu-item-link {
    background-color: #f7f2ec !important;
}

.mk-main-navigation .menu-item-link:hover {
    color: #ffffff !important;
    background-color: #b8b9b3 !important;
}


/* -------------------- FOOTER -------------------- */

.footer-wrapper, #sub-footer {
    padding-right: 60px !important;
    padding-left: 60px !important;
}

.footer-wrapper .mk-padding-wrapper .mk-col-1-2:nth-child(1) { width: 45%; }
.footer-wrapper .mk-padding-wrapper .mk-col-1-2:nth-child(2) { width: 55%; }
.footer-wrapper .mk-padding-wrapper .mk-col-1-2 .mk-col-1-2:nth-child(1), .footer-wrapper .mk-padding-wrapper .mk-col-1-2 .mk-col-1-2:nth-child(2) { width: 50%; }

.textwidget strong {
    font-size: 18px;
    line-height: 1.55em;
}

.textwidget a {
    transition: color 0.3s;
    -webkit-transition: color 0.3s;
    -mox-transition: color 0.3s;
    -ms-transition: color 0.3s;
    -o-transition: color 0.3s;
}

.textwidget svg:hover {
    fill: #b8b9b3 !important;
    transition: fill 0.3s;
    -webkit-transition: fill 0.3s;
    -moz-transition: fill 0.3s;
    -ms-transition: fill 0.3s;
    -o-transition: fill 0.3s;
}


/* -------------------- FORMS -------------------- */

.hide-label .gfield_label, .hide-sublabel .ginput_container label, .gfield_required { display: none !important; }

.form-half {
    display: inline-block;
    width: 50%;
}

.form-third {
    display: inline-block;
    width: 33.33%;
}

.gform_wrapper h3.gform_title {
    font-size: 24px;
    letter-spacing: 1px !important;
}

.gfield { padding: 0 !important; }
.form-padding-right { padding-right: 8px !important; }
.form-padding-left { padding-left: 8px !important; }

.ginput_container input[type=text], .textarea {
    border-color: #cacfc9 !important;
    border-radius: 3px;
    background-color: #fafafa !important;
}

.ginput_container input[type=text]:focus, .textarea:focus {
    background-color: #ffffff !important;
}

.gform_wrapper .button {
    font-size: 16px !important;
    font-weight: 500;
    letter-spacing: 2px;
    border-radius: 4px;
    margin: 0 !important;
    padding: 16px 20px !important;
}

.gform_wrapper .button:hover { background-color: #58595b !important; }

.contact-page-form {
    text-align: center !important;
    margin-bottom: 100px !important;
    padding-right: 18%;
    padding-left: 18%;
}

.contact-page-form h3.gform_title { margin-bottom: 45px; }

.contact-page-form .ginput_container input[type=text], .contact-page-form .textarea {
    font-size: 20px !important;
    font-weight: 300;
    border-radius: 5px;
    padding: 10px 15px !important;
}

.contact-page-form .gform_footer, .sidebar-contact .gform_footer { margin-top: 0 !important; }

.contact-page-form .button, .sidebar-contact .button { float: right; }

.sidebar-contact, .dental-whitepaper-form {
    border-radius: 12px;
    background: #f7f2ec;
    background: linear-gradient(to right,rgba(202,207,201,0.5),rgba(202,207,201,0));
    background: -webkit-linear-gradient(left,rgba(202,207,201,0.5),rgba(202,207,201,0));
    background: -moz-linear-gradient(right,rgba(202,207,201,0.5),rgba(202,207,201,0));
    background: -o-linear-gradient(right,rgba(202,207,201,0.5),rgba(202,207,201,0));
    padding: 18px 0 70px 30px;
}

.dental-whitepaper-form { padding-bottom: 25px !important; }

.sidebar-contact h3.gform_title {
    font-size: 20px !important;
    color: #58595b !important;
    letter-spacing: 1px !important;
}

.sidebar-contact .gform_description {
    font-size: 12px;
    line-height: 1.5em;
    margin-bottom: 10px !important;
}

.email-signup { text-align: center !important; }

.email-signup .gform_description {
    margin-top: 16px;
    margin-bottom: 24px !important;
}

.email-signup .ginput_container input[type=text] {
    text-align: center;
    font-size: 24px !important;
    font-weight: 300;
    border: 0 !important;
    border-radius: 4px;
    box-shadow: 0 0 10px rgba(0,0,0,0.2);
    -webkit-box-shadow: 0 0 10px rgba(0,0,0,0.2);
    -moz-box-shadow: 0 0 10px rgba(0,0,0,0.2);
    -ms-box-shadow: 0 0 10px rgba(0,0,0,0.2);
    -o-box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

.email-signup .gform_footer { margin-top: 5px; }

.footer-wrapper .email-signup {
    border-radius: 12px;
    background-color: rgba(169,185,185,0.5);
    padding: 10px 30px;
}

.footer-wrapper .email-signup h3.gform_title, .footer-wrapper .email-signup .ginput_container input[type=text], .dental-whitepaper-form h3.gform_title, .dental-whitepaper-form .ginput_container input[type=text] {
    font-size: 20px !important;
}

.footer-wrapper .email-signup h3.gform_title {
    text-transform: uppercase;
    letter-spacing: 1px !important;
}

.footer-wrapper .email-signup .gform_footer, .dental-whitepaper-form .gform_footer {
    margin-top: 0 !important;
}

.prescription-request .ginput_container input[type=text], .prescription-request .textarea {
    font-size: 12px !important;
}

.svc-client-form .gform_footer .gform_button {
    float: right;
    margin-top: -115px !important;
}


/* -------------------- BLOG -------------------- */

.mk-blog-meta-wrapper, .single-post .page-title { display: none !important; }

.blog .mk-header { margin-bottom: 200px !important; }

.single-post .mk-header { margin-bottom: 0px !important; }


/* -------------------- LOVE MY PET WELLNESS PLANS -------------------- */

.love-my-pet-landing { padding: 0px 30px; }

.love-my-pet-landing-button a {
    text-transform: uppercase;
    font-size: 18px;
    font-weight: 500;
    color: #415671 !important;
    border: 4px double #a9b9b9;
    padding: 10px 15px;
    transition: background-color 0.2s;
    -webkit-transition: background-color 0.2s;
    -moz-transition: background-color 0.2s;
    -ms-transition: background-color 0.2s;
    -o-transition: background-color 0.2s;
}

.love-my-pet-landing-button a:hover { background-color: #f7f2ec !important; }

.love-my-pet-pricing-mobile { display: none; }

.love-my-pet-pricing li, .love-my-pet-pricing-small li { font-weight: 600 !important; }

.love-my-pet-pricing li strong { font-weight: 400 !important; }

.love-my-pet-pricing .pricing-table, .love-my-pet-pricing-small .pricing-table {
    margin: 30px 0px;
}

.love-my-pet-pricing .pricing-cols { text-align: left; }

.love-my-pet-pricing-small .pricing-cols {
    width: 75%;
    text-align: left;
}

.love-my-pet-pricing-small .pricing-offer-grid { width: 25%; }

.adult-cat-01, .adult-cat-02, .adult-cat-03, .adult-cat-04, .adult-cat-05 {
    padding: 30px !important;
}

.adult-cat-06, .adult-cat-07, .adult-cat-09, .adult-cat-10, .adult-cat-11, .adult-cat-12, .adult-cat-13, .adult-cat-15 {
    padding: 22px !important;
}

.adult-cat-08, .adult-cat-14 {
    padding: 14px !important;
}

.adult-dog-01, .adult-dog-02, .adult-dog-03, .adult-dog-04, .adult-dog-05 {
    padding: 30px !important;
}

.adult-dog-07, .adult-dog-08, .adult-dog-10, .adult-dog-11, .adult-dog-12, .adult-dog-13, .adult-dog-14, .adult-dog-16 {
    padding: 22px !important;
}

.adult-dog-06, .adult-dog-09, .adult-dog-15 {
    padding: 14px !important;
}

.senior-cat-04 {
    padding: 38px !important;
}

.senior-cat-01, .senior-cat-02, .senior-cat-03, .senior-cat-05, .senior-cat-08 {
    padding: 30px !important;
}

.senior-cat-06, .senior-cat-07, .senior-cat-09, .senior-cat-10, .senior-cat-12, .senior-cat-13, .senior-cat-14, .senior-cat-15, .senior-cat-16, .senior-cat-18 {
    padding: 22px !important;
}

.senior-cat-11, .senior-cat-17 {
    padding: 14px !important;
}

.senior-dog-04 {
    padding: 38px !important;
}

.senior-dog-01, .senior-dog-02, .senior-dog-03, .senior-dog-05, .senior-dog-08 {
    padding: 30px !important;
}

.senior-dog-06, .senior-dog-07, .senior-dog-10, .senior-dog-11, .senior-dog-13, .senior-dog-14, .senior-dog-15, .senior-dog-16, .senior-dog-17, .senior-dog-19 {
    padding: 22px !important;
}

.senior-dog-09, .senior-dog-12, .senior-dog-18 {
    padding: 14px !important;
}

.love-my-pet-pricing .mk-button, .love-my-pet-pricing-small .mk-button {
    border-radius: 4px;
    font-weight: 500;
    text-transform: uppercase;
}

.love-my-pet-pricing .mk-button:hover, .love-my-pet-pricing-small .mk-button:hover {
    background-color: #58595b !important;
}

.love-my-pet-info em { font-size: 11px; }

.love-my-pet-table-small {
    width: 60%;
    margin-left: 20%;
    margin-right: 20%;
}

.love-my-pet-table th {
    font-family: Josefin Sans;
    font-size: 18px;
    color: #ffffff;
    background-color: rgba(88,89,91,0.85);
    padding: 4px;
    letter-spacing: 2px;
}

.love-my-pet-table .lmp-detail {
    text-align: left;
    background-color: #f7f2ec;
    padding: 2px 8px;
}

.love-my-pet-table .lmp-price {
    text-align: right;
    font-size: 16px;
    font-weight: 600;
    color: #ffffff;
    letter-spacing: 1px;
    background-color: #b8b9b3;
    border-top: solid 1px #ffffff;
    padding: 2px 8px;
}

.love-my-pet-table .lmp-table-indent {
    font-size: 12px;
    line-height: 12px;
    margin-bottom: 4px;
    margin-left: 12px;
}

.love-my-pet-table ul {
    font-size: 12px;
    line-height: 1.5em;
    margin-bottom: 0;
    margin-left: 10%;
}

.love-my-pet-faq {
    border: dashed 1px #8c8e91;
    border-radius: 6px;
    width: 95% !important;
    float: right;
}

.love-my-pet-faq h4 { font-size: 18px !important; }

.love-my-pet-faq table { margin: 0; }

.love-my-pet-faq table td {
    text-align: left;
    font-size: 13px;
    padding: 0px;
}

.love-my-pet-faq table ul li { font-weight: 400 !important; }

.love-my-pet-faq-small { float: left; }


/* -------------------- LANDING PAGES -------------------- */

.svc-lp-banner h1 {
    font-size: 42px !important;
    font-weight: 600 !important;
}

.svc-lp-banner h2 { color: #ffffff !important; }

.svc-lp-button .mk-button {
    font-family: Josefin Sans;
    color: #415671 !important;
    font-size: 28px !important;
    line-height: 0.75em;
    border-color: #415671 !important;
    background-color: #ffffff;
}

.svc-lp-button .mk-button--dimension-savvy:hover {
    color: #58595b !important;
    border-color: #58595b !important;
}

.svc-lp-button .mk-button--dimension-savvy:hover::after {
    background-color: #f7f2ec !important;
}

.svc-lp-overview .vc_col-sm-4:nth-child(1) .mk-svg-icon {
    top: 3px !important;
}

.svc-lp-overview .vc_col-sm-4:nth-child(2) .mk-svg-icon, .svc-lp-overview .vc_col-sm-4:nth-child(3) .mk-svg-icon {
    top: 5px !important;
    left: 1px !important;
}

.svc-lp-about a:hover, .svc-lp-footer a:hover { color: #cacfc9 !important; }

.svc-lp-services .mk-accordion-tab {
    color: #58595b !important;
    font-size: 18px !important;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.svc-lp-footer { margin-bottom: -100px !important; }


/* -------------------- I SPY CONTEST -------------------- */

.svc-secret-word {
    color: #ffffff;
    border-radius: 2px;
    background-color: #a9b9b9;
    padding: 2px 5px;
}

.secret-words .gform_description {
    font-size: 12px;
    line-height: 1.5em;
    margin-bottom: 10px !important;
}

.secret-words .gform_heading, .secret-words .gsection { margin-bottom: 10px !important; }

.secret-words .ginput_complex, .secret-words .gfield {
    margin-top: 0 !important;
}

.secret-words .gform_footer { padding-right: 16px; }

.secret-words .gform_button {
    float: left;
    width: 100% !important;
}


/* -------------------- MOBILE STYLING -------------------- */

@media screen and (max-width: 479px) {
    .mk-header {
        margin-top: 30px !important;
        margin-bottom: 0;
    }

    .mk-main-wrapper-holder {
        padding-right: 15px;
        padding-left: 15px;
    }

    #mk-footer .footer-wrapper {
        padding-right: 0 !important;
        padding-left: 0 !important;
    }

    .svc-cta {
        width: 100%;
        float: none;
        margin-top: 0 !important;
        margin-bottom: 30px;
    }

    .svc-contact-bar { margin-top: 0 !important; }

    .contact-page-form {
        padding-right: 0 !important;
        padding-left: 0 !important;
    }

    .love-my-pet-pricing-mobile { display: block; }

    .love-my-pet-pricing { display: none; }
}
