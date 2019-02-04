### Basic Instructions
1. Setup PI UFL Connector with the these [settings](PI%20Connector%20for%20UFL%20Data%20Source.md) and this ini file: [ttv-UFL-Connector.ini](ttv-UFL-Connector.ini)
2. Setup the SSL certificate per this OSIsoft KB: [KB01421](https://techsupport.osisoft.com/Troubleshooting/KB/KB01421)
   - You cannot use a self-signed or private certificate.  You must use a external / public trusted certificate
   - If you need a free certificate, you may want to try Let's Encrypt
3. Create a smart app using [toPIUFL.groovy](toPIUFL.groovy)
### Known Issues
1. The UFL configuration only accepts real values.  This means that the switch will error out as it sends off and on.  The next version of the ULF configuration and smart apps will address this issue.
