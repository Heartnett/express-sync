# Express-sync
Use an express server with browser-sync (without gulp)


#1 - Install express and browser-sync modules

    `npm install`



#2 - Launch the script 'npm start'

    `node app & browser-sync start --proxy 'localhost:9000' --files 'public'`

#3 - Modify style.css and save to test browser-sync

    `body {
        background: blue;
        color: black;
    }`

    Then you can see modifications without reload your browser