# sehgalrepo — SimpleStream Plugin Repository

> **Repository short code:** `sehgalrepo`  
> **Maintained by:** [sehgalvansh716-pixel](https://github.com/sehgalvansh716-pixel)  
> **Compatible with:** [SimpleStream](https://github.com/sehgalvansh716-pixel/Simple-Stream) (Android & Android TV)

This is a personal plugin repository for **SimpleStream**, hosting two premium streaming extensions: **NetMirror** and **Cinejoy**. Both plugins load as `.cs3` binary extensions inside the SimpleStream app and provide ad-free, paywall-free streaming of movies and TV series.

---

## 📥 How to Install This Repository in SimpleStream

1. **Open SimpleStream** on your Android device or TV.
2. Tap the **☰ Menu** (top-left) → go to **Settings**.
3. Scroll down and tap **Extensions / Plugins**.
4. Tap **Add Repository** (or the **+** button).
5. Paste the following repository URL:

   ```
   https://raw.githubusercontent.com/sehgalvansh716-pixel/sehgalrepo/main/repo.json
   ```

6. Tap **Add**. The repository named **sehgalrepo** will appear in your list.
7. Open the repository → tap **NetMirror** or **Cinejoy** → tap **Install**.
8. The plugin will download and activate automatically. No restart required.

---

## 🔌 Plugins in This Repository

### 1. NetMirror (v114)

| Field | Details |
|-------|---------|
| **Version** | 114 |
| **Content Types** | Movies, TV Series |
| **Language** | English |
| **Raw URL** | [NetMirror.cs3](https://raw.githubusercontent.com/sehgalvansh716-pixel/sehgalrepo/main/NetMirror.cs3) |

#### What it does
NetMirror is a multi-platform mirror streaming provider. It aggregates content from:
- **Netflix** titles
- **Amazon Prime Video** titles
- **Disney+ Hotstar** titles
- **Marvel** and **Star Wars** series & films

#### Key features
- ✅ Full multi-season & multi-episode loading
- ✅ Native HLS adaptive streaming with multi-audio track selection (Hindi, Tamil, Telugu, English)
- ✅ 100% ad-free and paywall-free playback
- ✅ High-quality metadata: posters, backdrops, episode thumbnails
- ✅ Works on phones, tablets, and Android TV (D-pad compatible)

---

### 2. Cinejoy (v5)

| Field | Details |
|-------|---------|
| **Version** | 5 |
| **Content Types** | Movies, TV Series |
| **Language** | English |
| **Raw URL** | [Cinejoy.cs3](https://raw.githubusercontent.com/sehgalvansh716-pixel/sehgalrepo/main/Cinejoy.cs3) |

#### What it does
Cinejoy is a standalone provider targeting [cinejoy.to](https://cinejoy.to), delivering a full cinematic streaming experience directly inside SimpleStream.

#### Key features
- ✅ Auto-multiplexed adaptive HLS streams with in-player resolution switching
- ✅ Multi-audio playback (select language from the player)
- ✅ **Dual trailer integration**: YouTube trailer + IMDb direct MP4 fallback
- ✅ Transparent title logos & TV-style cast avatar panels
- ✅ Content ratings, show status badges (Ongoing / Ended)
- ✅ **38 dynamic categories** (genre, trending, latest) that refresh on every restart
- ✅ Works on phones, tablets, and Android TV (D-pad compatible)

---

## 🔗 Direct Plugin URLs

Use these raw links if you want to sideload a plugin manually (Settings → Extensions → Install from URL):

| Plugin | Direct Install URL |
|--------|--------------------|
| NetMirror | `https://raw.githubusercontent.com/sehgalvansh716-pixel/sehgalrepo/main/NetMirror.cs3` |
| Cinejoy | `https://raw.githubusercontent.com/sehgalvansh716-pixel/sehgalrepo/main/Cinejoy.cs3` |

---

## ⚙️ Repository Files

| File | Purpose |
|------|---------|
| `repo.json` | Repository manifest — tells SimpleStream the repo name and plugin list URL |
| `plugins.json` | Plugin catalog — lists all available plugins with metadata & download URLs |
| `NetMirror.cs3` | Compiled NetMirror plugin binary |
| `Cinejoy.cs3` | Compiled Cinejoy plugin binary |

---

## ❓ FAQ

**Q: Do I need to pay or create an account?**  
A: No. Both plugins provide free, no-account streaming.

**Q: Will plugins update automatically?**  
A: Yes. SimpleStream checks plugin versions on launch. When a new version is pushed to this repo, you'll get an in-app update prompt.

**Q: Which Android version is required?**  
A: Android 5.0 (API 21) or higher. Android TV is fully supported.

**Q: How do I report a broken stream?**  
A: Open an [issue](https://github.com/sehgalvansh716-pixel/sehgalrepo/issues) in this repository.

---

## 📜 License

These plugins are distributed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).
