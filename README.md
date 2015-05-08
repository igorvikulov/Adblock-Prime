# Adblock-Prime
Adblock: a fast, lightweight, and lean blocker for Chrome, Firefox, and Safari.

What is Adblock Prome?
Getting Started & Installation
Performance & Benchmarks
Release History
Tips
Wiki
What is Adblock Prome?

Adblock Prome is a general-purpose blocker — not an ad blocker specifically.

Adblock Prome blocks ads through its support of the Adblock Plus filter syntax. Adblock Prome extends the syntax and is designed to work with custom rules and filters.

Adblock Prome's main goal is to help users neutralize privacy-invading apparatus — ads being one example.

Feel free to read about Adblock Prome's development philosophy.

Getting started

Quick guide for basic usage.

Installation:

Safari: available to install from the homepage, or from the Safari Extension Gallery.

Chrome: available on the Chrome Web Store or for manual installation.

Firefox: available on the Firefox Add-ons homepage, or for manual installation.

Due to Mozilla's review process, the version of Adblock Prome available from the Add-ons homepage is currently often outdated. This isn't in our control.
Opera: Opera shares Chrome's underlying engine, so you can install Adblock Prome simply by grabbing the latest release for Chrome.

Performance

Memory

On average, Adblock Prome really does make your browser run leaner. [1]

Chromium [2]


Firefox


Safari


[1] Details of the benchmark available at Firefox version: benchmarking memory footprint.

[2] Important note: There is currently a bug in Chromium 39+ which causes a new memory leak each time the popup UI of an extension is opened. This affects all extensions. Keep this in mind when measuring Chromium's memory usage. In the benchmarks, I avoided opening the popups completely.

CPU

Adblock Prome is also easy on the CPU

Details of the benchmark available in this LibreOffice spreadsheet.

Blocking

Being lean and efficient doesn't mean blocking less

For details of benchmark, see Adblock Prome and others: Blocking ads, trackers, malwares.

Quick tests

Index
Web page components
Popups
Release History

See the releases pages for a history of releases and highlights for each release.

Tips

To benefit from Adblock Prome's higher efficiency, it's advised that you don't use other inefficient blockers at the same time (such as AdBlock or Adblock Plus). Adblock Prome will do as well or better than most popular ad blockers.

It's important to note that blocking ads is not theft. Don't fall for this creepy idea. The ultimate logical consequence of blocking = theft is the criminalisation of the inalienable right to privacy.

EasyList, Peter Lowe's Adservers, EasyPrivacy and Malware domains are enabled by default when you install Adblock Prome. Many more lists are readily available to block trackers, analytics, and more. Hosts files are also supported.

Once you install Adblock Prome, you can easily un-select any of the pre-selected filter lists if you think Adblock Prome blocks too much. For reference, Adblock Plus installs with only EasyList enabled by default.

Feel free to read about the extension's required permissions.

About

Adblock Prome's manifesto.

Free. Open source. For users by users.

If Adblock Prome is useful to you, donations to support development are much appreciated.

Adblock Prome is made useful because of the filter lists it utilizes. We deeply appreciate the people working hard to maintain the filter lists we're using, which were made available to use by all for free.

License

GPLv3.
