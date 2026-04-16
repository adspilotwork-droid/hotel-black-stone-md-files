# Hotel The Black Stone — Contact Us Page Content Replacements

**Page URL:** https://chocolate-leopard-997635.hostingersite.com/contact-us/  
**Method:** FIND & REPLACE in HTML + WordPress Admin settings

---

## META TITLE & DESCRIPTION
*(WordPress Admin → Pages → Contact Us → SEO Settings via Rank Math / Yoast)*

| Field | Value |
|-------|-------|
| Meta Title | `Contact Us – Hotel The Black Stone, Koramangala Bengaluru` |
| Meta Description | `Get in touch with Hotel The Black Stone. Call +91 08884803777, email info@hoteltheblackstone.in, or visit us at 125, 1st Cross Rd, KHB Colony, 5th Block, Koramangala, Bengaluru.` |

> Title = 57 chars. Description = 176 chars — trim if needed to: "Reach Hotel The Black Stone in KHB Colony, Koramangala. Call +91 08884803777 or email info@hoteltheblackstone.in. We're always here to help." = 140 chars.

---

## PAGE SEO TITLE FIX
*(WordPress Admin → Pages → Contact Us → SEO Title)*

| Find | Replace With |
|------|-------------|
| `Contact Us – Hotel The Black Stone` | `Contact Us – Hotel The Black Stone` |

> ✅ Already correct — just confirm it hasn't reverted to "Black Diamond" anywhere.

---

## GLOBAL HEADER REPLACEMENTS
*(Fix once in Elementor header template)*

| Find | Replace With |
|------|-------------|
| `info@example.com` | `info@hoteltheblackstone.in` |
| `King Street, AUS` | `KHB Colony, 5th Block, Koramangala, Bengaluru` |
| `+01 (977) 2599 12` | `+91 08884803777` |

---

## HEADER PHONE SECTION (large number in nav bar)

| Find | Replace With |
|------|-------------|
| `+01 (977) 2599 12` | `+91 08884803777` |

---

## CONTACT US BODY — IMAGE REPLACEMENT

**Section: Left image next to "Reception Always Open"**

The image currently loads from the demo server:
```
src="https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-20.jpg"
```

| Find | Replace With |
|------|-------------|
| `https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-20.jpg` | *(Replace with a real hotel photo uploaded to the site — e.g., reception or lobby photo)* |

> ⚠️ Client to provide image. Upload to WordPress Media and paste the new URL.

---

## CONTACT US BODY — TEXT REPLACEMENTS

### "Online Reservations" section — REPLACE (says "The Black Diamond")

```
FIND:
<p>Our online reservation system makes booking your stay at The Black Diamond quick, secure, and convenient. With just a few clicks, you can select your preferred room, check availability in real time, and confirm your booking instantly.</p>

REPLACE WITH:
<p>Booking your stay at Hotel The Black Stone is quick and easy. Call us directly or send an email to check availability and confirm your reservation — our front desk team is available around the clock to assist you.</p>
```

### "Drop A Line" section heading — REPLACE (says "The Black Diamond")

```
FIND:
<p>Have a question or need assistance? Our friendly team at The Black Diamond is always ready to help. Get in touch with us anytime—we'd love to hear from you and make your experience exceptional.</p>

REPLACE WITH:
<p>Have a question or need assistance? Our friendly team at Hotel The Black Stone is always ready to help. Get in touch with us anytime — we'd love to hear from you and make your stay exceptional.</p>
```

### Our Location — REPLACE (says "Hotel the BLACK DIAMOND" and wrong address reference)

```
FIND:
Hotel the BLACK DIAMOND
Hosur Rd, Tavarekere, BACKSIDE, opp. The Forum Mall, Koramangala, Bengaluru, Bangalore 560095

REPLACE WITH:
Hotel The Black Stone
125, 1st Cross Rd, near Jyoti Nivas College Road, KHB Colony, 5th Block, Koramangala, Bengaluru, Karnataka 560095
```

