# Configure Ekylibre to test Pasteque

Launch server with this command to permit access from elsewhere in LAN:

  TENANT=demo rails s -b YOUR.OWN.IP.ADDRESS -p 8080

After configure Pasteque Android with :

  * Address: YOUR.OWN.IP.ADDRESS:8080/pasteque/v5
  * Account: admin@ekylibre.org
  * Password: 12345678

You need to disable HTTPS support.
