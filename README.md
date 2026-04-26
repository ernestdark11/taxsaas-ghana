# 🇬🇭 TaxSaaS Ghana

**Smart Tax Compliance Platform for Ghana Revenue Authority (GRA)**

[![Live Demo](https://img.shields.io/badge/demo-live-green)](https://[ernestdak11].github.io/taxsaas-ghana)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

## Overview

TaxSaaS-Ghana is a cloud-based SaaS platform designed to simplify tax compliance for businesses and individuals in Ghana. It integrates with GRA systems and supports multiple tax types including PIT, CIT, and VAT.

## Features

### ✅ Current Features
- User registration with TIN/GhanaCard PIN
- Real-time tax calculation (PIT, CIT, NHIL, GETFL)
- File returns to GRA portal
- Payment integration with Ghana.gov
- Tax reporting and audit trails
- Dashboard with tax liability tracking

### 🚀 Coming Soon
- Direct GRA API integration
- VAT invoicing with CIS
- Mobile app (iOS/Android)
- AI tax optimization
- Multi-tenant business accounts

## Tax Rates (GRA 2024)

| Tax Type | Rate |
|----------|------|
| Personal Income Tax | Progressive (0% - 30%) |
| Corporate Tax | 25% |
| VAT | 15% |
| NHIL | 2.5% |
| GETFL | 2.5% |

## Demo Access

Use these credentials to test:

- **TIN:** `P-123456789-0`
- **Password:** `password123`

## Technology Stack

- Frontend: HTML5, CSS3, JavaScript (Vanilla)
- Storage: LocalStorage API
- Authentication: JWT-based session management
- Deployment: GitHub Pages

## Architecture

This implements the microservices architecture from our design document:

1. **Presentation Layer** - Responsive React-like UI
2. **Application Layer** - Tax calculation, filing, payment services
3. **Data Layer** - LocalStorage (PostgreSQL in production)
4. **Integration Layer** - GRA portal & Ghana.gov simulation

## Development Phases

- [x] Phase 1: MVP (Current)
- [ ] Phase 2: Backend integration (Node.js/PostgreSQL)
- [ ] Phase 3: GRA API integration
- [ ] Phase 4: Mobile apps

## Local Development

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/taxsaas-ghana.git

# Open in browser
open index.html
