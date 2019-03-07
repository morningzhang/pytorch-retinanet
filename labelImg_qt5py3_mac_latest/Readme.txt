1. Remove the lsquarantine attribute：
xattr -d com.apple.quarantine  ./labelImg.app
(http://krypted.com/mac-security/app-translocation-services-os-x-10-12/)

2. Change the "predefined_classes.txt" within "labelImg.app/Contents/MacOS/data".
