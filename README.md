# RPStoreBot
A Bot which manages a fully working shop system to keep track of, earn and spend RP points.
# Original Source https://github.com/Luois45/DiscordShopBot

## Add the bot to your server

- #### 1. Click on the link and add the bot with admin permissions to your Discord server
https://discord.com/api/oauth2/authorize?client_id=1071899813412614154&permissions=8&scope=bot

- #### 2. The instructions about the Usage are in the [Usage section](#usage)

## Install the bot yourself

- #### 1. Install the requirements
```python
pip install -r requirements.txt
```
- #### 2. Fill out the config.json
- ##### 2.1 Fill the essentials out and test the connection using the included tool
```python
python configure.py
```
- #### 3. Start the discord-shop
```python
python discord-shop.py
```
- #### 4. Optional: Use Docker (This is from original code, not tested/used by me)
- ##### 4.1 Create the docker image
##### Navigate first into the discord-shop folder and then enter:
```bash
docker build -t discordshopbot .
```
- ##### 4.2 Upload the docker image to your server or run it on your local machine

<a name="usage"></a>
## Usage
#### You must have the "Seller" role on your server in order to use all features except the setup of the bot

- #### =help: Command Help
- #### =additem: Create a item
- #### React with ✏️ to a item to edit it.
- #### React with 🗑️ to a item to delete it.
- #### =use: Type GP or XP or both to use a gold or xp boost (removes one from count, adds notice if no boosts available)
- #### @RPShopBot: Tag rpshopbot and users to add RP too. Amount of RP must be last text

## Contributing
#### Pull requests are welcome. For major changes, please open an issue upfront to discuss what you would like to change.

#### Please make sure to update tests as appropriate.
