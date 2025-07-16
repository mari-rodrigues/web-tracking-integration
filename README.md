# web-tracking-integration

This project demonstrates a full integration of tracking, measurement, and privacy tools for a fictional coupon site called **MyBestDealz** (https://mybestdealz.shop/).

## Overview
The goal is to showcase a professional tracking setup as part of a personal portfolio, focusing on:

- Google Tag Manager (GTM)
- Google Analytics 4 (GA4)
- Cookie consent with Cookiebot (GDPR compliant)
- BigQuery (event data warehouse)
- Meta Pixel (in progress)

---

## Completed Steps

### 1. Landing Page (HTML + CSS)
- Responsive, minimalist layout with coupon cards
- Click events open a modal with coupon details

### 2. Google Tag Manager (GTM) Integration
- GTM configured and installed on the site
- Container published with custom events

### 3. Google Analytics 4 (GA4)
- GA4 property created
- GA4 Configuration Tag added via GTM
- Custom event `coupon_click` implemented
- `dataLayer.push()` used to send coupon interaction data

### 4. Cookie Consent with Cookiebot
- Cookie banner added via HTML tag in GTM
- Consent Mode enabled (`analytics_storage`)
- GA4 tags only fire after user consent

### 5. BigQuery
- Google Cloud project created: `mybestdealz-ga4`
- BigQuery API activated
- GA4 linked to BigQuery
- Daily event export enabled

---
