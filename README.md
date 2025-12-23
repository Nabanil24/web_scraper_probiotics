# web_scraper_probiotics

## Company Evaluation Framework: Probiotics 

| Category | What to Look For | Why it Matters |
| :--- | :--- | :--- |
| **Strain Specificity** | Mentions of specific strains (e.g., *Lactobacillus rhamnosus* GG, *Bifidobacterium* BB-12). | **High Intent.** Specificity indicates ownership or deep licensing of IP, typical of R&D-led companies. |
| **Quantifiable Metrics** | References to **CFU** (Colony Forming Units), stability data, or shelf-life potency. | **Manufacturing Strength.** Only serious manufacturers or high-end brands focus on viable cell counts. |
| **Scientific Validation** | Clinical trial links, white papers, or "In-Vitro/In-Vivo" study mentions. | **Pharma Alignment.** Distinguishes between "marketing-led" and "science-led" organizations. |
| **Regulatory Compliance** | GMP, ISO, FDA-GRAS status, or specific health claims (EFSA/Health Canada). | **Trust Signal.** Necessary for a pharma client looking for partners or competitors. |
| **Supply Chain Role** | "Bulk ingredients," "Custom formulation," or "Finished dosage forms." | **Classification.** Determines if they are a raw material supplier or a consumer-facing brand. |

