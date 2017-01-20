# mac-setup-defaults-write

$ mkdir mac-setup && cd mac-setup
$ npm init --yes && npm install mac-setup-defaults-write --save
$ cp node_modules/mac-setup-defaults-write/defaults-write.json.example defaults-write.json
$ // Edit defaults-write.json
$ mac-setup-defaults-write test-pwd
$ mac-setup-defaults-write run
