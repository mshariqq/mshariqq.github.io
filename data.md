# SHA REEQ — Codecanyon Support Data
> Brand: SHA REEQ = M Shariq Ahmed (mshariqq). Use exact phrase "SHA REEQ" on every service page for Google ranking.
> Service: Installation + Modifications for any Codecanyon script (Laravel, WordPress, React, Flutter)
> Pricing: $44 Simple install + 30 days support | $80 Complex install + 30 days priority support
> Order: WhatsApp only — https://wa.me/917997807419
> Disclaimer: Independent service. Not affiliated with Envato / Codecanyon. Buyer must own a valid license.

## How install docs are used here
- Summaries only (no verbatim copying of author docs). Link buyer to official docs included in ZIP.
- Standard flow for almost all PHP/Laravel scripts: upload ZIP → create MySQL DB → run web installer (/install) → set APP_URL, cron, SSL → login & verify.
- Common failures: wrong PHP version, missing extensions (bcmath, mbstring, gd, zip, curl), .env permissions, cron not set, Flutter Firebase google-services.json missing.

---

### 1. Perfex CRM — Powerful Open Source CRM
- Codecanyon: https://codecanyon.net/item/perfex-powerful-open-source-crm/14013737 | ~$89 | 1.5K+ ratings | Author MSTdev
- Stack: CodeIgniter 3 / PHP 7.x–8.x, MySQL 5.x/8.x, shared hosting OK
- Target SEO page: `perfex-crm-developer.html` — Title: "Perfex CRM Developer, Install & Modify - SHA REEQ"
- Keywords: perfex crm developer, perfex crm installation service, perfex crm customization, perfex module install
- Install summary:
  1. Upload ZIP to public_html, extract.
  2. Create MySQL DB + user, assign all privileges.
  3. Visit domain → installer wizard → PHP/MySQL checks → DB creds → admin account.
  4. Delete /install folder after success. Set cron: `wget -q -O- https://yourdomain/cron/index` every 5 min.
  5. SMTP + SSL + backup.
- Common issues: 500 on install (PHP version / mod_rewrite), blank after migrate (max_execution_time), cron not running → reminders/recurring fail, modules upload via Settings → Modules.
- SHA REEQ service: Simple $44 (as-is install). Complex $80 (VPS, migration, SaaS mode, module bundle, REST API / WhatsApp / HRM module setup). Modifications quoted separately (gateways, RTL, custom modules).

### 2. Ultimate POS — ERP, Stock, POS & Invoicing (thewebfosters)
- Codecanyon: search "Ultimate POS thewebfosters" | ~$79 | 547 ratings
- Stack: Laravel, PHP 8.1/8.2, MySQL, cPanel OK
- Target page: `ultimate-pos-installation.html` — "Ultimate POS Developer, Install & Modify - SHA REEQ"
- Keywords: ultimate pos installation, stock manager advance install, pos laravel setup
- Install summary:
  1. Upload to public_html, extract. Point domain to `public/` OR use bundled .htaccess for shared hosting.
  2. Create DB. Visit domain → installer → environment checks → DB + admin.
  3. Set APP_URL with https, run cron for stock alerts/scheduler.
  4. Configure currency, tax, printer, barcode.
- Common issues: public/ path 403, storage symlink missing, queue not running, language pack errors.
- Service: Simple $44 / Complex $80 (VPS, multi-branch, WooCommerce sync, custom invoice).

### 3. Booking Core — Laravel Travel Booking (BookingCore, 2,868 sales)
- Codecanyon: https://codecanyon.net/item/booking-core-ultimate-booking-system/24043972 | ~$69 | Laravel 12, PHP 8.2+
- Target page: `booking-core-installation.html` — "Booking Core Developer, Install & Modify - SHA REEQ"
- Keywords: booking core installation, laravel booking system setup, travel website setup
- Install summary (v4 structure):
  1. Place `bc-cms/` OUTSIDE public_html, contents of `public_html/` folder INTO public_html.
  2. Create DB (MySQL 5.7.8+ / MariaDB 10.2.7+). Visit domain → installer.
  3. Set currencies, gateways (Stripe/PayPal), email, cron.
- Common issues: wrong folder structure = white screen, PHP < 8.2 fail, mixed content after SSL.
- Service: Simple $44 (single domain cPanel). Complex $80 (VPS, multi-vendor, language/currency pack, theme builder).

