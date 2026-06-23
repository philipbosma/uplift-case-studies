# Consolidating UPLIFT Desk's Flagship Standing Desk for the V3 Launch

### Product Launch • Catalog Architecture • Product Configuration

---

## Overview

UPLIFT Desk launched its next-generation V3 standing desk frame to replace the existing V2 and V2-Commercial product lines. This required consolidating multiple standing desk experiences into a single flagship configurable product while preserving compatibility across hundreds of SKUs and tens of thousands of possible product configurations.

The launch centered on UPL960—UPLIFT Desk's highest-profile standing desk product—and was scheduled immediately before Black Friday, making reliability and execution critical.

---

## At a Glance

<table>
  <tbody>
    <tr>
      <td><strong>Company</strong></td>
      <td>UPLIFT Desk</td>
    </tr>
    <tr>
      <td><strong>Project</strong></td>
      <td>V3 Standing Desk Frame Launch</td>
    </tr>
    <tr>
      <td><strong>Role</strong></td>
      <td>Catalog Implementation &amp; Product Configuration</td>
    </tr>
    <tr>
      <td><strong>Platforms</strong></td>
      <td>BigCommerce, NetSuite, Threekit</td>
    </tr>
    <tr>
      <td><strong>Scale / Complexity</strong></td>
      <td>Hundreds of child SKUs and 50,000+ configurable combinations</td>
    </tr>
    <tr>
      <td><strong>Primary Responsibilities</strong></td>
      <td>Configuration rules, SKU mapping, compatibility documentation, testing, production launch</td>
    </tr>
    <tr>
      <td><strong>Primary Stakeholders</strong></td>
      <td>Product Development, Web Development, Marketing, Sales &amp; Customer Service, Shipping &amp; Fulfillment</td>
    </tr>
    <tr>
      <td><strong>Key Skills</strong></td>
      <td>Catalog Architecture, Product Configuration, Release Management, QA Testing</td>
    </tr>
    <tr>
      <td><strong>Timeline</strong></td>
      <td>Black Friday launch</td>
    </tr>
    <tr>
      <td><strong>Production Downtime</strong></td>
      <td>Less than 15 minutes</td>
    </tr>
  </tbody>
</table>

---

## Business Challenge

Prior to the V3 launch, customers navigated multiple product pages depending on desktop depth and frame type.

The catalog consisted of:

- UPL960 (30" desktops)
- UPL926 (24" desktops)
- Separate V2 frame options
- Separate V2-Commercial frame options

This fragmented experience created unnecessary customer confusion, increased maintenance complexity, and made compatibility rules difficult to manage.

The objective was to simplify the purchasing experience by combining these products into a single configurable listing while ensuring every customer selection generated a valid product configuration.

Complicating the project further, the launch coincided with the company's busiest sales period. Because the product represented one of UPLIFT Desk's highest-revenue pages, the implementation had to be completed with virtually no downtime.

---

## My Role

I owned the catalog implementation for the launch and coordinated the technical work required to safely transition the existing product experience.

My responsibilities included:

- Defining product configuration rules
- Creating centralized compatibility documentation
- Mapping new SKU relationships
- Building and testing BigCommerce configuration logic
- Validating NetSuite integration
- Coordinating cross-functional testing
- Executing the production launch

---

## Approach / Implementation

### 1. Created a Single Source of Truth

Compatibility information existed across multiple documents and teams.

I audited existing documentation, identified missing requirements, and worked with Product Development and Fulfillment to validate undocumented compatibility rules.

The result was centralized documentation that became the reference point for desktop, accessory, and frame compatibility.

### 2. Rebuilt Product Configuration Logic

The new catalog architecture needed to support:

- Multiple desktop depths
- Numerous desktop sizes
- Multiple desktop materials
- Frame color options
- Keypad selections
- Grommet configurations
- Compatible accessories

I updated configuration rules to ensure every customer selection generated valid SKU combinations while preventing incompatible products from being purchased.

### 3. Validated End-to-End Purchasing

Before launch, I tested the entire purchasing workflow, including:

- Product configuration logic
- SKU generation
- Shopping cart validation
- NetSuite mapping
- Order processing

Issues identified during testing were documented and coordinated with the development team prior to release.

### 4. Executed Production Launch

During the production release, the existing flagship product page was temporarily taken offline, updated, tested, and returned to production.

Total downtime remained under fifteen minutes.

---

## Architecture / Workflow

```text
Legacy Catalog

UPL960 (30")
        \
         \
          --> Multiple Frame Options
         /
UPL926 (24")


                ↓


New Catalog

            UPL960
               │
      Desktop Depth
               │
      Desktop Size
               │
      Desktop Material
               │
         V3 Frame
               │
          Keypad Option
               │
    Compatible Accessories
               │
      Valid SKU Generation
               │
      BigCommerce → NetSuite
```

---

## Results & Impact

The project successfully launched the V3 standing desk by transforming UPL960 into a unified configurable product that consolidated multiple legacy product experiences while preserving compatibility across tens of thousands of possible product configurations.

Key outcomes included:

- Successful Black Friday launch
- Less than 15 minutes of production downtime
- No major configurator issues after launch
- No incompatible product combinations reaching customers
- Successful SKU validation through BigCommerce and NetSuite
- Centralized compatibility documentation shared across teams
- Simplified purchasing experience by eliminating separate product pages for desktop depth and frame type

Although internal revenue metrics were not available, the project supported broader business goals of reducing customer confusion and simplifying the buying process.

---

## Skills Demonstrated

### E-commerce Operations

- Catalog Architecture
- Product Configuration Management
- SKU Architecture & Mapping
- Product Launch Coordination
- Release Management
- Risk Mitigation

### Product Data & Documentation

- Product Compatibility Documentation
- Business Rules Documentation
- Requirements Validation

### Platforms & Technical

- BigCommerce Administration
- NetSuite ERP
- Quality Assurance Testing

### Cross-Functional Collaboration

- Product Development
- Web Development
- Marketing
- Sales & Customer Service
- Shipping & Fulfillment

---

## Key Takeaways

This project demonstrated how thoughtful catalog architecture can improve both customer experience and operational efficiency.

Beyond implementing configuration logic, the work required translating complex product relationships into maintainable business rules, coordinating across multiple teams, and executing a high-risk production release with minimal downtime.

The centralized compatibility documentation created during the project also established a reusable reference that simplified future catalog maintenance and reduced the likelihood of configuration errors.

---

## Technologies Used

BigCommerce • NetSuite ERP • Threekit
