# PokeBot : Pokemon Discord Bot
PokeBot has collection of data of 890 pokemons and can perform various commands. All data was scraped using [Pokemon Data Scraper](https://github.com/DetainedDeveloper/Pokemon-Data-Scraper)

Other than this, all pokemon data is available in single file as well as categorized folder in both **`array[]`** and **`map{}`**

# Screenshots

<table>
  <tr>
    <td><h3>Help</h3></td>
    <td><h3>Pokemon Info</h3></td>
  </tr>
  <tr>
    <td><img src="https://github.com/DetainedDeveloper/PokeBot-Pokemon-Discord-Bot/blob/master/Screenshots/help.png?raw=true" width=496 height=361></td>
    <td><img src="https://github.com/DetainedDeveloper/PokeBot-Pokemon-Discord-Bot/blob/master/Screenshots/info.png?raw=true" width=388 height=434></td>
  </tr>
  <tr>
    <td><h3>Battle Two</h3></td>
    <td><h3>Battle Multiple</h3></td>
  </tr>
  <tr>
    <td><img src="https://github.com/DetainedDeveloper/PokeBot-Pokemon-Discord-Bot/blob/master/Screenshots/battle_two.png?raw=true" width=337 height=385></td>
    <td><img src="https://github.com/DetainedDeveloper/PokeBot-Pokemon-Discord-Bot/blob/master/Screenshots/battle_multiple.png?raw=true" width=397 height=386></td>
  </tr>
</table>

# Project Structure

### pokebot.js

- **`pokebot.js`** contains all the functions and logic. I might make different modules once I learn more **`JavaScript`**

### data

- **`config.js`** contains **`Bot Token`**, paste yours to get the bot up and running
- **`data.js`** contains **`map{}`** of **890 `{ pokemon_name : data }` pairs**
- **`dev.js`** contains information about the Developer, **me!**

# How to use

- I found this very informative [starting guide](https://www.digitalocean.com/community/tutorials/how-to-build-a-discord-bot-with-node-js) that helped me set up the **`environment`**

- After pasting your **`Bot Token`** in [**`data/config.js`**](https://github.com/DetainedDeveloper/PokeBot-Pokemon-Discord-Bot/blob/master/PokeBot/data/config.json), run **`node pokebot.js`**
- You can also install **`nodemon`** by **`npm install --save-dev nodemon -g`** and then adding **`"start" : "nodemon pokebot.js"`** inside [**`package.json`**](https://github.com/DetainedDeveloper/PokeBot-Pokemon-Discord-Bot/blob/master/PokeBot/package.json)
