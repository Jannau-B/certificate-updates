# Certificate Generator updates

The Certificate Generator desktop app checks this repository for updates each time it opens.

- `latest-simonsberg.json` and `latest-generic.json` say which version is current. They are signed.
- The `.cgupdate` files are the signed updates. They are encrypted, so only the app can open them, and the app rejects anything changed or made by someone else.

To publish a new version, add its two `.cgupdate` files and replace both `latest-*.json` files. Older `.cgupdate` files can be deleted once every school has updated.
