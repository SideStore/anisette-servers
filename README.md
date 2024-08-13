# anisette-servers

This is a central location for all officially recommended Anisette servers for use in SideStore.

## Adding your own Anisette Server

To add your own Anisette server to the official list, your Anisette server must meet the following requirements:

1. This will be a long term server. We don't want servers that will only be up for a short period of time.
2. Uptime is important, if you cannot guarantee high uptime, please don't request for your server to be added.
3. Your server should be an Anisette V3 server. We recommend [SideStore/omnisette-server](https://github.com/sidestore/omnisette-server) or [Dadoum/anisette-v3-server](https://github.com/dadoum/anisette-v3-server).
4. HTTPS is recommended, but not necessary.

To help increase the likelihood of your anisette server being listed, it is suggested that you tell us what anisette server you are running, and where it is being ran, for example: the cloud, your house, a workplace.

If your server meets these requirements, please do the following:

1. Fork the repo, and open it in a code or text editor of some sort.
2. Modify the `servers.json` file to include your server in the same format as the rest of the servers.
3. Commit your changes to your fork.
4. Make a Pull Request on the official repo requesting that your Anisette server is added.
