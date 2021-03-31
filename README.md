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

- [x] Add dotenv to package.json
- [x] Add concurrently to package.json
- [x] Install nodemon and concurrently
- [x] Update root package.json w/ new scripts (`npm dev`)
- [x] Check what the react-app is trying to do; what's the server endpoint attempting to getting hit? Why isn't it working? (hint: proxying)
