# Project 1: Shared shopping list

This shopping-list project is implemented with the help of 3-tier architecture
(client, server, database). The main file that runs the website is "app.js". The
project uses servies and controllers to make changes on the website. The
services retrieve info from the database and the controllers have functions that
use the information gathered from the sql functions.

The homepage ("/") of the website has the shopping-list statistics lined out.

The list part of the website ("/lists") has the created lists listed. You can
also add and deactivate lists from there.

The individual list part of the website ("/lists/{id}") has the items listed.
You can add and mark items there.

The project also contains tests in the "e2e-playwright" folder.

The website is deployed to: https://lingering-sun-2871.fly.dev/
