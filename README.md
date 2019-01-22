# SystemD Desktop Wallet

### Linux Setup
#### Prerequisites
- Install Git and add it to System path
- Install Node v4.9.1
#### Instructions
- Fork and clone the systemd-desktop-wallet repository
  - `git clone https://github.com/VokezOfficial/systemd-desktop-wallet.git`
- In the systemd-desktop-wallet directory, make a copy of the `config_example.js` file and name it `config.js`
- Run `npm install`
- If npm install fails in middle, run `npm install` again time to complete the installation process 
#### Dev Mode
- Run `gulp` in root directory to start up dev mode (this may not be funtional)
#### Build
- Run `gulp packages` in your command line to compile the production ready client executable
- Your desktop client is in the `packages/SystemD-Desktop-Wallet-1.5.1` directory
- Modify the `platforms` array in gulpfile.js (~line 350) to set the platforms targeted for compilation
