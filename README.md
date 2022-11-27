## Zoom V2

Zoom integration enables agents to schedule instant Zoom meetings with customers from Freshdesk ticket.

### Files and Folders

    .
    ├── README.md                 A file for your future self and developer friends to learn about app
    ├── app                       A folder to place all assets required for frontend components
    │   ├── index.html            A landing page for the user to use the app
    │   ├── scripts               JavaScript to place files frontend components business logic
    │   │   └── app.js
    │   └── styles                A folder to place all the styles for app
    │       ├── images
    │       │   └── icon.svg
    │       └── style.css
    ├── config                    A folder to place all the configuration files
    │   └── iparams.json
    └── manifest.json             A JSON file holding meta data for app to run on platform

### Installation steps of APP
1. To integrate Zoom in your Freshdesk account, get ‘Zoom V2’ app from Marketplace and click ‘Install’.
2. Now, you can view your ‘Zoom V2’ widget right below the ticket sidebar in the ticket details page.
3. Click on ‘Authorize’ button and enter your Zoom login credentials.
4. Click on Zoom V2 widget and click on ‘Generate meeting URL’ to generate and copy zoom meeting URL in the ticket.
5. Now, click on the meeting URL from the widget to start your zoom meeting.
6. To generate a new meeting URL in the same ticket, click on ‘Regenerate meeting URL’.

### Description of the APP
Integrating Zoom with Freshdesk Mint UI improves agent’s communication with the customer by scheduling instant Zoom meeting. Agents can use their Zoom login credentials and host concurrent Zoom meetings with customers in your Freshdesk account.

Zoom integration allows support agents to resolve issues faster through direct interaction with the customer:
    * Generate Zoom meeting URL in ticket details page and send it to customer
    * Multiple agents in an organization can host concurrent zoom meetings
    * Use audio, video, and screen sharing features for a better understanding of customers’ issue
    * Request remote control of customers’ screen


Useful links:
https://support.zoom.us/hc/en-us/articles/201362673-Request-or-Give-Remote-Control?zcid=1231
https://support.zoom.us/hc/en-us/articles/203741855-Cloud-Recording

### Changes done in this version
Oauth config for settings page was dynamic
