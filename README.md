ios-gradle-swift-template [![Status](https://travis-ci.org/jaredsburrows/ios-gradle-swift-template.svg?branch=master)](https://travis-ci.org/jaredsburrows/ios-gradle-swift-template) [![Coverage Status](https://coveralls.io/repos/jaredsburrows/ios-gradle-swift-template/badge.svg?branch=master)](https://coveralls.io/r/jaredsburrows/ios-gradle-swift-template?branch=master)
=========
Gradle + Xcode + XCTest + Gcovr

## Technologies used:
#### Build Tools:
|Name|Description|
|---|---|
| [Gradle](http://gradle.org/docs/current/release-notes) | Gradle build system |
| [Xcode](https://developer.apple.com/xcode/) | Xcode IDE |

####Testing Frameworks:
|Name|Description|
|---|---|
| [XCTest](https://developer.apple.com/library/ios/documentation/DeveloperTools/Conceptual/testing_with_xcode/chapters/04-writing_tests.html#//apple_ref/doc/uid/TP40014132-CH4-SW1) | XCTests Unit Testing Framework |
| [Gcovr](http://gcovr.com/) | GNU gcov utility |

####Reporting Plugins:
|Name|Description|
|---|---|
| [cpp-coveralls](https://github.com/eddyxu/cpp-coveralls) | C/C++ coverage report to coveralls.io |

####Continuous Integration:
|Name|Description|
|---|---|
| [TravisCI](http://docs.travis-ci.com/user/languages/android/) | Build Server(Builds, Tests, Publishes reports to Coveralls)

## Comand Line(Advanced):
##### Clone with `Git`:
 - `git clone https://github.com/jaredsburrows/ios-gradle-swift-template.git`
 - `cd ios-gradle-swift-template`

##### Building with `Gradle`:
 - **Asssembles the project:**
   - `gradlew assemble`
 - **Assemble and run tests:**
   - `gradlew build` 

##### Running tests with `Gradle`:
 - **Run all tests:**
   - `gradlew test`
   
##### Running coverage with `Gradle`:
 - **Run all [gcovr](http://gcovr.com/) code coverage:**
   - `gradlew coverage`

## Maps folders to local file system):

This project uses [`synx`](https://github.com/venmo/synx):

    sudo gem install cocoapods
    gem install synx

License
=========

    Copyright (C) 2016 ios-gradle-swift-template by Jared Burrows

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
