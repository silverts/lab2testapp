# lab2testapp
lab2 crash and burn

### Pushing app to Cloud Foundry
cf push lab2testapp

### Endpoints
- `/`: a simple landing page displaying the index and uptime
- `/env`: displays environment variables
- `/exit`: instructs the app to exit with status code 1
- `/index`: returns the application index
- `/port`: returns the local port the request was received on
