
  _______                     _____ _                                 
 |__   __|                   |  __ (_)                                
    | | ___  __ _ _ __ ___   | |__) | _ __   ___  ___ ___  _ __   ___ 
    | |/ _ \/ _` | '_ ` _ \  |  ___/ | '_ \ / _ \/ __/ _ \| '_ \ / _ \
    | |  __/ (_| | | | | | | | |   | | | | |  __/ (_| (_) | | | |  __/
    |_|\___|\__,_|_| |_| |_| |_|   |_|_| |_|\___|\___\___/|_| |_|\___|
                                                                      
                                                                      
    ----------------------------------------------------------------- 


Hi there! Welcome to Cloud9 IDE!

To get you started, create some files, play with the terminal,
or visit http://docs.c9.io for our documentation.
If you want, you can also go watch some training videos at
http://www.youtube.com/user/c9ide.

Happy coding!
The Cloud9 IDE team


Connect to CouchDB Futon C9:
https://pinecone-bryndlir.c9users.io/_utils/



Connect to Garak

group: pinecone
server to be used for second year project and for couchdb
os: ubuntu server

ip:  129.16.155.40 
dns: GARAK.SKIP.CHALMERS.SE

username: pinecone
password: hR5FdE2Q


//Running couchbeam

1) erl -pa ebin -pa deps/*/ebin

2) application:ensure_all_started(couchbeam).
