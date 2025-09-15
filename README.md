# AccessGov
**AI-Powered Accessibility Auditor for Congress**  

AccessGov is an open-source project designed to make Congressional documents and digital materials accessible to all Americans. By combining continuous monitoring, accessibility scanning, and AI-assisted remediation, AccessGov helps Congress conform to Section 508 and Web Content Accessibility Guidelines (WCAG) standards while ensuring that bills, reports, and hearings are usable for constituents with disabilities.  

---

## Features  

- **Continuous Monitoring**  
  Crawls new materials across [Congress.gov](https://www.congress.gov/), Congressional Research Service (CRS) reports, committee websites, and hearing video archives.  

- **Accessibility Checks**  
  Runs automated scans against WCAG 2.1/2.2 and Section 508 standards.  

- **AI-Assisted Fixes**  
  - Generates meaningful alternative text for images and charts.  
  - Proposes tagged structures and heading hierarchies for PDFs.  
  - Produces captions and transcripts for hearing videos.  
  - Drafts plain-language summaries for complex documents.  

- **Prioritization**  
  Ranks fixes by urgency and constituent impact (e.g., upcoming hearings, widely viewed CRS reports).  

- **Dashboard & Reporting**  
  - Accessibility scorecards for each office, committee, and chamber.  
  - Trend lines showing compliance progress over time.  
  - Exportable reports for GAO, ADA Title II, and Section 508 oversight.  

---

## Workflow  

1. **Ingest**  
   - Crawl Congress.gov, CRS, committee websites, and hearing archives.  
2. **Analyze**  
   - Run automated scans for WCAG/508 compliance.  
   - Identify accessibility gaps (e.g., missing alt text, untagged PDFs, no captions).  
3. **AI-Assisted Fixes**  
   - Suggest alt text, captions, PDF tags, plain-language summaries.  
4. **Prioritize**  
   - Rank by urgency (e.g., markup tomorrow) and public impact (high-traffic CRS reports).  
5. **Human-in-the-Loop**  
   - Staff review and approve AI suggestions.  
6. **Publish & Report**  
   - Republish accessible versions back to CRS, Congress.gov, or committee sites.  
   - Update dashboards and generate compliance reports.  

---

## Getting Started (Conceptual)  

> This project is currently **conceptual / prototype stage**.  
> Future iterations may include integrations with:  
> - [axe-core](https://github.com/dequelabs/axe-core)  
> - [WAVE API](https://wave.webaim.org/)  
> - [Google Lighthouse](https://developer.chrome.com/docs/lighthouse/accessibility)  
> - [ASAP PDF](https://github.com/codeforamerica/asap_pdf)

To run a proof-of-concept:  
```bash
git clone https://github.com/sanrav2016/accessgov.git
cd accessgov
```

---

## References
## 📚 References  

[1] N. Overdorff, “Inaccessible PDFs Reduce Access to Government Services,” *Equidox*, May 13, 2025. [Online]. Available: https://equidox.co/blog/inaccessible-pdfs-reduce-access-to-government-services/ (accessed Sep. 15, 2025).  

[2] “Justice Department to Publish Final Rule to Strengthen Web and Mobile App Access for People with Disabilities,” *Justice.gov*, Apr. 08, 2024. [Online]. Available: https://www.justice.gov/archives/opa/pr/justice-department-publish-final-rule-strengthen-web-and-mobile-app-access-people  

[3] “2025 Digital Accessibility Index: Analysis of 15,000 Sites,” *AudioEye*, 2025. [Online]. Available: https://www.audioeye.com/digital-accessibility-index/2025/ (accessed Sep. 15, 2025).  

[4] C. Teale, “Feds move to make gov websites more accessible to people with disabilities,” *Route Fifty*, Apr. 15, 2024. [Online]. Available: https://www.route-fifty.com/digital-government/2024/04/feds-move-make-gov-websites-more-accessible-people-disabilities/395744/ (accessed Sep. 15, 2025).  

[5] C. Teale, “Feds offer help complying with website accessibility rule,” *Route Fifty*, 2025. [Online]. Available: https://www.route-fifty.com/digital-government/2025/01/feds-offer-help-complying-website-accessibility-rule/402169/ (accessed Sep. 15, 2025).  

[6] C. Teale, “Government websites are littered with accessibility issues, research finds,” *Route Fifty*, 2025. [Online]. Available: https://www.route-fifty.com/digital-government/2025/03/government-websites-are-littered-accessibility-issues-research-finds/404026/  

[7] ADA.gov, “Fact Sheet: New Rule on the Accessibility of Web Content and Mobile Apps Provided by State and Local Governments,” *ADA.gov*, Mar. 08, 2024. [Online]. Available: https://www.ada.gov/resources/2024-03-08-web-rule/  

[8] “State and Local Governments: First Steps Toward Complying with the Americans with Disabilities Act Title II Web and Mobile Application Accessibility Rule,” *ADA.gov*, Jan. 08, 2025. [Online]. Available: https://www.ada.gov/resources/web-rule-first-steps/  

[9] “Section508.gov,” *Section508.gov*, 2024. [Online]. Available: https://www.section508.gov/manage/section-508-assessment/2024/executive-summary/ (accessed Sep. 15, 2025).  

[10] BGL Administrator, “Federal Digital Accessibility Disappearance on Trump Day One,” *Brown Goldstein Levy*, Jan. 31, 2025. [Online]. Available: https://browngold.com/blog/federal-digital-accessibility-disappearance-on-trump-day-one/  

[11] Centers for Disease Control and Prevention, “Disability Impacts All of Us Infographic,” *Disability and Health*, Dec. 10, 2024. [Online]. Available: https://www.cdc.gov/disability-and-health/articles-documents/disability-impacts-all-of-us-infographic.html  

[12] “The Hidden Accessibility Violations in Online Documents,” *AudioEye*, 2025. [Online]. Available: https://www.audioeye.com/post/accessibility-violations-in-online-documents/ (accessed Sep. 15, 2025).  

[13] “What Disability Pride Month Can Teach Us About Innovation, Accessibility, and the Future of Tech,” *AudioEye*, 2025. [Online]. Available: https://www.audioeye.com/post/what-disability-pride-month-can-teach-us-about-innovation-accessibility-and-the-future-of-tech/ (accessed Sep. 15, 2025).  

[14] Government Accountability Office, “Federal Accessibility: OMB Is Tracking Agency Implementation of Its Guidance on Information and Communication Technology,” *GAO.gov*, 2024. [Online]. Available: https://www.gao.gov/products/gao-24-107031  

[15] Code For America, “GitHub - codeforamerica/asap_pdf,” *GitHub*, 2025. [Online]. Available: https://github.com/codeforamerica/asap_pdf (accessed Sep. 15, 2025).  

[16] “Document Accessibility for Governments,” *247 Accessible Documents*, Aug. 19, 2025. [Online]. Available: https://247accessibledocuments.com/document-accessibility-for-governments/ (accessed Sep. 15, 2025).  

[17] USWDS, “GitHub - uswds/uswds: The U.S. Web Design System helps the federal government build fast, accessible, mobile-friendly websites.,” *GitHub*, 2015. [Online]. Available: https://github.com/uswds/uswds (accessed Sep. 15, 2025).  

[18] “FTC Order Requires Online Marketer to Pay $1 Million for Deceptive Claims that its AI Product Could Make Websites Compliant with Accessibility Guidelines,” *Federal Trade Commission*, Jan. 03, 2025. [Online]. Available: https://www.ftc.gov/news-events/news/press-releases/2025/01/ftc-order-requires-online-marketer-pay-1-million-deceptive-claims-its-ai-product-could-make-websites  

[19] “CRS Products from the Library of Congress,” *Congress.gov*, 2025. [Online]. Available: https://www.congress.gov/crs-products  
