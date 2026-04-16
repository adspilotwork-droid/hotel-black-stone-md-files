# Hotel The Black Stone — MASTER Content Replacements File
**Website:** https://chocolate-leopard-997635.hostingersite.com/  
**Prepared by:** AdsPilot | April 2026  
**Covers:** Homepage · About Us · Facilities · Blog · Contact Us  
**Standard:** SEO + AEO (Answer Engine Optimization) + GEO (Generative Engine Optimization)

---

> **How to use this doc:**  
> Each block shows the exact text to **FIND** in the HTML source and what to **REPLACE WITH**.  
> Use browser Ctrl+F or VS Code search to locate each string.  
> Fields marked ⚠️ need client confirmation before publishing.  
> Global fixes (header, footer, sidebar) appear **once** at the top — apply them across all pages together.

---

## ✅ CONFIRMED BUSINESS DETAILS (Use These Everywhere)

| Field | Value |
|-------|-------|
| Hotel Name | Hotel The Black Stone |
| Address | 125, 1st Cross Rd, near Jyoti Nivas College Road, KHB Colony, 5th Block, Koramangala, Bengaluru, Karnataka 560095 |
| Phone | +91 08884803777 |
| Email | info@hoteltheblackstone.in |
| Nearest Landmark | Jyoti Nivas College Road — 180 m away |
| Secondary Landmark | Nexus Mall Koramangala — 1.1 km away |
| Check-in | 12:00 PM |
| Check-out | 12:00 PM |

---

---

# PART 1 — GLOBAL FIXES (Apply Once — All Pages)

These appear on every page via shared Elementor templates. Fix them once and they update everywhere.

---

## GLOBAL HEADER — Top Bar Strip

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

## GLOBAL HEADER — Phone Section

### Label
```
FIND:
<h3 class="elementskit-section-subtitle  ">24/7 HOTEL SERVICES:</h3>

REPLACE WITH:
<h3 class="elementskit-section-subtitle  ">24/7 RESERVATIONS:</h3>
```

### Number
```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">+01 (977) 2599 12</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">+91 08884803777</h2>
```

---

## GLOBAL — Off-Canvas Sidebar (Hamburger Menu)

```
FIND:
<p>Est adipisci rutrum minim hat dolorum, nobis nonummy natoque dolores delectus magna turpis.</p>

REPLACE WITH:
<p>Hotel The Black Stone — KHB Colony, Koramangala. Affordable, comfortable rooms just 180 m from Jyoti Nivas College Road, Bengaluru.</p>
```

---

## GLOBAL FOOTER

### Footer Logo
```
FIND:
<img class="bew-site-logo-img" src="https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/main-logo-2.png" alt="default-logo">

REPLACE WITH:
<img class="bew-site-logo-img" src="https://chocolate-leopard-997635.hostingersite.com/wp-content/uploads/2026/04/resized_logo_no_stretch.png" alt="Hotel The Black Stone">
```

### Footer About Blurb
```
FIND:
<p>Laboriosam blandit suspendisse ducimus voluptate commodi, itaque. Veritatis iac ulisarchitecto, eiusmillo ea eleifendte mpore,debitis! Atque hac. Veritatis commodi, itaque.</p>

REPLACE WITH:
<p>Hotel The Black Stone — KHB Colony, Koramangala, Bengaluru. Affordable rooms with modern amenities, complimentary breakfast, and warm hospitality just 180 m from Jyoti Nivas College Road.</p>
```

### Footer Address
```
FIND:
<span class="elementor-icon-list-text">Address : 22th Streets, Colorado</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Address : 125, 1st Cross Rd, KHB Colony, 5th Block, Koramangala, Bengaluru – 560095</span>
```

### Footer Email
```
FIND:
<span class="elementor-icon-list-text">Email : info@example.com</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Email : info@hoteltheblackstone.in</span>
```

### Footer Phone
```
FIND:
<span class="elementor-icon-list-text">Phone : +988-256-266-88</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Phone : +91 08884803777</span>
```

### Footer Fax → WhatsApp
```
FIND:
<span class="elementor-icon-list-text">Fax : (+01)125-365-88</span>

REPLACE WITH:
<span class="elementor-icon-list-text">WhatsApp : +91 08884803777</span>
```

### Footer Copyright
```
FIND:
Copyright © 2026 Bosa Hotel. Powered by

REPLACE WITH:
Copyright © 2026 Hotel The Black Stone. Website by AdsPilot |
```

---

---

# PART 2 — HOMEPAGE

**Page URL:** /  
**WordPress Admin:** Pages → Home → SEO Settings

---

## META — Homepage

*(Set in Rank Math / Yoast)*

| Field | Value |
|-------|-------|
| Meta Title | `Hotel The Black Stone – Affordable Hotel in Koramangala, Bengaluru \| Book Direct` |
| Meta Description | `Hotel The Black Stone offers clean, air-conditioned rooms from ₹2,200/night in KHB Colony, Koramangala, Bengaluru. Free Wi-Fi, complimentary breakfast, 24/7 service. 180 m from Jyoti Nivas College Road. Call +91 08884803777.` |

> Title = 81 chars (trim if SEO plugin flags it). Description = 222 chars — trim to: "Affordable hotel in KHB Colony, Koramangala, Bengaluru. Free Wi-Fi, breakfast & 24/7 service. 180 m from Jyoti Nivas College Road. From ₹2,200/night. Call +91 08884803777." = 171 chars.

---

## SCHEMA MARKUP — Homepage (Add to `<head>` or via Rank Math Custom Schema)

> **What is Schema?** Invisible code that tells Google exactly what your business is. When Google answers questions like "hotels near Jyoti Nivas College Road Koramangala," this code helps it display your hotel's name, price, address, and phone directly in results — without the user clicking.  
> Add via Rank Math → Schema → Custom Schema, or paste in WordPress → Appearance → Theme Editor → header.php before `</head>`.

