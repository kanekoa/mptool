mptool
======

command line tool for .mobileprovision file

## features

### install

```
$ mptool install /path/to/yourapp.mobileprovision
installed to /Users/you/Library/MobileDevice/Provisioning Profiles/XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX.mobileprovision
```
### read

```
$ mptool read --key UUID /path/to/yourapp.mobileprovision
XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX
```

### dump

```
$ mptool dump /path/to/yourapp.mobileprovision
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>AppIDName</key>
	....
</dict>
</plist>
```

## license

Copyright (C) 2013 kanekoa All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
