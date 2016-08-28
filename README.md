# ESC/POS printer database

This is a community-maintained database of thermal receipt printer capabilities.

The capability data is shared by multiple open source receipt printing projects,
to allow improvements in hardware support, compatibility and localization.

Only features of ESC/POS printers are tracked at this stage. If you have a ZPL,
DPL, or ESC/P printer, it is not in-scope for being listed in this databse.

## Browse

TBD

## Contribute

This project is open to any kind of contribution.

- Submitting information about your printer
- Writing new profiles
- Typing up legacy code pages

### Write a profile

All data is in YAML format. If you are comfortable, please copy an existing
profile for a similar printer, fill out the details based on test prints,
bug reports and tea leaves, then submit a pull request.

### Submit a test page

If your printer is not listed, or has an incomplete profile, it may be because
nobody with a similar printer has contributed to this project yet.

To get your printer included in the database, try to find out some technical
info about what it supports, and post a new ussue with what you find out.

Minimum info is:

- Vendor name and model number
- Link to a vendor programming guide that lists supported features
- Paper width

If you don't have docs, try to find out what your printer supports by submitting:

- Test page output listing supported character encodings
- An indication of which features work on your printer.

For testing out features, the [escpos-php](https://github.com/mike42/escpos-php/tree/master/test/integration/resources/output) test outputs are suitable. 

## License

TBD

## Affiliated projects

TBD