```json
{
  "@context": "https://schema.org",
  "@type": "Hotel",
  "name": "Hotel The Black Stone",
  "description": "Affordable hotel in KHB Colony, Koramangala, Bengaluru. Clean, air-conditioned rooms with free Wi-Fi, complimentary breakfast, and 24/7 front desk service. 180 m from Jyoti Nivas College Road.",
  "url": "https://chocolate-leopard-997635.hostingersite.com/",
  "telephone": "+910888480377",
  "email": "info@hoteltheblackstone.in",
  "priceRange": "₹₹",
  "checkinTime": "12:00",
  "checkoutTime": "12:00",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "125, 1st Cross Rd, near Jyoti Nivas College Road, KHB Colony, 5th Block",
    "addressLocality": "Koramangala",
    "addressRegion": "Karnataka",
    "postalCode": "560095",
    "addressCountry": "IN"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": 12.9344531,
    "longitude": 77.6165832
  },
  "amenityFeature": [
    {"@type": "LocationFeatureSpecification", "name": "Free Wi-Fi", "value": true},
    {"@type": "LocationFeatureSpecification", "name": "Complimentary Breakfast", "value": true},
    {"@type": "LocationFeatureSpecification", "name": "Free Parking", "value": true},
    {"@type": "LocationFeatureSpecification", "name": "24-Hour Front Desk", "value": true},
    {"@type": "LocationFeatureSpecification", "name": "Room Service", "value": true},
    {"@type": "LocationFeatureSpecification", "name": "Luggage Storage", "value": true},
    {"@type": "LocationFeatureSpecification", "name": "Laundry Service", "value": true},
    {"@type": "LocationFeatureSpecification", "name": "Airport Shuttle", "value": true},
    {"@type": "LocationFeatureSpecification", "name": "Air Conditioning", "value": true}
  ],
  "containsPlace": [
    {
      "@type": "HotelRoom",
      "name": "Deluxe Single Room",
      "description": "Cozy air-conditioned single room with free Wi-Fi and daily housekeeping.",
      "offers": {"@type": "Offer", "price": "2200", "priceCurrency": "INR"}
    },
    {
      "@type": "HotelRoom",
      "name": "Deluxe Double Room",
      "description": "Spacious double room with flat-screen TV and modern furnishings.",
      "offers": {"@type": "Offer", "price": "2500", "priceCurrency": "INR"}
    },
    {
      "@type": "HotelRoom",
      "name": "Super Deluxe Single Room",
      "description": "Premium single room with upgraded bedding and enhanced amenities.",
      "offers": {"@type": "Offer", "price": "2600", "priceCurrency": "INR"}
    },
    {
      "@type": "HotelRoom",
      "name": "Super Deluxe Double Room",
      "description": "Well-furnished double room ideal for couples with all modern comforts.",
      "offers": {"@type": "Offer", "price": "3000", "priceCurrency": "INR"}
    },
    {
      "@type": "HotelRoom",
      "name": "Super Deluxe Triple Room",
      "description": "Spacious triple room suitable for small groups or families.",
      "offers": {"@type": "Offer", "price": "3500", "priceCurrency": "INR"}
    },
    {
      "@type": "HotelRoom",
      "name": "Single Suite",
      "description": "Suite-style stay with luxury finishing and extra comfort.",
      "offers": {"@type": "Offer", "price": "4500", "priceCurrency": "INR"}
    }
  ],
  "hasMap": "https://maps.app.goo.gl/[BLACK-STONE-GOOGLE-MAPS-LINK]"
}
```

> ⚠️ Replace the `hasMap` value with the actual Black Stone Google Maps share link. Get it from Google Maps → Share → Copy Link.

---

## SECTION 1 — Hero Banner (H1)

> **Heading hierarchy note:** The hero headline is the single most important heading on the page (H1). Only one H1 per page. It must contain the primary keyword for Google to understand what this page is about. All subsequent section headings use H2. Card and item headings use H3.

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">The Luxury Experience With Beautiful &amp; Unique Place</h2>

REPLACE WITH:
<h1 class="ekit-heading--title elementskit-section-title ">Affordable Hotel in Koramangala, Bengaluru</h1>
```

> **Note for developer:** Change the HTML tag from `<h2>` to `<h1>` for this hero headline only. In Elementor, use the widget's "HTML Tag" dropdown and set to H1. All other section headings remain H2.

### Hero Subtext
```
FIND:
<p>&nbsp;At Black Diamond Hotel, we believe a great stay goes beyond a comfortable room. It's about creating moments that feel effortless and memorable.</p>

REPLACE WITH:
<p>Hotel The Black Stone — just 180 m from Jyoti Nivas College Road in KHB Colony, Koramangala. Clean rooms, free Wi-Fi, complimentary breakfast, and genuine Bengaluru hospitality from ₹2,200/night.</p>
```

---

## SECTION 2 — About Us Snippet (H2)

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">We can help you feel more comfortable</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">We Make Every Stay Feel Like Home</h2>
```

### About Paragraph
```
FIND:
<p>Founded with a passion for hospitality, our hotel combines modern amenities with warm, attentive service. Located in Koramangala, we provide the perfect base to explore everything koramangala has to offer.</p>

REPLACE WITH:
<p>Nestled in KHB Colony, 5th Block, just 180 m from Jyoti Nivas College Road, Hotel The Black Stone offers clean, air-conditioned rooms with free Wi-Fi, complimentary breakfast, and round-the-clock service — all at an honest, budget-friendly price.</p>
```

### Bullet Point
```
FIND:
<span class="elementor-icon-list-text">Our team is dedicated to making every guest feel at home — whether it's your first visit or your tenth.</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Our team is here 24/7 — whether it is your first visit or your fiftieth, you will always leave with a smile.</span>
```

### Progress Bars
```
FIND:    data-value="90"   (label: Positive Reviews)
REPLACE: data-value="95"

FIND:    data-value="98"   (label: Happy Customers)
REPLACE: data-value="92"
```
> ⚠️ Confirm both values with client.

---

## SECTION 3 — Facilities (H2)

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">Our Facilities</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Everything You Need for a Comfortable Stay</h2>
```

### Intro Paragraph
```
FIND:
<p>Each of our rooms and suites is crafted to offer a relaxing retreat after a day of travel or exploration.</p>

REPLACE WITH:
<p>From free Wi-Fi and complimentary breakfast to room service, laundry, and free parking — everything is in place so you can simply relax.</p>
```

### Facility Card 1 — Room Services
```
FIND:
<p>Enjoy the convenience of our in-room dining service, available to bring freshly prepared meals مباشرة to your door.</p>

REPLACE WITH:
<p>Hot meals and snacks delivered fresh to your room — available any time of the day.</p>
```

### Facility Card 2 — Swimming Pool (lorem ipsum 1st instance)
```
FIND:
<p>Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.</p>

REPLACE WITH:
<p>Cool off and unwind in our clean, well-maintained pool after a long day in the city.</p>
```

### Facility Card 3 — Tea & Breakfast (lorem ipsum 2nd instance)
```
FIND:
<p>Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.</p>

