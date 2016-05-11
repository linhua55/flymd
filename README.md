# FLYMD

On the fly markdown preview.

### Requirements

- A computer
- Emacs
- A modern browser

### Demostration

Coming soon...

### Features

- Esay to use
- Auto scroll
- GFM compatible
- Online image render
- GFMize
- No external dependency (unless the browser is counted)

### Setup

``` emacs-lisp
(require 'flymd)

;; If you use firefox as your default browser, no extra setting.
;; If you use google chrome as your default browser, add this:
(setq flymd-browser-open-arg "--allow-file-access-from-files")

;; I did not try other browsers, please report if any errors occur.
```

### Usage

# `flymd-flyit`

**One and only one** interactive function in this package.

<kbd>M-x</kbd> `flymd-flyit`, current markdown buffer opened in a browser.

If you close the page accidentally, <kbd>M-x</kbd> `flymd-flyit` to reopen the page.

### Browser button

- Auto Scroll -------- Toggle auto scroll.
- Auto Refresh ----- Toggle auto refresh.
- GFM Mode ------- Toggle GFM mode.

  Render the page in GFM style (autolink, table and tasklist) if enabled.

- GFMize ------------ Render the page by github API

  Codeblock should be correctly highlight after action.

  Notice that github API allows only 60 accesses per hour.

## Contacts

mola@molamola.xyz

If you find any bugs or have any suggestions, you can make a pull request, report an issue or send me an email.

## Support

[![paypal](image/buy_me_a_beer.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AG4M5N3TZQ2DJ)    [![paypal](image/buy_me_a_bear.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AZ8SZKK4MZQQE)

## License

* Copyright (C) 2015-2016 Mola-T
* Author: Mola-T <Mola@molamola.xyz>
* URL: https://github.com/mola-T/flymd
* [GNU GENERAL PUBLIC LICENSE](LICENSE)