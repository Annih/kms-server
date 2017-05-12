# kms-server Cookbook
[![Build Status][build_status]][build_status]

Install and configure the Microsoft KMS server role.

## Requirements

This cookbook supports and requires Chef 12.6+.

### Platforms

* Windows Server 2012R2
* Windows Server 2016

### Cookbooks

The following cookbook is required as noted:

* [windows](windows_cookbook) (> 1.36.1) to leverage the `windows_feature` resource

## Contributing

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

## License and Authors

* Authors [Baptiste Courtois][annih] (<b.courtois@criteo.com>)

```text
Copyright 2017 Baptiste Courtois

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
[annih]:            https://github.com/Annih
[repository]:       https://github.com/Annih/kms-server
[build_status]:     https://api.travis-ci.org/Annih/kms-server.svg?branch=master