REPLACE WITH:
<p>Start your morning right with complimentary tea and breakfast served fresh daily for all guests.</p>
```

---

## SECTION 4 — Stats Counters

```
FIND:    data-to-value="23"   (label: Happy Clients)
REPLACE: data-to-value="500"

FIND:    data-to-value="600"  (label: Our Staffs)
REPLACE: data-to-value="15"

FIND:    data-to-value="420"  (label: Luxury Rooms)
REPLACE: data-to-value="20"

FIND:    data-to-value="40"   (label: Win Awards)
REPLACE: data-to-value="5"
```
> ⚠️ All 4 values need client confirmation.

---

## SECTION 5 — Rooms (H2)

### Section Intro
```
FIND:
<p>Laboris eum eligendi dapibus euismod proin, vivamus, rutrum iusto minim, delectus tempore corrupti elementum cubilia rerum. Conubia officiis, eges fugiat error natoque libero.</p>
(inside the BEST LUXURY ROOM heading block)

REPLACE WITH:
<p>Choose from our six room types — each designed for comfort, cleanliness, and a restful night's sleep in the heart of KHB Colony, Koramangala.</p>
```

### Room Cards (H3 — replace all 6 lorem ipsum descriptions in order)
```
FIND (all 6 instances):
<p>Purus cumque consectetuer facere cubilia urna nostra aliquip, eum suscipit.</p>
```

**Card 1 — Deluxe Single Room** → `<p>Cozy, air-conditioned room with a comfortable single bed, free Wi-Fi, and daily housekeeping. From ₹2,200/night.</p>`

**Card 2 — Deluxe Double Room** → `<p>Spacious double room with flat-screen TV, modern furnishings, and complimentary breakfast included. From ₹2,500/night.</p>`

**Card 3 — Super Deluxe Single** → `<p>An upgraded single room with premium bedding, enhanced amenities, and all the comforts you need. From ₹2,600/night.</p>`

**Card 4 — Super Deluxe Double** → `<p>Perfect for couples — a well-furnished double room with modern comforts and complimentary breakfast. From ₹3,000/night.</p>`

**Card 5 — Super Deluxe Triple** → `<p>Ideal for small groups or families, with ample space, premium amenities, and all essentials included. From ₹3,500/night.</p>`

**Card 6 — Single Suite** → `<p>Our most spacious offering — suite-style comfort with luxury finishing and extra room to relax. From ₹4,500/night.</p>`

### Fix Wrong Currency on Suite Card
```
FIND:
<h2 class="ekit-heading--title elementskit-section-title "><span><span>$100</span></span>/NIGHT</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title "><span><span>₹4,500</span></span>/NIGHT</h2>
```
> ⚠️ Confirm price with client.

---

## SECTION 6 — Feature Icons (H3 level — 4 mini highlights)

### Value For Money
```
FIND (1st instance):
<p>Deleniti nulla class primis corporis proin dignissim.</p>

REPLACE WITH:
<p>Quality rooms at honest, budget-friendly prices — no hidden charges.</p>
```

### Store Luggage
```
FIND (2nd instance):
<p>Deleniti nulla class primis corporis proin dignissim.</p>

REPLACE WITH:
<p>Secure luggage storage for early arrivals and late check-outs.</p>
```

### Passionate Room → rename heading
```
FIND heading:
<h2 class="ekit-heading--title elementskit-section-title ">Passionate Room</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Well-Kept Rooms</h2>
```
```
FIND (3rd instance):
<p>Deleniti nulla class primis corporis proin dignissim.</p>

REPLACE WITH:
<p>Every room is cleaned and prepared with careful attention before each guest arrives.</p>
```

### Diverse Destination
```
FIND (4th instance):
<p>Deleniti nulla class primis corporis proin dignissim.</p>

REPLACE WITH:
<p>Steps from Jyoti Nivas College Road, cafes, restaurants, and 1.1 km from Nexus Mall Koramangala.</p>
```

---

## SECTION 7 — Testimonials (H2)

```
FIND:
<p>Laboris eum eligendi dapibus euismod proin, vivamus, rutrum iusto minim, delectus tempore corrupti elementum cubilia rerum. Conubia officiis, eges fugiat error natoque libero.</p>
(inside the OUR TESTIMONIAL heading block)

REPLACE WITH:
<p>Hear what our guests say about staying at Hotel The Black Stone, Koramangala.</p>
```

### Review 1 Text
```
FIND:
<p>I had an excellent experience at this hotel. From check-in to check-out, everything was smooth and professional. The room was spotless, well-maintained, and very comfortable. The staff went above and beyond to make sure my stay was enjoyable. The amenities were great, especially the breakfast and pool area. Highly recommend this place for anyone looking for quality and comfort.</p>

REPLACE WITH:
<p>Exactly what I needed — clean room, friendly staff, and a great location near Jyoti Nivas College Road. Complimentary breakfast was a lovely touch. Will definitely be back on my next Bengaluru trip.</p>
```

### Review 1 Name
```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">Deepak Kumar</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Shankar N.</h2>
```

### Review 2 Text
```
FIND:
<p>The hotel overall was nice and in a convenient location. The room was clean, and the staff were polite. However, the Wi-Fi was a bit slow, and the check-in process took longer than expected. With a few improvements, this could be an excellent place to stay.</p>

REPLACE WITH:
<p>Good value for money in Koramangala. Tidy room, comfortable bed, and smooth check-in. Wi-Fi was solid and the location is ideal — plenty of eateries and recreation spots within walking distance.</p>
```

### Review 2 Name
```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">pooja kumari</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Deepak S.</h2>
```
> ⚠️ Replace both reviews with real Google review text and actual reviewer names from the Black Stone's Google Maps listing.

---

## SECTION 8 — Blog Intro (H2)

```
FIND:
<p>Laboris eum eligendi dapibus euismod proin, vivamus, rutrum iusto minim, delectus tempore corrupti elementum cubilia rerum. Conubia officiis, eges fugiat error natoque libero.</p>
(inside the RECENT BLOG heading block)

REPLACE WITH:
<p>Travel tips, local guides, and hospitality insights from our team at Hotel The Black Stone, Koramangala.</p>
```

---

---

# PART 3 — ABOUT US PAGE

**Page URL:** /about-us/  
**WordPress Admin:** Pages → About Us → SEO Settings

---

## META — About Us

| Field | Value |
|-------|-------|
| Meta Title | `About Us – Hotel The Black Stone \| KHB Colony, Koramangala, Bengaluru` |
| Meta Description | `Learn about Hotel The Black Stone — an affordable boutique hotel in KHB Colony, Koramangala, Bengaluru. Modern rooms, genuine hospitality, and everything you need for a comfortable stay near Jyoti Nivas College Road.` |

> Title = 70 chars. Description = 218 chars — trim to: "Hotel The Black Stone, Koramangala — affordable rooms, warm hospitality, and modern comfort in KHB Colony, Bengaluru." = 116 chars.

---

## SECTION 1 — Main Heading (H1)

```
FIND (About Us page body only — not homepage):
<h2 class="ekit-heading--title elementskit-section-title ">We can help you feel more comfortable</h2>

