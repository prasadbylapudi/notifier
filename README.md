# Notifier
A python tool that monitor system services and send notification about the status of the services.

### 1. Run example Node.js service in terminal.

```bash
$ node app.js
```

### 2. Now run Notifier along side in another terminal and stop the node service to see the notification.

```bash
$ python3 notifier.py
```

### 3. To see dashboard and add your configurations via form.
 #### Navigate to *django* folder and run below command

  ```bash
  $ python3 manage.py runserver
  ```
  Access *http://127.0.0.1:8000/*

#### You can also add your services and twilio configurations in config.json manually.


