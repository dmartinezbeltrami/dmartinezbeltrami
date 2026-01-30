# Hi, I'm Diego 👋

I'm an AI / Edge Systems Engineer focused on **real-time computer vision** on **embedded hardware**.

Most of my day-to-day work lives in private, production systems (Qualcomm EB5, NVIDIA Jetson Orin Nano, PPE detection pipelines, etc.), so this GitHub is a curated set of **clean, self-contained examples** inspired by that experience — not a dump of company code.

---

## What I do

- 🧠 **Computer Vision & Edge AI** – real-time inference on embedded devices (Qualcomm EB5 / SNPE, NVIDIA Jetson / TensorRT).
- ⚙️ **C++ Systems Engineering** – multithreaded, low-latency pipelines; async workers; backpressure and robustness instead of “just works on my machine”.
- 📡 **Cloud–Edge Integration** – S3-compatible uploads, REST APIs, and metadata flows between edge devices and cloud backends.
- 🎯 **Problem fixing** – inheriting partially broken systems and making them stable enough for production.

---

## What I'm working on (publicly)

I’m in the process of turning my professional experience into **small, focused, open-source examples**.  
These repos are being built as *clean-room* implementations (no proprietary code, no company details).

### Coming soon

- **`cpp-async-worker-queue`**  
  A minimal C++11 worker-queue implementation (bounded queue, background thread, graceful shutdown), similar to what I use for alert processing and background tasks in real-time pipelines.

- **`cpp-s3-uploader-libcurl-openssl`**  
  An S3-compatible uploader written in C++ using libcurl and OpenSSL, including AWS Signature v4 signing. Designed for edge devices that need to push snapshots or logs to object storage.

- **`embedded-snapshot-coordination-example`**  
  A small simulation of how detection threads can safely request snapshots from capture threads using atomic flags and callbacks, without blocking the video pipeline.

- **`cpp-rest-client-libcurl-json`**  
  A robust REST client example with JSON handling and UTF-8 sanitation, inspired by the kind of defensive coding needed on embedded systems talking to flaky networks and strict backends.

I’m prioritizing **quality over quantity** here: each repo is small, readable, and focused on one idea.

---

## Tech I use regularly

**Languages**
- C++ (multithreading, concurrency, low-level systems)
- Python

**Edge / CV stack**
- NVIDIA TensorRT, ONNX
- Qualcomm SNPE
- OpenCV
- GStreamer, RTSP
- Hardware-accelerated video decode/encode

**Cloud & tooling**
- libcurl, OpenSSL
- REST APIs, S3-compatible object storage (e.g. DigitalOcean Spaces)
- Linux, Docker, systemd, Bash
- Microsoft Azure (certified), OpenAI APIs

---

## How I like to work

- I care a lot about **stability**: no hidden crashes, no silent corrupt data, no “it works when we don’t touch it”.
- I prefer **simple, explicit designs** over clever hacks.
- I like turning messy, inherited systems into something you can **reason about and extend safely**.

---

## Contact

- 📧 **Email:** dp.martinezb@gmail.com  
- 🌎 **Location:** Chile  
- 🔗 **LinkedIn:** linkedin.com/in/dpmartinezb/

If you want to talk about embedded CV systems, edge AI, or migrating pipelines from weird hardware, feel free to reach out 🙂
