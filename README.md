# @dungeoneer-io/nodejs-utils

        Published to NPM as @dungeoneer-io/nodejs-utils


- Common utilities used by @dungeoneer-io when writing NodeJS processes
- { `getDb` and `initDb` } for connecting to a mongodb at env variable constring `ZEPHYR_BLIZZDATA_MONGO_CONSTRING`
- { `queueUntilResolved` } allows multi-threaded processing of async jobs
- { `lambdaTry200Catch500` } gives a standard framework to Lambda invocations
- { `sendDiscordNotification` } sends a message to Discord webhook found at env variable `DISCORD_NOTIFICATION_WEBHOOK`
- { `connectToBlizzard` } uses env variables `ZEPHYR_BLIZZARD_API_KEY` and
`ZEPHYR_BLIZARD_API_SECRET` to connect to BlizzAPI 



## Environment Variables
When implementing this project, you'll want to include env variables if you want to use Mongo, Blizzard, or Discord Notifications. Try installing `dotenv` to create the variables locally to the project

```
DIO_MONGO_CONSTRING="VALUEHERE"
BLIZZARD_API_KEY="VALUEHERE"
BLIZZARD_API_SECRET="VALUEHERE"
DISCORD_NOTIFICATION_WEBHOOK="(optional)"
```