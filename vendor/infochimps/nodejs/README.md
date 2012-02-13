# nodejs chef cookbook

Installs/Configures nodejs

* Cookbook source:   [http://github.com/infochimps-cookbooks/nodejs](http://github.com/infochimps-cookbooks/nodejs)
* ClusterChef tools: [http://github.com/infochimps/cluster_chef](http://github.com/infochimps/cluster_chef)
* Homebase (shows cookbook in use): [http://github.com/infochimps-labs/cluster_chef-homebase](http://github.com/infochimps-labs/cluster_chef-homebase)

## Overview

Installs/Configures nodejs

## Recipes 

* `compile`                  - Compile
* `default`                  - Base configuration for nodejs

## Integration

Supports platforms: debian and ubuntu

Cookbook dependencies:

* python


## Attributes

* `[:nodejs][:git_repo]`              -  (default: "https://github.com/joyent/node.git")
* `[:nodejs][:jobs]`                  -  (default: "2")
* `[:nodejs][:install_dir]`           -  (default: "/usr/src/nodejs")
* `[:nodejs][:bin_path]`              -  (default: "/usr/local/bin/node")

## License and Author

Author::                Nathaniel Eliot - Infochimps, Inc (<coders@infochimps.com>)
Copyright::             2011, Nathaniel Eliot - Infochimps, Inc

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

> readme generated by [cluster_chef](http://github.com/infochimps/cluster_chef)'s cookbook_munger