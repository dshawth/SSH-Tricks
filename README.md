# SSH Tricks

**The Guide for kids who can SSH -L -D & -R good, but want to learn to pivot & chain good too!**

*Original Authors: Daniel Hawthorne, Matthew Green, Adam Schinder*

**Note: Below is a work in progress, please see the pptx for now.**  

## The Basic Manuals

#### `ssh`

```
  -L (Local) 🡒 Bind a local port to be forwarded to a remote host/port.
  -D (Dynamic) 🡒 Necessary for services like ftp that use different return connections.
  -R (Reverse) 🡒 Bind a remote to local to forward a service over ssh.
  -N 🡒 Do not execute a remote command. Useful for forwarding ports. Leave shell open.
  -T 🡒 Disable pseudo-tty allocation. For cases that do not allow virtual terminal.
  -p PORT 🡒 Specify a port o connect on. To override port 22.
```

#### `sshpass`

```
  -p PASSWORD 🡒 Send a password to ssh without the extra prompt.  Saves time.
```

#### `proxychains`

- Uses port 9050 by default ot execute local binaries through ssh tunnels.

## Single-Pivot


## N-Pivot-Local


## Single-Pivot Dynamic


## N-Pivot Dynamic



## Single-Pivot Reverse


# N-Pivot Reverse


## Useful Commands


## TODO

- Add ssh-copy-id and warning about leaving info behind
- Add ssh-keygen and warning 