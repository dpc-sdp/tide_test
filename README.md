# tide_test
Test content type for Tide distribution

[![CircleCI](https://circleci.com/gh/dpc-sdp/tide_test.svg?style=svg&circle-token=2395a9f5b7b4212a37c28b26c6a63e007c26d59d)](https://circleci.com/gh/dpc-sdp/tide_test)

# CONTENTS OF THIS FILE

* Introduction
* Requirements
* Recommended Modules
* Installation

# INTRODUCTION
The Tide Test module provides the Test content type and related configurations.
This module is essentially used in behat tests.
You should not need to install this module on its own, the modules having behat tests based on
"Test" content type should define tide_test as a dependency.

# REQUIREMENTS
* [Tide Core](https://github.com/dpc-sdp/tide_core)


# INSTALLATION
Include the Tide Test module in your composer.json file
```bash
composer require dpc-sdp/tide_test
```

# PURPOSE
- test content type
- other test functionality

# Attribution
Single Digital Presence offers government agencies an open and flexible toolkit to build websites quickly and cost-effectively.
<p align="center"><a href="https://www.vic.gov.au/what-single-digital-presence-offers" target="_blank"><img src="docs/SDP_Logo_VicGov_RGB.jpg" alt="SDP logo" height="150"></a></p>

The Department of Premier and Cabinet partnered with Salsa Digital to deliver Single Digital Presence. As long-term supporters of open government approaches, they were integral to the establishment of SDP as an open source platform.
<p align="center"><a href="https://salsadigital.com.au/" target="_blank"><img src="docs/Salsa.png" alt="Salsa logo" height="150"></a></p>

