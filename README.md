# 🧪 TestCraft Pro — Automation Practice Hub

A complete, beautiful web application built for **Testsigma automation practice**. Covers every major UI component and end-to-end user flow.

## 🚀 Live Demo

Host on GitHub Pages: `https://<your-username>.github.io/<repo-name>/`

## 📋 Pages & Components

| Page | Components |
|------|-----------|
| **Home** | Hero, stat cards, feature grid, navigation |
| **Forms** | Registration, Login, Profile, Advanced Inputs |
| **Components** | Modals, Tabs, Accordion, Alerts, Toasts, Tooltips, Pagination, Calendar, Drag & Drop, iFrame |
| **Tables** | Sortable table, Search/Filter, Bulk actions, Inline CRUD, CSV Export |
| **Shop** | Product grid, Category filter, Add to Cart, Mini cart |
| **Checkout** | Multi-step stepper, Shipping form, Payment form with card preview, Coupon, Order confirm |
| **Dashboard** | Bar chart, Donut chart, KPI cards, Activity feed, Team leaderboard |

## 🏷️ data-testid Reference

Every interactive element has a `data-testid` attribute for easy Testsigma locators:

```
Registration: first-name, last-name, email, phone, password, confirm-password,
              country, role-qa, role-dev, role-pm, terms, newsletter, register-btn

Login: login-email, login-password, remember-me, login-btn, google-login, github-login

Profile: display-name, bio, website, dob, gender, profile-color,
         notif-email, notif-push, notif-digest, save-profile

Advanced: volume-slider, price-slider, rating-slider, adv-date, adv-time,
          adv-search, adv-number, file-drop, file-input, chip-*, star-*

Modals: open-info-modal, open-confirm-modal, open-form-modal, open-delete-modal,
        close-info-modal, ok-info-modal, cancel-confirm, confirm-action, modal-submit

Table: table-search, status-filter, export-csv, add-row-btn, select-all,
       col-id, col-name, col-status, run-TC-*, edit-TC-*, delete-TC-*

Shop: cat-all, cat-electronics, cat-books, cat-accessories, cat-clothing,
      sort-price-low, sort-price-high, sort-name, product-*, add-cart-*, go-checkout

Checkout: sh-fname, sh-lname, sh-email, sh-addr1, sh-city, sh-zip, sh-country,
          ship-standard, ship-express, ship-overnight, next-to-payment,
          card-number, card-name, card-expiry, card-cvv, next-to-review,
          coupon-input, apply-coupon, place-order, continue-shopping

Dashboard: dash-range, refresh-dash, export-team, bar-chart, donut-chart

Calendar: cal-prev, cal-next, cal-day-{N}

Drag & Drop: col-todo, col-inprogress, col-done, drag-tc{N}

Pagination: prev-page, page-1..5, next-page
```

## 🎯 E2E Test Flows

1. **Registration Flow** → Fill form → Validate errors → Submit → Redirect to login
2. **Login Flow** → Use `test@example.com / Test@1234` → Lands on Dashboard
3. **Shopping Flow** → Browse products → Add to cart → Checkout → Place order → Confirmation
4. **Table CRUD** → Add row → Edit → Delete → Sort → Filter → Export CSV
5. **Multi-step Checkout** → Shipping → Payment (card formatting) → Review + Coupon → Confirm

## 🛠️ Setup for GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Visit `https://<username>.github.io/<repo>/`

## 💻 Local Development

Just open `index.html` in any browser — no build step required!

```bash
# Optional: use a local server
npx serve .
# or
python3 -m http.server 8080
```

## ✅ Test Credentials

| Field | Value |
|-------|-------|
| Email | test@example.com |
| Password | Test@1234 |
| Coupon Code | SAVE10, QA20, HALF50 |

---
Built for Testsigma automation practice 🚀
