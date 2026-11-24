# Portfolio Project Data — Aorus Gaming Shop Mobile App UIUX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/aorus_gaming_shop_mobile/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image02.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "aorus-gaming-shop-mobile-app-uiux-design",
  "code": "PRO-03 // UX-03",
  "title": "Aorus Gaming Shop Mobile App UIUX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2021",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/Aorus-Gaming-Shop-Mobile-App-UIUX-Design",
  "license": "MIT License",
  "banner": "/images/projects/aorus_gaming_shop_mobile/banner.webp",
  "summary": "Mobile e-commerce UI/UX concept for AORUS gaming hardware, streamlining component discovery, wishlist management, cart checkout, and order tracking.",
  "projectDescription": "Aorus Gaming Shop Mobile App UIUX Design is a high-fidelity mobile e-commerce concept for PC hardware enthusiasts. Across six core screens, it streamlines category browsing, multi-series catalog filtering, hardware specifications, wishlist curation, cart checkout, and order tracking.",
  "architectureSummary": "Persistent 5-tab mobile navigation linking Category Home, 3-column Hardware Catalog, Spec-Rich Product Detail, Wishlist, Cart, and Order Tracking.",
  "techStack": [
    "Figma",
    "WebP"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile App UI/UX Design",
    "targetPlatform": "Mobile (iOS & Android)",
    "primaryDomain": "Gaming Hardware E-Commerce",
    "architecturePipeline": "Discovery -> Catalog -> Detail -> Cart",
    "testingAndAudit": "Visual Screen Audit",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "platformType": "iOS & Android Mobile App",
    "designRole": "UI/UX Designer",
    "targetIndustry": "Gaming Hardware E-Commerce",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "General-purpose marketplaces rarely surface dense PC hardware compatibility details alongside fast purchasing flows. This concept addresses that gap by designing a dedicated AORUS mobile storefront where gamers compare chipset tiers, inspect technical specifications, apply wallet vouchers, and complete hardware orders cleanly.",
  "uiUxUserResearch": {
    "keyFindings": [
      {
        "method": "E-Commerce Interface Audit",
        "description": "Reviewed standard mobile marketplace product listings against the information needs of PC component buyers comparing motherboard chipsets and GPU editions.",
        "keyFinding": "Buyers require immediate access to socket, chipset, DDR5 memory, and display specifications alongside upfront IDR pricing and store verification.",
        "badge": "Spec Clarity"
      },
      {
        "method": "Purchase Flow Decomposition",
        "description": "Mapped key e-commerce tasks across browsing, saving high-ticket hardware, applying shipping vouchers, and monitoring payment or delivery status.",
        "keyFinding": "Surfacing wallet balance, voucher indicators, and itemized platform fees early reduces checkout friction for high-value hardware purchases.",
        "badge": "Checkout Transparency"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Raka Pratama",
      "role": "Custom PC Builder & Enthusiast Gamer",
      "demographics": "20-32 years old, Indonesian tech-savvy mobile shopper",
      "quote": "When comparing Z690 motherboards or RTX 3090 GPUs on mobile, I want specs, stock, and voucher savings visible without digging through nested menus.",
      "painPoints": [
        "Compatibility details such as LGA1700 socket and DDR5 support are hidden in dense paragraphs on generic marketplaces",
        "High-ticket component purchases feel risky without clear official store verification and itemized fee summaries"
      ],
      "goals": [
        "Compare motherboard generations and trims side by side before adding items to the cart",
        "Save candidate parts in a spec-summarized wishlist and track payment or delivery status effortlessly"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The mobile information architecture centers on a persistent five-tab bottom navigation bar paired with a top search input and wallet voucher strip. Users transition cleanly from six hardware categories into tiered product grids, store-backed product detail views, saved wishlists, cart summaries, and order status tracking.",
    "nodes": [
      {
        "section": "Home & Discovery",
        "screens": [
          "Home Category Hub (Motherboard, Graphics Card, RAM, PSU, AIO Cooler, Monitor)",
          "Global Search & Wallet/Voucher Header"
        ]
      },
      {
        "section": "Catalog & Product Evaluation",
        "screens": [
          "Motherboard 3x3 Series Grid (Z690, Z590, Z490)",
          "Product Detail (Specs, Official Store Card, Reviews)"
        ]
      },
      {
        "section": "Wishlist & Retention",
        "screens": [
          "Recent & Wishlist Dual-Pill Grid",
          "Edit Mode & Quick Add-to-Cart Cards"
        ]
      },
      {
        "section": "Cart & Order Lifecycle",
        "screens": [
          "Shopping Cart with Voucher & Fee Breakdown",
          "Order History with Status Filters & Review/Cancel Actions"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "Starting from the Home category hub, shoppers select a hardware line such as Motherboard, compare Z690, Z590, and Z490 models in a 3x3 catalog grid, inspect chipset specifications and seller metrics on the Product Detail screen, save items to Wishlist, review voucher-adjusted pricing in Cart, and track orders.",
    "steps": [
      {
        "step": "01",
        "title": "Category Selection & Wallet Check",
        "description": "User views available wallet funds and voucher status in the top bar, then selects a component category such as Motherboard from the six-tile Home grid.",
        "screenOrAction": "Home Hub -> Category Tile Tap"
      },
      {
        "step": "02",
        "title": "Multi-Tier Catalog Comparison",
        "description": "User scans the 3x3 Motherboard grid comparing Z690, Z590, and Z490 variants across Xtreme, Master, and Ultra tiers with direct bookmark or cart actions.",
        "screenOrAction": "Motherboard Catalog Grid"
      },
      {
        "step": "03",
        "title": "Specification & Seller Verification",
        "description": "User inspects the Z690 Aorus Xtreme gallery, rating summary, Aorus Official Store response metrics, and structured LGA1700/DDR5 specifications.",
        "screenOrAction": "Product Detail Screen"
      },
      {
        "step": "04",
        "title": "Wishlist & Recent Item Curation",
        "description": "User switches between Recent and Wishlist pills to compare saved GPUs, monitors, SSDs, and cases with condensed spec highlights and Add to cart buttons.",
        "screenOrAction": "Recent & Wishlist Screen"
      },
      {
        "step": "05",
        "title": "Cart Review & Order Tracking",
        "description": "User adjusts item quantity, confirms free shipping voucher application and total breakdown before checkout, and later tracks order status pills.",
        "screenOrAction": "Shopping Cart -> Order History"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Home Discovery, Motherboard Catalog & Product Detail Interface",
      "imageUrl": "/images/projects/aorus_gaming_shop_mobile/image01.webp"
    },
    {
      "title": "Wishlist Management, Shopping Cart & Order Tracking Interface",
      "imageUrl": "/images/projects/aorus_gaming_shop_mobile/image02.webp"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Aorus Midnight Canvas",
        "hex": "#000036",
        "role": "Primary Background",
        "usage": "Deep gaming backdrop behind screen frames, header chrome, and dark overlay surfaces"
      },
      {
        "name": "Neon Cyber Cyan",
        "hex": "#18B0E8",
        "role": "Brand Accent",
        "usage": "Ambient gaming light streaks and visual energy highlights across category backdrops"
      },
      {
        "name": "Card Pure White",
        "hex": "#FFFFFF",
        "role": "Surface",
        "usage": "Product catalog cards, search inputs, wallet bar, and technical specification containers"
      },
      {
        "name": "Lavender Action Pill",
        "hex": "#A880F8",
        "role": "Secondary Action",
        "usage": "Add to cart pill buttons across catalog grid and wishlist cards"
      },
      {
        "name": "Checkout Royal Blue",
        "hex": "#002888",
        "role": "Primary Action",
        "usage": "Proceed to checkout primary CTA button on the Shopping Cart screen"
      },
      {
        "name": "Cart Soft Pink",
        "hex": "#FFD1EE",
        "role": "Highlight Surface",
        "usage": "Active shopping cart item card container highlighting store and voucher status"
      },
      {
        "name": "Order Blush Rose",
        "hex": "#FFD8DE",
        "role": "Card Surface",
        "usage": "Transaction history item cards separating individual order dates and status badges"
      }
    ],
    "typography": [
      {
        "name": "Gaming Display Header",
        "role": "Screen Heading",
        "font": "Sans-Serif Display",
        "sizeWeight": "22px / Bold Italic",
        "usage": "High-impact titles such as Shopping Cart and AORUS brand section headers"
      },
      {
        "name": "Price & Metric Emphasis",
        "role": "Numeric Heading",
        "font": "Sans-Serif",
        "sizeWeight": "18px / SemiBold",
        "usage": "Indonesian Rupiah price callouts, wallet balance, and cart total breakdown"
      },
      {
        "name": "Card Title & Specs Body",
        "role": "Body",
        "font": "Sans-Serif",
        "sizeWeight": "12px / Regular-Medium",
        "usage": "Hardware product titles, store metadata, and multi-line Product Details specs"
      },
      {
        "name": "Badge & Button Microcopy",
        "role": "Label",
        "font": "Sans-Serif",
        "sizeWeight": "10px / Medium",
        "usage": "Add to cart pills, order status tags, and compact filter dropdown labels"
      }
    ],
    "componentStates": [
      {
        "component": "Add to Cart & Checkout CTA",
        "states": ["Default", "Active"],
        "notes": "Rounded pill and rectangular buttons with high-contrast label legibility over light and dark surfaces"
      },
      {
        "component": "Bottom Navigation Tab",
        "states": ["Default", "Active"],
        "notes": "Five-icon persistent bar highlighting the current active screen tab with elevated light container contrast"
      },
      {
        "component": "Order Status & Filter Pills",
        "states": ["Waiting for payment", "Done", "Canceled"],
        "notes": "Semantic color-coded status tags paired with contextual Cancel or Leave a review actions"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "susScore": "Not Measured (Static Concept Archive)",
    "taskSuccessRate": "Not Measured (Static Concept Archive)",
    "timeOnTask": "Not Measured (Static Concept Archive)",
    "iterations": [
      {
        "usabilityIssue": "Dense motherboard technical specifications risk low legibility over patterned neon backgrounds",
        "iterationSolution": "Isolated catalog cards, product details, and cart items onto high-contrast white and soft pink surfaces",
        "impact": "Preserved gaming brand identity in the outer frame while keeping specs and IDR prices readable"
      },
      {
        "usabilityIssue": "Multi-step checkout totals and shipping discounts can feel opaque before payment",
        "iterationSolution": "Surfaced a dedicated Voucher badge inside the cart card paired with an itemized Subtotal, Shipping, Platform Fee, and Total summary",
        "impact": "Made final payable amounts and active free-shipping perks immediately verifiable prior to checkout"
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "High-Fidelity Visual Archive (WebP Exports)",
    "totalFrames": 6,
    "componentsCount": 16,
    "handoffSpecs": "Preserved as 1920x1080 showcase WebP boards covering 6 mobile screens, modular card grids, semantic status badges, and extracted HEX color tokens."
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "2-Column and 3-Column Grids",
    "designTokens": "High Contrast Gaming Tokens",
    "typography": "Sans-Serif & Display Headers",
    "prototypeFidelity": "High-Fidelity Static Mockups"
  }
}
```
