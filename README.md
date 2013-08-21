make sure maven is installed on your machine (find instructions at http://maven.apache.org/).

$> git clone LINK_TO_THIS_EPO

import project to your eclipse as "existing maven project".

update app.js, set "baseURL" to your StaffRoster server side URL.

deploy the project to your JBoss AS (or any other java server you prefer, but only tested on JBoss AS 7.1+), and use your browser to navigate to the page.
