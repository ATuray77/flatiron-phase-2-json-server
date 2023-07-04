## Back-end json-server deployed on render.com
https://new-json-server.onrender.com

## Setup

Fork and clone this repo. Then install the dependencies by running:

```sh
npm install
```

## Running the Server Locally

To run your server in development mode, run:

```sh
npm run dev
```

While running in development mode, the server will re-load any time you make
changes to the `db.json` file, so you can test our your seed data.

While your server is running, you can make requests to
[http://localhost:3000](http://localhost:3000). Check it out in the browser to
make sure your server works!

## Deploying

Free services like Render make it simple to deploy your Node server. Render also
works nicely with Rails, which you'll learn later in the program.


### Making Updates

Since Render deployment integrates with your GitHub repo, you can easily deploy
changes to your database. First, commit and push your code up to GitHub:

```sh
git add .
git commit -m "Updated database"
git push
```
