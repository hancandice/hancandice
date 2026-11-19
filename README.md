<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="assets/hero-dark-sm.svg" />
  <source media="(max-width: 600px)" srcset="assets/hero-light-sm.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg" />
  <img alt="Jeeyoung Han, senior mobile engineer in Paris. I build apps that handle real money, from React Native down to Swift, Kotlin and the backend behind them." src="assets/hero-light.svg" width="100%" />
</picture>

<p>
  <a href="https://hancandice.netlify.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-5B5FA8?style=for-the-badge" /></a>
  <a href="https://www.linkedin.com/in/candice-h-81814a173"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-15171B?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://www.npmjs.com/~jeehahn"><img alt="npm" src="https://img.shields.io/badge/npm-15171B?style=for-the-badge&logo=npm&logoColor=white" /></a>
  <a href="mailto:jeeyoung.han82@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-15171B?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

**8+ years in mobile · React Native since 2018 · founder of [Grida](https://gridalabs.com).**
Crypto wallets, on-device key security and real-time data — and the Node.js backend behind them.

### What I do

- **Wallet & transaction security** — simulate what a user is about to sign, flag scam dapps and EIP-7702 delegation scams, keep secrets out of screenshots and screen recordings.
- **On-device keys** — signing keys generated and used only in native code (Keychain + libsecp256k1, Android Keystore with StrongBox), never in JavaScript.
- **Real-time mobile** — live prices, charts and animation on the UI thread (Reanimated, Skia, Gesture Handler).
- **Backend when the product needs it** — Node.js / TypeScript APIs, Postgres, Redis, WebSockets, push, and the abuse and privacy rules behind them.

### Selected work

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="assets/work-exodus-dark-sm.svg" />
  <source media="(max-width: 600px)" srcset="assets/work-exodus-light-sm.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/work-exodus-dark.svg" />
  <img alt="Exodus — Self-custody crypto wallet used by millions. Mobile, Shared SDK, Desktop." src="assets/work-exodus-light.svg" width="100%" />
</picture>

- **Real-time pricing** — owned the pricing engine in the shared SDK behind mobile and desktop: a live-price endpoint with ETag caching and a 25 s price pipeline beside the 1 min market-data one, with fallback between them. Ported the Liveline chart engine to React Native Skia and replaced every legacy chart.
- **Transaction security** — Blockaid simulation of WalletConnect requests on EVM and Solana before signing, WalletConnect Verify API for scam dapps, new approval screens with unsafe-transaction warnings, EIP-7702 delegation scam flows.
- **Native security** — screen-recording detection and screenshot blocking in Objective-C, a BiometricPrompt cancel API in Java, fixes for unlock and biometric re-entry races and an Android SIGSEGV.

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="assets/work-feels-dark-sm.svg" />
  <source media="(max-width: 600px)" srcset="assets/work-feels-light-sm.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/work-feels-dark.svg" />
  <img alt="Feels — Dating app. Mobile, Backend." src="assets/work-feels-light.svg" width="100%" />
</picture>

- **App** — client-side ffmpeg video pipeline (HDR detection, size fallback), story editor, a new feed and direct messages, RTK Query with a token refresh that dedupes concurrent calls, Superwall + RevenueCat paywalls.
- **Backend** (Node.js, TypeScript, Express, Postgres, Redis, Socket.IO) — zod-validated request and response schemas with tests, trust & safety rules (blocking, reporting, abuse detection), push notifications with the sender's photo.

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="assets/work-grida-dark-sm.svg" />
  <source media="(max-width: 600px)" srcset="assets/work-grida-light-sm.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/work-grida-dark.svg" />
  <img alt="Grida — My own studio — I design, build and ship each product end to end. Founder, iOS · Android · Web." src="assets/work-grida-light.svg" width="100%" />
</picture>

- **Bonghwang** *(coming soon)* — self-custody perpetuals on Hyperliquid. Trading keys live in Swift and Kotlin and never touch JavaScript; orders are signed on-device and go straight to the venue; a passkey second factor is enforced in the signer.
- **[Inbound](https://inbound.gridalabs.com)** · **[Outbound](https://outbound.gridalabs.com)** — Flutter apps on the App Store and Google Play in 23 languages, with native Swift / Kotlin notification and scheduling code.
- **[Saju Alley](https://sajualley.com)** — Next.js web app with streaming AI readings, Supabase, Stripe and Kakao Pay.

<sub>Earlier: <b>Luko</b> (insurance, React Native — contract flows for 60–80k monthly users), <b>DANO</b> and <b>Linkey</b> (native Android in Kotlin).</sub>

### Open source

Both are 1.0 rewrites on Reanimated + Gesture Handler, verified on iOS and Android.

- **[react-native-reanimated-zoomable](https://github.com/hancandice/react-native-reanimated-zoomable)** [![npm](https://img.shields.io/npm/v/react-native-reanimated-zoomable?style=flat-square&color=5B5FA8&label=npm)](https://www.npmjs.com/package/react-native-reanimated-zoomable)<br>Pinch, pan and double-tap zoom for any view, on the UI thread. Built for Feels live events.
- **[react-native-sticky-range-slider](https://github.com/hancandice/react-native-sticky-range-slider)** [![npm](https://img.shields.io/npm/v/react-native-sticky-range-slider?style=flat-square&color=5B5FA8&label=npm)](https://www.npmjs.com/package/react-native-sticky-range-slider)<br>Two-thumb range slider whose labels ride on the thumbs. Accessible, RTL, works inside `<Modal>`.

### Stack

<p>
  <img alt="TypeScript, React, Swift, Kotlin, Java, Flutter" src="https://skillicons.dev/icons?i=ts,react,swift,kotlin,java,flutter&theme=dark" height="40" />
  &nbsp;
  <img alt="Node.js, Express, Postgres, Redis, Next.js, Supabase" src="https://skillicons.dev/icons?i=nodejs,express,postgres,redis,nextjs,supabase&theme=dark" height="40" />
</p>

**Mobile** React Native · Reanimated · Skia · Gesture Handler · Swift · Objective-C · Kotlin · Java · Flutter  
**Backend** Node.js · Express · Postgres · Redis · Socket.IO · Next.js · Supabase  
**Crypto** EVM · Solana · Hyperliquid · WalletConnect · Blockaid

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hancandice/hancandice/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hancandice/hancandice/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution grid snake animation" src="https://raw.githubusercontent.com/hancandice/hancandice/output/github-contribution-grid-snake.svg" />
</picture>

<p align="center"><sub>Open to senior and founding roles in mobile, backend, crypto and security.</sub></p>
