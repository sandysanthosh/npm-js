# NodeJs-Basics

## node packet manager

##package:

ls node_modules/unserscore/

      npm install
      npm start
      npm -h
      npm install -h
      npm install help
      npm help-search remove
      npm apihelo prune
      npm help prune

### Creating a package.json:

          ->3rd party package
          ->for users

### Json:

            track depenceices
            create script

                  npm init
                  npm init -y    ->default answer

                  npm set init-author-name 'Joe Eames'
                  npm set init-license 'MIT'
                  npm get init-author-name
                  npm config delete init-author-name
                  npm config set
                  npm config get
                  ls ~/.npmrc


### install packages:

                  npm install lodash
                  npm install angular
                  npm install express
                  npm install ion-drive
                  npm install lodash -S----/short cut to start i-install s-start
                  npm install karma --save-dev  or karma-D //shorcut to only developemnt not production
                  cat package.json

### listning install package:

                    npm list      // displau all the install package with depencies
                    npm list --depth 1
                    npm list --global true
                    npm list --global true --depth 0
                    npm list --global true
                    npm list --depth 0 --long true
                    npm list --depth 0 --json true  // display the details in json format
                    npm list --depth 0 parseable true
                    npm list --depth 0 --prod true
                    npm ls |  la | ll

### Global package:

          npm i gulp -g   // install package 
          npm list -g --depth 0    //this is install a package globally

### remove a package:

              npm uninstall underscore     
              cat package.json
              npm uninstall unserscore --save     //will remove with depencency
              npm un unistall
              npm r underscore -g  //remove or uninstall globally
              npm i underscore

### install specific version:

              npm i underscore@1.8.2
              npm i underscore">1.8.2   // past greater then equalto the same vesion
              npm i underscore">1.8.2 < 1.4.0
              npm i underscore@1.8.8
              npm i express@"3"
              npm i underscore@1.8.2 --save --save--exact

### install exisinting dependencies:

        npm rm unserscore
        npm i


### updating the package:

          cat package.json
          npm list --depth 0     //last update command
          npm update
          npm i underscore --save
          npm update --dev
          npm update --prod
          npm update underscore    //update the unserscore
          npm update -g gulp      //update globally gulp



### node.js:

                  creating networking and server-side applcations
                  install:
                  buffer
                  steaming
                  windows
                  repl
                  package manager
                  callbacks
                  event loop
                  os
                  path
                  query string
                  cryptography
                  debugger
                  URL
                  DNS
                  NET
                  UDP 
                  progress
                  child process
                  buffer
                  streams
                  file systems
                  web modules
                  cluster



### REPL:

          READ --reads the user input
          EVAL --takes data structures
          PRINT --prints the result
          LOOP  --ctrl-c twice

### REPL COMMANDS:

            ctrl + c      - current command
            ctrl + c twice-terminates
            ctrl + d      -node tepl
            up/down keys  -it is used
            tab keys      -list of current command
            .help  -list of all commands
            .break -exit from multi-line
            .clear -exot from multi-line
            .save filename  -current node repl session
            .load filename  -it is used to load file content


                node -v
                node --version

### help:

              node-h
              node -p script
              node -i     // add + mul + sub + divison


### os:

              os.arch()
              os.cpus()
              os.endianness()
              os.freemem()

### Node.js Timer:

                global function
                dont require()

### set timer function():

                setImmediate()
                setInterval()
                setTimeout()

### dns:

              dns.getServers()
              
       
<a href="http://starwalt.in/Blogs/index.html">Follow us on Blog</a>