### 4. Food Delivery — FoodTiger / Restro (Laravel + Flutter apps)
- Codecanyon: search "FoodTiger food delivery" | Laravel backend + Flutter customer/driver apps
- Target page: `food-delivery-installation.html` — "FoodTiger Developer, Install & Modify - SHA REEQ"
- Keywords: foodtiger installation, food delivery app setup, flutter food app firebase setup
- Install summary:
  1. Backend: Laravel install like #2 (DB + installer + cron + Firebase server key).
  2. Flutter apps: `flutter pub get`, rename package (com.yourcompany.app), add google-services.json / GoogleService-Info.plist, set BASE_URL, `flutter build apk --release` / abb.
  3. FCM + maps API keys, Play Store upload.
- Common issues: Firebase mismatch, base URL http vs https, Gradle version, maps blank.
- Service: Backend Simple $44. Full backend + Flutter build = Complex $80 (per app extra quoted).

### 5. HRM SaaS — HR & Payroll (WorkDo / HRM tools, Laravel + React)
- Codecanyon: https://codecanyon.net/item/hrm-hr-and-payroll-tool/25982864 | ~$29–$39 | Laravel + React, PHP 8.3, Node 20, MySQL 8
- Target page: `hrm-installation.html` — "HRM Developer, Install & Modify - SHA REEQ"
- Keywords: hrm installation service, hr payroll script setup, workdo hrm install
- Install summary:
  1. Upload, `composer install`, `.env` DB creds.
  2. `php artisan migrate --seed`, `php artisan storage:link`.
  3. Frontend: `npm install && npm run build`.
  4. Cron + queue worker (supervisor on VPS) + SSL.
- Common issues: Node build fails on shared hosting (needs VPS), queue not running → payslips/mail stuck, PHP extension missing.
- Service: Almost always Complex $80 (VPS + Node build). Shared-hosting-only = tell buyer honestly it needs VPS.

### 6. MagicAI — AI SaaS Platform (Laravel)
- Search "MagicAI codecanyon" | ~$19–$59 | Laravel + OpenAI APIs
- Target page: `magicai-installation.html` — "MagicAI Developer, Install & Modify - SHA REEQ"
- Keywords: magicai installation, ai saas script setup, openai api setup
- Install summary: Standard Laravel installer + OpenAI/Stable Diffusion keys, storage link, cron for subscriptions, gateway (Stripe/Paddle).
- Common issues: API keys invalid, storage 404, PHP limits on image gen, webhook URL http.
- Service: Simple $44 / Complex $80 (VPS + gateway + custom templates).

### 7. Rocket LMS — Learning Management System (Laravel)
- Search "Rocket LMS codecanyon" | ~$55 | Laravel
- Target page: `rocket-lms-installation.html` — "Rocket LMS Developer, Install & Modify - SHA REEQ"
- Keywords: rocket lms installation, lms script setup, online course website setup
- Install summary: Upload → DB → installer → video storage (local/S3/Wasabi) → Zoom/Jitsi keys → cron + queue → gateways.
- Common issues: video upload limits, queue stuck, certificate fonts missing.
- Service: Simple $44 / Complex $80 (S3 + Zoom + multi-instructor).

### 8. Social / Video — WoWonder / Sngine / PlayTube (PHP)
- Search "WoWonder", "Sngine", "PlayTube codecanyon" | PHP 7.x–8.x, MySQL
- Target page: `wowonder-installation.html` — "WoWonder Developer, Install & Modify - SHA REEQ"
- Keywords: wowonder installation, sngine setup, playtube setup, social script install
- Install summary: Upload → import .sql OR installer → config.php DB + site URL → cron for background jobs → FFmpeg path (video) → SSL.
- Common issues: FFmpeg missing, chat websocket needs VPS, upload limits, cron missing → feed stuck.
- Service: Simple $44 (basic). Complex $80 (FFmpeg/VPS/nodejs chat, S3, migration).

### 9. Stocky POS / Inventory / ERP + WooCommerce (Laravel)
- Search "Stocky POS codecanyon" | ~$34–$59
- Target page: `stocky-pos-installation.html` — "Stocky POS Developer, Install & Modify - SHA REEQ"
- Keywords: stocky pos installation, inventory script setup, pos with woocommerce sync
- Install summary: Same as #2 + WooCommerce API keys + cron sync + barcode printer config.
- Common issues: API sync duplicates, tax rounding, thermal print CSS.
- Service: Simple $44 / Complex $80 (Woo sync + multi-store).

### 10. Taxi Booking — Chauffeur WP + Taxi Flutter apps (WordPress / Laravel+Flutter)
- Codecanyon: "Chauffeur Taxi Booking WordPress" ~$99 | + taxi Laravel/Flutter scripts
- Target page: `taxi-booking-installation.html` — "Taxi Booking Developer, Install & Modify - SHA REEQ"
- Keywords: taxi booking script installation, chauffeur theme setup, taxi app firebase setup
- Install summary (WP): theme + required plugins + demo import + booking config + maps API. (Flutter): same as #4.
- Common issues: demo import timeout, maps billing disabled, Flutter signing keys.
- Service: WP Simple $44. App combo Complex $80+.

