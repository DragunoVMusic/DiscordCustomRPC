# DiscordCustomRPC

Create a custom Discord Rich Presence like this:

![Rich Presence in action](https://pays.host/uploads/dc34e6f5-6b32-4802-bd2f-439332796eca/8AXN90Vy.png)

With very easy setup. Just change some variables and off you go!

## Requirements

 - [NodeJS](https://nodejs.org/) with [NPM](https://www.npmjs.com/)
 - [Nodemon](https://nodemon.io/) (optional for debugging purposes)
 - A Code Editor (Notepad works too, but not preferred due to formatting issues)

## How to set up
It's very easy to set up this project:

First make a Discord Application. It's easy to do:

 1. [Go to the Discord Developers Dashboard](http://discord.com/developers/applications)
 2. Create a new application
 3. Name it whatever you want.
 4. Copy the application ID

To add images to your Rich Presence follow these steps

 1. Go to Rich Presence > Art Assets
 2. Add some images and give them a unique name. Remember that you can't change these "Asset Keys"
 3. Copy the asset keys

After that follow these steps
 1. Clone into an empty folder which you don't need admin access to.
 2. Open `index.js` into your favorite code editor.
 3.  Change variables declared at the top
	 - Set all the variables how you want. To get a feeling on how it should look check out the `Rich Presence > Vizualizer` tab.
	 - Add your asset keys you uploaded above
	 - Add your Application ID (This is required)
	 - Save
4. Open a terminal window in the folder and run `node index.js`. If you have nodemon installed you can also use `nodemon index.js`.
5. Check your Discord if everything is well
6. Enjoy your custom Rich Presence

![A beautiful logo](https://www.dragunovmusic.nl/wp-content/uploads/2021/05/DGNV-Black.png)
