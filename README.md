# ⚡ Assembly Web Server Demo

An interactive simulation showing how a web server written in pure x86-64 Assembly language works.

**🎮 [Live Demo](https://Darkness1202.github.io/assembly-web-server-demo/)**

## What is this?

This is an interactive browser-based simulation that demonstrates:
- How an HTTP web server works at the Assembly language level
- Real-time server logs showing Linux syscalls
- A retro terminal-style search interface
- The relationship between Assembly code and web servers

## Features

- ⚡ **Real-time simulation** of Assembly web server
- 🖥️ **Split-screen view** - server terminal + browser
- 📡 **Interactive controls** - start, stop, simulate requests
- 🎨 **Retro aesthetic** - Matrix-style green terminal
- 🔍 **Working search** - actually redirects to Google

## How to Use

1. Click **START SERVER** to boot up the server
2. Watch the syscalls execute in real-time
3. Click **SIMULATE REQUEST** to see HTTP requests
4. Use the search box to try actual searches
5. Click **STOP SERVER** when done

## What You'll See

### Server Terminal (Left)
Shows the actual Linux syscalls:
- `socket()` - Creating TCP socket
- `bind()` - Binding to port 8080
- `listen()` - Listening for connections
- `accept()` - Accepting client connections
- `read()/write()` - HTTP communication

### Browser View (Right)
The actual webpage served by the Assembly server with:
- Search functionality
- System information
- Assembly opcodes reference
- Request counter

## Educational Value

Learn about:
- x86-64 Assembly programming
- Linux system calls
- Socket programming
- HTTP protocol
- How web servers actually work

## Tech Stack

Built with pure HTML, CSS, and JavaScript - no frameworks!

## GitHub Pages Setup

1. Fork this repository
2. Go to Settings → Pages
3. Source: Deploy from branch `main`
4. Your demo will be live at `https://yourusername.github.io/assembly-web-server-demo/`

## License

MIT License - See [LICENSE](LICENSE)

---

<p align="center">
Made with ⚡ and Assembly<br>
<sub>Educational simulation of low-level web programming</sub>
</p>