REPLACE WITH:
<h1 class="ekit-heading--title elementskit-section-title ">About Hotel The Black Stone, Koramangala</h1>
```
> Change `<h2>` to `<h1>` for this page's main heading only. Use Elementor HTML Tag setting.

---

## SECTION 2 — Main Intro Paragraph (keep but fix hotel name)

```
FIND:
<p>Welcome to The Black Diamond, where comfort feels like home and every guest is treated like family. We pride ourselves on creating a warm, inviting atmosphere paired with quality service and attention to detail. Whether you're here for a short visit or an extended stay, we aim to make every moment special.</p>

REPLACE WITH:
<p>Welcome to Hotel The Black Stone, where comfort feels like home and every guest is treated like family. We pride ourselves on creating a warm, inviting atmosphere paired with quality service and attention to detail. Whether you are here for a short visit or an extended stay, we aim to make every moment special.</p>
```

### Bullet Point 1
```
FIND:
<span class="elementor-icon-list-text">The Black Diamond is a symbol of strength, elegance, and rarity.</span>

REPLACE WITH:
<span class="elementor-icon-list-text">The Black Stone stands for strength, stability, and enduring quality — values that shape every aspect of our hospitality.</span>
```

### Bullet Point 2
```
FIND:
<span class="elementor-icon-list-text">Our hotel embodies these qualities by offering exceptional comfort, modern design, and personalized hospitality—creating a stay that's truly one of a kind.</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Our hotel reflects these values through clean, well-maintained rooms, attentive staff, and a genuine commitment to making your stay memorable.</span>
```

---

## SECTION 3 — Second Text Block (below photo carousel)

```
FIND:
<p>The Black Diamond is more than a place to stay—it's an experience. Designed for travelers who appreciate style, comfort, and exceptional service, our hotel delivers a seamless blend of modern amenities and timeless design. From relaxing spaces to vibrant surroundings, we provide the perfect setting to unwind, connect, and explore.</p>

REPLACE WITH:
<p>Hotel The Black Stone is more than a place to stay — it is a genuine experience. Designed for travellers who value cleanliness, comfort, and friendly service, our hotel blends modern amenities with a warm atmosphere. From our well-furnished rooms to the vibrant streets of KHB Colony and Koramangala, we provide the perfect setting to unwind, connect, and explore.</p>
```

---

## SECTION 4 — Progress Bars

```
FIND:    data-value="90"   (label: Positive Reviews)
REPLACE: data-value="95"

FIND:    data-value="98"   (label: Happy Customers)
REPLACE: data-value="92"
```
> ⚠️ Confirm with client.

---

## SECTION 5 — OUR VALUES Heading (H2)

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">Visit Our Natural Paradise &amp; Reconnect With Yourself</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">What Makes Hotel The Black Stone Different</h2>
```

### OUR VALUES Paragraph
```
FIND:
<p>At The Black Diamond, we redefine modern luxury with a bold edge. Inspired by the rarity and strength of the black diamond, our hotel blends refined elegance with contemporary comfort. Every detail—from our thoughtfully designed rooms to our personalized service—is crafted to create an unforgettable stay. Whether you're visiting for business or leisure, The Black Diamond offers a sanctuary where sophistication meets warmth.</p>

REPLACE WITH:
<p>At Hotel The Black Stone, we believe in delivering quality without compromise. Inspired by the strength and reliability of the black stone, our hotel blends clean, modern comfort with genuine warmth. Every detail — from our carefully maintained rooms to our attentive service — is crafted to give you a stay worth remembering. Whether you are visiting for business or leisure, The Black Stone offers a welcoming retreat in the heart of Koramangala.</p>
```

---

## SECTION 6 — Stats Counters (About Us version — different IDs from Homepage)

```
FIND:    data-to-value="25"   (label: Years Experience)
REPLACE: data-to-value="10"

FIND:    data-to-value="420"  (label: Luxury Rooms)
REPLACE: data-to-value="20"

FIND:    data-to-value="23"   (label: Satisfied Guest)
REPLACE: data-to-value="500"
```
> ⚠️ All 3 values need client confirmation.

---

## SECTION 7 — YouTube Video

```
FIND:
href="https://www.youtube.com/embed/VhBl3dHT5SY?feature=oembed?playlist=VhBl3dHT5SY&amp;mute=0&amp;autoplay=0&amp;loop=no&amp;controls=0&amp;start=0&amp;end="

REPLACE WITH:
href="[CLIENT'S YOUTUBE VIDEO URL]"
```
> ⚠️ If no video available, hide this section in Elementor or replace with a real hotel photo.

---

---

# PART 4 — FACILITIES PAGE

**Page URL:** /facilities/  
**WordPress Admin:** Pages → Facilities → SEO Settings

---

## META — Facilities

| Field | Value |
|-------|-------|
| Meta Title | `Hotel Facilities – Hotel The Black Stone \| KHB Colony, Koramangala, Bengaluru` |
| Meta Description | `Hotel The Black Stone offers free Wi-Fi, complimentary breakfast, room service, free parking, laundry, luggage storage, airport shuttle, and pick-up & drop in KHB Colony, Koramangala, Bengaluru.` |

> Title = 77 chars (trim if needed). Description = 193 chars — trim to: "Free Wi-Fi, breakfast, room service, parking, laundry & luggage storage at Hotel The Black Stone, KHB Colony, Koramangala, Bengaluru." = 131 chars.

---

## FACILITIES PAGE — H1

```
FIND (Facilities page banner heading — first instance):
<h2 class="ekit-heading--title elementskit-section-title ">Our Facilities</h2>

REPLACE WITH:
<h1 class="ekit-heading--title elementskit-section-title ">Hotel Facilities – Hotel The Black Stone</h1>
```

---

## FACILITY CARDS — 9 Cards (H3 card titles — keep titles as-is, replace descriptions only)

> All 9 card images load from `demo.bosathemes.com` — each URL is listed below. Client must upload real photos and paste new URLs.

---

