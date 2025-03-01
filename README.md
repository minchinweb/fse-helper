Helper for FSEconomy
====================

Ideas
-----

- download data, and cache the raw xml to disk; re-read the XML to generate the
  results pages
- list of aircraft, showing correspondence between FSE and MSFS (including
  payware)
    - different liveries may not match (from MSFS), as each livery reports a
      different name to FSE
    - note 30 min and 1 hour range, fuel used, cargo capacity (in pax)
    - show (approximate) cost for ownership (per hour)
    - show last rental price range
    - show count (system and privately owner, amount for rent)
- find rentable aircraft
    - given an aircraft, show a list of those available to rent, sort by price
    - include approximate conversion between dry and wet rentals (to know which
      way to rent it)
        - use a global gas price as default, but then use local price
    - show CDF graph, along with average price. Also have 10, 25, 50, 75, and
      90 percentiles
    - display ownership cost
    - filter broken, un-filter user fixable
- FBO
    - networks
        - show FBO's showing the same owner/operator name
    - for sale
        - highlight ones that come on cheap
    - lottery
        - highlight FBO's on lottery without other ticket purchases, along with
          countdown to lottery closure
- calculations
    - breakeven on owning a plane
    - breakeven on owning a pair of FBO's and flying between them
