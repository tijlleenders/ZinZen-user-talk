Here's what we've been up to the last two weeks (including one week vacation).  
[Read more...](https://blog.zinzen.me/2021/11/04/App-update.html)   

First off, a big 🙏**THANK YOU**🙏 for the 💪 work done by all the testers and interviewees!  
ZinZen doesn't do much yet - but your feedback is valuable!

## Visible updates
- **✨Offline-first✨ is here!**
  - **Everything is now stored <u>only</u> on your device.**  
  Nothing is sent to the cloud unless you explicitly share it with ZinZen.  
  Can't get more 🔒 private 🔒 than that!
  - Happy consequence:  
  **No need for an account/login.** Just open the webapp and start using it! 
  - Another happy consequence:  
  **The app is still super fast** - but without preloading or distracting you with quotes.  
  But we'll leave the quotes anyway as people like it :)

## Invisible updates
- We're switching to the Rust programming language for the scheduler. Why?
  - The proof-of-concept in C has taught us that it is hard to write, read and reason about C.
- Rust is just as fast as C, and has a few added benefits:
  - Rust is safe by default. This will save us a lot of debugging/patches. 70% of Microsoft patches are related to memory issues. Rust avoids this. In the rare cases you actually require it, you can mark the unsafe piece of code as unsafe. This is where you'll look 🕵🏽‍♂️ when issues happen.  
  But in principle:
    - No segfaults
    - No buffer overflows
    - No null pointers
    - No data races
    - No headaches! 🥳
  - Rust has built-in package management and formatting.
  - Rust has a unified build system that works nicely for WASM (both originated at Mozilla).
  - Rust has a powerful type system.
  - Rust works with traditional tools: perf/gdb/lldb/valgrind/LLVM sanitizers
  - Rust has backwards compatibility of releases.
  - Rust uses composition. It doesn't even support inheritance.  
- Why not Go?  
It has garbage collection. C & Rust don't.
- No downsides to Rust? 
  - Sure there are.  
  It is relatively young. Developers/libraries are few... But that is changing!  
```rust_developers.count += 1```  
```++``` can be confusing and is not supported by Rust. 😄

Have an idea to improve ZinZen?  
Please [contact us](https://zinzen.me/contact.html).