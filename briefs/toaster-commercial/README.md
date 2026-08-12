# Cinematic Product Commercial — Toastley 2-Slice Smart Toaster

A 15s vertical spot matching the tool-set and blender spots: hero product in a dark studio
void, beam of light, macro tour, slow-motion toast pop, seamless loop. No people, no voiceover.

**CURRENT — 13s detail cut (use this one):**
https://d2ol7oe51mr4n9.cloudfront.net/user_3G3dt4B20P2XbJ6PQqKhDxgXLeb/662452e4-655c-434e-a1d2-918058b754c6.mp4

Clean plate for the detail cut:
https://d8j0ntlcm91z4.cloudfront.net/user_3G3dt4B20P2XbJ6PQqKhDxgXLeb/hf_20260812_100303_1ac73ea4-460d-4010-bb95-1819205ad776.mp4

### Superseded 15s cut

- With text: https://d2ol7oe51mr4n9.cloudfront.net/user_3G3dt4B20P2XbJ6PQqKhDxgXLeb/becfa4fe-eafe-4ebd-ab20-95e719d50378.mp4
- Clean plate: https://d8j0ntlcm91z4.cloudfront.net/user_3G3dt4B20P2XbJ6PQqKhDxgXLeb/hf_20260812_093553_131115de-57df-4004-a76b-bfdba8cee375.mp4

The 13s cut is shorter but carries **more** product detail — it was built after the seller's
feature images arrived, so it names real features instead of generic ones. Length was capped
at 13s by the credit balance, not by the edit.

**Hero keyframe** (check this if the screen looks wrong in the video):
https://d8j0ntlcm91z4.cloudfront.net/user_3G3dt4B20P2XbJ6PQqKhDxgXLeb/hf_20260812_092339_0cd389ac-8594-4893-bae3-15a4a8ba64eb.png

Format: 9:16, 720×1280, 15.10s, H.264 + AAC. Music bed and SFX generated natively.

## Product

- Source: `https://vm.tiktok.com/ZN9kLAu9gW3TF-jUXp7/` → TikTok Shop product `1729454464685411840`
- Toastley 2-Slice Smart Toaster, touchscreen control, 3 colours
  (Silver Stainless / Matt Black / Oat Cream)
- Brushed steel body, matte black end panels, chrome carriage lever, glossy touchscreen panel
- **£41.99**, was **£49.99** — **16% off**
- **4.7★ from 201 reviews · 822 sold**
- **Delivered from UK** · free returns for drop-offs

### Claims policy

On-screen copy carries only listing facts: price, discount, rating, slice count, preset count,
delivery origin, returns. `6 BREAD PRESETS` is countable from the listing image (Bagel, Gluten
Free, White, Waffle, Muffin, Grain). No performance, wattage, or speed claims.

`DELIVERED FROM UK` is used here because this listing states it — the blender ships from
overseas and does not get that line.

## The text problem this product has

Two things made this the hardest of the three to shoot:

1. **A real brand wordmark** ("Toastley") sits on the front panel. Generative models render
   wordmarks as gibberish or morph them into a real competitor's logo. A garbled version of the
   brand being sold is worse than no brand at all.
2. **The entire selling point is a touchscreen covered in tiny text** — Bagel, Gluten Free,
   White, Waffle, Muffin, Grain, Defrost, Reheat, Cancel. All of it renders as garbage.

**The fix:** the screen is prompted to render as a glowing grid of abstract pictograms and
graduated shade blocks — pictorial elements survive generation, text does not. Branding is
prompted tiny, unlit, out of focus and turned away. Then the **real preset names are burned on
in post**, correctly spelled, which also happens to be the strongest SEO beat in the spot.

The weakness became the best search line: `BAGEL / WAFFLE / GLUTEN FREE`.

## Beat structure — 13s detail cut (designed to loop)

Built from the seller's own feature images, so the beats show real documented features rather
than invented ones.

| Time | Action | On-screen text |
|---|---|---|
| 0–2s | Toaster hovers in the beam, two slices turning above the slots | `SMART TOASTER` / `TOUCHSCREEN CONTROL` |
| 2–4.5s | Hard macro on the panel: countdown marks pulse, six shade squares light in sequence pale → chestnut | `6 SHADE LEVELS` / `COUNTDOWN TIMER` |
| 4.5–7s | Macro drifts down the icon grid, each food pictogram blooming in turn, then the three function symbols | `BAGEL / GLUTEN FREE / WHITE` + `WAFFLE / MUFFIN / GRAIN` |
| 7–9.5s | Bread settles in, lever glides down and locks, elements bloom orange, crust browning macro | `4.7 STARS / DELIVERED FROM UK` |
| 9.5–11.5s | **The pop** — both slices launch in slow motion, steam and crumbs scatter | `WAS £49.99` / `NOW £41.99` / `SAVE 16%` |
| 11.5–13s | Toast settles back, camera orbits to the opening framing | `FREE RETURNS` / `TAP THE YELLOW CART` |

### Features documented in the listing images

Used to drive the beats and the copy:

- **Screen:** toasting level indicator, countdown timer (2:30), auto-sleep, touch to wake,
  shade & bread selector, cancel/shut-off
- **Presets:** Bagel, Gluten Free, White, Waffle, Muffin, Grain (six), plus Defrost, Reheat, Cancel
- **Smart features:** countdown timer, touch beep sounds, auto shut-off, last settings memory,
  independent touch panels
- **Design:** matt black finish, polished stainless steel, removable crumb tray, cord storage
  underneath, anti-slip base

Crumb tray, cord storage and anti-slip base were **cut for length** at 13s — they are the first
beat to restore if the spot is ever re-rendered at 15s.

## Type sizing

Every line measured before burning and capped at **≤560px wide in a 720px frame**, which keeps
text clear of TikTok's right-hand button column. Widest line in the detail cut is
`4.7 STARS / DELIVERED FROM UK` at 552px.

The detail cut carries 12 text elements in 13s versus 11 in 15s, so fade timings were tightened
(0.18s in, 0.22s out, 0.28s slide) to fit without the beats treading on each other.

## Production notes

- Hero keyframe: `seedream_v5_pro`, 9:16 2K, conditioned on the listing hero image.
- Motion: `seedance_2_0_mini`, 9:16 720p, 15s, high bitrate.
- Cost: 3 credits keyframe + 37.5 (15s cut) + 32.5 (13s detail cut) = 73. The detail cut reused
  the existing keyframe, so no image spend was repeated. Text passes free.
- Text verified after burn by pixel-delta against the clean plate at each beat.
- **Not visually verified:** the sandbox preview path corrupts above ~5KB and has no OCR, so
  the screen and wordmark rendering could not be confirmed before shipping. Check the video;
  if the panel shows fake words, a keyframe re-roll is 3 credits and the render is the only
  part that needs repeating.
