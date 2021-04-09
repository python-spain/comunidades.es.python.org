# comunidades.es.python.org PoC

This provides a proof of concept for the [comunidades.es.python.org](https://comunidades.es.python.org) site. It's hosted in Github and uses an scheduled Github Action to fetch, parse and store all new Meetup events in [`calendarEntries.json`](src/calendarEntries.json).

To add new Meetup groups, just create a new entry in [`meetups.json`](src/meetups.json). In the next scheduled CI exectution the app will be populated with their events automatically!

## Development

If needed install globally parcel with:

```
yarn global add parcel-bundler`
```

### Local development

Start dev server with:

```
yarn start
```

### Build

```
yarn build
```
