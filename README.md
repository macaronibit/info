Here's the full page. On GitHub, open README.md in macaronibit/info, click the pencil (Edit) icon, select all, and paste this over it:

# MacaroniBit - Privacy Policy & App Documentation

Welcome to the official documentation and privacy policy hub for applications developed by **MacaroniBit**.

---

## 1. General Privacy Policy

**Effective Date:** January 1, 2026
**Last Updated:** November 20, 2026
**Developer:** MacaroniBit
**Contact:** [macaronibit@gmail.com](mailto:macaronibit@gmail.com) · [GitHub Repository](https://github.com/macaronibit/info)

MacaroniBit builds mobile applications as educational, utility, or entertainment tools. Depending on the specific application, our apps may be offered free of charge, supported by optional tips, or include paid in-app purchases.

### Information Collection and Use
* **No Personal Data Collection:** We **do not** collect, store, or share any personal identification information, names, email addresses, location data, or unique device identifiers.
* **Local Storage Only:** App data, preferences, and learning progress are stored **locally on your device** and are never sent to MacaroniBit or any server we run. Data leaves your device only when you choose to share it (for example, sharing a recipe), or through Android's own backup to your Google account if you have it turned on.
* **Camera Usage (For Camera-Enabled Apps):** Some applications developed by MacaroniBit may request access to your device's camera.
  * **How camera data is handled:** Camera feeds or images captured within our apps are processed **entirely on your device in real-time**.
  * We **do not** upload or transmit any photos, videos, or camera frames to external servers or third parties. Live camera frames are never saved. A photo is kept only when you choose to add it (for example, a bake photo), and it stays in the app's private storage on your device.
* **No Third-Party Trackers:** We do not integrate tracking SDKs, analytics, or third-party advertising networks.
* **Google Services:** Some apps use Google components for specific features: Google ML Kit and the Google code scanner (on-device barcode, QR, and text reading) and Google Play Billing (optional tips and purchases). These run under [Google's Privacy Policy](https://policies.google.com/privacy), and Google Play services may collect diagnostic information. See each app's section below for what it uses.

### Children's Privacy
Our applications are safe for users of all ages. Because we do not collect any personal data, we knowingly collect no information from children under 13.

### Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Changes are effective immediately after being posted on this repository.

---

## 2. App Documentation Hub

### 📱 KanaPilot
* **Overview:** An offline Japanese learning app for mastering Hiragana and Katakana, plus 112 beginner vocabulary words (56 in each script).
* **Key Features:**
  * Study mode with flip cards, swipe navigation, shuffle, and saved progress.
  * Timed test mode (5 seconds per character) with session results.
  * Character library and vocabulary lists.
  * Japanese pronunciation using your device's built-in text-to-speech voice.
  * Optional tips through Google Play.
* **Permissions:**
  * `VIBRATE`: For subtle quiz haptic feedback.
  * `BILLING`: Added by Google Play Billing, used only for optional tips.
  * `INTERNET` / `ACCESS_NETWORK_STATE`: Added by Google Play Billing so tips can be processed through Google Play. The app itself sends no data anywhere.

---

### 📱 Calbacus
* **Overview:** An offline, privacy-focused calorie, macro, and exercise tracker designed for simple daily health and weight management.
* **Key Features:**
  * Daily calorie and macro targets from the Mifflin-St Jeor equation, adjusted for activity level and a weight-loss goal of 0 to 2 lbs per week, with an optional manual calorie goal.
  * Today dashboard: calories left, eaten, and burned, plus progress toward protein, carb, and fat targets.
  * Meal logging from a food library of staple foods and your own saved foods.
  * Cardio and weight exercise logging with an effort (RPE 1–10) slider and an estimated calorie burn.
  * History: calorie trend chart and per-day summaries for the last 7, 14, or 30 days, with editing of past days.
  * Imperial or metric units.
  * Optional tips through Google Play.
* **Permissions:**
  * `BILLING`: Added by Google Play Billing, used only for optional tips.
  * `INTERNET` / `ACCESS_NETWORK_STATE`: Added by Google Play Billing so tips can be processed through Google Play. The app itself sends no data anywhere.
* **Health & Medical Disclaimer:** Calbacus is an informational utility tool designed for general wellness and fitness tracking. It is not a medical device, and the information provided (including calorie targets, macro ratios, and exercise burn calculations) is for educational and informational purposes only and is not medical advice.

---

### 📱 Artisan Lab: Baking & Recipes
* **Overview:** An offline-first recipe book and baking companion with a sourdough starter tracker, bake timer, and dough tools.
* **Key Features:**
  * Recipe book for baking and savory dishes, with categories, ratings, and notes.
  * Lab versions: try changes to a recipe as named versions, alongside the original.
  * Dough tools: set a target hydration (counting starter water) and scale recipes.
  * Sourdough starter tracker with feeding logs and a rise & temperature graph.
  * Bake timer with an on-time alert, even if the app is closed or the phone restarts.
  * Bake photos and recipe sharing by text or QR code.
* **Permissions:**
  * `POST_NOTIFICATIONS`: To alert you when a bake timer finishes.
  * `SCHEDULE_EXACT_ALARM`: So the bake timer alert arrives on time.
  * `RECEIVE_BOOT_COMPLETED`: To restore a running bake timer after the phone restarts.
  * `INTERNET` / `ACCESS_NETWORK_STATE`: Added by Google Play services for the QR code scanner. The app itself sends no data anywhere.
* **Photos & Camera:** The app opens your device's own camera app or photo picker. Only the photo you take or choose is copied into the app's private storage; the app does not request camera or storage permissions.
* **QR Code Scanning:** Scanning a shared recipe uses the Google code scanner from Google Play services. The image is processed on your device and the app only receives the text in the code. Google Play services may collect diagnostic data under [Google's Privacy Policy](https://policies.google.com/privacy).
* **Backups:** If Android backup is on, Android may back up your recipes, starter logs, and settings to your Google account. Photos are not included.

---

### 📱 Pigment Lab
* **Overview:** A color mixing assistant for painters. Pick or scan a target color and Pigment Lab suggests a paint recipe to match it, then checks your mix with the camera.
* **Key Features:**
  * Paint-like (spectral Kubelka–Munk) color mixing, so blue and yellow make green just like real pigment.
  * Recipe matching for acrylics, oils, and watercolors, scored with the CIEDE2000 color-difference standard.
  * Camera color sampling, with white-paper calibration for more accurate swatch readings.
  * "Check My Mix": measure your mixed paint and see what's off and which paint to add.
  * Paint inventory and custom paints, with barcode and label scanning to add tubes quickly.
  * Vault for saving colors and their recipes to projects.
* **Permissions:**
  * `CAMERA`: For sampling colors, measuring swatches, and scanning paint barcodes and labels. Frames are processed on your device in real time and are never saved or uploaded.
  * `BILLING`: Added by Google Play Billing, used only for optional tips.
  * `INTERNET` / `ACCESS_NETWORK_STATE`: Added by Google Play Billing so tips can be processed through Google Play. The app itself sends no data anywhere.
* **Barcode & Label Scanning:** Uses Google ML Kit with on-device models. Nothing is sent to a server.
* **Optional Tips:** Tips are handled by Google Play under [Google's Privacy Policy](https://policies.google.com/privacy). Nothing in the app is locked behind a tip.
