# Hotel The Black Stone — About Us Page Content Replacements
**Page URL:** https://chocolate-leopard-997635.hostingersite.com/about-us/  
**Prepared by:** AdsPilot  
**Scope:** About Us page HTML-level find & replace — copy-paste ready for dev handoff

---

> **How to use this doc:**  
> Each block shows the exact text to **FIND** in the HTML source and what to **REPLACE WITH**.  
> Use browser Ctrl+F or VS Code search to locate each string.  
> Fields marked ⚠️ need client confirmation before publishing.

---

## META TITLE & DESCRIPTION
*(WordPress Admin → Pages → About Us → SEO Settings via Rank Math / Yoast)*

| Field | Value |
|-------|-------|
| Meta Title | `About Us – Hotel The Black Stone, Koramangala Bengaluru` |
| Meta Description | `Learn about Hotel The Black Stone — an affordable hotel in KHB Colony, Koramangala, Bengaluru. Modern rooms, warm hospitality, and everything you need for a comfortable stay.` |

> Title = 55 chars. Description = 173 chars — trim if needed to: "Hotel The Black Stone, Koramangala — affordable rooms, modern comfort, and warm hospitality near Jyoti Nivas College Road, Bengaluru." = 133 chars.

---

## 🚨 CRITICAL — Page Title Tag

The browser tab currently reads "About Us – Hotel The Black Stone" which is correct. However verify in WordPress SEO settings that it reads exactly:

```
VERIFY (in WordPress SEO / Rank Math):
About Us – Hotel The Black Stone
```

> If it still shows "Hotel The Black Diamond" anywhere — fix it in WordPress → Pages → About Us → SEO Title.

---

## SECTION 1 — Top Bar (Header Strip)

### Email

```
FIND:
<span class="elementor-icon-list-text">info@example.com</span>

REPLACE WITH:
<span class="elementor-icon-list-text">info@hoteltheblackstone.in</span>
```

### Location

```
FIND:
<span class="elementor-icon-list-text">King Street, AUS</span>

REPLACE WITH:
<span class="elementor-icon-list-text">KHB Colony, 5th Block, Koramangala, Bengaluru</span>
```

---

## SECTION 2 — Header Phone Number

```
FIND:
<h3 class="elementskit-section-subtitle  ">24/7 HOTEL SERVICES:</h3>

REPLACE WITH:
<h3 class="elementskit-section-subtitle  ">24/7 RESERVATIONS:</h3>
```

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">+01 (977) 2599 12</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">+91 08884803777</h2>
```

---

## SECTION 3 — Off-Canvas Sidebar Blurb

```
FIND:
<p>Est adipisci rutrum minim hat dolorum, nobis nonummy natoque dolores delectus magna turpis.</p>

REPLACE WITH:
<p>Hotel The Black Stone — a comfortable and affordable stay in KHB Colony, Koramangala, just 180m from Jyoti Nivas College Road.</p>
```

---

## SECTION 4 — About Us Main Section

### Section heading

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">We can help you feel more comfortable</h2>
(context: inside the About Us page body content)

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Where Every Guest Feels Right at Home</h2>
```

### Main intro paragraph — REPLACE (currently says "The Black Diamond")

```
FIND:
<p>Welcome to The Black Diamond, where comfort feels like home and every guest is treated like family. We pride ourselves on creating a warm, inviting atmosphere paired with quality service and attention to detail. Whether you're here for a short visit or an extended stay, we aim to make every moment special.</p>

REPLACE WITH:
<p>Welcome to Hotel The Black Stone, where comfort feels like home and every guest is treated like family. We pride ourselves on creating a warm, inviting atmosphere paired with quality service and attention to detail. Whether you're here for a short visit or an extended stay, we aim to make every moment special.</p>
```

### Bullet point 1 — REPLACE (currently says "The Black Diamond")

```
FIND:
<span class="elementor-icon-list-text">The Black Diamond is a symbol of strength, elegance, and rarity.</span>

REPLACE WITH:
<span class="elementor-icon-list-text">The Black Stone stands for strength, stability, and enduring quality — values that define every aspect of our hospitality.</span>
```

### Bullet point 2 — REPLACE (currently says "personalized hospitality")

```
FIND:
<span class="elementor-icon-list-text">Our hotel embodies these qualities by offering exceptional comfort, modern design, and personalized hospitality—creating a stay that's truly one of a kind.</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Our hotel reflects these values through clean, well-maintained rooms, attentive staff, and a genuine commitment to making your stay memorable.</span>
```

### Progress bar values

```
FIND:
data-value="90"
(label: Positive Reviews — on About Us page)

REPLACE WITH:
data-value="95"
```

```
FIND:
data-value="98"
(label: Happy Customers — on About Us page)

REPLACE WITH:
data-value="92"
```

> ⚠️ Confirm both percentages with client.

---

## SECTION 5 — Second Text Block (below photo carousel)

### REPLACE (currently says "The Black Diamond")

```
FIND:
<p>The Black Diamond is more than a place to stay—it's an experience. Designed for travelers who appreciate style, comfort, and exceptional service, our hotel delivers a seamless blend of modern amenities and timeless design. From relaxing spaces to vibrant surroundings, we provide the perfect setting to unwind, connect, and explore.</p>

REPLACE WITH:
<p>Hotel The Black Stone is more than a place to stay — it's a genuine experience. Designed for travellers who value cleanliness, comfort, and friendly service, our hotel offers a seamless blend of modern amenities and a warm atmosphere. From our well-furnished rooms to our vibrant Koramangala surroundings, we provide the perfect setting to unwind, connect, and explore.</p>
```

