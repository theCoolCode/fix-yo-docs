# Komga-Cover-Extractor
A python automation script that detects and extracts the cover from your cbz and epub files for each individal volume. 
Then takes the cover from the first volume and copies that as a cover file for your overall collection.

Allowing the user to use local higher-resolution covers within Komga instead of the compressed versions that Komga generates.

Primary usage is with https://github.com/gotson/komga

## Cover Detection
Cover-string detection is based on various scene releases, if none are detected, it will default to the first image. Which, unless you have scans from online, will almost always be the cover.

## Usage
Add desired paths that you want scanned into the string array at the top of komga-cover-extractor.py
Run komga-cover-extractor.py

## Contact
Discord: HCAZ#0665
