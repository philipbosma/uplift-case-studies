# Maintaining UPLIFT Desk's Configurable Product Ecosystem

### Product Configuration Management • Catalog Architecture • E-commerce Operations

---

## Overview

Throughout my time at UPLIFT Desk, I helped maintain and expand the configurable product ecosystem that powered the company's e-commerce platform.

Alongside maintaining individual product listings, I managed the configuration logic that allowed customers to build highly customized desks from thousands of compatible component combinations. Product launches, discontinued products, new accessories, compatibility rules, inventory changes, and purchasing logic all had to integrate seamlessly into an interconnected e-commerce system.

Although customers experienced a simple step-by-step configurator, every selection relied on complex business rules governing product compatibility, SKU generation, purchasing restrictions, inventory, and fulfillment.

---

## At a Glance

<table>
  <tbody>
    <tr>
      <td><strong>Company</strong></td>
      <td>UPLIFT Desk</td>
    </tr>
    <tr>
      <td><strong>Work Scope</strong></td>
      <td>Configurable standing desk product ecosystem</td>
    </tr>
    <tr>
      <td><strong>Role</strong></td>
      <td>Product Configuration Management &amp; Catalog Operations</td>
    </tr>
    <tr>
      <td><strong>Platforms</strong></td>
      <td>BigCommerce, Contentful, NetSuite, GitHub</td>
    </tr>
    <tr>
      <td><strong>Scale / Complexity</strong></td>
      <td>50,000+ possible desk configurations across multiple product families</td>
    </tr>
    <tr>
      <td><strong>Primary Responsibilities</strong></td>
      <td>Product configuration, compatibility management, purchasing rules, SKU architecture</td>
    </tr>
    <tr>
      <td><strong>Primary Stakeholders</strong></td>
      <td>Content, Product Development, Web Development, Order Fulfillment</td>
    </tr>
    <tr>
      <td><strong>Key Skills</strong></td>
      <td>Catalog Architecture, Product Configuration, Product Data Management, QA Testing</td>
    </tr>
  </tbody>
</table>

---

## Business Challenge

UPLIFT Desk's standing desks were built from dozens of configurable components including desktop materials, sizes, frames, keypads, accessories, and numerous product-specific options.

Unlike a traditional e-commerce catalog where each product is represented by a single SKU, every configurable option introduced new compatibility relationships that had to be maintained throughout the storefront.

Each product family exposed different configuration options depending on its design and compatibility requirements. The available options, purchasing rules, and customer workflow varied dynamically based on the product being configured.

Maintaining this ecosystem required ensuring customers could only build valid desk configurations while preserving accurate pricing, inventory, and fulfillment across every connected system.

---

## My Role

My role centered on maintaining the integrity of this configuration ecosystem as new products were introduced and existing products evolved.

Responsibilities included:

- Launching new desktop materials, accessories, and configurable product options
- Retiring discontinued products and configuration options
- Building and maintaining compatibility relationships
- Creating and updating purchasing rules
- Maintaining SKU mappings between BigCommerce and NetSuite
- Updating inventory availability and estimated shipping information
- Supporting frontend functionality required for new configuration options
- Collaborating with Product Development, Web Development, and Order Fulfillment teams

Beyond implementation, I regularly reviewed product documentation to identify conflicting requirements, missing compatibility information, and edge cases before work began.

---

## Approach / Implementation

Every catalog update followed a structured validation process designed to protect the integrity of the entire product ecosystem.

### 1. Review Product Requirements

- Review specifications
- Validate compatibility requirements
- Clarify missing documentation
- Identify implementation risks

### 2. Configure Products

- Create configurable options
- Configure pricing
- Build purchasing rules
- Configure metadata
- Update product availability

### 3. Update Connected Systems

- Upload product assets
- Update Contentful
- Create or update NetSuite SKUs
- Verify cross-system mappings

### 4. Validate the Configuration

Testing included:

- Product configurator behavior
- Compatibility validation
- Purchasing rule validation
- Image verification
- Test orders
- BigCommerce → NetSuite synchronization
- Final SKU validation

When new product functionality required frontend updates, I implemented smaller enhancements through GitHub pull requests and partnered with Web Development on larger feature work.

---

## Architecture / Workflow

Supporting this level of product customization required solving several architectural challenges.

Because BigCommerce imposed practical limits on the number of child SKUs that could exist within a single product listing, UPLIFT used a modular configuration architecture built around **product pick-list options**.

Rather than creating a SKU for every possible desk combination, the primary product listing stored only the base desktop configuration.

As customers customized their desks, additional hidden product options dynamically injected component SKUs—including frames, keypads, accessories, and other configurable products—into the final order.

This architecture allowed more than **50,000 purchasable configurations** while remaining within BigCommerce's platform limitations.

It also enabled shared components to be reused across multiple product families while simplifying inventory management.

```text
Base Desktop Configuration
            │
            ▼
Customer Option Selections
            │
            ├── Frame SKU
            ├── Keypad SKU
            ├── Accessory SKUs
            └── Additional Component SKUs
            │
            ▼
Compatibility & Purchasing Rules
            │
            ▼
Final Purchasable Configuration
            │
            ▼
BigCommerce → NetSuite → Fulfillment
```

---

## Results & Impact

Maintaining this ecosystem enabled UPLIFT Desk to continuously expand its configurable product catalog while preserving a reliable customer purchasing experience.

My work helped ensure that:

- New products integrated into existing product families without disrupting customer workflows.
- Customers could only purchase valid product configurations.
- Product data remained synchronized across BigCommerce, Contentful, and NetSuite.
- Fulfillment teams received accurate SKU configurations for every order.
- The configurator continued to scale as new products and accessories were introduced.

Although much of this work happened behind the scenes, it directly supported the reliability, scalability, and long-term maintainability of one of UPLIFT Desk's most sophisticated e-commerce experiences.

---

## Skills Demonstrated

### E-commerce Operations

- Product Configuration Management
- Catalog Architecture
- Product Catalog Management
- Purchasing Rule Development
- Product Launch Coordination
- Compatibility Management
- SKU Architecture

### Product Data & Documentation

- Product Data Management
- Technical Documentation Review
- Requirements Validation

### Platforms & Technical

- BigCommerce Administration
- Contentful CMS
- NetSuite ERP
- HTML, CSS & JavaScript
- Git & GitHub
- Pull Request Workflow
- Quality Assurance Testing

### Cross-Functional Collaboration

- Copywriting
- Web Development
- Marketing & SEO
- Multimedia Production
- Product Development
- Order Fulfillment

---

## Key Takeaways

This work reinforced that highly configurable e-commerce experiences depend on far more than product data.

Successful product configuration requires carefully managing compatibility relationships, purchasing rules, inventory systems, ERP integrations, frontend behavior, and fulfillment workflows as a unified system.

While customers saw a simple product configurator, maintaining that experience required continuous coordination across multiple teams and technologies to ensure every possible configuration remained accurate, purchasable, and fulfillable.

---

## Technologies Used

BigCommerce • Contentful CMS • NetSuite ERP • HTML • CSS • JavaScript • Git • GitHub
