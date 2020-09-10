Qload
=======

_Checking Son of Grid Engine queue loads_

Lists the different queues, users and their number of jobs and
reserved CPUs and GPUs. It parses the output of the `qstat` command
to make it more readable.

The script is now only configured for [my workplace](http://ufal.cz).
This means that the qstat command may need to be adapted to work
in a different environment. Let me know if you want to add your own
local settings.


Usage
-----

Requires Python 3. You can install the script using `pip`:
```
pip3 install git+https://github.com/tuetschek/qload
```

Run the script to see the current cluster load:
```
qload
```


License
-------

Copyright (c) 2020 Ondřej Dušek

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
