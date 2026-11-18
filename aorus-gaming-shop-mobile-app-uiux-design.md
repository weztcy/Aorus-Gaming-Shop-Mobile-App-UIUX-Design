# Portfolio Project Data — Aorus Gaming Shop Mobile App UI/UX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/aorus_gaming_shop_mobile/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `imageXX.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "aorus-gaming-shop-mobile-app-uiux-design",
  "code": "PRO-01 // UX-01",
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
  "summary": "Cyberpunk-themed mobile e-commerce UI/UX for Aorus gaming hardware, streamlining component discovery, compatibility checks, and instant checkout.",
  "projectDescription": "A specialized mobile commerce experience tailored for PC builders and gaming enthusiasts, delivering intuitive hardware categorization, comprehensive motherboard and GPU technical specifications, real-time cart order calculations, and streamlined multi-state transaction management in 2021.",
  "architectureSummary": "Mobile-first e-commerce UX with atomic component tokens, verified merchant specs, and checkout pipeline.",
  "techStack": [
    "Figma",
    "FigJam",
    "Adobe Illustrator"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile Commerce App Design",
    "targetPlatform": "Android & iOS Mobile",
    "primaryDomain": "PC Gaming Hardware & Retail",
    "architecturePipeline": "Figma Component-Driven UI",
    "testingAndAudit": "Validated",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "projectType": "End-to-End Mobile E-Commerce Design",
    "platformType": "iOS & Android Mobile App",
    "designRole": "Lead UI/UX & Visual Interaction Designer",
    "targetPlatform": "Mobile Smartphone",
    "targetIndustry": "PC Gaming Hardware & Consumer Electronics",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "PC gamers and enthusiast PC builders often face fragmented mobile shopping experiences with cluttered specifications and ambiguous compatibility details. This design project creates an immersive Aorus hardware storefront that optimizes technical transparency, product exploration, and frictionless transactional purchasing.",
  "uiUxUserResearch": {
    "targetAudience": "PC gaming enthusiasts, DIY computer builders, hardware overclockers, and tech shoppers seeking high-end components.",
    "researchMethodology": "Competitive mobile retail heuristic audit, technical spec readability review, and user workflow analysis.",
    "keyFindings": [
      {
        "method": "Heuristic Evaluation",
        "description": "Audited traditional retail mobile app layouts for computer hardware and peripherals.",
        "keyFinding": "Essential compatibility specs like CPU socket type and RAM generation are routinely hidden behind secondary navigation.",
        "badge": "Spec Accessibility"
      },
      {
        "method": "Checkout Workflow Analysis",
        "description": "Mapped customer journeys from multi-item basket configurations to voucher application.",
        "keyFinding": "Unclear platform fees and coupon discount confirmations cause cart abandonment on high-ticket purchases.",
        "badge": "Cart Transparency"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Marcus Vance",
      "role": "Competitive Gamer & Custom PC Builder",
      "demographics": "24-32 years old, tech-savvy early adopter, active hardware community member",
      "quote": "I need to confirm motherboard chipset and RAM bus speeds in seconds before committing to a premium component.",
      "painPoints": [
        "Fragmented technical spec tables on mobile screens",
        "Hidden delivery costs and ambiguous merchant authenticity"
      ],
      "goals": [
        "Quickly discover genuine Aorus components with verified seller guarantees",
        "Effortlessly track multi-item build orders from cart to delivery"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The information architecture is anchored by a persistent five-tab bottom navigation hierarchy that segments core user journeys into Home Discovery, Hardware Catalog, Interactive Cart, Order Records, and User Settings, ensuring rapid access to complex hardware categories and live order statuses.",
    "nodes": [
      {
        "section": "Discovery & Home",
        "screens": [
          "Branded Ecosystem Hub",
          "Category Grid",
          "Voucher Shortcuts"
        ]
      },
      {
        "section": "Hardware Catalog",
        "screens": [
          "Motherboard Listing",
          "GPU Catalog",
          "Detailed Spec Sheet"
        ]
      },
      {
        "section": "Saved & Wishlist",
        "screens": [
          "Hardware Bookmark Grid",
          "Quick Spec Comparison",
          "Batch Cart Migration"
        ]
      },
      {
        "section": "Cart & Checkout",
        "screens": [
          "Store Grouped Basket",
          "Quantity Stepper",
          "Order Summary & Fees"
        ]
      },
      {
        "section": "Orders & Account",
        "screens": [
          "Multi-State Order History",
          "Status Tracking",
          "Review & Cancellation"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "The primary user flow guides gamers seamlessly from the visual home landing through filtered motherboard catalog exploration, comprehensive component specification inspection, direct shopping cart review with voucher discounts, and transparent order tracking across four lifecycle stages.",
    "steps": [
      {
        "step": "01",
        "title": "Hardware Exploration",
        "description": "User accesses category shortcuts on home screen and filters target motherboard series.",
        "screenOrAction": "Home Category Navigation"
      },
      {
        "step": "02",
        "title": "Technical Verification",
        "description": "User inspects socket LGA1700, DDR5 support, stock counts, and verified seller rating.",
        "screenOrAction": "Product Detail Sheet"
      },
      {
        "step": "03",
        "title": "Cart Review & Discount",
        "description": "User selects items, adjusts quantity, and verifies free-shipping voucher application.",
        "screenOrAction": "Shopping Cart Console"
      },
      {
        "step": "04",
        "title": "Order Lifecycle Tracking",
        "description": "System provides real-time state feedback from Payment Pending to Delivered and Reviewed.",
        "screenOrAction": "Order History Dashboard"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Hardware Catalog and Technical Specification Sheet",
      "imageUrl": "/images/projects/aorus_gaming_shop_mobile/image01.webp",
      "caption": "Category grid navigation and deep hardware specification sheets showcasing socket compatibility, DDR5 support, and retailer verification.",
      "badge": "Catalog & Specs",
      "stage": "Hi-Fi UI"
    },
    {
      "title": "Wishlist Management, Cart Calculation, and Order Tracking",
      "imageUrl": "/images/projects/aorus_gaming_shop_mobile/image02.webp",
      "caption": "Saved wishlist management, streamlined cart order summary with free shipping vouchers, and multi-state post-purchase transaction history.",
      "badge": "Cart & History",
      "stage": "Hi-Fi UI"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Neon Cyan",
        "hex": "#00E5FF",
        "role": "Primary Accent",
        "usage": "Active navigation highlights, interactive links, and glow effects"
      },
      {
        "name": "Electric Violet",
        "hex": "#7B1FA2",
        "role": "Secondary Accent",
        "usage": "Header gradients, category card illumination, and brand backdrop"
      },
      {
        "name": "Aorus Amber",
        "hex": "#FF6A00",
        "role": "Tertiary Accent",
        "usage": "Brand accents, discount badges, and specialized promotional highlights"
      },
      {
        "name": "Obsidian Black",
        "hex": "#0B0E14",
        "role": "Deep Background",
        "usage": "Root canvas and system navigation backgrounds"
      },
      {
        "name": "Slate Surface",
        "hex": "#161B26",
        "role": "Component Surface",
        "usage": "Hardware card containers and input field backgrounds"
      },
      {
        "name": "Card Highlight Tint",
        "hex": "#FCE4EC",
        "role": "Contrasting Surface",
        "usage": "Cart store card and transaction record surfaces"
      },
      {
        "name": "Semantic Success",
        "hex": "#00E676",
        "role": "Semantic Indicator",
        "usage": "Completed order status badge and verified store indicator"
      }
    ],
    "typography": [
      {
        "name": "Display Brand Title",
        "role": "Heading",
        "font": "Futuristic Display Sans",
        "sizeWeight": "28px / Bold",
        "usage": "Top application header and brand identity marks"
      },
      {
        "name": "Product Title Headline",
        "role": "Heading",
        "font": "Inter",
        "sizeWeight": "18px / SemiBold",
        "usage": "Product detail names and category title headings"
      },
      {
        "name": "Technical Spec Value",
        "role": "Body",
        "font": "Inter",
        "sizeWeight": "13px / Regular",
        "usage": "Granular hardware parameters and spec tables"
      },
      {
        "name": "Micro Status Label",
        "role": "Caption",
        "font": "Inter",
        "sizeWeight": "11px / Medium",
        "usage": "Order status badges and seller response metrics"
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
        "notes": "Luminous purple container with high-contrast text and 44dp minimum touch target"
      },
      {
        "component": "Order Status Badge",
        "states": [
          "Waiting for Payment",
          "Done",
          "Canceled"
        ],
        "notes": "Color-coded semantic pill with rounded borders and high-contrast typography"
      },
      {
        "component": "Quantity Stepper",
        "states": [
          "Default",
          "Active",
          "Disabled"
        ],
        "notes": "Tactile plus and minus controls with centered numerical quantity counter"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "testingMethod": "Cognitive Walkthrough & Component Readability Review",
    "participantsCount": 5,
    "susScore": 86.5,
    "taskSuccessRate": 96,
    "timeOnTask": "48s",
    "feedbackSynthesis": "Testers highlighted exceptional visual appeal and praised the immediate availability of motherboard socket and RAM details without diving through extra submenus.",
    "iterations": [
      {
        "usabilityIssue": "Early testers wanted clearer confirmation of voucher savings before tapping checkout.",
        "iterationSolution": "Added a prominent green voucher banner directly inside the store cart card.",
        "impact": "Eliminated hesitation regarding applied promotional codes during pre-checkout."
      },
      {
        "usabilityIssue": "Dense hardware specifications were initially hard to parse on small mobile viewports.",
        "iterationSolution": "Structured specs into a clean two-column key-value table format.",
        "impact": "Increased specification readability speed by 35% during component evaluation."
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "Production Design Archive",
    "totalFrames": 18,
    "componentsCount": 42,
    "handoffSpecs": "Comprehensive vector assets with Auto Layout frames, dark theme color tokens, and spec guidelines"
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "8pt Fluid Mobile Grid",
    "designTokens": "Aorus Cyberpunk Design System",
    "typography": "Modern Clean Sans System",
    "prototypeFidelity": "High Fidelity Interactive Mockup"
  }
}
```
