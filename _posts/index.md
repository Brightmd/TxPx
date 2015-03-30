---
---
### Robust Process Management

TxPx is a system for spawning and killing processes from a Twisted
application server. It handles such details as:

- Wrapping a long-running process' lifetime in a deferred without losing
  the ability to communicate with it in realtime
- Logging output to a console, or an I/O stream connected to a parent
  process
- Simultaneously communicating with a parent process while outputting
  stderr to a log
- Building either byte-by-byte or line-buffered protocols without losing
  the benefits of separate I/O streams
- Keeping a list of child processes running with an easy way to
  terminate them when needed

```
$ git clone https://github.com/Brightmd/TxPx.git
```

Created by @BrightMD.
