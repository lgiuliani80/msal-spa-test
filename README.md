# How to run

* Configure the following redirect URIs in B2C:
  * `http://localhost:8080/msal-popup-demo.html`
  * `http://localhost:8080/msal-redirect-demo.html`   --> THIS WORKS ONLY WHEN NOT RUNNING IN A iframe

* Run the following commands in the terminal:

      npm install -g httpserver
      httpserver -p 8080

* Open the browser and navigate to [http://localhost:8080/index-popup.html](http://localhost:8080/index-popup.html)