### CARD 1 — Spa & Wellness

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-7.jpg
REPLACE WITH: [Upload real spa/wellness photo → paste new URL]
```

**Description:**
```
FIND (under Spa & Wellness):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Unwind and recharge at our in-house Spa & Wellness centre. Trained therapists offer relaxing massages and rejuvenating treatments tailored for your complete relaxation. Available daily for all guests.
```

---

### CARD 2 — Laundry Service

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-8.jpg
REPLACE WITH: [Upload real laundry/service photo → paste new URL]
```

**Description:**
```
FIND (under Laundry Service):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Keep your clothes fresh with our reliable same-day laundry service. We handle washing, ironing, and folding — just hand over your clothes and we take care of the rest, promptly and carefully.
```

---

### CARD 3 — Store Luggage

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-9-1.jpg
REPLACE WITH: [Upload real luggage area or reception photo → paste new URL]
```

**Description:**
```
FIND (under Store Luggage):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Secure luggage storage available before check-in and after check-out. Drop your bags at the front desk and explore Koramangala freely — we will keep everything safe until you return.
```

---

### CARD 4 — Parking Space

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-4.jpg
REPLACE WITH: [Upload real parking area photo → paste new URL]
```

**Description:**
```
FIND (under Parking Space):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Free on-site parking available for all guests arriving by car. Drive in with peace of mind knowing your vehicle is safe on our premises throughout your stay. Subject to availability — inform us in advance.
```

---

### CARD 5 — Pick Up & Drop

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-5.jpg
REPLACE WITH: [Upload relevant transport/vehicle photo → paste new URL]
```

**Description:**
```
FIND (under Pick Up & Drop):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Need a ride to the airport or railway station? Our paid pick-up and drop service ensures you travel comfortably without the hassle of finding a cab. Book through the front desk — we arrange everything on time.
```

---

### CARD 6 — Fiber Internet

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-6.jpg
REPLACE WITH: [Upload room/work desk or Wi-Fi themed photo → paste new URL]
```

**Description:**
```
FIND (under Fiber Internet):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Stay connected with high-speed fiber Wi-Fi, available across all rooms and common areas — completely free for all guests. Reliable enough for video calls, remote work, and streaming.
```

---

### CARD 7 — Room Services

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-1.jpg
REPLACE WITH: [Upload in-room dining or housekeeping photo → paste new URL]
```

**Description:**
```
FIND (under Room Services):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Our attentive room service team is available around the clock for food orders, housekeeping requests, extra towels, and more — all delivered promptly to your door.
```

---

### CARD 8 — Swimming Pool

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-2.jpg
REPLACE WITH: [Upload real swimming pool photo → paste new URL]
```

**Description:**
```
FIND (under Swimming Pool):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Take a refreshing dip in our clean, well-maintained swimming pool — open daily for all guests. A perfect way to unwind after a day of meetings or sightseeing in Bengaluru.
```

---

### CARD 9 — Tea & Breakfast

**Image:**
```
FIND src: https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-3.jpg
REPLACE WITH: [Upload real breakfast/dining photo → paste new URL]
```

**Description:**
```
FIND (under Tea & Breakfast):
Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.

REPLACE WITH:
Start every morning right with our complimentary tea and breakfast — fresh hot beverages, eggs, bread, and local favourites served daily to fuel your day in Bengaluru.
```

---

---

# PART 5 — BLOG PAGE

**Page URL:** /blog/  
**Method:** WordPress Admin (no Elementor body edits needed — blog body is auto-generated)

---

## META — Blog Listing Page

*(WordPress Admin → Pages → Blog → SEO Settings)*

| Field | Value |
|-------|-------|
| Meta Title | `Hotel Blog – Travel Tips & Bengaluru Guides \| Hotel The Black Stone, Koramangala` |
| Meta Description | `Read articles from Hotel The Black Stone — your affordable hotel in KHB Colony, Koramangala, Bengaluru. Travel tips, local guides, and everything you need to know about staying near Jyoti Nivas College Road.` |

> Title = 81 chars. Description = 206 chars — trim if needed.

---

## BLOG POST META TITLES & DESCRIPTIONS

*(WordPress Admin → Posts → Edit each post → SEO Settings in Rank Math / Yoast)*

---

### Post 1 — Affordable Price For Quality Services

| Field | Value |
|-------|-------|
| Meta Title | `Affordable Hotel Rooms in Koramangala, Bengaluru \| Hotel The Black Stone` |
| Meta Description | `Looking for budget-friendly hotel rooms in Koramangala? Hotel The Black Stone offers clean, comfortable rooms from ₹2,200/night in KHB Colony, near Jyoti Nivas College Road, Bengaluru.` |

---

### Post 2 — The Best Hotel Booking Platform

| Field | Value |
|-------|-------|
| Meta Title | `Book Your Stay Directly \| Hotel The Black Stone, Koramangala Bengaluru` |
| Meta Description | `Skip the middleman — book directly with Hotel The Black Stone. Call +91 08884803777 or email info@hoteltheblackstone.in for best rates and personalised service in Koramangala.` |

---

### Post 3 — Easy Way To Find Your Best Hotel

| Field | Value |
|-------|-------|
| Meta Title | `How to Find Hotel The Black Stone, Koramangala \| KHB Colony, Bengaluru` |
| Meta Description | `Hotel The Black Stone is at 125, 1st Cross Rd, KHB Colony, Koramangala — 180 m from Jyoti Nivas College Road and 1.1 km from Nexus Mall. Easy to reach, free parking available.` |

---

### Post 4 — Beautifully Day Spend In The Hotel

| Field | Value |
|-------|-------|
| Meta Title | `A Day at Hotel The Black Stone, Koramangala Bengaluru` |
| Meta Description | `Complimentary breakfast, free Wi-Fi, room service, laundry, and pick-up & drop — discover how Hotel The Black Stone makes every day of your stay comfortable and effortless.` |

---

## BLOG POST BODY CONTENT

*(WordPress Admin → Posts → Edit each post → replace body text in the editor)*

---

### POST 1 — Affordable Price For Quality Services

**Body:**

At Hotel The Black Stone, we believe that comfort and affordability should go hand in hand. Located in KHB Colony, 5th Block, Koramangala — one of Bengaluru's most sought-after neighbourhoods — our hotel offers well-furnished rooms, prompt service, and all the essentials you need for a pleasant stay, without the premium price tag.

Whether you are a business traveller on a tight schedule or a family looking for a comfortable base to explore the city, our rates are designed to give you genuine value. Deluxe Single rooms start at just ₹2,200 per night, making us one of the best-value options near Jyoti Nivas College Road, just 1.1 km from Nexus Mall Koramangala.

