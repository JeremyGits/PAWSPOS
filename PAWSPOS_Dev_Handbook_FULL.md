# PAWSPOS Developer Handbook — Full Source Map
_Last generated: **2025-08-15 03:25 UTC**_

This document enumerates **every file** in the uploaded source tree (backend + frontend) and annotates it with an inferred role and any top-of-file header comment detected. Use this as your onboarding map alongside inline code.

> Tip: Search within this file (Ctrl/Cmd+F) for a filename or folder (e.g. `routes/`, `models/`, `pos/`) to jump quickly.

---

## Project Tree (annotated)
- `PAWSPOS/README.md`  — *Project README*
- `PAWSPOS/backend/config/db.js`  — *Backend configuration*
- `PAWSPOS/backend/config/doge.js`  — *Backend configuration*
- `PAWSPOS/backend/config/env.js`  — *Backend configuration*
- `PAWSPOS/backend/controllers/auth.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/categories.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/category.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/inventory.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/modifier.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/orders.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/payments.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/payments.internal.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/payroll.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/product.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/products.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/reports.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/staff.controller.js`  — *Backend controller*
- `PAWSPOS/backend/controllers/time.controller.js`  — *Backend controller*
- `PAWSPOS/backend/crypto/dogeHd.js`  — *Backend source file*
- `PAWSPOS/backend/crypto/dogeRpc.js`  — *Backend source file*
- `PAWSPOS/backend/middleware/auth.js`  — *Backend middleware*
- `PAWSPOS/backend/middleware/authRequired.js`  — *Backend middleware*
- `PAWSPOS/backend/middleware/errorHandler.js`  — *Backend middleware*
- `PAWSPOS/backend/middleware/notFound.js`  — *Backend middleware*
- `PAWSPOS/backend/middleware/rateLimiter.js`  — *Backend middleware*
- `PAWSPOS/backend/middleware/requestId.js`  — *Backend middleware*
- `PAWSPOS/backend/middleware/requireAuth.js`  — *Backend middleware*
- `PAWSPOS/backend/middleware/requireRoles.js`  — *Backend middleware*
- `PAWSPOS/backend/middleware/roles.js`  — *Backend middleware*
- `PAWSPOS/backend/models/Inventory.js`  — *Backend data model*
- `PAWSPOS/backend/models/User.js`  — *Backend data model*
- `PAWSPOS/backend/models/category.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/device.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/deviceCode.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/deviceProfile.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/inventory/item.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/inventory/location.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/inventory/stockLevel.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/inventory/stockMove.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/inventoryItem.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/inventoryLevel.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/ledgerEntry.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/location.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/modifier.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/order.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/payment.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/payrun.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/posMode.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/printerProfile.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/product.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/staff.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/stockLedger.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/timesheet.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/tx.model.js`  — *Backend data model*
- `PAWSPOS/backend/models/wallet.model.js`  — *Backend data model*
- `PAWSPOS/backend/package-lock.json`  — *Backend source file*
- `PAWSPOS/backend/package.json`  — *Backend source file*
- `PAWSPOS/backend/payments/engine.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/payments/providers/baseProvider.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/payments/providers/coinbaseCommerce.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/payments/providers/coinremitterDoge.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/payments/providers/cryptoSim.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/payments/providers/dogecoinCore.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/payments/providers/gigawallet.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/payments/providers/mockAcquirer.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/payments/providers/stripeTerminal.js`  — *Payments provider/adapter*
- `PAWSPOS/backend/routes/auth.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/categories.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/category.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/devices.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/doge.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/inventory.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/modifier.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/orders.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/payments.doge.gw.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/payments.doge.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/payments.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/payroll.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/products.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/profiles.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/rates.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/reports.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/settings.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/staff.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/time.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/wallets.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/webhooks.coinbase.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/webhooks.coinremitter.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/webhooks.doge.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/webhooks.gigawallet.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/webhooks.routes.js`  — *Backend route*
- `PAWSPOS/backend/routes/webhooks.stripe.routes.js`  — *Backend route*
- `PAWSPOS/backend/scripts/bootstrap-db.js`  — *Backend source file*
- `PAWSPOS/backend/scripts/helpers/ensure-user.mjs`  — *Backend source file*
- `PAWSPOS/backend/scripts/init-indexes.js`  — *Backend source file*
- `PAWSPOS/backend/scripts/migrations/20250812-add-emailNorm.mjs`  — *Backend source file*
- `PAWSPOS/backend/scripts/peek-admin.js`  — *Backend source file*
- `PAWSPOS/backend/scripts/reset-admin.js`  — *Backend source file*
- `PAWSPOS/backend/scripts/seed-admin.js`  — *Backend source file*
- `PAWSPOS/backend/scripts/seed-modes-and-profiles.mjs`  — *Backend source file*
- `PAWSPOS/backend/scripts/seed.js`  — *Backend source file*
- `PAWSPOS/backend/scripts/update-payments-validator.mjs`  — *Backend source file*
- `PAWSPOS/backend/server.js`  — *Backend server entrypoint*
- `PAWSPOS/backend/services/coinbase.service.js`  — *Backend service*
- `PAWSPOS/backend/services/dogePrice.js`  — *Backend service*
- `PAWSPOS/backend/services/dogeWallet.service.js`  — *Backend service*
- `PAWSPOS/backend/services/dogeWatcher.js`  — *Backend service*
- `PAWSPOS/backend/services/orderNumber.js`  — *Backend service*
- `PAWSPOS/backend/services/rates.service.js`  — *Backend service*
- `PAWSPOS/backend/services/stripe-service.js`  — *Backend service*
- `PAWSPOS/backend/services/stripe.service.js`  — *Backend service*
- `PAWSPOS/backend/services/tax.service.js`  — *Backend service*
- `PAWSPOS/backend/services/tokenVault.service.js`  — *Backend service*
- `PAWSPOS/backend/services/ws.service.js`  — *Backend service*
- `PAWSPOS/backend/utils/asyncHandler.js`  — *Backend utility*
- `PAWSPOS/backend/utils/hashChain.js`  — *Backend utility*
- `PAWSPOS/backend/utils/logger.js`  — *Backend utility*
- `PAWSPOS/backend/utils/money.js`  — *Backend utility*
- `PAWSPOS/backend/utils/payrollMath.js`  — *Backend utility*
- `PAWSPOS/backend/validation/auth.validation.js`  — *Backend source file*
- `PAWSPOS/frontend/index.html`  — *Frontend source file*
- `PAWSPOS/frontend/package-lock.json`  — *Frontend source file*
- `PAWSPOS/frontend/package.json`  — *Frontend source file*
- `PAWSPOS/frontend/src/App.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/api/client.js`  — *Frontend source file*
- `PAWSPOS/frontend/src/api/devices.js`  — *Frontend source file*
- `PAWSPOS/frontend/src/api/profiles.js`  — *Frontend source file*
- `PAWSPOS/frontend/src/components/AnonymousOnly.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/DogeCheckout.tsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/Handheld/HandheldOrderScreen.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/Kiosk/Bar/BarPosScreen.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/Kiosk/Kitchen/KitchenScreen.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/Kiosk/Restaurant/RestaurantPosScreen.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/MobilePOS/MobilePosScreen.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/POS/PosScreen.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/Protected.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/StatCard.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/Table.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/TopNav.jsx`  — *Frontend UI component*
- `PAWSPOS/frontend/src/components/topnav.css`  — *Frontend UI component*
- `PAWSPOS/frontend/src/context/AuthProvider.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/hooks/useApi.js`  — *Frontend hook*
- `PAWSPOS/frontend/src/hooks/useStripeTerminal.js`  — *Frontend hook*
- `PAWSPOS/frontend/src/layout/DashboardShell.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/layout/Layout.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/layout/Sidebar.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/layout/TopBar.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/layout/TopNav.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/layout/topnav.css`  — *Frontend source file*
- `PAWSPOS/frontend/src/main.jsx`  — *Frontend entrypoint*
- `PAWSPOS/frontend/src/pages/Dashboard.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/NotFound.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/_Scaffold.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/admin/Admin.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/auth/Login.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/auth/Logout.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/customers/Customers.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/dashboard/Dashboard.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/dashboard/Home.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/dashboard/dashboard.css`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/devices/Devices.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/items/Categories.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/items/InventoryOverview.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/items/ItemLibrary.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/items/Modifiers.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/orders/Orders.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/payments/CryptoPay.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/payments/Overview.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/payments/VirtualTerminal.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/pos/BarDisplay.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/pos/Kiosk.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/pos/KitchenDisplay.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/pos/ModifierDialog.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/pos/POSModeRouter.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/pos/StandardPOS.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/pricing/Discounts.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/profiles/Profiles.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/reports/PaymentMethods.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/reports/Reports.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/reports/SalesSummary.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/reports/_SalesGauge.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/settings/General.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/terminal/Crypto.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pages/terminal/Terminal.jsx`  — *Frontend page/screen*
- `PAWSPOS/frontend/src/pos/checkout.js`  — *POS UI logic*
- `PAWSPOS/frontend/src/router.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/services/api.js`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/dashboard/CategoriesCard.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/dashboard/CustomersCard.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/dashboard/ItemsCard.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/dashboard/KPIs.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/dashboard/PaymentTypeChart.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/dashboard/SetupChecklist.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/dashboard/widgets.css`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/useDashboardData.js`  — *Frontend source file*
- `PAWSPOS/frontend/src/shared/useDashboardData.jsx`  — *Frontend source file*
- `PAWSPOS/frontend/src/theme/index.js`  — *Frontend source file*
- `PAWSPOS/frontend/src/theme/presets.js`  — *Frontend source file*
- `PAWSPOS/frontend/src/utils/ledger.js`  — *Frontend utility*
- `PAWSPOS/frontend/src/utils/money.js`  — *Frontend utility*
- `PAWSPOS/frontend/src/validation/loginSchema.js`  — *Frontend source file*
- `PAWSPOS/frontend/vite.config.js`  — *Frontend source file*

---

## File-by-File Notes
Below are per-file notes. If a file lacks a header comment, the description is inferred from its path and name.

### `PAWSPOS/README.md`
- **Role:** Project README
- **Size:** 181 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/config/db.js`
- **Role:** Backend configuration
- **Size:** 429 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/config/doge.js`
- **Role:** Backend configuration
- **Size:** 598 bytes
- **Overview:** config/doge.js

### `PAWSPOS/backend/config/env.js`
- **Role:** Backend configuration
- **Size:** 18 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/controllers/auth.controller.js`
- **Role:** Backend controller
- **Size:** 5777 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/controllers/categories.controller.js`
- **Role:** Backend controller
- **Size:** 1596 bytes
- **Overview:** GET /api/categories

### `PAWSPOS/backend/controllers/category.controller.js`
- **Role:** Backend controller
- **Size:** 2634 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/controllers/inventory.controller.js`
- **Role:** Backend controller
- **Size:** 11059 bytes
- **Overview:** controllers/inventory.controller.js