##  Company Profile
I chose the company Lallemand (https://lallemand-health-solutions.com/en/health-segments/gut-health/) for profiling.


| Category | Analysis of Lallemand Health Solutions | Score / Strength |
| :--- | :--- | :--- |
| **1. Strain Specificity** <br> *(Do they name the bug?)* | **Exceptional.** They do not just say "Lactobacillus"; they market specific, proprietary strains like *L. helveticus Rosell®-52* and *B. infantis Rosell®-33*. This is the highest level of specificity. | **+5 (Maximum)** |
| **2. Quantifiable Metrics** <br> *(CFU & Stability)* | **High.** They market specific stability technologies like **Probiocap®** (microencapsulation) to guarantee survival. They explicitly discuss stability data and shelf-life potency, not just "input count." | **+5 (Maximum)** |
| **3. Scientific Validation** <br> *(Clinical Trials)* | **Very High.** They operate the **Rosell® Institute for Microbiome and Probiotics.** Their website cites over **160 clinical studies.** They categorize products by therapeutic area (e.g., *Cerebiome®* for the Gut-Brain axis), which implies clinical backing. | **+5 (Maximum)** |
| **4. Regulatory Compliance** <br> *(Trust Signals)* | **Strong.** They list manufacturing standards including **Pharma GMP, Health Canada** NHP licenses, **USP** (United States Pharmacopeia) quality verification, and ISO 9001. | **+3 (High)** |
| **5. Supply Chain Role** <br> *(Bulk vs Retail)* | **Foundation Layer.** They describe themselves as a "One-stop-shop" offering active ingredients (bulk powder) and custom formulations. | **N/A (Context)** |


##Task 1 - Building the web scraper

The code can be run on jupyter notebook. No additional dependencies. Example command and sample output has been included with the code.

Output for Yakult:

{
    "A_Identity": {
        "Company_Name": "Probiotic Drink for Better Digestion & Immunity",
        "Website": "https://yakult.co.in",
        "Tagline": "Try Yakult, a probiotic drink that supports digestion, immunity, and gut health. Experience Yakult India's flavors, including Mango, and their benefits!"
    },
    "B_Business_Summary": {
        "What_They_Do": "Yakult Danone India Pvt. Ltd. is a 50:50 Joint Venture (JV) between Yakult Honsha in Japan and Groupe Danone in France, both of which are global probiotic leaders. The JV was formed in 2005 and Yakult, a probiotic fermented milk drink was launched in India in 2008. In 2018, Yakult Light, a reduced sugar version of Yakult, with vitamin D and E was launched.",
        "Primary_Offerings": [
            "packaged goods"
        ]
    },
    "C_Evidence": {
        "Key_Pages_Detected": [
            "Products: https://yakult.co.in/probiotic-drinks",
            "Products: https://www.yakult.co.in/probiotic-drinks",
            "Careers: https://www.yakult.co.in/career",
            "About: https://www.yakult.co.in/history-of-yakult",
            "About: https://www.yakult.co.in/about-us",
            "Contact: https://yakult.co.in",
            "Science: https://www.yakult.co.in/science-behind-yakult",
            "Contact: https://www.yakult.co.in/contact-us"
        ],
        "Signals_Found": [
            "Immunity",
            "Gut Health",
            "CFU",
            "Research",
            "Fermentation",
            "Strain",
            "ISO 9001",
            "Clinical Trial",
            "Copyright",
            "Lactobacillus",
            "Awards",
            "Testimonials",
            "GRAS",
            "L. casei",
            "Bifidobacterium",
            "Science",
            "Shirota",
            "All Rights Reserved"
        ],
        "Social_Links": [
            "https://www.linkedin.com/company/yakult-danone-india-private-limited/",
            "https://www.youtube.com/@yakultindia",
            "https://www.youtube.com/user/yakultindia",
            "https://www.instagram.com/yakult.india/?igshid=YmMyMTA2M2Y%3D",
            "https://www.instagram.com/yakult.india/",
            "https://www.youtube.com/playlist?list=PLqupz0dQ_yc_ONCrhlk7egue5wav_HEEP",
            "https://www.facebook.com/yakultind/",
            "https://www.youtube.com/@yakultindia/videos"
        ]
    },
    "D_Contact_Location": {
        "Emails": [
            "feedback@yakult.co.in"
        ],
        "Phones": [
            "011-40626262",
            "011-40626299"
        ],
        "Address": "Floor, Okhla Industrial Estate, Phase-3, New Delhi-110020",
        "Contact_URL": "https://www.yakult.co.in/contact-us"
    },
    "E_Team_Hiring": {
        "Careers_URL": "https://www.yakult.co.in/career",
        "Roles_Mentioned": []
    },
    "F_Metadata": {
        "Timestamp": "2025-12-23 00:54:13",
        "Pages_Visited": [
            "https://yakult.co.in",
            "https://yakult.co.in/probiotic-drinks",
            "https://www.yakult.co.in/about-us",
            "https://www.yakult.co.in/history-of-yakult",
            "https://www.yakult.co.in/science-behind-yakult",
            "https://www.yakult.co.in/contact-us",
            "https://www.yakult.co.in/probiotic-drinks"
        ],
        "Errors": []
    }
}

Output for tablets india:

{
    "A_Identity": {
        "Company_Name": "Tablets India",
        "Website": "https://tabletsindia.com",
        "Tagline": "Tablets India offers advanced probiotics, nutraceuticals and pharma solutions designed to support immunity, gut health and overall wellness for all age groups."
    },
    "B_Business_Summary": {
        "What_They_Do": "Tablets (India) Limited was one of the early pharma ventures in India and was founded in 1938 by Mr Sri Krishna Jhaver.",
        "Primary_Offerings": [
            "Capsule in capsule",
            "Sachet in Sachet",
            "Oral Dispersible Powder"
        ],
        "Target_Segments": []
    },
    "C_Evidence": {
        "Key_Pages_Detected": [
            "Science: https://tabletsindia.com/clinical-research",
            "Contact: https://tabletsindia.com/contact-us",
            "About: https://tabletsindia.com/about-us",
            "Careers: https://tabletsindia.com/careers",
            "Contact: https://tabletsindia.com/human-health/fertility-support/fertihope-m",
            "Science: https://tabletsindia.com/rd-activities"
        ],
        "Signals_Found": [
            "Immunity",
            "Patent",
            "Partners",
            "Research",
            "Clinical Trial",
            "Copyright",
            "Science",
            "All Rights Reserved"
        ],
        "Social_Links": [
            "https://www.facebook.com/TabletsIndia",
            "https://www.youtube.com/channel/UCQ2BbybacrxLP_ugHycIb-w/videos",
            "https://www.instagram.com/tabletsindia/",
            "https://twitter.com/TabletsIndiaLtd",
            "https://www.linkedin.com/company/tabletsindia/"
        ]
    },
    "D_Contact_Location": {
        "Emails": [
            "info@tabletsindia.com"
        ],
        "Phones": [],
        "Address": "Jhaver Centre 72 Marshalls Road, Chennai \u2013 600 008 600 008",
        "Contact_URL": "https://tabletsindia.com/contact-us"
    },
    "E_Team_Hiring": {
        "Careers_URL": "https://tabletsindia.com/careers",
        "Roles_Mentioned": []
    },
    "F_Metadata": {
        "Timestamp": "2025-12-23 01:34:06",
        "Pages_Visited": [
            "https://tabletsindia.com",
            "https://tabletsindia.com/about-us",
            "https://tabletsindia.com/clinical-research",
            "https://tabletsindia.com/contact-us",
            "https://tabletsindia.com/human-health/fertility-support/fertihope-m",
            "https://tabletsindia.com/rd-activities"
        ],
        "Errors": []
    }
}
