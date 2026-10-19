### Hi, I'm Noor 👋

Computer Science undergraduate at George Mason University ('29) focused on systems programming in C, POSIX networking and concurrency, and AI developer tooling.

### 🛠 Tech Stack

* **Languages:** C, Java, Python, JavaScript, Bash
* **Systems & Networking:** POSIX system calls, sockets, multithreading (pthreads, mutexes), AddressSanitizer / ThreadSanitizer
* **Tools:** Linux/Unix, macOS, Makefiles, Git, Vim, Maven, JUnit, Docker, Ollama

### 📌 Featured Projects

* **[llm-caching-proxy](https://github.com/noorhusaan302-png/llm-caching-proxy)**
  Multithreaded C proxy that sits in front of a local LLM (Ollama) and caches prompt/response pairs in a mutex-protected LRU cache, so repeated prompts are answered from memory in under a millisecond instead of re-running the model. Includes a test suite with a mock LLM server.

* **[ast-security-reviewer](https://github.com/noorhusaan302-png/ast-security-reviewer)**
  Java static analyzer that parses source into ASTs with JavaParser to find SQL injection and hardcoded secrets, asks a local LLM (Qwen 2.5 Coder via Ollama) for fixes, and re-parses every suggested fix to reject invalid Java. Runs as a CLI or an HMAC-verified GitHub webhook; 37 JUnit tests.

* **[enterprise-c-proxy](https://github.com/noorhusaan302-png/enterprise-c-proxy)**
  Multithreaded HTTP forward proxy in C with an LRU + TTL response cache, per-client token-bucket rate limiting, subdomain-aware domain blacklisting, and a JSON `/stats` endpoint. 14 integration tests, also run under ASan and TSan.

* **[Noorshell](https://github.com/noorhusaan302-png/Noorshell)**
  Unix shell written from scratch in C: process control with `fork`/`execvp`/`waitpid`, pipes and I/O redirection with `pipe`/`dup2`, background jobs reaped with non-blocking `waitpid(WNOHANG)`, and built-in `cd`/`exit`.

### 📬 Connect

* LinkedIn: [noor-ul-hassan](https://www.linkedin.com/in/noor-ul-hassan-84a553383)
* Email: [mbutt21@gmu.edu](mailto:mbutt21@gmu.edu) / [noorhusaan302@gmail.com](mailto:noorhusaan302@gmail.com)
