# npm-nodedom
Repo that shows loading issue with script tasks in npm in combination with nodedom.

# Run

npm install nodedom -g

npm install

npm run watch

This will now run all tasks properly and output will come in the main window.

Yet there is an issue with this setup, and that are the background processes that does not exit
when the main process ends. This means you have to restart the command promt each time npm run watch is run.

This is not an issue if relying on nodemon watch, which works fine with the example provided here.
