# dev-todo

A to-do app. Add a task, mark it in progress or done, and the list updates live.

Built in 2021. Live at [todoapp-f509b.web.app](https://todoapp-f509b.web.app/).

A React app on Firebase. Tasks live in a Firestore `todos` collection and the list re-renders on each snapshot. The UI uses Material UI.

## Run it

```bash
npm install
npm start
```

It reads Firebase config from `src/firebase_config.js`, which ships with a placeholder API key. Add your own Firebase web config there and enable Firestore.