Quality service does not have to come at a high cost — and at Hotel The Black Stone, we prove it every day.

**Excerpt:** At Hotel The Black Stone, comfort and affordability go hand in hand. Well-furnished rooms in KHB Colony, Koramangala from ₹2,200 per night.

---

### POST 2 — The Best Hotel Booking Platform

**Body:**

Booking your stay at Hotel The Black Stone is simple and hassle-free. Reach us directly by phone at +91 08884803777 or email info@hoteltheblackstone.in to check availability and confirm your reservation.

We always recommend booking directly with us for the best rates and personalised service. Unlike third-party platforms, a direct booking means you speak to our team, get accurate room information, and can request specific preferences — such as an early check-in, extra bedding, or a specific floor preference.

Our front desk team is available around the clock. Whether it is a last-minute booking or a planned stay weeks in advance, we will make sure your room is ready and waiting.

**Excerpt:** Booking your stay at Hotel The Black Stone is easy — call +91 08884803777 or email info@hoteltheblackstone.in for best rates and personalised service.

---

### POST 3 — Easy Way To Find Your Best Hotel

**Body:**

Finding the right hotel in Bengaluru can feel overwhelming — but if you need a clean, well-located, and affordable stay in Koramangala, Hotel The Black Stone is a straightforward choice.

We are at 125, 1st Cross Rd, KHB Colony, 5th Block, Koramangala — just 180 metres from Jyoti Nivas College Road. Easy to reach by cab, auto, or your own vehicle. Free parking is available on the premises.

Nearby you will find IT parks, hospitals, restaurants, shopping centres, and excellent road connectivity to Electronic City, BTM Layout, and Jayanagar. Nexus Forum Mall is just 1.1 km away. Whether your visit is for work, medical reasons, or leisure, our location puts you exactly where you need to be.

Find us on Google Maps: search **Hotel The Black Stone Koramangala** and we will be right there.

**Excerpt:** Located at 125, 1st Cross Rd, KHB Colony, Koramangala — 180 m from Jyoti Nivas College Road and 1.1 km from Nexus Mall. Hotel The Black Stone is perfectly placed for business and leisure stays in South Bengaluru.

---

### POST 4 — Beautifully Day Spend In The Hotel

**Body:**

A great hotel stay is not just about the room — it is about how you feel from the moment you walk in. At Hotel The Black Stone, every part of your experience is designed to feel easy and welcoming.

Start your morning with our complimentary tea and breakfast, freshly prepared each day. Spend your day in meetings, exploring Koramangala's vibrant cafes and markets, or simply relaxing in your room with high-speed fiber internet and attentive room service.

In the evening, return to a clean, well-maintained room that genuinely feels like a home away from home. Our housekeeping team ensures your space is fresh and ready whenever you need it.

We also offer luggage storage, laundry service, and pick-up & drop facilities — so you can focus entirely on your day while we handle the rest.

**Excerpt:** From a warm breakfast to attentive room service and reliable Wi-Fi — every detail at Hotel The Black Stone is designed to make your stay comfortable, easy, and memorable.

---

## BLOG — Author Display Name Fix

*(WordPress Admin → Users → Edit the author)*

| Field | Replace With |
|-------|-------------|
| Display Name | `Rajesh Kumar` |
| Nickname | `Rajesh Kumar` |
| "Display name publicly as" dropdown | Select `Rajesh Kumar` |

> **Why:** The current author shows as `adspilotwork@gmail.com` on the public blog — the raw email is visible to all visitors. This looks unprofessional and breaks guest trust.

---

---

# PART 6 — CONTACT US PAGE

**Page URL:** /contact-us/

---

## META — Contact Us

| Field | Value |
|-------|-------|
| Meta Title | `Contact Us – Hotel The Black Stone \| Koramangala, Bengaluru` |
| Meta Description | `Get in touch with Hotel The Black Stone. Call +91 08884803777, email info@hoteltheblackstone.in, or visit us at 125, 1st Cross Rd, KHB Colony, 5th Block, Koramangala, Bengaluru.` |

> Title = 60 chars. Description = 175 chars — trim if needed.

---

## CONTACT PAGE — H1

```
FIND (contact page banner/main heading):
<h2 class="ekit-heading--title elementskit-section-title ">Contact Us</h2>

REPLACE WITH:
<h1 class="ekit-heading--title elementskit-section-title ">Contact Hotel The Black Stone, Koramangala</h1>
```

---

## CONTACT PAGE — Body Text Fixes (currently says "The Black Diamond")

### Online Reservations Section
```
FIND:
<p>Our online reservation system makes booking your stay at The Black Diamond quick, secure, and convenient. With just a few clicks, you can select your preferred room, check availability in real time, and confirm your booking instantly.</p>

REPLACE WITH:
<p>Booking your stay at Hotel The Black Stone is quick and easy. Call us directly or send an email to check availability and confirm your reservation — our front desk team is available around the clock to assist you.</p>
```

### Drop A Line Section
```
FIND:
<p>Have a question or need assistance? Our friendly team at The Black Diamond is always ready to help. Get in touch with us anytime—we'd love to hear from you and make your experience exceptional.</p>

REPLACE WITH:
<p>Have a question or need assistance? Our friendly team at Hotel The Black Stone is always ready to help. Get in touch with us anytime — we would love to hear from you and make your stay exceptional.</p>
```

---

## CONTACT PAGE — Location Fix

```
FIND:
Hotel the BLACK DIAMOND
Hosur Rd, Tavarekere, BACKSIDE, opp. The Forum Mall, Koramangala, Bengaluru, Bangalore 560095

REPLACE WITH:
Hotel The Black Stone
125, 1st Cross Rd, near Jyoti Nivas College Road, KHB Colony, 5th Block, Koramangala, Bengaluru, Karnataka 560095
```

---

## CONTACT PAGE — Phone Fix

```
FIND:
+91 90080 77824

REPLACE WITH:
+91 08884803777
```

---

## CONTACT PAGE — Email Fix

```
FIND:
info@example.com, domain@example.com
(inside the Mail Address icon box)

REPLACE WITH:
info@hoteltheblackstone.in
```

---

## CONTACT PAGE — Demo Image

```
FIND src:
https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-20.jpg
(left image next to "Reception Always Open")

REPLACE WITH: [Upload real hotel reception or lobby photo → paste new URL]
```
> ⚠️ Client to provide image.

---