### Our Phone — ALREADY CORRECT ✅

```
+91 90080 77824
```

> ⚠️ Wait — this is the Black Diamond number. REPLACE with Black Stone number:

```
FIND:
+91 90080 77824

REPLACE WITH:
+91 08884803777
```

### Mail Address — FIX

```
FIND:
info@example.com, domain@example.com

REPLACE WITH:
info@hoteltheblackstone.in
```

---

## CONTACT DETAILS — MAP EMBED

The Google Maps embed currently searches "hotel the black diamond" — update to search for Black Stone:

```
FIND (in iframe src):
q=Hotel%20The%20BlackStone

(or if it shows Black Diamond):
q=hotel%20the%20black%20diamond

REPLACE WITH:
q=Hotel%20The%20Black%20Stone%20Koramangala%20Bengaluru
```

> Or better: embed the specific Google Maps link for 125, 1st Cross Rd, KHB Colony, 5th Block, Koramangala. Get the embed code from Google Maps → Share → Embed a map.

---

## GLOBAL FOOTER REPLACEMENTS
*(Fix once in Elementor footer template)*

| Find | Replace With |
|------|-------------|
| Footer logo `src="https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/main-logo-2.png"` | `src="https://chocolate-leopard-997635.hostingersite.com/wp-content/uploads/2026/04/resized_logo_no_stretch.png"` |
| `Laboriosam blandit suspendisse ducimus...` (lorem ipsum blurb) | `Hotel The Black Stone — KHB Colony, Koramangala, Bengaluru. Affordable rooms with modern amenities, complimentary breakfast, and warm hospitality near Jyoti Nivas College Road.` |
| `Address : 22th Streets, Colorado` | `Address : 125, 1st Cross Rd, KHB Colony, 5th Block, Koramangala, Bengaluru – 560095` |
| `Email : info@example.com` | `Email : info@hoteltheblackstone.in` |
| `Phone : +988-256-266-88` | `Phone : +91 08884803777` |
| `Fax : (+01)125-365-88` | `WhatsApp : +91 08884803777` |
| `Copyright © 2026 Bosa Hotel. Powered by` | `Copyright © 2026 Hotel The Black Stone. Website by` |

---

## OFF-CANVAS SIDEBAR REPLACEMENT

| Find | Replace With |
|------|-------------|
| `Est adipisci rutrum minim hat dolorum, nobis nonummy natoque dolores delectus magna turpis.` | `Hotel The Black Stone — a comfortable and affordable stay in KHB Colony, Koramangala, just 180m from Jyoti Nivas College Road.` |

---

## SUMMARY CHECKLIST FOR DEVELOPER / ADMIN

- [ ] Set meta title & description for Contact Us page (Rank Math / Yoast)
- [ ] Fix header email, location, phone (global template)
- [ ] Fix large phone number in header nav: `+01 (977) 2599 12` → `+91 08884803777`
- [ ] Fix "Online Reservations" body text (Black Diamond → Black Stone)
- [ ] Fix "Drop A Line" body text (Black Diamond → Black Stone)
- [ ] Fix "Our Location" box: hotel name + address (Black Diamond → Black Stone)
- [ ] Fix "Our Phone" box: `+91 90080 77824` → `+91 08884803777`
- [ ] Fix "Mail Address" box: `info@example.com` → `info@hoteltheblackstone.in`
- [ ] Replace demo image next to "Reception Always Open" with real hotel photo
- [ ] Update Google Maps embed to point to Black Stone's address
- [ ] Fix footer logo (demo → correct URL)
- [ ] Fix footer blurb (lorem ipsum → real text)
- [ ] Fix footer address, email, phone (if not already done)
- [ ] Replace Fax with WhatsApp in footer
- [ ] Fix footer copyright (Bosa Hotel → Hotel The Black Stone)
- [ ] Fix off-canvas sidebar blurb

---

*Prepared by AdsPilot | Hotel The Black Stone — Contact Us Page Dev Handoff*
