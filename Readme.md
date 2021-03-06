# CashWay PrestaShop module

## Installation

Still in development. DO NOT INSTALL OR USE unless you know what you're doing.

### Cron job

Please call `modules/cashway/cron_cashway_check_for_transactions.php`
at most every 30 minutes, ideally, every hour.

You may use PrestaShop Cron Task Manager module for this
or your own scheduling system.

### Dependencies

This module depends on APIs provided by [CashWay](https://www.cashway.fr/):

 * api.cashway.fr
 * maps.cashway.fr


## Contributing

Issues, PR and ideas are welcome.

You may get in touch here through issues or on #cashway_fr Freenode IRC.


## Licenses

 * the PrestaShop-specific code of this module is licensed under the
   Academic Free License 3.
 * CashWay API wrapper code is licensed under the
   [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
   (`lib/cashway/cashway_lib.php`, `views/js/cashway_map.js`)

### Apache License

    Copyright 2015 Epayment Solution - CashWay

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