## CONTACT PAGE — Google Maps Embed

Update the map embed to point to the Black Stone's actual address:

```
FIND (in iframe src):
q=hotel%20the%20black%20diamond
(or any incorrect hotel name in the map query)

REPLACE WITH:
q=Hotel+The+Black+Stone+125+1st+Cross+Rd+KHB+Colony+Koramangala+Bengaluru
```

> **Better option:** Go to Google Maps → search "Hotel The Black Stone Koramangala" → Share → Embed a map → copy the full `<iframe>` code and replace the existing map embed entirely.

---

## SCHEMA MARKUP — Contact Page

Add this to the Contact Us page `<head>` (or via Rank Math Custom Schema for this page only):

```json
{
  "@context": "https://schema.org",
  "@type": "ContactPage",
  "name": "Contact Hotel The Black Stone",
  "url": "https://chocolate-leopard-997635.hostingersite.com/contact-us/",
  "mainEntity": {
    "@type": "Hotel",
    "name": "Hotel The Black Stone",
    "telephone": "+910888480377",
    "email": "info@hoteltheblackstone.in",
    "address": {
      "@type": "PostalAddress",
      "streetAddress": "125, 1st Cross Rd, near Jyoti Nivas College Road, KHB Colony, 5th Block",
      "addressLocality": "Koramangala",
      "addressRegion": "Karnataka",
      "postalCode": "560095",
      "addressCountry": "IN"
    },
    "openingHoursSpecification": {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"],
      "opens": "00:00",
      "closes": "23:59"
    }
  }
}
```

---

---

# PART 7 — FAQ SECTION (AEO + GEO)

> **What is AEO?** Answer Engine Optimization means structuring content so AI tools (Google AI Overview, ChatGPT, Perplexity, Gemini) can directly pull and display your answers when someone asks a question. FAQs with schema are the most effective way to achieve this.
>
> **What is GEO?** Generative Engine Optimization means making content easy for AI search engines to quote and cite. Clear, factual, direct answers get cited more often by AI assistants.
>
> Add these FAQs as a dedicated section on the Homepage or Contact Us page. Also add the JSON schema below to the Homepage `<head>`.

---

## FAQ Content (Add a new section to Homepage or Contact page)

**H2 heading for this section:**
```
Frequently Asked Questions – Hotel The Black Stone
```

---

**Q: Where is Hotel The Black Stone located?**  
A: Hotel The Black Stone is located at 125, 1st Cross Rd, near Jyoti Nivas College Road, KHB Colony, 5th Block, Koramangala, Bengaluru, Karnataka 560095. We are just 180 metres from Jyoti Nivas College Road and 1.1 km from Nexus Mall Koramangala.

---

**Q: What are the room rates at Hotel The Black Stone?**  
A: Room rates at Hotel The Black Stone start from ₹2,200 per night for a Deluxe Single Room. Other room types include Deluxe Double (₹2,500), Super Deluxe Single (₹2,600), Super Deluxe Double (₹3,000), Super Deluxe Triple (₹3,500), and Single Suite (₹4,500). All rates include complimentary breakfast and free Wi-Fi.

---

**Q: What facilities are available at Hotel The Black Stone?**  
A: Hotel The Black Stone offers free Wi-Fi, complimentary breakfast, 24-hour front desk, room service, free parking, laundry service, luggage storage, pick-up & drop (paid), spa & wellness centre, swimming pool, and a restaurant serving Indian and local cuisine.

---

**Q: What are the check-in and check-out times at Hotel The Black Stone?**  
A: Check-in is from 12:00 PM and check-out is by 12:00 PM. Early check-in and late check-out are available subject to room availability — please contact the front desk in advance at +91 08884803777.

---

**Q: How can I book a room at Hotel The Black Stone?**  
A: Book directly by calling +91 08884803777 or emailing info@hoteltheblackstone.in. Direct bookings receive the best rates and personalised service.

---

**Q: Is Hotel The Black Stone near Jyoti Nivas College Road?**  
A: Yes. Hotel The Black Stone is just 180 metres from Jyoti Nivas College Road, Koramangala — approximately a 2-minute walk. Nexus Mall Koramangala is 1.1 km away.

---

**Q: Is breakfast included at Hotel The Black Stone?**  
A: Yes, complimentary tea and breakfast is included for all guests every morning. The hotel also serves Indian and local cuisine throughout the day.

---

**Q: Is parking available at Hotel The Black Stone?**  
A: Yes, free on-site parking is available for guests arriving by car, subject to availability. Please inform the hotel in advance if you require parking.

---

**Q: Does Hotel The Black Stone offer airport transfer?**  
A: Yes, a paid pick-up and drop service is available for airport and railway station transfers. Contact the front desk at +91 08884803777 to arrange your pickup or drop-off.

---

