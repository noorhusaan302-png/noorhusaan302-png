### Hi, I'm Noor 👋

Computer Science undergraduate at George Mason University ('29) focused on low-level systems programming in C, POSIX networking and concurrency, and AI developer tooling.

### 🛠 Tech Stack
- **Languages:** C, Java, Python, JavaScript, Bash
- **Systems & Networking:** POSIX System Calls, Network Sockets, Multi-threading (pthreads, mutexes), AddressSanitizer / ThreadSanitizer
- **Developer Tools:** Linux/Unix, macOS, Makefiles, Git, Vim, Maven, JUnit, Docker, Ollama

---

### 📌 Featured Projects

- **[llm-caching-proxy](https://github.com/noorhusaan302-png/llm-caching-proxy)**  
  Multithreaded C proxy for local LLM inference (Ollama). A mutex-protected LRU cache answers repeated prompts from memory in under a millisecond instead of re-running the model. Tested against a mock LLM server.

- **[ast-security-reviewer](https://github.com/noorhusaan302-png/ast-security-reviewer)**  
  Java static security analyzer that parses Abstract Syntax Trees (AST) to find SQL injection and hardcoded secrets, then asks an on-device LLM via Ollama (Qwen 2.5 Coder) for fixes and re-parses each one to reject invalid Java. Runs as a CLI or an HMAC-verified GitHub webhook, with 37 JUnit tests.

- **[enterprise-c-proxy](https://github.com/noorhusaan302-png/enterprise-c-proxy)**  
  Multithreaded HTTP forward proxy built in C, with an LRU + TTL response cache, per-client token bucket rate limiting, subdomain-aware domain blacklisting, and a live JSON `/stats` endpoint. 14 integration tests, also run under ASan and TSan.

- **[Noorshell](https://github.com/noorhusaan302-png/Noorshell)**  
  Custom POSIX Unix shell implemented from scratch in C. Features process lifecycle control (`fork`, `execvp`, non-blocking `waitpid` with `WNOHANG` to reap background jobs), file descriptor piping (`pipe`, `dup2`), I/O redirection, and built-in commands.

---

### 📬 Connect
- **LinkedIn:** [noor-ul-hassan](https://www.linkedin.com/in/noor-ul-hassan-84a553383)
- **Email:** mbutt21@gmu.edu / noorhusaan302@gmail.com
