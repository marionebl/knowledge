# Terminal

## Recordings

* [asciinema](https://asciinema.org/) - Share terminal sessions
* [pv](https://linux.die.net/man/1/pv) - Simulate typing in a shell script

```sh
echo "npx create-react-app my-app" | pv -qL $[10+(-2 + RANDOM%5)]
```
