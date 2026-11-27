# SoundShield

SoundShield is a free, open-source educational DNS/privacy guide for reducing known music ad and tracker requests using device-level or network-level DNS settings.

## What it does
  Spotify ad block DNS guide for Android, iPhone, Windows, Mac, router, Pi-hole and AdGuard.
- Shows a simple browser reachability test for known ad/tracker domains.
- Detects the visitor's device type from the browser user agent.
- Provides device-specific DNS setup steps for Android, iPhone, Windows, Mac, Alexa, and routers.
- Generates downloadable blocklist formats for hosts, Pi-hole, AdGuard, uBlock, and JSON.
- Offers copy buttons and a share flow for quick setup.

## What it does not do

- It does **not** bypass Spotify Premium, DRM, subscriptions, payments, or app restrictions.
- It does **not** download, modify, crack, patch, or reverse-engineer Spotify or any music app.
- It does **not** guarantee ad blocking. DNS results can vary by device, browser, network, VPN, DNS cache, and app behavior.
- It does **not** collect emails, reports, analytics, or user data in this static version.

## How to use

1. Open `index.html` in a browser or deploy it with GitHub Pages.
2. Run the browser reachability test.
3. Open the guide for your device.
4. Review and apply the DNS or hosts-file steps you trust.
5. Re-run the test to compare the result.

## Safety note

Review any blocklist before applying it to your device, router, hosts file, Pi-hole, AdGuard, or uBlock setup. Some domains may affect app features, analytics, login flows, playback behavior, or unrelated services.

## GitHub Pages deploy

1. Create a new public GitHub repository.
2. Upload `index.html`, `README.md`, and `LICENSE`.
3. Go to **Settings → Pages**.
4. Select **Deploy from branch**.
5. Choose the `main` branch and `/root` folder.
6. Save and open the generated GitHub Pages URL.

## Credits

SoundShield references public/community blocklist formats and educational DNS concepts. Credit is kept in generated blocklist files for sources such as x0uid/SpotifyAdBlock, EasyList, and AdGuard community resources.

SoundShield is not affiliated with Spotify, Amazon, Google, AdGuard, EasyList, or any listed service.

## License

MIT License. See `LICENSE`.
