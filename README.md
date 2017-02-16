# SE2Lab_Exam_2017_02

fatal: 'heroku' does not appear to be a git repository
fatal: Could not read from remote repository.

è l'errore che mi da qunado prevo a fare git push heroku master dopo aver fatto
heroku create

errore npm start

info it worked if it ends with ok
1 verbose cli [ '/usr/local/node-v4.6.1/bin/node',
1 verbose cli   '/usr/local/bin/npm',
1 verbose cli   'start' ]
2 info using npm@2.15.9
3 info using node@v4.6.1
4 verbose stack Error: Failed to parse json
4 verbose stack Unexpected token 'i' at 7:27
4 verbose stack     "start": "node server\index.js"
4 verbose stack                           ^
4 verbose stack     at parseError (/usr/local/node-v4.6.1/lib/node_modules/npm/node_modules/read-package-json/read-json.js:390:11)
4 verbose stack     at parseJson (/usr/local/node-v4.6.1/lib/node_modules/npm/node_modules/read-package-json/read-json.js:79:23)
4 verbose stack     at /usr/local/node-v4.6.1/lib/node_modules/npm/node_modules/read-package-json/read-json.js:48:5
4 verbose stack     at /usr/local/node-v4.6.1/lib/node_modules/npm/node_modules/graceful-fs/graceful-fs.js:78:16
4 verbose stack     at FSReqWrap.readFileAfterClose [as oncomplete] (fs.js:380:3)
5 verbose cwd /home/marco.arnoldi/Desktop/SE2Lab_Exam_2017_02
6 error Linux 4.4.0-36-generic
7 error argv "/usr/local/node-v4.6.1/bin/node" "/usr/local/bin/npm" "start"
8 error node v4.6.1
9 error npm  v2.15.9
10 error file /home/marco.arnoldi/Desktop/SE2Lab_Exam_2017_02/package.json
11 error code EJSONPARSE
12 error Failed to parse json
12 error Unexpected token 'i' at 7:27
12 error     "start": "node server\index.js"
12 error                           ^
13 error File: /home/marco.arnoldi/Desktop/SE2Lab_Exam_2017_02/package.json
14 error Failed to parse package.json data.
14 error package.json must be actual JSON, not just JavaScript.
14 error
14 error This is not a bug in npm.
14 error Tell the package author to fix their package.json file. JSON.parse
15 verbose exit [ 1, true ]