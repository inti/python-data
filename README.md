Description
===========

Install python packages for data analysis.
Full list of packages can be found on the recipes/default.rb file but it includes

* IPython
* Pandas
* numpy
* scipy
* matplotib
* scikit-learn
* statsmodels and patsy
* pymc

All pachages will be installed with pip install pkg --upgrade so the latest version will be available.



Requirements
============

Chef 0.10.10+.

Platform
--------

* Ubuntu

Tested on:

* Ubuntu 12.04

Cookbooks
---------

Requires Opscode's apt cookbook.
Requires Opscode's python cookbook for pip to install packages. 

License and Author
==================

- Current version by Inti Pedroso
- Original Author:: Becky Sweger and its license

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
