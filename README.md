
# Webtrees Custom Module: Facts and Events

This [webtrees](https://www.webtrees.net/) custom module provides an extended 'Facts and Events' tab, with hooks for other custom modules.
The project’s website is [cissee.de](https://cissee.de).

## Contents

* [Features](#features)
* [Download](#download)
* [Installation](#installation)
* [License](#license)

### Features<a name="features"/>

Mainly intended as a base for other custom modules. Some features are available independently:

* Fixes [Webtrees issue #1192](https://github.com/fisharebest/webtrees/issues/1192). When 'Events of close relatives' are activated, the inverse associations and relationships are also displayed:

![FactsAndEventsExt1](FactsAndEventsExt1.PNG)
* Links to external maps (Google, Bing, OpenStreetMap) are configurable via module administration.

### Download<a name="download"/>

* Current version: 1.7.9.5
* Based on and tested with webtrees 1.7.9, may also work with older 1.7.x versions.
* Requires the Hooks module ('hooks_repackaged', or the original Hooks module via webtrees-geneajaubart).
* Download the zipped module, including all required dependencies, [here](https://cissee.de/facts_and_events/facts_and_events.1.7.9.5.zip).
* Support, suggestions, feature requests: <ric@richard-cissee.de>
* Issues also via <https://github.com/ric2016/personal_facts_with_hooks/issues>

### Installation<a name="installation"/>

* Unzip the files and copy them to the modules_v3 folder of your webtrees installation. All required modules are included in the zip file. It's safe to overwrite the respective directories if they already exist (they are bundled with other custom modules as well), as long as other custom models using these dependencies are also upgraded to their respective latest versions.
* Enable the extended 'Facts and Events' module via Control Panel -> Modules -> Module Administration -> Facts and Events.
* Enable the Hooks module via Control Panel -> Modules -> Module Administration -> Hooks. Make sure all hooks are selected (in the preferences of the Hooks module).				
* Configure the visibility of the old and the extended 'Facts and Events' tab via Control Panel -> Modules -> Tabs (they both appear as 'Facts and Events' here - usually, you'll want to use only one of them. You may just disable the old 'Facts and Events' module altogether).

### License<a name="license"/>

* **personal_facts_with_hooks: a webtrees custom module**
* Copyright (C) 2016 to 2017 Richard Cissée
* Derived from **webtrees** - Copyright (C) 2010 to 2016  webtrees development team.
* Derived from **webtrees-geneajaubart** - Copyright (C) 2009 to 2016  Jonathan Jaubart.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.