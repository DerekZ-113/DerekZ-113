# Hey, I'm Derek!

MS Computer Science @ Northeastern (April 2026)  
3+ years at Zoox working with autonomous vehicle fleets

---

## Featured Projects

[**Flight Telemetry System**](https://github.com/DerekZ-113/flight_telemetry): DO-178C-aligned flight telemetry in C++17 on a Raspberry Pi. My own BME280, MPU-6050 and GPS drivers over I2C and serial, Kalman altitude fusion, and fault detection that degrades instead of crashing. Triple-redundant processing lanes with a bit-exact majority voter, verified by a 97,100-run Monte Carlo fault-injection campaign. 68 requirements traced to 585 Google Tests and 186 pytest integration tests at 94.9% branch coverage, with ASan/UBSan gating every pull request. Streams over ZeroMQ and UDP to a React primary flight display that tracks live ADS-B arrivals into SFO.

[**PatternBank**](https://github.com/DerekZ-113/pattern-bank) · [Web App](https://pattern-bank.vercel.app/) · [App Store](https://apps.apple.com/app/patternbank/id6759760762): Cross-platform spaced repetition app for LeetCode interview prep, on React web and React Native iOS. 2,000+ organic visitors, 300+ registered accounts and zero reported crashes. Shared logic lives in @patternbank/core, a published npm package, with local-first sync to Supabase and fail-closed merges, verified by 1,000+ tests.

[**Sentinel**](https://github.com/DerekZ-113/Sentinel) · [Live Demo](https://sentinel-theta-three.vercel.app): ML triage for AV fleet alerts, built on simulated data. An XGBoost classifier cuts the false-positive rate from 61.4% to 32.2% at 79.3% recall and 0.864 ROC-AUC across 26.7M simulated samples, using event-grouped splits. 11 interaction features, drawn from watching thousands of alerts, produced 6 of the top 10 predictors. FastAPI inference service, React/TypeScript monitoring dashboard, 400+ tests with CI, containerized with Docker Compose.

---

## Background

I started at Zoox as a Software Testing Specialist running overnight operations on a 500-vehicle autonomous fleet. After years of watching operators get buried in false alerts, I built Sentinel to fix it.

After solving 347 LeetCode problems and forgetting most of them, I built PatternBank to fix that too.

I've loved aviation since I was a kid, and C++ was the gap between me and aerospace work, so I built a flight telemetry system on a Raspberry Pi to close it.

I finished my MS in April 2026 and I'm looking for software engineering roles in the Bay Area, especially embedded, robotics, autonomy and full stack.

---

## Tech

**Languages:** C++17, Python, JavaScript/TypeScript, SQL, Swift, Java, HTML/CSS  
**Embedded/Systems:** Linux, Raspberry Pi, I2C/UART drivers, CMake, ZeroMQ, UDP sockets, multithreading  
**Testing/Verification:** Google Test, pytest, gcov/lcov, cppcheck, ASan/UBSan, GitHub Actions, Vitest, Playwright, Jest  
**Methods:** DO-178C-aligned development, requirements traceability, Kalman filtering, sensor fusion, fault injection  
**ML/Data:** XGBoost, Feature Engineering, PyTorch, scikit-learn, Pandas, NumPy  
**Web:** React, React Native, Node.js, Express.js, FastAPI, Tailwind CSS, Expo, MongoDB, REST APIs  
**Infrastructure:** Docker/Docker Compose, Supabase, TimescaleDB, PostgreSQL, Vercel, Git

---

## Links

[LinkedIn](https://linkedin.com/in/derekz113) · San Francisco, CA
