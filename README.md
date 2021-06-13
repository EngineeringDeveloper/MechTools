MechTools ChangeLog

V1.4.0

-- *** NEW Features *** --

- Added a Home screen
	* This can be accessed at any time with CTRL + H
	
- Web Material Searching
	* searches a curated list for material properties
	** There is  an existing bug where the GUI freezes while the search occurs **

- Datafiles can now be pointed to any location
	* example -- a network location for all users to access
	
- Guidance for the type of fit between hole and shaft
- Added standard tolerances for tolerance stacking
	* ISO 2768 -- linear tolerances
	* ISO 8062 -- casting tolerances
- Improved installer experience and branding
- Installer now downloads asynchronously in the background
- Prettier tables where they are used, better and more consistent formatting
- Created "tools Updater" a standalone binary for installing MechTools

-- *** Bug fixes *** ---
- Iso fits copy button now copies, did not function before
- Friction requirement on fastener quantity started off as N not KN
- Made Settings file Parsing more robust to prevent some crashes


-- *** Back end improvements *** --
- added some standard tests for builds
- Removed installed files that were not required
- Refactored some parsing sections of code to reuse functions and be more self compatible and fail safe
- refactored some sections of code to be less verbose


Available features:

Calculation
- Thread Stress
- Fastener Elongation
- Fastener Quantity
- Hole and Shaft fits
- ISO268-2 Interference & fit type

Analysis
- Tolerance Stacking - With ISO2768 tolerances
- Key Frequencies