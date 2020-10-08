# [Material Dashboard React](https://demos.creative-tim.com/material-dashboard-react/#/dashboard) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fcreativetimofficial.github.io%2Fmaterial-dashboard-react&text=Material%20Dashboard%20React%20-%20Free%20Bootstrap%20Admin%20Template&original_referer=https%3A%2F%2Fdemos.creative-tim.com%2Fmaterial-dashboard-react%2F%3F_ga%3D2.10428917.198078103.1532329372-1803433978.1528781151&via=creativetim&hashtags=react%2Cmaterial-ui)



![version](https://img.shields.io/badge/version-1.9.0-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/material-dashboard-react.svg?maxAge=2592000)]() [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/material-dashboard-react.svg?maxAge=2592000)]() [![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)](https://gitter.im/creative-tim/material-dashboard?utm_source=share-link&utm_medium=link&utm_campaign=share-link) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)

![Product Gif](src/assets/github/md-react.gif)

Material Dashboard React is a free Material-UI Admin with a fresh, new design inspired by Google's Material Design. We are very excited to introduce our take on the material concepts through an easy to use and beautiful set of components. Material Dashboard React was built over the popular Material-UI framework.

Material Dashboard React makes use of light, surface and movement. The general layout resembles sheets of paper following multiple different layers, so that the depth and order is obvious. The navigation stays mainly on the left sidebar and the content is on the right inside the main panel.

Material Dashboard React comes with 5 color filter choices for both the sidebar and the card headers (blue, green, orange, red and purple) and an option to have a background image on the sidebar.

Material Dashboard React was created using [create-react-app](https://github.com/facebook/create-react-app) and it uses a framework built by our friend [Olivier - Material-UI v3.1.0](https://github.com/mui-org/material-ui), who did an amazing job creating the backbone for the material effects, animations, ripples and transitions. Big thanks to his team for the effort and forward thinking they put into it.

Special thanks go to:
+ [React-chartist](https://github.com/fraserxu/react-chartist) for the wonderful charts.

We are very excited to share this dashboard with you and we look forward to hearing your feedback!

You can find the Github Repo here.

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Usage](#usage)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)


## Versions

[<img src="src/assets/github/html.png" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard)
[<img src="src/assets/github/react.svg" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-react)
[<img src="src/assets/github/vuejs.png" width="60" height="60" />](https://www.creative-tim.com/product/vue-material-dashboard)
[<img src="src/assets/github/angular.png" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-angular2)


| HTML | React | Vue | Angular |
| --- | --- | --- | --- |
| [![Material Dashboard HTML](src/assets/github/opt_md_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard) | [![Material Dashboard React](src/assets/github/opt_mdr_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-react) | [![Vue Material Dashboard ](src/assets/github/opt_md_vue_thumbnail.jpg)](https://www.creative-tim.com/product/vue-material-dashboard) | [![Material Dashboard Angular](src/assets/github/opt_md_angular_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-angular2)

## Demo

| Dashboard | User Profile | Tables | Maps | Notification |
| --- | --- | --- | --- | --- |
| [![Start page](src/assets/github/dashboard.png)](https://demos.creative-tim.com/material-dashboard-react/#/dashboard) | [![User profile page](src/assets/github/user_profile.png)](https://demos.creative-tim.com/material-dashboard-react/#/user) | [![Tables page ](src/assets/github/tables.png)](https://demos.creative-tim.com/material-dashboard-react/#/table) | [![Maps Page](src/assets/github/maps.png)](https://demos.creative-tim.com/material-dashboard-react/#/maps) | [![Notification page](src/assets/github/notification.png)](https://demos.creative-tim.com/material-dashboard-react/#/notifications)

[View More](https://demos.creative-tim.com/material-dashboard-react/#/dashboard).


## Quick start

Quick start options:

- Download and install [Docker]("https://docs.docker.com/desktop/")
- Clone the repo: `git clone https://github.com/creativetimofficial/material-dashboard-react.git`.
- [Download from Github](https://github.com/creativetimofficial/material-dashboard-react/archive/master.zip).
- [Download from Creative Tim](https://www.creative-tim.com/product/material-dashboard-react).
- From the project root folder run `docker-compose up --build`. Note that the first time you run this the images will build.
- Once docker-compose has finished, you will find the projects on the following URLs:
[Dashboard](http://localhost:3000/admin/dashboard)
[Identity Server](http://localhost:5000/.well-known/openid-configuration) -


## Usage
You now have 2 applications running consisting of a React front end and application an Identity Server (IDS) based on C# and .Net Core. This implentation follow the resource owner password flow but can be modified to support others.

The integration gives you 3 features:
1. Login. The IDS has 2 default logins to get you started:
	Username: alice	Password: Pass123$
	Username: bob	Password: Pass123$

2. Register. This registers a new user in IDS

3. User Profile. Update profile and change password.

If you wish to change any of the settings around authentications, please refer to the following files:
- \React\src\services\oauth.js
- \IdentityServer\Config.cs
- \IdentityServer\Startup.cs
- \IdentityServer\Quickstart\Account\AccountOptions.cs

You can find documentation  on IDS [here](https://identityserver.io/)

## Documentation
The documentation for the Material Dashboard React is hosted at our [website](https://demos.creative-tim.com/material-dashboard-react/#/documentation/tutorial).


## File Structure

Within the download you'll find the following directories and files:

```
argon-dashboard-pro-free-react - Copy
 ┣ IdentityServer
 ┃ ┣ Data
 ┃ ┃ ┣ Migrations
 ┃ ┃ ┃ ┣ 20180109192453_CreateIdentitySchema.cs
 ┃ ┃ ┃ ┣ 20180109192453_CreateIdentitySchema.Designer.cs
 ┃ ┃ ┃ ┗ ApplicationDbContextModelSnapshot.cs
 ┃ ┃ ┗ ApplicationDbContext.cs
 ┃ ┣ Helpers
 ┃ ┃ ┗ X509Helper.cs
 ┃ ┣ Models
 ┃ ┃ ┗ ApplicationUser.cs
 ┃ ┣ Properties
 ┃ ┃ ┗ launchSettings.json
 ┃ ┣ Quickstart
 ┃ ┃ ┣ Account
 ┃ ┃ ┃ ┣ AccountController.cs
 ┃ ┃ ┃ ┣ AccountOptions.cs
 ┃ ┃ ┃ ┣ ExternalController.cs
 ┃ ┃ ┃ ┣ ExternalProvider.cs
 ┃ ┃ ┃ ┣ LoggedOutViewModel.cs
 ┃ ┃ ┃ ┣ LoginInputModel.cs
 ┃ ┃ ┃ ┣ LoginViewModel.cs
 ┃ ┃ ┃ ┣ LogoutInputModel.cs
 ┃ ┃ ┃ ┣ LogoutViewModel.cs
 ┃ ┃ ┃ ┣ PasswordController.cs
 ┃ ┃ ┃ ┣ ProfileController.cs
 ┃ ┃ ┃ ┣ RedirectViewModel.cs
 ┃ ┃ ┃ ┣ RegisterController.cs
 ┃ ┃ ┃ ┣ RegisterViewModel.cs
 ┃ ┃ ┃ ┣ UpdatePasswordModel.cs
 ┃ ┃ ┃ ┗ UpdateProfileModel.cs
 ┃ ┃ ┣ Consent
 ┃ ┃ ┃ ┣ ConsentController.cs
 ┃ ┃ ┃ ┣ ConsentInputModel.cs
 ┃ ┃ ┃ ┣ ConsentOptions.cs
 ┃ ┃ ┃ ┣ ConsentViewModel.cs
 ┃ ┃ ┃ ┣ ProcessConsentResult.cs
 ┃ ┃ ┃ ┗ ScopeViewModel.cs
 ┃ ┃ ┣ Device
 ┃ ┃ ┃ ┣ DeviceAuthorizationInputModel.cs
 ┃ ┃ ┃ ┣ DeviceAuthorizationViewModel.cs
 ┃ ┃ ┃ ┗ DeviceController.cs
 ┃ ┃ ┣ Diagnostics
 ┃ ┃ ┃ ┣ DiagnosticsController.cs
 ┃ ┃ ┃ ┗ DiagnosticsViewModel.cs
 ┃ ┃ ┣ Grants
 ┃ ┃ ┃ ┣ GrantsController.cs
 ┃ ┃ ┃ ┗ GrantsViewModel.cs
 ┃ ┃ ┣ Home
 ┃ ┃ ┃ ┣ ErrorViewModel.cs
 ┃ ┃ ┃ ┗ HomeController.cs
 ┃ ┃ ┣ Extensions.cs
 ┃ ┃ ┣ SecurityHeadersAttribute.cs
 ┃ ┃ ┗ TestUsers.cs
 ┃ ┣ Views
 ┃ ┃ ┣ Account
 ┃ ┃ ┃ ┣ AccessDenied.cshtml
 ┃ ┃ ┃ ┣ LoggedOut.cshtml
 ┃ ┃ ┃ ┣ Login.cshtml
 ┃ ┃ ┃ ┗ Logout.cshtml
 ┃ ┃ ┣ Consent
 ┃ ┃ ┃ ┗ Index.cshtml
 ┃ ┃ ┣ Device
 ┃ ┃ ┃ ┣ Success.cshtml
 ┃ ┃ ┃ ┣ UserCodeCapture.cshtml
 ┃ ┃ ┃ ┗ UserCodeConfirmation.cshtml
 ┃ ┃ ┣ Diagnostics
 ┃ ┃ ┃ ┗ Index.cshtml
 ┃ ┃ ┣ Grants
 ┃ ┃ ┃ ┗ Index.cshtml
 ┃ ┃ ┣ Home
 ┃ ┃ ┃ ┗ Index.cshtml
 ┃ ┃ ┣ Shared
 ┃ ┃ ┃ ┣ Error.cshtml
 ┃ ┃ ┃ ┣ Redirect.cshtml
 ┃ ┃ ┃ ┣ _Layout.cshtml
 ┃ ┃ ┃ ┣ _Nav.cshtml
 ┃ ┃ ┃ ┣ _ScopeListItem.cshtml
 ┃ ┃ ┃ ┗ _ValidationSummary.cshtml
 ┃ ┃ ┣ _ViewImports.cshtml
 ┃ ┃ ┗ _ViewStart.cshtml
 ┃ ┣ wwwroot
 ┃ ┃ ┣ css
 ┃ ┃ ┃ ┣ site.css
 ┃ ┃ ┃ ┣ site.min.css
 ┃ ┃ ┃ ┗ site.scss
 ┃ ┃ ┣ images
 ┃ ┃ ┃ ┗ login.59fc83e2.jpeg
 ┃ ┃ ┣ js
 ┃ ┃ ┃ ┣ signin-redirect.js
 ┃ ┃ ┃ ┗ signout-redirect.js
 ┃ ┃ ┣ lib
 ┃ ┃ ┃ ┣ bootstrap
 ┃ ┃ ┃ ┃ ┣ dist
 ┃ ┃ ┃ ┃ ┃ ┣ css
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-grid.css
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-grid.css.map
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-grid.min.css
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-grid.min.css.map
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-reboot.css
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-reboot.css.map
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-reboot.min.css
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-reboot.min.css.map
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.css
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.css.map
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.min.css
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ bootstrap.min.css.map
 ┃ ┃ ┃ ┃ ┃ ┗ js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.bundle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.bundle.js.map
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.bundle.min.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.bundle.min.js.map
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.js.map
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.min.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ bootstrap.min.js.map
 ┃ ┃ ┃ ┃ ┣ scss
 ┃ ┃ ┃ ┃ ┃ ┣ mixins
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _alert.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _background-variant.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _badge.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _border-radius.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _box-shadow.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _breakpoints.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _buttons.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _caret.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _clearfix.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _deprecate.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _float.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _forms.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _gradients.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _grid-framework.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _grid.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _hover.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _image.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _list-group.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _lists.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _nav-divider.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _pagination.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _reset-text.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _resize.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _screen-reader.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _size.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _table-row.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _text-emphasis.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _text-hide.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _text-truncate.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _transition.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _visibility.scss
 ┃ ┃ ┃ ┃ ┃ ┣ utilities
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _align.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _background.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _borders.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _clearfix.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _display.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _embed.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _flex.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _float.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _overflow.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _position.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _screenreaders.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _shadows.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _sizing.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _spacing.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _stretched-link.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _text.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _visibility.scss
 ┃ ┃ ┃ ┃ ┃ ┣ vendor
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _rfs.scss
 ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-grid.scss
 ┃ ┃ ┃ ┃ ┃ ┣ bootstrap-reboot.scss
 ┃ ┃ ┃ ┃ ┃ ┣ bootstrap.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _alert.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _badge.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _breadcrumb.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _button-group.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _buttons.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _card.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _carousel.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _close.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _code.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _custom-forms.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _dropdown.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _forms.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _functions.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _grid.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _images.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _input-group.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _jumbotron.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _list-group.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _media.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _mixins.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _modal.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _nav.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _navbar.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _pagination.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _popover.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _print.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _progress.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _reboot.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _root.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _spinners.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _tables.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _toasts.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _tooltip.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _transitions.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _type.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _utilities.scss
 ┃ ┃ ┃ ┃ ┃ ┗ _variables.scss
 ┃ ┃ ┃ ┃ ┗ README.md
 ┃ ┃ ┃ ┗ jquery
 ┃ ┃ ┃ ┃ ┣ dist
 ┃ ┃ ┃ ┃ ┃ ┣ jquery.js
 ┃ ┃ ┃ ┃ ┃ ┣ jquery.min.js
 ┃ ┃ ┃ ┃ ┃ ┣ jquery.min.map
 ┃ ┃ ┃ ┃ ┃ ┣ jquery.slim.js
 ┃ ┃ ┃ ┃ ┃ ┣ jquery.slim.min.js
 ┃ ┃ ┃ ┃ ┃ ┗ jquery.slim.min.map
 ┃ ┃ ┃ ┃ ┣ LICENSE.txt
 ┃ ┃ ┃ ┃ ┗ README.md
 ┃ ┃ ┣ favicon.ico
 ┃ ┃ ┣ icon.jpg
 ┃ ┃ ┗ icon.png
 ┃ ┣ appsettings.json
 ┃ ┣ AspIdUsers.db
 ┃ ┣ Config.cs
 ┃ ┣ Dockerfile
 ┃ ┣ IdentityServer.csproj
 ┃ ┣ IdentityServer.csproj.user
 ┃ ┣ Program.cs
 ┃ ┣ SeedData.cs
 ┃ ┣ Startup.cs
 ┃ ┣ tempkey.jwk
 ┃ ┗ updateUI.ps1
 ┣ React
 ┃ ┣ documentation
 ┃ ┃ ┣ assets
 ┃ ┃ ┃ ┣ css
 ┃ ┃ ┃ ┃ ┣ bootstrap.min.css
 ┃ ┃ ┃ ┃ ┣ demo-documentation.css
 ┃ ┃ ┃ ┃ ┗ material-dashboard.css
 ┃ ┃ ┃ ┣ img
 ┃ ┃ ┃ ┃ ┣ faces
 ┃ ┃ ┃ ┃ ┃ ┗ marc.jpg
 ┃ ┃ ┃ ┃ ┣ apple-icon.png
 ┃ ┃ ┃ ┃ ┣ cover.jpeg
 ┃ ┃ ┃ ┃ ┣ favicon.png
 ┃ ┃ ┃ ┃ ┣ mask.png
 ┃ ┃ ┃ ┃ ┣ new_logo.png
 ┃ ┃ ┃ ┃ ┣ reactlogo.png
 ┃ ┃ ┃ ┃ ┣ sidebar-1.jpg
 ┃ ┃ ┃ ┃ ┣ sidebar-2.jpg
 ┃ ┃ ┃ ┃ ┣ sidebar-3.jpg
 ┃ ┃ ┃ ┃ ┣ sidebar-4.jpg
 ┃ ┃ ┃ ┃ ┗ tim_80x80.png
 ┃ ┃ ┃ ┗ js
 ┃ ┃ ┃ ┃ ┣ bootstrap.min.js
 ┃ ┃ ┃ ┃ ┗ jquery-3.2.1.min.js
 ┃ ┃ ┗ tutorial-components.html
 ┃ ┣ public
 ┃ ┃ ┣ apple-icon.png
 ┃ ┃ ┣ favicon.ico
 ┃ ┃ ┣ index.html
 ┃ ┃ ┗ manifest.json
 ┃ ┣ src
 ┃ ┃ ┣ actions
 ┃ ┃ ┃ ┣ authActions.js
 ┃ ┃ ┃ ┗ types.js
 ┃ ┃ ┣ assets
 ┃ ┃ ┃ ┣ css
 ┃ ┃ ┃ ┃ ┗ material-dashboard-react.css
 ┃ ┃ ┃ ┣ github
 ┃ ┃ ┃ ┃ ┣ angular.png
 ┃ ┃ ┃ ┃ ┣ chrome.png
 ┃ ┃ ┃ ┃ ┣ dashboard.jpg
 ┃ ┃ ┃ ┃ ┣ edge.png
 ┃ ┃ ┃ ┃ ┣ firefox.png
 ┃ ┃ ┃ ┃ ┣ html.png
 ┃ ┃ ┃ ┃ ┣ map.jpg
 ┃ ┃ ┃ ┃ ┣ md-react.gif
 ┃ ┃ ┃ ┃ ┣ notifications.jpg
 ┃ ┃ ┃ ┃ ┣ opera.png
 ┃ ┃ ┃ ┃ ┣ opt_mdr_thumbnail.jpg
 ┃ ┃ ┃ ┃ ┣ opt_md_angular_thumbnail.jpg
 ┃ ┃ ┃ ┃ ┣ opt_md_thumbnail.jpg
 ┃ ┃ ┃ ┃ ┣ opt_md_vue_thumbnail.jpg
 ┃ ┃ ┃ ┃ ┣ react.svg
 ┃ ┃ ┃ ┃ ┣ safari.png
 ┃ ┃ ┃ ┃ ┣ tables.jpg
 ┃ ┃ ┃ ┃ ┣ userprofile.jpg
 ┃ ┃ ┃ ┃ ┗ vuejs.png
 ┃ ┃ ┃ ┣ img
 ┃ ┃ ┃ ┃ ┣ faces
 ┃ ┃ ┃ ┃ ┃ ┗ marc.jpg
 ┃ ┃ ┃ ┃ ┣ apple-icon.png
 ┃ ┃ ┃ ┃ ┣ cover.jpeg
 ┃ ┃ ┃ ┃ ┣ favicon.png
 ┃ ┃ ┃ ┃ ┣ login.jpeg
 ┃ ┃ ┃ ┃ ┣ mask.png
 ┃ ┃ ┃ ┃ ┣ new_logo.png
 ┃ ┃ ┃ ┃ ┣ reactlogo.png
 ┃ ┃ ┃ ┃ ┣ register.jpeg
 ┃ ┃ ┃ ┃ ┣ sidebar-1.jpg
 ┃ ┃ ┃ ┃ ┣ sidebar-2.jpg
 ┃ ┃ ┃ ┃ ┣ sidebar-3.jpg
 ┃ ┃ ┃ ┃ ┣ sidebar-4.jpg
 ┃ ┃ ┃ ┃ ┗ tim_80x80.png
 ┃ ┃ ┃ ┗ jss
 ┃ ┃ ┃ ┃ ┣ material-dashboard-react
 ┃ ┃ ┃ ┃ ┃ ┣ components
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ authNavbarStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ buttonStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ cardAvatarStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ cardBodyStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ cardFooterStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ cardHeaderStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ cardIconStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ cardStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ customInputStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ customTabsStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ footerStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ headerLinksStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ headerStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ infoStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ rtlHeaderLinksStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ sidebarStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ snackbarContentStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ tableStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ tasksStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ typographyStyle.js
 ┃ ┃ ┃ ┃ ┃ ┣ layouts
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ adminStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ authStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ rtlStyle.js
 ┃ ┃ ┃ ┃ ┃ ┣ views
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ dashboardStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ iconsStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ loginPageStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ registerPageStyle.js
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ rtlStyle.js
 ┃ ┃ ┃ ┃ ┃ ┣ cardImagesStyles.js
 ┃ ┃ ┃ ┃ ┃ ┣ checkboxAdnRadioStyle.js
 ┃ ┃ ┃ ┃ ┃ ┣ customCheckboxRadioSwitch.js
 ┃ ┃ ┃ ┃ ┃ ┣ dropdownStyle.js
 ┃ ┃ ┃ ┃ ┃ ┗ tooltipStyle.js
 ┃ ┃ ┃ ┃ ┗ material-dashboard-react.js
 ┃ ┃ ┣ components
 ┃ ┃ ┃ ┣ Card
 ┃ ┃ ┃ ┃ ┣ Card.js
 ┃ ┃ ┃ ┃ ┣ CardAvatar.js
 ┃ ┃ ┃ ┃ ┣ CardBody.js
 ┃ ┃ ┃ ┃ ┣ CardFooter.js
 ┃ ┃ ┃ ┃ ┣ CardHeader.js
 ┃ ┃ ┃ ┃ ┗ CardIcon.js
 ┃ ┃ ┃ ┣ CustomButtons
 ┃ ┃ ┃ ┃ ┗ Button.js
 ┃ ┃ ┃ ┣ CustomInput
 ┃ ┃ ┃ ┃ ┗ CustomInput.js
 ┃ ┃ ┃ ┣ CustomTabs
 ┃ ┃ ┃ ┃ ┗ CustomTabs.js
 ┃ ┃ ┃ ┣ FixedPlugin
 ┃ ┃ ┃ ┃ ┗ FixedPlugin.js
 ┃ ┃ ┃ ┣ Footer
 ┃ ┃ ┃ ┃ ┗ Footer.js
 ┃ ┃ ┃ ┣ Grid
 ┃ ┃ ┃ ┃ ┣ GridContainer.js
 ┃ ┃ ┃ ┃ ┗ GridItem.js
 ┃ ┃ ┃ ┣ InfoArea
 ┃ ┃ ┃ ┃ ┗ InfoArea.js
 ┃ ┃ ┃ ┣ Navbars
 ┃ ┃ ┃ ┃ ┣ AdminNavbarLinks.js
 ┃ ┃ ┃ ┃ ┣ AuthNavBar.js
 ┃ ┃ ┃ ┃ ┣ Navbar.js
 ┃ ┃ ┃ ┃ ┗ RTLNavbarLinks.js
 ┃ ┃ ┃ ┣ Sidebar
 ┃ ┃ ┃ ┃ ┗ Sidebar.js
 ┃ ┃ ┃ ┣ Snackbar
 ┃ ┃ ┃ ┃ ┣ Snackbar.js
 ┃ ┃ ┃ ┃ ┗ SnackbarContent.js
 ┃ ┃ ┃ ┣ Table
 ┃ ┃ ┃ ┃ ┗ Table.js
 ┃ ┃ ┃ ┣ Tasks
 ┃ ┃ ┃ ┃ ┗ Tasks.js
 ┃ ┃ ┃ ┗ Typography
 ┃ ┃ ┃ ┃ ┣ Danger.js
 ┃ ┃ ┃ ┃ ┣ Info.js
 ┃ ┃ ┃ ┃ ┣ Muted.js
 ┃ ┃ ┃ ┃ ┣ Primary.js
 ┃ ┃ ┃ ┃ ┣ Quote.js
 ┃ ┃ ┃ ┃ ┣ Success.js
 ┃ ┃ ┃ ┃ ┗ Warning.js
 ┃ ┃ ┣ data
 ┃ ┃ ┃ ┗ store
 ┃ ┃ ┃ ┃ ┣ slices
 ┃ ┃ ┃ ┃ ┗ transforms
 ┃ ┃ ┣ layouts
 ┃ ┃ ┃ ┣ Admin.js
 ┃ ┃ ┃ ┣ Auth.js
 ┃ ┃ ┃ ┗ RTL.js
 ┃ ┃ ┣ reducers
 ┃ ┃ ┃ ┣ authReducer.js
 ┃ ┃ ┃ ┗ index.js
 ┃ ┃ ┣ services
 ┃ ┃ ┃ ┗ oauth.js
 ┃ ┃ ┣ utils
 ┃ ┃ ┃ ┣ authProvider.js
 ┃ ┃ ┃ ┣ axiosHeaders.js
 ┃ ┃ ┃ ┗ protectedRoute.js
 ┃ ┃ ┣ variables
 ┃ ┃ ┃ ┣ charts.js
 ┃ ┃ ┃ ┗ general.js
 ┃ ┃ ┣ views
 ┃ ┃ ┃ ┣ Dashboard
 ┃ ┃ ┃ ┃ ┗ Dashboard.js
 ┃ ┃ ┃ ┣ Icons
 ┃ ┃ ┃ ┃ ┗ Icons.js
 ┃ ┃ ┃ ┣ Maps
 ┃ ┃ ┃ ┃ ┗ Maps.js
 ┃ ┃ ┃ ┣ Notifications
 ┃ ┃ ┃ ┃ ┗ Notifications.js
 ┃ ┃ ┃ ┣ RTLPage
 ┃ ┃ ┃ ┃ ┗ RTLPage.js
 ┃ ┃ ┃ ┣ TableList
 ┃ ┃ ┃ ┃ ┗ TableList.js
 ┃ ┃ ┃ ┣ Typography
 ┃ ┃ ┃ ┃ ┗ Typography.js
 ┃ ┃ ┃ ┣ UpgradeToPro
 ┃ ┃ ┃ ┃ ┗ UpgradeToPro.js
 ┃ ┃ ┃ ┗ UserProfile
 ┃ ┃ ┃ ┃ ┣ LoginPage.js
 ┃ ┃ ┃ ┃ ┣ RegisterPage.js
 ┃ ┃ ┃ ┃ ┗ UserProfile.js
 ┃ ┃ ┣ App.js
 ┃ ┃ ┣ index.js
 ┃ ┃ ┣ logo.svg
 ┃ ┃ ┣ routes.js
 ┃ ┃ ┗ store.js
 ┃ ┣ .babelrc
 ┃ ┣ .env
 ┃ ┣ .eslintignore
 ┃ ┣ .eslintrc.js
 ┃ ┣ bower.json
 ┃ ┣ CHANGELOG.md
 ┃ ┣ Dockerfile
 ┃ ┣ gulpfile.js
 ┃ ┣ ISSUE_TEMPLATE.md
 ┃ ┣ jsconfig.json
 ┃ ┣ LICENSE.md
 ┃ ┣ package-lock.json
 ┃ ┣ package.json
 ┃ ┣ React.njsproj
 ┃ ┗ React.njsproj.user
 ┣ .dockerignore
 ┣ .gitignore
 ┣ CreativeTim.sln
 ┣ docker-compose.yml
 ┗ README.md
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="src/assets/github/chrome.png" width="64" height="64"> <img src="src/assets/github/firefox.png" width="64" height="64"> <img src="src/assets/github/edge.png" width="64" height="64"> <img src="src/assets/github/safari.png" width="64" height="64"> <img src="src/assets/github/opera.png" width="64" height="64">


## Resources
- Demo: https://demos.creative-tim.com/material-dashboard-react
- Download Page: https://www.creative-tim.com/product/material-dashboard-react
- Documentation: https://demos.creative-tim.com/material-dashboard-react/#/documentation/tutorial
- License Agreement: https://www.creative-tim.com/license
- Support: https://www.creative-tim.com/contact-us
- Issues: [Github Issues Page](https://github.com/creativetimofficial/material-dashboard-react/issues)
- [Material Kit React - For Front End Development](https://www.creative-tim.com/product/material-kit-react?ref=github-mdr-free)

## Reporting Issues
We use GitHub Issues as the official bug tracker for the Material Dashboard React. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Dashboard React. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us) instead of opening an issue.

## Licensing

- Copyright 2020 Creative Tim (https://www.creative-tim.com)
- Licensed under MIT (https://github.com/creativetimofficial/material-dashboard-react/blob/master/LICENSE.md)

## Useful Links

More products from Creative Tim: <https://www.creative-tim.com/products>

Tutorials: <https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w>

Freebies: <https://www.creative-tim.com/products>

Affiliate Program (earn money): <https://www.creative-tim.com/affiliates/new>

Social Media:

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>