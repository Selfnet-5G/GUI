# SELFNET Graphical User Interface

The GUI is the main interaction point between SELFNET’s operators and SELFNET
framework. SELFNET’s GUI allows studying and managing the variation and status of SELFNET
controlled environment. Authorized users are able to see the current status of
SELFNET monitoring system’s KPIs, messages and symptoms.
Users are able to audit SELFNET’s autonomous decisions allowing the
understanding of autonomously taken actions, its trigger causes and the validity and
success rate of its actuation. The GUI also provides a view on how the elements
are distributed among the network allowing SELFNET operators to study the network
topology and pinpoint the physical and virtual locations where problems are
occurring.

All information displayed by the GUI, as well as all the features provided by it, use
SELFNET API broker services. Since the API broker requires every request to
contain an authentication and authorization token, the first and only screen available
for non-authenticated users, allows to acquire the authentication token by specifying
a username, password.


## Installation

In order to install the SELFNET-GUI the 

### Requirements

In order to successfully execute SELFNET-GUI the following requirements are needed:

* [SELFNET-NBI](https://github.com/Selfnet-5G/NBI), SELFNET-GUI uses SELFNET-NBI as the only source of information.

* Node and [http-server](https://www.npmjs.com/package/http-server) to run the GUI
```sh
npm install http-server -g
```


## Usage

Start the http-server on SELFNET-GUI location
```sh
http-server
```


## License

The SELFNET-GUI is published under Apache 2.0 license. Please see the LICENSE file for more details.