---

## SECTION 6 — Stats Counters (About Us version)

```
FIND:    data-to-value="25"   (label: YEARS EXPERIENCE)
REPLACE: data-to-value="10"
```

```
FIND:    data-to-value="420"  (label: LUXURY ROOMS)
REPLACE: data-to-value="20"
```

```
FIND:    data-to-value="23"   (label: SATISFIED GUEST)
REPLACE: data-to-value="500"
```

> ⚠️ All 3 values need client confirmation.

---

## SECTION 7 — OUR VALUES Section

### Section heading — REPLACE

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">Visit Our Natural Paradise &amp; Reconnect With Yourself</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">What Makes The Black Stone Different</h2>
```

### OUR VALUES paragraph — REPLACE (currently says "The Black Diamond" twice)

```
FIND:
<p>At The Black Diamond, we redefine modern luxury with a bold edge. Inspired by the rarity and strength of the black diamond, our hotel blends refined elegance with contemporary comfort. Every detail—from our thoughtfully designed rooms to our personalized service—is crafted to create an unforgettable stay. Whether you're visiting for business or leisure, The Black Diamond offers a sanctuary where sophistication meets warmth.</p>

REPLACE WITH:
<p>At Hotel The Black Stone, we believe in delivering quality without compromise. Inspired by the strength and reliability of the black stone, our hotel blends clean, modern comfort with genuine warmth. Every detail — from our thoughtfully maintained rooms to our attentive service — is crafted to give you a stay worth remembering. Whether you're visiting for business or leisure, The Black Stone offers a welcoming retreat in the heart of Koramangala.</p>
```

### YouTube Video Link

The page has a YouTube video widget with a placeholder video. Ask the client if they have a hotel walkthrough/reel:

```
FIND:
href="https://www.youtube.com/embed/VhBl3dHT5SY?feature=oembed?playlist=VhBl3dHT5SY&amp;mute=0&amp;autoplay=0&amp;loop=no&amp;controls=0&amp;start=0&amp;end="

REPLACE WITH:
href="[CLIENT'S YOUTUBE VIDEO URL]"
```

> ⚠️ If no video is available, hide this section in Elementor or replace with a static hotel image.

---

## SECTION 8 — Footer

### Footer logo (still demo site)

```
FIND:
<img class="bew-site-logo-img" src="https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/main-logo-2.png" alt="default-logo">

REPLACE WITH:
<img class="bew-site-logo-img" src="https://chocolate-leopard-997635.hostingersite.com/wp-content/uploads/2026/04/resized_logo_no_stretch.png" alt="Hotel The Black Stone">
```

### Footer about blurb

```
FIND:
<p>Laboriosam blandit suspendisse ducimus voluptate commodi, itaque. Veritatis iac ulisarchitecto, eiusmillo ea eleifendte mpore,debitis! Atque hac. Veritatis commodi, itaque.</p>

REPLACE WITH:
<p>Hotel The Black Stone — KHB Colony, Koramangala, Bengaluru. Affordable rooms with modern amenities, complimentary breakfast, and warm hospitality near Jyoti Nivas College Road.</p>
```

### Footer address

```
FIND:
<span class="elementor-icon-list-text">Address : 22th Streets, Colorado</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Address : 125, 1st Cross Rd, KHB Colony, 5th Block, Koramangala, Bengaluru 560095</span>
```

### Footer email

```
FIND:
<span class="elementor-icon-list-text">Email : info@example.com</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Email : info@hoteltheblackstone.in</span>
```

### Footer phone

```
FIND:
<span class="elementor-icon-list-text">Phone : +988-256-266-88</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Phone : +91 08884803777</span>
```

### Footer fax → WhatsApp

```
FIND:
<span class="elementor-icon-list-text">Fax : (+01)125-365-88</span>

REPLACE WITH:
<span class="elementor-icon-list-text">WhatsApp : +91 08884803777</span>
```

### Footer copyright

```
FIND:
Copyright © 2026 Bosa Hotel. Powered by

REPLACE WITH:
Copyright © 2026 Hotel The Black Stone. Website by
```

---

## What's Good — Photo Carousel

The About Us page already has 4 real hotel photos uploaded correctly:
- DSC07190 ✅
- DSC07265-2-Pano ✅
- DSC07318 ✅
- DSC07332 ✅

No image changes needed in the photo carousel section.

---

## Summary — Items Requiring Client Confirmation Before Publishing

| # | Item | Current Value | Action Required |
|---|---|---|---|
| 1 | Positive Reviews % | 90% | Confirm real value |
| 2 | Happy Customers % | 98% | Confirm real value |
| 3 | Years Experience counter | 25 | Confirm actual years in business |
| 4 | Luxury Rooms counter | 420 | Confirm actual room count |
| 5 | Satisfied Guest counter | 23 | Confirm realistic number |
| 6 | YouTube video | Placeholder | Provide hotel's own video URL or hide section |

---

*Document prepared by AdsPilot | Hotel The Black Stone — About Us Page Dev Handoff*
