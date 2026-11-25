# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users
People with photos or videos that are too small, blurry, old or low quality, who want them bigger and clearer without uploading them anywhere: family photo restorers, people preparing images for print or a wallpaper, anime and cartoon fans, and anyone with old low-resolution video. They arrive from the Microsoft Store, Google Play, search or a shared link, usually on a phone or a Windows PC, and decide in seconds whether to install.

## Product Purpose
Upscaly makes pictures and video up to 4x bigger with AI models that run on the visitor's own graphics card. The website's job is to show that result honestly and send the visitor to the right store: Microsoft Store for Windows (paid, with a free trial) or Google Play for Android (free).

## Positioning
Nothing is uploaded: the work happens on the device, with no account, no subscription and no credits. A buy-once desktop app with real video upscaling (frame stepping, start/end marks, sample renders) and named models for each kind of picture.

## Capabilities and Constraints
- Windows 2.0.1 (Microsoft Store, product 9NFFHP49BVDT, "Upscaly: Photo & Video Enhancer"): photos and video, 2x/3x/4x, batches and whole folders, pause/stop, compare two models, protect text and logos with a brush, side-by-side and split compare, PNG/JPEG/WebP, own ncnn models, works offline with built-in models. Video needs FFmpeg, downloaded on first use. Vulkan GPU recommended; runs on the processor more slowly.
- Models: Everyday Photos, Old & Blurry Photos, Illustrations (built in); Keep Film Grain, Fine Detail, Maximum Detail (free download); Animation Video 2x/3x/4x.
- Android (Google Play, com.wexpa.upscaly.mobile): free, photos only, on-device, Android 8.0+ arm64. 1.0.5 is in progress, not live.
- Crash reports: Windows off by default; Android 1.0.5 adds Crashlytics/Analytics with a switch. Photos are never included.
- Live Store listing (read 25 Nov 2026): $9.99 one-time, 15-day free trial (full app, nothing watermarked), released 29 Sep 2026, updated 25 Nov 2026. Requirements: Windows 10 17763+, x64, 8 GB RAM (16 recommended), Vulkan 1.2 GPU with 2 GB video memory (6 recommended). Store's six screenshots are store/final-2.0.0/1-6.
- Hosting: static HTML on GitHub Pages (upscaly.shayxo.dev), repo shayann07/upscaly-web. No build step.

## Brand Commitments
- Name: Upscaly. Visual system is the apps' own: warm near-black ground, crimson accent, Archivo and Martian Mono, hairline borders, no drop shadows on chrome, diagonal stripe backdrop.
- Never the word "sharp" (or sharper/sharpen) in marketing copy.
- Faceless imagery only: people seen from behind or without faces.
- Plain, non-technical words; British-neutral, honest copy. Only the Store version of Windows is advertised, never the office build.
- Results use generative AI and can differ from the real subject; say so where results are shown.

## Evidence on Hand
- Honest before/after: bare-back store frame, original 270x480 and the built-in model's real 4x (1080x1920): `wt/m105-look/src/assets/sample-before.jpg`, `sample-after.jpg`; source video `store/sample-media-2.0.0/sample-c7.mp4`.
- Real Windows 2.0 screenshots: `store/final-2.0.0/1-photo-compare.png` to `6-settings.png` (1920x1080).
- No testimonials, ratings, download counts or press. Do not invent any.

## Product Principles
- Show the result, don't describe it.
- Privacy by construction, stated plainly and accurately.
- Honest about limits: generative detail, GPU needs, trial and price.
- One clear next step per platform.
