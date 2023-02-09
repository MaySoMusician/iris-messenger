# Iris Data Saver Preview

- All `iris.to` are replaced to my custom domain
- The app (might) not automatically fetch Like event (kind:7 etc.)

---

<i><b>Note 23.12.2022:</b> Heavily under construction:
started integrating <a href="https://github.com/nostr-protocol/nostr">Nostr</a> this week.</i>

# Iris

Iris is like the social networking apps we're used to, but better.

- No phone number or signup required. Just type in your name or alias and go!
- Secure: It's open source. Users can validate that big brother doesn't read your private messages.
- Available: It works offline-first and is not dependent on any single centrally managed server.

![Screenshot](screenshot.png)

## Use

Browser application: [iris.to](https://iris.to) [![Netlify Status](https://api.netlify.com/api/v1/badges/1181c85b-b6af-4ce7-bc74-c484bff631e5/deploy-status)](https://app.netlify.com/sites/iris-messenger/deploys)

- No installation required
- Progressive web app
  - Use offline
  - Save as an app to home screen or desktop

## Develop

```bash
# install dependencies
yarn

# serve with hot reload at localhost:8080
yarn dev

# build for production with minification
yarn build

# test the production build locally
yarn serve

# run tests with jest and enzyme
yarn test
```

[iris-lib](https://github.com/irislib/iris-lib) is a core part of the application. You can clone it and run `yarn link` in the iris-lib directory. Then run `yarn link iris-lib` in the iris-messenger directory.

## Privacy

The application is an unaudited proof-of-concept implementation, so don't use it for security critical purposes.

## Contact

Join our [Telegram](https://t.me/irismessenger) (will be moved onto Iris when group chat is ready).

---

<a href="https://opencollective.com/iris-social/donate" target="_blank"><img src="https://opencollective.com/iris-social/donate/button@2x.png?color=blue" width=200 /></a>

<p><sub>BTC: bc1qypfnmcgf9cdxcw307u20qzdyxf66egdgj0ljze</sub></p>
