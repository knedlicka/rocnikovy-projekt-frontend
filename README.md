# RP frontend

## Local setup

Just open the `./index.html` file in your browser.

In order to use admin capabilities, you need to run the following command in
the console of the browser where you will be using the app:

`localStorage.setItem("adminPassword", "abcxyzdummy");`

The exact value of the password has to be the same as on the backend (in backend's `.env` file).

If the tasks dropdown is empty, it means there are no tasks in the database, so you need to
add some first using the _Add task_ form.
