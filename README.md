# Skyport Panel
## Overview
An open source project powered by Docker for managing applications, game servers and more. Ditch Pterodactyl or PufferPanel and fly higher with a panel that isn't named after a creature.

> [!WARNING]
> Skyport is not ready for production use, nor does it have a stable and completed release yet.


## Installation
b1:
`sudo mkdir -p /etc/apt/keyrings`

b2:
`
1. Clone the repository:
`git clone https://github.com/MoonlightPanel/skyport.git`
`sudo apt install -y nodejs git`
`cd skyport`

3. Install dependencies:
`npm install`

4. Seed images and create a user:
```
npm run seed
npm run createUser
```

4. Start the Panel:
`node . # or use pm2 to keep it online`

## Configuration
Edit the `config.json` file in the root directory to set up the application settings including the database connection and port.

## Usage
Navigate to `http://localhost:<port>` to access the Skyport Panel. Log in with your user credentials to manage and view instances.

## Contributing
Contributions are welcome. Please fork the repository and submit pull requests with your proposed changes.

## License
(c) 2024 Matt James and contributors. All rights reserved. Licensed under the MIT License.
