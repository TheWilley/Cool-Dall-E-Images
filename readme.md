# Cool Dall-E Images
Some cool images generated by Dall-E 

The title of the images are the prompts used to generate them

## Compression
I've included a compression library as images generated by Dall-E have a big file size when generated in the `1028 x 1028` aspect ratio. You need `Node.js` installed, then:

1. Add all generated images you want compressed in the `raw` folder

2. Install dependencies
   ```
   $ npm i
   ```

3. Run compression script
   ```
   $ npm run compress
   ```

A folder called `compressed` will be created inside the `dist` folder, containing the compressed images

**Note that the raw folder is used only for compression purposes. No images will be commited in their raw format as they are HUGE in file size (something like 3mb per image, and that adds up quickly!)**

## License
MIT

PLEASE DO NOT CREDIT ME! I DID NOT MAKE THESE IMAGES, Dall-E DID! (you can of course link to this respotory, but NEVER claim you or I made them)
