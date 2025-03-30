# Ray Tracing in One Weekend Series (v4.0.1)

This repository contains the complete source code and formatted books for Peter Shirley’s classic _Ray Tracing in One Weekend_ trilogy — a hands-on introduction to building a path tracer from scratch in modern C++.

---

## 📚 Read the Books (Free Online)

- [Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html)
- [Ray Tracing: The Next Week](https://raytracing.github.io/books/RayTracingTheNextWeek.html)
- [Ray Tracing: The Rest of Your Life](https://raytracing.github.io/books/RayTracingTheRestOfYourLife.html)

For print options and PDFs, see [`PRINTING.md`](PRINTING.md).

---

## 🛠️ Build Instructions

This project uses **CMake** for building:

### Linux / macOS
```bash
cmake -B build/Release -DCMAKE_BUILD_TYPE=Release
cmake --build build/Release
./build/Release/inOneWeekend > image.ppm
