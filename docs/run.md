# Running the application
> You can find developer-specific instructions in the [developer install instructions](install-dev).

To run the application, simply use the npm start script:
```
npm start
```

Advanced users may also set the `NODE_ENV` environment variable to specify which configuration file is loaded with the application. This value is `production` by default:
```
NODE_ENV=dev npm start
```

_You can read more about configuring your environment on [this page](configure-environment)._

The application will take a while to start up on the first boot, as it has various initialisation tasks to perform. Subsequent boots will be much quicker.