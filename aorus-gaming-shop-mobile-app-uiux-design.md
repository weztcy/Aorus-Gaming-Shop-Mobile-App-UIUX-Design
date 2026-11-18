# Portfolio Project Data — Aorus Gaming Shop Mobile App UI/UX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/aorus_gaming_shop_mobile/`
- **Required Local Images:** `banner.webp`, `image01.webp`, `image02.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "aorus-gaming-shop-mobile-app-uiux-design",
  "code": "PRO-21 // UX-01",
  "title": "Aorus Gaming Shop Mobile App UI/UX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2021",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/Aorus-Gaming-Shop-Mobile-App-UIUX-Design",
  "license": "MIT License",
  "imageUrl": "/images/projects/aorus_gaming_shop_mobile/banner.webp",
  "images": [
    "/images/projects/aorus_gaming_shop_mobile/banner.webp"
  ],
  "summary": "Mobile e-commerce UX design for Aorus PC hardware, featuring streamlined component discovery, technical spec sheets, and seamless order tracking.",
  "projectDescription": "A mobile commerce UI/UX concept tailored for PC gaming enthusiasts and builders. The design provides immersive dark-mode visual merchandising, transparent technical specification matrices, seamless hardware compatibility verification, and end-to-end shopping cart checkout workflows.",
  "architectureSummary": "5-tab mobile shopping architecture linking category discovery, spec comparison, cart checkout, and live order tracking.",
  "techStack": [
    "Figma",
    "FigJam",
    "Adobe Photoshop",
    "Adobe Illustrator"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile E-Commerce Design",
    "targetPlatform": "Mobile (iOS & Android)",
    "primaryDomain": "Gaming Hardware & E-Commerce",
    "architecturePipeline": "Figma Component System & Flow",
    "testingAndAudit": "Validated",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "projectType": "End-to-End Mobile E-Commerce Design",
    "platformType": "Mobile (iOS & Android)",
    "designRole": "Lead UI/UX Designer",
    "targetPlatform": "iOS & Android",
    "targetIndustry": "Gaming Hardware & E-Commerce",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "Purchasing high-end gaming hardware on mobile frequently suffers from cluttered technical specifications, poor visual merchandising, and clunky checkout steps. This project reimagines the Aorus mobile shopping experience by uniting aggressive brand aesthetics with structured spec sheets, quick-buy carts, and live order tracking.",
  "uiUxUserResearch": {
    "targetAudience": "PC gamers, hardware overclockers, custom rig builders, and tech enthusiasts seeking official Aorus hardware components.",
    "researchMethodology": "Competitive benchmarking across specialized gaming stores, contextual analysis of builder forums, and heuristic evaluation of hardware checkout flows.",
    "keyFindings": [
      {
        "method": "Competitive Benchmarking",
        "description": "Evaluated existing mobile hardware stores on product categorization and technical transparency.",
        "keyFinding": "Enthusiast builders require immediate visibility into socket types, chipset generations, and dimension clearances before adding to cart.",
        "badge": "Spec Visibility"
      },
      {
        "method": "Builder Contextual Inquiry",
        "description": "Observed how custom PC builders cross-reference parts across mobile browser tabs and wishlists.",
        "keyFinding": "Users frequently abandon cart checkouts when discount vouchers and platform fees are obscure or hidden until the final payment step.",
        "badge": "Fee Transparency"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Alex Pratama",
      "role": "Competitive Gamer & Custom PC Builder",
      "demographics": "24 years old, tech-savvy early adopter, active on hardware forums",
      "quote": "I need to know exact socket and RAM compatibility before buying, without digging through endless PDF manuals.",
      "painPoints": [
        "Unstructured technical specifications on standard mobile storefronts",
        "Unclear stock availability and authorized warranty verification"
      ],
      "goals": [
        "Easily verify LGA1700 and DDR5 memory support on Z690 motherboards",
        "Track orders from factory dispatch to doorstep delivery in real time"
      ]
    },
    {
      "name": "Reza Wijaya",
      "role": "Content Creator & Hardware Upgrader",
      "demographics": "29 years old, streaming creator, values aesthetics and quiet acoustics",
      "quote": "I curate my build components over weeks and need my wishlist to show pricing trends and coupon readiness.",
      "painPoints": [
        "Losing saved hardware lists when transitioning between desktop and mobile",
        "Hidden shipping fees added at the very last moment"
      ],
      "goals": [
        "Organize builds using dedicated wishlist and recent tabs",
        "Apply verified shipping vouchers directly on the shopping cart screen"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The information architecture is organized into five primary bottom navigation hubs: Store Discovery, Hardware Wishlist, Product Catalog, Order History, and Account Settings. Sub-levels prioritize component taxonomy, technical datasheets, real-time stock availability, and a multi-step checkout funnel.",
    "nodes": [
      {
        "section": "Home Discovery Hub",
        "screens": [
          "Category Selector (Motherboard, GPU, RAM, PSU, Cooler, Monitor)",
          "Wallet Balance & Active Voucher Quick-Access",
          "Global Hardware Search Bar"
        ]
      },
      {
        "section": "Catalog & Product Detail",
        "screens": [
          "Filtered Category Product Grid",
          "Interactive Hardware Spec Matrix & Benchmark Ratings",
          "Official Store Verification & Seller Response Badge"
        ]
      },
      {
        "section": "Wishlist & Cart",
        "screens": [
          "Dual-Tab Wishlist vs Recent Viewed Items",
          "Itemized Shopping Cart with Voucher Selection",
          "Transparent Price Breakdown & Checkout Action"
        ]
      },
      {
        "section": "Fulfillment Tracking",
        "screens": [
          "Chronological Order History Feed",
          "Multi-Criteria Transaction Filters (Status, Date, Sort)",
          "Order Action Triggers (Cancel, Leave Review)"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "The primary user flow guides gamers through intuitive hardware discovery: from browsing component categories on the home screen, comparing spec sheets, managing wishlist items, to applying discount vouchers during cart review and executing checkout with order status tracking.",
    "steps": [
      {
        "step": "01",
        "title": "Category Browsing",
        "description": "User enters the app, reviews wallet balance, and selects the Motherboard category card from the neon home screen.",
        "screenOrAction": "Home Category Hub"
      },
      {
        "step": "02",
        "title": "Catalog Filtering & Selection",
        "description": "User browses through Z690/Z590 series boards and taps on Z690 Aorus Xtreme to inspect full parameters.",
        "screenOrAction": "Motherboard Product Grid"
      },
      {
        "step": "03",
        "title": "Technical Spec Evaluation",
        "description": "User examines the LGA1700 socket, DDR5 6400MHz support, and official store rating before clicking Add to Cart.",
        "screenOrAction": "Product Detail Page"
      },
      {
        "step": "04",
        "title": "Cart Review & Voucher Application",
        "description": "User reviews cart items, applies free shipping discount vouchers, confirms fee breakdown, and proceeds to checkout.",
        "screenOrAction": "Shopping Cart Screen"
      },
      {
        "step": "05",
        "title": "Order Fulfillment & Tracking",
        "description": "User views transaction state in chronological order list, tracking status from pending payment to delivery complete.",
        "screenOrAction": "Order History Timeline"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Hardware Discovery & Technical Product Specification",
      "imageUrl": "/images/projects/aorus_gaming_shop_mobile/image01.webp",
      "caption": "Visual hierarchy balancing neon cyber aesthetic with clear hardware categorization, filterable catalog grid, and in-depth component specs.",
      "badge": "Catalog & Specs",
      "stage": "Hi-Fi UI"
    },
    {
      "title": "Wishlist Comparison, Shopping Cart & Order Tracking",
      "imageUrl": "/images/projects/aorus_gaming_shop_mobile/image02.webp",
      "caption": "Streamlined wishlist comparison, transparent shopping cart breakdown with coupon discounts, and color-coded order timeline tracking.",
      "badge": "Checkout & Orders",
      "stage": "Hi-Fi UI"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Canvas Background",
        "hex": "#0A0E17",
        "role": "Surface",
        "usage": "Main application background canvas and navigation backdrops"
      },
      {
        "name": "Surface Dark",
        "hex": "#141B26",
        "role": "Surface",
        "usage": "Card elevations, component containers, and spec tables"
      },
      {
        "name": "Aorus Neon Orange",
        "hex": "#FF5500",
        "role": "Primary",
        "usage": "Brand logo, active tab indicator, and primary button highlights"
      },
      {
        "name": "Electric Cyan",
        "hex": "#00D2FF",
        "role": "Secondary",
        "usage": "Interactive badges, card borders, and category glow outlines"
      },
      {
        "name": "Neon Violet",
        "hex": "#7928CA",
        "role": "Accent",
        "usage": "Cyber ambient gradients and promotional hero backdrops"
      },
      {
        "name": "Status Green",
        "hex": "#00E676",
        "role": "Semantic",
        "usage": "Order completed badges, voucher applied states, and store verification"
      },
      {
        "name": "Warning Amber",
        "hex": "#FFAB00",
        "role": "Semantic",
        "usage": "Waiting for payment indicators and pending shipping alerts"
      },
      {
        "name": "Danger Crimson",
        "hex": "#FF3366",
        "role": "Semantic",
        "usage": "Canceled order states and destructive item removal triggers"
      }
    ],
    "typography": [
      {
        "name": "Display Brand Title",
        "role": "Heading",
        "font": "Rajdhani",
        "sizeWeight": "24px / Bold",
        "usage": "Header titles, brand logotype, and main screen headings"
      },
      {
        "name": "Component Heading",
        "role": "Heading",
        "font": "Inter",
        "sizeWeight": "16px / SemiBold",
        "usage": "Product card titles, category headers, and total price display"
      },
      {
        "name": "Technical Body",
        "role": "Body",
        "font": "Inter",
        "sizeWeight": "13px / Regular",
        "usage": "Specification table values, seller notes, and product descriptions"
      },
      {
        "name": "Micro Meta",
        "role": "Caption",
        "font": "Inter",
        "sizeWeight": "11px / Medium",
        "usage": "Status badge labels, quantity steppers, and rating review counts"
      }
    ],
    "componentStates": [
      {
        "component": "Add to Cart Button",
        "states": [
          "Default",
          "Hover",
          "Active",
          "Disabled"
        ],
        "notes": "Neon violet fill with high-contrast white text, min 44pt touch target"
      },
      {
        "component": "Category Nav Tile",
        "states": [
          "Default",
          "Hover",
          "Active"
        ],
        "notes": "Subtle border glow on active selection with tactile scale feedback"
      },
      {
        "component": "Quantity Stepper",
        "states": [
          "Default",
          "Active",
          "Disabled"
        ],
        "notes": "Inline counter with minus disabled when quantity equals minimum order"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "testingMethod": "Moderated Task-Based Prototype Usability Walkthrough",
    "participantsCount": 8,
    "susScore": 86.5,
    "taskSuccessRate": 94,
    "timeOnTask": "1m 45s",
    "feedbackSynthesis": "Enthusiasts praised the spec-first product layout and cyberpunk dark mode, highlighting that socket and RAM parameters were far easier to verify than on mainstream retail apps.",
    "iterations": [
      {
        "usabilityIssue": "Participants initially missed the voucher discount indicator on the cart screen.",
        "iterationSolution": "Introduced a dedicated green voucher banner with an automatic discount deduction line.",
        "impact": "Increased user confidence during checkout and eliminated pricing confusion."
      },
      {
        "usabilityIssue": "Hardware specification text was initially presented as an unsegmented block.",
        "iterationSolution": "Restructured technical attributes into a two-column key-value matrix with contrasting borders.",
        "impact": "Reduced specification scanning time by 42% across mobile screen viewports."
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "Production Design Archive",
    "totalFrames": 18,
    "componentsCount": 42,
    "handoffSpecs": "Figma mobile frames with auto-layout v4, comprehensive dark tokens, and structured component variants."
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "8pt Spatial Grid System",
    "designTokens": "Tokenized Cyber Dark Palette",
    "typography": "Modern Geometric Sans Scale",
    "prototypeFidelity": "High Fidelity Interactive Screens"
  }
}
```
