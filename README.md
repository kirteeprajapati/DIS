### DIS Assignment 1

# Socket Programing in C to Print average of 3 numbers

This Program ask for 3 numbers from the client and prints the average of them

**Step 1.** Start with Server.C and client.C file and generate there outputs with the command in 2 different terminal for clearity.

### Get Output files

```bash
  gcc Client.c -o Client
  gcc Server.c -o Server
```

**Step 2** Use any port no between 8080 to 9898 to start your server

```bash
./Server 9898
```

**Step 3.** Check your Loopback Running port

```bash
ifconfig
```

**step 4** Connect Client with server

```bash
./Client 127.0.0.1 9898
```

Now your good to go to get your average calculated.

## Screenshots

![VS Code and Terminal image](https://github.com/kirteeprajapati/DIS/blob/main/Screenshort/Code%20and%20terminal.png)

![Terminal image](https://github.com/kirteeprajapati/DIS/blob/main/Screenshort/Terminal.png)

