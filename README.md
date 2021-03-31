# Hella Hungry (C41)

## Installation Instructions

- `git clone` this repo
- `cd` into it.
- `npm install`
- `cd client && npm install`

- Copy over a new `.env` file from `.env.sample`: `cp .env.sample .env`
- In `.env`, fill in the `YELP_API_KEY` value with the API key from Yelp.com.

---

### To do

- [x] Add dotenv to the root directory package.json
- [x] Add your environment variables in your `.env` file.
  - NOTE: You won't see the `.env` file on this GitHub, because it's a bad look to make that file visible. That's why I included the `.env.sample` file, so you can see how you can model your own `.env` file.
- [x] Make references to whatever environment variables you need in your `server.js` file by `process.env`
- [x] Add concurrently to package.json
- [x] Install nodemon and concurrently
- [x] Update root package.json w/ new scripts (`npm dev`)
- [x] Check what the react-app is trying to do; what's the server endpoint attempting to getting hit? Why isn't it working? (hint: proxying)
- [x] Add a proxy to `/client/package.json` set to our backend localhost at localhost:8080
