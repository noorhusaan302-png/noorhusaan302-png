### Hi, I'm Noor 👋

CS student at George Mason University ('28) working on systems programming in C, backend Java, and local LLM tooling. I also do undergrad research at GMU on AI model reliability, running models on the school's GPU cluster.

**Open to Summer 2027 software engineering internships.**

🥊 **Founder, [Helios Boxing](https://heliosboxing.com):** my own boxing gear brand. I run the business and its online store (WordPress + WooCommerce).

### 🚧 Currently Building
- **GPT-2 inference engine** – built from scratch in C++ and CUDA, with custom GPU kernels, a KV cache and tokens/sec benchmarks.

### 🛠 Tech Stack
- **Languages:** C, Java, Python, SQL, JavaScript, Bash
- **Systems & Networking:** POSIX System Calls, Network Sockets, Multi-threading (pthreads, mutexes), AddressSanitizer / ThreadSanitizer
- **Developer Tools:** Linux/Unix, macOS, Makefiles, Git, Vim, Maven, JUnit, Docker, Ollama

---

### 📌 Featured Projects

- **[llm-caching-proxy](https://github.com/noorhusaan302-png/llm-caching-proxy)**  
  Multithreaded C proxy for local LLM inference (Ollama). A mutex-protected LRU cache answers repeated prompts from memory instead of re-running the model, so 20 concurrent calls went from 20s to 1s. Tested against a mock LLM server.

- **[ast-security-reviewer](https://github.com/noorhusaan302-png/ast-security-reviewer)**  
  Java static security analyzer that parses Abstract Syntax Trees (AST) to find SQL injection and hardcoded secrets, then asks an on-device LLM via Ollama (Qwen 2.5 Coder) for fixes and re-parses each one to reject invalid Java. Runs as a CLI or an HMAC-verified GitHub webhook, with 37 JUnit tests.

- **[enterprise-c-proxy](https://github.com/noorhusaan302-png/enterprise-c-proxy)**  
  Multithreaded HTTP forward proxy built in C, with an LRU + TTL response cache, per-client token bucket rate limiting, subdomain-aware domain blacklisting, and a live JSON `/stats` endpoint. Served 12,500+ cached requests with 0 errors in testing, with 14 integration tests also run under ASan and TSan.

- **[Noorshell](https://github.com/noorhusaan302-png/Noorshell)**  
  Custom POSIX Unix shell implemented from scratch in C. Features process lifecycle control (`fork`, `execvp`, non-blocking `waitpid` with `WNOHANG` to reap background jobs), file descriptor piping (`pipe`, `dup2`), I/O redirection, and built-in commands.

---

### 📬 Connect
- **Portfolio:** [noorhusaan302-png.github.io/noor-portfolio](https://noorhusaan302-png.github.io/noor-portfolio/)
- **LinkedIn:** [muhammad-noor-ul-hassan-butt](https://www.linkedin.com/in/muhammad-noor-ul-hassan-butt-84a553383/)
- **Email:** mbutt21@gmu.edu / noorhusaan302@gmail.com
