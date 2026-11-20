# CompareKaro (EstateVue) — Property Discovery and Comparison Platform

## Overview

CompareKaro (EstateVue) is a responsive, client-side web application developed to streamline residential real estate discovery and evaluation. Prospective buyers frequently encounter fragmented property specifications across multiple platforms, making direct evaluation difficult. This application addresses that problem by providing unified search, multi-parameter filtering, bookmarking, and a side-by-side comparison matrix for up to four properties within a single interface.

---

## Problem Statement

Evaluating real estate listings across disconnected web pages forces users to manually track pricing, floor area, layout specifications, and available amenities. CompareKaro centralizes property discovery and decision-making into a single dashboard, allowing users to shortlist properties and compare key metrics directly.

---

## Key Features

### 1. Search and Multi-Criteria Filtering
* **Keyword Search:** Real-time filtering by property title, city, or street address.
* **Parameter Filters:** Filter listings by location, property category (Single Family, Luxury Condominium, Penthouse, Modern Villa, Townhouse), maximum budget threshold, minimum square footage, and bedroom count.
* **Amenity Filtering:** Multi-select checklist to filter properties by specific amenities such as swimming pools, smart home automation, private gardens, and ocean views.
* **Dynamic Sorting:** Sort filtered results by featured status, price (ascending or descending), and total floor area.

### 2. Side-by-Side Comparison Matrix
* **Comparison Dock:** Persistent floating dock allowing users to queue up to four properties from the main listing grid.
* **Specification Matrix:** Tabular side-by-side breakdown comparing property images, pricing, estimated price per square foot, location, room counts, total area, year of construction, and an automated amenity availability checklist.

### 3. Bookmark Management
* **Saved Listings View:** Dedicated bookmarks section enabling users to save and manage shortlisted properties with live counter indicators in the navigation bar.

### 4. Property Inspection and Inquiry Workflow
* **Detail Modal:** Interactive modal displaying an image gallery with thumbnail switching, architectural metrics, property descriptions, and amenity tags.
* **Agent Inquiry Form:** Built-in inquiry modal with form validation and real-time toast notifications upon submission.

---

## Technology Stack

* **Markup:** HTML5
* **Styling:** Tailwind CSS (configured with custom color palettes and utility classes)
* **Icons & Typography:** Font Awesome 6.4.0, Google Fonts (Inter)
* **Application Logic:** Vanilla JavaScript (ES6+), utilizing `Set` data structures for state management and dynamic DOM manipulation

---

## Architecture and Implementation Details

The application is engineered as a self-contained single-page interface without external build dependencies:

* **State Management:** Tracks user bookmarks (`favorites`), selected comparison items (`compareList`), active filter parameters, and modal states in memory.
* **Rendering Engine:** Dynamically generates property cards, comparison matrix columns, gallery thumbnails, and toast alerts from a structured JSON-like property dataset.
* **Responsive Layout:** Adapts across desktop, tablet, and mobile viewports using CSS Grid and Flexbox utilities.

---

## Setup and Execution

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<username>/<repository-name>.git# site_comparison
