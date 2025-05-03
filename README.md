

# midnight

a dark, sleek and modern discord theme.

## install

### vencord/betterdiscord (or any client that supports theme files)

1. download the theme file, [`SleekModern.theme.css`](https://github.com/refact0r/midnight-discord/blob/master/themes/midnight.theme.css). (there should be a download button at the top right of the page)
2. drag the file into your theme folder. (there should be a button to open the theme folder in theme settings)
3. (optional) customize the theme by editing the options in `SleekModern.theme.css`.


## contributing

this theme uses a dev script to check for changes in the source css files and combine them into a build file. to run locally:

1. clone the repository.
2. run `npm i`.
3. create a `.env` file in the project root with the paths of any local theme files you want to update (comma separated)

```
DEV_OUTPUT_PATH=C:\Users\USERNAME\AppData\Roaming\Vencord\themes\SleekModern-dev.theme.css
```

4. run `npm run dev`.
5. make changes to any file in `/src` or the main theme file. the local theme files you listed will automatically be updated, along with the build file in `/build`.
6. make a pull request with your changes!

## credits

forked from midnight theme.

thanks!
