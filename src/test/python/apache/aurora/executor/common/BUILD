#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

python_tests(
  name = 'common',
  sources = globs('*.py'),
  dependencies = [
    '3rdparty/python:mesos.interface',
    '3rdparty/python:mock',
    '3rdparty/python:twitter.common.contextutil',
    '3rdparty/python:twitter.common.dirutil',
    '3rdparty/python:twitter.common.quantity',
    '3rdparty/python:twitter.common.testing',
    'api/src/main/thrift/org/apache/aurora/gen',
    'src/main/python/apache/aurora/common',
    'src/main/python/apache/aurora/config',
    'src/main/python/apache/aurora/executor',
    'src/main/python/apache/thermos/config',
    'src/main/python/apache/thermos/core',
    'src/main/python/apache/thermos/monitoring',
  ]
)
