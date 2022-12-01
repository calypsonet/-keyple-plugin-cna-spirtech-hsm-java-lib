# Spirtech HSM Example

This example make use of the Spirtech HSM plugin with a Keyple Calypso Extension library. They demonstrate the main features of the library's
API. 

* Card Authentication (certified reading of a file record): 
  * Set up a card transaction using the Card Resource Service to process a basic Calypso Secure Session.
  * Real mode with PC/SC reader for the card and Spirtech HSM for the SAM [`Main_CardAuthentication_PCSC_HSM.java`]
