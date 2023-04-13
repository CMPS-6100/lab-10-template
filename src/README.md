# Compilation

Once you add multithreading to your client and server,
to compile `client.c` and `server.c`:

```
$ gcc -pthread server.c -o server
$ gcc -pthread client.c -o client
```