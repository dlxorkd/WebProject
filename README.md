### shoppingMall

- Welcome our DayBreeze

## Installation

1. Create a folder to hold your installation: `mkdir dayBreeze`
2. FTP/Copy the contents of the zip to your newly created folder
3. Enter folder: `cd dayBreeze`
4. Install dependencies: `npm install`
5. Start application: `npm start --production`
6. Visit [http://127.0.0.1:1111](http://127.0.0.1:1111) in your browser

Keeping dayBreeze running after closing the terminal can be done in a few ways but we recommend using the `PM2` package. To set this up:

1. Install PM2: `npm install pm2 -g`
2. Add dayBreeze to PM2: `NODE_ENV=production pm2 start app.js --name "expressCart"`
3. Check PM2 has our app: `pm2 list`
4. Save the PM2 config: `pm2 save`
5. To start/stop: `pm2 start dayBreeze` / `pm2 stop dayBreeze`