## FAQ Schema Markup (Add to Homepage `<head>`)

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Where is Hotel The Black Stone located?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Hotel The Black Stone is located at 125, 1st Cross Rd, near Jyoti Nivas College Road, KHB Colony, 5th Block, Koramangala, Bengaluru, Karnataka 560095. We are 180 metres from Jyoti Nivas College Road and 1.1 km from Nexus Mall Koramangala."
      }
    },
    {
      "@type": "Question",
      "name": "What are the room rates at Hotel The Black Stone?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Room rates start from ₹2,200/night for a Deluxe Single Room. Other options: Deluxe Double (₹2,500), Super Deluxe Single (₹2,600), Super Deluxe Double (₹3,000), Super Deluxe Triple (₹3,500), Single Suite (₹4,500). All rates include complimentary breakfast and free Wi-Fi."
      }
    },
    {
      "@type": "Question",
      "name": "What facilities are available at Hotel The Black Stone?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Facilities include free Wi-Fi, complimentary breakfast, 24-hour front desk, room service, free parking, laundry, luggage storage, pick-up & drop (paid), spa & wellness, swimming pool, and a restaurant serving Indian and local cuisine."
      }
    },
    {
      "@type": "Question",
      "name": "What are the check-in and check-out times at Hotel The Black Stone?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Check-in is from 12:00 PM and check-out is by 12:00 PM. Early check-in and late check-out are available subject to availability — contact the front desk at +91 08884803777 in advance."
      }
    },
    {
      "@type": "Question",
      "name": "How can I book a room at Hotel The Black Stone?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Book directly by calling +91 08884803777 or emailing info@hoteltheblackstone.in. Direct bookings receive the best rates and personalised service."
      }
    },
    {
      "@type": "Question",
      "name": "Is Hotel The Black Stone near Jyoti Nivas College Road?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. Hotel The Black Stone is just 180 metres from Jyoti Nivas College Road, Koramangala — approximately a 2-minute walk. Nexus Mall Koramangala is 1.1 km away."
      }
    },
    {
      "@type": "Question",
      "name": "Is breakfast included at Hotel The Black Stone?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, complimentary tea and breakfast is included for all guests every morning. The hotel also serves Indian and local cuisine throughout the day."
      }
    },
    {
      "@type": "Question",
      "name": "Is parking available at Hotel The Black Stone?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, free on-site parking is available for guests, subject to availability. Please inform the hotel in advance if you require parking."
      }
    },
    {
      "@type": "Question",
      "name": "Does Hotel The Black Stone offer airport transfer?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, a paid pick-up and drop service is available for airport and railway station transfers. Contact the front desk at +91 08884803777 to arrange pickup or drop-off."
      }
    }
  ]
}
```

---

---

# PART 8 — MASTER CHECKLIST

Use this to track progress across all pages.

## Global (Apply Once)
- [ ] Fix header email: `info@example.com` → `info@hoteltheblackstone.in`
- [ ] Fix header location: `King Street, AUS` → `KHB Colony, 5th Block, Koramangala, Bengaluru`
- [ ] Fix header phone: `+01 (977) 2599 12` → `+91 08884803777`
- [ ] Fix header label: `24/7 HOTEL SERVICES` → `24/7 RESERVATIONS`
- [ ] Fix off-canvas sidebar blurb (lorem ipsum → real text)
- [ ] Fix footer logo (demo.bosathemes.com → site logo)
- [ ] Fix footer about blurb (lorem ipsum → real text)
- [ ] Fix footer address, email, phone
- [ ] Replace Fax with WhatsApp in footer
- [ ] Fix footer copyright (Bosa Hotel → Hotel The Black Stone)

## Homepage
- [ ] Set meta title & description
- [ ] Add Hotel schema JSON-LD to `<head>`
- [ ] Add FAQ schema JSON-LD to `<head>`
- [ ] Add FAQ content section to page body
- [ ] Change hero H2 → H1 (Elementor HTML Tag setting)
- [ ] Replace hero headline text (keyword: "Affordable Hotel in Koramangala, Bengaluru")
- [ ] Replace hero subtext
- [ ] Replace About section heading (H2)
- [ ] Replace About paragraph
- [ ] Replace bullet point text
- [ ] Fix progress bar values (confirm with client)
- [ ] Replace Facilities section heading + intro (H2)
- [ ] Fix all 3 facility card descriptions
- [ ] Fix stats counters (confirm with client)
- [ ] Replace Rooms section intro (H2)
- [ ] Replace all 6 room card descriptions (H3)
- [ ] Fix currency on Suite card ($100 → ₹4,500)
- [ ] Replace all 4 feature icon descriptions (H3)
- [ ] Rename "Passionate Room" → "Well-Kept Rooms"
- [ ] Replace testimonials section intro
- [ ] Replace Review 1 text + name (or use real Google review)
- [ ] Replace Review 2 text + name (or use real Google review)
- [ ] Replace Blog section intro

## About Us Page
- [ ] Set meta title & description
- [ ] Change main H2 → H1 "About Hotel The Black Stone, Koramangala"
- [ ] Fix main intro paragraph (Black Diamond → Black Stone)
- [ ] Fix bullet point 1 (Black Diamond → Black Stone)
- [ ] Fix bullet point 2
- [ ] Fix second text block (Black Diamond → Black Stone)
- [ ] Fix OUR VALUES heading (H2)
- [ ] Fix OUR VALUES paragraph (Black Diamond → Black Stone)
- [ ] Fix progress bar values (confirm with client)
- [ ] Fix stats counters (confirm with client)
- [ ] Replace/hide YouTube video placeholder

## Facilities Page
- [ ] Set meta title & description
- [ ] Change page banner H2 → H1 "Hotel Facilities – Hotel The Black Stone"
- [ ] Replace all 9 facility card descriptions (H3 card titles unchanged)
- [ ] Replace all 9 facility card images (client to upload real photos)

## Blog Page
- [ ] Set meta title & description for Blog listing page
- [ ] Set meta title & description for Post 1
- [ ] Set meta title & description for Post 2
- [ ] Set meta title & description for Post 3
- [ ] Set meta title & description for Post 4
- [ ] Replace body content for all 4 posts
- [ ] Add excerpts for all 4 posts
- [ ] Fix author display name → `Rajesh Kumar`

## Contact Us Page
- [ ] Set meta title & description
- [ ] Add ContactPage schema JSON-LD to `<head>`
- [ ] Change main H2 → H1 "Contact Hotel The Black Stone, Koramangala"
- [ ] Fix "Online Reservations" body text (Black Diamond → Black Stone)
- [ ] Fix "Drop A Line" body text (Black Diamond → Black Stone)
- [ ] Fix Our Location box (hotel name + address)
- [ ] Fix Our Phone box: `+91 90080 77824` → `+91 08884803777`
- [ ] Fix email in Mail Address icon box
- [ ] Update Google Maps embed to Black Stone's address
- [ ] Replace demo image with real hotel photo (client to provide)

---

## ⚠️ ITEMS REQUIRING CLIENT CONFIRMATION BEFORE PUBLISHING

| # | Item | Current | Confirm |
|---|------|---------|---------|
| 1 | Positive Reviews % | 90% → suggested 95% | Confirm real figure |
| 2 | Happy Customers % | 98% → suggested 92% | Confirm real figure |
| 3 | Years in Business | 25 (demo) → suggested 10 | Confirm actual years |
| 4 | Total Rooms | 420 (demo) → suggested 20 | Confirm actual room count |
| 5 | Happy/Satisfied Guests | 23 (demo) → suggested 500 | Confirm realistic figure |
| 6 | Awards Won | 40 (demo) → suggested 5 | Confirm actual number |
| 7 | Suite Price | $100 USD → suggested ₹4,500 | Confirm actual rate |
| 8 | Testimonials | Fake names → need real reviews | Share 2 real Google reviews with names |
| 9 | YouTube video | Placeholder → client's own video | Provide hotel video URL or hide section |
| 10 | Facility images (all 9) | Demo server images | Upload real hotel photos |
| 11 | Contact page image | Demo server image | Upload real reception photo |
| 12 | Google Maps link | Not set | Provide correct Google Maps share link for schema |

---

*Prepared by AdsPilot | Hotel The Black Stone — Master Content Dev Handoff | April 2026*
