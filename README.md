# iOS Core NFC Scanner

## Descritpion
- A demo of NFC scanner app that stores catalog of product locally uniquely by ID. 
- NFC Scanning session scans the NFC Tag containing the URI appended by id as the second path.
- After retrieving the id from the tag, it then search the product inside the local store using the ID.
- If found, the product detail is presented to the user.

## Usage
- Clone the project, run with Xcode 10.1
- Follow the tutorial on https://medium.com/@alfianlosari/building-nfc-product-scanner-ios-app-with-corenfc-alfian-losari-5da0365bcde5
- If you want to use background scan, provide your own app link domain and host the apple associated file there.
- Provide your own NFC tag, and write the URL with format https://YourApplinkDomain.com/YourSkuID
