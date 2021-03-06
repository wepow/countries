# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).


## 1.0.0
- Switch to Marshalling for cache storage @rposborne
- Country class helper now must be explicitly loaded @rposborne
- Removed Rails 2.0 FormHelper COUNTRIES @rposborne
- Add class codes method to get list of all alpha2 codes @rposborne
- Change default behavior of all method to return a list of country objects vs a tuple of alpha code + name

## 0.11.5
- Refactored data loading into it's own class
- Added ability to override bad translations from i18n
- Update languages in NO.yml @matfiz
- Fix Subdivisions & States in README @pnomolos
- Fix New York, Washington, Oklahoma state's latitude/longitude information @GUI
- Bad state data present in Uruguay has been removed @saisha92
- Various Other Content Updates by @danshultz @embs @sykaeh, @tg0

## 0.11.4
- Added coordinates for subdivisions @fabn
- Various Other Content Updates by @fabn, @snowblink

## 0.11.3
- Translations update from i18n-data

## 0.11.2
- silence ruby warnings @franckverrot
- add find_country_by_translated_name @rposborne NOTE: this is garbage for the
  time being, some translations have duplicates in them and causes false results

## 0.11.1
- added bounding box coordinates for VI, CW, PR, AS, and GU : @marinom
- revert Lookup country by translated name via find_by_name @rposborne

## [0.11.0] - 2015-03-03
### Changed
- Cached Translations in gem to translation lookup speed @rposborne, @stayhero
- Upgrade test suite to rspec 3 @rposborne
- Added region_short for postal codes @stayhero
- Content Updates @masolino, @rosetree, @stayhero, @skarlcf, @cllns, @speric, @rposborne
- Adding Lat/Lng to countries @jabawack81
- Readme Updates @cllns
