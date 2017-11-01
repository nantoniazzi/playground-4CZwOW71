@[DEBUG]({stubs: [debug.sh], command: 'bash /project/target/debug.sh'})

@[RUN]({stubs:[Answer.js, test.js, test.html], command: 'bash /project/target/run.sh'})

@[VALIDATE]({stubs:[Answer.js, test.js, test.html], command: 'bash -c "/project/target/validate.sh \"should add a new unchecked item at the end of the list\"; echo \"hello\""'})
