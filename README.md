# a-client-setup-eclipse
Eclipse setup for A Client

# download

Eclipse setup:

`https://www.eclipse.org`

Select "Eclipse IDE for JavaScript and Web Developers" during install

Install Eclipse Angular Plugin:

`https://marketplace.eclipse.org/content/angular-eclipse`

# Import project

import new project

use git

define URI, e.g. https://github.com/domschmidt/a...-client.git

use new project wizard

select Angular > Angular Project

define project name, e.g. "A Client"

select NodeJS (prefer last LTS version)

Angular CLI -> select "install"

Source dir -> "src"

Prefix -> ""

Style -> SCSS

Routing -> Check

# No Run Configuration possible
Eclipse Angular Plugin can handle NG commands only.

# Terminal
Open terminal and execute

`npm install`

`ionic serve`

# Open browser

`http://localhost:8100`
