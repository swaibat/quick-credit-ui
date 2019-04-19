# quick-credit-ui

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/ce427c86332745ec83592d61114ba94f)](https://app.codacy.com/app/swaibat/quick-credit-ui?utm_source=github.com&utm_medium=referral&utm_content=swaibat/quick-credit-ui&utm_campaign=Badge_Grade_Dashboard)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/swaibat/sassadminlite/blob/master/LICENSE)

Quick Credit is anonline lending platform that provides short term soft loans to individuals.This helps solve problems of financial inclusion as away to alleviate poverty and empower low income earners.

<nav class="flex-x shadow padding-y-1 fixed-top full-width">

<div class="logo margin-l-3 margin-t-2">[QCredit](/)</div>

* [Dashboard](dashboard.html) * Users<span class="float-right margin-r-2 mobile-view">▼</span> * [All Clients](users.html) * [Verified](verified.html) * [Un-verified](un-verified.html) * Loans<span class="float-right margin-r-2 mobile-view">▼</span> * [All Applications](applications.html) * [Special Loans](special.html) * [Current](current.html) * [Pending](pending.html) * [Repaid](repaid.html) * [Post repayment](post-loan-repayment.html)

<div class="margin-l-auto margin-r-3 d-flex">

<div class="auth-btn margin-t-1"><button id="signin" class="btn blue">sign in</button><button id="signup" class="btn blue margin-l-1">sign up</button></div>

<button id="avatar" class="collapsible padding-t-1 d-flex btn"><span class="padding-r-2 margin-t-1">My account</span> ![user](./assets/img/user.svg)</button> * [my account](client.html) * <a>profile</a> * <a>Notifications</a>

<div class="client-links">* [Apply for Loan](apply-for-loan.html)* [repayment history](repayment-history.html)</div>

* [Logout](/) <button type="button" onclick="toggle()" class="btn mobile-view"><span class="humberger">⋮</span></button></div>

</nav>

<main role="main">

<div class="slider blue padding-3 d-flex">

<div class="hero-txt resp-50 white-txt"># quick credit Quick Credit is anonline lending platform that provides short term soft loans to individuals.This helps solve problems of financial inclusion as away to alleviate poverty and empower low income earners.</div>

<div class="hero">![](./../dist/assets/img/quick-credit-preview.png)</div>

</div>

<div class="padding-5"># File structure * * * Within Quick credit UI you WIll find the following directories and files. Cross check in any of the file misses the app may have a problem while bieng excetuted

<pre>                    `Quick-credit-ui-1/
                    │
                    ├── dist/
                    │   ├── assets/
                    │   └── pages
                    ├── documentation/
                    ├── src/
                    │   ├── assets/
                    │   ├── layouts/
                    │   ├── pages/
                    │   └── patials/
                    ├── .gitignore/
                    ├── gulpfile.js
                    ├── LICENCE
                    ├── package.json
                    └──README.md` 
                </pre>

# Getting Started * * * on your local machine run the following command that will enable you save Quick credit Ui on your local machine(you need to have git installed on your machine) OR Or you can download it manually on clone or download button `$ git clone https://github.com/swaibat/quick-credit-ui-1.git` open the file and the check `dist` directory thats where all the necessary pages and their assets are found `$ cd quick-credit-ui-1` then `quick-credit-ui-1/dist` ## For developers requirements

<table>

<tbody>

<tr>

<td>Nodejs:</td>

<td>download nodejs [here](https://nodejs.org)</td>

</tr>

<tr>

<td>gulp:</td>

<td>run `$ npm install gulp-cli -g` to install gulp globally</td>

</tr>

<tr>

<td>Modules:</td>

<td>then run `$ npm install` to install all the necessary module for tha app to operate</td>

</tr>

</tbody>

</table>

Now you will be able to edit files located in `src` folder and your files will be watched each time you make a change and browser will be refreshed each time you edit ### THANK YOU

<div class="align-center margin-t-6">## Rumbiiha Swaibu

<div class="flex-y">**Front-end Developer** <small>Website: https://sassybootstrap.com</small> <small>Github: https://github.com/swaibat</small> <small>Codepen:https://codepen.io/swaibu</small></div>

</div>

</div>

</main>

<footer class="shadow-top padding-y-3 full-width"><a>Quick credit 2019</a></footer>
