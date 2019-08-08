
## Tech Used
laravel, reactjs, materal ui, wbpack, babel (jsx),axios(api),



## Front-end and Backe-end explaination
### Back-end
php
directory 
 `app/Http/Controller/Api/CardContrller.php` file, `index()` function.

Cards name and page number are stored as configure file in `config/card.php`.

### Front-end
reactjs

All `React.js` front-end code will be found in `resource/src` directory.

Webpack configuration to compile the file is in `webpack.config.dev` file.


## Instlallation
Clone the repo on your development/test environment

```
git clone git@github.com:arifulhb/react-playing-card.git react_playing_card
cd react_playing_card
composer install
```

Now you should be able to access the site based on your `apache` / `nginx` configuration.

## Install via Docker : Keep your enviornment clear
![Docker](https://i.imgur.com/Kal7nwu.png)
using docker 


```
git clone git@github.com:arifulhb/react-playing-card.git react_playing_card
cd react_playing_card/docker
```
After moving to the `react_playing_card/docker` directory, run this command to build the docker container.
```
lemp/build
```
After build command complete building the container, run this two command one after another to run the docker and install the app
```
lemp/run
lemp/install
```
After install is successful, go to your [browser](http://localhost) `http://localhost` to run the site.

## Development
To develop the front-end (React, Javascript) and compile again, you need to install npm packages used in this project.

```
npm install
```
### Compile the React and Javascript
To compile the new javascript, react codes
```
npm run dev
```
This will compile all vendors `node_modules` and `src` code and export in `public/dist` directory.


## ToDo
1. Webpack for Production is not ready
2. Implement Redux, Saga 
## Contact
If you have any question to ask, please email me at [arifulhb@gmail.com](mailto:arifulhb@gmail.com). 
I usually replay within 24 hours.


## Screenshots

Page 1: Input Page
![Page 1](https://i.imgur.com/KMDJRdN.png)

Page 2: Result Page
![Result Page](https://i.imgur.com/ZvDao4S.png)
