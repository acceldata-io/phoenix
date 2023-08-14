
<!---
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
-->
# PHOENIX  thirdparty-2.0.0 Release Notes

These release notes cover new developer and user-facing incompatibilities, important issues, features, and major improvements.


---

* [PHOENIX-6575](https://issues.apache.org/jira/browse/PHOENIX-6575) | *Major* | **Replace patched commons-cli with original one when a release with CLI-254 is available**

Phoenix-thirdparty now uses unmodified (apart from the relocation) upstream commons-cli 1.5.0.
commons-cli 1.5.0 includes the fix for CLI-254, bu the API to activate it is different than the patched version included in phoenix-thirdparty 1.1.0.
Hence phoenix-thirdparty is 2.0 NOT API compatible with phoenix-thirdparty 1.1.0


---

* [PHOENIX-6641](https://issues.apache.org/jira/browse/PHOENIX-6641) | *Major* | **Bump Guava to 31.0.1 in phoenix-thirdparty**

Phoenix-thirdparty now includes Guava 31.0.1.



# PHOENIX  thirdparty-1.1.0 Release Notes

These release notes cover new developer and user-facing incompatibilities, important issues, features, and major improvements.


---

* [PHOENIX-6349](https://issues.apache.org/jira/browse/PHOENIX-6349) | *Major* | **Add and use commons-cli to phoenix-thirdparty**

Added phoenix-shaded-commons-cli to phoenix-thirdparty.
This helps avoid classpath conflicts and includes a patch on top of commons-cli 1.4.0 that fixes CLI-254.


# PHOENIX  thirdparty-1.0.0 Release Notes

These release notes cover new developer and user-facing incompatibilities, important issues, features, and major improvements.