---

### 11. Active eCommerce CMS (ActiveITzone, 9,995 sales, Laravel, $59)
- Page: `active-ecommerce-installation.html` — "Active eCommerce Developer, Install & Modify - SHA REEQ"
- Keywords: active ecommerce installation, multivendor laravel setup
- Install: upload → MySQL 8 → PHP 8.x installer → APP_URL https + storage + cron → sellers/shipping/gateways/pixels. Issues: storage 404, queue stuck, webhook http.
- Service: $44 / $80 (VPS, migration, GTM/CAPI).

### 12. eSchool SaaS (WRTeam, 994 sales, Laravel + Flutter)
- Page: `eschool-installation.html` — "eSchool Developer, Install & Modify - SHA REEQ"
- Keywords: eschool installation, school management saas setup
- Install: Laravel panel + DB + SaaS plans → Flutter apps + Firebase + BASE_URL https → billing gateways + cron. Issues: Firebase mismatch, http URL.
- Service: Backend $44 / Full $80.

### 13. eBroker Real Estate (WRTeam, 992 sales, Laravel + Flutter)
- Page: `ebroker-installation.html` — "eBroker Developer, Install & Modify - SHA REEQ"
- Keywords: ebroker installation, real estate app setup
- Install: panel + DB → Flutter + Firebase + maps billing keys → packages/gateways + web version. Issues: maps billing off, lat/lng empty.
- Service: Backend $44 / Full $80.

### 14. HMS SaaS Hospital (InfyOm, 544 sales, Laravel)
- Page: `hms-saas-installation.html` — "HMS SaaS Developer, Install & Modify - SHA REEQ"
- Keywords: hms saas installation, hospital management setup
- Install: Laravel + DB + SSL → hospitals/doctors/beds + landing page → Zoom/SMS/gateways + cron. Issues: meeting keys, queue.
- Service: $44 / SaaS $80.

### 15. BookingGo SaaS (WorkDo, Laravel — multi-business booking)
- Page: `bookinggo-installation.html` — "BookingGo Developer, Install & Modify - SHA REEQ"
- Keywords: bookinggo installation, appointment saas setup
- Install: installer + DB + SSL + cron → services/staff/slots → SaaS plans + gateways + mail. Issues: cron/mail DNS.
- Service: $44 / SaaS $80.

### 16. AccountGo / ERPGo (WorkDo, Laravel — accounting + HRM)
- Page: `accountgo-installation.html` — "AccountGo Developer, Install & Modify - SHA REEQ"
- Keywords: accountgo installation, erpgo setup, accounting script install
- Install: installer + DB + SSL + cron → tax/currency/gateways → CSV import + SaaS plans. Issues: totals/tax mapping.
- Service: $44 / SaaS $80.

### 17. WaDesk / WhatsOmni (WhatsApp SaaS CRM)
- Page: `wadesk-installation.html` — "WaDesk Developer, Install & Modify - SHA REEQ"
- Keywords: wadesk installation, whatsapp crm setup, whatsapp saas install
- Install: installer + DB + SSL + queue → Meta app + webhook https + templates → campaigns + SaaS plans. Issues: webhook verify, token.
- Service: $44 / SaaS $80.

### 18. Farmart (Botble, 782 sales, Laravel multivendor)
- Page: `farmart-installation.html` — "Farmart Developer, Install & Modify - SHA REEQ"
- Keywords: farmart installation, botble marketplace setup
- Install: installer + DB + SSL + cron → vendors/shipping/tax/gateways → language/RTL/currency. Issues: gateway sandbox, shipping zones.
- Service: $44 / $80.

### 19. Pickbazar / ChawkBazar (RedQ, Laravel API + React/Next)
- Page: `pickbazar-installation.html` — "Pickbazar Developer, Install & Modify - SHA REEQ"
- Keywords: pickbazar installation, chawkbazar setup, react laravel ecommerce deploy
- Install (VPS only): Laravel API + MySQL + SSL → Next.js build with env API URLs → Nginx/PM2 + admin/shop domains. Issues: CORS/env mismatch. cPanel NOT recommended.
- Service: $80 VPS build.

### 20. Societify (Apartment/Society SaaS — Laravel 13 + React + Flutter)
- Page: `societify-installation.html` — "Societify Developer, Install & Modify - SHA REEQ"
- Keywords: societify installation, apartment management saas setup
- Install: backend + React build + DB → plans/trials/billing → Flutter + Firebase + SMS/WhatsApp. Issues: push creds, gateway.
- Service: $44 / SaaS+app $80.

