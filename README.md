# Angular Material Firebase Scaffolding

Scaffolding to develop apps based on firebase using angular material

## How to run

1. Install deps

```angular2html
npm i
```

2. Generate environments to provide firebase config
```
ng generate environments
```

2.1 Navigate to `src/environments/environments.development.ts` and add that config.

```

export const environment = {
  production: false,
  firebase: {
    apiKey: "your-api-key",
    authDomain: "your-auth-domain.firebaseapp.com",
    projectId: "your-project-id",
    storageBucket: "your-storage-bucket.appspot.com",
    messagingSenderId: "your-messaging-sender-id",
    appId: "your-app-id"
  }
};

```

3. Run the app

```angular2html
npm run start
```