### `PAWSPOS/backend/controllers/modifier.controller.js`
- **Role:** Backend controller
- **Size:** 3779 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/controllers/orders.controller.js`
- **Role:** Backend controller
- **Size:** 5580 bytes
- **Overview:** Build line items from client items

### `PAWSPOS/backend/controllers/payments.controller.js`
- **Role:** Backend controller
- **Size:** 4177 bytes
- **Overview:** shared schema

### `PAWSPOS/backend/controllers/payments.internal.controller.js`
- **Role:** Backend controller
- **Size:** 2444 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/controllers/payroll.controller.js`
- **Role:** Backend controller
- **Size:** 3975 bytes
- **Overview:** controllers/payroll.controller.js

### `PAWSPOS/backend/controllers/product.controller.js`
- **Role:** Backend controller
- **Size:** 880 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/controllers/products.controller.js`
- **Role:** Backend controller
- **Size:** 5020 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/controllers/reports.controller.js`
- **Role:** Backend controller
- **Size:** 2910 bytes
- **Overview:** GET /api/reports/dashboard Returns the shape your <Home/> expects: {   keyMetrics: { netSales, grossSales, returns, transactions, avgNetSale, inventoryValue },

### `PAWSPOS/backend/controllers/staff.controller.js`
- **Role:** Backend controller
- **Size:** 1926 bytes
- **Overview:** controllers/staff.controller.js

### `PAWSPOS/backend/controllers/time.controller.js`
- **Role:** Backend controller
- **Size:** 1573 bytes
- **Overview:** controllers/time.controller.js

### `PAWSPOS/backend/crypto/dogeHd.js`
- **Role:** Backend source file
- **Size:** 2542 bytes
- **Overview:** Dogecoin network params for dogecoinjs-lib:

### `PAWSPOS/backend/crypto/dogeRpc.js`
- **Role:** Backend source file
- **Size:** 997 bytes
- **Overview:** (Optional) tiny helper to log RPC target once at boot

### `PAWSPOS/backend/middleware/auth.js`
- **Role:** Backend middleware
- **Size:** 891 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/middleware/authRequired.js`
- **Role:** Backend middleware
- **Size:** 623 bytes
- **Overview:** middleware/authRequired.js

### `PAWSPOS/backend/middleware/errorHandler.js`
- **Role:** Backend middleware
- **Size:** 459 bytes
- **Overview:** Default export (ESM)

### `PAWSPOS/backend/middleware/notFound.js`
- **Role:** Backend middleware
- **Size:** 207 bytes
- **Overview:** Default export (ESM)

### `PAWSPOS/backend/middleware/rateLimiter.js`
- **Role:** Backend middleware
- **Size:** 212 bytes
- **Overview:** Default export (ESM)

### `PAWSPOS/backend/middleware/requestId.js`
- **Role:** Backend middleware
- **Size:** 303 bytes
- **Overview:** Named export (ESM)

### `PAWSPOS/backend/middleware/requireAuth.js`
- **Role:** Backend middleware
- **Size:** 2759 bytes
- **Overview:** Pull bearer token from Authorization header.

### `PAWSPOS/backend/middleware/requireRoles.js`
- **Role:** Backend middleware
- **Size:** 326 bytes
- **Overview:** middleware/requireRoles.js

### `PAWSPOS/backend/middleware/roles.js`
- **Role:** Backend middleware
- **Size:** 188 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/models/Inventory.js`
- **Role:** Backend data model
- **Size:** 370 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/models/User.js`
- **Role:** Backend data model
- **Size:** 2938 bytes
- **Overview:** include legacy alias 'self_checkout' so validation doesn't explode

### `PAWSPOS/backend/models/category.model.js`
- **Role:** Backend data model
- **Size:** 599 bytes
- **Overview:** Category - name: unique label (“Food”, “Drinks”, …) - parent: optional nested categories - routeTag: optional hint for Kitchen/Bar routing

### `PAWSPOS/backend/models/device.model.js`
- **Role:** Backend data model
- **Size:** 979 bytes
- **Overview:** models/device.model.js

### `PAWSPOS/backend/models/deviceCode.model.js`
- **Role:** Backend data model
- **Size:** 670 bytes
- **Overview:** models/deviceCode.model.js

### `PAWSPOS/backend/models/deviceProfile.model.js`
- **Role:** Backend data model
- **Size:** 720 bytes
- **Overview:** models/deviceProfile.model.js

### `PAWSPOS/backend/models/inventory/item.model.js`
- **Role:** Backend data model
- **Size:** 908 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/models/inventory/location.model.js`
- **Role:** Backend data model
- **Size:** 624 bytes
- **Overview:** models/location.model.js

### `PAWSPOS/backend/models/inventory/stockLevel.model.js`
- **Role:** Backend data model
- **Size:** 476 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/models/inventory/stockMove.model.js`
- **Role:** Backend data model
- **Size:** 656 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/models/inventoryItem.model.js`
- **Role:** Backend data model
- **Size:** 1574 bytes
- **Overview:** models/inventoryItem.model.js

### `PAWSPOS/backend/models/inventoryLevel.model.js`
- **Role:** Backend data model
- **Size:** 902 bytes
- **Overview:** models/inventoryLevel.model.js

### `PAWSPOS/backend/models/ledgerEntry.model.js`
- **Role:** Backend data model
- **Size:** 1194 bytes
- **Overview:** Double-entry ledger journal: every “event” (payment/refund/settlement) posts >=2 lines amountCents is signed on lines (debit=+ / credit=-). Sum(lines.amountCents) must be 0.

### `PAWSPOS/backend/models/location.model.js`
- **Role:** Backend data model
- **Size:** 466 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/models/modifier.model.js`
- **Role:** Backend data model
- **Size:** 907 bytes
- **Overview:** Keep one index statement

### `PAWSPOS/backend/models/order.model.js`
- **Role:** Backend data model
- **Size:** 2382 bytes
- **Overview:** Keep all amounts in CENTS

### `PAWSPOS/backend/models/payment.model.js`
- **Role:** Backend data model
- **Size:** 2317 bytes
- **Overview:** backend/models/payment.model.js

### `PAWSPOS/backend/models/payrun.model.js`
- **Role:** Backend data model
- **Size:** 1490 bytes
- **Overview:** models/payrun.model.js

### `PAWSPOS/backend/models/posMode.model.js`
- **Role:** Backend data model
- **Size:** 543 bytes
- **Overview:** models/posMode.model.js

### `PAWSPOS/backend/models/printerProfile.model.js`
- **Role:** Backend data model
- **Size:** 890 bytes
- **Overview:** models/printerProfile.model.js

### `PAWSPOS/backend/models/product.model.js`
- **Role:** Backend data model
- **Size:** 1245 bytes
- **Overview:** backend/models/product.model.js

### `PAWSPOS/backend/models/staff.model.js`
- **Role:** Backend data model
- **Size:** 1265 bytes
- **Overview:** models/staff.model.js

### `PAWSPOS/backend/models/stockLedger.model.js`
- **Role:** Backend data model
- **Size:** 1195 bytes
- **Overview:** models/stockLedger.model.js

### `PAWSPOS/backend/models/timesheet.model.js`
- **Role:** Backend data model
- **Size:** 808 bytes
- **Overview:** models/timesheet.model.js

### `PAWSPOS/backend/models/tx.model.js`
- **Role:** Backend data model
- **Size:** 855 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/models/wallet.model.js`
- **Role:** Backend data model
- **Size:** 1038 bytes
- **Overview:** HD derivation metadata

### `PAWSPOS/backend/package-lock.json`
- **Role:** Backend source file
- **Size:** 299175 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/package.json`
- **Role:** Backend source file
- **Size:** 1450 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/payments/engine.js`
- **Role:** Payments provider/adapter
- **Size:** 2117 bytes
- **Overview:** payments/engine.js

### `PAWSPOS/backend/payments/providers/baseProvider.js`
- **Role:** Payments provider/adapter
- **Size:** 350 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/payments/providers/coinbaseCommerce.js`
- **Role:** Payments provider/adapter
- **Size:** 1619 bytes
- **Overview:** backend/payments/providers/coinbaseCommerce.js

### `PAWSPOS/backend/payments/providers/coinremitterDoge.js`
- **Role:** Payments provider/adapter
- **Size:** 3333 bytes
- **Overview:** Create a unique DOGE deposit address for an order. DOCS: POST https://api.coinremitter.com/v1/wallet/address/create Common fields: api_key, password, label

### `PAWSPOS/backend/payments/providers/cryptoSim.js`
- **Role:** Payments provider/adapter
- **Size:** 601 bytes
- **Overview:** capture/refund handled by webhook/confirm in controller for sim

### `PAWSPOS/backend/payments/providers/dogecoinCore.js`
- **Role:** Payments provider/adapter
- **Size:** 1797 bytes
- **Overview:** getnewaddress "label" "bech32"

### `PAWSPOS/backend/payments/providers/gigawallet.js`
- **Role:** Payments provider/adapter
- **Size:** 1783 bytes
- **Overview:** Create/ensure an Account (one per POS/user)

### `PAWSPOS/backend/payments/providers/mockAcquirer.js`
- **Role:** Payments provider/adapter
- **Size:** 1845 bytes
- **Overview:** source.cardToken is required (from terminal simulator or future hardware)

### `PAWSPOS/backend/payments/providers/stripeTerminal.js`
- **Role:** Payments provider/adapter
- **Size:** 1359 bytes
- **Overview:** backend/payments/providers/stripeTerminal.js

### `PAWSPOS/backend/routes/auth.routes.js`
- **Role:** Backend route
- **Size:** 610 bytes
- **Overview:** cookie parser only for this router (for /refresh)

### `PAWSPOS/backend/routes/categories.routes.js`
- **Role:** Backend route
- **Size:** 342 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/routes/category.routes.js`
- **Role:** Backend route
- **Size:** 747 bytes
- **Overview:** Read (any authenticated)

### `PAWSPOS/backend/routes/devices.routes.js`
- **Role:** Backend route
- **Size:** 2330 bytes
- **Overview:** routes/devices.routes.js

### `PAWSPOS/backend/routes/doge.routes.js`
- **Role:** Backend route
- **Size:** 3408 bytes
- **Overview:** Create a unique DOGE deposit address for a sale/cashier/terminal. Body: { orderId?, amountCents, currency='USD', label? } Returns: { paymentId, address, label, expectedDoge, usdPerDoge }

### `PAWSPOS/backend/routes/inventory.routes.js`
- **Role:** Backend route
- **Size:** 924 bytes
- **Overview:** routes/inventory.routes.js

### `PAWSPOS/backend/routes/modifier.routes.js`
- **Role:** Backend route
- **Size:** 775 bytes
- **Overview:** Read (any authenticated)

### `PAWSPOS/backend/routes/orders.routes.js`
- **Role:** Backend route
- **Size:** 923 bytes
- **Overview:** List / view (kitchen, bar, manager, admin)

### `PAWSPOS/backend/routes/payments.doge.gw.routes.js`
- **Role:** Backend route
- **Size:** 3197 bytes
- **Overview:** backend/routes/payments.doge.gw.routes.js

### `PAWSPOS/backend/routes/payments.doge.routes.js`
- **Role:** Backend route
- **Size:** 2432 bytes
- **Overview:** backend/routes/payments.doge.routes.js

### `PAWSPOS/backend/routes/payments.routes.js`
- **Role:** Backend route
- **Size:** 6229 bytes
- **Overview:**  ===================== STRIPE TERMINAL =====================

### `PAWSPOS/backend/routes/payroll.routes.js`
- **Role:** Backend route
- **Size:** 616 bytes
- **Overview:** routes/payroll.routes.js

### `PAWSPOS/backend/routes/products.routes.js`
- **Role:** Backend route
- **Size:** 1185 bytes
- **Overview:** Read (any authenticated user: cashier/kiosk/kitchen/bar/manager/admin)

### `PAWSPOS/backend/routes/profiles.routes.js`
- **Role:** Backend route
- **Size:** 1086 bytes
- **Overview:** routes/profiles.routes.js

### `PAWSPOS/backend/routes/rates.routes.js`
- **Role:** Backend route
- **Size:** 422 bytes
- **Overview:** routes/rates.routes.js

### `PAWSPOS/backend/routes/reports.routes.js`
- **Role:** Backend route
- **Size:** 5828 bytes
- **Overview:** GET /api/reports/dashboard Supports:   ?range=7d|30d|90d   ?from=YYYY-MM-DD&to=YYYY-MM-DD

### `PAWSPOS/backend/routes/settings.routes.js`
- **Role:** Backend route
- **Size:** 225 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/routes/staff.routes.js`
- **Role:** Backend route
- **Size:** 729 bytes
- **Overview:** routes/staff.routes.js

### `PAWSPOS/backend/routes/time.routes.js`
- **Role:** Backend route
- **Size:** 354 bytes
- **Overview:** routes/time.routes.js

### `PAWSPOS/backend/routes/wallets.routes.js`
- **Role:** Backend route
- **Size:** 1478 bytes
- **Overview:** Create a POS wallet (assign a unique accountIndex per POS/user)

### `PAWSPOS/backend/routes/webhooks.coinbase.routes.js`
- **Role:** Backend route
- **Size:** 3816 bytes
- **Overview:** Coinbase Commerce webhook IMPORTANT: server.js mounts this BEFORE any JSON body parser so req.body is raw.

### `PAWSPOS/backend/routes/webhooks.coinremitter.routes.js`
- **Role:** Backend route
- **Size:** 3354 bytes
- **Overview:** ✅ Dev-friendly POST pre-handler: - Accepts empty/unknown content-type as 200 *only in non-production* (so Hookdeck “mock” works). - In production, enforces token up front even for pings.

### `PAWSPOS/backend/routes/webhooks.doge.routes.js`
- **Role:** Backend route
- **Size:** 1369 bytes
- **Overview:** routes/webhooks.doge.routes.js

### `PAWSPOS/backend/routes/webhooks.gigawallet.routes.js`
- **Role:** Backend route
- **Size:** 2241 bytes
- **Overview:** Webhook (JSON). Configure in GigaWallet to POST here.

### `PAWSPOS/backend/routes/webhooks.routes.js`
- **Role:** Backend route
- **Size:** 841 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/routes/webhooks.stripe.routes.js`
- **Role:** Backend route
- **Size:** 2286 bytes
- **Overview:** Stripe webhook IMPORTANT: server.js mounts this BEFORE any JSON body parser so req.body is raw.

### `PAWSPOS/backend/scripts/bootstrap-db.js`
- **Role:** Backend source file
- **Size:** 4024 bytes
- **Overview:** backend/scripts/bootstrap-db.js

### `PAWSPOS/backend/scripts/helpers/ensure-user.mjs`
- **Role:** Backend source file
- **Size:** 1895 bytes
- **Overview:** backend/scripts/helpers/ensure-user.mjs

### `PAWSPOS/backend/scripts/init-indexes.js`
- **Role:** Backend source file
- **Size:** 1375 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/scripts/migrations/20250812-add-emailNorm.mjs`
- **Role:** Backend source file
- **Size:** 530 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/scripts/peek-admin.js`
- **Role:** Backend source file
- **Size:** 809 bytes
- **Overview:** scripts/peek-admin.js (ESM)

### `PAWSPOS/backend/scripts/reset-admin.js`
- **Role:** Backend source file
- **Size:** 888 bytes
- **Overview:** scripts/reset-admin.mjs

### `PAWSPOS/backend/scripts/seed-admin.js`
- **Role:** Backend source file
- **Size:** 965 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/scripts/seed-modes-and-profiles.mjs`
- **Role:** Backend source file
- **Size:** 1540 bytes
- **Overview:** scripts/seed-modes-and-profiles.mjs

### `PAWSPOS/backend/scripts/seed.js`
- **Role:** Backend source file
- **Size:** 1926 bytes
- **Overview:**  noop

### `PAWSPOS/backend/scripts/update-payments-validator.mjs`
- **Role:** Backend source file
- **Size:** 1949 bytes
- **Overview:** scripts/update-payments-validator.mjs

### `PAWSPOS/backend/server.js`
- **Role:** Backend server entrypoint
- **Size:** 7840 bytes
- **Overview:** server.js

### `PAWSPOS/backend/services/coinbase.service.js`
- **Role:** Backend service
- **Size:** 1148 bytes
- **Overview:** Lazy init via REST to avoid import-time crashes. Set COINBASE_API_KEY in backend/.env to enable real calls. Without a key, this module loads fine; the endpoint will throw only if called.

### `PAWSPOS/backend/services/dogePrice.js`
- **Role:** Backend service
- **Size:** 2162 bytes
- **Overview:** services/dogePrice.js

### `PAWSPOS/backend/services/dogeWallet.service.js`
- **Role:** Backend service
- **Size:** 2596 bytes
- **Overview:** Create a POS wallet account (one per POS/user)

### `PAWSPOS/backend/services/dogeWatcher.js`
- **Role:** Backend service
- **Size:** 4820 bytes
- **Overview:** ENV knobs: DOGE_WATCHER_POLL_MS         default 5000 DOGE_WATCHER_MIN_CONF        default DOGE.MIN_CONFIRMATIONS (1) DOGE_WATCHER_WINDOW_TX       default 200  (how many recent tx we scan)

### `PAWSPOS/backend/services/orderNumber.js`
- **Role:** Backend service
- **Size:** 381 bytes
- **Overview:** Simple readable order numbers: ORD-YYYYMMDD-NNNNN

### `PAWSPOS/backend/services/rates.service.js`
- **Role:** Backend service
- **Size:** 269 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/services/stripe-service.js`
- **Role:** Backend service
- **Size:** 0 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/services/stripe.service.js`
- **Role:** Backend service
- **Size:** 519 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/services/tax.service.js`
- **Role:** Backend service
- **Size:** 104 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/services/tokenVault.service.js`
- **Role:** Backend service
- **Size:** 1231 bytes
- **Overview:** DO NOT use env secrets for real vaulting in prod. This is a dev placeholder.

### `PAWSPOS/backend/services/ws.service.js`
- **Role:** Backend service
- **Size:** 275 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/utils/asyncHandler.js`
- **Role:** Backend utility
- **Size:** 150 bytes
- **Overview:** Tiny helper to avoid try/catch noise

### `PAWSPOS/backend/utils/hashChain.js`
- **Role:** Backend utility
- **Size:** 172 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/backend/utils/logger.js`
- **Role:** Backend utility
- **Size:** 518 bytes
- **Overview:**  Minimal logger wrapper; easy to swap with Winston later

### `PAWSPOS/backend/utils/money.js`
- **Role:** Backend utility
- **Size:** 504 bytes
- **Overview:** Keep money as integer cents to avoid float rounding issues.

### `PAWSPOS/backend/utils/payrollMath.js`
- **Role:** Backend utility
- **Size:** 707 bytes
- **Overview:** utils/payrollMath.js

### `PAWSPOS/backend/validation/auth.validation.js`
- **Role:** Backend source file
- **Size:** 558 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/index.html`
- **Role:** Frontend source file
- **Size:** 253 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/package-lock.json`
- **Role:** Frontend source file
- **Size:** 150032 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/package.json`
- **Role:** Frontend source file
- **Size:** 852 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/App.jsx`
- **Role:** Frontend source file
- **Size:** 872 bytes
- **Overview:**  Private routes

### `PAWSPOS/frontend/src/api/client.js`
- **Role:** Frontend source file
- **Size:** 2261 bytes
- **Overview:** src/api/client.js

### `PAWSPOS/frontend/src/api/devices.js`
- **Role:** Frontend source file
- **Size:** 578 bytes
- **Overview:** GET /api/devices -> { devices: [...] }

### `PAWSPOS/frontend/src/api/profiles.js`
- **Role:** Frontend source file
- **Size:** 467 bytes
- **Overview:** Profiles API (read-only for now)

### `PAWSPOS/frontend/src/components/AnonymousOnly.jsx`
- **Role:** Frontend UI component
- **Size:** 488 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/DogeCheckout.tsx`
- **Role:** Frontend UI component
- **Size:** 6466 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/Handheld/HandheldOrderScreen.jsx`
- **Role:** Frontend UI component
- **Size:** 207 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/Kiosk/Bar/BarPosScreen.jsx`
- **Role:** Frontend UI component
- **Size:** 184 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/Kiosk/Kitchen/KitchenScreen.jsx`
- **Role:** Frontend UI component
- **Size:** 189 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/Kiosk/Restaurant/RestaurantPosScreen.jsx`
- **Role:** Frontend UI component
- **Size:** 197 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/MobilePOS/MobilePosScreen.jsx`
- **Role:** Frontend UI component
- **Size:** 181 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/POS/PosScreen.jsx`
- **Role:** Frontend UI component
- **Size:** 179 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/Protected.jsx`
- **Role:** Frontend UI component
- **Size:** 435 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/StatCard.jsx`
- **Role:** Frontend UI component
- **Size:** 377 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/Table.jsx`
- **Role:** Frontend UI component
- **Size:** 1229 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/TopNav.jsx`
- **Role:** Frontend UI component
- **Size:** 5640 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/components/topnav.css`
- **Role:** Frontend UI component
- **Size:** 3907 bytes
- **Overview:**  menu

### `PAWSPOS/frontend/src/context/AuthProvider.jsx`
- **Role:** Frontend source file
- **Size:** 1900 bytes
- **Overview:** Rehydrate from localStorage

### `PAWSPOS/frontend/src/hooks/useApi.js`
- **Role:** Frontend hook
- **Size:** 455 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/hooks/useStripeTerminal.js`
- **Role:** Frontend hook
- **Size:** 2759 bytes
- **Overview:** frontend/src/hooks/useStripeTerminal.js

### `PAWSPOS/frontend/src/layout/DashboardShell.jsx`
- **Role:** Frontend source file
- **Size:** 885 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/layout/Layout.jsx`
- **Role:** Frontend source file
- **Size:** 7203 bytes
- **Overview:** --- Menu model (add/remove items freely)

### `PAWSPOS/frontend/src/layout/Sidebar.jsx`
- **Role:** Frontend source file
- **Size:** 3238 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/layout/TopBar.jsx`
- **Role:** Frontend source file
- **Size:** 840 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/layout/TopNav.jsx`
- **Role:** Frontend source file
- **Size:** 4162 bytes
- **Overview:** close on route change

### `PAWSPOS/frontend/src/layout/topnav.css`
- **Role:** Frontend source file
- **Size:** 2057 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/main.jsx`
- **Role:** Frontend entrypoint
- **Size:** 590 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/Dashboard.jsx`
- **Role:** Frontend page/screen
- **Size:** 413 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/NotFound.jsx`
- **Role:** Frontend page/screen
- **Size:** 165 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/_Scaffold.jsx`
- **Role:** Frontend page/screen
- **Size:** 575 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/admin/Admin.jsx`
- **Role:** Frontend page/screen
- **Size:** 133 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/auth/Login.jsx`
- **Role:** Frontend page/screen
- **Size:** 2015 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/auth/Logout.jsx`
- **Role:** Frontend page/screen
- **Size:** 226 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/customers/Customers.jsx`
- **Role:** Frontend page/screen
- **Size:** 141 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/dashboard/Dashboard.jsx`
- **Role:** Frontend page/screen
- **Size:** 171 bytes
- **Overview:** Re-export your existing dashboard page so routes that import "./pages/Dashboard" continue to work.

### `PAWSPOS/frontend/src/pages/dashboard/Home.jsx`
- **Role:** Frontend page/screen
- **Size:** 4831 bytes
- **Overview:**  KPIs

### `PAWSPOS/frontend/src/pages/dashboard/dashboard.css`
- **Role:** Frontend page/screen
- **Size:** 2892 bytes
- **Overview:**  payment type chart

### `PAWSPOS/frontend/src/pages/devices/Devices.jsx`
- **Role:** Frontend page/screen
- **Size:** 4950 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/items/Categories.jsx`
- **Role:** Frontend page/screen
- **Size:** 141 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/items/InventoryOverview.jsx`
- **Role:** Frontend page/screen
- **Size:** 4297 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/items/ItemLibrary.jsx`
- **Role:** Frontend page/screen
- **Size:** 4046 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/items/Modifiers.jsx`
- **Role:** Frontend page/screen
- **Size:** 139 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/orders/Orders.jsx`
- **Role:** Frontend page/screen
- **Size:** 2394 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/payments/CryptoPay.jsx`
- **Role:** Frontend page/screen
- **Size:** 1351 bytes
- **Overview:** frontend/src/pages/payments/CryptoPay.jsx

### `PAWSPOS/frontend/src/pages/payments/Overview.jsx`
- **Role:** Frontend page/screen
- **Size:** 2151 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/payments/VirtualTerminal.jsx`
- **Role:** Frontend page/screen
- **Size:** 859 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/pos/BarDisplay.jsx`
- **Role:** Frontend page/screen
- **Size:** 144 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/pos/Kiosk.jsx`
- **Role:** Frontend page/screen
- **Size:** 158 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/pos/KitchenDisplay.jsx`
- **Role:** Frontend page/screen
- **Size:** 152 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/pos/ModifierDialog.jsx`
- **Role:** Frontend page/screen
- **Size:** 3718 bytes
- **Overview:** props:  open, onClose(), modifierSets: [{ _id,name,displayName,selection:{required,min,max}, options:[{name,price,inStock}] }]  onConfirm(mods) -> mods = [{ setId,setName,options:[{name,price}] }]

### `PAWSPOS/frontend/src/pages/pos/POSModeRouter.jsx`
- **Role:** Frontend page/screen
- **Size:** 543 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/pos/StandardPOS.jsx`
- **Role:** Frontend page/screen
- **Size:** 9623 bytes
- **Overview:** For modifiers

### `PAWSPOS/frontend/src/pages/pricing/Discounts.jsx`
- **Role:** Frontend page/screen
- **Size:** 145 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/profiles/Profiles.jsx`
- **Role:** Frontend page/screen
- **Size:** 3366 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/reports/PaymentMethods.jsx`
- **Role:** Frontend page/screen
- **Size:** 150 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/reports/Reports.jsx`
- **Role:** Frontend page/screen
- **Size:** 137 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/reports/SalesSummary.jsx`
- **Role:** Frontend page/screen
- **Size:** 486 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/reports/_SalesGauge.jsx`
- **Role:** Frontend page/screen
- **Size:** 939 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/settings/General.jsx`
- **Role:** Frontend page/screen
- **Size:** 635 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/pages/terminal/Crypto.jsx`
- **Role:** Frontend page/screen
- **Size:** 1519 bytes
- **Overview:** frontend/src/pages/terminal/Crypto.jsx

### `PAWSPOS/frontend/src/pages/terminal/Terminal.jsx`
- **Role:** Frontend page/screen
- **Size:** 3578 bytes
- **Overview:** frontend/src/pages/terminal/Terminal.jsx

### `PAWSPOS/frontend/src/pos/checkout.js`
- **Role:** POS UI logic
- **Size:** 4000 bytes
- **Overview:** src/pos/checkout.js

### `PAWSPOS/frontend/src/router.jsx`
- **Role:** Frontend source file
- **Size:** 2252 bytes
- **Overview:** Real pages

### `PAWSPOS/frontend/src/services/api.js`
- **Role:** Frontend source file
- **Size:** 293 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/shared/dashboard/CategoriesCard.jsx`
- **Role:** Frontend source file
- **Size:** 448 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/shared/dashboard/CustomersCard.jsx`
- **Role:** Frontend source file
- **Size:** 1307 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/shared/dashboard/ItemsCard.jsx`
- **Role:** Frontend source file
- **Size:** 435 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/shared/dashboard/KPIs.jsx`
- **Role:** Frontend source file
- **Size:** 1055 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/shared/dashboard/PaymentTypeChart.jsx`
- **Role:** Frontend source file
- **Size:** 4081 bytes
- **Overview:**  Crypto row

### `PAWSPOS/frontend/src/shared/dashboard/SetupChecklist.jsx`
- **Role:** Frontend source file
- **Size:** 721 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/shared/dashboard/widgets.css`
- **Role:** Frontend source file
- **Size:** 792 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/shared/useDashboardData.js`
- **Role:** Frontend source file
- **Size:** 1647 bytes
- **Overview:** src/shared/useDashboardData.js

### `PAWSPOS/frontend/src/shared/useDashboardData.jsx`
- **Role:** Frontend source file
- **Size:** 1484 bytes
- **Overview:** Public (exported) fallback so it can be reused in tests/other views

### `PAWSPOS/frontend/src/theme/index.js`
- **Role:** Frontend source file
- **Size:** 313 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/theme/presets.js`
- **Role:** Frontend source file
- **Size:** 328 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/utils/ledger.js`
- **Role:** Frontend utility
- **Size:** 1026 bytes
- **Overview:** backend/utils/ledger.js

### `PAWSPOS/frontend/src/utils/money.js`
- **Role:** Frontend utility
- **Size:** 191 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/src/validation/loginSchema.js`
- **Role:** Frontend source file
- **Size:** 493 bytes
- **Overview:** No header comment detected; description inferred by path/name.

### `PAWSPOS/frontend/vite.config.js`
- **Role:** Frontend source file
- **Size:** 157 bytes
- **Overview:** No header comment detected; description inferred by path/name.


---

## How to Regenerate This Handbook
1. Zip the source (without `node_modules/`).
2. Upload the ZIP and re-run the extraction + doc generation script.