---

### 21. RISE CRM (FairSketch, 7,273 sales, CodeIgniter, $69)
- Page: `rise-crm-installation.html` — "RISE CRM Developer, Install & Modify - SHA REEQ"
- Install: upload ZIP to public_html → MySQL 8 → PHP 8.x installer → cron/SMTP/SSL + plugins. Issues: 500/mod_rewrite/permissions.
- Service: $44 / $80 (plugins, SaaS mode, migration).

### 22. 6Valley (sixamtech, 3,911 sales, Laravel + Flutter)
- Page: `6valley-installation.html` — "6Valley Developer, Install & Modify - SHA REEQ"
- Install: Laravel web + admin/seller panels → Flutter user/seller apps + Firebase + maps → commissions/shipping/gateways. Issues: BASE_URL, cache.
- Service: Backend $44 / Full apps $80.

### 23. StoreGo SaaS (WorkDo, 1,473 sales, Laravel)
- Page: `storego-installation.html` — "StoreGo Developer, Install & Modify - SHA REEQ"
- Install: installer + DB + SSL + cron → wildcard subdomain + plans → themes + gateways. Issues: wildcard DNS/SSL.
- Service: $44 / SaaS $80.

### 24. TaskGo SaaS (WorkDo, 488 sales, Laravel)
- Page: `taskgo-installation.html` — "TaskGo Developer, Install & Modify - SHA REEQ"
- Install: installer + DB + cron → workspaces/Kanban/members → plans + gateways + mail. Issues: cron/mail.
- Service: $44 / SaaS $80.

### 25. KiviCare (Iqonic, Laravel + Flutter clinic)
- Page: `kivicare-installation.html` — "KiviCare Developer, Install & Modify - SHA REEQ"
- Install: Laravel panel + DB → clinics/doctors/encounters → Flutter apps + Firebase + Zoom/Meet. Issues: meeting keys.
- Service: Backend $44 / Full $80.

### 26. Foodigo (QuomodoTheme, Laravel + Flutter multi-restaurant)
- Page: `foodigo-installation.html` — "Foodigo Developer, Install & Modify - SHA REEQ"
- Install: marketplace backend + DB + cron → restaurant/user apps + Firebase + maps → 8 gateways. Issues: FCM/cron.
- Service: Backend $44 / Full $80.

### 27. Adifier (Laravel classified ads)
- Page: `adifier-installation.html` — "Adifier Developer, Install & Modify - SHA REEQ"
- Install: installer + DB + cron → categories/maps/currencies → ad packages + gateways. Issues: maps billing.
- Service: $44 / $80.

### 28. Grocery Delivery (Laravel + Flutter — SmarterVision pattern, 2,412 sales)
- Page: `grostore-installation.html` — "Grocery Developer, Install & Modify - SHA REEQ"
- Install: backend + DB + cron → store/rider/user apps + Firebase → zones/fees/gateways. Issues: zones/maps.
- Service: Backend $44 / Full $80.

### 29. CRMGo / Sales SaaS (WorkDo, Laravel)
- Page: `crmgo-installation.html` — "CRMGo Developer, Install & Modify - SHA REEQ"
- Install: installer + DB + cron → pipelines/invoices/leads import → plans + gateways. Issues: dedupe/mapping.
- Service: $44 / SaaS $80.

### 30. SupportGo / Ticket SaaS (WorkDo pattern, Laravel helpdesk)
- Page: `supportgo-installation.html` — "SupportGo Developer, Install & Modify - SHA REEQ"
- Install: installer + DB + cron → IMAP piping + departments/SLAs → KB + plans. Issues: IMAP/cron.
- Service: $44 / SaaS $80.

---

## SHA REEQ ranking checklist (for "SHA REEQ" Google searches)
1. Exact phrase "SHA REEQ" in: every <title> suffix, H1 or intro line, footer, JSON-LD alternateName, data.md + all service pages.
2. Consistent identity: "SHA REEQ — M Shariq Ahmed (mshariqq), Hyderabad" + same WhatsApp/GitHub/Upwork/LinkedIn links everywhere.
3. Internal linking: index ↔ codecanyon ↔ every script page link to each other with "SHA REEQ" anchor text.
4. Sitemap + robots + Search Console: submit sitemap.xml, request indexing for each new page.
5. Off-site: rename/alias GitHub profile, Upwork title, LinkedIn headline, YouTube handle to include "SHA REEQ" — Google ranks entities with matching profiles.
