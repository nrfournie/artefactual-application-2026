# Migration Workflow: WordPress to Wix (Manual Process)

## Overview
This document outlines the manual data migration process I designed and executed for The Contemplative Society's website. Because Wix does not support direct XML import from WordPress, I developed a systematic manual workflow to preserve 28 years of legacy content with 100% integrity. Beyond migration, I identified and removed duplicate/outdated files that had created a bloated backend, reducing storage needs by 80GB and improving site performance.
---

## Phase 1: Data Audit & Backup
**Challenge:** Legacy WordPress site contained years of blog posts dating back to the early 2000's, audio files, and images with inconsistent organization and broken metadata, lost in pages of spaghetti code. Wix's platform does not accept WordPress XML exports, requiring manual content transfer. 

**Actions:**
- Conducted a full content audit via the WordPress dashboard to catalogue all posts, pages, and media
- Downloaded all media files (audio, images, PDFs) to external hard drive
- Created an organized folder structure with Finder key for reference during rebuild
- Documented existing site architecture and navigation structure
- Maintaining the old site on a free, password-protected domain, while disabling paid plugins, for when access to old data is required

**Outcome:** Complete backup created; zero risk of data loss during migration

**Alternative Outcomes:**
- Redesigned site from scratch for improved accessibility and visual appeal
- The development of the Cynthia Bourgeault Digital Archive for the proper organization of legacy content

---

## Phase 2: Content Restructuring & Metadata Planning

Rather than automated field mapping, I manually reviewed and restructured content for the new platform:

| WordPress Content Type | New Wix Structure | Manual Process |
| :--- | :--- | :--- |
| Blog posts | Wix Blog + Content Manager | Copy/paste with metadata cleanup |
| Audio resources | Wix Velo Dynamic Pages | Upload files, create custom fields |
| Category tags | Structured taxonomy | Standardize naming conventions |
| Author attributions | Contributor fields | Verify accuracy, add where missing |

**Key Decision:** Built custom Wix Velo collections for archival resources (rather than standard blog format) to enable better filtering and search functionality.

---

## Phase 3: Manual Migration & Quality Control

**Migration Process:**
- Manually transferred 450+ posts and 200+ media files over 6-week period
- Rebuilt each page in Wix editor, maintaining original content while improving readability
- Created a new navigation structure optimized for contemplative spirituality audiences
- Implemented JSON structured data markup to improve search discoverability

**Quality Assurance:**
- Cross-referenced the original WordPress site (kept live during migration) with new Wix pages
- Tested all internal links and media embeds
- Verified metadata accuracy across all resources
- Conducted user testing with board members before launch

**Final Result:** 100% content preserved. Zero files lost. Platform successfully transitioned with improved user experience and +60% organic traffic increase post-launch.

---

## Phase 4: Post-Launch Improvements

**Ongoing Optimization:**
- Created data management policy for future content additions
- Designed workflow for volunteer staff to maintain the site without technical expertise
- Reduced monthly hosting costs and eliminated the need for external contractor support

---

## Key Takeaways

**What I Learned:**
- Manual migration, while time-intensive, allows for quality improvements impossible with automated tools
- Creating organized backup systems is non-negotiable before any migration
- User-friendly platforms like Wix enable volunteer organizations to maintain their own digital presence

**Skills Applied:**
- Systematic content auditing and preservation planning
- Patient, detail-oriented manual data transfer
- Platform evaluation and workflow design for non-technical users
- Quality assurance and verification processes
