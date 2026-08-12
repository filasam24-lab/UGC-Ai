# Cinematic Product Commercial — Toastley 2-Slice Smart Toaster

A 15s vertical spot matching the tool-set and blender spots: hero product in a dark studio
void, beam of light, macro tour, slow-motion toast pop, seamless loop. No people, no voiceover.

**Final video (text burned in):**
https://d2ol7oe51mr4n9.cloudfront.net/user_3G3dt4B20P2XbJ6PQqKhDxgXLeb/becfa4fe-eafe-4ebd-ab20-95e719d50378.mp4

**Clean plate (no text), for re-cutting copy:**
https://d8j0ntlcm91z4.cloudfront.net/user_3G3dt4B20P2XbJ6PQqKhDxgXLeb/hf_20260812_093553_131115de-57df-4004-a76b-bfdba8cee375.mp4

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

## Beat structure (15s, designed to loop)

| Time | Action | On-screen text |
|---|---|---|
| 0–2.5s | Toaster hovers in the beam, two slices turning above the slots | `SMART TOASTER` / `TOUCHSCREEN CONTROL` |
| 2.5–5.5s | Macro traverse — steel grain, chrome lever, glowing control panel | `2 SLICE TOASTER` / `6 BREAD PRESETS` |
| 5.5–8.5s | Bread settles in, lever glides down and locks, elements bloom orange | `BAGEL / WAFFLE / GLUTEN FREE` |
| 8.5–11.5s | Macro down into the slot: crust browning, heat shimmer, glowing crumb | `4.7 STARS / DELIVERED FROM UK` |
| 11.5–13.5s | **The pop** — both slices launch in slow motion, steam and crumbs scatter | `WAS £49.99` / `NOW £41.99` / `SAVE 16%` |
| 13.5–15s | Toast settles back, camera orbits to the opening framing | `FREE RETURNS` / `TAP THE YELLOW CART` |

## Type sizing

Every line measured before burning and capped at **≤560px wide in a 720px frame**, which keeps
text clear of TikTok's right-hand button column. Widest line here is
`4.7 STARS / DELIVERED FROM UK` at 552px.

## Production notes

- Hero keyframe: `seedream_v5_pro`, 9:16 2K, conditioned on the listing hero image.
- Motion: `seedance_2_0_mini`, 9:16 720p, 15s, high bitrate.
- Cost: 3 credits keyframe + 37.5 video = 40.5. Text pass free.
- Text verified after burn by pixel-delta against the clean plate at each beat.
- **Not visually verified:** the sandbox preview path corrupts above ~5KB and has no OCR, so
  the screen and wordmark rendering could not be confirmed before shipping. Check the video;
  if the panel shows fake words, a keyframe re-roll is 3 credits and the render is the only
  part that needs repeating.
