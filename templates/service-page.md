# [Service] in [City], [State] | [Brand Name]

<!-- META
Title: [Service] in [City] | [Brand Name]
Description: [130-155 chars. Lead with benefit, include service + city + brand.]
URL: /[service-slug]-[city-slug]/
-->

<!-- SCHEMA: Service, LocalBusiness, BreadcrumbList, FAQPage — see seo/schema.md -->
<!-- OG TAGS: title, description, image — match meta title/description -->

---

## Content

[Opening paragraph: 2-3 sentences. State the homeowner's problem. What are they dealing with? What do they need? Speak directly to them.]

[Second paragraph: Introduce your service as the solution. Keep it specific to the city and service. No fluff.]

### What [Service] Includes

| Component | Details |
|---|---|
| [Item 1] | [What the homeowner gets] |
| [Item 2] | [What the homeowner gets] |
| [Item 3] | [What the homeowner gets] |
| [Item 4] | [What the homeowner gets] |

### Materials and Options

| Material/Option | Best For | Price Range | Lifespan |
|---|---|---|---|
| [Option 1] | [Use case] | $X - $X | X years |
| [Option 2] | [Use case] | $X - $X | X years |
| [Option 3] | [Use case] | $X - $X | X years |

### How Much Does [Service] Cost in [City]?

[1-2 sentences framing the cost section. Be upfront.]

| Factor | Impact on Cost |
|---|---|
| [Factor 1] | [How it affects pricing] |
| [Factor 2] | [How it affects pricing] |
| [Factor 3] | [How it affects pricing] |

**Average cost in [City]:** $X,XXX - $X,XXX depending on [key variables].

*Pricing reflects [year] estimates for the [City] market. Request a quote for your specific project.*

> **[CTA] Get a Free Quote** — Call [phone] or fill out our online form.

### Our Process

1. **Free consultation** — [What happens during the visit]
2. **Custom proposal** — [What the homeowner receives]
3. **Scheduled installation** — [Timeline and what to expect]
4. **Final walkthrough** — [How you ensure quality]

### Why [City] Homeowners Choose [Brand]

- [Trust signal: license, certification]
- [Trust signal: years in business, project count]
- [Trust signal: guarantee or warranty]
- [Trust signal: star rating with review count]

[1-2 review snippets from real customers]

### Before and After

[Include 2-3 before/after project examples with descriptions. Each should have:]

**Project:** [Brief description — neighborhood, scope of work]
**Before:** [What the homeowner was dealing with]
**After:** [What was delivered]
<!-- Alt text: [Descriptive alt text with keyword] -->

### Frequently Asked Questions

**Q: [Common question about this service in this city]**
A: [Direct answer. 2-3 sentences max.]

**Q: [Cost or timeline question]**
A: [Direct answer with specific numbers where possible.]

**Q: [Materials or process question]**
A: [Direct answer. Reference a section above if helpful.]

**Q: [Permit or regulation question specific to the area]**
A: [Direct answer citing local codes or requirements.]

> **Ready to get started?** Call [phone] for a free estimate or [schedule online](link).

---

## SEO

### Target Keywords

| Type | Keyword | Search Intent |
|---|---|---|
| Primary | [service] [city] | Transactional |
| Secondary | [service] cost [city] | Informational/Transactional |
| Secondary | best [service] [city] | Transactional |
| Long-tail | [specific question about service in city] | Informational |

### Internal Links

- Link to: [related service page]
- Link to: [relevant blog post]
- Link to: [city/service area page]
- Link from: [blog posts that reference this service]

### Schema Markup

```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "name": "[Service] in [City]",
  "provider": {
    "@type": "LocalBusiness",
    "name": "[Brand Name]",
    "address": {
      "@type": "PostalAddress",
      "streetAddress": "[Street]",
      "addressLocality": "[City]",
      "addressRegion": "[State]",
      "postalCode": "[Zip]"
    },
    "telephone": "[Phone]",
    "url": "[Website URL]",
    "geo": {
      "@type": "GeoCoordinates",
      "latitude": "[Lat]",
      "longitude": "[Lng]"
    },
    "aggregateRating": {
      "@type": "AggregateRating",
      "ratingValue": "[X.X]",
      "reviewCount": "[X]"
    }
  },
  "areaServed": {
    "@type": "City",
    "name": "[City]",
    "sameAs": "[Wikipedia or authoritative URL for the city]"
  },
  "description": "[Service description]",
  "offers": {
    "@type": "Offer",
    "priceRange": "$X - $X"
  }
}
```

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "[Question 1]",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "[Answer 1]"
      }
    },
    {
      "@type": "Question",
      "name": "[Question 2]",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "[Answer 2]"
      }
    }
  ]
}
```

```json
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "[Website URL]"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "[Service Category]",
      "item": "[Category URL]"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "[Service] in [City]",
      "item": "[Page URL]"
    }
  ]
}
```

### Open Graph Tags

```html
<meta property="og:title" content="[Service] in [City] | [Brand Name]">
<meta property="og:description" content="[Same as meta description]">
<meta property="og:image" content="[Featured image URL — 1200x630px]">
<meta property="og:url" content="[Page URL]">
<meta property="og:type" content="website">
```

### NAP Block

**[Brand Name]**
[Street Address]
[City], [State] [Zip]
[Phone]
[Google Maps CID Link]
