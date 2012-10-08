This is a fork of https://github.com/tow/sunburnt with the group_by (https://github.com/Spantree/sunburnt) and currency (https://github.com/ikanobori/sunburnt) patches.
It also contains some patches:
- The currency field by ikanobori, originally didn't properly handle sorting for currency range-queries.
- The original branch from tow, improperly sent a float for the commitWithin parameter to add when Solr expected an int.

WIP:
- Support for query filter functions such as "bbox".
