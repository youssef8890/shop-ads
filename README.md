# Shop TV ad player

A web page that loops your ads full screen on the shop TV (Samsung UE65NU7179, built-in Internet app).

## Change the ads (from your phone)

1. Open this repository on github.com and go into the `ads` folder.
2. **Add file → Upload files**, pick your JPG/PNG images or MP4 videos, then **Commit changes**.
3. To remove an ad: tap the file, the **…** menu, **Delete file**, then **Commit changes**.

The TV picks up changes by itself within about 10 minutes.

- **Order:** ads play in filename order. Start names with numbers: `01_welcome.jpg`, `02_offer.mp4`.
- **Time per image:** 10 seconds by default. Put `_15s` at the end of the name to change it, for example `03_sale_15s.jpg`.
- **Videos** play to the end, without sound.
- **Best size:** 1920×1080 (16:9). Keep videos under about 50 MB.

## TV setup (one time)

1. **Wi-Fi:** Home button → Settings → General → Network → Open Network Settings → Wireless → pick your Wi-Fi.
2. **Open the page:** Home button → **Internet** app → type the page address → OK.
3. **Bookmark it:** in the Internet app, choose the star / "Add to Bookmarks" (Lesezeichen), and pin it to Home if offered.
4. **Full screen:** open the browser menu and choose "Full Screen" (Vollbild).
5. **Stay on:**
   - Settings → General → Eco Solution → **Auto Power Off: Off** (Automatisch Ausschalten: Aus).
   - Settings → General → Eco Solution → **No Signal Power Off: Off** if present.
   - Settings → General → System Manager → **Screen Burn Protection / Screensaver: Off**.

After a power cut: Home → Internet → open the bookmark → Full Screen.
