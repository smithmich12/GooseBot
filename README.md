# GooseBot

## Requirements before you start
- This is being run on my personal machine with an RTX 4070 TI with 12 GB of vRAM. Results may vary.
- [ComfyUi](https://github.com/comfyanonymous/ComfyUI) installed and running on port 8188
- [Flux.1 Dev](https://huggingface.co/black-forest-labs/FLUX.1-dev) and the rest of it's requirements for the model installed and in the correct ComfyUi folders
- A discord bot with a token and client id. Place the token in a .env file with DISCORD_TOKEN and DISCORD_CLIENTID
- If you want the output directory cleared you must specify OUTPUT_DIR

## Getting it up and running
1. Clone the directory
`git clone https://github.com/smithmich12/GooseBot.git`
2. Install npm packages
`npm i`
3. Run registercommands.js to register the image command
`node registercommands.js`
4. Run the bot
`node .`

That's it you should now be able to go and run the command in discord and give it a prompt to get an image. With my GPU it takes about 30 seconds with the settings in the workflow but to increase speed you can reduce the number of steps in image.js at the cost of quality of the image.