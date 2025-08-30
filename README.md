# 🕷️ C++ Web Crawler (Menu-Driven CLI)

A simple **multi-threaded web crawler** implemented in C++ to demonstrate **OOP, concurrency, and CLI interaction**.  
The crawler starts from a seed URL, explores links up to a given depth, and allows the user to interactively control it via a menu.

---

## 🚀 Features
- Menu-driven **interactive CLI**.
- **Multi-threaded crawling** using `std::thread`, `std::mutex`, and `std::condition_variable`.
- **Thread-safe URL queue** for managing tasks.
- **Visited URL tracking** to avoid duplicate crawling.
- Depth-limited crawling (prevent infinite loops).
- **Export results** to a text file (`results.txt`).
- Options to **pause, resume, and stop** crawling.



