# Changelog for CashWay PrestaShop module

## 9 avril - 0.3.0, dev version

 * removed root {validation,payment}.php out-of-sync
   endpoints (and deprecated since PS 1.5, so breaks
   pre 1.5 compatibility)
 * style fixes

## 8 avril - 0.2.0, dev version

 * fix points highlighted by code audit
 * move status update cron into new front controller
 * manage API failures better
 * JS map is now loaded from remote

## 31 mars - 0.1.1, dev version

 * fix install process

## 18 mars - 0.1.0, dev version

 * added cron task: check local orders pending payment,
   check transactions status by CashWay service,
   compare, update.


## 12 mars 2015 - 0.0.1, dev version

 * [+] MO : new CashWay module with basic functionality:
   - installs itself with basic config.
   - creates a new transaction on payment method confirmation.
