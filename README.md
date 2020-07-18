# GAIN3D.TokenExchange
Ethereum Token exchange

dependences needed for project
-Metamask
-Ganache
-atom w/ ethereum language package
-choco and npm installed
-react installed
-the truffle framework installed
-Micrsoft Visual Studio 2015 (C++ package) 


process to start up development enviroment

Open Ganache and start a blockchain up.

Open powershell and navigate to the cloned Repo folder.
type "npm install"
type "truffle migrate --reset"
type "truffle exec ./scripts/seed-exchange.js"

Open another powershell window and navigate to the Repo folder
type "npm start"

once the React web server is up and running you will need to import your tuffle accounts and manually connect to the webpage 
