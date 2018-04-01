## MaskPass

**MaskPass** is a standalone mnemonic password generator that runs solely within your browser using Javascript, nothing generated or typed ever leaves your screen.

The use case for **MaskPass** is similar to that of *Lastpass*-like services in which you use a single password or passphrase to generate all your other passwords.  The difference with **MaskPass** is that you're expected to remember your passwords using mnemonics instead of relying on a service, thus never having to trust a third party with your credentials.

The passwords generated are designed to be memorable, but if you forget one you can simply type your master passphrase in again to find it.

The page (*index.htm*) can be "*saved as*" a portable single html file that can be executed locally without ever needing to return to the site (**maskpass.com**) again.

## Validation

There is a checksum of the Javascript code generated and displayed at the bottom of the page.  This checksum can be compared against the *script.sum* file in this repository to ensure it's up to date and/or hasn't been tampered with.
